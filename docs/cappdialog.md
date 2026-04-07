CAppDialog



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [Panels and Dialogs](controls.md) / CAppDialog

[![Previous](previous.png)](cdialogondialogdragend.md) 
[![Next](next.png)](cappdialogcreate.md)

CAppDialog

CAppDialog is a class of Application Dialog complex control (with dependent controls).

Description

CAppDialog class is intended to combine the controls with different functions in the group inside the MQL5 program.

Declaration

```
   class CAppDialog : public CDialog
```

Title

```
   #include <Controls\Dialog.mqh>
```

|  |
| --- |
| Inheritance hierarchy    [CObject](cobject.md)        [CWnd](cwnd.md)            [CWndContainer](cwndcontainer.md)                [CDialog](cdialog.md)                    CAppDialog |

Class Methods by Groups

| Create and destroy |  |
| --- | --- |
| [Create](cappdialogcreate.md) | Creates control |
| [Destroy](cappdialogdestroy.md) | Destroys control |
| Events processing |  |
| [OnEvent](cappdialogonevent.md) | Event handler of all chart events |
| Run |  |
| [Run](cappdialogrun.md) | Runs control |
| Chart events processing |  |
| [ChartEvent](cappdialogchartevent.md) | Event handler of all chart events |
| Settings |  |
| [Minimized](cappdialogminimized.md) | Sets a value indicating whether the control is minimized |
| Save/Load |  |
| [IniFileSave](cappdialoginifilesave.md) | Saves the control state to file |
| [IniFileLoad](cappdialoginifileload.md) | Loads the control state from file |
| [IniFileName](cappdialoginifilename.md) | Sets the file name for loading/saving the control state |
| [IniFileExt](cappdialoginifileext.md) | Sets the file extension for loading/saving the control state |
| Initialization |  |
| [CreateCommon](cappdialogcreatecommon.md) | Common initialization method |
| [CreateExpert](cappdialogcreateexpert.md) | Initialization method for working in Expert Advisors |
| [CreateIndicator](cappdialogcreateindicator.md) | Initialization method for working in indicators |
| Dependent controls |  |
| [CreateButtonMinMax](cappdialogcreatebuttonminmax.md) | Creates dependent controls (minimize/maximize buttons) |
| Dependent controls event handlers |  |
| [OnClickButtonClose](cappdialogonclickbuttonclose.md) | "ClickButtonClose" internal event handler (virtual) |
| [OnClickButtonMinMax](cappdialogonclickbuttonminmax.md) | "ClickButtonMinMax" internal event handler (virtual) |
| External events |  |
| [OnAnotherApplicationClose](cappdialogonanotherapplicationclose.md) | Event handler of external events (virtual) |
| Methods |  |
| [Rebound](cappdialogrebound.md) | Sets new coordinates of the control using CRect class coordinates |
| [Minimize](cappdialogminimize.md) | Shows the control in the minimized state |
| [Maximize](cappdialogmaximize.md) | Shows the control in the maximized (restored) state |
| [CreateInstanceId](cappdialogcreateinstanceid.md) | Creates a unique Id for the names of the control objects |
| [ProgramName](cappdialogprogramname.md) | Gets the name of MQL5 program, at which the control is used |
| [SubwinOff](cappdialogsubwinoff.md) | Get the Y offset of the control subwindow |

| Methods inherited from class CObject  Prev, Prev, Next, Next, [Type](cobjecttype.md), [Compare](cobjectcompare.md) |
| --- |
| Methods inherited from class CWnd  [Name](cwndname.md), [ControlsTotal](cwndcontrolstotal.md), [Control](cwndcontrol.md), [Rect](cwndrect.md), [Left](cwndleft.md), [Left](cwndleft.md), [Top](cwndtop.md), [Top](cwndtop.md), [Right](cwndright.md), [Right](cwndright.md), [Bottom](cwndbottom.md), [Bottom](cwndbottom.md), [Width](cwndwidth.md), [Width](cwndwidth.md), [Height](cwndheight.md), [Height](cwndheight.md), Size, Size, Size, [Contains](cwndcontains.md), [Contains](cwndcontains.md), [Alignment](cwndalignment.md), [Align](cwndalign.md), [Id](cwndid.md), [IsEnabled](cwndisenabled.md), [IsVisible](cwndisvisible.md), [Visible](cwndvisible.md), [IsActive](cwndisactive.md), [Activate](cwndactivate.md), [Deactivate](cwnddeactivate.md), [StateFlags](cwndstateflags.md), [StateFlags](cwndstateflags.md), [StateFlagsSet](cwndstateflagsset.md), [StateFlagsReset](cwndstateflagsreset.md), [PropFlags](cwndpropflags.md), [PropFlags](cwndpropflags.md), [PropFlagsSet](cwndpropflagsset.md), [PropFlagsReset](cwndpropflagsreset.md), [MouseX](cwndmousex.md), [MouseX](cwndmousex.md), [MouseY](cwndmousey.md), [MouseY](cwndmousey.md), [MouseFlags](cwndmouseflags.md), [MouseFlags](cwndmouseflags.md), [MouseFocusKill](cwndmousefocuskill.md), BringToTop |
| Methods inherited from class CWndContainer  [OnMouseEvent](cwndcontaineronmouseevent.md), [ControlsTotal](cwndcontainercontrolstotal.md), [Control](cwndcontainercontrol.md), [ControlFind](cwndcontainercontrolfind.md), [MouseFocusKill](cwndcontainermousefocuskill.md), [Add](cwndcontaineradd.md), [Add](cwndcontaineradd.md), [Delete](cwndcontainerdelete.md), [Delete](cwndcontainerdelete.md), [Move](cwndcontainermove.md), [Move](cwndcontainermove.md), [Shift](cwndcontainershift.md), [Id](cwndcontainerid.md), [Enable](cwndcontainerenable.md), [Disable](cwndcontainerdisable.md), [Show](cwndcontainershow.md), [Hide](cwndcontainerhide.md) |
| Methods inherited from class CDialog  [Caption](cdialogcaption.md), [Caption](cdialogcaption.md), [Add](cdialogadd.md), [Add](cdialogadd.md) |