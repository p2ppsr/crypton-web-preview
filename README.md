# Crypton Web preview

Open https://p2ppsr.github.io/crypton-web-preview/ inside a compatible Metanet wallet browser for wallet-backed sending and receiving.

The initial screen is To, message and Send. Paste an encrypted QR image into the textarea: the same boxes become From, QR and Receive. Hold Receive to read; release it to restore the QR. Focus the message area to return immediately to Send. The QR fits the existing textarea height without moving the button.

Wallet-backed sends place the sender’s resolved name and identity key inside the encrypted content. Names appear only after decryption and are supplied labels, not verified signatures. Old messages remain readable. Other controls are behind the gear.

This repository contains only compiled preview assets. The web app does not require TestFlight; ME identity discovery requires a compatible updated build.
