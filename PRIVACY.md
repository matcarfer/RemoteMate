# Privacy

[Español](PRIVACY.es.md) · **English**

RemoteMate **does not collect, send or share any data** with anyone.

- **No servers, no accounts, no cloud.** The phone talks only to your TV box, on your local network.
  The `INTERNET` permission is needed for that local connection; the app never contacts the internet.
- **No ads, analytics or trackers.** No third-party libraries.
- **What travels between phone and box** (encrypted): the keys you press, pointer moves, the text you
  type and the names of both devices.
- **What is stored, only on each device:** on the phone, the boxes you know (name, address, pairing
  token) and your settings; on the box, the paired phones (name and token) and its settings. The box's
  ADB key stays in the app's private folder. Uninstalling deletes everything.
- **Permissions:** network state and Wi-Fi to find boxes; vibration; on the box, start at boot,
  foreground service + notification (required to keep the receiver alive), draw over other apps (the
  pointer and the pairing code) and wake lock.
- **The phone side never runs in the background.**

Questions: open an [issue](https://github.com/matcarfer/RemoteMate/issues).
