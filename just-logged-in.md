# JUST-LOGGED-IN
### All request do by Instagram application AFTER **login method**.

## Login
### Request [POST]
```
https://i.instagram.com/api/v1/accounts/login/
```
### Headers
```
X-Pigeon-Session-Id: eb7165e8-c590-4729-8656-7b57e4d9cdfd
X-Pigeon-Rawclienttime: 1565942618.565
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
Cookie: mid=XVLRpwABAAG_kqYiZihqukSRfL9F; csrftoken=ZsjKxFu1AfeyYlA1KuLCQNsgEBejsZbi; rur=FTW
Content-Type: application/x-www-form-urlencoded; charset=UTF-8
Accept-Encoding: gzip, deflate
Host: i.instagram.com
X-FB-HTTP-Engine: Liger
Connection: close
Content-Length: 644
```
### Arguments encoded
```
signed_body=15185383c69edeef01b816351930399620f53f004ed08830cc77ffec6a9796c3.%7B%22country_codes%22%3A%22%5B%7B%5C%22country_code%5C%22%3A%5C%221%5C%22%2C%5C%22source%5C%22%3A%5B%5C%22default%5C%22%5D%7D%5D%22%2C%22phone_id%22%3A%22065c3b59-b457-45a0-a5b3-fca0076ff52b%22%2C%22_csrftoken%22%3A%22ZsjKxFu1AfeyYlA1KuLCQNsgEBejsZbi%22%2C%22username%22%3A%22potatomayl%22%2C%22adid%22%3A%22%22%2C%22guid%22%3A%22ffbe7b2f-1663-43d4-847b-c3f51803637e%22%2C%22device_id%22%3A%22android-3e3cde3b8e81d35%22%2C%22google_tokens%22%3A%22%5B%5D%22%2C%22password%22%3A%22ax1452d8f5v0%236619%22%2C%22login_attempt_count%22%3A%220%22%7D&ig_sig_key_version=4
```
### Arguments decoded
```
signed_body=15185383c69edeef01b816351930399620f53f004ed08830cc77ffec6a9796c3.{"country_codes":"[{\"country_code\":\"1\",\"source\":[\"default\"]}]","phone_id":"065c3b59-b457-45a0-a5b3-fca0076ff52b","_csrftoken":"ZsjKxFu1AfeyYlA1KuLCQNsgEBejsZbi","username":"potatomayl","adid":"","guid":"ffbe7b2f-1663-43d4-847b-c3f51803637e","device_id":"android-3e3cde3b8e81d35","google_tokens":"[]","password":"ax1452d8f5v0#6619","login_attempt_count":"0"}&ig_sig_key_version=4
```
### CURL Command
```
curl -i -s -k  -X 'POST'

-H 'X-Pigeon-Session-Id: eb7165e8-c590-4729-8656-7b57e4d9cdfd' -H 'X-Pigeon-Rawclienttime: 1565942618.565' -H 'X-IG-Connection-Speed: -1kbps' -H 'X-IG-Bandwidth-Speed-KBPS: -1.000' -H 'X-IG-Bandwidth-TotalBytes-B: 0' -H 'X-IG-Bandwidth-TotalTime-MS: 0' -H 'X-IG-VP9-Capable: false' -H 'X-Bloks-Version-Id: 14f543394cf83e14784db6457e197a7e61e34fcd161891682143f74cb69a8981' -H 'X-IG-Connection-Type: WIFI' -H 'X-IG-Capabilities: 3brTvw==' -H 'X-IG-App-ID: 567067343352427' -H 'User-Agent: Instagram 103.1.0.15.119 Android (28/9; 420dpi; 1080x2034; unknown/Android; Google Pixel 3; vbox86p; vbox86; en_US; 164094540)' -H 'Accept-Language: en-US' -H 'Cookie: mid=XVLRpwABAAG_kqYiZihqukSRfL9F; csrftoken=ZsjKxFu1AfeyYlA1KuLCQNsgEBejsZbi; rur=FTW' -H 'Content-Type: application/x-www-form-urlencoded; charset=UTF-8' -H 'Accept-Encoding: gzip, deflate' -H 'Host: i.instagram.com' -H 'X-FB-HTTP-Engine: Liger' -H 'Connection: close' -H 'Content-Length: 644'

-b 'mid=XVLRpwABAAG_kqYiZihqukSRfL9F; csrftoken=ZsjKxFu1AfeyYlA1KuLCQNsgEBejsZbi; rur=FTW'

--data-binary 'signed_body=15185383c69edeef01b816351930399620f53f004ed08830cc77ffec6a9796c3.%7B%22country_codes%22%3A%22%5B%7B%5C%22country_code%5C%22%3A%5C%221%5C%22%2C%5C%22source%5C%22%3A%5B%5C%22default%5C%22%5D%7D%5D%22%2C%22phone_id%22%3A%22065c3b59-b457-45a0-a5b3-fca0076ff52b%22%2C%22_csrftoken%22%3A%22ZsjKxFu1AfeyYlA1KuLCQNsgEBejsZbi%22%2C%22username%22%3A%22potatomayl%22%2C%22adid%22%3A%22%22%2C%22guid%22%3A%22ffbe7b2f-1663-43d4-847b-c3f51803637e%22%2C%22device_id%22%3A%22android-3e3cde3b8e81d35%22%2C%22google_tokens%22%3A%22%5B%5D%22%2C%22password%22%3A%22ax1452d8f5v0%236619%22%2C%22login_attempt_count%22%3A%220%22%7D&ig_sig_key_version=4'

'https://i.instagram.com/api/v1/accounts/login/'
```
___
## get_account_family
### Request [GET]
```
https://i.instagram.com/api/v1/multiple_accounts/get_account_family/
```
### Headers
```
GET /api/v1/multiple_accounts/get_account_family/ HTTP/1.1
X-Pigeon-Session-Id: 140864b2-5517-4d55-85b4-0e0401423dae
X-Pigeon-Rawclienttime: 1565942621.464
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
Cookie: urlgen={\"2.32.17.241\": 30722}:1hyXD4:bwl7H0cNDMctvSGxubSfwMeha_M; ds_user=potatomayl; ds_user_id=123456789; mid=XVLRpwABAAG_kqYiZihqukSRfL9F; shbts=1565942622.665477; sessionid=123456789%2A3CEmcOySZOVzk9%3A2; csrftoken=ap6Xt3UkFaHlx6ALQMPnwkIi9mGVJ1kB; shbid=13717; rur=FTW
Accept-Encoding: gzip, deflate
Host: i.instagram.com
X-FB-HTTP-Engine: Liger
Connection: close
```
### CURL Command
```
curl -i -s -k  -X 'GET'

-H 'X-Pigeon-Session-Id: 140864b2-5517-4d55-85b4-0e0401423dae' -H 'X-Pigeon-Rawclienttime: 1565942621.464' -H 'X-IG-Connection-Speed: -1kbps' -H 'X-IG-Bandwidth-Speed-KBPS: -1.000' -H 'X-IG-Bandwidth-TotalBytes-B: 0' -H 'X-IG-Bandwidth-TotalTime-MS: 0' -H 'X-IG-VP9-Capable: false' -H 'X-Bloks-Version-Id: 14f543394cf83e14784db6457e197a7e61e34fcd161891682143f74cb69a8981' -H 'X-IG-Connection-Type: WIFI' -H 'X-IG-Capabilities: 3brTvw==' -H 'X-IG-App-ID: 567067343352427' -H 'User-Agent: Instagram 103.1.0.15.119 Android (28/9; 420dpi; 1080x2034; unknown/Android; Google Pixel 3; vbox86p; vbox86; en_US; 164094540)' -H 'Accept-Language: en-US' -H 'Cookie: urlgen={\\\"2.32.17.241\\\": 30722}:1hyXD4:bwl7H0cNDMctvSGxubSfwMeha_M; ds_user=potatomayl; ds_user_id=123456789; mid=XVLRpwABAAG_kqYiZihqukSRfL9F; shbts=1565942622.665477; sessionid=123456789%2A3CEmcOySZOVzk9%3A2; csrftoken=ap6Xt3UkFaHlx6ALQMPnwkIi9mGVJ1kB; shbid=13717; rur=FTW' -H 'Accept-Encoding: gzip, deflate' -H 'Host: i.instagram.com' -H 'X-FB-HTTP-Engine: Liger' -H 'Connection: close'

-b 'urlgen={\\\"2.32.17.241\\\": 30722}:1hyXD4:bwl7H0cNDMctvSGxubSfwMeha_M; ds_user=potatomayl; ds_user_id=123456789; mid=XVLRpwABAAG_kqYiZihqukSRfL9F; shbts=1565942622.665477; sessionid=123456789%2A3CEmcOySZOVzk9%3A2; csrftoken=ap6Xt3UkFaHlx6ALQMPnwkIi9mGVJ1kB; shbid=13717; rur=FTW'

'https://i.instagram.com/api/v1/multiple_accounts/get_account_family/'
```
___
## igtv/browse_feed [GET]
### Request
```
https://i.instagram.com/api/v1/igtv/browse_feed/?prefetch=1&banner_token=FsjuvoiE2ZDFOhae8ZnVCxo2yO6-iITZkMU66uCxsO_Qu8U63N-tgbSJp8c6AA%3D%3D
```
### Headers
```
X-Pigeon-Session-Id: 140864b2-5517-4d55-85b4-0e0401423dae
X-Pigeon-Rawclienttime: 1565942621.769
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
Cookie: urlgen={\"2.32.17.241\": 30722}:1hyXD4:bwl7H0cNDMctvSGxubSfwMeha_M; ds_user=potatomayl; ds_user_id=123456789; mid=XVLRpwABAAG_kqYiZihqukSRfL9F; shbts=1565942622.665477; sessionid=123456789%2A3CEmcOySZOVzk9%3A2; csrftoken=ap6Xt3UkFaHlx6ALQMPnwkIi9mGVJ1kB; shbid=13717; rur=FTW
Accept-Encoding: gzip, deflate
Host: i.instagram.com
X-FB-HTTP-Engine: Liger
Connection: close
```
### CURL Command
```
curl -i -s -k  -X 'GET'

-H 'X-Pigeon-Session-Id: 140864b2-5517-4d55-85b4-0e0401423dae' -H 'X-Pigeon-Rawclienttime: 1565942621.769' -H 'X-IG-Connection-Speed: -1kbps' -H 'X-IG-Bandwidth-Speed-KBPS: -1.000' -H 'X-IG-Bandwidth-TotalBytes-B: 0' -H 'X-IG-Bandwidth-TotalTime-MS: 0' -H 'X-IG-Prefetch-Request: foreground' -H 'X-IG-VP9-Capable: false' -H 'X-Bloks-Version-Id: 14f543394cf83e14784db6457e197a7e61e34fcd161891682143f74cb69a8981' -H 'X-IG-Connection-Type: WIFI' -H 'X-IG-Capabilities: 3brTvw==' -H 'X-IG-App-ID: 567067343352427' -H 'User-Agent: Instagram 103.1.0.15.119 Android (28/9; 420dpi; 1080x2034; unknown/Android; Google Pixel 3; vbox86p; vbox86; en_US; 164094540)' -H 'Accept-Language: en-US' -H 'Cookie: urlgen={\\\"2.32.17.241\\\": 30722}:1hyXD4:bwl7H0cNDMctvSGxubSfwMeha_M; ds_user=potatomayl; ds_user_id=123456789; mid=XVLRpwABAAG_kqYiZihqukSRfL9F; shbts=1565942622.665477; sessionid=123456789%2A3CEmcOySZOVzk9%3A2; csrftoken=ap6Xt3UkFaHlx6ALQMPnwkIi9mGVJ1kB; shbid=13717; rur=FTW' -H 'Accept-Encoding: gzip, deflate' -H 'Host: i.instagram.com' -H 'X-FB-HTTP-Engine: Liger' -H 'Connection: close'

-b 'urlgen={\\\"2.32.17.241\\\": 30722}:1hyXD4:bwl7H0cNDMctvSGxubSfwMeha_M; ds_user=potatomayl; ds_user_id=123456789; mid=XVLRpwABAAG_kqYiZihqukSRfL9F; shbts=1565942622.665477; sessionid=123456789%2A3CEmcOySZOVzk9%3A2; csrftoken=ap6Xt3UkFaHlx6ALQMPnwkIi9mGVJ1kB; shbid=13717; rur=FTW'

'https://i.instagram.com/api/v1/igtv/browse_feed/?prefetch=1&banner_token=FsjuvoiE2ZDFOhae8ZnVCxo2yO6-iITZkMU66uCxsO_Qu8U63N-tgbSJp8c6AA%3D%3D'
```
___
## reels_tray [POST]
### Request
```
https://i.instagram.com/api/v1/feed/reels_tray/
```
### Headers
```
X-Pigeon-Session-Id: 140864b2-5517-4d55-85b4-0e0401423dae
X-Pigeon-Rawclienttime: 1565942621.813
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
Cookie: urlgen={\"2.32.17.241\": 30722}:1hyXD4:bwl7H0cNDMctvSGxubSfwMeha_M; ds_user=potatomayl; ds_user_id=123456789; mid=XVLRpwABAAG_kqYiZihqukSRfL9F; shbts=1565942622.665477; sessionid=123456789%2A3CEmcOySZOVzk9%3A2; csrftoken=ap6Xt3UkFaHlx6ALQMPnwkIi9mGVJ1kB; shbid=13717; rur=FTW
Content-Type: application/x-www-form-urlencoded; charset=UTF-8
Accept-Encoding: gzip, deflate
Host: i.instagram.com
X-FB-HTTP-Engine: Liger
Connection: close
Content-Length: 1073
```
### Arguments encoded
```
supported_capabilities_new=%5B%7B%22name%22%3A%22SUPPORTED_SDK_VERSIONS%22%2C%22value%22%3A%2213.0%2C14.0%2C15.0%2C16.0%2C17.0%2C18.0%2C19.0%2C20.0%2C21.0%2C22.0%2C23.0%2C24.0%2C25.0%2C26.0%2C27.0%2C28.0%2C29.0%2C30.0%2C31.0%2C32.0%2C33.0%2C34.0%2C35.0%2C36.0%2C37.0%2C38.0%2C39.0%2C40.0%2C41.0%2C42.0%2C43.0%2C44.0%2C45.0%2C46.0%2C47.0%2C48.0%2C49.0%2C50.0%2C51.0%2C52.0%2C53.0%2C54.0%2C55.0%2C56.0%2C57.0%2C58.0%2C59.0%2C60.0%2C61.0%2C62.0%2C63.0%2C64.0%2C65.0%2C66.0%2C67.0%22%7D%2C%7B%22name%22%3A%22FACE_TRACKER_VERSION%22%2C%22value%22%3A%2212%22%7D%2C%7B%22name%22%3A%22COMPRESSION%22%2C%22value%22%3A%22ETC2_COMPRESSION%22%7D%2C%7B%22name%22%3A%22world_tracker%22%2C%22value%22%3A%22world_tracker_enabled%22%7D%5D&reason=cold_start&_csrftoken=ap6Xt3UkFaHlx6ALQMPnwkIi9mGVJ1kB&_uuid=ffbe7b2f-1663-43d4-847b-c3f51803637e&preloaded_reel_ids=2940730274%2C1437903828%2C6067490673%2C240008080%2C4663582744%2C3049947906%2C2182907585%2C9313550669&preloaded_reel_timestamp=1565729344%2C1565723278%2C1565717038%2C1565709072%2C1565705283%2C1565702026%2C1565701992%2C1565700894
```
### Arguments decoded
```
supported_capabilities_new=[{"name":"SUPPORTED_SDK_VERSIONS","value":"13.0,14.0,15.0,16.0,17.0,18.0,19.0,20.0,21.0,22.0,23.0,24.0,25.0,26.0,27.0,28.0,29.0,30.0,31.0,32.0,33.0,34.0,35.0,36.0,37.0,38.0,39.0,40.0,41.0,42.0,43.0,44.0,45.0,46.0,47.0,48.0,49.0,50.0,51.0,52.0,53.0,54.0,55.0,56.0,57.0,58.0,59.0,60.0,61.0,62.0,63.0,64.0,65.0,66.0,67.0"},{"name":"FACE_TRACKER_VERSION","value":"12"},{"name":"COMPRESSION","value":"ETC2_COMPRESSION"},{"name":"world_tracker","value":"world_tracker_enabled"}]&reason=cold_start&_csrftoken=ap6Xt3UkFaHlx6ALQMPnwkIi9mGVJ1kB&_uuid=ffbe7b2f-1663-43d4-847b-c3f51803637e&preloaded_reel_ids=2940730274,1437903828,6067490673,240008080,4663582744,3049947906,2182907585,9313550669&preloaded_reel_timestamp=1565729344,1565723278,1565717038,1565709072,1565705283,1565702026,1565701992,1565700894
```
### CURL Command
```
curl -i -s -k  -X 'POST'

-H 'X-Pigeon-Session-Id: 140864b2-5517-4d55-85b4-0e0401423dae' -H 'X-Pigeon-Rawclienttime: 1565942621.813' -H 'X-IG-Connection-Speed: -1kbps' -H 'X-IG-Bandwidth-Speed-KBPS: -1.000' -H 'X-IG-Bandwidth-TotalBytes-B: 0' -H 'X-IG-Bandwidth-TotalTime-MS: 0' -H 'X-IG-VP9-Capable: false' -H 'X-Bloks-Version-Id: 14f543394cf83e14784db6457e197a7e61e34fcd161891682143f74cb69a8981' -H 'X-IG-Connection-Type: WIFI' -H 'X-IG-Capabilities: 3brTvw==' -H 'X-IG-App-ID: 567067343352427' -H 'User-Agent: Instagram 103.1.0.15.119 Android (28/9; 420dpi; 1080x2034; unknown/Android; Google Pixel 3; vbox86p; vbox86; en_US; 164094540)' -H 'Accept-Language: en-US' -H 'Cookie: urlgen={\\\"2.32.17.241\\\": 30722}:1hyXD4:bwl7H0cNDMctvSGxubSfwMeha_M; ds_user=potatomayl; ds_user_id=123456789; mid=XVLRpwABAAG_kqYiZihqukSRfL9F; shbts=1565942622.665477; sessionid=123456789%2A3CEmcOySZOVzk9%3A2; csrftoken=ap6Xt3UkFaHlx6ALQMPnwkIi9mGVJ1kB; shbid=13717; rur=FTW' -H 'Content-Type: application/x-www-form-urlencoded; charset=UTF-8' -H 'Accept-Encoding: gzip, deflate' -H 'Host: i.instagram.com' -H 'X-FB-HTTP-Engine: Liger' -H 'Connection: close' -H 'Content-Length: 1073'

-b 'urlgen={\\\"2.32.17.241\\\": 30722}:1hyXD4:bwl7H0cNDMctvSGxubSfwMeha_M; ds_user=potatomayl; ds_user_id=123456789; mid=XVLRpwABAAG_kqYiZihqukSRfL9F; shbts=1565942622.665477; sessionid=123456789%2A3CEmcOySZOVzk9%3A2; csrftoken=ap6Xt3UkFaHlx6ALQMPnwkIi9mGVJ1kB; shbid=13717; rur=FTW'

--data-binary 'supported_capabilities_new=%5B%7B%22name%22%3A%22SUPPORTED_SDK_VERSIONS%22%2C%22value%22%3A%2213.0%2C14.0%2C15.0%2C16.0%2C17.0%2C18.0%2C19.0%2C20.0%2C21.0%2C22.0%2C23.0%2C24.0%2C25.0%2C26.0%2C27.0%2C28.0%2C29.0%2C30.0%2C31.0%2C32.0%2C33.0%2C34.0%2C35.0%2C36.0%2C37.0%2C38.0%2C39.0%2C40.0%2C41.0%2C42.0%2C43.0%2C44.0%2C45.0%2C46.0%2C47.0%2C48.0%2C49.0%2C50.0%2C51.0%2C52.0%2C53.0%2C54.0%2C55.0%2C56.0%2C57.0%2C58.0%2C59.0%2C60.0%2C61.0%2C62.0%2C63.0%2C64.0%2C65.0%2C66.0%2C67.0%22%7D%2C%7B%22name%22%3A%22FACE_TRACKER_VERSION%22%2C%22value%22%3A%2212%22%7D%2C%7B%22name%22%3A%22COMPRESSION%22%2C%22value%22%3A%22ETC2_COMPRESSION%22%7D%2C%7B%22name%22%3A%22world_tracker%22%2C%22value%22%3A%22world_tracker_enabled%22%7D%5D&reason=cold_start&_csrftoken=ap6Xt3UkFaHlx6ALQMPnwkIi9mGVJ1kB&_uuid=ffbe7b2f-1663-43d4-847b-c3f51803637e&preloaded_reel_ids=2940730274%2C1437903828%2C6067490673%2C240008080%2C4663582744%2C3049947906%2C2182907585%2C9313550669&preloaded_reel_timestamp=1565729344%2C1565723278%2C1565717038%2C1565709072%2C1565705283%2C1565702026%2C1565701992%2C1565700894'

'https://i.instagram.com/api/v1/feed/reels_tray/'
```
___
## timeline [POST]
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
X-Pigeon-Session-Id: 140864b2-5517-4d55-85b4-0e0401423dae
X-Pigeon-Rawclienttime: 1565942621.823
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
Cookie: urlgen={\"2.32.17.241\": 30722}:1hyXD4:bwl7H0cNDMctvSGxubSfwMeha_M; ds_user=potatomayl; ds_user_id=123456789; mid=XVLRpwABAAG_kqYiZihqukSRfL9F; shbts=1565942622.665477; sessionid=123456789%2A3CEmcOySZOVzk9%3A2; csrftoken=ap6Xt3UkFaHlx6ALQMPnwkIi9mGVJ1kB; shbid=13717; rur=FTW
Content-Type: application/x-www-form-urlencoded; charset=UTF-8
Content-Encoding: gzip
Accept-Encoding: gzip, deflate
Host: i.instagram.com
X-FB-HTTP-Engine: Liger
Connection: close
Content-Length: 754
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

-H 'X-Ads-Opt-Out: 0' -H 'X-DEVICE-ID: ffbe7b2f-1663-43d4-847b-c3f51803637e' -H 'X-CM-Bandwidth-KBPS: 3887.655' -H 'X-CM-Latency: 34.296' -H 'X-Pigeon-Session-Id: 140864b2-5517-4d55-85b4-0e0401423dae' -H 'X-Pigeon-Rawclienttime: 1565942621.823' -H 'X-IG-Connection-Speed: -1kbps' -H 'X-IG-Bandwidth-Speed-KBPS: -1.000' -H 'X-IG-Bandwidth-TotalBytes-B: 0' -H 'X-IG-Bandwidth-TotalTime-MS: 0' -H 'X-IG-VP9-Capable: false' -H 'X-Bloks-Version-Id: 14f543394cf83e14784db6457e197a7e61e34fcd161891682143f74cb69a8981' -H 'X-IG-Connection-Type: WIFI' -H 'X-IG-Capabilities: 3brTvw==' -H 'X-IG-App-ID: 567067343352427' -H 'User-Agent: Instagram 103.1.0.15.119 Android (28/9; 420dpi; 1080x2034; unknown/Android; Google Pixel 3; vbox86p; vbox86; en_US; 164094540)' -H 'Accept-Language: en-US' -H 'Cookie: urlgen={\\\"2.32.17.241\\\": 30722}:1hyXD4:bwl7H0cNDMctvSGxubSfwMeha_M; ds_user=potatomayl; ds_user_id=123456789; mid=XVLRpwABAAG_kqYiZihqukSRfL9F; shbts=1565942622.665477; sessionid=123456789%2A3CEmcOySZOVzk9%3A2; csrftoken=ap6Xt3UkFaHlx6ALQMPnwkIi9mGVJ1kB; shbid=13717; rur=FTW' -H 'Content-Type: application/x-www-form-urlencoded; charset=UTF-8' -H 'Content-Encoding: gzip' -H 'Accept-Encoding: gzip, deflate' -H 'Host: i.instagram.com' -H 'X-FB-HTTP-Engine: Liger' -H 'Connection: close' -H 'Content-Length: 754'

-b 'urlgen={\\\"2.32.17.241\\\": 30722}:1hyXD4:bwl7H0cNDMctvSGxubSfwMeha_M; ds_user=potatomayl; ds_user_id=123456789; mid=XVLRpwABAAG_kqYiZihqukSRfL9F; shbts=1565942622.665477; sessionid=123456789%2A3CEmcOySZOVzk9%3A2; csrftoken=ap6Xt3UkFaHlx6ALQMPnwkIi9mGVJ1kB; shbid=13717; rur=FTW'

--data-binary '\x1f\x8b\x08\x00\x00\x00\x00\x00\x00\x00\xd5UM\x8f\xe36\x0c\xfd5\xf1\xcd\x0bI\xa4D\xe9\x90\xc3N\x17\xfdB\x0b\xb4\x87\x16\xbd\x09\xb2D\xed\x18\xf1\xd8S\xdb\xc9t\xfb\xeb+\x8f\'A\xc6\xc0\x02\xd9\xdd.\xd0\x1a\x81\x11?\x92\x12\x1f\x1f%\xb6\x93\x7f\x1c9\xf3\x1c\xef\xf7\xa2\xca\xcc\xc9\x9fZ~\xf2m\x9f\x87\xfdN\xdf\xed\xe8n\xa7\xd4\x03\xa76\xf86\x95\xbf;x[\xdeJ\x0a\xa7\xd1\x1a\x8b\xca9!\x95\x91\xd6;B2dP\xd0\xe2\xa6\xbe)\xef\x13\x8fS;\xf4k\x984+\xb8.\xf6\x18\xe7\x15\x16o\xc8Qy\xecj\x9d\xdb\x07~\xde\xfde\xaf\xe7\xfd\xa5X\xbf\x9ct\xab\x97\xd2+\xa0\xce\x8bj\xb1\x01\xe8\xc5CJ\xbd\xa3w\xcb\xaf\xc0\x1f\'c\xac\x96V\x08Wr\x11\x06\xc9\x93\x91\x88\xdaj\xa7?\x89\x8c|#n\xa0!\x15\xca\xd7<\xb4\xd8\xf0\xb8\x00\x17\x1eB\xdc\xc2\xa3\xc4Y\x90\x8b&\x08\xd6\xc0\xe7\x8b\xe2\x1c,\x0f\xde@\xc7lU\xb9\x00g6R\xca\xad*\xf2&U\xc0X\xd2\xa8\x8dp`\xd1\xf9\x85 (\x10\xd6B}\xb6\x17\x0f\xb2\x16Qh\xbc\xb6\x7f\x05\xd9,\xea\xd7</\x80\xdez\x9cy\x12\xdc\xd4}\x1f?J\xf5\xd9LFXc@i\xf5\x05\xa2\xfe\x17N\x9a@0\x04\xa4\xad\x94\xa8\x9d\xf0P\xe8\x91\x05\xbd\xa4\xf5\xef\x9f\xb4\xd2\x1f\xafyHmq\xd3\x9c\x17\x84\xae}\xbe\xac=\xff?\xedW\xb2\xd5ZQ\xe9>\x83\x92\xa4\x02\xe5\x8d\x00\x09\x02\x8d\xf9*\x8a\xa0\"\x12\x1bQ\xaeA}\xe5i\x8c\xdbH\xf3\x02\xae\xac\xf4\xbb\xea\xf1~\xe8\xcbni/\x8c\x8e\xd0hW7\xa8\xa9F\x1dD\x1dt\x03u\x8eA\x0829k\xd5T#\x87i\xe8\xf7q\xe8\x92\x9f\xe60\xce\xfey\xf4UM\x98g\x1e?\xf8\x8eO\xdc\xedQV\x0b\x87\xbf\x97\x95\x87\x9c\'\x9e\xf7u\x19\x07BT>Nc\x9e\x87\x03\xf7\xfb\xf0h\xfe\x98\xe1\xb7\xc3\xb7\xe1\xfb\xee/\xf3\xf6\xa7_\x7f\xfe\xa5\x7f:\xfc\xd0\xba\x87\xef~\xffQ\x1e\xee\xaa\xd8\xb5\xdc\xcf~\xe2i)\xdd\x92b\x06K\x82\x88\xeb\xc8Q\xd4\xc8\x92j\x0b\xaa\xa9\x13stMFg\x1aQ%>\xb5\xf1\x99Q\xce\x0dS\xa3r-\xcb\xc1\xaf\x11\x12\xd6\x16\xa9\xa9#\xe4eX\x81\x01\xe2\xaa-\x03\xfc\xd8u~\x1e|\x99\xe3#O\xcb\x1c\xf7\xc7\xe3\'\xc4\xc7\xfb0\xbeo\xfb\xf7{\xb9|\x85\xe9C\x1f}HS\x91\xd0\xdfsH\xdd\x10\x92\xe7>4\x1d\x97*W\xe3\xdc\xfa\xc4]{Z\xea\xd5\x84Xj\xb1\xc0\xaf\"\xd3p,\xde%\xa1?\x8f<\xcd\xc5\xfa\xd4\x96\x14\xa7\xe1\xd8\'_\xca/\xaa\xab\xa2\xa4H\x1c\x04\x84r\xd39U\x8a\x92L\xdd\xb8\xa4j\xc3.2h\x17\xc1\x85\xaa\xe9\x86\xc3\xe4_\xba\xb0\xa4\xba\x04J\xcc\x1a\x01\x1c\xc6l\x81e\xb9D05\xa6\x88\xcf\xd2Q 6\x92\x01sL\xb2\xdc\xa8\xae\\\x04\xaa\x8c\xc4L\x18\x1b\xe3\x82uvC\xb6\xd0\xda\x8b\x7f\x00\xfa\x11\xccJ\x0e\x09\x00\x00'

'https://i.instagram.com/api/v1/feed/timeline/'
```
___
## push/register [POST]
### Request
```
https://i.instagram.com/api/v1/push/register/
```
### Headers
```
X-Pigeon-Session-Id: 140864b2-5517-4d55-85b4-0e0401423dae
X-Pigeon-Rawclienttime: 1565942622.202
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
Cookie: urlgen={\"2.32.17.241\": 30722}:1hyXD5:c0Q_BtsJPmyl-HiEadWuHBeaogg; ds_user=potatomayl; ds_user_id=123456789; mid=XVLRpwABAAG_kqYiZihqukSRfL9F; shbts=1565942622.665477; sessionid=123456789%2A3CEmcOySZOVzk9%3A2; csrftoken=ap6Xt3UkFaHlx6ALQMPnwkIi9mGVJ1kB; shbid=13717; rur=FRC
Content-Type: application/x-www-form-urlencoded; charset=UTF-8
Accept-Encoding: gzip, deflate
Host: i.instagram.com
X-FB-HTTP-Engine: Liger
Connection: close
Content-Length: 507
```
### Arguments encoded
```
device_type=android_mqtt&is_main_push_channel=true&device_sub_type=2&device_token=%7B%22k%22%3A%22eyJwbiI6ImNvbS5pbnN0YWdyYW0uYW5kcm9pZCIsImRpIjoiNmI4NTdkNmItZGFkYi00YzMyLTlhZGYtYWY0MDdlMTc5MTIwIiwiYWkiOjU2NzMxMDIwMzQxNTA1MiwiY2siOiIxMDgxNjY5OTYxMDUzNDMxIn0%3D%22%2C%22v%22%3A0%2C%22t%22%3A%22fbns-b64%22%7D&_csrftoken=ap6Xt3UkFaHlx6ALQMPnwkIi9mGVJ1kB&guid=ffbe7b2f-1663-43d4-847b-c3f51803637e&_uuid=ffbe7b2f-1663-43d4-847b-c3f51803637e&users=123456789&family_device_id=065c3b59-b457-45a0-a5b3-fca0076ff52b
```
### Arguments decoded
```
device_type=android_mqtt&is_main_push_channel=true&device_sub_type=2&device_token={"k":"eyJwbiI6ImNvbS5pbnN0YWdyYW0uYW5kcm9pZCIsImRpIjoiNmI4NTdkNmItZGFkYi00YzMyLTlhZGYtYWY0MDdlMTc5MTIwIiwiYWkiOjU2NzMxMDIwMzQxNTA1MiwiY2siOiIxMDgxNjY5OTYxMDUzNDMxIn0=","v":0,"t":"fbns-b64"}&_csrftoken=ap6Xt3UkFaHlx6ALQMPnwkIi9mGVJ1kB&guid=ffbe7b2f-1663-43d4-847b-c3f51803637e&_uuid=ffbe7b2f-1663-43d4-847b-c3f51803637e&users=123456789&family_device_id=065c3b59-b457-45a0-a5b3-fca0076ff52b
```
### CURL Command
```
curl -i -s -k  -X 'POST'

-H 'X-Pigeon-Session-Id: 140864b2-5517-4d55-85b4-0e0401423dae' -H 'X-Pigeon-Rawclienttime: 1565942622.202' -H 'X-IG-Connection-Speed: -1kbps' -H 'X-IG-Bandwidth-Speed-KBPS: -1.000' -H 'X-IG-Bandwidth-TotalBytes-B: 0' -H 'X-IG-Bandwidth-TotalTime-MS: 0' -H 'X-IG-VP9-Capable: false' -H 'X-Bloks-Version-Id: 14f543394cf83e14784db6457e197a7e61e34fcd161891682143f74cb69a8981' -H 'X-IG-Connection-Type: WIFI' -H 'X-IG-Capabilities: 3brTvw==' -H 'X-IG-App-ID: 567067343352427' -H 'User-Agent: Instagram 103.1.0.15.119 Android (28/9; 420dpi; 1080x2034; unknown/Android; Google Pixel 3; vbox86p; vbox86; en_US; 164094540)' -H 'Accept-Language: en-US' -H 'Cookie: urlgen={\\\"2.32.17.241\\\": 30722}:1hyXD5:c0Q_BtsJPmyl-HiEadWuHBeaogg; ds_user=potatomayl; ds_user_id=123456789; mid=XVLRpwABAAG_kqYiZihqukSRfL9F; shbts=1565942622.665477; sessionid=123456789%2A3CEmcOySZOVzk9%3A2; csrftoken=ap6Xt3UkFaHlx6ALQMPnwkIi9mGVJ1kB; shbid=13717; rur=FRC' -H 'Content-Type: application/x-www-form-urlencoded; charset=UTF-8' -H 'Accept-Encoding: gzip, deflate' -H 'Host: i.instagram.com' -H 'X-FB-HTTP-Engine: Liger' -H 'Connection: close' -H 'Content-Length: 507'

-b 'urlgen={\\\"2.32.17.241\\\": 30722}:1hyXD5:c0Q_BtsJPmyl-HiEadWuHBeaogg; ds_user=potatomayl; ds_user_id=123456789; mid=XVLRpwABAAG_kqYiZihqukSRfL9F; shbts=1565942622.665477; sessionid=123456789%2A3CEmcOySZOVzk9%3A2; csrftoken=ap6Xt3UkFaHlx6ALQMPnwkIi9mGVJ1kB; shbid=13717; rur=FRC'

--data-binary 'device_type=android_mqtt&is_main_push_channel=true&device_sub_type=2&device_token=%7B%22k%22%3A%22eyJwbiI6ImNvbS5pbnN0YWdyYW0uYW5kcm9pZCIsImRpIjoiNmI4NTdkNmItZGFkYi00YzMyLTlhZGYtYWY0MDdlMTc5MTIwIiwiYWkiOjU2NzMxMDIwMzQxNTA1MiwiY2siOiIxMDgxNjY5OTYxMDUzNDMxIn0%3D%22%2C%22v%22%3A0%2C%22t%22%3A%22fbns-b64%22%7D&_csrftoken=ap6Xt3UkFaHlx6ALQMPnwkIi9mGVJ1kB&guid=ffbe7b2f-1663-43d4-847b-c3f51803637e&_uuid=ffbe7b2f-1663-43d4-847b-c3f51803637e&users=123456789&family_device_id=065c3b59-b457-45a0-a5b3-fca0076ff52b'

'https://i.instagram.com/api/v1/push/register/'
```
___
## banyan [GET]
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
X-Pigeon-Session-Id: 140864b2-5517-4d55-85b4-0e0401423dae
X-Pigeon-Rawclienttime: 1565942622.224
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
Cookie: urlgen={\"2.32.17.241\": 30722}:1hyXD5:c0Q_BtsJPmyl-HiEadWuHBeaogg; ds_user=potatomayl; ds_user_id=123456789; mid=XVLRpwABAAG_kqYiZihqukSRfL9F; shbts=1565942622.665477; sessionid=123456789%2A3CEmcOySZOVzk9%3A2; csrftoken=ap6Xt3UkFaHlx6ALQMPnwkIi9mGVJ1kB; shbid=13717; rur=FRC
Accept-Encoding: gzip, deflate
Host: i.instagram.com
X-FB-HTTP-Engine: Liger
Connection: close
```
### CURL Command
```
curl -i -s -k  -X 'GET'

-H 'X-Pigeon-Session-Id: 140864b2-5517-4d55-85b4-0e0401423dae' -H 'X-Pigeon-Rawclienttime: 1565942622.224' -H 'X-IG-Connection-Speed: -1kbps' -H 'X-IG-Bandwidth-Speed-KBPS: -1.000' -H 'X-IG-Bandwidth-TotalBytes-B: 0' -H 'X-IG-Bandwidth-TotalTime-MS: 0' -H 'X-IG-VP9-Capable: false' -H 'X-Bloks-Version-Id: 14f543394cf83e14784db6457e197a7e61e34fcd161891682143f74cb69a8981' -H 'X-IG-Connection-Type: WIFI' -H 'X-IG-Capabilities: 3brTvw==' -H 'X-IG-App-ID: 567067343352427' -H 'User-Agent: Instagram 103.1.0.15.119 Android (28/9; 420dpi; 1080x2034; unknown/Android; Google Pixel 3; vbox86p; vbox86; en_US; 164094540)' -H 'Accept-Language: en-US' -H 'Cookie: urlgen={\\\"2.32.17.241\\\": 30722}:1hyXD5:c0Q_BtsJPmyl-HiEadWuHBeaogg; ds_user=potatomayl; ds_user_id=123456789; mid=XVLRpwABAAG_kqYiZihqukSRfL9F; shbts=1565942622.665477; sessionid=123456789%2A3CEmcOySZOVzk9%3A2; csrftoken=ap6Xt3UkFaHlx6ALQMPnwkIi9mGVJ1kB; shbid=13717; rur=FRC' -H 'Accept-Encoding: gzip, deflate' -H 'Host: i.instagram.com' -H 'X-FB-HTTP-Engine: Liger' -H 'Connection: close'

-b 'urlgen={\\\"2.32.17.241\\\": 30722}:1hyXD5:c0Q_BtsJPmyl-HiEadWuHBeaogg; ds_user=potatomayl; ds_user_id=123456789; mid=XVLRpwABAAG_kqYiZihqukSRfL9F; shbts=1565942622.665477; sessionid=123456789%2A3CEmcOySZOVzk9%3A2; csrftoken=ap6Xt3UkFaHlx6ALQMPnwkIi9mGVJ1kB; shbid=13717; rur=FRC'

'https://i.instagram.com/api/v1/banyan/banyan/?views=%5B%22story_share_sheet%22%2C%22threads_people_picker%22%2C%22reshare_share_sheet%22%5D'
```
___
## inbox [GET]
### Request
```
https://i.instagram.com/api/v1/news/inbox/
```
### Headers
```
X-Pigeon-Session-Id: 140864b2-5517-4d55-85b4-0e0401423dae
X-Pigeon-Rawclienttime: 1565942624.809
X-IG-Connection-Speed: -1kbps
X-IG-Bandwidth-Speed-KBPS: 9486.134
X-IG-Bandwidth-TotalBytes-B: 996044
X-IG-Bandwidth-TotalTime-MS: 105
X-IG-Prefetch-Request: foreground
X-IG-VP9-Capable: false
X-Bloks-Version-Id: 14f543394cf83e14784db6457e197a7e61e34fcd161891682143f74cb69a8981
X-IG-Connection-Type: WIFI
X-IG-Capabilities: 3brTvw==
X-IG-App-ID: 567067343352427
User-Agent: Instagram 103.1.0.15.119 Android (28/9; 420dpi; 1080x2034; unknown/Android; Google Pixel 3; vbox86p; vbox86; en_US; 164094540)
Accept-Language: en-US
Cookie: urlgen={\"2.32.17.241\": 30722}:1hyXD8:CtBwsrvpw7Kf-CZYDemiflBEdHg; ds_user=potatomayl; igfl=potatomayl; ds_user_id=123456789; mid=XVLRpwABAAG_kqYiZihqukSRfL9F; shbts=1565942622.665477; sessionid=123456789%2A3CEmcOySZOVzk9%3A2; csrftoken=ap6Xt3UkFaHlx6ALQMPnwkIi9mGVJ1kB; shbid=13717; rur=FRC; is_starred_enabled=yes
Accept-Encoding: gzip, deflate
Host: i.instagram.com
X-FB-HTTP-Engine: Liger
Connection: close
```
### CURL Command
```
curl -i -s -k  -X 'GET'

-H 'X-Pigeon-Session-Id: 140864b2-5517-4d55-85b4-0e0401423dae' -H 'X-Pigeon-Rawclienttime: 1565942624.809' -H 'X-IG-Connection-Speed: -1kbps' -H 'X-IG-Bandwidth-Speed-KBPS: 9486.134' -H 'X-IG-Bandwidth-TotalBytes-B: 996044' -H 'X-IG-Bandwidth-TotalTime-MS: 105' -H 'X-IG-Prefetch-Request: foreground' -H 'X-IG-VP9-Capable: false' -H 'X-Bloks-Version-Id: 14f543394cf83e14784db6457e197a7e61e34fcd161891682143f74cb69a8981' -H 'X-IG-Connection-Type: WIFI' -H 'X-IG-Capabilities: 3brTvw==' -H 'X-IG-App-ID: 567067343352427' -H 'User-Agent: Instagram 103.1.0.15.119 Android (28/9; 420dpi; 1080x2034; unknown/Android; Google Pixel 3; vbox86p; vbox86; en_US; 164094540)' -H 'Accept-Language: en-US' -H 'Cookie: urlgen={\\\"2.32.17.241\\\": 30722}:1hyXD8:CtBwsrvpw7Kf-CZYDemiflBEdHg; ds_user=potatomayl; igfl=potatomayl; ds_user_id=123456789; mid=XVLRpwABAAG_kqYiZihqukSRfL9F; shbts=1565942622.665477; sessionid=123456789%2A3CEmcOySZOVzk9%3A2; csrftoken=ap6Xt3UkFaHlx6ALQMPnwkIi9mGVJ1kB; shbid=13717; rur=FRC; is_starred_enabled=yes' -H 'Accept-Encoding: gzip, deflate' -H 'Host: i.instagram.com' -H 'X-FB-HTTP-Engine: Liger' -H 'Connection: close'

-b 'urlgen={\\\"2.32.17.241\\\": 30722}:1hyXD8:CtBwsrvpw7Kf-CZYDemiflBEdHg; ds_user=potatomayl; igfl=potatomayl; ds_user_id=123456789; mid=XVLRpwABAAG_kqYiZihqukSRfL9F; shbts=1565942622.665477; sessionid=123456789%2A3CEmcOySZOVzk9%3A2; csrftoken=ap6Xt3UkFaHlx6ALQMPnwkIi9mGVJ1kB; shbid=13717; rur=FRC; is_starred_enabled=yes'

'https://i.instagram.com/api/v1/news/inbox/'
```
___
## info [GET]
### Request
```
https://i.instagram.com/api/v1/users/123456789/info/
```
### Headers
```
X-Pigeon-Session-Id: 140864b2-5517-4d55-85b4-0e0401423dae
X-Pigeon-Rawclienttime: 1565942624.819
X-IG-Connection-Speed: -1kbps
X-IG-Bandwidth-Speed-KBPS: 9486.134
X-IG-Bandwidth-TotalBytes-B: 996044
X-IG-Bandwidth-TotalTime-MS: 105
X-IG-VP9-Capable: false
X-Bloks-Version-Id: 14f543394cf83e14784db6457e197a7e61e34fcd161891682143f74cb69a8981
X-IG-Connection-Type: WIFI
X-IG-Capabilities: 3brTvw==
X-IG-App-ID: 567067343352427
User-Agent: Instagram 103.1.0.15.119 Android (28/9; 420dpi; 1080x2034; unknown/Android; Google Pixel 3; vbox86p; vbox86; en_US; 164094540)
Accept-Language: en-US
Cookie: urlgen={\"2.32.17.241\": 30722}:1hyXD8:CtBwsrvpw7Kf-CZYDemiflBEdHg; ds_user=potatomayl; igfl=potatomayl; ds_user_id=123456789; mid=XVLRpwABAAG_kqYiZihqukSRfL9F; shbts=1565942622.665477; sessionid=123456789%2A3CEmcOySZOVzk9%3A2; csrftoken=ap6Xt3UkFaHlx6ALQMPnwkIi9mGVJ1kB; shbid=13717; rur=FRC; is_starred_enabled=yes
Accept-Encoding: gzip, deflate
Host: i.instagram.com
X-FB-HTTP-Engine: Liger
Connection: close
```
### CURL Command
```
curl -i -s -k  -X 'GET'

-H 'X-Pigeon-Session-Id: 140864b2-5517-4d55-85b4-0e0401423dae' -H 'X-Pigeon-Rawclienttime: 1565942624.819' -H 'X-IG-Connection-Speed: -1kbps' -H 'X-IG-Bandwidth-Speed-KBPS: 9486.134' -H 'X-IG-Bandwidth-TotalBytes-B: 996044' -H 'X-IG-Bandwidth-TotalTime-MS: 105' -H 'X-IG-VP9-Capable: false' -H 'X-Bloks-Version-Id: 14f543394cf83e14784db6457e197a7e61e34fcd161891682143f74cb69a8981' -H 'X-IG-Connection-Type: WIFI' -H 'X-IG-Capabilities: 3brTvw==' -H 'X-IG-App-ID: 567067343352427' -H 'User-Agent: Instagram 103.1.0.15.119 Android (28/9; 420dpi; 1080x2034; unknown/Android; Google Pixel 3; vbox86p; vbox86; en_US; 164094540)' -H 'Accept-Language: en-US' -H 'Cookie: urlgen={\\\"2.32.17.241\\\": 30722}:1hyXD8:CtBwsrvpw7Kf-CZYDemiflBEdHg; ds_user=potatomayl; igfl=potatomayl; ds_user_id=123456789; mid=XVLRpwABAAG_kqYiZihqukSRfL9F; shbts=1565942622.665477; sessionid=123456789%2A3CEmcOySZOVzk9%3A2; csrftoken=ap6Xt3UkFaHlx6ALQMPnwkIi9mGVJ1kB; shbid=13717; rur=FRC; is_starred_enabled=yes' -H 'Accept-Encoding: gzip, deflate' -H 'Host: i.instagram.com' -H 'X-FB-HTTP-Engine: Liger' -H 'Connection: close'

-b 'urlgen={\\\"2.32.17.241\\\": 30722}:1hyXD8:CtBwsrvpw7Kf-CZYDemiflBEdHg; ds_user=potatomayl; igfl=potatomayl; ds_user_id=123456789; mid=XVLRpwABAAG_kqYiZihqukSRfL9F; shbts=1565942622.665477; sessionid=123456789%2A3CEmcOySZOVzk9%3A2; csrftoken=ap6Xt3UkFaHlx6ALQMPnwkIi9mGVJ1kB; shbid=13717; rur=FRC; is_starred_enabled=yes'

'https://i.instagram.com/api/v1/users/123456789/info/'
```
___
## fetch_config [GET]
### Request
```
https://i.instagram.com/api/v1/loom/fetch_config/
```
### Headers
```
X-Pigeon-Session-Id: 140864b2-5517-4d55-85b4-0e0401423dae
X-Pigeon-Rawclienttime: 1565942624.813
X-IG-Connection-Speed: -1kbps
X-IG-Bandwidth-Speed-KBPS: 9486.134
X-IG-Bandwidth-TotalBytes-B: 996044
X-IG-Bandwidth-TotalTime-MS: 105
X-IG-VP9-Capable: false
X-Bloks-Version-Id: 14f543394cf83e14784db6457e197a7e61e34fcd161891682143f74cb69a8981
X-IG-Connection-Type: WIFI
X-IG-Capabilities: 3brTvw==
X-IG-App-ID: 567067343352427
User-Agent: Instagram 103.1.0.15.119 Android (28/9; 420dpi; 1080x2034; unknown/Android; Google Pixel 3; vbox86p; vbox86; en_US; 164094540)
Accept-Language: en-US
Cookie: urlgen={\"2.32.17.241\": 30722}:1hyXD8:CtBwsrvpw7Kf-CZYDemiflBEdHg; ds_user=potatomayl; igfl=potatomayl; ds_user_id=123456789; mid=XVLRpwABAAG_kqYiZihqukSRfL9F; shbts=1565942622.665477; sessionid=123456789%2A3CEmcOySZOVzk9%3A2; csrftoken=ap6Xt3UkFaHlx6ALQMPnwkIi9mGVJ1kB; shbid=13717; rur=FRC; is_starred_enabled=yes
Accept-Encoding: gzip, deflate
Host: i.instagram.com
X-FB-HTTP-Engine: Liger
Connection: close
```
### CURL Command
```
curl -i -s -k  -X 'GET'

-H 'X-Pigeon-Session-Id: 140864b2-5517-4d55-85b4-0e0401423dae' -H 'X-Pigeon-Rawclienttime: 1565942624.813' -H 'X-IG-Connection-Speed: -1kbps' -H 'X-IG-Bandwidth-Speed-KBPS: 9486.134' -H 'X-IG-Bandwidth-TotalBytes-B: 996044' -H 'X-IG-Bandwidth-TotalTime-MS: 105' -H 'X-IG-VP9-Capable: false' -H 'X-Bloks-Version-Id: 14f543394cf83e14784db6457e197a7e61e34fcd161891682143f74cb69a8981' -H 'X-IG-Connection-Type: WIFI' -H 'X-IG-Capabilities: 3brTvw==' -H 'X-IG-App-ID: 567067343352427' -H 'User-Agent: Instagram 103.1.0.15.119 Android (28/9; 420dpi; 1080x2034; unknown/Android; Google Pixel 3; vbox86p; vbox86; en_US; 164094540)' -H 'Accept-Language: en-US' -H 'Cookie: urlgen={\\\"2.32.17.241\\\": 30722}:1hyXD8:CtBwsrvpw7Kf-CZYDemiflBEdHg; ds_user=potatomayl; igfl=potatomayl; ds_user_id=123456789; mid=XVLRpwABAAG_kqYiZihqukSRfL9F; shbts=1565942622.665477; sessionid=123456789%2A3CEmcOySZOVzk9%3A2; csrftoken=ap6Xt3UkFaHlx6ALQMPnwkIi9mGVJ1kB; shbid=13717; rur=FRC; is_starred_enabled=yes' -H 'Accept-Encoding: gzip, deflate' -H 'Host: i.instagram.com' -H 'X-FB-HTTP-Engine: Liger' -H 'Connection: close'

-b 'urlgen={\\\"2.32.17.241\\\": 30722}:1hyXD8:CtBwsrvpw7Kf-CZYDemiflBEdHg; ds_user=potatomayl; igfl=potatomayl; ds_user_id=123456789; mid=XVLRpwABAAG_kqYiZihqukSRfL9F; shbts=1565942622.665477; sessionid=123456789%2A3CEmcOySZOVzk9%3A2; csrftoken=ap6Xt3UkFaHlx6ALQMPnwkIi9mGVJ1kB; shbid=13717; rur=FRC; is_starred_enabled=yes'

'https://i.instagram.com/api/v1/loom/fetch_config/'
```
___
## device_capabilities/decisions [GET]
### Request
```
https://i.instagram.com/api/v1/device_capabilities/decisions/?signed_body=652ad369e0176fd2b347f3711348400fde60477f711249581813d74feba9ec2d.%7B%7D&ig_sig_key_version=4
```
### Headers
```
X-Pigeon-Session-Id: 140864b2-5517-4d55-85b4-0e0401423dae
X-Pigeon-Rawclienttime: 1565942624.845
X-IG-Connection-Speed: -1kbps
X-IG-Bandwidth-Speed-KBPS: 9486.134
X-IG-Bandwidth-TotalBytes-B: 996044
X-IG-Bandwidth-TotalTime-MS: 105
X-IG-VP9-Capable: false
X-Bloks-Version-Id: 14f543394cf83e14784db6457e197a7e61e34fcd161891682143f74cb69a8981
X-IG-Connection-Type: WIFI
X-IG-Capabilities: 3brTvw==
X-IG-App-ID: 567067343352427
User-Agent: Instagram 103.1.0.15.119 Android (28/9; 420dpi; 1080x2034; unknown/Android; Google Pixel 3; vbox86p; vbox86; en_US; 164094540)
Accept-Language: en-US
Cookie: urlgen={\"2.32.17.241\": 30722}:1hyXD8:CtBwsrvpw7Kf-CZYDemiflBEdHg; ds_user=potatomayl; igfl=potatomayl; ds_user_id=123456789; mid=XVLRpwABAAG_kqYiZihqukSRfL9F; shbts=1565942622.665477; sessionid=123456789%2A3CEmcOySZOVzk9%3A2; csrftoken=ap6Xt3UkFaHlx6ALQMPnwkIi9mGVJ1kB; shbid=13717; rur=FRC; is_starred_enabled=yes
Accept-Encoding: gzip, deflate
Host: i.instagram.com
X-FB-HTTP-Engine: Liger
Connection: close
```
### CURL Command
```
curl -i -s -k  -X 'GET'

-H 'X-Pigeon-Session-Id: 140864b2-5517-4d55-85b4-0e0401423dae' -H 'X-Pigeon-Rawclienttime: 1565942624.845' -H 'X-IG-Connection-Speed: -1kbps' -H 'X-IG-Bandwidth-Speed-KBPS: 9486.134' -H 'X-IG-Bandwidth-TotalBytes-B: 996044' -H 'X-IG-Bandwidth-TotalTime-MS: 105' -H 'X-IG-VP9-Capable: false' -H 'X-Bloks-Version-Id: 14f543394cf83e14784db6457e197a7e61e34fcd161891682143f74cb69a8981' -H 'X-IG-Connection-Type: WIFI' -H 'X-IG-Capabilities: 3brTvw==' -H 'X-IG-App-ID: 567067343352427' -H 'User-Agent: Instagram 103.1.0.15.119 Android (28/9; 420dpi; 1080x2034; unknown/Android; Google Pixel 3; vbox86p; vbox86; en_US; 164094540)' -H 'Accept-Language: en-US' -H 'Cookie: urlgen={\\\"2.32.17.241\\\": 30722}:1hyXD8:CtBwsrvpw7Kf-CZYDemiflBEdHg; ds_user=potatomayl; igfl=potatomayl; ds_user_id=123456789; mid=XVLRpwABAAG_kqYiZihqukSRfL9F; shbts=1565942622.665477; sessionid=123456789%2A3CEmcOySZOVzk9%3A2; csrftoken=ap6Xt3UkFaHlx6ALQMPnwkIi9mGVJ1kB; shbid=13717; rur=FRC; is_starred_enabled=yes' -H 'Accept-Encoding: gzip, deflate' -H 'Host: i.instagram.com' -H 'X-FB-HTTP-Engine: Liger' -H 'Connection: close'

-b 'urlgen={\\\"2.32.17.241\\\": 30722}:1hyXD8:CtBwsrvpw7Kf-CZYDemiflBEdHg; ds_user=potatomayl; igfl=potatomayl; ds_user_id=123456789; mid=XVLRpwABAAG_kqYiZihqukSRfL9F; shbts=1565942622.665477; sessionid=123456789%2A3CEmcOySZOVzk9%3A2; csrftoken=ap6Xt3UkFaHlx6ALQMPnwkIi9mGVJ1kB; shbid=13717; rur=FRC; is_starred_enabled=yes'

'https://i.instagram.com/api/v1/device_capabilities/decisions/?signed_body=652ad369e0176fd2b347f3711348400fde60477f711249581813d74feba9ec2d.%7B%7D&ig_sig_key_version=4'
```
___
## get_linkage_status [GET]
### Request
```
https://i.instagram.com/api/v1/linked_accounts/get_linkage_status/
```
### Headers
```
X-Pigeon-Session-Id: 140864b2-5517-4d55-85b4-0e0401423dae
X-Pigeon-Rawclienttime: 1565942624.855
X-IG-Connection-Speed: -1kbps
X-IG-Bandwidth-Speed-KBPS: 9486.134
X-IG-Bandwidth-TotalBytes-B: 996044
X-IG-Bandwidth-TotalTime-MS: 105
X-IG-VP9-Capable: false
X-Bloks-Version-Id: 14f543394cf83e14784db6457e197a7e61e34fcd161891682143f74cb69a8981
X-IG-Connection-Type: WIFI
X-IG-Capabilities: 3brTvw==
X-IG-App-ID: 567067343352427
User-Agent: Instagram 103.1.0.15.119 Android (28/9; 420dpi; 1080x2034; unknown/Android; Google Pixel 3; vbox86p; vbox86; en_US; 164094540)
Accept-Language: en-US
Cookie: urlgen={\"2.32.17.241\": 30722}:1hyXD8:CtBwsrvpw7Kf-CZYDemiflBEdHg; ds_user=potatomayl; igfl=potatomayl; ds_user_id=123456789; mid=XVLRpwABAAG_kqYiZihqukSRfL9F; shbts=1565942622.665477; sessionid=123456789%2A3CEmcOySZOVzk9%3A2; csrftoken=ap6Xt3UkFaHlx6ALQMPnwkIi9mGVJ1kB; shbid=13717; rur=FRC; is_starred_enabled=yes
Accept-Encoding: gzip, deflate
Host: i.instagram.com
X-FB-HTTP-Engine: Liger
Connection: close
```
### CURL Command
```
curl -i -s -k  -X 'GET'

-H 'X-Pigeon-Session-Id: 140864b2-5517-4d55-85b4-0e0401423dae' -H 'X-Pigeon-Rawclienttime: 1565942624.855' -H 'X-IG-Connection-Speed: -1kbps' -H 'X-IG-Bandwidth-Speed-KBPS: 9486.134' -H 'X-IG-Bandwidth-TotalBytes-B: 996044' -H 'X-IG-Bandwidth-TotalTime-MS: 105' -H 'X-IG-VP9-Capable: false' -H 'X-Bloks-Version-Id: 14f543394cf83e14784db6457e197a7e61e34fcd161891682143f74cb69a8981' -H 'X-IG-Connection-Type: WIFI' -H 'X-IG-Capabilities: 3brTvw==' -H 'X-IG-App-ID: 567067343352427' -H 'User-Agent: Instagram 103.1.0.15.119 Android (28/9; 420dpi; 1080x2034; unknown/Android; Google Pixel 3; vbox86p; vbox86; en_US; 164094540)' -H 'Accept-Language: en-US' -H 'Cookie: urlgen={\\\"2.32.17.241\\\": 30722}:1hyXD8:CtBwsrvpw7Kf-CZYDemiflBEdHg; ds_user=potatomayl; igfl=potatomayl; ds_user_id=123456789; mid=XVLRpwABAAG_kqYiZihqukSRfL9F; shbts=1565942622.665477; sessionid=123456789%2A3CEmcOySZOVzk9%3A2; csrftoken=ap6Xt3UkFaHlx6ALQMPnwkIi9mGVJ1kB; shbid=13717; rur=FRC; is_starred_enabled=yes' -H 'Accept-Encoding: gzip, deflate' -H 'Host: i.instagram.com' -H 'X-FB-HTTP-Engine: Liger' -H 'Connection: close'

-b 'urlgen={\\\"2.32.17.241\\\": 30722}:1hyXD8:CtBwsrvpw7Kf-CZYDemiflBEdHg; ds_user=potatomayl; igfl=potatomayl; ds_user_id=123456789; mid=XVLRpwABAAG_kqYiZihqukSRfL9F; shbts=1565942622.665477; sessionid=123456789%2A3CEmcOySZOVzk9%3A2; csrftoken=ap6Xt3UkFaHlx6ALQMPnwkIi9mGVJ1kB; shbid=13717; rur=FRC; is_starred_enabled=yes'

'https://i.instagram.com/api/v1/linked_accounts/get_linkage_status/'
```
___
## Method name [GET]
### Request
```
https://i.instagram.com/api/v1/media/blocked/
```
### Headers
```
X-Pigeon-Session-Id: 140864b2-5517-4d55-85b4-0e0401423dae
X-Pigeon-Rawclienttime: 1565942624.864
X-IG-Connection-Speed: -1kbps
X-IG-Bandwidth-Speed-KBPS: 9486.134
X-IG-Bandwidth-TotalBytes-B: 996044
X-IG-Bandwidth-TotalTime-MS: 105
X-IG-VP9-Capable: false
X-Bloks-Version-Id: 14f543394cf83e14784db6457e197a7e61e34fcd161891682143f74cb69a8981
X-IG-Connection-Type: WIFI
X-IG-Capabilities: 3brTvw==
X-IG-App-ID: 567067343352427
User-Agent: Instagram 103.1.0.15.119 Android (28/9; 420dpi; 1080x2034; unknown/Android; Google Pixel 3; vbox86p; vbox86; en_US; 164094540)
Accept-Language: en-US
Cookie: urlgen={\"2.32.17.241\": 30722}:1hyXD8:CtBwsrvpw7Kf-CZYDemiflBEdHg; ds_user=potatomayl; igfl=potatomayl; ds_user_id=123456789; mid=XVLRpwABAAG_kqYiZihqukSRfL9F; shbts=1565942622.665477; sessionid=123456789%2A3CEmcOySZOVzk9%3A2; csrftoken=ap6Xt3UkFaHlx6ALQMPnwkIi9mGVJ1kB; shbid=13717; rur=FRC; is_starred_enabled=yes
Accept-Encoding: gzip, deflate
Host: i.instagram.com
X-FB-HTTP-Engine: Liger
Connection: close
```
### CURL Command
```
curl -i -s -k  -X 'GET'

-H 'X-Pigeon-Session-Id: 140864b2-5517-4d55-85b4-0e0401423dae' -H 'X-Pigeon-Rawclienttime: 1565942624.864' -H 'X-IG-Connection-Speed: -1kbps' -H 'X-IG-Bandwidth-Speed-KBPS: 9486.134' -H 'X-IG-Bandwidth-TotalBytes-B: 996044' -H 'X-IG-Bandwidth-TotalTime-MS: 105' -H 'X-IG-VP9-Capable: false' -H 'X-Bloks-Version-Id: 14f543394cf83e14784db6457e197a7e61e34fcd161891682143f74cb69a8981' -H 'X-IG-Connection-Type: WIFI' -H 'X-IG-Capabilities: 3brTvw==' -H 'X-IG-App-ID: 567067343352427' -H 'User-Agent: Instagram 103.1.0.15.119 Android (28/9; 420dpi; 1080x2034; unknown/Android; Google Pixel 3; vbox86p; vbox86; en_US; 164094540)' -H 'Accept-Language: en-US' -H 'Cookie: urlgen={\\\"2.32.17.241\\\": 30722}:1hyXD8:CtBwsrvpw7Kf-CZYDemiflBEdHg; ds_user=potatomayl; igfl=potatomayl; ds_user_id=123456789; mid=XVLRpwABAAG_kqYiZihqukSRfL9F; shbts=1565942622.665477; sessionid=123456789%2A3CEmcOySZOVzk9%3A2; csrftoken=ap6Xt3UkFaHlx6ALQMPnwkIi9mGVJ1kB; shbid=13717; rur=FRC; is_starred_enabled=yes' -H 'Accept-Encoding: gzip, deflate' -H 'Host: i.instagram.com' -H 'X-FB-HTTP-Engine: Liger' -H 'Connection: close'

-b 'urlgen={\\\"2.32.17.241\\\": 30722}:1hyXD8:CtBwsrvpw7Kf-CZYDemiflBEdHg; ds_user=potatomayl; igfl=potatomayl; ds_user_id=123456789; mid=XVLRpwABAAG_kqYiZihqukSRfL9F; shbts=1565942622.665477; sessionid=123456789%2A3CEmcOySZOVzk9%3A2; csrftoken=ap6Xt3UkFaHlx6ALQMPnwkIi9mGVJ1kB; shbid=13717; rur=FRC; is_starred_enabled=yes'

'https://i.instagram.com/api/v1/media/blocked/'
```
___
## batch_fetch [POST]
### Request
```
https://i.instagram.com/api/v1/qp/batch_fetch/
```
### Headers
```
X-Pigeon-Session-Id: 140864b2-5517-4d55-85b4-0e0401423dae
X-Pigeon-Rawclienttime: 1565942624.975
X-IG-Connection-Speed: -1kbps
X-IG-Bandwidth-Speed-KBPS: 9486.134
X-IG-Bandwidth-TotalBytes-B: 996044
X-IG-Bandwidth-TotalTime-MS: 105
X-IG-VP9-Capable: false
X-Bloks-Version-Id: 14f543394cf83e14784db6457e197a7e61e34fcd161891682143f74cb69a8981
X-IG-Connection-Type: WIFI
X-IG-Capabilities: 3brTvw==
X-IG-App-ID: 567067343352427
User-Agent: Instagram 103.1.0.15.119 Android (28/9; 420dpi; 1080x2034; unknown/Android; Google Pixel 3; vbox86p; vbox86; en_US; 164094540)
Accept-Language: en-US
Cookie: urlgen={\"2.32.17.241\": 30722}:1hyXD8:CtBwsrvpw7Kf-CZYDemiflBEdHg; ds_user=potatomayl; igfl=potatomayl; ds_user_id=123456789; mid=XVLRpwABAAG_kqYiZihqukSRfL9F; shbts=1565942622.665477; sessionid=123456789%2A3CEmcOySZOVzk9%3A2; csrftoken=ap6Xt3UkFaHlx6ALQMPnwkIi9mGVJ1kB; shbid=13717; rur=FRC; is_starred_enabled=yes
Content-Type: application/x-www-form-urlencoded; charset=UTF-8
Accept-Encoding: gzip, deflate
Host: i.instagram.com
X-FB-HTTP-Engine: Liger
Connection: close
Content-Length: 6518
```
### Arguments encoded
```
signed_body=45b1a332a30c0e7e381fd26cde9c1a44b1e9e27dc3f1e45d863ccc6ed8f71d11.%7B%22surfaces_to_triggers%22%3A%22%7B%5C%225734%5C%22%3A%5B%5C%22instagram_feed_prompt%5C%22%5D%2C%5C%224715%5C%22%3A%5B%5C%22instagram_feed_header%5C%22%5D%2C%5C%225858%5C%22%3A%5B%5C%22instagram_feed_tool_tip%5C%22%5D%7D%22%2C%22surfaces_to_queries%22%3A%22%7B%5C%225734%5C%22%3A%5C%22viewer%28%29+%7Beligible_promotions.trigger_context_v2%28%3Ctrigger_context_v2%3E%29.ig_parameters%28%3Cig_parameters%3E%29.trigger_name%28%3Ctrigger_name%3E%29.surface_nux_id%28%3Csurface%3E%29.external_gating_permitted_qps%28%3Cexternal_gating_permitted_qps%3E%29.supports_client_filters%28true%29.include_holdouts%28true%29+%7Bedges+%7Bclient_ttl_seconds%2Clog_eligibility_waterfall%2Cis_holdout%2Cpriority%2Ctime_range+%7Bstart%2Cend%7D%2Cnode+%7Bid%2Cpromotion_id%2Clogging_data%2Cmax_impressions%2Ctriggers%2Ccontextual_filters+%7Bclause_type%2Cfilters+%7Bfilter_type%2Cunknown_action%2Cvalue+%7Bname%2Crequired%2Cbool_value%2Cint_value%2Cstring_value%7D%2Cextra_datas+%7Bname%2Crequired%2Cbool_value%2Cint_value%2Cstring_value%7D%7D%2Cclauses+%7Bclause_type%2Cfilters+%7Bfilter_type%2Cunknown_action%2Cvalue+%7Bname%2Crequired%2Cbool_value%2Cint_value%2Cstring_value%7D%2Cextra_datas+%7Bname%2Crequired%2Cbool_value%2Cint_value%2Cstring_value%7D%7D%2Cclauses+%7Bclause_type%2Cfilters+%7Bfilter_type%2Cunknown_action%2Cvalue+%7Bname%2Crequired%2Cbool_value%2Cint_value%2Cstring_value%7D%2Cextra_datas+%7Bname%2Crequired%2Cbool_value%2Cint_value%2Cstring_value%7D%7D%2Cclauses+%7Bclause_type%2Cfilters+%7Bfilter_type%2Cunknown_action%2Cvalue+%7Bname%2Crequired%2Cbool_value%2Cint_value%2Cstring_value%7D%2Cextra_datas+%7Bname%2Crequired%2Cbool_value%2Cint_value%2Cstring_value%7D%7D%7D%7D%7D%7D%2Cis_uncancelable%2Ctemplate+%7Bname%2Cparameters+%7Bname%2Crequired%2Cbool_value%2Cstring_value%2Ccolor_value%2C%7D%7D%2Ccreatives+%7Btitle+%7Btext%7D%2Ccontent+%7Btext%7D%2Cfooter+%7Btext%7D%2Csocial_context+%7Btext%7D%2Csocial_context_images%2Cprimary_action%7Btitle+%7Btext%7D%2Curl%2Climit%2Cdismiss_promotion%7D%2Csecondary_action%7Btitle+%7Btext%7D%2Curl%2Climit%2Cdismiss_promotion%7D%2Cdismiss_action%7Btitle+%7Btext%7D%2Curl%2Climit%2Cdismiss_promotion%7D%2Cimage.scale%28%3Cscale%3E%29+%7Buri%2Cwidth%2Cheight%7D%7D%7D%7D%7D%7D%5C%22%2C%5C%224715%5C%22%3A%5C%22viewer%28%29+%7Beligible_promotions.trigger_context_v2%28%3Ctrigger_context_v2%3E%29.ig_parameters%28%3Cig_parameters%3E%29.trigger_name%28%3Ctrigger_name%3E%29.surface_nux_id%28%3Csurface%3E%29.external_gating_permitted_qps%28%3Cexternal_gating_permitted_qps%3E%29.supports_client_filters%28true%29.include_holdouts%28true%29+%7Bedges+%7Bclient_ttl_seconds%2Clog_eligibility_waterfall%2Cis_holdout%2Cpriority%2Ctime_range+%7Bstart%2Cend%7D%2Cnode+%7Bid%2Cpromotion_id%2Clogging_data%2Cmax_impressions%2Ctriggers%2Ccontextual_filters+%7Bclause_type%2Cfilters+%7Bfilter_type%2Cunknown_action%2Cvalue+%7Bname%2Crequired%2Cbool_value%2Cint_value%2Cstring_value%7D%2Cextra_datas+%7Bname%2Crequired%2Cbool_value%2Cint_value%2Cstring_value%7D%7D%2Cclauses+%7Bclause_type%2Cfilters+%7Bfilter_type%2Cunknown_action%2Cvalue+%7Bname%2Crequired%2Cbool_value%2Cint_value%2Cstring_value%7D%2Cextra_datas+%7Bname%2Crequired%2Cbool_value%2Cint_value%2Cstring_value%7D%7D%2Cclauses+%7Bclause_type%2Cfilters+%7Bfilter_type%2Cunknown_action%2Cvalue+%7Bname%2Crequired%2Cbool_value%2Cint_value%2Cstring_value%7D%2Cextra_datas+%7Bname%2Crequired%2Cbool_value%2Cint_value%2Cstring_value%7D%7D%2Cclauses+%7Bclause_type%2Cfilters+%7Bfilter_type%2Cunknown_action%2Cvalue+%7Bname%2Crequired%2Cbool_value%2Cint_value%2Cstring_value%7D%2Cextra_datas+%7Bname%2Crequired%2Cbool_value%2Cint_value%2Cstring_value%7D%7D%7D%7D%7D%7D%2Cis_uncancelable%2Ctemplate+%7Bname%2Cparameters+%7Bname%2Crequired%2Cbool_value%2Cstring_value%2Ccolor_value%2C%7D%7D%2Ccreatives+%7Btitle+%7Btext%7D%2Ccontent+%7Btext%7D%2Cfooter+%7Btext%7D%2Csocial_context+%7Btext%7D%2Csocial_context_images%2Cprimary_action%7Btitle+%7Btext%7D%2Curl%2Climit%2Cdismiss_promotion%7D%2Csecondary_action%7Btitle+%7Btext%7D%2Curl%2Climit%2Cdismiss_promotion%7D%2Cdismiss_action%7Btitle+%7Btext%7D%2Curl%2Climit%2Cdismiss_promotion%7D%2Cimage.scale%28%3Cscale%3E%29+%7Buri%2Cwidth%2Cheight%7D%7D%7D%7D%7D%7D%5C%22%2C%5C%225858%5C%22%3A%5C%22viewer%28%29+%7Beligible_promotions.trigger_context_v2%28%3Ctrigger_context_v2%3E%29.ig_parameters%28%3Cig_parameters%3E%29.trigger_name%28%3Ctrigger_name%3E%29.surface_nux_id%28%3Csurface%3E%29.external_gating_permitted_qps%28%3Cexternal_gating_permitted_qps%3E%29.supports_client_filters%28true%29.include_holdouts%28true%29+%7Bedges+%7Bclient_ttl_seconds%2Clog_eligibility_waterfall%2Cis_holdout%2Cpriority%2Ctime_range+%7Bstart%2Cend%7D%2Cnode+%7Bid%2Cpromotion_id%2Clogging_data%2Cmax_impressions%2Ctriggers%2Ccontextual_filters+%7Bclause_type%2Cfilters+%7Bfilter_type%2Cunknown_action%2Cvalue+%7Bname%2Crequired%2Cbool_value%2Cint_value%2Cstring_value%7D%2Cextra_datas+%7Bname%2Crequired%2Cbool_value%2Cint_value%2Cstring_value%7D%7D%2Cclauses+%7Bclause_type%2Cfilters+%7Bfilter_type%2Cunknown_action%2Cvalue+%7Bname%2Crequired%2Cbool_value%2Cint_value%2Cstring_value%7D%2Cextra_datas+%7Bname%2Crequired%2Cbool_value%2Cint_value%2Cstring_value%7D%7D%2Cclauses+%7Bclause_type%2Cfilters+%7Bfilter_type%2Cunknown_action%2Cvalue+%7Bname%2Crequired%2Cbool_value%2Cint_value%2Cstring_value%7D%2Cextra_datas+%7Bname%2Crequired%2Cbool_value%2Cint_value%2Cstring_value%7D%7D%2Cclauses+%7Bclause_type%2Cfilters+%7Bfilter_type%2Cunknown_action%2Cvalue+%7Bname%2Crequired%2Cbool_value%2Cint_value%2Cstring_value%7D%2Cextra_datas+%7Bname%2Crequired%2Cbool_value%2Cint_value%2Cstring_value%7D%7D%7D%7D%7D%7D%2Cis_uncancelable%2Ctemplate+%7Bname%2Cparameters+%7Bname%2Crequired%2Cbool_value%2Cstring_value%2Ccolor_value%2C%7D%7D%2Ccreatives+%7Btitle+%7Btext%7D%2Ccontent+%7Btext%7D%2Cfooter+%7Btext%7D%2Csocial_context+%7Btext%7D%2Csocial_context_images%2Cprimary_action%7Btitle+%7Btext%7D%2Curl%2Climit%2Cdismiss_promotion%7D%2Csecondary_action%7Btitle+%7Btext%7D%2Curl%2Climit%2Cdismiss_promotion%7D%2Cdismiss_action%7Btitle+%7Btext%7D%2Curl%2Climit%2Cdismiss_promotion%7D%2Cimage.scale%28%3Cscale%3E%29+%7Buri%2Cwidth%2Cheight%7D%7D%7D%7D%7D%7D%5C%22%7D%22%2C%22vc_policy%22%3A%22default%22%2C%22_csrftoken%22%3A%22ap6Xt3UkFaHlx6ALQMPnwkIi9mGVJ1kB%22%2C%22_uid%22%3A%22123456789%22%2C%22_uuid%22%3A%22ffbe7b2f-1663-43d4-847b-c3f51803637e%22%2C%22scale%22%3A%223%22%2C%22version%22%3A%221%22%7D&ig_sig_key_version=4
```
### Arguments decoded
```
signed_body=45b1a332a30c0e7e381fd26cde9c1a44b1e9e27dc3f1e45d863ccc6ed8f71d11.{"surfaces_to_triggers":"{\"5734\":[\"instagram_feed_prompt\"],\"4715\":[\"instagram_feed_header\"],\"5858\":[\"instagram_feed_tool_tip\"]}","surfaces_to_queries":"{\"5734\":\"viewer() {eligible_promotions.trigger_context_v2(<trigger_context_v2>).ig_parameters(<ig_parameters>).trigger_name(<trigger_name>).surface_nux_id(<surface>).external_gating_permitted_qps(<external_gating_permitted_qps>).supports_client_filters(true).include_holdouts(true) {edges {client_ttl_seconds,log_eligibility_waterfall,is_holdout,priority,time_range {start,end},node {id,promotion_id,logging_data,max_impressions,triggers,contextual_filters {clause_type,filters {filter_type,unknown_action,value {name,required,bool_value,int_value,string_value},extra_datas {name,required,bool_value,int_value,string_value}},clauses {clause_type,filters {filter_type,unknown_action,value {name,required,bool_value,int_value,string_value},extra_datas {name,required,bool_value,int_value,string_value}},clauses {clause_type,filters {filter_type,unknown_action,value {name,required,bool_value,int_value,string_value},extra_datas {name,required,bool_value,int_value,string_value}},clauses {clause_type,filters {filter_type,unknown_action,value {name,required,bool_value,int_value,string_value},extra_datas {name,required,bool_value,int_value,string_value}}}}}},is_uncancelable,template {name,parameters {name,required,bool_value,string_value,color_value,}},creatives {title {text},content {text},footer {text},social_context {text},social_context_images,primary_action{title {text},url,limit,dismiss_promotion},secondary_action{title {text},url,limit,dismiss_promotion},dismiss_action{title {text},url,limit,dismiss_promotion},image.scale(<scale>) {uri,width,height}}}}}}\",\"4715\":\"viewer() {eligible_promotions.trigger_context_v2(<trigger_context_v2>).ig_parameters(<ig_parameters>).trigger_name(<trigger_name>).surface_nux_id(<surface>).external_gating_permitted_qps(<external_gating_permitted_qps>).supports_client_filters(true).include_holdouts(true) {edges {client_ttl_seconds,log_eligibility_waterfall,is_holdout,priority,time_range {start,end},node {id,promotion_id,logging_data,max_impressions,triggers,contextual_filters {clause_type,filters {filter_type,unknown_action,value {name,required,bool_value,int_value,string_value},extra_datas {name,required,bool_value,int_value,string_value}},clauses {clause_type,filters {filter_type,unknown_action,value {name,required,bool_value,int_value,string_value},extra_datas {name,required,bool_value,int_value,string_value}},clauses {clause_type,filters {filter_type,unknown_action,value {name,required,bool_value,int_value,string_value},extra_datas {name,required,bool_value,int_value,string_value}},clauses {clause_type,filters {filter_type,unknown_action,value {name,required,bool_value,int_value,string_value},extra_datas {name,required,bool_value,int_value,string_value}}}}}},is_uncancelable,template {name,parameters {name,required,bool_value,string_value,color_value,}},creatives {title {text},content {text},footer {text},social_context {text},social_context_images,primary_action{title {text},url,limit,dismiss_promotion},secondary_action{title {text},url,limit,dismiss_promotion},dismiss_action{title {text},url,limit,dismiss_promotion},image.scale(<scale>) {uri,width,height}}}}}}\",\"5858\":\"viewer() {eligible_promotions.trigger_context_v2(<trigger_context_v2>).ig_parameters(<ig_parameters>).trigger_name(<trigger_name>).surface_nux_id(<surface>).external_gating_permitted_qps(<external_gating_permitted_qps>).supports_client_filters(true).include_holdouts(true) {edges {client_ttl_seconds,log_eligibility_waterfall,is_holdout,priority,time_range {start,end},node {id,promotion_id,logging_data,max_impressions,triggers,contextual_filters {clause_type,filters {filter_type,unknown_action,value {name,required,bool_value,int_value,string_value},extra_datas {name,required,bool_value,int_value,string_value}},clauses {clause_type,filters {filter_type,unknown_action,value {name,required,bool_value,int_value,string_value},extra_datas {name,required,bool_value,int_value,string_value}},clauses {clause_type,filters {filter_type,unknown_action,value {name,required,bool_value,int_value,string_value},extra_datas {name,required,bool_value,int_value,string_value}},clauses {clause_type,filters {filter_type,unknown_action,value {name,required,bool_value,int_value,string_value},extra_datas {name,required,bool_value,int_value,string_value}}}}}},is_uncancelable,template {name,parameters {name,required,bool_value,string_value,color_value,}},creatives {title {text},content {text},footer {text},social_context {text},social_context_images,primary_action{title {text},url,limit,dismiss_promotion},secondary_action{title {text},url,limit,dismiss_promotion},dismiss_action{title {text},url,limit,dismiss_promotion},image.scale(<scale>) {uri,width,height}}}}}}\"}","vc_policy":"default","_csrftoken":"ap6Xt3UkFaHlx6ALQMPnwkIi9mGVJ1kB","_uid":"123456789","_uuid":"ffbe7b2f-1663-43d4-847b-c3f51803637e","scale":"3","version":"1"}&ig_sig_key_version=4
```
### CURL Command
```
curl -i -s -k  -X 'POST'

-H 'X-Pigeon-Session-Id: 140864b2-5517-4d55-85b4-0e0401423dae' -H 'X-Pigeon-Rawclienttime: 1565942624.975' -H 'X-IG-Connection-Speed: -1kbps' -H 'X-IG-Bandwidth-Speed-KBPS: 9486.134' -H 'X-IG-Bandwidth-TotalBytes-B: 996044' -H 'X-IG-Bandwidth-TotalTime-MS: 105' -H 'X-IG-VP9-Capable: false' -H 'X-Bloks-Version-Id: 14f543394cf83e14784db6457e197a7e61e34fcd161891682143f74cb69a8981' -H 'X-IG-Connection-Type: WIFI' -H 'X-IG-Capabilities: 3brTvw==' -H 'X-IG-App-ID: 567067343352427' -H 'User-Agent: Instagram 103.1.0.15.119 Android (28/9; 420dpi; 1080x2034; unknown/Android; Google Pixel 3; vbox86p; vbox86; en_US; 164094540)' -H 'Accept-Language: en-US' -H 'Cookie: urlgen={\\\"2.32.17.241\\\": 30722}:1hyXD8:CtBwsrvpw7Kf-CZYDemiflBEdHg; ds_user=potatomayl; igfl=potatomayl; ds_user_id=123456789; mid=XVLRpwABAAG_kqYiZihqukSRfL9F; shbts=1565942622.665477; sessionid=123456789%2A3CEmcOySZOVzk9%3A2; csrftoken=ap6Xt3UkFaHlx6ALQMPnwkIi9mGVJ1kB; shbid=13717; rur=FRC; is_starred_enabled=yes' -H 'Content-Type: application/x-www-form-urlencoded; charset=UTF-8' -H 'Accept-Encoding: gzip, deflate' -H 'Host: i.instagram.com' -H 'X-FB-HTTP-Engine: Liger' -H 'Connection: close' -H 'Content-Length: 6518'

-b 'urlgen={\\\"2.32.17.241\\\": 30722}:1hyXD8:CtBwsrvpw7Kf-CZYDemiflBEdHg; ds_user=potatomayl; igfl=potatomayl; ds_user_id=123456789; mid=XVLRpwABAAG_kqYiZihqukSRfL9F; shbts=1565942622.665477; sessionid=123456789%2A3CEmcOySZOVzk9%3A2; csrftoken=ap6Xt3UkFaHlx6ALQMPnwkIi9mGVJ1kB; shbid=13717; rur=FRC; is_starred_enabled=yes'

--data-binary 'signed_body=45b1a332a30c0e7e381fd26cde9c1a44b1e9e27dc3f1e45d863ccc6ed8f71d11.%7B%22surfaces_to_triggers%22%3A%22%7B%5C%225734%5C%22%3A%5B%5C%22instagram_feed_prompt%5C%22%5D%2C%5C%224715%5C%22%3A%5B%5C%22instagram_feed_header%5C%22%5D%2C%5C%225858%5C%22%3A%5B%5C%22instagram_feed_tool_tip%5C%22%5D%7D%22%2C%22surfaces_to_queries%22%3A%22%7B%5C%225734%5C%22%3A%5C%22viewer%28%29+%7Beligible_promotions.trigger_context_v2%28%3Ctrigger_context_v2%3E%29.ig_parameters%28%3Cig_parameters%3E%29.trigger_name%28%3Ctrigger_name%3E%29.surface_nux_id%28%3Csurface%3E%29.external_gating_permitted_qps%28%3Cexternal_gating_permitted_qps%3E%29.supports_client_filters%28true%29.include_holdouts%28true%29+%7Bedges+%7Bclient_ttl_seconds%2Clog_eligibility_waterfall%2Cis_holdout%2Cpriority%2Ctime_range+%7Bstart%2Cend%7D%2Cnode+%7Bid%2Cpromotion_id%2Clogging_data%2Cmax_impressions%2Ctriggers%2Ccontextual_filters+%7Bclause_type%2Cfilters+%7Bfilter_type%2Cunknown_action%2Cvalue+%7Bname%2Crequired%2Cbool_value%2Cint_value%2Cstring_value%7D%2Cextra_datas+%7Bname%2Crequired%2Cbool_value%2Cint_value%2Cstring_value%7D%7D%2Cclauses+%7Bclause_type%2Cfilters+%7Bfilter_type%2Cunknown_action%2Cvalue+%7Bname%2Crequired%2Cbool_value%2Cint_value%2Cstring_value%7D%2Cextra_datas+%7Bname%2Crequired%2Cbool_value%2Cint_value%2Cstring_value%7D%7D%2Cclauses+%7Bclause_type%2Cfilters+%7Bfilter_type%2Cunknown_action%2Cvalue+%7Bname%2Crequired%2Cbool_value%2Cint_value%2Cstring_value%7D%2Cextra_datas+%7Bname%2Crequired%2Cbool_value%2Cint_value%2Cstring_value%7D%7D%2Cclauses+%7Bclause_type%2Cfilters+%7Bfilter_type%2Cunknown_action%2Cvalue+%7Bname%2Crequired%2Cbool_value%2Cint_value%2Cstring_value%7D%2Cextra_datas+%7Bname%2Crequired%2Cbool_value%2Cint_value%2Cstring_value%7D%7D%7D%7D%7D%7D%2Cis_uncancelable%2Ctemplate+%7Bname%2Cparameters+%7Bname%2Crequired%2Cbool_value%2Cstring_value%2Ccolor_value%2C%7D%7D%2Ccreatives+%7Btitle+%7Btext%7D%2Ccontent+%7Btext%7D%2Cfooter+%7Btext%7D%2Csocial_context+%7Btext%7D%2Csocial_context_images%2Cprimary_action%7Btitle+%7Btext%7D%2Curl%2Climit%2Cdismiss_promotion%7D%2Csecondary_action%7Btitle+%7Btext%7D%2Curl%2Climit%2Cdismiss_promotion%7D%2Cdismiss_action%7Btitle+%7Btext%7D%2Curl%2Climit%2Cdismiss_promotion%7D%2Cimage.scale%28%3Cscale%3E%29+%7Buri%2Cwidth%2Cheight%7D%7D%7D%7D%7D%7D%5C%22%2C%5C%224715%5C%22%3A%5C%22viewer%28%29+%7Beligible_promotions.trigger_context_v2%28%3Ctrigger_context_v2%3E%29.ig_parameters%28%3Cig_parameters%3E%29.trigger_name%28%3Ctrigger_name%3E%29.surface_nux_id%28%3Csurface%3E%29.external_gating_permitted_qps%28%3Cexternal_gating_permitted_qps%3E%29.supports_client_filters%28true%29.include_holdouts%28true%29+%7Bedges+%7Bclient_ttl_seconds%2Clog_eligibility_waterfall%2Cis_holdout%2Cpriority%2Ctime_range+%7Bstart%2Cend%7D%2Cnode+%7Bid%2Cpromotion_id%2Clogging_data%2Cmax_impressions%2Ctriggers%2Ccontextual_filters+%7Bclause_type%2Cfilters+%7Bfilter_type%2Cunknown_action%2Cvalue+%7Bname%2Crequired%2Cbool_value%2Cint_value%2Cstring_value%7D%2Cextra_datas+%7Bname%2Crequired%2Cbool_value%2Cint_value%2Cstring_value%7D%7D%2Cclauses+%7Bclause_type%2Cfilters+%7Bfilter_type%2Cunknown_action%2Cvalue+%7Bname%2Crequired%2Cbool_value%2Cint_value%2Cstring_value%7D%2Cextra_datas+%7Bname%2Crequired%2Cbool_value%2Cint_value%2Cstring_value%7D%7D%2Cclauses+%7Bclause_type%2Cfilters+%7Bfilter_type%2Cunknown_action%2Cvalue+%7Bname%2Crequired%2Cbool_value%2Cint_value%2Cstring_value%7D%2Cextra_datas+%7Bname%2Crequired%2Cbool_value%2Cint_value%2Cstring_value%7D%7D%2Cclauses+%7Bclause_type%2Cfilters+%7Bfilter_type%2Cunknown_action%2Cvalue+%7Bname%2Crequired%2Cbool_value%2Cint_value%2Cstring_value%7D%2Cextra_datas+%7Bname%2Crequired%2Cbool_value%2Cint_value%2Cstring_value%7D%7D%7D%7D%7D%7D%2Cis_uncancelable%2Ctemplate+%7Bname%2Cparameters+%7Bname%2Crequired%2Cbool_value%2Cstring_value%2Ccolor_value%2C%7D%7D%2Ccreatives+%7Btitle+%7Btext%7D%2Ccontent+%7Btext%7D%2Cfooter+%7Btext%7D%2Csocial_context+%7Btext%7D%2Csocial_context_images%2Cprimary_action%7Btitle+%7Btext%7D%2Curl%2Climit%2Cdismiss_promotion%7D%2Csecondary_action%7Btitle+%7Btext%7D%2Curl%2Climit%2Cdismiss_promotion%7D%2Cdismiss_action%7Btitle+%7Btext%7D%2Curl%2Climit%2Cdismiss_promotion%7D%2Cimage.scale%28%3Cscale%3E%29+%7Buri%2Cwidth%2Cheight%7D%7D%7D%7D%7D%7D%5C%22%2C%5C%225858%5C%22%3A%5C%22viewer%28%29+%7Beligible_promotions.trigger_context_v2%28%3Ctrigger_context_v2%3E%29.ig_parameters%28%3Cig_parameters%3E%29.trigger_name%28%3Ctrigger_name%3E%29.surface_nux_id%28%3Csurface%3E%29.external_gating_permitted_qps%28%3Cexternal_gating_permitted_qps%3E%29.supports_client_filters%28true%29.include_holdouts%28true%29+%7Bedges+%7Bclient_ttl_seconds%2Clog_eligibility_waterfall%2Cis_holdout%2Cpriority%2Ctime_range+%7Bstart%2Cend%7D%2Cnode+%7Bid%2Cpromotion_id%2Clogging_data%2Cmax_impressions%2Ctriggers%2Ccontextual_filters+%7Bclause_type%2Cfilters+%7Bfilter_type%2Cunknown_action%2Cvalue+%7Bname%2Crequired%2Cbool_value%2Cint_value%2Cstring_value%7D%2Cextra_datas+%7Bname%2Crequired%2Cbool_value%2Cint_value%2Cstring_value%7D%7D%2Cclauses+%7Bclause_type%2Cfilters+%7Bfilter_type%2Cunknown_action%2Cvalue+%7Bname%2Crequired%2Cbool_value%2Cint_value%2Cstring_value%7D%2Cextra_datas+%7Bname%2Crequired%2Cbool_value%2Cint_value%2Cstring_value%7D%7D%2Cclauses+%7Bclause_type%2Cfilters+%7Bfilter_type%2Cunknown_action%2Cvalue+%7Bname%2Crequired%2Cbool_value%2Cint_value%2Cstring_value%7D%2Cextra_datas+%7Bname%2Crequired%2Cbool_value%2Cint_value%2Cstring_value%7D%7D%2Cclauses+%7Bclause_type%2Cfilters+%7Bfilter_type%2Cunknown_action%2Cvalue+%7Bname%2Crequired%2Cbool_value%2Cint_value%2Cstring_value%7D%2Cextra_datas+%7Bname%2Crequired%2Cbool_value%2Cint_value%2Cstring_value%7D%7D%7D%7D%7D%7D%2Cis_uncancelable%2Ctemplate+%7Bname%2Cparameters+%7Bname%2Crequired%2Cbool_value%2Cstring_value%2Ccolor_value%2C%7D%7D%2Ccreatives+%7Btitle+%7Btext%7D%2Ccontent+%7Btext%7D%2Cfooter+%7Btext%7D%2Csocial_context+%7Btext%7D%2Csocial_context_images%2Cprimary_action%7Btitle+%7Btext%7D%2Curl%2Climit%2Cdismiss_promotion%7D%2Csecondary_action%7Btitle+%7Btext%7D%2Curl%2Climit%2Cdismiss_promotion%7D%2Cdismiss_action%7Btitle+%7Btext%7D%2Curl%2Climit%2Cdismiss_promotion%7D%2Cimage.scale%28%3Cscale%3E%29+%7Buri%2Cwidth%2Cheight%7D%7D%7D%7D%7D%7D%5C%22%7D%22%2C%22vc_policy%22%3A%22default%22%2C%22_csrftoken%22%3A%22ap6Xt3UkFaHlx6ALQMPnwkIi9mGVJ1kB%22%2C%22_uid%22%3A%22123456789%22%2C%22_uuid%22%3A%22ffbe7b2f-1663-43d4-847b-c3f51803637e%22%2C%22scale%22%3A%223%22%2C%22version%22%3A%221%22%7D&ig_sig_key_version=4'

'https://i.instagram.com/api/v1/qp/batch_fetch/'
```
___
## get_presence [GET]
### Request
```
https://i.instagram.com/api/v1/direct_v2/get_presence/
```
### Headers
```
X-Pigeon-Session-Id: 140864b2-5517-4d55-85b4-0e0401423dae
X-Pigeon-Rawclienttime: 1565942625.307
X-IG-Connection-Speed: -1kbps
X-IG-Bandwidth-Speed-KBPS: 9486.134
X-IG-Bandwidth-TotalBytes-B: 996044
X-IG-Bandwidth-TotalTime-MS: 105
X-IG-VP9-Capable: false
X-Bloks-Version-Id: 14f543394cf83e14784db6457e197a7e61e34fcd161891682143f74cb69a8981
X-IG-Connection-Type: WIFI
X-IG-Capabilities: 3brTvw==
X-IG-App-ID: 567067343352427
User-Agent: Instagram 103.1.0.15.119 Android (28/9; 420dpi; 1080x2034; unknown/Android; Google Pixel 3; vbox86p; vbox86; en_US; 164094540)
Accept-Language: en-US
Cookie: urlgen={\"2.32.17.241\": 30722}:1hyXD8:CtBwsrvpw7Kf-CZYDemiflBEdHg; ds_user=potatomayl; igfl=potatomayl; ds_user_id=123456789; mid=XVLRpwABAAG_kqYiZihqukSRfL9F; shbts=1565942622.665477; sessionid=123456789%2A3CEmcOySZOVzk9%3A2; csrftoken=ap6Xt3UkFaHlx6ALQMPnwkIi9mGVJ1kB; shbid=13717; rur=FRC; is_starred_enabled=yes
Accept-Encoding: gzip, deflate
Host: i.instagram.com
X-FB-HTTP-Engine: Liger
Connection: close
```
### CURL Command
```
curl -i -s -k  -X 'GET'

-H 'X-Pigeon-Session-Id: 140864b2-5517-4d55-85b4-0e0401423dae' -H 'X-Pigeon-Rawclienttime: 1565942625.307' -H 'X-IG-Connection-Speed: -1kbps' -H 'X-IG-Bandwidth-Speed-KBPS: 9486.134' -H 'X-IG-Bandwidth-TotalBytes-B: 996044' -H 'X-IG-Bandwidth-TotalTime-MS: 105' -H 'X-IG-VP9-Capable: false' -H 'X-Bloks-Version-Id: 14f543394cf83e14784db6457e197a7e61e34fcd161891682143f74cb69a8981' -H 'X-IG-Connection-Type: WIFI' -H 'X-IG-Capabilities: 3brTvw==' -H 'X-IG-App-ID: 567067343352427' -H 'User-Agent: Instagram 103.1.0.15.119 Android (28/9; 420dpi; 1080x2034; unknown/Android; Google Pixel 3; vbox86p; vbox86; en_US; 164094540)' -H 'Accept-Language: en-US' -H 'Cookie: urlgen={\\\"2.32.17.241\\\": 30722}:1hyXD8:CtBwsrvpw7Kf-CZYDemiflBEdHg; ds_user=potatomayl; igfl=potatomayl; ds_user_id=123456789; mid=XVLRpwABAAG_kqYiZihqukSRfL9F; shbts=1565942622.665477; sessionid=123456789%2A3CEmcOySZOVzk9%3A2; csrftoken=ap6Xt3UkFaHlx6ALQMPnwkIi9mGVJ1kB; shbid=13717; rur=FRC; is_starred_enabled=yes' -H 'Accept-Encoding: gzip, deflate' -H 'Host: i.instagram.com' -H 'X-FB-HTTP-Engine: Liger' -H 'Connection: close'

-b 'urlgen={\\\"2.32.17.241\\\": 30722}:1hyXD8:CtBwsrvpw7Kf-CZYDemiflBEdHg; ds_user=potatomayl; igfl=potatomayl; ds_user_id=123456789; mid=XVLRpwABAAG_kqYiZihqukSRfL9F; shbts=1565942622.665477; sessionid=123456789%2A3CEmcOySZOVzk9%3A2; csrftoken=ap6Xt3UkFaHlx6ALQMPnwkIi9mGVJ1kB; shbid=13717; rur=FRC; is_starred_enabled=yes'

'https://i.instagram.com/api/v1/direct_v2/get_presence/'
```
___
## Method name [POST/GET]
### Request
```
https://i.instagram.com/api/v1/discover/topical_explore/?is_prefetch=true&omit_cover_media=true&use_sectional_payload=true&timezone_offset=-14400&session_id=e94f7de2-8b68-452b-84e2-2ce83f7382ee&include_fixed_destinations=true
```
### Headers
```
X-Pigeon-Session-Id: 140864b2-5517-4d55-85b4-0e0401423dae
X-Pigeon-Rawclienttime: 1565942625.928
X-IG-Connection-Speed: -1kbps
X-IG-Bandwidth-Speed-KBPS: 4911.635
X-IG-Bandwidth-TotalBytes-B: 1089468
X-IG-Bandwidth-TotalTime-MS: 382
X-IG-Prefetch-Request: foreground
X-IG-VP9-Capable: false
X-Bloks-Version-Id: 14f543394cf83e14784db6457e197a7e61e34fcd161891682143f74cb69a8981
X-IG-Connection-Type: WIFI
X-IG-Capabilities: 3brTvw==
X-IG-App-ID: 567067343352427
User-Agent: Instagram 103.1.0.15.119 Android (28/9; 420dpi; 1080x2034; unknown/Android; Google Pixel 3; vbox86p; vbox86; en_US; 164094540)
Accept-Language: en-US
Cookie: urlgen={\"2.32.17.241\": 30722}:1hyXD9:ivH1JtJQQF19SsqEzC5DmdSW41s; ds_user=potatomayl; igfl=potatomayl; ds_user_id=123456789; mid=XVLRpwABAAG_kqYiZihqukSRfL9F; shbts=1565942622.665477; sessionid=123456789%2A3CEmcOySZOVzk9%3A2; csrftoken=ap6Xt3UkFaHlx6ALQMPnwkIi9mGVJ1kB; shbid=13717; rur=FRC; is_starred_enabled=yes
Accept-Encoding: gzip, deflate
Host: i.instagram.com
X-FB-HTTP-Engine: Liger
Connection: close
```
### CURL Command
```
curl -i -s -k  -X 'GET'

-H 'X-Pigeon-Session-Id: 140864b2-5517-4d55-85b4-0e0401423dae' -H 'X-Pigeon-Rawclienttime: 1565942625.928' -H 'X-IG-Connection-Speed: -1kbps' -H 'X-IG-Bandwidth-Speed-KBPS: 4911.635' -H 'X-IG-Bandwidth-TotalBytes-B: 1089468' -H 'X-IG-Bandwidth-TotalTime-MS: 382' -H 'X-IG-Prefetch-Request: foreground' -H 'X-IG-VP9-Capable: false' -H 'X-Bloks-Version-Id: 14f543394cf83e14784db6457e197a7e61e34fcd161891682143f74cb69a8981' -H 'X-IG-Connection-Type: WIFI' -H 'X-IG-Capabilities: 3brTvw==' -H 'X-IG-App-ID: 567067343352427' -H 'User-Agent: Instagram 103.1.0.15.119 Android (28/9; 420dpi; 1080x2034; unknown/Android; Google Pixel 3; vbox86p; vbox86; en_US; 164094540)' -H 'Accept-Language: en-US' -H 'Cookie: urlgen={\\\"2.32.17.241\\\": 30722}:1hyXD9:ivH1JtJQQF19SsqEzC5DmdSW41s; ds_user=potatomayl; igfl=potatomayl; ds_user_id=123456789; mid=XVLRpwABAAG_kqYiZihqukSRfL9F; shbts=1565942622.665477; sessionid=123456789%2A3CEmcOySZOVzk9%3A2; csrftoken=ap6Xt3UkFaHlx6ALQMPnwkIi9mGVJ1kB; shbid=13717; rur=FRC; is_starred_enabled=yes' -H 'Accept-Encoding: gzip, deflate' -H 'Host: i.instagram.com' -H 'X-FB-HTTP-Engine: Liger' -H 'Connection: close'

-b 'urlgen={\\\"2.32.17.241\\\": 30722}:1hyXD9:ivH1JtJQQF19SsqEzC5DmdSW41s; ds_user=potatomayl; igfl=potatomayl; ds_user_id=123456789; mid=XVLRpwABAAG_kqYiZihqukSRfL9F; shbts=1565942622.665477; sessionid=123456789%2A3CEmcOySZOVzk9%3A2; csrftoken=ap6Xt3UkFaHlx6ALQMPnwkIi9mGVJ1kB; shbid=13717; rur=FRC; is_starred_enabled=yes'

'https://i.instagram.com/api/v1/discover/topical_explore/?is_prefetch=true&omit_cover_media=true&use_sectional_payload=true&timezone_offset=-14400&session_id=e94f7de2-8b68-452b-84e2-2ce83f7382ee&include_fixed_destinations=true'
```
___
## direct_v2/inbox [GET]
### Request
```
https://i.instagram.com/api/v1/direct_v2/inbox/?visual_message_return_type=unseen&persistentBadging=true&limit=0
```
### Headers
```
X-Pigeon-Session-Id: 140864b2-5517-4d55-85b4-0e0401423dae
X-Pigeon-Rawclienttime: 1565942625.938
X-IG-Connection-Speed: -1kbps
X-IG-Bandwidth-Speed-KBPS: 4911.635
X-IG-Bandwidth-TotalBytes-B: 1089468
X-IG-Bandwidth-TotalTime-MS: 382
X-IG-Prefetch-Request: foreground
X-IG-VP9-Capable: false
X-Bloks-Version-Id: 14f543394cf83e14784db6457e197a7e61e34fcd161891682143f74cb69a8981
X-IG-Connection-Type: WIFI
X-IG-Capabilities: 3brTvw==
X-IG-App-ID: 567067343352427
User-Agent: Instagram 103.1.0.15.119 Android (28/9; 420dpi; 1080x2034; unknown/Android; Google Pixel 3; vbox86p; vbox86; en_US; 164094540)
Accept-Language: en-US
Cookie: urlgen={\"2.32.17.241\": 30722}:1hyXD9:ivH1JtJQQF19SsqEzC5DmdSW41s; ds_user=potatomayl; igfl=potatomayl; ds_user_id=123456789; mid=XVLRpwABAAG_kqYiZihqukSRfL9F; shbts=1565942622.665477; sessionid=123456789%2A3CEmcOySZOVzk9%3A2; csrftoken=ap6Xt3UkFaHlx6ALQMPnwkIi9mGVJ1kB; shbid=13717; rur=FRC; is_starred_enabled=yes
Accept-Encoding: gzip, deflate
Host: i.instagram.com
X-FB-HTTP-Engine: Liger
Connection: close
```
### CURL Command
```
curl -i -s -k  -X 'GET'

-H 'X-Pigeon-Session-Id: 140864b2-5517-4d55-85b4-0e0401423dae' -H 'X-Pigeon-Rawclienttime: 1565942625.938' -H 'X-IG-Connection-Speed: -1kbps' -H 'X-IG-Bandwidth-Speed-KBPS: 4911.635' -H 'X-IG-Bandwidth-TotalBytes-B: 1089468' -H 'X-IG-Bandwidth-TotalTime-MS: 382' -H 'X-IG-Prefetch-Request: foreground' -H 'X-IG-VP9-Capable: false' -H 'X-Bloks-Version-Id: 14f543394cf83e14784db6457e197a7e61e34fcd161891682143f74cb69a8981' -H 'X-IG-Connection-Type: WIFI' -H 'X-IG-Capabilities: 3brTvw==' -H 'X-IG-App-ID: 567067343352427' -H 'User-Agent: Instagram 103.1.0.15.119 Android (28/9; 420dpi; 1080x2034; unknown/Android; Google Pixel 3; vbox86p; vbox86; en_US; 164094540)' -H 'Accept-Language: en-US' -H 'Cookie: urlgen={\\\"2.32.17.241\\\": 30722}:1hyXD9:ivH1JtJQQF19SsqEzC5DmdSW41s; ds_user=potatomayl; igfl=potatomayl; ds_user_id=123456789; mid=XVLRpwABAAG_kqYiZihqukSRfL9F; shbts=1565942622.665477; sessionid=123456789%2A3CEmcOySZOVzk9%3A2; csrftoken=ap6Xt3UkFaHlx6ALQMPnwkIi9mGVJ1kB; shbid=13717; rur=FRC; is_starred_enabled=yes' -H 'Accept-Encoding: gzip, deflate' -H 'Host: i.instagram.com' -H 'X-FB-HTTP-Engine: Liger' -H 'Connection: close'

-b 'urlgen={\\\"2.32.17.241\\\": 30722}:1hyXD9:ivH1JtJQQF19SsqEzC5DmdSW41s; ds_user=potatomayl; igfl=potatomayl; ds_user_id=123456789; mid=XVLRpwABAAG_kqYiZihqukSRfL9F; shbts=1565942622.665477; sessionid=123456789%2A3CEmcOySZOVzk9%3A2; csrftoken=ap6Xt3UkFaHlx6ALQMPnwkIi9mGVJ1kB; shbid=13717; rur=FRC; is_starred_enabled=yes'

'https://i.instagram.com/api/v1/direct_v2/inbox/?visual_message_return_type=unseen&persistentBadging=true&limit=0'
```
___
## bootstrap/users [GET]
### Request encoded
```
https://i.instagram.com/api/v1/scores/bootstrap/users/?surfaces=%5B%22autocomplete_user_list%22%2C%22coefficient_besties_list_ranking%22%2C%22coefficient_rank_recipient_user_suggestion%22%2C%22coefficient_ios_section_test_bootstrap_ranking%22%2C%22coefficient_direct_recipients_ranking_variant_2%22%5D
```
### Request decoded
```
https://i.instagram.com/api/v1/scores/bootstrap/users/?surfaces=["autocomplete_user_list","coefficient_besties_list_ranking","coefficient_rank_recipient_user_suggestion","coefficient_ios_section_test_bootstrap_ranking","coefficient_direct_recipients_ranking_variant_2"]
```
### Headers
```
X-Pigeon-Session-Id: 140864b2-5517-4d55-85b4-0e0401423dae
X-Pigeon-Rawclienttime: 1565942626.358
X-IG-Connection-Speed: -1kbps
X-IG-Bandwidth-Speed-KBPS: 2687.834
X-IG-Bandwidth-TotalBytes-B: 2071175
X-IG-Bandwidth-TotalTime-MS: 771
X-IG-VP9-Capable: false
X-Bloks-Version-Id: 14f543394cf83e14784db6457e197a7e61e34fcd161891682143f74cb69a8981
X-IG-Connection-Type: WIFI
X-IG-Capabilities: 3brTvw==
X-IG-App-ID: 567067343352427
User-Agent: Instagram 103.1.0.15.119 Android (28/9; 420dpi; 1080x2034; unknown/Android; Google Pixel 3; vbox86p; vbox86; en_US; 164094540)
Accept-Language: en-US
Cookie: urlgen={\"2.32.17.241\": 30722}:1hyXD9:ivH1JtJQQF19SsqEzC5DmdSW41s; ds_user=potatomayl; igfl=potatomayl; ds_user_id=123456789; mid=XVLRpwABAAG_kqYiZihqukSRfL9F; shbts=1565942622.665477; sessionid=123456789%2A3CEmcOySZOVzk9%3A2; csrftoken=ap6Xt3UkFaHlx6ALQMPnwkIi9mGVJ1kB; shbid=13717; rur=FRC; is_starred_enabled=yes
Accept-Encoding: gzip, deflate
Host: i.instagram.com
X-FB-HTTP-Engine: Liger
Connection: close
```
### CURL Command
```
curl -i -s -k  -X 'GET'

-H 'X-Pigeon-Session-Id: 140864b2-5517-4d55-85b4-0e0401423dae' -H 'X-Pigeon-Rawclienttime: 1565942626.358' -H 'X-IG-Connection-Speed: -1kbps' -H 'X-IG-Bandwidth-Speed-KBPS: 2687.834' -H 'X-IG-Bandwidth-TotalBytes-B: 2071175' -H 'X-IG-Bandwidth-TotalTime-MS: 771' -H 'X-IG-VP9-Capable: false' -H 'X-Bloks-Version-Id: 14f543394cf83e14784db6457e197a7e61e34fcd161891682143f74cb69a8981' -H 'X-IG-Connection-Type: WIFI' -H 'X-IG-Capabilities: 3brTvw==' -H 'X-IG-App-ID: 567067343352427' -H 'User-Agent: Instagram 103.1.0.15.119 Android (28/9; 420dpi; 1080x2034; unknown/Android; Google Pixel 3; vbox86p; vbox86; en_US; 164094540)' -H 'Accept-Language: en-US' -H 'Cookie: urlgen={\\\"2.32.17.241\\\": 30722}:1hyXD9:ivH1JtJQQF19SsqEzC5DmdSW41s; ds_user=potatomayl; igfl=potatomayl; ds_user_id=123456789; mid=XVLRpwABAAG_kqYiZihqukSRfL9F; shbts=1565942622.665477; sessionid=123456789%2A3CEmcOySZOVzk9%3A2; csrftoken=ap6Xt3UkFaHlx6ALQMPnwkIi9mGVJ1kB; shbid=13717; rur=FRC; is_starred_enabled=yes' -H 'Accept-Encoding: gzip, deflate' -H 'Host: i.instagram.com' -H 'X-FB-HTTP-Engine: Liger' -H 'Connection: close'

-b 'urlgen={\\\"2.32.17.241\\\": 30722}:1hyXD9:ivH1JtJQQF19SsqEzC5DmdSW41s; ds_user=potatomayl; igfl=potatomayl; ds_user_id=123456789; mid=XVLRpwABAAG_kqYiZihqukSRfL9F; shbts=1565942622.665477; sessionid=123456789%2A3CEmcOySZOVzk9%3A2; csrftoken=ap6Xt3UkFaHlx6ALQMPnwkIi9mGVJ1kB; shbid=13717; rur=FRC; is_starred_enabled=yes'

'https://i.instagram.com/api/v1/scores/bootstrap/users/?surfaces=%5B%22autocomplete_user_list%22%2C%22coefficient_besties_list_ranking%22%2C%22coefficient_rank_recipient_user_suggestion%22%2C%22coefficient_ios_section_test_bootstrap_ranking%22%2C%22coefficient_direct_recipients_ranking_variant_2%22%5D'
```
___
