---
title: unfold/2
url: Stream/unfold/2
---

# Stream.unfold/2

{{< signature >}}

Emits a sequence of values for the given accumulator `acc`.

Successive values are generated by calling `fun` with the previous accumulator and it must return a tuple with the current value and next accumulator. The enumeration finishes if it returns `nil`.

{{< figure src="images/functions/Stream/unfold-2.svg" >}}