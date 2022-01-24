# talon_accessibility

Experimental [Talon](https://talonvoice.com/) integrations using macOS accessibility APIs.

## Features

- **menu:** support for creating actions that directly run menu commands 
- **window_close:** support for closing application windows (the current one, everything but the current one, or everything -- even for apps that are not focused!)
- **window_doc:** revealing the current file/directory in Finder ("document reveal"), opening it ("document open"), or copying its path ("document copy path")

## Coming soon

- **Slack and Discord channel navigation:** Switch directly to channels with a single voice command; a list of channels in the grammar increases accuracy.
- **Window navigation using lists:** Switch between windows of the current application, or a non-focused application, by specifying a subset of the window title (a list grammar increases accuracy). Handy for switching between projects in your editor, for example.
- **Accessibility dictation:** A provider for context-aware dictation that can work instantly in supported applications, instead of doing the cursor selection dance. We can also directly insert into the text field. 
- **Accessibility _editing_:** Navigate and/or directly edit the current input field by referring to words (e.g. "select the quick brown fox"; "replace dog with cat")

## Installation

Clone alongside knausj. It doesn't have to be a recent version.
