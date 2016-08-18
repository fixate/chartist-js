# Chartist - Edu Game Branch

**This branch on this fork is specifically for fixate/react-chartist to pull in a
version of Chartist that doesn't throw runtime errors on Node when running
tests.**

The only difference between this repo and master, when it was forked at
[bc34bf](https://github.com/gionkunz/chartist-js/commit/bc34bf9103c30c44cf1336d119ed4f1a20226e7e)
is that it doesn't require `window` and `document` to be passed into IIFEs.

Look at the original [ChartistJs](https://github.com/gionkunz/chartist-js) if you wanna.
