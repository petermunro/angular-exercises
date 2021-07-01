# Using Output Parameters

Create a component, `TweetBox`, that lets users send a tweet or another kind of message.

It could be invoked like this:

	<app-tweetbox (onSend)="handleSend($event)"></app-tweetbox>

It should display the following:

- a `<textarea>` or `<input>` for the user to type the message
- a count of the characters remaining, which should update live
- a _Send_ button which enables the message to be sent

Your component should be reusable, so that the actual sending is able
to be performed and customised by the parent component.


