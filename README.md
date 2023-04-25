# Demo Vue app for broken pause on exception

This demo illustrates the problem that the Pause on uncaught exception
feature does not work as expected with Vite and Chrome DevTools.

## Steps

1. Run `npm install`
1. Run `npm run dev`
1. Navigate to the URL reported by vite.
1. Enable _Pause on uncaught exceptions_ in Chrome DevTools.
1. Click the button on the page and notice that execution doesn't stop.

