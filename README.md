message
=======

Simple Pub/Sub module

### Usage

Please copy the source code to use.
```js
var Message = require('message');

// subscribe global message
Message.on('chaneg', doSomething);
// unsubscribe global message
Message.off('chaneg', doSomething);
// publish globale message
Message.emit('change', data);

// Local Message instance
var msg = new Message()

// subscribe message from the instance
msg.on('chaneg', doSomething);
// unsubscribe message  from the instance
msg.off('chaneg', doSomething);
// publish message to the instance
msg.emit('change', data);
```
