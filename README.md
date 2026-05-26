# Systems Biology Lab website v4

Upload the contents of this folder to the root of the GitHub repository:
`ykosysbiolab.github.io`

This version:
- Home page contains only the large hero image and lab introduction.
- Members and Publications are separate menu pages.
- Publications include the full list migrated from the previous Weebly website.
- Member portrait slots are included in `assets/img/members/`.

Replacing member photos:
1. Prepare square JPG/PNG photos.
2. Rename them using the same names used in the HTML, or edit `members.html`.
3. Suggested filenames:
   - prof-younhee-ko.jpg
   - dayeon-kim.jpg
   - nayoung-park.jpg
   - song-im.jpg
4. If using JPG files, update the image paths in `members.html` from `.svg` to `.jpg`.

Important:
This package intentionally does not include CNAME, so `https://ykosysbiolab.github.io` will not redirect to the old Weebly-forwarded domain during testing.
