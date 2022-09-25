# catalog-mods-db
> *What is this?*

Actual repo where the catalog fetches the assets and the `db.json` from

> *How `db.json` is structured?*

```
id: <int> - magic key index (unused)
folder: <string> - mod root folder
mod_title: <string> - name of the mod
mod_creator: <string> - chart/mod creator
mod_artist: <string> - mod original artist
song_artist: <string> - mods song artist
song_title: <string> - mods song title
length: <string MM:SS> - song's or mod length
bpm: <int> - bpm of the mod
preview_imgs: <string '[name].[extension]'> - image preview name for the mod card
thumb_img: <string '[name].[extension]'> - mods thumbnail name
release_date: <string YYYY/MM/DD> - mods original release
download_link: <url> - download link to mod, multiple links separated by comma with no spaces
tags: <string> - mod tags with no spaces commas used as a separator
```
