# DynamicPage
Angular single page application build upon a predefined json

Using a custom model to build a web form configured in a json format. All angular component will be appended dynimacly to the root element, which is defined in the DOM. The json format will be parsed to a typescript based object (with the right type) and ligthly coupled through its type to an angular component. Whenever a register user action take place, this component send an event to the parent, and with a rule (update others state on demand), which will modify the model data (reference), and the component gets rerendered (reactive way) 
