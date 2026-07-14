# Profile photo design

## Goal

Add the same photo used on the blog's About page to the GitHub profile README.
Match the blog's rounded, left-aligned presentation without making the profile
header feel crowded.

## Asset

Create `assets/profile.png` from the blog's existing profile JPEG. Use a square
crop centered on Antonio, apply a circular alpha mask, and export enough pixels
for a sharp 160px display. Preserve the photo's appearance and remove all EXIF,
device, timestamp, and GPS metadata before committing it.

## README layout

Place the photo before the main heading with `align="left"`, a display width of
160px, and `alt="Antonio Fulgencio"`. Let the heading and introduction flow to
its right. Clear the alignment before the "Right now" section so later sections
always span the full README width.

## Verification

Confirm that the PNG has transparent corners, contains no metadata, renders at
the intended size, has useful alternative text, and does not break existing
links or badges.
