#### Test 564496605d11e75_thali05_samsung-SM-G800H Logs


```
--------- beginning of /dev/log/main
D/GalaxyFinderApplication( 4399): [Slink platform] Version = 29011
D/GalaxyFinderApplication( 4399): [Slink platform] use state of slink location service is [false] to [true]
I/SELinux ( 4423): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 4423):  
--------- beginning of /dev/log/system
I/ActivityManager(  777): Killing 3053:com.LocalFota/u0a110 (adj 15): empty #43
I/SELinux ( 4423): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 4423):  
I/SELinux ( 4423):  
I/SELinux ( 4423): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 4423): [DEBUG] seapp_context_lookup: seinfoCategory = release
E/dalvikvm( 4423): >>>>> Normal User
E/dalvikvm( 4423): >>>>> com.sec.android.app.shealth [ userId:0 | appId:10035 ]
E/SELinux ( 4423): [DEBUG] seapp_context_lookup: seinfoCategory = release
D/TimaKeyStoreProvider( 4423): in addTimaSignatureService
D/TimaKeyStoreProvider( 4423): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 4423): Added TimaKesytore provider
V/AlarmManager(  777): waitForAlarm result :4
,V/AlarmManager(  777): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
D/dalvikvm( 3456): GC_CONCURRENT freed 6649K, 42% free 11041K/18724K, paused 3ms+4ms, total 56ms
D/dalvikvm( 3456): WAIT_FOR_CONCURRENT_GC blocked 45ms
W/ActivityManager(  777): Permission Denial: getCurrentUser() from pid=4423, uid=10035 requires android.permission.INTERACT_ACROSS_USERS
W/ContextImpl( 4423): Implicit intents with startService are not safe: Intent { act=com.sec.android.service.health.cp.accesscontrol } android.content.ContextWrapper.bindService:529 com.samsung.android.sdk.health.content.ShealthAccessControl.startService:274 com.samsung.android.sdk.health.content.ShealthAccessControl.requestPermission:212 
I/SELinux ( 4446): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 4446):  
E/Device Type Shared Preferences( 4423): Device Type Shared Preferences - getDeviceTypeChecked -true
E/Device Type Shared Preferences( 4423): Device Type Shared Preferences - not connecting to service
E/com.sec.android.app.shealth.SHealthApplication( 4423): ContentProvider is not null
I/SELinux ( 4446): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 4446):  
I/SELinux ( 4446):  
I/SELinux ( 4446): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 4446): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 4446): >>>>> Normal User
E/dalvikvm( 4446): >>>>> com.sec.android.service.health [ userId:0 | appId:10016 ]
E/SELinux ( 4446): [DEBUG] seapp_context_lookup: seinfoCategory = platform
D/TimaKeyStoreProvider( 4446): in addTimaSignatureService
D/TimaKeyStoreProvider( 4446): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 4446): Added TimaKesytore provider
V/MediaPlayer( 4423): decode(61, 33979084, 48105)
V/MediaPlayerService(  252): decode(35, 33979084, 48105)
V/MediaPlayerService(  252): player type = 3
V/AwesomePlayer(  252): setDefault
V/AwesomePlayer(  252): constructor
V/AwesomePlayer(  252): setDefault
V/AwesomePlayer(  252): reset_l()
V/AwesomePlayer(  252): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  252): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  252): mAudioTrackVector clear
V/AwesomePlayer(  252): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  252): mSecMediaClock clear
V/StagefrightPlayer(  252): StagefrightPlayer
V/AwesomePlayer(  252): setListener
V/StagefrightPlayer(  252): initCheck
V/AwesomePlayer(  252): setAudioSink
V/StagefrightPlayer(  252): setDataSource(35, 33979084, 48105)
V/AwesomePlayer(  252): reset_l()
V/AwesomePlayer(  252): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  252): notify(0xb861b190, 8, 0, 0)
V/AudioCache(  252): ignored
V/AwesomePlayer(  252): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  252): mAudioTrackVector clear
V/AwesomePlayer(  252): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  252): mSecMediaClock clear
V/AwesomePlayer(  252): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer(  252): mBitrate = -1 bits/sec
V/AwesomePlayer(  252): current audio track index (0) is added to vector
V/AwesomePlayer(  252): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer(  252): AwesomePlayer::setDataSource_l():: This is not a DRM content
V/MediaPlayerService(  252): prepare
V/AwesomePlayer(  252): prepareAsync
V/MediaPlayerService(  252): wait for prepare
V/AwesomePlayer(  252): onPrepareAsyncEvent
I/SecMediaClock(  252): SecMediaClock constructor
I/SecMediaClock(  252): reset
V/AwesomePlayer(  252): initAudioDecoder
V/AwesomePlayer(  252): checkOffloadExceptions is true
I/OMXCodec(  252): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
I/OMX     (  252): mDispatchers.add
I/OMXCodec(  252): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec(  252): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec(  252): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec(  252): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/OMXCodec(  252): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer(  252): finishAsyncPrepare_l
V/AwesomePlayer(  252): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache(  252): notify(0xb861b190, 200, 973, 0)
V/AudioCache(  252): ignored
V/AwesomePlayer(  252): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  252): notify(0xb861b190, 5, 0, 0)
V/AudioCache(  252): ignored
V/AwesomePlayer(  252): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  252): notify(0xb861b190, 1, 0, 0)
V/AudioCache(  252): prepared
V/AudioCache(  252): wait - success
V/MediaPlayerService(  252): start
V/StagefrightPlayer(  252): start
V/AwesomePlayer(  252): play
V/AwesomePlayer(  252): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer(  252): startAudioPlayer_l, sendErrorNotification (0)
I/OMXCodec(  252): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec(  252): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec(  252): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/AudioPlayer(  252):  Audioplayer kKeyAudioPCMFormat:1, 2, 0
I/AudioPlayer(  252):  Audioplayer kKeyAudioPCMFormat read fail(2, 1)
V/AudioCache(  252): open(44100, 2, 0x0, 1, 4)
V/AwesomePlayer(  252): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache(  252): notify(0xb861b190, 6, 0, 0)
V/AudioCache(  252): ignored
V/AwesomePlayer(  252): addBatteryData
V/MediaPlayerService(  252): wait for playback complete
I/OMXCodec(  252): [OMX.google.vorbis.decoder] End Of Stream
V/AwesomePlayer(  252): postAudioEOS delayUs (0)
W/ActivityManager(  777): Permission Denial: getCurrentUser() from pid=4446, uid=10016 requires android.permission.INTERACT_ACROSS_USERS
V/AwesomePlayer(  252): onCheckAudioStatus
V/AwesomePlayer(  252): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  252): onStreamDone
V/AwesomePlayer(  252): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  252): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  252): notify(0xb861b190, 2, 0, 0)
V/AudioCache(  252): playback complete - thread will wake up later
V/AwesomePlayer(  252): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  252): notify(0xb861b190, 7, 0, 0)
V/AudioCache(  252): ignored
V/AwesomePlayer(  252): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer(  252): addBatteryData
V/AudioCache(  252): wait - success
V/StagefrightPlayer(  252): reset
V/AwesomePlayer(  252): reset_l()
V/AwesomePlayer(  252): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  252): notify(0xb861b190, 8, 0, 0)
V/AudioCache(  252): ignored
V/AwesomePlayer(  252): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  252): mAudioTrackVector clear
I/OMXCodec(  252): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec(  252): [OMX.google.vorbis.decoder] stop() sendCommand(0x37, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec(  252): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
I/OMXCodec(  252): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/OMX     (  252): instance freeNode
I/AudioPlayer(  252): reset out
V/AwesomePlayer(  252): reset_l() mAudioPlayer successfully deleted
I/SecMediaClock(  252): SecMediaClock destructor
V/AwesomePlayer(  252): mSecMediaClock clear
V/StagefrightPlayer(  252): ~StagefrightPlayer
V/StagefrightPlayer(  252): reset
V/AwesomePlayer(  252): reset_l()
V/AwesomePlayer(  252): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  252): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  252): mAudioTrackVector clear
V/AwesomePlayer(  252): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  252): mSecMediaClock clear
V/AwesomePlayer(  252): destructor
V/AwesomePlayer(  252): reset_l()
V/AwesomePlayer(  252): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  252): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  252): mAudioTrackVector clear
V/AwesomePlayer(  252): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  252): mSecMediaClock clear
V/MediaPlayer( 4423): decode(62, 33914984, 10421)
V/MediaPlayerService(  252): decode(35, 33914984, 10421)
V/MediaPlayerService(  252): player type = 3
V/AwesomePlayer(  252): setDefault
V/AwesomePlayer(  252): constructor
V/AwesomePlayer(  252): setDefault
V/AwesomePlayer(  252): reset_l()
V/AwesomePlayer(  252): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  252): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  252): mAudioTrackVector clear
V/AwesomePlayer(  252): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  252): mSecMediaClock clear
V/StagefrightPlayer(  252): StagefrightPlayer
V/AwesomePlayer(  252): setListener
V/StagefrightPlayer(  252): initCheck
V/AwesomePlayer(  252): setAudioSink
V/StagefrightPlayer(  252): setDataSource(35, 33914984, 10421)
V/AwesomePlayer(  252): reset_l()
V/AwesomePlayer(  252): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  252): notify(0xb860e290, 8, 0, 0)
V/AudioCache(  252): ignored
V/AwesomePlayer(  252): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  252): mAudioTrackVector clear
V/AwesomePlayer(  252): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  252): mSecMediaClock clear
V/AwesomePlayer(  252): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer(  252): mBitrate = -1 bits/sec
V/AwesomePlayer(  252): current audio track index (0) is added to vector
V/AwesomePlayer(  252): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer(  252): AwesomePlayer::setDataSource_l():: This is not a DRM content
V/MediaPlayerService(  252): prepare
V/AwesomePlayer(  252): prepareAsync
V/MediaPlayerService(  252): wait for prepare
V/AwesomePlayer(  252): onPrepareAsyncEvent
I/SecMediaClock(  252): SecMediaClock constructor
I/SecMediaClock(  252): reset
V/AwesomePlayer(  252): initAudioDecoder
V/AwesomePlayer(  252): checkOffloadExceptions is true
I/OMXCodec(  252): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
I/OMX     (  252): mDispatchers.add
I/OMXCodec(  252): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec(  252): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec(  252): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec(  252): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/OMXCodec(  252): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer(  252): finishAsyncPrepare_l
V/AwesomePlayer(  252): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache(  252): notify(0xb860e290, 200, 973, 0)
V/AudioCache(  252): ignored
V/AwesomePlayer(  252): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  252): notify(0xb860e290, 5, 0, 0)
V/AudioCache(  252): ignored
V/AwesomePlayer(  252): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  252): notify(0xb860e290, 1, 0, 0)
V/AudioCache(  252): prepared
V/AudioCache(  252): wait - success
V/MediaPlayerService(  252): start
V/StagefrightPlayer(  252): start
V/AwesomePlayer(  252): play
V/AwesomePlayer(  252): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer(  252): startAudioPlayer_l, sendErrorNotification (0)
D/AndroidRuntime( 4437): 
D/AndroidRuntime( 4437): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
I/OMXCodec(  252): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec(  252): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec(  252): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/AudioPlayer(  252):  Audioplayer kKeyAudioPCMFormat:1, 2, 0
I/AudioPlayer(  252):  Audioplayer kKeyAudioPCMFormat read fail(2, 1)
V/AudioCache(  252): open(44100, 2, 0x0, 1, 4)
V/AwesomePlayer(  252): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache(  252): notify(0xb860e290, 6, 0, 0)
V/AudioCache(  252): ignored
V/AwesomePlayer(  252): addBatteryData
I/AudioPlayer(  252): First fillBuffer call!!
V/MediaPlayerService(  252): wait for playback complete
D/AndroidRuntime( 4437): CheckJNI is OFF
D/AndroidRuntime( 4437): setted country_code = Poland
D/AndroidRuntime( 4437): setted countryiso_code = PL
D/AndroidRuntime( 4437): setted sales_code = XEO
D/AndroidRuntime( 4437): readGMSProperty: start
D/AndroidRuntime( 4437): readGMSProperty: already setted!!
D/AndroidRuntime( 4437): readGMSProperty: end
D/AndroidRuntime( 4437): addProductProperty: start
I/OMXCodec(  252): [OMX.google.vorbis.decoder] End Of Stream
V/AwesomePlayer(  252): postAudioEOS delayUs (0)
V/AwesomePlayer(  252): onCheckAudioStatus
V/AwesomePlayer(  252): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  252): onStreamDone
V/AwesomePlayer(  252): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  252): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  252): notify(0xb860e290, 2, 0, 0)
V/AudioCache(  252): playback complete - thread will wake up later
V/AwesomePlayer(  252): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  252): notify(0xb860e290, 7, 0, 0)
V/AudioCache(  252): ignored
V/AwesomePlayer(  252): cancelPlayerEvents (keepNotifications=1)
D/dalvikvm( 4437): Trying to load lib libjavacore.so 0x0
V/AwesomePlayer(  252): addBatteryData
V/AudioCache(  252): wait - success
V/StagefrightPlayer(  252): reset
V/AwesomePlayer(  252): reset_l()
V/AwesomePlayer(  252): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  252): notify(0xb860e290, 8, 0, 0)
V/AudioCache(  252): ignored
V/AwesomePlayer(  252): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  252): mAudioTrackVector clear
I/OMXCodec(  252): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec(  252): [OMX.google.vorbis.decoder] stop() sendCommand(0x38, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec(  252): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
D/dalvikvm( 4437): Added shared lib libjavacore.so 0x0
I/OMXCodec(  252): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/OMX     (  252): instance freeNode
I/AudioPlayer(  252): reset out
V/AwesomePlayer(  252): reset_l() mAudioPlayer successfully deleted
I/SecMediaClock(  252): SecMediaClock destructor
V/AwesomePlayer(  252): mSecMediaClock clear
V/StagefrightPlayer(  252): ~StagefrightPlayer
V/StagefrightPlayer(  252): reset
V/AwesomePlayer(  252): reset_l()
V/AwesomePlayer(  252): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  252): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  252): mAudioTrackVector clear
V/AwesomePlayer(  252): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  252): mSecMediaClock clear
V/AwesomePlayer(  252): destructor
V/AwesomePlayer(  252): reset_l()
V/AwesomePlayer(  252): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  252): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  252): mAudioTrackVector clear
D/dalvikvm( 4437): Trying to load lib libnativehelper.so 0x0
V/AwesomePlayer(  252): reset_l() mAudioPlayer successfully deleted
D/dalvikvm( 4437): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 4437): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
V/AwesomePlayer(  252): mSecMediaClock clear
V/MediaPlayer( 4423): decode(63, 37457308, 34198)
V/MediaPlayerService(  252): decode(35, 37457308, 34198)
V/MediaPlayerService(  252): player type = 3
V/AwesomePlayer(  252): setDefault
V/AwesomePlayer(  252): constructor
V/AwesomePlayer(  252): setDefault
V/AwesomePlayer(  252): reset_l()
V/AwesomePlayer(  252): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  252): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  252): mAudioTrackVector clear
V/AwesomePlayer(  252): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  252): mSecMediaClock clear
V/StagefrightPlayer(  252): StagefrightPlayer
V/AwesomePlayer(  252): setListener
V/StagefrightPlayer(  252): initCheck
V/AwesomePlayer(  252): setAudioSink
V/StagefrightPlayer(  252): setDataSource(35, 37457308, 34198)
V/AwesomePlayer(  252): reset_l()
V/AwesomePlayer(  252): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  252): notify(0xb860f860, 8, 0, 0)
V/AudioCache(  252): ignored
V/AwesomePlayer(  252): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  252): mAudioTrackVector clear
V/AwesomePlayer(  252): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  252): mSecMediaClock clear
V/AwesomePlayer(  252): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer(  252): mBitrate = -1 bits/sec
V/AwesomePlayer(  252): current audio track index (0) is added to vector
V/AwesomePlayer(  252): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer(  252): AwesomePlayer::setDataSource_l():: This is not a DRM content
V/MediaPlayerService(  252): prepare
V/AwesomePlayer(  252): prepareAsync
V/MediaPlayerService(  252): wait for prepare
V/AwesomePlayer(  252): onPrepareAsyncEvent
I/SecMediaClock(  252): SecMediaClock constructor
I/SecMediaClock(  252): reset
V/AwesomePlayer(  252): initAudioDecoder
V/AwesomePlayer(  252): checkOffloadExceptions is true
I/OMXCodec(  252): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
I/OMX     (  252): mDispatchers.add
I/OMXCodec(  252): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec(  252): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec(  252): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec(  252): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/OMXCodec(  252): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer(  252): finishAsyncPrepare_l
V/AwesomePlayer(  252): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache(  252): notify(0xb860f860, 200, 973, 0)
V/AudioCache(  252): ignored
V/AwesomePlayer(  252): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  252): notify(0xb860f860, 5, 0, 0)
V/AudioCache(  252): ignored
V/AwesomePlayer(  252): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  252): notify(0xb860f860, 1, 0, 0)
V/AudioCache(  252): prepared
V/AudioCache(  252): wait - success
V/MediaPlayerService(  252): start
V/StagefrightPlayer(  252): start
V/AwesomePlayer(  252): play
V/AwesomePlayer(  252): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer(  252): startAudioPlayer_l, sendErrorNotification (0)
I/OMXCodec(  252): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec(  252): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec(  252): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
D/dalvikvm( 4446): No JNI_OnLoad found in /system/lib/libsecure_storage_jni.so 0x42af6b28, skipping init
I/SecureStorage( 4446): [INFO]: SPID(0x00000000)Checking if this device supports Secure Storage
I/AudioPlayer(  252):  Audioplayer kKeyAudioPCMFormat:1, 2, 0
I/AudioPlayer(  252):  Audioplayer kKeyAudioPCMFormat read fail(2, 1)
V/AudioCache(  252): open(44100, 2, 0x0, 1, 4)
I/SecureStorage( 4446): [INFO]: SPID(0x00000000)This device supports Secure Storage
V/AwesomePlayer(  252): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache(  252): notify(0xb860f860, 6, 0, 0)
V/AudioCache(  252): ignored
V/AwesomePlayer(  252): addBatteryData
V/MediaPlayerService(  252): wait for playback complete
I/AudioPlayer(  252): First fillBuffer call!!
I/SecureStorage(  309): [INFO]: SPID(0x00000003)Credentials: uid 10016, gid 10016, pid 4446
I/SecureStorage(  309): [INFO]: SPID(0x00000003)Received function mask & code: 0000010C
I/SecureStorage( 4446): [INFO]: SPID(0x00000000)SS Daemon is running
I/SecureStorage( 4446): [INFO]: SPID(0x00000000)Processing data
I/SecureStorage(  309): [INFO]: SPID(0x00000003)Credentials: uid 10016, gid 10016, pid 4446
I/SecureStorage(  309): [INFO]: SPID(0x00000003)Received function mask & code: 00000106
I/OMXCodec(  252): [OMX.google.vorbis.decoder] End Of Stream
V/AwesomePlayer(  252): postAudioEOS delayUs (0)
V/AwesomePlayer(  252): onCheckAudioStatus
V/AwesomePlayer(  252): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  252): onStreamDone
V/AwesomePlayer(  252): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  252): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  252): notify(0xb860f860, 2, 0, 0)
V/AudioCache(  252): playback complete - thread will wake up later
V/AwesomePlayer(  252): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  252): notify(0xb860f860, 7, 0, 0)
V/AudioCache(  252): ignored
V/AwesomePlayer(  252): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer(  252): addBatteryData
V/AudioCache(  252): wait - success
V/StagefrightPlayer(  252): reset
V/AwesomePlayer(  252): reset_l()
V/AwesomePlayer(  252): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  252): notify(0xb860f860, 8, 0, 0)
V/AudioCache(  252): ignored
V/AwesomePlayer(  252): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  252): mAudioTrackVector clear
I/OMXCodec(  252): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec(  252): [OMX.google.vorbis.decoder] stop() sendCommand(0x39, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec(  252): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
I/OMXCodec(  252): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/OMX     (  252): instance freeNode
I/AudioPlayer(  252): reset out
V/AwesomePlayer(  252): reset_l() mAudioPlayer successfully deleted
I/SecMediaClock(  252): SecMediaClock destructor
V/AwesomePlayer(  252): mSecMediaClock clear
V/StagefrightPlayer(  252): ~StagefrightPlayer
V/StagefrightPlayer(  252): reset
V/AwesomePlayer(  252): reset_l()
V/AwesomePlayer(  252): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  252): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  252): mAudioTrackVector clear
V/AwesomePlayer(  252): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  252): mSecMediaClock clear
V/AwesomePlayer(  252): destructor
V/AwesomePlayer(  252): reset_l()
V/AwesomePlayer(  252): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  252): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  252): mAudioTrackVector clear
V/AwesomePlayer(  252): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  252): mSecMediaClock clear
V/MediaPlayer( 4423): decode(64, 33862452, 7405)
V/MediaPlayerService(  252): decode(35, 33862452, 7405)
V/MediaPlayerService(  252): player type = 3
V/AwesomePlayer(  252): setDefault
V/AwesomePlayer(  252): constructor
V/AwesomePlayer(  252): setDefault
V/AwesomePlayer(  252): reset_l()
V/AwesomePlayer(  252): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  252): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  252): mAudioTrackVector clear
V/AwesomePlayer(  252): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  252): mSecMediaClock clear
V/StagefrightPlayer(  252): StagefrightPlayer
V/AwesomePlayer(  252): setListener
V/StagefrightPlayer(  252): initCheck
V/AwesomePlayer(  252): setAudioSink
V/StagefrightPlayer(  252): setDataSource(35, 33862452, 7405)
V/AwesomePlayer(  252): reset_l()
V/AwesomePlayer(  252): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  252): notify(0xb860f9f0, 8, 0, 0)
V/AudioCache(  252): ignored
V/AwesomePlayer(  252): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  252): mAudioTrackVector clear
V/AwesomePlayer(  252): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  252): mSecMediaClock clear
V/AwesomePlayer(  252): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer(  252): mBitrate = -1 bits/sec
V/AwesomePlayer(  252): current audio track index (0) is added to vector
V/AwesomePlayer(  252): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer(  252): AwesomePlayer::setDataSource_l():: This is not a DRM content
V/MediaPlayerService(  252): prepare
V/AwesomePlayer(  252): prepareAsync
V/MediaPlayerService(  252): wait for prepare
V/AwesomePlayer(  252): onPrepareAsyncEvent
I/SecMediaClock(  252): SecMediaClock constructor
I/SecMediaClock(  252): reset
V/AwesomePlayer(  252): initAudioDecoder
V/AwesomePlayer(  252): checkOffloadExceptions is true
I/OMXCodec(  252): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
I/OMX     (  252): mDispatchers.add
I/OMXCodec(  252): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec(  252): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec(  252): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec(  252): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/OMXCodec(  252): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer(  252): finishAsyncPrepare_l
V/AwesomePlayer(  252): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache(  252): notify(0xb860f9f0, 200, 973, 0)
V/AudioCache(  252): ignored
V/AwesomePlayer(  252): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  252): notify(0xb860f9f0, 5, 0, 0)
V/AudioCache(  252): ignored
V/AwesomePlayer(  252): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  252): notify(0xb860f9f0, 1, 0, 0)
V/AudioCache(  252): prepared
V/AudioCache(  252): wait - success
V/MediaPlayerService(  252): start
V/StagefrightPlayer(  252): start
V/AwesomePlayer(  252): play
V/AwesomePlayer(  252): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer(  252): startAudioPlayer_l, sendErrorNotification (0)
I/OMXCodec(  252): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec(  252): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec(  252): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/AudioPlayer(  252):  Audioplayer kKeyAudioPCMFormat:1, 2, 0
I/AudioPlayer(  252):  Audioplayer kKeyAudioPCMFormat read fail(2, 1)
V/AudioCache(  252): open(44100, 2, 0x0, 1, 4)
V/AwesomePlayer(  252): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache(  252): notify(0xb860f9f0, 6, 0, 0)
V/AudioCache(  252): ignored
V/AwesomePlayer(  252): addBatteryData
I/AudioPlayer(  252): First fillBuffer call!!
V/MediaPlayerService(  252): wait for playback complete
I/OMXCodec(  252): [OMX.google.vorbis.decoder] End Of Stream
V/AwesomePlayer(  252): postAudioEOS delayUs (0)
V/AwesomePlayer(  252): onCheckAudioStatus
V/AwesomePlayer(  252): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  252): onStreamDone
V/AwesomePlayer(  252): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  252): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  252): notify(0xb860f9f0, 2, 0, 0)
V/AudioCache(  252): playback complete - thread will wake up later
V/AwesomePlayer(  252): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  252): notify(0xb860f9f0, 7, 0, 0)
V/AudioCache(  252): ignored
V/AwesomePlayer(  252): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer(  252): addBatteryData
V/AudioCache(  252): wait - success
V/StagefrightPlayer(  252): reset
V/AwesomePlayer(  252): reset_l()
V/AwesomePlayer(  252): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  252): notify(0xb860f9f0, 8, 0, 0)
V/AudioCache(  252): ignored
V/AwesomePlayer(  252): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  252): mAudioTrackVector clear
I/OMXCodec(  252): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec(  252): [OMX.google.vorbis.decoder] stop() sendCommand(0x3a, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec(  252): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
I/OMXCodec(  252): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/OMX     (  252): instance freeNode
I/AudioPlayer(  252): reset out
V/AwesomePlayer(  252): reset_l() mAudioPlayer successfully deleted
I/SecMediaClock(  252): SecMediaClock destructor
V/AwesomePlayer(  252): mSecMediaClock clear
V/StagefrightPlayer(  252): ~StagefrightPlayer
V/StagefrightPlayer(  252): reset
V/AwesomePlayer(  252): reset_l()
V/AwesomePlayer(  252): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  252): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  252): mAudioTrackVector clear
V/AwesomePlayer(  252): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  252): mSecMediaClock clear
V/AwesomePlayer(  252): destructor
V/AwesomePlayer(  252): reset_l()
V/AwesomePlayer(  252): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  252): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  252): mAudioTrackVector clear
V/AwesomePlayer(  252): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  252): mSecMediaClock clear
V/MediaPlayer( 4423): decode(65, 37547940, 5555)
V/MediaPlayerService(  252): decode(35, 37547940, 5555)
V/MediaPlayerService(  252): player type = 3
V/AwesomePlayer(  252): setDefault
V/AwesomePlayer(  252): constructor
V/AwesomePlayer(  252): setDefault
V/AwesomePlayer(  252): reset_l()
V/AwesomePlayer(  252): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  252): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  252): mAudioTrackVector clear
V/AwesomePlayer(  252): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  252): mSecMediaClock clear
V/StagefrightPlayer(  252): StagefrightPlayer
V/AwesomePlayer(  252): setListener
V/StagefrightPlayer(  252): initCheck
V/AwesomePlayer(  252): setAudioSink
V/StagefrightPlayer(  252): setDataSource(35, 37547940, 5555)
V/AwesomePlayer(  252): reset_l()
V/AwesomePlayer(  252): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  252): notify(0xb861b2d8, 8, 0, 0)
V/AudioCache(  252): ignored
V/AwesomePlayer(  252): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  252): mAudioTrackVector clear
V/AwesomePlayer(  252): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  252): mSecMediaClock clear
V/AwesomePlayer(  252): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer(  252): mBitrate = -1 bits/sec
V/AwesomePlayer(  252): current audio track index (0) is added to vector
V/AwesomePlayer(  252): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer(  252): AwesomePlayer::setDataSource_l():: This is not a DRM content
V/MediaPlayerService(  252): prepare
V/AwesomePlayer(  252): prepareAsync
V/MediaPlayerService(  252): wait for prepare
V/AwesomePlayer(  252): onPrepareAsyncEvent
I/SecMediaClock(  252): SecMediaClock constructor
I/SecMediaClock(  252): reset
V/AwesomePlayer(  252): initAudioDecoder
V/AwesomePlayer(  252): checkOffloadExceptions is true
I/OMXCodec(  252): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
I/OMX     (  252): mDispatchers.add
I/OMXCodec(  252): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec(  252): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec(  252): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec(  252): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/OMXCodec(  252): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer(  252): finishAsyncPrepare_l
V/AwesomePlayer(  252): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache(  252): notify(0xb861b2d8, 200, 973, 0)
V/AudioCache(  252): ignored
V/AwesomePlayer(  252): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  252): notify(0xb861b2d8, 5, 0, 0)
V/AudioCache(  252): ignored
V/AwesomePlayer(  252): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  252): notify(0xb861b2d8, 1, 0, 0)
V/AudioCache(  252): prepared
V/AudioCache(  252): wait - success
V/MediaPlayerService(  252): start
V/StagefrightPlayer(  252): start
V/AwesomePlayer(  252): play
V/AwesomePlayer(  252): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer(  252): startAudioPlayer_l, sendErrorNotification (0)
I/OMXCodec(  252): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec(  252): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec(  252): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/AudioPlayer(  252):  Audioplayer kKeyAudioPCMFormat:1, 2, 0
I/AudioPlayer(  252):  Audioplayer kKeyAudioPCMFormat read fail(2, 1)
V/AudioCache(  252): open(44100, 2, 0x0, 1, 4)
V/AwesomePlayer(  252): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache(  252): notify(0xb861b2d8, 6, 0, 0)
V/AudioCache(  252): ignored
V/AwesomePlayer(  252): addBatteryData
V/MediaPlayerService(  252): wait for playback complete
I/OMXCodec(  252): [OMX.google.vorbis.decoder] End Of Stream
V/AwesomePlayer(  252): postAudioEOS delayUs (0)
V/AwesomePlayer(  252): onCheckAudioStatus
V/AwesomePlayer(  252): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  252): onStreamDone
V/AwesomePlayer(  252): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  252): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  252): notify(0xb861b2d8, 2, 0, 0)
V/AudioCache(  252): playback complete - thread will wake up later
V/AwesomePlayer(  252): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  252): notify(0xb861b2d8, 7, 0, 0)
V/AudioCache(  252): ignored
V/AwesomePlayer(  252): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer(  252): addBatteryData
V/AudioCache(  252): wait - success
V/StagefrightPlayer(  252): reset
V/AwesomePlayer(  252): reset_l()
V/AwesomePlayer(  252): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  252): notify(0xb861b2d8, 8, 0, 0)
V/AudioCache(  252): ignored
V/AwesomePlayer(  252): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  252): mAudioTrackVector clear
I/OMXCodec(  252): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec(  252): [OMX.google.vorbis.decoder] stop() sendCommand(0x3b, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec(  252): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
I/OMXCodec(  252): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/OMX     (  252): instance freeNode
I/AudioPlayer(  252): reset out
V/AwesomePlayer(  252): reset_l() mAudioPlayer successfully deleted
I/SecMediaClock(  252): SecMediaClock destructor
V/AwesomePlayer(  252): mSecMediaClock clear
V/StagefrightPlayer(  252): ~StagefrightPlayer
V/StagefrightPlayer(  252): reset
V/AwesomePlayer(  252): reset_l()
V/AwesomePlayer(  252): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  252): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  252): mAudioTrackVector clear
V/AwesomePlayer(  252): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  252): mSecMediaClock clear
V/AwesomePlayer(  252): destructor
V/AwesomePlayer(  252): reset_l()
V/AwesomePlayer(  252): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  252): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  252): mAudioTrackVector clear
V/AwesomePlayer(  252): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  252): mSecMediaClock clear
V/MediaPlayer( 4423): decode(66, 30367732, 5085)
V/MediaPlayerService(  252): decode(35, 30367732, 5085)
V/MediaPlayerService(  252): player type = 3
V/AwesomePlayer(  252): setDefault
V/AwesomePlayer(  252): constructor
V/AwesomePlayer(  252): setDefault
V/AwesomePlayer(  252): reset_l()
V/AwesomePlayer(  252): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  252): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  252): mAudioTrackVector clear
V/AwesomePlayer(  252): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  252): mSecMediaClock clear
V/StagefrightPlayer(  252): StagefrightPlayer
V/AwesomePlayer(  252): setListener
V/StagefrightPlayer(  252): initCheck
V/AwesomePlayer(  252): setAudioSink
V/StagefrightPlayer(  252): setDataSource(35, 30367732, 5085)
V/AwesomePlayer(  252): reset_l()
V/AwesomePlayer(  252): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  252): notify(0xb86154c8, 8, 0, 0)
V/AudioCache(  252): ignored
V/AwesomePlayer(  252): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  252): mAudioTrackVector clear
V/AwesomePlayer(  252): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  252): mSecMediaClock clear
V/AwesomePlayer(  252): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer(  252): mBitrate = -1 bits/sec
V/AwesomePlayer(  252): current audio track index (0) is added to vector
V/AwesomePlayer(  252): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer(  252): AwesomePlayer::setDataSource_l():: This is not a DRM content
V/MediaPlayerService(  252): prepare
V/AwesomePlayer(  252): prepareAsync
V/MediaPlayerService(  252): wait for prepare
V/AwesomePlayer(  252): onPrepareAsyncEvent
I/SecMediaClock(  252): SecMediaClock constructor
I/SecMediaClock(  252): reset
V/AwesomePlayer(  252): initAudioDecoder
V/AwesomePlayer(  252): checkOffloadExceptions is true
I/OMXCodec(  252): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
I/OMX     (  252): mDispatchers.add
I/OMXCodec(  252): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec(  252): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec(  252): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec(  252): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/OMXCodec(  252): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer(  252): finishAsyncPrepare_l
V/AwesomePlayer(  252): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache(  252): notify(0xb86154c8, 200, 973, 0)
V/AudioCache(  252): ignored
V/AwesomePlayer(  252): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  252): notify(0xb86154c8, 5, 0, 0)
V/AudioCache(  252): ignored
V/AwesomePlayer(  252): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  252): notify(0xb86154c8, 1, 0, 0)
V/AudioCache(  252): prepared
V/AudioCache(  252): wait - success
V/MediaPlayerService(  252): start
V/StagefrightPlayer(  252): start
V/AwesomePlayer(  252): play
V/AwesomePlayer(  252): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer(  252): startAudioPlayer_l, sendErrorNotification (0)
I/OMXCodec(  252): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec(  252): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec(  252): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/AudioPlayer(  252):  Audioplayer kKeyAudioPCMFormat:1, 2, 0
I/AudioPlayer(  252):  Audioplayer kKeyAudioPCMFormat read fail(2, 1)
V/AudioCache(  252): open(44100, 2, 0x0, 1, 4)
E/memtrack( 4437): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 4437): failed to load memtrack module: -2
V/AwesomePlayer(  252): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache(  252): notify(0xb86154c8, 6, 0, 0)
V/AudioCache(  252): ignored
V/AwesomePlayer(  252): addBatteryData
V/MediaPlayerService(  252): wait for playback complete
I/AudioPlayer(  252): First fillBuffer call!!
I/OMXCodec(  252): [OMX.google.vorbis.decoder] End Of Stream
V/AwesomePlayer(  252): postAudioEOS delayUs (0)
V/AwesomePlayer(  252): onCheckAudioStatus
V/AwesomePlayer(  252): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  252): onStreamDone
V/AwesomePlayer(  252): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  252): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  252): notify(0xb86154c8, 2, 0, 0)
V/AudioCache(  252): playback complete - thread will wake up later
V/AwesomePlayer(  252): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  252): notify(0xb86154c8, 7, 0, 0)
V/AudioCache(  252): ignored
V/AwesomePlayer(  252): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer(  252): addBatteryData
V/AudioCache(  252): wait - success
V/StagefrightPlayer(  252): reset
V/AwesomePlayer(  252): reset_l()
V/AwesomePlayer(  252): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  252): notify(0xb86154c8, 8, 0, 0)
V/AudioCache(  252): ignored
V/AwesomePlayer(  252): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  252): mAudioTrackVector clear
I/OMXCodec(  252): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec(  252): [OMX.google.vorbis.decoder] stop() sendCommand(0x3c, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec(  252): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
I/OMXCodec(  252): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/OMX     (  252): instance freeNode
I/AudioPlayer(  252): reset out
V/AwesomePlayer(  252): reset_l() mAudioPlayer successfully deleted
I/SecMediaClock(  252): SecMediaClock destructor
V/AwesomePlayer(  252): mSecMediaClock clear
V/StagefrightPlayer(  252): ~StagefrightPlayer
V/StagefrightPlayer(  252): reset
V/AwesomePlayer(  252): reset_l()
V/AwesomePlayer(  252): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  252): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  252): mAudioTrackVector clear
V/AwesomePlayer(  252): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  252): mSecMediaClock clear
V/AwesomePlayer(  252): destructor
V/AwesomePlayer(  252): reset_l()
V/AwesomePlayer(  252): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  252): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  252): mAudioTrackVector clear
V/AwesomePlayer(  252): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  252): mSecMediaClock clear
V/MediaPlayer( 4423): decode(68, 30372876, 21552)
V/MediaPlayerService(  252): decode(35, 30372876, 21552)
V/MediaPlayerService(  252): player type = 3
V/AwesomePlayer(  252): setDefault
V/AwesomePlayer(  252): constructor
V/AwesomePlayer(  252): setDefault
V/AwesomePlayer(  252): reset_l()
V/AwesomePlayer(  252): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  252): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  252): mAudioTrackVector clear
V/AwesomePlayer(  252): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  252): mSecMediaClock clear
V/StagefrightPlayer(  252): StagefrightPlayer
V/AwesomePlayer(  252): setListener
V/StagefrightPlayer(  252): initCheck
V/AwesomePlayer(  252): setAudioSink
V/StagefrightPlayer(  252): setDataSource(35, 30372876, 21552)
V/AwesomePlayer(  252): reset_l()
V/AwesomePlayer(  252): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  252): notify(0xb860f9f0, 8, 0, 0)
V/AudioCache(  252): ignored
V/AwesomePlayer(  252): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  252): mAudioTrackVector clear
V/AwesomePlayer(  252): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  252): mSecMediaClock clear
V/AwesomePlayer(  252): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer(  252): mBitrate = -1 bits/sec
V/AwesomePlayer(  252): current audio track index (0) is added to vector
V/AwesomePlayer(  252): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer(  252): AwesomePlayer::setDataSource_l():: This is not a DRM content
V/MediaPlayerService(  252): prepare
V/AwesomePlayer(  252): prepareAsync
V/MediaPlayerService(  252): wait for prepare
V/AwesomePlayer(  252): onPrepareAsyncEvent
I/SecMediaClock(  252): SecMediaClock constructor
I/SecMediaClock(  252): reset
V/AwesomePlayer(  252): initAudioDecoder
V/AwesomePlayer(  252): checkOffloadExceptions is true
I/OMXCodec(  252): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
I/OMX     (  252): mDispatchers.add
I/OMXCodec(  252): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec(  252): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec(  252): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec(  252): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/OMXCodec(  252): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer(  252): finishAsyncPrepare_l
V/AwesomePlayer(  252): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache(  252): notify(0xb860f9f0, 200, 973, 0)
V/AudioCache(  252): ignored
V/AwesomePlayer(  252): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  252): notify(0xb860f9f0, 5, 0, 0)
V/AudioCache(  252): ignored
V/AwesomePlayer(  252): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  252): notify(0xb860f9f0, 1, 0, 0)
V/AudioCache(  252): prepared
V/AudioCache(  252): wait - success
V/MediaPlayerService(  252): start
V/StagefrightPlayer(  252): start
V/AwesomePlayer(  252): play
V/AwesomePlayer(  252): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer(  252): startAudioPlayer_l, sendErrorNotification (0)
I/OMXCodec(  252): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec(  252): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec(  252): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/AudioPlayer(  252):  Audioplayer kKeyAudioPCMFormat:1, 2, 0
I/AudioPlayer(  252):  Audioplayer kKeyAudioPCMFormat read fail(2, 1)
V/AudioCache(  252): open(44100, 2, 0x0, 1, 4)
V/AwesomePlayer(  252): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache(  252): notify(0xb860f9f0, 6, 0, 0)
V/AudioCache(  252): ignored
V/AwesomePlayer(  252): addBatteryData
V/MediaPlayerService(  252): wait for playback complete
D/dalvikvm( 4437): Note: class Landroid/app/ActivityManagerNative; has 192 unimplemented (abstract) methods
I/OMXCodec(  252): [OMX.google.vorbis.decoder] End Of Stream
V/AwesomePlayer(  252): postAudioEOS delayUs (0)
V/AwesomePlayer(  252): onCheckAudioStatus
V/AwesomePlayer(  252): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  252): onStreamDone
V/AwesomePlayer(  252): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  252): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  252): notify(0xb860f9f0, 2, 0, 0)
V/AudioCache(  252): playback complete - thread will wake up later
V/AwesomePlayer(  252): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  252): notify(0xb860f9f0, 7, 0, 0)
V/AudioCache(  252): ignored
V/AwesomePlayer(  252): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer(  252): addBatteryData
V/AudioCache(  252): wait - success
V/StagefrightPlayer(  252): reset
V/AwesomePlayer(  252): reset_l()
V/AwesomePlayer(  252): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  252): notify(0xb860f9f0, 8, 0, 0)
V/AudioCache(  252): ignored
V/AwesomePlayer(  252): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  252): mAudioTrackVector clear
I/OMXCodec(  252): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec(  252): [OMX.google.vorbis.decoder] stop() sendCommand(0x3d, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec(  252): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
I/OMXCodec(  252): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/OMX     (  252): instance freeNode
I/AudioPlayer(  252): reset out
V/AwesomePlayer(  252): reset_l() mAudioPlayer successfully deleted
I/SecMediaClock(  252): SecMediaClock destructor
V/AwesomePlayer(  252): mSecMediaClock clear
V/StagefrightPlayer(  252): ~StagefrightPlayer
V/StagefrightPlayer(  252): reset
V/AwesomePlayer(  252): reset_l()
V/AwesomePlayer(  252): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  252): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  252): mAudioTrackVector clear
V/AwesomePlayer(  252): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  252): mSecMediaClock clear
V/AwesomePlayer(  252): destructor
V/AwesomePlayer(  252): reset_l()
V/AwesomePlayer(  252): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  252): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  252): mAudioTrackVector clear
V/AwesomePlayer(  252): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  252): mSecMediaClock clear
V/MediaPlayer( 4423): decode(69, 37543652, 4230)
V/MediaPlayerService(  252): decode(35, 37543652, 4230)
V/MediaPlayerService(  252): player type = 3
V/AwesomePlayer(  252): setDefault
V/AwesomePlayer(  252): constructor
V/AwesomePlayer(  252): setDefault
V/AwesomePlayer(  252): reset_l()
V/AwesomePlayer(  252): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  252): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  252): mAudioTrackVector clear
V/AwesomePlayer(  252): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  252): mSecMediaClock clear
V/StagefrightPlayer(  252): StagefrightPlayer
V/AwesomePlayer(  252): setListener
V/StagefrightPlayer(  252): initCheck
V/AwesomePlayer(  252): setAudioSink
V/StagefrightPlayer(  252): setDataSource(35, 37543652, 4230)
V/AwesomePlayer(  252): reset_l()
V/AwesomePlayer(  252): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  252): notify(0xb8610f38, 8, 0, 0)
V/AudioCache(  252): ignored
V/AwesomePlayer(  252): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  252): mAudioTrackVector clear
V/AwesomePlayer(  252): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  252): mSecMediaClock clear
V/AwesomePlayer(  252): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer(  252): mBitrate = -1 bits/sec
V/AwesomePlayer(  252): current audio track index (0) is added to vector
V/AwesomePlayer(  252): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer(  252): AwesomePlayer::setDataSource_l():: This is not a DRM content
V/MediaPlayerService(  252): prepare
V/AwesomePlayer(  252): prepareAsync
V/MediaPlayerService(  252): wait for prepare
V/AwesomePlayer(  252): onPrepareAsyncEvent
I/SecMediaClock(  252): SecMediaClock constructor
I/SecMediaClock(  252): reset
V/AwesomePlayer(  252): initAudioDecoder
V/AwesomePlayer(  252): checkOffloadExceptions is true
I/OMXCodec(  252): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
I/OMX     (  252): mDispatchers.add
I/OMXCodec(  252): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec(  252): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec(  252): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec(  252): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/OMXCodec(  252): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer(  252): finishAsyncPrepare_l
V/AwesomePlayer(  252): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache(  252): notify(0xb8610f38, 200, 973, 0)
V/AudioCache(  252): ignored
V/AwesomePlayer(  252): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  252): notify(0xb8610f38, 5, 0, 0)
V/AudioCache(  252): ignored
V/AwesomePlayer(  252): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  252): notify(0xb8610f38, 1, 0, 0)
V/AudioCache(  252): prepared
V/AudioCache(  252): wait - success
V/MediaPlayerService(  252): start
V/StagefrightPlayer(  252): start
V/AwesomePlayer(  252): play
V/AwesomePlayer(  252): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer(  252): startAudioPlayer_l, sendErrorNotification (0)
I/OMXCodec(  252): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec(  252): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec(  252): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/OMXCodec(  252): [OMX.google.vorbis.decoder] End Of Stream
I/AudioPlayer(  252):  Audioplayer kKeyAudioPCMFormat:1, 1, 0
I/AudioPlayer(  252):  Audioplayer kKeyAudioPCMFormat read fail(1, 1)
V/AudioCache(  252): open(44100, 1, 0x0, 1, 4)
V/AwesomePlayer(  252): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache(  252): notify(0xb8610f38, 6, 0, 0)
V/AudioCache(  252): ignored
V/AwesomePlayer(  252): addBatteryData
V/MediaPlayerService(  252): wait for playback complete
V/AwesomePlayer(  252): postAudioEOS delayUs (0)
V/AwesomePlayer(  252): onCheckAudioStatus
V/AwesomePlayer(  252): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  252): onStreamDone
V/AwesomePlayer(  252): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  252): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  252): notify(0xb8610f38, 2, 0, 0)
V/AudioCache(  252): playback complete - thread will wake up later
V/AwesomePlayer(  252): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  252): notify(0xb8610f38, 7, 0, 0)
V/AudioCache(  252): ignored
V/AwesomePlayer(  252): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer(  252): addBatteryData
V/AudioCache(  252): wait - success
V/StagefrightPlayer(  252): reset
V/AwesomePlayer(  252): reset_l()
V/AwesomePlayer(  252): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  252): notify(0xb8610f38, 8, 0, 0)
V/AudioCache(  252): ignored
V/AwesomePlayer(  252): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  252): mAudioTrackVector clear
I/OMXCodec(  252): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec(  252): [OMX.google.vorbis.decoder] stop() sendCommand(0x3e, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec(  252): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
D/AndroidRuntime( 4437): Calling main entry com.android.commands.am.Am
I/OMXCodec(  252): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/OMX     (  252): instance freeNode
I/AudioPlayer(  252): reset out
V/AwesomePlayer(  252): reset_l() mAudioPlayer successfully deleted
I/SecMediaClock(  252): SecMediaClock destructor
V/AwesomePlayer(  252): mSecMediaClock clear
V/StagefrightPlayer(  252): ~StagefrightPlayer
V/StagefrightPlayer(  252): reset
V/AwesomePlayer(  252): reset_l()
V/AwesomePlayer(  252): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  252): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  252): mAudioTrackVector clear
V/AwesomePlayer(  252): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  252): mSecMediaClock clear
V/AwesomePlayer(  252): destructor
V/AwesomePlayer(  252): reset_l()
V/AwesomePlayer(  252): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  252): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  252): mAudioTrackVector clear
V/AwesomePlayer(  252): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  252): mSecMediaClock clear
V/MediaPlayer( 4423): decode(70, 30337076, 9400)
V/MediaPlayerService(  252): decode(35, 30337076, 9400)
V/MediaPlayerService(  252): player type = 3
V/AwesomePlayer(  252): setDefault
V/AwesomePlayer(  252): constructor
V/AwesomePlayer(  252): setDefault
V/AwesomePlayer(  252): reset_l()
V/AwesomePlayer(  252): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  252): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  252): mAudioTrackVector clear
V/AwesomePlayer(  252): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  252): mSecMediaClock clear
V/StagefrightPlayer(  252): StagefrightPlayer
V/AwesomePlayer(  252): setListener
V/StagefrightPlayer(  252): initCheck
V/AwesomePlayer(  252): setAudioSink
V/StagefrightPlayer(  252): setDataSource(35, 30337076, 9400)
V/AwesomePlayer(  252): reset_l()
V/AwesomePlayer(  252): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  252): notify(0xb861d098, 8, 0, 0)
V/AudioCache(  252): ignored
V/AwesomePlayer(  252): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  252): mAudioTrackVector clear
V/AwesomePlayer(  252): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  252): mSecMediaClock clear
V/AwesomePlayer(  252): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer(  252): mBitrate = -1 bits/sec
V/AwesomePlayer(  252): current audio track index (0) is added to vector
V/AwesomePlayer(  252): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer(  252): AwesomePlayer::setDataSource_l():: This is not a DRM content
V/MediaPlayerService(  252): prepare
V/AwesomePlayer(  252): prepareAsync
V/MediaPlayerService(  252): wait for prepare
V/AwesomePlayer(  252): onPrepareAsyncEvent
I/SecMediaClock(  252): SecMediaClock constructor
I/SecMediaClock(  252): reset
V/AwesomePlayer(  252): initAudioDecoder
V/AwesomePlayer(  252): checkOffloadExceptions is true
I/OMXCodec(  252): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
I/OMX     (  252): mDispatchers.add
I/OMXCodec(  252): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec(  252): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec(  252): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec(  252): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/OMXCodec(  252): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer(  252): finishAsyncPrepare_l
V/AwesomePlayer(  252): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache(  252): notify(0xb861d098, 200, 973, 0)
V/AudioCache(  252): ignored
V/AwesomePlayer(  252): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  252): notify(0xb861d098, 5, 0, 0)
V/AudioCache(  252): ignored
V/AwesomePlayer(  252): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  252): notify(0xb861d098, 1, 0, 0)
V/AudioCache(  252): prepared
V/AudioCache(  252): wait - success
V/MediaPlayerService(  252): start
V/StagefrightPlayer(  252): start
V/AwesomePlayer(  252): play
V/AwesomePlayer(  252): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer(  252): startAudioPlayer_l, sendErrorNotification (0)
I/OMXCodec(  252): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec(  252): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec(  252): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/AudioPlayer(  252):  Audioplayer kKeyAudioPCMFormat:1, 1, 0
I/AudioPlayer(  252):  Audioplayer kKeyAudioPCMFormat read fail(1, 1)
V/AudioCache(  252): open(44100, 1, 0x0, 1, 4)
V/AwesomePlayer(  252): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache(  252): notify(0xb861d098, 6, 0, 0)
V/AudioCache(  252): ignored
V/AwesomePlayer(  252): addBatteryData
V/MediaPlayerService(  252): wait for playback complete
I/OMXCodec(  252): [OMX.google.vorbis.decoder] End Of Stream
V/AwesomePlayer(  252): postAudioEOS delayUs (0)
V/AwesomePlayer(  252): onCheckAudioStatus
V/AwesomePlayer(  252): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  252): onStreamDone
V/AwesomePlayer(  252): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  252): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  252): notify(0xb861d098, 2, 0, 0)
V/AudioCache(  252): playback complete - thread will wake up later
V/AwesomePlayer(  252): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  252): notify(0xb861d098, 7, 0, 0)
V/AudioCache(  252): ignored
V/AwesomePlayer(  252): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer(  252): addBatteryData
V/AudioCache(  252): wait - success
V/StagefrightPlayer(  252): reset
V/AwesomePlayer(  252): reset_l()
V/AwesomePlayer(  252): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  252): notify(0xb861d098, 8, 0, 0)
V/AudioCache(  252): ignored
V/AwesomePlayer(  252): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  252): mAudioTrackVector clear
I/OMXCodec(  252): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec(  252): [OMX.google.vorbis.decoder] stop() sendCommand(0x3f, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec(  252): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
I/OMXCodec(  252): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/OMX     (  252): instance freeNode
I/AudioPlayer(  252): reset out
V/AwesomePlayer(  252): reset_l() mAudioPlayer successfully deleted
I/SecMediaClock(  252): SecMediaClock destructor
V/AwesomePlayer(  252): mSecMediaClock clear
V/StagefrightPlayer(  252): ~StagefrightPlayer
V/StagefrightPlayer(  252): reset
V/AwesomePlayer(  252): reset_l()
V/AwesomePlayer(  252): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  252): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  252): mAudioTrackVector clear
V/AwesomePlayer(  252): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  252): mSecMediaClock clear
V/AwesomePlayer(  252): destructor
V/AwesomePlayer(  252): reset_l()
V/AwesomePlayer(  252): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  252): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  252): mAudioTrackVector clear
V/AwesomePlayer(  252): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  252): mSecMediaClock clear
V/MediaPlayer( 4423): decode(71, 33925464, 44276)
V/ApplicationPolicy(  777): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
V/MediaPlayerService(  252): decode(35, 33925464, 44276)
V/MediaPlayerService(  252): player type = 3
V/AwesomePlayer(  252): setDefault
V/AwesomePlayer(  252): constructor
V/AwesomePlayer(  252): setDefault
V/AwesomePlayer(  252): reset_l()
V/AwesomePlayer(  252): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  252): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  252): mAudioTrackVector clear
V/AwesomePlayer(  252): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  252): mSecMediaClock clear
V/StagefrightPlayer(  252): StagefrightPlayer
V/AwesomePlayer(  252): setListener
V/StagefrightPlayer(  252): initCheck
V/AwesomePlayer(  252): setAudioSink
V/StagefrightPlayer(  252): setDataSource(35, 33925464, 44276)
V/AwesomePlayer(  252): reset_l()
V/AwesomePlayer(  252): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  252): notify(0xb860f860, 8, 0, 0)
V/AudioCache(  252): ignored
V/AwesomePlayer(  252): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  252): mAudioTrackVector clear
V/AwesomePlayer(  252): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  252): mSecMediaClock clear
V/AwesomePlayer(  252): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer(  252): mBitrate = -1 bits/sec
V/AwesomePlayer(  252): current audio track index (0) is added to vector
V/AwesomePlayer(  252): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer(  252): AwesomePlayer::setDataSource_l():: This is not a DRM content
V/MediaPlayerService(  252): prepare
V/AwesomePlayer(  252),: prepareAsync
V/MediaPlayerService(  252): wait for prepare
V/AwesomePlayer(  252): onPrepareAsyncEvent
I/SecMediaClock(  252): SecMediaClock constructor
I/SecMediaClock(  252): reset
V/AwesomePlayer(  252): initAudioDecoder
V/AwesomePlayer(  252): checkOffloadExceptions is true
I/OMXCodec(  252): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
I/OMX     (  252): mDispatchers.add
I/OMXCodec(  252): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec(  252): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec(  252): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec(  252): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/OMXCodec(  252): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer(  252): finishAsyncPrepare_l
V/AwesomePlayer(  252): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache(  252): notify(0xb860f860, 200, 973, 0)
V/AudioCache(  252): ignored
V/AwesomePlayer(  252): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  252): notify(0xb860f860, 5, 0, 0)
V/AudioCache(  252): ignored
V/AwesomePlayer(  252): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  252): notify(0xb860f860, 1, 0, 0)
V/AudioCache(  252): prepared
V/AudioCache(  252): wait - success
V/MediaPlayerService(  252): start
V/StagefrightPlayer(  252): start
V/AwesomePlayer(  252): play
V/AwesomePlayer(  252): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer(  252): startAudioPlayer_l, sendErrorNotification (0)
I/OMXCodec(  252): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec(  252): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec(  252): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/AudioPlayer(  252):  Audioplayer kKeyAudioPCMFormat:1, 2, 0
I/AudioPlayer(  252):  Audioplayer kKeyAudioPCMFormat read fail(2, 1)
V/AudioCache(  252): open(44100, 2, 0x0, 1, 4)
V/AwesomePlayer(  252): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache(  252): notify(0xb860f860, 6, 0, 0)
V/AudioCache(  252): ignored
V/AwesomePlayer(  252): addBatteryData
V/MediaPlayerService(  252): wait for playback complete
D/CustomFrequencyManagerService(  777): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 777  pkgName : ACTIVITY_RESUME_BOOSTER@5
W/ActivityManager(  777): mDVFSHelper.acquire()
I/SELinux ( 4518): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 4518):  
I/OMXCodec(  252): [OMX.google.vorbis.decoder] End Of Stream
V/AwesomePlayer(  252): postAudioEOS delayUs (0)
V/AwesomePlayer(  252): onCheckAudioStatus
V/AwesomePlayer(  252): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  252): onStreamDone
V/AwesomePlayer(  252): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  252): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  252): notify(0xb860f860, 2, 0, 0)
V/AudioCache(  252): playback complete - thread will wake up later
V/AwesomePlayer(  252): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  252): notify(0xb860f860, 7, 0, 0)
V/AudioCache(  252): ignored
V/AwesomePlayer(  252): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer(  252): addBatteryData
V/AudioCache(  252): wait - success
V/StagefrightPlayer(  252): reset
V/AwesomePlayer(  252): reset_l()
V/AwesomePlayer(  252): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  252): notify(0xb860f860, 8, 0, 0)
V/AudioCache(  252): ignored
V/AwesomePlayer(  252): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  252): mAudioTrackVector clear
I/OMXCodec(  252): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec(  252): [OMX.google.vorbis.decoder] stop() sendCommand(0x40, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec(  252): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
I/OMXCodec(  252): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/OMX     (  252): instance freeNode
I/AudioPlayer(  252): reset out
V/AwesomePlayer(  252): reset_l() mAudioPlayer successfully deleted
I/SecMediaClock(  252): SecMediaClock destructor
V/AwesomePlayer(  252): mSecMediaClock clear
V/StagefrightPlayer(  252): ~StagefrightPlayer
V/StagefrightPlayer(  252): reset
V/AwesomePlayer(  252): reset_l()
V/AwesomePlayer(  252): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  252): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  252): mAudioTrackVector clear
V/AwesomePlayer(  252): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  252): mSecMediaClock clear
V/AwesomePlayer(  252): destructor
V/AwesomePlayer(  252): reset_l()
V/AwesomePlayer(  252): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  252): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  252): mAudioTrackVector clear
V/AwesomePlayer(  252): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  252): mSecMediaClock clear
V/MediaPlayer( 4423): decode(72, 33885672, 29256)
V/MediaPlayerService(  252): decode(35, 33885672, 29256)
V/MediaPlayerService(  252): player type = 3
V/AwesomePlayer(  252): setDefault
V/AwesomePlayer(  252): constructor
V/AwesomePlayer(  252): setDefault
V/AwesomePlayer(  252): reset_l()
V/AwesomePlayer(  252): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  252): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  252): mAudioTrackVector clear
V/AwesomePlayer(  252): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  252): mSecMediaClock clear
V/StagefrightPlayer(  252): StagefrightPlayer
V/AwesomePlayer(  252): setListener
V/StagefrightPlayer(  252): initCheck
V/AwesomePlayer(  252): setAudioSink
V/StagefrightPlayer(  252): setDataSource(35, 33885672, 29256)
V/AwesomePlayer(  252): reset_l()
V/AwesomePlayer(  252): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  252): notify(0xb861c2c8, 8, 0, 0)
V/AudioCache(  252): ignored
V/AwesomePlayer(  252): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  252): mAudioTrackVector clear
V/AwesomePlayer(  252): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  252): mSecMediaClock clear
I/SELinux ( 4518): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 4518):  
I/SELinux ( 4518):  
I/SELinux ( 4518): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 4518): [DEBUG] seapp_context_lookup: seinfoCategory = default
E/dalvikvm( 4518): >>>>> Normal User
E/dalvikvm( 4518): >>>>> com.test.thalitest [ userId:0 | appId:10179 ]
D/LockPatternUtils( 1069): isPcwEnable = null
D/AndroidRuntime( 4437): Shutting down VM
V/AwesomePlayer(  252): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer(  252): mBitrate = -1 bits/sec
E/SELinux ( 4518): [DEBUG] seapp_context_lookup: seinfoCategory = default
V/AwesomePlayer(  252): current audio track index (0) is added to vector
V/AwesomePlayer(  252): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer(  252): AwesomePlayer::setDataSource_l():: This is not a DRM content
V/MediaPlayerService(  252): prepare
V/AwesomePlayer(  252): prepareAsync
V/MediaPlayerService(  252): wait for prepare
V/AwesomePlayer(  252): onPrepareAsyncEvent
I/SecMediaClock(  252): SecMediaClock constructor
I/SecMediaClock(  252): reset
V/AwesomePlayer(  252): initAudioDecoder
V/AwesomePlayer(  252): checkOffloadExceptions is true
I/OMXCodec(  252): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
I/OMX     (  252): mDispatchers.add
I/OMXCodec(  252): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec(  252): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec(  252): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec(  252): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/OMXCodec(  252): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer(  252): finishAsyncPrepare_l
V/AwesomePlayer(  252): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache(  252): notify(0xb861c2c8, 200, 973, 0)
V/AudioCache(  252): ignored
V/AwesomePlayer(  252): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  252): notify(0xb861c2c8, 5, 0, 0)
V/AudioCache(  252): ignored
V/AwesomePlayer(  252): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  252): notify(0xb861c2c8, 1, 0, 0)
V/AudioCache(  252): prepared
V/AudioCache(  252): wait - success
V/MediaPlayerService(  252): start
D/dalvikvm( 4437): GC_CONCURRENT freed 97K, 13% free 717K/816K, paused 0ms+0ms, total 2ms
V/StagefrightPlayer(  252): start
V/AwesomePlayer(  252): play
V/AwesomePlayer(  252): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer(  252): startAudioPlayer_l, sendErrorNotification (0)
I/OMXCodec(  252): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec(  252): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec(  252): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/AudioPlayer(  252):  Audioplayer kKeyAudioPCMFormat:1, 2, 0
I/AudioPlayer(  252):  Audioplayer kKeyAudioPCMFormat read fail(2, 1)
V/AudioCache(  252): open(44100, 2, 0x0, 1, 4)
V/AwesomePlayer(  252): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache(  252): notify(0xb861c2c8, 6, 0, 0)
V/AudioCache(  252): ignored
V/AwesomePlayer(  252): addBatteryData
V/MediaPlayerService(  252): wait for playback complete
I/SELinux ( 4531): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 4531):  
D/dalvikvm(  250): GC_EXPLICIT freed 44K, 50% free 9510K/18724K, paused 2ms+3ms, total 32ms
D/dalvikvm(  250): GC_EXPLICIT freed <1K, 50% free 9510K/18724K, paused 2ms+2ms, total 19ms
I/SELinux ( 4531): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 4531):  
I/SELinux ( 4531):  
I/SELinux ( 4531): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 4531): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 4531): >>>>> Normal User
E/dalvikvm( 4531): >>>>> com.policydm [ userId:0 | appId:1000 ]
E/SELinux ( 4531): [DEBUG] seapp_context_lookup: seinfoCategory = platform
I/ActivityManager(  777): Killing 3120:com.sec.android.app.camera/u0a147 (adj 15): empty #43
D/TimaKeyStoreProvider( 4518): in addTimaSignatureService
D/TimaKeyStoreProvider( 4518): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 4518): Added TimaKesytore provider
D/dalvikvm(  250): GC_EXPLICIT freed <1K, 50% free 9510K/18724K, paused 2ms+2ms, total 28ms
I/OMXCodec(  252): [OMX.google.vorbis.decoder] End Of Stream
V/AwesomePlayer(  252): postAudioEOS delayUs (0)
V/AwesomePlayer(  252): onCheckAudioStatus
V/AwesomePlayer(  252): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  252): onStreamDone
V/AwesomePlayer(  252): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  252): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  252): notify(0xb861c2c8, 2, 0, 0)
V/AudioCache(  252): playback complete - thread will wake up later
V/AwesomePlayer(  252): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  252): notify(0xb861c2c8, 7, 0, 0)
V/AudioCache(  252): ignored
V/AwesomePlayer(  252): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer(  252): addBatteryData
V/AudioCache(  252): wait - success
V/StagefrightPlayer(  252): reset
V/AwesomePlayer(  252): reset_l()
V/AwesomePlayer(  252): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  252): notify(0xb861c2c8, 8, 0, 0)
V/AudioCache(  252): ignored
V/AwesomePlayer(  252): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  252): mAudioTrackVector clear
I/OMXCodec(  252): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec(  252): [OMX.google.vorbis.decoder] stop() sendCommand(0x41, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec(  252): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
I/OMXCodec(  252): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/OMX     (  252): instance freeNode
I/AudioPlayer(  252): reset out
V/AwesomePlayer(  252): reset_l() mAudioPlayer successfully deleted
I/SecMediaClock(  252): SecMediaClock destructor
V/AwesomePlayer(  252): mSecMediaClock clear
V/StagefrightPlayer(  252): ~StagefrightPlayer
V/StagefrightPlayer(  252): reset
V/AwesomePlayer(  252): reset_l()
V/AwesomePlayer(  252): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  252): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  252): mAudioTrackVector clear
V/AwesomePlayer(  252): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  252): mSecMediaClock clear
V/AwesomePlayer(  252): destructor
V/AwesomePlayer(  252): reset_l()
V/AwesomePlayer(  252): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  252): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  252): mAudioTrackVector clear
V/AwesomePlayer(  252): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  252): mSecMediaClock clear
V/MediaPlayer( 4423): decode(73, 37491572, 52024)
V/MediaPlayerService(  252): decode(35, 37491572, 52024)
D/LockPatternUtils( 1069): isPcwEnable = null
V/MediaPlayerService(  252): player type = 3
V/AwesomePlayer(  252): setDefault
V/AwesomePlayer(  252): constructor
V/AwesomePlayer(  252): setDefault
V/AwesomePlayer(  252): reset_l()
V/AwesomePlayer(  252): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  252): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  252): mAudioTrackVector clear
V/AwesomePlayer(  252): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  252): mSecMediaClock clear
V/StagefrightPlayer(  252): StagefrightPlayer
V/AwesomePlayer(  252): setListener
V/StagefrightPlayer(  252): initCheck
V/AwesomePlayer(  252): setAudioSink
V/StagefrightPlayer(  252): setDataSource(35, 37491572, 52024)
V/AwesomePlayer(  252): reset_l()
V/AwesomePlayer(  252): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  252): notify(0xb861d098, 8, 0, 0)
V/AudioCache(  252): ignored
V/AwesomePlayer(  252): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  252): mAudioTrackVector clear
V/AwesomePlayer(  252): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  252): mSecMediaClock clear
V/AwesomePlayer(  252): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer(  252): mBitrate = -1 bits/sec
V/AwesomePlayer(  252): current audio track index (0) is added to vector
V/AwesomePlayer(  252): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer(  252): AwesomePlayer::setDataSource_l():: This is not a DRM content
V/MediaPlayerService(  252): prepare
V/AwesomePlayer(  252): prepareAsync
V/MediaPlayerService(  252): wait for prepare
V/AwesomePlayer(  252): onPrepareAsyncEvent
I/SecMediaClock(  252): SecMediaClock constructor
I/SecMediaClock(  252): reset
V/AwesomePlayer(  252): initAudioDecoder
V/AwesomePlayer(  252): checkOffloadExceptions is true
I/OMXCodec(  252): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
I/OMX     (  252): mDispatchers.add
I/OMXCodec(  252): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec(  252): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec(  252): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec(  252): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
D/TimaKeyStoreProvider( 4531): in addTimaSignatureService
I/OMXCodec(  252): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer(  252): finishAsyncPrepare_l
V/AwesomePlayer(  252): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache(  252): notify(0xb861d098, 200, 973, 0)
V/AudioCache(  252): ignored
V/AwesomePlayer(  252): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  252): notify(0xb861d098, 5, 0, 0)
V/AudioCache(  252): ignored
V/AwesomePlayer(  252): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  252): notify(0xb861d098, 1, 0, 0)
V/AudioCache(  252): prepared
V/AudioCache(  252): wait - success
V/MediaPlayerService(  252): start
V/StagefrightPlayer(  252): start
V/AwesomePlayer(  252): play
V/AwesomePlayer(  252): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer(  252): startAudioPlayer_l, sendErrorNotification (0)
I/OMXCodec(  252): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec(  252): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec(  252): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/AudioPlayer(  252):  Audioplayer kKeyAudioPCMFormat:1, 2, 0
I/AudioPlayer(  252):  Audioplayer kKeyAudioPCMFormat read fail(2, 1)
V/AudioCache(  252): open(48000, 2, 0x0, 1, 4)
V/AwesomePlayer(  252): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache(  252): notify(0xb861d098, 6, 0, 0)
V/AudioCache(  252): ignored
V/AwesomePlayer(  252): addBatteryData
V/MediaPlayerService(  252): wait for playback complete
D/TimaKeyStoreProvider( 4531): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 4531): Added TimaKesytore provider
I/SurfaceFlinger(  249): id=14 Removed CatteryCove (8/12)
D/SurfaceWidgetClient$ISurfaceWidgetStub( 1450): [237392/5] Surface widget visibility changed visibility = false on instance = 1
I/SurfaceFlinger(  249): id=14 Removed CatteryCove (-2/12)
D/KeyguardUpdateMonitor( 1069): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1069): handleKeyguardVisibilityChanged(1)
D/SurfaceWidgetView( 1250): destroyHardwareResources():1131381880
,W/ActivityManager(  777): Permission Denial: getCurrentUser() from pid=4518, uid=10179 requires android.permission.INTERACT_ACROSS_USERS
,I/OMXCodec(  252): [OMX.google.vorbis.decoder] End Of Stream
,V/AwesomePlayer(  252): postAudioEOS delayUs (0)
V/AwesomePlayer(  252): onCheckAudioStatus
V/AwesomePlayer(  252): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  252): onStreamDone
V/AwesomePlayer(  252): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  252): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  252): notify(0xb861d098, 2, 0, 0)
V/AudioCache(  252): playback complete - thread will wake up later
V/AwesomePlayer(  252): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  252): notify(0xb861d098, 7, 0, 0)
V/AudioCache(  252): ignored
V/AwesomePlayer(  252): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer(  252): addBatteryData
V/AudioCache(  252): wait - success
V/StagefrightPlayer(  252): reset
V/AwesomePlayer(  252): reset_l()
V/AwesomePlayer(  252): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  252): notify(0xb861d098, 8, 0, 0)
V/AudioCache(  252): ignored
V/AwesomePlayer(  252): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  252): mAudioTrackVector clear
I/OMXCodec(  252): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec(  252): [OMX.google.vorbis.decoder] stop() sendCommand(0x42, OMX_CommandStateSet, OMX_StateIdle)
,I/OMXCodec(  252): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
I/OMXCodec(  252): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
,I/OMX     (  252): instance freeNode
I/AudioPlayer(  252): reset out
V/AwesomePlayer(  252): reset_l() mAudioPlayer successfully deleted
I/SecMediaClock(  252): SecMediaClock destructor
V/AwesomePlayer(  252): mSecMediaClock clear
V/StagefrightPlayer(  252): ~StagefrightPlayer
V/StagefrightPlayer(  252): reset
V/AwesomePlayer(  252): reset_l()
V/AwesomePlayer(  252): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  252): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  252): mAudioTrackVector clear
V/AwesomePlayer(  252): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  252): mSecMediaClock clear
V/AwesomePlayer(  252): destructor
V/AwesomePlayer(  252): reset_l()
V/AwesomePlayer(  252): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  252): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  252): mAudioTrackVector clear
V/AwesomePlayer(  252): reset_l() mAudioPlayer successfully deleted
,V/AwesomePlayer(  252): mSecMediaClock clear
V/MediaPlayer( 4423): decode(74, 33969800, 9226)
,V/MediaPlayerService(  252): decode(35, 33969800, 9226)
V/MediaPlayerService(  252): player type = 3
V/AwesomePlayer(  252): setDefault
,V/AwesomePlayer(  252): constructor
V/AwesomePlayer(  252): setDefault
V/AwesomePlayer(  252): reset_l()
V/AwesomePlayer(  252): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  252): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  252): mAudioTrackVector clear
V/AwesomePlayer(  252): reset_l() mAudioPlayer successfully deleted
,V/AwesomePlayer(  252): mSecMediaClock clear
V/StagefrightPlayer(  252): StagefrightPlayer
V/AwesomePlayer(  252): setListener
V/StagefrightPlayer(  252): initCheck
V/AwesomePlayer(  252): setAudioSink
V/StagefrightPlayer(  252): setDataSource(35, 33969800, 9226)
,V/AwesomePlayer(  252): reset_l()
V/AwesomePlayer(  252): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  252): notify(0xb860ad00, 8, 0, 0)
V/AudioCache(  252): ignored
V/AwesomePlayer(  252): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  252): mAudioTrackVector clear
V/AwesomePlayer(  252): reset_l() mAudioPlayer successfully deleted
,V/AwesomePlayer(  252): mSecMediaClock clear
,W/ActivityManager(  777): Permission Denial: getCurrentUser() from pid=4518, uid=10179 requires android.permission.INTERACT_ACROSS_USERS
V/AwesomePlayer(  252): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer(  252): mBitrate = -1 bits/sec
V/AwesomePlayer(  252): current audio track index (0) is added to vector
V/AwesomePlayer(  252): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer(  252): AwesomePlayer::setDataSource_l():: This is not a DRM content
V/MediaPlayerService(  252): prepare
V/AwesomePlayer(  252): prepareAsync
V/MediaPlayerService(  252): wait for prepare
V/AwesomePlayer(  252): onPrepareAsyncEvent
I/SecMediaClock(  252): SecMediaClock constructor
I/SecMediaClock(  252): reset
V/AwesomePlayer(  252): initAudioDecoder
V/AwesomePlayer(  252): checkOffloadExceptions is true
I/OMXCodec(  252): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
I/OMX     (  252): mDispatchers.add
I/OMXCodec(  252): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec(  252): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec(  252): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec(  252): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/OMXCodec(  252): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer(  252): finishAsyncPrepare_l
V/AwesomePlayer(  252): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache(  252): notify(0xb860ad00, 200, 973, 0)
V/AudioCache(  252): ignored
V/AwesomePlayer(  252): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  252): notify(0xb860ad00, 5, 0, 0)
V/AudioCache(  252): ignored
V/AwesomePlayer(  252): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  252): notify(0xb860ad00, 1, 0, 0)
V/AudioCache(  252): prepared
V/AudioCache(  252): wait - success
V/MediaPlayerService(  252): start
V/StagefrightPlayer(  252): start
V/AwesomePlayer(  252): play
V/AwesomePlayer(  252): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer(  252): startAudioPlayer_l, sendErrorNotification (0)
I/SQLiteSecureOpenHelper( 2015): getWritableDatabase(pwd)
I/SQLiteSecureOpenHelper( 2015): getDatabaseLocked(b,b,pwd)...
I/OMXCodec(  252): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec(  252): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec(  252): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/AudioPlayer(  252):  Audioplayer kKeyAudioPCMFormat:1, 2, 0
I/AudioPlayer(  252):  Audioplayer kKeyAudioPCMFormat read fail(2, 1)
V/AudioCache(  252): open(44100, 2, 0x0, 1, 4)
V/AwesomePlayer(  252): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache(  252): notify(0xb860ad00, 6, 0, 0)
V/AudioCache(  252): ignored
V/AwesomePlayer(  252): addBatteryData
V/MediaPlayerService(  252): wait for playback complete
D/KeyguardUpdateMonitor( 1069): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1069): handleKeyguardVisibilityChanged(1)
V/WebViewChromium( 4518): Binding Chromium to the background looper Looper (main, tid 1) {427d0358}
I/chromium( 4518): [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
I/OMXCodec(  252): [OMX.google.vorbis.decoder] End Of Stream
I/BrowserProcessMain( 4518): Initializing chromium process, renderers=0
V/AwesomePlayer(  252): postAudioEOS delayUs (0)
V/AwesomePlayer(  252): onCheckAudioStatus
V/AwesomePlayer(  252): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  252): onStreamDone
V/AwesomePlayer(  252): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  252): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  252): notify(0xb860ad00, 2, 0, 0)
V/AudioCache(  252): playback complete - thread will wake up later
V/AwesomePlayer(  252): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  252): notif,y(0xb860ad00, 7, 0, 0)
V/AudioCache(  252): ignored
V/AwesomePlayer(  252): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer(  252): addBatteryData
V/AudioCache(  252): wait - success
V/StagefrightPlayer(  252): reset
V/AwesomePlayer(  252): reset_l()
V/AwesomePlayer(  252): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  252): notify(0xb860ad00, 8, 0, 0)
V/AudioCache(  252): ignored
V/AwesomePlayer(  252): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  252): mAudioTrackVector clear
I/OMXCodec(  252): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec(  252): [OMX.google.vorbis.decoder] stop() sendCommand(0x43, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec(  252): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
I/OMXCodec(  252): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/OMX     (  252): instance freeNode
I/AudioPlayer(  252): reset out
V/AwesomePlayer(  252): reset_l() mAudioPlayer successfully deleted
I/SecMediaClock(  252): SecMediaClock destructor
V/AwesomePlayer(  252): mSecMediaClock clear
V/StagefrightPlayer(  252): ~StagefrightPlayer
V/StagefrightPlayer(  252): reset
V/AwesomePlayer(  252): reset_l()
V/AwesomePlayer(  252): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  252): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  252): mAudioTrackVector clear
V/AwesomePlayer(  252): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  252): mSecMediaClock clear
V/AwesomePlayer(  252): destructor
V/AwesomePlayer(  252): reset_l()
V/AwesomePlayer(  252): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  252): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  252): mAudioTrackVector clear
V/AwesomePlayer(  252): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  252): mSecMediaClock clear
V/MediaPlayer( 4423): decode(75, 30402580, 4509)
V/MediaPlayerService(  252): decode(35, 30402580, 4509)
V/MediaPlayerService(  252): player type = 3
V/AwesomePlayer(  252): setDefault
V/AwesomePlayer(  252): constructor
V/AwesomePlayer(  252): setDefault
V/AwesomePlayer(  252): reset_l()
V/AwesomePlayer(  252): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  252): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  252): mAudioTrackVector clear
V/AwesomePlayer(  252): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  252): mSecMediaClock clear
V/StagefrightPlayer(  252): StagefrightPlayer
V/AwesomePlayer(  252): setListener
V/StagefrightPlayer(  252): initCheck
V/AwesomePlayer(  252): setAudioSink
V/StagefrightPlayer(  252): setDataSource(35, 30402580, 4509)
V/AwesomePlayer(  252): reset_l()
V/AwesomePlayer(  252): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  252): notify(0xb860f860, 8, 0, 0)
V/AudioCache(  252): ignored
V/AwesomePlayer(  252): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  252): mAudioTrackVector clear
V/AwesomePlayer(  252): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  252): mSecMediaClock clear
V/AwesomePlayer(  252): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer(  252): mBitrate = -1 bits/sec
V/AwesomePlayer(  252): current audio track index (0) is added to vector
V/AwesomePlayer(  252): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer(  252): AwesomePlayer::setDataSource_l():: This is not a DRM content
V/MediaPlayerService(  252): prepare
,V/AwesomePlayer(  252): prepareAsync
V/MediaPlayerService(  252): wait for prepare
V/AwesomePlayer(  252): onPrepareAsyncEvent
I/SecMediaClock(  252): SecMediaClock constructor
I/SecMediaClock(  252): reset
V/AwesomePlayer(  252): initAudioDecoder
V/AwesomePlayer(  252): checkOffloadExceptions is true
I/OMXCodec(  252): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
I/OMX     (  252): mDispatchers.add
I/OMXCodec(  252): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec(  252): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec(  252): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec(  252): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/OMXCodec(  252): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer(  252): finishAsyncPrepare_l
V/AwesomePlayer(  252): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache(  252): notify(0xb860f860, 200, 973, 0)
,V/AudioCache(  252): ignored
V/AwesomePlayer(  252): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  252): notify(0xb860f860, 5, 0, 0)
V/AudioCache(  252): ignored
V/AwesomePlayer(  252): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  252): notify(0xb860f860, 1, 0, 0)
V/AudioCache(  252): prepared
V/AudioCache(  252): wait - success
V/MediaPlayerService(  252): start
V/StagefrightPlayer(  252): start
V/AwesomePlayer(  252): play
V/AwesomePlayer(  252): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer(  252): startAudioPlayer_l, sendErrorNotification (0)
I/OMXCodec(  252): [OMX.google.vorbis.decoder] End Of Stream
I/OMXCodec(  252): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec(  252): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec(  252): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
W/chromium( 4518): [WARNING:proxy_service.cc(888)] PAC support disabled because there is no system implementation
I/AudioPlayer(  252):  Audioplayer kKeyAudioPCMFormat:1, 2, 0
I/AudioPlayer(  252):  Audioplayer kKeyAudioPCMFormat read fail(2, 1)
V/AudioCache(  252): open(44100, 2, 0x0, 1, 4)
,V/AwesomePlayer(  252): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache(  252): notify(0xb860f860, 6, 0, 0)
V/AudioCache(  252): ignored
V/AwesomePlayer(  252): addBatteryData
V/MediaPlayerService(  252): wait for playback complete
V/AwesomePlayer(  252): postAudioEOS delayUs (0)
V/AwesomePlayer(  252): onCheckAudioStatus
V/AwesomePlayer(  252): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  252): onStreamDone
V/AwesomePlayer(  252): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  252): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  252): notify(0xb860f860, 2, 0, 0)
,V/AudioCache(  252): playback complete - thread will wake up later
V/AwesomePlayer(  252): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  252): notify(0xb860f860, 7, 0, 0)
V/AudioCache(  252): ignored
V/AwesomePlayer(  252): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer(  252): addBatteryData
V/AudioCache(  252): wait - success
V/StagefrightPlayer(  252): reset
V/AwesomePlayer(  252): reset_l()
V/AwesomePlayer(  252): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  252): notify(0xb860f860, 8, 0, 0)
,V/AudioCache(  252): ignored
V/AwesomePlayer(  252): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  252): mAudioTrackVector clear
I/OMXCodec(  252): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec(  252): [OMX.google.vorbis.decoder] stop() sendCommand(0x44, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec(  252): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
I/OMXCodec(  252): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/OMX     (  252): instance freeNode
I/AudioPlayer(  252): reset out
V/AwesomePlayer(  252): reset_l() mAudioPlayer successfully deleted
I/SecMediaClock(  252): SecMediaClock destructor
,V/AwesomePlayer(  252): mSecMediaClock clear
V/StagefrightPlayer(  252): ~StagefrightPlayer
V/StagefrightPlayer(  252): reset
V/AwesomePlayer(  252): reset_l()
V/AwesomePlayer(  252): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  252): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  252): mAudioTrackVector clear
V/AwesomePlayer(  252): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  252): mSecMediaClock clear
V/AwesomePlayer(  252): destructor
,V/AwesomePlayer(  252): reset_l()
V/AwesomePlayer(  252): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  252): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  252): mAudioTrackVector clear
V/AwesomePlayer(  252): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  252): mSecMediaClock clear
,D/Finsky  ( 3456): [349] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 3456): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,I/SELinux ( 4576): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 4576):  
I/ActivityManager(  777): Killing 3221:com.android.email/u0a155 (adj 15): empty #43
,I/SELinux ( 4576): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 4576):  
I/SELinux ( 4576):  
,I/SELinux ( 4576): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 4576): [DEBUG] seapp_context_lookup: seinfoCategory = default
E/dalvikvm( 4576): >>>>> Normal User
,E/dalvikvm( 4576): >>>>> com.osp.app.signin [ userId:0 | appId:10043 ]
,E/SELinux ( 4576): [DEBUG] seapp_context_lookup: seinfoCategory = default
,D/TimaKeyStoreProvider( 4576): in addTimaSignatureService
,D/TimaKeyStoreProvider( 4576): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 4576): Added TimaKesytore provider
,I/SA      ( 4576): [SSP] onCreated
,I/SA      ( 4576): [TPM] There is no property file
,I/SA      ( 4576): [SCU] isHaveSA() - false
I/SA      ( 4576): [TPM] getModelProperty : null
,I/SA      ( 4576): [TPM] getCSCProperty : null
,I/SA      ( 4576): [PMR] Received action : android.intent.action.PACKAGE_ADDED
,I/SA      ( 4576): [DM] init START
,I/SA      ( 4576): [DM] This device is not a Vodafone
,I/SA      ( 4576): [DM] getCountryCodeFromCSC : PL
I/SA      ( 4576): support phone number id : false
,I/SA      ( 4576): [DM] init END
I/SA      ( 4576): [SUR] onReceive log=[SA = 2.0.0117 V = 19 HWD = 1280X720 2.0 dpi = 320  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = kmini3g P = kmini3gxx I = KOT49H M = SM-G800H OKLEFT false DIS KOT49H.G800HXXU1ANK2 PSS = 4.497045606779314  ]
I/SA      ( 4576): [SUR] onReceive Intent=[ action.PACKAGE_ADDED. package ]
I/ActivityManager(  777): Killing 3217:com.samsung.android.provider.shootingmodeprovider/u0a162 (adj 15): empty #43
D/Mms/PackageInstallReceiver( 3746): loadAuthorityPref(): sEnableAuthority = true
,I/IcingCorporaProvider( 2116): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
,W/ContextImpl( 2799): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1857 android.content.ContextWrapper.startService:506 android.content.ContextWrapper.startService:506 com.samsung.android.app.assistantmenu.AssistantMenuReceiver.onReceive:153 android.app.ActivityThread.handleReceiver:2698 
,I/SELinux ( 4594): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 4594):  
,I/SELinux ( 4594): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 4594):  
I/SELinux ( 4594):  
,I/SELinux ( 4594): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 4594): [DEBUG] seapp_context_lookup: seinfoCategory = samsung
E/dalvikvm( 4594): >>>>> Normal User
,E/dalvikvm( 4594): >>>>> com.sec.android.service.cm [ userId:0 | appId:10078 ]
,E/SELinux ( 4594): [DEBUG] seapp_context_lookup: seinfoCategory = samsung
,D/TimaKeyStoreProvider( 4594): in addTimaSignatureService
,D/TimaKeyStoreProvider( 4594): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 4594): Added TimaKesytore provider
,W/ActivityManager(  777): Permission Denial: getCurrentUser() from pid=4594, uid=10078 requires android.permission.INTERACT_ACROSS_USERS
D/CapabilityManagerService New( 4594): Receiver Broadcast:android.intent.action.PACKAGE_ADDED
I/IcingCorporaProvider( 2116): UpdateCorporaTask done [took 166 ms] updated apps [took 166 ms] 
,I/SELinux ( 4607): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 4607):  
I/ActivityManager(  777): Killing 1343:com.sec.android.provider.badge/u0a72 (adj 15): empty #43
,I/SELinux ( 4607): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 4607):  
I/SELinux ( 4607):  
,I/SELinux ( 4607): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 4607): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 4607): >>>>> Normal User
,E/dalvikvm( 4607): >>>>> com.google.android.apps.docs [ userId:0 | appId:10090 ]
,E/SELinux ( 4607): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
,I/Adreno-EGL( 4518): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 4518): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 4518): Build Date: 03/21/14 Fri
I/Adreno-EGL( 4518): Local Branch: AU200+patches_03212014
I/Adreno-EGL( 4518): Remote Branch: 
I/Adreno-EGL( 4518): Local Patches: 
I/Adreno-EGL( 4518): Reconstruct Branch: 
,I/SurfaceFlinger(  249): id=9 Removed Mauncher (7/11)
,I/SurfaceFlinger(  249): id=9 Removed Mauncher (-2/11)
,D/KeyguardUpdateMonitor( 1069): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1069): handleKeyguardVisibilityChanged(1)
,I/SecureStorage(  309): [INFO]: SPID(0x00000003)Secure Storage Daemon finished processing with result: 0
,I/SecureStorage(  309): [INFO]: SPID(0x00000003)PID: 4446, TID: 4446
,D/TimaKeyStoreProvider( 4607): in addTimaSignatureService
,D/Launcher( 1250): onTrimMemory. Level: 20
,D/TimaKeyStoreProvider( 4607): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 4607): Added TimaKesytore provider
,I/dalvikvm( 4518): Could not find method android.webkit.CookieManager.setAcceptThirdPartyCookies, referenced from method org.apache.cordova.engine.SystemCookieManager.<init>
,W/dalvikvm( 4518): VFY: unable to resolve virtual method 252: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
D/dalvikvm( 4518): VFY: replacing opcode 0x6e at 0x0016
I/dalvikvm( 4518): Could not find method android.webkit.CookieManager.flush, referenced from method org.apache.cordova.engine.SystemCookieManager.flush
W/dalvikvm( 4518): VFY: unable to resolve virtual method 247: Landroid/webkit/CookieManager;.flush ()V
,D/dalvikvm( 4518): VFY: replacing opcode 0x6e at 0x0008
,W/dalvikvm( 4518): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
,W/dalvikvm( 4518): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
I/dalvikvm( 4518): Could not find method android.webkit.WebViewClient.onReceivedClientCertRequest, referenced from method org.apache.cordova.engine.SystemWebViewClient.onReceivedClientCertRequest
W/dalvikvm( 4518): VFY: unable to resolve virtual method 305: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
,D/dalvikvm( 4518): VFY: replacing opcode 0x6f at 0x001a
,W/dalvikvm( 4518): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
I/dalvikvm( 4518): Could not find method android.webkit.PermissionRequest.getResources, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onPermissionRequest
W/dalvikvm( 4518): VFY: unable to resolve virtual method 263: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
,D/dalvikvm( 4518): VFY: replacing opcode 0x6e at 0x000d
I/dalvikvm( 4518): Could not find method android.webkit.WebChromeClient$FileChooserParams.createIntent, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onShowFileChooser
,W/dalvikvm( 4518): VFY: unable to resolve virtual method 268: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
,D/dalvikvm( 4518): VFY: replacing opcode 0x6e at 0x0000
,D/SystemWebViewEngine( 4518): CordovaWebView is running on device made by: samsung
,I/SecureStorage( 4446): [INFO]: SPID(0x00000000)Processing data has been completed
I/SecureStorage( 4446): [INFO]: SPID(0x00000000)WARNING! Failed to find SecureStorageExceptionJNI!..
I/SQLiteSecureOpenHelper( 4446): getWritableDatabase(pwd)
I/SQLiteSecureOpenHelper( 4446): getDatabaseLocked(b,b,pwd)...
,I/SQLiteSecureOpenHelper( 4446): Open platform.db in secure mode
,I/SurfaceFlinger(  249): id=17 createSurf (1x1),1 flag=404, NainActivit
,D/KeyguardUpdateMonitor( 1069): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1069): handleKeyguardVisibilityChanged(1)
,D/KeyguardUpdateMonitor( 1069): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1069): handleKeyguardVisibilityChanged(1)
,I/HWUI    ( 4518): EGLImpl-HWUI Protected EGL context created
,I/SQLiteSecureOpenHelper( 4446): ...getDatabaseLocked(b,b,pwd)
,D/SQLiteSecureOpenHelper( 4446): ...getDatabaseLocked(b,b,pwd)
,W/ActivityManager(  777): Permission Denial: getCurrentUser() from pid=4607, uid=10090 requires android.permission.INTERACT_ACROSS_USERS
,D/OpenGLRenderer( 4518): Enabling debug mode 0
,D/OpenGLRenderer( 4518): GL error from OpenGLRenderer: 0x502
,E/OpenGLRenderer( 4518):   GL_INVALID_OPERATION
,D/KeyguardUpdateMonitor( 1069): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1069): handleKeyguardVisibilityChanged(1)
,I/ActivityManager(  777): Killing 3248:com.sec.modem.settings/1000 (adj 15): empty #43
,D/CustomFrequencyManagerService(  777): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 777  tag : ACTIVITY_RESUME_BOOSTER@5
,W/ActivityManager(  777): mDVFSHelper.release()
,D/KeyguardUpdateMonitor( 1069): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1069): handleKeyguardVisibilityChanged(1)
D/CustomFrequencyManagerService(  777): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 777  pkgName : ACTIVITY_RESUME_BOOSTER@9
,D/JsMessageQueue( 4518): Set native->JS mode to OnlineEventsBridgeMode
,D/dalvikvm( 4518): Trying to load lib /data/app-lib/com.test.thalitest-2/libjxcore.so 0x42af7188
,D/dalvikvm( 4518): Added shared lib /data/app-lib/com.test.thalitest-2/libjxcore.so 0x42af7188
,D/jxcore_app_log( 4518): JniHelper::setJavaVM(0x41d6c4f8), pthread_self() = 1923138312
,W/GAV2    ( 4607): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,I/chromium( 4518): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot call method 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/SELinux ( 4642): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 4642):  
,I/SELinux ( 4642): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 4642):  
I/SELinux ( 4642):  
,I/SELinux ( 4642): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 4642): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 4642): >>>>> Normal User
E/dalvikvm( 4642): >>>>> com.samsung.android.app.watchmanagerstub [ userId:0 | appId:10100 ]
E/SELinux ( 4642): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 4642): in addTimaSignatureService
,D/TimaKeyStoreProvider( 4642): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 4642): Added TimaKesytore provider
,D/PackageIntentReceiver( 4642): ACTION_PACKAGE_ADDED
,D/PackageIntentReceiver( 4642): Not GearManger package! 
,I/SELinux ( 4657): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 4657):  
I/ActivityManager(  777): Killing 3271:tv.peel.smartremote/u0a163 (adj 15): empty #43
,I/SELinux ( 4657): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 4657):  
I/SELinux ( 4657):  
,I/SELinux ( 4657): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 4657): [DEBUG] seapp_context_lookup: seinfoCategory = release
E/dalvikvm( 4657): >>>>> Normal User
E/dalvikvm( 4657): >>>>> com.samsung.android.magazine.service [ userId:0 | appId:10106 ]
,E/SELinux ( 4657): [DEBUG] seapp_context_lookup: seinfoCategory = release
,D/TimaKeyStoreProvider( 4657): in addTimaSignatureService
,D/TimaKeyStoreProvider( 4657): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 4657): Added TimaKesytore provider
,E/SMD     (  243): DCD ON
,I/Icing   ( 1787): Indexing 04B0A0E440E57B3CEEF518675F9B8A06EBE0353B from com.google.android.googlequicksearchbox
,D/MagazineService Version( 4657): Magazine-Channel: 13
,D/MagazineService Version( 4657): Magazine-Provider: 13
,D/MagazineService Version( 4657): Magazine-Administrator: 11
,D/HeadlinesChannelApplication( 4657): [onCreate]
,D/MagazineService::MagazineBroadcastReceiver( 4657): [onReceive] android.intent.action.PACKAGE_ADDED com.test.thalitest
W/ActivityManager(  777): Permission Denial: getCurrentUser() from pid=4657, uid=10106 requires android.permission.INTERACT_ACROSS_USERS
,I/MagazineService::MagazineService( 4657): [onHandleIntent] ACTION_PACKAGE_INSTALLED
,D/dalvikvm( 4518): GC_CONCURRENT freed 4950K, 32% free 12741K/18724K, paused 3ms+3ms, total 38ms
,D/dalvikvm( 4518): WAIT_FOR_CONCURRENT_GC blocked 17ms
,I/SELinux ( 4670): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 4670):  
,D/MagazineService::MagazineService( 4657): [onHandleIntent] Send broadcast to (com.test.thalitest).
I/ActivityManager(  777): Killing 3293:org.simalliance.openmobileapi.service/1101 (adj 15): empty #43
,W/GAV2    ( 4607): Thread[main,5,main]: dispatch call queued.  Need to call GAServiceManager.getInstance().initialize().
I/ActivityManager(  777): Killing 3351:com.sec.android.app.taskmanager/u0a166 (adj 15): empty #43
,I/SELinux ( 4670): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 4670):  
I/SELinux ( 4670):  
,I/SELinux ( 4670): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 4670): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 4670): >>>>> Normal User
,E/dalvikvm( 4670): >>>>> com.samsung.helphub [ userId:0 | appId:1000 ]
,E/SELinux ( 4670): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 4670): in addTimaSignatureService
,D/TimaKeyStoreProvider( 4670): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 4670): Added TimaKesytore provider
,I/Icing   ( 1787): Indexing done 04B0A0E440E57B3CEEF518675F9B8A06EBE0353B
,I/SELinux ( 4684): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 4684):  
I/ActivityManager(  777): Killing 3369:com.samsung.android.service.travel/u0a169 (adj 15): empty #43
,D/CustomFrequencyManagerService(  777): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 777  tag : ACTIVITY_RESUME_BOOSTER@9
,I/SELinux ( 4684): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 4684):  
I/SELinux ( 4684):  
,I/SELinux ( 4684): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 4684): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 4684): >>>>> Normal User
,E/dalvikvm( 4684): >>>>> com.sec.kidsplat.installer [ userId:0 | appId:10158 ]
,E/SELinux ( 4684): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 4684): in addTimaSignatureService
,D/TimaKeyStoreProvider( 4684): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 4684): Added TimaKesytore provider
,W/ActivityManager(  777): Permission Denial: getCurrentUser() from pid=4684, uid=10158 requires android.permission.INTERACT_ACROSS_USERS
,D/KidsPlatformStub( 4684): Package not found : com.sec.android.app.kidshome
,I/SELinux ( 4696): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 4696):  
I/ActivityManager(  777): Killing 3388:com.google.android.youtube/u0a175 (adj 15): empty #43
,I/SELinux ( 4696): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 4696):  
I/SELinux ( 4696):  
,I/SELinux ( 4696): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 4696): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 4696): >>>>> Normal User
,E/dalvikvm( 4696): >>>>> com.samsung.android.provider.shootingmodeprovider [ userId:0 | appId:10162 ]
,E/SELinux ( 4696): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 4696): in addTimaSignatureService
,D/TimaKeyStoreProvider( 4696): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 4696): Added TimaKesytore provider
,I/SELinux ( 4708): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 4708):  
I/ActivityManager(  777): Killing 3068:com.sec.android.app.mt/1000 (adj 15): empty #43
,I/SELinux ( 4708): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 4708):  
I/SELinux ( 4708):  
,I/SELinux ( 4708): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 4708): [DEBUG] seapp_context_lookup: seinfoCategory = samsung
E/dalvikvm( 4708): >>>>> Normal User
E/dalvikvm( 4708): >>>>> com.sec.android.app.samsungapps [ userId:0 | appId:10040 ]
,E/SELinux ( 4708): [DEBUG] seapp_context_lookup: seinfoCategory = samsung
,D/dalvikvm( 4518): GC_CONCURRENT freed 4689K, 27% free 16228K/21968K, paused 2ms+4ms, total 48ms
,D/dalvikvm( 4518): WAIT_FOR_CONCURRENT_GC blocked 31ms
,D/dalvikvm( 4518): WAIT_FOR_CONCURRENT_GC blocked 25ms
,D/TimaKeyStoreProvider( 4708): in addTimaSignatureService
,D/TimaKeyStoreProvider( 4708): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 4708): Added TimaKesytore provider
,I/ActivityManager(  777): Killing 3574:com.sec.android.widgetapp.activeapplicationwidget/u0a152 (adj 15): empty #43
,D/Finsky  ( 3456): [1] ExternalReferrer.access$200: Package state data is missing for com.test.thalitest
,D/PackageBroadcastService( 1787): Received broadcast action=android.intent.action.PACKAGE_ADDED and uri=com.test.thalitest
I/dalvikvm( 1787): Could not find method android.app.admin.DevicePolicyManager.getProfileOwner, referenced from method com.google.android.gms.auth.WorkAccountAuthenticatorInitializer.a
W/dalvikvm( 1787): VFY: unable to resolve virtual method 174: Landroid/app/admin/DevicePolicyManager;.getProfileOwner ()Landroid/content/ComponentName;
,D/dalvikvm( 1787): VFY: replacing opcode 0x6e at 0x0053
,D/ChimeraCfgMgr( 1787): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 1787): Loading module APK com.google.android.play.games
,I/dalvikvm( 1787): Failed resolving Lcom/google/android/gms/common/permission/PermissionUtils$1; interface 96 'Landroid/content/pm/PackageManager$OnPermissionsChangedListener;'
W/dalvikvm( 1787): Link of class 'Lcom/google/android/gms/common/permission/PermissionUtils$1;' failed
,E/dalvikvm( 1787): Could not find class 'com.google.android.gms.common.permission.PermissionUtils$1', referenced from method com.google.android.gms.chimera.GmsModuleInitializer.initializeModuleV0
W/dalvikvm( 1787): VFY: unable to resolve new-instance 2374 (Lcom/google/android/gms/common/permission/PermissionUtils$1;) in Lcom/google/android/gms/chimera/GmsModuleInitializer;
,D/dalvikvm( 1787): VFY: replacing opcode 0x22 at 0x001a
,I/dalvikvm( 1787): Failed resolving Lcom/google/android/gms/common/permission/PermissionUtils$1; interface 96 'Landroid/content/pm/PackageManager$OnPermissionsChangedListener;'
W/dalvikvm( 1787): Link of class 'Lcom/google/android/gms/common/permission/PermissionUtils$1;' failed
,D/dalvikvm( 1787): DexOpt: unable to opt direct call 0x338d at 0x1c in Lcom/google/android/gms/chimera/GmsModuleInitializer;.initializeModuleV0
,D/dalvikvm(  777): GC_EXPLICIT freed 2331K, 59% free 23455K/56508K, paused 7ms+14ms, total 133ms
,D/ChimeraCfgMgr( 1787): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 1787): Module APK com.google.android.play.games already loaded
,D/ChimeraCfgMgr( 1787): Loading module com.google.android.gms.gass from APK com.google.android.gms
,D/AsyncTaskServiceImpl( 1787): Submit a task: k
,D/ChimeraCfgMgr( 1787): Loading module com.google.android.gms.gass from APK com.google.android.gms
,D/ChimeraCfgMgr( 1787): Loading module com.google.android.gms.vision from APK com.google.android.gms
,D/k       ( 1787): Processing package: com.test.thalitest
,D/dalvikvm( 4518): GC_FOR_ALLOC freed 5104K, 31% free 17219K/24640K, paused 39ms, total 39ms
,I/dalvikvm-heap( 4518): Grow heap (frag case) to 22.167MB for 2459024-byte allocation
,D/dalvikvm( 1296): GC_EXPLICIT freed 1070K, 43% free 10788K/18724K, paused 3ms+5ms, total 43ms
W/BaseAppContext( 1787): Using Auth Proxy for data requests.
,W/BaseAppContext( 1787): Using Auth Proxy for data requests.
,D/GassUtils( 1787): Found app info for package com.test.thalitest:18. Hash: 4eebbbb84f07ed56a3e96e5e8f9d6abddaaf154fffa2a65432a1006e0fa38f32
,D/k       ( 1787): Found info for package com.test.thalitest in db.
,W/BaseAppContext( 1787): Using Auth Proxy for data requests.
,W/BaseAppContext( 1787): Using Auth Proxy for data requests.
W/BaseAppContext( 1787): Using Auth Proxy for data requests.
,W/BaseAppContext( 1787): Using Auth Proxy for data requests.
,W/BaseAppContext( 1787): Using Auth Proxy for data requests.
,W/dalvikvm( 1787): VFY: unable to find class referenced in signature (Landroid/app/SharedElementCallback;)
,I/dalvikvm( 1787): Could not find method android.app.Activity.setEnterSharedElementCallback, referenced from method android.support.v4.app.w.setEnterSharedElementCallback
W/dalvikvm( 1787): VFY: unable to resolve virtual method 53: Landroid/app/Activity;.setEnterSharedElementCallback (Landroid/app/SharedElementCallback;)V
,D/dalvikvm( 1787): VFY: replacing opcode 0x6e at 0x000e
W/dalvikvm( 1787): VFY: unable to find class referenced in signature (Landroid/app/SharedElementCallback;)
,I/dalvikvm( 1787): Could not find method android.app.Activity.setExitSharedElementCallback, referenced from method android.support.v4.app.w.setExitSharedElementCallback
W/dalvikvm( 1787): VFY: unable to resolve virtual method 54: Landroid/app/Activity;.setExitSharedElementCallback (Landroid/app/SharedElementCallback;)V
,D/dalvikvm( 1787): VFY: replacing opcode 0x6e at 0x000e
I/dalvikvm( 1787): Could not find method android.app.Activity.finishAfterTransition, referenced from method android.support.v4.app.w.supportFinishAfterTransition
W/dalvikvm( 1787): VFY: unable to resolve virtual method 31: Landroid/app/Activity;.finishAfterTransition ()V
,D/dalvikvm( 1787): VFY: replacing opcode 0x6e at 0x0006
I/dalvikvm( 1787): Could not find method android.app.Activity.postponeEnterTransition, referenced from method android.support.v4.app.w.supportPostponeEnterTransition
W/dalvikvm( 1787): VFY: unable to resolve virtual method 49: Landroid/app/Activity;.postponeEnterTransition ()V
D/dalvikvm( 1787): VFY: replacing opcode 0x6e at 0x0006
I/dalvikvm( 1787): Could not find method android.app.Activity.startPostponedEnterTransition, referenced from method android.support.v4.app.w.supportStartPostponedEnterTransition
,W/dalvikvm( 1787): VFY: unable to resolve virtual method 61: Landroid/app/Activity;.startPostponedEnterTransition ()V
,D/dalvikvm( 1787): VFY: replacing opcode 0x6e at 0x0006
,I/PeopleDatabaseHelper( 1787): cleanUpNonGplusAccounts done.
,D/dalvikvm( 4518): GC_FOR_ALLOC freed 3736K, 34% free 17932K/27044K, paused 33ms, total 36ms
,W/dalvikvm( 1787): VFY: unable to find class referenced in signature (Landroid/util/Size;)
,D/ChimeraCfgMgr( 1787): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 1787): Module APK com.google.android.play.games already loaded
,D/dalvikvm( 4518): GC_FOR_ALLOC freed 1185K, 35% free 17841K/27044K, paused 30ms, total 30ms
,D/dalvikvm( 4518): GC_FOR_ALLOC freed 4467K, 38% free 19152K/30648K, paused 34ms, total 36ms
,W/jxcore-log( 4518): Initializing JXcore engine
,W/jxcore-log( 4518): JXcore engine is ready
,W/jxcore-log( 4518): Starting JXcore engine
,I/Icing   ( 1787): Indexing 49CA7E3A917E607C6D98AA15891295369CED2106 from com.google.android.gms
,W/jxcore-log( 4518): Platform android
W/jxcore-log( 4518): 
,W/jxcore-log( 4518): Process ARCH arm
W/jxcore-log( 4518): 
,D/dalvikvm( 1787): GC_CONCURRENT freed 1434K, 37% free 11904K/18724K, paused 4ms+98ms, total 142ms
,D/dalvikvm( 1787): WAIT_FOR_CONCURRENT_GC blocked 118ms
,I/Icing   ( 1787): Indexing done 49CA7E3A917E607C6D98AA15891295369CED2106
,E/SMD     (  243): DCD ON
,I/jxcore-log( 4518): JXcore Cordova bridge is ready!
I/jxcore-log( 4518): 
,W/jxcore-log( 4518): JXcore engine is started
,E/jxcore  ( 4518): Error!: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js
E/jxcore  ( 4518): Stack: [{"_fileName":"node.js","_functionName":"$h.require","_lineNumber":"1472","_columnNumber":"1","_msg":"    at $h.require@node.js:1472:1"},{"_fileName":"main.js.js","_functionName":"internal_methods.loadMainFile","_lineNumber":"260","_columnNumber":"5","_msg":"    at internal_methods.loadMainFile@main.js.js:260:5"},{"_fileName":"main.js.js","_functionName":"JXMobile.executeJSON","_lineNumber":"279","_columnNumber":"7","_msg":"    at JXMobile.executeJSON@main.js.js:279:7"},{"_fileName":"JX_Evaluate","_functionName":"","_lineNumber":"1","_columnNumber":"1","_msg":"    at @JX_Evaluate:1:1"},{"_fileName":"node.js","_functionName":"unknown","_lineNumber":"1472","_columnNumber":"1","_msg":""}]
,I/chromium( 4518): [INFO:CONSOLE(37)] "App.js file failed to load : "No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\nError: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\n    at $h.require@node.js:1472:1\n    at internal_methods.loadMainFile@main.js.js:260:5\n    at JXMobile.executeJSON@main.js.js:279:7\n    at @JX_Evaluate:1:1\n"", source: file:///android_asset/www/js/thali_main.js (37)
,D/LockPatternUtils( 1069): isPcwEnable = null
I/ActivityManager(  777): Killing 3631:com.sec.android.app.sns3/u0a36 (adj 15): empty #43
,W/PluginManager( 4518): THREAD WARNING: exec() call to CoreAndroid.exitApp blocked the main thread for 23ms. Plugin should use CordovaInterface.getThreadPool().
,I/SurfaceFlinger(  249): id=17 Removed NainActivit (7/11)
,I/SurfaceFlinger(  249): id=17 Removed NainActivit (-2/11)
,D/KeyguardUpdateMonitor( 1069): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1069): handleKeyguardVisibilityChanged(1)
,D/CustomFrequencyManagerService(  777): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 777  pkgName : ACTIVITY_RESUME_BOOSTER@5
,W/ActivityManager(  777): mDVFSHelper.acquire()
D/KeyguardUpdateMonitor( 1069): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1069): handleKeyguardVisibilityChanged(1)
,D/KeyguardUpdateMonitor( 1069): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1069): handleKeyguardVisibilityChanged(1)
,D/LockPatternUtils( 1069): isPcwEnable = null
,D/SurfaceWidgetView( 1250): destroyHardwareResources():1131381880
,D/KeyguardUpdateMonitor( 1069): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1069): handleKeyguardVisibilityChanged(1)
D/Launcher( 1250): onRestart, Launcher: 1119447024
D/Launcher( 1250): onStart, Launcher: 1119447024
,D/Launcher.HomeView( 1250): onStart
,D/SurfaceWidgetClient$ISurfaceWidgetStub( 1450): [237392/5] Surface widget visibility changed visibility = true on instance = 1
,D/SurfaceWidget.Renderer( 1450): [237392/5] SurfaceWidget drawing first frame
,D/KeyguardUpdateMonitor( 1069): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1069): handleKeyguardVisibilityChanged(1)
,I/SurfaceFlinger(  249): id=18 createSurf (1x1),2 flag=404, CatteryCove
,D/KeyguardUpdateMonitor( 1069): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1069): handleKeyguardVisibilityChanged(1)
,I/SurfaceFlinger(  249): id=19 createSurf (720x1280),1 flag=4, Mauncher
,D/KeyguardUpdateMonitor( 1069): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1069): handleKeyguardVisibilityChanged(1)
,D/Launcher.HomeView( 1250): onStop
,D/KeyguardUpdateMonitor( 1069): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1069): handleKeyguardVisibilityChanged(1)
,D/KeyguardUpdateMonitor( 1069): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1069): handleKeyguardVisibilityChanged(1)
,D/KeyguardUpdateMonitor( 1069): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1069): handleKeyguardVisibilityChanged(1)
,D/AmoledAdjustTimer(  777): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,D/CustomFrequencyManagerService(  777): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 777  pkgName : ACTIVITY_RESUME_BOOSTER@9
,D/CustomFrequencyManagerService(  777): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 777  tag : ACTIVITY_RESUME_BOOSTER@5
,D/CustomFrequencyManagerService(  777): FrequencyrequestList.getNextMaxCPUCoreRequest, index: 0
,D/KeyguardUpdateMonitor( 1069): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1069): handleKeyguardVisibilityChanged(1)
W/ActivityManager(  777): mDVFSHelper.release()
,D/CustomFrequencyManagerService(  777): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 777  tag : ACTIVITY_RESUME_BOOSTER@9
,I/GAV2    ( 4607): Thread[GAThread,5,main]: No campaign data found.
,D/BatteryService(  777): level:100, scale:100, status:5, health:2, present:true, voltage: 4366, temperature: 288, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:20, charge type:1, power sharing:false
,D/BatteryService(  777): stay LED for fully charged
,D/BatteryService(  777): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
D/UiModeManager(  777): mCoverManager.getCoverState() : true
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1069): checkOverflow(384), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  777): SIOP:: AP = 320, Delta = 10
,E/SMD     (  243): DCD ON
,I/HarmonyEASService(  777): Updating for all 1
,E/SMD     (  243): DCD ON
,E/Watchdog(  777): !@Sync 3
,E/SMD     (  243): DCD ON
,D/AmoledAdjustTimer(  777): prevTemp = 287, currTemp = 288, prevStep = 4, currStep = 4
,I/PowerManagerService(  777): [PWL] Off : 50s ago
,D/SSRMv2:SIOP(  777): SIOP:: AP = 300, Delta = -20
,E/SMD     (  243): DCD ON
,V/AlarmManager(  777): waitForAlarm result :4
,V/AlarmManager(  777): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,D/BatteryService(  777): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 288, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:21, charge type:1, power sharing:false
,D/BatteryService(  777): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  777): stay LED for fully charged
,D/UiModeManager(  777): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1069): checkOverflow(384), More:false, Req:false Child:2
,W/ContextImpl(  777): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/dalvikvm( 3456): GC_CONCURRENT freed 1799K, 41% free 11202K/18724K, paused 4ms+5ms, total 42ms
,D/Finsky  ( 3456): [349] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 3456): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/FactoryTest( 4039): Not factory mode
,D/FactoryTest( 4039): Not factory mode. isFactoryMode() returend false
,D/MTPRx   ( 4039): DRIVER_TIME_OUT 60s lapsed
,D/MTPRx   ( 4039): still no open session command from host, so toast
,W/ContextImpl( 4039): Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1398 android.content.ContextWrapper.startActivity:323 android.content.ContextWrapper.startActivity:323 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:767 android.os.Handler.dispatchMessage:102 
,W/ContextImpl( 4039): Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1410 android.app.ContextImpl.startActivity:1399 android.content.ContextWrapper.startActivity:323 android.content.ContextWrapper.startActivity:323 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:767 
,V/ApplicationPolicy(  777): isApplicationStateBlocked userId 0 pkgname com.android.settings
,D/CustomFrequencyManagerService(  777): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 777  pkgName : ACTIVITY_RESUME_BOOSTER@5
,W/ActivityManager(  777): mDVFSHelper.acquire()
,D/LockPatternUtils( 1069): isPcwEnable = null
,D/LockPatternUtils( 1069): isPcwEnable = null
,E/MTPRx   ( 4039): started activity for popup
,I/SQLiteSecureOpenHelper( 2015): getWritableDatabase(pwd)
,I/SQLiteSecureOpenHelper( 2015): getDatabaseLocked(b,b,pwd)...
,E/SettingsReceiverActivity( 4039): PREF_DONT_ASK_AGAIN : true
,D/LockPatternUtils( 1069): isPcwEnable = null
,D/SettingsReceiverActivity( 4039): dev.kiessupport is : TRUE
,I/WindowManager(  777): Screenshot max retries 4 of Token{436877c0 ActivityRecord{432461d8 u0 com.sec.android.app.popupuireceiver/.BatteryCover t2}} appWin=Window{43465350 u0 com.sec.android.app.popupuireceiver/com.sec.android.app.popupuireceiver.BatteryCover} drawState=4
,W/WindowManager(  777): Screenshot failure taking screenshot for (720x1280) to layer 21005
D/LockPatternUtils( 1069): isPcwEnable = null
,D/AmoledAdjustTimer(  777): prevTemp = 288, currTemp = 288, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,D/CustomFrequencyManagerService(  777): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 777  tag : ACTIVITY_RESUME_BOOSTER@5
W/ActivityManager(  777): mDVFSHelper.release()
,D/CustomFrequencyManagerService(  777): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 777  pkgName : ACTIVITY_RESUME_BOOSTER@9
,D/SSRMv2:SIOP(  777): SIOP:: AP = 300, Delta = 0
,D/CustomFrequencyManagerService(  777): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 777  tag : ACTIVITY_RESUME_BOOSTER@9
,D/BatteryService(  777): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:20, charge type:1, power sharing:false
,D/BatteryService(  777): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  777): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
D/UiModeManager(  777): mCoverManager.getCoverState() : true
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1069): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  243): DCD ON
,V/AlarmManager(  777): waitForAlarm result :8
,V/AlarmManager(  777): ClockReceiver onReceive() ACTION_TIME_TICK
,V/AlarmManager(  777): ___SyncScheduler (v3) ACTIVATED___
,V/AlarmManager(  777): <AppSync3 Whitelist>
,V/AlarmManager(  777): (AppSync) ### 0 added ###
D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.TIME_TICK
D/KeyguardUpdateMonitor( 1069): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1069): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/AmoledAdjustTimer(  777): prevTemp = 288, currTemp = 286, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP(  777): SIOP:: AP = 300, Delta = 0
,E/SMD     (  243): DCD ON
,W/ContextImpl(  777): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  243): DCD ON
,I/PowerManagerService(  777): [PWL] Off : 75s ago
,E/Watchdog(  777): !@Sync 4
,V/AlarmManager(  777): waitForAlarm result :4
,V/AlarmManager(  777): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,D/NtpTrustedTime(  777): forceRefresh() from cache miss
,D/NtpTrustedTime(  777): forceRefresh Fail.
,E/SMD     (  243): DCD ON
,D/BatteryService(  777): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 284, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:25, charge type:1, power sharing:false
,D/BatteryService(  777): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  777): stay LED for fully charged
,D/UiModeManager(  777): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1069): checkOverflow(384), More:false, Req:false Child:2
,D/AmoledAdjustTimer(  777): prevTemp = 286, currTemp = 284, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  777): SIOP:: AP = 300, Delta = 0
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/BatteryService(  777): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 283, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:21, charge type:1, power sharing:false
,D/BatteryService(  777): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  777): mCoverManager.getCoverState() : true
,D/BatteryService(  777): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1069): checkOverflow(384), More:false, Req:false Child:2
,D/AmoledAdjustTimer(  777): prevTemp = 284, currTemp = 283, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  777): SIOP:: AP = 300, Delta = 0
,W/ContextImpl(  777): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/BatteryService(  777): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:23, charge type:1, power sharing:false
,D/BatteryService(  777): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  777): mCoverManager.getCoverState() : true
,D/BatteryService(  777): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 1069): checkOverflow(384), More:false, Req:false Child:2
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  243): DCD ON
,D/AmoledAdjustTimer(  777): prevTemp = 283, currTemp = 282, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP(  777): SIOP:: AP = 300, Delta = 0
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,I/PowerManagerService(  777): [PWL] Off : 105s ago
,E/Watchdog(  777): !@Sync 5
,E/SMD     (  243): DCD ON
,D/BatteryService(  777): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:15, charge type:1, power sharing:false
,D/BatteryService(  777): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  777): stay LED for fully charged
,D/UiModeManager(  777): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1069): checkOverflow(384), More:false, Req:false Child:2
,D/AmoledAdjustTimer(  777): prevTemp = 282, currTemp = 281, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  777): SIOP:: AP = 300, Delta = 0
,W/ContextImpl(  777): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/BatteryService(  777): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:14, charge type:1, power sharing:false
,D/BatteryService(  777): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  777): stay LED for fully charged
,D/UiModeManager(  777): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1069): checkOverflow(384), More:false, Req:false Child:2
,D/AmoledAdjustTimer(  777): prevTemp = 281, currTemp = 281, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  777): SIOP:: AP = 300, Delta = 0
,E/SMD     (  243): DCD ON
,V/AlarmManager(  777): waitForAlarm result :8
,V/AlarmManager(  777): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1069): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1069): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/AmoledAdjustTimer(  777): prevTemp = 281, currTemp = 281, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP(  777): SIOP:: AP = 300, Delta = 0
,E/SMD     (  243): DCD ON
,W/ContextImpl(  777): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  243): DCD ON
,E/Watchdog(  777): !@Sync 6
,V/AlarmManager(  777): waitForAlarm result :4
,V/AlarmManager(  777): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,D/NtpTrustedTime(  777): forceRefresh() from cache miss
,D/NtpTrustedTime(  777): forceRefresh Fail.
,E/SMD     (  243): DCD ON
,D/BatteryService(  777): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 280, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:16, charge type:1, power sharing:false
,D/BatteryService(  777): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  777): mCoverManager.getCoverState() : true
,D/BatteryService(  777): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 1069): checkOverflow(384), More:false, Req:false Child:2
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/ClearcutLoggerApiImpl( 1296): disconnect managed GoogleApiClient
,I/VacuumService( 1220): Vacuum at: now=1453807694489 tag=VacuumService
,D/AmoledAdjustTimer(  777): prevTemp = 281, currTemp = 280, prevStep = 4, currStep = 4
,I/PowerManagerService(  777): [PWL] Off : 140s ago
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  777): SIOP:: AP = 300, Delta = 0
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/BatteryService(  777): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:20, charge type:1, power sharing:false
,D/BatteryService(  777): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  777): mCoverManager.getCoverState() : true
,D/BatteryService(  777): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 1069): checkOverflow(384), More:false, Req:false Child:2
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer(  777): prevTemp = 280, currTemp = 279, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  777): SIOP:: AP = 300, Delta = 0
,W/ContextImpl(  777): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/BatteryService(  777): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:22, charge type:1, power sharing:false
,D/BatteryService(  777): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  777): mCoverManager.getCoverState() : true
,D/BatteryService(  777): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1069): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  243): DCD ON
,D/AmoledAdjustTimer(  777): prevTemp = 279, currTemp = 279, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP(  777): SIOP:: AP = 300, Delta = 0
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,E/Watchdog(  777): !@Sync 7
,E/SMD     (  243): DCD ON
,D/BatteryService(  777): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:19, charge type:1, power sharing:false
,D/BatteryService(  777): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  777): mCoverManager.getCoverState() : true
,D/BatteryService(  777): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1069): checkOverflow(384), More:false, Req:false Child:2
,D/AmoledAdjustTimer(  777): prevTemp = 279, currTemp = 278, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  777): SIOP:: AP = 300, Delta = 0
,W/ContextImpl(  777): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/BatteryService(  777): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:18, charge type:1, power sharing:false
,D/BatteryService(  777): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  777): mCoverManager.getCoverState() : true
,D/BatteryService(  777): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1069): checkOverflow(384), More:false, Req:false Child:2
,D/AmoledAdjustTimer(  777): prevTemp = 278, currTemp = 278, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,I/PowerManagerService(  777): [PWL] Off : 180s ago
,D/SSRMv2:SIOP(  777): SIOP:: AP = 300, Delta = 0
,E/SMD     (  243): DCD ON
,V/AlarmManager(  777): waitForAlarm result :8
,V/AlarmManager(  777): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1069): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1069): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  243): DCD ON
,D/BatteryService(  777): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:18, charge type:1, power sharing:false
,D/BatteryService(  777): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  777): mCoverManager.getCoverState() : true
,D/BatteryService(  777): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1069): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  243): DCD ON
,D/AmoledAdjustTimer(  777): prevTemp = 278, currTemp = 277, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP(  777): SIOP:: AP = 300, Delta = 0
,E/SMD     (  243): DCD ON
,W/ContextImpl(  777): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  243): DCD ON
,E/Watchdog(  777): !@Sync 8
,E/SMD     (  243): DCD ON
,D/BatteryService(  777): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:13, charge type:1, power sharing:false
,D/BatteryService(  777): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  777): stay LED for fully charged
,D/UiModeManager(  777): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1069): checkOverflow(384), More:false, Req:false Child:2
,D/AmoledAdjustTimer(  777): prevTemp = 277, currTemp = 277, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  777): SIOP:: AP = 300, Delta = 0
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/BatteryService(  777): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:16, charge type:1, power sharing:false
,D/BatteryService(  777): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  777): mCoverManager.getCoverState() : true
,D/BatteryService(  777): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 1069): checkOverflow(384), More:false, Req:false Child:2
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer(  777): prevTemp = 277, currTemp = 277, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  777): SIOP:: AP = 300, Delta = 0
,W/ContextImpl(  777): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/BatteryService(  777): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:12, charge type:1, power sharing:false
,D/BatteryService(  777): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  777): stay LED for fully charged
,D/UiModeManager(  777): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1069): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  243): DCD ON
,D/AmoledAdjustTimer(  777): prevTemp = 277, currTemp = 276, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP(  777): SIOP:: AP = 300, Delta = 0
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,I/PowerManagerService(  777): [PWL] Off : 225s ago
,E/Watchdog(  777): !@Sync 9
,E/SMD     (  243): DCD ON
,D/BatteryService(  777): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:14, charge type:1, power sharing:false
,D/BatteryService(  777): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  777): stay LED for fully charged
,D/UiModeManager(  777): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 1069): checkOverflow(384), More:false, Req:false Child:2
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer(  777): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  777): SIOP:: AP = 300, Delta = 0
,W/ContextImpl(  777): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/BatteryService(  777): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:20, charge type:1, power sharing:false
,D/BatteryService(  777): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  777): mCoverManager.getCoverState() : true
,D/BatteryService(  777): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1069): checkOverflow(384), More:false, Req:false Child:2
,D/AmoledAdjustTimer(  777): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  777): SIOP:: AP = 300, Delta = 0
,E/SMD     (  243): DCD ON
,V/AlarmManager(  777): waitForAlarm result :8
,V/AlarmManager(  777): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1069): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1069): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  243): DCD ON
,D/BatteryService(  777): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:17, charge type:1, power sharing:false
,D/BatteryService(  777): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  777): stay LED for fully charged
,D/UiModeManager(  777): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1069): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  243): DCD ON
,D/AmoledAdjustTimer(  777): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,D/TimaService(  777): TIMA: TimaService scheduler is intialized. 
D/TimaService(  777): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService(  777): TimaServiceHandler.handleMessage what =1
,I/TLC_TIMA_PKM_initialize(  777): initializing...
,I/TLC_TIMA_PKM_initialize(  777): root = /firmware/image, root_strlen = 15
,I/TLC_TIMA_PKM_initialize(  777): process = tima_pkm, process_strlen = 8
,I/TZ: qc_tlc_communication(  777): root = /firmware/image, root_len = 15
,I/TZ: qc_tlc_communication(  777): process = tima_pkm, process_strlen = 8
,I/TZ: qc_tlc_communication(  777): aligned max_sendmsg_size = 262208 = 0x40040
,I/TZ: qc_tlc_communication(  777): aligned max_recvmsg_size = 262208 = 0x40040,
,I/TZ: qc_tlc_communication(  777): max_message_size = 524416 = 0x80080
,D/QSEECOMAPI: (  777): QSEECom_get_handle sb_length = 0x80080
,D/QSEECOMAPI: (  777): App is not loaded in QSEE
,D/QSEECOMAPI: (  777): Loaded image: APP id = 2
,I/TZ: qc_tlc_communication(  777): TIMA: path = /firmware/image, fname = tima_pkm, tzapp is loaded
,I/TLC_TIMA_PKM_initialize(  777): Trustlet response is completed
,D/SSRMv2:SIOP(  777): SIOP:: AP = 300, Delta = 0
,E/SMD     (  243): DCD ON
,W/ContextImpl(  777): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  243): DCD ON
,I/TLC_TIMA_PKM_measure_kernel(  777): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel(  777): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService(  777): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService(  777): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/Watchdog(  777): !@Sync 10
,E/SMD     (  243): DCD ON
,D/BatteryService(  777): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:17, charge type:1, power sharing:false
,D/BatteryService(  777): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  777): stay LED for fully charged
,D/UiModeManager(  777): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1069): checkOverflow(384), More:false, Req:false Child:2
,D/AmoledAdjustTimer(  777): prevTemp = 276, currTemp = 275, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  777): SIOP:: AP = 300, Delta = 0
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/AmoledAdjustTimer(  777): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  777): SIOP:: AP = 300, Delta = 0
,W/ContextImpl(  777): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  243): DCD ON
,I/PowerManagerService(  777): [PWL] Off : 275s ago
,E/SMD     (  243): DCD ON
,V/AlarmManager(  777): waitForAlarm result :4
,V/AlarmManager(  777): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,I/SELinux ( 4861): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 4861):  
,I/SELinux ( 4861): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 4861):  
I/SELinux ( 4861):  
,I/SELinux ( 4861): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 4861): [DEBUG] seapp_context_lookup: seinfoCategory = default
,E/dalvikvm( 4861): >>>>> Normal User
,E/dalvikvm( 4861): >>>>> com.blurb.checkout [ userId:0 | appId:10075 ]
,E/SELinux ( 4861): [DEBUG] seapp_context_lookup: seinfoCategory = default
,D/TimaKeyStoreProvider( 4861): in addTimaSignatureService
,D/TimaKeyStoreProvider( 4861): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 4861): Added TimaKesytore provider
,W/ActivityManager(  777): Permission Denial: getCurrentUser() from pid=4861, uid=10075 requires android.permission.INTERACT_ACROSS_USERS
,E/SMD     (  243): DCD ON
,I/ActivityManager(  777): Killing 3683:com.sec.spp.push:RemoteDlcProcess/u0a38 (adj 15): empty #43
,D/AmoledAdjustTimer(  777): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP(  777): SIOP:: AP = 300, Delta = 0
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,E/Watchdog(  777): !@Sync 11
,V/GLSActivity( 1296): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1296): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/SocketClient(  240): write error (Broken pipe)
,E/SMD     (  243): DCD ON
,D/BatteryService(  777): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:15, charge type:1, power sharing:false
,D/BatteryService(  777): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  777): stay LED for fully charged
,D/UiModeManager(  777): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1069): checkOverflow(384), More:false, Req:false Child:2
,D/AmoledAdjustTimer(  777): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  777): SIOP:: AP = 300, Delta = 0
,W/ContextImpl(  777): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/BatteryService(  777): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:16, charge type:1, power sharing:false
,D/BatteryService(  777): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  777): stay LED for fully charged
,D/UiModeManager(  777): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1069): checkOverflow(384), More:false, Req:false Child:2
,D/AmoledAdjustTimer(  777): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  777): SIOP:: AP = 300, Delta = 0
,E/SMD     (  243): DCD ON
,V/AlarmManager(  777): waitForAlarm result :8
,V/AlarmManager(  777): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1069): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1069): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  243): DCD ON
,D/BatteryService(  777): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:16, charge type:1, power sharing:false
,D/BatteryService(  777): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  777): mCoverManager.getCoverState() : true
,D/BatteryService(  777): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1069): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  243): DCD ON
,D/AmoledAdjustTimer(  777): prevTemp = 275, currTemp = 274, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  777): SIOP:: AP = 300, Delta = 0
,W/ContextImpl(  777): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  243): DCD ON
,E/Watchdog(  777): !@Sync 12
,E/SMD     (  243): DCD ON
,D/BatteryService(  777): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:10, charge type:1, power sharing:false
,D/BatteryService(  777): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  777): stay LED for fully charged
,D/UiModeManager(  777): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1069): checkOverflow(384), More:false, Req:false Child:2
,D/AmoledAdjustTimer(  777): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  777): SIOP:: AP = 300, Delta = 0
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/BatteryService(  777): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:12, charge type:1, power sharing:false
,D/BatteryService(  777): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  777): mCoverManager.getCoverState() : true
,D/BatteryService(  777): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1069): checkOverflow(384), More:false, Req:false Child:2
,D/dalvikvm(  777): GC_CONCURRENT freed 3403K, 59% free 23440K/56508K, paused 34ms+52ms, total 543ms
,D/AmoledAdjustTimer(  777): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,I/PowerManagerService(  777): [PWL] Off : 330s ago
,D/SSRMv2:SIOP(  777): SIOP:: AP = 300, Delta = 0
,W/ContextImpl(  777): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/AmoledAdjustTimer(  777): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  777): SIOP:: AP = 300, Delta = 0
,E/SMD     (  243): DCD ON
,E/Watchdog(  777): !@Sync 13
,E/SMD     (  243): DCD ON
,D/BatteryService(  777): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:13, charge type:1, power sharing:false
,D/BatteryService(  777): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  777): mCoverManager.getCoverState() : true
,D/BatteryService(  777): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1069): checkOverflow(384), More:false, Req:false Child:2
,D/AmoledAdjustTimer(  777): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  777): SIOP:: AP = 300, Delta = 0
,W/ContextImpl(  777): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/BatteryService(  777): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:13, charge type:1, power sharing:false
,D/BatteryService(  777): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  777): mCoverManager.getCoverState() : true
,D/BatteryService(  777): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1069): checkOverflow(384), More:false, Req:false Child:2
,D/AmoledAdjustTimer(  777): prevTemp = 274, currTemp = 273, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  777): SIOP:: AP = 300, Delta = 0
,E/SMD     (  243): DCD ON
,V/AlarmManager(  777): waitForAlarm result :8
,V/AlarmManager(  777): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1069): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1069): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  243): DCD ON
,D/BatteryService(  777): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:18, charge type:1, power sharing:false
,D/BatteryService(  777): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  777): mCoverManager.getCoverState() : true
,D/BatteryService(  777): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1069): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  243): DCD ON
,D/AmoledAdjustTimer(  777): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,W/ContextImpl(  777): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/SSRMv2:SIOP(  777): SIOP:: AP = 300, Delta = 0
,E/SMD     (  243): DCD ON
,E/Watchdog(  777): !@Sync 14
,E/SMD     (  243): DCD ON
,D/BatteryService(  777): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:14, charge type:1, power sharing:false
,D/BatteryService(  777): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  777): stay LED for fully charged
,D/UiModeManager(  777): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1069): checkOverflow(384), More:false, Req:false Child:2
,D/AmoledAdjustTimer(  777): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  777): SIOP:: AP = 300, Delta = 0
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/BatteryService(  777): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:12, charge type:1, power sharing:false
,D/BatteryService(  777): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  777): stay LED for fully charged
,D/UiModeManager(  777): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1069): checkOverflow(384), More:false, Req:false Child:2
,D/AmoledAdjustTimer(  777): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,I/PowerManagerService(  777): [PWL] Off : 390s ago
,W/ContextImpl(  777): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/SSRMv2:SIOP(  777): SIOP:: AP = 300, Delta = 0
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/BatteryService(  777): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:11, charge type:1, power sharing:false
,D/BatteryService(  777): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  777): mCoverManager.getCoverState() : true
,E/SMD     (  243): DCD ON
,D/BatteryService(  777): stay LED for fully charged
D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1069): checkOverflow(384), More:false, Req:false Child:2
,D/AmoledAdjustTimer(  777): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  777): SIOP:: AP = 300, Delta = 0
,E/SMD     (  243): DCD ON
,E/Watchdog(  777): !@Sync 15
,E/SMD     (  243): DCD ON
,D/BatteryService(  777): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:14, charge type:1, power sharing:false
,D/BatteryService(  777): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  777): mCoverManager.getCoverState() : true
,D/BatteryService(  777): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1069): checkOverflow(384), More:false, Req:false Child:2
,D/AmoledAdjustTimer(  777): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,W/ContextImpl(  777): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/SSRMv2:SIOP(  777): SIOP:: AP = 300, Delta = 0
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/BatteryService(  777): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:14, charge type:1, power sharing:false
,D/BatteryService(  777): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  777): mCoverManager.getCoverState() : true
,D/BatteryService(  777): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1069): checkOverflow(384), More:false, Req:false Child:2
,D/AmoledAdjustTimer(  777): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  777): SIOP:: AP = 300, Delta = 0
,E/SMD     (  243): DCD ON
,V/AlarmManager(  777): waitForAlarm result :8
,V/AlarmManager(  777): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1069): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1069): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/BatteryService(  777): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:10, charge type:1, power sharing:false
,D/BatteryService(  777): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  777): stay LED for fully charged
,D/UiModeManager(  777): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1069): checkOverflow(384), More:false, Req:false Child:2
,D/AmoledAdjustTimer(  777): prevTemp = 273, currTemp = 272, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,W/ContextImpl(  777): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/SSRMv2:SIOP(  777): SIOP:: AP = 300, Delta = 0
,E/SMD     (  243): DCD ON
,E/Watchdog(  777): !@Sync 16
,E/SMD     (  243): DCD ON
,D/BatteryService(  777): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:12, charge type:1, power sharing:false
,D/BatteryService(  777): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  777): mCoverManager.getCoverState() : true
,D/BatteryService(  777): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer(  777): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,D/STATUSBAR-IconMerger( 1069): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  777): SIOP:: AP = 300, Delta = 0
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/AmoledAdjustTimer(  777): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,D/BatteryService(  777): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:18, charge type:1, power sharing:false
,D/BatteryService(  777): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  777): mCoverManager.getCoverState() : true
,D/BatteryService(  777): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1069): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  243): DCD ON
,W/ContextImpl(  777): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/SSRMv2:SIOP(  777): SIOP:: AP = 300, Delta = 0
,E/SMD     (  243): DCD ON
,I/PowerManagerService(  777): [PWL] Off : 455s ago
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/AmoledAdjustTimer(  777): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,D/BatteryService(  777): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:10, charge type:1, power sharing:false
,D/BatteryService(  777): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  777): mCoverManager.getCoverState() : true
,D/BatteryService(  777): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 1069): checkOverflow(384), More:false, Req:false Child:2
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  777): SIOP:: AP = 300, Delta = 0
,E/SMD     (  243): DCD ON
,E/Watchdog(  777): !@Sync 17
,E/SMD     (  243): DCD ON
,D/AmoledAdjustTimer(  777): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,D/BatteryService(  777): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:12, charge type:1, power sharing:false
,D/BatteryService(  777): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  777): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
D/UiModeManager(  777): mCoverManager.getCoverState() : true
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1069): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  243): DCD ON
,W/ContextImpl(  777): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/SSRMv2:SIOP(  777): SIOP:: AP = 300, Delta = 0
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/AmoledAdjustTimer(  777): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,D/BatteryService(  777): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:10, charge type:1, power sharing:false
,D/BatteryService(  777): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  777): mCoverManager.getCoverState() : true
,D/BatteryService(  777): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1069): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  777): SIOP:: AP = 300, Delta = 0
,E/SMD     (  243): DCD ON
,V/AlarmManager(  777): waitForAlarm result :8
,V/AlarmManager(  777): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1069): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1069): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/AmoledAdjustTimer(  777): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,D/BatteryService(  777): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:11, charge type:1, power sharing:false
,D/BatteryService(  777): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  777): mCoverManager.getCoverState() : true
,D/BatteryService(  777): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1069): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  243): DCD ON
,W/ContextImpl(  777): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/SSRMv2:SIOP(  777): SIOP:: AP = 300, Delta = 0
,E/SMD     (  243): DCD ON
,E/Watchdog(  777): !@Sync 18
,E/SMD     (  243): DCD ON
,D/AmoledAdjustTimer(  777): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,D/BatteryService(  777): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:14, charge type:1, power sharing:false
,D/BatteryService(  777): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  777): mCoverManager.getCoverState() : true
,D/BatteryService(  777): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1069): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  777): SIOP:: AP = 300, Delta = 0
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/AmoledAdjustTimer(  777): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,W/ContextImpl(  777): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/SSRMv2:SIOP(  777): SIOP:: AP = 300, Delta = 0
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/AmoledAdjustTimer(  777): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,D/BatteryService(  777): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:8, charge type:1, power sharing:false
,D/BatteryService(  777): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  777): stay LED for fully charged
,D/UiModeManager(  777): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1069): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  777): SIOP:: AP = 300, Delta = 0
,E/SMD     (  243): DCD ON
,I/PowerManagerService(  777): [PWL] Off : 525s ago
,E/Watchdog(  777): !@Sync 19
,E/SMD     (  243): DCD ON
,D/AmoledAdjustTimer(  777): prevTemp = 272, currTemp = 271, prevStep = 4, currStep = 4
,D/BatteryService(  777): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:14, charge type:1, power sharing:false
,D/BatteryService(  777): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  777): mCoverManager.getCoverState() : true
,D/BatteryService(  777): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1069): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  243): DCD ON
,W/ContextImpl(  777): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/SSRMv2:SIOP(  777): SIOP:: AP = 300, Delta = 0
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/AmoledAdjustTimer(  777): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,D/BatteryService(  777): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:8, charge type:1, power sharing:false
,D/BatteryService(  777): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  777): stay LED for fully charged
,D/UiModeManager(  777): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1069): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  777): SIOP:: AP = 300, Delta = 0
,V/AlarmManager(  777): waitForAlarm result :8
,V/AlarmManager(  777): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1069): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1069): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/AmoledAdjustTimer(  777): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,D/BatteryService(  777): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:13, charge type:1, power sharing:false
,D/BatteryService(  777): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  777): mCoverManager.getCoverState() : true
,D/BatteryService(  777): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1069): checkOverflow(384), More:false, Req:false Child:2
,D/TimaService(  777): TIMA: TimaService scheduler is intialized. 
D/TimaService(  777): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService(  777): TimaServiceHandler.handleMessage what =1
,E/SMD     (  243): DCD ON
,W/ContextImpl(  777): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/SSRMv2:SIOP(  777): SIOP:: AP = 300, Delta = 0
,E/SMD     (  243): DCD ON
,I/TLC_TIMA_PKM_measure_kernel(  777): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel(  777): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService(  777): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService(  777): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/Watchdog(  777): !@Sync 20
,E/SMD     (  243): DCD ON
,D/AmoledAdjustTimer(  777): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,D/BatteryService(  777): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:12, charge type:1, power sharing:false
,D/BatteryService(  777): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  777): stay LED for fully charged
,D/UiModeManager(  777): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1069): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  777): SIOP:: AP = 300, Delta = 0
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/AmoledAdjustTimer(  777): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,D/BatteryService(  777): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:8, charge type:1, power sharing:false
,D/BatteryService(  777): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  777): stay LED for fully charged
,D/UiModeManager(  777): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,E/SMD     (  243): DCD ON
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1069): checkOverflow(384), More:false, Req:false Child:2
,W/ContextImpl(  777): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  777): SIOP:: AP = 300, Delta = 0
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/AmoledAdjustTimer(  777): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,D/BatteryService(  777): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:11, charge type:1, power sharing:false
,D/BatteryService(  777): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  777): mCoverManager.getCoverState() : true
,D/BatteryService(  777): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1069): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  777): SIOP:: AP = 300, Delta = 0
,E/SMD     (  243): DCD ON
,E/Watchdog(  777): !@Sync 21
,V/GLSActivity( 1296): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1296): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/SMD     (  243): DCD ON
,W/SocketClient(  240): write error (Broken pipe)
,D/AmoledAdjustTimer(  777): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,D/BatteryService(  777): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:12, charge type:1, power sharing:false
,D/BatteryService(  777): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  777): mCoverManager.getCoverState() : true
,D/BatteryService(  777): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1069): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  777): SIOP:: AP = 300, Delta = 0
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/AmoledAdjustTimer(  777): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,V/AlarmManager(  777): waitForAlarm result :4
,D/LightsService(  777): [api] onReceive : SvcLEDReceiver re-enables LightSenor and sends MSG_FORCEDSVCLEDTASK
I/SensorManagerA(  777): getReportingMode :: sensor.mType = 5
D/Sensors (  777): LightSensor setDelay = 200000000
D/Sensors (  777): LightSensor setSensorDelay = 200000000
D/Sensors (  777): Light sensor flush: not enabled 0
D/Sensors (  777): LightSensor enable = 1
D/Sensors (  777): LightSensor enableSensor = 1
D/SensorManager(  777): registerListener :: 16, CM36686 Light Sensor, 200000, 0,  
,V/AlarmManager(  777): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,I/PowerManagerService(  777): [PWL] Off : 600s ago
,I/PowerManagerService(  777): [PWL]   PowerManagerService.WakeLocks: ref count=1
,I/PowerManagerService(  777): [PWL]     mWakeLockSummary : 0x1
,I/PowerManagerService(  777): [PWL]       PARTIAL_WAKE_LOCK              'Event Log Handoff' (uid=10011, pid=1787, ws=WorkSource{10011 com.google.android.gms}) (elapsedTime=31)
,D/BatteryService(  777): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:4, charge type:1, power sharing:false
,D/BatteryService(  777): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  777): stay LED for fully charged
,D/UiModeManager(  777): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1069): checkOverflow(384), More:false, Req:false Child:2
,D/Sensors (  777): LightSensor enable = 0
,D/Sensors (  777): LightSensor enableSensor = 0
,D/SensorManager(  777): unregisterListener ::   
D/LightsService(  777): [SvcLED]  onSensorChanged::light value = 25
D/LightsService(  777): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,I/EventLogService( 1787): Aggregate from 1453806220438 (log), 1453806220438 (data)
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  777): SIOP:: AP = 300, Delta = 0
,V/AlarmManager(  777): waitForAlarm result :8
,V/AlarmManager(  777): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1069): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1069): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/AmoledAdjustTimer(  777): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,D/BatteryService(  777): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:11, charge type:1, power sharing:false
,D/BatteryService(  777): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  777): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/UiModeManager(  777): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1069): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  777): SIOP:: AP = 300, Delta = 0
,E/SMD     (  243): DCD ON
,E/Watchdog(  777): !@Sync 22
,E/SMD     (  243): DCD ON
,D/AmoledAdjustTimer(  777): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,D/BatteryService(  777): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:9, charge type:1, power sharing:false
,D/BatteryService(  777): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  777): stay LED for fully charged
,D/UiModeManager(  777): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1069): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  777): SIOP:: AP = 300, Delta = 0
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/AmoledAdjustTimer(  777): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,D/BatteryService(  777): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:13, charge type:1, power sharing:false
,D/BatteryService(  777): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  777): mCoverManager.getCoverState() : true
,D/BatteryService(  777): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1069): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  777): SIOP:: AP = 300, Delta = 0
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/AmoledAdjustTimer(  777): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,D/BatteryService(  777): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:5, charge type:1, power sharing:false
,D/BatteryService(  777): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  777): mCoverManager.getCoverState() : true
,D/BatteryService(  777): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1069): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  777): SIOP:: AP = 300, Delta = 0
,E/SMD     (  243): DCD ON
,E/Watchdog(  777): !@Sync 23
,E/SMD     (  243): DCD ON
,D/AmoledAdjustTimer(  777): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,D/BatteryService(  777): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:8, charge type:1, power sharing:false
,D/BatteryService(  777): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  777): stay LED for fully charged
,D/UiModeManager(  777): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1069): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  777): SIOP:: AP = 300, Delta = 0
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/AmoledAdjustTimer(  777): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,D/BatteryService(  777): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:8, charge type:1, power sharing:false
,D/BatteryService(  777): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  777): stay LED for fully charged
,D/UiModeManager(  777): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1069): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  777): SIOP:: AP = 300, Delta = 0
,V/AlarmManager(  777): waitForAlarm result :8
,V/AlarmManager(  777): ClockReceiver onReceive() ACTION_TIME_TICK
,V/AlarmManager(  777): ___SyncScheduler (v3) ACTIVATED___
,V/AlarmManager(  777): <AppSync3 Whitelist>
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.TIME_TICK
,V/AlarmManager(  777): (AppSync) ### 0 added ###
D/KeyguardUpdateMonitor( 1069): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1069): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/AmoledAdjustTimer(  777): prevTemp = 271, currTemp = 270, prevStep = 4, currStep = 4
,D/BatteryService(  777): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:9, charge type:1, power sharing:false
,D/BatteryService(  777): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  777): stay LED for fully charged
,D/UiModeManager(  777): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1069): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  777): SIOP:: AP = 300, Delta = 0
,E/SMD     (  243): DCD ON
,E/Watchdog(  777): !@Sync 24
,E/SMD     (  243): DCD ON
,D/AmoledAdjustTimer(  777): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,I/PowerManagerService(  777): [PWL] Off : 680s ago
,D/BatteryService(  777): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:8, charge type:1, power sharing:false
,D/BatteryService(  777): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  777): mCoverManager.getCoverState() : true
,D/BatteryService(  777): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1069): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  777): SIOP:: AP = 300, Delta = 0
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/AmoledAdjustTimer(  777): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,D/BatteryService(  777): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:11, charge type:1, power sharing:false
,D/BatteryService(  777): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  777): stay LED for fully charged
,D/UiModeManager(  777): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1069): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  777): SIOP:: AP = 300, Delta = 0
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/AmoledAdjustTimer(  777): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,D/BatteryService(  777): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService(  777): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  777): mCoverManager.getCoverState() : true
,D/BatteryService(  777): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1069): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  777): SIOP:: AP = 300, Delta = 0
,E/SMD     (  243): DCD ON
,E/Watchdog(  777): !@Sync 25
,E/SMD     (  243): DCD ON
,D/AmoledAdjustTimer(  777): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,D/BatteryService(  777): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:3, charge type:1, power sharing:false
,D/BatteryService(  777): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  777): stay LED for fully charged
,D/UiModeManager(  777): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1069): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  777): SIOP:: AP = 300, Delta = 0
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/AmoledAdjustTimer(  777): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,D/BatteryService(  777): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:9, charge type:1, power sharing:false
,D/BatteryService(  777): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  777): stay LED for fully charged
,D/UiModeManager(  777): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1069): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  243): DCD ON
,V/AlarmManager(  777): waitForAlarm result :8
,V/AlarmManager(  777): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1069): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1069): checkOverflow(384), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  777): SIOP:: AP = 300, Delta = 0
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/AmoledAdjustTimer(  777): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,D/BatteryService(  777): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:6, charge type:1, power sharing:false
,D/BatteryService(  777): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  777): stay LED for fully charged
,D/UiModeManager(  777): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1069): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  777): SIOP:: AP = 300, Delta = 0
,E/SMD     (  243): DCD ON
,E/Watchdog(  777): !@Sync 26
,E/SMD     (  243): DCD ON
,D/AmoledAdjustTimer(  777): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  777): SIOP:: AP = 300, Delta = 0
,E/SMD     (  243): DCD ON
,D/AmoledAdjustTimer(  777): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,D/BatteryService(  777): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:6, charge type:1, power sharing:false
,D/BatteryService(  777): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  777): stay LED for fully charged
,D/UiModeManager(  777): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1069): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  777): SIOP:: AP = 300, Delta = 0
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/AmoledAdjustTimer(  777): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,D/BatteryService(  777): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:4, charge type:1, power sharing:false
,D/BatteryService(  777): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  777): stay LED for fully charged
,D/UiModeManager(  777): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1069): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  777): SIOP:: AP = 300, Delta = 0
,E/SMD     (  243): DCD ON
,I/PowerManagerService(  777): [PWL] Off : 765s ago
,E/Watchdog(  777): !@Sync 27
,E/SMD     (  243): DCD ON
,D/AmoledAdjustTimer(  777): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,D/dalvikvm(  777): GC_CONCURRENT freed 3475K, 59% free 23352K/56284K, paused 28ms+61ms, total 537ms
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  777): SIOP:: AP = 300, Delta = 0
,E/SMD     (  243): DCD ON
,D/AmoledAdjustTimer(  777): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,V/AlarmManager(  777): waitForAlarm result :8
,V/AlarmManager(  777): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1069): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1069): checkOverflow(384), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  777): SIOP:: AP = 300, Delta = 0
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/AmoledAdjustTimer(  777): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,D/BatteryService(  777): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:10, charge type:1, power sharing:false
,D/BatteryService(  777): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  777): stay LED for fully charged
,D/UiModeManager(  777): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1069): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  777): SIOP:: AP = 300, Delta = 0
,E/SMD     (  243): DCD ON
,E/Watchdog(  777): !@Sync 28
,E/SMD     (  243): DCD ON
,D/AmoledAdjustTimer(  777): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  777): SIOP:: AP = 300, Delta = 0
,E/SMD     (  243): DCD ON
,D/AmoledAdjustTimer(  777): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,D/BatteryService(  777): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:4, charge type:1, power sharing:false
,D/BatteryService(  777): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  777): stay LED for fully charged
,D/UiModeManager(  777): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1069): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  777): SIOP:: AP = 300, Delta = 0
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/AmoledAdjustTimer(  777): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,D/BatteryService(  777): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:10, charge type:1, power sharing:false
,D/BatteryService(  777): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  777): mCoverManager.getCoverState() : true
,D/BatteryService(  777): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1069): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  777): SIOP:: AP = 300, Delta = 0
,E/SMD     (  243): DCD ON
,E/Watchdog(  777): !@Sync 29
,E/SMD     (  243): DCD ON
,D/AmoledAdjustTimer(  777): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,D/BatteryService(  777): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:6, charge type:1, power sharing:false
,D/BatteryService(  777): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  777): mCoverManager.getCoverState() : true
,D/BatteryService(  777): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1069): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  777): SIOP:: AP = 300, Delta = 0
,E/SMD     (  243): DCD ON
,D/AmoledAdjustTimer(  777): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,D/BatteryService(  777): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:8, charge type:1, power sharing:false
,D/BatteryService(  777): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  777): stay LED for fully charged
,D/UiModeManager(  777): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1069): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  243): DCD ON
,V/AlarmManager(  777): waitForAlarm result :8
,V/AlarmManager(  777): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1069): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1069): checkOverflow(384), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  777): SIOP:: AP = 300, Delta = 0
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/AmoledAdjustTimer(  777): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,D/TimaService(  777): TIMA: TimaService scheduler is intialized. 
D/TimaService(  777): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService(  777): TimaServiceHandler.handleMessage what =1
,D/BatteryService(  777): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:7, charge type:1, power sharing:false
,D/BatteryService(  777): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  777): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
D/BatteryService(  777): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1069): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  777): SIOP:: AP = 300, Delta = 0
,I/PowerManagerService(  777): [PWL] Off : 855s ago
,I/PowerManagerService(  777): [PWL]   PowerManagerService.WakeLocks: ref count=1
,I/PowerManagerService(  777): [PWL]     mWakeLockSummary : 0x1
,I/PowerManagerService(  777): [PWL]       PARTIAL_WAKE_LOCK              'TimaService' (uid=1000, pid=777, ws=null) (elapsedTime=3859)
,E/SMD     (  243): DCD ON
,I/TLC_TIMA_PKM_measure_kernel(  777): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel(  777): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService(  777): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService(  777): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/Watchdog(  777): !@Sync 30
,E/SMD     (  243): DCD ON
,D/AmoledAdjustTimer(  777): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,D/BatteryService(  777): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:3, charge type:1, power sharing:false
,D/BatteryService(  777): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  777): mCoverManager.getCoverState() : true
,D/BatteryService(  777): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1069): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  777): SIOP:: AP = 300, Delta = 0
,E/SMD     (  243): DCD ON
,D/AmoledAdjustTimer(  777): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,D/BatteryService(  777): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:2, charge type:1, power sharing:false
,D/BatteryService(  777): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  777): stay LED for fully charged
,D/UiModeManager(  777): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1069): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  777): SIOP:: AP = 300, Delta = 0
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/AmoledAdjustTimer(  777): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,D/BatteryService(  777): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  777): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  777): stay LED for fully charged
,D/UiModeManager(  777): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1069): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  777): SIOP:: AP = 300, Delta = 0
,E/SMD     (  243): DCD ON
,E/Watchdog(  777): !@Sync 31
,E/SMD     (  243): DCD ON
,V/GLSActivity( 1296): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1296): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/AmoledAdjustTimer(  777): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,D/BatteryService(  777): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:2, charge type:1, power sharing:false
,D/BatteryService(  777): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  777): stay LED for fully charged
,D/UiModeManager(  777): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1069): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  777): SIOP:: AP = 300, Delta = 0
,E/SMD     (  243): DCD ON
,D/AmoledAdjustTimer(  777): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,D/BatteryService(  777): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:2, charge type:1, power sharing:false
,D/BatteryService(  777): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  777): stay LED for fully charged
,D/UiModeManager(  777): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1069): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  243): DCD ON
,V/AlarmManager(  777): waitForAlarm result :8
,V/AlarmManager(  777): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1069): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1069): checkOverflow(384), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  777): SIOP:: AP = 300, Delta = 0
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/AmoledAdjustTimer(  777): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,D/BatteryService(  777): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-2, charge type:1, power sharing:false
,D/BatteryService(  777): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  777): mCoverManager.getCoverState() : true
,D/BatteryService(  777): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1069): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  777): SIOP:: AP = 300, Delta = 0
,E/SMD     (  243): DCD ON
,E/Watchdog(  777): !@Sync 32
,E/SMD     (  243): DCD ON
,D/AmoledAdjustTimer(  777): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,D/BatteryService(  777): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:7, charge type:1, power sharing:false
,D/BatteryService(  777): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  777): stay LED for fully charged
,D/UiModeManager(  777): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1069): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  777): SIOP:: AP = 300, Delta = 0
,E/SMD     (  243): DCD ON
,D/AmoledAdjustTimer(  777): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,D/BatteryService(  777): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:7, charge type:1, power sharing:false
,D/BatteryService(  777): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  777): stay LED for fully charged
,D/UiModeManager(  777): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1069): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  777): SIOP:: AP = 300, Delta = 0
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/AmoledAdjustTimer(  777): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,D/BatteryService(  777): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:8, charge type:1, power sharing:false
,D/BatteryService(  777): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  777): stay LED for fully charged
,D/UiModeManager(  777): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,E/SMD     (  243): DCD ON
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1069): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  777): SIOP:: AP = 300, Delta = 0
,E/Watchdog(  777): !@Sync 33
,E/SMD     (  243): DCD ON
,I/PowerManagerService(  777): [PWL] Off : 950s ago
,D/AmoledAdjustTimer(  777): prevTemp = 270, currTemp = 269, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,D/BatteryService(  777): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:3, charge type:1, power sharing:false
,D/BatteryService(  777): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  777): mCoverManager.getCoverState() : true
,D/BatteryService(  777): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1069): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  777): SIOP:: AP = 300, Delta = 0
,E/SMD     (  243): DCD ON
,D/AmoledAdjustTimer(  777): prevTemp = 269, currTemp = 269, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,D/BatteryService(  777): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:8, charge type:1, power sharing:false
,D/BatteryService(  777): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  777): stay LED for fully charged
,D/UiModeManager(  777): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1069): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  243): DCD ON
,V/AlarmManager(  777): waitForAlarm result :8
,V/AlarmManager(  777): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1069): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1069): checkOverflow(384), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  777): SIOP:: AP = 300, Delta = 0
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/AmoledAdjustTimer(  777): prevTemp = 269, currTemp = 269, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,D/BatteryService(  777): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:10, charge type:1, power sharing:false
,D/BatteryService(  777): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  777): mCoverManager.getCoverState() : true
,D/BatteryService(  777): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1069): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  777): SIOP:: AP = 300, Delta = 0
,E/Watchdog(  777): !@Sync 34
,E/SMD     (  243): DCD ON
,D/AmoledAdjustTimer(  777): prevTemp = 269, currTemp = 269, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,D/BatteryService(  777): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:3, charge type:1, power sharing:false
,D/BatteryService(  777): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  777): mCoverManager.getCoverState() : true
,D/BatteryService(  777): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1069): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  777): SIOP:: AP = 300, Delta = 0
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
D/AmoledAdjustTimer(  777): prevTemp = 269, currTemp = 269, prevStep = 4, currStep = 4
,D/BatteryService(  777): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:8, charge type:1, power sharing:false
,D/BatteryService(  777): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  777): mCoverManager.getCoverState() : true
,D/BatteryService(  777): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1069): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  777): SIOP:: AP = 300, Delta = 0
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/AmoledAdjustTimer(  777): prevTemp = 269, currTemp = 269, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,D/BatteryService(  777): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:9, charge type:1, power sharing:false
,D/BatteryService(  777): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  777): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
D/UiModeManager(  777): mCoverManager.getCoverState() : true
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1069): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  777): SIOP:: AP = 300, Delta = 0
,E/Watchdog(  777): !@Sync 35
,E/SMD     (  243): DCD ON
,D/AmoledAdjustTimer(  777): prevTemp = 269, currTemp = 269, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,D/BatteryService(  777): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:9, charge type:1, power sharing:false
,D/BatteryService(  777): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  777): stay LED for fully charged
,D/UiModeManager(  777): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1069): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  777): SIOP:: AP = 300, Delta = 0
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/AmoledAdjustTimer(  777): prevTemp = 269, currTemp = 269, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,V/AlarmManager(  777): waitForAlarm result :8
,V/AlarmManager(  777): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1069): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1069): checkOverflow(384), More:false, Req:false Child:2
,D/BatteryService(  777): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:2, charge type:1, power sharing:false
,D/BatteryService(  777): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  777): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/UiModeManager(  777): mCoverManager.getCoverState() : true
,D/STATUSBAR-IconMerger( 1069): checkOverflow(384), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  777): SIOP:: AP = 300, Delta = 0
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/AmoledAdjustTimer(  777): prevTemp = 269, currTemp = 269, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,D/BatteryService(  777): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:2, charge type:1, power sharing:false
,D/BatteryService(  777): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  777): stay LED for fully charged
,D/UiModeManager(  777): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1069): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  777): SIOP:: AP = 300, Delta = 0
,E/Watchdog(  777): !@Sync 36
,E/SMD     (  243): DCD ON
,D/AmoledAdjustTimer(  777): prevTemp = 269, currTemp = 269, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,D/BatteryService(  777): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:10, charge type:1, power sharing:false
,D/BatteryService(  777): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  777): stay LED for fully charged
,D/UiModeManager(  777): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1069): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  777): SIOP:: AP = 300, Delta = 0
,E/SMD     (  243): DCD ON
,I/PowerManagerService(  777): [PWL] Off : 1050s ago
,E/SMD     (  243): DCD ON
,D/AmoledAdjustTimer(  777): prevTemp = 269, currTemp = 269, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,D/BatteryService(  777): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  777): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  777): stay LED for fully charged
,D/UiModeManager(  777): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1069): checkOverflow(384), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  777): SIOP:: AP = 300, Delta = 0
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/AmoledAdjustTimer(  777): prevTemp = 269, currTemp = 269, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,D/BatteryService(  777): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  777): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  777): stay LED for fully charged
,D/UiModeManager(  777): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1069): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  777): SIOP:: AP = 300, Delta = 0
,E/Watchdog(  777): !@Sync 37
,E/SMD     (  243): DCD ON
,D/AmoledAdjustTimer(  777): prevTemp = 269, currTemp = 269, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  777): SIOP:: AP = 300, Delta = 0
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/AmoledAdjustTimer(  777): prevTemp = 269, currTemp = 269, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,V/AlarmManager(  777): waitForAlarm result :8
,V/AlarmManager(  777): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1069): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1069): checkOverflow(384), More:false, Req:false Child:2
,D/BatteryService(  777): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:5, charge type:1, power sharing:false
,D/BatteryService(  777): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  777): mCoverManager.getCoverState() : true
,D/BatteryService(  777): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1069): checkOverflow(384), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  777): SIOP:: AP = 300, Delta = 0
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/AmoledAdjustTimer(  777): prevTemp = 269, currTemp = 269, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,D/BatteryService(  777): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:7, charge type:1, power sharing:false
,D/BatteryService(  777): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  777): stay LED for fully charged
,D/UiModeManager(  777): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1069): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  777): SIOP:: AP = 300, Delta = 0
,E/Watchdog(  777): !@Sync 38
,E/SMD     (  243): DCD ON
,D/AmoledAdjustTimer(  777): prevTemp = 269, currTemp = 269, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/BatteryService(  777): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:9, charge type:1, power sharing:false
,D/BatteryService(  777): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  777): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
D/BatteryService(  777): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1069): checkOverflow(384), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  777): SIOP:: AP = 300, Delta = 0
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/AmoledAdjustTimer(  777): prevTemp = 269, currTemp = 269, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,D/BatteryService(  777): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:8, charge type:1, power sharing:false
,D/BatteryService(  777): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  777): stay LED for fully charged
,D/UiModeManager(  777): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1069): checkOverflow(384), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  777): SIOP:: AP = 300, Delta = 0
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/AmoledAdjustTimer(  777): prevTemp = 269, currTemp = 269, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  777): SIOP:: AP = 300, Delta = 0
,E/Watchdog(  777): !@Sync 39
,E/SMD     (  243): DCD ON
,D/AmoledAdjustTimer(  777): prevTemp = 269, currTemp = 269, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/BatteryService(  777): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:10, charge type:1, power sharing:false
,D/BatteryService(  777): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  777): mCoverManager.getCoverState() : true
,D/BatteryService(  777): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1069): checkOverflow(384), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  777): SIOP:: AP = 300, Delta = 0
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/AmoledAdjustTimer(  777): prevTemp = 269, currTemp = 269, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,V/AlarmManager(  777): waitForAlarm result :8
,V/AlarmManager(  777): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1069): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1069): checkOverflow(384), More:false, Req:false Child:2
,D/BatteryService(  777): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:5, charge type:1, power sharing:false
,D/BatteryService(  777): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  777): mCoverManager.getCoverState() : true
,D/BatteryService(  777): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1069): checkOverflow(384), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  777): SIOP:: AP = 300, Delta = 0
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/AmoledAdjustTimer(  777): prevTemp = 269, currTemp = 269, prevStep = 4, currStep = 4
,D/TimaService(  777): TIMA: TimaService scheduler is intialized. 
D/TimaService(  777): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService(  777): TimaServiceHandler.handleMessage what =1
,E/SMD     (  243): DCD ON
,D/BatteryService(  777): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:8, charge type:1, power sharing:false
,D/BatteryService(  777): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  777): stay LED for fully charged
,D/UiModeManager(  777): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1069): checkOverflow(384), More:false, Req:false Child:2
,I/PowerManagerService(  777): [PWL] Off : 1155s ago
,I/PowerManagerService(  777): [PWL]   PowerManagerService.WakeLocks: ref count=1
,I/PowerManagerService(  777): [PWL]     mWakeLockSummary : 0x1
,I/PowerManagerService(  777): [PWL]       PARTIAL_WAKE_LOCK              'TimaService' (uid=1000, pid=777, ws=null) (elapsedTime=3880)
,I/TLC_TIMA_PKM_measure_kernel(  777): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel(  777): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService(  777): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService(  777): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  777): SIOP:: AP = 300, Delta = 0
,E/Watchdog(  777): !@Sync 40
,E/SMD     (  243): DCD ON
,D/AmoledAdjustTimer(  777): prevTemp = 269, currTemp = 269, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/BatteryService(  777): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  777): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  777): stay LED for fully charged
,D/UiModeManager(  777): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1069): checkOverflow(384), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  777): SIOP:: AP = 300, Delta = 0
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/AmoledAdjustTimer(  777): prevTemp = 269, currTemp = 269, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,D/BatteryService(  777): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:9, charge type:1, power sharing:false
,D/BatteryService(  777): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  777): stay LED for fully charged
,D/UiModeManager(  777): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1069): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  777): SIOP:: AP = 300, Delta = 0
,E/SMD     (  243): DCD ON
,D/AmoledAdjustTimer(  777): prevTemp = 269, currTemp = 269, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,D/BatteryService(  777): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-2, charge type:1, power sharing:false
,D/BatteryService(  777): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  777): stay LED for fully charged
,D/UiModeManager(  777): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1069): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  777): SIOP:: AP = 300, Delta = 0
,E/Watchdog(  777): !@Sync 41
,E/SMD     (  243): DCD ON
,V/GLSActivity( 1296): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1296): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/AmoledAdjustTimer(  777): prevTemp = 269, currTemp = 269, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/BatteryService(  777): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:8, charge type:1, power sharing:false
,D/BatteryService(  777): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  777): mCoverManager.getCoverState() : true
,D/BatteryService(  777): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1069): checkOverflow(384), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  777): SIOP:: AP = 300, Delta = 0
,E/SMD     (  243): DCD ON
,V/AlarmManager(  777): waitForAlarm result :8
,I/SensorManagerA(  777): getReportingMode :: sensor.mType = 5
,D/Sensors (  777): LightSensor setDelay = 200000000
,D/Sensors (  777): LightSensor setSensorDelay = 200000000
,D/Sensors (  777): Light sensor flush: not enabled 0
D/Sensors (  777): LightSensor enable = 1
,D/LightsService(  777): [api] onReceive : SvcLEDReceiver re-enables LightSenor and sends MSG_FORCEDSVCLEDTASK
D/Sensors (  777): LightSensor enableSensor = 1
D/SensorManager(  777): registerListener :: 16, CM36686 Light Sensor, 200000, 0,  
,E/SMD     (  243): DCD ON
,D/Sensors (  777): LightSensor enable = 0
,D/Sensors (  777): LightSensor enableSensor = 0
,D/LightsService(  777): [SvcLED]  onSensorChanged::light value = 23
,D/SensorManager(  777): unregisterListener ::   
D/LightsService(  777): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,D/AmoledAdjustTimer(  777): prevTemp = 269, currTemp = 269, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,V/AlarmManager(  777): waitForAlarm result :8
,V/AlarmManager(  777): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1069): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1069): checkOverflow(384), More:false, Req:false Child:2
,D/BatteryService(  777): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:4, charge type:1, power sharing:false
,D/BatteryService(  777): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  777): mCoverManager.getCoverState() : true
,D/BatteryService(  777): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1069): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  777): SIOP:: AP = 300, Delta = 0
,E/SMD     (  243): DCD ON
,D/AmoledAdjustTimer(  777): prevTemp = 269, currTemp = 269, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,D/BatteryService(  777): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  777): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  777): stay LED for fully charged
,D/UiModeManager(  777): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1069): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  777): SIOP:: AP = 300, Delta = 0
,E/Watchdog(  777): !@Sync 42
,E/SMD     (  243): DCD ON
,D/AmoledAdjustTimer(  777): prevTemp = 269, currTemp = 269, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/BatteryService(  777): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:2, charge type:1, power sharing:false
,D/BatteryService(  777): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  777): stay LED for fully charged
,D/UiModeManager(  777): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1069): checkOverflow(384), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  777): SIOP:: AP = 300, Delta = 0
,E/SMD     (  243): DCD ON
,E/SMD     (  243): DCD ON
,D/AmoledAdjustTimer(  777): prevTemp = 269, currTemp = 269, prevStep = 4, currStep = 4
,D/dalvikvm(  777): GC_CONCURRENT freed 3350K, 59% free 23375K/56284K, paused 26ms+47ms, total 495ms
,E/SMD     (  243): DCD ON
,D/BatteryService(  777): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:5, charge type:1, power sharing:false
,D/BatteryService(  777): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  777): mCoverManager.getCoverState() : true
,D/BatteryService(  777): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1069): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  777): SIOP:: AP = 300, Delta = 0
,E/SMD     (  243): DCD ON
,D/AmoledAdjustTimer(  777): prevTemp = 269, currTemp = 269, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,D/BatteryService(  777): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:5, charge type:1, power sharing:false
,D/BatteryService(  777): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  777): stay LED for fully charged
,D/UiModeManager(  777): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1069): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  243): DCD ON
,D/SSRMv2:SIOP(  777): SIOP:: AP = 300, Delta = 0
,E/Watchdog(  777): !@Sync 43
,E/SMD     (  243): DCD ON
,D/AmoledAdjustTimer(  777): prevTemp = 269, currTemp = 269, prevStep = 4, currStep = 4
,E/SMD     (  243): DCD ON
,TIME-OUT KILL (timeout was 1200000ms),D/AndroidRuntime( 5090): 
D/AndroidRuntime( 5090): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 5090): CheckJNI is OFF
D/AndroidRuntime( 5090): setted country_code = Poland
D/AndroidRuntime( 5090): setted countryiso_code = PL
D/AndroidRuntime( 5090): setted sales_code = XEO
D/AndroidRuntime( 5090): readGMSProperty: start
D/AndroidRuntime( 5090): readGMSProperty: already setted!!
D/AndroidRuntime( 5090): readGMSProperty: end
D/AndroidRuntime( 5090): addProductProperty: start
D/dalvikvm( 5090): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 5090): Added shared lib libjavacore.so 0x0
D/dalvikvm( 5090): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 5090): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 5090): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
E/memtrack( 5090): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 5090): failed to load memtrack module: -2
D/dalvikvm( 5090): Note: class Landroid/app/ActivityManagerNative; has 192 unimplemented (abstract) methods
D/AndroidRuntime( 5090): Calling main entry com.android.commands.pm.Pm
D/PackageManagerService(  777): deletePackageAsUser- pkg:com.test.thalitest, userId:0
D/PersonaManagerService(  777): isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
D/PersonaManagerService(  777): isFromApprovedUnInstaller: isApproved : true
D/PersonaManagerService(  777): isFromApprovedUnInstaller: isApproved before exit: true
D/PackageManager(  777): deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag3
D/PackageManager(  777): deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag3
D/PackageManagerService(  777): deletePackage- pkg:com.test.thalitest, edmuserId:0
D/PackageManagerService(  777): deletePackage- pkg:com.test.thalitest, edmuserId:-1
D/ApplicationPolicy(  777): getApplicationUninstallationEnabled
D/ApplicationPolicy(  777): getApplicationUninstallationEnabled :  enabled true
D/PackageManagerService(  777): deletePackageX- pkg:com.test.thalitest, userId:0
D/PackageManager(  777): START PACKAGE DELETE: observer{1145119912}
D/PackageManager(  777): pkg{<packageName>}
D/PackageManager(  777): user{0}
D/PackageManager(  777): deletePackageAsUser : uid = 2000 userId = 0
D/PackageManager(  777): [MSG] DELETE_PACKAGE_AS_USER
D/PackageManager(  777): !@killApplicatoin: 10179, uninstall pkg
I/ActivityManager(  777): Killing 4518:com.test.thalitest/u0a179 (adj 9): stop com.test.thalitest
D/PackageManager(  777): Sending to user 0: act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000000 Bundle[{android.intent.extra.REMOVED_FOR_ALL_USERS=true, android.intent.extra.UID=10179, android.intent.extra.DATA_REMOVED=true, android.intent.extra.user_handle=0}]
D/dalvikvm( 1787): GC_EXPLICIT freed 704K, 37% free 11864K/18724K, paused 4ms+7ms, total 47ms
D/dalvikvm( 2116): GC_EXPLICIT freed 1202K, 40% free 11246K/18724K, paused 2ms+3ms, total 40ms
D/PackageManager(  777): Sending to user 0: act=android.intent.action.PACKAGE_FULLY_REMOVED dat=package:com.test.thalitest flg=0x4000000 Bundle[{android.intent.extra.REMOVED_FOR_ALL_USERS=true, android.intent.extra.UID=10179, android.intent.extra.DATA_REMOVED=true, android.intent.extra.user_handle=0}]
I/FPMS_FingerprintManagerService( 1088): onReceive: android.intent.action.PACKAGE_REMOVED
D/AdaptiveEventManager( 1069): action=android.intent.action.PACKAGE_REMOVED
I/InputReader(  777): Reconfiguring input devices.  changes=0x00000010
D/dalvikvm( 1404): GC_EXPLICIT freed 4287K, 47% free 10024K/18724K, paused 3ms+4ms, total 48ms
D/QuickConnect[1.1][2] ( 3082): SconnectManager.onReceiver - action : android.intent.action.PACKAGE_REMOVED, package : com.test.thalitest
I/SELinux ( 5110): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5110):  
D/dalvikvm(  250): GC_EXPLICIT freed 43K, 50% free 9510K/18724K, paused 2ms+3ms, total 29ms
D/dalvikvm(  250): GC_EXPLICIT freed <1K, 50% free 9510K/18724K, paused 2ms+3ms, total 20ms
I/SELinux ( 5110): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5110):  
I/SELinux ( 5110):  
I/SELinux ( 5110): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 5110): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 5110): >>>>> Normal User
E/dalvikvm( 5110): >>>>> com.sec.esdk.elm [ userId:0 | appId:10094 ]
E/SELinux ( 5110): [DEBUG] seapp_context_lookup: seinfoCategory = platform
D/TimaKeyStoreProvider( 5110): in addTimaSignatureService
D/dalvikvm(  250): GC_EXPLICIT freed <1K, 50% free 9510K/18724K, paused 8ms+2ms, total 25ms
W/GeofencerStateMachine( 1220): Ignoring removeGeofence because network location is disabled.
I/PackageManager(  777):   Action: "android.intent.action.SENDTO"
I/PackageManager(  777):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  777):   Scheme: "sms"
I/PackageManager(  777): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
D/TimaKeyStoreProvider( 5110): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 5110): Added TimaKesytore provider
I/PackageManager(  777):   Action: "android.intent.action.SENDTO"
I/PackageManager(  777):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  777):   Scheme: "smsto"
I/PackageManager(  777): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
W/InputMethodInfo(  777): Duplicated subtype definition found: , voice
I/PackageManager(  777):   Action: "android.intent.action.SENDTO"
I/PackageManager(  777):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  777):   Scheme: "mms"
I/PackageManager(  777): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
I/PackageManager(  777):   Action: "android.intent.action.SENDTO"
I/PackageManager(  777):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  777):   Scheme: "mmsto"
I/PackageManager(  777): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
D/dalvikvm(  777): GC_EXPLICIT freed 1338K, 59% free 23428K/56284K, paused 9ms+16ms, total 228ms
D/dalvikvm(  777): WAIT_FOR_CONCURRENT_GC blocked 66ms
W/ActivityManager(  777): Permission Denial: getCurrentUser() from pid=5110, uid=10094 requires android.permission.INTERACT_ACROSS_USERS
I/PackageManager(  777):   Action: "android.intent.action.SENDTO"
I/PackageManager(  777):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  777):   Scheme: "sms"
D/EnterpriseDeviceManagerService(  777): Package has changed for user 0
D/EnterpriseDeviceManagerService(  777): Admin package name: com.google.android.gms
I/PackageManager(  777): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
D/RCPManagerService(  777): PackageReceiver onReceive()
D/elm:14132( 5110): ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
D/elm:14132( 5110): ELMEngine.ELMEngine( context ).
D/elm:14132( 5110): MDMBridge.setEnterpriseBridge()
I/HarmonyEASService(  777): onReceive : android.intent.action.PACKAGE_REMOVED for 0
I/PackageManager(  777):   Action: "android.intent.action.SENDTO"
I/PackageManager(  777):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  777):   Scheme: "smsto"
I/PackageManager(  777): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
D/elm:14132( 5110): ELMAbstractReceiver : Receive Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
D/elm:14132( 5110): ElmAgentService : onCreate()
D/elm:14132( 5110): ElmAgentService : onHandleIntent() Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
D/elm:14132( 5110): MainReceiver.listeningToPackageRemoved()
D/elm:14132( 5110): MDMBridge.getInstance()
D/elm:14132( 5110): MDMBridge.getAllLicenseInfoFromSDK()
D/elm:14132( 5110): MDMBridge.getAllLicenseInfoFromSDK()
I/PackageManager(  777):   Action: "android.intent.action.SENDTO"
I/PackageManager(  777):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  777):   Scheme: "mms"
I/PackageManager(  777): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
I/PackageManager(  777):   Action: "android.intent.action.SENDTO"
I/PackageManager(  777):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  777):   Scheme: "mmsto"
I/PackageManager(  777): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
I/SELinux ( 5129): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5129):  
D/elm:14132( 5110): MainReceiver.listeningToPackageRemoved(). SEND to KLMS. Remove All KNOX/ONS License
W/Resources(  777): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/elm:14132( 5110): ElmAgentService : onDestroy().
W/Resources(  777): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
I/SELinux ( 5129): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5129):  
I/SELinux ( 5129):  
I/SELinux ( 5129): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 5129): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 5129): >>>>> Normal User
E/dalvikvm( 5129): >>>>> com.sec.android.app.mss [ userId:0 | appId:10021 ]
E/SELinux ( 5129): [DEBUG] seapp_context_lookup: seinfoCategory = platform
W/Resources(  777): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/TimaKeyStoreProvider( 5129): in addTimaSignatureService
E/SMD     (  243): DCD ON
D/TimaKeyStoreProvider( 5129): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 5129): Added TimaKesytore provider
W/Resources(  777): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/BackupManagerService(  777): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
V/BackupManagerService(  777): removePackageParticipantsLocked: uid=10179 #1
D/dalvikvm(  777): GC_EXPLICIT freed 890K, 59% free 23449K/56284K, paused 7ms+21ms, total 252ms
D/PackageManager(  777): delete sourFile : 
D/PackageManager(  777): delete native library directory: 
D/PackageManager(  777): return delete result to caller: 1145119912
D/AndroidRuntime( 5090): Shutting down VM
D/PackageManager(  777): returnCode: 1
D/dalvikvm( 5090): GC_CONCURRENT freed 96K, 14% free 670K/772K, paused 0ms+0ms, total 2ms
W/Resources(  777): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
I/PackageManager(  777):   Action: "android.intent.action.SENDTO"
I/PackageManager(  777):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  777):   Scheme: "sms"
I/PackageManager(  777): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
I/PackageManager(  777):   Action: "android.intent.action.SENDTO"
I/PackageManager(  777):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  777):   Scheme: "smsto"
I/PackageManager(  777): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
W/ActivityManager(  777): Permission Denial: getCurrentUser() from pid=5129, uid=10021 requires android.permission.INTERACT_ACROSS_USERS
I/PackageManager(  777):   Action: "android.intent.action.SENDTO"
I/PackageManager(  777):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  777):   Scheme: "mms"
I/PackageManager(  777): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
I/PackageManager(  777):   Action: "android.intent.action.SENDTO"
I/PackageManager(  777):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  777):   Scheme: "mmsto"
I/PackageManager(  777): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
I/PCWCLIENTTRACE_PushUtil( 4387): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 4387): sales region : global
I/PCWCLIENTTRACE_PushUtil( 4387): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver( 4387): [onReceive] - android.intent.action.PACKAGE_REMOVED
W/Resources(  777): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  777): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  777): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  777): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  777): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  777): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
W/Resources(  777): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  777): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  777): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
W/Resources(  777): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
I/SA      ( 4576): [SUR] onReceive log=[SA = 2.0.0117 V = 19 HWD = 1280X720 2.0 dpi = 320  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = kmini3g P = kmini3gxx I = KOT49H M = SM-G800H OKLEFT false DIS KOT49H.G800HXXU1ANK2 PSS = 4.497045606779314  ]
W/Resources(  777): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  777): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
I/SA      ( 4576): [SUR] onReceive Intent=[ action_PACKAGE_REMOVED package ]
I/ActivityManager(  777): Killing 3926:com.sec.android.app.videoplayer/u0a52 (adj 15): empty #43
D/UsbSettingsManager(  777): clearDefaults: com.test.thalitest
I/CrashAnrDetector(  777): onPackageRemoved : com.test.thalitest
I/IcingCorporaProvider( 2116): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
I/SELinux ( 5151): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5151):  
E/SQLiteLog( 2116): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
I/SELinux ( 5151): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5151):  
I/SELinux ( 5151):  
I/SELinux ( 5151): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 5151): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 5151): >>>>> Normal User
E/dalvikvm( 5151): >>>>> com.samsung.android.intelligenceservice [ userId:0 | appId:10005 ]
E/IcingCorporaProvider( 2116): Exception thrown from notifyTableChanged
E/IcingCorporaProvider( 2116): java.lang.RuntimeException: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/IcingCorporaProvider( 2116): 	at apg.a(PG:301)
E/IcingCorporaProvider( 2116): 	at apg.c(PG:222)
E/IcingCorporaProvider( 2116): 	at clo.b(PG:660)
E/IcingCorporaProvider( 2116): 	at clo.a(PG:651)
E/IcingCorporaProvider( 2116): 	at clo.g(PG:597)
E/IcingCorporaProvider( 2116): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider.update(PG:301)
E/IcingCorporaProvider( 2116): 	at android.content.ContentProvider$Transport.update(ContentProvider.java:287)
E/IcingCorporaProvider( 2116): 	at android.content.ContentResolver.update(ContentResolver.java:1327)
E/IcingCorporaProvider( 2116): 	at clp.Rl(PG:910)
E/IcingCorporaProvider( 2116): 	at clr.tL(PG:827)
E/IcingCorporaProvider( 2116): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateCorporaService.a(PG:1271)
E/IcingCorporaProvider( 2116): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateCorporaService.onHandleIntent(PG:1204)
E/IcingCorporaProvider( 2116): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/IcingCorporaProvider( 2116): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/IcingCorporaProvider( 2116): 	at android.os.Looper.loop(Looper.java:146)
E/IcingCorporaProvider( 2116): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/IcingCorporaProvider( 2116): Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/IcingCorporaProvider( 2116): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/IcingCorporaProvider( 2116): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:745)
E/IcingCorporaProvider( 2116): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/IcingCorporaProvider( 2116): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/IcingCorporaProvider( 2116): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:507)
E/IcingCorporaProvider( 2116): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:418)
E/IcingCorporaProvider( 2116): 	at apa.a(PG:382)
E/IcingCorporaProvider( 2116): 	at apg.i(PG:325)
E/IcingCorporaProvider( 2116): 	at aph.call(PG:215)
E/IcingCorporaProvider( 2116): 	at apg.a(PG:299)
E/IcingCorporaProvider( 2116): 	... 15 more
W/IcingCorporaProvider( 2116): notifyTableChanged failed.
W/IcingCorporaProvider( 2116): Table change notification failed for TableStorageSpec[applications]
I/IcingCorporaProvider( 2116): UpdateCorporaTask done [took 115 ms] updated apps [took 115 ms] 
E/SELinux ( 5151): [DEBUG] seapp_context_lookup: seinfoCategory = platform
D/TimaKeyStoreProvider( 5151): in addTimaSignatureService
D/TimaKeyStoreProvider( 5151): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 5151): Added TimaKesytore provider
D/InputReader(  777): Processing first event
D/UserAnalysis.PlaceProvider( 5151): Create SecureDbHelper
D/UserAnalysis.UserAnalysisBroadcastReceiver( 5151): Create SecureDbHelper
W/ActivityManager(  777): Permission Denial: getCurrentUser() from pid=5151, uid=10005 requires android.permission.INTERACT_ACROSS_USERS
W/ApplicationsProvider( 1404): Could not fetch usage stats
W/ApplicationsProvider( 1404): java.lang.SecurityException: Neither user 10020 nor current process has android.permission.PACKAGE_USAGE_STATS.
W/ApplicationsProvider( 1404): 	at android.os.Parcel.readException(Parcel.java:1465)
W/ApplicationsProvider( 1404): 	at android.os.Parcel.readException(Parcel.java:1419)
W/ApplicationsProvider( 1404): 	at com.android.internal.app.IUsageStats$Stub$Proxy.getAllPkgUsageStats(IUsageStats.java:317)
W/ApplicationsProvider( 1404): 	at android.app.ActivityManager.getAllPackageUsageStats(ActivityManager.java:2543)
W/ApplicationsProvider( 1404): 	at com.android.providers.applications.ApplicationsProvider.fetchUsageStats(ApplicationsProvider.java:681)
W/ApplicationsProvider( 1404): 	at com.android.providers.applications.ApplicationsProvider.updateApplicationsList(ApplicationsProvider.java:519)
W/ApplicationsProvider( 1404): 	at com.android.providers.applications.ApplicationsProvider.access$300(ApplicationsProvider.java:70)
W/ApplicationsProvider( 1404): 	at com.android.providers.applications.ApplicationsProvider$UpdateHandler.handleMessage(ApplicationsProvider.java:209)
W/ApplicationsProvider( 1404): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/ApplicationsProvider( 1404): 	at android.os.Looper.loop(Looper.java:146)
W/ApplicationsProvider( 1404): 	at android.os.HandlerThread.run(HandlerThread.java:61)
D/BatteryService(  777): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:7, charge type:1, power sharing:false
D/BatteryService(  777): Sending ACTION_BATTERY_CHANGED.
D/BatteryService(  777): stay LED for fully charged
D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
D/UiModeManager(  777): mCoverManager.getCoverState() : true
D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true

```
