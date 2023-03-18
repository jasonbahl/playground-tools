<!-- Do not edit this file. It is automatically generated by API Documenter. -->

## awaitReply() function

awaitReply<!-- -->(\
&emsp;&emsp;&emsp;<!-- -->messageTarget<!-- -->: [IsomorphicEventTarget](./web-service-worker.isomorphiceventtarget.md)<!-- -->, \
&emsp;&emsp;&emsp;<!-- -->requestId<!-- -->: [number](https://www.typescriptlang.org/docs/handbook/2/everyday-types.html#the-primitives-string-number-and-boolean)<!-- -->, \
&emsp;&emsp;&emsp;<!-- -->timeout?<!-- -->: [number](https://www.typescriptlang.org/docs/handbook/2/everyday-types.html#the-primitives-string-number-and-boolean)\
)<!-- -->: [Promise](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Promise)<!-- -->&lt;[any](https://www.typescriptlang.org/docs/handbook/2/everyday-types.html#any)<!-- -->&gt;

-   `messageTarget` – EventEmitter emitting `message` events, e.g. `window`
    or a `Worker` instance.

-   `requestId` – The message ID returned by postMessageExpectReply().
-   `timeout` – Optional. The number of milliseconds to wait for a reply before
    throwing an error.

-   Returns: The reply from the messageTarget.

Exceptions:

Awaits a reply to the message with the given ID.