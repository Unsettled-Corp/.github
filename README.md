# Unsettled Corp on GitHub

Files for the fictional Unsettled Corp, for the GitHub organisation [Unsettled-Corp](https://github.com/Unsettled-Corp). Copy them as they are; nothing here is used by the app itself.

## What goes where

| Folder here | GitHub | Notes |
|---|---|---|
| `brand/` | the organisation's avatar, and `.github/profile/` | Upload `brand/logo-512.png` as the organisation's profile picture. Copy `brand/wordmark.svg` into the `.github` repo alongside the profile README. |
| `org-profile/README.md` | repo `.github`, at `profile/README.md` | GitHub shows this on the organisation's page. Put Chris's real Instagram handle in where it says TODO. |
| `facilities-handbook/` | repo `facilities-handbook` (renamed from `level-23`) | See the commit plan below. |
| `staff-directory/` | repo `staff-directory` | Avatars are generated SVGs, so no real faces. Put Chris's handle in her page. |

## Hiding 1883 in the history (level 25)

The answer is in the building's history, then redacted. Make the commits in this order:

1. **First commit:** the handbook as it is here, but with the README line reading *"Unsettled Corp has occupied the building since 1883."* Message: `Add facilities handbook`.
2. **Second commit:** replace `1883` with `[REDACTED BY IT SECURITY]`, exactly as in this folder. Message: `Remove building history (per IT Security, P. Nair)`.

Anyone who reads the current README sees the redaction; anyone who opens the history finds the year. The wordmark's *EST. MDCCCLXXXIII* is 1883 in Roman numerals, a second way in for anyone sharp enough to read it.

## Easter eggs

The handbook and staff pages are full of nods to the levels: the fitting read from the floor, the flickering safe-room bulbs, the glass door, tracking numbers, the signage only lit at night, Biscuit returned to C. Wood, Tom's desk going one further. Staff extensions are red herrings and none matches an answer. The restricted record in the staff directory (an external contractor in Paris) is Olivia, for chapter 3.
