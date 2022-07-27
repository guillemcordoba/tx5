# tx4

Holochain WebRTC P2P Communication Ecosystem

- :warning: This code is new and should not yet be considered secure for production use!

[![Project](https://img.shields.io/badge/project-holochain-blue.svg?style=flat-square)](http://holochain.org/)
[![Forum](https://img.shields.io/badge/chat-forum%2eholochain%2enet-blue.svg?style=flat-square)](https://forum.holochain.org)
[![Chat](https://img.shields.io/badge/chat-chat%2eholochain%2enet-blue.svg?style=flat-square)](https://chat.holochain.org)

[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](https://opensource.org/licenses/MIT)
[![License: Apache-2.0](https://img.shields.io/badge/License-Apache%202.0-blue.svg)](https://www.apache.org/licenses/LICENSE-2.0)

## Crates Managed Within This Monorepo

- [tx4-core](crates/tx4-core) - Core types used in other tx4 crates.
- [tx4-go-pion-sys](crates/tx4-go-pion-sys) - Low level rust bindings to the go pion webrtc library.
- [tx4-go-pion](crates/tx4-go-pion) - Higher level rust bindings to the go pion webrtc library.
- [tx4-signal-core](crates/tx4-signal-core) - Core types related to tx4-signal-srv and tx4-signal-cli.
- [tx4-signal-core](crates/tx4-signal-core) - Holochain webrtc signal server.
- [tx4-signal-core](crates/tx4-signal-core) - Holochain webrtc signal client.
- [tx4-demo](crates/tx4-demo) - Demo showing off tx4 p2p connectivity.
