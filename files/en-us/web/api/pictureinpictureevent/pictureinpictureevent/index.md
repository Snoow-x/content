---
title: PictureInPictureEvent()
slug: Web/API/PictureInPictureEvent/PictureInPictureEvent
browser-compat: api.PictureInPictureEvent.PictureInPictureEvent
---
{{APIRef("DOM Events")}}

The **`PictureInPictureEvent()`** constructor returns a newly
created {{domxref("PictureInPictureEvent")}} object with an optional
{{domxref("EventTarget")}}. When the event has both a source and a destination, the
`relatedTarget` value must be set to the other target.

## Syntax

```js
new PictureInPictureEvent(typeArg)
new PictureInPictureEvent(typeArg, pictureInPictureInit);
```

### Properties

_The `PictureInPictureEvent()` constructor also inherits arguments from
{{domxref("Event.Event", "Event()")}}._

- `typeArg`
  - : A {{domxref("DOMString")}} representing the name of the event.
- `focusEventInit` {{optional_inline}}

  - : A `PictureInPictureEventInit` dictionary, having the following
    fields:

    - `"relatedTarget"`, optional and defaulting to
      `null`, is an {{domxref("EventTarget")}}.

## Specifications

{{Specifications}}

## Browser compatibility

{{Compat}}

## See also

- The {{domxref("PictureInPictureEvent")}} interface it belongs to.
