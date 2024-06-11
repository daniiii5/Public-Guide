# John's and Dani's Ultimate Guide
## Attention! This is still a work in progress
The guide is still being updated to bring the best experience to the user. A lot of changes might occur during the development of the guide.

## FAQ

- I can't access the Developer Settings!
  - Make sure you have gone in Metaconfig Settings and Overrides, that's where all the flags are in.
- I don't see the Developer Settings when holding the home icon.
  - This only works for Instagram Mods that have the Developer Options enabled. It's not available on the stock Instagram as it's normally only for developers.
- A flag is not working.
  - Check your base version. If it's on the working bases, then it might be region locked, available on limited people, server sided or stopped working completely, where if the last case happens, the flag will be moved to the Archive category.
- Instagram is crashing!
  - You have enabled a faulty flag (flag that is causing issues to features or in the app). If it happens with a flag on the guide regarding new features, kindly inform us. Otherwise, we're not responsible for that. Clear the app data and start adding the flags all over again.
- I need support!
  - Send a message in the patreon chat to get assistance.
- Why don't the flags that have been added before the 310 base mention the specific one?
  - We are using a bot about flag information, and that bot is configured for the bases between 310 and beyond, and as we can't just start searching the previous bases for the flags (it will take us forever), we're just adding that sentence.

# How to enable/disable flags
(photos/animations pending)

- [Yet Another Instagram Developer Guide by Dani](#yet-another-instagram-developer-guide-by-dani)
  - [Made by Dani, with main collaborator(s): John Xirouchakis](#made-by-dani-with-main-collaborators-john-xirouchakis)
  - [Last update: 25/5/24](#last-update-25524)
  - [Attention! This is still a work in progress](#attention-this-is-still-a-work-in-progress)
  - [FAQ](#faq)
- [How to enable/disable flags](#how-to-enabledisable-flags)
- [Important](#important)
  - [🆕 Prevent Instagram from taking lots of space in app data](#prevent-instagram-from-taking-lots-of-space-in-app-data)
  - [Make the app more efficient](#make-the-app-more-efficient)
  - [Remove the Google Play update dialog](#remove-the-google-play-update-dialog)
  - [Disable Thread posts in the feed](#disable-thread-posts-in-the-feed)
  - [Messenger update](#messenger-update)
  - [Remove Threads usernames and button](#remove-threads-usernames-and-button)
  - [🆕Remove the reel ads and improve/fix adblocking in Instagram mods](#remove-the-reel-ads-and-improvefix-adblocking-in-instagram-mods)
  - [🆕Remove the story ads with the "LEARN MORE" stickers inside](#remove-the-story-ads-with-the-learn-more-stickers-inside)
  - [🆕Enable the shake phone to report a problem sheet even if you disabled it](#enable-the-shake-phone-to-report-a-problem-sheet-even-if-you-disabled-it)
- [Quality](#quality)
  - [Upload photos up to 1440p resolution in stories](#upload-photos-up-to-1440p-resolution-in-stories)
  - [Reduce compression of photo uploads in the feed](#reduce-compression-of-photo-uploads-in-the-feed)
  - [High quality video uploads on stories and reels](#high-quality-video-uploads-on-stories-and-reels)
  - [Audio](#audio)
  - [Enable 48khz sample rate](#enable-48khz-sample-rate)
  - [Enable stereo](#enable-stereo)
- [UI](#ui)
  - [New loading screen](#new-loading-screen)
  - [Customize buttons layout](#customize-buttons-layout)
  - [Change activity icon to bell icon](#change-activity-icon-to-bell-icon)
  - [New spinner in the feed and profile](#new-spinner-in-the-feed-and-profile)
  - [Filled bottom row buttons](#filled-bottom-row-buttons)
  - [New dark mode](#new-dark-mode)
  - [Fix empty space below bottom navigation bar](#fix-empty-space-below-bottom-navigation-bar)
  - [Enable sheet multi tab](#enable-sheet-multi-tab)
  - [🆕Redesigned comment section](#redesigned-comment-section)
  - [Open links in external browser](#open-links-in-external-browser)
  - [New stories stickers menu design](#new-stories-stickers-menu-design)
  - [Redesign of the media picker in Direct](#redesign-of-the-media-picker-in-direct)
  - [🆕Dark gallery in Direct at all times](#dark-gallery-in-direct-at-all-times)
  - [User avatar size in stories tray](#user-avatar-size-in-stories-tray)
  - [Media previews in stories](#media-previews-in-stories)
  - [Redesign of the media previews of stories](#redesign-of-the-media-previews-of-stories)
  - [New heart like animation](#new-heart-like-animation)
  - [Old settings UI](#old-settings-ui)
  - [Accessibility settings](#accessibility-settings)
  - [Creator support option in Settings](#creator-support-option-in-settings)
  - [Content languages](#content-languages)
  - [New login UI](#new-login-ui)
  - [Extra Activity Status setting in Direct](#extra-activity-status-setting-in-direct)
  - [Direct new icon](#direct-new-icon)
  - [Redesign of the search bar in Direct](#redesign-of-the-search-bar-in-direct)
  - [More details about broadcast channels on the search section in Direct](#more-details-about-broadcast-channels-on-the-search-section-in-direct)
  - [Channels tab](#channels-tab)
  - [🆕Merge a lot of actions into a Plus button in the Direct chat list](#merge-a-lot-of-actions-into-a-plus-button-in-the-direct-chat-list)
  - [Plus button in stories tray](#plus-button-in-stories-tray)
  - [Show save animation](#show-save-animation)
  - [Fundraiser redesign](#fundraiser-redesign)
  - [New swipe to camera animation](#new-swipe-to-camera-animation)
  - [Enable threads icon in profile menu](#enable-threads-icon-in-profile-menu)
  - [Timestamps](#timestamps)
  - [Show live in direct panel](#show-live-in-direct-panel)
  - [Android widget](#android-widget)
  - [Liked by author](#liked-by-author)
  - [Album picker](#album-picker)
  - [Call screen redesign](#call-screen-redesign)
  - [New pip mode for audio calls](#new-pip-mode-for-audio-calls)
  - [Thick story ring](#thick-story-ring)
  - [Save Draft button in post publishing section](#save-draft-button-in-post-publishing-section)
  - [Redesign of the post editing section](#redesign-of-the-post-editing-section)
  - [🆕Music picker as the default post editing option with a redesigned appearance](#music-picker-as-the-default-post-editing-option-with-a-redesigned-appearance)
  - [Move the Alt Text option from the Advanced Settings to the normal ones](#move-the-alt-text-option-from-the-advanced-settings-to-the-normal-ones)
  - [Redesign of the search section in Direct](#redesign-of-the-search-section-in-direct)
  - [Redesign of the Text to Speech picker in Reels editor](#redesign-of-the-text-to-speech-picker-in-reels-editor)
  - [Redesign of the text creator in Reels editor](#redesign-of-the-text-creator-in-reels-editor)
  - [Merge audio and video call icons together and get an info button in chats](#merge-audio-and-video-call-icons-together-and-get-an-info-button-in-chats)
  - [Redesigned Watch more Reels page when a reel stops playing in the feed](#redesigned-watch-more-reels-page-when-a-reel-stops-playing-in-the-feed)
  - [🆕Remove the Watch again button from reels in the feed](#remove-the-watch-again-button-from-reels-in-the-feed)
  - [Variations of the new group chat button on the sharing sheet](#variations-of-the-new-group-chat-button-on-the-sharing-sheet)
  - [🆕Redesign of the message actions in Direct](#redesign-of-the-message-actions-in-direct)
  - [🆕Redesign of the unfinished draft reminder](#redesign-of-the-unfinished-draft-reminder)
  - [New filters icon](#new-filters-icon)
  - [🆕Redesign of the saving post draft animation](#redesign-of-the-saving-post-draft-animation)
  - [New apperance of reactions](#new-apperance-of-reactions)
  - [🆕Redesign of the reaction counter animation in Direct](#redesign-of-the-reaction-counter-animation-in-direct)
- [Feed](#feed)
  - [Feed video scrubber](#feed-video-scrubber)
  - [Shorter reels on the feed](#shorter-reels-on-the-feed)
  - [New sharing shortcut](#new-sharing-shortcut)
  - [Reminder post](#reminder-post)
  - [Add a poll when creating a post](#add-a-poll-when-creating-a-post)
  - [Change the intensity of the filter you're adding on a photo in post editor](#change-the-intensity-of-the-filter-youre-adding-on-a-photo-in-post-editor)
  - [Comments translations](#comments-translations)
  - [New sharing sheet](#new-sharing-sheet)
  - [🆕Redesigned circles on the sharing sheet](#redesigned-circles-on-the-sharing-sheet)
  - [Add notes to posts/reels](#add-notes-to-postsreels)
  - [Audience controls](#audience-controls)
  - [Simplified like, comment and share counts in the feed](#simplified-like-comment-and-share-counts-in-the-feed)
  - [Loop every reel for a second time in the feed](#loop-every-reel-for-a-second-time-in-the-feed)
  - [Quick share](#quick-share)
  - [Enable For You Tab](#enable-for-you-tab)
  - [Feed nav scroll away](#feed-nav-scroll-away)
  - [Auto advance carrousel posts](#auto-advance-carrousel-posts)
  - [Avatars in comments](#avatars-in-comments)
  - [🆕More images on posts](#more-images-on-posts)
  - [🆕Multi select photos on by default](#multi-select-photos-on-by-default)
  - [🆕Redesign of the media reordering on the carousel post editor](#redesign-of-the-media-reordering-on-the-carousel-post-editor)
  - [🆕Add music to carousel posts with video](#add-music-to-carousel-posts-with-video)
- [Reels](#reels)
  - [Hide Follow button](#hide-follow-button)
  - [Remove the audio description under the username in Reels](#remove-the-audio-description-under-the-username-in-reels)
  - [🆕Remove the audio pills at the bottom](#remove-the-audio-pills-at-the-bottom)
  - [Reels seekbar](#reels-seekbar)
  - [Fast forward reels](#fast-forward-reels)
  - [Change the fast forward speed of the reels](#change-the-fast-forward-speed-of-the-reels)
  - [Automatically scrolling reels](#automatically-scrolling-reels)
  - [Timestamp](#timestamp)
  - [❌ Music bar with pill border](#-music-bar-with-pill-border)
  - [❌ Show indicator "Liked by..."](#-show-indicator-liked-by)
  - [Show the number of views on your own reels](#show-the-number-of-views-on-your-own-reels)
  - [Caption translations](#caption-translations)
  - [Comment filtering](#comment-filtering)
  - [Comment previews](#comment-previews)
  - [Share comments to your story](#share-comments-to-your-story)
  - [Swipe view to profile](#swipe-view-to-profile)
  - [Hide suggested posts with certain words](#hide-suggested-posts-with-certain-words)
  - [🆕Manage captions and translations section in the reel options](#manage-captions-and-translations-section-in-the-reel-options)
  - [🆕Translate auto generated captions](#translate-auto-generated-captions)
  - [Text to speech](#text-to-speech)
  - [Captions creation](#captions-creation)
  - [Effects in Reels](#effects-in-reels)
  - [🆕Clip hub](#clip-hub)
  - [🆕Captions and Voiceover buttons on the quick reel editing options](#captions-and-voiceover-buttons-on-the-quick-reel-editing-options)
  - [🆕Gallery button on the quick reel editor](#gallery-button-on-the-quick-reel-editor)
  - [🆕Reverse clips on the reel editor](#reverse-clips-on-the-reel-editor)
  - [Add multiple tracks on Reel editor](#add-multiple-tracks-on-reel-editor)
  - [🆕New add to text bar on the Reels editor](#new-add-to-text-bar-on-the-reels-editor)
  - [🆕Add multiple clips on the reel editor at once](#add-multiple-clips-on-the-reel-editor-at-once)
  - [Tap on the reel preview on the editor to add text](#tap-on-the-reel-preview-on-the-editor-to-add-text)
  - [Floating friend’s likes](#floating-friends-likes)
  - [Short comment hint text](#short-comment-hint-text)
  - [Enable listen in spotify, or add to spotify playlist](#enable-listen-in-spotify-or-add-to-spotify-playlist)
  - [🆕Audio effects](#audio-effects)
  - [Tap to pause](#tap-to-pause)
  - [🆕Clear mode](#clear-mode)
  - [Copy link button under the share button in Reels](#copy-link-button-under-the-share-button-in-reels)
  - [Enable longer reels](#enable-longer-reels)
  - [Download reels](#download-reels)
  - [Share comments](#share-comments)
  - [Avatar comments](#avatar-comments)
  - [Carousel post mention](#carousel-post-mention)
  - [New comments menu](#new-comments-menu)
  - [Replies to replies](#replies-to-replies)
  - [Comments for you](#comments-for-you)
  - [Tap header to scroll to top](#tap-header-to-scroll-to-top)
  - [Filter](#filter)
  - [🆕Inspiration, Nearby, and Internal tabs in Reels](#inspiration-nearby-and-internal-tabs-in-reels)
  - [Reels map](#reels-map)
  - [Direct button in Reels](#direct-button-in-reels)
  - [Fixed brightness in the Reels section](#fixed-brightness-in-the-reels-section)
  - [Full screen reels](#full-screen-reels)
  - [🆕Pinch to zoom in reels](#pinch-to-zoom-in-reels)
  - [Reels blends](#reels-blends)
  - [🆕Profile Display](#profile-display)
  - [🆕Use the same colour in texts by default](#use-the-same-colour-in-texts-by-default)
  - [🆕Options of the reels editor being on the bottom. with rectangular buttons and new options](#options-of-the-reels-editor-being-on-the-bottom-with-rectangular-buttons-and-new-options)
  - [🆕Hold the reel to see a preview on your profile on the reel editor](#hold-the-reel-to-see-a-preview-on-your-profile-on-the-reel-editor)
  - [🆕Create cutout stickers with audio](#create-cutout-stickers-with-audio)
  - [🆕Reels stacks](#reels-stacks)
  - [🆕Remove the countdown from Voiceover on the reel editor](#remove-the-countdown-from-voiceover-on-the-reel-editor)
- [Explore](#explore)
  - [Share your Explore grid into a story](#share-your-explore-grid-into-a-story)
  - [Reduce and hide sensitive content](#reduce-and-hide-sensitive-content)
  - [For you and Add feed options in Explore](#for-you-and-add-feed-options-in-explore)
  - [Meta AI search feature in Explore](#meta-ai-search-feature-in-explore)
  - [Audio preview](#audio-preview)
  - [Increase audio preview duration](#increase-audio-preview-duration)
  - [Mutual filters](#mutual-filters)
  - [Reels tab in Explore](#reels-tab-in-explore)
  - [🆕Audio tab on the search tabs](#audio-tab-on-the-search-tabs)
  - [🆕Reels tab on the search tabs](#reels-tab-on-the-search-tabs)
  - [🆕Icons instead of texts while searching something](#icons-instead-of-texts-while-searching-something)
- [Stories](#stories)
  - [Rounded edges on the mentioned story](#rounded-edges-on-the-mentioned-story)
  - [🆕Mention back button on mentioned story](#mention-back-button-on-mentioned-story)
  - [Rounded edges on reels shared into story](#rounded-edges-on-reels-shared-into-story)
  - [Full screen reels shared into story](#full-screen-reels-shared-into-story)
  - [Story layers](#story-layers)
  - [Sound button](#sound-button)
  - [Move the progress bar to the bottom](#move-the-progress-bar-to-the-bottom)
  - [Custom replies](#custom-replies)
  - [Redesign of the reply bar in stories](#redesign-of-the-reply-bar-in-stories)
  - [Fix the reply bar not showing in Stories](#fix-the-reply-bar-not-showing-in-stories)
  - [Fix story replies not sending to the user](#fix-story-replies-not-sending-to-the-user)
  - [Story user search](#story-user-search)
  - [Messenger and Reply icons in viewer list](#messenger-and-reply-icons-in-viewer-list)
  - [Custom color stickers](#custom-color-stickers)
  - [Music sticker with avatar stickers](#music-sticker-with-avatar-stickers)
  - [Notify sticker](#notify-sticker)
  - [Add comments to stories](#add-comments-to-stories)
  - [Request Mention](#request-mention)
  - [Archive posted stories](#archive-posted-stories)
  - [Multiple close friends lists](#multiple-close-friends-lists)
  - [Enable story snapshot](#enable-story-snapshot)
  - [Disable cubic animation](#disable-cubic-animation)
  - [Add yours sticker button in the camera section](#add-yours-sticker-button-in-the-camera-section)
  - [Upload collaborative stories](#upload-collaborative-stories)
  - [Redesign of the story posting options](#redesign-of-the-story-posting-options)
  - [Shared Lists in stories](#shared-lists-in-stories)
  - [Friend's Story](#friends-story)
  - [60 second stories](#60-second-stories)
  - [Share profile to stories](#share-profile-to-stories)
  - [Post directly to highlights](#post-directly-to-highlights)
  - [Convert close friends to regular story](#convert-close-friends-to-regular-story)
  - [Group mention in stories](#group-mention-in-stories)
  - [Filled bar story reply box](#filled-bar-story-reply-box)
  - [Custom emoji reaction](#custom-emoji-reaction)
  - [More avatar reactions](#more-avatar-reactions)
  - [Spotify share](#spotify-share)
  - [Zoom stories](#zoom-stories)
  - [Generative AI in the stories editor](#generative-ai-in-the-stories-editor)
- [Camera](#camera)
  - [Music button in Stories creation](#music-button-in-stories-creation)
  - [Show the Music button first in Stories creation](#show-the-music-button-first-in-stories-creation)
  - [Organised toolbar in Stories creation](#organised-toolbar-in-stories-creation)
  - [New fonts](#new-fonts)
  - [New options in media selection](#new-options-in-media-selection)
  - [🆕Photos and Videos categories in media selection](#photos-and-videos-categories-in-media-selection)
  - [🆕Audio and Trending options in reel media selection](#audio-and-trending-options-in-reel-media-selection)
  - [🆕Draft counts](#draft-counts)
  - [🆕Duplicate reel drafts](#duplicate-reel-drafts)
  - [🆕Restore reel drafts that you have deleted](#restore-reel-drafts-that-you-have-deleted)
  - [🆕Suggested albums](#suggested-albums)
  - [🆕Zoom and unzoom the photos row in media selection](#zoom-and-unzoom-the-photos-row-in-media-selection)
  - [Boomerang on reel creation](#boomerang-on-reel-creation)
  - [Better organisation of the sidebar](#better-organisation-of-the-sidebar)
  - [🆕Better use of the gesture controls](#better-use-of-the-gesture-controls)
  - [Useful options as circles on reel recording](#useful-options-as-circles-on-reel-recording)
  - [Preview of the media while holding in Reels picker](#preview-of-the-media-while-holding-in-reels-picker)
  - [🆕Rename the Edit video button to Edit timing on the reel editor](#rename-the-edit-video-button-to-edit-timing-on-the-reel-editor)
- [Direct](#direct)
  - [Notes](#notes)
  - [Map bubble next to notes creation](#map-bubble-next-to-notes-creation)
  - [Vanish mode](#vanish-mode)
  - [Quiet mode](#quiet-mode)
  - [Chat translations](#chat-translations)
  - [Resize preview of shared reels](#resize-preview-of-shared-reels)
  - [Autoplay preview of shared reels](#autoplay-preview-of-shared-reels)
  - [Sent reel indicator on chat previews](#sent-reel-indicator-on-chat-previews)
  - [Forward button](#forward-button)
  - [Favourite stickers](#favourite-stickers)
  - [GIF and sticker forwarding](#gif-and-sticker-forwarding)
  - [Pong game while pressing an emoji in Direct](#pong-game-while-pressing-an-emoji-in-direct)
  - [New layout of chat details](#new-layout-of-chat-details)
  - [More options on the Privacy and Safety section in group chats](#more-options-on-the-privacy-and-safety-section-in-group-chats)
  - [Create a group chat through DMs](#create-a-group-chat-through-dms)
  - [Mute chat within XX hours](#mute-chat-within-xx-hours)
  - [Remove calls tab \& camera button](#remove-calls-tab--camera-button)
  - [Redesign of the new group chat screen](#redesign-of-the-new-group-chat-screen)
  - [Long press to change chat theme](#long-press-to-change-chat-theme)
  - [Enable gyroscopic themes](#enable-gyroscopic-themes)
  - [Theme picker redesign](#theme-picker-redesign)
  - [Swipe to open chat details](#swipe-to-open-chat-details)
  - [Animated avatar stickers](#animated-avatar-stickers)
  - [Smaller size of avatars in Direct](#smaller-size-of-avatars-in-direct)
  - [Smaller size of stickers in Direct](#smaller-size-of-stickers-in-direct)
  - [GIF categories](#gif-categories)
  - [New layout of long press menu](#new-layout-of-long-press-menu)
  - [Create Images with AI](#create-images-with-ai)
  - [Enable dropdown menu](#enable-dropdown-menu)
  - [Location Sharing](#location-sharing)
  - [Avatar powerups](#avatar-powerups)
  - [Fix GIFs and stickers not showing on the powerups section](#fix-gifs-and-stickers-not-showing-on-the-powerups-section)
  - [Pin chats](#pin-chats)
  - [Edit messages](#edit-messages)
  - [Disable read receipts](#disable-read-receipts)
  - [Disable typing indicator](#disable-typing-indicator)
  - [New modern design of the "send" button in a chat/note reply/comment composer](#new-modern-design-of-the-send-button-in-a-chatnote-replycomment-composer)
  - [Group invites](#group-invites)
  - [Voice messages](#voice-messages)
  - [In chat search](#in-chat-search)
  - [Change the group photo](#change-the-group-photo)
  - [Threshold for displaying the number of unread messages](#threshold-for-displaying-the-number-of-unread-messages)
  - [Chat with AI](#chat-with-ai)
  - [Disable swipe to direct](#disable-swipe-to-direct)
  - [Media stacks enabled](#media-stacks-enabled)
  - [Media previews before sending](#media-previews-before-sending)
  - [Avatar Animation](#avatar-animation)
  - [Non text replies](#non-text-replies)
  - [Reply to links](#reply-to-links)
  - [Show avatars in star tab](#show-avatars-in-star-tab)
  - [Set star tab to avatars](#set-star-tab-to-avatars)
  - [Seen states](#seen-states)
  - [AI Message replies](#ai-message-replies)
  - [Avatar reactions](#avatar-reactions)
  - [Delete messages for you](#delete-messages-for-you)
  - [Rename the Delete button to Unsend and get a new icon](#rename-the-delete-button-to-unsend-and-get-a-new-icon)
  - [Collab collections](#collab-collections)
  - [Reply box on sent reels](#reply-box-on-sent-reels)
  - [Tap to react](#tap-to-react)
  - [Silent share](#silent-share)
  - [Roll call](#roll-call)
  - [Birthday](#birthday)
  - [Leave silently from group chats](#leave-silently-from-group-chats)
  - [🆕Select button in the gallery in Direct](#select-button-in-the-gallery-in-direct)
  - [🆕Call settings](#call-settings)
  - [🆕Replace the Following button to Message on the fmembers list of a group chat](#replace-the-following-button-to-message-on-the-fmembers-list-of-a-group-chat)
- [Profile](#profile)
  - [Highlights design](#highlights-design)
  - [My week](#my-week)
  - [Highlights tray as cards](#highlights-tray-as-cards)
  - [Flipside](#flipside)
  - [Highlights grid](#highlights-grid)
  - [Highlights scrollable media preview](#highlights-scrollable-media-preview)
  - [Schedule posts](#schedule-posts)
  - [Insights for all accounts](#insights-for-all-accounts)
  - [Reels pinning](#reels-pinning)
  - [Show your other account in your username](#show-your-other-account-in-your-username)
  - [Remove suggested accounts](#remove-suggested-accounts)
  - [New "Create" icon](#new-create-icon)
  - [Show IGTV section](#show-igtv-section)
  - [Just seen](#just-seen)
  - [Profile Interests](#profile-interests)
  - [Pin your broadcast chat/social channel to your profile](#pin-your-broadcast-chatsocial-channel-to-your-profile)
  - [Saved subtab in Profile](#saved-subtab-in-profile)
  - [New header design](#new-header-design)
  - [Mutuals button in the header](#mutuals-button-in-the-header)
  - [New private account screen](#new-private-account-screen)
  - ["Threads" button added to profile header tab](#threads-button-added-to-profile-header-tab)
  - [Avatar as profile picture](#avatar-as-profile-picture)
  - [Wall notes](#wall-notes)
  - [Remove highlights in profile](#remove-highlights-in-profile)
  - [Compare activity](#compare-activity)
  - [External sharing](#external-sharing)
  - [Zoom people's profile icons](#zoom-peoples-profile-icons)
- [Livestreams](#livestreams)
  - [More audience options on live creation](#more-audience-options-on-live-creation)
  - [Share media with your audience in livestreams](#share-media-with-your-audience-in-livestreams)
  - [Games in livestreams](#games-in-livestreams)
- [Calls](#calls)
  - [Backgrounds in video calls](#backgrounds-in-video-calls)
- [Professional/Creator accounts](#professionalcreator-accounts)
  - [Welcome message](#welcome-message)
- [Fixes](#fixes)
  - [Fix all the hints showing even if they are already seen](#fix-all-the-hints-showing-even-if-they-are-already-seen)
  - [Fix the confetti animation showing in every note](#fix-the-confetti-animation-showing-in-every-note)
  - [Fix the huge gap in Direct when the Direct tab is on the bottom bar](#fix-the-huge-gap-in-direct-when-the-direct-tab-is-on-the-bottom-bar)
  - [🆕Fix music not playing in notes](#fix-music-not-playing-in-notes)
  - [Fix not being able to record videos for stories](#fix-not-being-able-to-record-videos-for-stories)
  - [🆕Fix not being able to take photos for stories](#fix-not-being-able-to-take-photos-for-stories)
  - [🆕Fix not being able to take photos with effects for your story](#fix-not-being-able-to-take-photos-with-effects-for-your-story)
  - [🆕Fix the story editor crashing when taking a photo](#fix-the-story-editor-crashing-when-taking-a-photo)
  - [🆕Fix the carousel post editor crashing](#fix-the-carousel-post-editor-crashing)
  - [🆕Fix the post gallery crashing](#fix-the-post-gallery-crashing)
  - [Fix the loud audio distortion and the image glitches when recording a video for stories / not being able to record videos for stories (for older bases)](#fix-the-loud-audio-distortion-and-the-image-glitches-when-recording-a-video-for-stories--not-being-able-to-record-videos-for-stories-for-older-bases)
  - [Fix low light mode being always enabled](#fix-low-light-mode-being-always-enabled)
  - [Fix the chats not loading after switching accounts](#fix-the-chats-not-loading-after-switching-accounts)
  - [Fix the chats crashing in Direct](#fix-the-chats-crashing-in-direct)
  - [🆕Fix the Direct tab crashing](#fix-the-direct-tab-crashing)
  - [Fix the notification tab crashing](#fix-the-notification-tab-crashing)
  - [Fix the muted audio in stories](#fix-the-muted-audio-in-stories)
  - [Fix Avatar options not showing in Direct](#fix-avatar-options-not-showing-in-direct)
  - [🆕Fix recommended users always showing up when adding a text in the Stories editor](#fix-recommended-users-always-showing-up-when-adding-a-text-in-the-stories-editor)
  - [🆕Fix the audio page crashing](#fix-the-audio-page-crashing)
  - [🆕Fix like and comment counts not showing in Reels](#fix-like-and-comment-counts-not-showing-in-reels)
  - [🆕Fix the text you add in the Reels editor being placed 0.5s ahead of where you put it](#fix-the-text-you-add-in-the-reels-editor-being-placed-05s-ahead-of-where-you-put-it)
  - [🆕Fix the Reels lagging](#fix-the-reels-lagging)
  - [🆕Fix the "The reel is unavailable." errors](#fix-the-the-reel-is-unavailable-errors)
  - [Fix not being able to press anything on the media picker in stories](#fix-not-being-able-to-press-anything-on-the-media-picker-in-stories)
  - [Fix crashes when opening Your Story](#fix-crashes-when-opening-your-story)
  - [Fix the weirdly streched reels](#fix-the-weirdly-streched-reels)
  - [🆕Fix some green boxes showing while watching reels](#fix-some-green-boxes-showing-while-watching-reels)
  - [🆕Fix the stories crashing](#fix-the-stories-crashing)
  - [Bring back the filters in Stories creation](#bring-back-the-filters-in-stories-creation)
  - [🆕Fix not being able to navigate in the Camera](#fix-not-being-able-to-navigate-in-the-camera)
  - [🆕Fix the gallery picker in Direct crashing](#fix-the-gallery-picker-in-direct-crashing)
  - [🆕Fix the status bar being white while watching reels](#fix-the-status-bar-being-white-while-watching-reels)
  - [🆕Fix the Mute options not showing](#fix-the-mute-options-not-showing)
  - [🆕Fix not being able to swipe to the feed while being on the chats list in Direct](#fix-not-being-able-to-swipe-to-the-feed-while-being-on-the-chats-list-in-direct)
  - [Fix the post editing section always being in HDR](#fix-the-post-editing-section-always-being-in-hdr)
  - [Fix the story editor always being in HDR](#fix-the-story-editor-always-being-in-hdr)
  - [🆕Fix the avatar reactions not showing on the reaction sheet in Stories](#fix-the-avatar-reactions-not-showing-on-the-reaction-sheet-in-stories)
  - [🆕Fix the avatar reactions not loading on the reaction sheet in Stories](#fix-the-avatar-reactions-not-loading-on-the-reaction-sheet-in-stories)
  - [Fix shared reels always being big](#fix-shared-reels-always-being-big)

---

# Important
## 🆕 Prevent Instagram from taking lots of space in app data
- ```analytics2 consolidation max batch lock attempts``` = 0
This prevents Instagram from creating analytic files on device, which in turn allows you to keep a correct size of the application.

Flag information:
- Added in version 310 or earlier
<br>[Jump to start!](#how-to-enabledisable-flags)

## Make the app more efficient
- ```analytics2 consolidation``` - disable everything
- ```autofill global v2``` - disable everything
Disable everything so the app creates less processes and becomes more efficient.

Flag information:
- Added in version 310 or earlier
<br>[Jump to start!](#how-to-enabledisable-flags)

## Remove the Google Play update dialog
- ```google play update api``` - disable everything

Flag information:
- Added in version 310 or earlier
- Removed temporarily in version 318.0.0.0.58
- Added back in version 318.0.0.0.65
<br>[Jump to start!](#how-to-enabledisable-flags)

## Disable Thread posts in the feed
```threads xma```
<br>[Jump to start!](#how-to-enabledisable-flags)

## Messenger update
```igd xac unbundle```<br>
Enables all settings for you even if your account is not eligible for these<br>
Removed in 317.0.0.0.41
<br>[Jump to start!](#how-to-enabledisable-flags)

## Remove Threads usernames and button
```spain growth```
<br>[Jump to start!](#how-to-enabledisable-flags)

## 🆕Remove the reel ads and improve/fix adblocking in Instagram mods
- ```sundial ads```
- ```tigon config```
- ```network stack```
- ```nme ig dev```
- ```csv reason```
Disable everything
<br>[Jump to start!](#how-to-enabledisable-flags)

## 🆕Remove the story ads with the "LEARN MORE" stickers inside
```stories cta stickers```
<br>[Jump to start!](#how-to-enabledisable-flags)

## 🆕Enable the shake phone to report a problem sheet even if you disabled it
```rageshake ui```
<br>[Jump to start!](#how-to-enabledisable-flags)

# Quality
## Upload photos up to 1440p resolution in stories
```ensure 1440p photo upload```<br>
By default the photos you upload to stories are 1080, enabling this setting will increase the resolution up to 1440.
<br>[Jump to start!](#how-to-enabledisable-flags)

## Reduce compression of photo uploads in the feed
```photo creation```<br>
70 = 30% compression<br>
100 = 0% compression (without compression)
<br>[Jump to start!](#how-to-enabledisable-flags)

## High quality video uploads on stories and reels
```high quality upload setting```<br>
Enter the name and enable the toggle and put the bitrate mbps to 20 (recommended).

You can change it to 20 if you use video with 1080p or 1440p resolution (for slightly better compression). And the maximum bitrate you can use is 30 (suitable for 4k video) but there is a possibility that the video will fail to upload if you use bitrate above 25Mbps so be careful.


After enabling the setting restart the app, and then go to the Instagram settings > Account or Preferences > Cellular data use > and turn on the "Upload at highest quality" option.
<br>[Jump to start!](#how-to-enabledisable-flags)

## Audio
## Enable 48khz sample rate
```cameracore fbaudio ig use 48khz sample rate```
<br>[Jump to start!](#how-to-enabledisable-flags)

## Enable stereo
```cameracore fbaudio ig use stereo```
<br>[Jump to start!](#how-to-enabledisable-flags)

# UI
## New loading screen
- ```async app init clone``` - enable everything

Please note that you must clear the app data if you want to remove it after that otherwise the app will crash continuously.

Flag information:
- Added in version 310 or earlier
- Removed temporarily in version 310.0.0.0.277
- Added back in version 310.0.0.0.285
- Removed temporarily again in version 318.0.0.0.58
- Added back again in version 318.0.0.0.65
<br>[Jump to start!](#how-to-enabledisable-flags)

## Customize buttons layout 
```panavision nav3```<br>
Words You Can Use in Changeable Settings (between tab 0-4 and top bar 0-2) (When typing, you should write them all in lowercase.); 

- home
- explore
- clips
- shopping
- profile
- direct
- share
- news
- menu
- friend_map
- groups (removed in newer versions)
<br>[Jump to start!](#how-to-enabledisable-flags)

## Change activity icon to bell icon
```bell icon```<br>
Photo preview pending
<br>[Jump to start!](#how-to-enabledisable-flags)

## New spinner in the feed and profile
```ptr spinner is enabled```
<br>[Jump to start!](#how-to-enabledisable-flags)

## Filled bottom row buttons
```filled tab icons```<br>
Only works for the buttons on the bottom row.

(this animation took me 3 hours)
<br>[Jump to start!](#how-to-enabledisable-flags)

## New dark mode
```igds prism launcher config android```<br>
Enable the new dark mode in instagram, from being an AMOLED black to a more pleasant dark blue.
<br>[Jump to start!](#how-to-enabledisable-flags)

## Fix empty space below bottom navigation bar
```is mw bottom padding enabled```<br>
Doesn't work anymore
<br>[Jump to start!](#how-to-enabledisable-flags)

## Enable sheet multi tab
```comment sheet multi tabs```<br>
The ```is share tab enabled``` option inside this flag can crash the comments when trying to open them in a post through the See all comments button. Instead, press the comments action to open them.
<br>[Jump to start!](#how-to-enabledisable-flags)

## 🆕Redesigned comment section
```comments mvvm migration```
<br>[Jump to start!](#how-to-enabledisable-flags)

## Open links in external browser
```should override to external browser```
<br>[Jump to start!](#how-to-enabledisable-flags)

## New stories stickers menu design
```stories sticker tray redesign```
<br>[Jump to start!](#how-to-enabledisable-flags)

## Redesign of the media picker in Direct
```convos reshare hub```<br>
New media button in dm, with some nice-to-have features.<br>
Removed in 326.0.0.0.29
<br>[Jump to start!](#how-to-enabledisable-flags)

## 🆕Dark gallery in Direct at all times
```gallery dark theme```
<br>[Jump to start!](#how-to-enabledisable-flags)

## User avatar size in stories tray
```avatar in standard tray```<br>
Only choose one.
<br>[Jump to start!](#how-to-enabledisable-flags)

## Media previews in stories
```media previews in stories tray```<br>
Disable ```only gray background enabled for debugging``` if the previews are always gray.
<br>[Jump to start!](#how-to-enabledisable-flags)

## Redesign of the media previews of stories
```stories in feed redesign```<br>
If you enable ```show author on top``` the previews will show abnormal.
<br>[Jump to start!](#how-to-enabledisable-flags)

## New heart like animation
```new double tap to like animation```<br>
or (depends on version)

```new double tap heart animation```<br>
<br>[Jump to start!](#how-to-enabledisable-flags)

## Old settings UI
```fx centralized settings show entrypoint```<br>
```project elevation enabled```<br>
Disable both, Show the old UI of instagram setting menu instead of the new one.
<br>[Jump to start!](#how-to-enabledisable-flags)

## Accessibility settings
```accessibility setting```
<br>[Jump to start!](#how-to-enabledisable-flags)

## Creator support option in Settings
```creator support portal```<br>
As it's not ready yet (the page shows a 404 error), you can find the setting only by searching for it in Settings.
<br>[Jump to start!](#how-to-enabledisable-flags)

## Content languages
```ig4a content languages```
<br>[Jump to start!](#how-to-enabledisable-flags)

## New login UI
- ```bypass triage oe``` = true
- ```should see xav switcher``` = true

Flag information:
- Added in version 310 or earlier
- Removed in version 318.0.0.0.58
- Added back in version 318.0.0.0.65
<br>[Jump to start!](#how-to-enabledisable-flags)

## Extra Activity Status setting in Direct
```enable bloks www activity status settings screen```<br>
No idea why it doesn't work
<br>[Jump to start!](#how-to-enabledisable-flags)

## Direct new icon
```direct interop rebrand```
<br>[Jump to start!](#how-to-enabledisable-flags)

## Redesign of the search bar in Direct
```igd android gen ai search xstack```

- MetaAI logo animation
  - ```show meta ai flip animation in search```
  - ```show meta ai spin animation in search```
  Only enable one, or the app will crash when you leave the search section if the flip animation hasn't ended.
<br>[Jump to start!](#how-to-enabledisable-flags)

## More details about broadcast channels on the search section in Direct
```igd search h1 2023```<br>
Don't enable ```disable inbox cache results``` and ```disable trt on share sheet private share```.
<br>[Jump to start!](#how-to-enabledisable-flags)

## Channels tab
```channels inbox discovery```<br>
Enable everything except:

- ```disable channels tab badging```
- ```disable mesages tab badging```
- ```fetch channels on startup``` (this makes unloadable direct list)
- ```decline invitations from inbox enabled```
<br>[Jump to start!](#how-to-enabledisable-flags)

## 🆕Merge a lot of actions into a Plus button in the Direct chat list
```action based conversations```
<br>[Jump to start!](#how-to-enabledisable-flags)

## Plus button in stories tray
```icon over ring enabled```
<br>[Jump to start!](#how-to-enabledisable-flags)

## Show save animation
```should show save flow on tap```<br>
Removed in 318.0.0.0.84
<br>[Jump to start!](#how-to-enabledisable-flags)

## Fundraiser redesign
```fundraiser donation sheet redesign```
<br>[Jump to start!](#how-to-enabledisable-flags)

## New swipe to camera animation
```camera android nav3 bottom creation animation```
<br>[Jump to start!](#how-to-enabledisable-flags)

## Enable threads icon in profile menu
```is ig to p92 app switcher enabled android```
<br>[Jump to start!](#how-to-enabledisable-flags)

## Timestamps
```feed marie kondo android```<br>
Show when the post/reel was posted.

Keep disabled ```feed marie kondo android should disable timestamps for recommended posts```.<br>
<br>[Jump to start!](#how-to-enabledisable-flags)

## Show live in direct panel
```live android direct```<br>
Shows live in direct panel over the user's profile picture.
<br>[Jump to start!](#how-to-enabledisable-flags)

## Android widget
```direct widget```<br>
Enables a new widget to use on your Android homescreen.<br>
Not working yet
<br>[Jump to start!](#how-to-enabledisable-flags)

## Liked by author
```bullying comment liked by author```<br>
Shows liked by author in reels and feed comments
<br>[Jump to start!](#how-to-enabledisable-flags)

## Album picker
```gallery album picker```<br>
Choose an album, photos or videos to show in the list
<br>[Jump to start!](#how-to-enabledisable-flags)

## Call screen redesign
```vc halo call controls```<br>
Make the end call and the action buttons more circular.<br>
Removed in 333.0.0.0.38
<br>[Jump to start!](#how-to-enabledisable-flags)

## New pip mode for audio calls
```lounge```<br>
Press the Mute button only once, it's buggy and it won't show the Unmute text while it'll unmute, press the Full screen button and go back and it'll show it normally.
<br>[Jump to start!](#how-to-enabledisable-flags)

## Thick story ring
```craft android pog parity```<br>
<br>[Jump to start!](#how-to-enabledisable-flags)

## Save Draft button in post publishing section
```feed publish screen redesign```
<br>[Jump to start!](#how-to-enabledisable-flags)

## Redesign of the post editing section
```post editing flow updates```
<br>[Jump to start!](#how-to-enabledisable-flags)

## 🆕Music picker as the default post editing option with a redesigned appearance
```mif creation post cap```
<br>[Jump to start!](#how-to-enabledisable-flags)

## Move the Alt Text option from the Advanced Settings to the normal ones
```custom alt text update```
<br>[Jump to start!](#how-to-enabledisable-flags)

## Redesign of the search section in Direct
```igd search h2 2023```
<br>[Jump to start!](#how-to-enabledisable-flags)

## Redesign of the Text to Speech picker in Reels editor
```camera android reels tts postcap```
<br>[Jump to start!](#how-to-enabledisable-flags)

## Redesign of the text creator in Reels editor
```reels feels like ig text```
<br>[Jump to start!](#how-to-enabledisable-flags)

## Merge audio and video call icons together and get an info button in chats
```direct thread details discovery```
<br>[Jump to start!](#how-to-enabledisable-flags)

## Redesigned Watch more Reels page when a reel stops playing in the feed
```panavision consumption enable end scene```<br>
Removed in 327 and later<br>
🆕Newer versions:<br>
```clips feed preview is endscreen preview thumbnail enabled```<br>
Crashes the app when the reel plays for a second time in 330 and later.
<br>[Jump to start!](#how-to-enabledisable-flags)

## 🆕Remove the Watch again button from reels in the feed
```clips feed preview is watch again full screen enabled```
<br>[Jump to start!](#how-to-enabledisable-flags)

## Variations of the new group chat button on the sharing sheet
```group cration entrypoint variant```<br>
Values: 0, 1, 2
<br>[Jump to start!](#how-to-enabledisable-flags)

## 🆕Redesign of the message actions in Direct
```igd long press message action```
<br>[Jump to start!](#how-to-enabledisable-flags)

## 🆕Redesign of the unfinished draft reminder
```unfinished reminder draft preview```
<br>[Jump to start!](#how-to-enabledisable-flags)

## New filters icon
```ar effects icon change```
<br>[Jump to start!](#how-to-enabledisable-flags)

## 🆕Redesign of the saving post draft animation
```feed initial exit save spinner enabled```
<br>[Jump to start!](#how-to-enabledisable-flags)

## New apperance of reactions
```direct multi react xstack```<br>
Disable if the reactions are buggy
<br>[Jump to start!](#how-to-enabledisable-flags)

## 🆕Redesign of the reaction counter animation in Direct
```direct reaction counter animation```
<br>[Jump to start!](#how-to-enabledisable-flags)

# Feed
## Feed video scrubber
```scrubber in expanded video```<br>
Attention!!! Only works for reels videos in the main feed. This doesn't work for IGTV, regular video, and carousel videos in the Following, Explore, and Profile tabs.
<br>[Jump to start!](#how-to-enabledisable-flags)

## Shorter reels on the feed
```tall video```<br>
Disable everything<br>
Makes the reels on the feed shorter, so they don't take use of the entire screen.
<br>[Jump to start!](#how-to-enabledisable-flags)

## New sharing shortcut
```super share```<br>
Attention!!! Not recommended to activate the 3rd option because the "add X to your story" button will stop appearing on the IGTV posts and regular ones in the Profile & Explore tabs.<br>
Also if the save button doesn't show then disable ```show save```.
<br>[Jump to start!](#how-to-enabledisable-flags)

## Reminder post
```upcoming events creation```
<br>[Jump to start!](#how-to-enabledisable-flags)

## Add a poll when creating a post
```android comment polls```
<br>[Jump to start!](#how-to-enabledisable-flags)

## Change the intensity of the filter you're adding on a photo in post editor
```camera feed photo filters show filter intensity indicator```
<br>[Jump to start!](#how-to-enabledisable-flags)

## Comments translations
```comments translations```
<br>[Jump to start!](#how-to-enabledisable-flags)

## New sharing sheet
```super share v3```<br>
Enable everything, and modify add top story hscroll to 0 if you want the add to story button, or set it to 1 to remove it
<br>[Jump to start!](#how-to-enabledisable-flags)

## 🆕Redesigned circles on the sharing sheet
```visual hscroll```
<br>[Jump to start!](#how-to-enabledisable-flags)

## Add notes to posts/reels
```content notes```<br>
No preview until it works again
<br>[Jump to start!](#how-to-enabledisable-flags)

## Audience controls
```audience controls```
<br>[Jump to start!](#how-to-enabledisable-flags)

## Simplified like, comment and share counts in the feed
Enable everything inside:

- ```feed emphasized social ufi```
Keep disabled:

- ```feed emphasized social ufi view all comments enabled```

Old versions<br>
```simplified post layout```
<br>[Jump to start!](#how-to-enabledisable-flags)

## Loop every reel for a second time in the feed
```feed  video min length for single loop ms```<br>
Set the value to 1000000.
<br>[Jump to start!](#how-to-enabledisable-flags)

## Quick share
```quick send tlc```<br>
Hold the share button to quickly share the post to a user.<br>
If you see some weird rings, disable ```show prism avatar ring``` from ```igds prism launcher config android```.
<br>[Jump to start!](#how-to-enabledisable-flags)

## Enable For You Tab
```feed dsa header nav enable for you title switch```<br>
```feed dsa header nav enable for you title switch with delay```<br>
The second one makes the For You tab showing abnormally after going to profile and back to home in newer versions.
<br>[Jump to start!](#how-to-enabledisable-flags)

## Feed nav scroll away
```feed scroll away nav```<br>
The top bar scrolls away when navigating though the feed
<br>[Jump to start!](#how-to-enabledisable-flags)

## Auto advance carrousel posts
```concurrent grid video autoplay```<br>
Auto scroll posts in the feed.
<br>[Jump to start!](#how-to-enabledisable-flags)

## Avatars in comments
```avatars in comments```<br>
Keep is internal only disabled
<br>[Jump to start!](#how-to-enabledisable-flags)

## 🆕More images on posts
```core flows android increased carousel size limit```<br>
Set the option to more than 10.
<br>[Jump to start!](#how-to-enabledisable-flags)

## 🆕Multi select photos on by default
```feed creation multiselect enabled```
<br>[Jump to start!](#how-to-enabledisable-flags)

## 🆕Redesign of the media reordering on the carousel post editor
```camera android feed carousel reorder```
<br>[Jump to start!](#how-to-enabledisable-flags)

## 🆕Add music to carousel posts with video
```music in carousel 2024```
<br>[Jump to start!](#how-to-enabledisable-flags)

# Reels
## Hide Follow button
```android viewer disable follow button```<br>
Removes the follow button while watching reels.
<br>[Jump to start!](#how-to-enabledisable-flags)

## Remove the audio description under the username in Reels
```should add audio secondary text```<br>
Disable it
<br>[Jump to start!](#how-to-enabledisable-flags)

## 🆕Remove the audio pills at the bottom
```should hide attribution hub```
<br>[Jump to start!](#how-to-enabledisable-flags)

## Reels seekbar
```clips viewer scrubber improvements```<br>
Set android attachment scrubber duration to 1 to have the scrubber in all reels including short ones

```preview thumbnails are enabled```
<br>[Jump to start!](#how-to-enabledisable-flags)

## Fast forward reels
```long press fast reels```<br>
Hold the edges of the reel.
<br>[Jump to start!](#how-to-enabledisable-flags)

## Change the fast forward speed of the reels
```long press fast reels fast playback speed```<br>
Change the value to 3 for 3x speed, 3.5 for 3.5x etc.
<br>[Jump to start!](#how-to-enabledisable-flags)

## Automatically scrolling reels
```reels auto scroll v1```
<br>[Jump to start!](#how-to-enabledisable-flags)

## Timestamp
```clips relative timestamp```<br>
Enter the name and enable all the toggles.

Removed in newer versions
<br>[Jump to start!](#how-to-enabledisable-flags)

## ❌ Music bar with pill border
```viewer merchandising pill system```
<br>[Jump to start!](#how-to-enabledisable-flags)

## ❌ Show indicator "Liked by..."
```clips social context likers```
<br>[Jump to start!](#how-to-enabledisable-flags)

## Show the number of views on your own reels
```reels played by```<br>
Show the ammount of users that have seen your reel

No idea why it does not work
<br>[Jump to start!](#how-to-enabledisable-flags)

## Caption translations
```clips viewer caption see translation```<br>
Only activate the 1st option.
<br>[Jump to start!](#how-to-enabledisable-flags)

## Comment filtering
```participation comments dsa```
<br>[Jump to start!](#how-to-enabledisable-flags)

## Comment previews
```clips comment previews```
<br>[Jump to start!](#how-to-enabledisable-flags)

## Share comments to your story
```creator connection share to stories```
<br>[Jump to start!](#how-to-enabledisable-flags)

## Swipe view to profile
Older versions:<br>
```swipe to profile```<br>
🆕Newer versions:<br>
```reels swipe to action```<br>
Don't enable ```enable swipe debug visualizer``` (it will cause [this:](#fix-some-green-boxes-showing-while-watching-reels)).<br>
Only works on reels tab.
<br>[Jump to start!](#how-to-enabledisable-flags)

## Hide suggested posts with certain words
```hide unconnected posts with words```<br>
With this option you can hide or get rid of suggested posts that have certain words and emojis in the captions of the video, after adding the word you want to hide then all suggested posts that have that word in their captions 'will not' appear in your feed and reels tab as suggested posts.
<br>[Jump to start!](#how-to-enabledisable-flags)

## 🆕Manage captions and translations section in the reel options
```clips translated audio dubbing```
<br>[Jump to start!](#how-to-enabledisable-flags)

## 🆕Translate auto generated captions
```reels closed captions translations```<br>
Doesn't work on my side
<br>[Jump to start!](#how-to-enabledisable-flags)

## Text to speech
```reels text to speech```<br>
This feature is only available for reels and not for stories.
<br>[Jump to start!](#how-to-enabledisable-flags)

## Captions creation
Older versions:
```reels add captions```<br>
Removed in 319.0.0.0.104

Newer versions:
```camera android reels captions expansion```<br>
Added in 319.0.0.0.104

This feature is only available for reels and not for stories.
<br>[Jump to start!](#how-to-enabledisable-flags)

## Effects in Reels
```timeline ar effects button```<br>
Add effects on your reels.
<br>[Jump to start!](#how-to-enabledisable-flags)

## 🆕Clip hub
```camera android tp media```<br>
Add GIFs to reels.
<br>[Jump to start!](#how-to-enabledisable-flags)

## 🆕Captions and Voiceover buttons on the quick reel editing options
```camera android reels postcap high increment tools caption and voiceover```
<br>[Jump to start!](#how-to-enabledisable-flags)

## 🆕Gallery button on the quick reel editor
```camera android reels postcap high increment tools gallery sticker button```
<br>[Jump to start!](#how-to-enabledisable-flags)

## 🆕Reverse clips on the reel editor
```enable clip reverse```<br>
It doesn't reverse the audio.
<br>[Jump to start!](#how-to-enabledisable-flags)

## Add multiple tracks on Reel editor
```camera android multiple audio tracks```<br>
Don't enable ```single track only```.
<br>[Jump to start!](#how-to-enabledisable-flags)

## 🆕New add to text bar on the Reels editor
```camera android timeline text ghost track```
<br>[Jump to start!](#how-to-enabledisable-flags)

## 🆕Add multiple clips on the reel editor at once
```reels add clips multiselect enabled```
<br>[Jump to start!](#how-to-enabledisable-flags)

## Tap on the reel preview on the editor to add text
```reels tap to add text is enabled```
<br>[Jump to start!](#how-to-enabledisable-flags)

## Floating friend’s likes
```clips friendly viewer```<br>
Disable everything if you get any "This reel is unavailable." errors
<br>[Jump to start!](#how-to-enabledisable-flags)

## Short comment hint text
```should shorten comment hint text```
<br>[Jump to start!](#how-to-enabledisable-flags)

## Enable listen in spotify, or add to spotify playlist
```spotify partnership```
<br>[Jump to start!](#how-to-enabledisable-flags)

## 🆕Audio effects
```camera android reels audio filters```
<br>[Jump to start!](#how-to-enabledisable-flags)

## Tap to pause
```reels tap to pause```
<br>[Jump to start!](#how-to-enabledisable-flags)

## 🆕Clear mode
```reels gestures```<br>
Enable the option and set the value to 1.
<br>[Jump to start!](#how-to-enabledisable-flags)

## Copy link button under the share button in Reels
```external sharing is copy link on reel ufi enabled```
<br>[Jump to start!](#how-to-enabledisable-flags)

## Enable longer reels
```reels duration```
<br>[Jump to start!](#how-to-enabledisable-flags)

## Download reels
```reels third party downloads```<br>
Press the share button and press Download.<br>
Only works for public reels.
<br>[Jump to start!](#how-to-enabledisable-flags)

## Share comments
Older versions (only for limited accounts):<br>
```conversations comment reshares```<br>
(Removed in 318.0.0.0.58)

Newer versions:<br>
comment  reshares<br>
(Added in 319.0.0.0.7)<br>
Make sure that this will remove your ability to share comments to stories.
<br>[Jump to start!](#how-to-enabledisable-flags)

## Avatar comments
```avatars in comments```
<br>[Jump to start!](#how-to-enabledisable-flags)

## Carousel post mention
Old versions<br>
```carousel slide comments```<br>
New versions<br>
```carousel comments with combo button```<br>
Removed in 320.0.0.0.1
<br>[Jump to start!](#how-to-enabledisable-flags)

## New comments menu
```comment actions menu```
<br>[Jump to start!](#how-to-enabledisable-flags)

## Replies to replies
```comments replies to replies```
<br>[Jump to start!](#how-to-enabledisable-flags)

## Comments for you
```android comments for you```
<br>[Jump to start!](#how-to-enabledisable-flags)

## Tap header to scroll to top
```reels scroll to top status bar disabled```<br>
Disable to tap on the status bar to scroll to the first seen reel.
<br>[Jump to start!](#how-to-enabledisable-flags)

## Filter
```clips tab dsa```<br>
Choose between close reels and following users.<br>
<br>[Jump to start!](#how-to-enabledisable-flags)

## 🆕Inspiration, Nearby, and Internal tabs in Reels
```clips content lanes```<br>
Don't enable ```enable inspiration lane prefetch``` otherwise the Inspiration tab will not work.
<br>[Jump to start!](#how-to-enabledisable-flags)

## Reels map
```reels map```
<br>[Jump to start!](#how-to-enabledisable-flags)

## Direct button in Reels
```direct in viewer```
<br>[Jump to start!](#how-to-enabledisable-flags)

## Fixed brightness in the Reels section
```clips brightness```<br>
Enable the option and set the value from 0-100 to have a fixed brightness in reels.
<br>[Jump to start!](#how-to-enabledisable-flags)

## Full screen reels
```is extended scrollaway nav enabled for reels```<br>
Not working for all versions between 317 and 324.<br>
To enable full screen reels for these versions enable:<br>
```clips playback force scaling mode fit for clips```
<br>[Jump to start!](#how-to-enabledisable-flags)

## 🆕Pinch to zoom in reels
```reels pinch to zoom```<br>
It might crash on some bases (or mods, I'm not that sure).
<br>[Jump to start!](#how-to-enabledisable-flags)

## Reels blends
```reels blends```<br>
Like reels together for newer versions
<br>[Jump to start!](#how-to-enabledisable-flags)

## 🆕Profile Display
```camera android reels profile display```<br>
Choose whether you want the reel to be seen to your profile or only on the reels tab.
<br>[Jump to start!](#how-to-enabledisable-flags)

## 🆕Use the same colour in texts by default
```camera android reels sticky text```
<br>[Jump to start!](#how-to-enabledisable-flags)

## 🆕Options of the reels editor being on the bottom. with rectangular buttons and new options
```camera android creation post cap lite```
<br>[Jump to start!](#how-to-enabledisable-flags)

## 🆕Hold the reel to see a preview on your profile on the reel editor
```camera android postcap reels viewer preview```
<br>[Jump to start!](#how-to-enabledisable-flags)

## 🆕Create cutout stickers with audio
```cutout sticker audio```<br>
Only works when adding them in reels.
<br>[Jump to start!](#how-to-enabledisable-flags)

## 🆕Reels stacks
```reels stacks```<br>
<br>[Jump to start!](#how-to-enabledisable-flags)

## 🆕Remove the countdown from Voiceover on the reel editor
```skip countdown```
<br>[Jump to start!](#how-to-enabledisable-flags)

# Explore
## Share your Explore grid into a story
```explore shareable grid```
<br>[Jump to start!](#how-to-enabledisable-flags)

## Reduce and hide sensitive content
```igmwb explore controls```
<br>[Jump to start!](#how-to-enabledisable-flags)

## For you and Add feed options in Explore
```friend grid```
<br>[Jump to start!](#how-to-enabledisable-flags)

## Meta AI search feature in Explore
```client search meta ai integration```<br>
Either I don't know how to use it, or it's only available in the U.S.
<br>[Jump to start!](#how-to-enabledisable-flags)

## Audio preview
```clips global audio search```
<br>[Jump to start!](#how-to-enabledisable-flags)

## Increase audio preview duration
```audio page music preview duration```
<br>[Jump to start!](#how-to-enabledisable-flags)

## Mutual filters
```stories mutuals filter```<br>
Not working at the moment
<br>[Jump to start!](#how-to-enabledisable-flags)

## Reels tab in Explore
```reels subtab```<br>
Long press search icon to search<br>
Removed in newer versions
<br>[Jump to start!](#how-to-enabledisable-flags)

## 🆕Audio tab on the search tabs
```clips global audio search```
<br>[Jump to start!](#how-to-enabledisable-flags)

## 🆕Reels tab on the search tabs
- ```reels search tab is reels search subtab enabled android```
- ```reels search tab search subtab enabled ios```
<br>[Jump to start!](#how-to-enabledisable-flags)

## 🆕Icons instead of texts while searching something
Newer versions:
- ```scrollable tabs enabled```
- ```scrollable serp tabs```
Disable everything<br>
Older versions:
- ```client search non profiled serp android force icons```
- ```client search non profiled serp ios force icons```
Enable everything
- ```android search enabled```
- ```ios search enabled```
Disable everything
<br>[Jump to start!](#how-to-enabledisable-flags)

# Stories
## Rounded edges on the mentioned story
```stories mention reshare video sticker```<br>
When resharing a story where you have been mentioned, no sound will be audible.<br>
Removed in 333.0.0.87
<br>[Jump to start!](#how-to-enabledisable-flags)

## 🆕Mention back button on mentioned story
```stories reiprocal mentions```<br>
Take into account that it might cause some issues.
<br>[Jump to start!](#how-to-enabledisable-flags)

## Rounded edges on reels shared into story
```stories video sticker migration```<br>
Might not work well in some versions<br>
If you want to share 60-second stories with the full duration showing into the story, disable this.
<br>[Jump to start!](#how-to-enabledisable-flags)

## Full screen reels shared into story
```stories originality immersive reshare```
<br>[Jump to start!](#how-to-enabledisable-flags)

## Story layers
```stories layer editor```<br>
```stories android sticker layering tool```
<br>[Jump to start!](#how-to-enabledisable-flags)

## Sound button
```stories sound indicator```<br>
Can be enabled, but wont work in newer versions
<br>[Jump to start!](#how-to-enabledisable-flags)

## Move the progress bar to the bottom
```stories bottom progress bar```<br>
Removed in version 309.0.0.0.98
<br>[Jump to start!](#how-to-enabledisable-flags)

## Custom replies
```reply types```<br>
Reply to stories with media, camera, stickers, emojis, gifs or reacts
<br>[Jump to start!](#how-to-enabledisable-flags)

## Redesign of the reply bar in stories
```reply bar modernization```<br>
Only works since the base 325 and later, in the previous bases it'll crash the stories.
<br>[Jump to start!](#how-to-enabledisable-flags)

## Fix the reply bar not showing in Stories
```stories viewer reply composer mvvm```<br>
Disable it
<br>[Jump to start!](#how-to-enabledisable-flags)

## Fix story replies not sending to the user
```is enabled for story internal```
<br>[Jump to start!](#how-to-enabledisable-flags)

## Story user search
```story dashboard search```<br>
Removed in newer versions
<br>[Jump to start!](#how-to-enabledisable-flags)

## Messenger and Reply icons in viewer list
```ios spark viewer list message icon```<br>
Only 1

Pending animation preview
<br>[Jump to start!](#how-to-enabledisable-flags)

## Custom color stickers
```stories custom color gradient stickers```<br>
Working for location, mention, link, and hashtag stickers.
<br>[Jump to start!](#how-to-enabledisable-flags)

## Music sticker with avatar stickers
```avatars avatar with music sticker```<br>
```music sticker with animated avatar stickers```<br>
```avatars avatar with music sticker is animated stickers enabled```
<br>[Jump to start!](#how-to-enabledisable-flags)

## Notify sticker
```notify me sticker```
<br>[Jump to start!](#how-to-enabledisable-flags)

## Add comments to stories
```story interactions hype```<br>
Pending launch
<br>[Jump to start!](#how-to-enabledisable-flags)

## Request Mention
```stories request mention```<br>
Removed in newer versions
<br>[Jump to start!](#how-to-enabledisable-flags)

## Archive posted stories
```stories archive refactor```<br>
Removed in newer versions
<br>[Jump to start!](#how-to-enabledisable-flags)

## Multiple close friends lists
```private lists```<br>
They're not working well at the moment
<br>[Jump to start!](#how-to-enabledisable-flags)

## Enable story snapshot
```story snapshot```
<br>[Jump to start!](#how-to-enabledisable-flags)

## Disable cubic animation
```stories viewer preq cube```
<br>[Jump to start!](#how-to-enabledisable-flags)

## Add yours sticker button in the camera section
```add yours browser```
<br>[Jump to start!](#how-to-enabledisable-flags)

## Upload collaborative stories
```stories collab stories```<br>
Not working for now, if you try this feature you will end with a story error and a video that you will not be able to delete.
<br>[Jump to start!](#how-to-enabledisable-flags)

## Redesign of the story posting options
```ampersand story sharecut null```<br>
Enable both options
<br>[Jump to start!](#how-to-enabledisable-flags)

## Shared Lists in stories
```hallpass```<br>
Not to be confused with [collaborative stories](#upload-collaborative-stories) or the [multiple close friends lists](#multiple-close-friends-lists).
<br>[Jump to start!](#how-to-enabledisable-flags)

## Friend's Story
```stories share to your friends story```<br>
Your friends must support the feature too<br>
Not to be confused with the [shared lists](#🆕shared-lists-in-stories) or the [multiple close friends lists](#multiple-close-friends-lists).
<br>[Jump to start!](#how-to-enabledisable-flags)

## 60 second stories
```stories video trimmer```<br>
Make sure that this option removes the sharing options of some reels in newer versions.<br>
```stories originality reel reshares```
<br>[Jump to start!](#how-to-enabledisable-flags)

## Share profile to stories
```share profile to stories```
<br>[Jump to start!](#how-to-enabledisable-flags)

## Post directly to highlights
```profile post story directly to highlights```<br>
Not working for now
<br>[Jump to start!](#how-to-enabledisable-flags)

## Convert close friends to regular story
```close friends to regular story```<br>
Switch story to regular one from close friends
<br>[Jump to start!](#how-to-enabledisable-flags)

## Group mention in stories
```new group mentions```<br>
Enables tagging multiple users.
<br>[Jump to start!](#how-to-enabledisable-flags)

## Filled bar story reply box
```stories modernization```<br>
When watching a story, a filled bar is shown instead of an outlined bar.
<br>[Jump to start!](#how-to-enabledisable-flags)

## Custom emoji reaction
```custom eqr picker```<br>
Lets you choose more than the preselected emojis to react to a story.
<br>[Jump to start!](#how-to-enabledisable-flags)

## More avatar reactions
```avatars aqrv3```<br>
Lets you choose more than the preselected avatars to react to a story.
<br>[Jump to start!](#how-to-enabledisable-flags)

## Spotify share
```stories spotify audio reshare```
<br>[Jump to start!](#how-to-enabledisable-flags)

## Zoom stories
```stories pinch to zoom```<br>
Enables zooming on stories by pinching it.
<br>[Jump to start!](#how-to-enabledisable-flags)

## Generative AI in the stories editor
```genai magic mod```<br>
Region locked at the moment
<br>[Jump to start!](#how-to-enabledisable-flags)

# Camera
## Music button in Stories creation
```stories music in postcap toolbar is enabled```
<br>[Jump to start!](#how-to-enabledisable-flags)

## Show the Music button first in Stories creation
```stories music in postcap toolbar show music first```
<br>[Jump to start!](#how-to-enabledisable-flags)

## Organised toolbar in Stories creation
- ```stories music in postcap toolbar show effects in overflow```
- ```stories music in postcap toolbar show text in overflow```
<br>[Jump to start!](#how-to-enabledisable-flags)

## New fonts
camera android reels text expansion
<br>[Jump to start!](#how-to-enabledisable-flags)

## New options in media selection
```stories destination toolbar```<br>
Adds Camera, Drafts, Photos and Videos sections on media selection.
<br>[Jump to start!](#how-to-enabledisable-flags)

## 🆕Photos and Videos categories in media selection
```feed gallery revamp```<br>
Don't enable ```camera disabled```<br>
Removed in newer versions
<br>[Jump to start!](#how-to-enabledisable-flags)

## 🆕Audio and Trending options in reel media selection
```camera android reels gallery audio```
<br>[Jump to start!](#how-to-enabledisable-flags)

## 🆕Draft counts
```camera android reels destination bar draft is draft count enabled```
<br>[Jump to start!](#how-to-enabledisable-flags)

## 🆕Duplicate reel drafts
```clips duplicate drafts```
<br>[Jump to start!](#how-to-enabledisable-flags)

## 🆕Restore reel drafts that you have deleted
```camera android draft backup manual restore```
<br>[Jump to start!](#how-to-enabledisable-flags)

## 🆕Suggested albums
```gallery smart albums```
<br>[Jump to start!](#how-to-enabledisable-flags)

## 🆕Zoom and unzoom the photos row in media selection
```camera android reels gallery zoom```<br>
Set the min and the max span values to whatever values you want (min for zooming in and max for zooming out, bigger values in max will cause the app to lag when zooming out).
<br>[Jump to start!](#how-to-enabledisable-flags)

## Boomerang on reel creation
```camera reels boomerang```
<br>[Jump to start!](#how-to-enabledisable-flags)

## Better organisation of the sidebar
```igrp android ar sidebar```<br>
This will hide the extra options in an arrow button, which will show them to you when you press on it.
<br>[Jump to start!](#how-to-enabledisable-flags)

## 🆕Better use of the gesture controls
```gesture control improved experience```
<br>[Jump to start!](#how-to-enabledisable-flags)

## Useful options as circles on reel recording
```camera platform utility toolbar```
<br>[Jump to start!](#how-to-enabledisable-flags)

## Preview of the media while holding in Reels picker
```reels long press gallery```<br>
It also has a Select button if you still want to select multiple media.
<br>[Jump to start!](#how-to-enabledisable-flags)

## 🆕Rename the Edit video button to Edit timing on the reel editor
```camera android post capture edit video renaming```
<br>[Jump to start!](#how-to-enabledisable-flags)

# Direct
## Notes
- Enable the notes feature to your account

  - ```cf hub```
    Set hub layout type to ONE_ROW_POGS_2

- Increase the character limit of notes

  - ```max notes length```
    Default: 60<br>
    Max: 300

- Music in notes

  - ```music notes```
    Keep ```is text required for sharing``` disabled<br>
    If you can't post music notes without text disable ```text variants in music note require text```.

- Location notes

  - ```location notes```
    Keep ```is text required for sharing``` disabled.

- Videos in notes

  - ```notes profile video```
- Photos in notes
  - ```is photo capture enabled```
- Questions & Answers

  - ```notes prompts```
    No preview until stable release<br>
- Chat notes

  - ```note chat```
    The people who reply in your note will be added on a temporary group chat with you for 24 hours.
- Enable lives in notes

  - ```live notes```

- Enable voice recordings in notes

  - ```audio notes config```
    Keep disabled ```internal only```

- Enable audio and media replies

  - ```notes replies```
    Keep ```hide audio reply for audio notes``` disabled<br>
    Optional enabling ```should expose on inbox open```
- Enable sticker replies

  - ```notes sticker replies```
- Happy New Year confetti, Valentine's Day and Birthday animations

  - ```notes visual effects```<br>
- Translate notes

  - ```see translation notes```

- Post note for followers, following or close friends

  - ```notes audience expansion```
- Open profile when pressing it

  - ```notes profile pic tap reply sheet```
- Send notes as ampersand

  - ```group notes```
- Show notes in profile

  - ```notes on profile```
    This might cause crashes
- Enable tap profile to open user story

  - ```stories in notes```
    This will make the note texts go to the right
- React to notes

  - ```content notes```
    Keep disabled ```content notes is direct likes enabled```<br>
    Keep disabled ```content notes is lightweight feedback enabled```<br>
    Keep disabled ```content notes is phase 1 enabled```<br>
    Keep disabled ```content notes is phase I notes likes enabled```<br>
  - ```notes lightweight feedback```
    Keep disabled ```notes lightweight feedback likes only enabled```<br>
    Reactions removed in newer versions, only the likes are working
- Must not<br>
  Don't enable this, otherwise you wont be able to reply to notes

  - ```send share manager v2 enable notes reply```
<br>[Jump to start!](#how-to-enabledisable-flags)

## Map bubble next to notes creation
```nsx nearby places```<br>
Make sure you have your location enabled while having this active or Instagram will crash when going to Direct.
<br>[Jump to start!](#how-to-enabledisable-flags)

## Vanish mode
```direct vanish mode```<br>
```direct vanish mode intro qp```<br>
```direct vanish mode message replay```<br>
Send messages as "ephemeral" or "one time view"

Photo/Animation preview pending<br>
Removed since 327 and later
<br>[Jump to start!](#how-to-enabledisable-flags)

## Quiet mode
```quiet mode```<br>
Just like the 'pause all' notifications option in Instagram settings, the quiet mode will disable all types of notifications at a certain time and you can set when it will turn on and off automatically.

```quiet mode x plat```<br>
Improve the "Quiet mode" feature by adding the ability to choose which days to activate this mode.
<br>[Jump to start!](#how-to-enabledisable-flags)

## Chat translations
```igd android thread translation is enabled```<br>
attention!!! not working in all chats, i don't know how instagram chose it but if you see a banner in a chat to translate this chat it means you can activate this feature in this chat from the chat details, if not then you cannot activate it in any other way.

Not working on my side yet
<br>[Jump to start!](#how-to-enabledisable-flags)

## Resize preview of shared reels
```clips direct reshare size```<br>
Default: 164<br>
Max: 300

Animation preview pending
<br>[Jump to start!](#how-to-enabledisable-flags)

## Autoplay preview of shared reels
```full autoplay enabled```
<br>[Jump to start!](#how-to-enabledisable-flags)

## Sent reel indicator on chat previews
```reels consumption v2```
<br>[Jump to start!](#how-to-enabledisable-flags)

## Forward button
- Messages forwarding

  - ```direct forwarding```
- Reels forward button
  - Old versions:
    - ```reels direct message forwarding```<br>
  - Newer versions:
    - ```igd open reels forwarding```
Photo preview pending
<br>[Jump to start!](#how-to-enabledisable-flags)

## Favourite stickers
```igd android favorite sticker```<br>
You can favorite stickers and find them quickly in one place.
<br>[Jump to start!](#how-to-enabledisable-flags)

## GIF and sticker forwarding
```igd armadillo gifs stickers forwarding```
<br>[Jump to start!](#how-to-enabledisable-flags)

## Pong game while pressing an emoji in Direct
```studio emoji pong easter game```
<br>[Jump to start!](#how-to-enabledisable-flags)

## New layout of chat details
```direct thread details redesign```<br>
Keep disabled ```show privacy buttons on main page```<br>
Keep disabled ```use alternate privacy icon```<br>
<br>[Jump to start!](#how-to-enabledisable-flags)

## More options on the Privacy and Safety section in group chats
```direct android group privacy and safety```
<br>[Jump to start!](#how-to-enabledisable-flags)

## Create a group chat through DMs
```group from thread```
<br>[Jump to start!](#how-to-enabledisable-flags)

## Mute chat within XX hours
```thread time muting```<br>
Keep disabled ```has debug time option```
<br>[Jump to start!](#how-to-enabledisable-flags)

## Remove calls tab & camera button
- Old:
  - ```remove calls tab entrypoint```
  - ```remove inbox camera entrypoint```
- New:
  - ```enable inbox directory inbox navigation bar entry point```<br>
The new one replaces the calls and camera buttons with a new button that shows you the broadcast channels you are invited to.

Animation preview pending
<br>[Jump to start!](#how-to-enabledisable-flags)

## Redesign of the new group chat screen
```direct group creation improvements```<br>
<br>[Jump to start!](#how-to-enabledisable-flags)

## Long press to change chat theme
```long press to theme picker```
<br>[Jump to start!](#how-to-enabledisable-flags)

## Enable gyroscopic themes
```igd android gyroscopic themes```

Removed in newer versions
<br>[Jump to start!](#how-to-enabledisable-flags)

## Theme picker redesign
```igd new themes```
<br>[Jump to start!](#how-to-enabledisable-flags)

## Swipe to open chat details
```swipe to thread details```<br>
Removed in 317.0.0.0.78
<br>[Jump to start!](#how-to-enabledisable-flags)

## Animated avatar stickers
```igd animated avatar stickers```
<br>[Jump to start!](#how-to-enabledisable-flags)

## Smaller size of avatars in Direct
```igd avatar tray improvements```<br>
Decrease the size of the avatars in Direct, showing more avatar options at once.
<br>[Jump to start!](#how-to-enabledisable-flags)

## Smaller size of stickers in Direct
```igd sticker tray improvements```<br>
Decrease the size of the stickers in Direct, showing more stickers at once.
<br>[Jump to start!](#how-to-enabledisable-flags)

## GIF categories
```igd gif categories```
<br>[Jump to start!](#how-to-enabledisable-flags)

## New layout of long press menu
```igd long press message action```
<br>[Jump to start!](#how-to-enabledisable-flags)

## Create Images with AI
```imagine create```<br>
```direct ai agents eligibility``` = 3<br>
Make sure to have enabled [the dropdown menu](#enable-dropdown-menu).

Animation preview pending
<br>[Jump to start!](#how-to-enabledisable-flags)

## Enable dropdown menu
```direct composer overflow is composer```
<br>[Jump to start!](#how-to-enabledisable-flags)

## Location Sharing
```location share xma```<br>
```location sharing```<br>
Make sure to have enabled [the dropdown menu](#enable-dropdown-menu).<br>
Removed in newer versions
<br>[Jump to start!](#how-to-enabledisable-flags)

## Avatar powerups
```avatar powerups```<br>
Animation preview pending
<br>[Jump to start!](#how-to-enabledisable-flags)

## Fix GIFs and stickers not showing on the powerups section
```gifs stickers shortcut disabled```
<br>[Jump to start!](#how-to-enabledisable-flags)

## Pin chats
New versions<br>
```igd android pin threads```
Old versions<br>
```thread pinning```
<br>[Jump to start!](#how-to-enabledisable-flags)

## Edit messages
```igd android edit message```<br>
Photo/Animation preview pending
<br>[Jump to start!](#how-to-enabledisable-flags)

## Disable read receipts
```igd read receipt control is enabled for open```<br>
Enables an option inside each user direct details panel to disable seen states.
<br>[Jump to start!](#how-to-enabledisable-flags)

## Disable typing indicator
```typing indicator control```
<br>[Jump to start!](#how-to-enabledisable-flags)

## New modern design of the "send" button in a chat/note reply/comment composer
```smashable send```
<br>[Jump to start!](#how-to-enabledisable-flags)

## Group invites
```igd android groups invites```
<br>[Jump to start!](#how-to-enabledisable-flags)

## Voice messages
- 10m voice messages

  - ```voice msg improvements length increase 10 min```
- Playing out of chat

  - ```igd voice msg out of chat playback```

- Playback speed

  - ```voice msg improvements playback speed enabled```

- Timer

  - ```add audio message timer```

- Scrubber

  - ```voice msg improvements scrubbing handle enabled```

- Listened state

  - ```voice msg improvements listened state styling enabled```<br>
  - Make sure it can cause crashes while listening to a voice message out of the chat.
<br>[Jump to start!](#how-to-enabledisable-flags)

## In chat search
```in thread content search```<br>
Removed in newer versions
<br>[Jump to start!](#how-to-enabledisable-flags)

## Change the group photo
Old versions:<br>
```direct group photo customization```<br>
Lets you to change the photo of a group chat.<br>
🆕New versions:<br>
```igd change group photo```<br>
Lets you use an emoji as a group chat photo.
<br>[Jump to start!](#how-to-enabledisable-flags)

## Threshold for displaying the number of unread messages
```snapshot messages per thread count```
<br>[Jump to start!](#how-to-enabledisable-flags)

## Chat with AI
```direct ai agents```<br>
```direct ai agents eligibility``` = 3<br>
Not released in Europe (pending launch).
<br>[Jump to start!](#how-to-enabledisable-flags)

## Disable swipe to direct
```should disable swipe to direct```
<br>[Jump to start!](#how-to-enabledisable-flags)

## Media stacks enabled
```direct media stacks enabled```
<br>[Jump to start!](#how-to-enabledisable-flags)

## Media previews before sending
```igd android media preview```<br>
Lets you to preview a line of selected photos, and if you do not have any selected and press one, you will be able to edit the photo.

Make sure to disable it if you're not okay with the aspect ratio modification

Photo preview pending
<br>[Jump to start!](#how-to-enabledisable-flags)

## Avatar Animation
Avatar Animation while reacting to a message

```avatar reactions```<br>
Animation preview pending
<br>[Jump to start!](#how-to-enabledisable-flags)

## Non text replies
Enable replies with photos, videos, audios, etc

```igd non text replies```<br>
Photo preview pending
<br>[Jump to start!](#how-to-enabledisable-flags)

## Reply to links
```direct link replies```
<br>[Jump to start!](#how-to-enabledisable-flags)

## Show avatars in star tab
```igd avatar growth```<br>
Photo preview pending
<br>[Jump to start!](#how-to-enabledisable-flags)

## Set star tab to avatars
```android avatars quick reactions direct receive```<br>
Photo preview pending
<br>[Jump to start!](#how-to-enabledisable-flags)

## Seen states
```direct seen states in inbox```<br>
Show how long the user has read your message instead of "Seen" only

Photo preview pending
<br>[Jump to start!](#how-to-enabledisable-flags)

## AI Message replies
```creator agents suggested replies```
<br>[Jump to start!](#how-to-enabledisable-flags)

## Avatar reactions
```ig4a avatar reactions```<br>
Adds an avatar to the red heart like animation

Animation preview pending
<br>[Jump to start!](#how-to-enabledisable-flags)

## Delete messages for you
```igd android delete message```<br>
Removed in 317.0.0.0.41
<br>[Jump to start!](#how-to-enabledisable-flags)

## Rename the Delete button to Unsend and get a new icon
```igd delete messages```
<br>[Jump to start!](#how-to-enabledisable-flags)

## Collab collections
```nsx collab collections```<br>
Adds a saved button to the left or right of the reel inside direct to add it to the direct chat saved collection.
<br>[Jump to start!](#how-to-enabledisable-flags)

## Reply box on sent reels
```reels consumption v1```<br>
Show reply box when you open a reel that was sent to you<br>
Disable if different reels start showing instead of the original one in chats.
<br>[Jump to start!](#how-to-enabledisable-flags)

## Tap to react
```direct reactions gating```<br>
Disable this toggle to switch off double tap reactions in your DMs.
<br>[Jump to start!](#how-to-enabledisable-flags)

## Silent share
```send control```<br>
Ability to share a post/video without notifying the user.
<br>[Jump to start!](#how-to-enabledisable-flags)

## Roll call
```roll call```<br>
Enable everything except ```composer entry sticker sheet enabled```<br>
Enable roll call, where you can post a photo and the others can reply with another one, with all that lasting for 24 hours.<br>
Removed in 324.0.0.0.4
<br>[Jump to start!](#how-to-enabledisable-flags)

## Birthday
```ig4a birthday opt in```
<br>[Jump to start!](#how-to-enabledisable-flags)

## Leave silently from group chats
```igd leave silently```<br>
Not working yet
<br>[Jump to start!](#how-to-enabledisable-flags)

## 🆕Select button in the gallery in Direct
```gallery select button enabled```
<br>[Jump to start!](#how-to-enabledisable-flags)

## 🆕Call settings
```incall settings```<br>
Get two call optimisation options while calling someone.
<br>[Jump to start!](#how-to-enabledisable-flags)

## 🆕Replace the Following button to Message on the fmembers list of a group chat
```direct thread details message entrypoints```
<br>[Jump to start!](#how-to-enabledisable-flags)

# Profile
## Highlights design
```japan labs my week is edit header enable```
Enable a new edit button over your profile highlights, you can enable some settings

## My week
```japan labs my week is enabled```<br>
```japan labs my week is settings action sheet entry point enabled```<br>
```japan labs my week is share enabled```<br>
Enables a My week highlight to post stories about how your week is going.

Pending photo preview
<br>[Jump to start!](#how-to-enabledisable-flags)

## Highlights tray as cards
Older versions:
```highlights tray as cards```
New versions:
```japan labs my week is cards layout enabled```<br>
Make sure to have [the highlights design enabled](#highlights-design).

Photo preview pending
<br>[Jump to start!](#how-to-enabledisable-flags)

## Flipside
```opal v1```<br>
Enable everything except:
- ```is profile ptr disabled```<br>
Not available for all accounts, probably region locked
<br>[Jump to start!](#how-to-enabledisable-flags)

## Highlights grid
```profile highlights click into grid```<br>
Photo preview pending
<br>[Jump to start!](#how-to-enabledisable-flags)

## Highlights scrollable media preview
```expression highlights improvements highlights```<br>
Animation preview pending
<br>[Jump to start!](#how-to-enabledisable-flags)

## Schedule posts
```content scheduling```<br>
This feature is only available for professional accounts.

I do not have a perofessional account
<br>[Jump to start!](#how-to-enabledisable-flags)

## Insights for all accounts
```ig4a insights for public```
<br>[Jump to start!](#how-to-enabledisable-flags)

## Reels pinning
```clips reels pinning```
<br>[Jump to start!](#how-to-enabledisable-flags)

## Show your other account in your username
```mimicry```<br>
Photo preview pending
<br>[Jump to start!](#how-to-enabledisable-flags)

## Remove suggested accounts
```self profile chaining enabled```
<br>[Jump to start!](#how-to-enabledisable-flags)

## New "Create" icon
```is profile creation button icon swap```
<br>[Jump to start!](#how-to-enabledisable-flags)

## Show IGTV section
```consumption merge profile video tabs```<br>
This option should be enabled in your account, it combines the igtv section to the reels section into one section on the profile tab, disable it if you want to get that IGTV section back.
<br>[Jump to start!](#how-to-enabledisable-flags)

## Just seen
```profile just watched```<br>
Enables a message when entering the profile of a post from the feed.

Photo preview pending
<br>[Jump to start!](#how-to-enabledisable-flags)

## Profile Interests
```bio interests```<br>
Not working yet<br>
Animation preview pending
<br>[Jump to start!](#how-to-enabledisable-flags)

## Pin your broadcast chat/social channel to your profile
```direct pin chat to profile```<br>
Can't test it properly because I do not have a broadcast chat/social channel.
<br>[Jump to start!](#how-to-enabledisable-flags)

## Saved subtab in Profile
```saved subtab on profile is enabled```<br>
This tab wont load if you have ```public collections``` enabled

Animation preview pending
<br>[Jump to start!](#how-to-enabledisable-flags)

## New header design
```profile header daisy```<br>
Removed in version 310.0.0.0.192
<br>[Jump to start!](#how-to-enabledisable-flags)

## Mutuals button in the header
```profile stat row improvements```<br>
Don't enable ```posts disabled```
<br>[Jump to start!](#how-to-enabledisable-flags)

## New private account screen
```profile public highlights```
<br>[Jump to start!](#how-to-enabledisable-flags)

## "Threads" button added to profile header tab
```is ig to p92 app switcher enabled android```
<br>[Jump to start!](#how-to-enabledisable-flags)

## Avatar as profile picture
```is coin flip ssr enabled```
<br>[Jump to start!](#how-to-enabledisable-flags)

## Wall notes
```profile wall notes```<br>
Your followers can add Notes to your profile<br>
It stays on your profile for up to 3 days<br>
You can choose to remove any notes added by your followers<br>
Not working for now
<br>[Jump to start!](#how-to-enabledisable-flags)

## Remove highlights in profile
```stories archive negative holdout```
<br>[Jump to start!](#how-to-enabledisable-flags)

## Compare activity
```shared activity```<br>
It is a feature that shows some information between your profile and someone else's.
<br>[Jump to start!](#how-to-enabledisable-flags)

## External sharing
- ```can download nametag image mode pdf```
- ```has app tray tooltip nux```
- ```has download button on self qr page```
- ```has external share in overflow```
- ```has nametag redesign```
- ```has nametag gradients```
- ```has reshare promt after screenshot```
- ```has share button on profile```
- ```has share button on profile android```
- ```has share in expandable profile view```
- ```is external share option minimized```
- ```is promt cta of icon style```
- ```is utm qr enabled```
- ```qr redesign on profile enabled```
- ```qr sharing download button enabled```
- ```test uss with other sharesheet test```
- ```sue bussiness copy for qr entrypoints```<br>
Removed in newer versions
<br>[Jump to start!](#how-to-enabledisable-flags)

## Zoom people's profile icons
```profile pfp zoom```
<br>[Jump to start!](#how-to-enabledisable-flags)

# Livestreams
## More audience options on live creation
```live android invite only```
<br>[Jump to start!](#how-to-enabledisable-flags)

## Share media with your audience in livestreams
```live media picker```<br>
Not working yet as it causes crashes.
<br>[Jump to start!](#how-to-enabledisable-flags)

## Games in livestreams
```live android games```
<br>[Jump to start!](#how-to-enabledisable-flags)

# Calls
## Backgrounds in video calls
```rtc solo backgrounds```
<br>[Jump to start!](#how-to-enabledisable-flags)

# Professional/Creator accounts
## Welcome message
```welcome message```<br>
Either it's not working yet or I'm using it wrong.
<br>[Jump to start!](#how-to-enabledisable-flags)

# Fixes
## Fix all the hints showing even if they are already seen
```reuse sharedprefs editor```
<br>[Jump to start!](#how-to-enabledisable-flags)

## Fix the confetti animation showing in every note
```notes birthday v2 activation enabled```<br>
Disable it
<br>[Jump to start!](#how-to-enabledisable-flags)

## Fix the huge gap in Direct when the Direct tab is on the bottom bar
```is extended scrollaway nav enabled for feed```
<br>[Jump to start!](#how-to-enabledisable-flags)

## 🆕Fix music not playing in notes
```quick reply sheet mvvm migration enabled```
<br>[Jump to start!](#how-to-enabledisable-flags)

## Fix not being able to record videos for stories
```cameracore fbaudio ig enable state machine```
<br>[Jump to start!](#how-to-enabledisable-flags)

## 🆕Fix not being able to take photos for stories
```enable sensor pixel mode maximum resolution```
<br>[Jump to start!](#how-to-enabledisable-flags)

## 🆕Fix not being able to take photos with effects for your story
```andriod ar engine```
<br>[Jump to start!](#how-to-enabledisable-flags)

## 🆕Fix the story editor crashing when taking a photo
```sticker anything dark test```<br>
Only crashes in some versions (311 only known currently).
<br>[Jump to start!](#how-to-enabledisable-flags)

## 🆕Fix the carousel post editor crashing
```reels creation dark mode```
<br>[Jump to start!](#how-to-enabledisable-flags)

## 🆕Fix the post gallery crashing
```camera android reels text expansion enable new fonts stories```
<br>[Jump to start!](#how-to-enabledisable-flags)
 
## Fix the loud audio distortion and the image glitches when recording a video for stories / not being able to record videos for stories (for older bases)
```cameracore fbaudio ig use pcm float```
<br>[Jump to start!](#how-to-enabledisable-flags)

## Fix low light mode being always enabled
```low light mode capture is enabled```
<br>[Jump to start!](#how-to-enabledisable-flags)

## Fix the chats not loading after switching accounts
```ig4a direct inbox streaming```
<br>[Jump to start!](#how-to-enabledisable-flags)

## Fix the chats crashing in Direct
```direct xma mi migration```<br>
Or (for newer versions):
```igd android voice msg transcription```
<br>[Jump to start!](#how-to-enabledisable-flags)

## 🆕Fix the Direct tab crashing
```is get notes enabled```
<br>[Jump to start!](#how-to-enabledisable-flags)

## Fix the notification tab crashing
```ptr spinner is enabled in newsfeed you```
<br>[Jump to start!](#how-to-enabledisable-flags)

## Fix the muted audio in stories
```segment enabled story raven```
Fixed in newer versions
<br>[Jump to start!](#how-to-enabledisable-flags)

## Fix Avatar options not showing in Direct
```avatars longterm holdout 2023```<br>
Disable everything to fix the Avatar tab not showing in chats.
<br>[Jump to start!](#how-to-enabledisable-flags)

## 🆕Fix recommended users always showing up when adding a text in the Stories editor
```stories group mention```
<br>[Jump to start!](#how-to-enabledisable-flags)

## 🆕Fix the audio page crashing
```audio page layout ap layout enabled```
<br>[Jump to start!](#how-to-enabledisable-flags)

## 🆕Fix like and comment counts not showing in Reels
- ```android viewer disable comment count```
- ```android viewer disable like count```
- ```disable viewer like count```
- ```ios disable viewer comment count```
<br>[Jump to start!](#how-to-enabledisable-flags)

## 🆕Fix the text you add in the Reels editor being placed 0.5s ahead of where you put it
```camera android reels stacked timeline add things```
<br>[Jump to start!](#how-to-enabledisable-flags)

## 🆕Fix the Reels lagging
```clips playback tests```
<br>[Jump to start!](#how-to-enabledisable-flags)

## 🆕Fix the "The reel is unavailable." errors
```clips friendly viewer is floaty follows enabled```
<br>[Jump to start!](#how-to-enabledisable-flags)

## Fix not being able to press anything on the media picker in stories
```gallery modularization```<br>
Disable everything
<br>[Jump to start!](#how-to-enabledisable-flags)

## Fix crashes when opening Your Story
```stories quick captions v2```<br>
This disables the "Add a caption" feature completely, which causes crashes when adding a caption.
<br>[Jump to start!](#how-to-enabledisable-flags)

## Fix the weirdly streched reels
```av1 playback```<br>
Disable everything
<br>[Jump to start!](#how-to-enabledisable-flags)

## 🆕Fix some green boxes showing while watching reels
```reels swipe to action enable swipe debug visualizer```<br>
Removed in newer versions
<br>[Jump to start!](#how-to-enabledisable-flags)

## 🆕Fix the stories crashing
- ```stories ads toolbar```
- ```stories should launch viewer as modal```
<br>[Jump to start!](#how-to-enabledisable-flags)

## Bring back the filters in Stories creation
- ```ig4a effect filtering migration```
- ```stories attributions separate camera tools enabled```
<br>[Jump to start!](#how-to-enabledisable-flags)

## 🆕Fix not being able to navigate in the Camera
```fix folder selector inflate crash```
<br>[Jump to start!](#how-to-enabledisable-flags)

## 🆕Fix the gallery picker in Direct crashing
```view mode selector enabled```
<br>[Jump to start!](#how-to-enabledisable-flags)

## 🆕Fix the status bar being white while watching reels
```status nav bar api update```
<br>[Jump to start!](#how-to-enabledisable-flags)

## 🆕Fix the Mute options not showing
```enable prism alert dialog```
<br>[Jump to start!](#how-to-enabledisable-flags)

## 🆕Fix not being able to swipe to the feed while being on the chats list in Direct
```source logging disabled```
<br>[Jump to start!](#how-to-enabledisable-flags)

## Fix the post editing section always being in HDR
```enable jpegr feed photo edit surface view```<br>
Disable it
<br>[Jump to start!](#how-to-enabledisable-flags)

## Fix the story editor always being in HDR
```enable jpegr feed photo edit surface view```<br>
Disable it
<br>[Jump to start!](#how-to-enabledisable-flags)

## 🆕Fix the avatar reactions not showing on the reaction sheet in Stories
```avatars longterm holdout 2023```
<br>[Jump to start!](#how-to-enabledisable-flags)

## 🆕Fix the avatar reactions not loading on the reaction sheet in Stories
- ```avatars vpr in quick reactions```
- ```avatars android aqr media type```
<br>[Jump to start!](#how-to-enabledisable-flags)

## Fix shared reels always being big
```rocket replies use large xma```
<br>[Jump to start!](#how-to-enabledisable-flags)
