# CanAir.io Air quality Reporter 


<a href="https://itunes.apple.com/us/app/" target="_blank"><img src="https://github.com/leo0307vb/ios-hpma115s0/blob/master/assets/appstore/appstoreicon.png" align="right" width="128" ></a>


[CanAirIO](http://canair.io) is a citizen science initiative for air quality tracking, visualization and dissemination by using PM2.5 particulate material sensors paired with your smartphone via bluetooth.

This code is for [CanAir.io](http://canair.io) iOS client and reporter for [esp32-hpma115s0](https://github.com/kike-canaries/esp32-hpma115s0) pollution sensor.


---
<a href="https://github.com/leo0307vb/ios-hpma115s0/blob/master/screenshots/main.jpg"><img src="https://github.com/leo0307vb/ios-hpma115s0/blob/master/screenshots/main.jpg" align="right" width="512" ></a>
---

## TODO

- [ ] BLE scanning and connecting 
- [ ] BLE auto connect and reconnect
- [ ] Receive data via BLE notification
- [ ] Basic chart for PM 2.5 data
- [ ] BLE persist connection on background service
- [ ] Recoding data in the phone
- [ ] List recorded tracks fragment
- [ ] Open Street map fragment
- [ ] Connect list records to record track
- [ ] Connect Open Street Maps to pollution data
- [ ] Firebase connection for publish reports
- [ ] Osmdroid clusters (for static points)
- [ ] Osmdroid routes (for line or dinamic points)
- [ ] Export data to json or others

## Dependencies

- Swift 4.2
- Cocoapods
- Fastlane

## Compiling

```bash
git clone https://github.com/leo0307vb/ios-hpma115s0.git
cd ios-hpma115s0.git
```

## Credits

<div>Icons made by <a href="https://www.flaticon.com/authors/prosymbols" title="Prosymbols">Prosymbols</a> from <a href="https://www.flaticon.com/" title="Flaticon">www.flaticon.com</a> is licensed by <a href="http://creativecommons.org/licenses/by/3.0/" title="Creative Commons BY 3.0" target="_blank">CC 3.0 BY</a></div>