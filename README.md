# 📱 Yet A Final Dani and Community's Guide!
⚠️ SOME FLAGS COULD HAVE A MISLEADING SETTING, ENABLED WHEN IT IS SUPPOSED TO BE DISABLED, REPORT THIS IN THE OFFICIAL SERVER

Welcome to the official end of the legendary **Community's Ultimate Guide by John and Dani**!

This is a community-driven project dedicated to tracking and documenting changes in Instagram's Android alpha versions by analyzing internal feature flags (GKs/QEs) from Metaconfig. Updates are automatically published to our Telegram channel and to this guide via a self-hosted bot, built and maintained by the community.

## 🌙 The Project is Now in Legacy Mode
**This project has entered a self-sustaining, community-driven "Legacy" state.** Active development by the original maintainer has ended — not because the project failed, but because the Instagram modding community's enthusiasm has been steadily declining, and it no longer makes sense to keep investing active development time into it. Instead of quietly abandoning it, the goal was to leave it in the best possible shape to keep running on its own, for as long as the community keeps contributing to it.

Before wrapping up, the following was completed as a final major update:
* **Bot rewrite** — recoded from scratch with `aiogram`. Multiple users can now run commands at the same time without the bot hanging or crashing.
* **Database migration** — over 2GB of raw files were moved into an optimized database under 50MB, cutting RAM usage and making changelog lookups (even 20+ versions apart) take a fraction of a second instead of tens of seconds.
* **Public API** — built for querying flag data and changelogs (the raw database files themselves stay private).
* **Autonomous guide updates** — community flag submissions sent through Telegram are now automatically processed and pushed straight to this guide, no manual work required.

This guide, the bot, and the API will keep running exactly as they are — for as long as the community keeps sending submissions. There are no more planned updates beyond that.

## 🤝 Built by the Community, for the Community
**Attention! This is a living document.**
The guide has fully transitioned to a **community-supported version**. This means that any user in the **Instagram Developer Community** can contribute to expanding and improving it. By opening the guide to community collaboration, everyone has the opportunity to share their insights, discovered features, and updates. Together, we can keep this a comprehensive and up-to-date resource for as long as people keep using it!

## 🙏 Acknowledgments
This project would not have made it this far without:
* **[@panagiotis25](https://t.me/panagiotis25) Panagiotis** — for being the first to fuel my enthusiasm for Instagram flags; without him, this project would never have started in the first place.
* **[@ioannisxir](https://t.me/ioannisxir) John Xirouchakis** — for helping kickstart the guide back at the very beginning.
* **[@Salman_memon](https://t.me/Salman_memon) Salman Memon** — for helping upload guides, keeping the project's motivation alive, and helping promote it.
* And above all, **[@iamzainnnn](https://t.me/iamzainnnn) 𝒁𝒂𝒊𝒏** — for uploading hundreds of versions without ever stopping, for keeping this project afloat, and for being the reason it's still alive today.

Thank you all, and thank you to everyone who contributed since this started on June 1, 2023. 🚀

---

## ⚙️ How it works
* Instagram alpha APKs are analyzed for changes in internal flags.
* Additions, removals, and updates are carefully documented and categorized.
* A Telegram bot automatically publishes each new changelog entry and guide update.
* The community contributes flag descriptions, testing, and feature context.

## 🔗 Resources
* 📢 **Telegram Channel:** [igdevdani](https://t.me/igdevdani)
* 🤝 **Contributing:** See the FAQ and community guidelines to start submitting your findings.

---

## ❓ FAQ (Frequently Asked Questions)

**I can't access the Developer Settings!**
> Make sure you have gone into *MetaConfig Settings and Overrides*—that is where all the flags are located.

**I don't see the Developer Settings when holding the home icon.**
> This only works for Instagram Mods that have the Developer Options enabled. It's not available on the stock Instagram app, as it is normally restricted to developers only.

**A flag is not working.**
> Check your base version. If you are on a supported base, the flag might be region-locked, available only to limited accounts (A/B testing), server-sided, or it has stopped working completely. If it has been completely removed or broken, the flag will eventually be moved to our Archive category.

**Instagram is crashing!**
> You have enabled a faulty flag (a flag that causes issues with some features or the core app). If this happens with a flag listed in our guide regarding new features, please kindly inform us so we can update it. Otherwise, we are not responsible for random crashes. To fix your app, clear the app data and start adding your flags all over again.

**I need support!**
> Send a message in the Patreon chat to get assistance from the team.

**Why don't flags added before the 305.0.0.0.107 base mention their specific version?**
> We use a mapping database for flag information configured specifically for bases from `305.0.0.0.107` and beyond. Because we cannot feasibly search all previous bases for historical flags (it would take forever), we simply use the label *"Added in version 305.0.0.0.107 or earlier"* for those older entries.

- [Important](#important)
  - [Make the app more efficient](#make-the-app-more-efficient)
  - [Prevent Instagram from taking lots of space in app data](#prevent-instagram-from-taking-lots-of-space-in-app-data)
  - [Remove the story ads with the "LEARN MORE" stickers inside](#remove-the-story-ads-with-the-learn-more-stickers-inside)
  - [Remove Threads usernames and button](#remove-threads-usernames-and-button)
- [Quality](#quality)
  - [Upload photos up to 1440p resolution in stories](#upload-photos-up-to-1440p-resolution-in-stories)
  - [Enable stereo](#enable-stereo)
- [UI](#ui)
  - [Redesign of the Message Requests](#redesign-of-the-message-requests)
  - [Channels tab](#channels-tab)
  - [New apperance of reactions](#new-apperance-of-reactions)
  - [New dark mode](#new-dark-mode)
  - [Redesign of the search section in Direct](#redesign-of-the-search-section-in-direct)
  - [Timestamps](#timestamps)
  - [Enable threads icon in profile menu](#enable-threads-icon-in-profile-menu)
  - [Fix empty space below bottom navigation bar](#fix-empty-space-below-bottom-navigation-bar)
  - [Open links in external browser](#open-links-in-external-browser)
- [Feed](#feed)
  - [New sharing shortcut](#new-sharing-shortcut)
  - [Quick share](#quick-share)
- [Reels](#reels)
  - [Avatar comments](#avatar-comments)
  - [Download reels](#download-reels)
- [Comments](#comments)
  - [Write comments anonymously](#write-comments-anonymously)
  - [Avatars in comments](#avatars-in-comments)
- [Explore](#explore)
  - [Reduce and hide sensitive content](#reduce-and-hide-sensitive-content)
- [Stories](#stories)
  - [Add comments to stories](#add-comments-to-stories)
  - [Custom color stickers](#custom-color-stickers)
  - [Music sticker with avatar stickers](#music-sticker-with-avatar-stickers)
- [Camera](#camera)
  - [Organised toolbar in Stories creation](#organised-toolbar-in-stories-creation)
- [Direct](#direct)
  - [Animated avatar stickers](#animated-avatar-stickers)
  - [Non text replies](#non-text-replies)
  - [Reply box on sent reels](#reply-box-on-sent-reels)
  - [Resize preview of shared reels](#resize-preview-of-shared-reels)
  - [Sent reel indicator on chat previews](#sent-reel-indicator-on-chat-previews)
  - [Threshold for displaying the number of unread messages](#threshold-for-displaying-the-number-of-unread-messages)
- [Profile](#profile)
  - ["Threads" button added to profile header tab](#threads-button-added-to-profile-header-tab)
  - [Avatar as profile picture](#avatar-as-profile-picture)
  - [External sharing](#external-sharing)
  - [Insights for all accounts](#insights-for-all-accounts)
  - [Remove suggested accounts](#remove-suggested-accounts)
- [Fixes](#fixes)
  - [Bring back the filters in Stories creation](#bring-back-the-filters-in-stories-creation)
  - [Fix not being able to press anything on the media picker in stories](#fix-not-being-able-to-press-anything-on-the-media-picker-in-stories)
  - [Fix the weirdly streched reels](#fix-the-weirdly-streched-reels)
  - [Fix low light mode being always enabled](#fix-low-light-mode-being-always-enabled)
  - [Fix not being able to record videos for stories](#fix-not-being-able-to-record-videos-for-stories)
- [OUTDATED OR REMOVED - OLDER THAN VERSION 448.0.0.0.13](#outdated-or-removed---older-than-version-44800013)

# Important
## Make the app more efficient

❌ `ig_analytics2_consolidation` `[29064]`

## Prevent Instagram from taking lots of space in app data

`ig_analytics2_consolidation` `[29064]`
  - `max_batch_lock_attempts` = 0 `[111]`

## Remove the story ads with the "LEARN MORE" stickers inside

✅ `ig_android_stories_cta_stickers` `[40751]`

## Remove Threads usernames and button

✅ `ig_spain_growth` `[58467]`

# Quality
## Upload photos up to 1440p resolution in stories
By default the photos you upload to stories are 1080, enabling this setting will increase the resolution up to 1440.

✅ `ig_android_ensure_1440p_photo_upload` `[23744]`

## Enable stereo

`android_cameracore_fbaudio_ig_launcher` `[31064]`
  - ✅ `use_stereo` `[21]`

# UI
## Redesign of the Message Requests

✅ `igd_message_requests` `[53626]`

## Channels tab
Enable everything except: (Outdated)

✅ `ig_android_channels_inbox_discovery` `[55958]`

## New apperance of reactions
Disable if the reactions are buggy

✅ `ig_android_direct_multi_react_xstack` `[62067]`

## New dark mode
Enable the new dark mode in instagram, from being an AMOLED black to a more pleasant dark blue.

✅ `igds_prism_launcher_config_android` `[62246]`

## Redesign of the search section in Direct

✅ `android_igd_search_h2_2023` `[62449]`

## Timestamps
Show when the post/reel was posted.

✅ `ig_feed_marie_kondo_android` `[62969]`

## Enable threads icon in profile menu

`ig_spain_growth` `[58467]`
  - ✅ `is_ig_to_p92_app_switcher_enabled_android` `[20]`

## Fix empty space below bottom navigation bar
Doesn't work anymore

`ig_android_foldable_responsive_window_insets` `[56160]`
  - ✅ `is_mw_bottom_padding_enabled` `[1]`

## Open links in external browser

`ig_android_browser_lite` `[39443]`
  - ✅ `should_override_to_external_browser` `[3]`

# Feed
## New sharing shortcut
Attention!!! Not recommended to activate the 3rd option because the "add X to your story" button will stop appearing on the IGTV posts and regular ones in the Profile & Explore tabs.

✅ `ig_android_super_share_v3` `[56850]`

## Quick share
Hold the share button to quickly share the post to a user.

✅ `ig_android_quick_send_tlc` `[60484]`

# Reels
## Avatar comments

✅ `ig_android_avatars_in_comments` `[62329]`

## Download reels
Press the share button and press Download.

✅ `ig_reels_third_party_downloads` `[56124]`

# Comments
## Write comments anonymously

✅ `ig_ghost_writer` `[60408]`

## Avatars in comments

✅ `ig_android_avatars_in_comments` `[62329]`

# Explore
## Reduce and hide sensitive content

✅ `igmwb_explore_controls` `[47680]`

# Stories
## Add comments to stories
Pending launch

✅ `ig_story_interactions_hype` `[56859]`

## Custom color stickers
Working for location, mention, link, and hashtag stickers.

✅ `ig_android_stories_custom_color_gradient_stickers` `[48493]`

## Music sticker with avatar stickers

`ig_android_avatars_avatar_with_music_sticker` `[48850]`
  - ✅ `is_animated_stickers_enabled` `[4]`

# Camera
## Organised toolbar in Stories creation

`ig_stories_music_in_postcap_toolbar_launcher` `[59802]`
  - ✅ `show_effects_in_overflow` `[4]`

# Direct
## Animated avatar stickers

✅ `igd_animated_avatar_stickers` `[53317]`

## Non text replies
Enable replies with photos, videos, audios, etc

✅ `igd_non_text_replies` `[56702]`

## Reply box on sent reels
Show reply box when you open a reel that was sent to you

✅ `ig_android_reels_consumption_v1` `[57849]`

## Resize preview of shared reels
Default: 164

✅ `ig_android_clips_direct_reshare_size` `[51078]`

## Sent reel indicator on chat previews

✅ `ig_android_reels_consumption_v2` `[63017]`

## Threshold for displaying the number of unread messages

`ig_android_direct_inbox_snapshot_limits` `[26104]`
  - ✅ `snapshot_messages_per_thread_count` `[1]`

# Profile
## "Threads" button added to profile header tab

`ig_spain_growth` `[58467]`
  - ✅ `is_ig_to_p92_app_switcher_enabled_android` `[20]`

## Avatar as profile picture

`ig_avatars_android_profile` `[49180]`
  - ✅ `is_coin_flip_ssr_enabled` `[6]`

## External sharing

`ig_external_sharing` `[44750]`
  - ✅ `can_download_nametag_image_mode_pdf` `[45]`

## Insights for all accounts

✅ `ig4a_insights_for_public` `[65122]`

## Remove suggested accounts

`ig_account_discovery_launcher` `[33903]`
  - ✅ `self_profile_chaining_enabled` `[2]`

# Fixes
## Bring back the filters in Stories creation

✅ `ig4a_effect_filtering_migration` `[50133]`

## Fix not being able to press anything on the media picker in stories
Disable everything

❌ `ig_android_gallery_modularization` `[63695]`

## Fix the weirdly streched reels

❌ `ig_android_av1_playback` `[45757]`

## Fix low light mode being always enabled

`ig_android_low_light_mode_capture` `[55533]`
  - ✅ `is_enabled` `[0]`

## Fix not being able to record videos for stories

`android_cameracore_fbaudio_ig_launcher` `[31064]`
  - ✅ `enable_state_machine` `[14]`


# OUTDATED OR REMOVED - OLDER THAN VERSION 448.0.0.0.13
## Important
- Disable Thread posts in the feed (last removed in 393.0.0.0.22)
  ✅ `ig_threads_xma` `[61804]` **Removed in version 393.0.0.0.22**

- Enable the shake phone to report a problem sheet even if you disabled it (last removed in 342.0.0.0.23)
  ✅ `ig_android_rageshake_ui` `[30451]` **Removed in version 342.0.0.0.23**

- Messenger update (last removed in 317.0.0.0.36)
  ✅ `igd_xac_unbundle` `[56088]` **Removed in version 317.0.0.0.36**

- Remove the reel ads and improve/fix adblocking in Instagram mods (last removed in 387.0.0.0.61)
  ✅ `ig_sundial_ads` `[33268]` **Removed in version 387.0.0.0.61**

- Remove the Google Play update dialog (last added in 409.0.0.0.17)
  ❌ `ig_google_play_update_api` `[57502]` **Added in version 409.0.0.0.17**

- Disable Device Permissions Popup (last removed in 446.0.0.0.12)
  ❌ `ig_device_permissions` `[64463]` **Removed in version 446.0.0.0.12**


## Quality
- High quality video uploads on stories and reels (last removed in 385.0.0.0.32)
  `ig_android_high_quality_upload_setting` = 20 `[49978]` **Removed in version 385.0.0.0.32**

- Improve quality of posts (last added in 385.0.0.0.32)
  ✅ `ig_android_high_quality_upload_setting_fbid` `[91245]` **Added in version 385.0.0.0.32**

- Reduce compression of photo uploads in the feed (last added in 357.0.0.0.90)
  ✅ `ig_camera_android_ultra_hdr_photo_creation` `[80055]` **Added in version 357.0.0.0.90**

- 4K Quality Command (last added in 425.0.0.0.6)
  ✅ `ig_android_4k_image_upload` `[117622]` **Added in version 425.0.0.0.6**

- Enable 48khz sample rate (last removed in 419.0.0.0.60)
  `android_cameracore_fbaudio_ig_launcher` `[31064]`
    - ✅ `use_48khz_sample_rate` `[18]` **Removed in version 419.0.0.0.60**


## UI
- Variations of the Reel uploading section (last removed in 388.0.0.0.67)
  `ig_android_reels_publish_screen_decluttering` `[71831]` **Removed in version 388.0.0.0.67**
    - ✅ `enable_variant_a` `[3]` **Removed in version 345.0.0.0.79**

- Accessibility settings (last removed in 348.0.0.0.7)
  ✅ `ig_accessibility_setting` `[41236]` **Removed in version 348.0.0.0.7**

- Album picker (last added in 346.0.0.0.66)
  ✅ `ig_android_gallery_album_picker_menu` `[76418]` **Added in version 346.0.0.0.66**

- Android widget (last removed in 318.0.0.0.80)
  ✅ `ig_android_direct_widget` `[49971]` **Removed in version 318.0.0.0.80**

- Call screen redesign (last removed in 333.0.0.0.33)
  ✅ `ig_android_vc_halo_call_controls` `[33674]` **Removed in version 333.0.0.0.33**

- Change activity icon to bell icon (last removed in 363.0.0.0.63)
  ✅ `p92_activity_feed_bell_icon_device_scoped` `[73316]` **Removed in version 363.0.0.0.63**

- Content languages (last removed in 388.0.0.0.62)
  ✅ `ig4a_content_languages` `[57434]` **Removed in version 388.0.0.0.62**

- Creator support option in Settings (last removed in 434.0.0.0.35)
  ✅ `ig_creator_support_portal` `[36173]` **Removed in version 434.0.0.0.35**

- Customize buttons layout (last removed in 434.0.0.0.8)
  ✅ `ig_panavision_nav3_launcher` `[47131]` **Removed in version 434.0.0.0.8**

- Direct new icon (last removed in 386.0.0.4.84)
  ✅ `ig_direct_interop_rebrand` `[24692]` **Removed in version 386.0.0.4.84**

- Fundraiser redesign (last removed in 327.0.0.0.92)
  ✅ `ig_android_fundraiser_donation_sheet_redesign` `[28676]` **Removed in version 327.0.0.0.92**

- Media previews in stories (last removed in 361.0.0.0.33)
  ✅ `ig_media_previews_in_stories_tray` `[65590]` **Removed in version 361.0.0.0.33**

- Merge a lot of actions into a Plus button in the Direct chat list (last removed in 432.0.0.0.66)
  ✅ `ig_android_action_based_conversations` `[71372]` **Removed in version 432.0.0.0.66**

- Merge audio and video call icons together and get an info button in chats (last removed in 355.0.0.0.85)
  ✅ `ig_direct_thread_details_discovery` `[67900]` **Removed in version 355.0.0.0.85**

- More details about broadcast channels on the search section in Direct (last removed in 419.0.0.0.25)
  `android_igd_search_h1_2023` `[54874]`
    - ❌ `disable_inbox_cache_results` `[23]` **Removed in version 332.0.0.0.24**
    - ❌ `disable_rtr_on_share_sheet_private_share` `[34]` **Removed in version 419.0.0.0.25**

- Move the Alt Text option from the Advanced Settings to the normal ones (last removed in 341.0.0.0.1)
  ✅ `ig_custom_alt_text_update` `[50864]` **Removed in version 341.0.0.0.1**

- Multiple comment tabs (last removed in 370.0.0.0.67)
  ✅ `ig_android_comment_sheet_multi_tabs` `[55075]` **Removed in version 370.0.0.0.67**

- Music picker as the default post editing option with a redesigned appearance (last removed in 377.0.0.0.20)
  ✅ `ig_android_mif_creation_post_cap` `[70063]` **Removed in version 377.0.0.0.20**

- New filters icon (last removed in 411.0.0.0.84)
  ✅ `ig_ar_effects_icon_change` `[65144]` **Removed in version 411.0.0.0.84**

- New loading screen (last removed in 370.0.0.0.67)
  ✅ `ig_android_async_app_init_clone` `[66193]` **Removed in version 370.0.0.0.67**

- New pip mode for audio calls (last removed in 358.0.0.0.4)
  ✅ `ig_android_lounge` `[44718]` **Removed in version 358.0.0.0.4**

- New stories stickers menu design (last added in 308.0.0.0.57)
  ✅ `ig_android_stories_sticker_tray_redesign` `[65751]` **Added in version 308.0.0.0.57**

- New swipe to camera animation (last removed in 355.0.0.0.85)
  ✅ `ig_camera_android_nav3_bottom_creation_animation` `[57497]` **Removed in version 355.0.0.0.85**

- Redesign of the media picker in Direct (last removed in 326.0.0.0.29)
  ✅ `ig_android_convos_reshare_hub` `[41691]` **Removed in version 326.0.0.0.29**

- Redesign of the media previews of stories (last added in 322.0.0.0.81)
  ✅ `ig_stories_in_feed_redesign` `[69624]` **Added in version 322.0.0.0.81**

- Redesign of the media reordering on the carousel post editor (last removed in 381.0.0.0.75)
  ✅ `ig_camera_android_feed_carousel_reorder` `[70139]` **Removed in version 381.0.0.0.75**

- Redesign of the message actions in Direct (last removed in 440.0.0.0.25)
  ✅ `igd_long_press_message_action_android` `[51328]` **Removed in version 440.0.0.0.25**

- Redesign of the post editing section (last removed in 394.0.0.0.29)
  ✅ `ig_android_post_editing_flow_updates` `[62466]` **Removed in version 394.0.0.0.29**

- Redesign of the reaction counter animation in Direct (last added in 328.0.0.0.18)
  ✅ `ig_android_direct_reaction_counter_animations` `[70706]` **Added in version 328.0.0.0.18**

- Redesign of the search bar in Direct (last added in 321.0.0.0.17)
  ✅ `igd_android_gen_ai_search_xstack` `[62485]` **Added in version 321.0.0.0.17**

- Redesign of the text creator in Reels editor (last added in 317.0.0.0.3)
  ✅ `ig_android_reels_feels_like_ig_text` `[67701]` **Added in version 317.0.0.0.3**

- Redesign of the Text to Speech picker in Reels editor (last removed in 341.0.0.0.61)
  ✅ `ig_camera_android_reels_tts_postcap` `[68686]` **Removed in version 341.0.0.0.61**

- Redesigned comment section (last removed in 368.0.0.0.74)
  ✅ `ig_android_comments_mvvm_migration` `[58179]` **Removed in version 368.0.0.0.74**

- Reel view counts in the profile and redesign of the existing ones in the Reels tab (last removed in 348.0.0.0.99)
  ✅ `ig_clips_android_profile_view_count` `[72501]` **Removed in version 348.0.0.0.99**

- Save Draft button in post publishing section (last removed in 339.0.0.0.80)
  ✅ `ig_android_feed_publish_screen_redesign` `[62651]` **Removed in version 339.0.0.0.80**

- Show live in direct panel (last removed in 361.0.0.0.84)
  ✅ `ig_live_android_direct` `[58241]` **Removed in version 361.0.0.0.84**

- Thick story ring (last removed in 336.0.0.0.34)
  ✅ `ig_craft_android_pog_parity` `[64684]` **Removed in version 336.0.0.0.34**

- Story Interest Signals (last added in 371.0.0.0.6)
  ✅ `ig_android_reels_overflow_interested_options` `[84236]` **Added in version 371.0.0.0.6**

- Minimal Overflow Menu Icon (last added in 425.0.0.0.17)
  ✅ `ig_overflow_menu_icon` `[117613]` **Added in version 425.0.0.0.17**

- Story Upload Progress Percentage (last removed in 446.0.0.0.0)
  ✅ `ig_android_story_upload_progress_percentage` `[115501]` **Removed in version 446.0.0.0.0**

- Note Likes UI (last added in 427.0.0.0.38)
  ✅ `ig_android_notes_public_comments_v2` `[119100]` **Added in version 427.0.0.0.38**

- Redesign of the send button in the gallery picker in Direct (last removed in 421.0.0.0.50)
  `igd_android_media_preview_fbid` `[68556]` **Added in version 319.0.0.0.33**
    - ✅ `view_mode_selector_enabled` `[16]` **Removed in version 421.0.0.0.50**

- Dark gallery in Direct at all times (last added in 327.0.0.0.92)
  `igd_android_media_preview_fbid` `[68556]` **Added in version 319.0.0.0.33**
    - ✅ `gallery_dark_theme` `[17]` **Added in version 327.0.0.0.92**

- Rename the Advanced Settings to More Options (last removed in 388.0.0.0.67)
  `ig_android_reels_publish_screen_decluttering` `[71831]` **Removed in version 388.0.0.0.67**
    - ✅ `should_rename_advanced_settings` `[0]` **Removed in version 343.0.0.0.72**

- Extra Activity Status setting in Direct (last removed in 375.0.0.0.17)
  `ig_android_presence_activity_status_settings_screen_launcher` `[47832]` **Removed in version 375.0.0.0.17**
    - ✅ `enable_bloks_www_activity_status_settings_screen` `[0]` **Removed in version 375.0.0.0.17**

- Filled bottom row buttons (last removed in 434.0.0.0.8)
  `ig_panavision_nav3_launcher` `[47131]` **Removed in version 434.0.0.0.8**
    - ✅ `filled_tab_icons_enabled` `[12]` **Removed in version 434.0.0.0.8**

- New heart like animation (last added in 310.0.0.0.9)
  ✅ `ig_android_new_double_tap_heart_animation` `[66115]` **Added in version 310.0.0.0.9**

- New login UI (last removed in 333.0.0.0.9)
  `fx_ig_android_switcher_wave_2_3_fdid` `[50769]`
    - ✅ `bypass_triage_oe` `[1]` **Removed in version 333.0.0.0.9**

- Old settings UI (last removed in 342.0.0.0.0)
  `ig_fx_centralized_settings` `[40559]`
    - ❌ `show_entrypoint` `[3]` **Removed in version 310.0.0.0.295**

  `ig_project_elevation` `[51538]` **Removed in version 342.0.0.0.0**
    - ❌ `enabled` `[0]` **Removed in version 342.0.0.0.0**

- New Button Design Across Instagram (last added in 404.0.0.0.46)
  ✅ `android_material_components` `[101772]` **Added in version 404.0.0.0.46**

- Comment Composer Rotate Ghost Text (last added in 403.0.0.0.0)
  ✅ `ig_android_comment_composer_rotate_ghost_text` `[100545]` **Added in version 403.0.0.0.0**

- Follow button in stories viewers list (last added in 405.0.0.0.0)
  ✅ `ig_follow_button_in_stories_viewers_list` `[102000]` **Added in version 405.0.0.0.0**

- Profile unseen post indicator (last added in 394.0.0.0.7)
  ✅ `ig_android_profile_unseen_post_h2_2025` `[95085]` **Added in version 394.0.0.0.7**

- Indicador de amigos próximos na aba de compartilhar (last removed in 418.0.0.0.41)
  ✅ `igd_sharesheet_close_friends_indicator` `[104446]` **Removed in version 418.0.0.0.41**

- New design in notification settings (last added in 387.0.0.0.61)
  ✅ `ig4a_notifications_setting` `[91066]` **Added in version 387.0.0.0.61**

- Airplane Button Share (last added in 411.0.0.0.84)
  ✅ `igd_quick_send` `[106331]` **Added in version 411.0.0.0.84**

- Cast Instagram to TV (last added in 406.0.0.0.96)
  ✅ `ig_airwave_settings_bookmark` `[103010]` **Added in version 406.0.0.0.96**

- Visual moderno de menu (last added in 402.0.0.0.5)
  ✅ `ig_igds_android_prism_overflow_sheet` `[100002]` **Added in version 402.0.0.0.5**

- New visual of the account center in settings (last added in 410.0.0.0.19)
  `xe_ac_entrypoint_ig` `[103432]` **Added in version 407.0.0.0.196**
    - ❌ `xe_ig_entrypoint_variant1` `[5]` **Added in version 410.0.0.0.19**

- Minimize the number of apps in the "also from meta" section in settings. (last added in 389.0.0.0.6)
  ✅ `igs2_tier1_meta_apps_revamp` `[92808]` **Added in version 389.0.0.0.6**

- Plus button in stories tray (last removed in 335.0.0.0.12)
  `ig_stories_show_menu_on_self_story_pog` `[58677]` **Removed in version 335.0.0.0.12**
    - ✅ `icon_over_ring_enabled` `[1]` **Removed in version 335.0.0.0.12**

- Redesign of the saving post draft animation (last removed in 388.0.0.0.21)
  `ig_android_reels_and_feed_sharing_draft_optimizations` `[64653]` **Removed in version 388.0.0.0.21**
    - ✅ `feed_initial_exit_save_spinner_enabled` `[6]` **Removed in version 388.0.0.0.21**

- Show save animation (last removed in 318.0.0.0.80)
  `ig_direct_collaborative_collections` `[45238]` **Removed in version 318.0.0.0.80**
    - ✅ `should_show_save_flow_on_tap` `[2]` **Removed in version 318.0.0.0.80**

- Notes self sheet view Redesign (last added in 429.0.0.0.31)
  ✅ `ig_notes_self_sheet_redesign` `[120352]` **Added in version 429.0.0.0.31**


## Feed
- Add texts, stickers and overlay photos in posts (last added in 316.0.0.0.67)
  ✅ `ig_android_feed_text_stickers` `[67653]` **Added in version 316.0.0.0.67**

- Orientation options for photos in the post editing section (last removed in 405.0.0.0.58)
  ✅ `ig_android_feed_multiple_aspect_ratios` `[71060]` **Removed in version 405.0.0.0.58**

- Add music to carousel posts with video (last removed in 413.0.0.0.33)
  ✅ `ig_music_in_carousel_2024` `[68346]` **Removed in version 413.0.0.0.33**

- Add notes to posts/reels (last added in 317.0.0.0.3)
  ✅ `ig4a_content_notes_fbidv2` `[67738]` **Added in version 317.0.0.0.3**

- Audience controls (last removed in 386.0.0.4.84)
  ✅ `ig_android_audience_controls` `[49793]` **Removed in version 386.0.0.4.84**

- Auto advance carrousel posts (last added in 409.0.0.0.57)
  ✅ `ig4a_fbid_concurrent_grid_video_autoplay` `[104779]` **Added in version 409.0.0.0.57**

- Comments translations (last removed in 338.0.0.0.81)
  ✅ `ig_android_comments_translations` `[51191]` **Removed in version 338.0.0.0.81**

- Feed nav scroll away (last removed in 434.0.0.0.0)
  ✅ `ig_android_feed_scroll_away_nav` `[54983]` **Removed in version 434.0.0.0.0**

- Multi select photos on by default (last removed in 377.0.0.0.20)
  ✅ `ig_android_feed_creation_multiselect_enabled` `[60151]` **Removed in version 377.0.0.0.20**

- New sharing sheet (last removed in 424.0.0.0.13)
  `ig_android_super_share_v3` `[56850]`
    - `add_to_story_hscroll` = 0 `[2]` **Removed in version 424.0.0.0.13**

- Redesigned circles on the sharing sheet (last removed in 366.0.0.0.1)
  ✅ `ig_android_visual_hscroll` `[69639]` **Removed in version 366.0.0.0.1**

- Reminder post (last removed in 337.0.0.15.102)
  ✅ `ig_android_upcoming_events_creation_universe` `[24606]` **Removed in version 337.0.0.15.102**

- Shorter reels on the feed (last added in 426.0.0.0.8)
  ❌ `ig_collection_tall_video` `[118065]` **Added in version 426.0.0.0.8**

- Simplified like, comment and share counts in the feed (last removed in 333.0.0.0.26)
  ✅ `ig_android_simplified_post_layout` `[55553]` **Removed in version 333.0.0.0.26**

- Feed video 2x speed (last added in 424.0.0.0.63)
  ✅ `ig_feed_video_2x_speed` `[103957]` **Added in version 424.0.0.0.63**

- Edit comment (last added in 416.0.0.0.65)
  ✅ `ig4a_comment_editing` `[109051]` **Added in version 416.0.0.0.65**

- Carousel Individual Captions (last removed in 441.0.0.0.20)
  ✅ `ig_android_carousel_individual_captions` `[111882]` **Removed in version 441.0.0.0.20**

- Silent Post to Profile (last added in 433.0.0.0.0)
  ✅ `ig_android_aura_silent_post_to_profile` `[119699]` **Added in version 433.0.0.0.0**

- Programar posts and reels reels to date (last removed in 407.0.0.0.207)
  ✅ `ig_android_posts_publish_screen_decluttering` `[75600]` **Removed in version 407.0.0.0.207**

- Loop every reel for a second time in the feed (last removed in 332.0.0.0.18)
  `ig_android_clips_feed_preview` `[24714]` **Removed in version 332.0.0.0.18**
    - `feed_video_min_length_for_single_loop_ms` = 1000000 `[14]` **Removed in version 332.0.0.0.18**


## Reels
- Add multiple clips on the reel editor at once (last removed in 421.0.0.0.3)
  ✅ `ig_android_reels_add_clips_multiselect_enabled` `[65055]` **Removed in version 421.0.0.0.3**

- Add multiple tracks on Reel editor (last removed in 387.0.0.0.61)
  ✅ `ig_camera_android_multiple_audio_tracks` `[64392]` **Removed in version 387.0.0.0.61**

- Audio effects (last removed in 430.0.0.0.22)
  ✅ `ig_camera_android_reels_audio_filters` `[62376]` **Removed in version 430.0.0.0.22**

- Automatically scrolling reels (last removed in 398.0.0.0.43)
  ✅ `ig_reels_auto_scroll_v1` `[66707]` **Removed in version 398.0.0.0.43**

- Caption translations (last removed in 356.0.0.0.93)
  ✅ `ig_android_clips_viewer_caption_see_translation` `[43242]` **Removed in version 356.0.0.0.93**

- Clear mode (last added in 330.0.0.0.81)
  `ig_android_reels_gestures` = 1 `[72006]` **Added in version 330.0.0.0.81**

- Clip hub (last removed in 385.0.0.0.32)
  ✅ `ig_camera_android_tp_media` `[61454]` **Removed in version 385.0.0.0.32**

- Comments for you (last removed in 338.0.0.0.81)
  ✅ `ig_android_comments_for_you` `[64226]` **Removed in version 338.0.0.0.81**

- Create cutout stickers with audio (last removed in 342.0.0.0.0)
  ✅ `ig_android_cutout_sticker_audio` `[69605]` **Removed in version 342.0.0.0.0**

- Effects in Reels (last removed in 334.0.0.0.33)
  ✅ `ig_camera_android_timeline_ar_effects_button` `[58408]` **Removed in version 334.0.0.0.33**

- Enable listen in spotify, or add to spotify playlist (last removed in 385.0.0.0.32)
  ✅ `ig_android_spotify_partnership` `[62244]` **Removed in version 385.0.0.0.32**

- Fast forward reels (last removed in 371.0.0.0.31)
  ✅ `ig_android_long_press_fast_reels` `[67378]` **Removed in version 371.0.0.0.31**

- Filter (last removed in 362.0.0.0.218)
  ✅ `ig_android_clips_tab_dsa` `[57498]` **Removed in version 362.0.0.0.218**

- Fixed brightness in the Reels section (last removed in 343.0.0.0.5)
  ✅ `ig_android_clips_brightness` `[59060]` **Removed in version 343.0.0.0.5**

- Floating friend’s likes (last added in 348.0.0.0.7)
  ❌ `ig_android_clips_friendly_viewer_launch` `[76834]` **Added in version 348.0.0.0.7**

- Hide suggested posts with certain words (last removed in 410.0.0.0.7)
  ✅ `ig_hide_unconnected_posts_with_words` `[47507]` **Removed in version 410.0.0.0.7**

- Hold the reel to see a preview on your profile on the reel editor (last removed in 386.0.0.4.84)
  ✅ `ig_camera_android_postcap_reels_viewer_preview` `[57537]` **Removed in version 386.0.0.4.84**

- Inspiration, Nearby, and Internal tabs in Reels (last added in 326.0.0.0.4)
  `ig_android_clips_content_lanes` `[58377]`
    - ❌ `enable_creator_inspiration_lane_prefetch` `[11]` **Added in version 326.0.0.0.4**

- New add to text bar on the Reels editor (last removed in 363.0.0.0.25)
  ✅ `ig_camera_android_timeline_text_ghost_track` `[65868]` **Removed in version 363.0.0.0.25**

- New comments menu (last removed in 374.0.0.0.66)
  ✅ `ig_android_comment_actions_menu` `[58962]` **Removed in version 374.0.0.0.66**

- Pinch to zoom in reels (last added in 333.0.0.0.87)
  ✅ `ig4a_reels_pinch_to_zoom` `[72984]` **Added in version 333.0.0.0.87**

- Profile Display (last removed in 344.0.0.0.78)
  ✅ `ig_camera_android_reels_profile_display` `[65682]` **Removed in version 344.0.0.0.78**

- Reels blends (last removed in 395.0.0.0.106)
  ✅ `ig_android_reels_blends` `[69355]` **Removed in version 395.0.0.0.106**

- Reels map (last removed in 340.0.0.0.16)
  ✅ `ig_android_reels_map` `[50253]` **Removed in version 340.0.0.0.16**

- Reels seekbar (last removed in 362.0.0.0.105)
  `ig_clips_viewer_scrubber_improvements` `[55196]` **Removed in version 362.0.0.0.105**
    - ✅ `preview_thumbnails_are_enabled` `[8]` **Removed in version 332.0.0.0.31**
    - `attached_scrubber_duration` = 1 `[5]` **Removed in version 332.0.0.0.31**

- Reels stacks (last added in 327.0.0.0.70)
  ✅ `ig_android_reels_stacks` `[71131]` **Added in version 327.0.0.0.70**

- Replies to replies (last removed in 409.0.0.0.0)
  ✅ `ig_comments_replies_to_replies` `[65837]` **Removed in version 409.0.0.0.0**

- Share comments (last removed in 318.0.0.0.65)
  ✅ `ig_android_conversations_comment_reshares` `[43332]` **Removed in version 318.0.0.0.65**

- Show the number of views on your own reels (last removed in 317.0.0.0.36)
  ✅ `ig_reels_played_by` `[52376]` **Removed in version 317.0.0.0.36**

- Tap header to scroll to top (last removed in 364.0.0.0.12)
  ✅ `ig_android_reels_scroll_to_top_status_bar_disabled` `[65329]` **Removed in version 364.0.0.0.12**

- Tap on the reel preview on the editor to add text (last removed in 362.0.0.0.48)
  `ig_android_reels_tap_to_add_text` `[69501]` **Removed in version 362.0.0.0.48**
    - ✅ `is_enabled` `[0]` **Removed in version 362.0.0.0.48**

- Text to speech (last removed in 320.0.0.0.87)
  ✅ `ig_reels_text_to_speech` `[35587]` **Removed in version 320.0.0.0.87**

- Timestamp (last removed in 355.0.0.0.13)
  ✅ `ig_android_clips_relative_timestamp` `[33454]` **Removed in version 355.0.0.0.13**

- Translate auto generated captions (last added in 314.0.0.0.100)
  ✅ `ig_android_reels_closed_captions_translations` `[67269]` **Added in version 314.0.0.0.100**

- Use the same colour in texts by default (last removed in 379.0.0.0.71)
  ✅ `ig_camera_android_reels_sticky_text` `[69192]` **Removed in version 379.0.0.0.71**

- Reels Picture-in-Picture Playback (last added in 378.0.0.0.4)
  ✅ `ig_android_reels_pip` `[87480]` **Added in version 378.0.0.0.4**

- Playback Speed in Reels Menu (last added in 417.0.0.0.38)
  ✅ `ig_android_reels_overflow_menu_playback_speed` `[109947]` **Added in version 417.0.0.0.38**

- Reels Timestamp Comments (last added in 401.0.0.0.26)
  ✅ `ig_reels_timestamp_comments` `[99556]` **Added in version 401.0.0.0.26**

- Save video button in the Reels tab (last added in 409.0.0.0.0)
  `ig_android_reels_save_ufi` `[104612]` **Added in version 409.0.0.0.0**
    - ❌ `should_hide_audio_ufi` `[2]` **Added in version 409.0.0.0.0**

- Repost Mini Menu (last added in 414.0.0.0.10)
  ✅ `ig_android_multi_tap_repost` `[107347]` **Added in version 414.0.0.0.10**

- Full screen reels (last removed in 434.0.0.0.0)
  `ig_android_clips_playback` `[66537]` **Added in version 310.0.0.0.214**
    - ✅ `force_scaling_mode_fit_for_clips` `[0]` **Added in version 320.0.0.0.94**

  `ig_android_feed_scroll_away_nav` `[54983]` **Removed in version 434.0.0.0.0**
    - ✅ `is_extended_scrollaway_nav_enabled_for_reels` `[5]` **Removed in version 434.0.0.0.0**

- Hide Follow button (last removed in 393.0.0.0.57)
  `ig_reels_interactivity_flywheel_test` `[52814]` **Removed in version 393.0.0.0.57**
    - ✅ `android_viewer_disable_follow_button` `[12]` **Removed in version 393.0.0.0.57**

- Remove the audio description under the username in Reels (last removed in 369.0.0.0.3)
  `ig_android_clips_friendly_viewer` `[67072]` **Removed in version 369.0.0.0.3**
    - ❌ `should_add_audio_secondary_text` `[12]` **Removed in version 369.0.0.0.3**

- Remove the audio pills at the bottom (last removed in 369.0.0.0.3)
  `ig_android_clips_friendly_viewer` `[67072]` **Removed in version 369.0.0.0.3**
    - ✅ `should_hide_attribution_hub` `[9]` **Removed in version 369.0.0.0.3**

- Remove the countdown from Voiceover on the reel editor (last removed in 373.0.0.0.25)
  `ig_camera_android_reels_stacked_timeline_voiceover` `[61524]` **Removed in version 373.0.0.0.25**
    - ✅ `skip_countdown` `[4]` **Removed in version 373.0.0.0.25**

- Reverse clips on the reel editor (last removed in 368.0.0.0.25)
  `ig_camera_android_clips_stacked_timeline_clip_reverse` `[65336]` **Removed in version 368.0.0.0.25**
    - ✅ `enable_clip_reverse` `[0]` **Removed in version 368.0.0.0.25**

- Short comment hint text (last removed in 402.0.0.0.0)
  `ig_android_comments_craft_h2_2023` `[62816]` **Removed in version 402.0.0.0.0**
    - ✅ `should_shorten_comment_hint_text` `[0]` **Removed in version 332.0.0.0.66**


## Comments
- Comment filtering (last removed in 433.0.0.0.0)
  ✅ `ig_android_participation_comments_dsa` `[62405]` **Removed in version 433.0.0.0.0**

- Comment previews (last removed in 432.0.0.0.14)
  ✅ `ig_clips_comment_previews_fbid` `[68630]` **Removed in version 432.0.0.0.14**

- Mention Meta AI in Comments (last added in 418.0.0.0.5)
  ✅ `ig_meta_ai_mentions` `[110316]` **Added in version 418.0.0.0.5**

- Next Post Button in Comments (last added in 436.0.0.0.68)
  ✅ `ig_android_next_post_button` `[126382]` **Added in version 436.0.0.0.68**


## Explore
- Audio preview (last removed in 437.0.0.0.53)
  ✅ `ig_android_clips_global_audio_search` `[33546]` **Removed in version 437.0.0.0.53**

- Audio tab on the search tabs (last removed in 437.0.0.0.53)
  ✅ `ig_android_clips_global_audio_search` `[33546]` **Removed in version 437.0.0.0.53**

- For you and Add feed options in Explore (last removed in 331.0.0.0.88)
  ✅ `ig_android_friend_grid` `[55399]` **Removed in version 331.0.0.0.88**

- Increase audio preview duration (last removed in 329.0.0.0.11)
  ✅ `ig_audio_page_music_preview_duration` `[43467]` **Removed in version 329.0.0.0.11**

- Meta AI search feature in Explore (last added in 343.0.0.0.5)
  ✅ `ig_client_search_meta_ai_integration_new` `[74933]` **Added in version 343.0.0.0.5**

- Mutual filters (last removed in 333.0.0.0.33)
  ✅ `ig_stories_mutuals_filter` `[64057]` **Removed in version 333.0.0.0.33**

- Reels tab in Explore (last removed in 415.0.0.0.43)
  ✅ `ig_search_reels_subtab_autoplay` `[80216]` **Removed in version 415.0.0.0.43**

- Reels tab on the search tabs (last removed in 395.0.0.0.106)
  `ig_reels_search_tab` `[56473]` **Removed in version 395.0.0.0.106**
    - ✅ `is_reels_search_subtab_enabled_android` `[0]` **Removed in version 395.0.0.0.106**

- Share your Explore grid into a story (last removed in 369.0.0.0.95)
  ✅ `ig_explore_shareable_grid` `[61638]` **Removed in version 369.0.0.0.95**

- Remove Tags Tab from Search Results (last added in 414.0.0.0.80)
  ✅ `ig_search_client_serp_tabs_removal` `[107831]` **Added in version 414.0.0.0.80**

- Updated UI for explore tab. (last added in 435.0.0.0.37)
  `ig_relevance_explore_lab_android` `[124823]` **Added in version 435.0.0.0.37**
    - ✅ `is_enabled` `[0]` **Added in version 435.0.0.0.37**


## Stories
- Activate color picker (last removed in 446.0.0.0.12)
  ✅ `ig_stories_background_color_picker` `[80182]` **Removed in version 446.0.0.0.12**

- 60 second stories (last removed in 375.0.0.0.17)
  ✅ `ig_android_stories_video_trimmer` `[56537]` **Removed in version 375.0.0.0.17**

  ✅ `ig_stories_originality_reel_reshares` `[60559]` **Removed in version 352.0.0.0.91**

- Add yours sticker button in the camera section (last removed in 339.0.0.0.20)
  ✅ `ig_android_add_yours_browser` `[49316]` **Removed in version 339.0.0.0.20**

- Archive posted stories (last removed in 376.0.0.0.27)
  ✅ `ig_android_stories_archive_refactor` `[52652]` **Removed in version 376.0.0.0.27**

- Convert close friends to regular story (last removed in 362.0.0.0.68)
  ✅ `ig_close_friends_to_regular_story` `[67266]` **Removed in version 362.0.0.0.68**

- Custom replies (last removed in 431.0.0.0.6)
  ✅ `ig_android_interactions_story_reply_types` `[45145]` **Removed in version 431.0.0.0.6**

- Enable story snapshot (last removed in 373.0.0.0.21)
  ✅ `ig_story_snapshot` `[64935]` **Removed in version 373.0.0.0.21**

- Filled bar story reply box (last removed in 322.0.0.0.17)
  ✅ `ig_stories_modernization` `[56125]` **Removed in version 322.0.0.0.17**

- Fix the reply bar not showing in Stories (last removed in 378.0.0.0.56)
  ✅ `stories_viewer_reply_composer_mvvm` `[66521]` **Removed in version 378.0.0.0.56**

- Friend's Story (last removed in 393.0.0.0.14)
  ✅ `ig_stories_share_to_your_friends_story` `[64899]` **Removed in version 393.0.0.0.14**

- Full screen reels shared into story (last added in 317.0.0.0.3)
  ✅ `ig_stories_originality_immersive_reshare` `[67697]` **Added in version 317.0.0.0.3**

- Group mention in stories (last removed in 333.0.0.0.87)
  ✅ `igd_android_new_group_mentions_launcher` `[32606]` **Removed in version 333.0.0.0.87**

- Messenger and Reply icons in viewer list (last removed in 389.0.0.0.6)
  ✅ `ig_ios_spark_viewer_list_message_icon` `[45849]` **Removed in version 389.0.0.0.6**

- More avatar reactions (last removed in 412.0.0.0.0)
  ✅ `ig_avatars_aqrv3` `[56968]` **Removed in version 412.0.0.0.0**

- Multiple close friends lists (last removed in 386.0.0.4.84)
  ✅ `ig_private_lists` `[61267]` **Removed in version 386.0.0.4.84**

- Notify sticker (last added in 306.0.0.0.75)
  ✅ `ig_notify_me_sticker` `[65288]` **Added in version 306.0.0.0.75**

- Post directly to highlights (last removed in 410.0.0.0.7)
  ✅ `ig_profile_post_story_directly_to_highlights` `[57228]` **Removed in version 410.0.0.0.7**

- Redesign of the reply bar in stories (last removed in 355.0.0.0.37)
  ✅ `ig_android_reply_bar_modernization` `[63119]` **Removed in version 355.0.0.0.37**

- Request Mention (last removed in 373.0.0.0.18)
  ✅ `ig_stories_request_mentions` `[68439]` **Removed in version 373.0.0.0.18**

- Rounded edges on reels shared into story (last removed in 446.0.0.0.12)
  ✅ `ig_android_stories_video_sticker_migration` `[67821]` **Removed in version 446.0.0.0.12**

- Rounded edges on the mentioned story (last removed in 423.0.0.0.48)
  ✅ `ig_android_stories_mention_reshare_video_sticker` `[47335]` **Removed in version 423.0.0.0.48**

- Share profile to stories (last removed in 366.0.0.0.1)
  ✅ `ig_android_share_profile_to_stories` `[66299]` **Removed in version 366.0.0.0.1**

- Shared Lists in stories (last removed in 439.0.0.0.42)
  ✅ `ig_hallpass` `[62179]` **Removed in version 439.0.0.0.42**

- Sound button (last removed in 393.0.0.0.6)
  ✅ `ig_stories_sound_indicator` `[52803]` **Removed in version 393.0.0.0.6**

- Spotify share (last removed in 338.0.0.0.65)
  ✅ `ig_stories_spotify_audio_reshare` `[54391]` **Removed in version 338.0.0.0.65**

- Story layers (last removed in 394.0.0.0.14)
  ✅ `ig_android_stories_layer_editor` `[60845]` **Removed in version 317.0.0.0.3**

  ✅ `ig_stories_android_sticker_layering_tool` `[63512]` **Removed in version 394.0.0.0.14**

- Story user search (last removed in 393.0.0.0.6)
  ✅ `ig_story_dashboard_search_bar` `[51536]` **Removed in version 393.0.0.0.6**

- Upload collaborative stories (last removed in 365.0.0.0.1)
  ✅ `ig_stories_collab_stories` `[56857]` **Removed in version 365.0.0.0.1**

- Zoom stories (last removed in 339.0.0.0.80)
  ✅ `ig_android_stories_pinch_to_zoom` `[55260]` **Removed in version 339.0.0.0.80**

- Scrollable Toolbar (last added in 417.0.0.0.38)
  ✅ `ig_stories_post_cap_toolbar_scrollable` `[108969]` **Added in version 417.0.0.0.38**

- Stories Unified Reply Composer (last added in 417.0.0.0.38)
  ✅ `ig_android_stories_unified_reply_composer` `[109758]` **Added in version 417.0.0.0.38**

- Stories pause during zoom (last added in 420.0.0.0.10)
  ✅ `ig_android_stories_pause_during_zoom` `[112322]` **Added in version 420.0.0.0.10**

- Background of the story blurred in the corners of the screen (last removed in 434.0.0.0.64)
  `ig_stories_immersive_blur_android` `[117283]` **Removed in version 434.0.0.0.64**
    - ✅ `enable_chrome_blur` `[0]` **Removed in version 434.0.0.0.64**

- Stories Viewer List Redesign (last added in 427.0.0.0.65)
  ✅ `ig_android_stories_viewer_list_redesign` `[119728]` **Added in version 427.0.0.0.65**

- Search Story Viewers (last added in 414.0.0.0.80)
  ✅ `ig_android_aura_story_viewer` `[107820]` **Added in version 414.0.0.0.80**

- Stop Auto-Advance on Expiring Stories (last added in 414.0.0.0.7)
  ✅ `ig_android_stories_auto_advance` `[107227]` **Added in version 414.0.0.0.7**

- Self-Remove From Someone’s Close Friends List (last added in 415.0.0.0.43)
  ✅ `ig_stories_close_friends_self_remove` `[105130]` **Added in version 415.0.0.0.43**

- Super Like on Posts (last added in 415.0.0.0.43)
  ✅ `ig_android_aura_superlike` `[107371]` **Added in version 415.0.0.0.43**

- Story Peek Preview in Feed (last added in 416.0.0.0.43)
  ✅ `ig_android_aura_story_peeks` `[107913]` **Added in version 416.0.0.0.43**

- Redesigned Mentioned Story Reshare UI (last added in 391.0.0.0.70)
  ✅ `ig_stories_mention_reshare_redesign` `[93948]` **Added in version 391.0.0.0.70**

- Custom Emoji Reactions in Stories (last removed in 447.0.0.0.25)
  ✅ `ig_stories_emoji_quick_reactions_refresh` `[110285]` **Removed in version 447.0.0.0.25**

- Create Custom Audience Lists (last added in 411.0.0.0.139)
  ✅ `ig_aura_unlimited_audience_lists` `[106589]` **Added in version 411.0.0.0.139**

- Top Five Besties Sharing Option (last removed in 423.0.0.0.20)
  ✅ `ig_stories_top_five_besties` `[98728]` **Removed in version 423.0.0.0.20**

- Instaflow Flags (last added in 409.0.0.0.57)
  ✅ `ig_android_stories_archive_craft` `[104900]` **Added in version 409.0.0.0.57**

  `ig_stories_archive_bulk_delete` `[103057]` **Added in version 408.0.0.0.1**
    - ✅ `is_m2_enabled` `[2]` **Added in version 408.0.0.0.1**

- Stories Archive Craft (last added in 408.0.0.0.1)
  ✅ `ig_stories_archive_bulk_delete` `[103057]` **Added in version 408.0.0.0.1**

- AI Photo Transitions (last added in 411.0.0.0.57)
  ✅ `ig_stories_ai_transitions` `[105390]` **Added in version 411.0.0.0.57**

- Stories Draft Count (last added in 411.0.0.0.57)
  ✅ `ig_android_stories_draft_count` `[106190]` **Added in version 411.0.0.0.57**

- stories lipsync (last added in 410.0.0.0.7)
  ✅ `ig_android_stories_lipsync` `[104898]` **Added in version 410.0.0.0.7**

- stories android video trimmer v2 (last added in 415.0.0.0.43)
  ✅ `ig_stories_android_video_trimmer_v2` `[107653]` **Added in version 415.0.0.0.43**

- Stories Photostrip Sticker v1 (last added in 428.0.0.0.54)
  ✅ `ig_stories_photostrip_sticker_v1` `[119945]` **Added in version 428.0.0.0.54**

- Story Interest Signals (last added in 418.0.0.0.11)
  ✅ `ig_story_interest_signals` `[110034]` **Added in version 418.0.0.0.11**

- Blurred Background for Story Reshares (last added in 418.0.0.0.5)
  ✅ `ig_stories_reshares_blur_background` `[110215]` **Added in version 418.0.0.0.5**

- Story Creation Entrypoints (last added in 425.0.0.0.53)
  `ig_story_creation_entrypoints` `[117563]` **Added in version 425.0.0.0.53**
    - ✅ `is_avatar_entry_enabled` `[0]` **Added in version 425.0.0.0.53**
    - ✅ `is_plus_entry_enabled` `[1]` **Added in version 425.0.0.0.53**

- Remove Stories Add Yours Midcard (last removed in 438.0.0.0.78)
  `ig_stories_android_qccm` `[113040]` **Added in version 421.0.0.0.21**
    - ❌ `add_yours_enabled` `[1]` **Removed in version 438.0.0.0.78**
    - ❌ `enable_add_yours_templates` `[18]` **Removed in version 438.0.0.0.78**

- Fix weird icon placement (last added in 437.0.0.0.65)
  ❌ `ig_android_story_pog_tap_area_expansion_v2` `[126926]` **Added in version 437.0.0.0.65**


## Camera
- Audio and Trending options in reel media selection (last removed in 355.0.0.0.72)
  ✅ `ig_camera_android_reels_gallery_audio` `[61406]` **Removed in version 355.0.0.0.72**

- Better organisation of the sidebar (last removed in 422.0.0.0.55)
  ✅ `igrp_android_ar_sidebar` `[55254]` **Removed in version 422.0.0.0.55**

- Better use of the gesture controls (last removed in 387.0.0.0.61)
  ✅ `ig_android_gesture_control_improved_experience_launcher` `[57679]` **Removed in version 387.0.0.0.61**

- Boomerang on reel creation (last removed in 332.0.0.0.52)
  ✅ `ig_android_camera_reels_boomerang_launcher` `[59166]` **Removed in version 332.0.0.0.52**

- Duplicate reel drafts (last removed in 374.0.0.0.16)
  ✅ `ig_android_clips_duplicate_drafts` `[62705]` **Removed in version 374.0.0.0.16**

- New fonts (last removed in 407.0.0.0.173)
  ✅ `ig_camera_android_reels_text_expansion` `[63079]` **Removed in version 407.0.0.0.173**

- New options in media selection (last removed in 384.0.0.0.74)
  ✅ `ig_android_stories_destination_toolbar` `[62058]` **Removed in version 384.0.0.0.74**

- Photos and Videos categories in media selection (last removed in 362.0.0.0.48)
  `ig_android_feed_gallery_revamp_launcher` `[70798]` **Removed in version 362.0.0.0.48**
    - ❌ `camera_disabled` `[2]` **Removed in version 362.0.0.0.48**

- Preview of the media while holding in Reels picker (last removed in 326.0.0.0.80)
  ✅ `ig_android_reels_long_press_gallery` `[60395]` **Removed in version 326.0.0.0.80**

- Suggested albums (last removed in 378.0.0.0.18)
  ✅ `ig_android_gallery_smart_albums` `[66467]` **Removed in version 378.0.0.0.18**

- Useful options as circles on reel recording (last removed in 374.0.0.0.16)
  ✅ `ig_android_camera_platform_utility_toolbar` `[56166]` **Removed in version 374.0.0.0.16**

- Zoom and unzoom the photos row in media selection (last removed in 345.0.0.0.39)
  ✅ `ig_camera_android_reels_gallery_zoom` `[62229]` **Removed in version 345.0.0.0.39**

- Send reel drafts to other people (last removed in 362.0.0.0.89)
  `ig_android_share_reel_to_direct_igfbidv2` `[71694]` **Removed in version 362.0.0.0.89**
    - ✅ `is_draft_share_enabled` `[0]` **Removed in version 362.0.0.0.89**


## Direct
- Nicknames (last added in 335.0.0.0.78)
  ✅ `igd_nicknames` `[73256]` **Added in version 335.0.0.0.78**

- AI Message replies (last removed in 362.0.0.0.93)
  ✅ `ig_creator_agents_suggested_replies` `[64118]` **Removed in version 362.0.0.0.93**

- Avatar Animation (last removed in 434.0.0.0.0)
  ✅ `ig_stories_avatar_reactions` `[101199]` **Removed in version 434.0.0.0.0**

- Avatar powerups (last removed in 448.0.0.0.7)
  ✅ `igd_avatar_powerups` `[61586]` **Removed in version 448.0.0.0.7**

- Avatar reactions (last removed in 403.0.0.0.19)
  ✅ `ig4a_avatar_reactions` `[66684]` **Removed in version 403.0.0.0.19**

- Birthday (last removed in 411.0.0.0.13)
  ✅ `ig4a_birthday_opt_in` `[60232]` **Removed in version 411.0.0.0.13**

- Collab collections (last removed in 376.0.0.0.8)
  ✅ `ig_android_nsx_collab_collections` `[63479]` **Removed in version 376.0.0.0.8**

- Create a group chat through DMs (last added in 325.0.0.0.72)
  ✅ `ig_direct_android_create_group_from_thread_details` `[70472]` **Added in version 325.0.0.0.72**

- Delete messages for you (last removed in 317.0.0.0.3)
  ✅ `igd_android_delete_messages` `[65707]` **Removed in version 317.0.0.0.3**

- Disable typing indicator (last added in 324.0.0.0.45)
  ✅ `igd_typing_indicator_control` `[69810]` **Added in version 324.0.0.0.45**

- Edit messages (last removed in 386.0.0.4.84)
  ✅ `igd_android_edit_message` `[64903]` **Removed in version 386.0.0.4.84**

- Enable gyroscopic themes (last removed in 317.0.0.0.98)
  ✅ `igd_android_gyroscopic_themes` `[38187]` **Removed in version 317.0.0.0.98**

- Favourite stickers (last added in 306.0.0.0.87)
  ✅ `igd_android_favorite_sticker` `[65322]` **Added in version 306.0.0.0.87**

- GIF and sticker forwarding (last removed in 411.0.0.0.65)
  ✅ `igd_armadillo_gifs_stickers_forwarding` `[60250]` **Removed in version 411.0.0.0.65**

- GIF categories (last removed in 419.0.0.0.9)
  ✅ `igd_gif_categories` `[61514]` **Removed in version 419.0.0.0.9**

- Group invites (last removed in 431.0.0.0.21)
  ✅ `igd_android_groups_invites_launcher` `[43449]` **Removed in version 431.0.0.0.21**

- In chat search (last removed in 403.0.0.0.66)
  ✅ `ig_android_in_thread_content_search` `[42110]` **Removed in version 403.0.0.0.66**

- Leave silently from group chats (last added in 322.0.0.0.67)
  ✅ `igd_leave_silently` `[69505]` **Added in version 322.0.0.0.67**

- Location Sharing (last removed in 402.0.0.0.11)
  `ig_android_location_share_xma` `[50122]` **Removed in version 402.0.0.0.11**
    - ✅ `location_share_xma_enabled` `[0]` **Removed in version 402.0.0.0.11**

- Long press to change chat theme (last removed in 390.0.0.0.6)
  ✅ `igd_android_long_press_to_theme_picker` `[52822]` **Removed in version 390.0.0.0.6**

- Media previews before sending (last added in 319.0.0.0.33)
  ✅ `igd_android_media_preview_fbid` `[68556]` **Added in version 319.0.0.0.33**

- More options on the Privacy and Safety section in group chats (last removed in 401.0.0.0.26)
  ✅ `ig_direct_android_group_privacy_and_safety_settings` `[70787]` **Removed in version 401.0.0.0.26**

- Mute chat within XX hours (last removed in 409.0.0.0.0)
  `ig_direct_android_thread_time_muting` `[50215]` **Removed in version 409.0.0.0.0**
    - ❌ `has_debug_time_option` `[1]` **Removed in version 409.0.0.0.0**

- New layout of chat details (last removed in 379.0.0.0.1)
  `ig_android_direct_thread_details_redesign` `[44864]`
    - ❌ `show_privacy_buttons_on_main_page` `[7]` **Removed in version 379.0.0.0.1**

- New layout of long press menu (last removed in 440.0.0.0.25)
  ✅ `igd_long_press_message_action_android` `[51328]` **Removed in version 440.0.0.0.25**

- New modern design of the "send" button in a chat/note reply/comment composer (last removed in 389.0.0.0.64)
  ✅ `ig_android_smashable_send_stories_alignment` `[81107]` **Removed in version 389.0.0.0.64**

- Pin chats (last removed in 399.0.0.0.16)
  `igd_android_pin_threads_fbid` `[67423]` **Removed in version 399.0.0.0.16**
    - ✅ `is_enabled` `[0]` **Removed in version 399.0.0.0.16**

- Quiet mode (last removed in 411.0.0.0.234)
  ✅ `ig_quiet_mode` `[49432]`

  ✅ `ig_quiet_mode_x_plat` `[65571]` **Removed in version 411.0.0.0.234**

- Redesign of the new group chat screen (last removed in 437.0.0.0.53)
  ✅ `ig_android_direct_group_creation_improvements_launcher` `[58570]` **Removed in version 437.0.0.0.53**

- Rename the Delete button to Unsend and get a new icon (last removed in 401.0.0.0.70)
  ✅ `igd_delete_messages` `[63463]` **Removed in version 401.0.0.0.70**

- Replace the Following button to Message on the fmembers list of a group chat (last added in 309.0.0.0.36)
  ✅ `ig_android_direct_thread_details_message_entrypoints` `[65907]` **Added in version 309.0.0.0.36**

- Reply to links (last removed in 406.0.0.0.154)
  ✅ `ig_android_direct_link_replies` `[44096]` **Removed in version 406.0.0.0.154**

- Roll call (last removed in 408.0.0.0.45)
  ✅ `ig_android_roll_call` `[52350]` **Removed in version 408.0.0.0.45**

- Seen states (last removed in 348.0.0.0.18)
  ✅ `ig_android_direct_seen_states_in_inbox` `[26842]` **Removed in version 348.0.0.0.18**

- Set star tab to avatars (last removed in 363.0.0.0.25)
  ✅ `ig_android_avatars_quick_reactions_direct_receive` `[44861]` **Removed in version 363.0.0.0.25**

- Show avatars in star tab (last removed in 421.0.0.0.21)
  ✅ `igd_avatar_growth` `[66577]` **Removed in version 421.0.0.0.21**

- Silent share (last removed in 317.0.0.0.3)
  ✅ `ig_android_send_control` `[51758]` **Removed in version 317.0.0.0.3**

- Smaller size of avatars in Direct (last removed in 411.0.0.0.7)
  ✅ `igd_avatar_tray_improvements` `[62060]` **Removed in version 411.0.0.0.7**

- Smaller size of stickers in Direct (last removed in 420.0.0.0.43)
  ✅ `igd_sticker_tray_improvements` `[62390]` **Removed in version 420.0.0.0.43**

- Swipe to open chat details (last removed in 317.0.0.0.78)
  ✅ `ig_direct_android_swipe_to_thread_details` `[51324]` **Removed in version 317.0.0.0.78**

- Tap to react (last removed in 364.0.0.0.24)
  ✅ `ig_android_direct_reactions_gating_launcher` `[27766]` **Removed in version 364.0.0.0.24**

- Theme picker redesign (last added in 323.0.0.0.53)
  ✅ `igd_new_themes` `[69519]` **Added in version 323.0.0.0.53**

- Shows upload progress for Direct Messages (last added in 424.0.0.0.63)
  ✅ `cancellable_and_retryable_media_uploads` `[79502]` **Added in version 424.0.0.0.63**

- Profile Music Reply (last added in 419.0.0.0.60)
  ✅ `ig_android_profile_music_reply` `[111839]` **Added in version 419.0.0.0.60**

- Aura Message Peek (last added in 425.0.0.0.56)
  ✅ `ig_android_aura_message_peek_2` `[117726]` **Added in version 425.0.0.0.56**

- New Typing Indicator (Dot Style) in DM (last added in 423.0.0.0.20)
  ✅ `igd_android_inbox_typing_indicator` `[115516]` **Added in version 423.0.0.0.20**

- Valentine’s Theme Pack for Notes (last added in 415.0.0.0.43)
  ✅ `ig_notes_valentines_theme_pack_2026` `[107450]` **Added in version 415.0.0.0.43**

- Send Event Reminder from IG Direct (last added in 414.0.0.0.7)
  ✅ `igd_android_events` `[107324]` **Added in version 414.0.0.0.7**

- Notes Audience Expansion (last added in 415.0.0.0.43)
  ✅ `ig_notes_audience_expansion` `[58832]` **Added in version 415.0.0.0.43**

- Tema de ano novo nas notas (last removed in 429.0.0.0.62)
  ✅ `ig_android_notes_theme_packs` `[100233]` **Removed in version 429.0.0.0.62**

- igd threaded replies (last removed in 429.0.0.0.0)
  `igd_threaded_replies` `[94846]` **Removed in version 429.0.0.0.0**
    - ✅ `is_enabled` `[3]` **Removed in version 429.0.0.0.0**
    - ✅ `enable_composer_media_options` `[5]` **Removed in version 429.0.0.0.0**
    - ✅ `process_cache_inbox` `[0]` **Removed in version 429.0.0.0.0**
    - ✅ `process_cache_startup` `[2]` **Removed in version 429.0.0.0.0**
    - ✅ `process_cache_thread` `[1]` **Removed in version 429.0.0.0.0**
    - ✅ `use_bottom_sheet` `[4]` **Removed in version 429.0.0.0.0**

- Show temporary photo/video spoiler (last added in 399.0.0.0.24)
  ✅ `igd_android_ephemeral_media_preview` `[98405]` **Added in version 399.0.0.0.24**

- Play games in Direct (last added in 405.0.0.0.33)
  ✅ `ig_android_direct_games` `[102340]` **Added in version 405.0.0.0.33**

- igd android calling buttons config (last added in 415.0.0.0.43)
  ✅ `igd_android_action_bar_rewrite` `[76114]` **Added in version 345.0.0.0.92**

  `igd_android_calling_buttons_config` = 1 `[91189]` **Added in version 415.0.0.0.43**

- Autoplay preview of shared reels (last removed in 332.0.0.0.24)
  `ig_android_clips_direct_reshare_autoplay` `[50074]`
    - ✅ `full_autoplay_enabled` `[0]` **Removed in version 332.0.0.0.24**

- Disable swipe to direct (last removed in 340.0.0.0.75)
  `ig_disable_swipe_to_direct` `[47343]` **Removed in version 340.0.0.0.75**
    - ✅ `should_disable_swipe_to_direct` `[0]` **Removed in version 340.0.0.0.75**

- Fix GIFs and stickers not showing on the powerups section (last removed in 358.0.0.0.69)
  `igd_media_feature_unship_android` `[66319]` **Removed in version 358.0.0.0.69**
    - ✅ `gifs_stickers_shortcut_disabled` `[0]` **Removed in version 358.0.0.0.69**

- Select button in the gallery in Direct (last added in 319.0.0.0.33)
  `igd_android_media_preview_fbid` `[68556]` **Added in version 319.0.0.0.33**
    - ✅ `gallery_select_button_enabled` `[4]` **Added in version 319.0.0.0.33**

- Custom Fonts in Chats & Stories (last removed in 435.0.0.0.37)
  ✅ `ig_android_consumer_subs_custom_fonts` `[118893]` **Removed in version 435.0.0.0.37**

- Remove accounts to follow from DMs (last added in 343.0.0.0.9)
  `igd_inbox_fetch_optimizations` = 9000000000 `[75196]` **Added in version 343.0.0.0.9**

- Cancellable & Retryable Media Uploads (last added in 424.0.0.0.63)
  ✅ `cancellable_and_retryable_media_uploads` `[79502]` **Added in version 424.0.0.0.63**

- 😀📤 Emoji Bar Above Share Composer (last added in 422.0.0.0.13)
  `igd_android_sharesheet_emoji_composer` `[111639]` **Added in version 419.0.0.0.60**
    - ✅ `show_emoji_above_composer` `[1]` **Added in version 422.0.0.0.13**

- Remove cutout button from direct chats (last added in 399.0.0.0.16)
  `igd_android_riff` `[96230]` **Added in version 396.0.0.0.237**
    - ❌ `is_cutout_action_enabled` `[2]` **Added in version 399.0.0.0.16**

- Account Notification Badging Control (last added in 354.0.0.0.2)
  `xav_ig_android_switcher_badging_fdid` `[78977]` **Added in version 354.0.0.0.2**
    - ✅ `hide_tab_bar_badging` `[1]` **Added in version 354.0.0.0.2**
    - ✅ `hide_all_badging` `[0]` **Added in version 354.0.0.0.2**


## Profile
- Compare activity (last removed in 362.0.0.0.105)
  ✅ `ig_shared_activity_android` `[59115]` **Removed in version 362.0.0.0.105**

- Highlights grid (last removed in 317.0.0.0.98)
  ✅ `ig_profile_highlights_click_into_grid` `[55286]` **Removed in version 317.0.0.0.98**

- Highlights tray as cards (last removed in 412.0.0.0.33)
  ✅ `ig_android_highlights_tray_as_cards` `[63316]` **Removed in version 318.0.0.0.102**

  `ig_japan_labs_my_week` `[66089]` **Removed in version 412.0.0.0.33**
    - ✅ `is_cards_layout_enabled` `[4]` **Removed in version 412.0.0.0.33**

- Just seen (last removed in 397.0.0.0.24)
  ✅ `ig4a_profile_just_watched` `[66523]` **Removed in version 397.0.0.0.24**

- Mutuals button in the header (last removed in 362.0.0.0.26)
  ✅ `ig_android_profile_stat_row_improvements` `[70751]` **Removed in version 362.0.0.0.26**

- New header design (last removed in 310.0.0.0.192)
  ✅ `ig_android_profile_header_daisy` `[45440]` **Removed in version 310.0.0.0.192**

- New private account screen (last removed in 356.0.0.0.72)
  ✅ `ig_android_profile_public_highlights` `[69788]` **Removed in version 356.0.0.0.72**

- Pin your broadcast chat/social channel to your profile (last removed in 369.0.0.0.11)
  ✅ `ig_android_direct_pin_chat_to_profile` `[52321]` **Removed in version 369.0.0.0.11**

- Profile Interests (last removed in 370.0.0.0.86)
  ✅ `ig_bio_interests` `[50766]` **Removed in version 370.0.0.0.86**

- Reels pinning (last removed in 400.0.0.0.17)
  ✅ `ig_android_clips_reels_pinning_on_profile` `[53089]` **Removed in version 400.0.0.0.17**

- Wall notes (last removed in 336.0.0.0.74)
  ✅ `ig_android_profile_wall_notes` `[65647]` **Removed in version 336.0.0.0.74**

- Zoom people's profile icons (last removed in 363.0.0.0.42)
  ✅ `ig_android_profile_pfp_zoom` `[67281]` **Removed in version 363.0.0.0.42**

- PFP Reaction (last added in 422.0.0.0.48)
  ✅ `ig_android_pfp_reaction` `[114906]` **Added in version 422.0.0.0.48**

- Expressive Profile Header (Pill UI) (last added in 417.0.0.0.38)
  ✅ `ig4a_profile_expressive_header` `[109802]` **Added in version 417.0.0.0.38**

- Profile Flags (last added in 403.0.0.0.66)
  ✅ `ig_profile_preview` `[96269]` **Added in version 403.0.0.0.66**

- Show IGTV section (last removed in 357.0.0.0.68)
  `ig_panavision_v0` `[37418]` **Removed in version 357.0.0.0.68**
    - ✅ `consumption_merge_profile_video_tabs` `[53]` **Removed in version 332.0.0.0.24**

- Restore Share Profile Button (last added in 425.0.0.0.17)
  `ig4a_profile_header_discover_people_button_swap` `[117777]` **Added in version 425.0.0.0.17**
    - ❌ `is_enabled` `[0]` **Added in version 425.0.0.0.17**
    - ❌ `use_share_icon` `[1]` **Added in version 425.0.0.0.17**


## Livestreams
- Add texts and draw in livestreams (last removed in 390.0.0.0.26)
  ✅ `ig_live_stickers` `[71753]` **Removed in version 390.0.0.0.26**

- Games in livestreams (last removed in 331.0.0.0.88)
  ✅ `ig_live_android_games` `[60136]` **Removed in version 331.0.0.0.88**

- More audience options on live creation (last removed in 390.0.0.0.12)
  ✅ `ig_live_android_invite_only` `[56829]` **Removed in version 390.0.0.0.12**

- Share media with your audience in livestreams (last removed in 330.0.0.0.67)
  ✅ `ig_android_live_media_picker` `[37206]` **Removed in version 330.0.0.0.67**


## Professional
- Welcome message (last removed in 411.0.0.0.73)
  ✅ `ig_android_welcome_message` `[41207]` **Removed in version 411.0.0.0.73**


## Fixes
- Fix the voice message and gallery button missing in some chats in some bases (last removed in 423.0.0.0.60)
  ❌ `igd_server_powered_thread_capabilities` `[51321]` **Removed in version 423.0.0.0.60**

- Fix Avatar options not showing in Direct (last removed in 392.0.0.0.10)
  ❌ `ig_avatars_longterm_holdout_2023` `[61129]` **Removed in version 392.0.0.0.10**

- Fix crashes when opening Your Story (last removed in 362.0.0.0.105)
  ✅ `ig_stories_quick_captions_v2` `[61966]` **Removed in version 362.0.0.0.105**

- Fix not being able to take photos with effects for your story (last added in 326.0.0.0.80)
  ✅ `ig_andriod_ar_engine` `[69563]` **Added in version 326.0.0.0.80**

- Fix recommended users always showing up when adding a text in the Stories editor (last removed in 341.0.0.0.6)
  ✅ `ig_android_stories_group_mention` `[48810]` **Removed in version 341.0.0.0.6**

- Fix the avatar reactions not showing on the reaction sheet in Stories (last removed in 392.0.0.0.10)
  ✅ `ig_avatars_longterm_holdout_2023` `[61129]` **Removed in version 392.0.0.0.10**

- Fix the carousel post editor crashing (last removed in 440.0.0.0.25)
  ✅ `ig_android_reels_creation_dark_mode` `[68432]` **Removed in version 440.0.0.0.25**

- Fix the chats crashing in Direct (last added in 367.0.0.0.70)
  ✅ `ig_android_direct_xma_mi_migration` `[38405]`

  ✅ `igd_android_voice_msg_transcription_server_based` `[82773]` **Added in version 367.0.0.0.70**

- Fix the chats not loading after switching accounts (last removed in 336.0.0.0.66)
  ✅ `ig4a_direct_inbox_streaming` `[61874]` **Removed in version 336.0.0.0.66**

- Fix the post gallery crashing (last removed in 407.0.0.0.173)
  `ig_camera_android_reels_text_expansion` `[63079]` **Removed in version 407.0.0.0.173**
    - ✅ `enable_new_fonts_stories` `[4]` **Removed in version 407.0.0.0.173**

- Fix the Reels lagging (last removed in 402.0.0.0.0)
  ✅ `ig_android_clips_playback_tests` `[37030]` **Removed in version 402.0.0.0.0**

- Fix the status bar being white while watching reels (last removed in 362.0.0.0.93)
  ✅ `ig_android_status_nav_bar_api_update_launcher` `[53998]` **Removed in version 362.0.0.0.93**

- Fix the stories crashing (last removed in 347.0.0.0.85)
  ✅ `ig_android_stories_ads_toolbar` `[68262]` **Removed in version 347.0.0.0.85**

- Fix the story editor crashing when taking a photo (last removed in 348.0.0.0.35)
  ✅ `ig_android_sticker_anything_dark_test_launcher` `[63196]` **Removed in version 348.0.0.0.35**

- Fix the text you add in the Reels editor being placed 0.5s ahead of where you put it (last removed in 334.0.0.0.33)
  ✅ `ig_camera_android_reels_stacked_timeline_add_things` `[55557]` **Removed in version 334.0.0.0.33**

- Profile truncation fix (last added in 420.0.0.0.10)
  ✅ `ig_profile_fix_h1_2026` `[112318]` **Added in version 420.0.0.0.10**

- Fix visual bug when opening notification (last added in 356.0.0.0.72)
  ❌ `ignx_nf_craft_fixes` `[79765]` **Added in version 356.0.0.0.72**

- Fix broadcast channels crashing when pressing any of their media (last removed in 431.0.0.0.55)
  `ig_broadcast_channel_fbidv2` `[59942]` **Removed in version 431.0.0.0.55**
    - ❌ `is_silent_toggle_enabled` `[89]` **Removed in version 431.0.0.0.55**

- Fix the like button not showing in Stories (last removed in 405.0.0.0.33)
  `ig_android_stories_viewer_like_mvvm` `[71861]` **Removed in version 405.0.0.0.33**
    - ✅ `is_enabled` `[0]` **Removed in version 405.0.0.0.33**

- Fix the profiles you visit not loading properly (last removed in 349.0.0.0.27)
  `ig_android_profile_scroll_perf` `[65295]` **Removed in version 349.0.0.0.27**
    - ❌ `should_update` `[0]` **Removed in version 349.0.0.0.27**

- Remove the Suggested header while watching Reels (last added in 327.0.0.0.70)
  `ig_android_reels_stacks` `[71131]` **Added in version 327.0.0.0.70**
    - ❌ `is_reply_bar_and_header_enabled` `[1]` **Added in version 327.0.0.0.70**

- Remove the weird button showing on Instagram while a page is loading (last added in 311.0.0.0.0)
  `igds_prism_launcher_config_android` `[62246]`
    - ❌ `enable_prism_headline` `[16]` **Added in version 311.0.0.0.0**

- Fix all the hints showing even if they are already seen (last removed in 409.0.0.0.146)
  `ig_sharing_foundations_optimizations_h1_2024` `[68472]` **Removed in version 409.0.0.0.146**
    - ✅ `reuse_sharedprefs_editor` `[7]` **Removed in version 409.0.0.0.146**

- Fix like and comment counts not showing in Reels (last removed in 393.0.0.0.57)
  `ig_reels_interactivity_flywheel_test` `[52814]` **Removed in version 393.0.0.0.57**
    - ✅ `android_viewer_disable_comment_count` `[16]` **Removed in version 347.0.0.0.94**

- Fix music not playing in notes (last removed in 336.0.0.11.90)
  `ig_android_notes_mvvm_migrations` `[67933]` **Removed in version 336.0.0.11.90**
    - ✅ `quick_reply_sheet_mvvm_migration_enabled` `[1]` **Removed in version 336.0.0.11.90**

- Fix not being able to navigate in the Camera (last removed in 421.0.0.0.3)
  `ig_android_reels_add_clips_multiselect_enabled` `[65055]` **Removed in version 421.0.0.0.3**
    - ✅ `fix_folder_selector_inflate_crash` `[5]` **Removed in version 421.0.0.0.3**

- Fix not being able to swipe to the feed while being on the chats list in Direct (last removed in 420.0.0.0.10)
  `ig_android_reels_consumption_v1` `[57849]`
    - ✅ `source_logging_disabled` `[9]` **Removed in version 420.0.0.0.10**

- Fix not being able to take photos for stories (last removed in 342.0.0.0.23)
  `ig_camera_android_capture_request_experiments` `[67384]` **Removed in version 342.0.0.0.23**
    - ✅ `enable_sensor_pixel_mode_maximum_resolution` `[1]` **Removed in version 342.0.0.0.23**

- Fix shared reels always being big (last removed in 367.0.0.0.78)
  `ig_rocket_replies` `[65206]` **Removed in version 367.0.0.0.78**
    - ✅ `use_large_xma` `[2]` **Removed in version 367.0.0.0.78**

- Fix some green boxes showing while watching reels (last removed in 419.0.0.0.60)
  `ig_android_reels_swipe_to_action` `[54948]`
    - ✅ `enable_swipe_debug_visualizer` `[66]` **Removed in version 419.0.0.0.60**

- Fix the "The reel is unavailable." errors (last removed in 369.0.0.0.3)
  `ig_android_clips_friendly_viewer` `[67072]` **Removed in version 369.0.0.0.3**
    - ✅ `is_floaty_follows_enabled` `[2]` **Removed in version 369.0.0.0.3**

- Fix the audio page crashing (last removed in 360.0.0.0.11)
  `ig_android_audio_page_layout` `[68956]` **Removed in version 360.0.0.0.11**
    - ✅ `ap_layout_enabled` `[0]` **Removed in version 360.0.0.0.11**

- Fix the confetti animation showing in every note (last added in 421.0.0.0.3)
  `ig_notes_birthday_v2` `[69682]` **Added in version 421.0.0.0.3**
    - ✅ `activation_enabled` `[1]` **Added in version 421.0.0.0.3**

- Fix the Direct tab crashing (last removed in 368.0.0.0.86)
  `ig_android_notes_super_endpoint` `[68611]` **Removed in version 368.0.0.0.86**
    - ✅ `is_get_notes_enabled` `[1]` **Removed in version 368.0.0.0.86**

- Fix the huge gap in Direct when the Direct tab is on the bottom bar (last removed in 434.0.0.0.0)
  `ig_android_feed_scroll_away_nav` `[54983]` **Removed in version 434.0.0.0.0**
    - ✅ `is_extended_scrollaway_nav_enabled_for_feed` `[4]` **Removed in version 434.0.0.0.0**

- Fix the loud audio distortion and the image glitches when recording a video for stories / not being able to record videos for stories (for older bases) (last removed in 419.0.0.0.60)
  `android_cameracore_fbaudio_ig_launcher` `[31064]`
    - ✅ `use_pcm_float` `[23]` **Removed in version 419.0.0.0.60**

- Fix the Mute options not showing (last added in 329.0.0.0.82)
  `igds_prism_launcher_config_android` `[62246]`
    - ✅ `enable_prism_alert_dialog` `[28]` **Added in version 329.0.0.0.82**

- Fix the muted audio in stories (last removed in 420.0.0.0.43)
  `qe_ig_android_reel_raven_video_segmented_upload_universe` `[34393]` **Removed in version 420.0.0.0.43**
    - ✅ `segment_enabled_story_raven` `[7]` **Removed in version 420.0.0.0.43**

- Fix the notification tab crashing (last removed in 362.0.0.0.93)
  `ig_android_ptr_spinner_update_launcher` `[46297]` **Removed in version 362.0.0.0.93**
    - ❌ `is_enabled_in_newsfeed_you` `[4]` **Removed in version 362.0.0.0.93**

- Fix the post editing section always being in HDR (last removed in 372.0.0.0.35)
  `ig_camera_android_ultra_hdr_photo_capture` `[64894]`
    - ❌ `enable_jpegr_feed_photo_edit_surface_view` `[4]` **Removed in version 372.0.0.0.35**

- Fix the story editor always being in HDR (last removed in 372.0.0.0.35)
  `ig_camera_android_ultra_hdr_photo_capture` `[64894]`
    - ❌ `enable_jpegr_feed_photo_edit_surface_view` `[4]` **Removed in version 372.0.0.0.35**

- Founder attribution test (last removed in 393.0.0.0.22)
  ✅ `ig_threads_xma` `[61804]` **Removed in version 393.0.0.0.22**
