CWndContainer



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [Panels and Dialogs](controls.md) / CWndContainer

[![Previous](previous.png)](cwndobjonchange.md) 
[![Next](next.png)](cwndcontainerdestroy.md)

CWndContainer

CWndContainer is a base class for a complex control (containing dependent controls) of the Standard library.

Description

CWndContainer class implements base methods of the complex control.

Declaration

```
   class CWndContainer : public CWnd
```

Title

```
   #include <Controls\WndContainer.mqh>
```

|  |
| --- |
| Inheritance hierarchy    [CObject](cobject.md)        [CWnd](cwnd.md)            CWndContainer  Direct descendants  [CCheckBox](ccheckbox.md), [CComboBox](ccombobox.md), CDateDropList, CDatePicker, [CDialog](cdialog.md), [CRadioButton](cradiobutton.md), [CScroll](cscroll.md), [CSpinEdit](cspinedit.md), [CWndClient](cwndclient.md) |

Class Methods by Groups

| Destroy |  |
| --- | --- |
| [Destroy](cwndcontainerdestroy.md) | Destroys all the container controls |
| Chart event handlers |  |
| [OnEvent](cwndcontaineronevent.md) | Event handler of all chart events |
| [OnMouseEvent](cwndcontaineronmouseevent.md) | The [CHARTEVENT\_MOUSE\_MOVE](enum_chartevents.md) event handler |
| Access to container |  |
| [ControlsTotal](cwndcontainercontrolstotal.md) | Gets the number of controls in the container |
| [Control](cwndcontainercontrol.md) | Gets control by index |
| [ControlFind](cwndcontainercontrolfind.md) | Gets control by ID |
| Add/Delete |  |
| [Add](cwndcontaineradd.md) | Adds control to a group (container) |
| [Delete](cwndcontainerdelete.md) | Deletes control from a group (container) |
| Geometry |  |
| [Move](cwndcontainermove.md) | Performs a absolute displacement of an element group |
| [Shift](cwndcontainershift.md) | Performs a relative displacement of an element group |
| Identification |  |
| [Id](cwndcontainerid.md) | Sets the ID for all controls of the container |
| State |  |
| [Enable](cwndcontainerenable.md) | Enables all controls of the container |
| [Disable](cwndcontainerdisable.md) | Disables all controls of the container |
| [Show](cwndcontainershow.md) | Shows all controls of the container |
| [Hide](cwndcontainerhide.md) | Hides all controls of the container |
| Mouse operations |  |
| [MouseFocusKill](cwndcontainermousefocuskill.md) | Kills mouse focus |
| File operations |  |
| [Save](cwndcontainersave.md) | Saves container information to file |
| [Load](cwndcontainerload.md) | Loads container information from file |
| Internal event handlers |  |
| [OnResize](cwndcontaineronresize.md) | "Resize" event handler |
| [OnActivate](cwndcontaineronactivate.md) | "Activate" event handler |
| [OnDeactivate](cwndcontainerondeactivate.md) | "Deactivate" event handler |

| Methods inherited from class CObject  Prev, Prev, Next, Next, [Type](cobjecttype.md), [Compare](cobjectcompare.md) |
| --- |
| Methods inherited from class CWnd  [Create](cwndcreate.md), [Name](cwndname.md), [ControlsTotal](cwndcontrolstotal.md), [Control](cwndcontrol.md), [Rect](cwndrect.md), [Left](cwndleft.md), [Left](cwndleft.md), [Top](cwndtop.md), [Top](cwndtop.md), [Right](cwndright.md), [Right](cwndright.md), [Bottom](cwndbottom.md), [Bottom](cwndbottom.md), [Width](cwndwidth.md), [Width](cwndwidth.md), [Height](cwndheight.md), [Height](cwndheight.md), Size, Size, Size, [Contains](cwndcontains.md), [Contains](cwndcontains.md), [Alignment](cwndalignment.md), [Align](cwndalign.md), [Id](cwndid.md), [IsEnabled](cwndisenabled.md), [IsVisible](cwndisvisible.md), [Visible](cwndvisible.md), [IsActive](cwndisactive.md), [Activate](cwndactivate.md), [Deactivate](cwnddeactivate.md), [StateFlags](cwndstateflags.md), [StateFlags](cwndstateflags.md), [StateFlagsSet](cwndstateflagsset.md), [StateFlagsReset](cwndstateflagsreset.md), [PropFlags](cwndpropflags.md), [PropFlags](cwndpropflags.md), [PropFlagsSet](cwndpropflagsset.md), [PropFlagsReset](cwndpropflagsreset.md), [MouseX](cwndmousex.md), [MouseX](cwndmousex.md), [MouseY](cwndmousey.md), [MouseY](cwndmousey.md), [MouseFlags](cwndmouseflags.md), [MouseFlags](cwndmouseflags.md), [MouseFocusKill](cwndmousefocuskill.md), BringToTop |