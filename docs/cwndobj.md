CWndObj



[MQL5 Reference](index.md)  /  [Standard Library](standardlibrary.md)  /  [Panels and Dialogs](controls.md) / CWndObj

[![Previous](previous.png)](cwnddragobjectdestroy.md) 
[![Next](next.png)](cwndobjonevent.md)

CWndObj

CWndObj is a base class for simple controls (based on chart objects) of the Standard Library.

Description

CWndObj class implements base methods of the simple control.

Declaration

```
   class CWndObj : public CWnd
```

Title

```
   #include <Controls\WndObj.mqh>
```

|  |
| --- |
| Inheritance hierarchy    [CObject](cobject.md)        [CWnd](cwnd.md)            CWndObj  Direct descendants  [CBmpButton](cbmpbutton.md), [CButton](cbutton.md), [CEdit](cedit.md), [CLabel](clabel.md), [CPanel](cpanel.md), [CPicture](cpicture.md) |

Class Methods by Groups

| Chart events processing |  |
| --- | --- |
| [OnEvent](cwndobjonevent.md) | Event handler of all chart events |
| Properties |  |
| [Text](cwndobjtext.md) | Gets/sets the [OBJPROP\_TEXT](enum_object_property.md#enum_object_property_string) property of the chart object |
| [Color](cwndobjcolor.md) | Gets/sets the [OBJPROP\_COLOR](enum_object_property.md#enum_object_property_integer) property of the chart object |
| [ColorBackground](cwndobjcolorbackground.md) | Gets/sets the [OBJPROP\_BGCOLOR](enum_object_property.md#enum_object_property_integer) property of the chart object |
| [ColorBorder](cwndobjcolorborder.md) | Gets/sets the [OBJPROP\_BORDER\_COLOR](enum_object_property.md#enum_object_property_integer) property of the chart object |
| [Font](cwndobjfont.md) | Gets/sets the [OBJPROP\_FONT](enum_object_property.md#enum_object_property_string) property of the chart object |
| [FontSize](cwndobjfontsize.md) | Gets/sets the [OBJPROP\_FONTSIZE](enum_object_property.md#enum_object_property_integer) property of the chart object |
| [ZOrder](cwndobjzorder.md) | Gets/sets the [OBJPROP\_ZORDER](enum_object_property.md#enum_object_property_integer) property of the chart object |
| Chart objects event handlers |  |
| [OnObjectCreate](cwndobjonobjectcreate.md) | [CHARTEVENT\_OBJECT\_CREATE](enum_chartevents.md) event handler |
| [OnObjectChange](cwndobjonobjectchange.md) | [CHARTEVENT\_OBJECT\_CHANGE](enum_chartevents.md) event handler |
| [OnObjectDelete](cwndobjonobjectdelete.md) | [CHARTEVENT\_OBJECT\_DELETE](enum_chartevents.md) event handler |
| [OnObjectDrag](cwndobjonobjectdrag.md) | [CHARTEVENT\_OBJECT\_DRAG](enum_chartevents.md) event handler |
| Properties change event handlers |  |
| [OnSetText](cwndobjonsettext.md) | "SetText" event handler |
| [OnSetColor](cwndobjonsetcolor.md) | "SetColor" event handler |
| [OnSetColorBackground](cwndobjonsetcolorbackground.md) | "SetColorBackground" event handler |
| [OnSetFont](cwndobjonsetfont.md) | "SetFont" event handler |
| [OnSetFontSize](cwndobjonsetfontsize.md) | "SetFontSize" event handler |
| [OnSetZOrder](cwndobjonsetzorder.md) | "SetZOrder" event handler |
| Internal event handlers |  |
| [OnDestroy](cwndobjondestroy.md) | "Destroy" internal event handler |
| [OnChange](cwndobjonchange.md) | "Change" internal event handler |

| Methods inherited from class CObject  Prev, Prev, Next, Next, [Save](cobjectsave.md), [Load](cobjectload.md), [Type](cobjecttype.md), [Compare](cobjectcompare.md) |
| --- |
| Methods inherited from class CWnd  [Create](cwndcreate.md), [Destroy](cwnddestroy.md), [OnMouseEvent](cwndonmouseevent.md), [Name](cwndname.md), [ControlsTotal](cwndcontrolstotal.md), [Control](cwndcontrol.md), [ControlFind](cwndcontrolfind.md), [Rect](cwndrect.md), [Left](cwndleft.md), [Left](cwndleft.md), [Top](cwndtop.md), [Top](cwndtop.md), [Right](cwndright.md), [Right](cwndright.md), [Bottom](cwndbottom.md), [Bottom](cwndbottom.md), [Width](cwndwidth.md), [Width](cwndwidth.md), [Height](cwndheight.md), [Height](cwndheight.md), Size, Size, Size, [Move](cwndmove.md), [Move](cwndmove.md), [Shift](cwndshift.md), [Contains](cwndcontains.md), [Contains](cwndcontains.md), [Alignment](cwndalignment.md), [Align](cwndalign.md), [Id](cwndid.md), [Id](cwndid.md), [IsEnabled](cwndisenabled.md), [Enable](cwndenable.md), [Disable](cwnddisable.md), [IsVisible](cwndisvisible.md), [Visible](cwndvisible.md), [Show](cwndshow.md), [Hide](cwndhide.md), [IsActive](cwndisactive.md), [Activate](cwndactivate.md), [Deactivate](cwnddeactivate.md), [StateFlags](cwndstateflags.md), [StateFlags](cwndstateflags.md), [StateFlagsSet](cwndstateflagsset.md), [StateFlagsReset](cwndstateflagsreset.md), [PropFlags](cwndpropflags.md), [PropFlags](cwndpropflags.md), [PropFlagsSet](cwndpropflagsset.md), [PropFlagsReset](cwndpropflagsreset.md), [MouseX](cwndmousex.md), [MouseX](cwndmousex.md), [MouseY](cwndmousey.md), [MouseY](cwndmousey.md), [MouseFlags](cwndmouseflags.md), [MouseFlags](cwndmouseflags.md), [MouseFocusKill](cwndmousefocuskill.md), BringToTop |