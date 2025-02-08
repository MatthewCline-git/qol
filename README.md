# qol

## fast backspace

How to make shift+backspace delete 5 characters in iTerm2

Open iTerm2 Preferences (Cmd + ,)
Go to "Profiles" tab
Select "Keys" on the right
Click the "+" button under the key mappings list
In the dialog that appears:

Press Shift+Backspace in the "Keyboard Shortcut" field
Set "Action" to "Send Hex Code"
In the text field that appears, enter: 0x08 0x08 0x08 0x08 0x08

Then restart iTerm

## forward and back navigation

How to make option+f and option+b take you forward and backward one word, respectively

Open iTerm2 Preferences (Cmd + ,)
Go to "Profiles" tab
Select "Keys" on the right

Keyboard Shortcut: Option+F
Action: "Send Escape Sequence"
Value: f

and 

Keyboard Shortcut: Option+B
Action: "Send Escape Sequence"
Value: b

