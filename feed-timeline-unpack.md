# FEED-TIMELINE
### Multiple cases of feed/timeline request unpacked gzip/deflate request/response

# JUST-LOGGED-IN
### Request
```
https://i.instagram.com/api/v1/feed/timeline/
```
### Headers
```
X-Ads-Opt-Out: 0
X-DEVICE-ID: ffbe7b2f-1663-43d4-847b-c3f51803637e
X-CM-Bandwidth-KBPS: 4529.905
X-CM-Latency: 57.166
X-Pigeon-Session-Id: 8c221b22-cb55-4949-accb-a7d96154bb26
X-Pigeon-Rawclienttime: 1565946514.645
X-IG-Connection-Speed: 10001kbps
X-IG-Bandwidth-Speed-KBPS: 5553.958
X-IG-Bandwidth-TotalBytes-B: 3583173
X-IG-Bandwidth-TotalTime-MS: 841
X-IG-VP9-Capable: false
X-Bloks-Version-Id: 14f543394cf83e14784db6457e197a7e61e34fcd161891682143f74cb69a8981
X-IG-Connection-Type: WIFI
X-IG-Capabilities: 3brTvw==
X-IG-App-ID: 567067343352427
User-Agent: Instagram 103.1.0.15.119 Android (28/9; 420dpi; 1080x2034; unknown/Android; Google Pixel 3; vbox86p; vbox86; en_US; 164094540)
Accept-Language: en-US
Cookie: urlgen={\"2.32.17.241\": 30722}:1hyYDs:OI8nnRnD8UtgnpmV2dBKA5Rwklw; ds_user=potatomayl; ds_user_id=123456789; mid=XVLRpwABAAG_kqYiZihqukSRfL9F; shbts=1565946516.2772255; sessionid=123456789%3AfzxHObsuKaqLkA%3A2; csrftoken=U4vBAxbCknAEVGNHgpTGoG58WfCm87wx; shbid=13717; rur=FTW
Content-Type: application/x-www-form-urlencoded; charset=UTF-8
Accept-Encoding: gzip, deflate
Host: i.instagram.com
X-FB-HTTP-Engine: Liger
Connection: close
Content-Length: 1092
```
### Arguments encoded
```
is_prefetch=0&feed_view_info=%5B%7B%22media_id%22%3A%222111625231118646840_5564188868%22%2C%22version%22%3A16%2C%22media_pct%22%3A1.0%2C%22time_info%22%3A%7B%2210%22%3A244893%2C%2225%22%3A244893%2C%2250%22%3A244893%2C%2275%22%3A244893%7D%7D%2C%7B%22media_id%22%3A%222111403171268341739_6083859190%22%2C%22version%22%3A16%2C%22media_pct%22%3A0.98370373%2C%22time_info%22%3A%7B%2210%22%3A4760%2C%2225%22%3A4760%2C%2250%22%3A3226%2C%2275%22%3A3226%7D%7D%5D&phone_id=065c3b59-b457-45a0-a5b3-fca0076ff52b&reason=cold_start_fetch&battery_level=97&last_unseen_ad_id=2098626302353237692_3108958821&timezone_offset=-14400&_csrftoken=U4vBAxbCknAEVGNHgpTGoG58WfCm87wx&client_session_id=9b9e862b-8633-40cb-97a3-fcd2b0999471&device_id=ffbe7b2f-1663-43d4-847b-c3f51803637e&is_pull_to_refresh=0&_uuid=ffbe7b2f-1663-43d4-847b-c3f51803637e&is_charging=1&is_async_ads_in_headload_enabled=0&rti_delivery_backend=0&is_async_ads_double_request=0&will_sound_on=0&session_id=1083eacd-ddd1-4460-a4aa-21c36565c1d5&bloks_versioning_id=14f543394cf83e14784db6457e197a7e61e34fcd161891682143f74cb69a8981&is_async_ads_rti=0
```
### Arguments decoded
```
is_prefetch=0&feed_view_info=[{"media_id":"2111625231118646840_5564188868","version":16,"media_pct":1.0,"time_info":{"10":244893,"25":244893,"50":244893,"75":244893}},{"media_id":"2111403171268341739_6083859190","version":16,"media_pct":0.98370373,"time_info":{"10":4760,"25":4760,"50":3226,"75":3226}}]&phone_id=065c3b59-b457-45a0-a5b3-fca0076ff52b&reason=cold_start_fetch&battery_level=97&last_unseen_ad_id=2098626302353237692_3108958821&timezone_offset=-14400&_csrftoken=U4vBAxbCknAEVGNHgpTGoG58WfCm87wx&client_session_id=9b9e862b-8633-40cb-97a3-fcd2b0999471&device_id=ffbe7b2f-1663-43d4-847b-c3f51803637e&is_pull_to_refresh=0&_uuid=ffbe7b2f-1663-43d4-847b-c3f51803637e&is_charging=1&is_async_ads_in_headload_enabled=0&rti_delivery_backend=0&is_async_ads_double_request=0&will_sound_on=0&session_id=1083eacd-ddd1-4460-a4aa-21c36565c1d5&bloks_versioning_id=14f543394cf83e14784db6457e197a7e61e34fcd161891682143f74cb69a8981&is_async_ads_rti=0
```
### CURL Command
```
curl -i -s -k  -X 'POST'

-H 'X-Ads-Opt-Out: 0' -H 'X-DEVICE-ID: ffbe7b2f-1663-43d4-847b-c3f51803637e' -H 'X-CM-Bandwidth-KBPS: 4529.905' -H 'X-CM-Latency: 57.166' -H 'X-Pigeon-Session-Id: 8c221b22-cb55-4949-accb-a7d96154bb26' -H 'X-Pigeon-Rawclienttime: 1565946514.645' -H 'X-IG-Connection-Speed: 10001kbps' -H 'X-IG-Bandwidth-Speed-KBPS: 5553.958' -H 'X-IG-Bandwidth-TotalBytes-B: 3583173' -H 'X-IG-Bandwidth-TotalTime-MS: 841' -H 'X-IG-VP9-Capable: false' -H 'X-Bloks-Version-Id: 14f543394cf83e14784db6457e197a7e61e34fcd161891682143f74cb69a8981' -H 'X-IG-Connection-Type: WIFI' -H 'X-IG-Capabilities: 3brTvw==' -H 'X-IG-App-ID: 567067343352427' -H 'User-Agent: Instagram 103.1.0.15.119 Android (28/9; 420dpi; 1080x2034; unknown/Android; Google Pixel 3; vbox86p; vbox86; en_US; 164094540)' -H 'Accept-Language: en-US' -H 'Cookie: urlgen={\\\"2.32.17.241\\\": 30722}:1hyYDs:OI8nnRnD8UtgnpmV2dBKA5Rwklw; ds_user=potatomayl; ds_user_id=123456789; mid=XVLRpwABAAG_kqYiZihqukSRfL9F; shbts=1565946516.2772255; sessionid=123456789%3AfzxHObsuKaqLkA%3A2; csrftoken=U4vBAxbCknAEVGNHgpTGoG58WfCm87wx; shbid=13717; rur=FTW' -H 'Content-Type: application/x-www-form-urlencoded; charset=UTF-8' -H 'Accept-Encoding: gzip, deflate' -H 'Host: i.instagram.com' -H 'X-FB-HTTP-Engine: Liger' -H 'Connection: close' -H 'Content-Length: 1092'

-b 'urlgen={\\\"2.32.17.241\\\": 30722}:1hyYDs:OI8nnRnD8UtgnpmV2dBKA5Rwklw; ds_user=potatomayl; ds_user_id=123456789; mid=XVLRpwABAAG_kqYiZihqukSRfL9F; shbts=1565946516.2772255; sessionid=123456789%3AfzxHObsuKaqLkA%3A2; csrftoken=U4vBAxbCknAEVGNHgpTGoG58WfCm87wx; shbid=13717; rur=FTW'

--data-binary 'is_prefetch=0&feed_view_info=%5B%7B%22media_id%22%3A%222111625231118646840_5564188868%22%2C%22version%22%3A16%2C%22media_pct%22%3A1.0%2C%22time_info%22%3A%7B%2210%22%3A244893%2C%2225%22%3A244893%2C%2250%22%3A244893%2C%2275%22%3A244893%7D%7D%2C%7B%22media_id%22%3A%222111403171268341739_6083859190%22%2C%22version%22%3A16%2C%22media_pct%22%3A0.98370373%2C%22time_info%22%3A%7B%2210%22%3A4760%2C%2225%22%3A4760%2C%2250%22%3A3226%2C%2275%22%3A3226%7D%7D%5D&phone_id=065c3b59-b457-45a0-a5b3-fca0076ff52b&reason=cold_start_fetch&battery_level=97&last_unseen_ad_id=2098626302353237692_3108958821&timezone_offset=-14400&_csrftoken=U4vBAxbCknAEVGNHgpTGoG58WfCm87wx&client_session_id=9b9e862b-8633-40cb-97a3-fcd2b0999471&device_id=ffbe7b2f-1663-43d4-847b-c3f51803637e&is_pull_to_refresh=0&_uuid=ffbe7b2f-1663-43d4-847b-c3f51803637e&is_charging=1&is_async_ads_in_headload_enabled=0&rti_delivery_backend=0&is_async_ads_double_request=0&will_sound_on=0&session_id=1083eacd-ddd1-4460-a4aa-21c36565c1d5&bloks_versioning_id=14f543394cf83e14784db6457e197a7e61e34fcd161891682143f74cb69a8981&is_async_ads_rti=0'

'https://i.instagram.com/api/v1/feed/timeline/'
```
___
# REOPEN-Application (after 20m)
### Request
```
https://i.instagram.com/api/v1/feed/timeline/
```
### Headers
```
X-Ads-Opt-Out: 0
X-DEVICE-ID: ffbe7b2f-1663-43d4-847b-c3f51803637e
X-CM-Bandwidth-KBPS: 4569.073
X-CM-Latency: 45.065
X-Pigeon-Session-Id: 0da182c8-9f68-4e25-98b1-04e57a1f6113
X-Pigeon-Rawclienttime: 1565948099.159
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
Cookie: urlgen={\"2.32.17.241\": 30722}:1hyYEl:kCpi82AZpJHW6qtPA5hu3PzoBy4; ig_direct_region_hint=LLA; ds_user=potatomayl; igfl=potatomayl; ds_user_id=123456789; mid=XVLRpwABAAG_kqYiZihqukSRfL9F; shbts=1565946516.2772255; sessionid=123456789%3AfzxHObsuKaqLkA%3A2; csrftoken=U4vBAxbCknAEVGNHgpTGoG58WfCm87wx; shbid=13717; rur=FRC; is_starred_enabled=yes
Content-Type: application/x-www-form-urlencoded; charset=UTF-8
Accept-Encoding: gzip, deflate
Host: i.instagram.com
X-FB-HTTP-Engine: Liger
Connection: close
Content-Length: 1077
```
### Arguments encoded
```
is_prefetch=0&feed_view_info=%5B%7B%22media_id%22%3A%222111319981702785308_1566616655%22%2C%22version%22%3A16%2C%22media_pct%22%3A1.0%2C%22time_info%22%3A%7B%2210%22%3A189008%2C%2225%22%3A189008%2C%2250%22%3A189008%2C%2275%22%3A189009%7D%7D%2C%7B%22media_id%22%3A%222111319981702785308_1566616655-2111319811246474455_1566616655%22%2C%22version%22%3A16%2C%22media_pct%22%3A1.0%2C%22time_info%22%3A%7B%2210%22%3A189016%2C%2225%22%3A189016%2C%2250%22%3A189016%2C%2275%22%3A189016%7D%7D%5D&phone_id=065c3b59-b457-45a0-a5b3-fca0076ff52b&reason=cold_start_fetch&battery_level=100&last_unseen_ad_id=2111626875360159989_1560900654&timezone_offset=-14400&_csrftoken=U4vBAxbCknAEVGNHgpTGoG58WfCm87wx&client_session_id=592aca6b-7dcd-4bfc-9fc8-62bbcdb5f315&device_id=ffbe7b2f-1663-43d4-847b-c3f51803637e&is_pull_to_refresh=0&_uuid=ffbe7b2f-1663-43d4-847b-c3f51803637e&is_charging=1&is_async_ads_in_headload_enabled=0&rti_delivery_backend=0&is_async_ads_double_request=0&will_sound_on=0&bloks_versioning_id=14f543394cf83e14784db6457e197a7e61e34fcd161891682143f74cb69a8981&is_async_ads_rti=0
```
### Arguments decoded
```
is_prefetch=0&feed_view_info=[{"media_id":"2111319981702785308_1566616655","version":16,"media_pct":1.0,"time_info":{"10":189008,"25":189008,"50":189008,"75":189009}},{"media_id":"2111319981702785308_1566616655-2111319811246474455_1566616655","version":16,"media_pct":1.0,"time_info":{"10":189016,"25":189016,"50":189016,"75":189016}}]&phone_id=065c3b59-b457-45a0-a5b3-fca0076ff52b&reason=cold_start_fetch&battery_level=100&last_unseen_ad_id=2111626875360159989_1560900654&timezone_offset=-14400&_csrftoken=U4vBAxbCknAEVGNHgpTGoG58WfCm87wx&client_session_id=592aca6b-7dcd-4bfc-9fc8-62bbcdb5f315&device_id=ffbe7b2f-1663-43d4-847b-c3f51803637e&is_pull_to_refresh=0&_uuid=ffbe7b2f-1663-43d4-847b-c3f51803637e&is_charging=1&is_async_ads_in_headload_enabled=0&rti_delivery_backend=0&is_async_ads_double_request=0&will_sound_on=0&bloks_versioning_id=14f543394cf83e14784db6457e197a7e61e34fcd161891682143f74cb69a8981&is_async_ads_rti=0
```
### CURL Command
```
curl -i -s -k  -X 'POST'

-H 'X-Ads-Opt-Out: 0' -H 'X-DEVICE-ID: ffbe7b2f-1663-43d4-847b-c3f51803637e' -H 'X-CM-Bandwidth-KBPS: 4569.073' -H 'X-CM-Latency: 45.065' -H 'X-Pigeon-Session-Id: 0da182c8-9f68-4e25-98b1-04e57a1f6113' -H 'X-Pigeon-Rawclienttime: 1565948099.159' -H 'X-IG-Connection-Speed: -1kbps' -H 'X-IG-Bandwidth-Speed-KBPS: -1.000' -H 'X-IG-Bandwidth-TotalBytes-B: 0' -H 'X-IG-Bandwidth-TotalTime-MS: 0' -H 'X-IG-VP9-Capable: false' -H 'X-Bloks-Version-Id: 14f543394cf83e14784db6457e197a7e61e34fcd161891682143f74cb69a8981' -H 'X-IG-Connection-Type: WIFI' -H 'X-IG-Capabilities: 3brTvw==' -H 'X-IG-App-ID: 567067343352427' -H 'User-Agent: Instagram 103.1.0.15.119 Android (28/9; 420dpi; 1080x2034; unknown/Android; Google Pixel 3; vbox86p; vbox86; en_US; 164094540)' -H 'Accept-Language: en-US' -H 'Cookie: urlgen={\\\"2.32.17.241\\\": 30722}:1hyYEl:kCpi82AZpJHW6qtPA5hu3PzoBy4; ig_direct_region_hint=LLA; ds_user=potatomayl; igfl=potatomayl; ds_user_id=123456789; mid=XVLRpwABAAG_kqYiZihqukSRfL9F; shbts=1565946516.2772255; sessionid=123456789%3AfzxHObsuKaqLkA%3A2; csrftoken=U4vBAxbCknAEVGNHgpTGoG58WfCm87wx; shbid=13717; rur=FRC; is_starred_enabled=yes' -H 'Content-Type: application/x-www-form-urlencoded; charset=UTF-8' -H 'Accept-Encoding: gzip, deflate' -H 'Host: i.instagram.com' -H 'X-FB-HTTP-Engine: Liger' -H 'Connection: close' -H 'Content-Length: 1077'

-b 'urlgen={\\\"2.32.17.241\\\": 30722}:1hyYEl:kCpi82AZpJHW6qtPA5hu3PzoBy4; ig_direct_region_hint=LLA; ds_user=potatomayl; igfl=potatomayl; ds_user_id=123456789; mid=XVLRpwABAAG_kqYiZihqukSRfL9F; shbts=1565946516.2772255; sessionid=123456789%3AfzxHObsuKaqLkA%3A2; csrftoken=U4vBAxbCknAEVGNHgpTGoG58WfCm87wx; shbid=13717; rur=FRC; is_starred_enabled=yes'

--data-binary 'is_prefetch=0&feed_view_info=%5B%7B%22media_id%22%3A%222111319981702785308_1566616655%22%2C%22version%22%3A16%2C%22media_pct%22%3A1.0%2C%22time_info%22%3A%7B%2210%22%3A189008%2C%2225%22%3A189008%2C%2250%22%3A189008%2C%2275%22%3A189009%7D%7D%2C%7B%22media_id%22%3A%222111319981702785308_1566616655-2111319811246474455_1566616655%22%2C%22version%22%3A16%2C%22media_pct%22%3A1.0%2C%22time_info%22%3A%7B%2210%22%3A189016%2C%2225%22%3A189016%2C%2250%22%3A189016%2C%2275%22%3A189016%7D%7D%5D&phone_id=065c3b59-b457-45a0-a5b3-fca0076ff52b&reason=cold_start_fetch&battery_level=100&last_unseen_ad_id=2111626875360159989_1560900654&timezone_offset=-14400&_csrftoken=U4vBAxbCknAEVGNHgpTGoG58WfCm87wx&client_session_id=592aca6b-7dcd-4bfc-9fc8-62bbcdb5f315&device_id=ffbe7b2f-1663-43d4-847b-c3f51803637e&is_pull_to_refresh=0&_uuid=ffbe7b2f-1663-43d4-847b-c3f51803637e&is_charging=1&is_async_ads_in_headload_enabled=0&rti_delivery_backend=0&is_async_ads_double_request=0&will_sound_on=0&bloks_versioning_id=14f543394cf83e14784db6457e197a7e61e34fcd161891682143f74cb69a8981&is_async_ads_rti=0'

'https://i.instagram.com/api/v1/feed/timeline/'
```
___
## PULL-TO-REFRESH
### Request
```
https://i.instagram.com/api/v1/feed/timeline/
```
### Headers
```
X-Ads-Opt-Out: 0
X-DEVICE-ID: ffbe7b2f-1663-43d4-847b-c3f51803637e
X-CM-Bandwidth-KBPS: 5020.196
X-CM-Latency: 56.576
X-Pigeon-Session-Id: 0da182c8-9f68-4e25-98b1-04e57a1f6113
X-Pigeon-Rawclienttime: 1565948431.225
X-IG-Connection-Speed: 10168kbps
X-IG-Bandwidth-Speed-KBPS: 6498.754
X-IG-Bandwidth-TotalBytes-B: 1527555
X-IG-Bandwidth-TotalTime-MS: 331
X-IG-VP9-Capable: false
X-Bloks-Version-Id: 14f543394cf83e14784db6457e197a7e61e34fcd161891682143f74cb69a8981
X-IG-Connection-Type: WIFI
X-IG-Capabilities: 3brTvw==
X-IG-App-ID: 567067343352427
User-Agent: Instagram 103.1.0.15.119 Android (28/9; 420dpi; 1080x2034; unknown/Android; Google Pixel 3; vbox86p; vbox86; en_US; 164094540)
Accept-Language: en-US
Cookie: urlgen={\"2.32.17.241\": 30722}:1hyYhC:-3940Gt5MJQ7WUFVVPsOKc9eh4o; ig_direct_region_hint=LLA; ds_user=potatomayl; igfl=potatomayl; ds_user_id=123456789; mid=XVLRpwABAAG_kqYiZihqukSRfL9F; shbts=1565946516.2772255; sessionid=123456789%3AfzxHObsuKaqLkA%3A2; csrftoken=U4vBAxbCknAEVGNHgpTGoG58WfCm87wx; shbid=13717; rur=FRC; is_starred_enabled=yes
Content-Type: application/x-www-form-urlencoded; charset=UTF-8
Accept-Encoding: gzip, deflate
Host: i.instagram.com
X-FB-HTTP-Engine: Liger
Connection: close
Content-Length: 1336
```
### Arguments encoded
```
is_prefetch=0&feed_view_info=%5B%7B%22media_id%22%3A%222111636103483698186_12386695325%22%2C%22version%22%3A16%2C%22media_pct%22%3A1.0%2C%22time_info%22%3A%7B%2210%22%3A329413%2C%2225%22%3A329413%2C%2250%22%3A329413%2C%2275%22%3A329413%7D%7D%2C%7B%22media_id%22%3A%222111319981702785308_1566616655%22%2C%22version%22%3A16%2C%22media_pct%22%3A1.0%2C%22time_info%22%3A%7B%2210%22%3A189008%2C%2225%22%3A189008%2C%2250%22%3A189008%2C%2275%22%3A189009%7D%7D%2C%7B%22media_id%22%3A%222111319981702785308_1566616655-2111319811246474455_1566616655%22%2C%22version%22%3A16%2C%22media_pct%22%3A1.0%2C%22time_info%22%3A%7B%2210%22%3A189016%2C%2225%22%3A189016%2C%2250%22%3A189016%2C%2275%22%3A189016%7D%7D%5D&phone_id=065c3b59-b457-45a0-a5b3-fca0076ff52b&reason=pull_to_refresh&battery_level=100&last_unseen_ad_id=2111648196768979672_1560900654&timezone_offset=-14400&_csrftoken=U4vBAxbCknAEVGNHgpTGoG58WfCm87wx&client_session_id=b23aea50-ac36-44d0-a696-02acd98eb5b4&device_id=ffbe7b2f-1663-43d4-847b-c3f51803637e&is_pull_to_refresh=1&_uuid=ffbe7b2f-1663-43d4-847b-c3f51803637e&is_charging=1&is_async_ads_in_headload_enabled=0&rti_delivery_backend=0&is_async_ads_double_request=0&will_sound_on=0&session_id=3a53a330-fd5e-473c-b31c-f402df587dc0&bloks_versioning_id=14f543394cf83e14784db6457e197a7e61e34fcd161891682143f74cb69a8981&is_async_ads_rti=0
```
### Arguments decoded
```
is_prefetch=0&feed_view_info=[{"media_id":"2111636103483698186_12386695325","version":16,"media_pct":1.0,"time_info":{"10":329413,"25":329413,"50":329413,"75":329413}},{"media_id":"2111319981702785308_1566616655","version":16,"media_pct":1.0,"time_info":{"10":189008,"25":189008,"50":189008,"75":189009}},{"media_id":"2111319981702785308_1566616655-2111319811246474455_1566616655","version":16,"media_pct":1.0,"time_info":{"10":189016,"25":189016,"50":189016,"75":189016}}]&phone_id=065c3b59-b457-45a0-a5b3-fca0076ff52b&reason=pull_to_refresh&battery_level=100&last_unseen_ad_id=2111648196768979672_1560900654&timezone_offset=-14400&_csrftoken=U4vBAxbCknAEVGNHgpTGoG58WfCm87wx&client_session_id=b23aea50-ac36-44d0-a696-02acd98eb5b4&device_id=ffbe7b2f-1663-43d4-847b-c3f51803637e&is_pull_to_refresh=1&_uuid=ffbe7b2f-1663-43d4-847b-c3f51803637e&is_charging=1&is_async_ads_in_headload_enabled=0&rti_delivery_backend=0&is_async_ads_double_request=0&will_sound_on=0&session_id=3a53a330-fd5e-473c-b31c-f402df587dc0&bloks_versioning_id=14f543394cf83e14784db6457e197a7e61e34fcd161891682143f74cb69a8981&is_async_ads_rti=0
```
### CURL Command
```
curl -i -s -k  -X 'POST'

-H 'X-Ads-Opt-Out: 0' -H 'X-DEVICE-ID: ffbe7b2f-1663-43d4-847b-c3f51803637e' -H 'X-CM-Bandwidth-KBPS: 5020.196' -H 'X-CM-Latency: 56.576' -H 'X-Pigeon-Session-Id: 0da182c8-9f68-4e25-98b1-04e57a1f6113' -H 'X-Pigeon-Rawclienttime: 1565948431.225' -H 'X-IG-Connection-Speed: 10168kbps' -H 'X-IG-Bandwidth-Speed-KBPS: 6498.754' -H 'X-IG-Bandwidth-TotalBytes-B: 1527555' -H 'X-IG-Bandwidth-TotalTime-MS: 331' -H 'X-IG-VP9-Capable: false' -H 'X-Bloks-Version-Id: 14f543394cf83e14784db6457e197a7e61e34fcd161891682143f74cb69a8981' -H 'X-IG-Connection-Type: WIFI' -H 'X-IG-Capabilities: 3brTvw==' -H 'X-IG-App-ID: 567067343352427' -H 'User-Agent: Instagram 103.1.0.15.119 Android (28/9; 420dpi; 1080x2034; unknown/Android; Google Pixel 3; vbox86p; vbox86; en_US; 164094540)' -H 'Accept-Language: en-US' -H 'Cookie: urlgen={\\\"2.32.17.241\\\": 30722}:1hyYhC:-3940Gt5MJQ7WUFVVPsOKc9eh4o; ig_direct_region_hint=LLA; ds_user=potatomayl; igfl=potatomayl; ds_user_id=123456789; mid=XVLRpwABAAG_kqYiZihqukSRfL9F; shbts=1565946516.2772255; sessionid=123456789%3AfzxHObsuKaqLkA%3A2; csrftoken=U4vBAxbCknAEVGNHgpTGoG58WfCm87wx; shbid=13717; rur=FRC; is_starred_enabled=yes' -H 'Content-Type: application/x-www-form-urlencoded; charset=UTF-8' -H 'Accept-Encoding: gzip, deflate' -H 'Host: i.instagram.com' -H 'X-FB-HTTP-Engine: Liger' -H 'Connection: close' -H 'Content-Length: 1336'

-b 'urlgen={\\\"2.32.17.241\\\": 30722}:1hyYhC:-3940Gt5MJQ7WUFVVPsOKc9eh4o; ig_direct_region_hint=LLA; ds_user=potatomayl; igfl=potatomayl; ds_user_id=123456789; mid=XVLRpwABAAG_kqYiZihqukSRfL9F; shbts=1565946516.2772255; sessionid=123456789%3AfzxHObsuKaqLkA%3A2; csrftoken=U4vBAxbCknAEVGNHgpTGoG58WfCm87wx; shbid=13717; rur=FRC; is_starred_enabled=yes'

--data-binary 'is_prefetch=0&feed_view_info=%5B%7B%22media_id%22%3A%222111636103483698186_12386695325%22%2C%22version%22%3A16%2C%22media_pct%22%3A1.0%2C%22time_info%22%3A%7B%2210%22%3A329413%2C%2225%22%3A329413%2C%2250%22%3A329413%2C%2275%22%3A329413%7D%7D%2C%7B%22media_id%22%3A%222111319981702785308_1566616655%22%2C%22version%22%3A16%2C%22media_pct%22%3A1.0%2C%22time_info%22%3A%7B%2210%22%3A189008%2C%2225%22%3A189008%2C%2250%22%3A189008%2C%2275%22%3A189009%7D%7D%2C%7B%22media_id%22%3A%222111319981702785308_1566616655-2111319811246474455_1566616655%22%2C%22version%22%3A16%2C%22media_pct%22%3A1.0%2C%22time_info%22%3A%7B%2210%22%3A189016%2C%2225%22%3A189016%2C%2250%22%3A189016%2C%2275%22%3A189016%7D%7D%5D&phone_id=065c3b59-b457-45a0-a5b3-fca0076ff52b&reason=pull_to_refresh&battery_level=100&last_unseen_ad_id=2111648196768979672_1560900654&timezone_offset=-14400&_csrftoken=U4vBAxbCknAEVGNHgpTGoG58WfCm87wx&client_session_id=b23aea50-ac36-44d0-a696-02acd98eb5b4&device_id=ffbe7b2f-1663-43d4-847b-c3f51803637e&is_pull_to_refresh=1&_uuid=ffbe7b2f-1663-43d4-847b-c3f51803637e&is_charging=1&is_async_ads_in_headload_enabled=0&rti_delivery_backend=0&is_async_ads_double_request=0&will_sound_on=0&session_id=3a53a330-fd5e-473c-b31c-f402df587dc0&bloks_versioning_id=14f543394cf83e14784db6457e197a7e61e34fcd161891682143f74cb69a8981&is_async_ads_rti=0'

'https://i.instagram.com/api/v1/feed/timeline/'
```
___