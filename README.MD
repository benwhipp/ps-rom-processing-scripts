# Playstation 1 ROM Processing Scripts

Scripts to unzip and convert downloaded Playstation 1 ROMs into the more compressed .chd format, and create playlist files with correct formatting for use with the Anbernic RG35XX running Garlic OS. Will probably also work for other similar systems.

1. Install [chdman](https://wiki.recalbox.com/en/tutorials/utilities/rom-conversion/chdman)
```
# Ubuntu
sudo apt install mame-tools
```

2. Download the ROMS into your /Roms/PS directory on your RG35XX's memory card (no need to unzip them).

3. Run the preparation script to unzip them, convert them to .chd files, and then delete the zip archives if no longer needed.
```
prepare-ps
```

4. For any multi-disc games, run the playlist script to add all the disc files to a directory and create a .m3u file that will be used by the RG35XX instead.
```
create-ps-disc-playlist
```
