# Release Notes

## 1.0-alpha.3
* Update underlying SDKs
  * Application Insights SDK for iOS 1.0-beta.7
  * Application Insights SDK for Android 1.0-beta.9
* Remove crash/exception reporting APIs
* Add APIs for setting common properties
* Remove API to set the `userID` field, add API to set the `authUserID` (fixes user statistics)
* Minor bugfixes

## 1.0-alpha.2
* Add NuGet support
* Prevent linker from stripping SDK assemblies (release builds on iOS)
* Align public interface (remove additional parameters of setup()-method on Android)
* Add license and release notes

## 1.0-alpha.1
* Android and iOS support
	* **Auto collection** (sessions and page views)
	* **Tracking of telemetry** data (events, metrics, traces, page views, and handled exceptions)
	* **Crash reporting** for both managed and unmanaged unhandled exceptions
* Support for plattform specific as well as shared projects
* Demo project added