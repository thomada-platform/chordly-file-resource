# Chordly song files

Songs with chords for the Chordly app, in ChordPro format (`.cho`):

```
<Artist>/<Title>.cho
```

## Adding songs

Songs are copied here from the **song-scraper** tool in the folder next to this one (`Desktop\Test\song-scraper`):

```powershell
cd C:\Users\PHEARAK\Desktop\Test\song-scraper
node scripts/scrape/copy.mjs <song title, id or URL>
```

See the song-scraper README for all options. Edit the copies here, not the scraped files in `song-scraper/output/`.

## Using them in Chordly

Import a song file or this whole folder in Chordly (Import folder, or drag and drop onto the window). Chordly converts ChordPro into its own format as it copies the songs into its library. The files here are not changed.
