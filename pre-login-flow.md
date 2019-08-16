# PRE-LOGIN-FLOW
### All request do by Instagram application BEFORE **login method**.

## contact_point_prefill
### Request
```
https://i.instagram.com/api/v1/accounts/contact_point_prefill/
```
### Headers
```
X-Pigeon-Session-Id: eb7165e8-c590-4729-8656-7b57e4d9cdfd
X-Pigeon-Rawclienttime: 1565941500.461
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
Content-Length: 253
```
### Arguments encoded
```
signed_body=5857910902dc08cd0d1b9e901ba1c6ffcd5a4d1c3887bffdb9a296cb2ca33f34.%7B%22phone_id%22%3A%22065c3b59-b457-45a0-a5b3-fca0076ff52b%22%2C%22_csrftoken%22%3A%22ZsjKxFu1AfeyYlA1KuLCQNsgEBejsZbi%22%2C%22usage%22%3A%22prefill%22%7D&ig_sig_key_version=4
```
### Arguments decoded
```
signed_body=5857910902dc08cd0d1b9e901ba1c6ffcd5a4d1c3887bffdb9a296cb2ca33f34.{"phone_id":"065c3b59-b457-45a0-a5b3-fca0076ff52b","_csrftoken":"ZsjKxFu1AfeyYlA1KuLCQNsgEBejsZbi","usage":"prefill"}&ig_sig_key_version=4
```
### CURL Command
```
curl -i -s -k  -X 'POST'

-H 'X-Pigeon-Session-Id: eb7165e8-c590-4729-8656-7b57e4d9cdfd' -H 'X-Pigeon-Rawclienttime: 1565941500.461' -H 'X-IG-Connection-Speed: -1kbps' -H 'X-IG-Bandwidth-Speed-KBPS: -1.000' -H 'X-IG-Bandwidth-TotalBytes-B: 0' -H 'X-IG-Bandwidth-TotalTime-MS: 0' -H 'X-IG-VP9-Capable: false' -H 'X-Bloks-Version-Id: 14f543394cf83e14784db6457e197a7e61e34fcd161891682143f74cb69a8981' -H 'X-IG-Connection-Type: WIFI' -H 'X-IG-Capabilities: 3brTvw==' -H 'X-IG-App-ID: 567067343352427' -H 'User-Agent: Instagram 103.1.0.15.119 Android (28/9; 420dpi; 1080x2034; unknown/Android; Google Pixel 3; vbox86p; vbox86; en_US; 164094540)' -H 'Accept-Language: en-US' -H 'Cookie: mid=XVLRpwABAAG_kqYiZihqukSRfL9F; csrftoken=ZsjKxFu1AfeyYlA1KuLCQNsgEBejsZbi; rur=FTW' -H 'Content-Type: application/x-www-form-urlencoded; charset=UTF-8' -H 'Accept-Encoding: gzip, deflate' -H 'Host: i.instagram.com' -H 'X-FB-HTTP-Engine: Liger' -H 'Connection: close' -H 'Content-Length: 253'


-b 'mid=XVLRpwABAAG_kqYiZihqukSRfL9F; csrftoken=ZsjKxFu1AfeyYlA1KuLCQNsgEBejsZbi; rur=FTW'


--data-binary 'signed_body=5857910902dc08cd0d1b9e901ba1c6ffcd5a4d1c3887bffdb9a296cb2ca33f34.%7B%22phone_id%22%3A%22065c3b59-b457-45a0-a5b3-fca0076ff52b%22%2C%22_csrftoken%22%3A%22ZsjKxFu1AfeyYlA1KuLCQNsgEBejsZbi%22%2C%22usage%22%3A%22prefill%22%7D&ig_sig_key_version=4'


'https://i.instagram.com/api/v1/accounts/contact_point_prefill/'
```
___

## read_msisdn_header
### Request
```
https://i.instagram.com/api/v1/accounts/read_msisdn_header/
```
### Headers
```
X-DEVICE-ID: ffbe7b2f-1663-43d4-847b-c3f51803637e
X-Pigeon-Session-Id: eb7165e8-c590-4729-8656-7b57e4d9cdfd
X-Pigeon-Rawclienttime: 1565941500.469
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
Content-Length: 267
```
### Arguments encoded
```
signed_body=f0d8427682ee2c49fd044a3baa65dfc5cdd4f2838a4d01d04205f228bf1f00f5.%7B%22mobile_subno_usage%22%3A%22default%22%2C%22_csrftoken%22%3A%22ZsjKxFu1AfeyYlA1KuLCQNsgEBejsZbi%22%2C%22device_id%22%3A%22ffbe7b2f-1663-43d4-847b-c3f51803637e%22%7D&ig_sig_key_version=4
```
### Arguments decoded
```
signed_body=f0d8427682ee2c49fd044a3baa65dfc5cdd4f2838a4d01d04205f228bf1f00f5.{"mobile_subno_usage":"default","_csrftoken":"ZsjKxFu1AfeyYlA1KuLCQNsgEBejsZbi","device_id":"ffbe7b2f-1663-43d4-847b-c3f51803637e"}&ig_sig_key_version=4
```
### CURL Command
```
curl -i -s -k  -X 'POST'

-H 'X-DEVICE-ID: ffbe7b2f-1663-43d4-847b-c3f51803637e' -H 'X-Pigeon-Session-Id: eb7165e8-c590-4729-8656-7b57e4d9cdfd' -H 'X-Pigeon-Rawclienttime: 1565941500.469' -H 'X-IG-Connection-Speed: -1kbps' -H 'X-IG-Bandwidth-Speed-KBPS: -1.000' -H 'X-IG-Bandwidth-TotalBytes-B: 0' -H 'X-IG-Bandwidth-TotalTime-MS: 0' -H 'X-IG-VP9-Capable: false' -H 'X-Bloks-Version-Id: 14f543394cf83e14784db6457e197a7e61e34fcd161891682143f74cb69a8981' -H 'X-IG-Connection-Type: WIFI' -H 'X-IG-Capabilities: 3brTvw==' -H 'X-IG-App-ID: 567067343352427' -H 'User-Agent: Instagram 103.1.0.15.119 Android (28/9; 420dpi; 1080x2034; unknown/Android; Google Pixel 3; vbox86p; vbox86; en_US; 164094540)' -H 'Accept-Language: en-US' -H 'Cookie: mid=XVLRpwABAAG_kqYiZihqukSRfL9F; csrftoken=ZsjKxFu1AfeyYlA1KuLCQNsgEBejsZbi; rur=FTW' -H 'Content-Type: application/x-www-form-urlencoded; charset=UTF-8' -H 'Accept-Encoding: gzip, deflate' -H 'Host: i.instagram.com' -H 'X-FB-HTTP-Engine: Liger' -H 'Connection: close' -H 'Content-Length: 267'

-b 'mid=XVLRpwABAAG_kqYiZihqukSRfL9F; csrftoken=ZsjKxFu1AfeyYlA1KuLCQNsgEBejsZbi; rur=FTW'

--data-binary 'signed_body=f0d8427682ee2c49fd044a3baa65dfc5cdd4f2838a4d01d04205f228bf1f00f5.%7B%22mobile_subno_usage%22%3A%22default%22%2C%22_csrftoken%22%3A%22ZsjKxFu1AfeyYlA1KuLCQNsgEBejsZbi%22%2C%22device_id%22%3A%22ffbe7b2f-1663-43d4-847b-c3f51803637e%22%7D&ig_sig_key_version=4'

'https://i.instagram.com/api/v1/accounts/read_msisdn_header/'
```
___
## qe/sync
### Request
```
https://i.instagram.com/api/v1/qe/sync/
```
### Headers
```
X-DEVICE-ID: ffbe7b2f-1663-43d4-847b-c3f51803637e
X-Pigeon-Session-Id: eb7165e8-c590-4729-8656-7b57e4d9cdfd
X-Pigeon-Rawclienttime: 1565941500.517
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
Content-Length: 3113
```
### Arguments encoded
```
signed_body=92c12ca534e63551811b194573cbe8d8cfaec19ec21c48ce9328b1d897689d65.%7B%22_csrftoken%22%3A%22ZsjKxFu1AfeyYlA1KuLCQNsgEBejsZbi%22%2C%22id%22%3A%22ffbe7b2f-1663-43d4-847b-c3f51803637e%22%2C%22server_config_retrieval%22%3A%221%22%2C%22experiments%22%3A%22ig_android_fci_onboarding_friend_search%2Cig_android_device_detection_info_upload%2Cig_android_sms_retriever_backtest_universe%2Cig_android_direct_add_direct_to_android_native_photo_share_sheet%2Cig_growth_android_profile_pic_prefill_with_fb_pic_2%2Cig_account_identity_logged_out_signals_global_holdout_universe%2Cig_android_login_identifier_fuzzy_match%2Cig_android_reliability_leak_fixes_h1_2019%2Cig_android_video_render_codec_low_memory_gc%2Cig_android_custom_transitions_universe%2Cig_android_push_fcm%2Cig_android_show_login_info_reminder_universe%2Cig_android_email_fuzzy_matching_universe%2Cig_android_one_tap_aymh_redesign_universe%2Cig_android_direct_send_like_from_notification%2Cig_android_suma_landing_page%2Cig_android_direct_main_tab_universe%2Cig_android_session_scoped_logger%2Cig_android_accoun_switch_badge_fix_universe%2Cig_android_smartlock_hints_universe%2Cig_android_black_out%2Cig_android_account_switch_infra_universe%2Cig_android_video_ffmpegutil_pts_fix%2Cig_android_multi_tap_login_new%2Cig_android_caption_typeahead_fix_on_o_universe%2Cig_android_save_pwd_checkbox_reg_universe%2Cig_android_nux_add_email_device%2Cig_android_direct_remove_view_mode_stickiness_universe%2Cig_username_suggestions_on_username_taken%2Cig_android_analytics_accessibility_event%2Cig_android_ingestion_video_support_hevc_decoding%2Cig_android_account_recovery_auto_login%2Cig_android_feed_cache_device_universe2%2Cig_android_sim_info_upload%2Cig_android_mobile_http_flow_device_universe%2Cig_account_recovery_via_whatsapp_universe%2Cig_android_hide_fb_button_when_not_installed_universe%2Cig_android_targeted_one_tap_upsell_universe%2Cig_android_gmail_oauth_in_reg%2Cig_android_native_logcat_interceptor%2Cig_android_hide_typeahead_for_logged_users%2Cig_android_vc_interop_use_test_igid_universe%2Cig_android_reg_modularization_universe%2Cig_android_phone_edit_distance_universe%2Cig_android_device_verification_separate_endpoint%2Cig_android_universe_noticiation_channels%2Cig_smartlock_login%2Cig_android_account_linking_universe%2Cig_android_hsite_prefill_new_carrier%2Cig_android_retry_create_account_universe%2Cig_android_family_apps_user_values_provider_universe%2Cig_android_reg_nux_headers_cleanup_universe%2Cig_android_device_info_foreground_reporting%2Cig_android_device_verification_fb_signup%2Cig_android_onetaplogin_optimization%2Cig_video_debug_overlay%2Cig_android_ask_for_permissions_on_reg%2Cig_assisted_login_universe%2Cig_android_display_full_country_name_in_reg_universe%2Cig_android_security_intent_switchoff%2Cig_android_device_info_job_based_reporting%2Cig_android_passwordless_auth%2Cig_android_direct_main_tab_account_switch%2Cig_android_modularized_dynamic_nux_universe%2Cig_android_fb_account_linking_sampling_freq_universe%2Cig_android_fix_sms_read_lollipop%2Cig_android_access_flow_prefill%22%7D&ig_sig_key_version=4
```
### Arguments decoded
```
signed_body=92c12ca534e63551811b194573cbe8d8cfaec19ec21c48ce9328b1d897689d65.{"_csrftoken":"ZsjKxFu1AfeyYlA1KuLCQNsgEBejsZbi","id":"ffbe7b2f-1663-43d4-847b-c3f51803637e","server_config_retrieval":"1","experiments":"ig_android_fci_onboarding_friend_search,ig_android_device_detection_info_upload,ig_android_sms_retriever_backtest_universe,ig_android_direct_add_direct_to_android_native_photo_share_sheet,ig_growth_android_profile_pic_prefill_with_fb_pic_2,ig_account_identity_logged_out_signals_global_holdout_universe,ig_android_login_identifier_fuzzy_match,ig_android_reliability_leak_fixes_h1_2019,ig_android_video_render_codec_low_memory_gc,ig_android_custom_transitions_universe,ig_android_push_fcm,ig_android_show_login_info_reminder_universe,ig_android_email_fuzzy_matching_universe,ig_android_one_tap_aymh_redesign_universe,ig_android_direct_send_like_from_notification,ig_android_suma_landing_page,ig_android_direct_main_tab_universe,ig_android_session_scoped_logger,ig_android_accoun_switch_badge_fix_universe,ig_android_smartlock_hints_universe,ig_android_black_out,ig_android_account_switch_infra_universe,ig_android_video_ffmpegutil_pts_fix,ig_android_multi_tap_login_new,ig_android_caption_typeahead_fix_on_o_universe,ig_android_save_pwd_checkbox_reg_universe,ig_android_nux_add_email_device,ig_android_direct_remove_view_mode_stickiness_universe,ig_username_suggestions_on_username_taken,ig_android_analytics_accessibility_event,ig_android_ingestion_video_support_hevc_decoding,ig_android_account_recovery_auto_login,ig_android_feed_cache_device_universe2,ig_android_sim_info_upload,ig_android_mobile_http_flow_device_universe,ig_account_recovery_via_whatsapp_universe,ig_android_hide_fb_button_when_not_installed_universe,ig_android_targeted_one_tap_upsell_universe,ig_android_gmail_oauth_in_reg,ig_android_native_logcat_interceptor,ig_android_hide_typeahead_for_logged_users,ig_android_vc_interop_use_test_igid_universe,ig_android_reg_modularization_universe,ig_android_phone_edit_distance_universe,ig_android_device_verification_separate_endpoint,ig_android_universe_noticiation_channels,ig_smartlock_login,ig_android_account_linking_universe,ig_android_hsite_prefill_new_carrier,ig_android_retry_create_account_universe,ig_android_family_apps_user_values_provider_universe,ig_android_reg_nux_headers_cleanup_universe,ig_android_device_info_foreground_reporting,ig_android_device_verification_fb_signup,ig_android_onetaplogin_optimization,ig_video_debug_overlay,ig_android_ask_for_permissions_on_reg,ig_assisted_login_universe,ig_android_display_full_country_name_in_reg_universe,ig_android_security_intent_switchoff,ig_android_device_info_job_based_reporting,ig_android_passwordless_auth,ig_android_direct_main_tab_account_switch,ig_android_modularized_dynamic_nux_universe,ig_android_fb_account_linking_sampling_freq_universe,ig_android_fix_sms_read_lollipop,ig_android_access_flow_prefill"}&ig_sig_key_version=4
```
### CURL Command
```
curl -i -s -k  -X 'POST'

-H 'X-DEVICE-ID: ffbe7b2f-1663-43d4-847b-c3f51803637e' -H 'X-Pigeon-Session-Id: eb7165e8-c590-4729-8656-7b57e4d9cdfd' -H 'X-Pigeon-Rawclienttime: 1565941500.517' -H 'X-IG-Connection-Speed: -1kbps' -H 'X-IG-Bandwidth-Speed-KBPS: -1.000' -H 'X-IG-Bandwidth-TotalBytes-B: 0' -H 'X-IG-Bandwidth-TotalTime-MS: 0' -H 'X-IG-VP9-Capable: false' -H 'X-Bloks-Version-Id: 14f543394cf83e14784db6457e197a7e61e34fcd161891682143f74cb69a8981' -H 'X-IG-Connection-Type: WIFI' -H 'X-IG-Capabilities: 3brTvw==' -H 'X-IG-App-ID: 567067343352427' -H 'User-Agent: Instagram 103.1.0.15.119 Android (28/9; 420dpi; 1080x2034; unknown/Android; Google Pixel 3; vbox86p; vbox86; en_US; 164094540)' -H 'Accept-Language: en-US' -H 'Cookie: mid=XVLRpwABAAG_kqYiZihqukSRfL9F; csrftoken=ZsjKxFu1AfeyYlA1KuLCQNsgEBejsZbi; rur=FTW' -H 'Content-Type: application/x-www-form-urlencoded; charset=UTF-8' -H 'Accept-Encoding: gzip, deflate' -H 'Host: i.instagram.com' -H 'X-FB-HTTP-Engine: Liger' -H 'Connection: close' -H 'Content-Length: 3113'

-b 'mid=XVLRpwABAAG_kqYiZihqukSRfL9F; csrftoken=ZsjKxFu1AfeyYlA1KuLCQNsgEBejsZbi; rur=FTW'

--data-binary 'signed_body=92c12ca534e63551811b194573cbe8d8cfaec19ec21c48ce9328b1d897689d65.%7B%22_csrftoken%22%3A%22ZsjKxFu1AfeyYlA1KuLCQNsgEBejsZbi%22%2C%22id%22%3A%22ffbe7b2f-1663-43d4-847b-c3f51803637e%22%2C%22server_config_retrieval%22%3A%221%22%2C%22experiments%22%3A%22ig_android_fci_onboarding_friend_search%2Cig_android_device_detection_info_upload%2Cig_android_sms_retriever_backtest_universe%2Cig_android_direct_add_direct_to_android_native_photo_share_sheet%2Cig_growth_android_profile_pic_prefill_with_fb_pic_2%2Cig_account_identity_logged_out_signals_global_holdout_universe%2Cig_android_login_identifier_fuzzy_match%2Cig_android_reliability_leak_fixes_h1_2019%2Cig_android_video_render_codec_low_memory_gc%2Cig_android_custom_transitions_universe%2Cig_android_push_fcm%2Cig_android_show_login_info_reminder_universe%2Cig_android_email_fuzzy_matching_universe%2Cig_android_one_tap_aymh_redesign_universe%2Cig_android_direct_send_like_from_notification%2Cig_android_suma_landing_page%2Cig_android_direct_main_tab_universe%2Cig_android_session_scoped_logger%2Cig_android_accoun_switch_badge_fix_universe%2Cig_android_smartlock_hints_universe%2Cig_android_black_out%2Cig_android_account_switch_infra_universe%2Cig_android_video_ffmpegutil_pts_fix%2Cig_android_multi_tap_login_new%2Cig_android_caption_typeahead_fix_on_o_universe%2Cig_android_save_pwd_checkbox_reg_universe%2Cig_android_nux_add_email_device%2Cig_android_direct_remove_view_mode_stickiness_universe%2Cig_username_suggestions_on_username_taken%2Cig_android_analytics_accessibility_event%2Cig_android_ingestion_video_support_hevc_decoding%2Cig_android_account_recovery_auto_login%2Cig_android_feed_cache_device_universe2%2Cig_android_sim_info_upload%2Cig_android_mobile_http_flow_device_universe%2Cig_account_recovery_via_whatsapp_universe%2Cig_android_hide_fb_button_when_not_installed_universe%2Cig_android_targeted_one_tap_upsell_universe%2Cig_android_gmail_oauth_in_reg%2Cig_android_native_logcat_interceptor%2Cig_android_hide_typeahead_for_logged_users%2Cig_android_vc_interop_use_test_igid_universe%2Cig_android_reg_modularization_universe%2Cig_android_phone_edit_distance_universe%2Cig_android_device_verification_separate_endpoint%2Cig_android_universe_noticiation_channels%2Cig_smartlock_login%2Cig_android_account_linking_universe%2Cig_android_hsite_prefill_new_carrier%2Cig_android_retry_create_account_universe%2Cig_android_family_apps_user_values_provider_universe%2Cig_android_reg_nux_headers_cleanup_universe%2Cig_android_device_info_foreground_reporting%2Cig_android_device_verification_fb_signup%2Cig_android_onetaplogin_optimization%2Cig_video_debug_overlay%2Cig_android_ask_for_permissions_on_reg%2Cig_assisted_login_universe%2Cig_android_display_full_country_name_in_reg_universe%2Cig_android_security_intent_switchoff%2Cig_android_device_info_job_based_reporting%2Cig_android_passwordless_auth%2Cig_android_direct_main_tab_account_switch%2Cig_android_modularized_dynamic_nux_universe%2Cig_android_fb_account_linking_sampling_freq_universe%2Cig_android_fix_sms_read_lollipop%2Cig_android_access_flow_prefill%22%7D&ig_sig_key_version=4'

'https://i.instagram.com/api/v1/qe/sync/'
```
___
## launcher/sync
### Request
```
https://i.instagram.com/api/v1/launcher/sync/
```
### Headers
```
X-Pigeon-Session-Id: eb7165e8-c590-4729-8656-7b57e4d9cdfd
X-Pigeon-Rawclienttime: 1565941500.518
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
Content-Length: 259
```
### Arguments encoded
```
signed_body=ea1156a7eb1aa2509766cd406e9462c8072d2b85d8a66c15e012e5150c12f756.%7B%22_csrftoken%22%3A%22ZsjKxFu1AfeyYlA1KuLCQNsgEBejsZbi%22%2C%22id%22%3A%22ffbe7b2f-1663-43d4-847b-c3f51803637e%22%2C%22server_config_retrieval%22%3A%221%22%7D&ig_sig_key_version=4
```
### Arguments decoded
```
signed_body=ea1156a7eb1aa2509766cd406e9462c8072d2b85d8a66c15e012e5150c12f756.{"_csrftoken":"ZsjKxFu1AfeyYlA1KuLCQNsgEBejsZbi","id":"ffbe7b2f-1663-43d4-847b-c3f51803637e","server_config_retrieval":"1"}&ig_sig_key_version=4
```
### CURL Command
```
curl -i -s -k  -X 'POST'

-H 'X-Pigeon-Session-Id: eb7165e8-c590-4729-8656-7b57e4d9cdfd' -H 'X-Pigeon-Rawclienttime: 1565941500.518' -H 'X-IG-Connection-Speed: -1kbps' -H 'X-IG-Bandwidth-Speed-KBPS: -1.000' -H 'X-IG-Bandwidth-TotalBytes-B: 0' -H 'X-IG-Bandwidth-TotalTime-MS: 0' -H 'X-IG-VP9-Capable: false' -H 'X-Bloks-Version-Id: 14f543394cf83e14784db6457e197a7e61e34fcd161891682143f74cb69a8981' -H 'X-IG-Connection-Type: WIFI' -H 'X-IG-Capabilities: 3brTvw==' -H 'X-IG-App-ID: 567067343352427' -H 'User-Agent: Instagram 103.1.0.15.119 Android (28/9; 420dpi; 1080x2034; unknown/Android; Google Pixel 3; vbox86p; vbox86; en_US; 164094540)' -H 'Accept-Language: en-US' -H 'Cookie: mid=XVLRpwABAAG_kqYiZihqukSRfL9F; csrftoken=ZsjKxFu1AfeyYlA1KuLCQNsgEBejsZbi; rur=FTW' -H 'Content-Type: application/x-www-form-urlencoded; charset=UTF-8' -H 'Accept-Encoding: gzip, deflate' -H 'Host: i.instagram.com' -H 'X-FB-HTTP-Engine: Liger' -H 'Connection: close' -H 'Content-Length: 259'

-b 'mid=XVLRpwABAAG_kqYiZihqukSRfL9F; csrftoken=ZsjKxFu1AfeyYlA1KuLCQNsgEBejsZbi; rur=FTW'

--data-binary 'signed_body=ea1156a7eb1aa2509766cd406e9462c8072d2b85d8a66c15e012e5150c12f756.%7B%22_csrftoken%22%3A%22ZsjKxFu1AfeyYlA1KuLCQNsgEBejsZbi%22%2C%22id%22%3A%22ffbe7b2f-1663-43d4-847b-c3f51803637e%22%2C%22server_config_retrieval%22%3A%221%22%7D&ig_sig_key_version=4'

'https://i.instagram.com/api/v1/launcher/sync/'
```
___
