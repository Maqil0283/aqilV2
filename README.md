# Wedding Scroll Invitation V2

A GitHub Pages-ready, mobile-first wedding invitation. Guests move between full-screen pages by scrolling or swiping vertically. No Open or Next button is required.

## 1. Edit wedding details from your phone

Open `config.js` on GitHub, tap the pencil icon, change the text inside quotation marks, then commit the change.

Important fields:

- Couple names: `couple`
- Parents/hosts: `invitation`
- Date, time and venue: `event`
- WhatsApp RSVP number: `rsvp.whatsapp`
- Bank details: `gift`

Use the WhatsApp number in international format without `+`, spaces or dashes. Malaysia example: `60123456789`.

## 2. Add photos

Upload images into `assets/images/` with these filenames:

- `photo-1.jpg`
- `photo-2.jpg`
- `photo-3.jpg`
- `photo-4.jpg`

To use other filenames, update the `media.photos` list in `config.js`.

## 3. Add music

Upload an MP3 into `assets/music/` and name it:

`wedding-song.mp3`

Mobile browsers require a user interaction before audio can play. Guests can tap the record or music icon.

## 4. Upload to GitHub

1. Extract this ZIP.
2. Create a public GitHub repository.
3. Upload every extracted file and folder to the repository root.
4. Commit the files.
5. Open repository Settings, then Pages.
6. Under Build and deployment, select Deploy from a branch.
7. Select `main` and `/ (root)`, then save.

## 5. Test before sharing

- Swipe through every section on Android and iPhone.
- Test the music control.
- Test Google Maps and Waze.
- Submit a test RSVP.
- Verify the countdown date and Malaysian timezone offset in `dateISO`.
- Compress each image for faster loading on mobile.

## Security note

Anything committed to a public GitHub repository is publicly visible, including bank details and phone numbers.
