# Directives

## Using Attribute Directives

1.  Create a component that displays a text `<input>` field. If the user has entered data into the text field, the border should be green; otherwise it should be red.

    ### Notes

      - Use the `input` event type to detect changes.
      - Your event handler can accept events of type `Event`.
      - You may need to cast `event.target` to use `event.target.value`:

          ```typescript
          (event.target as HTMLInputElement).value
          ```


2.  Create an `<app-warning>` component that displays its contents with a red border and pink background. A parent should be able to invoke it like this:

        <app-warning>
          A problem occurred in communicating with an upstream server
        </app-warning>
