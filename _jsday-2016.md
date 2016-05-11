# JS Day 2016 - Verona

## Physical web - @shwetank
Existing known possibilities
- Eddystone protocol
- QR Code

Existing uses
- Key finder
- Museum
- Poster
- Interactive totems

BLE devices finder [app](https://play.google.com/store/apps/details?id=no.nordicsemi.android.mcp&hl=it)

Oral-B Developer program

#### Web Bluetooth API
- User access required
- HTTPs only
- Partially implemented

GATT services

Main Javascript API object
```javascript
  navigator.bluetooth
```

Introductory article in Opera Dev center https://dev.opera.com/articles/web-bluetooth-intro/

#### Libraries
- node-eddystone-beacon

#### Missing parts
- scan RSSI and txPower
- Get EddyStone url
- Better docs by hardware maker
- Firefox is not going to implement it soon
