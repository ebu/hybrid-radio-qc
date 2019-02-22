## Service Provider 

Tests for service provider data.

## Service Provider Logo 

These ensure that there are enough logos for a client to use, and that they are adequate for a range of displays. For size, it is preferable to have a single large size that can be scaled down that a smaller size, although a range of sizes that can be rendered properly to a range of sizes would be preferred.

* Test the existance of at least one service provider logo (FAIL)
* Test there is at least one logo equal or larger than 600x600 (WARNING)
* Test there are additional smaller sizes for smaller displays: 128x128, 320x240
* Test the logo has not got a transparent background (WARNING)
* Test that content negotiation for a different size results in that size being returned (ADVISORY)
