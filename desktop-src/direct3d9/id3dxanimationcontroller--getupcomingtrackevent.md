---
Description: Returns an event handle to the next event scheduled to occur after a specified event on an animation track.
ms.assetid: 616b2de1-6107-4d18-ad2e-de2ef4560aee
title: ID3DXAnimationController::GetUpcomingTrackEvent method
ms.technology: desktop
ms.prod: windows
ms.author: windowssdkdev
ms.topic: article
ms.date: 05/31/2018
---

# ID3DXAnimationController::GetUpcomingTrackEvent method

Returns an event handle to the next event scheduled to occur after a specified event on an animation track.

## Syntax


```C++
D3DXEVENTHANDLE GetUpcomingTrackEvent(
  [in] UINT            Track,
  [in] D3DXEVENTHANDLE hEvent
);
```



## Parameters

<dl> <dt>

*Track* \[in\]
</dt> <dd>

Type: **[**UINT**](https://msdn.microsoft.com/4553cafc-450e-4493-a4d4-cb6e2f274d46)**

Track identifier.

</dd> <dt>

*hEvent* \[in\]
</dt> <dd>

Type: **[**D3DXEVENTHANDLE**](id3dxanimationcontroller.md)**

Event handle to a specified event after which to search for a following event. If set to **NULL**, then the method will return the next scheduled event.

</dd> </dl>

## Return value

Type: **[**D3DXEVENTHANDLE**](id3dxanimationcontroller.md)**

Event handle to the next event scheduled to run on the specified track. **NULL** is returned if no new event is scheduled.

## Remarks

This method can be used iteratively to locate a desired event by repeatedly passing in **NULL** for hEvent.

> [!Note]  
> Do not iterate further after the method has returned **NULL**.

 

## Requirements



|                    |                                                                                        |
|--------------------|----------------------------------------------------------------------------------------|
| Header<br/>  | <dl> <dt>D3dx9anim.h</dt> </dl> |
| Library<br/> | <dl> <dt>D3dx9.lib</dt> </dl>   |



## See also

<dl> <dt>

[ID3DXAnimationController](id3dxanimationcontroller.md)
</dt> </dl>

 

 



