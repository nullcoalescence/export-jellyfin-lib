# export-jellyfin-lib
Powershell script that iterates through a supplied list of directories and exports a list of all the files. Good for backing up TV, movies, ebooks, audiobooks, comics, music and other things viewed on Jellyfin or other media servers, in case of catostrophic harddrive destruction.

# usage
1. Clone:
```$ git clone https://github.com/nullcoalescence/export-jellyfin-lib ~/scripts```
2. Edit script and add paths to your libraries under ```$libsToExport```
3. Execute script ```./Export-JellyfinLib.ps1 -out ~/jellyfin_export.txt```