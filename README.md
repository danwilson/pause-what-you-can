# Pause what you can!
Use methods to control playback on web animations globally.

# Why?
Animations are a lot of fun, but we must keep accessibility in mind.  Motion can cause problems for people, such as those with [vestibular disorders](http://alistapart.com/article/designing-safer-web-animation-for-motion-sensitivity). This library aims to provide an easy way for developers to include a global toggle to pause/play whatever animations we can control.  

As an initial version, this includes animations created with the Web Animations API and CSS Keyframes.

There are new tools coming to web animations that will help with these needs in browsers, so this is more an exploration of what is possible for now.

# Usage
By default, this library will creates a control with a checkbox that can be styled and latches on to the library's main functions.  If you do not want this to show you can either hide it with CSS or call `initialize({showControls: false})`

## Methods
`initialize(options)`
Optional call to if defaults are not sufficient. Options (with default values) are:
`showControls: true`: Show a control on screen that can play/pause all pausable animations.
