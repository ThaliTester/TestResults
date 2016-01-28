#### Test 573480789efee08_thali05_samsung-SM-G800H Logs


```
--------- beginning of /dev/log/main
D/GalaxyFinderApplication( 4426): [Slink platform] Version = 29011
D/GalaxyFinderApplication( 4426): [Slink platform] use state of slink location service is [false] to [true]
I/SELinux ( 4445): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 4445):  
,--------- beginning of /dev/log/system
I/ActivityManager(  723): Killing 3114:com.LocalFota/u0a110 (adj 15): empty #43
I/SELinux ( 4445): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 4445):  
I/SELinux ( 4445):  
I/SELinux ( 4445): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 4445): [DEBUG] seapp_context_lookup: seinfoCategory = release
E/dalvikvm( 4445): >>>>> Normal User
E/dalvikvm( 4445): >>>>> com.sec.android.app.shealth [ userId:0 | appId:10035 ]
E/SELinux ( 4445): [DEBUG] seapp_context_lookup: seinfoCategory = release
D/TimaKeyStoreProvider( 4445): in addTimaSignatureService
D/TimaKeyStoreProvider( 4445): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 4445): Added TimaKesytore provider
V/AlarmManager(  723): waitForAlarm result :4
V/AlarmManager(  723): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
D/BatteryService(  723): level:100, scale:100, status:5, health:2, present:true, voltage: 4366, temperature: 283, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:16, charge type:1, power sharing:false
D/BatteryService(  723): Sending ACTION_BATTERY_CHANGED.
D/BatteryService(  723): stay LED for fully charged
D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
D/UiModeManager(  723): mCoverManager.getCoverState() : true
W/ActivityManager(  723): Permission Denial: getCurrentUser() from pid=4445, uid=10035 requires android.permission.INTERACT_ACROSS_USERS
E/SMD     (  240): DCD OFF
D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
W/ContextImpl( 4445): Implicit intents with startService are not safe: Intent { act=com.sec.android.service.health.cp.accesscontrol } android.content.ContextWrapper.bindService:529 com.samsung.android.sdk.health.content.ShealthAccessControl.startService:274 com.samsung.android.sdk.health.content.ShealthAccessControl.requestPermission:212 
D/STATUSBAR-IconMerger( 1066): checkOverflow(384), More:false, Req:false Child:2
I/SELinux ( 4471): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 4471):  
D/SSRMv2:SIOP(  723): SIOP:: AP = 310, Delta = 0
E/Device Type Shared Preferences( 4445): Device Type Shared Preferences - getDeviceTypeChecked -true
E/Device Type Shared Preferences( 4445): Device Type Shared Preferences - not connecting to service
E/com.sec.android.app.shealth.SHealthApplication( 4445): ContentProvider is not null
I/SELinux ( 4471): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 4471):  
I/SELinux ( 4471):  
I/SELinux ( 4471): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 4471): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 4471): >>>>> Normal User
E/dalvikvm( 4471): >>>>> com.sec.android.service.health [ userId:0 | appId:10016 ]
E/SELinux ( 4471): [DEBUG] seapp_context_lookup: seinfoCategory = platform
D/TimaKeyStoreProvider( 4471): in addTimaSignatureService
D/TimaKeyStoreProvider( 4471): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 4471): Added TimaKesytore provider
V/MediaPlayer( 4445): decode(61, 33979084, 48105)
V/MediaPlayerService(  249): decode(35, 33979084, 48105)
V/MediaPlayerService(  249): player type = 3
V/AwesomePlayer(  249): setDefault
V/AwesomePlayer(  249): constructor
V/AwesomePlayer(  249): setDefault
V/AwesomePlayer(  249): reset_l()
V/AwesomePlayer(  249): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  249): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  249): mAudioTrackVector clear
V/AwesomePlayer(  249): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  249): mSecMediaClock clear
V/StagefrightPlayer(  249): StagefrightPlayer
V/AwesomePlayer(  249): setListener
V/StagefrightPlayer(  249): initCheck
V/AwesomePlayer(  249): setAudioSink
V/StagefrightPlayer(  249): setDataSource(35, 33979084, 48105)
V/AwesomePlayer(  249): reset_l()
V/AwesomePlayer(  249): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  249): notify(0xb8837388, 8, 0, 0)
V/AudioCache(  249): ignored
V/AwesomePlayer(  249): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  249): mAudioTrackVector clear
V/AwesomePlayer(  249): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  249): mSecMediaClock clear
V/AwesomePlayer(  249): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer(  249): mBitrate = -1 bits/sec
V/AwesomePlayer(  249): current audio track index (0) is added to vector
V/AwesomePlayer(  249): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer(  249): AwesomePlayer::setDataSource_l():: This is not a DRM content
V/MediaPlayerService(  249): prepare
V/AwesomePlayer(  249): prepareAsync
V/MediaPlayerService(  249): wait for prepare
V/AwesomePlayer(  249): onPrepareAsyncEvent
I/SecMediaClock(  249): SecMediaClock constructor
I/SecMediaClock(  249): reset
V/AwesomePlayer(  249): initAudioDecoder
V/AwesomePlayer(  249): checkOffloadExceptions is true
I/OMXCodec(  249): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
I/OMX     (  249): mDispatchers.add
I/OMXCodec(  249): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec(  249): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec(  249): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec(  249): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/OMXCodec(  249): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer(  249): finishAsyncPrepare_l
V/AwesomePlayer(  249): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache(  249): notify(0xb8837388, 200, 973, 0)
V/AudioCache(  249): ignored
V/AwesomePlayer(  249): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  249): notify(0xb8837388, 5, 0, 0)
V/AudioCache(  249): ignored
V/AwesomePlayer(  249): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  249): notify(0xb8837388, 1, 0, 0)
V/AudioCache(  249): prepared
V/AudioCache(  249): wait - success
V/MediaPlayerService(  249): start
V/StagefrightPlayer(  249): start
V/AwesomePlayer(  249): play
V/AwesomePlayer(  249): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer(  249): startAudioPlayer_l, sendErrorNotification (0)
I/OMXCodec(  249): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec(  249): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec(  249): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/AudioPlayer(  249):  Audioplayer kKeyAudioPCMFormat:1, 2, 0
I/AudioPlayer(  249):  Audioplayer kKeyAudioPCMFormat read fail(2, 1)
V/AudioCache(  249): open(44100, 2, 0x0, 1, 4)
V/AwesomePlayer(  249): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache(  249): notify(0xb8837388, 6, 0, 0)
V/AudioCache(  249): ignored
V/AwesomePlayer(  249): addBatteryData
V/MediaPlayerService(  249): wait for playback complete
I/OMXCodec(  249): [OMX.google.vorbis.decoder] End Of Stream
V/AwesomePlayer(  249): postAudioEOS delayUs (0)
V/AwesomePlayer(  249): onCheckAudioStatus
V/AwesomePlayer(  249): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  249): onStreamDone
V/AwesomePlayer(  249): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  249): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  249): notify(0xb8837388, 2, 0, 0)
V/AudioCache(  249): playback complete - thread will wake up later
V/AwesomePlayer(  249): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  249): notify(0xb8837388, 7, 0, 0)
V/AudioCache(  249): ignored
V/AwesomePlayer(  249): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer(  249): addBatteryData
V/AudioCache(  249): wait - success
V/StagefrightPlayer(  249): reset
V/AwesomePlayer(  249): reset_l()
V/AwesomePlayer(  249): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  249): notify(0xb8837388, 8, 0, 0)
V/AudioCache(  249): ignored
V/AwesomePlayer(  249): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  249): mAudioTrackVector clear
I/OMXCodec(  249): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec(  249): [OMX.google.vorbis.decoder] stop() sendCommand(0x37, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec(  249): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
I/OMXCodec(  249): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/OMX     (  249): instance freeNode
I/AudioPlayer(  249): reset out
V/AwesomePlayer(  249): reset_l() mAudioPlayer successfully deleted
I/SecMediaClock(  249): SecMediaClock destructor
V/AwesomePlayer(  249): mSecMediaClock clear
V/StagefrightPlayer(  249): ~StagefrightPlayer
V/StagefrightPlayer(  249): reset
V/AwesomePlayer(  249): reset_l()
V/AwesomePlayer(  249): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  249): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  249): mAudioTrackVector clear
V/AwesomePlayer(  249): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  249): mSecMediaClock clear
V/AwesomePlayer(  249): destructor
V/AwesomePlayer(  249): reset_l()
V/AwesomePlayer(  249): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  249): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  249): mAudioTrackVector clear
V/AwesomePlayer(  249): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  249): mSecMediaClock clear
V/MediaPlayer( 4445): decode(63, 33914984, 10421)
V/MediaPlayerService(  249): decode(35, 33914984, 10421)
V/MediaPlayerService(  249): player type = 3
V/AwesomePlayer(  249): setDefault
V/AwesomePlayer(  249): constructor
V/AwesomePlayer(  249): setDefault
V/AwesomePlayer(  249): reset_l()
V/AwesomePlayer(  249): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  249): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  249): mAudioTrackVector clear
V/AwesomePlayer(  249): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  249): mSecMediaClock clear
V/StagefrightPlayer(  249): StagefrightPlayer
V/AwesomePlayer(  249): setListener
V/StagefrightPlayer(  249): initCheck
V/AwesomePlayer(  249): setAudioSink
V/StagefrightPlayer(  249): setDataSource(35, 33914984, 10421)
V/AwesomePlayer(  249): reset_l()
V/AwesomePlayer(  249): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  249): notify(0xb8838988, 8, 0, 0)
V/AudioCache(  249): ignored
V/AwesomePlayer(  249): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  249): mAudioTrackVector clear
V/AwesomePlayer(  249): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  249): mSecMediaClock clear
V/AwesomePlayer(  249): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer(  249): mBitrate = -1 bits/sec
V/AwesomePlayer(  249): current audio track index (0) is added to vector
V/AwesomePlayer(  249): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer(  249): AwesomePlayer::setDataSource_l():: This is not a DRM content
V/MediaPlayerService(  249): prepare
V/AwesomePlayer(  249): prepareAsync
V/MediaPlayerService(  249): wait for prepare
V/AwesomePlayer(  249): onPrepareAsyncEvent
I/SecMediaClock(  249): SecMediaClock constructor
I/SecMediaClock(  249): reset
V/AwesomePlayer(  249): initAudioDecoder
V/AwesomePlayer(  249): checkOffloadExceptions is true
I/OMXCodec(  249): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
I/OMX     (  249): mDispatchers.add
I/OMXCodec(  249): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec(  249): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec(  249): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec(  249): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/OMXCodec(  249): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer(  249): finishAsyncPrepare_l
V/AwesomePlayer(  249): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache(  249): notify(0xb8838988, 200, 973, 0)
V/AudioCache(  249): ignored
V/AwesomePlayer(  249): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  249): notify(0xb8838988, 5, 0, 0)
V/AudioCache(  249): ignored
V/AwesomePlayer(  249): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  249): notify(0xb8838988, 1, 0, 0)
V/AudioCache(  249): prepared
V/AudioCache(  249): wait - success
V/MediaPlayerService(  249): start
V/StagefrightPlayer(  249): start
V/AwesomePlayer(  249): play
V/AwesomePlayer(  249): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer(  249): startAudioPlayer_l, sendErrorNotification (0)
I/OMXCodec(  249): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec(  249): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec(  249): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/AudioPlayer(  249):  Audioplayer kKeyAudioPCMFormat:1, 2, 0
I/AudioPlayer(  249):  Audioplayer kKeyAudioPCMFormat read fail(2, 1)
V/AudioCache(  249): open(44100, 2, 0x0, 1, 4)
V/AwesomePlayer(  249): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache(  249): notify(0xb8838988, 6, 0, 0)
V/AudioCache(  249): ignored
V/AwesomePlayer(  249): addBatteryData
V/MediaPlayerService(  249): wait for playback complete
I/OMXCodec(  249): [OMX.google.vorbis.decoder] End Of Stream
V/AwesomePlayer(  249): postAudioEOS delayUs (0)
V/AwesomePlayer(  249): onCheckAudioStatus
V/AwesomePlayer(  249): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  249): onStreamDone
V/AwesomePlayer(  249): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  249): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  249): notify(0xb8838988, 2, 0, 0)
V/AudioCache(  249): playback complete - thread will wake up later
V/AwesomePlayer(  249): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  249): notify(0xb8838988, 7, 0, 0)
V/AudioCache(  249): ignored
V/AwesomePlayer(  249): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer(  249): addBatteryData
V/AudioCache(  249): wait - success
V/StagefrightPlayer(  249): reset
V/AwesomePlayer(  249): reset_l()
V/AwesomePlayer(  249): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  249): notify(0xb8838988, 8, 0, 0)
V/AudioCache(  249): ignored
V/AwesomePlayer(  249): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  249): mAudioTrackVector clear
I/OMXCodec(  249): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec(  249): [OMX.google.vorbis.decoder] stop() sendCommand(0x38, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec(  249): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
I/OMXCodec(  249): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/OMX     (  249): instance freeNode
I/AudioPlayer(  249): reset out
V/AwesomePlayer(  249): reset_l() mAudioPlayer successfully deleted
I/SecMediaClock(  249): SecMediaClock destructor
V/AwesomePlayer(  249): mSecMediaClock clear
V/StagefrightPlayer(  249): ~StagefrightPlayer
V/StagefrightPlayer(  249): reset
V/AwesomePlayer(  249): reset_l()
V/AwesomePlayer(  249): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  249): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  249): mAudioTrackVector clear
V/AwesomePlayer(  249): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  249): mSecMediaClock clear
V/AwesomePlayer(  249): destructor
V/AwesomePlayer(  249): reset_l()
V/AwesomePlayer(  249): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  249): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  249): mAudioTrackVector clear
V/AwesomePlayer(  249): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  249): mSecMediaClock clear
V/MediaPlayer( 4445): decode(64, 37457308, 34198)
V/MediaPlayerService(  249): decode(35, 37457308, 34198)
V/MediaPlayerService(  249): player type = 3
V/AwesomePlayer(  249): setDefault
V/AwesomePlayer(  249): constructor
V/AwesomePlayer(  249): setDefault
V/AwesomePlayer(  249): reset_l()
V/AwesomePlayer(  249): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  249): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  249): mAudioTrackVector clear
V/AwesomePlayer(  249): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  249): mSecMediaClock clear
V/StagefrightPlayer(  249): StagefrightPlayer
V/AwesomePlayer(  249): setListener
V/StagefrightPlayer(  249): initCheck
V/AwesomePlayer(  249): setAudioSink
V/StagefrightPlayer(  249): setDataSource(35, 37457308, 34198)
V/AwesomePlayer(  249): reset_l()
V/AwesomePlayer(  249): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  249): notify(0xb88455f8, 8, 0, 0)
V/AudioCache(  249): ignored
V/AwesomePlayer(  249): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  249): mAudioTrackVector clear
V/AwesomePlayer(  249): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  249): mSecMediaClock clear
V/AwesomePlayer(  249): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer(  249): mBitrate = -1 bits/sec
V/AwesomePlayer(  249): current audio track index (0) is added to vector
V/AwesomePlayer(  249): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer(  249): AwesomePlayer::setDataSource_l():: This is not a DRM content
V/MediaPlayerService(  249): prepare
V/AwesomePlayer(  249): prepareAsync
V/MediaPlayerService(  249): wait for prepare
V/AwesomePlayer(  249): onPrepareAsyncEvent
I/SecMediaClock(  249): SecMediaClock constructor
I/SecMediaClock(  249): reset
V/AwesomePlayer(  249): initAudioDecoder
V/AwesomePlayer(  249): checkOffloadExceptions is true
I/OMXCodec(  249): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
I/OMX     (  249): mDispatchers.add
I/OMXCodec(  249): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec(  249): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec(  249): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec(  249): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/OMXCodec(  249): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer(  249): finishAsyncPrepare_l
V/AwesomePlayer(  249): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache(  249): notify(0xb88455f8, 200, 973, 0)
V/AudioCache(  249): ignored
V/AwesomePlayer(  249): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  249): notify(0xb88455f8, 5, 0, 0)
V/AudioCache(  249): ignored
V/AwesomePlayer(  249): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  249): notify(0xb88455f8, 1, 0, 0)
V/AudioCache(  249): prepared
V/AudioCache(  249): wait - success
V/MediaPlayerService(  249): start
V/StagefrightPlayer(  249): start
V/AwesomePlayer(  249): play
V/AwesomePlayer(  249): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer(  249): startAudioPlayer_l, sendErrorNotification (0)
I/OMXCodec(  249): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec(  249): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec(  249): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/AudioPlayer(  249):  Audioplayer kKeyAudioPCMFormat:1, 2, 0
I/AudioPlayer(  249):  Audioplayer kKeyAudioPCMFormat read fail(2, 1)
V/AudioCache(  249): open(44100, 2, 0x0, 1, 4)
D/AndroidRuntime( 4463): 
D/AndroidRuntime( 4463): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
V/AwesomePlayer(  249): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache(  249): notify(0xb88455f8, 6, 0, 0)
V/AudioCache(  249): ignored
V/AwesomePlayer(  249): addBatteryData
V/MediaPlayerService(  249): wait for playback complete
D/AndroidRuntime( 4463): CheckJNI is OFF
D/AndroidRuntime( 4463): setted country_code = Poland
D/AndroidRuntime( 4463): setted countryiso_code = PL
D/AndroidRuntime( 4463): setted sales_code = XEO
D/AndroidRuntime( 4463): readGMSProperty: start
D/AndroidRuntime( 4463): readGMSProperty: already setted!!
D/AndroidRuntime( 4463): readGMSProperty: end
D/AndroidRuntime( 4463): addProductProperty: start
D/dalvikvm( 4463): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 4463): Added shared lib libjavacore.so 0x0
I/OMXCodec(  249): [OMX.google.vorbis.decoder] End Of Stream
D/dalvikvm( 4463): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 4463): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 4463): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
V/AwesomePlayer(  249): postAudioEOS delayUs (0)
V/AwesomePlayer(  249): onCheckAudioStatus
V/AwesomePlayer(  249): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  249): onStreamDone
V/AwesomePlayer(  249): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  249): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  249): notify(0xb88455f8, 2, 0, 0)
V/AudioCache(  249): playback complete - thread will wake up later
V/AwesomePlayer(  249): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  249): notify(0xb88455f8, 7, 0, 0)
V/AudioCache(  249): ignored
V/AwesomePlayer(  249): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer(  249): addBatteryData
V/AudioCache(  249): wait - success
V/StagefrightPlayer(  249): reset
V/AwesomePlayer(  249): reset_l()
V/AwesomePlayer(  249): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  249): notify(0xb88455f8, 8, 0, 0)
V/AudioCache(  249): ignored
V/AwesomePlayer(  249): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  249): mAudioTrackVector clear
I/OMXCodec(  249): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec(  249): [OMX.google.vorbis.decoder] stop() sendCommand(0x39, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec(  249): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
I/OMXCodec(  249): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
W/ActivityManager(  723): Permission Denial: getCurrentUser() from pid=4471, uid=10016 requires android.permission.INTERACT_ACROSS_USERS
I/OMX     (  249): instance freeNode
I/AudioPlayer(  249): reset out
V/AwesomePlayer(  249): reset_l() mAudioPlayer successfully deleted
I/SecMediaClock(  249): SecMediaClock destructor
V/AwesomePlayer(  249): mSecMediaClock clear
V/StagefrightPlayer(  249): ~StagefrightPlayer
V/StagefrightPlayer(  249): reset
V/AwesomePlayer(  249): reset_l()
V/AwesomePlayer(  249): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  249): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  249): mAudioTrackVector clear
V/AwesomePlayer(  249): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  249): mSecMediaClock clear
V/AwesomePlayer(  249): destructor
V/AwesomePlayer(  249): reset_l()
V/AwesomePlayer(  249): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  249): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  249): mAudioTrackVector clear
V/AwesomePlayer(  249): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  249): mSecMediaClock clear
V/MediaPlayer( 4445): decode(65, 33862452, 7405)
V/MediaPlayerService(  249): decode(35, 33862452, 7405)
V/MediaPlayerService(  249): player type = 3
V/AwesomePlayer(  249): setDefault
V/AwesomePlayer(  249): constructor
V/AwesomePlayer(  249): setDefault
V/AwesomePlayer(  249): reset_l()
V/AwesomePlayer(  249): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  249): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  249): mAudioTrackVector clear
V/AwesomePlayer(  249): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  249): mSecMediaClock clear
V/StagefrightPlayer(  249): StagefrightPlayer
V/AwesomePlayer(  249): setListener
V/StagefrightPlayer(  249): initCheck
V/AwesomePlayer(  249): setAudioSink
V/StagefrightPlayer(  249): setDataSource(35, 33862452, 7405)
V/AwesomePlayer(  249): reset_l()
V/AwesomePlayer(  249): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  249): notify(0xb8827948, 8, 0, 0)
V/AudioCache(  249): ignored
V/AwesomePlayer(  249): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  249): mAudioTrackVector clear
V/AwesomePlayer(  249): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  249): mSecMediaClock clear
V/AwesomePlayer(  249): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer(  249): mBitrate = -1 bits/sec
V/AwesomePlayer(  249): current audio track index (0) is added to vector
V/AwesomePlayer(  249): setDataSource_l: Audio(1), Video(0)
D/dalvikvm( 4471): No JNI_OnLoad found in /system/lib/libsecure_storage_jni.so 0x425cdb98, skipping init
I/AwesomePlayer(  249): AwesomePlayer::setDataSource_l():: This is not a DRM content
I/SecureStorage( 4471): [INFO]: SPID(0x00000000)Checking if this device supports Secure Storage
I/SecureStorage( 4471): [INFO]: SPID(0x00000000)This device supports Secure Storage
V/MediaPlayerService(  249): prepare
V/AwesomePlayer(  249): prepareAsync
V/MediaPlayerService(  249): wait for prepare
V/AwesomePlayer(  249): onPrepareAsyncEvent
I/SecMediaClock(  249): SecMediaClock constructor
I/SecMediaClock(  249): reset
V/AwesomePlayer(  249): initAudioDecoder
V/AwesomePlayer(  249): checkOffloadExceptions is true
I/OMXCodec(  249): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
I/OMX     (  249): mDispatchers.add
I/OMXCodec(  249): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec(  249): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec(  249): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec(  249): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/SecureStorage(  296): [INFO]: SPID(0x00000003)Credentials: uid 10016, gid 10016, pid 4471
I/SecureStorage(  296): [INFO]: SPID(0x00000003)Received function mask & code: 0000010C
I/SecureStorage( 4471): [INFO]: SPID(0x00000000)SS Daemon is running
I/OMXCodec(  249): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer(  249): finishAsyncPrepare_l
V/AwesomePlayer(  249): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache(  249): notify(0xb8827948, 200, 973, 0)
V/AudioCache(  249): ignored
V/AwesomePlayer(  249): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  249): notify(0xb8827948, 5, 0, 0)
V/AudioCache(  249): ignored
V/AwesomePlayer(  249): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  249): notify(0xb8827948, 1, 0, 0)
V/AudioCache(  249): prepared
V/AudioCache(  249): wait - success
V/MediaPlayerService(  249): start
V/StagefrightPlayer(  249): start
V/AwesomePlayer(  249): play
V/AwesomePlayer(  249): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer(  249): startAudioPlayer_l, sendErrorNotification (0)
I/SecureStorage( 4471): [INFO]: SPID(0x00000000)Processing data
I/SecureStorage(  296): [INFO]: SPID(0x00000003)Credentials: uid 10016, gid 10016, pid 4471
I/SecureStorage(  296): [INFO]: SPID(0x00000003)Received function mask & code: 00000106
I/OMXCodec(  249): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec(  249): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec(  249): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/AudioPlayer(  249):  Audioplayer kKeyAudioPCMFormat:1, 2, 0
I/AudioPlayer(  249):  Audioplayer kKeyAudioPCMFormat read fail(2, 1)
V/AudioCache(  249): open(44100, 2, 0x0, 1, 4)
V/AwesomePlayer(  249): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache(  249): notify(0xb8827948, 6, 0, 0)
V/AudioCache(  249): ignored
V/AwesomePlayer(  249): addBatteryData
V/MediaPlayerService(  249): wait for playback complete
I/OMXCodec(  249): [OMX.google.vorbis.decoder] End Of Stream
V/AwesomePlayer(  249): postAudioEOS delayUs (0)
V/AwesomePlayer(  249): onCheckAudioStatus
V/AwesomePlayer(  249): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  249): onStreamDone
V/AwesomePlayer(  249): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  249): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  249): notify(0xb8827948, 2, 0, 0)
V/AudioCache(  249): playback complete - thread will wake up later
V/AwesomePlayer(  249): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  249): notify(0xb8827948, 7, 0, 0)
V/AudioCache(  249): ignored
V/AwesomePlayer(  249): cancelPlayerEvents (keepNotifications=1)
V/AudioCache(  249): wait - success
V/StagefrightPlayer(  249): reset
V/AwesomePlayer(  249): addBatteryData
V/AwesomePlayer(  249): reset_l()
V/AwesomePlayer(  249): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  249): notify(0xb8827948, 8, 0, 0)
V/AudioCache(  249): ignored
V/AwesomePlayer(  249): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  249): mAudioTrackVector clear
I/OMXCodec(  249): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec(  249): [OMX.google.vorbis.decoder] stop() sendCommand(0x3a, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec(  249): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
I/OMXCodec(  249): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/OMX     (  249): instance freeNode
I/AudioPlayer(  249): reset out
V/AwesomePlayer(  249): reset_l() mAudioPlayer successfully deleted
I/SecMediaClock(  249): SecMediaClock destructor
V/AwesomePlayer(  249): mSecMediaClock clear
V/StagefrightPlayer(  249): ~StagefrightPlayer
V/StagefrightPlayer(  249): reset
V/AwesomePlayer(  249): reset_l()
V/AwesomePlayer(  249): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  249): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  249): mAudioTrackVector clear
V/AwesomePlayer(  249): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  249): mSecMediaClock clear
V/AwesomePlayer(  249): destructor
V/AwesomePlayer(  249): reset_l()
V/AwesomePlayer(  249): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  249): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  249): mAudioTrackVector clear
V/AwesomePlayer(  249): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  249): mSecMediaClock clear
V/MediaPlayer( 4445): decode(66, 37547940, 5555)
V/MediaPlayerService(  249): decode(35, 37547940, 5555)
V/MediaPlayerService(  249): player type = 3
V/AwesomePlayer(  249): setDefault
V/AwesomePlayer(  249): constructor
V/AwesomePlayer(  249): setDefault
V/AwesomePlayer(  249): reset_l()
V/AwesomePlayer(  249): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  249): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  249): mAudioTrackVector clear
V/AwesomePlayer(  249): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  249): mSecMediaClock clear
V/StagefrightPlayer(  249): StagefrightPlayer
V/AwesomePlayer(  249): setListener
V/StagefrightPlayer(  249): initCheck
V/AwesomePlayer(  249): setAudioSink
V/StagefrightPlayer(  249): setDataSource(35, 37547940, 5555)
V/AwesomePlayer(  249): reset_l()
V/AwesomePlayer(  249): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  249): notify(0xb8838bf8, 8, 0, 0)
V/AudioCache(  249): ignored
V/AwesomePlayer(  249): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  249): mAudioTrackVector clear
V/AwesomePlayer(  249): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  249): mSecMediaClock clear
V/AwesomePlayer(  249): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer(  249): mBitrate = -1 bits/sec
V/AwesomePlayer(  249): current audio track index (0) is added to vector
V/AwesomePlayer(  249): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer(  249): AwesomePlayer::setDataSource_l():: This is not a DRM content
V/MediaPlayerService(  249): prepare
V/AwesomePlayer(  249): prepareAsync
V/MediaPlayerService(  249): wait for prepare
V/AwesomePlayer(  249): onPrepareAsyncEvent
I/SecMediaClock(  249): SecMediaClock constructor
I/SecMediaClock(  249): reset
V/AwesomePlayer(  249): initAudioDecoder
V/AwesomePlayer(  249): checkOffloadExceptions is true
I/OMXCodec(  249): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
I/OMX     (  249): mDispatchers.add
I/OMXCodec(  249): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec(  249): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec(  249): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec(  249): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/OMXCodec(  249): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer(  249): finishAsyncPrepare_l
V/AwesomePlayer(  249): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache(  249): notify(0xb8838bf8, 200, 973, 0)
V/AudioCache(  249): ignored
V/AwesomePlayer(  249): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  249): notify(0xb8838bf8, 5, 0, 0)
V/AudioCache(  249): ignored
V/AwesomePlayer(  249): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  249): notify(0xb8838bf8, 1, 0, 0)
V/AudioCache(  249): prepared
V/AudioCache(  249): wait - success
V/MediaPlayerService(  249): start
V/StagefrightPlayer(  249): start
V/AwesomePlayer(  249): play
V/AwesomePlayer(  249): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer(  249): startAudioPlayer_l, sendErrorNotification (0)
I/OMXCodec(  249): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec(  249): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec(  249): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/AudioPlayer(  249):  Audioplayer kKeyAudioPCMFormat:1, 2, 0
I/AudioPlayer(  249):  Audioplayer kKeyAudioPCMFormat read fail(2, 1)
V/AudioCache(  249): open(44100, 2, 0x0, 1, 4)
V/AwesomePlayer(  249): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache(  249): notify(0xb8838bf8, 6, 0, 0)
V/AudioCache(  249): ignored
V/AwesomePlayer(  249): addBatteryData
V/MediaPlayerService(  249): wait for playback complete
I/OMXCodec(  249): [OMX.google.vorbis.decoder] End Of Stream
V/AwesomePlayer(  249): postAudioEOS delayUs (0)
V/AwesomePlayer(  249): onCheckAudioStatus
V/AwesomePlayer(  249): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  249): onStreamDone
V/AwesomePlayer(  249): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  249): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  249): notify(0xb8838bf8, 2, 0, 0)
V/AudioCache(  249): playback complete - thread will wake up later
V/AwesomePlayer(  249): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  249): notify(0xb8838bf8, 7, 0, 0)
V/AudioCache(  249): ignored
V/AwesomePlayer(  249): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer(  249): addBatteryData
V/AudioCache(  249): wait - success
V/StagefrightPlayer(  249): reset
V/AwesomePlayer(  249): reset_l()
V/AwesomePlayer(  249): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  249): notify(0xb8838bf8, 8, 0, 0)
V/AudioCache(  249): ignored
V/AwesomePlayer(  249): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  249): mAudioTrackVector clear
I/OMXCodec(  249): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec(  249): [OMX.google.vorbis.decoder] stop() sendCommand(0x3b, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec(  249): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
I/OMXCodec(  249): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/OMX     (  249): instance freeNode
I/AudioPlayer(  249): reset out
V/AwesomePlayer(  249): reset_l() mAudioPlayer successfully deleted
I/SecMediaClock(  249): SecMediaClock destructor
V/AwesomePlayer(  249): mSecMediaClock clear
V/StagefrightPlayer(  249): ~StagefrightPlayer
V/StagefrightPlayer(  249): reset
V/AwesomePlayer(  249): reset_l()
V/AwesomePlayer(  249): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  249): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  249): mAudioTrackVector clear
V/AwesomePlayer(  249): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  249): mSecMediaClock clear
V/AwesomePlayer(  249): destructor
V/AwesomePlayer(  249): reset_l()
V/AwesomePlayer(  249): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  249): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  249): mAudioTrackVector clear
V/AwesomePlayer(  249): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  249): mSecMediaClock clear
V/MediaPlayer( 4445): decode(67, 30367732, 5085)
V/MediaPlayerService(  249): decode(35, 30367732, 5085)
V/MediaPlayerService(  249): player type = 3
V/AwesomePlayer(  249): setDefault
V/AwesomePlayer(  249): constructor
V/AwesomePlayer(  249): setDefault
V/AwesomePlayer(  249): reset_l()
V/AwesomePlayer(  249): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  249): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  249): mAudioTrackVector clear
V/AwesomePlayer(  249): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  249): mSecMediaClock clear
V/StagefrightPlayer(  249): StagefrightPlayer
V/AwesomePlayer(  249): setListener
V/StagefrightPlayer(  249): initCheck
V/AwesomePlayer(  249): setAudioSink
V/StagefrightPlayer(  249): setDataSource(35, 30367732, 5085)
V/AwesomePlayer(  249): reset_l()
V/AwesomePlayer(  249): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  249): notify(0xb8842900, 8, 0, 0)
V/AudioCache(  249): ignored
V/AwesomePlayer(  249): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  249): mAudioTrackVector clear
V/AwesomePlayer(  249): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  249): mSecMediaClock clear
V/AwesomePlayer(  249): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer(  249): mBitrate = -1 bits/sec
V/AwesomePlayer(  249): current audio track index (0) is added to vector
V/AwesomePlayer(  249): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer(  249): AwesomePlayer::setDataSource_l():: This is not a DRM content
V/MediaPlayerService(  249): prepare
V/AwesomePlayer(  249): prepareAsync
V/MediaPlayerService(  249): wait for prepare
V/AwesomePlayer(  249): onPrepareAsyncEvent
I/SecMediaClock(  249): SecMediaClock constructor
I/SecMediaClock(  249): reset
V/AwesomePlayer(  249): initAudioDecoder
V/AwesomePlayer(  249): checkOffloadExceptions is true
I/OMXCodec(  249): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
I/OMX     (  249): mDispatchers.add
I/OMXCodec(  249): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec(  249): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec(  249): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec(  249): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/OMXCodec(  249): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer(  249): finishAsyncPrepare_l
V/AwesomePlayer(  249): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache(  249): notify(0xb8842900, 200, 973, 0)
V/AudioCache(  249): ignored
V/AwesomePlayer(  249): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  249): notify(0xb8842900, 5, 0, 0)
V/AudioCache(  249): ignored
V/AwesomePlayer(  249): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  249): notify(0xb8842900, 1, 0, 0)
V/AudioCache(  249): prepared
V/AudioCache(  249): wait - success
V/MediaPlayerService(  249): start
V/StagefrightPlayer(  249): start
V/AwesomePlayer(  249): play
V/AwesomePlayer(  249): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer(  249): startAudioPlayer_l, sendErrorNotification (0)
I/OMXCodec(  249): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec(  249): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec(  249): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/AudioPlayer(  249):  Audioplayer kKeyAudioPCMFormat:1, 2, 0
I/AudioPlayer(  249):  Audioplayer kKeyAudioPCMFormat read fail(2, 1)
V/AudioCache(  249): open(44100, 2, 0x0, 1, 4)
V/AwesomePlayer(  249): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache(  249): notify(0xb8842900, 6, 0, 0)
V/AudioCache(  249): ignored
V/AwesomePlayer(  249): addBatteryData
V/MediaPlayerService(  249): wait for playback complete
I/AudioPlayer(  249): First fillBuffer call!!
I/OMXCodec(  249): [OMX.google.vorbis.decoder] End Of Stream
V/AwesomePlayer(  249): postAudioEOS delayUs (0)
V/AwesomePlayer(  249): onCheckAudioStatus
V/AwesomePlayer(  249): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  249): onStreamDone
V/AwesomePlayer(  249): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  249): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  249): notify(0xb8842900, 2, 0, 0)
V/AudioCache(  249): playback complete - thread will wake up later
V/AwesomePlayer(  249): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  249): notify(0xb8842900, 7, 0, 0)
V/AudioCache(  249): ignored
V/AwesomePlayer(  249): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer(  249): addBatteryData
V/AudioCache(  249): wait - success
V/StagefrightPlayer(  249): reset
V/AwesomePlayer(  249): reset_l()
V/AwesomePlayer(  249): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  249): notify(0xb8842900, 8, 0, 0)
V/AudioCache(  249): ignored
V/AwesomePlayer(  249): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  249): mAudioTrackVector clear
I/OMXCodec(  249): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec(  249): [OMX.google.vorbis.decoder] stop() sendCommand(0x3c, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec(  249): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
I/OMXCodec(  249): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/OMX     (  249): instance freeNode
I/AudioPlayer(  249): reset out
V/AwesomePlayer(  249): reset_l() mAudioPlayer successfully deleted
I/SecMediaClock(  249): SecMediaClock destructor
V/AwesomePlayer(  249): mSecMediaClock clear
V/StagefrightPlayer(  249): ~StagefrightPlayer
V/StagefrightPlayer(  249): reset
V/AwesomePlayer(  249): reset_l()
V/AwesomePlayer(  249): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  249): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  249): mAudioTrackVector clear
V/AwesomePlayer(  249): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  249): mSecMediaClock clear
V/AwesomePlayer(  249): destructor
V/AwesomePlayer(  249): reset_l()
V/AwesomePlayer(  249): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  249): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  249): mAudioTrackVector clear
V/AwesomePlayer(  249): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  249): mSecMediaClock clear
V/MediaPlayer( 4445): decode(68, 30372876, 21552)
V/MediaPlayerService(  249): decode(35, 30372876, 21552)
V/MediaPlayerService(  249): player type = 3
V/AwesomePlayer(  249): setDefault
V/AwesomePlayer(  249): constructor
V/AwesomePlayer(  249): setDefault
V/AwesomePlayer(  249): reset_l()
V/AwesomePlayer(  249): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  249): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  249): mAudioTrackVector clear
V/AwesomePlayer(  249): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  249): mSecMediaClock clear
V/StagefrightPlayer(  249): StagefrightPlayer
V/AwesomePlayer(  249): setListener
V/StagefrightPlayer(  249): initCheck
V/AwesomePlayer(  249): setAudioSink
V/StagefrightPlayer(  249): setDataSource(35, 30372876, 21552)
V/AwesomePlayer(  249): reset_l()
V/AwesomePlayer(  249): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  249): notify(0xb882cb88, 8, 0, 0)
V/AudioCache(  249): ignored
V/AwesomePlayer(  249): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  249): mAudioTrackVector clear
V/AwesomePlayer(  249): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  249): mSecMediaClock clear
V/AwesomePlayer(  249): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer(  249): mBitrate = -1 bits/sec
V/AwesomePlayer(  249): current audio track index (0) is added to vector
V/AwesomePlayer(  249): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer(  249): AwesomePlayer::setDataSource_l():: This is not a DRM content
V/MediaPlayerService(  249): prepare
V/AwesomePlayer(  249): prepareAsync
V/MediaPlayerService(  249): wait for prepare
V/AwesomePlayer(  249): onPrepareAsyncEvent
I/SecMediaClock(  249): SecMediaClock constructor
I/SecMediaClock(  249): reset
V/AwesomePlayer(  249): initAudioDecoder
V/AwesomePlayer(  249): checkOffloadExceptions is true
I/OMXCodec(  249): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
I/OMX     (  249): mDispatchers.add
I/OMXCodec(  249): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec(  249): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec(  249): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec(  249): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/OMXCodec(  249): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer(  249): finishAsyncPrepare_l
V/AwesomePlayer(  249): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache(  249): notify(0xb882cb88, 200, 973, 0)
V/AudioCache(  249): ignored
V/AwesomePlayer(  249): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  249): notify(0xb882cb88, 5, 0, 0)
V/AudioCache(  249): ignored
V/AwesomePlayer(  249): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  249): notify(0xb882cb88, 1, 0, 0)
V/AudioCache(  249): prepared
V/AudioCache(  249): wait - success
V/MediaPlayerService(  249): start
V/StagefrightPlayer(  249): start
V/AwesomePlayer(  249): play
V/AwesomePlayer(  249): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer(  249): startAudioPlayer_l, sendErrorNotification (0)
I/OMXCodec(  249): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec(  249): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec(  249): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/AudioPlayer(  249):  Audioplayer kKeyAudioPCMFormat:1, 2, 0
I/AudioPlayer(  249):  Audioplayer kKeyAudioPCMFormat read fail(2, 1)
V/AudioCache(  249): open(44100, 2, 0x0, 1, 4)
V/AwesomePlayer(  249): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache(  249): notify(0xb882cb88, 6, 0, 0)
V/AudioCache(  249): ignored
V/AwesomePlayer(  249): addBatteryData
V/MediaPlayerService(  249): wait for playback complete
E/memtrack( 4463): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 4463): failed to load memtrack module: -2
I/OMXCodec(  249): [OMX.google.vorbis.decoder] End Of Stream
V/AwesomePlayer(  249): postAudioEOS delayUs (0)
V/AwesomePlayer(  249): onCheckAudioStatus
V/AwesomePlayer(  249): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  249): onStreamDone
V/AwesomePlayer(  249): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  249): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  249): notify(0xb882cb88, 2, 0, 0)
V/AudioCache(  249): playback complete - thread will wake up later
V/AwesomePlayer(  249): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  249): notify(0xb882cb88, 7, 0, 0)
V/AudioCache(  249): ignored
V/AwesomePlayer(  249): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer(  249): addBatteryData
V/AudioCache(  249): wait - success
V/StagefrightPlayer(  249): reset
V/AwesomePlayer(  249): reset_l()
V/AwesomePlayer(  249): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  249): notify(0xb882cb88, 8, 0, 0)
V/AudioCache(  249): ignored
V/AwesomePlayer(  249): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  249): mAudioTrackVector clear
I/OMXCodec(  249): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec(  249): [OMX.google.vorbis.decoder] stop() sendCommand(0x3d, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec(  249): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
I/OMXCodec(  249): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
,I/OMX     (  249): instance freeNode
I/AudioPlayer(  249): reset out
V/AwesomePlayer(  249): reset_l() mAudioPlayer successfully deleted
I/SecMediaClock(  249): SecMediaClock destructor
V/AwesomePlayer(  249): mSecMediaClock clear
V/StagefrightPlayer(  249): ~StagefrightPlayer
V/StagefrightPlayer(  249): reset
V/AwesomePlayer(  249): reset_l()
V/AwesomePlayer(  249): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  249): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  249): mAudioTrackVector clear
V/AwesomePlayer(  249): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  249): mSecMediaClock clear
V/AwesomePlayer(  249): destructor
V/AwesomePlayer(  249): reset_l()
V/AwesomePlayer(  249): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  249): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  249): mAudioTrackVector clear
V/AwesomePlayer(  249): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  249): mSecMediaClock clear
V/MediaPlayer( 4445): decode(69, 37543652, 4230)
V/MediaPlayerService(  249): decode(35, 37543652, 4230)
V/MediaPlayerService(  249): player type = 3
V/AwesomePlayer(  249): setDefault
V/AwesomePlayer(  249): constructor
V/AwesomePlayer(  249): setDefault
V/AwesomePlayer(  249): reset_l()
V/AwesomePlayer(  249): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  249): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  249): mAudioTrackVector clear
V/AwesomePlayer(  249): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  249): mSecMediaClock clear
V/StagefrightPlayer(  249): StagefrightPlayer
V/AwesomePlayer(  249): setListener
V/StagefrightPlayer(  249): initCheck
V/AwesomePlayer(  249): setAudioSink
V/StagefrightPlayer(  249): setDataSource(35, 37543652, 4230)
V/AwesomePlayer(  249): reset_l()
V/AwesomePlayer(  249): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  249): notify(0xb8827c30, 8, 0, 0)
V/AudioCache(  249): ignored
V/AwesomePlayer(  249): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  249): mAudioTrackVector clear
V/AwesomePlayer(  249): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  249): mSecMediaClock clear
D/dalvikvm( 4463): Note: class Landroid/app/ActivityManagerNative; has 192 unimplemented (abstract) methods
V/AwesomePlayer(  249): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer(  249): mBitrate = -1 bits/sec
V/AwesomePlayer(  249): current audio track index (0) is added to vector
V/AwesomePlayer(  249): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer(  249): AwesomePlayer::setDataSource_l():: This is not a DRM content
V/MediaPlayerService(  249): prepare
V/AwesomePlayer(  249): prepareAsync
V/MediaPlayerService(  249): wait for prepare
V/AwesomePlayer(  249): onPrepareAsyncEvent
I/SecMediaClock(  249): SecMediaClock constructor
I/SecMediaClock(  249): reset
V/AwesomePlayer(  249): initAudioDecoder
V/AwesomePlayer(  249): checkOffloadExceptions is true
I/OMXCodec(  249): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
I/OMX     (  249): mDispatchers.add
I/OMXCodec(  249): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec(  249): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec(  249): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec(  249): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/OMXCodec(  249): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer(  249): finishAsyncPrepare_l
V/AwesomePlayer(  249): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache(  249): notify(0xb8827c30, 200, 973, 0)
V/AudioCache(  249): ignored
V/AwesomePlayer(  249): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  249): notify(0xb8827c30, 5, 0, 0)
V/AudioCache(  249): ignored
V/AwesomePlayer(  249): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  249): notify(0xb8827c30, 1, 0, 0)
V/AudioCache(  249): prepared
V/AudioCache(  249): wait - success
V/MediaPlayerService(  249): start
V/StagefrightPlayer(  249): start
V/AwesomePlayer(  249): play
V/AwesomePlayer(  249): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer(  249): startAudioPlayer_l, sendErrorNotification (0)
I/OMXCodec(  249): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec(  249): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec(  249): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/OMXCodec(  249): [OMX.google.vorbis.decoder] End Of Stream
I/AudioPlayer(  249):  Audioplayer kKeyAudioPCMFormat:1, 1, 0
I/AudioPlayer(  249):  Audioplayer kKeyAudioPCMFormat read fail(1, 1)
V/AudioCache(  249): open(44100, 1, 0x0, 1, 4)
V/AwesomePlayer(  249): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache(  249): notify(0xb8827c30, 6, 0, 0)
V/AudioCache(  249): ignored
V/AwesomePlayer(  249): addBatteryData
V/MediaPlayerService(  249): wait for playback complete
V/AwesomePlayer(  249): postAudioEOS delayUs (0)
V/AwesomePlayer(  249): onCheckAudioStatus
V/AwesomePlayer(  249): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  249): onStreamDone
V/AwesomePlayer(  249): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  249): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  249): notify(0xb8827c30, 2, 0, 0)
V/AudioCache(  249): playback complete - thread will wake up later
V/AwesomePlayer(  249): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  249): notify(0xb8827c30, 7, 0, 0)
V/AudioCache(  249): ignored
V/AwesomePlayer(  249): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer(  249): addBatteryData
V/AudioCache(  249): wait - success
V/StagefrightPlayer(  249): reset
V/AwesomePlayer(  249): reset_l()
V/AwesomePlayer(  249): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  249): notify(0xb8827c30, 8, 0, 0)
V/AudioCache(  249): ignored
V/AwesomePlayer(  249): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  249): mAudioTrackVector clear
I/OMXCodec(  249): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec(  249): [OMX.google.vorbis.decoder] stop() sendCommand(0x3e, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec(  249): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
I/OMXCodec(  249): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/OMX     (  249): instance freeNode
I/AudioPlayer(  249): reset out
V/AwesomePlayer(  249): reset_l() mAudioPlayer successfully deleted
I/SecMediaClock(  249): SecMediaClock destructor
V/AwesomePlayer(  249): mSecMediaClock clear
V/StagefrightPlayer(  249): ~StagefrightPlayer
V/StagefrightPlayer(  249): reset
V/AwesomePlayer(  249): reset_l()
V/AwesomePlayer(  249): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  249): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  249): mAudioTrackVector clear
V/AwesomePlayer(  249): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  249): mSecMediaClock clear
V/AwesomePlayer(  249): destructor
V/AwesomePlayer(  249): reset_l()
V/AwesomePlayer(  249): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  249): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  249): mAudioTrackVector clear
V/AwesomePlayer(  249): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  249): mSecMediaClock clear
V/MediaPlayer( 4445): decode(70, 30337076, 9400)
V/MediaPlayerService(  249): decode(35, 30337076, 9400)
V/MediaPlayerService(  249): player type = 3
V/AwesomePlayer(  249): setDefault
V/AwesomePlayer(  249): constructor
V/AwesomePlayer(  249): setDefault
V/AwesomePlayer(  249): reset_l()
V/AwesomePlayer(  249): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  249): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  249): mAudioTrackVector clear
V/AwesomePlayer(  249): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  249): mSecMediaClock clear
V/StagefrightPlayer(  249): StagefrightPlayer
V/AwesomePlayer(  249): setListener
V/StagefrightPlayer(  249): initCheck
V/AwesomePlayer(  249): setAudioSink
V/StagefrightPlayer(  249): setDataSource(35, 30337076, 9400)
V/AwesomePlayer(  249): reset_l()
V/AwesomePlayer(  249): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  249): notify(0xb8827c30, 8, 0, 0)
V/AudioCache(  249): ignored
V/AwesomePlayer(  249): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  249): mAudioTrackVector clear
V/AwesomePlayer(  249): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  249): mSecMediaClock clear
V/AwesomePlayer(  249): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer(  249): mBitrate = -1 bits/sec
V/AwesomePlayer(  249): current audio track index (0) is added to vector
V/AwesomePlayer(  249): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer(  249): AwesomePlayer::setDataSource_l():: This is not a DRM content
V/MediaPlayerService(  249): prepare
V/AwesomePlayer(  249): prepareAsync
V/MediaPlayerService(  249): wait for prepare
V/AwesomePlayer(  249): onPrepareAsyncEvent
I/SecMediaClock(  249): SecMediaClock constructor
I/SecMediaClock(  249): reset
V/AwesomePlayer(  249): initAudioDecoder
V/AwesomePlayer(  249): checkOffloadExceptions is true
I/OMXCodec(  249): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
I/OMX     (  249): mDispatchers.add
I/OMXCodec(  249): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec(  249): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec(  249): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec(  249): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/OMXCodec(  249): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer(  249): finishAsyncPrepare_l
V/AwesomePlayer(  249): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache(  249): notify(0xb8827c30, 200, 973, 0)
V/AudioCache(  249): ignored
V/AwesomePlayer(  249): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  249): notify(0xb8827c30, 5, 0, 0)
V/AudioCache(  249): ignored
V/AwesomePlayer(  249): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  249): notify(0xb8827c30, 1, 0, 0)
V/AudioCache(  249): prepared
V/AudioCache(  249): wait - success
V/MediaPlayerService(  249): start
V/StagefrightPlayer(  249): start
V/AwesomePlayer(  249): play
V/AwesomePlayer(  249): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer(  249): startAudioPlayer_l, sendErrorNotification (0)
I/OMXCodec(  249): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec(  249): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec(  249): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/AudioPlayer(  249):  Audioplayer kKeyAudioPCMFormat:1, 1, 0
I/AudioPlayer(  249):  Audioplayer kKeyAudioPCMFormat read fail(1, 1)
V/AudioCache(  249): open(44100, 1, 0x0, 1, 4)
V/AwesomePlayer(  249): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache(  249): notify(0xb8827c30, 6, 0, 0)
V/AudioCache(  249): ignored
V/AwesomePlayer(  249): addBatteryData
V/MediaPlayerService(  249): wait for playback complete
I/SELinux ( 4537): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 4537):  
I/ActivityManager(  723): Killing 3130:com.sec.android.app.mt/1000 (adj 15): empty #43
D/AndroidRuntime( 4463): Calling main entry com.android.commands.am.Am
I/SELinux ( 4537): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 4537):  
I/SELinux ( 4537):  
I/SELinux ( 4537): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 4537): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 4537): >>>>> Normal User
E/dalvikvm( 4537): >>>>> com.policydm [ userId:0 | appId:1000 ]
E/SELinux ( 4537): [DEBUG] seapp_context_lookup: seinfoCategory = platform
I/OMXCodec(  249): [OMX.google.vorbis.decoder] End Of Stream
V/AwesomePlayer(  249): postAudioEOS delayUs (0)
V/AwesomePlayer(  249): onCheckAudioStatus
V/AwesomePlayer(  249): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  249): onStreamDone
V/AwesomePlayer(  249): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  249): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  249): notify(0xb8827c30, 2, 0, 0)
V/AudioCache(  249): playback complete - thread will wake up later
V/AwesomePlayer(  249): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  249): notify(0xb8827c30, 7, 0, 0)
V/AudioCache(  249): ignored
V/AwesomePlayer(  249): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer(  249): addBatteryData
V/AudioCache(  249): wait - success
V/StagefrightPlayer(  249): reset
V/AwesomePlayer(  249): reset_l()
V/AwesomePlayer(  249): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  249): notify(0xb8827c30, 8, 0, 0)
V/AudioCache(  249): ignored
V/AwesomePlayer(  249): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  249): mAudioTrackVector clear
I/OMXCodec(  249): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec(  249): [OMX.google.vorbis.decoder] stop() sendCommand(0x3f, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec(  249): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
D/TimaKeyStoreProvider( 4537): in addTimaSignatureService
I/OMXCodec(  249): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/OMX     (  249): instance freeNode
I/AudioPlayer(  249): reset out
V/AwesomePlayer(  249): reset_l() mAudioPlayer successfully deleted
I/SecMediaClock(  249): SecMediaClock destructor
V/AwesomePlayer(  249): mSecMediaClock clear
V/StagefrightPlayer(  249): ~StagefrightPlayer
V/StagefrightPlayer(  249): reset
V/AwesomePlayer(  249): reset_l()
V/AwesomePlayer(  249): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  249): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  249): mAudioTrackVector clear
V/AwesomePlayer(  249): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  249): mSecMediaClock clear
V/AwesomePlayer(  249): destructor
V/AwesomePlayer(  249): reset_l()
V/AwesomePlayer(  249): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  249): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  249): mAudioTrackVector clear
V/AwesomePlayer(  249): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  249): mSecMediaClock clear
V/MediaPlayer( 4445): decode(71, 33925464, 44276)
V/MediaPlayerService(  249): decode(35, 33925464, 44276)
V/MediaPlayerService(  249): player type = 3
V/AwesomePlayer(  249): setDefault
V/AwesomePlayer(  249): constructor
V/AwesomePlayer(  249): setDefault
V/AwesomePlayer(  249): reset_l()
V/AwesomePlayer(  249): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  249): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  249): mAudioTrackVector clear
V/AwesomePlayer(  249): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  249): mSecMediaClock clear
V/StagefrightPlayer(  249): StagefrightPlayer
V/AwesomePlayer(  249): setListener
V/StagefrightPlayer(  249): initCheck
V/AwesomePlayer(  249): setAudioSink
V/StagefrightPlayer(  249): setDataSource(35, 33925464, 44276)
V/AwesomePlayer(  249): reset_l()
V/ApplicationPolicy(  723): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
V/AwesomePlayer(  249): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  249): notify(0xb882caf0, 8, 0, 0)
V/AudioCache(  249): ignored
V/AwesomePlayer(  249): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  249): mAudioTrackVector clear
V/AwesomePlayer(  249): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  249): mSecMediaClock clear
V/AwesomePlayer(  249): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer(  249): mBitrate = -1 bits/sec
V/AwesomePlayer(  249): current audio track index (0) is added to vector
V/AwesomePlayer(  249): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer(  249): AwesomePlayer::setDataSource_l():: This is not a DRM content
V/MediaPlayerService(  249): prepare
V/AwesomePlayer(  249): prepareAsync
V/MediaPlayerService(  249): wait for prepare
V/AwesomePlayer(  249): onPrepareAsyncEvent
I/SecMediaClock(  249): SecMediaClock constructor
I/SecMediaClock(  249): reset
V/AwesomePlayer(  249): initAudioDecoder
V/AwesomePlayer(  249): checkOffloadExceptions is true
I/OMXCodec(  249): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
I/OMX     (  249): mDispatchers.add
I/OMXCodec(  249): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec(  249): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec(  249): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec(  249): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
D/TimaKeyStoreProvider( 4537): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 4537): Added TimaKesytore provider
I/OMXCodec(  249): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer(  249): finishAsyncPrepare_l
V/AwesomePlayer(  249): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache(  249): notify(0xb882caf0, 200, 973, 0)
V/AudioCache(  249): ignored
V/AwesomePlayer(  249): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  249): notify(0xb882caf0, 5, 0, 0)
V/AudioCache(  249): ignored
V/AwesomePlayer(  249): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  249): notify(0xb882caf0, 1, 0, 0)
V/AudioCache(  249): prepared
V/AudioCache(  249): wait - success
V/MediaPlayerService(  249): start
V/StagefrightPlayer(  249): start
V/AwesomePlayer(  249): play
V/AwesomePlayer(  249): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer(  249): startAudioPlayer_l, sendErrorNotification (0)
I/OMXCodec(  249): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec(  249): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec(  249): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/AudioPlayer(  249):  Audioplayer kKeyAudioPCMFormat:1, 2, 0
I/AudioPlayer(  249):  Audioplayer kKeyAudioPCMFormat read fail(2, 1)
V/AudioCache(  249): open(44100, 2, 0x0, 1, 4)
V/AwesomePlayer(  249): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache(  249): notify(0xb882caf0, 6, 0, 0)
V/AudioCache(  249): ignored
V/AwesomePlayer(  249): addBatteryData
V/MediaPlayerService(  249): wait for playback complete
I/AudioPlayer(  249): First fillBuffer call!!
D/CustomFrequencyManagerService(  723): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 723  pkgName : ACTIVITY_RESUME_BOOSTER@5
W/ActivityManager(  723): mDVFSHelper.acquire()
I/SELinux ( 4555): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 4555):  
D/dalvikvm(  247): GC_EXPLICIT freed 45K, 51% free 9509K/19060K, paused 2ms+2ms, total 32ms
D/LockPatternUtils( 1066): isPcwEnable = null
D/AndroidRuntime( 4463): Shutting down VM
D/dalvikvm( 4463): GC_CONCURRENT freed 97K, 13% free 717K/816K, paused 1ms+0ms, total 4ms
I/SELinux ( 4555): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 4555):  
I/SELinux ( 4555):  
I/SELinux ( 4555): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 4555): [DEBUG] seapp_context_lookup: seinfoCategory = default
E/dalvikvm( 4555): >>>>> Normal User
E/dalvikvm( 4555): >>>>> com.test.thalitest [ userId:0 | appId:10179 ]
E/SELinux ( 4555): [DEBUG] seapp_context_lookup: seinfoCategory = default
D/dalvikvm(  247): GC_EXPLICIT freed <1K, 51% free 9509K/19060K, paused 2ms+4ms, total 22ms
D/SurfaceWidgetView( 1254): destroyHardwareResources():1125975184
D/TimaKeyStoreProvider( 4555): in addTimaSignatureService
D/dalvikvm(  247): GC_EXPLICIT freed <1K, 51% free 9509K/19060K, paused 2ms+2ms, total 20ms
D/TimaKeyStoreProvider( 4555): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 4555): Added TimaKesytore provider
I/OMXCodec(  249): [OMX.google.vorbis.decoder] End Of Stream
D/LockPatternUtils( 1066): isPcwEnable = null
V/AwesomePlayer(  249): postAudioEOS delayUs (0)
V/AwesomePlayer(  249): onCheckAudioStatus
V/AwesomePlayer(  249): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  249): onStreamDone
V/AwesomePlayer(  249): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  249): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  249): notify(0xb882caf0, 2, 0, 0)
V/AudioCache(  249): playback complete - thread will wake up later
V/AwesomePlayer(  249): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  249): notify(0xb882caf0, 7, 0, 0)
V/AudioCache(  249): ignored
V/AwesomePlayer(  249): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer(  249): addBatteryData
V/AudioCache(  249): wait - success
V/StagefrightPlayer(  249): reset
V/AwesomePlayer(  249): reset_l()
V/AwesomePlayer(  249): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  249): notify(0xb882caf0, 8, 0, 0)
V/AudioCache(  249): ignored
V/AwesomePlayer(  249): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  249): mAudioTrackVector clear
I/OMXCodec(  249): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec(  249): [OMX.google.vorbis.decoder] stop() sendCommand(0x40, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec(  249): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
I/OMXCodec(  249): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/OMX     (  249): instance freeNode
I/AudioPlayer(  249): reset out
V/AwesomePlayer(  249): reset_l() mAudioPlayer successfully deleted
I/SecMediaClock(  249): SecMediaClock destructor
V/AwesomePlayer(  249): mSecMediaClock clear
V/StagefrightPlayer(  249): ~StagefrightPlayer
V/StagefrightPlayer(  249): reset
V/AwesomePlayer(  249): reset_l()
V/AwesomePlayer(  249): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  249): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  249): mAudioTrackVector clear
V/AwesomePlayer(  249): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  249): mSecMediaClock clear
V/AwesomePlayer(  249): destructor
V/AwesomePlayer(  249): reset_l()
V/AwesomePlayer(  249): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  249): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  249): mAudioTrackVector clear
V/AwesomePlayer(  249): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  249): mSecMediaClock clear
V/MediaPlayer( 4445): decode(72, 33885672, 29256)
V/MediaPlayerService(  249): decode(35, 33885672, 29256)
V/MediaPlayerService(  249): player type = 3
V/AwesomePlayer(  249): setDefault
V/AwesomePlayer(  249): constructor
V/AwesomePlayer(  249): setDefault
V/AwesomePlayer(  249): reset_l()
V/AwesomePlayer(  249): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  249): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  249): mAudioTrackVector clear
V/AwesomePlayer(  249): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  249): mSecMediaClock clear
V/StagefrightPlayer(  249): StagefrightPlayer
V/AwesomePlayer(  249): setListener
V/StagefrightPlayer(  249): initCheck
V/AwesomePlayer(  249): setAudioSink
V/StagefrightPlayer(  249): setDataSource(35, 33885672, 29256)
V/AwesomePlayer(  249): reset_l()
V/AwesomePlayer(  249): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  249): notify(0xb8830180, 8, 0, 0)
V/AudioCache(  249): ignored
V/AwesomePlayer(  249): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  249): mAudioTrackVector clear
V/AwesomePlayer(  249): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  249): mSecMediaClock clear
V/AwesomePlayer(  249): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer(  249): mBitrate = -1 bits/sec
V/AwesomePlayer(  249): current audio track index (0) is added to vector
V/AwesomePlayer(  249): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer(  249): AwesomePlayer::setDataSource_l():: This is not a DRM content
V/MediaPlayerService(  249): prepare
V/AwesomePlayer(  249): prepareAsync
V/MediaPlayerService(  249): wait for prepare
V/AwesomePlayer(  249): onPrepareAsyncEvent
I/SecMediaClock(  249): SecMediaClock constructor
I/SecMediaClock(  249): reset
V/AwesomePlayer(  249): initAudioDecoder
V/AwesomePlayer(  249): checkOffloadExceptions is true
I/OMXCodec(  249): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
I/OMX     (  249): mDispatchers.add
I/OMXCodec(  249): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec(  249): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec(  249): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec(  249): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/OMXCodec(  249): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer(  249): finishAsyncPrepare_l
V/AwesomePlayer(  249): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache(  249): notify(0xb8830180, 200, 973, 0)
V/AudioCache(  249): ignored
V/AwesomePlayer(  249): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  249): notify(0xb8830180, 5, 0, 0)
V/AudioCache(  249): ignored
V/AwesomePlayer(  249): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  249): notify(0xb8830180, 1, 0, 0)
V/AudioCache(  249): prepared
V/AudioCache(  249): wait - success
V/MediaPlayerService(  249): start
V/StagefrightPlayer(  249): start
V/AwesomePlayer(  249): play
V/AwesomePlayer(  249): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer(  249): startAudioPlayer_l, sendErrorNotification (0)
I/OMXCodec(  249): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec(  249): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec(  249): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/AudioPlayer(  249):  Audioplayer kKeyAudioPCMFormat:1, 2, 0
I/AudioPlayer(  249):  Audioplayer kKeyAudioPCMFormat read fail(2, 1)
V/AudioCache(  249): open(44100, 2, 0x0, 1, 4)
V/AwesomePlayer(  249): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache(  249): notify(0xb8830180, 6, 0, 0)
V/AudioCache(  249): ignored
V/AwesomePlayer(  249): addBatteryData
V/MediaPlayerService(  249): wait for playback complete
I/SQLiteSecureOpenHelper( 2012): getWritableDatabase(pwd)
I/SQLiteSecureOpenHelper( 2012): getDatabaseLocked(b,b,pwd)...
I/SurfaceFlinger(  246): id=13 Removed CatteryCove (8/12)
I/SurfaceFlinger(  246): id=13 Removed CatteryCove (-2/12)
D/KeyguardUpdateMonitor( 1066): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1066): handleKeyguardVisibilityChanged(1)
I/OMXCodec(  249): [OMX.google.vorbis.decoder] End Of Stream
V/AwesomePlayer(  249): postAudioEOS delayUs (0)
V/AwesomePlayer(  249): onCheckAudioStatus
V/AwesomePlayer(  249): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  249): onStreamDone
V/AwesomePlayer(  249): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  249): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  249): notify(0xb8830180, 2, 0, 0)
V/AudioCache(  249): playback complete - thread will wake up later
V/AwesomePlayer(  249): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  249): notify(0xb8830180, 7, 0, 0)
V/AudioCache(  249): ignored
V/AwesomePlayer(  249): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer(  249): addBatteryData
V/AudioCache(  249): wait - success
V/StagefrightPlayer(  249): reset
V/AwesomePlayer(  249): reset_l()
V/AwesomePlayer(  249): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  249): notify(0xb8830180, 8, 0, 0)
V/AudioCache(  249): ignored
V/AwesomePlayer(  249): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  249): mAudioTrackVector clear
I/OMXCodec(  249): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec(  249): [OMX.google.vorbis.decoder] stop() sendCommand(0x41, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec(  249): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
I/OMXCodec(  249): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/OMX     (  249): instance freeNode
I/AudioPlayer(  249): reset out
V/AwesomePlayer(  249): reset_l() mAudioPlayer successfully deleted
I/SecMediaClock(  249): SecMediaClock destructor
V/AwesomePlayer(  249): mSecMediaClock clear
V/StagefrightPlayer(  249): ~StagefrightPlayer
V/StagefrightPlayer(  249): reset
V/AwesomePlayer(  249): reset_l()
V/AwesomePlayer(  249): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  249): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  249): mAudioTrackVector clear
V/AwesomePlayer(  249): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  249): mSecMediaClock clear
V/AwesomePlayer(  249): destructor
V/AwesomePlayer(  249): reset_l()
V/AwesomePlayer(  249): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  249): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  249): mAudioTrackVector clear
V/AwesomePlayer(  249): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  249): mSecMediaClock clear
V/MediaPlayer( 4445): decode(73, 37491572, 52024)
V/MediaPlayerService(  249): decode(35, 37491572, 52024)
V/MediaPlayerService(  249): player type = 3
V/AwesomePlayer(  249): setDefault
V/AwesomePlayer(  249): constructor
V/AwesomePlayer(  249): setDefault
V/AwesomePlayer(  249): reset_l()
V/AwesomePlayer(  249): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  249): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  249): mAudioTrackVector clear
V/AwesomePlayer(  249): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  249): mSecMediaClock clear
V/StagefrightPlayer(  249): StagefrightPlayer
V/AwesomePlayer(  249): setListener
V/StagefrightPlayer(  249): initCheck
V/AwesomePlayer(  249): setAudioSink
V/StagefrightPlayer(  249): setDataSource(35, 37491572, 52024)
V/AwesomePlayer(  249): reset_l()
V/AwesomePlayer(  249): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  249): notify(0xb8833fb8, 8, 0, 0)
V/AudioCache(  249): ignored
V/AwesomePlayer(  249): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  249): mAudioTrackVector clear
V/AwesomePlayer(  249): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  249): mSecMediaClock clear
V/AwesomePlayer(  249): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer(  249): mBitrate = -1 bits/sec
V/AwesomePlayer(  249): current audio track index (0) is added to vector
V/AwesomePlayer(  249): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer(  249): AwesomePlayer::setDataSource_l():: This is not a DRM content
V/MediaPlayerService(  249): prepare
V/AwesomePlayer(  249): prepareAsync
V/MediaPlayerService(  249): wait for prepare
V/AwesomePlayer(  249): onPrepareAsyncEvent
I/SecMediaClock(  249): SecMediaClock constructor
I/SecMediaClock(  249): reset
V/AwesomePlayer(  249): initAudioDecoder
V/AwesomePlayer(  249): checkOffloadExceptions is true
I/OMXCodec(  249): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
I/OMX     (  249): mDispatchers.add
I/OMXCodec(  249): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec(  249): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec(  249): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec(  249): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/OMXCodec(  249): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer(  249): finishAsyncPrepare_l
V/AwesomePlayer(  249): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache(  249): notify(0xb8833fb8, 200, 973, 0)
V/AudioCache(  249): ignored
V/AwesomePlayer(  249): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  249): notify(0xb8833fb8, 5, 0, 0)
V/AudioCache(  249): ignored
V/AwesomePlayer(  249): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  249): notify(0xb8833fb8, 1, 0, 0)
V/AudioCache(  249): prepared
V/AudioCache(  249): wait - success
V/MediaPlayerService(  249): start
V/StagefrightPlayer(  249): start
V/AwesomePlayer(  249): play
V/AwesomePlayer(  249): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer(  249): startAudioPlayer_l, sendErrorNotification (0)
I/OMXCodec(  249): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec(  249): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec(  249): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/AudioPlayer(  249):  Audioplayer kKeyAudioPCMFormat:1, 2, 0
I/AudioPlayer(  249):  Audioplayer kKeyAudioPCMFormat read fail(2, 1)
V/AudioCache(  249): open(48000, 2, 0x0, 1, 4)
V/AwesomePlayer(  249): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache(  249): notify(0xb8833fb8, 6, 0, 0)
V/AudioCache(  249): ignored
V/AwesomePlayer(  249): addBatteryData
V/MediaPlayerService(  249): wait for playback complete
W/ActivityManager(  723): Permission Denial: getCurrentUser() from pid=4555, uid=10179 requires android.permission.INTERACT_ACROSS_USERS
W/ActivityManager(  723): Permission Denial: getCurrentUser() from pid=4555, uid=10179 requires android.permission.INTERACT_ACROSS_USERS
V/WebViewChromium( 4555): Binding Chromium to the background looper Looper (main, tid 1) {422a8718}
I/chromium( 4555): [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserProcessMain( 4555): Initializing chromium process, renderers=0
W/chromium( 4555): [WARNING:proxy_service.cc(888)] PAC support disabled because there is no system implementation
,I/OMXCodec(  249): [OMX.google.vorbis.decoder] End Of Stream
,V/AwesomePlayer(  249): postAudioEOS delayUs (0)
,V/AwesomePlayer(  249): onCheckAudioStatus
V/AwesomePlayer(  249): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  249): onStreamDone
V/AwesomePlayer(  249): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  249): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  249): notify(0xb8833fb8, 2, 0, 0)
,V/AudioCache(  249): playback complete - thread will wake up later
V/AwesomePlayer(  249): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
,V/AudioCache(  249): notify(0xb8833fb8, 7, 0, 0)
V/AudioCache(  249): ignored
V/AwesomePlayer(  249): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer(  249): addBatteryData
V/AudioCache(  249): wait - success
,V/StagefrightPlayer(  249): reset
V/AwesomePlayer(  249): reset_l()
V/AwesomePlayer(  249): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  249): notify(0xb8833fb8, 8, 0, 0)
,V/AudioCache(  249): ignored
V/AwesomePlayer(  249): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  249): mAudioTrackVector clear
I/OMXCodec(  249): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec(  249): [OMX.google.vorbis.decoder] stop() sendCommand(0x42, OMX_CommandStateSet, OMX_StateIdle)
,I/OMXCodec(  249): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
I/OMXCodec(  249): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
,I/OMX     (  249): instance freeNode
,I/AudioPlayer(  249): reset out
V/AwesomePlayer(  249): reset_l() mAudioPlayer successfully deleted
I/SecMediaClock(  249): SecMediaClock destructor
V/AwesomePlayer(  249): mSecMediaClock clear
V/StagefrightPlayer(  249): ~StagefrightPlayer
V/StagefrightPlayer(  249): reset
V/AwesomePlayer(  249): reset_l()
,V/AwesomePlayer(  249): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  249): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  249): mAudioTrackVector clear
V/AwesomePlayer(  249): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  249): mSecMediaClock clear
V/AwesomePlayer(  249): destructor
,V/AwesomePlayer(  249): reset_l()
V/AwesomePlayer(  249): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  249): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  249): mAudioTrackVector clear
V/AwesomePlayer(  249): reset_l() mAudioPlayer successfully deleted
,V/AwesomePlayer(  249): mSecMediaClock clear
V/MediaPlayer( 4445): decode(74, 33969800, 9226)
,V/MediaPlayerService(  249): decode(36, 33969800, 9226)
,V/MediaPlayerService(  249): player type = 3
V/AwesomePlayer(  249): setDefault
V/AwesomePlayer(  249): constructor
V/AwesomePlayer(  249): setDefault
,V/AwesomePlayer(  249): reset_l()
V/AwesomePlayer(  249): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  249): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  249): mAudioTrackVector clear
V/AwesomePlayer(  249): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  249): mSecMediaClock clear
,V/StagefrightPlayer(  249): StagefrightPlayer
V/AwesomePlayer(  249): setListener
V/StagefrightPlayer(  249): initCheck
V/AwesomePlayer(  249): setAudioSink
V/StagefrightPlayer(  249): setDataSource(36, 33969800, 9226)
V/AwesomePlayer(  249): reset_l()
,V/AwesomePlayer(  249): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  249): notify(0xb8827cd8, 8, 0, 0)
V/AudioCache(  249): ignored
V/AwesomePlayer(  249): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  249): mAudioTrackVector clear
V/AwesomePlayer(  249): reset_l() mAudioPlayer successfully deleted
,V/AwesomePlayer(  249): mSecMediaClock clear
,V/AwesomePlayer(  249): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer(  249): mBitrate = -1 bits/sec
V/AwesomePlayer(  249): current audio track index (0) is added to vector
V/AwesomePlayer(  249): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer(  249): AwesomePlayer::setDataSource_l():: This is not a DRM content
V/MediaPlayerService(  249): prepare
,V/AwesomePlayer(  249): prepareAsync
V/MediaPlayerService(  249): wait for prepare
V/AwesomePlayer(  249): onPrepareAsyncEvent
I/SecMediaClock(  249): SecMediaClock constructor
I/SecMediaClock(  249): reset
V/AwesomePlayer(  249): initAudioDecoder
,V/AwesomePlayer(  249): checkOffloadExceptions is true
,I/OMXCodec(  249): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
,I/OMX     (  249): mDispatchers.add
I/OMXCodec(  249): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec(  249): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec(  249): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
,I/OMXCodec(  249): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/OMXCodec(  249): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer(  249): finishAsyncPrepare_l
V/AwesomePlayer(  249): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache(  249): notify(0xb8827cd8, 200, 973, 0)
V/AudioCache(  249): ignored
V/AwesomePlayer(  249): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  249): notify(0xb8827cd8, 5, 0, 0)
V/AudioCache(  249): ignored
V/AwesomePlayer(  249): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  249): notify(0xb8827cd8, 1, 0, 0)
V/AudioCache(  249): prepared
V/AudioCache(  249): wait - success
V/MediaPlayerService(  249): start
,V/StagefrightPlayer(  249): start
V/AwesomePlayer(  249): play
V/AwesomePlayer(  249): AwesomePlayer::play_l():: This is not a DRM content
,V/AwesomePlayer(  249): startAudioPlayer_l, sendErrorNotification (0)
I/OMXCodec(  249): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec(  249): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
,I/OMXCodec(  249): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/AudioPlayer(  249):  Audioplayer kKeyAudioPCMFormat:1, 2, 0
I/AudioPlayer(  249):  Audioplayer kKeyAudioPCMFormat read fail(2, 1)
,V/AudioCache(  249): open(44100, 2, 0x0, 1, 4)
V/AwesomePlayer(  249): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache(  249): notify(0xb8827cd8, 6, 0, 0)
V/AudioCache(  249): ignored
V/AwesomePlayer(  249): addBatteryData
,V/MediaPlayerService(  249): wait for playback complete
,I/OMXCodec(  249): [OMX.google.vorbis.decoder] End Of Stream
,V/AwesomePlayer(  249): postAudioEOS delayUs (0)
,V/AwesomePlayer(  249): onCheckAudioStatus
V/AwesomePlayer(  249): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  249): onStreamDone
V/AwesomePlayer(  249): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  249): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  249): notify(0xb8827cd8, 2, 0, 0)
V/AudioCache(  249): playback complete - thread will wake up later
V/AwesomePlayer(  249): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  249): notify(0xb8827cd8, 7, 0, 0)
V/AudioCache(  249): ignored
V/AwesomePlayer(  249): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer(  249): addBatteryData
V/AudioCache(  249): wait - success
V/StagefrightPlayer(  249): reset
V/AwesomePlayer(  249): reset_l()
V/AwesomePlayer(  249): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  249): notify(0xb8827cd8, 8, 0, 0)
V/AudioCache(  249): ignored
V/AwesomePlayer(  249): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  249): mAudioTrackVector clear
I/OMXCodec(  249): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec(  249): [OMX.google.vorbis.decoder] stop() sendCommand(0x43, OMX_CommandStateSet, OMX_StateIdle)
,I/OMXCodec(  249): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
I/OMXCodec(  249): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
,I/OMX     (  249): instance freeNode
I/AudioPlayer(  249): reset out
V/AwesomePlayer(  249): reset_l() mAudioPlayer successfully deleted
I/SecMediaClock(  249): SecMediaClock destructor
V/AwesomePlayer(  249): mSecMediaClock clear
V/StagefrightPlayer(  249): ~StagefrightPlayer
V/StagefrightPlayer(  249): reset
V/AwesomePlayer(  249): reset_l()
V/AwesomePlayer(  249): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  249): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  249): mAudioTrackVector clear
V/AwesomePlayer(  249): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  249): mSecMediaClock clear
V/AwesomePlayer(  249): destructor
V/AwesomePlayer(  249): reset_l()
V/AwesomePlayer(  249): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  249): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  249): mAudioTrackVector clear
V/AwesomePlayer(  249): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  249): mSecMediaClock clear
V/MediaPlayer( 4445): decode(75, 30402580, 4509)
,V/MediaPlayerService(  249): decode(35, 30402580, 4509)
V/MediaPlayerService(  249): player type = 3
V/AwesomePlayer(  249): setDefault
,V/AwesomePlayer(  249): constructor
V/AwesomePlayer(  249): setDefault
V/AwesomePlayer(  249): reset_l()
V/AwesomePlayer(  249): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  249): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  249): mAudioTrackVector clear
V/AwesomePlayer(  249): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  249): mSecMediaClock clear
V/StagefrightPlayer(  249): StagefrightPlayer
V/AwesomePlayer(  249): setListener
V/StagefrightPlayer(  249): initCheck
V/AwesomePlayer(  249): setAudioSink
V/StagefrightPlayer(  249): setDataSource(35, 30402580, 4509)
V/AwesomePlayer(  249): reset_l()
V/AwesomePlayer(  249): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  249): notify(0xb883b460, 8, 0, 0)
V/AudioCache(  249): ignored
V/AwesomePlayer(  249): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  249): mAudioTrackVector clear
V/AwesomePlayer(  249): reset_l() mAudioPlayer successfully deleted
,V/AwesomePlayer(  249): mSecMediaClock clear
V/AwesomePlayer(  249): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer(  249): mBitrate = -1 bits/sec
V/AwesomePlayer(  249): current audio track index (0) is added to vector
V/AwesomePlayer(  249): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer(  249): AwesomePlayer::setDataSource_l():: This is not a DRM content
V/MediaPlayerService(  249): prepare
V/AwesomePlayer(  249): prepareAsync
V/MediaPlayerService(  249): wait for prepare
V/AwesomePlayer(  249): onPrepareAsyncEvent
I/SecMediaClock(  249): SecMediaClock constructor
I/SecMediaClock(  249): reset
V/AwesomePlayer(  249): initAudioDecoder
V/AwesomePlayer(  249): checkOffloadExceptions is true
,I/OMXCodec(  249): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
I/OMX     (  249): mDispatchers.add
I/OMXCodec(  249): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec(  249): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
,I/OMXCodec(  249): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec(  249): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/OMXCodec(  249): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer(  249): finishAsyncPrepare_l
V/AwesomePlayer(  249): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache(  249): notify(0xb883b460, 200, 973, 0)
V/AudioCache(  249): ignored
V/AwesomePlayer(  249): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  249): notify(0xb883b460, 5, 0, 0)
V/AudioCache(  249): ignored
V/AwesomePlayer(  249): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  249): notify(0xb883b460, 1, 0, 0)
V/AudioCache(  249): prepared
V/AudioCache(  249): wait - success
V/MediaPlayerService(  249): start
V/StagefrightPlayer(  249): start
V/AwesomePlayer(  249): play
V/AwesomePlayer(  249): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer(  249): startAudioPlayer_l, sendErrorNotification (0)
I/OMXCodec(  249): [OMX.google.vorbis.decoder] End Of Stream
I/OMXCodec(  249): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec(  249): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec(  249): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/AudioPlayer(  249):  Audioplayer kKeyAudioPCMFormat:1, 2, 0
I/AudioPlayer(  249):  Audioplayer kKeyAudioPCMFormat read fail(2, 1)
V/AudioCache(  249): open(44100, 2, 0x0, 1, 4)
V/AwesomePlayer(  249): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache(  249): notify(0xb883b460, 6, 0, 0)
V/AudioCache(  249): ignored
V/AwesomePlayer(  249): addBatteryData
V/MediaPlayerService(  249): wait for playback complete
I/AudioPlayer(  249): First fillBuffer call!!
V/AwesomePlayer(  249): postAudioEOS delayUs (0)
V/AwesomePlayer(  249): onCheckAudioStatus
V/AwesomePlayer(  249): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  249): onStreamDone
V/AwesomePlayer(  249): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  249): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  249): notify(0xb883b460, 2, 0, 0)
V/AudioCache(  249): playback complete - thread will wake up later
V/AwesomePlayer(  249): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  249): notify(0xb883b460, 7, 0, 0)
V/AudioCache(  249): ignored
V/AwesomePlayer(  249): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer(  249): addBatteryData
V/AudioCache(  249): wait - success
V/StagefrightPlayer(  249): reset
V/AwesomePlayer(  249): reset_l()
V/AwesomePlayer(  249): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  249): notify(0xb883b460, 8, 0, 0)
V/AudioCache(  249): ignored
V/AwesomePlayer(  249): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  249): mAudioTrackVector clear
I/OMXCodec(  249): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec(  249): [OMX.google.vorbis.decoder] stop() sendCommand(0x44, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec(  249): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
I/OMXCodec(  249): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/OMX     (  249): instance freeNode
I/AudioPlayer(  249): reset out
V/AwesomePlayer(  249): reset_l() mAudioPlayer successfully deleted
I/SecMediaClock(  249): SecMediaClock destructor
V/AwesomePlayer(  249): mSecMediaClock clear
V/StagefrightPlayer(  249): ~StagefrightPlayer
V/StagefrightPlayer(  249): reset
V/AwesomePlayer(  249): reset_l()
V/AwesomePlayer(  249): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  249): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  249): mAudioTrackVector clear
V/AwesomePlayer(  249): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  249): mSecMediaClock clear
V/AwesomePlayer(  249): destructor
V/AwesomePlayer(  249): reset_l()
V/AwesomePlayer(  249): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  249): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  249): mAudioTrackVector clear
V/AwesomePlayer(  249): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  249): mSecMediaClock clear
,I/SELinux ( 4599): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 4599):  
I/ActivityManager(  723): Killing 3193:com.sec.android.app.camera/u0a147 (adj 15): empty #43
,I/SELinux ( 4599): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 4599):  
I/SELinux ( 4599):  
,I/SELinux ( 4599): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 4599): [DEBUG] seapp_context_lookup: seinfoCategory = default
E/dalvikvm( 4599): >>>>> Normal User
E/dalvikvm( 4599): >>>>> com.osp.app.signin [ userId:0 | appId:10043 ]
,E/SELinux ( 4599): [DEBUG] seapp_context_lookup: seinfoCategory = default
,D/TimaKeyStoreProvider( 4599): in addTimaSignatureService
,D/TimaKeyStoreProvider( 4599): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 4599): Added TimaKesytore provider
,I/SA      ( 4599): [SSP] onCreated
,I/SA      ( 4599): [TPM] There is no property file
,I/SA      ( 4599): [SCU] isHaveSA() - false
I/SA      ( 4599): [TPM] getModelProperty : null
,I/SA      ( 4599): [TPM] getCSCProperty : null
,I/SA      ( 4599): [PMR] Received action : android.intent.action.PACKAGE_ADDED
,I/SA      ( 4599): [DM] init START
,I/SA      ( 4599): [DM] This device is not a Vodafone
I/SA      ( 4599): [DM] getCountryCodeFromCSC : PL
,I/SA      ( 4599): support phone number id : false
I/SA      ( 4599): [DM] init END
,I/SA      ( 4599): [SUR] onReceive log=[SA = 2.0.0117 V = 19 HWD = 1280X720 2.0 dpi = 320  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = kmini3g P = kmini3gxx I = KOT49H M = SM-G800H OKLEFT false DIS KOT49H.G800HXXU1ANK2 PSS = 4.497045606779314  ]
,I/SA      ( 4599): [SUR] onReceive Intent=[ action.PACKAGE_ADDED. package ]
I/ActivityManager(  723): Killing 3299:com.android.email/u0a155 (adj 15): empty #43
,D/Mms/PackageInstallReceiver( 3803): loadAuthorityPref(): sEnableAuthority = true
,I/IcingCorporaProvider( 2120): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
W/ContextImpl( 2854): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1857 android.content.ContextWrapper.startService:506 android.content.ContextWrapper.startService:506 com.samsung.android.app.assistantmenu.AssistantMenuReceiver.onReceive:153 android.app.ActivityThread.handleReceiver:2698 
,I/SELinux ( 4618): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 4618):  
,I/SELinux ( 4618): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 4618):  
I/SELinux ( 4618):  
,I/SELinux ( 4618): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 4618): [DEBUG] seapp_context_lookup: seinfoCategory = samsung
E/dalvikvm( 4618): >>>>> Normal User
,E/dalvikvm( 4618): >>>>> com.sec.android.service.cm [ userId:0 | appId:10078 ]
,E/SELinux ( 4618): [DEBUG] seapp_context_lookup: seinfoCategory = samsung
,D/TimaKeyStoreProvider( 4618): in addTimaSignatureService
,D/TimaKeyStoreProvider( 4618): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 4618): Added TimaKesytore provider
,I/IcingCorporaProvider( 2120): UpdateCorporaTask done [took 153 ms] updated apps [took 153 ms] 
,W/ActivityManager(  723): Permission Denial: getCurrentUser() from pid=4618, uid=10078 requires android.permission.INTERACT_ACROSS_USERS
D/CapabilityManagerService New( 4618): Receiver Broadcast:android.intent.action.PACKAGE_ADDED
,I/SELinux ( 4631): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 4631):  
I/ActivityManager(  723): Killing 3294:com.samsung.android.provider.shootingmodeprovider/u0a162 (adj 15): empty #43
,I/SELinux ( 4631): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 4631):  
I/SELinux ( 4631):  
,I/SELinux ( 4631): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 4631): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 4631): >>>>> Normal User
,E/dalvikvm( 4631): >>>>> com.google.android.apps.docs [ userId:0 | appId:10090 ]
,E/SELinux ( 4631): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
,D/TimaKeyStoreProvider( 4631): in addTimaSignatureService
,D/TimaKeyStoreProvider( 4631): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 4631): Added TimaKesytore provider
,I/Adreno-EGL( 4555): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 4555): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 4555): Build Date: 03/21/14 Fri
I/Adreno-EGL( 4555): Local Branch: AU200+patches_03212014
I/Adreno-EGL( 4555): Remote Branch: 
I/Adreno-EGL( 4555): Local Patches: 
I/Adreno-EGL( 4555): Reconstruct Branch: 
,I/SurfaceFlinger(  246): id=7 Removed Mauncher (7/11)
,I/SurfaceFlinger(  246): id=7 Removed Mauncher (-2/11)
,D/KeyguardUpdateMonitor( 1066): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1066): handleKeyguardVisibilityChanged(1)
I/SecureStorage(  296): [INFO]: SPID(0x00000003)Secure Storage Daemon finished processing with result: 0
,I/SecureStorage(  296): [INFO]: SPID(0x00000003)PID: 4471, TID: 4471
,D/SurfaceWidgetClient$ISurfaceWidgetStub( 1443): [237392/5] Surface widget visibility changed visibility = false on instance = 1
,D/Launcher( 1254): onTrimMemory. Level: 20
,I/SecureStorage( 4471): [INFO]: SPID(0x00000000)Processing data has been completed
I/SecureStorage( 4471): [INFO]: SPID(0x00000000)WARNING! Failed to find SecureStorageExceptionJNI!..
I/SQLiteSecureOpenHelper( 4471): getWritableDatabase(pwd)
I/SQLiteSecureOpenHelper( 4471): getDatabaseLocked(b,b,pwd)...
,I/SQLiteSecureOpenHelper( 4471): Open platform.db in secure mode
,I/dalvikvm( 4555): Could not find method android.webkit.CookieManager.setAcceptThirdPartyCookies, referenced from method org.apache.cordova.engine.SystemCookieManager.<init>
,W/dalvikvm( 4555): VFY: unable to resolve virtual method 252: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
D/dalvikvm( 4555): VFY: replacing opcode 0x6e at 0x0016
I/dalvikvm( 4555): Could not find method android.webkit.CookieManager.flush, referenced from method org.apache.cordova.engine.SystemCookieManager.flush
W/dalvikvm( 4555): VFY: unable to resolve virtual method 247: Landroid/webkit/CookieManager;.flush ()V
,D/dalvikvm( 4555): VFY: replacing opcode 0x6e at 0x0008
,W/dalvikvm( 4555): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
,W/dalvikvm( 4555): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
I/dalvikvm( 4555): Could not find method android.webkit.WebViewClient.onReceivedClientCertRequest, referenced from method org.apache.cordova.engine.SystemWebViewClient.onReceivedClientCertRequest
W/dalvikvm( 4555): VFY: unable to resolve virtual method 305: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
,D/dalvikvm( 4555): VFY: replacing opcode 0x6f at 0x001a
,W/dalvikvm( 4555): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
I/dalvikvm( 4555): Could not find method android.webkit.PermissionRequest.getResources, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onPermissionRequest
W/dalvikvm( 4555): VFY: unable to resolve virtual method 263: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
D/dalvikvm( 4555): VFY: replacing opcode 0x6e at 0x000d
,I/dalvikvm( 4555): Could not find method android.webkit.WebChromeClient$FileChooserParams.createIntent, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onShowFileChooser
W/dalvikvm( 4555): VFY: unable to resolve virtual method 268: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
,D/dalvikvm( 4555): VFY: replacing opcode 0x6e at 0x0000
,D/SystemWebViewEngine( 4555): CordovaWebView is running on device made by: samsung
I/SQLiteSecureOpenHelper( 4471): ...getDatabaseLocked(b,b,pwd)
,D/SQLiteSecureOpenHelper( 4471): ...getDatabaseLocked(b,b,pwd)
,I/ActivityManager(  723): Killing 3325:com.sec.modem.settings/1000 (adj 15): empty #43
,I/SurfaceFlinger(  246): id=16 createSurf (1x1),1 flag=404, NainActivit
,W/ActivityManager(  723): Permission Denial: getCurrentUser() from pid=4631, uid=10090 requires android.permission.INTERACT_ACROSS_USERS
D/KeyguardUpdateMonitor( 1066): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1066): handleKeyguardVisibilityChanged(1)
,D/KeyguardUpdateMonitor( 1066): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1066): handleKeyguardVisibilityChanged(1)
,I/HWUI    ( 4555): EGLImpl-HWUI Protected EGL context created
,D/OpenGLRenderer( 4555): Enabling debug mode 0
,D/KeyguardUpdateMonitor( 1066): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1066): handleKeyguardVisibilityChanged(1)
,D/CustomFrequencyManagerService(  723): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 723  pkgName : ACTIVITY_RESUME_BOOSTER@9
,D/CustomFrequencyManagerService(  723): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 723  tag : ACTIVITY_RESUME_BOOSTER@5
,D/CustomFrequencyManagerService(  723): FrequencyrequestList.getNextMaxCPUCoreRequest, index: 0
,W/ActivityManager(  723): mDVFSHelper.release()
D/KeyguardUpdateMonitor( 1066): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1066): handleKeyguardVisibilityChanged(1)
,W/ContextImpl(  723): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/JsMessageQueue( 4555): Set native->JS mode to OnlineEventsBridgeMode
,I/SELinux ( 4665): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 4665):  
I/ActivityManager(  723): Killing 1332:com.sec.android.provider.badge/u0a72 (adj 15): empty #43
,W/GAV2    ( 4631): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,I/SELinux ( 4665): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 4665):  
I/SELinux ( 4665):  
,I/SELinux ( 4665): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 4665): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 4665): >>>>> Normal User
,E/dalvikvm( 4665): >>>>> com.samsung.android.app.watchmanagerstub [ userId:0 | appId:10100 ]
,D/dalvikvm( 4555): Trying to load lib /data/app-lib/com.test.thalitest-8/libjxcore.so 0x425cf4a0
,E/SELinux ( 4665): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/dalvikvm( 4555): Added shared lib /data/app-lib/com.test.thalitest-8/libjxcore.so 0x425cf4a0
,D/jxcore_app_log( 4555): JniHelper::setJavaVM(0x416f3528), pthread_self() = 2033417928
,D/TimaKeyStoreProvider( 4665): in addTimaSignatureService
,D/TimaKeyStoreProvider( 4665): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 4665): Added TimaKesytore provider
,I/chromium( 4555): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot call method 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,D/PackageIntentReceiver( 4665): ACTION_PACKAGE_ADDED
,D/PackageIntentReceiver( 4665): Not GearManger package! 
,I/SELinux ( 4682): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 4682):  
,I/SELinux ( 4682): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 4682):  
I/SELinux ( 4682):  
,I/SELinux ( 4682): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 4682): [DEBUG] seapp_context_lookup: seinfoCategory = release
E/dalvikvm( 4682): >>>>> Normal User
,E/dalvikvm( 4682): >>>>> com.samsung.android.magazine.service [ userId:0 | appId:10106 ]
,E/SELinux ( 4682): [DEBUG] seapp_context_lookup: seinfoCategory = release
,D/TimaKeyStoreProvider( 4682): in addTimaSignatureService
,D/TimaKeyStoreProvider( 4682): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 4682): Added TimaKesytore provider
,I/Icing   ( 1756): Indexing 04B0A0E440E57B3CEEF518675F9B8A06EBE0353B from com.google.android.googlequicksearchbox
,D/MagazineService Version( 4682): Magazine-Channel: 13
,D/MagazineService Version( 4682): Magazine-Provider: 13
,D/MagazineService Version( 4682): Magazine-Administrator: 11
,D/HeadlinesChannelApplication( 4682): [onCreate]
,D/MagazineService::MagazineBroadcastReceiver( 4682): [onReceive] android.intent.action.PACKAGE_ADDED com.test.thalitest
W/ActivityManager(  723): Permission Denial: getCurrentUser() from pid=4682, uid=10106 requires android.permission.INTERACT_ACROSS_USERS
,I/MagazineService::MagazineService( 4682): [onHandleIntent] ACTION_PACKAGE_INSTALLED
,I/SELinux ( 4695): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 4695):  
,D/MagazineService::MagazineService( 4682): [onHandleIntent] Send broadcast to (com.test.thalitest).
,W/GAV2    ( 4631): Thread[main,5,main]: dispatch call queued.  Need to call GAServiceManager.getInstance().initialize().
I/ActivityManager(  723): Killing 3345:tv.peel.smartremote/u0a163 (adj 15): empty #43
,I/ActivityManager(  723): Killing 3379:org.simalliance.openmobileapi.service/1101 (adj 15): empty #43
,I/SELinux ( 4695): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 4695):  
I/SELinux ( 4695):  
,I/SELinux ( 4695): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 4695): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 4695): >>>>> Normal User
,E/dalvikvm( 4695): >>>>> com.samsung.helphub [ userId:0 | appId:1000 ]
,E/SELinux ( 4695): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 4695): in addTimaSignatureService
,D/TimaKeyStoreProvider( 4695): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 4695): Added TimaKesytore provider
,I/Icing   ( 1756): Indexing done 04B0A0E440E57B3CEEF518675F9B8A06EBE0353B
,D/dalvikvm( 4555): GC_CONCURRENT freed 4953K, 34% free 12736K/19060K, paused 3ms+3ms, total 42ms
D/dalvikvm( 4555): WAIT_FOR_CONCURRENT_GC blocked 18ms
,D/dalvikvm( 4555): WAIT_FOR_CONCURRENT_GC blocked 25ms
,I/SELinux ( 4709): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 4709):  
I/ActivityManager(  723): Killing 3429:com.sec.android.app.taskmanager/u0a166 (adj 15): empty #43
,V/AlarmManager(  723): waitForAlarm result :4
,V/AlarmManager(  723): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,I/SELinux ( 4709): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 4709):  
I/SELinux ( 4709):  
,I/SELinux ( 4709): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 4709): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 4709): >>>>> Normal User
E/dalvikvm( 4709): >>>>> com.sec.kidsplat.installer [ userId:0 | appId:10158 ]
,E/SELinux ( 4709): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 4709): in addTimaSignatureService
,D/TimaKeyStoreProvider( 4709): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 4709): Added TimaKesytore provider
,D/dalvikvm( 3544): GC_CONCURRENT freed 6642K, 43% free 10947K/19060K, paused 6ms+4ms, total 40ms
,D/CustomFrequencyManagerService(  723): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 723  tag : ACTIVITY_RESUME_BOOSTER@9
,W/ActivityManager(  723): Permission Denial: getCurrentUser() from pid=4709, uid=10158 requires android.permission.INTERACT_ACROSS_USERS
,D/KidsPlatformStub( 4709): Package not found : com.sec.android.app.kidshome
,I/SELinux ( 4721): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 4721):  
,E/SMD     (  240): DCD OFF
I/ActivityManager(  723): Killing 3444:com.samsung.android.service.travel/u0a169 (adj 15): empty #43
,I/SELinux ( 4721): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 4721):  
I/SELinux ( 4721):  
,I/SELinux ( 4721): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 4721): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 4721): >>>>> Normal User
,E/dalvikvm( 4721): >>>>> com.samsung.android.provider.shootingmodeprovider [ userId:0 | appId:10162 ]
,E/SELinux ( 4721): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 4721): in addTimaSignatureService
,D/TimaKeyStoreProvider( 4721): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 4721): Added TimaKesytore provider
,I/SELinux ( 4733): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 4733):  
I/ActivityManager(  723): Killing 3457:com.google.android.youtube/u0a175 (adj 15): empty #43
,I/SELinux ( 4733): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 4733):  
I/SELinux ( 4733):  
,I/SELinux ( 4733): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 4733): [DEBUG] seapp_context_lookup: seinfoCategory = samsung
E/dalvikvm( 4733): >>>>> Normal User
,E/dalvikvm( 4733): >>>>> com.sec.android.app.samsungapps [ userId:0 | appId:10040 ]
,E/SELinux ( 4733): [DEBUG] seapp_context_lookup: seinfoCategory = samsung
,D/TimaKeyStoreProvider( 4733): in addTimaSignatureService
,D/TimaKeyStoreProvider( 4733): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 4733): Added TimaKesytore provider
,D/dalvikvm( 4555): GC_CONCURRENT freed 4640K, 28% free 16271K/22300K, paused 1ms+5ms, total 41ms
D/dalvikvm( 4555): WAIT_FOR_CONCURRENT_GC blocked 28ms
,D/dalvikvm( 4555): WAIT_FOR_CONCURRENT_GC blocked 26ms
,D/Finsky  ( 3544): [349] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 3544): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,I/ActivityManager(  723): Killing 3650:com.sec.android.widgetapp.activeapplicationwidget/u0a152 (adj 15): empty #43
,D/Finsky  ( 3544): [1] ExternalReferrer.access$200: Package state data is missing for com.test.thalitest
,D/ChimeraCfgMgr( 1756): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 1756): Loading module APK com.google.android.play.games
,D/PackageBroadcastService( 1756): Received broadcast action=android.intent.action.PACKAGE_ADDED and uri=com.test.thalitest
,I/dalvikvm( 1756): Could not find method android.app.admin.DevicePolicyManager.getProfileOwner, referenced from method com.google.android.gms.auth.WorkAccountAuthenticatorInitializer.a
W/dalvikvm( 1756): VFY: unable to resolve virtual method 174: Landroid/app/admin/DevicePolicyManager;.getProfileOwner ()Landroid/content/ComponentName;
,D/dalvikvm( 1756): VFY: replacing opcode 0x6e at 0x0053
,I/dalvikvm( 1756): Failed resolving Lcom/google/android/gms/common/permission/PermissionUtils$1; interface 96 'Landroid/content/pm/PackageManager$OnPermissionsChangedListener;'
,W/dalvikvm( 1756): Link of class 'Lcom/google/android/gms/common/permission/PermissionUtils$1;' failed
E/dalvikvm( 1756): Could not find class 'com.google.android.gms.common.permission.PermissionUtils$1', referenced from method com.google.android.gms.chimera.GmsModuleInitializer.initializeModuleV0
W/dalvikvm( 1756): VFY: unable to resolve new-instance 2374 (Lcom/google/android/gms/common/permission/PermissionUtils$1;) in Lcom/google/android/gms/chimera/GmsModuleInitializer;
,D/dalvikvm( 1756): VFY: replacing opcode 0x22 at 0x001a
,I/dalvikvm( 1756): Failed resolving Lcom/google/android/gms/common/permission/PermissionUtils$1; interface 96 'Landroid/content/pm/PackageManager$OnPermissionsChangedListener;'
W/dalvikvm( 1756): Link of class 'Lcom/google/android/gms/common/permission/PermissionUtils$1;' failed
,D/dalvikvm( 1756): DexOpt: unable to opt direct call 0x338d at 0x1c in Lcom/google/android/gms/chimera/GmsModuleInitializer;.initializeModuleV0
,D/ChimeraCfgMgr( 1756): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 1756): Module APK com.google.android.play.games already loaded
,D/ChimeraCfgMgr( 1756): Loading module com.google.android.gms.gass from APK com.google.android.gms
,D/AsyncTaskServiceImpl( 1756): Submit a task: k
,D/dalvikvm(  723): GC_EXPLICIT freed 2538K, 59% free 23453K/57076K, paused 7ms+12ms, total 134ms
,D/dalvikvm( 4555): GC_FOR_ALLOC freed 5165K, 31% free 17272K/24972K, paused 35ms, total 37ms
,I/dalvikvm-heap( 4555): Grow heap (frag case) to 22.549MB for 2459024-byte allocation
,D/ChimeraCfgMgr( 1756): Loading module com.google.android.gms.gass from APK com.google.android.gms
,W/BaseAppContext( 1756): Using Auth Proxy for data requests.
,W/BaseAppContext( 1756): Using Auth Proxy for data requests.
,D/ChimeraCfgMgr( 1756): Loading module com.google.android.gms.vision from APK com.google.android.gms
,D/k       ( 1756): Processing package: com.test.thalitest
,W/BaseAppContext( 1756): Using Auth Proxy for data requests.
,D/GassUtils( 1756): Found app info for package com.test.thalitest:18. Hash: 4eebbbb84f07ed56a3e96e5e8f9d6abddaaf154fffa2a65432a1006e0fa38f32
,D/k       ( 1756): Found info for package com.test.thalitest in db.
,W/BaseAppContext( 1756): Using Auth Proxy for data requests.
W/dalvikvm( 1756): VFY: unable to find class referenced in signature (Landroid/app/SharedElementCallback;)
I/dalvikvm( 1756): Could not find method android.app.Activity.setEnterSharedElementCallback, referenced from method android.support.v4.app.w.setEnterSharedElementCallback
W/dalvikvm( 1756): VFY: unable to resolve virtual method 53: Landroid/app/Activity;.setEnterSharedElementCallback (Landroid/app/SharedElementCallback;)V
,D/dalvikvm( 1756): VFY: replacing opcode 0x6e at 0x000e
W/dalvikvm( 1756): VFY: unable to find class referenced in signature (Landroid/app/SharedElementCallback;)
I/dalvikvm( 1756): Could not find method android.app.Activity.setExitSharedElementCallback, referenced from method android.support.v4.app.w.setExitSharedElementCallback
W/dalvikvm( 1756): VFY: unable to resolve virtual method 54: Landroid/app/Activity;.setExitSharedElementCallback (Landroid/app/SharedElementCallback;)V
,D/dalvikvm( 1756): VFY: replacing opcode 0x6e at 0x000e
I/dalvikvm( 1756): Could not find method android.app.Activity.finishAfterTransition, referenced from method android.support.v4.app.w.supportFinishAfterTransition
W/dalvikvm( 1756): VFY: unable to resolve virtual method 31: Landroid/app/Activity;.finishAfterTransition ()V
D/dalvikvm( 1756): VFY: replacing opcode 0x6e at 0x0006
I/dalvikvm( 1756): Could not find method android.app.Activity.postponeEnterTransition, referenced from method android.support.v4.app.w.supportPostponeEnterTransition
W/dalvikvm( 1756): VFY: unable to resolve virtual method 49: Landroid/app/Activity;.postponeEnterTransition ()V
D/dalvikvm( 1756): VFY: replacing opcode 0x6e at 0x0006
I/dalvikvm( 1756): Could not find method android.app.Activity.startPostponedEnterTransition, referenced from method android.support.v4.app.w.supportStartPostponedEnterTransition
W/dalvikvm( 1756): VFY: unable to resolve virtual method 61: Landroid/app/Activity;.startPostponedEnterTransition ()V
,D/dalvikvm( 1756): VFY: replacing opcode 0x6e at 0x0006
W/BaseAppContext( 1756): Using Auth Proxy for data requests.
,W/BaseAppContext( 1756): Using Auth Proxy for data requests.
,W/BaseAppContext( 1756): Using Auth Proxy for data requests.
,I/PeopleDatabaseHelper( 1756): cleanUpNonGplusAccounts done.
,D/dalvikvm( 1318): GC_EXPLICIT freed 781K, 44% free 10795K/19060K, paused 2ms+4ms, total 33ms
,D/dalvikvm( 4555): GC_FOR_ALLOC freed 3741K, 35% free 17980K/27376K, paused 34ms, total 35ms
,W/dalvikvm( 1756): VFY: unable to find class referenced in signature (Landroid/util/Size;)
,D/ChimeraCfgMgr( 1756): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 1756): Module APK com.google.android.play.games already loaded
,D/dalvikvm( 4555): GC_FOR_ALLOC freed 1186K, 35% free 17889K/27376K, paused 30ms, total 30ms
,D/dalvikvm( 4555): GC_FOR_ALLOC freed 4543K, 38% free 19213K/30980K, paused 32ms, total 35ms
,W/PluginManager( 4555): THREAD WARNING: exec() call to JXcore.isReady blocked the main thread for 36ms. Plugin should use CordovaInterface.getThreadPool().
,W/jxcore-log( 4555): Initializing JXcore engine
,W/jxcore-log( 4555): JXcore engine is ready
,W/jxcore-log( 4555): Starting JXcore engine
,W/jxcore-log( 4555): Platform android
W/jxcore-log( 4555): 
,W/jxcore-log( 4555): Process ARCH arm
W/jxcore-log( 4555): 
,I/Icing   ( 1756): Indexing 49CA7E3A917E607C6D98AA15891295369CED2106 from com.google.android.gms
,D/dalvikvm( 1756): GC_CONCURRENT freed 1442K, 38% free 11827K/19060K, paused 3ms+6ms, total 36ms
,I/Icing   ( 1756): Indexing done 49CA7E3A917E607C6D98AA15891295369CED2106
,I/jxcore-log( 4555): JXcore Cordova bridge is ready!
I/jxcore-log( 4555): 
,W/jxcore-log( 4555): JXcore engine is started
,E/jxcore  ( 4555): Error!: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js
E/jxcore  ( 4555): Stack: [{"_fileName":"node.js","_functionName":"$h.require","_lineNumber":"1472","_columnNumber":"1","_msg":"    at $h.require@node.js:1472:1"},{"_fileName":"main.js.js","_functionName":"internal_methods.loadMainFile","_lineNumber":"260","_columnNumber":"5","_msg":"    at internal_methods.loadMainFile@main.js.js:260:5"},{"_fileName":"main.js.js","_functionName":"JXMobile.executeJSON","_lineNumber":"279","_columnNumber":"7","_msg":"    at JXMobile.executeJSON@main.js.js:279:7"},{"_fileName":"JX_Evaluate","_functionName":"","_lineNumber":"1","_columnNumber":"1","_msg":"    at @JX_Evaluate:1:1"},{"_fileName":"node.js","_functionName":"unknown","_lineNumber":"1472","_columnNumber":"1","_msg":""}]
,I/chromium( 4555): [INFO:CONSOLE(37)] "App.js file failed to load : "No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\nError: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\n    at $h.require@node.js:1472:1\n    at internal_methods.loadMainFile@main.js.js:260:5\n    at JXMobile.executeJSON@main.js.js:279:7\n    at @JX_Evaluate:1:1\n"", source: file:///android_asset/www/js/thali_main.js (37)
,D/LockPatternUtils( 1066): isPcwEnable = null
I/ActivityManager(  723): Killing 3706:com.sec.android.app.sns3/u0a36 (adj 15): empty #43
,I/SurfaceFlinger(  246): id=16 Removed NainActivit (7/11)
,I/SurfaceFlinger(  246): id=16 Removed NainActivit (-2/11)
,D/KeyguardUpdateMonitor( 1066): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1066): handleKeyguardVisibilityChanged(1)
D/CustomFrequencyManagerService(  723): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 723  pkgName : ACTIVITY_RESUME_BOOSTER@5
,W/ActivityManager(  723): mDVFSHelper.acquire()
D/KeyguardUpdateMonitor( 1066): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1066): handleKeyguardVisibilityChanged(1)
,D/KeyguardUpdateMonitor( 1066): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1066): handleKeyguardVisibilityChanged(1)
,D/LockPatternUtils( 1066): isPcwEnable = null
,D/SurfaceWidgetView( 1254): destroyHardwareResources():1125975184
,D/KeyguardUpdateMonitor( 1066): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1066): handleKeyguardVisibilityChanged(1)
,D/KeyguardUpdateMonitor( 1066): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1066): handleKeyguardVisibilityChanged(1)
D/Launcher( 1254): onRestart, Launcher: 1114039512
D/Launcher( 1254): onStart, Launcher: 1114039512
,D/Launcher.HomeView( 1254): onStart
,D/SurfaceWidgetClient$ISurfaceWidgetStub( 1443): [237392/5] Surface widget visibility changed visibility = true on instance = 1
,D/SurfaceWidget.Renderer( 1443): [237392/5] SurfaceWidget drawing first frame
,I/SurfaceFlinger(  246): id=17 createSurf (1x1),2 flag=404, CatteryCove
,D/KeyguardUpdateMonitor( 1066): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1066): handleKeyguardVisibilityChanged(1)
,I/SurfaceFlinger(  246): id=18 createSurf (720x1280),1 flag=4, Mauncher
,D/KeyguardUpdateMonitor( 1066): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1066): handleKeyguardVisibilityChanged(1)
,D/Launcher.HomeView( 1254): onStop
,D/KeyguardUpdateMonitor( 1066): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1066): handleKeyguardVisibilityChanged(1)
,D/KeyguardUpdateMonitor( 1066): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1066): handleKeyguardVisibilityChanged(1)
,D/KeyguardUpdateMonitor( 1066): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1066): handleKeyguardVisibilityChanged(1)
,D/CustomFrequencyManagerService(  723): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 723  tag : ACTIVITY_RESUME_BOOSTER@5
,W/ActivityManager(  723): mDVFSHelper.release()
,D/KeyguardUpdateMonitor( 1066): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1066): handleKeyguardVisibilityChanged(1)
D/CustomFrequencyManagerService(  723): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 723  pkgName : ACTIVITY_RESUME_BOOSTER@9
,E/SMD     (  240): DCD OFF
,D/CustomFrequencyManagerService(  723): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 723  tag : ACTIVITY_RESUME_BOOSTER@9
,I/GAV2    ( 4631): Thread[GAThread,5,main]: No campaign data found.
,E/SMD     (  240): DCD OFF
,D/AmoledAdjustTimer(  723): prevTemp = 283, currTemp = 283, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP(  723): SIOP:: AP = 310, Delta = 0
,I/HarmonyEASService(  723): Updating for all 1
,E/SMD     (  240): DCD OFF
,E/SMD     (  240): DCD OFF
,E/Watchdog(  723): !@Sync 3
,E/SMD     (  240): DCD OFF
,V/AlarmManager(  723): waitForAlarm result :4
,V/AlarmManager(  723): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,D/BatteryService(  723): level:100, scale:100, status:5, health:2, present:true, voltage: 4367, temperature: 284, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:16, charge type:1, power sharing:false
,D/BatteryService(  723): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  723): stay LED for fully charged
,D/UiModeManager(  723): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1066): checkOverflow(384), More:false, Req:false Child:2
,D/dalvikvm( 3544): GC_CONCURRENT freed 1688K, 42% free 11185K/19060K, paused 4ms+4ms, total 51ms
,D/AmoledAdjustTimer(  723): prevTemp = 283, currTemp = 284, prevStep = 4, currStep = 4
,D/Finsky  ( 3544): [349] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 3544): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,I/PowerManagerService(  723): [PWL] Off : 50s ago
,D/SSRMv2:SIOP(  723): SIOP:: AP = 300, Delta = -10
,E/SMD     (  240): DCD OFF
,W/ContextImpl(  723): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  240): DCD OFF
,D/FactoryTest( 4106): Not factory mode
,D/FactoryTest( 4106): Not factory mode. isFactoryMode() returend false
,D/MTPRx   ( 4106): DRIVER_TIME_OUT 60s lapsed
,D/MTPRx   ( 4106): still no open session command from host, so toast
W/ContextImpl( 4106): Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1398 android.content.ContextWrapper.startActivity:323 android.content.ContextWrapper.startActivity:323 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:767 android.os.Handler.dispatchMessage:102 
W/ContextImpl( 4106): Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1410 android.app.ContextImpl.startActivity:1399 android.content.ContextWrapper.startActivity:323 android.content.ContextWrapper.startActivity:323 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:767 
,V/ApplicationPolicy(  723): isApplicationStateBlocked userId 0 pkgname com.android.settings
,D/CustomFrequencyManagerService(  723): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 723  pkgName : ACTIVITY_RESUME_BOOSTER@5
,W/ActivityManager(  723): mDVFSHelper.acquire()
,D/LockPatternUtils( 1066): isPcwEnable = null
,D/LockPatternUtils( 1066): isPcwEnable = null
,E/MTPRx   ( 4106): started activity for popup
,I/SQLiteSecureOpenHelper( 2012): getWritableDatabase(pwd)
,I/SQLiteSecureOpenHelper( 2012): getDatabaseLocked(b,b,pwd)...
,E/SettingsReceiverActivity( 4106): PREF_DONT_ASK_AGAIN : true
,D/LockPatternUtils( 1066): isPcwEnable = null
,D/SettingsReceiverActivity( 4106): dev.kiessupport is : TRUE
,I/WindowManager(  723): Screenshot max retries 4 of Token{42c59fa8 ActivityRecord{42620338 u0 com.sec.android.app.popupuireceiver/.BatteryCover t2}} appWin=Window{42ea8c90 u0 com.sec.android.app.popupuireceiver/com.sec.android.app.popupuireceiver.BatteryCover} drawState=4
,W/WindowManager(  723): Screenshot failure taking screenshot for (720x1280) to layer 21005
,D/LockPatternUtils( 1066): isPcwEnable = null
,E/SMD     (  240): DCD OFF
,V/AlarmManager(  723): waitForAlarm result :8
,V/AlarmManager(  723): ClockReceiver onReceive() ACTION_TIME_TICK
,V/AlarmManager(  723): ___SyncScheduler (v3) ACTIVATED___
V/AlarmManager(  723): <AppSync3 Whitelist>
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1066): handleTimeUpdate
V/AlarmManager(  723): (AppSync) ### 0 added ###
,D/STATUSBAR-IconMerger( 1066): checkOverflow(384), More:false, Req:false Child:2
,D/BatteryService(  723): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:16, charge type:1, power sharing:false
,D/BatteryService(  723): stay LED for fully charged
,D/BatteryService(  723): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  723): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1066): checkOverflow(384), More:false, Req:false Child:2
,D/CustomFrequencyManagerService(  723): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 723  tag : ACTIVITY_RESUME_BOOSTER@5
,W/ActivityManager(  723): mDVFSHelper.release()
,D/CustomFrequencyManagerService(  723): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 723  pkgName : ACTIVITY_RESUME_BOOSTER@9
,D/AmoledAdjustTimer(  723): prevTemp = 284, currTemp = 282, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD OFF
,D/CustomFrequencyManagerService(  723): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 723  tag : ACTIVITY_RESUME_BOOSTER@9
,D/SSRMv2:SIOP(  723): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD OFF
,E/SMD     (  240): DCD OFF
,E/SMD     (  240): DCD OFF
,D/AmoledAdjustTimer(  723): prevTemp = 282, currTemp = 282, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP(  723): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD OFF
,W/ContextImpl(  723): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,I/PowerManagerService(  723): [PWL] Off : 75s ago
,E/SMD     (  240): DCD OFF
,E/Watchdog(  723): !@Sync 4
,V/AlarmManager(  723): waitForAlarm result :4
,V/AlarmManager(  723): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,D/NtpTrustedTime(  723): forceRefresh() from cache miss
,D/NtpTrustedTime(  723): forceRefresh Fail.
,D/BatteryService(  723): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 280, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:16, charge type:1, power sharing:false
,D/BatteryService(  723): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  723): stay LED for fully charged
,D/UiModeManager(  723): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1066): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  240): DCD OFF
,D/AmoledAdjustTimer(  723): prevTemp = 282, currTemp = 280, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP(  723): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD OFF
,E/SMD     (  240): DCD OFF
,E/SMD     (  240): DCD OFF
,D/BatteryService(  723): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:14, charge type:1, power sharing:false
,D/BatteryService(  723): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  723): stay LED for fully charged
,D/UiModeManager(  723): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1066): checkOverflow(384), More:false, Req:false Child:2
,D/AmoledAdjustTimer(  723): prevTemp = 280, currTemp = 279, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD OFF
,D/SSRMv2:SIOP(  723): SIOP:: AP = 300, Delta = 0
,W/ContextImpl(  723): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  240): DCD OFF
,E/SMD     (  240): DCD OFF
,D/BatteryService(  723): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:16, charge type:1, power sharing:false
,D/BatteryService(  723): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  723): stay LED for fully charged
,D/UiModeManager(  723): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1066): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  240): DCD OFF
,D/AmoledAdjustTimer(  723): prevTemp = 279, currTemp = 278, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP(  723): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD OFF
,I/PowerManagerService(  723): [PWL] Off : 105s ago
,E/SMD     (  240): DCD OFF
,E/Watchdog(  723): !@Sync 5
,D/BatteryService(  723): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:13, charge type:1, power sharing:false
,D/BatteryService(  723): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  723): mCoverManager.getCoverState() : true
,D/BatteryService(  723): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1066): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  240): DCD OFF
,D/AmoledAdjustTimer(  723): prevTemp = 278, currTemp = 277, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP(  723): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD OFF
,W/ContextImpl(  723): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  240): DCD OFF
,E/SMD     (  240): DCD OFF
,V/AlarmManager(  723): waitForAlarm result :8
,V/AlarmManager(  723): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1066): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1066): checkOverflow(384), More:false, Req:false Child:2
,D/BatteryService(  723): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:12, charge type:1, power sharing:false
,D/BatteryService(  723): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  723): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
D/UiModeManager(  723): mCoverManager.getCoverState() : true
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1066): checkOverflow(384), More:false, Req:false Child:2
,D/AmoledAdjustTimer(  723): prevTemp = 277, currTemp = 276, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD OFF
,D/SSRMv2:SIOP(  723): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD OFF
,E/SMD     (  240): DCD OFF
,E/SMD     (  240): DCD OFF
,D/AmoledAdjustTimer(  723): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP(  723): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD OFF
,W/ContextImpl(  723): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  240): DCD OFF
,E/Watchdog(  723): !@Sync 6
,V/AlarmManager(  723): waitForAlarm result :4
,V/AlarmManager(  723): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,D/NtpTrustedTime(  723): forceRefresh() from cache miss
,D/NtpTrustedTime(  723): forceRefresh Fail.
,D/BatteryService(  723): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:12, charge type:1, power sharing:false
,D/BatteryService(  723): stay LED for fully charged
,D/BatteryService(  723): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
D/UiModeManager(  723): mCoverManager.getCoverState() : true
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1066): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  240): DCD OFF
,I/VacuumService( 1218): Vacuum at: now=1453981699430 tag=VacuumService
,D/AmoledAdjustTimer(  723): prevTemp = 276, currTemp = 275, prevStep = 4, currStep = 4
,I/PowerManagerService(  723): [PWL] Off : 140s ago
,D/SSRMv2:SIOP(  723): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD OFF
,E/SMD     (  240): DCD OFF
,E/SMD     (  240): DCD OFF
,D/BatteryService(  723): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:8, charge type:1, power sharing:false
,D/BatteryService(  723): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  723): stay LED for fully charged
,D/UiModeManager(  723): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1066): checkOverflow(384), More:false, Req:false Child:2
,D/AmoledAdjustTimer(  723): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD OFF
,D/SSRMv2:SIOP(  723): SIOP:: AP = 300, Delta = 0
,W/ContextImpl(  723): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  240): DCD OFF
,E/SMD     (  240): DCD OFF
,D/BatteryService(  723): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:10, charge type:1, power sharing:false
,D/BatteryService(  723): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  723): mCoverManager.getCoverState() : true
,D/BatteryService(  723): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1066): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  240): DCD OFF
,D/AmoledAdjustTimer(  723): prevTemp = 275, currTemp = 274, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP(  723): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD OFF
,E/SMD     (  240): DCD OFF
,E/Watchdog(  723): !@Sync 7
,D/BatteryService(  723): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:3, charge type:1, power sharing:false
,D/BatteryService(  723): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  723): stay LED for fully charged
,D/UiModeManager(  723): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1066): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  240): DCD OFF
,D/AmoledAdjustTimer(  723): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP(  723): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD OFF
,W/ContextImpl(  723): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  240): DCD OFF
,E/SMD     (  240): DCD OFF
,V/AlarmManager(  723): waitForAlarm result :8
,V/AlarmManager(  723): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1066): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1066): checkOverflow(384), More:false, Req:false Child:2
,D/BatteryService(  723): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:12, charge type:1, power sharing:false
,D/BatteryService(  723): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  723): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
D/UiModeManager(  723): mCoverManager.getCoverState() : true
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1066): checkOverflow(384), More:false, Req:false Child:2
,D/AmoledAdjustTimer(  723): prevTemp = 274, currTemp = 273, prevStep = 4, currStep = 4
,I/PowerManagerService(  723): [PWL] Off : 180s ago
,E/SMD     (  240): DCD OFF
,D/SSRMv2:SIOP(  723): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD OFF
,E/SMD     (  240): DCD OFF
,D/BatteryService(  723): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:5, charge type:1, power sharing:false
,D/BatteryService(  723): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  723): mCoverManager.getCoverState() : true
,D/BatteryService(  723): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1066): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  240): DCD OFF
,D/AmoledAdjustTimer(  723): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP(  723): SIOP:: AP = 300, Delta = 0
,W/ContextImpl(  723): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  240): DCD OFF
,E/SMD     (  240): DCD OFF
,E/Watchdog(  723): !@Sync 8
,E/SMD     (  240): DCD OFF
,D/BatteryService(  723): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:11, charge type:1, power sharing:false
,D/BatteryService(  723): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  723): stay LED for fully charged
,D/UiModeManager(  723): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1066): checkOverflow(384), More:false, Req:false Child:2
,D/AmoledAdjustTimer(  723): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP(  723): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD OFF
,E/SMD     (  240): DCD OFF
,E/SMD     (  240): DCD OFF
,D/BatteryService(  723): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:5, charge type:1, power sharing:false
,D/BatteryService(  723): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  723): stay LED for fully charged
,D/UiModeManager(  723): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1066): checkOverflow(384), More:false, Req:false Child:2
,D/AmoledAdjustTimer(  723): prevTemp = 273, currTemp = 272, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD OFF
,D/SSRMv2:SIOP(  723): SIOP:: AP = 300, Delta = 0
,W/ContextImpl(  723): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  240): DCD OFF
,E/SMD     (  240): DCD OFF
,E/SMD     (  240): DCD OFF
,D/AmoledAdjustTimer(  723): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP(  723): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD OFF
,I/PowerManagerService(  723): [PWL] Off : 225s ago
,E/SMD     (  240): DCD OFF
,E/Watchdog(  723): !@Sync 9
,E/SMD     (  240): DCD OFF
,D/BatteryService(  723): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:13, charge type:1, power sharing:false
,D/BatteryService(  723): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  723): stay LED for fully charged
,D/UiModeManager(  723): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1066): checkOverflow(384), More:false, Req:false Child:2
,D/AmoledAdjustTimer(  723): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP(  723): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD OFF
,W/ContextImpl(  723): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  240): DCD OFF
,E/SMD     (  240): DCD OFF
,V/AlarmManager(  723): waitForAlarm result :8
,V/AlarmManager(  723): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1066): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1066): checkOverflow(384), More:false, Req:false Child:2
,D/BatteryService(  723): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:6, charge type:1, power sharing:false
,D/BatteryService(  723): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  723): stay LED for fully charged
,D/UiModeManager(  723): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1066): checkOverflow(384), More:false, Req:false Child:2
,D/AmoledAdjustTimer(  723): prevTemp = 272, currTemp = 271, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD OFF
,D/SSRMv2:SIOP(  723): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD OFF
,E/SMD     (  240): DCD OFF
,E/SMD     (  240): DCD OFF
,D/BatteryService(  723): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:12, charge type:1, power sharing:false
,D/BatteryService(  723): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  723): mCoverManager.getCoverState() : true
,D/BatteryService(  723): stay LED for fully charged
D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1066): checkOverflow(384), More:false, Req:false Child:2
,D/AmoledAdjustTimer(  723): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP(  723): SIOP:: AP = 300, Delta = 0
,D/TimaService(  723): TIMA: TimaService scheduler is intialized. 
,D/TimaService(  723): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService(  723): TimaServiceHandler.handleMessage what =1
,I/TLC_TIMA_PKM_initialize(  723): initializing...
,I/TLC_TIMA_PKM_initialize(  723): root = /firmware/image, root_strlen = 15
,I/TLC_TIMA_PKM_initialize(  723): process = tima_pkm, process_strlen = 8
,I/TZ: qc_tlc_communication(  723): root = /firmware/image, root_len = 15
,I/TZ: qc_tlc_communication(  723): process = tima_pkm, process_strlen = 8
,I/TZ: qc_tlc_communication(  723): aligned max_sendmsg_size = 262208 = 0x40040
,I/TZ: qc_tlc_communication(  723): aligned max_recvmsg_size = 262208 = 0x40040
,I/TZ: qc_tlc_communication(  723): max_message_size = 524416 = 0x80080
,D/QSEECOMAPI: (  723): QSEECom_get_handle sb_length = 0x80080
,D/QSEECOMAPI: (  723): App is not loaded in QSEE
,D/QSEECOMAPI: (  723): Loaded image: APP id = 2
,I/TZ: qc_tlc_communication(  723): TIMA: path = /firmware/image, fname = tima_pkm, tzapp is loaded
,I/TLC_TIMA_PKM_initialize(  723): Trustlet response is completed
,W/ContextImpl(  723): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  240): DCD OFF
,E/SMD     (  240): DCD OFF
,I/TLC_TIMA_PKM_measure_kernel(  723): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel(  723): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService(  723): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService(  723): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/Watchdog(  723): !@Sync 10
,E/SMD     (  240): DCD OFF
,D/BatteryService(  723): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:10, charge type:1, power sharing:false
,D/BatteryService(  723): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  723): stay LED for fully charged
,D/UiModeManager(  723): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1066): checkOverflow(384), More:false, Req:false Child:2
,D/AmoledAdjustTimer(  723): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP(  723): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD OFF
,E/SMD     (  240): DCD OFF
,E/SMD     (  240): DCD OFF
,D/AmoledAdjustTimer(  723): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD OFF
,D/SSRMv2:SIOP(  723): SIOP:: AP = 300, Delta = 0
,W/ContextImpl(  723): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  240): DCD OFF
,I/PowerManagerService(  723): [PWL] Off : 275s ago
,E/SMD     (  240): DCD OFF
,V/AlarmManager(  723): waitForAlarm result :4
,V/AlarmManager(  723): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,I/SELinux ( 4880): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 4880):  
,V/AlarmManager(  723): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,D/BatteryService(  723): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:8, charge type:1, power sharing:false
,D/BatteryService(  723): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  723): mCoverManager.getCoverState() : true
,D/BatteryService(  723): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 1066): checkOverflow(384), More:false, Req:false Child:2
,D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/SELinux ( 4880): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 4880):  
I/SELinux ( 4880):  
,I/SELinux ( 4880): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 4880): [DEBUG] seapp_context_lookup: seinfoCategory = default
,E/dalvikvm( 4880): >>>>> Normal User
,E/dalvikvm( 4880): >>>>> com.blurb.checkout [ userId:0 | appId:10075 ]
,E/SELinux ( 4880): [DEBUG] seapp_context_lookup: seinfoCategory = default
,D/TimaKeyStoreProvider( 4880): in addTimaSignatureService
,D/TimaKeyStoreProvider( 4880): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 4880): Added TimaKesytore provider
,W/ActivityManager(  723): Permission Denial: getCurrentUser() from pid=4880, uid=10075 requires android.permission.INTERACT_ACROSS_USERS
,I/ActivityManager(  723): Killing 3747:com.sec.spp.push:RemoteDlcProcess/u0a38 (adj 15): empty #43,
,I/EventLogService( 1756): Aggregate from 1453979911613 (log), 1453979911613 (data)
,E/SMD     (  240): DCD OFF
,D/AmoledAdjustTimer(  723): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP(  723): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD OFF
,E/SMD     (  240): DCD OFF
,V/GLSActivity( 1318): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1318): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/Watchdog(  723): !@Sync 11
,D/BatteryService(  723): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:8, charge type:1, power sharing:false
,D/BatteryService(  723): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
D/UiModeManager(  723): mCoverManager.getCoverState() : true
D/BatteryService(  723): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1066): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  240): DCD OFF
,D/AmoledAdjustTimer(  723): prevTemp = 271, currTemp = 270, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP(  723): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD OFF
,W/ContextImpl(  723): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  240): DCD OFF
,E/SMD     (  240): DCD OFF
,V/AlarmManager(  723): waitForAlarm result :8
,V/AlarmManager(  723): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1066): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1066): checkOverflow(384), More:false, Req:false Child:2
,D/BatteryService(  723): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:9, charge type:1, power sharing:false
,D/BatteryService(  723): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  723): stay LED for fully charged
,D/UiModeManager(  723): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1066): checkOverflow(384), More:false, Req:false Child:2
,D/AmoledAdjustTimer(  723): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD OFF
,D/SSRMv2:SIOP(  723): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD OFF
,E/SMD     (  240): DCD OFF
,D/BatteryService(  723): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:11, charge type:1, power sharing:false
,D/BatteryService(  723): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  723): stay LED for fully charged
,D/UiModeManager(  723): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1066): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  240): DCD OFF
,D/AmoledAdjustTimer(  723): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP(  723): SIOP:: AP = 300, Delta = 0
,W/ContextImpl(  723): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  240): DCD OFF
,E/SMD     (  240): DCD OFF
,E/Watchdog(  723): !@Sync 12
,E/SMD     (  240): DCD OFF
,D/BatteryService(  723): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:10, charge type:1, power sharing:false
,D/BatteryService(  723): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  723): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
D/BatteryService(  723): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1066): checkOverflow(384), More:false, Req:false Child:2
,D/AmoledAdjustTimer(  723): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP(  723): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD OFF
,E/SMD     (  240): DCD OFF
,E/SMD     (  240): DCD OFF
,D/BatteryService(  723): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:8, charge type:1, power sharing:false
,D/BatteryService(  723): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  723): stay LED for fully charged
,D/UiModeManager(  723): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1066): checkOverflow(384), More:false, Req:false Child:2
,D/dalvikvm(  723): GC_CONCURRENT freed 3408K, 59% free 23431K/57076K, paused 28ms+42ms, total 465ms
,D/AmoledAdjustTimer(  723): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,I/PowerManagerService(  723): [PWL] Off : 330s ago
,E/SMD     (  240): DCD OFF
,D/SSRMv2:SIOP(  723): SIOP:: AP = 300, Delta = 0
,W/ContextImpl(  723): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  240): DCD OFF
,E/SMD     (  240): DCD OFF
,D/BatteryService(  723): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:5, charge type:1, power sharing:false
,D/BatteryService(  723): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  723): mCoverManager.getCoverState() : true
,D/BatteryService(  723): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  240): DCD OFF
D/STATUSBAR-IconMerger( 1066): checkOverflow(384), More:false, Req:false Child:2
,D/AmoledAdjustTimer(  723): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP(  723): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD OFF
,E/SMD     (  240): DCD OFF
,E/Watchdog(  723): !@Sync 13
,E/SMD     (  240): DCD OFF
,D/BatteryService(  723): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:8, charge type:1, power sharing:false
,D/BatteryService(  723): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  723): mCoverManager.getCoverState() : true
,D/BatteryService(  723): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1066): checkOverflow(384), More:false, Req:false Child:2
,D/AmoledAdjustTimer(  723): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP(  723): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD OFF
,W/ContextImpl(  723): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  240): DCD OFF
,E/SMD     (  240): DCD OFF
,V/AlarmManager(  723): waitForAlarm result :8
,V/AlarmManager(  723): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1066): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1066): checkOverflow(384), More:false, Req:false Child:2
,D/BatteryService(  723): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:6, charge type:1, power sharing:false
,D/BatteryService(  723): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  723): mCoverManager.getCoverState() : true
,D/BatteryService(  723): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1066): checkOverflow(384), More:false, Req:false Child:2
,D/AmoledAdjustTimer(  723): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD OFF
,D/SSRMv2:SIOP(  723): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD OFF
,E/SMD     (  240): DCD OFF
,E/SMD     (  240): DCD OFF
,D/BatteryService(  723): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:5, charge type:1, power sharing:false
,D/BatteryService(  723): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  723): mCoverManager.getCoverState() : true
,D/BatteryService(  723): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1066): checkOverflow(384), More:false, Req:false Child:2
,D/AmoledAdjustTimer(  723): prevTemp = 270, currTemp = 269, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP(  723): SIOP:: AP = 300, Delta = 0
,W/ContextImpl(  723): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  240): DCD OFF
,E/SMD     (  240): DCD OFF
,E/Watchdog(  723): !@Sync 14
,E/SMD     (  240): DCD OFF
,D/BatteryService(  723): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:7, charge type:1, power sharing:false
,D/BatteryService(  723): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  723): stay LED for fully charged
,D/UiModeManager(  723): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1066): checkOverflow(384), More:false, Req:false Child:2
,D/AmoledAdjustTimer(  723): prevTemp = 269, currTemp = 269, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD OFF
,D/SSRMv2:SIOP(  723): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD OFF
,E/SMD     (  240): DCD OFF
,D/BatteryService(  723): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:4, charge type:1, power sharing:false
,D/BatteryService(  723): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  723): stay LED for fully charged
,D/UiModeManager(  723): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1066): checkOverflow(384), More:false, Req:false Child:2
,D/AmoledAdjustTimer(  723): prevTemp = 269, currTemp = 269, prevStep = 4, currStep = 4
,I/PowerManagerService(  723): [PWL] Off : 390s ago
,E/SMD     (  240): DCD OFF
,D/SSRMv2:SIOP(  723): SIOP:: AP = 300, Delta = 0
,W/ContextImpl(  723): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  240): DCD OFF
,E/SMD     (  240): DCD OFF
,E/SMD     (  240): DCD OFF
,D/BatteryService(  723): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:8, charge type:1, power sharing:false
,D/BatteryService(  723): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  723): mCoverManager.getCoverState() : true
,D/BatteryService(  723): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1066): checkOverflow(384), More:false, Req:false Child:2
,D/AmoledAdjustTimer(  723): prevTemp = 269, currTemp = 269, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP(  723): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD OFF
,E/SMD     (  240): DCD OFF
,E/Watchdog(  723): !@Sync 15
,E/SMD     (  240): DCD OFF
,D/BatteryService(  723): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:10, charge type:1, power sharing:false
,D/BatteryService(  723): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  723): stay LED for fully charged
,D/UiModeManager(  723): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1066): checkOverflow(384), More:false, Req:false Child:2
,D/AmoledAdjustTimer(  723): prevTemp = 269, currTemp = 269, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD OFF
,D/SSRMv2:SIOP(  723): SIOP:: AP = 300, Delta = 0
,W/ContextImpl(  723): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  240): DCD OFF
,E/SMD     (  240): DCD OFF
,V/AlarmManager(  723): waitForAlarm result :8
,V/AlarmManager(  723): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1066): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1066): checkOverflow(384), More:false, Req:false Child:2
,D/BatteryService(  723): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:11, charge type:1, power sharing:false
,D/BatteryService(  723): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  723): stay LED for fully charged
,D/UiModeManager(  723): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer(  723): prevTemp = 269, currTemp = 269, prevStep = 4, currStep = 4
,D/STATUSBAR-IconMerger( 1066): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  240): DCD OFF
,D/SSRMv2:SIOP(  723): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD OFF
,E/SMD     (  240): DCD OFF
,E/SMD     (  240): DCD OFF
,D/BatteryService(  723): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:10, charge type:1, power sharing:false
,D/BatteryService(  723): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  723): mCoverManager.getCoverState() : true
,D/BatteryService(  723): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/AmoledAdjustTimer(  723): prevTemp = 269, currTemp = 269, prevStep = 4, currStep = 4
,D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1066): checkOverflow(384), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  723): SIOP:: AP = 300, Delta = 0
,W/ContextImpl(  723): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  240): DCD OFF
,E/SMD     (  240): DCD OFF
,E/Watchdog(  723): !@Sync 16
,E/SMD     (  240): DCD OFF
,D/BatteryService(  723): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:9, charge type:1, power sharing:false
,D/BatteryService(  723): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  723): mCoverManager.getCoverState() : true
,D/BatteryService(  723): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,D/AmoledAdjustTimer(  723): prevTemp = 269, currTemp = 269, prevStep = 4, currStep = 4
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1066): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  240): DCD OFF
,D/SSRMv2:SIOP(  723): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD OFF
,E/SMD     (  240): DCD OFF
,D/AmoledAdjustTimer(  723): prevTemp = 269, currTemp = 269, prevStep = 4, currStep = 4
,D/BatteryService(  723): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:12, charge type:1, power sharing:false
,D/BatteryService(  723): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  723): mCoverManager.getCoverState() : true
,D/BatteryService(  723): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1066): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  240): DCD OFF
,D/SSRMv2:SIOP(  723): SIOP:: AP = 300, Delta = 0
,W/ContextImpl(  723): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  240): DCD OFF
,I/PowerManagerService(  723): [PWL] Off : 455s ago
,E/SMD     (  240): DCD OFF
,E/SMD     (  240): DCD OFF
,D/AmoledAdjustTimer(  723): prevTemp = 269, currTemp = 269, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP(  723): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD OFF
,E/SMD     (  240): DCD OFF
,E/Watchdog(  723): !@Sync 17
,E/SMD     (  240): DCD OFF
,D/AmoledAdjustTimer(  723): prevTemp = 269, currTemp = 269, prevStep = 4, currStep = 4
,D/BatteryService(  723): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:9, charge type:1, power sharing:false
,D/BatteryService(  723): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  723): stay LED for fully charged
,D/UiModeManager(  723): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1066): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  240): DCD OFF
,D/SSRMv2:SIOP(  723): SIOP:: AP = 300, Delta = 0
,W/ContextImpl(  723): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  240): DCD OFF
,E/SMD     (  240): DCD OFF
,V/AlarmManager(  723): waitForAlarm result :8
,V/AlarmManager(  723): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1066): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1066): checkOverflow(384), More:false, Req:false Child:2
,D/AmoledAdjustTimer(  723): prevTemp = 269, currTemp = 269, prevStep = 4, currStep = 4
,D/BatteryService(  723): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:6, charge type:1, power sharing:false
,D/BatteryService(  723): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  723): stay LED for fully charged
,D/UiModeManager(  723): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1066): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  240): DCD OFF
,D/SSRMv2:SIOP(  723): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD OFF
,E/SMD     (  240): DCD OFF
,E/SMD     (  240): DCD OFF
,D/AmoledAdjustTimer(  723): prevTemp = 269, currTemp = 268, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP(  723): SIOP:: AP = 300, Delta = 0
,W/ContextImpl(  723): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  240): DCD OFF
,E/SMD     (  240): DCD OFF
,E/Watchdog(  723): !@Sync 18
,E/SMD     (  240): DCD OFF
,D/AmoledAdjustTimer(  723): prevTemp = 268, currTemp = 268, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD OFF
,D/SSRMv2:SIOP(  723): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD OFF
,E/SMD     (  240): DCD OFF
,D/AmoledAdjustTimer(  723): prevTemp = 268, currTemp = 268, prevStep = 4, currStep = 4
,D/BatteryService(  723): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:12, charge type:1, power sharing:false
,D/BatteryService(  723): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  723): stay LED for fully charged
,D/UiModeManager(  723): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1066): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  240): DCD OFF
,D/SSRMv2:SIOP(  723): SIOP:: AP = 300, Delta = 0
,W/ContextImpl(  723): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  240): DCD OFF
,E/SMD     (  240): DCD OFF
,E/SMD     (  240): DCD OFF
,D/AmoledAdjustTimer(  723): prevTemp = 268, currTemp = 268, prevStep = 4, currStep = 4
,D/BatteryService(  723): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:3, charge type:1, power sharing:false
,D/BatteryService(  723): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  723): mCoverManager.getCoverState() : true
,D/BatteryService(  723): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1066): checkOverflow(384), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  723): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD OFF
,I/PowerManagerService(  723): [PWL] Off : 525s ago
,E/SMD     (  240): DCD OFF
,E/Watchdog(  723): !@Sync 19
,E/SMD     (  240): DCD OFF
,D/AmoledAdjustTimer(  723): prevTemp = 268, currTemp = 268, prevStep = 4, currStep = 4
,D/BatteryService(  723): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  723): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  723): mCoverManager.getCoverState() : true
,D/BatteryService(  723): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1066): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  240): DCD OFF
,D/SSRMv2:SIOP(  723): SIOP:: AP = 300, Delta = 0
,W/ContextImpl(  723): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  240): DCD OFF
,E/SMD     (  240): DCD OFF
,V/AlarmManager(  723): waitForAlarm result :8
,V/AlarmManager(  723): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1066): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1066): checkOverflow(384), More:false, Req:false Child:2
,D/AmoledAdjustTimer(  723): prevTemp = 268, currTemp = 268, prevStep = 4, currStep = 4
,D/BatteryService(  723): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:10, charge type:1, power sharing:false
,D/BatteryService(  723): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  723): stay LED for fully charged
,D/UiModeManager(  723): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,E/SMD     (  240): DCD OFF
D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1066): checkOverflow(384), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  723): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD OFF
,E/SMD     (  240): DCD OFF
,E/SMD     (  240): DCD OFF
,D/AmoledAdjustTimer(  723): prevTemp = 268, currTemp = 268, prevStep = 4, currStep = 4
,D/BatteryService(  723): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:9, charge type:1, power sharing:false
,D/BatteryService(  723): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  723): stay LED for fully charged
,D/UiModeManager(  723): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1066): checkOverflow(384), More:false, Req:false Child:2
,D/TimaService(  723): TIMA: TimaService scheduler is intialized. 
,D/TimaService(  723): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService(  723): TimaServiceHandler.handleMessage what =1
,D/SSRMv2:SIOP(  723): SIOP:: AP = 300, Delta = 0
,W/ContextImpl(  723): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  240): DCD OFF
,I/TLC_TIMA_PKM_measure_kernel(  723): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel(  723): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService(  723): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService(  723): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/SMD     (  240): DCD OFF
,E/Watchdog(  723): !@Sync 20
,E/SMD     (  240): DCD OFF
,D/AmoledAdjustTimer(  723): prevTemp = 268, currTemp = 268, prevStep = 4, currStep = 4
,D/BatteryService(  723): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:7, charge type:1, power sharing:false
,D/BatteryService(  723): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  723): stay LED for fully charged
,D/UiModeManager(  723): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1066): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  240): DCD OFF
,D/SSRMv2:SIOP(  723): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD OFF
,E/SMD     (  240): DCD OFF
,D/AmoledAdjustTimer(  723): prevTemp = 268, currTemp = 268, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD OFF
,D/BatteryService(  723): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:7, charge type:1, power sharing:false
,D/BatteryService(  723): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  723): stay LED for fully charged
,D/UiModeManager(  723): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1066): checkOverflow(384), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  723): SIOP:: AP = 300, Delta = 0
,W/ContextImpl(  723): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  240): DCD OFF
,E/SMD     (  240): DCD OFF
,E/SMD     (  240): DCD OFF
,D/AmoledAdjustTimer(  723): prevTemp = 268, currTemp = 268, prevStep = 4, currStep = 4
,D/BatteryService(  723): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:6, charge type:1, power sharing:false
,D/BatteryService(  723): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  723): stay LED for fully charged
,D/UiModeManager(  723): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1066): checkOverflow(384), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  723): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD OFF
,E/SMD     (  240): DCD OFF
,E/Watchdog(  723): !@Sync 21
,V/GLSActivity( 1318): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1318): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/SMD     (  240): DCD OFF
,D/AmoledAdjustTimer(  723): prevTemp = 268, currTemp = 268, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD OFF
,D/SSRMv2:SIOP(  723): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD OFF
,E/SMD     (  240): DCD OFF
,V/AlarmManager(  723): waitForAlarm result :8
,V/AlarmManager(  723): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1066): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1066): checkOverflow(384), More:false, Req:false Child:2
,V/AlarmManager(  723): waitForAlarm result :4
,I/SensorManagerA(  723): getReportingMode :: sensor.mType = 5
,D/Sensors (  723): LightSensor setDelay = 200000000
,D/Sensors (  723): LightSensor setSensorDelay = 200000000
,D/LightsService(  723): [api] onReceive : SvcLEDReceiver re-enables LightSenor and sends MSG_FORCEDSVCLEDTASK
D/Sensors (  723): Light sensor flush: not enabled 0
D/Sensors (  723): LightSensor enable = 1
D/Sensors (  723): LightSensor enableSensor = 1
D/SensorManager(  723): registerListener :: 16, CM36686 Light Sensor, 200000, 0,  
,I/PowerManagerService(  723): [PWL] Off : 600s ago
,I/PowerManagerService(  723): [PWL]   PowerManagerService.WakeLocks: ref count=1
,I/PowerManagerService(  723): [PWL]     mWakeLockSummary : 0x1
,D/Finsky  ( 3544): [1] DailyHygiene.onStartCommand: Beginning daily hygiene
I/PowerManagerService(  723): [PWL]       PARTIAL_WAKE_LOCK              'AlarmManager' (uid=1000, pid=723, ws=WorkSource{1000}) (elapsedTime=37)
,V/AlarmManager(  723): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,D/BatteryService(  723): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:8, charge type:1, power sharing:false
,D/BatteryService(  723): stay LED for fully charged
,D/BatteryService(  723): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
D/AmoledAdjustTimer(  723): prevTemp = 268, currTemp = 268, prevStep = 4, currStep = 4
,D/UiModeManager(  723): mCoverManager.getCoverState() : true
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1066): checkOverflow(384), More:false, Req:false Child:2
,V/GLSActivity( 1318): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/LightsService(  723): [SvcLED]  onSensorChanged::light value = 4
D/Sensors (  723): LightSensor enable = 0
D/Sensors (  723): LightSensor enableSensor = 0
D/SensorManager(  723): unregisterListener ::   
,V/GLSActivity( 1318): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/LightsService(  723): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,I/System.out( 3544): Thread-336 calls detatch()
,W/Finsky  ( 3544): [1] DailyHygiene$1.onErrorResponse: Unable to preload experiments: com.android.volley.NoConnectionError: java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
,V/GLSActivity( 1318): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1318): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/System.out( 3544): Thread-337 calls detatch()
,E/SMD     (  240): DCD OFF
,V/GLSActivity( 1318): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1318): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/System.out( 3544): Thread-336 calls detatch()
,W/Finsky  ( 3544): [1] LibraryUpdateListener.onErrorResponse: Library replication failed: com.android.volley.NoConnectionError: java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
,D/dalvikvm( 3544): GC_CONCURRENT freed 1871K, 42% free 11244K/19060K, paused 5ms+5ms, total 46ms
,V/GLSActivity( 1318): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1318): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/System.out( 3544): Thread-337 calls detatch()
,W/Finsky  ( 3544): [1] UpdateChecker$1$2.onErrorResponse: Update check failed: com.android.volley.NoConnectionError: java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
,D/Finsky  ( 3544): [1] DailyHygiene.access$600: Logging device features
,V/AlarmManager(  723): waitForAlarm result :4
,V/AlarmManager(  723): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,D/Finsky  ( 3544): [1] DailyHygiene.reschedule: Scheduling new run in 27 minutes (failures=2)
,D/DeviceConnectionService( 1218): client connected with version: 8296000
,D/WearableService( 1218): callingUid 10011, callindPid: 1218
,D/Finsky  ( 3544): [1] VerifyInstalledPackagesReceiver.onReceive: Skipping verification because network inactive
,D/Finsky  ( 3544): [364] FlushLogsService.onHandleIntent: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 3544): [1] WearSupportService$8.onConnectionFailed: onConnectionFailed: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/Finsky  ( 3544): [1] WearSupportService.access$100: Dropping command=hygiene due to Gms not connected
,V/GLSActivity( 1318): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1318): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/SSRMv2:SIOP(  723): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD OFF
,E/SMD     (  240): DCD OFF
,E/SMD     (  240): DCD OFF
,D/AmoledAdjustTimer(  723): prevTemp = 268, currTemp = 268, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP(  723): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD OFF
,E/SMD     (  240): DCD OFF
,V/AlarmManager(  723): waitForAlarm result :4
,V/AlarmManager(  723): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,D/BatteryService(  723): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:7, charge type:1, power sharing:false
,D/BatteryService(  723): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  723): stay LED for fully charged
,D/UiModeManager(  723): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1066): checkOverflow(384), More:false, Req:false Child:2
,D/dalvikvm( 3544): GC_CONCURRENT freed 1933K, 42% free 11239K/19060K, paused 5ms+5ms, total 44ms
,D/Finsky  ( 3544): [349] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 3544): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,E/Watchdog(  723): !@Sync 22
,E/SMD     (  240): DCD OFF
,D/AmoledAdjustTimer(  723): prevTemp = 268, currTemp = 268, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD OFF
,D/SSRMv2:SIOP(  723): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD OFF
,D/BatteryService(  723): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:5, charge type:1, power sharing:false
,D/BatteryService(  723): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  723): stay LED for fully charged
,D/UiModeManager(  723): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1066): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  240): DCD OFF
,D/AmoledAdjustTimer(  723): prevTemp = 268, currTemp = 268, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD OFF
,D/SSRMv2:SIOP(  723): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD OFF
,D/BatteryService(  723): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:8, charge type:1, power sharing:false
,D/BatteryService(  723): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  723): stay LED for fully charged
,D/UiModeManager(  723): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1066): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  240): DCD OFF
,E/SMD     (  240): DCD OFF
,D/AmoledAdjustTimer(  723): prevTemp = 268, currTemp = 268, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP(  723): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD OFF
,E/SMD     (  240): DCD OFF
,D/BatteryService(  723): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:8, charge type:1, power sharing:false
,D/BatteryService(  723): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  723): stay LED for fully charged
,D/UiModeManager(  723): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1066): checkOverflow(384), More:false, Req:false Child:2
,E/Watchdog(  723): !@Sync 23
,E/SMD     (  240): DCD OFF
,D/AmoledAdjustTimer(  723): prevTemp = 268, currTemp = 268, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD OFF
,D/SSRMv2:SIOP(  723): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD OFF
,D/BatteryService(  723): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:7, charge type:1, power sharing:false
,D/BatteryService(  723): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  723): stay LED for fully charged
,D/UiModeManager(  723): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1066): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  240): DCD OFF
,V/AlarmManager(  723): waitForAlarm result :8
,V/AlarmManager(  723): ClockReceiver onReceive() ACTION_TIME_TICK
,V/AlarmManager(  723): ___SyncScheduler (v3) ACTIVATED___
,V/AlarmManager(  723): <AppSync3 Whitelist>
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1066): handleTimeUpdate
V/AlarmManager(  723): (AppSync) ### 0 added ###
,D/STATUSBAR-IconMerger( 1066): checkOverflow(384), More:false, Req:false Child:2
,D/AmoledAdjustTimer(  723): prevTemp = 268, currTemp = 268, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD OFF
,D/SSRMv2:SIOP(  723): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD OFF
,D/BatteryService(  723): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:9, charge type:1, power sharing:false
,D/BatteryService(  723): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  723): mCoverManager.getCoverState() : true
,D/BatteryService(  723): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1066): checkOverflow(384), More:false, Req:false Child:2
,D/dalvikvm(  723): GC_CONCURRENT freed 3399K, 59% free 23417K/56768K, paused 42ms+40ms, total 421ms
,E/SMD     (  240): DCD OFF
,E/SMD     (  240): DCD OFF
,D/AmoledAdjustTimer(  723): prevTemp = 268, currTemp = 268, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP(  723): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD OFF
,E/SMD     (  240): DCD OFF
,D/BatteryService(  723): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:5, charge type:1, power sharing:false
,D/BatteryService(  723): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  723): stay LED for fully charged
,D/UiModeManager(  723): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1066): checkOverflow(384), More:false, Req:false Child:2
,E/Watchdog(  723): !@Sync 24
,E/SMD     (  240): DCD OFF
,I/PowerManagerService(  723): [PWL] Off : 680s ago
,D/AmoledAdjustTimer(  723): prevTemp = 268, currTemp = 268, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD OFF
,D/SSRMv2:SIOP(  723): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD OFF
,D/BatteryService(  723): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:4, charge type:1, power sharing:false
,D/BatteryService(  723): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  723): stay LED for fully charged
,D/UiModeManager(  723): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1066): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  240): DCD OFF
,D/AmoledAdjustTimer(  723): prevTemp = 268, currTemp = 268, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD OFF
,D/SSRMv2:SIOP(  723): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD OFF
,D/BatteryService(  723): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:5, charge type:1, power sharing:false
,D/BatteryService(  723): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  723): stay LED for fully charged
,D/UiModeManager(  723): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1066): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  240): DCD OFF
,E/SMD     (  240): DCD OFF
,D/AmoledAdjustTimer(  723): prevTemp = 268, currTemp = 268, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP(  723): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD OFF
,E/SMD     (  240): DCD OFF
,D/BatteryService(  723): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:5, charge type:1, power sharing:false
,D/BatteryService(  723): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  723): mCoverManager.getCoverState() : true
,D/BatteryService(  723): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1066): checkOverflow(384), More:false, Req:false Child:2
,E/Watchdog(  723): !@Sync 25
,E/SMD     (  240): DCD OFF
,D/AmoledAdjustTimer(  723): prevTemp = 268, currTemp = 267, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD OFF
,D/SSRMv2:SIOP(  723): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD OFF
,D/BatteryService(  723): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:5, charge type:1, power sharing:false
,D/BatteryService(  723): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  723): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/BatteryService(  723): stay LED for fully charged
D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1066): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  240): DCD OFF
,V/AlarmManager(  723): waitForAlarm result :8
,V/AlarmManager(  723): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1066): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1066): checkOverflow(384), More:false, Req:false Child:2
,D/AmoledAdjustTimer(  723): prevTemp = 267, currTemp = 267, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD OFF
,D/SSRMv2:SIOP(  723): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD OFF
,D/BatteryService(  723): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:5, charge type:1, power sharing:false
,D/BatteryService(  723): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  723): stay LED for fully charged
,D/UiModeManager(  723): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1066): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  240): DCD OFF
,E/SMD     (  240): DCD OFF
,D/AmoledAdjustTimer(  723): prevTemp = 267, currTemp = 267, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD OFF
,D/SSRMv2:SIOP(  723): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD OFF
,D/BatteryService(  723): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:4, charge type:1, power sharing:false
,D/BatteryService(  723): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  723): stay LED for fully charged
,D/UiModeManager(  723): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1066): checkOverflow(384), More:false, Req:false Child:2
,E/Watchdog(  723): !@Sync 26
,E/SMD     (  240): DCD OFF
,D/AmoledAdjustTimer(  723): prevTemp = 267, currTemp = 267, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD OFF
,D/SSRMv2:SIOP(  723): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD OFF
,D/BatteryService(  723): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:2, charge type:1, power sharing:false
,D/BatteryService(  723): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  723): mCoverManager.getCoverState() : true
,D/BatteryService(  723): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1066): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  240): DCD OFF
,D/AmoledAdjustTimer(  723): prevTemp = 267, currTemp = 267, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD OFF
,D/SSRMv2:SIOP(  723): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD OFF
,D/BatteryService(  723): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:18, charge type:1, power sharing:false
,D/BatteryService(  723): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  723): mCoverManager.getCoverState() : true
,D/BatteryService(  723): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
E/SMD     (  240): DCD OFF
,D/STATUSBAR-IconMerger( 1066): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  240): DCD OFF
,D/AmoledAdjustTimer(  723): prevTemp = 267, currTemp = 267, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD OFF
,D/SSRMv2:SIOP(  723): SIOP:: AP = 300, Delta = 0
,I/PowerManagerService(  723): [PWL] Off : 765s ago
,E/SMD     (  240): DCD OFF
,D/BatteryService(  723): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:17, charge type:1, power sharing:false
,D/BatteryService(  723): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  723): stay LED for fully charged
,D/UiModeManager(  723): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1066): checkOverflow(384), More:false, Req:false Child:2
,E/Watchdog(  723): !@Sync 27
,E/SMD     (  240): DCD OFF
,D/AmoledAdjustTimer(  723): prevTemp = 267, currTemp = 267, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD OFF
,D/SSRMv2:SIOP(  723): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD OFF
,D/BatteryService(  723): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:10, charge type:1, power sharing:false
,D/BatteryService(  723): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  723): mCoverManager.getCoverState() : true
,D/BatteryService(  723): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1066): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  240): DCD OFF
,V/AlarmManager(  723): waitForAlarm result :8
,V/AlarmManager(  723): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1066): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1066): checkOverflow(384), More:false, Req:false Child:2
,D/AmoledAdjustTimer(  723): prevTemp = 267, currTemp = 267, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD OFF
,D/SSRMv2:SIOP(  723): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD OFF
,E/SMD     (  240): DCD OFF
,D/BatteryService(  723): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:11, charge type:1, power sharing:false
,D/BatteryService(  723): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  723): mCoverManager.getCoverState() : true
,D/BatteryService(  723): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1066): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  240): DCD OFF
,D/AmoledAdjustTimer(  723): prevTemp = 267, currTemp = 267, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD OFF
,D/SSRMv2:SIOP(  723): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD OFF
,D/BatteryService(  723): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:9, charge type:1, power sharing:false
,D/BatteryService(  723): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  723): stay LED for fully charged
,D/UiModeManager(  723): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1066): checkOverflow(384), More:false, Req:false Child:2
,E/Watchdog(  723): !@Sync 28
,E/SMD     (  240): DCD OFF
,D/AmoledAdjustTimer(  723): prevTemp = 267, currTemp = 267, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD OFF
,D/SSRMv2:SIOP(  723): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD OFF
,D/BatteryService(  723): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:6, charge type:1, power sharing:false
,D/BatteryService(  723): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  723): mCoverManager.getCoverState() : true
,D/BatteryService(  723): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1066): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  240): DCD OFF
,D/AmoledAdjustTimer(  723): prevTemp = 267, currTemp = 267, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD OFF
,D/SSRMv2:SIOP(  723): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD OFF
,E/SMD     (  240): DCD OFF
,D/BatteryService(  723): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:4, charge type:1, power sharing:false
,D/BatteryService(  723): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  723): stay LED for fully charged
,D/UiModeManager(  723): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1066): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  240): DCD OFF
,D/AmoledAdjustTimer(  723): prevTemp = 267, currTemp = 267, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD OFF
,D/SSRMv2:SIOP(  723): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD OFF
,D/BatteryService(  723): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:6, charge type:1, power sharing:false
,D/BatteryService(  723): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  723): mCoverManager.getCoverState() : true
,D/BatteryService(  723): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1066): checkOverflow(384), More:false, Req:false Child:2
,E/Watchdog(  723): !@Sync 29
,E/SMD     (  240): DCD OFF
,D/AmoledAdjustTimer(  723): prevTemp = 267, currTemp = 267, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD OFF
,D/SSRMv2:SIOP(  723): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD OFF
,D/BatteryService(  723): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:4, charge type:1, power sharing:false
,D/BatteryService(  723): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  723): mCoverManager.getCoverState() : true
,D/BatteryService(  723): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1066): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  240): DCD OFF
,V/AlarmManager(  723): waitForAlarm result :8
,V/AlarmManager(  723): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1066): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1066): checkOverflow(384), More:false, Req:false Child:2
,D/AmoledAdjustTimer(  723): prevTemp = 267, currTemp = 267, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD OFF
,D/SSRMv2:SIOP(  723): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD OFF
,E/SMD     (  240): DCD OFF
,D/BatteryService(  723): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:15, charge type:1, power sharing:false
,D/BatteryService(  723): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  723): mCoverManager.getCoverState() : true
,D/BatteryService(  723): stay LED for fully charged
D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1066): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  240): DCD OFF
,D/AmoledAdjustTimer(  723): prevTemp = 267, currTemp = 267, prevStep = 4, currStep = 4
,D/TimaService(  723): TIMA: TimaService scheduler is intialized. 
,D/TimaService(  723): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService(  723): TimaServiceHandler.handleMessage what =1
,E/SMD     (  240): DCD OFF
,D/SSRMv2:SIOP(  723): SIOP:: AP = 300, Delta = 0
,I/PowerManagerService(  723): [PWL] Off : 855s ago
,I/PowerManagerService(  723): [PWL]   PowerManagerService.WakeLocks: ref count=1
,I/PowerManagerService(  723): [PWL]     mWakeLockSummary : 0x1
,I/PowerManagerService(  723): [PWL]       PARTIAL_WAKE_LOCK              'TimaService' (uid=1000, pid=723, ws=null) (elapsedTime=3337)
,I/TLC_TIMA_PKM_measure_kernel(  723): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel(  723): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService(  723): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService(  723): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/SMD     (  240): DCD OFF
,E/Watchdog(  723): !@Sync 30
,E/SMD     (  240): DCD OFF
,D/AmoledAdjustTimer(  723): prevTemp = 267, currTemp = 267, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD OFF
,D/SSRMv2:SIOP(  723): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD OFF
,D/BatteryService(  723): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:8, charge type:1, power sharing:false
,D/BatteryService(  723): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  723): stay LED for fully charged
,D/UiModeManager(  723): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1066): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  240): DCD OFF
,D/AmoledAdjustTimer(  723): prevTemp = 267, currTemp = 267, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD OFF
,D/SSRMv2:SIOP(  723): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD OFF
,E/SMD     (  240): DCD OFF
,D/BatteryService(  723): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-4, charge type:1, power sharing:false
,D/BatteryService(  723): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  723): mCoverManager.getCoverState() : true
,D/BatteryService(  723): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1066): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  240): DCD OFF
,D/AmoledAdjustTimer(  723): prevTemp = 267, currTemp = 267, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD OFF
,D/SSRMv2:SIOP(  723): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD OFF
,D/BatteryService(  723): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:6, charge type:1, power sharing:false
,D/BatteryService(  723): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  723): stay LED for fully charged
,D/UiModeManager(  723): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog(  723): !@Sync 31
,D/STATUSBAR-IconMerger( 1066): checkOverflow(384), More:false, Req:false Child:2
,V/GLSActivity( 1318): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1318): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/SMD     (  240): DCD OFF
,D/AmoledAdjustTimer(  723): prevTemp = 267, currTemp = 267, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD OFF
,D/SSRMv2:SIOP(  723): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD OFF
,D/BatteryService(  723): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:3, charge type:1, power sharing:false
,D/BatteryService(  723): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  723): stay LED for fully charged
,D/UiModeManager(  723): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1066): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  240): DCD OFF
,V/AlarmManager(  723): waitForAlarm result :8
,V/AlarmManager(  723): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1066): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1066): checkOverflow(384), More:false, Req:false Child:2
,D/AmoledAdjustTimer(  723): prevTemp = 267, currTemp = 267, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD OFF
,D/SSRMv2:SIOP(  723): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD OFF
,E/SMD     (  240): DCD OFF
,D/BatteryService(  723): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:5, charge type:1, power sharing:false
,D/BatteryService(  723): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  723): mCoverManager.getCoverState() : true
,D/BatteryService(  723): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1066): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  240): DCD OFF
,D/AmoledAdjustTimer(  723): prevTemp = 267, currTemp = 267, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD OFF
,D/SSRMv2:SIOP(  723): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD OFF
,E/Watchdog(  723): !@Sync 32
,D/BatteryService(  723): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:4, charge type:1, power sharing:false
,D/BatteryService(  723): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  723): stay LED for fully charged
,D/UiModeManager(  723): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1066): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  240): DCD OFF
,D/AmoledAdjustTimer(  723): prevTemp = 267, currTemp = 267, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD OFF
,D/SSRMv2:SIOP(  723): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD OFF
,D/BatteryService(  723): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:17, charge type:1, power sharing:false
,D/BatteryService(  723): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  723): mCoverManager.getCoverState() : true
,D/BatteryService(  723): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1066): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  240): DCD OFF
,D/AmoledAdjustTimer(  723): prevTemp = 267, currTemp = 267, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD OFF
,D/SSRMv2:SIOP(  723): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD OFF
,E/SMD     (  240): DCD OFF
,D/BatteryService(  723): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:18, charge type:1, power sharing:false
,D/BatteryService(  723): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  723): mCoverManager.getCoverState() : true
,D/BatteryService(  723): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1066): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  240): DCD OFF
,D/AmoledAdjustTimer(  723): prevTemp = 267, currTemp = 267, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD OFF
,D/SSRMv2:SIOP(  723): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD OFF
,E/Watchdog(  723): !@Sync 33
,D/BatteryService(  723): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:19, charge type:1, power sharing:false
,D/BatteryService(  723): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  723): mCoverManager.getCoverState() : true
,D/BatteryService(  723): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1066): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  240): DCD OFF
,I/PowerManagerService(  723): [PWL] Off : 950s ago
,D/AmoledAdjustTimer(  723): prevTemp = 267, currTemp = 267, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD OFF
,D/SSRMv2:SIOP(  723): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD OFF
,E/SMD     (  240): DCD OFF
,V/AlarmManager(  723): waitForAlarm result :8
,V/AlarmManager(  723): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1066): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1066): checkOverflow(384), More:false, Req:false Child:2
,D/BatteryService(  723): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:3, charge type:1, power sharing:false
,D/BatteryService(  723): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  723): stay LED for fully charged
,D/UiModeManager(  723): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1066): checkOverflow(384), More:false, Req:false Child:2
,D/AmoledAdjustTimer(  723): prevTemp = 267, currTemp = 267, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD OFF
,D/SSRMv2:SIOP(  723): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD OFF
,E/SMD     (  240): DCD OFF
,E/SMD     (  240): DCD OFF
,D/AmoledAdjustTimer(  723): prevTemp = 267, currTemp = 267, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD OFF
,D/SSRMv2:SIOP(  723): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD OFF
,E/Watchdog(  723): !@Sync 34
,E/SMD     (  240): DCD OFF
,D/AmoledAdjustTimer(  723): prevTemp = 267, currTemp = 267, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD OFF
,D/SSRMv2:SIOP(  723): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD OFF
,E/SMD     (  240): DCD OFF
,D/BatteryService(  723): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:19, charge type:1, power sharing:false
,D/BatteryService(  723): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  723): mCoverManager.getCoverState() : true
,D/BatteryService(  723): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1066): checkOverflow(384), More:false, Req:false Child:2
,D/AmoledAdjustTimer(  723): prevTemp = 267, currTemp = 267, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD OFF
,D/SSRMv2:SIOP(  723): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD OFF
,E/SMD     (  240): DCD OFF
,D/BatteryService(  723): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:20, charge type:1, power sharing:false
,D/BatteryService(  723): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  723): stay LED for fully charged
,D/UiModeManager(  723): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1066): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  240): DCD OFF
,D/AmoledAdjustTimer(  723): prevTemp = 267, currTemp = 266, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD OFF
,D/SSRMv2:SIOP(  723): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD OFF
,E/Watchdog(  723): !@Sync 35
,E/SMD     (  240): DCD OFF
,D/BatteryService(  723): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:19, charge type:1, power sharing:false
,D/BatteryService(  723): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  723): stay LED for fully charged
,D/UiModeManager(  723): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1066): checkOverflow(384), More:false, Req:false Child:2
,D/AmoledAdjustTimer(  723): prevTemp = 266, currTemp = 266, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD OFF
,D/SSRMv2:SIOP(  723): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD OFF
,E/SMD     (  240): DCD OFF
,V/AlarmManager(  723): waitForAlarm result :8
,V/AlarmManager(  723): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1066): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1066): checkOverflow(384), More:false, Req:false Child:2
,D/BatteryService(  723): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:3, charge type:1, power sharing:false
,D/BatteryService(  723): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  723): mCoverManager.getCoverState() : true
,D/BatteryService(  723): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1066): checkOverflow(384), More:false, Req:false Child:2
,D/AmoledAdjustTimer(  723): prevTemp = 266, currTemp = 266, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD OFF
,D/SSRMv2:SIOP(  723): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD OFF
,E/SMD     (  240): DCD OFF
,D/BatteryService(  723): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:2, charge type:1, power sharing:false
,D/BatteryService(  723): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  723): stay LED for fully charged
,D/UiModeManager(  723): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1066): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  240): DCD OFF
,D/AmoledAdjustTimer(  723): prevTemp = 266, currTemp = 266, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD OFF
,D/SSRMv2:SIOP(  723): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD OFF
,E/Watchdog(  723): !@Sync 36
,E/SMD     (  240): DCD OFF
,D/AmoledAdjustTimer(  723): prevTemp = 266, currTemp = 266, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD OFF
,D/SSRMv2:SIOP(  723): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD OFF
,E/SMD     (  240): DCD OFF
,D/BatteryService(  723): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:4, charge type:1, power sharing:false
,D/BatteryService(  723): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  723): mCoverManager.getCoverState() : true
,D/BatteryService(  723): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1066): checkOverflow(384), More:false, Req:false Child:2
,I/PowerManagerService(  723): [PWL] Off : 1050s ago
,D/AmoledAdjustTimer(  723): prevTemp = 266, currTemp = 266, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD OFF
,E/SMD     (  240): DCD OFF
,D/SSRMv2:SIOP(  723): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD OFF
,E/SMD     (  240): DCD OFF
,D/AmoledAdjustTimer(  723): prevTemp = 266, currTemp = 266, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD OFF
,D/SSRMv2:SIOP(  723): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD OFF
,E/Watchdog(  723): !@Sync 37
,E/SMD     (  240): DCD OFF
,D/BatteryService(  723): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:3, charge type:1, power sharing:false
,D/BatteryService(  723): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  723): mCoverManager.getCoverState() : true
,D/BatteryService(  723): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1066): checkOverflow(384), More:false, Req:false Child:2
,D/AmoledAdjustTimer(  723): prevTemp = 266, currTemp = 266, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD OFF
,D/SSRMv2:SIOP(  723): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD OFF
,E/SMD     (  240): DCD OFF
,V/AlarmManager(  723): waitForAlarm result :8
,V/AlarmManager(  723): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1066): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1066): checkOverflow(384), More:false, Req:false Child:2
,D/AmoledAdjustTimer(  723): prevTemp = 266, currTemp = 266, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD OFF
,E/SMD     (  240): DCD OFF
,D/SSRMv2:SIOP(  723): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD OFF
,E/SMD     (  240): DCD OFF
,D/AmoledAdjustTimer(  723): prevTemp = 266, currTemp = 266, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD OFF
,D/SSRMv2:SIOP(  723): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD OFF
,E/Watchdog(  723): !@Sync 38
,E/SMD     (  240): DCD OFF
,D/BatteryService(  723): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:2, charge type:1, power sharing:false
,D/BatteryService(  723): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  723): stay LED for fully charged
,D/UiModeManager(  723): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1066): checkOverflow(384), More:false, Req:false Child:2
,D/AmoledAdjustTimer(  723): prevTemp = 266, currTemp = 266, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD OFF
,D/SSRMv2:SIOP(  723): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD OFF
,E/SMD     (  240): DCD OFF
,D/BatteryService(  723): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:6, charge type:1, power sharing:false
,D/BatteryService(  723): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  723): mCoverManager.getCoverState() : true
,D/BatteryService(  723): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1066): checkOverflow(384), More:false, Req:false Child:2
,D/AmoledAdjustTimer(  723): prevTemp = 266, currTemp = 266, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD OFF
,E/SMD     (  240): DCD OFF
,D/SSRMv2:SIOP(  723): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD OFF
,E/SMD     (  240): DCD OFF
,D/BatteryService(  723): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:17, charge type:1, power sharing:false
,D/BatteryService(  723): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  723): mCoverManager.getCoverState() : true
,D/BatteryService(  723): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1066): checkOverflow(384), More:false, Req:false Child:2
,D/AmoledAdjustTimer(  723): prevTemp = 266, currTemp = 266, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD OFF
,D/SSRMv2:SIOP(  723): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD OFF
,E/Watchdog(  723): !@Sync 39
,E/SMD     (  240): DCD OFF
,D/AmoledAdjustTimer(  723): prevTemp = 266, currTemp = 266, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD OFF
,D/SSRMv2:SIOP(  723): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD OFF
,E/SMD     (  240): DCD OFF
,V/AlarmManager(  723): waitForAlarm result :8
,V/AlarmManager(  723): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1066): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1066): checkOverflow(384), More:false, Req:false Child:2
,D/BatteryService(  723): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:6, charge type:1, power sharing:false
,D/BatteryService(  723): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  723): stay LED for fully charged
,D/UiModeManager(  723): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1066): checkOverflow(384), More:false, Req:false Child:2
,D/AmoledAdjustTimer(  723): prevTemp = 266, currTemp = 266, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD OFF
,E/SMD     (  240): DCD OFF
,D/SSRMv2:SIOP(  723): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD OFF
,E/SMD     (  240): DCD OFF
,D/BatteryService(  723): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:7, charge type:1, power sharing:false
,D/BatteryService(  723): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  723): stay LED for fully charged
,D/UiModeManager(  723): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 1066): checkOverflow(384), More:false, Req:false Child:2
,D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer(  723): prevTemp = 266, currTemp = 266, prevStep = 4, currStep = 4
,D/dalvikvm(  723): GC_CONCURRENT freed 3459K, 59% free 23364K/56768K, paused 45ms+37ms, total 444ms
,D/TimaService(  723): TIMA: TimaService scheduler is intialized. 
,D/TimaService(  723): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService(  723): TimaServiceHandler.handleMessage what =1
,E/SMD     (  240): DCD OFF
,D/SSRMv2:SIOP(  723): SIOP:: AP = 300, Delta = 0
,I/PowerManagerService(  723): [PWL] Off : 1155s ago
,I/PowerManagerService(  723): [PWL]   PowerManagerService.WakeLocks: ref count=1
,I/PowerManagerService(  723): [PWL]     mWakeLockSummary : 0x1
,I/PowerManagerService(  723): [PWL]       PARTIAL_WAKE_LOCK              'TimaService' (uid=1000, pid=723, ws=null) (elapsedTime=3345)
,I/TLC_TIMA_PKM_measure_kernel(  723): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel(  723): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService(  723): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService(  723): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/SMD     (  240): DCD OFF
,E/Watchdog(  723): !@Sync 40
,E/SMD     (  240): DCD OFF
,D/BatteryService(  723): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:9, charge type:1, power sharing:false
,D/BatteryService(  723): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  723): mCoverManager.getCoverState() : true
,D/BatteryService(  723): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1066): checkOverflow(384), More:false, Req:false Child:2
,D/AmoledAdjustTimer(  723): prevTemp = 266, currTemp = 266, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD OFF
,D/SSRMv2:SIOP(  723): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD OFF
,E/SMD     (  240): DCD OFF
,D/BatteryService(  723): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:15, charge type:1, power sharing:false
,D/BatteryService(  723): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  723): stay LED for fully charged
,D/UiModeManager(  723): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1066): checkOverflow(384), More:false, Req:false Child:2
,D/AmoledAdjustTimer(  723): prevTemp = 266, currTemp = 266, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD OFF
,E/SMD     (  240): DCD OFF
,D/SSRMv2:SIOP(  723): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD OFF
,E/SMD     (  240): DCD OFF
,D/BatteryService(  723): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:16, charge type:1, power sharing:false
,D/BatteryService(  723): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  723): stay LED for fully charged
,D/UiModeManager(  723): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer(  723): prevTemp = 266, currTemp = 266, prevStep = 4, currStep = 4
,D/STATUSBAR-IconMerger( 1066): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  240): DCD OFF
,D/SSRMv2:SIOP(  723): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD OFF
,E/Watchdog(  723): !@Sync 41
,V/GLSActivity( 1318): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1318): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/SMD     (  240): DCD OFF
,D/BatteryService(  723): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:4, charge type:1, power sharing:false
,D/BatteryService(  723): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  723): mCoverManager.getCoverState() : true
,D/BatteryService(  723): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,D/AmoledAdjustTimer(  723): prevTemp = 266, currTemp = 266, prevStep = 4, currStep = 4
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1066): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  240): DCD OFF
,D/SSRMv2:SIOP(  723): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD OFF
,E/SMD     (  240): DCD OFF
,V/AlarmManager(  723): waitForAlarm result :8
,V/AlarmManager(  723): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1066): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1066): checkOverflow(384), More:false, Req:false Child:2
,V/AlarmManager(  723): waitForAlarm result :8
,I/SensorManagerA(  723): getReportingMode :: sensor.mType = 5
,D/Sensors (  723): LightSensor setDelay = 200000000
,D/Sensors (  723): LightSensor setSensorDelay = 200000000
,D/LightsService(  723): [api] onReceive : SvcLEDReceiver re-enables LightSenor and sends MSG_FORCEDSVCLEDTASK
D/Sensors (  723): Light sensor flush: not enabled 0
D/Sensors (  723): LightSensor enable = 1
D/Sensors (  723): LightSensor enableSensor = 1
D/SensorManager(  723): registerListener :: 16, CM36686 Light Sensor, 200000, 0,  
,D/Sensors (  723): LightSensor enable = 0
,D/Sensors (  723): LightSensor enableSensor = 0
,D/LightsService(  723): [SvcLED]  onSensorChanged::light value = 24
D/SensorManager(  723): unregisterListener ::   
D/lights  (  723): led_pattern : 5 +
,D/lights  (  723): led_pattern : 5 -
D/LightsService(  723): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,D/AmoledAdjustTimer(  723): prevTemp = 266, currTemp = 266, prevStep = 4, currStep = 4
,D/BatteryService(  723): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:14, charge type:1, power sharing:false
,D/BatteryService(  723): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  723): stay LED for fully charged
,D/UiModeManager(  723): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1066): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  240): DCD OFF
,E/SMD     (  240): DCD OFF
,D/SSRMv2:SIOP(  723): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD OFF
,E/SMD     (  240): DCD OFF
,D/AmoledAdjustTimer(  723): prevTemp = 266, currTemp = 266, prevStep = 4, currStep = 4
,D/BatteryService(  723): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:17, charge type:1, power sharing:false
,D/BatteryService(  723): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  723): stay LED for fully charged
,D/UiModeManager(  723): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1066): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  240): DCD OFF
,D/SSRMv2:SIOP(  723): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD OFF
,E/Watchdog(  723): !@Sync 42
,E/SMD     (  240): DCD OFF
,D/AmoledAdjustTimer(  723): prevTemp = 266, currTemp = 266, prevStep = 4, currStep = 4
,D/BatteryService(  723): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:16, charge type:1, power sharing:false
,D/BatteryService(  723): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  723): stay LED for fully charged
,D/UiModeManager(  723): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1066): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  240): DCD OFF
,D/SSRMv2:SIOP(  723): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD OFF
,E/SMD     (  240): DCD OFF
,D/AmoledAdjustTimer(  723): prevTemp = 266, currTemp = 266, prevStep = 4, currStep = 4
,D/BatteryService(  723): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:4, charge type:1, power sharing:false
,D/BatteryService(  723): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  723): stay LED for fully charged
,D/UiModeManager(  723): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1066): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  240): DCD OFF
,E/SMD     (  240): DCD OFF
,D/SSRMv2:SIOP(  723): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD OFF
,E/SMD     (  240): DCD OFF
,D/AmoledAdjustTimer(  723): prevTemp = 266, currTemp = 266, prevStep = 4, currStep = 4
,D/BatteryService(  723): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:5, charge type:1, power sharing:false
,D/BatteryService(  723): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  723): stay LED for fully charged
,D/UiModeManager(  723): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1066): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  240): DCD OFF
,D/SSRMv2:SIOP(  723): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD OFF
,E/Watchdog(  723): !@Sync 43
,E/SMD     (  240): DCD OFF
,D/AmoledAdjustTimer(  723): prevTemp = 266, currTemp = 266, prevStep = 4, currStep = 4
,D/BatteryService(  723): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:4, charge type:1, power sharing:false
,D/BatteryService(  723): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  723): stay LED for fully charged
,D/UiModeManager(  723): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1066): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  240): DCD OFF
,TIME-OUT KILL (timeout was 1200000ms),D/SSRMv2:SIOP(  723): SIOP:: AP = 300, Delta = 0
E/SMD     (  240): DCD OFF
D/AndroidRuntime( 5122): 
D/AndroidRuntime( 5122): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 5122): CheckJNI is OFF
D/AndroidRuntime( 5122): setted country_code = Poland
D/AndroidRuntime( 5122): setted countryiso_code = PL
D/AndroidRuntime( 5122): setted sales_code = XEO
D/AndroidRuntime( 5122): readGMSProperty: start
D/AndroidRuntime( 5122): readGMSProperty: already setted!!
D/AndroidRuntime( 5122): readGMSProperty: end
D/AndroidRuntime( 5122): addProductProperty: start
D/dalvikvm( 5122): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 5122): Added shared lib libjavacore.so 0x0
D/dalvikvm( 5122): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 5122): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 5122): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
E/memtrack( 5122): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 5122): failed to load memtrack module: -2
D/dalvikvm( 5122): Note: class Landroid/app/ActivityManagerNative; has 192 unimplemented (abstract) methods
D/AndroidRuntime( 5122): Calling main entry com.android.commands.pm.Pm
D/PackageManagerService(  723): deletePackageAsUser- pkg:com.test.thalitest, userId:0
D/PersonaManagerService(  723): isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
D/PersonaManagerService(  723): isFromApprovedUnInstaller: isApproved : true
D/PersonaManagerService(  723): isFromApprovedUnInstaller: isApproved before exit: true
D/PackageManager(  723): deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag3
D/PackageManager(  723): deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag3
D/PackageManagerService(  723): deletePackage- pkg:com.test.thalitest, edmuserId:0
D/PackageManagerService(  723): deletePackage- pkg:com.test.thalitest, edmuserId:-1
D/ApplicationPolicy(  723): getApplicationUninstallationEnabled
D/ApplicationPolicy(  723): getApplicationUninstallationEnabled :  enabled true
D/PackageManagerService(  723): deletePackageX- pkg:com.test.thalitest, userId:0
D/PackageManager(  723): START PACKAGE DELETE: observer{1110879056}
D/PackageManager(  723): pkg{<packageName>}
D/PackageManager(  723): user{0}
D/PackageManager(  723): deletePackageAsUser : uid = 2000 userId = 0
D/PackageManager(  723): [MSG] DELETE_PACKAGE_AS_USER
D/PackageManager(  723): !@killApplicatoin: 10179, uninstall pkg
I/ActivityManager(  723): Killing 4555:com.test.thalitest/u0a179 (adj 9): stop com.test.thalitest
D/PackageManager(  723): Sending to user 0: act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000000 Bundle[{android.intent.extra.REMOVED_FOR_ALL_USERS=true, android.intent.extra.UID=10179, android.intent.extra.DATA_REMOVED=true, android.intent.extra.user_handle=0}]
D/PackageManager(  723): Sending to user 0: act=android.intent.action.PACKAGE_FULLY_REMOVED dat=package:com.test.thalitest flg=0x4000000 Bundle[{android.intent.extra.REMOVED_FOR_ALL_USERS=true, android.intent.extra.UID=10179, android.intent.extra.DATA_REMOVED=true, android.intent.extra.user_handle=0}]
I/FPMS_FingerprintManagerService( 1085): onReceive: android.intent.action.PACKAGE_REMOVED
D/AdaptiveEventManager( 1066): action=android.intent.action.PACKAGE_REMOVED
D/dalvikvm( 1401): GC_EXPLICIT freed 4283K, 48% free 10019K/19060K, paused 3ms+3ms, total 52ms
I/InputReader(  723): Reconfiguring input devices.  changes=0x00000010
W/GeofencerStateMachine( 1218): Ignoring removeGeofence because network location is disabled.
D/dalvikvm( 2120): GC_EXPLICIT freed 1343K, 41% free 11259K/19060K, paused 19ms+17ms, total 77ms
D/QuickConnect[1.1][2] ( 3147): SconnectManager.onReceiver - action : android.intent.action.PACKAGE_REMOVED, package : com.test.thalitest
I/PackageManager(  723):   Action: "android.intent.action.SENDTO"
I/PackageManager(  723):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  723):   Scheme: "sms"
I/SELinux ( 5146): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5146):  
I/PackageManager(  723): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
D/dalvikvm(  247): GC_EXPLICIT freed 43K, 51% free 9509K/19060K, paused 2ms+3ms, total 27ms
I/PackageManager(  723):   Action: "android.intent.action.SENDTO"
I/PackageManager(  723):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  723):   Scheme: "smsto"
I/PackageManager(  723): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
I/SELinux ( 5146): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5146):  
I/SELinux ( 5146):  
I/SELinux ( 5146): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 5146): [DEBUG] seapp_context_lookup: seinfoCategory = platform
D/dalvikvm(  247): GC_EXPLICIT freed <1K, 51% free 9509K/19060K, paused 2ms+2ms, total 19ms
E/dalvikvm( 5146): >>>>> Normal User
E/dalvikvm( 5146): >>>>> com.sec.esdk.elm [ userId:0 | appId:10094 ]
E/SELinux ( 5146): [DEBUG] seapp_context_lookup: seinfoCategory = platform
I/PackageManager(  723):   Action: "android.intent.action.SENDTO"
I/PackageManager(  723):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  723):   Scheme: "mms"
I/PackageManager(  723): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
D/TimaKeyStoreProvider( 5146): in addTimaSignatureService
D/dalvikvm(  247): GC_EXPLICIT freed <1K, 51% free 9509K/19060K, paused 2ms+2ms, total 20ms
D/dalvikvm( 1756): GC_EXPLICIT freed 715K, 38% free 11862K/19060K, paused 28ms+9ms, total 199ms
D/dalvikvm(  723): GC_EXPLICIT freed 1842K, 59% free 23441K/56768K, paused 7ms+15ms, total 190ms
D/TimaKeyStoreProvider( 5146): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 5146): Added TimaKesytore provider
I/PackageManager(  723):   Action: "android.intent.action.SENDTO"
I/PackageManager(  723):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  723):   Scheme: "mmsto"
I/PackageManager(  723): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
D/RCPManagerService(  723): PackageReceiver onReceive()
I/HarmonyEASService(  723): onReceive : android.intent.action.PACKAGE_REMOVED for 0
I/PackageManager(  723):   Action: "android.intent.action.SENDTO"
I/PackageManager(  723):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  723):   Scheme: "sms"
I/PackageManager(  723): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
I/PackageManager(  723):   Action: "android.intent.action.SENDTO"
I/PackageManager(  723):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  723):   Scheme: "smsto"
I/PackageManager(  723): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
W/ActivityManager(  723): Permission Denial: getCurrentUser() from pid=5146, uid=10094 requires android.permission.INTERACT_ACROSS_USERS
W/InputMethodInfo(  723): Duplicated subtype definition found: , voice
I/PackageManager(  723):   Action: "android.intent.action.SENDTO"
I/PackageManager(  723):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  723):   Scheme: "mms"
I/PackageManager(  723): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
I/PackageManager(  723):   Action: "android.intent.action.SENDTO"
I/PackageManager(  723):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  723):   Scheme: "mmsto"
I/PackageManager(  723): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
D/elm:14132( 5146): ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
D/elm:14132( 5146): ELMEngine.ELMEngine( context ).
D/elm:14132( 5146): MDMBridge.setEnterpriseBridge()
D/elm:14132( 5146): ELMAbstractReceiver : Receive Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
D/EnterpriseDeviceManagerService(  723): Package has changed for user 0
D/EnterpriseDeviceManagerService(  723): Admin package name: com.google.android.gms
D/elm:14132( 5146): ElmAgentService : onCreate()
D/elm:14132( 5146): ElmAgentService : onHandleIntent() Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
D/elm:14132( 5146): MainReceiver.listeningToPackageRemoved()
D/elm:14132( 5146): MDMBridge.getInstance()
D/elm:14132( 5146): MDMBridge.getAllLicenseInfoFromSDK()
D/dalvikvm(  723): GC_EXPLICIT freed 576K, 59% free 23522K/56768K, paused 5ms+18ms, total 170ms
D/PackageManager(  723): delete sourFile : 
D/elm:14132( 5146): MDMBridge.getAllLicenseInfoFromSDK()
D/AndroidRuntime( 5122): Shutting down VM
D/PackageManager(  723): delete native library directory: 
D/BackupManagerService(  723): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
V/BackupManagerService(  723): removePackageParticipantsLocked: uid=10179 #1
D/PackageManager(  723): return delete result to caller: 1110879056
D/PackageManager(  723): returnCode: 1
D/dalvikvm( 5122): GC_CONCURRENT freed 96K, 14% free 670K/772K, paused 0ms+1ms, total 3ms
I/SELinux ( 5162): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5162):  
D/elm:14132( 5146): MainReceiver.listeningToPackageRemoved(). SEND to KLMS. Remove All KNOX/ONS License
D/elm:14132( 5146): ElmAgentService : onDestroy().
I/PackageManager(  723):   Action: "android.intent.action.SENDTO"
I/PackageManager(  723):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  723):   Scheme: "sms"
I/PackageManager(  723): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
W/Resources(  723): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
I/PackageManager(  723):   Action: "android.intent.action.SENDTO"
I/PackageManager(  723):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  723):   Scheme: "smsto"
I/PackageManager(  723): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
W/Resources(  723): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
I/SELinux ( 5162): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5162):  
I/SELinux ( 5162):  
I/SELinux ( 5162): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 5162): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 5162): >>>>> Normal User
E/dalvikvm( 5162): >>>>> com.sec.android.app.mss [ userId:0 | appId:10021 ]
I/PackageManager(  723):   Action: "android.intent.action.SENDTO"
I/PackageManager(  723):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  723):   Scheme: "mms"
E/SELinux ( 5162): [DEBUG] seapp_context_lookup: seinfoCategory = platform
I/PackageManager(  723): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
I/PackageManager(  723):   Action: "android.intent.action.SENDTO"
I/PackageManager(  723):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  723):   Scheme: "mmsto"
D/TimaKeyStoreProvider( 5162): in addTimaSignatureService
D/TimaKeyStoreProvider( 5162): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 5162): Added TimaKesytore provider
I/PackageManager(  723): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
W/Resources(  723): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  723): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/ActivityManager(  723): Permission Denial: getCurrentUser() from pid=5162, uid=10021 requires android.permission.INTERACT_ACROSS_USERS
W/Resources(  723): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
I/PCWCLIENTTRACE_PushUtil( 4414): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 4414): sales region : global
I/PCWCLIENTTRACE_PushUtil( 4414): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver( 4414): [onReceive] - android.intent.action.PACKAGE_REMOVED
W/Resources(  723): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  723): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  723): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  723): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  723): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  723): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
W/Resources(  723): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  723): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  723): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
W/Resources(  723): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  723): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  723): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
I/CrashAnrDetector(  723): onPackageRemoved : com.test.thalitest
D/UsbSettingsManager(  723): clearDefaults: com.test.thalitest
I/SA      ( 4599): [SUR] onReceive log=[SA = 2.0.0117 V = 19 HWD = 1280X720 2.0 dpi = 320  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = kmini3g P = kmini3gxx I = KOT49H M = SM-G800H OKLEFT false DIS KOT49H.G800HXXU1ANK2 PSS = 4.497045606779314  ]
I/SA      ( 4599): [SUR] onReceive Intent=[ action_PACKAGE_REMOVED package ]
I/ActivityManager(  723): Killing 3994:com.sec.android.app.videoplayer/u0a52 (adj 15): empty #43
I/IcingCorporaProvider( 2120): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
I/SELinux ( 5186): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5186):  
E/SQLiteLog( 2120): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
W/dalvikvm( 2120): threadid=14: thread exiting with uncaught exception (group=0x41802da0)
E/AndroidRuntime( 2120): FATAL EXCEPTION: IntentService[UpdateCorporaService]
E/AndroidRuntime( 2120): Process: com.google.android.googlequicksearchbox:search, PID: 2120
E/AndroidRuntime( 2120): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 2120): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/AndroidRuntime( 2120): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:745)
E/AndroidRuntime( 2120): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/AndroidRuntime( 2120): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/AndroidRuntime( 2120): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:507)
E/AndroidRuntime( 2120): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:418)
E/AndroidRuntime( 2120): 	at cid.d(PG:186)
E/AndroidRuntime( 2120): 	at clo.g(PG:594)
E/AndroidRuntime( 2120): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider.update(PG:301)
E/AndroidRuntime( 2120): 	at android.content.ContentProvider$Transport.update(ContentProvider.java:287)
E/AndroidRuntime( 2120): 	at android.content.ContentResolver.update(ContentResolver.java:1327)
E/AndroidRuntime( 2120): 	at clp.Rl(PG:910)
E/AndroidRuntime( 2120): 	at clr.tL(PG:827)
E/AndroidRuntime( 2120): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateCorporaService.a(PG:1271)
E/AndroidRuntime( 2120): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateCorporaService.onHandleIntent(PG:1204)
E/AndroidRuntime( 2120): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 2120): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 2120): 	at android.os.Looper.loop(Looper.java:146)
E/AndroidRuntime( 2120): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/Process ( 2120): Sending signal. PID: 2120 SIG: 9
I/SELinux ( 5186): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5186):  
I/SELinux ( 5186):  
I/SELinux ( 5186): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/DropBoxManagerService(  723): Can't write: system_app_crash
E/DropBoxManagerService(  723): java.io.FileNotFoundException: /data/system/dropbox/drop208.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  723): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService(  723): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService(  723): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService(  723): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:218)
E/DropBoxManagerService(  723): 	at android.os.DropBoxManager.addText(DropBoxManager.java:272)
E/DropBoxManagerService(  723): 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12552)
E/DropBoxManagerService(  723): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  723): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  723): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService(  723): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService(  723): 	... 5 more
E/SELinux ( 5186): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 5186): >>>>> Normal User
E/dalvikvm( 5186): >>>>> com.samsung.android.intelligenceservice [ userId:0 | appId:10005 ]
E/SELinux ( 5186): [DEBUG] seapp_context_lookup: seinfoCategory = platform
D/TimaKeyStoreProvider( 5186): in addTimaSignatureService
D/InputReader(  723): Processing first event
D/TimaKeyStoreProvider( 5186): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 5186): Added TimaKesytore provider
I/EventHub(  723): Removing device sec_touchscreen due to epoll hang-up event.
I/EventHub(  723): Removed device: path=/dev/input/event1 name=sec_touchscreen id=6 fd=218 classes=0x94
I/ActivityManager(  723): Process com.google.android.googlequicksearchbox:search (pid 2120) (adj 5) has died.
I/InputReader(  723): Device removed: id=6, name='sec_touchscreen', sources=0x80001002
D/InputReader(  723): Could not retrieve current multitouch slot index.  status=-1
D/InputReader(  723): MultiTouchMotionAccumulator: initial slot number is -1
I/EventHub(  723): Removing device '/dev/input/event1' due to inotify event
I/ActivityManager(  723): Config changes=8 {0 1.0 ?mcc?mnc en_US ldltr sw360dp w360dp h615dp 320dpi nrml long port -touch -keyb/v/h -nav/h s.6}
D/InputDispatcher(  723): setInputDispatchMode: enabled=0, frozen=1
I/SurfaceFlinger(  246): id=19 createSurf (720x1280),2 flag=404, TcreenshotS
D/PermissionCache(  246): checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (201 us)
D/Mms/MmsApp( 3803): [start]    onConfigurationChanged(),newConfig={0 1.0 ?mcc?mnc en_US ldltr sw360dp w360dp h615dp 320dpi nrml long port -touch -keyb/v/h -nav/h s.6}
D/Mms/MmsApp( 3803): [end]    onConfigurationChanged(),newConfig={0 1.0 ?mcc?mnc en_US ldltr sw360dp w360dp h615dp 320dpi nrml long port -touch -keyb/v/h -nav/h s.6}
D/PhoneStatusBar( 1066): mSettingsPanelGravity = 55
D/PhoneStatusBarView( 1066): marqueeStatusBar:123, mClearCover:0
D/MenuAppsGridFragment( 1254): onDestroyView
W/Launcher.MenuAppsGrid( 1254): Trying to exit a state that hasn't been entered
D/KeyguardUpdateMonitor( 1066): sendKeyguardVisibilityChanged(true)
I/SurfaceFlinger(  246): id=17 Removed CatteryCove (8/13)
I/SurfaceFlinger(  246): id=17 Removed CatteryCove (-2/13)
E/Tethering(  723): No numeric data
E/SmartFaceService(  723): onReceive: android.intent.action.CONFIGURATION_CHANGED
E/SmartFaceService(  723): mFolderCoverOpened: (true, true) -> true
D/KeyguardUpdateMonitor( 1066): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1066): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1066): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1066): handleKeyguardVisibilityChanged(1)
D/KeyguardUpdateMonitor( 1066): sendKeyguardVisibilityChanged(true)
D/STATUSBAR-IconMerger( 1066): checkOverflow(384), More:false, Req:false Child:2
D/STATUSBAR-QuickSettingPanel( 1066): setSingleLine:true
D/STATUSBAR-QuickSettingPanel( 1066): updateButtonInfo mButtonWidth : 144 mColumnNumber:5 orien: 1
D/STATUSBAR-QuickSettingPanel( 1066): onConfigurationChanged - dynamicallyReduceTextSize
D/STATUSBAR-QuickSettingButton( 1066): dynamicallyReduceTextSize: 144
D/STATUSBAR-QuickSettingButton( 1066): dynamicallyReduceTextSize: 144
D/STATUSBAR-QuickSettingButton( 1066): dynamicallyReduceTextSize: 144
D/STATUSBAR-QuickSettingButton( 1066): dynamicallyReduceTextSize: 144
D/STATUSBAR-QuickSettingButton( 1066): dynamicallyReduceTextSize: 144
D/STATUSBAR-QuickSettingButton( 1066): dynamicallyReduceTextSize: 144
D/STATUSBAR-QuickSettingButton( 1066): dynamicallyReduceTextSize: 144
D/STATUSBAR-QuickSettingButton( 1066): dynamicallyReduceTextSize: 144
D/STATUSBAR-QuickSettingButton( 1066): dynamicallyReduceTextSize: 144
D/STATUSBAR-QuickSettingButton( 1066): dynamicallyReduceTextSize: 144
D/STATUSBAR-QuickSettingButton( 1066): dynamicallyReduceTextSize: 144
D/STATUSBAR-QuickSettingButton( 1066): dynamicallyReduceTextSize: 144
D/STATUSBAR-QuickSettingButton( 1066): dynamicallyReduceTextSize: 144
D/STATUSBAR-QuickSettingButton( 1066): dynamicallyReduceTextSize: 144
D/STATUSBAR-QuickSettingButton( 1066): dynamicallyReduceTextSize: 144
D/STATUSBAR-QuickSettingButton( 1066): dynamicallyReduceTextSize: 144
D/STATUSBAR-QuickSettingButton( 1066): dynamicallyReduceTextSize: 144
D/KeyguardHostView( 1066): onSaveInstanceState, tstate=1
D/KeyguardGuestSelectorView( 1066): onDetachedFromWindow()
V/KeyguardUpdateMonitor( 1066): *** unregister callback for com.android.keyguard.CarrierText$1@425671f0
V/KeyguardUpdateMonitor( 1066): *** unregister callback for com.android.keyguard.MSimCarrierText$1@42567258
V/KeyguardUpdateMonitor( 1066): *** unregister callback for com.android.keyguard.CarrierText$1@42591c00
V/KeyguardUpdateMonitor( 1066): *** unregister callback for com.android.keyguard.EmergencyButton$1@425a3268
V/KeyguardUpdateMonitor( 1066): *** unregister callback for com.android.keyguard.sec.KeyguardSecurityViewOverlay$1@425dce28
V/KeyguardUpdateMonitor( 1066): *** unregister callback for com.android.keyguard.KeyguardHostView$2@4299edd0
E/KeyguardHostView( 1066): KeyguardHostView()
D/ContextualEventManager( 1066): setOnClickHandler()
V/KeyguardHostView( 1066): mIsMultipleLockOn is false
D/KeyguardHostView( 1066): mIsVoiceUnlockOn=false
V/KeyguardHostView( 1066): Initial transport state: 1, pbstate=0
I/KeyguardEffectViewMain( 1066): *** KeyguardEffectView getInstance ***
D/LockPatternUtils( 1066): isPcwEnable = null
D/ContextualEventContainer( 1066): ContextualEventContainer()
V/KeyguardUpdateMonitor( 1066): *** register callback for com.android.keyguard.KeyguardMessageArea$2@42c64ec8
V/KeyguardUpdateMonitor( 1066): *** unregister callback for null
D/ContextualEventContainer( 1066): onFinishInflate()
D/ContextualEventContainer( 1066): update()
D/LockPatternUtils( 1066): isPcwEnable = null
D/LockPatternUtils( 1066): isPcwEnable = null
D/LockPatternUtils( 1066): isPcwEnable = null
D/KeyguardHostView( 1066): mIsFMMEnabled = false, mIsCarrierLockEnabled = false, mIsCarrierLockPlusEnabled = false
D/LockPatternUtils( 1066): isPcwEnable = null
V/KeyguardHostView( 1066): showPrimarySecurityScreen(turningOff=false)
I/MDPP    ( 1066): Property: Empty
D/KeyguardHostView( 1066): showSecurityScreen(None)
V/KeyguardHostView( 1066): inflating id = 2130903095
D/SecuritySelectorView( 1066): explore by touch mode off
I/KeyguardEffectViewMain( 1066): *** KeyguardEffectView getInstance ***
I/KeyguardEffectViewMain( 1066): *** KeyguardEffectView getInstance ***
D/SecCameraShortcut( 1066): shortcutSetting:1
D/SecCameraShortcut( 1066): isKidsMode:false
D/SecCameraShortcut( 1066): isEmergencyMode:false
D/LockPatternUtils( 1066): isPcwEnable = null
D/EmergencyButton( 1066): enabled = false, :0
D/LockPatternUtils( 1066): isPcwEnable = null
I/KeyguardEffectViewMain( 1066): *** KeyguardEffectView getInstance ***
D/SecCameraShortcut( 1066): setCallback(): null
D/KeyguardVoiceEngineThread( 1066): condition = 0
D/SecuritySelectorView( 1066): mIsAirViewEnabled =false
D/SecCameraShortcut( 1066): setCallback(): not null
D/SecuritySelectorView( 1066): hideBouncer mBouncerHelpText != null
D/SecCameraShortcut( 1066): setCallback(): not null
D/SecCameraShortcut( 1066): setCallback(): not null
D/SecuritySelectorView( 1066): hideBouncer mBouncerHelpText != null
D/KeyguardHostView( 1066): mKeyguardHelpOverlay : null
D/KeyguardHostView( 1066): AUTO_WIPE = false , IT Policy = false
D/ContextualEventManager( 1066): setOnClickHandler()
E/LSO     ( 1066): LSO Service is not yet ready!!!
V/KeyguardUpdateMonitor( 1066): *** register callback for com.android.keyguard.KeyguardHostView$2@42c5ecc0
V/KeyguardUpdateMonitor( 1066): *** unregister callback for null
V/KeyguardHostView( 1066): music state changed: 0
D/KeyguardProperties( 1066): isIgnoreNationalRoaming() = false
D/VisualEffectCircleUnlockEffect( 1066): KeyguardEffectViewNone : Constructor
D/VisualEffectCircleUnlockEffect( 1066): screenWidth : 720
D/VisualEffectCircleUnlockEffect( 1066): screenHeight : 1280
D/VisualEffectCircleUnlockEffect( 1066): ratio : 0.6666667
D/VisualEffectCircleUnlockEffect( 1066): Constructor
D/VisualEffectCircleUnlockEffect( 1066): arrowImageId = 2130837796
D/VisualEffectCircleUnlockEffect( 1066): circleUnlockMaxWidth = 576
D/VisualEffectCircleUnlockEffect( 1066): circleUnlockMinWidth = 172
D/VisualEffectCircleUnlockEffect( 1066): outerStrokeWidth = 2
D/VisualEffectCircleUnlockEffect( 1066): innerStrokeWidth = 4
D/VisualEffectCircleUnlockEffect( 1066): lockSequenceTotal = 30
V/KeyguardUpdateMonitor( 1066): *** register callback for com.android.keyguard.sec.KeyguardSecurityViewOverlay$1@42c696b0
V/KeyguardUpdateMonitor( 1066): *** unregister callback for null
V/KeyguardUpdateMonitor( 1066): *** register callback for com.android.keyguard.MSimCarrierText$1@42c77270
V/KeyguardUpdateMonitor( 1066): *** unregister callback for null
D/MSimCarrierText( 1066):  onRefreshCarrierInfo:: PLMN : nullSPN:null SUB: 0
D/CarrierText( 1066): getCarrierTextForSimState: status = Normal
D/CarrierText( 1066): getCarrierTextForSimState: status = Normal
D/MSimCarrierText( 1066): updateCarrierText: text = 
D/CarrierText( 1066): getCarrierTextForSimState: status = SimNotReady
D/CarrierText( 1066): getCarrierTextForSimState: status = Normal
D/MSimCarrierText( 1066): updateCarrierText: text = 
D/MSimCarrierText( 1066):  onRefreshCarrierInfo:: PLMN : nullSPN:null SUB: 1
D/CarrierText( 1066): getCarrierTextForSimState: status = SimNotReady
D/CarrierText( 1066): getCarrierTextForSimState: status = Normal
D/MSimCarrierText( 1066): updateCarrierText: text = 
D/CarrierText( 1066): getCarrierTextForSimState: status = SimNotReady
D/CarrierText( 1066): getCarrierTextForSimState: status = SimNotReady
D/MSimCarrierText( 1066): updateCarrierText: text = null
V/KeyguardUpdateMonitor( 1066): *** register callback for com.android.keyguard.EmergencyButton$1@42c74920
V/KeyguardUpdateMonitor( 1066): *** unregister callback for null
D/LockPatternUtils( 1066): isPcwEnable = null
D/EmergencyButton( 1066): enabled = false, :0
D/SecCameraShortcut( 1066): setCallback(): not null

```
