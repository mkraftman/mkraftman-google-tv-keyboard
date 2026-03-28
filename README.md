# Mkraftman Google TV Keyboard

Custom HACS Lovelace card for Google TV text input via Android TV Remote.

## Features

- Keyboard icon that opens the native soft keyboard on iPad/iPhone
- Sends text via `remote.send_command` with `text:` prefix (batch input)
- Backspace sends `DEL` commands to the Android TV Remote
- Clears device text field on keyboard open
- iOS scroll drift prevention
- Tap outside to dismiss

## Installation

1. Add this repository to HACS as a custom repository
2. Install the card
3. Add to your dashboard

## Prerequisites

The Android TV Remote integration must be configured with **Enable IME** enabled for text input to work.

## Configuration

```yaml
type: custom:mkraftman-google-tv-keyboard
entity: remote.google_tv_living_room
```
