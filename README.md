# PubNub-pong


## Details

Pong game with lobby and chat functionality.

99% Vibe coded with [Claude Code](https://code.claude.com/docs/en/overview) and some help from a [PubNub MCP Server](https://www.pubnub.com/docs/ai/pubnub-mcp-server).

PubNub is used for synchronizing the paddle movements, lobby, join & leave game events, game segmentation, chat, and score. Ball movements are all rendered locally.


## Config

Replace
```
publishKey: "pub-key-here"
subscribeKey: "sub-key-here"
```
with your pub/sub keys

Ball speed can be changed by altering
```
const BASE_SPD     = 3;
```
