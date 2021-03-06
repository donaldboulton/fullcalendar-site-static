---
title: eventMouseLeave
type: callback
---

Triggered when the user mouses out of an event. Similar to the native [mouseleave](https://developer.mozilla.org/en-US/docs/Web/Events/mouseleave).

<div class='spec' markdown='1'>
function( *mouseLeaveInfo* ) { }
</div>

`mouseLeaveInfo` is a plain object with the following properties:

<table>

<tr>
<th>event</th>
<td markdown='1'>
The associated [Event Object](event-object).
</td>
</tr>

<tr>
<th>el</th>
<td markdown='1'>
The HTML element for this event.
</td>
</tr>

<tr>
<th>jsEvent</th>
<td markdown='1'>
The native JavaScript event with low-level information such as click coordinates.
</td>
</tr>

<tr>
<th>view</th>
<td markdown='1'>
The current [View Object](view-object).
</td>
</tr>

</table>
