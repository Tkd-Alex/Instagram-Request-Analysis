# REOPEN-Application
### All request do by Instagram application AFTER **open the application**, with account already logged-in.

## reels_tray [POST]
### Request
```
https://i.instagram.com/api/v1/feed/reels_tray/
```
### Headers
```
X-Pigeon-Session-Id: 230e2261-faac-4428-945e-9e8943bd1baa
X-Pigeon-Rawclienttime: 1565945557.852
X-IG-Connection-Speed: -1kbps
X-IG-Bandwidth-Speed-KBPS: -1.000
X-IG-Bandwidth-TotalBytes-B: 0
X-IG-Bandwidth-TotalTime-MS: 0
X-IG-VP9-Capable: false
X-Bloks-Version-Id: 14f543394cf83e14784db6457e197a7e61e34fcd161891682143f74cb69a8981
X-IG-Connection-Type: WIFI
X-IG-Capabilities: 3brTvw==
X-IG-App-ID: 567067343352427
User-Agent: Instagram 103.1.0.15.119 Android (28/9; 420dpi; 1080x2034; unknown/Android; Google Pixel 3; vbox86p; vbox86; en_US; 164094540)
Accept-Language: en-US
Cookie: urlgen={\"2.32.17.241\": 30722}:1hyXeC:kpQ_FHWgzYzcPqlg46rWVhBsgj0; ig_direct_region_hint=LLA; ds_user=potatomayl; igfl=potatomayl; ds_user_id=123456789; mid=XVLRpwABAAG_kqYiZihqukSRfL9F; shbts=1565942622.665477; sessionid=123456789%3A9RVmCOVSZOVfy8%3A2; csrftoken=ap6Xt3UkFaHlx6ALQMPnwkIi9mGVJ1kB; shbid=13717; rur=FRC; is_starred_enabled=yes
Content-Type: application/x-www-form-urlencoded; charset=UTF-8
Accept-Encoding: gzip, deflate
Host: i.instagram.com
X-FB-HTTP-Engine: Liger
Content-Length: 1098
```
### Arguments encoded
```
supported_capabilities_new=%5B%7B%22name%22%3A%22SUPPORTED_SDK_VERSIONS%22%2C%22value%22%3A%2213.0%2C14.0%2C15.0%2C16.0%2C17.0%2C18.0%2C19.0%2C20.0%2C21.0%2C22.0%2C23.0%2C24.0%2C25.0%2C26.0%2C27.0%2C28.0%2C29.0%2C30.0%2C31.0%2C32.0%2C33.0%2C34.0%2C35.0%2C36.0%2C37.0%2C38.0%2C39.0%2C40.0%2C41.0%2C42.0%2C43.0%2C44.0%2C45.0%2C46.0%2C47.0%2C48.0%2C49.0%2C50.0%2C51.0%2C52.0%2C53.0%2C54.0%2C55.0%2C56.0%2C57.0%2C58.0%2C59.0%2C60.0%2C61.0%2C62.0%2C63.0%2C64.0%2C65.0%2C66.0%2C67.0%22%7D%2C%7B%22name%22%3A%22FACE_TRACKER_VERSION%22%2C%22value%22%3A%2212%22%7D%2C%7B%22name%22%3A%22COMPRESSION%22%2C%22value%22%3A%22ETC2_COMPRESSION%22%7D%2C%7B%22name%22%3A%22world_tracker%22%2C%22value%22%3A%22world_tracker_enabled%22%7D%5D&reason=cold_start&_csrftoken=ap6Xt3UkFaHlx6ALQMPnwkIi9mGVJ1kB&_uuid=ffbe7b2f-1663-43d4-847b-c3f51803637e&preloaded_reel_ids=407571611%2C2940730274%2C1437903828%2C6067490673%2C240008080%2C4663582744%2C3049947906%2C2182907585%2C9313550669&preloaded_reel_timestamp=1565873926%2C1565729344%2C1565723278%2C1565717038%2C1565709072%2C1565705283%2C1565702026%2C1565701992%2C1565700894
```
### Arguments decoded
```
supported_capabilities_new=[{"name":"SUPPORTED_SDK_VERSIONS","value":"13.0,14.0,15.0,16.0,17.0,18.0,19.0,20.0,21.0,22.0,23.0,24.0,25.0,26.0,27.0,28.0,29.0,30.0,31.0,32.0,33.0,34.0,35.0,36.0,37.0,38.0,39.0,40.0,41.0,42.0,43.0,44.0,45.0,46.0,47.0,48.0,49.0,50.0,51.0,52.0,53.0,54.0,55.0,56.0,57.0,58.0,59.0,60.0,61.0,62.0,63.0,64.0,65.0,66.0,67.0"},{"name":"FACE_TRACKER_VERSION","value":"12"},{"name":"COMPRESSION","value":"ETC2_COMPRESSION"},{"name":"world_tracker","value":"world_tracker_enabled"}]&reason=cold_start&_csrftoken=ap6Xt3UkFaHlx6ALQMPnwkIi9mGVJ1kB&_uuid=ffbe7b2f-1663-43d4-847b-c3f51803637e&preloaded_reel_ids=407571611,2940730274,1437903828,6067490673,240008080,4663582744,3049947906,2182907585,9313550669&preloaded_reel_timestamp=1565873926,1565729344,1565723278,1565717038,1565709072,1565705283,1565702026,1565701992,1565700894
```
### CURL Command
```
curl -i -s -k  -X 'POST'

-H 'X-Pigeon-Session-Id: 230e2261-faac-4428-945e-9e8943bd1baa' -H 'X-Pigeon-Rawclienttime: 1565945557.852' -H 'X-IG-Connection-Speed: -1kbps' -H 'X-IG-Bandwidth-Speed-KBPS: -1.000' -H 'X-IG-Bandwidth-TotalBytes-B: 0' -H 'X-IG-Bandwidth-TotalTime-MS: 0' -H 'X-IG-VP9-Capable: false' -H 'X-Bloks-Version-Id: 14f543394cf83e14784db6457e197a7e61e34fcd161891682143f74cb69a8981' -H 'X-IG-Connection-Type: WIFI' -H 'X-IG-Capabilities: 3brTvw==' -H 'X-IG-App-ID: 567067343352427' -H 'User-Agent: Instagram 103.1.0.15.119 Android (28/9; 420dpi; 1080x2034; unknown/Android; Google Pixel 3; vbox86p; vbox86; en_US; 164094540)' -H 'Accept-Language: en-US' -H 'Cookie: urlgen={\\\"2.32.17.241\\\": 30722}:1hyXeC:kpQ_FHWgzYzcPqlg46rWVhBsgj0; ig_direct_region_hint=LLA; ds_user=potatomayl; igfl=potatomayl; ds_user_id=123456789; mid=XVLRpwABAAG_kqYiZihqukSRfL9F; shbts=1565942622.665477; sessionid=123456789%3A9RVmCOVSZOVfy8%3A2; csrftoken=ap6Xt3UkFaHlx6ALQMPnwkIi9mGVJ1kB; shbid=13717; rur=FRC; is_starred_enabled=yes' -H 'Content-Type: application/x-www-form-urlencoded; charset=UTF-8' -H 'Accept-Encoding: gzip, deflate' -H 'Host: i.instagram.com' -H 'X-FB-HTTP-Engine: Liger' -H 'Connection: close' -H 'Content-Length: 1098'

-b 'urlgen={\\\"2.32.17.241\\\": 30722}:1hyXeC:kpQ_FHWgzYzcPqlg46rWVhBsgj0; ig_direct_region_hint=LLA; ds_user=potatomayl; igfl=potatomayl; ds_user_id=123456789; mid=XVLRpwABAAG_kqYiZihqukSRfL9F; shbts=1565942622.665477; sessionid=123456789%3A9RVmCOVSZOVfy8%3A2; csrftoken=ap6Xt3UkFaHlx6ALQMPnwkIi9mGVJ1kB; shbid=13717; rur=FRC; is_starred_enabled=yes'

--data-binary 'supported_capabilities_new=%5B%7B%22name%22%3A%22SUPPORTED_SDK_VERSIONS%22%2C%22value%22%3A%2213.0%2C14.0%2C15.0%2C16.0%2C17.0%2C18.0%2C19.0%2C20.0%2C21.0%2C22.0%2C23.0%2C24.0%2C25.0%2C26.0%2C27.0%2C28.0%2C29.0%2C30.0%2C31.0%2C32.0%2C33.0%2C34.0%2C35.0%2C36.0%2C37.0%2C38.0%2C39.0%2C40.0%2C41.0%2C42.0%2C43.0%2C44.0%2C45.0%2C46.0%2C47.0%2C48.0%2C49.0%2C50.0%2C51.0%2C52.0%2C53.0%2C54.0%2C55.0%2C56.0%2C57.0%2C58.0%2C59.0%2C60.0%2C61.0%2C62.0%2C63.0%2C64.0%2C65.0%2C66.0%2C67.0%22%7D%2C%7B%22name%22%3A%22FACE_TRACKER_VERSION%22%2C%22value%22%3A%2212%22%7D%2C%7B%22name%22%3A%22COMPRESSION%22%2C%22value%22%3A%22ETC2_COMPRESSION%22%7D%2C%7B%22name%22%3A%22world_tracker%22%2C%22value%22%3A%22world_tracker_enabled%22%7D%5D&reason=cold_start&_csrftoken=ap6Xt3UkFaHlx6ALQMPnwkIi9mGVJ1kB&_uuid=ffbe7b2f-1663-43d4-847b-c3f51803637e&preloaded_reel_ids=407571611%2C2940730274%2C1437903828%2C6067490673%2C240008080%2C4663582744%2C3049947906%2C2182907585%2C9313550669&preloaded_reel_timestamp=1565873926%2C1565729344%2C1565723278%2C1565717038%2C1565709072%2C1565705283%2C1565702026%2C1565701992%2C1565700894'

'https://i.instagram.com/api/v1/feed/reels_tray/'
```
___
## timeline [POST/GET]
### Request
```
https://i.instagram.com/api/v1/feed/timeline/
```
### Headers
```
X-Ads-Opt-Out: 0
X-DEVICE-ID: ffbe7b2f-1663-43d4-847b-c3f51803637e
X-CM-Bandwidth-KBPS: 3887.655
X-CM-Latency: 34.296
X-Pigeon-Session-Id: 230e2261-faac-4428-945e-9e8943bd1baa
X-Pigeon-Rawclienttime: 1565945557.849
X-IG-Connection-Speed: -1kbps
X-IG-Bandwidth-Speed-KBPS: -1.000
X-IG-Bandwidth-TotalBytes-B: 0
X-IG-Bandwidth-TotalTime-MS: 0
X-IG-VP9-Capable: false
X-Bloks-Version-Id: 14f543394cf83e14784db6457e197a7e61e34fcd161891682143f74cb69a8981
X-IG-Connection-Type: WIFI
X-IG-Capabilities: 3brTvw==
X-IG-App-ID: 567067343352427
User-Agent: Instagram 103.1.0.15.119 Android (28/9; 420dpi; 1080x2034; unknown/Android; Google Pixel 3; vbox86p; vbox86; en_US; 164094540)
Accept-Language: en-US
Cookie: urlgen={\"2.32.17.241\": 30722}:1hyXeC:kpQ_FHWgzYzcPqlg46rWVhBsgj0; ig_direct_region_hint=LLA; ds_user=potatomayl; igfl=potatomayl; ds_user_id=123456789; mid=XVLRpwABAAG_kqYiZihqukSRfL9F; shbts=1565942622.665477; sessionid=123456789%3A9RVmCOVSZOVfy8%3A2; csrftoken=ap6Xt3UkFaHlx6ALQMPnwkIi9mGVJ1kB; shbid=13717; rur=FRC; is_starred_enabled=yes
Content-Type: application/x-www-form-urlencoded; charset=UTF-8
Content-Encoding: gzip
Accept-Encoding: gzip, deflate
Host: i.instagram.com
X-FB-HTTP-Engine: Liger
Content-Length: 524
```
### Arguments encoded
```
SEE feed-timeline-unpack.md
```
### Arguments decoded
```
```
### CURL Command
```
curl -i -s -k  -X 'POST'

-H 'X-Ads-Opt-Out: 0' -H 'X-DEVICE-ID: ffbe7b2f-1663-43d4-847b-c3f51803637e' -H 'X-CM-Bandwidth-KBPS: 3887.655' -H 'X-CM-Latency: 34.296' -H 'X-Pigeon-Session-Id: 230e2261-faac-4428-945e-9e8943bd1baa' -H 'X-Pigeon-Rawclienttime: 1565945557.849' -H 'X-IG-Connection-Speed: -1kbps' -H 'X-IG-Bandwidth-Speed-KBPS: -1.000' -H 'X-IG-Bandwidth-TotalBytes-B: 0' -H 'X-IG-Bandwidth-TotalTime-MS: 0' -H 'X-IG-VP9-Capable: false' -H 'X-Bloks-Version-Id: 14f543394cf83e14784db6457e197a7e61e34fcd161891682143f74cb69a8981' -H 'X-IG-Connection-Type: WIFI' -H 'X-IG-Capabilities: 3brTvw==' -H 'X-IG-App-ID: 567067343352427' -H 'User-Agent: Instagram 103.1.0.15.119 Android (28/9; 420dpi; 1080x2034; unknown/Android; Google Pixel 3; vbox86p; vbox86; en_US; 164094540)' -H 'Accept-Language: en-US' -H 'Cookie: urlgen={\\\"2.32.17.241\\\": 30722}:1hyXeC:kpQ_FHWgzYzcPqlg46rWVhBsgj0; ig_direct_region_hint=LLA; ds_user=potatomayl; igfl=potatomayl; ds_user_id=123456789; mid=XVLRpwABAAG_kqYiZihqukSRfL9F; shbts=1565942622.665477; sessionid=123456789%3A9RVmCOVSZOVfy8%3A2; csrftoken=ap6Xt3UkFaHlx6ALQMPnwkIi9mGVJ1kB; shbid=13717; rur=FRC; is_starred_enabled=yes' -H 'Content-Type: application/x-www-form-urlencoded; charset=UTF-8' -H 'Content-Encoding: gzip' -H 'Accept-Encoding: gzip, deflate' -H 'Host: i.instagram.com' -H 'X-FB-HTTP-Engine: Liger' -H 'Connection: close' -H 'Content-Length: 524'

-b 'urlgen={\\\"2.32.17.241\\\": 30722}:1hyXeC:kpQ_FHWgzYzcPqlg46rWVhBsgj0; ig_direct_region_hint=LLA; ds_user=potatomayl; igfl=potatomayl; ds_user_id=123456789; mid=XVLRpwABAAG_kqYiZihqukSRfL9F; shbts=1565942622.665477; sessionid=123456789%3A9RVmCOVSZOVfy8%3A2; csrftoken=ap6Xt3UkFaHlx6ALQMPnwkIi9mGVJ1kB; shbid=13717; rur=FRC; is_starred_enabled=yes'

--data-binary '\x1f\x8b\x08\x00\x00\x00\x00\x00\x00\x00\x95R\xc9\x8e\x1b!\x10\xfd\x1a\xf7\xad#\xf6\xe5\xd0\x87\x99\x8c\xb2)\x91\x92C\xa2\xdc\x10K1F\xee\xa1\x9d\x86\xb63\xf9\xfa\x80\xedKFs\x89\x84\x10\x14U\xf5\x1e\xaf^*\xe6\xb8B\x84\xea\xf7\x13\x1a\"@0\xa7\x04g\x93r\\\xa6\x1d\xbf\xdf\xc9\xfb\x1d!O\x10\x925)\xb4\xe3\x8e\xde\xb5\x9d`\x8c\x09\xe7\x82I\xcd\x15\xe6\x88\x13l\xa4\xd0DH\xcc%\xebi\xe4m\xdbO\xb0\x96\xb4\xe4k\x19\x16\xd7\xe0\xb5\xd9\xd1\xd7k\x18\xbd\xd1\x8aJD%\xbd>\xd7\xf4\x04\x17\xf8\x1b\xd8\x85\x00F\xb7\x1eJs\x8a\xf55\x93\xf0W\x82\xfc\xb5L\xf9\"S>\xf4\xc5\x1f\x86\xe3~\xc9\x0d-LHpO\x1d\xd7\xa3c\\\x8e\x8c[4Z\xee\xe8\x18\xbdEH\x8a\x189q\xc3\x0a\xb6,y\xf2\xcb\x1cL\xa9v\xad\xe6\"\xdc\xe0l\xad\xb0>\x9b\x19N0O\x1a\x0d\xb3-\xd5l\xb9\x00dcC\xefO\x90V\x82\x08\x8a\x08\xe5\x94\xd0\xae\x95\xa1\x185>J\x11<\xf4O\xff\xe9T\x96\x18\x0b\xd4i\xc4\x8c!4\x18_\xd6X\x97\x03\xe4\xc9\x1e\xc5\xcfJ\xbf\x1f\xde\xd9\x0f\xf3oq\xf7\xf9\xdb\x97\xaf\xf9|\xf8\x98\xf4\xd3\xfb\x1f\x9f\xf0\xe1~\xf0s\x82\\M\x81\xd2%\xef\x98\x10@*\x0db\x8c\xc8\xd9\x91\x81F\xa3\x0b\xdc\x8fBX\xa6\x80\x81b\x01\x0d\x01N\xc9_$\x88\xd1\x81t$\x8eX\x08:2\x1a\xd8\xa8\x98t\xa3\xa7\x91c\x85\xa8\xa0\x12\x86\xd4\xfc\xb2\xcd\xb3\xa9\x8bi\xb6Y\xa1t\xdb\x98m\xfb\x8fz\xbf\xb7\xebc\xca\x8f\x13\xee7[\x9e\xb3o\"\x956s\xb3\x07\x1b\xe6\xa5)\x06\xd9\xba\x19\xdaX\x86\xb5&\x13`N\xa7.\xb0\xb3\xbei\xd1\xc3\xffT\x86ek\xd9\x8d\xd0\xaf\x0dJm\xaf\xe7\xd4(\x96e\xcb\xc1\xb4y\xa1\xc1\xcd\xcb\xa1\x98\x9b\x1b\x1bt\xff.f\x913J5\xf3QQ\xc0L69\x9ch\xd3\x07\xac\xa5\x95 0P\x16}\xc0\xa2\xb9\x06\x8b6%F\xa3d\xde\x09m\x95V/\xc87\x9a\x13\xfa\x0b\xe7=\xac\xb5M\x03\x00\x00'

'https://i.instagram.com/api/v1/feed/timeline/'
```
___
## Method name [GET]
### Request
```
https://i.instagram.com/api/v1/igtv/browse_feed/?prefetch=1&banner_token=FoSFt5Cs7bbLOhbAjbPVCxpGhIW3kKzttss6yO6-iITZkMU66uCxsO_Qu8U63N-tgbSJp8c6AA%3D%3D
```
### Headers
```
X-Pigeon-Session-Id: 230e2261-faac-4428-945e-9e8943bd1baa
X-Pigeon-Rawclienttime: 1565945558.005
X-IG-Connection-Speed: -1kbps
X-IG-Bandwidth-Speed-KBPS: -1.000
X-IG-Bandwidth-TotalBytes-B: 0
X-IG-Bandwidth-TotalTime-MS: 0
X-IG-Prefetch-Request: foreground
X-IG-VP9-Capable: false
X-Bloks-Version-Id: 14f543394cf83e14784db6457e197a7e61e34fcd161891682143f74cb69a8981
X-IG-Connection-Type: WIFI
X-IG-Capabilities: 3brTvw==
X-IG-App-ID: 567067343352427
User-Agent: Instagram 103.1.0.15.119 Android (28/9; 420dpi; 1080x2034; unknown/Android; Google Pixel 3; vbox86p; vbox86; en_US; 164094540)
Accept-Language: en-US
Cookie: urlgen={\"2.32.17.241\": 30722}:1hyXeC:kpQ_FHWgzYzcPqlg46rWVhBsgj0; ig_direct_region_hint=LLA; ds_user=potatomayl; igfl=potatomayl; ds_user_id=123456789; mid=XVLRpwABAAG_kqYiZihqukSRfL9F; shbts=1565942622.665477; sessionid=123456789%3A9RVmCOVSZOVfy8%3A2; csrftoken=ap6Xt3UkFaHlx6ALQMPnwkIi9mGVJ1kB; shbid=13717; rur=FRC; is_starred_enabled=yes
Accept-Encoding: gzip, deflate
Host: i.instagram.com
X-FB-HTTP-Engine: Liger
### CURL Command
```
curl -i -s -k  -X 'GET'

-H 'X-Pigeon-Session-Id: 230e2261-faac-4428-945e-9e8943bd1baa' -H 'X-Pigeon-Rawclienttime: 1565945558.005' -H 'X-IG-Connection-Speed: -1kbps' -H 'X-IG-Bandwidth-Speed-KBPS: -1.000' -H 'X-IG-Bandwidth-TotalBytes-B: 0' -H 'X-IG-Bandwidth-TotalTime-MS: 0' -H 'X-IG-Prefetch-Request: foreground' -H 'X-IG-VP9-Capable: false' -H 'X-Bloks-Version-Id: 14f543394cf83e14784db6457e197a7e61e34fcd161891682143f74cb69a8981' -H 'X-IG-Connection-Type: WIFI' -H 'X-IG-Capabilities: 3brTvw==' -H 'X-IG-App-ID: 567067343352427' -H 'User-Agent: Instagram 103.1.0.15.119 Android (28/9; 420dpi; 1080x2034; unknown/Android; Google Pixel 3; vbox86p; vbox86; en_US; 164094540)' -H 'Accept-Language: en-US' -H 'Cookie: urlgen={\\\"2.32.17.241\\\": 30722}:1hyXeC:kpQ_FHWgzYzcPqlg46rWVhBsgj0; ig_direct_region_hint=LLA; ds_user=potatomayl; igfl=potatomayl; ds_user_id=123456789; mid=XVLRpwABAAG_kqYiZihqukSRfL9F; shbts=1565942622.665477; sessionid=123456789%3A9RVmCOVSZOVfy8%3A2; csrftoken=ap6Xt3UkFaHlx6ALQMPnwkIi9mGVJ1kB; shbid=13717; rur=FRC; is_starred_enabled=yes' -H 'Accept-Encoding: gzip, deflate' -H 'Host: i.instagram.com' -H 'X-FB-HTTP-Engine: Liger' -H 'Connection: close'

-b 'urlgen={\\\"2.32.17.241\\\": 30722}:1hyXeC:kpQ_FHWgzYzcPqlg46rWVhBsgj0; ig_direct_region_hint=LLA; ds_user=potatomayl; igfl=potatomayl; ds_user_id=123456789; mid=XVLRpwABAAG_kqYiZihqukSRfL9F; shbts=1565942622.665477; sessionid=123456789%3A9RVmCOVSZOVfy8%3A2; csrftoken=ap6Xt3UkFaHlx6ALQMPnwkIi9mGVJ1kB; shbid=13717; rur=FRC; is_starred_enabled=yes'

'https://i.instagram.com/api/v1/igtv/browse_feed/?prefetch=1&banner_token=FoSFt5Cs7bbLOhbAjbPVCxpGhIW3kKzttss6yO6-iITZkMU66uCxsO_Qu8U63N-tgbSJp8c6AA%3D%3D'
```
___
## Method name [POST]
### Request encoded
```
https://i.instagram.com/api/v1/banyan/banyan/?views=%5B%22story_share_sheet%22%2C%22threads_people_picker%22%2C%22reshare_share_sheet%22%5D
```
### Request decoded
```
https://i.instagram.com/api/v1/banyan/banyan/?views=["story_share_sheet","threads_people_picker","reshare_share_sheet"]
```
### Headers
```
X-Pigeon-Session-Id: 230e2261-faac-4428-945e-9e8943bd1baa
X-Pigeon-Rawclienttime: 1565945559.360
X-IG-Connection-Speed: -1kbps
X-IG-Bandwidth-Speed-KBPS: -1.000
X-IG-Bandwidth-TotalBytes-B: 0
X-IG-Bandwidth-TotalTime-MS: 0
X-IG-VP9-Capable: false
X-Bloks-Version-Id: 14f543394cf83e14784db6457e197a7e61e34fcd161891682143f74cb69a8981
X-IG-Connection-Type: WIFI
X-IG-Capabilities: 3brTvw==
X-IG-App-ID: 567067343352427
User-Agent: Instagram 103.1.0.15.119 Android (28/9; 420dpi; 1080x2034; unknown/Android; Google Pixel 3; vbox86p; vbox86; en_US; 164094540)
Accept-Language: en-US
Cookie: urlgen={\"2.32.17.241\": 30722}:1hyXyS:8QkWW7iIxZ1oxJgkZ4eEOCzn76o; ig_direct_region_hint=LLA; ds_user=potatomayl; igfl=potatomayl; ds_user_id=123456789; mid=XVLRpwABAAG_kqYiZihqukSRfL9F; shbts=1565942622.665477; sessionid=123456789%3A9RVmCOVSZOVfy8%3A2; csrftoken=ap6Xt3UkFaHlx6ALQMPnwkIi9mGVJ1kB; shbid=13717; rur=FRC; is_starred_enabled=yes
Accept-Encoding: gzip, deflate
Host: i.instagram.com
X-FB-HTTP-Engine: Liger
### CURL Command
```
curl -i -s -k  -X 'GET'

-H 'X-Pigeon-Session-Id: 230e2261-faac-4428-945e-9e8943bd1baa' -H 'X-Pigeon-Rawclienttime: 1565945559.360' -H 'X-IG-Connection-Speed: -1kbps' -H 'X-IG-Bandwidth-Speed-KBPS: -1.000' -H 'X-IG-Bandwidth-TotalBytes-B: 0' -H 'X-IG-Bandwidth-TotalTime-MS: 0' -H 'X-IG-VP9-Capable: false' -H 'X-Bloks-Version-Id: 14f543394cf83e14784db6457e197a7e61e34fcd161891682143f74cb69a8981' -H 'X-IG-Connection-Type: WIFI' -H 'X-IG-Capabilities: 3brTvw==' -H 'X-IG-App-ID: 567067343352427' -H 'User-Agent: Instagram 103.1.0.15.119 Android (28/9; 420dpi; 1080x2034; unknown/Android; Google Pixel 3; vbox86p; vbox86; en_US; 164094540)' -H 'Accept-Language: en-US' -H 'Cookie: urlgen={\\\"2.32.17.241\\\": 30722}:1hyXyS:8QkWW7iIxZ1oxJgkZ4eEOCzn76o; ig_direct_region_hint=LLA; ds_user=potatomayl; igfl=potatomayl; ds_user_id=123456789; mid=XVLRpwABAAG_kqYiZihqukSRfL9F; shbts=1565942622.665477; sessionid=123456789%3A9RVmCOVSZOVfy8%3A2; csrftoken=ap6Xt3UkFaHlx6ALQMPnwkIi9mGVJ1kB; shbid=13717; rur=FRC; is_starred_enabled=yes' -H 'Accept-Encoding: gzip, deflate' -H 'Host: i.instagram.com' -H 'X-FB-HTTP-Engine: Liger' -H 'Connection: close'

-b 'urlgen={\\\"2.32.17.241\\\": 30722}:1hyXyS:8QkWW7iIxZ1oxJgkZ4eEOCzn76o; ig_direct_region_hint=LLA; ds_user=potatomayl; igfl=potatomayl; ds_user_id=123456789; mid=XVLRpwABAAG_kqYiZihqukSRfL9F; shbts=1565942622.665477; sessionid=123456789%3A9RVmCOVSZOVfy8%3A2; csrftoken=ap6Xt3UkFaHlx6ALQMPnwkIi9mGVJ1kB; shbid=13717; rur=FRC; is_starred_enabled=yes'

'https://i.instagram.com/api/v1/banyan/banyan/?views=%5B%22story_share_sheet%22%2C%22threads_people_picker%22%2C%22reshare_share_sheet%22%5D'
```
___
## topical_explore [GET]
### Request
```
https://i.instagram.com/api/v1/discover/topical_explore/?is_prefetch=true&omit_cover_media=true&use_sectional_payload=true&timezone_offset=-14400&session_id=2e8331db-5fd0-4073-af1c-c86df43dfeba&include_fixed_destinations=true
```
### Headers
```
X-Pigeon-Session-Id: 230e2261-faac-4428-945e-9e8943bd1baa
X-Pigeon-Rawclienttime: 1565945561.176
X-IG-Connection-Speed: -1kbps
X-IG-Bandwidth-Speed-KBPS: -1.000
X-IG-Bandwidth-TotalBytes-B: 0
X-IG-Bandwidth-TotalTime-MS: 0
X-IG-Prefetch-Request: foreground
X-IG-VP9-Capable: false
X-Bloks-Version-Id: 14f543394cf83e14784db6457e197a7e61e34fcd161891682143f74cb69a8981
X-IG-Connection-Type: WIFI
X-IG-Capabilities: 3brTvw==
X-IG-App-ID: 567067343352427
User-Agent: Instagram 103.1.0.15.119 Android (28/9; 420dpi; 1080x2034; unknown/Android; Google Pixel 3; vbox86p; vbox86; en_US; 164094540)
Accept-Language: en-US
Cookie: urlgen={\"2.32.17.241\": 30722}:1hyXyV:b6cCMRr_ThXcPHcGeNbEHpNOV6Q; ig_direct_region_hint=LLA; ds_user=potatomayl; igfl=potatomayl; ds_user_id=123456789; mid=XVLRpwABAAG_kqYiZihqukSRfL9F; shbts=1565942622.665477; sessionid=123456789%3A9RVmCOVSZOVfy8%3A2; csrftoken=ap6Xt3UkFaHlx6ALQMPnwkIi9mGVJ1kB; shbid=13717; rur=FRC; is_starred_enabled=yes
Accept-Encoding: gzip, deflate
Host: i.instagram.com
X-FB-HTTP-Engine: Liger
### CURL Command
```
curl -i -s -k  -X 'GET'

-H 'X-Pigeon-Session-Id: 230e2261-faac-4428-945e-9e8943bd1baa' -H 'X-Pigeon-Rawclienttime: 1565945561.176' -H 'X-IG-Connection-Speed: -1kbps' -H 'X-IG-Bandwidth-Speed-KBPS: -1.000' -H 'X-IG-Bandwidth-TotalBytes-B: 0' -H 'X-IG-Bandwidth-TotalTime-MS: 0' -H 'X-IG-Prefetch-Request: foreground' -H 'X-IG-VP9-Capable: false' -H 'X-Bloks-Version-Id: 14f543394cf83e14784db6457e197a7e61e34fcd161891682143f74cb69a8981' -H 'X-IG-Connection-Type: WIFI' -H 'X-IG-Capabilities: 3brTvw==' -H 'X-IG-App-ID: 567067343352427' -H 'User-Agent: Instagram 103.1.0.15.119 Android (28/9; 420dpi; 1080x2034; unknown/Android; Google Pixel 3; vbox86p; vbox86; en_US; 164094540)' -H 'Accept-Language: en-US' -H 'Cookie: urlgen={\\\"2.32.17.241\\\": 30722}:1hyXyV:b6cCMRr_ThXcPHcGeNbEHpNOV6Q; ig_direct_region_hint=LLA; ds_user=potatomayl; igfl=potatomayl; ds_user_id=123456789; mid=XVLRpwABAAG_kqYiZihqukSRfL9F; shbts=1565942622.665477; sessionid=123456789%3A9RVmCOVSZOVfy8%3A2; csrftoken=ap6Xt3UkFaHlx6ALQMPnwkIi9mGVJ1kB; shbid=13717; rur=FRC; is_starred_enabled=yes' -H 'Accept-Encoding: gzip, deflate' -H 'Host: i.instagram.com' -H 'X-FB-HTTP-Engine: Liger' -H 'Connection: close'

-b 'urlgen={\\\"2.32.17.241\\\": 30722}:1hyXyV:b6cCMRr_ThXcPHcGeNbEHpNOV6Q; ig_direct_region_hint=LLA; ds_user=potatomayl; igfl=potatomayl; ds_user_id=123456789; mid=XVLRpwABAAG_kqYiZihqukSRfL9F; shbts=1565942622.665477; sessionid=123456789%3A9RVmCOVSZOVfy8%3A2; csrftoken=ap6Xt3UkFaHlx6ALQMPnwkIi9mGVJ1kB; shbid=13717; rur=FRC; is_starred_enabled=yes'

'https://i.instagram.com/api/v1/discover/topical_explore/?is_prefetch=true&omit_cover_media=true&use_sectional_payload=true&timezone_offset=-14400&session_id=2e8331db-5fd0-4073-af1c-c86df43dfeba&include_fixed_destinations=true'
```
___
## info [GET]
### Request
```
https://i.instagram.com/api/v1/users/123456789/info/
```
### Headers
```
X-Pigeon-Session-Id: 230e2261-faac-4428-945e-9e8943bd1baa
X-Pigeon-Rawclienttime: 1565945561.476
X-IG-Connection-Speed: 1646kbps
X-IG-Bandwidth-Speed-KBPS: 3783.802
X-IG-Bandwidth-TotalBytes-B: 457840
X-IG-Bandwidth-TotalTime-MS: 121
X-IG-VP9-Capable: false
X-Bloks-Version-Id: 14f543394cf83e14784db6457e197a7e61e34fcd161891682143f74cb69a8981
X-IG-Connection-Type: WIFI
X-IG-Capabilities: 3brTvw==
X-IG-App-ID: 567067343352427
User-Agent: Instagram 103.1.0.15.119 Android (28/9; 420dpi; 1080x2034; unknown/Android; Google Pixel 3; vbox86p; vbox86; en_US; 164094540)
Accept-Language: en-US
Cookie: urlgen={\"2.32.17.241\": 30722}:1hyXyV:b6cCMRr_ThXcPHcGeNbEHpNOV6Q; ig_direct_region_hint=LLA; ds_user=potatomayl; igfl=potatomayl; ds_user_id=123456789; mid=XVLRpwABAAG_kqYiZihqukSRfL9F; shbts=1565942622.665477; sessionid=123456789%3A9RVmCOVSZOVfy8%3A2; csrftoken=ap6Xt3UkFaHlx6ALQMPnwkIi9mGVJ1kB; shbid=13717; rur=FRC; is_starred_enabled=yes
Accept-Encoding: gzip, deflate
Host: i.instagram.com
X-FB-HTTP-Engine: Liger
### CURL Command
```
curl -i -s -k  -X 'GET'

-H 'X-Pigeon-Session-Id: 230e2261-faac-4428-945e-9e8943bd1baa' -H 'X-Pigeon-Rawclienttime: 1565945561.476' -H 'X-IG-Connection-Speed: 1646kbps' -H 'X-IG-Bandwidth-Speed-KBPS: 3783.802' -H 'X-IG-Bandwidth-TotalBytes-B: 457840' -H 'X-IG-Bandwidth-TotalTime-MS: 121' -H 'X-IG-VP9-Capable: false' -H 'X-Bloks-Version-Id: 14f543394cf83e14784db6457e197a7e61e34fcd161891682143f74cb69a8981' -H 'X-IG-Connection-Type: WIFI' -H 'X-IG-Capabilities: 3brTvw==' -H 'X-IG-App-ID: 567067343352427' -H 'User-Agent: Instagram 103.1.0.15.119 Android (28/9; 420dpi; 1080x2034; unknown/Android; Google Pixel 3; vbox86p; vbox86; en_US; 164094540)' -H 'Accept-Language: en-US' -H 'Cookie: urlgen={\\\"2.32.17.241\\\": 30722}:1hyXyV:b6cCMRr_ThXcPHcGeNbEHpNOV6Q; ig_direct_region_hint=LLA; ds_user=potatomayl; igfl=potatomayl; ds_user_id=123456789; mid=XVLRpwABAAG_kqYiZihqukSRfL9F; shbts=1565942622.665477; sessionid=123456789%3A9RVmCOVSZOVfy8%3A2; csrftoken=ap6Xt3UkFaHlx6ALQMPnwkIi9mGVJ1kB; shbid=13717; rur=FRC; is_starred_enabled=yes' -H 'Accept-Encoding: gzip, deflate' -H 'Host: i.instagram.com' -H 'X-FB-HTTP-Engine: Liger' -H 'Connection: close'

-b 'urlgen={\\\"2.32.17.241\\\": 30722}:1hyXyV:b6cCMRr_ThXcPHcGeNbEHpNOV6Q; ig_direct_region_hint=LLA; ds_user=potatomayl; igfl=potatomayl; ds_user_id=123456789; mid=XVLRpwABAAG_kqYiZihqukSRfL9F; shbts=1565942622.665477; sessionid=123456789%3A9RVmCOVSZOVfy8%3A2; csrftoken=ap6Xt3UkFaHlx6ALQMPnwkIi9mGVJ1kB; shbid=13717; rur=FRC; is_starred_enabled=yes'

'https://i.instagram.com/api/v1/users/123456789/info/'
```
___
## inbox [GET]
### Request
```
https://i.instagram.com/api/v1/news/inbox/
```
### Headers
```
X-Pigeon-Session-Id: 230e2261-faac-4428-945e-9e8943bd1baa
X-Pigeon-Rawclienttime: 1565945561.476
X-IG-Connection-Speed: 1646kbps
X-IG-Bandwidth-Speed-KBPS: 3783.802
X-IG-Bandwidth-TotalBytes-B: 457840
X-IG-Bandwidth-TotalTime-MS: 121
X-IG-Prefetch-Request: foreground
X-IG-VP9-Capable: false
X-Bloks-Version-Id: 14f543394cf83e14784db6457e197a7e61e34fcd161891682143f74cb69a8981
X-IG-Connection-Type: WIFI
X-IG-Capabilities: 3brTvw==
X-IG-App-ID: 567067343352427
User-Agent: Instagram 103.1.0.15.119 Android (28/9; 420dpi; 1080x2034; unknown/Android; Google Pixel 3; vbox86p; vbox86; en_US; 164094540)
Accept-Language: en-US
Cookie: urlgen={\"2.32.17.241\": 30722}:1hyXyV:b6cCMRr_ThXcPHcGeNbEHpNOV6Q; ig_direct_region_hint=LLA; ds_user=potatomayl; igfl=potatomayl; ds_user_id=123456789; mid=XVLRpwABAAG_kqYiZihqukSRfL9F; shbts=1565942622.665477; sessionid=123456789%3A9RVmCOVSZOVfy8%3A2; csrftoken=ap6Xt3UkFaHlx6ALQMPnwkIi9mGVJ1kB; shbid=13717; rur=FRC; is_starred_enabled=yes
Accept-Encoding: gzip, deflate
Host: i.instagram.com
X-FB-HTTP-Engine: Liger
### CURL Command
```
curl -i -s -k  -X 'GET'

-H 'X-Pigeon-Session-Id: 230e2261-faac-4428-945e-9e8943bd1baa' -H 'X-Pigeon-Rawclienttime: 1565945561.476' -H 'X-IG-Connection-Speed: 1646kbps' -H 'X-IG-Bandwidth-Speed-KBPS: 3783.802' -H 'X-IG-Bandwidth-TotalBytes-B: 457840' -H 'X-IG-Bandwidth-TotalTime-MS: 121' -H 'X-IG-Prefetch-Request: foreground' -H 'X-IG-VP9-Capable: false' -H 'X-Bloks-Version-Id: 14f543394cf83e14784db6457e197a7e61e34fcd161891682143f74cb69a8981' -H 'X-IG-Connection-Type: WIFI' -H 'X-IG-Capabilities: 3brTvw==' -H 'X-IG-App-ID: 567067343352427' -H 'User-Agent: Instagram 103.1.0.15.119 Android (28/9; 420dpi; 1080x2034; unknown/Android; Google Pixel 3; vbox86p; vbox86; en_US; 164094540)' -H 'Accept-Language: en-US' -H 'Cookie: urlgen={\\\"2.32.17.241\\\": 30722}:1hyXyV:b6cCMRr_ThXcPHcGeNbEHpNOV6Q; ig_direct_region_hint=LLA; ds_user=potatomayl; igfl=potatomayl; ds_user_id=123456789; mid=XVLRpwABAAG_kqYiZihqukSRfL9F; shbts=1565942622.665477; sessionid=123456789%3A9RVmCOVSZOVfy8%3A2; csrftoken=ap6Xt3UkFaHlx6ALQMPnwkIi9mGVJ1kB; shbid=13717; rur=FRC; is_starred_enabled=yes' -H 'Accept-Encoding: gzip, deflate' -H 'Host: i.instagram.com' -H 'X-FB-HTTP-Engine: Liger' -H 'Connection: close'

-b 'urlgen={\\\"2.32.17.241\\\": 30722}:1hyXyV:b6cCMRr_ThXcPHcGeNbEHpNOV6Q; ig_direct_region_hint=LLA; ds_user=potatomayl; igfl=potatomayl; ds_user_id=123456789; mid=XVLRpwABAAG_kqYiZihqukSRfL9F; shbts=1565942622.665477; sessionid=123456789%3A9RVmCOVSZOVfy8%3A2; csrftoken=ap6Xt3UkFaHlx6ALQMPnwkIi9mGVJ1kB; shbid=13717; rur=FRC; is_starred_enabled=yes'

'https://i.instagram.com/api/v1/news/inbox/'
```
___
## device_capabilities/decisions [GET]
### Request
```
https://i.instagram.com/api/v1/device_capabilities/decisions/?signed_body=652ad369e0176fd2b347f3711348400fde60477f711249581813d74feba9ec2d.%7B%7D&ig_sig_key_version=4
```
### Headers
```
X-Pigeon-Session-Id: 230e2261-faac-4428-945e-9e8943bd1baa
X-Pigeon-Rawclienttime: 1565945561.486
X-IG-Connection-Speed: 1646kbps
X-IG-Bandwidth-Speed-KBPS: 3783.802
X-IG-Bandwidth-TotalBytes-B: 457840
X-IG-Bandwidth-TotalTime-MS: 121
X-IG-VP9-Capable: false
X-Bloks-Version-Id: 14f543394cf83e14784db6457e197a7e61e34fcd161891682143f74cb69a8981
X-IG-Connection-Type: WIFI
X-IG-Capabilities: 3brTvw==
X-IG-App-ID: 567067343352427
User-Agent: Instagram 103.1.0.15.119 Android (28/9; 420dpi; 1080x2034; unknown/Android; Google Pixel 3; vbox86p; vbox86; en_US; 164094540)
Accept-Language: en-US
Cookie: urlgen={\"2.32.17.241\": 30722}:1hyXyV:b6cCMRr_ThXcPHcGeNbEHpNOV6Q; ig_direct_region_hint=LLA; ds_user=potatomayl; igfl=potatomayl; ds_user_id=123456789; mid=XVLRpwABAAG_kqYiZihqukSRfL9F; shbts=1565942622.665477; sessionid=123456789%3A9RVmCOVSZOVfy8%3A2; csrftoken=ap6Xt3UkFaHlx6ALQMPnwkIi9mGVJ1kB; shbid=13717; rur=FRC; is_starred_enabled=yes
Accept-Encoding: gzip, deflate
Host: i.instagram.com
X-FB-HTTP-Engine: Liger
### CURL Command
```
curl -i -s -k  -X 'GET'

-H 'X-Pigeon-Session-Id: 230e2261-faac-4428-945e-9e8943bd1baa' -H 'X-Pigeon-Rawclienttime: 1565945561.486' -H 'X-IG-Connection-Speed: 1646kbps' -H 'X-IG-Bandwidth-Speed-KBPS: 3783.802' -H 'X-IG-Bandwidth-TotalBytes-B: 457840' -H 'X-IG-Bandwidth-TotalTime-MS: 121' -H 'X-IG-VP9-Capable: false' -H 'X-Bloks-Version-Id: 14f543394cf83e14784db6457e197a7e61e34fcd161891682143f74cb69a8981' -H 'X-IG-Connection-Type: WIFI' -H 'X-IG-Capabilities: 3brTvw==' -H 'X-IG-App-ID: 567067343352427' -H 'User-Agent: Instagram 103.1.0.15.119 Android (28/9; 420dpi; 1080x2034; unknown/Android; Google Pixel 3; vbox86p; vbox86; en_US; 164094540)' -H 'Accept-Language: en-US' -H 'Cookie: urlgen={\\\"2.32.17.241\\\": 30722}:1hyXyV:b6cCMRr_ThXcPHcGeNbEHpNOV6Q; ig_direct_region_hint=LLA; ds_user=potatomayl; igfl=potatomayl; ds_user_id=123456789; mid=XVLRpwABAAG_kqYiZihqukSRfL9F; shbts=1565942622.665477; sessionid=123456789%3A9RVmCOVSZOVfy8%3A2; csrftoken=ap6Xt3UkFaHlx6ALQMPnwkIi9mGVJ1kB; shbid=13717; rur=FRC; is_starred_enabled=yes' -H 'Accept-Encoding: gzip, deflate' -H 'Host: i.instagram.com' -H 'X-FB-HTTP-Engine: Liger' -H 'Connection: close'

-b 'urlgen={\\\"2.32.17.241\\\": 30722}:1hyXyV:b6cCMRr_ThXcPHcGeNbEHpNOV6Q; ig_direct_region_hint=LLA; ds_user=potatomayl; igfl=potatomayl; ds_user_id=123456789; mid=XVLRpwABAAG_kqYiZihqukSRfL9F; shbts=1565942622.665477; sessionid=123456789%3A9RVmCOVSZOVfy8%3A2; csrftoken=ap6Xt3UkFaHlx6ALQMPnwkIi9mGVJ1kB; shbid=13717; rur=FRC; is_starred_enabled=yes'

'https://i.instagram.com/api/v1/device_capabilities/decisions/?signed_body=652ad369e0176fd2b347f3711348400fde60477f711249581813d74feba9ec2d.%7B%7D&ig_sig_key_version=4'
```
___
## arlink_download_info [GET]
### Request
```
https://i.instagram.com/api/v1/users/arlink_download_info/?version_override=2.2.1
```
### Headers
```
X-Pigeon-Session-Id: 230e2261-faac-4428-945e-9e8943bd1baa
X-Pigeon-Rawclienttime: 1565945561.707
X-IG-Connection-Speed: 1646kbps
X-IG-Bandwidth-Speed-KBPS: 3783.802
X-IG-Bandwidth-TotalBytes-B: 457840
X-IG-Bandwidth-TotalTime-MS: 121
X-IG-VP9-Capable: false
X-Bloks-Version-Id: 14f543394cf83e14784db6457e197a7e61e34fcd161891682143f74cb69a8981
X-IG-Connection-Type: WIFI
X-IG-Capabilities: 3brTvw==
X-IG-App-ID: 567067343352427
User-Agent: Instagram 103.1.0.15.119 Android (28/9; 420dpi; 1080x2034; unknown/Android; Google Pixel 3; vbox86p; vbox86; en_US; 164094540)
Accept-Language: en-US
Cookie: urlgen={\"2.32.17.241\": 30722}:1hyXyV:b6cCMRr_ThXcPHcGeNbEHpNOV6Q; ig_direct_region_hint=LLA; ds_user=potatomayl; igfl=potatomayl; ds_user_id=123456789; mid=XVLRpwABAAG_kqYiZihqukSRfL9F; shbts=1565942622.665477; sessionid=123456789%3A9RVmCOVSZOVfy8%3A2; csrftoken=ap6Xt3UkFaHlx6ALQMPnwkIi9mGVJ1kB; shbid=13717; rur=FRC; is_starred_enabled=yes
Accept-Encoding: gzip, deflate
Host: i.instagram.com
X-FB-HTTP-Engine: Liger
### CURL Command
```
curl -i -s -k  -X 'GET'

-H 'X-Pigeon-Session-Id: 230e2261-faac-4428-945e-9e8943bd1baa' -H 'X-Pigeon-Rawclienttime: 1565945561.707' -H 'X-IG-Connection-Speed: 1646kbps' -H 'X-IG-Bandwidth-Speed-KBPS: 3783.802' -H 'X-IG-Bandwidth-TotalBytes-B: 457840' -H 'X-IG-Bandwidth-TotalTime-MS: 121' -H 'X-IG-VP9-Capable: false' -H 'X-Bloks-Version-Id: 14f543394cf83e14784db6457e197a7e61e34fcd161891682143f74cb69a8981' -H 'X-IG-Connection-Type: WIFI' -H 'X-IG-Capabilities: 3brTvw==' -H 'X-IG-App-ID: 567067343352427' -H 'User-Agent: Instagram 103.1.0.15.119 Android (28/9; 420dpi; 1080x2034; unknown/Android; Google Pixel 3; vbox86p; vbox86; en_US; 164094540)' -H 'Accept-Language: en-US' -H 'Cookie: urlgen={\\\"2.32.17.241\\\": 30722}:1hyXyV:b6cCMRr_ThXcPHcGeNbEHpNOV6Q; ig_direct_region_hint=LLA; ds_user=potatomayl; igfl=potatomayl; ds_user_id=123456789; mid=XVLRpwABAAG_kqYiZihqukSRfL9F; shbts=1565942622.665477; sessionid=123456789%3A9RVmCOVSZOVfy8%3A2; csrftoken=ap6Xt3UkFaHlx6ALQMPnwkIi9mGVJ1kB; shbid=13717; rur=FRC; is_starred_enabled=yes' -H 'Accept-Encoding: gzip, deflate' -H 'Host: i.instagram.com' -H 'X-FB-HTTP-Engine: Liger' -H 'Connection: close'

-b 'urlgen={\\\"2.32.17.241\\\": 30722}:1hyXyV:b6cCMRr_ThXcPHcGeNbEHpNOV6Q; ig_direct_region_hint=LLA; ds_user=potatomayl; igfl=potatomayl; ds_user_id=123456789; mid=XVLRpwABAAG_kqYiZihqukSRfL9F; shbts=1565942622.665477; sessionid=123456789%3A9RVmCOVSZOVfy8%3A2; csrftoken=ap6Xt3UkFaHlx6ALQMPnwkIi9mGVJ1kB; shbid=13717; rur=FRC; is_starred_enabled=yes'

'https://i.instagram.com/api/v1/users/arlink_download_info/?version_override=2.2.1'
```
___
## get_presence [GET]
### Request
```
https://i.instagram.com/api/v1/direct_v2/get_presence/
```
### Headers
```
X-Pigeon-Session-Id: 230e2261-faac-4428-945e-9e8943bd1baa
X-Pigeon-Rawclienttime: 1565945561.761
X-IG-Connection-Speed: 1646kbps
X-IG-Bandwidth-Speed-KBPS: 3783.802
X-IG-Bandwidth-TotalBytes-B: 457840
X-IG-Bandwidth-TotalTime-MS: 121
X-IG-VP9-Capable: false
X-Bloks-Version-Id: 14f543394cf83e14784db6457e197a7e61e34fcd161891682143f74cb69a8981
X-IG-Connection-Type: WIFI
X-IG-Capabilities: 3brTvw==
X-IG-App-ID: 567067343352427
User-Agent: Instagram 103.1.0.15.119 Android (28/9; 420dpi; 1080x2034; unknown/Android; Google Pixel 3; vbox86p; vbox86; en_US; 164094540)
Accept-Language: en-US
Cookie: urlgen={\"2.32.17.241\": 30722}:1hyXyV:b6cCMRr_ThXcPHcGeNbEHpNOV6Q; ig_direct_region_hint=LLA; ds_user=potatomayl; igfl=potatomayl; ds_user_id=123456789; mid=XVLRpwABAAG_kqYiZihqukSRfL9F; shbts=1565942622.665477; sessionid=123456789%3A9RVmCOVSZOVfy8%3A2; csrftoken=ap6Xt3UkFaHlx6ALQMPnwkIi9mGVJ1kB; shbid=13717; rur=FRC; is_starred_enabled=yes
Accept-Encoding: gzip, deflate
Host: i.instagram.com
X-FB-HTTP-Engine: Liger
### CURL Command
```
curl -i -s -k  -X 'GET'

-H 'X-Pigeon-Session-Id: 230e2261-faac-4428-945e-9e8943bd1baa' -H 'X-Pigeon-Rawclienttime: 1565945561.761' -H 'X-IG-Connection-Speed: 1646kbps' -H 'X-IG-Bandwidth-Speed-KBPS: 3783.802' -H 'X-IG-Bandwidth-TotalBytes-B: 457840' -H 'X-IG-Bandwidth-TotalTime-MS: 121' -H 'X-IG-VP9-Capable: false' -H 'X-Bloks-Version-Id: 14f543394cf83e14784db6457e197a7e61e34fcd161891682143f74cb69a8981' -H 'X-IG-Connection-Type: WIFI' -H 'X-IG-Capabilities: 3brTvw==' -H 'X-IG-App-ID: 567067343352427' -H 'User-Agent: Instagram 103.1.0.15.119 Android (28/9; 420dpi; 1080x2034; unknown/Android; Google Pixel 3; vbox86p; vbox86; en_US; 164094540)' -H 'Accept-Language: en-US' -H 'Cookie: urlgen={\\\"2.32.17.241\\\": 30722}:1hyXyV:b6cCMRr_ThXcPHcGeNbEHpNOV6Q; ig_direct_region_hint=LLA; ds_user=potatomayl; igfl=potatomayl; ds_user_id=123456789; mid=XVLRpwABAAG_kqYiZihqukSRfL9F; shbts=1565942622.665477; sessionid=123456789%3A9RVmCOVSZOVfy8%3A2; csrftoken=ap6Xt3UkFaHlx6ALQMPnwkIi9mGVJ1kB; shbid=13717; rur=FRC; is_starred_enabled=yes' -H 'Accept-Encoding: gzip, deflate' -H 'Host: i.instagram.com' -H 'X-FB-HTTP-Engine: Liger' -H 'Connection: close'

-b 'urlgen={\\\"2.32.17.241\\\": 30722}:1hyXyV:b6cCMRr_ThXcPHcGeNbEHpNOV6Q; ig_direct_region_hint=LLA; ds_user=potatomayl; igfl=potatomayl; ds_user_id=123456789; mid=XVLRpwABAAG_kqYiZihqukSRfL9F; shbts=1565942622.665477; sessionid=123456789%3A9RVmCOVSZOVfy8%3A2; csrftoken=ap6Xt3UkFaHlx6ALQMPnwkIi9mGVJ1kB; shbid=13717; rur=FRC; is_starred_enabled=yes'

'https://i.instagram.com/api/v1/direct_v2/get_presence/'
```
___
## direct_v2/inbox [GET]
### Request
```
https://i.instagram.com/api/v1/direct_v2/inbox/?visual_message_return_type=unseen&persistentBadging=true&limit=0
```
### Headers
```
X-Pigeon-Session-Id: 230e2261-faac-4428-945e-9e8943bd1baa
X-Pigeon-Rawclienttime: 1565945562.261
X-IG-Connection-Speed: 3252kbps
X-IG-Bandwidth-Speed-KBPS: 2482.502
X-IG-Bandwidth-TotalBytes-B: 767525
X-IG-Bandwidth-TotalTime-MS: 383
X-IG-Prefetch-Request: foreground
X-IG-VP9-Capable: false
X-Bloks-Version-Id: 14f543394cf83e14784db6457e197a7e61e34fcd161891682143f74cb69a8981
X-IG-Connection-Type: WIFI
X-IG-Capabilities: 3brTvw==
X-IG-App-ID: 567067343352427
User-Agent: Instagram 103.1.0.15.119 Android (28/9; 420dpi; 1080x2034; unknown/Android; Google Pixel 3; vbox86p; vbox86; en_US; 164094540)
Accept-Language: en-US
Cookie: urlgen={\"2.32.17.241\": 30722}:1hyXyW:cVRRlX2-_-URiZeRYayKD5bvDrk; ig_direct_region_hint=LLA; ds_user=potatomayl; igfl=potatomayl; ds_user_id=123456789; mid=XVLRpwABAAG_kqYiZihqukSRfL9F; shbts=1565942622.665477; sessionid=123456789%3A9RVmCOVSZOVfy8%3A2; csrftoken=ap6Xt3UkFaHlx6ALQMPnwkIi9mGVJ1kB; shbid=13717; rur=FRC; is_starred_enabled=yes
Accept-Encoding: gzip, deflate
Host: i.instagram.com
X-FB-HTTP-Engine: Liger
### CURL Command
```
curl -i -s -k  -X 'GET'

-H 'X-Pigeon-Session-Id: 230e2261-faac-4428-945e-9e8943bd1baa' -H 'X-Pigeon-Rawclienttime: 1565945562.261' -H 'X-IG-Connection-Speed: 3252kbps' -H 'X-IG-Bandwidth-Speed-KBPS: 2482.502' -H 'X-IG-Bandwidth-TotalBytes-B: 767525' -H 'X-IG-Bandwidth-TotalTime-MS: 383' -H 'X-IG-Prefetch-Request: foreground' -H 'X-IG-VP9-Capable: false' -H 'X-Bloks-Version-Id: 14f543394cf83e14784db6457e197a7e61e34fcd161891682143f74cb69a8981' -H 'X-IG-Connection-Type: WIFI' -H 'X-IG-Capabilities: 3brTvw==' -H 'X-IG-App-ID: 567067343352427' -H 'User-Agent: Instagram 103.1.0.15.119 Android (28/9; 420dpi; 1080x2034; unknown/Android; Google Pixel 3; vbox86p; vbox86; en_US; 164094540)' -H 'Accept-Language: en-US' -H 'Cookie: urlgen={\\\"2.32.17.241\\\": 30722}:1hyXyW:cVRRlX2-_-URiZeRYayKD5bvDrk; ig_direct_region_hint=LLA; ds_user=potatomayl; igfl=potatomayl; ds_user_id=123456789; mid=XVLRpwABAAG_kqYiZihqukSRfL9F; shbts=1565942622.665477; sessionid=123456789%3A9RVmCOVSZOVfy8%3A2; csrftoken=ap6Xt3UkFaHlx6ALQMPnwkIi9mGVJ1kB; shbid=13717; rur=FRC; is_starred_enabled=yes' -H 'Accept-Encoding: gzip, deflate' -H 'Host: i.instagram.com' -H 'X-FB-HTTP-Engine: Liger' -H 'Connection: close'

-b 'urlgen={\\\"2.32.17.241\\\": 30722}:1hyXyW:cVRRlX2-_-URiZeRYayKD5bvDrk; ig_direct_region_hint=LLA; ds_user=potatomayl; igfl=potatomayl; ds_user_id=123456789; mid=XVLRpwABAAG_kqYiZihqukSRfL9F; shbts=1565942622.665477; sessionid=123456789%3A9RVmCOVSZOVfy8%3A2; csrftoken=ap6Xt3UkFaHlx6ALQMPnwkIi9mGVJ1kB; shbid=13717; rur=FRC; is_starred_enabled=yes'

'https://i.instagram.com/api/v1/direct_v2/inbox/?visual_message_return_type=unseen&persistentBadging=true&limit=0'
```
___