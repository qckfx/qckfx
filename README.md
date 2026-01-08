# qckfx

The personal QA for iOS developers. Record your manual testing sessions in the simulator and replay them to catch visual regressions, crashes, or hangs.

No code changes, SDKs, or test code required.

## Install

```bash
brew install --cask qckfx/tap/qckfx
open -a qckfx
```

Or download the latest release from the [Releases](https://github.com/qckfx/qckfx/releases) page.

## How to use

1. **Launch qckfx** - Look for the `q` icon in your menu bar
2. **Open the iOS Simulator** and launch your app - qckfx starts recording automatically
3. **Interact with your app** - Click, tap, scroll through the flows you want to test
4. **Save as a test** - Press **Cmd+Shift+S** to save your recording
5. **Run tests** - Press **Cmd+Shift+T** to open the test picker and run your saved tests

qckfx will spin up the simulator, build and install a fresh version of your app, replay the interactions, and compare screenshots to catch any visual regressions.

## How it works

- **Record** - qckfx watches your Simulator. Click, tap, scroll - it captures everything.
- **Replay** - Run the recording. It performs the same actions and compares screenshots.
- **Diff** - If something changed, you see exactly what. Accept or reject.

## Use with AI Coding Agents

qckfx includes MCP support for Claude Code and Cursor. Your agent can run tests and see exactly what changed.

To install, click the `q` menu bar icon and select **Install as MCP**. One click installs it to Claude Code or Cursor. You can uninstall from the same menu.

## Current Limitations

- macOS only
- iOS Simulator only (no physical devices)

## Learn more

Visit [qckfx.com](https://qckfx.com) for more information.
