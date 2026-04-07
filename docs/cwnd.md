CWnd



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [Panels and Dialogs](controls.md) / CWnd

[![Previous](previous.png)](cdatetimeyearinc.md) 
[![Next](next.png)](cwndcreate.md)

CWnd

CWnd is a base class for all Standard Library controls.

Description

CWnd class is the implementation of the base control class.

Declaration

```
   class CWnd : public CObject
```

Title

```
   #include <Controls\Wnd.mqh>
```

|  |
| --- |
| Inheritance hierarchy    [CObject](cobject.md)        CWnd  Direct descendants  CDragWnd, [CWndContainer](cwndcontainer.md), [CWndObj](cwndobj.md) |

Class Methods by Groups

| Create and destroy |  |
| --- | --- |
| [Create](cwndcreate.md) | Creates control |
| [Destroy](cwnddestroy.md) | Destroys control |
| Chart event handlers |  |
| [OnEvent](cwndonevent.md) | Event handler of all chart events |
| [OnMouseEvent](cwndonmouseevent.md) | Event handler for the [CHARTEVENT\_MOUSE\_MOVE](enum_chartevents.md) event |
| Name |  |
| [Name](cwndname.md) | Gets control name |
| Access to container |  |
| [ControlsTotal](cwndcontrolstotal.md) | Gets the number of controls in the container |
| [Control](cwndcontrol.md) | Gets the control by index |
| [ControlFind](cwndcontrolfind.md) | Gets the control by ID |
| Geometry |  |
| [Rect](cwndrect.md) | Gets the control coordinates |
| [Left](cwndleft.md) | Gets/sets the X coordinate of the upper-left corner |
| [Top](cwndtop.md) | Gets/sets the Y coordinate of the upper-left corner |
| [Right](cwndright.md) | Gets/sets the X coordinate of the lower-right corner |
| [Bottom](cwndbottom.md) | Gets/sets the Y coordinate of the lower-right corner |
| [Width](cwndwidth.md) | Gets/sets the control width |
| [Height](cwndheight.md) | Gets/sets the control height |
| [Move](cwndmove.md) | Control absolute displacement |
| [Shift](cwndshift.md) | Control relative displacement |
| [Resize](cwndresize.md) | Changes control size |
| [Contains](cwndcontains.md) | Checks if the point/control is inside the control area |
| Align |  |
| [Alignment](cwndalignment.md) | Sets alignment properties of the control |
| [Align](cwndalign.md) | Performs control alignment in the specified chart area |
| Identification |  |
| [Id](cwndid.md) | Gets/sets the control ID |
| State |  |
| [IsEnabled](cwndisenabled.md) | Checks the control ability to respond to user's actions |
| [Enable](cwndenable.md) | Enables the control ability to respond to user's actions |
| [Disable](cwnddisable.md) | Disables the control ability to respond to user's actions |
| [IsVisible](cwndisvisible.md) | Checks the visibility flag |
| [Visible](cwndvisible.md) | Sets the visibility flag |
| [Show](cwndshow.md) | Shows the control |
| [Hide](cwndhide.md) | Hides the control |
| [IsActive](cwndisactive.md) | Checks the control activity |
| [Activate](cwndactivate.md) | Activates the control |
| [Deactivate](cwnddeactivate.md) | Deactivates the control |
| State flags |  |
| [StateFlags](cwndstateflags.md) | Gets/sets the control state flags |
| [StateFlagsSet](cwndstateflagsset.md) | Sets the control state flags |
| [StateFlagsReset](cwndstateflagsreset.md) | Resets the control state flags |
| Properties flags |  |
| [PropFlags](cwndpropflags.md) | Gets/sets the control properties flags |
| [PropFlagsSet](cwndpropflagsset.md) | Sets the control properties flags |
| [PropFlagsReset](cwndpropflagsreset.md) | Resets the control properties flags |
| Mouse operations |  |
| [MouseX](cwndmousex.md) | Gets/saves the mouse X coordinate |
| [MouseY](cwndmousey.md) | Gets/saves the mouse Y coordinate |
| [MouseFlags](cwndmouseflags.md) | Gets/saves the mouse buttons state |
| [MouseFocusKill](cwndmousefocuskill.md) | Kills mouse focus |
| Internal event handlers |  |
| [OnCreate](cwndoncreate.md) | "Create" event handler |
| [OnDestroy](cwndondestroy.md) | "Destroy" event handler |
| [OnMove](cwndonmove.md) | "Move" event handler |
| [OnResize](cwndonresize.md) | "Resize" event handler |
| [OnEnable](cwndonenable.md) | "Enable" event handler |
| [OnDisable](cwndondisable.md) | "Disable" event handler |
| [OnShow](cwndonshow.md) | "Show" event handler |
| [OnHide](cwndonhide.md) | "Hide" event handler |
| [OnActivate](cwndonactivate.md) | "Activate" event handler |
| [OnDeactivate](cwndondeactivate.md) | "Deactivate" event handler |
| [OnClick](cwndonclick.md) | "Click" event handler |
| [OnChange](cwndonchange.md) | "Change" event handler |
| Mouse event handlers |  |
| [OnMouseDown](cwndonmousedown.md) | "MouseDown" event handler |
| [OnMouseUp](cwndonmouseup.md) | "MouseUp" event handler |
| Drag event handlers |  |
| [OnDragStart](cwndondragstart.md) | "DragStart" event handler |
| [OnDragProcess](cwndondragprocess.md) | "DragProcess" event handler |
| [OnDragEnd](cwndondragend.md) | "DragEnd" event handler |
| Drag object |  |
| [DragObjectCreate](cwnddragobjectcreate.md) | Creates drag object |
| [DragObjectDestroy](cwnddragobjectdestroy.md) | Destroys drag object |

|  |
| --- |
| Methods inherited from class CObject  Prev, Prev, Next, Next, [Save](cobjectsave.md), [Load](cobjectload.md), [Type](cobjecttype.md), [Compare](cobjectcompare.md) |