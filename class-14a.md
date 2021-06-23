# CSS Transforms, Transitions, and Animations
  When used together, these properties allow you to create simple animations and add valuable interaction and visual feedback for your users.

Just remember when adding any kind of movement to your project to keep it simple, subtle, and consistent. The movement you create should convey meaning, always enhancing, not distracting from the interaction for your users.

So what are transforms and transitions? At their most basic level, transforms move or change the appearance of an element, while transitions make the element smoothly and gradually change from one state to another.

CSS transitions: an introduction
Let’s start with CSS transitions. Transitions are the grease in the wheel of CSS transforms. Without a transition, an element being transformed would change abruptly from one state to another. By applying a transition you can control the change, making it smooth and gradual.

There are two properties that are required in order for the transition to take effect:

1.transition-property
2.transition-duration

* Each transition property can be defined individually, but for cleaner and faster code, it’s recommended that you use the transition shorthand.

Here’s the full shorthand sequence. Again, the first two properties are required.


`div {
  transition: [property] [duration] [timing-function] [delay];
}`

* transition-duration  
The transition-duration property specifies the time span of the transition. You can specify in seconds or milliseconds.

