# CHAIN-ACTIONS
### From home-page to user => media. Like, save and command chain actions.

## topsearch_flat [GET] (search user)
### Request
```
https://i.instagram.com/api/v1/fbsearch/topsearch_flat/?timezone_offset=-14400&count=30&query=preta&context=blended
```
### Headers
```
X-Pigeon-Session-Id: f66adecf-9b43-4d39-929a-f7a1dab624b9
X-Pigeon-Rawclienttime: 1566154946.442
X-IG-Connection-Speed: 8054kbps
X-IG-Bandwidth-Speed-KBPS: 2471.987
X-IG-Bandwidth-TotalBytes-B: 5339105
X-IG-Bandwidth-TotalTime-MS: 9687
X-IG-VP9-Capable: false
X-Bloks-Version-Id: 14f543394cf83e14784db6457e197a7e61e34fcd161891682143f74cb69a8981
X-IG-Connection-Type: WIFI
X-IG-Capabilities: 3brTvw==
X-IG-App-ID: 567067343352427
User-Agent: Instagram 103.1.0.15.119 Android (28/9; 420dpi; 1080x2034; unknown/Android; Google Pixel 3; vbox86p; vbox86; en_US; 164094540)
Accept-Language: en-US
Cookie: urlgen={\"100.122.249.137\": 30722}:1hzQRS:kNl0sSGh0vRFH3QHgLRjDHnRhMg; ig_direct_region_hint=LLA; ds_user=potatomayl; igfl=potatomayl; ds_user_id=6578241026; mid=XVLRpwABAAG_kqYiZihqukSRfL9F; shbts=1566139954.4433396; sessionid=6578241026%3AKSVy2v5SQ9eCbK%3A2; csrftoken=8z78A9VVEAIcDGi9eM7GXpAnbly1245h; shbid=13717; rur=FRC; is_starred_enabled=yes
Accept-Encoding: gzip, deflate
Host: i.instagram.com
X-FB-HTTP-Engine: Liger
Connection: close
```
### CURL Command
```
curl -i -s -k  -X 'GET'

-H 'X-Pigeon-Session-Id: f66adecf-9b43-4d39-929a-f7a1dab624b9' -H 'X-Pigeon-Rawclienttime: 1566154946.442' -H 'X-IG-Connection-Speed: 8054kbps' -H 'X-IG-Bandwidth-Speed-KBPS: 2471.987' -H 'X-IG-Bandwidth-TotalBytes-B: 5339105' -H 'X-IG-Bandwidth-TotalTime-MS: 9687' -H 'X-IG-VP9-Capable: false' -H 'X-Bloks-Version-Id: 14f543394cf83e14784db6457e197a7e61e34fcd161891682143f74cb69a8981' -H 'X-IG-Connection-Type: WIFI' -H 'X-IG-Capabilities: 3brTvw==' -H 'X-IG-App-ID: 567067343352427' -H 'User-Agent: Instagram 103.1.0.15.119 Android (28/9; 420dpi; 1080x2034; unknown/Android; Google Pixel 3; vbox86p; vbox86; en_US; 164094540)' -H 'Accept-Language: en-US' -H 'Cookie: urlgen={\\\"100.122.249.137\\\": 30722}:1hzQRS:kNl0sSGh0vRFH3QHgLRjDHnRhMg; ig_direct_region_hint=LLA; ds_user=potatomayl; igfl=potatomayl; ds_user_id=6578241026; mid=XVLRpwABAAG_kqYiZihqukSRfL9F; shbts=1566139954.4433396; sessionid=6578241026%3AKSVy2v5SQ9eCbK%3A2; csrftoken=8z78A9VVEAIcDGi9eM7GXpAnbly1245h; shbid=13717; rur=FRC; is_starred_enabled=yes' -H 'Accept-Encoding: gzip, deflate' -H 'Host: i.instagram.com' -H 'X-FB-HTTP-Engine: Liger' -H 'Connection: close'

-b 'urlgen={\\\"100.122.249.137\\\": 30722}:1hzQRS:kNl0sSGh0vRFH3QHgLRjDHnRhMg; ig_direct_region_hint=LLA; ds_user=potatomayl; igfl=potatomayl; ds_user_id=6578241026; mid=XVLRpwABAAG_kqYiZihqukSRfL9F; shbts=1566139954.4433396; sessionid=6578241026%3AKSVy2v5SQ9eCbK%3A2; csrftoken=8z78A9VVEAIcDGi9eM7GXpAnbly1245h; shbid=13717; rur=FRC; is_starred_enabled=yes'

'https://i.instagram.com/api/v1/fbsearch/topsearch_flat/?timezone_offset=-14400&count=30&query=preta&context=blended'
```
___
## friendships/show [GET]
### Request
```
https://i.instagram.com/api/v1/friendships/show/6853370264/
```
### Headers
```
X-Pigeon-Session-Id: f66adecf-9b43-4d39-929a-f7a1dab624b9
X-Pigeon-Rawclienttime: 1566154950.769
X-IG-Connection-Speed: 6642kbps
X-IG-Bandwidth-Speed-KBPS: 2471.987
X-IG-Bandwidth-TotalBytes-B: 5339105
X-IG-Bandwidth-TotalTime-MS: 9687
X-IG-VP9-Capable: false
X-Bloks-Version-Id: 14f543394cf83e14784db6457e197a7e61e34fcd161891682143f74cb69a8981
X-IG-Connection-Type: WIFI
X-IG-Capabilities: 3brTvw==
X-IG-App-ID: 567067343352427
User-Agent: Instagram 103.1.0.15.119 Android (28/9; 420dpi; 1080x2034; unknown/Android; Google Pixel 3; vbox86p; vbox86; en_US; 164094540)
Accept-Language: en-US
Cookie: urlgen={\"100.122.249.137\": 30722}:1hzQRh:r4MRHIusNlNO7Vk3syiLdyKEtbw; ig_direct_region_hint=LLA; ds_user=potatomayl; igfl=potatomayl; ds_user_id=6578241026; mid=XVLRpwABAAG_kqYiZihqukSRfL9F; shbts=1566139954.4433396; sessionid=6578241026%3AKSVy2v5SQ9eCbK%3A2; csrftoken=8z78A9VVEAIcDGi9eM7GXpAnbly1245h; shbid=13717; rur=FRC; is_starred_enabled=yes
Accept-Encoding: gzip, deflate
Host: i.instagram.com
X-FB-HTTP-Engine: Liger
Connection: close
```
### CURL Command
```
curl -i -s -k  -X 'GET'

-H 'X-Pigeon-Session-Id: f66adecf-9b43-4d39-929a-f7a1dab624b9' -H 'X-Pigeon-Rawclienttime: 1566154950.769' -H 'X-IG-Connection-Speed: 6642kbps' -H 'X-IG-Bandwidth-Speed-KBPS: 2471.987' -H 'X-IG-Bandwidth-TotalBytes-B: 5339105' -H 'X-IG-Bandwidth-TotalTime-MS: 9687' -H 'X-IG-VP9-Capable: false' -H 'X-Bloks-Version-Id: 14f543394cf83e14784db6457e197a7e61e34fcd161891682143f74cb69a8981' -H 'X-IG-Connection-Type: WIFI' -H 'X-IG-Capabilities: 3brTvw==' -H 'X-IG-App-ID: 567067343352427' -H 'User-Agent: Instagram 103.1.0.15.119 Android (28/9; 420dpi; 1080x2034; unknown/Android; Google Pixel 3; vbox86p; vbox86; en_US; 164094540)' -H 'Accept-Language: en-US' -H 'Cookie: urlgen={\\\"100.122.249.137\\\": 30722}:1hzQRh:r4MRHIusNlNO7Vk3syiLdyKEtbw; ig_direct_region_hint=LLA; ds_user=potatomayl; igfl=potatomayl; ds_user_id=6578241026; mid=XVLRpwABAAG_kqYiZihqukSRfL9F; shbts=1566139954.4433396; sessionid=6578241026%3AKSVy2v5SQ9eCbK%3A2; csrftoken=8z78A9VVEAIcDGi9eM7GXpAnbly1245h; shbid=13717; rur=FRC; is_starred_enabled=yes' -H 'Accept-Encoding: gzip, deflate' -H 'Host: i.instagram.com' -H 'X-FB-HTTP-Engine: Liger' -H 'Connection: close'

-b 'urlgen={\\\"100.122.249.137\\\": 30722}:1hzQRh:r4MRHIusNlNO7Vk3syiLdyKEtbw; ig_direct_region_hint=LLA; ds_user=potatomayl; igfl=potatomayl; ds_user_id=6578241026; mid=XVLRpwABAAG_kqYiZihqukSRfL9F; shbts=1566139954.4433396; sessionid=6578241026%3AKSVy2v5SQ9eCbK%3A2; csrftoken=8z78A9VVEAIcDGi9eM7GXpAnbly1245h; shbid=13717; rur=FRC; is_starred_enabled=yes'

'https://i.instagram.com/api/v1/friendships/show/6853370264/'
```
___
## feed/user/story [POST/GET]
### Request encoded
```
https://i.instagram.com/api/v1/feed/user/6853370264/story/?supported_capabilities_new=%5B%7B%22name%22%3A%22SUPPORTED_SDK_VERSIONS%22%2C%22value%22%3A%2213.0%2C14.0%2C15.0%2C16.0%2C17.0%2C18.0%2C19.0%2C20.0%2C21.0%2C22.0%2C23.0%2C24.0%2C25.0%2C26.0%2C27.0%2C28.0%2C29.0%2C30.0%2C31.0%2C32.0%2C33.0%2C34.0%2C35.0%2C36.0%2C37.0%2C38.0%2C39.0%2C40.0%2C41.0%2C42.0%2C43.0%2C44.0%2C45.0%2C46.0%2C47.0%2C48.0%2C49.0%2C50.0%2C51.0%2C52.0%2C53.0%2C54.0%2C55.0%2C56.0%2C57.0%2C58.0%2C59.0%2C60.0%2C61.0%2C62.0%2C63.0%2C64.0%2C65.0%2C66.0%2C67.0%22%7D%2C%7B%22name%22%3A%22FACE_TRACKER_VERSION%22%2C%22value%22%3A%2212%22%7D%2C%7B%22name%22%3A%22COMPRESSION%22%2C%22value%22%3A%22ETC2_COMPRESSION%22%7D%2C%7B%22name%22%3A%22world_tracker%22%2C%22value%22%3A%22world_tracker_enabled%22%7D%5D
```
### Request decoded
```
https://i.instagram.com/api/v1/feed/user/6853370264/story/?supported_capabilities_new=[{"name":"SUPPORTED_SDK_VERSIONS","value":"13.0,14.0,15.0,16.0,17.0,18.0,19.0,20.0,21.0,22.0,23.0,24.0,25.0,26.0,27.0,28.0,29.0,30.0,31.0,32.0,33.0,34.0,35.0,36.0,37.0,38.0,39.0,40.0,41.0,42.0,43.0,44.0,45.0,46.0,47.0,48.0,49.0,50.0,51.0,52.0,53.0,54.0,55.0,56.0,57.0,58.0,59.0,60.0,61.0,62.0,63.0,64.0,65.0,66.0,67.0"},{"name":"FACE_TRACKER_VERSION","value":"12"},{"name":"COMPRESSION","value":"ETC2_COMPRESSION"},{"name":"world_tracker","value":"world_tracker_enabled"}]
```
### Headers
```
X-Pigeon-Session-Id: f66adecf-9b43-4d39-929a-f7a1dab624b9
X-Pigeon-Rawclienttime: 1566154950.827
X-IG-Connection-Speed: 6642kbps
X-IG-Bandwidth-Speed-KBPS: 2471.987
X-IG-Bandwidth-TotalBytes-B: 5339105
X-IG-Bandwidth-TotalTime-MS: 9687
X-IG-VP9-Capable: false
X-Bloks-Version-Id: 14f543394cf83e14784db6457e197a7e61e34fcd161891682143f74cb69a8981
X-IG-Connection-Type: WIFI
X-IG-Capabilities: 3brTvw==
X-IG-App-ID: 567067343352427
User-Agent: Instagram 103.1.0.15.119 Android (28/9; 420dpi; 1080x2034; unknown/Android; Google Pixel 3; vbox86p; vbox86; en_US; 164094540)
Accept-Language: en-US
Cookie: urlgen={\"100.122.249.137\": 30722}:1hzQRh:r4MRHIusNlNO7Vk3syiLdyKEtbw; ig_direct_region_hint=LLA; ds_user=potatomayl; igfl=potatomayl; ds_user_id=6578241026; mid=XVLRpwABAAG_kqYiZihqukSRfL9F; shbts=1566139954.4433396; sessionid=6578241026%3AKSVy2v5SQ9eCbK%3A2; csrftoken=8z78A9VVEAIcDGi9eM7GXpAnbly1245h; shbid=13717; rur=FRC; is_starred_enabled=yes
Accept-Encoding: gzip, deflate
Host: i.instagram.com
X-FB-HTTP-Engine: Liger
Connection: close
```
### CURL Command
```
curl -i -s -k  -X 'GET'

-H 'X-Pigeon-Session-Id: f66adecf-9b43-4d39-929a-f7a1dab624b9' -H 'X-Pigeon-Rawclienttime: 1566154950.827' -H 'X-IG-Connection-Speed: 6642kbps' -H 'X-IG-Bandwidth-Speed-KBPS: 2471.987' -H 'X-IG-Bandwidth-TotalBytes-B: 5339105' -H 'X-IG-Bandwidth-TotalTime-MS: 9687' -H 'X-IG-VP9-Capable: false' -H 'X-Bloks-Version-Id: 14f543394cf83e14784db6457e197a7e61e34fcd161891682143f74cb69a8981' -H 'X-IG-Connection-Type: WIFI' -H 'X-IG-Capabilities: 3brTvw==' -H 'X-IG-App-ID: 567067343352427' -H 'User-Agent: Instagram 103.1.0.15.119 Android (28/9; 420dpi; 1080x2034; unknown/Android; Google Pixel 3; vbox86p; vbox86; en_US; 164094540)' -H 'Accept-Language: en-US' -H 'Cookie: urlgen={\\\"100.122.249.137\\\": 30722}:1hzQRh:r4MRHIusNlNO7Vk3syiLdyKEtbw; ig_direct_region_hint=LLA; ds_user=potatomayl; igfl=potatomayl; ds_user_id=6578241026; mid=XVLRpwABAAG_kqYiZihqukSRfL9F; shbts=1566139954.4433396; sessionid=6578241026%3AKSVy2v5SQ9eCbK%3A2; csrftoken=8z78A9VVEAIcDGi9eM7GXpAnbly1245h; shbid=13717; rur=FRC; is_starred_enabled=yes' -H 'Accept-Encoding: gzip, deflate' -H 'Host: i.instagram.com' -H 'X-FB-HTTP-Engine: Liger' -H 'Connection: close'

-b 'urlgen={\\\"100.122.249.137\\\": 30722}:1hzQRh:r4MRHIusNlNO7Vk3syiLdyKEtbw; ig_direct_region_hint=LLA; ds_user=potatomayl; igfl=potatomayl; ds_user_id=6578241026; mid=XVLRpwABAAG_kqYiZihqukSRfL9F; shbts=1566139954.4433396; sessionid=6578241026%3AKSVy2v5SQ9eCbK%3A2; csrftoken=8z78A9VVEAIcDGi9eM7GXpAnbly1245h; shbid=13717; rur=FRC; is_starred_enabled=yes'

'https://i.instagram.com/api/v1/feed/user/6853370264/story/?supported_capabilities_new=%5B%7B%22name%22%3A%22SUPPORTED_SDK_VERSIONS%22%2C%22value%22%3A%2213.0%2C14.0%2C15.0%2C16.0%2C17.0%2C18.0%2C19.0%2C20.0%2C21.0%2C22.0%2C23.0%2C24.0%2C25.0%2C26.0%2C27.0%2C28.0%2C29.0%2C30.0%2C31.0%2C32.0%2C33.0%2C34.0%2C35.0%2C36.0%2C37.0%2C38.0%2C39.0%2C40.0%2C41.0%2C42.0%2C43.0%2C44.0%2C45.0%2C46.0%2C47.0%2C48.0%2C49.0%2C50.0%2C51.0%2C52.0%2C53.0%2C54.0%2C55.0%2C56.0%2C57.0%2C58.0%2C59.0%2C60.0%2C61.0%2C62.0%2C63.0%2C64.0%2C65.0%2C66.0%2C67.0%22%7D%2C%7B%22name%22%3A%22FACE_TRACKER_VERSION%22%2C%22value%22%3A%2212%22%7D%2C%7B%22name%22%3A%22COMPRESSION%22%2C%22value%22%3A%22ETC2_COMPRESSION%22%7D%2C%7B%22name%22%3A%22world_tracker%22%2C%22value%22%3A%22world_tracker_enabled%22%7D%5D'
```
___
## users/info [GET]
### Request
```
https://i.instagram.com/api/v1/users/6853370264/info/
```
### Headers
```
X-Pigeon-Session-Id: f66adecf-9b43-4d39-929a-f7a1dab624b9
X-Pigeon-Rawclienttime: 1566154950.828
X-IG-Connection-Speed: 6642kbps
X-IG-Bandwidth-Speed-KBPS: 2471.987
X-IG-Bandwidth-TotalBytes-B: 5339105
X-IG-Bandwidth-TotalTime-MS: 9687
X-IG-VP9-Capable: false
X-Bloks-Version-Id: 14f543394cf83e14784db6457e197a7e61e34fcd161891682143f74cb69a8981
X-IG-Connection-Type: WIFI
X-IG-Capabilities: 3brTvw==
X-IG-App-ID: 567067343352427
User-Agent: Instagram 103.1.0.15.119 Android (28/9; 420dpi; 1080x2034; unknown/Android; Google Pixel 3; vbox86p; vbox86; en_US; 164094540)
Accept-Language: en-US
Cookie: urlgen={\"100.122.249.137\": 30722}:1hzQRh:r4MRHIusNlNO7Vk3syiLdyKEtbw; ig_direct_region_hint=LLA; ds_user=potatomayl; igfl=potatomayl; ds_user_id=6578241026; mid=XVLRpwABAAG_kqYiZihqukSRfL9F; shbts=1566139954.4433396; sessionid=6578241026%3AKSVy2v5SQ9eCbK%3A2; csrftoken=8z78A9VVEAIcDGi9eM7GXpAnbly1245h; shbid=13717; rur=FRC; is_starred_enabled=yes
Accept-Encoding: gzip, deflate
Host: i.instagram.com
X-FB-HTTP-Engine: Liger
Connection: close
```
### CURL Command
```
curl -i -s -k  -X 'GET'

-H 'X-Pigeon-Session-Id: f66adecf-9b43-4d39-929a-f7a1dab624b9' -H 'X-Pigeon-Rawclienttime: 1566154950.828' -H 'X-IG-Connection-Speed: 6642kbps' -H 'X-IG-Bandwidth-Speed-KBPS: 2471.987' -H 'X-IG-Bandwidth-TotalBytes-B: 5339105' -H 'X-IG-Bandwidth-TotalTime-MS: 9687' -H 'X-IG-VP9-Capable: false' -H 'X-Bloks-Version-Id: 14f543394cf83e14784db6457e197a7e61e34fcd161891682143f74cb69a8981' -H 'X-IG-Connection-Type: WIFI' -H 'X-IG-Capabilities: 3brTvw==' -H 'X-IG-App-ID: 567067343352427' -H 'User-Agent: Instagram 103.1.0.15.119 Android (28/9; 420dpi; 1080x2034; unknown/Android; Google Pixel 3; vbox86p; vbox86; en_US; 164094540)' -H 'Accept-Language: en-US' -H 'Cookie: urlgen={\\\"100.122.249.137\\\": 30722}:1hzQRh:r4MRHIusNlNO7Vk3syiLdyKEtbw; ig_direct_region_hint=LLA; ds_user=potatomayl; igfl=potatomayl; ds_user_id=6578241026; mid=XVLRpwABAAG_kqYiZihqukSRfL9F; shbts=1566139954.4433396; sessionid=6578241026%3AKSVy2v5SQ9eCbK%3A2; csrftoken=8z78A9VVEAIcDGi9eM7GXpAnbly1245h; shbid=13717; rur=FRC; is_starred_enabled=yes' -H 'Accept-Encoding: gzip, deflate' -H 'Host: i.instagram.com' -H 'X-FB-HTTP-Engine: Liger' -H 'Connection: close'

-b 'urlgen={\\\"100.122.249.137\\\": 30722}:1hzQRh:r4MRHIusNlNO7Vk3syiLdyKEtbw; ig_direct_region_hint=LLA; ds_user=potatomayl; igfl=potatomayl; ds_user_id=6578241026; mid=XVLRpwABAAG_kqYiZihqukSRfL9F; shbts=1566139954.4433396; sessionid=6578241026%3AKSVy2v5SQ9eCbK%3A2; csrftoken=8z78A9VVEAIcDGi9eM7GXpAnbly1245h; shbid=13717; rur=FRC; is_starred_enabled=yes'

'https://i.instagram.com/api/v1/users/6853370264/info/'
```
___
## feed/user [GET]
### Request
```
https://i.instagram.com/api/v1/feed/user/6853370264/?exclude_comment=true&only_fetch_first_carousel_media=false
```
### Headers
```
X-Pigeon-Session-Id: f66adecf-9b43-4d39-929a-f7a1dab624b9
X-Pigeon-Rawclienttime: 1566154951.449
X-IG-Connection-Speed: 6642kbps
X-IG-Bandwidth-Speed-KBPS: 2471.987
X-IG-Bandwidth-TotalBytes-B: 5339105
X-IG-Bandwidth-TotalTime-MS: 9687
X-IG-VP9-Capable: false
X-Bloks-Version-Id: 14f543394cf83e14784db6457e197a7e61e34fcd161891682143f74cb69a8981
X-IG-Connection-Type: WIFI
X-IG-Capabilities: 3brTvw==
X-IG-App-ID: 567067343352427
User-Agent: Instagram 103.1.0.15.119 Android (28/9; 420dpi; 1080x2034; unknown/Android; Google Pixel 3; vbox86p; vbox86; en_US; 164094540)
Accept-Language: en-US
Cookie: urlgen={\"100.122.249.137\": 30722}:1hzQRl:fNGjky7TcQ8bPL2mps59ykeWTzY; ig_direct_region_hint=LLA; ds_user=potatomayl; igfl=potatomayl; ds_user_id=6578241026; mid=XVLRpwABAAG_kqYiZihqukSRfL9F; shbts=1566139954.4433396; sessionid=6578241026%3AKSVy2v5SQ9eCbK%3A2; csrftoken=8z78A9VVEAIcDGi9eM7GXpAnbly1245h; shbid=13717; rur=FRC; is_starred_enabled=yes
Accept-Encoding: gzip, deflate
Host: i.instagram.com
X-FB-HTTP-Engine: Liger
Connection: close
```
### CURL Command
```
curl -i -s -k  -X 'GET'

-H 'X-Pigeon-Session-Id: f66adecf-9b43-4d39-929a-f7a1dab624b9' -H 'X-Pigeon-Rawclienttime: 1566154951.449' -H 'X-IG-Connection-Speed: 6642kbps' -H 'X-IG-Bandwidth-Speed-KBPS: 2471.987' -H 'X-IG-Bandwidth-TotalBytes-B: 5339105' -H 'X-IG-Bandwidth-TotalTime-MS: 9687' -H 'X-IG-VP9-Capable: false' -H 'X-Bloks-Version-Id: 14f543394cf83e14784db6457e197a7e61e34fcd161891682143f74cb69a8981' -H 'X-IG-Connection-Type: WIFI' -H 'X-IG-Capabilities: 3brTvw==' -H 'X-IG-App-ID: 567067343352427' -H 'User-Agent: Instagram 103.1.0.15.119 Android (28/9; 420dpi; 1080x2034; unknown/Android; Google Pixel 3; vbox86p; vbox86; en_US; 164094540)' -H 'Accept-Language: en-US' -H 'Cookie: urlgen={\\\"100.122.249.137\\\": 30722}:1hzQRl:fNGjky7TcQ8bPL2mps59ykeWTzY; ig_direct_region_hint=LLA; ds_user=potatomayl; igfl=potatomayl; ds_user_id=6578241026; mid=XVLRpwABAAG_kqYiZihqukSRfL9F; shbts=1566139954.4433396; sessionid=6578241026%3AKSVy2v5SQ9eCbK%3A2; csrftoken=8z78A9VVEAIcDGi9eM7GXpAnbly1245h; shbid=13717; rur=FRC; is_starred_enabled=yes' -H 'Accept-Encoding: gzip, deflate' -H 'Host: i.instagram.com' -H 'X-FB-HTTP-Engine: Liger' -H 'Connection: close'

-b 'urlgen={\\\"100.122.249.137\\\": 30722}:1hzQRl:fNGjky7TcQ8bPL2mps59ykeWTzY; ig_direct_region_hint=LLA; ds_user=potatomayl; igfl=potatomayl; ds_user_id=6578241026; mid=XVLRpwABAAG_kqYiZihqukSRfL9F; shbts=1566139954.4433396; sessionid=6578241026%3AKSVy2v5SQ9eCbK%3A2; csrftoken=8z78A9VVEAIcDGi9eM7GXpAnbly1245h; shbid=13717; rur=FRC; is_starred_enabled=yes'

'https://i.instagram.com/api/v1/feed/user/6853370264/?exclude_comment=true&only_fetch_first_carousel_media=false'
```
___
## media/comment_infos [GET] (click the media)
### Request
```
https://i.instagram.com/api/v1/media/comment_infos/?media_ids=2113141109585887328_6853370264
```
### Headers
```
X-Pigeon-Session-Id: f66adecf-9b43-4d39-929a-f7a1dab624b9
X-Pigeon-Rawclienttime: 1566155414.973
X-IG-Connection-Speed: 6642kbps
X-IG-Bandwidth-Speed-KBPS: 2471.987
X-IG-Bandwidth-TotalBytes-B: 5339105
X-IG-Bandwidth-TotalTime-MS: 9687
X-IG-VP9-Capable: false
X-Bloks-Version-Id: 14f543394cf83e14784db6457e197a7e61e34fcd161891682143f74cb69a8981
X-IG-Connection-Type: WIFI
X-IG-Capabilities: 3brTvw==
X-IG-App-ID: 567067343352427
User-Agent: Instagram 103.1.0.15.119 Android (28/9; 420dpi; 1080x2034; unknown/Android; Google Pixel 3; vbox86p; vbox86; en_US; 164094540)
Accept-Language: en-US
Cookie: urlgen={\"100.122.249.137\": 30722}:1hzQRm:e1dGiQxBDGwoHdZY0MAv7m2sXNo; ig_direct_region_hint=LLA; ds_user=potatomayl; igfl=potatomayl; ds_user_id=6578241026; mid=XVLRpwABAAG_kqYiZihqukSRfL9F; shbts=1566139954.4433396; sessionid=6578241026%3AKSVy2v5SQ9eCbK%3A2; csrftoken=8z78A9VVEAIcDGi9eM7GXpAnbly1245h; shbid=13717; rur=FRC; is_starred_enabled=yes
Accept-Encoding: gzip, deflate
Host: i.instagram.com
X-FB-HTTP-Engine: Liger
Connection: close
```
### CURL Command
```
curl -i -s -k  -X 'GET'

-H 'X-Pigeon-Session-Id: f66adecf-9b43-4d39-929a-f7a1dab624b9' -H 'X-Pigeon-Rawclienttime: 1566155414.973' -H 'X-IG-Connection-Speed: 6642kbps' -H 'X-IG-Bandwidth-Speed-KBPS: 2471.987' -H 'X-IG-Bandwidth-TotalBytes-B: 5339105' -H 'X-IG-Bandwidth-TotalTime-MS: 9687' -H 'X-IG-VP9-Capable: false' -H 'X-Bloks-Version-Id: 14f543394cf83e14784db6457e197a7e61e34fcd161891682143f74cb69a8981' -H 'X-IG-Connection-Type: WIFI' -H 'X-IG-Capabilities: 3brTvw==' -H 'X-IG-App-ID: 567067343352427' -H 'User-Agent: Instagram 103.1.0.15.119 Android (28/9; 420dpi; 1080x2034; unknown/Android; Google Pixel 3; vbox86p; vbox86; en_US; 164094540)' -H 'Accept-Language: en-US' -H 'Cookie: urlgen={\\\"100.122.249.137\\\": 30722}:1hzQRm:e1dGiQxBDGwoHdZY0MAv7m2sXNo; ig_direct_region_hint=LLA; ds_user=potatomayl; igfl=potatomayl; ds_user_id=6578241026; mid=XVLRpwABAAG_kqYiZihqukSRfL9F; shbts=1566139954.4433396; sessionid=6578241026%3AKSVy2v5SQ9eCbK%3A2; csrftoken=8z78A9VVEAIcDGi9eM7GXpAnbly1245h; shbid=13717; rur=FRC; is_starred_enabled=yes' -H 'Accept-Encoding: gzip, deflate' -H 'Host: i.instagram.com' -H 'X-FB-HTTP-Engine: Liger' -H 'Connection: close'

-b 'urlgen={\\\"100.122.249.137\\\": 30722}:1hzQRm:e1dGiQxBDGwoHdZY0MAv7m2sXNo; ig_direct_region_hint=LLA; ds_user=potatomayl; igfl=potatomayl; ds_user_id=6578241026; mid=XVLRpwABAAG_kqYiZihqukSRfL9F; shbts=1566139954.4433396; sessionid=6578241026%3AKSVy2v5SQ9eCbK%3A2; csrftoken=8z78A9VVEAIcDGi9eM7GXpAnbly1245h; shbid=13717; rur=FRC; is_starred_enabled=yes'

'https://i.instagram.com/api/v1/media/comment_infos/?media_ids=2113141109585887328_6853370264'
```
___
## like [POST] (heart)
### Request
```
https://i.instagram.com/api/v1/media/2113323773613911713_6853370264/like/
```
### Headers
```
X-Pigeon-Session-Id: f66adecf-9b43-4d39-929a-f7a1dab624b9
X-Pigeon-Rawclienttime: 1566155454.523
X-IG-Connection-Speed: 6586kbps
X-IG-Bandwidth-Speed-KBPS: 2471.987
X-IG-Bandwidth-TotalBytes-B: 5339105
X-IG-Bandwidth-TotalTime-MS: 9687
X-IG-VP9-Capable: false
X-Bloks-Version-Id: 14f543394cf83e14784db6457e197a7e61e34fcd161891682143f74cb69a8981
X-IG-Connection-Type: WIFI
X-IG-Capabilities: 3brTvw==
X-IG-App-ID: 567067343352427
User-Agent: Instagram 103.1.0.15.119 Android (28/9; 420dpi; 1080x2034; unknown/Android; Google Pixel 3; vbox86p; vbox86; en_US; 164094540)
Accept-Language: en-US
Cookie: urlgen={\"100.122.249.137\": 30722}:1hzQZF:cABYRpo_oZ6uFLdRsn4e78eLHoM; ig_direct_region_hint=LLA; ds_user=potatomayl; igfl=potatomayl; ds_user_id=6578241026; mid=XVLRpwABAAG_kqYiZihqukSRfL9F; shbts=1566139954.4433396; sessionid=6578241026%3AKSVy2v5SQ9eCbK%3A2; csrftoken=8z78A9VVEAIcDGi9eM7GXpAnbly1245h; shbid=13717; rur=FRC; is_starred_enabled=yes
Content-Type: application/x-www-form-urlencoded; charset=UTF-8
Accept-Encoding: gzip, deflate
Host: i.instagram.com
X-FB-HTTP-Engine: Liger
Connection: close
Content-Length: 534
```
### Arguments encoded
```
signed_body=334956fcdb4d61d022915735792ebd91350660d98a17cb401526acac7d48f3a8.%7B%22media_id%22%3A%222113323773613911713_6853370264%22%2C%22_csrftoken%22%3A%228z78A9VVEAIcDGi9eM7GXpAnbly1245h%22%2C%22radio_type%22%3A%22wifi-none%22%2C%22_uid%22%3A%226578241026%22%2C%22device_id%22%3A%22android-3e3cde3b8e81d35%22%2C%22_uuid%22%3A%22ffbe7b2f-1663-43d4-847b-c3f51803637e%22%2C%22is_carousel_bumped_post%22%3A%22false%22%2C%22container_module%22%3A%22feed_contextual_profile%22%2C%22feed_position%22%3A%220%22%7D&ig_sig_key_version=4&d=0
```
### Arguments decoded
```
signed_body=334956fcdb4d61d022915735792ebd91350660d98a17cb401526acac7d48f3a8.{"media_id":"2113323773613911713_6853370264","_csrftoken":"8z78A9VVEAIcDGi9eM7GXpAnbly1245h","radio_type":"wifi-none","_uid":"6578241026","device_id":"android-3e3cde3b8e81d35","_uuid":"ffbe7b2f-1663-43d4-847b-c3f51803637e","is_carousel_bumped_post":"false","container_module":"feed_contextual_profile","feed_position":"0"}&ig_sig_key_version=4&d=0
```
### CURL Command
```
curl -i -s -k  -X 'POST'

-H 'X-Pigeon-Session-Id: f66adecf-9b43-4d39-929a-f7a1dab624b9' -H 'X-Pigeon-Rawclienttime: 1566155454.523' -H 'X-IG-Connection-Speed: 6586kbps' -H 'X-IG-Bandwidth-Speed-KBPS: 2471.987' -H 'X-IG-Bandwidth-TotalBytes-B: 5339105' -H 'X-IG-Bandwidth-TotalTime-MS: 9687' -H 'X-IG-VP9-Capable: false' -H 'X-Bloks-Version-Id: 14f543394cf83e14784db6457e197a7e61e34fcd161891682143f74cb69a8981' -H 'X-IG-Connection-Type: WIFI' -H 'X-IG-Capabilities: 3brTvw==' -H 'X-IG-App-ID: 567067343352427' -H 'User-Agent: Instagram 103.1.0.15.119 Android (28/9; 420dpi; 1080x2034; unknown/Android; Google Pixel 3; vbox86p; vbox86; en_US; 164094540)' -H 'Accept-Language: en-US' -H 'Cookie: urlgen={\\\"100.122.249.137\\\": 30722}:1hzQZF:cABYRpo_oZ6uFLdRsn4e78eLHoM; ig_direct_region_hint=LLA; ds_user=potatomayl; igfl=potatomayl; ds_user_id=6578241026; mid=XVLRpwABAAG_kqYiZihqukSRfL9F; shbts=1566139954.4433396; sessionid=6578241026%3AKSVy2v5SQ9eCbK%3A2; csrftoken=8z78A9VVEAIcDGi9eM7GXpAnbly1245h; shbid=13717; rur=FRC; is_starred_enabled=yes' -H 'Content-Type: application/x-www-form-urlencoded; charset=UTF-8' -H 'Accept-Encoding: gzip, deflate' -H 'Host: i.instagram.com' -H 'X-FB-HTTP-Engine: Liger' -H 'Connection: close' -H 'Content-Length: 534'

-b 'urlgen={\\\"100.122.249.137\\\": 30722}:1hzQZF:cABYRpo_oZ6uFLdRsn4e78eLHoM; ig_direct_region_hint=LLA; ds_user=potatomayl; igfl=potatomayl; ds_user_id=6578241026; mid=XVLRpwABAAG_kqYiZihqukSRfL9F; shbts=1566139954.4433396; sessionid=6578241026%3AKSVy2v5SQ9eCbK%3A2; csrftoken=8z78A9VVEAIcDGi9eM7GXpAnbly1245h; shbid=13717; rur=FRC; is_starred_enabled=yes'

--data-binary 'signed_body=334956fcdb4d61d022915735792ebd91350660d98a17cb401526acac7d48f3a8.%7B%22media_id%22%3A%222113323773613911713_6853370264%22%2C%22_csrftoken%22%3A%228z78A9VVEAIcDGi9eM7GXpAnbly1245h%22%2C%22radio_type%22%3A%22wifi-none%22%2C%22_uid%22%3A%226578241026%22%2C%22device_id%22%3A%22android-3e3cde3b8e81d35%22%2C%22_uuid%22%3A%22ffbe7b2f-1663-43d4-847b-c3f51803637e%22%2C%22is_carousel_bumped_post%22%3A%22false%22%2C%22container_module%22%3A%22feed_contextual_profile%22%2C%22feed_position%22%3A%220%22%7D&ig_sig_key_version=4&d=0'

'https://i.instagram.com/api/v1/media/2113323773613911713_6853370264/like/'
```
___
## like [POST] (double-tap)
### Request
```
https://i.instagram.com/api/v1/media/2113323773613911713_6853370264/like/
```
### Headers
```
X-Pigeon-Session-Id: f66adecf-9b43-4d39-929a-f7a1dab624b9
X-Pigeon-Rawclienttime: 1566155462.127
X-IG-Connection-Speed: 6586kbps
X-IG-Bandwidth-Speed-KBPS: 2471.987
X-IG-Bandwidth-TotalBytes-B: 5339105
X-IG-Bandwidth-TotalTime-MS: 9687
X-IG-VP9-Capable: false
X-Bloks-Version-Id: 14f543394cf83e14784db6457e197a7e61e34fcd161891682143f74cb69a8981
X-IG-Connection-Type: WIFI
X-IG-Capabilities: 3brTvw==
X-IG-App-ID: 567067343352427
User-Agent: Instagram 103.1.0.15.119 Android (28/9; 420dpi; 1080x2034; unknown/Android; Google Pixel 3; vbox86p; vbox86; en_US; 164094540)
Accept-Language: en-US
Cookie: urlgen={\"100.122.249.137\": 30722}:1hzQZw:Vc9ysKMhxsEkQ2S6729Q8-zrPXc; ig_direct_region_hint=LLA; ds_user=potatomayl; igfl=potatomayl; ds_user_id=6578241026; mid=XVLRpwABAAG_kqYiZihqukSRfL9F; shbts=1566139954.4433396; sessionid=6578241026%3AKSVy2v5SQ9eCbK%3A2; csrftoken=8z78A9VVEAIcDGi9eM7GXpAnbly1245h; shbid=13717; rur=FRC; is_starred_enabled=yes
Content-Type: application/x-www-form-urlencoded; charset=UTF-8
Accept-Encoding: gzip, deflate
Host: i.instagram.com
X-FB-HTTP-Engine: Liger
Connection: close
Content-Length: 534
```
### Arguments encoded
```
signed_body=334956fcdb4d61d022915735792ebd91350660d98a17cb401526acac7d48f3a8.%7B%22media_id%22%3A%222113323773613911713_6853370264%22%2C%22_csrftoken%22%3A%228z78A9VVEAIcDGi9eM7GXpAnbly1245h%22%2C%22radio_type%22%3A%22wifi-none%22%2C%22_uid%22%3A%226578241026%22%2C%22device_id%22%3A%22android-3e3cde3b8e81d35%22%2C%22_uuid%22%3A%22ffbe7b2f-1663-43d4-847b-c3f51803637e%22%2C%22is_carousel_bumped_post%22%3A%22false%22%2C%22container_module%22%3A%22feed_contextual_profile%22%2C%22feed_position%22%3A%220%22%7D&ig_sig_key_version=4&d=1
```
### Arguments decoded
```
signed_body=334956fcdb4d61d022915735792ebd91350660d98a17cb401526acac7d48f3a8.{"media_id":"2113323773613911713_6853370264","_csrftoken":"8z78A9VVEAIcDGi9eM7GXpAnbly1245h","radio_type":"wifi-none","_uid":"6578241026","device_id":"android-3e3cde3b8e81d35","_uuid":"ffbe7b2f-1663-43d4-847b-c3f51803637e","is_carousel_bumped_post":"false","container_module":"feed_contextual_profile","feed_position":"0"}&ig_sig_key_version=4&d=1
```
### CURL Command
```
curl -i -s -k  -X 'POST'

-H 'X-Pigeon-Session-Id: f66adecf-9b43-4d39-929a-f7a1dab624b9' -H 'X-Pigeon-Rawclienttime: 1566155462.127' -H 'X-IG-Connection-Speed: 6586kbps' -H 'X-IG-Bandwidth-Speed-KBPS: 2471.987' -H 'X-IG-Bandwidth-TotalBytes-B: 5339105' -H 'X-IG-Bandwidth-TotalTime-MS: 9687' -H 'X-IG-VP9-Capable: false' -H 'X-Bloks-Version-Id: 14f543394cf83e14784db6457e197a7e61e34fcd161891682143f74cb69a8981' -H 'X-IG-Connection-Type: WIFI' -H 'X-IG-Capabilities: 3brTvw==' -H 'X-IG-App-ID: 567067343352427' -H 'User-Agent: Instagram 103.1.0.15.119 Android (28/9; 420dpi; 1080x2034; unknown/Android; Google Pixel 3; vbox86p; vbox86; en_US; 164094540)' -H 'Accept-Language: en-US' -H 'Cookie: urlgen={\\\"100.122.249.137\\\": 30722}:1hzQZw:Vc9ysKMhxsEkQ2S6729Q8-zrPXc; ig_direct_region_hint=LLA; ds_user=potatomayl; igfl=potatomayl; ds_user_id=6578241026; mid=XVLRpwABAAG_kqYiZihqukSRfL9F; shbts=1566139954.4433396; sessionid=6578241026%3AKSVy2v5SQ9eCbK%3A2; csrftoken=8z78A9VVEAIcDGi9eM7GXpAnbly1245h; shbid=13717; rur=FRC; is_starred_enabled=yes' -H 'Content-Type: application/x-www-form-urlencoded; charset=UTF-8' -H 'Accept-Encoding: gzip, deflate' -H 'Host: i.instagram.com' -H 'X-FB-HTTP-Engine: Liger' -H 'Connection: close' -H 'Content-Length: 534'

-b 'urlgen={\\\"100.122.249.137\\\": 30722}:1hzQZw:Vc9ysKMhxsEkQ2S6729Q8-zrPXc; ig_direct_region_hint=LLA; ds_user=potatomayl; igfl=potatomayl; ds_user_id=6578241026; mid=XVLRpwABAAG_kqYiZihqukSRfL9F; shbts=1566139954.4433396; sessionid=6578241026%3AKSVy2v5SQ9eCbK%3A2; csrftoken=8z78A9VVEAIcDGi9eM7GXpAnbly1245h; shbid=13717; rur=FRC; is_starred_enabled=yes'

--data-binary 'signed_body=334956fcdb4d61d022915735792ebd91350660d98a17cb401526acac7d48f3a8.%7B%22media_id%22%3A%222113323773613911713_6853370264%22%2C%22_csrftoken%22%3A%228z78A9VVEAIcDGi9eM7GXpAnbly1245h%22%2C%22radio_type%22%3A%22wifi-none%22%2C%22_uid%22%3A%226578241026%22%2C%22device_id%22%3A%22android-3e3cde3b8e81d35%22%2C%22_uuid%22%3A%22ffbe7b2f-1663-43d4-847b-c3f51803637e%22%2C%22is_carousel_bumped_post%22%3A%22false%22%2C%22container_module%22%3A%22feed_contextual_profile%22%2C%22feed_position%22%3A%220%22%7D&ig_sig_key_version=4&d=1'

'https://i.instagram.com/api/v1/media/2113323773613911713_6853370264/like/'
```
___
## save [POST]
### Request
```
https://i.instagram.com/api/v1/media/2113323773613911713_6853370264/save/
```
### Headers
```
X-Pigeon-Session-Id: f66adecf-9b43-4d39-929a-f7a1dab624b9
X-Pigeon-Rawclienttime: 1566155472.432
X-IG-Connection-Speed: 6586kbps
X-IG-Bandwidth-Speed-KBPS: 2471.987
X-IG-Bandwidth-TotalBytes-B: 5339105
X-IG-Bandwidth-TotalTime-MS: 9687
X-IG-VP9-Capable: false
X-Bloks-Version-Id: 14f543394cf83e14784db6457e197a7e61e34fcd161891682143f74cb69a8981
X-IG-Connection-Type: WIFI
X-IG-Capabilities: 3brTvw==
X-IG-App-ID: 567067343352427
User-Agent: Instagram 103.1.0.15.119 Android (28/9; 420dpi; 1080x2034; unknown/Android; Google Pixel 3; vbox86p; vbox86; en_US; 164094540)
Accept-Language: en-US
Cookie: urlgen={\"100.122.249.137\": 30722}:1hzQa0:sLZwjJYJbx-8nHsgZ4GC6O1jmEI; ig_direct_region_hint=LLA; ds_user=potatomayl; igfl=potatomayl; ds_user_id=6578241026; mid=XVLRpwABAAG_kqYiZihqukSRfL9F; shbts=1566139954.4433396; sessionid=6578241026%3AKSVy2v5SQ9eCbK%3A2; csrftoken=8z78A9VVEAIcDGi9eM7GXpAnbly1245h; shbid=13717; rur=FRC; is_starred_enabled=yes
Content-Type: application/x-www-form-urlencoded; charset=UTF-8
Accept-Encoding: gzip, deflate
Host: i.instagram.com
X-FB-HTTP-Engine: Liger
Connection: close
Content-Length: 341
```
### Arguments encoded
```
signed_body=c7a32f766fc49eca323230f063d027d0d8b9e149c5f64afdeb1753b55473ff08.%7B%22module_name%22%3A%22feed_contextual_profile%22%2C%22_csrftoken%22%3A%228z78A9VVEAIcDGi9eM7GXpAnbly1245h%22%2C%22radio_type%22%3A%22wifi-none%22%2C%22_uid%22%3A%226578241026%22%2C%22_uuid%22%3A%22ffbe7b2f-1663-43d4-847b-c3f51803637e%22%7D&ig_sig_key_version=4
```
### Arguments decoded
```
signed_body=c7a32f766fc49eca323230f063d027d0d8b9e149c5f64afdeb1753b55473ff08.{"module_name":"feed_contextual_profile","_csrftoken":"8z78A9VVEAIcDGi9eM7GXpAnbly1245h","radio_type":"wifi-none","_uid":"6578241026","_uuid":"ffbe7b2f-1663-43d4-847b-c3f51803637e"}&ig_sig_key_version=4
```
### CURL Command
```
curl -i -s -k  -X 'POST'

-H 'X-Pigeon-Session-Id: f66adecf-9b43-4d39-929a-f7a1dab624b9' -H 'X-Pigeon-Rawclienttime: 1566155472.432' -H 'X-IG-Connection-Speed: 6586kbps' -H 'X-IG-Bandwidth-Speed-KBPS: 2471.987' -H 'X-IG-Bandwidth-TotalBytes-B: 5339105' -H 'X-IG-Bandwidth-TotalTime-MS: 9687' -H 'X-IG-VP9-Capable: false' -H 'X-Bloks-Version-Id: 14f543394cf83e14784db6457e197a7e61e34fcd161891682143f74cb69a8981' -H 'X-IG-Connection-Type: WIFI' -H 'X-IG-Capabilities: 3brTvw==' -H 'X-IG-App-ID: 567067343352427' -H 'User-Agent: Instagram 103.1.0.15.119 Android (28/9; 420dpi; 1080x2034; unknown/Android; Google Pixel 3; vbox86p; vbox86; en_US; 164094540)' -H 'Accept-Language: en-US' -H 'Cookie: urlgen={\\\"100.122.249.137\\\": 30722}:1hzQa0:sLZwjJYJbx-8nHsgZ4GC6O1jmEI; ig_direct_region_hint=LLA; ds_user=potatomayl; igfl=potatomayl; ds_user_id=6578241026; mid=XVLRpwABAAG_kqYiZihqukSRfL9F; shbts=1566139954.4433396; sessionid=6578241026%3AKSVy2v5SQ9eCbK%3A2; csrftoken=8z78A9VVEAIcDGi9eM7GXpAnbly1245h; shbid=13717; rur=FRC; is_starred_enabled=yes' -H 'Content-Type: application/x-www-form-urlencoded; charset=UTF-8' -H 'Accept-Encoding: gzip, deflate' -H 'Host: i.instagram.com' -H 'X-FB-HTTP-Engine: Liger' -H 'Connection: close' -H 'Content-Length: 341'

-b 'urlgen={\\\"100.122.249.137\\\": 30722}:1hzQa0:sLZwjJYJbx-8nHsgZ4GC6O1jmEI; ig_direct_region_hint=LLA; ds_user=potatomayl; igfl=potatomayl; ds_user_id=6578241026; mid=XVLRpwABAAG_kqYiZihqukSRfL9F; shbts=1566139954.4433396; sessionid=6578241026%3AKSVy2v5SQ9eCbK%3A2; csrftoken=8z78A9VVEAIcDGi9eM7GXpAnbly1245h; shbid=13717; rur=FRC; is_starred_enabled=yes'

--data-binary 'signed_body=c7a32f766fc49eca323230f063d027d0d8b9e149c5f64afdeb1753b55473ff08.%7B%22module_name%22%3A%22feed_contextual_profile%22%2C%22_csrftoken%22%3A%228z78A9VVEAIcDGi9eM7GXpAnbly1245h%22%2C%22radio_type%22%3A%22wifi-none%22%2C%22_uid%22%3A%226578241026%22%2C%22_uuid%22%3A%22ffbe7b2f-1663-43d4-847b-c3f51803637e%22%7D&ig_sig_key_version=4'

'https://i.instagram.com/api/v1/media/2113323773613911713_6853370264/save/'
```
___
## comment [POST]
### Request
```
https://i.instagram.com/api/v1/media/2113323773613911713_6853370264/comment/
```
### Headers
```
X-Pigeon-Session-Id: f66adecf-9b43-4d39-929a-f7a1dab624b9
X-Pigeon-Rawclienttime: 1566155478.809
X-IG-Connection-Speed: 6586kbps
X-IG-Bandwidth-Speed-KBPS: 2471.987
X-IG-Bandwidth-TotalBytes-B: 5339105
X-IG-Bandwidth-TotalTime-MS: 9687
X-IG-VP9-Capable: false
X-Bloks-Version-Id: 14f543394cf83e14784db6457e197a7e61e34fcd161891682143f74cb69a8981
X-IG-Connection-Type: WIFI
X-IG-Capabilities: 3brTvw==
X-IG-App-ID: 567067343352427
User-Agent: Instagram 103.1.0.15.119 Android (28/9; 420dpi; 1080x2034; unknown/Android; Google Pixel 3; vbox86p; vbox86; en_US; 164094540)
Accept-Language: en-US
Cookie: urlgen={\"100.122.249.137\": 30722}:1hzQaC:3H9QTDGxiCiwknGTLPWDWF_2lEU; ig_direct_region_hint=LLA; ds_user=potatomayl; igfl=potatomayl; ds_user_id=6578241026; mid=XVLRpwABAAG_kqYiZihqukSRfL9F; shbts=1566139954.4433396; sessionid=6578241026%3AKSVy2v5SQ9eCbK%3A2; csrftoken=8z78A9VVEAIcDGi9eM7GXpAnbly1245h; shbid=13717; rur=FRC; is_starred_enabled=yes
Content-Type: application/x-www-form-urlencoded; charset=UTF-8
Accept-Encoding: gzip, deflate
Host: i.instagram.com
X-FB-HTTP-Engine: Liger
Connection: close
Content-Length: 622
```
### Arguments encoded
```
signed_body=302871b2fd381f8ab90f43b2d9288da59b2ef42e6eb0aa1b5fc50bb6d55438cc.%7B%22user_breadcrumb%22%3A%22a2rDcCA%2FYHaavlT11I6rf8oNHyaIakiK%2B8na%2F1r3BYw%3D%5CnNiAyNTAxIDAgMTU2NjE1NTQ3ODQzMA%3D%3D%5Cn%22%2C%22idempotence_token%22%3A%2272013f10-c3ea-4bcf-a14d-1fa713034c07%22%2C%22_csrftoken%22%3A%228z78A9VVEAIcDGi9eM7GXpAnbly1245h%22%2C%22radio_type%22%3A%22wifi-none%22%2C%22_uid%22%3A%226578241026%22%2C%22device_id%22%3A%22android-3e3cde3b8e81d35%22%2C%22_uuid%22%3A%22ffbe7b2f-1663-43d4-847b-c3f51803637e%22%2C%22comment_text%22%3A%22Ciao+%21%22%2C%22container_module%22%3A%22comments_v2%22%7D&ig_sig_key_version=4
```
### Arguments decoded
```
signed_body=302871b2fd381f8ab90f43b2d9288da59b2ef42e6eb0aa1b5fc50bb6d55438cc.{"user_breadcrumb":"a2rDcCA/YHaavlT11I6rf8oNHyaIakiK+8na/1r3BYw=\nNiAyNTAxIDAgMTU2NjE1NTQ3ODQzMA==\n","idempotence_token":"72013f10-c3ea-4bcf-a14d-1fa713034c07","_csrftoken":"8z78A9VVEAIcDGi9eM7GXpAnbly1245h","radio_type":"wifi-none","_uid":"6578241026","device_id":"android-3e3cde3b8e81d35","_uuid":"ffbe7b2f-1663-43d4-847b-c3f51803637e","comment_text":"Ciao !","container_module":"comments_v2"}&ig_sig_key_version=4
```
### CURL Command
```
curl -i -s -k  -X 'POST'

-H 'X-Pigeon-Session-Id: f66adecf-9b43-4d39-929a-f7a1dab624b9' -H 'X-Pigeon-Rawclienttime: 1566155478.809' -H 'X-IG-Connection-Speed: 6586kbps' -H 'X-IG-Bandwidth-Speed-KBPS: 2471.987' -H 'X-IG-Bandwidth-TotalBytes-B: 5339105' -H 'X-IG-Bandwidth-TotalTime-MS: 9687' -H 'X-IG-VP9-Capable: false' -H 'X-Bloks-Version-Id: 14f543394cf83e14784db6457e197a7e61e34fcd161891682143f74cb69a8981' -H 'X-IG-Connection-Type: WIFI' -H 'X-IG-Capabilities: 3brTvw==' -H 'X-IG-App-ID: 567067343352427' -H 'User-Agent: Instagram 103.1.0.15.119 Android (28/9; 420dpi; 1080x2034; unknown/Android; Google Pixel 3; vbox86p; vbox86; en_US; 164094540)' -H 'Accept-Language: en-US' -H 'Cookie: urlgen={\\\"100.122.249.137\\\": 30722}:1hzQaC:3H9QTDGxiCiwknGTLPWDWF_2lEU; ig_direct_region_hint=LLA; ds_user=potatomayl; igfl=potatomayl; ds_user_id=6578241026; mid=XVLRpwABAAG_kqYiZihqukSRfL9F; shbts=1566139954.4433396; sessionid=6578241026%3AKSVy2v5SQ9eCbK%3A2; csrftoken=8z78A9VVEAIcDGi9eM7GXpAnbly1245h; shbid=13717; rur=FRC; is_starred_enabled=yes' -H 'Content-Type: application/x-www-form-urlencoded; charset=UTF-8' -H 'Accept-Encoding: gzip, deflate' -H 'Host: i.instagram.com' -H 'X-FB-HTTP-Engine: Liger' -H 'Connection: close' -H 'Content-Length: 622'

-b 'urlgen={\\\"100.122.249.137\\\": 30722}:1hzQaC:3H9QTDGxiCiwknGTLPWDWF_2lEU; ig_direct_region_hint=LLA; ds_user=potatomayl; igfl=potatomayl; ds_user_id=6578241026; mid=XVLRpwABAAG_kqYiZihqukSRfL9F; shbts=1566139954.4433396; sessionid=6578241026%3AKSVy2v5SQ9eCbK%3A2; csrftoken=8z78A9VVEAIcDGi9eM7GXpAnbly1245h; shbid=13717; rur=FRC; is_starred_enabled=yes'

--data-binary 'signed_body=302871b2fd381f8ab90f43b2d9288da59b2ef42e6eb0aa1b5fc50bb6d55438cc.%7B%22user_breadcrumb%22%3A%22a2rDcCA%2FYHaavlT11I6rf8oNHyaIakiK%2B8na%2F1r3BYw%3D%5CnNiAyNTAxIDAgMTU2NjE1NTQ3ODQzMA%3D%3D%5Cn%22%2C%22idempotence_token%22%3A%2272013f10-c3ea-4bcf-a14d-1fa713034c07%22%2C%22_csrftoken%22%3A%228z78A9VVEAIcDGi9eM7GXpAnbly1245h%22%2C%22radio_type%22%3A%22wifi-none%22%2C%22_uid%22%3A%226578241026%22%2C%22device_id%22%3A%22android-3e3cde3b8e81d35%22%2C%22_uuid%22%3A%22ffbe7b2f-1663-43d4-847b-c3f51803637e%22%2C%22comment_text%22%3A%22Ciao+%21%22%2C%22container_module%22%3A%22comments_v2%22%7D&ig_sig_key_version=4'

'https://i.instagram.com/api/v1/media/2113323773613911713_6853370264/comment/'
```
___