# Hathora Cloud Unity Plugin Version History

## LATEST
*Released November 7th 2023 5:58pm PDT*

* Fix links to Hathora docs
* Fix server build generation script (`HathoraServerBuild.cs`) to better produce dedicated server build. Note: after running "Generate Server Build", Build Settings will be set to "Dedicated Server - Linux".
* Fix tar script (`HathoraTar.cs`) to properly ignore new ButDontShip directory

## v0_0_7
*Released November 2nd 2023 6:57pm PDT*

* HathoraClientMgr.CreateLobbyAsync now supports optional roomId override
* HATHORA_REGION environment variable now stored in HathoraServerContext
* Updated Hathora Cloud Unity SDK to latest version
* Minor stability and code improvements

## v0_0_6
*Released October 16th 2023 5:25pm PDT*

* New and improved Hathora Cloud Unity SDK
* "Hathora Server Config Finder" pop-up window has been moved to the "Hathora" top menu
* Caching of edtior plugin expand/collapse state
* Minor stability and code improvements

## v0_0_5
*Released September 13st 2023 1:42pm PDT*

* Improved HathoraServerMgr and HathoraClientMgr to make integration easier and more intuitive 
* Bug fixed: EnvVariables and AdditionalPorts are no longer removed when deploying with the Editor plugin
* Bug fixed: CreateRoom Region selector would sometimes be innacurate
* Minor stability and code improvements

## v0_0_4
*Released August 21st 2023 5:16pm PDT*

* WSS/TLS support added to Mirror Demo
* Minor stability and code improvements

## v0_0_3
*Released August 8th 2023 6:60pm PDT*

* Fix for Dockerfile generation bug introduce in v0_0_2
* Minor stability and code improvements

## v0_0_2
*Released August 4th 2023 4:12pm PDT*

* Added WebGL support for FishNet Demo (currently only WSS/TLS is supported)
* Minor stability and code improvements

## v0_0_1
*Released July 27th 2023 2:29pm PDT*

* Our first official release of the Hathora Cloud Unity Plugin!