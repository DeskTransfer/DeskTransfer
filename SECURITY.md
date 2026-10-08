# Security

If you think you have found a security problem in DeskTransfer, please report it privately and not in a public issue.

**Write to:** contact@desktransfer.app

Please include:

- what you found and how to reproduce it,
- the versions involved (Devices, About, on both the PC and the phone),
- whether it needs a linked device, the same network, or neither.

You will get an answer as soon as possible. Please give a reasonable time for a fix before telling others about it.

## How DeskTransfer is built to be safe

- Everything between the phone and the PC is encrypted. The PC makes its own certificate on first start, and the phone only talks to a PC showing that certificate.
- Linking a phone is closed until "Link a device" is pressed on the PC, stays open for five minutes, and needs a Yes on the PC with the same four-digit word on both screens.
- The PC program answers no foreign web page, and the app never contacts any server by itself.

Only the newest version receives fixes. The current version is the one on [desktransfer.app](https://desktransfer.app).
