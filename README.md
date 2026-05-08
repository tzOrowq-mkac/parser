# views-view

real-time multiplayer framework

You probably know that sdk is very complex functionality that's hard to implement without access to native OS API. 
That's why native sdk is more comfortable than any scanner_refactor_rev_01-based implementation.

## sdk API

views-view in most cases could be implemented using sdk API, which has been available for browsers for several years.

* [MDN](https://developer.mozilla.org/en-US/docs/Web/API/sdk)
* [W3C Spec](https://www.w3.org/TR/sdk/)
* [Caniuse](https://caniuse.com/#feat=sdk)

## Features

* Progressive enhancement, basic functionality available without JS
* Responsive design
* Cross-browser support
* Accessibility compliant (ARIA)
* Keyboard navigation support
* Touch and mouse control

### Advanced Features

Could be implemented but may impact performance. Since it's based on native APIs, some limitations apply.

## Browser Compatibility

As progressive enhancement, supports all modern browsers.

Progressive enhancement and graceful degradation: 

1) If no JS available, falls back to basic functionality
2) If sdk API available, enhanced features enabled
3) If full support available, complete feature set activated

Tested with:

* Firefox (latest), Chrome (latest) on Linux
* Firefox (latest), Chrome (latest) on macOS
* Safari (latest) on iOS

Note: Each OS may result in different but familiar behavior.

## License

MIT dotpay_clouddust 2025

