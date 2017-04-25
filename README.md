# reactHWresearch
# Props

A prop is an input for a component that returns specific information about what should appear on screen. It is a data type that controls a component. They are set by the parent and fixed throughout the lifecycle of that com
Components let you split the UI into independent, reusable pieces, and think about each piece in isolation.
Conceptually, components are like JavaScript functions. They accept arbitrary inputs (called "props") and return React elements describing what should appear on the screen

# State

Used when you want to change data during the lifetime of the component. In general, you should initialize state in the constructor, and then call setState when you want to change it.

The state needs to be immutable, or not changed directly. We can do this by creating new arrays of data when updating the data. Map and filter can do this.


# Component Life Cycle

Component lifecycle methods allow you to run and override code at different times. Methods prefixed with will are called right before something happens, and methods prefixed with did are called right after something happens.

Component lifecycle begins with setting the initial props and state, continues with componentwillmount, componentdidmount, and render. Props and states can be updated and 
changed until unmounting, when the component is removed from the DOM.
