**[trakt_api.py](https://github.com/ReaLx3m/FLAM-Fixes/blob/main/trakt_api.py)**

Implements needed changes due to latest API change for Trakt to work again in Fen Light AM. Tested on FLAM 2.2.04.

Replace your old trakt_api.py with this one, located in Kodi\addons\plugin.video.fenlight\resources\lib\apis. 



**[request_client.py](https://github.com/ReaLx3m/FLAM-Fixes/blob/main/request_client.py)**

Fix for youtube trailers video freezing and audio stuttering. Client id has been changed as per this commit https://github.com/anxdpanic/plugin.video.youtube/pull/1482/changes/71a8d9b4b5ceb4cd352843cb050c364bf7be3463

You can download request_client.py and replace your original one located in Kodi\addons\plugin.video.youtube\resources\lib\youtube_plugin\youtube\client , or manually edit the file and copy/replace needed entries as described in the link above

And a third option, the official youtube plugin with modified request_client.py inside it(restart kodi after installing) - https://github.com/ReaLx3m/FLAM-Fixes/blob/main/plugin.video.youtube-7.4.4.zip 
