Code snippets for WMSAuth Paywall hot-linking protection
=====================

WMSAuth Paywall is a feature set of WMSPanel which is the admin and reporting panel for media servers. This feature set can be applied to **Wowza Streaming Engine** (https://wmspanel.com/wowza) and **Nimble Streamer** (https://wmspanel.com/nimble). It allows restriction of your media access by:
- hot-linking re-publishing protection;
- geo-location and IP ranges;
- connections count.

Please read Paywall section of WMSPanel website for details: https://wmspanel.com/paywall

Current sample code snippets are provided for quick and seamless integration of hot-linking protection. The repository directories have the code as described below.

"CSharp" contains C# snippet

"java" contains Java snippet 

"javascript" contains NodeJS JavaScript snippet

"python" contains Python snippet

"php" contains snippets for PHP:
- jwpayer-rtmp-hls.php - code sample for JWPlayer with RTMP and HLS
- jwpayer-rtmp-hls-with-proxy.php - code sample for JWPlayer with RTMP and HLS which has IP address obtained from various headers
- rtmp-flowplayer.php - Flowplayer sample with RTMP
- basic-hls-rtmp-obfuscation.php - basic sample for HLS and RTMP with code obfuscation agains grabbers.
- basic-hls-stream-based.php - basic sample for HLS where signature includes streams name
- basic-rtsp.php - basic sample for RTSP
