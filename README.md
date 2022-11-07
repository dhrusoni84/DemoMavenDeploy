v4.6.0
======
* Supported CDP versions: 85, 105, 106, 107
* Updated IllegalArgumentException to NullPointerException for Null Values in Require Class (#11162)
* Fix page ranges issue in PrintOptions (#11172) (#11174)
* Ensure the correct output stream is used (#11175)
* Add initial support for Selenium Manager
* Revert "[java] only allow enabled select lists for Select class"
* [grid] Closing input pipeline when 404 is returned
* JDK Http client - avoid chunking without buffering to memory (#11198)
* Avoiding pulling same netty dependencies for AsyncHttpClient
* [grid] Only check for IEDriver on Windows.
