## 1.6.1 (Jun 18, 2017)

* Use `react-transition-group` instead of `react-addons-css-transition-group`.

## 1.6.0 (April 14, 2017)

* Added `transitionConfig` prop to allow configuring `ReactCSSTransitionGroup` for the loader overlay.
* Added fade transition to demo0.

## 1.5.0 (April 14, 2017)

* Use React `Component` instead of `createClass` and `prop-types` library to suppress deprication warnings

## 1.4.0 (May 28, 2016)

* Added `contentStyle` property to extend content container styles

* Added `messageStyle` property to extend message container styles

## 1.3.0 (May 7, 2016)

* Removed babel-polyfill that was polluting globals. Now using
babel-transform-runtime instead.

* Internal changes.

## 1.1.1 (Mar 8, 2016)

Very important bugfix: rendering was causing redundant mounts and
unmounts that caused unwanted side-effects on rare cases.

## 0.7.0 (Oct 23, 2015)

### Breaking changes

CSS styles now follow correct BEM-naming. Update your classes if you have
overriden Loader classes.

* Loader--content => Loader__content
* Loader--background => Loader__background
* Loader--foreground => Loader__foreground
* Loader--message => Loader__message
