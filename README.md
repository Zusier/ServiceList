# ServiceList
A list of services that are on the latest version of windows (20H2). 

TODO:
- Complete Service List
- Make lists for older versions
- Sort alphabetically




| Service | Service Name | Impacts | My Recommendation
| --- | --- | --- | --- |
| DiagTrack | Connected User Experiences And Telemetry | Collects and Reports Diagnostic and Telemetry data to Microsoft [This service is impacted by this setting](https://github.com/Zusier/ServiceList/blob/main/.github/img/66860455-167D-4BAA-979B-4B2C6DAB22A5.jpeg) Disabling it will disabled that form of Telemetry | Disable |
| AJRouter | AllJoyn Router Service | Routes AllJoyn messages for the local AllJoyn clients. If this service is stopped the AllJoyn clients that do not have their own bundled routers will be unable to run. | Disable |
| Beep | Beep | It beeps, very cool I know. | Disable |
| PeerDistSvc | BranchCache | Caches network content from peers on the **local** subnet | Disable |
| autotimesvc | Cellular Time | Sets time based on NITZ messages from a mobile network. | Disable |
| CAD | Charge Arbitration Driver | Seems to a battery life control driver to extend the age of the laptop driver. | Disable |
| cbdhsvc | Clipboard User Service | Controls Clipboard History, not required for regular clipboard functionality | Disable |
| CompositeBus | Composite Bus Enumerator Driver | Can't seem to find the actual functionality yet. | Disable |



## Resources
[RevertService](http://revertservice.com/10/) Provides a list of services and their default startup mode. 
[BatCMD](http://batcmd.com/windows/10/services/) Provides a list of services and their default startup mode. 
