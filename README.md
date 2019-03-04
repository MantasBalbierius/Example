# How to change data settings of NOIA Node GUI for Windows 10

**Settings file automatically is located and generated on directory _AppData\Roaming\noia-node_ to quick locate settings file press "File folder" button on Wallet settings**

## Wallet > Wallet 
Settings are for your ethereum wallet address. You can simply copy your wallet address with ctrl+c and press button "Paste from clipboard".
On settings file is located on `airdropAddress` name. **Example:** `airdropAddress=Your ethereum wallet address`

## Settings > Node > Master address
NOIA master server address.
On settings file is located on `masterAddress` name. **Example:** `masterAddress=wss://csl-masters.noia.network:5565`

## Settings > Node > WebRTC control port and WebRTC data port
WebRTC is an open source project to enable realtime communication of audio, video and data in Web and native apps. You can check it if it is active or not by clicking on "Check port" button.
On settings file control port is located on `controlPort` name. Example: `controlPort=Port address`
On settings file data port is located on `dataPort` name. **Example:** `dataPort=Port address`

## Settings > Node > Storage directory
Storage directory is located by default on *\AppData\Roaming\noia-node\storage* but you can change it by pressing on folder icon or your storage address.
On settings file Storage directory is located on `dir` name under `[node.storage]`. **Example:** `dir=Storage directory`

## Settings > Node > Storage size
Storage size settings is to share your storage capacity.
On settings file Storage size is located on `size` name under `[node.storage]`. **Example:** `size=Storage size`

## Settings > Node > Enable NAT-PMP
The NAT Port Mapping Protocol (NAT-PMP) is a network protocol for establishing network address translation (NAT) settings and port forwarding configurations automatically without user effort.
On settings file NAT-PMP is located on `natPmp` name. **Example:** `natPmp=true`. We recommend NAT-PMP to be enabled.

## Settings > Application > Minimize to tray
Allows user to minimize application to the windows tray.
On settings file Minimize to tray is located on `minimizeToTray` name. **Example:** `minimizeToTray=true`
