# 🍅 Pomodoro Tab

A Chrome extension that enforces focus during Pomodoro sessions
by locking your browser to the current tab.

## Install
[Available on the Chrome Web Store](https://chrome.google.com/webstore/detail/pomodoro-tab) ← update with your live link once approved

## Features
- 25-minute focus sessions with 5-minute breaks
- Hard Mode — prevents tab switching during work sessions
- Runs in the background using Chrome service workers
- Badge countdown on the toolbar icon
- Session end notifications

## How it works
Start a session on any tab. Enable Hard Mode for strict enforcement.
If you try to switch tabs during a session, you are immediately snapped
back. Pause or reset any time to regain control.

No account required. No data collected. Everything runs locally.

## Tech
- Manifest V3
- Chrome service workers
- chrome.alarms, chrome.storage, chrome.tabs, chrome.notifications
- Timestamp-based state recovery across Chrome restarts

## Local development
1. Clone this repo
2. Go to chrome://extensions
3. Enable Developer mode
4. Click Load unpacked → select this folder
