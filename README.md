# akvs site

- `index.html` is the whole site. Text, songs and links are in the block marked EDIT YOUR DETAILS HERE near the bottom.
- `photos/` holds the pictures.
- `photos.json` decides which pictures show up and how they're grouped. Each [ ... ] is one string of polaroids.

## Adding photos
1. Shrink photos to about 1600 px on the long side (squoosh.app works well), and name them simply, e.g. `beach-01.jpg`.
2. On GitHub, open the `photos` folder, click "Add file" then "Upload files", drop them in, and click "Commit changes".
3. Open `photos.json`, click the pencil icon, and add the file names to a group:
   ["beach-01.jpg", "beach-02.jpg", {"file": "beach-03.jpg", "caption": "low tide"}]
   Separate items with commas. Keep the quotes. A new group is a new [ ... ] line, with a comma after the previous one.
4. Click "Commit changes". The site updates in about a minute.

Delete the example-*.jpg files and their entries once your own photos are in.
