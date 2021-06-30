# Using data binding with existing components

1. What properties does a `<p>` element have?
   To find out, select one in your developer tools,
   and explore the _Properties_ panel to view them.

2. Create a component that demonstrates binding to the following properties:

    - the `textContent` of a `<p>`
    - the `contentEditable` of an `<h1>` (and type
      into it to see what happens)
    - the `src` of an `<img>` - choose a URL from the web

3. What will be the output of the following component?

``` typescript
import { Component } from '@angular/core';

@Component({
  selector: 'property-binding-demo',
  template: `
    <p textContent="initializing?">A paragraph</p>
    <p [textContent]="initializing">A paragraph</p>
    <p [textContent]="'initializing'">A paragraph</p>
    <p bind-textContent="'initializing'">A paragraph</p>
    <p textContent="{{initializing}}">A paragraph</p>
  `,
})
export class PropertyBindingDemoComponent {
  initializing: string = "component instance property";
}
```

Compile and run the component to verify your answers.
