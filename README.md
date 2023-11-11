# Interval - Js class for advanced countdown timer.

Using this library you can create countdown for a specific task to happen, like for sms, otp an demail verifications, and live chats etc.

```
const interval = new Interval({
    counter: '#counter',
    delay: 1000,
    duration: 1,
    onStart: function () {
        console.log('When started the interval');
    },
    onEnd: function () {

        console.log('When ended the interval');
    },
    onPaused: function () {

        console.log('When paused the interval');
    },
    onReset: function () {

        console.log('When reseted the interval');
    },
    onRestart: function () {

        console.log('When restarted the interval');
    }
});
```

## Properties

### counter : property

This defines the targeted element you want to update the content.

class : '.count'

id : '#count'

tagname : 'div'

### delay : property

Defines the refresh rate of the `setInterval` method.

### duration : property

Defines how long you want to run the function. This should be in `seconds`. But by few modifications you can convert it to seconds, mili-seconds or hours etc.

## Methods

### onStart : method

You can run any actions when the `setInterval` method started.

### onEnd : method

You can run any actions when the `setInterval` method ends due to timeout.

### onPaused : method

You can run any actions when the `setInterval` method is paused.

### onReset : method

You can run any actions when the `setInterval` method is reset. This will bring the countdown to `initial` time. But it won't start the countdown.

