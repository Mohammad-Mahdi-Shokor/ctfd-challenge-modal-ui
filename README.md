# CTFd Challenge Modal UI Tweaks

A custom Theme Header CSS + JS snippet for CTFd using the Pixo theme.
Improves the challenge modal layout to be cleaner and more functional.

## Features
- Wider modal (1000px)
- Two-column layout: description on left, hints on right
- Hints displayed as a numbered grid with cost labels
- "Hints" title hidden if no hints exist
- Description expands to full width when no hints
- Click-to-copy button on all code blocks
- Hint confirmation modal styled with border and smaller width
- Flag input and submit button separated by a clean divider

## How to Use
1. Go to your CTFd Admin Panel
2. Navigate to **Config → Appearance → Theme → Theme Header**
3. Paste the contents of `theme-header.html` into the field
4. Click **Save**

## Notes
- Tested on CTFd v3.8.1 with the Pixo theme
- May need minor adjustments for other themes