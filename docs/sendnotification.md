SendNotification



[MQL5 Reference](index.md)  /  [Network Functions](network.md) / SendNotification

[![Previous](previous.png)](sendmail.md) 
[![Next](next.png)](globals.md)

SendNotification

Sends push notifications to the mobile terminals, whose MetaQuotes IDs are specified in the "Notifications" tab.

```
bool  SendNotification(
   string  text          // Text of the notification
   );
```

Parameters

text

[in]   The text of the notification. The message length should not exceed 255 characters.

Return Value

true if a notification has been successfully sent from the terminal; in case of failure returns false. When checking after a failed push of notification, [GetLastError ()](getlasterror.md) may return one of the following errors:

* 4515 ERR\_NOTIFICATION\_SEND\_FAILED,
* 4516 ERR\_NOTIFICATION\_WRONG\_PARAMETER,
* 4517 ERR\_NOTIFICATION\_WRONG\_SETTINGS,
* 4518 ERR\_NOTIFICATION\_TOO\_FREQUENT.

Note

Strict use restrictions are set for the SendNotification() function: no more than 2 calls per second and not more than 10 calls per minute. Monitoring the frequency of use is dynamic. The function can be disabled in case of the restriction violation.

SendNotification() function does not work in the [Strategy Tester](testing.md#alert_etc).

Example:

```
//+------------------------------------------------------------------+
//|                                             SendNotification.mq5 |
//|                                  Copyright 2024, MetaQuotes Ltd. |
//|                                             https://www.mql5.com |
//+------------------------------------------------------------------+
#property copyright "Copyright 2024, MetaQuotes Ltd."
#property link      "https://www.mql5.com
#property version     "1.00"
 
#define   MESSAGE   "Test Message"
//+------------------------------------------------------------------+
//| Script program start function                                    |
//+------------------------------------------------------------------+
void OnStart(void)
  {
//--- check permission to send notifications in the terminal
   if(!TerminalInfoInteger(TERMINAL_NOTIFICATIONS_ENABLED))
     {
      Print("Error. The client terminal does not have permission to send notifications");
      return;
     }
//--- send notification
   ResetLastError();
   if(!SendNotification(MESSAGE))
      Print("SendNotification() failed. Error ",GetLastError());
  }
```