# 10-second timer #

[Demo](https://MERNCraft.github.io/10s-timer)

A simple CSS animation which modifies the `background-color` of a div. The background-color seems to pulse. This is because:

* Animations use transitions by default
* `background-color` is a property that can transition through intermediate values
* The default [`transition-timing-function`](https://developer.mozilla.org/en-US/docs/Web/CSS/transition-timing-function) for an animation is `ease-in-out`

As a result, the `background-color` starts changing slowly, then moves quickly through the central intermediate values, then slows down as it approaches each keyframe value.