# Obsidian Modal Form Plugin - Reloaded
A fork of danielo515's [Obsidian Modal Form Plugin](https://github.com/danielo515/obsidian-modal-form) that aims to fix a couple of bugs and implements quality-of-life functionality to make making forms a little more buttery than they already are.

As of 14 February 2026, I'm not changing anything major. The functionality is just about the same. As such, **go read the original documentation if you want to know how to use it.**

(P.S. Danielo, I am so sorry, I am not primarily an FP, so my solutions may be a little barbaric. Thank you for the incredible groundwork!)

## Notable bugs fixed
- Fixed a bug where fields which were made visible and then made invisible will still push data when the form is submitted.

## Other fixes I'm working on
- Allow user to turn *any* field required, not just numbers and strings.
- Allow user to push "ghost" data using hidden fields.

## Pipe dreams
- Develop an API to allow users to create forms programatically.

## Installation
### The BRAT method
Install [BRAT](https://github.com/TfTHacker/obsidian42-brat) and input this repository's link when prompted.
### The Manual method
Download the latest releases from the Releases tabs and import it into your vault's `.obsidian\plugins\modalforms-reloaded`.