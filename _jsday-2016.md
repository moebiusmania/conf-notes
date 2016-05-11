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

## Reactive programming with cycle.js - @lucamezzalira

#### Agenda
- reactive programming
- model view intent
- cycle.js

#### Programming paradigms
- Imperative | focuses on describing how program operates
- Functional | everything is a (asyncronous) function
- Reactive

#### Reactive programming
AngularJS 2 will include cycle.js

#### RxJS
Learning curve mainly referred to the new vocabulary.

- streams | sequence of ongoing events oredered in time

#### Architecture Timeline
- MVC (80s)
- MVP (90s)
- MVVM (2005)
- DCI (2009)
- Flux (2013)
- MVI (2015)

#### Cycle.js
http://cycle.js.org/

## Out of the browser and onto the streets - @rumyra

#### Web Audio APIs
- concept of nodes
- input node
- create audio with oscillator

#### Web MIDI APIs
Music Instrument Digital Interface.

Every sound is a message.

[144,60,100]
[Message type, Note, Velocity/pressure]
