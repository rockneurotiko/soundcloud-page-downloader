SoundCloud Page Downloader
==========================

Download a SoundCloud user's music. All of it. Also takes care of ID3 tagging the files for you.

**Note:** Requires RoboBrowser and Mutagen packages to run. Simply do `pip install mutagen robobrowser` before installing.

**Usage Examples:**
* `python soundcloud-downloader.py http://soundcloud.com/diplo` will download all of Diplo's music into `<current directory>/soundcloud-downloader/diplo/`.

* `python soundcloud-downloader.py http://soundcloud.com/chainsawpolice` will download all of Chainsaw Police's music into `<current directory>/soundcloud-downloader/chainsawpolice/`.

* `python soundcloud-downloader.py diplo` will break the program and will not work (yet).