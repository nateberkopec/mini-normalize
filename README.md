# mini-normalize

A miniature CSS reset, based on normalize.css, suitable for inlining. 549 bytes gzipped.

Browser target is IE11+ and current versions of popular mobile browsers
(i.e. any version with 1% or greater adoption on [caniuse](http://caniuse.com/usage-table)).
Removes much of the weight associated with supporting old IE and old iOS versions.

Intended for those who prefer low cognitive overhead in their CSS or for use in
size-constrained, critical-path environments.

This reset intentionally does not reset many uncommon elements, such as `mark`, `kbd` or `samp`.

## CSS reset size comparison

| Name           | Size          | Size (gzip)   |
| -------------- | ------------- | ------------- |
| This library   | 947 bytes     | 463 bytes     |
| normalize.css  | 8052 bytes    | 964 bytes     |

## References

Based on the work of the following authors:

* [Eric Meyer's Reset](http://cssreset.com/scripts/eric-meyer-reset-css/)
* [Vladimir Carrer](https://github.com/vladocar/CSS-Mini-Reset)
* [Russ Weakley](http://maxdesign.com.au/articles/css-reset/)
* [Normalize.css](https://necolas.github.io/normalize.css/)
