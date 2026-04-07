CScroll



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [Panels and Dialogs](controls.md) / CScroll

[![Previous](previous.png)](cpictureonchange.md) 
[![Next](next.png)](cscrollcreate.md)

CScroll

CScroll is a base class for creation of scroll bars.

Description

CScroll is a complex control (with dependent controls), it contains the base functionality for creation of scroll bars. The base class itself is not used as a separate control, two of its heirs ([CScrollV](cscrollv.md) and [CScrollH](cscrollh.md) classes) are used as controls.

Declaration

```
   class CScroll : public CWndContainer
```

Title

```
   #include <Controls\Scrolls.mqh>
```

|  |
| --- |
| Inheritance hierarchy    [CObject](cobject.md)        [CWnd](cwnd.md)            [CWndContainer](cwndcontainer.md)                CScroll  Direct descendants  [CScrollH](cscrollh.md), [CScrollV](cscrollv.md) |

Class Methods by Groups

| Create |  |
| --- | --- |
| [Create](cscrollcreate.md) | Creates control |
| Chart object event handlers |  |
| [OnEvent](cscrollonevent.md) | Event handler of all chart events |
| Properties |  |
| [MinPos](cscrollminpos.md) | Gets/sets the minimal position |
| [MaxPos](cscrollmaxpos.md) | Gets/sets the maximal position |
| [CurrPos](cscrollcurrpos.md) | Gets/sets the current position |
| Dependent controls creation |  |
| [CreateBack](cscrollcreateback.md) | Creates background button |
| [CreateInc](cscrollcreateinc.md) | Creates increment button of the scroll bar |
| [CreateDec](cscrollcreatedec.md) | Creates decrement button of the scroll bar |
| [CreateThumb](cscrollcreatethumb.md) | Creates thumb button (can be dragged) of the scroll bar |
| Dependent controls event handlers |  |
| [OnClickInc](cscrollonclickinc.md) | Event handler used for handling increment button events |
| [OnClickDec](cscrollonclickdec.md) | Event handler used for handling decrement button events |
| Internal event handlers |  |
| [OnShow](cscrollonshow.md) | "Create" internal event handler |
| [OnHide](cscrollonhide.md) | "Hide" internal event handler |
| [OnChangePos](cscrollonchangepos.md) | "ChangePosition" internal event handler |
| Object drag handlers |  |
| [OnThumbDragStart](cscrollonthumbdragstart.md) | "ThumbDragStart" event handler |
| [OnThumbDragProcess](cscrollonthumbdragprocess.md) | "ThumbDragProcess" event handler |
| [OnThumbDragEnd](cscrollonthumbdragend.md) | "ThumbDragEnd" event handler |
| Position |  |
| [CalcPos](cscrollcalcpos.md) | Gets scroll bar position by coordinate |

| Methods inherited from class CObject  Prev, Prev, Next, Next, [Type](cobjecttype.md), [Compare](cobjectcompare.md) |
| --- |
| Methods inherited from class CWnd  [Name](cwndname.md), [ControlsTotal](cwndcontrolstotal.md), [Control](cwndcontrol.md), [Rect](cwndrect.md), [Left](cwndleft.md), [Left](cwndleft.md), [Top](cwndtop.md), [Top](cwndtop.md), [Right](cwndright.md), [Right](cwndright.md), [Bottom](cwndbottom.md), [Bottom](cwndbottom.md), [Width](cwndwidth.md), [Width](cwndwidth.md), [Height](cwndheight.md), [Height](cwndheight.md), Size, Size, Size, [Contains](cwndcontains.md), [Contains](cwndcontains.md), [Alignment](cwndalignment.md), [Align](cwndalign.md), [Id](cwndid.md), [IsEnabled](cwndisenabled.md), [IsVisible](cwndisvisible.md), [Visible](cwndvisible.md), [IsActive](cwndisactive.md), [Activate](cwndactivate.md), [Deactivate](cwnddeactivate.md), [StateFlags](cwndstateflags.md), [StateFlags](cwndstateflags.md), [StateFlagsSet](cwndstateflagsset.md), [StateFlagsReset](cwndstateflagsreset.md), [PropFlags](cwndpropflags.md), [PropFlags](cwndpropflags.md), [PropFlagsSet](cwndpropflagsset.md), [PropFlagsReset](cwndpropflagsreset.md), [MouseX](cwndmousex.md), [MouseX](cwndmousex.md), [MouseY](cwndmousey.md), [MouseY](cwndmousey.md), [MouseFlags](cwndmouseflags.md), [MouseFlags](cwndmouseflags.md), [MouseFocusKill](cwndmousefocuskill.md), BringToTop |
| Methods inherited from class CWndContainer  [Destroy](cwndcontainerdestroy.md), [OnMouseEvent](cwndcontaineronmouseevent.md), [ControlsTotal](cwndcontainercontrolstotal.md), [Control](cwndcontainercontrol.md), [ControlFind](cwndcontainercontrolfind.md), [MouseFocusKill](cwndcontainermousefocuskill.md), [Add](cwndcontaineradd.md), [Add](cwndcontaineradd.md), [Delete](cwndcontainerdelete.md), [Delete](cwndcontainerdelete.md), [Move](cwndcontainermove.md), [Move](cwndcontainermove.md), [Shift](cwndcontainershift.md), [Id](cwndcontainerid.md), [Enable](cwndcontainerenable.md), [Disable](cwndcontainerdisable.md), [Show](cwndcontainershow.md), [Hide](cwndcontainerhide.md), [Save](cwndcontainersave.md), [Load](cwndcontainerload.md) |