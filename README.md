# Interval - Js class for advanced countdown timer.

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