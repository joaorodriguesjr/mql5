CDialog



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [Panels and Dialogs](controls.md) / CDialog

[![Previous](previous.png)](cspineditonchangevalue.md) 
[![Next](next.png)](cdialogcreate.md)

CDialog

CDialog is class of the Dialog complex control.

Description

CDialog class is intended to combine the controls with different functions in the group.

Declaration

```
   class CDialog : public CWndContainer
```

Title

```
   #include <Controls\Dialog.mqh>
```

|  |
| --- |
| Inheritance hierarchy    [CObject](cobject.md)        [CWnd](cwnd.md)            [CWndContainer](cwndcontainer.md)                CDialog  Direct descendants  [CAppDialog](cappdialog.md) |

Class Methods by Groups

| Create |  |
| --- | --- |
| [Create](cdialogcreate.md) | Creates control |
| Chart event handlers |  |
| [OnEvent](cdialogonevent.md) | Event handler of all chart events |
| Properties |  |
| [Caption](cdialogcaption.md) | Gets/sets the value of the "Caption" property |
| Add |  |
| [Add](cdialogadd.md) | Adds control to the client area |
| Dependent controls |  |
| [CreateWhiteBorder](cdialogcreatewhiteborder.md) | Creates dependent control (white border) |
| [CreateBackground](cdialogcreatebackground.md) | Creates dependent control (background) |
| [CreateCaption](cdialogcreatecaption.md) | Creates dependent control (caption) |
| [CreateButtonClose](cdialogcreatebuttonclose.md) | Creates dependent control (close button) |
| [CreateClientArea](cdialogcreateclientarea.md) | Creates dependent control (client area) |
| Dependent controls event handlers |  |
| [OnClickCaption](cdialogonclickcaption.md) | "ClickCaption" internal event handler |
| [OnClickButtonClose](cdialogonclickbuttonclose.md) | "ClickButtonClose" internal event handler |
| Access to client area properties |  |
| [ClientAreaVisible](cdialogclientareavisible.md) | Sets a value indicating whether the client area is visible |
| [ClientAreaLeft](cdialogclientarealeft.md) | Gets X coordinate of the upper-left corner of the control client area |
| [ClientAreaTop](cdialogclientareatop.md) | Gets Y coordinate of the upper-left corner of the control client area |
| [ClientAreaRight](cdialogclientarearight.md) | Gets X coordinate of the lower-right corner of the control client area |
| [ClientAreaBottom](cdialogclientareabottom.md) | Gets Y coordinate of the lower-right corner of the control client area |
| [ClientAreaWidth](cdialogclientareawidth.md) | Gets the client area width |
| [ClientAreaHeight](cdialogclientareaheight.md) | Gets the client area height |
| Drag event handlers |  |
| [OnDialogDragStart](cdialogondialogdragstart.md) | "DialogDragStart" event handler (virtual) |
| [OnDialogDragProcess](cdialogondialogdragprocess.md) | "DialogDragProcess" event handler (virtual) |
| [OnDialogDragEnd](cdialogondialogdragend.md) | "DialogDragEnd" event handler (virtual) |

| Methods inherited from class CObject  Prev, Prev, Next, Next, [Type](cobjecttype.md), [Compare](cobjectcompare.md) |
| --- |
| Methods inherited from class CWnd  [Name](cwndname.md), [ControlsTotal](cwndcontrolstotal.md), [Control](cwndcontrol.md), [Rect](cwndrect.md), [Left](cwndleft.md), [Left](cwndleft.md), [Top](cwndtop.md), [Top](cwndtop.md), [Right](cwndright.md), [Right](cwndright.md), [Bottom](cwndbottom.md), [Bottom](cwndbottom.md), [Width](cwndwidth.md), [Width](cwndwidth.md), [Height](cwndheight.md), [Height](cwndheight.md), Size, Size, Size, [Contains](cwndcontains.md), [Contains](cwndcontains.md), [Alignment](cwndalignment.md), [Align](cwndalign.md), [Id](cwndid.md), [IsEnabled](cwndisenabled.md), [IsVisible](cwndisvisible.md), [Visible](cwndvisible.md), [IsActive](cwndisactive.md), [Activate](cwndactivate.md), [Deactivate](cwnddeactivate.md), [StateFlags](cwndstateflags.md), [StateFlags](cwndstateflags.md), [StateFlagsSet](cwndstateflagsset.md), [StateFlagsReset](cwndstateflagsreset.md), [PropFlags](cwndpropflags.md), [PropFlags](cwndpropflags.md), [PropFlagsSet](cwndpropflagsset.md), [PropFlagsReset](cwndpropflagsreset.md), [MouseX](cwndmousex.md), [MouseX](cwndmousex.md), [MouseY](cwndmousey.md), [MouseY](cwndmousey.md), [MouseFlags](cwndmouseflags.md), [MouseFlags](cwndmouseflags.md), [MouseFocusKill](cwndmousefocuskill.md), BringToTop |
| Methods inherited from class CWndContainer  [Destroy](cwndcontainerdestroy.md), [OnMouseEvent](cwndcontaineronmouseevent.md), [ControlsTotal](cwndcontainercontrolstotal.md), [Control](cwndcontainercontrol.md), [ControlFind](cwndcontainercontrolfind.md), [MouseFocusKill](cwndcontainermousefocuskill.md), [Add](cwndcontaineradd.md), [Add](cwndcontaineradd.md), [Delete](cwndcontainerdelete.md), [Delete](cwndcontainerdelete.md), [Move](cwndcontainermove.md), [Move](cwndcontainermove.md), [Shift](cwndcontainershift.md), [Id](cwndcontainerid.md), [Enable](cwndcontainerenable.md), [Disable](cwndcontainerdisable.md), [Show](cwndcontainershow.md), [Hide](cwndcontainerhide.md) |