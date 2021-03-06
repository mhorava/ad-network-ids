# SKAdNetwork id collection

App developers that want to leverage Apples install/conversion attribution API [SKAdNetwork](https://developer.apple.com/documentation/storekit/skadnetwork) need to update their apps for iOS14. Apps that display advertisement have to include each advertising partners Apple issued id in the [Info.plist](https://developer.apple.com/library/archive/documentation/General/Reference/InfoPlistKeyReference/Articles/AboutInformationPropertyListFiles.html). (Given that they like to enable measurement for this partner.)

Until there is a centralized place or a tool to curate/update the list this repository can serve as a starting point. If you like to add an id please open a PR.

# Related

* An example implementation of SKAdNetwork: https://github.com/singular-labs/Singular-SKAdNetwork-App.
* A proposal how to implement conversion value managemant: [Elixir](https://github.com/2ndpotion/ElixiriOS) ([demo](https://www.youtube.com/watch?v=cY0jnPw6TOI))  


## List of ids

As Info.plist entries that can be copy and pasted: [ad-network-ids.plist](ad-network-ids.plist)

|Company|Id|Description|
|-------|--|-----------|
|[Jampp](https://jampp.com)|YCLNXRL5PM|Mobile user acquisition & retargeting DSP|
|[remerge](https://www.remerge.com)|2U9PT9HC89|Mobile retargeting DSP|
