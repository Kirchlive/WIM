# WIM - TurtleWoW Fork

## Patch Notes - v1.4.0

### New Features
- **New Filter Type: Exact** – Now filters only whispers matching exact. "inv" only blocks message "inv" but still allows "can you make raid inv later"
- **Unfocus WIM Window** – Pressing Escape now removes window focus but keep text intact. This feature is optional and can be enabled under general.
- **Alt+Arrow Key Toggle** – Added option to text cursor moving. Alt modifier now can be disabled to work like in normal inputbox with arrow keys.

### Bug Fixes
- **Ingame Links** – All chat links such as items, spells, quests, etc. now insert correctly without gaps.
- **Macro Whispers** – Script- and macro-based whispers now send and display correctly in the WIM window.
- **Filter Iteration** – Fixed Lua 5.0 table iteration to now properly use `pairs()`, preventing undefined behavior.

### UI Improvements
- Reorganized General options for improved clarity and better accessibility
- Updated code formatting across all checkboxes for consistency

## Previous Changes
- Added 30s WHO cooldown (TurtleWoW limit)
- Added GM detection with Blizzard icon and `<GM>` tag
- GMs now skip WHO cooldown
- Messages now display immediately (WHO loads async)
- Removed "Block Low Level" option
- Added debug mode: `/wimdebug`

And some other minor quality of life changes.
