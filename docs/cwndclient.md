CWndClient



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [Panels and Dialogs](controls.md) / CWndClient

[![Previous](previous.png)](cscrollhcalcpos.md) 
[![Next](next.png)](cwndclientcreate.md)

CWndClient

CWndClient is a class of the "Client area" complex control (with dependent controls). It is a base class for creation of scroll bars area.

Description

CWndClient implements the functionality for creation of client area with scroll bars.

Declaration

```
   class CWndClient : public CWndContainer
```

Title

```
   #include <Controls\WndClient.mqh>
```

|  |
| --- |
| Inheritance hierarchy    [CObject](cobject.md)        [CWnd](cwnd.md)            [CWndContainer](cwndcontainer.md)                CWndClient  Direct descendants  [CCheckGroup](ccheckgroup.md), [CListView](clistview.md), [CRadioGroup](cradiogroup.md) |

Class Methods by Groups

| Create |  |
| --- | --- |
| [Create](cwndclientcreate.md) | Creates control |
| Chart event handler |  |
| [OnEvent](cwndclientonevent.md) | Event handler of all chart events |
| Properties |  |
| [ColorBackground](cwndclientcolorbackground.md) | Sets background color |
| [ColorBorder](cwndclientcolorborder.md) | Sets border color |
| [BorderType](cwndclientbordertype.md) | Sets border type |
| Settings |  |
| [VScrolled](cwndclientvscrolled.md) | Gets/sets the flag indicating that vertical scroll bar is used |
| [HScrolled](cwndclienthscrolled.md) | Gets/sets the flag indicating that horizontal scroll bar is used |
| Dependent controls |  |
| [CreateBack](cwndclientcreateback.md) | Creates background for scroll bar |
| [CreateScrollV](cwndclientcreatescrollv.md) | Creates vertical scroll bar |
| [CreateScrollH](cwndclientcreatescrollh.md) | Creates horizontal scroll bar |
| Internal event handlers |  |
| [OnResize](cwndclientonresize.md) | "Resize" internal event handler |
| Dependent controls event handlers |  |
| [OnVScrollShow](cwndclientonvscrollshow.md) | "Show" internal event handler (virtual) of VScroll dependent control |
| [OnVScrollHide](cwndclientonvscrollhide.md) | "Hide" internal event handler (virtual) of VScroll dependent control |
| [OnHScrollShow](cwndclientonhscrollshow.md) | "Show" internal event handler (virtual) of HScroll dependent control |
| [OnHScrollHide](cwndclientonhscrollhide.md) | "Hide" internal event handler (virtual) of HScroll dependent control |
| [OnScrollLineDown](cwndclientonscrolllinedown.md) | "ScrollLineDown" internal event handler (virtual) of VScroll dependent control |
| [OnScrollLineUp](cwndclientonscrolllineup.md) | "ScrollLineUp" internal event handler (virtual) of VScroll dependent control |
| [OnScrollLineLeft](cwndclientonscrolllineleft.md) | "ScrollLineLeft" internal event handler (virtual) of HScroll dependent control |
| [OnScrollLineRight](cwndclientonscrolllineright.md) | "ScrollLineRight" internal event handler (virtual) of HScroll dependent control |
| Resize |  |
| [Rebound](cwndclientrebound.md) | Sets new parameters of the control using CRect class coordinates |

| Methods inherited from class CObject  Prev, Prev, Next, Next, [Type](cobjecttype.md), [Compare](cobjectcompare.md) |
| --- |
| Methods inherited from class CWnd  [Name](cwndname.md), [ControlsTotal](cwndcontrolstotal.md), [Control](cwndcontrol.md), [Rect](cwndrect.md), [Left](cwndleft.md), [Left](cwndleft.md), [Top](cwndtop.md), [Top](cwndtop.md), [Right](cwndright.md), [Right](cwndright.md), [Bottom](cwndbottom.md), [Bottom](cwndbottom.md), [Width](cwndwidth.md), [Width](cwndwidth.md), [Height](cwndheight.md), [Height](cwndheight.md), Size, Size, Size, [Contains](cwndcontains.md), [Contains](cwndcontains.md), [Alignment](cwndalignment.md), [Align](cwndalign.md), [Id](cwndid.md), [IsEnabled](cwndisenabled.md), [IsVisible](cwndisvisible.md), [Visible](cwndvisible.md), [IsActive](cwndisactive.md), [Activate](cwndactivate.md), [Deactivate](cwnddeactivate.md), [StateFlags](cwndstateflags.md), [StateFlags](cwndstateflags.md), [StateFlagsSet](cwndstateflagsset.md), [StateFlagsReset](cwndstateflagsreset.md), [PropFlags](cwndpropflags.md), [PropFlags](cwndpropflags.md), [PropFlagsSet](cwndpropflagsset.md), [PropFlagsReset](cwndpropflagsreset.md), [MouseX](cwndmousex.md), [MouseX](cwndmousex.md), [MouseY](cwndmousey.md), [MouseY](cwndmousey.md), [MouseFlags](cwndmouseflags.md), [MouseFlags](cwndmouseflags.md), [MouseFocusKill](cwndmousefocuskill.md), BringToTop |
| Methods inherited from class CWndContainer  [Destroy](cwndcontainerdestroy.md), [OnMouseEvent](cwndcontaineronmouseevent.md), [ControlsTotal](cwndcontainercontrolstotal.md), [Control](cwndcontainercontrol.md), [ControlFind](cwndcontainercontrolfind.md), [MouseFocusKill](cwndcontainermousefocuskill.md), [Add](cwndcontaineradd.md), [Add](cwndcontaineradd.md), [Delete](cwndcontainerdelete.md), [Delete](cwndcontainerdelete.md), [Move](cwndcontainermove.md), [Move](cwndcontainermove.md), [Shift](cwndcontainershift.md), [Enable](cwndcontainerenable.md), [Disable](cwndcontainerdisable.md), [Hide](cwndcontainerhide.md), [Save](cwndcontainersave.md), [Load](cwndcontainerload.md) |