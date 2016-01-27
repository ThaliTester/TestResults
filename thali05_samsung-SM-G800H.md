#### Test 568182540458528_thali05_samsung-SM-G800H Logs


```
--------- beginning of /dev/log/main
D/GalaxyFinderApplication( 4367): [Slink platform] Version = 29011
D/GalaxyFinderApplication( 4367): [Slink platform] use state of slink location service is [false] to [true]
I/SELinux ( 4386): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 4386):  
--------- beginning of /dev/log/system
I/ActivityManager(  732): Killing 3062:com.LocalFota/u0a110 (adj 15): empty #43
I/SELinux ( 4386): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 4386):  
I/SELinux ( 4386):  
I/SELinux ( 4386): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 4386): [DEBUG] seapp_context_lookup: seinfoCategory = release
E/dalvikvm( 4386): >>>>> Normal User
,E/dalvikvm( 4386): >>>>> com.sec.android.app.shealth [ userId:0 | appId:10035 ]
E/SELinux ( 4386): [DEBUG] seapp_context_lookup: seinfoCategory = release
D/TimaKeyStoreProvider( 4386): in addTimaSignatureService
D/TimaKeyStoreProvider( 4386): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 4386): Added TimaKesytore provider
W/ActivityManager(  732): Permission Denial: getCurrentUser() from pid=4386, uid=10035 requires android.permission.INTERACT_ACROSS_USERS
W/ContextImpl( 4386): Implicit intents with startService are not safe: Intent { act=com.sec.android.service.health.cp.accesscontrol } android.content.ContextWrapper.bindService:529 com.samsung.android.sdk.health.content.ShealthAccessControl.startService:274 com.samsung.android.sdk.health.content.ShealthAccessControl.requestPermission:212 
I/SELinux ( 4414): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 4414):  
E/Device Type Shared Preferences( 4386): Device Type Shared Preferences - getDeviceTypeChecked -true
E/Device Type Shared Preferences( 4386): Device Type Shared Preferences - not connecting to service
E/com.sec.android.app.shealth.SHealthApplication( 4386): ContentProvider is not null
I/SELinux ( 4414): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 4414):  
I/SELinux ( 4414):  
I/SELinux ( 4414): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 4414): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 4414): >>>>> Normal User
E/dalvikvm( 4414): >>>>> com.sec.android.service.health [ userId:0 | appId:10016 ]
E/SELinux ( 4414): [DEBUG] seapp_context_lookup: seinfoCategory = platform
D/TimaKeyStoreProvider( 4414): in addTimaSignatureService
D/TimaKeyStoreProvider( 4414): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 4414): Added TimaKesytore provider
V/MediaPlayer( 4386): decode(61, 33979084, 48105)
V/MediaPlayerService(  251): decode(33, 33979084, 48105)
V/MediaPlayerService(  251): player type = 3
V/AwesomePlayer(  251): setDefault
V/AwesomePlayer(  251): constructor
V/AwesomePlayer(  251): setDefault
V/AwesomePlayer(  251): reset_l()
V/AwesomePlayer(  251): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  251): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  251): mAudioTrackVector clear
V/AwesomePlayer(  251): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  251): mSecMediaClock clear
V/StagefrightPlayer(  251): StagefrightPlayer
V/AwesomePlayer(  251): setListener
V/StagefrightPlayer(  251): initCheck
V/AwesomePlayer(  251): setAudioSink
V/StagefrightPlayer(  251): setDataSource(33, 33979084, 48105)
V/AwesomePlayer(  251): reset_l()
V/AwesomePlayer(  251): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  251): notify(0xb743dc80, 8, 0, 0)
V/AudioCache(  251): ignored
V/AwesomePlayer(  251): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  251): mAudioTrackVector clear
V/AwesomePlayer(  251): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  251): mSecMediaClock clear
V/AwesomePlayer(  251): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer(  251): mBitrate = -1 bits/sec
V/AwesomePlayer(  251): current audio track index (0) is added to vector
V/AwesomePlayer(  251): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer(  251): AwesomePlayer::setDataSource_l():: This is not a DRM content
V/MediaPlayerService(  251): prepare
V/AwesomePlayer(  251): prepareAsync
V/MediaPlayerService(  251): wait for prepare
V/AwesomePlayer(  251): onPrepareAsyncEvent
I/SecMediaClock(  251): SecMediaClock constructor
I/SecMediaClock(  251): reset
V/AwesomePlayer(  251): initAudioDecoder
V/AwesomePlayer(  251): checkOffloadExceptions is true
I/OMXCodec(  251): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
I/OMX     (  251): mDispatchers.add
I/OMXCodec(  251): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec(  251): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec(  251): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec(  251): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/OMXCodec(  251): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer(  251): finishAsyncPrepare_l
V/AwesomePlayer(  251): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache(  251): notify(0xb743dc80, 200, 973, 0)
V/AudioCache(  251): ignored
V/AwesomePlayer(  251): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  251): notify(0xb743dc80, 5, 0, 0)
V/AudioCache(  251): ignored
V/AwesomePlayer(  251): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  251): notify(0xb743dc80, 1, 0, 0)
V/AudioCache(  251): prepared
V/AudioCache(  251): wait - success
V/MediaPlayerService(  251): start
V/StagefrightPlayer(  251): start
V/AwesomePlayer(  251): play
V/AwesomePlayer(  251): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer(  251): startAudioPlayer_l, sendErrorNotification (0)
I/OMXCodec(  251): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec(  251): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec(  251): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/AudioPlayer(  251):  Audioplayer kKeyAudioPCMFormat:1, 2, 0
I/AudioPlayer(  251):  Audioplayer kKeyAudioPCMFormat read fail(2, 1)
V/AudioCache(  251): open(44100, 2, 0x0, 1, 4)
V/AwesomePlayer(  251): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache(  251): notify(0xb743dc80, 6, 0, 0)
V/AudioCache(  251): ignored
V/AwesomePlayer(  251): addBatteryData
V/MediaPlayerService(  251): wait for playback complete
I/OMXCodec(  251): [OMX.google.vorbis.decoder] End Of Stream
V/AwesomePlayer(  251): postAudioEOS delayUs (0)
V/AwesomePlayer(  251): onCheckAudioStatus
V/AwesomePlayer(  251): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  251): onStreamDone
V/AwesomePlayer(  251): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  251): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  251): notify(0xb743dc80, 2, 0, 0)
V/AudioCache(  251): playback complete - thread will wake up later
V/AwesomePlayer(  251): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  251): notify(0xb743dc80, 7, 0, 0)
V/AudioCache(  251): ignored
V/AwesomePlayer(  251): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer(  251): addBatteryData
V/AudioCache(  251): wait - success
V/StagefrightPlayer(  251): reset
V/AwesomePlayer(  251): reset_l()
V/AwesomePlayer(  251): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  251): notify(0xb743dc80, 8, 0, 0)
V/AudioCache(  251): ignored
V/AwesomePlayer(  251): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  251): mAudioTrackVector clear
I/OMXCodec(  251): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec(  251): [OMX.google.vorbis.decoder] stop() sendCommand(0x37, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec(  251): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
I/OMXCodec(  251): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/OMX     (  251): instance freeNode
I/AudioPlayer(  251): reset out
V/AwesomePlayer(  251): reset_l() mAudioPlayer successfully deleted
I/SecMediaClock(  251): SecMediaClock destructor
V/AwesomePlayer(  251): mSecMediaClock clear
V/StagefrightPlayer(  251): ~StagefrightPlayer
V/StagefrightPlayer(  251): reset
V/AwesomePlayer(  251): reset_l()
V/AwesomePlayer(  251): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  251): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  251): mAudioTrackVector clear
V/AwesomePlayer(  251): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  251): mSecMediaClock clear
V/AwesomePlayer(  251): destructor
V/AwesomePlayer(  251): reset_l()
V/AwesomePlayer(  251): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  251): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  251): mAudioTrackVector clear
V/AwesomePlayer(  251): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  251): mSecMediaClock clear
V/MediaPlayer( 4386): decode(62, 33914984, 10421)
V/MediaPlayerService(  251): decode(33, 33914984, 10421)
V/MediaPlayerService(  251): player type = 3
V/AwesomePlayer(  251): setDefault
V/AwesomePlayer(  251): constructor
V/AwesomePlayer(  251): setDefault
V/AwesomePlayer(  251): reset_l()
V/AwesomePlayer(  251): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  251): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  251): mAudioTrackVector clear
V/AwesomePlayer(  251): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  251): mSecMediaClock clear
V/StagefrightPlayer(  251): StagefrightPlayer
V/AwesomePlayer(  251): setListener
V/StagefrightPlayer(  251): initCheck
V/AwesomePlayer(  251): setAudioSink
V/StagefrightPlayer(  251): setDataSource(33, 33914984, 10421)
V/AwesomePlayer(  251): reset_l()
V/AwesomePlayer(  251): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  251): notify(0xb743dc40, 8, 0, 0)
V/AudioCache(  251): ignored
V/AwesomePlayer(  251): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  251): mAudioTrackVector clear
V/AwesomePlayer(  251): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  251): mSecMediaClock clear
V/AwesomePlayer(  251): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer(  251): mBitrate = -1 bits/sec
V/AwesomePlayer(  251): current audio track index (0) is added to vector
V/AwesomePlayer(  251): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer(  251): AwesomePlayer::setDataSource_l():: This is not a DRM content
V/MediaPlayerService(  251): prepare
V/AwesomePlayer(  251): prepareAsync
V/MediaPlayerService(  251): wait for prepare
V/AwesomePlayer(  251): onPrepareAsyncEvent
I/SecMediaClock(  251): SecMediaClock constructor
I/SecMediaClock(  251): reset
V/AwesomePlayer(  251): initAudioDecoder
V/AwesomePlayer(  251): checkOffloadExceptions is true
I/OMXCodec(  251): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
I/OMX     (  251): mDispatchers.add
I/OMXCodec(  251): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec(  251): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec(  251): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec(  251): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/OMXCodec(  251): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer(  251): finishAsyncPrepare_l
V/AwesomePlayer(  251): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache(  251): notify(0xb743dc40, 200, 973, 0)
V/AudioCache(  251): ignored
V/AwesomePlayer(  251): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  251): notify(0xb743dc40, 5, 0, 0)
V/AudioCache(  251): ignored
V/AwesomePlayer(  251): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  251): notify(0xb743dc40, 1, 0, 0)
V/AudioCache(  251): prepared
V/AudioCache(  251): wait - success
V/MediaPlayerService(  251): start
V/StagefrightPlayer(  251): start
V/AwesomePlayer(  251): play
V/AwesomePlayer(  251): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer(  251): startAudioPlayer_l, sendErrorNotification (0)
I/OMXCodec(  251): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec(  251): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec(  251): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
W/ActivityManager(  732): Permission Denial: getCurrentUser() from pid=4414, uid=10016 requires android.permission.INTERACT_ACROSS_USERS
I/AudioPlayer(  251):  Audioplayer kKeyAudioPCMFormat:1, 2, 0
I/AudioPlayer(  251):  Audioplayer kKeyAudioPCMFormat read fail(2, 1)
V/AudioCache(  251): open(44100, 2, 0x0, 1, 4)
V/AwesomePlayer(  251): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache(  251): notify(0xb743dc40, 6, 0, 0)
V/AudioCache(  251): ignored
V/AwesomePlayer(  251): addBatteryData
V/MediaPlayerService(  251): wait for playback complete
I/OMXCodec(  251): [OMX.google.vorbis.decoder] End Of Stream
V/AwesomePlayer(  251): postAudioEOS delayUs (0)
V/AwesomePlayer(  251): onCheckAudioStatus
V/AwesomePlayer(  251): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  251): onStreamDone
V/AwesomePlayer(  251): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  251): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  251): notify(0xb743dc40, 2, 0, 0)
V/AudioCache(  251): playback complete - thread will wake up later
V/AwesomePlayer(  251): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  251): notify(0xb743dc40, 7, 0, 0)
V/AudioCache(  251): ignored
V/AwesomePlayer(  251): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer(  251): addBatteryData
V/AudioCache(  251): wait - success
V/StagefrightPlayer(  251): reset
V/AwesomePlayer(  251): reset_l()
V/AwesomePlayer(  251): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  251): notify(0xb743dc40, 8, 0, 0)
V/AudioCache(  251): ignored
V/AwesomePlayer(  251): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  251): mAudioTrackVector clear
I/OMXCodec(  251): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec(  251): [OMX.google.vorbis.decoder] stop() sendCommand(0x38, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec(  251): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
I/OMXCodec(  251): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/OMX     (  251): instance freeNode
I/AudioPlayer(  251): reset out
V/AwesomePlayer(  251): reset_l() mAudioPlayer successfully deleted
I/SecMediaClock(  251): SecMediaClock destructor
V/AwesomePlayer(  251): mSecMediaClock clear
V/StagefrightPlayer(  251): ~StagefrightPlayer
V/StagefrightPlayer(  251): reset
V/AwesomePlayer(  251): reset_l()
V/AwesomePlayer(  251): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  251): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  251): mAudioTrackVector clear
V/AwesomePlayer(  251): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  251): mSecMediaClock clear
V/AwesomePlayer(  251): destructor
V/AwesomePlayer(  251): reset_l()
V/AwesomePlayer(  251): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  251): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  251): mAudioTrackVector clear
V/AwesomePlayer(  251): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  251): mSecMediaClock clear
V/MediaPlayer( 4386): decode(63, 37457308, 34198)
V/MediaPlayerService(  251): decode(33, 37457308, 34198)
V/MediaPlayerService(  251): player type = 3
V/AwesomePlayer(  251): setDefault
V/AwesomePlayer(  251): constructor
V/AwesomePlayer(  251): setDefault
V/AwesomePlayer(  251): reset_l()
V/AwesomePlayer(  251): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  251): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  251): mAudioTrackVector clear
V/AwesomePlayer(  251): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  251): mSecMediaClock clear
V/StagefrightPlayer(  251): StagefrightPlayer
V/AwesomePlayer(  251): setListener
V/StagefrightPlayer(  251): initCheck
V/AwesomePlayer(  251): setAudioSink
V/StagefrightPlayer(  251): setDataSource(33, 37457308, 34198)
V/AwesomePlayer(  251): reset_l()
V/AwesomePlayer(  251): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  251): notify(0xb743dc40, 8, 0, 0)
V/AudioCache(  251): ignored
V/AwesomePlayer(  251): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  251): mAudioTrackVector clear
V/AwesomePlayer(  251): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  251): mSecMediaClock clear
V/AwesomePlayer(  251): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer(  251): mBitrate = -1 bits/sec
V/AwesomePlayer(  251): current audio track index (0) is added to vector
V/AwesomePlayer(  251): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer(  251): AwesomePlayer::setDataSource_l():: This is not a DRM content
V/MediaPlayerService(  251): prepare
V/AwesomePlayer(  251): prepareAsync
V/MediaPlayerService(  251): wait for prepare
V/AwesomePlayer(  251): onPrepareAsyncEvent
I/SecMediaClock(  251): SecMediaClock constructor
I/SecMediaClock(  251): reset
V/AwesomePlayer(  251): initAudioDecoder
V/AwesomePlayer(  251): checkOffloadExceptions is true
I/OMXCodec(  251): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
I/OMX     (  251): mDispatchers.add
I/OMXCodec(  251): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec(  251): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec(  251): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec(  251): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/OMXCodec(  251): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer(  251): finishAsyncPrepare_l
V/AwesomePlayer(  251): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache(  251): notify(0xb743dc40, 200, 973, 0)
V/AudioCache(  251): ignored
V/AwesomePlayer(  251): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  251): notify(0xb743dc40, 5, 0, 0)
V/AudioCache(  251): ignored
V/AwesomePlayer(  251): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  251): notify(0xb743dc40, 1, 0, 0)
V/AudioCache(  251): prepared
V/AudioCache(  251): wait - success
V/MediaPlayerService(  251): start
V/StagefrightPlayer(  251): start
V/AwesomePlayer(  251): play
V/AwesomePlayer(  251): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer(  251): startAudioPlayer_l, sendErrorNotification (0)
I/OMXCodec(  251): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec(  251): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec(  251): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
D/dalvikvm( 4414): No JNI_OnLoad found in /system/lib/libsecure_storage_jni.so 0x4262cb20, skipping init
I/SecureStorage( 4414): [INFO]: SPID(0x00000000)Checking if this device supports Secure Storage
I/SecureStorage( 4414): [INFO]: SPID(0x00000000)This device supports Secure Storage
I/AudioPlayer(  251):  Audioplayer kKeyAudioPCMFormat:1, 2, 0
I/AudioPlayer(  251):  Audioplayer kKeyAudioPCMFormat read fail(2, 1)
V/AudioCache(  251): open(44100, 2, 0x0, 1, 4)
V/AwesomePlayer(  251): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache(  251): notify(0xb743dc40, 6, 0, 0)
V/AudioCache(  251): ignored
V/AwesomePlayer(  251): addBatteryData
V/MediaPlayerService(  251): wait for playback complete
D/AndroidRuntime( 4406): 
D/AndroidRuntime( 4406): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
I/SecureStorage(  295): [INFO]: SPID(0x00000003)Credentials: uid 10016, gid 10016, pid 4414
I/SecureStorage(  295): [INFO]: SPID(0x00000003)Received function mask & code: 0000010C
I/SecureStorage( 4414): [INFO]: SPID(0x00000000)SS Daemon is running
D/AndroidRuntime( 4406): CheckJNI is OFF
D/AndroidRuntime( 4406): setted country_code = Poland
D/AndroidRuntime( 4406): setted countryiso_code = PL
D/AndroidRuntime( 4406): setted sales_code = XEO
D/AndroidRuntime( 4406): readGMSProperty: start
D/AndroidRuntime( 4406): readGMSProperty: already setted!!
D/AndroidRuntime( 4406): readGMSProperty: end
D/AndroidRuntime( 4406): addProductProperty: start
I/SecureStorage( 4414): [INFO]: SPID(0x00000000)Processing data
I/SecureStorage(  295): [INFO]: SPID(0x00000003)Credentials: uid 10016, gid 10016, pid 4414
I/SecureStorage(  295): [INFO]: SPID(0x00000003)Received function mask & code: 00000106
D/dalvikvm( 4406): Trying to load lib libjavacore.so 0x0
I/OMXCodec(  251): [OMX.google.vorbis.decoder] End Of Stream
D/dalvikvm( 4406): Added shared lib libjavacore.so 0x0
V/AwesomePlayer(  251): postAudioEOS delayUs (0)
V/AwesomePlayer(  251): onCheckAudioStatus
V/AwesomePlayer(  251): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  251): onStreamDone
V/AwesomePlayer(  251): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  251): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  251): notify(0xb743dc40, 2, 0, 0)
V/AudioCache(  251): playback complete - thread will wake up later
V/AwesomePlayer(  251): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  251): notify(0xb743dc40, 7, 0, 0)
V/AudioCache(  251): ignored
V/AwesomePlayer(  251): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer(  251): addBatteryData
V/AudioCache(  251): wait - success
V/StagefrightPlayer(  251): reset
V/AwesomePlayer(  251): reset_l()
V/AwesomePlayer(  251): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  251): notify(0xb743dc40, 8, 0, 0)
V/AudioCache(  251): ignored
V/AwesomePlayer(  251): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  251): mAudioTrackVector clear
I/OMXCodec(  251): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec(  251): [OMX.google.vorbis.decoder] stop() sendCommand(0x39, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec(  251): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
I/OMXCodec(  251): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/OMX     (  251): instance freeNode
I/AudioPlayer(  251): reset out
V/AwesomePlayer(  251): reset_l() mAudioPlayer successfully deleted
I/SecMediaClock(  251): SecMediaClock destructor
V/AwesomePlayer(  251): mSecMediaClock clear
V/StagefrightPlayer(  251): ~StagefrightPlayer
V/StagefrightPlayer(  251): reset
V/AwesomePlayer(  251): reset_l()
V/AwesomePlayer(  251): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  251): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  251): mAudioTrackVector clear
V/AwesomePlayer(  251): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  251): mSecMediaClock clear
V/AwesomePlayer(  251): destructor
V/AwesomePlayer(  251): reset_l()
V/AwesomePlayer(  251): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  251): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  251): mAudioTrackVector clear
V/AwesomePlayer(  251): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  251): mSecMediaClock clear
V/MediaPlayer( 4386): decode(64, 33862452, 7405)
V/MediaPlayerService(  251): decode(33, 33862452, 7405)
D/dalvikvm( 4406): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 4406): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 4406): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
V/MediaPlayerService(  251): player type = 3
V/AwesomePlayer(  251): setDefault
V/AwesomePlayer(  251): constructor
V/AwesomePlayer(  251): setDefault
V/AwesomePlayer(  251): reset_l()
V/AwesomePlayer(  251): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  251): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  251): mAudioTrackVector clear
V/AwesomePlayer(  251): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  251): mSecMediaClock clear
V/StagefrightPlayer(  251): StagefrightPlayer
V/AwesomePlayer(  251): setListener
V/StagefrightPlayer(  251): initCheck
V/AwesomePlayer(  251): setAudioSink
V/StagefrightPlayer(  251): setDataSource(33, 33862452, 7405)
V/AwesomePlayer(  251): reset_l()
V/AwesomePlayer(  251): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  251): notify(0xb74447d8, 8, 0, 0)
V/AudioCache(  251): ignored
V/AwesomePlayer(  251): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  251): mAudioTrackVector clear
V/AwesomePlayer(  251): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  251): mSecMediaClock clear
V/AwesomePlayer(  251): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer(  251): mBitrate = -1 bits/sec
V/AwesomePlayer(  251): current audio track index (0) is added to vector
V/AwesomePlayer(  251): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer(  251): AwesomePlayer::setDataSource_l():: This is not a DRM content
V/MediaPlayerService(  251): prepare
V/AwesomePlayer(  251): prepareAsync
V/MediaPlayerService(  251): wait for prepare
V/AwesomePlayer(  251): onPrepareAsyncEvent
I/SecMediaClock(  251): SecMediaClock constructor
I/SecMediaClock(  251): reset
V/AwesomePlayer(  251): initAudioDecoder
V/AwesomePlayer(  251): checkOffloadExceptions is true
I/OMXCodec(  251): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
I/OMX     (  251): mDispatchers.add
I/OMXCodec(  251): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec(  251): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec(  251): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec(  251): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/OMXCodec(  251): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer(  251): finishAsyncPrepare_l
V/AwesomePlayer(  251): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache(  251): notify(0xb74447d8, 200, 973, 0)
V/AudioCache(  251): ignored
V/AwesomePlayer(  251): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  251): notify(0xb74447d8, 5, 0, 0)
V/AudioCache(  251): ignored
V/AwesomePlayer(  251): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  251): notify(0xb74447d8, 1, 0, 0)
V/AudioCache(  251): prepared
V/AudioCache(  251): wait - success
V/MediaPlayerService(  251): start
V/StagefrightPlayer(  251): start
V/AwesomePlayer(  251): play
V/AwesomePlayer(  251): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer(  251): startAudioPlayer_l, sendErrorNotification (0)
I/OMXCodec(  251): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec(  251): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec(  251): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/AudioPlayer(  251):  Audioplayer kKeyAudioPCMFormat:1, 2, 0
I/AudioPlayer(  251):  Audioplayer kKeyAudioPCMFormat read fail(2, 1)
V/AudioCache(  251): open(44100, 2, 0x0, 1, 4)
V/AwesomePlayer(  251): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache(  251): notify(0xb74447d8, 6, 0, 0)
V/AudioCache(  251): ignored
V/AwesomePlayer(  251): addBatteryData
V/MediaPlayerService(  251): wait for playback complete
I/OMXCodec(  251): [OMX.google.vorbis.decoder] End Of Stream
V/AwesomePlayer(  251): postAudioEOS delayUs (0)
V/AwesomePlayer(  251): onCheckAudioStatus
V/AwesomePlayer(  251): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  251): onStreamDone
V/AwesomePlayer(  251): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  251): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  251): notify(0xb74447d8, 2, 0, 0)
V/AudioCache(  251): playback complete - thread will wake up later
V/AwesomePlayer(  251): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  251): notify(0xb74447d8, 7, 0, 0)
V/AudioCache(  251): ignored
V/AwesomePlayer(  251): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer(  251): addBatteryData
V/AudioCache(  251): wait - success
V/StagefrightPlayer(  251): reset
V/AwesomePlayer(  251): reset_l()
V/AwesomePlayer(  251): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  251): notify(0xb74447d8, 8, 0, 0)
V/AudioCache(  251): ignored
V/AwesomePlayer(  251): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  251): mAudioTrackVector clear
I/OMXCodec(  251): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec(  251): [OMX.google.vorbis.decoder] stop() sendCommand(0x3a, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec(  251): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
I/OMXCodec(  251): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/OMX     (  251): instance freeNode
I/AudioPlayer(  251): reset out
V/AwesomePlayer(  251): reset_l() mAudioPlayer successfully deleted
I/SecMediaClock(  251): SecMediaClock destructor
V/AwesomePlayer(  251): mSecMediaClock clear
V/StagefrightPlayer(  251): ~StagefrightPlayer
V/StagefrightPlayer(  251): reset
V/AwesomePlayer(  251): reset_l()
V/AwesomePlayer(  251): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  251): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  251): mAudioTrackVector clear
V/AwesomePlayer(  251): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  251): mSecMediaClock clear
V/AwesomePlayer(  251): destructor
V/AwesomePlayer(  251): reset_l()
V/AwesomePlayer(  251): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  251): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  251): mAudioTrackVector clear
V/AwesomePlayer(  251): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  251): mSecMediaClock clear
V/MediaPlayer( 4386): decode(65, 37547940, 5555)
V/MediaPlayerService(  251): decode(33, 37547940, 5555)
V/MediaPlayerService(  251): player type = 3
V/AwesomePlayer(  251): setDefault
V/AwesomePlayer(  251): constructor
V/AwesomePlayer(  251): setDefault
V/AwesomePlayer(  251): reset_l()
V/AwesomePlayer(  251): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  251): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  251): mAudioTrackVector clear
V/AwesomePlayer(  251): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  251): mSecMediaClock clear
V/StagefrightPlayer(  251): StagefrightPlayer
V/AwesomePlayer(  251): setListener
V/StagefrightPlayer(  251): initCheck
V/AwesomePlayer(  251): setAudioSink
V/StagefrightPlayer(  251): setDataSource(33, 37547940, 5555)
V/AwesomePlayer(  251): reset_l()
V/AwesomePlayer(  251): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  251): notify(0xb743dc40, 8, 0, 0)
V/AudioCache(  251): ignored
V/AwesomePlayer(  251): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  251): mAudioTrackVector clear
V/AwesomePlayer(  251): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  251): mSecMediaClock clear
V/AwesomePlayer(  251): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer(  251): mBitrate = -1 bits/sec
V/AwesomePlayer(  251): current audio track index (0) is added to vector
V/AwesomePlayer(  251): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer(  251): AwesomePlayer::setDataSource_l():: This is not a DRM content
V/MediaPlayerService(  251): prepare
V/AwesomePlayer(  251): prepareAsync
V/MediaPlayerService(  251): wait for prepare
V/AwesomePlayer(  251): onPrepareAsyncEvent
I/SecMediaClock(  251): SecMediaClock constructor
I/SecMediaClock(  251): reset
V/AwesomePlayer(  251): initAudioDecoder
V/AwesomePlayer(  251): checkOffloadExceptions is true
I/OMXCodec(  251): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
I/OMX     (  251): mDispatchers.add
I/OMXCodec(  251): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec(  251): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec(  251): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec(  251): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/OMXCodec(  251): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer(  251): finishAsyncPrepare_l
V/AwesomePlayer(  251): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache(  251): notify(0xb743dc40, 200, 973, 0)
V/AudioCache(  251): ignored
V/AwesomePlayer(  251): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  251): notify(0xb743dc40, 5, 0, 0)
V/AudioCache(  251): ignored
V/AwesomePlayer(  251): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  251): notify(0xb743dc40, 1, 0, 0)
V/AudioCache(  251): prepared
V/AudioCache(  251): wait - success
V/MediaPlayerService(  251): start
V/StagefrightPlayer(  251): start
V/AwesomePlayer(  251): play
V/AwesomePlayer(  251): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer(  251): startAudioPlayer_l, sendErrorNotification (0)
I/OMXCodec(  251): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec(  251): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec(  251): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/AudioPlayer(  251):  Audioplayer kKeyAudioPCMFormat:1, 2, 0
I/AudioPlayer(  251):  Audioplayer kKeyAudioPCMFormat read fail(2, 1)
V/AudioCache(  251): open(44100, 2, 0x0, 1, 4)
V/AwesomePlayer(  251): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache(  251): notify(0xb743dc40, 6, 0, 0)
V/AudioCache(  251): ignored
V/AwesomePlayer(  251): addBatteryData
V/MediaPlayerService(  251): wait for playback complete
I/OMXCodec(  251): [OMX.google.vorbis.decoder] End Of Stream
V/AwesomePlayer(  251): postAudioEOS delayUs (0)
V/AwesomePlayer(  251): onCheckAudioStatus
V/AwesomePlayer(  251): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  251): onStreamDone
V/AwesomePlayer(  251): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  251): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  251): notify(0xb743dc40, 2, 0, 0)
V/AudioCache(  251): playback complete - thread will wake up later
V/AwesomePlayer(  251): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  251): notify(0xb743dc40, 7, 0, 0)
V/AudioCache(  251): ignored
V/AwesomePlayer(  251): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer(  251): addBatteryData
V/AudioCache(  251): wait - success
V/StagefrightPlayer(  251): reset
V/AwesomePlayer(  251): reset_l()
V/AwesomePlayer(  251): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  251): notify(0xb743dc40, 8, 0, 0)
V/AudioCache(  251): ignored
V/AwesomePlayer(  251): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  251): mAudioTrackVector clear
I/OMXCodec(  251): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec(  251): [OMX.google.vorbis.decoder] stop() sendCommand(0x3b, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec(  251): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
I/OMXCodec(  251): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/OMX     (  251): instance freeNode
I/AudioPlayer(  251): reset out
V/AwesomePlayer(  251): reset_l() mAudioPlayer successfully deleted
I/SecMediaClock(  251): SecMediaClock destructor
V/AwesomePlayer(  251): mSecMediaClock clear
V/StagefrightPlayer(  251): ~StagefrightPlayer
V/StagefrightPlayer(  251): reset
V/AwesomePlayer(  251): reset_l()
V/AwesomePlayer(  251): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  251): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  251): mAudioTrackVector clear
V/AwesomePlayer(  251): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  251): mSecMediaClock clear
V/AwesomePlayer(  251): destructor
V/AwesomePlayer(  251): reset_l()
V/AwesomePlayer(  251): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  251): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  251): mAudioTrackVector clear
V/AwesomePlayer(  251): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  251): mSecMediaClock clear
V/MediaPlayer( 4386): decode(66, 30367732, 5085)
V/MediaPlayerService(  251): decode(33, 30367732, 5085)
V/MediaPlayerService(  251): player type = 3
V/AwesomePlayer(  251): setDefault
V/AwesomePlayer(  251): constructor
V/AwesomePlayer(  251): setDefault
V/AwesomePlayer(  251): reset_l()
V/AwesomePlayer(  251): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  251): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  251): mAudioTrackVector clear
V/AwesomePlayer(  251): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  251): mSecMediaClock clear
V/StagefrightPlayer(  251): StagefrightPlayer
V/AwesomePlayer(  251): setListener
V/StagefrightPlayer(  251): initCheck
V/AwesomePlayer(  251): setAudioSink
V/StagefrightPlayer(  251): setDataSource(33, 30367732, 5085)
V/AwesomePlayer(  251): reset_l()
V/AwesomePlayer(  251): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  251): notify(0xb7437ec0, 8, 0, 0)
V/AudioCache(  251): ignored
V/AwesomePlayer(  251): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  251): mAudioTrackVector clear
V/AwesomePlayer(  251): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  251): mSecMediaClock clear
V/AwesomePlayer(  251): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer(  251): mBitrate = -1 bits/sec
V/AwesomePlayer(  251): current audio track index (0) is added to vector
V/AwesomePlayer(  251): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer(  251): AwesomePlayer::setDataSource_l():: This is not a DRM content
V/MediaPlayerService(  251): prepare
V/AwesomePlayer(  251): prepareAsync
V/MediaPlayerService(  251): wait for prepare
V/AwesomePlayer(  251): onPrepareAsyncEvent
I/SecMediaClock(  251): SecMediaClock constructor
I/SecMediaClock(  251): reset
V/AwesomePlayer(  251): initAudioDecoder
V/AwesomePlayer(  251): checkOffloadExceptions is true
I/OMXCodec(  251): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
I/OMX     (  251): mDispatchers.add
I/OMXCodec(  251): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec(  251): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec(  251): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec(  251): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/OMXCodec(  251): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer(  251): finishAsyncPrepare_l
V/AwesomePlayer(  251): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache(  251): notify(0xb7437ec0, 200, 973, 0)
V/AudioCache(  251): ignored
V/AwesomePlayer(  251): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  251): notify(0xb7437ec0, 5, 0, 0)
V/AudioCache(  251): ignored
V/AwesomePlayer(  251): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  251): notify(0xb7437ec0, 1, 0, 0)
V/AudioCache(  251): prepared
V/AudioCache(  251): wait - success
V/MediaPlayerService(  251): start
V/StagefrightPlayer(  251): start
V/AwesomePlayer(  251): play
V/AwesomePlayer(  251): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer(  251): startAudioPlayer_l, sendErrorNotification (0)
I/OMXCodec(  251): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec(  251): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec(  251): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/AudioPlayer(  251):  Audioplayer kKeyAudioPCMFormat:1, 2, 0
I/AudioPlayer(  251):  Audioplayer kKeyAudioPCMFormat read fail(2, 1)
V/AudioCache(  251): open(44100, 2, 0x0, 1, 4)
V/AwesomePlayer(  251): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache(  251): notify(0xb7437ec0, 6, 0, 0)
V/AudioCache(  251): ignored
V/AwesomePlayer(  251): addBatteryData
V/MediaPlayerService(  251): wait for playback complete
I/OMXCodec(  251): [OMX.google.vorbis.decoder] End Of Stream
V/AwesomePlayer(  251): postAudioEOS delayUs (0)
V/AwesomePlayer(  251): onCheckAudioStatus
V/AwesomePlayer(  251): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  251): onStreamDone
V/AwesomePlayer(  251): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  251): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  251): notify(0xb7437ec0, 2, 0, 0)
V/AudioCache(  251): playback complete - thread will wake up later
V/AwesomePlayer(  251): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  251): notify(0xb7437ec0, 7, 0, 0)
V/AudioCache(  251): ignored
V/AwesomePlayer(  251): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer(  251): addBatteryData
V/AudioCache(  251): wait - success
V/StagefrightPlayer(  251): reset
V/AwesomePlayer(  251): reset_l()
V/AwesomePlayer(  251): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  251): notify(0xb7437ec0, 8, 0, 0)
V/AudioCache(  251): ignored
V/AwesomePlayer(  251): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  251): mAudioTrackVector clear
I/OMXCodec(  251): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec(  251): [OMX.google.vorbis.decoder] stop() sendCommand(0x3c, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec(  251): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
I/OMXCodec(  251): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/OMX     (  251): instance freeNode
I/AudioPlayer(  251): reset out
V/AwesomePlayer(  251): reset_l() mAudioPlayer successfully deleted
I/SecMediaClock(  251): SecMediaClock destructor
V/AwesomePlayer(  251): mSecMediaClock clear
V/StagefrightPlayer(  251): ~StagefrightPlayer
V/StagefrightPlayer(  251): reset
V/AwesomePlayer(  251): reset_l()
V/AwesomePlayer(  251): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  251): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  251): mAudioTrackVector clear
V/AwesomePlayer(  251): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  251): mSecMediaClock clear
V/AwesomePlayer(  251): destructor
V/AwesomePlayer(  251): reset_l()
V/AwesomePlayer(  251): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  251): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  251): mAudioTrackVector clear
V/AwesomePlayer(  251): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  251): mSecMediaClock clear
V/MediaPlayer( 4386): decode(68, 30372876, 21552)
V/MediaPlayerService(  251): decode(33, 30372876, 21552)
V/MediaPlayerService(  251): player type = 3
V/AwesomePlayer(  251): setDefault
V/AwesomePlayer(  251): constructor
V/AwesomePlayer(  251): setDefault
V/AwesomePlayer(  251): reset_l()
V/AwesomePlayer(  251): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  251): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  251): mAudioTrackVector clear
V/AwesomePlayer(  251): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  251): mSecMediaClock clear
V/StagefrightPlayer(  251): StagefrightPlayer
V/AwesomePlayer(  251): setListener
V/StagefrightPlayer(  251): initCheck
V/AwesomePlayer(  251): setAudioSink
V/StagefrightPlayer(  251): setDataSource(33, 30372876, 21552)
V/AwesomePlayer(  251): reset_l()
V/AwesomePlayer(  251): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  251): notify(0xb7445e20, 8, 0, 0)
V/AudioCache(  251): ignored
V/AwesomePlayer(  251): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  251): mAudioTrackVector clear
V/AwesomePlayer(  251): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  251): mSecMediaClock clear
V/AwesomePlayer(  251): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer(  251): mBitrate = -1 bits/sec
V/AwesomePlayer(  251): current audio track index (0) is added to vector
V/AwesomePlayer(  251): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer(  251): AwesomePlayer::setDataSource_l():: This is not a DRM content
V/MediaPlayerService(  251): prepare
V/AwesomePlayer(  251): prepareAsync
V/MediaPlayerService(  251): wait for prepare
V/AwesomePlayer(  251): onPrepareAsyncEvent
I/SecMediaClock(  251): SecMediaClock constructor
I/SecMediaClock(  251): reset
V/AwesomePlayer(  251): initAudioDecoder
V/AwesomePlayer(  251): checkOffloadExceptions is true
I/OMXCodec(  251): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
I/OMX     (  251): mDispatchers.add
I/OMXCodec(  251): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec(  251): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec(  251): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec(  251): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/OMXCodec(  251): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer(  251): finishAsyncPrepare_l
V/AwesomePlayer(  251): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache(  251): notify(0xb7445e20, 200, 973, 0)
V/AudioCache(  251): ignored
V/AwesomePlayer(  251): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  251): notify(0xb7445e20, 5, 0, 0)
V/AudioCache(  251): ignored
V/AwesomePlayer(  251): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  251): notify(0xb7445e20, 1, 0, 0)
V/AudioCache(  251): prepared
V/AudioCache(  251): wait - success
V/MediaPlayerService(  251): start
V/StagefrightPlayer(  251): start
V/AwesomePlayer(  251): play
V/AwesomePlayer(  251): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer(  251): startAudioPlayer_l, sendErrorNotification (0)
I/OMXCodec(  251): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec(  251): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec(  251): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/AudioPlayer(  251):  Audioplayer kKeyAudioPCMFormat:1, 2, 0
I/AudioPlayer(  251):  Audioplayer kKeyAudioPCMFormat read fail(2, 1)
V/AudioCache(  251): open(44100, 2, 0x0, 1, 4)
V/AwesomePlayer(  251): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache(  251): notify(0xb7445e20, 6, 0, 0)
V/AudioCache(  251): ignored
V/AwesomePlayer(  251): addBatteryData
V/MediaPlayerService(  251): wait for playback complete
I/AudioPlayer(  251): First fillBuffer call!!
I/OMXCodec(  251): [OMX.google.vorbis.decoder] End Of Stream
V/AwesomePlayer(  251): postAudioEOS delayUs (0)
V/AwesomePlayer(  251): onCheckAudioStatus
V/AwesomePlayer(  251): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  251): onStreamDone
V/AwesomePlayer(  251): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  251): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  251): notify(0xb7445e20, 2, 0, 0)
V/AudioCache(  251): playback complete - thread will wake up later
V/AwesomePlayer(  251): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  251): notify(0xb7445e20, 7, 0, 0)
V/AudioCache(  251): ignored
V/AwesomePlayer(  251): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer(  251): addBatteryData
V/AudioCache(  251): wait - success
V/StagefrightPlayer(  251): reset
V/AwesomePlayer(  251): reset_l()
V/AwesomePlayer(  251): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  251): notify(0xb7445e20, 8, 0, 0)
V/AudioCache(  251): ignored
V/AwesomePlayer(  251): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  251): mAudioTrackVector clear
I/OMXCodec(  251): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec(  251): [OMX.google.vorbis.decoder] stop() sendCommand(0x3d, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec(  251): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
I/OMXCodec(  251): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/OMX     (  251): instance freeNode
I/AudioPlayer(  251): reset out
V/AwesomePlayer(  251): reset_l() mAudioPlayer successfully deleted
I/SecMediaClock(  251): SecMediaClock destructor
V/AwesomePlayer(  251): mSecMediaClock clear
V/StagefrightPlayer(  251): ~StagefrightPlayer
V/StagefrightPlayer(  251): reset
V/AwesomePlayer(  251): reset_l()
V/AwesomePlayer(  251): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  251): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  251): mAudioTrackVector clear
V/AwesomePlayer(  251): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  251): mSecMediaClock clear
V/AwesomePlayer(  251): destructor
V/AwesomePlayer(  251): reset_l()
V/AwesomePlayer(  251): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  251): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  251): mAudioTrackVector clear
V/AwesomePlayer(  251): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  251): mSecMediaClock clear
V/MediaPlayer( 4386): decode(69, 37543652, 4230)
V/MediaPlayerService(  251): decode(33, 37543652, 4230)
V/MediaPlayerService(  251): player type = 3
V/AwesomePlayer(  251): setDefault
V/AwesomePlayer(  251): constructor
V/AwesomePlayer(  251): setDefault
V/AwesomePlayer(  251): reset_l()
V/AwesomePlayer(  251): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  251): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  251): mAudioTrackVector clear
V/AwesomePlayer(  251): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  251): mSecMediaClock clear
V/StagefrightPlayer(  251): StagefrightPlayer
V/AwesomePlayer(  251): setListener
V/StagefrightPlayer(  251): initCheck
V/AwesomePlayer(  251): setAudioSink
V/StagefrightPlayer(  251): setDataSource(33, 37543652, 4230)
V/AwesomePlayer(  251): reset_l()
V/AwesomePlayer(  251): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  251): notify(0xb743c3d0, 8, 0, 0)
V/AudioCache(  251): ignored
V/AwesomePlayer(  251): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  251): mAudioTrackVector clear
V/AwesomePlayer(  251): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  251): mSecMediaClock clear
V/AwesomePlayer(  251): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer(  251): mBitrate = -1 bits/sec
V/AwesomePlayer(  251): current audio track index (0) is added to vector
V/AwesomePlayer(  251): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer(  251): AwesomePlayer::setDataSource_l():: This is not a DRM content
V/MediaPlayerService(  251): prepare
V/AwesomePlayer(  251): prepareAsync
V/MediaPlayerService(  251): wait for prepare
V/AwesomePlayer(  251): onPrepareAsyncEvent
I/SecMediaClock(  251): SecMediaClock constructor
I/SecMediaClock(  251): reset
V/AwesomePlayer(  251): initAudioDecoder
V/AwesomePlayer(  251): checkOffloadExceptions is true
I/OMXCodec(  251): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
I/OMX     (  251): mDispatchers.add
I/OMXCodec(  251): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec(  251): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec(  251): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec(  251): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/OMXCodec(  251): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer(  251): finishAsyncPrepare_l
V/AwesomePlayer(  251): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache(  251): notify(0xb743c3d0, 200, 973, 0)
V/AudioCache(  251): ignored
V/AwesomePlayer(  251): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  251): notify(0xb743c3d0, 5, 0, 0)
V/AudioCache(  251): ignored
V/AwesomePlayer(  251): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  251): notify(0xb743c3d0, 1, 0, 0)
V/AudioCache(  251): prepared
V/AudioCache(  251): wait - success
V/MediaPlayerService(  251): start
,V/StagefrightPlayer(  251): start
V/AwesomePlayer(  251): play
V/AwesomePlayer(  251): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer(  251): startAudioPlayer_l, sendErrorNotification (0)
I/OMXCodec(  251): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec(  251): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec(  251): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/OMXCodec(  251): [OMX.google.vorbis.decoder] End Of Stream
I/AudioPlayer(  251):  Audioplayer kKeyAudioPCMFormat:1, 1, 0
I/AudioPlayer(  251):  Audioplayer kKeyAudioPCMFormat read fail(1, 1)
V/AudioCache(  251): open(44100, 1, 0x0, 1, 4)
V/AwesomePlayer(  251): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache(  251): notify(0xb743c3d0, 6, 0, 0)
V/AudioCache(  251): ignored
V/AwesomePlayer(  251): addBatteryData
V/MediaPlayerService(  251): wait for playback complete
V/AwesomePlayer(  251): postAudioEOS delayUs (0)
V/AwesomePlayer(  251): onCheckAudioStatus
V/AwesomePlayer(  251): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  251): onStreamDone
V/AwesomePlayer(  251): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  251): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  251): notify(0xb743c3d0, 2, 0, 0)
V/AudioCache(  251): playback complete - thread will wake up later
V/AwesomePlayer(  251): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  251): notify(0xb743c3d0, 7, 0, 0)
V/AudioCache(  251): ignored
V/AwesomePlayer(  251): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer(  251): addBatteryData
V/AudioCache(  251): wait - success
V/StagefrightPlayer(  251): reset
V/AwesomePlayer(  251): reset_l()
V/AwesomePlayer(  251): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  251): notify(0xb743c3d0, 8, 0, 0)
V/AudioCache(  251): ignored
V/AwesomePlayer(  251): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  251): mAudioTrackVector clear
I/OMXCodec(  251): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec(  251): [OMX.google.vorbis.decoder] stop() sendCommand(0x3e, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec(  251): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
I/OMXCodec(  251): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/OMX     (  251): instance freeNode
I/AudioPlayer(  251): reset out
V/AwesomePlayer(  251): reset_l() mAudioPlayer successfully deleted
I/SecMediaClock(  251): SecMediaClock destructor
V/AwesomePlayer(  251): mSecMediaClock clear
V/StagefrightPlayer(  251): ~StagefrightPlayer
V/StagefrightPlayer(  251): reset
V/AwesomePlayer(  251): reset_l()
V/AwesomePlayer(  251): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  251): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  251): mAudioTrackVector clear
V/AwesomePlayer(  251): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  251): mSecMediaClock clear
V/AwesomePlayer(  251): destructor
V/AwesomePlayer(  251): reset_l()
V/AwesomePlayer(  251): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  251): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  251): mAudioTrackVector clear
V/AwesomePlayer(  251): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  251): mSecMediaClock clear
V/MediaPlayer( 4386): decode(70, 30337076, 9400)
V/MediaPlayerService(  251): decode(33, 30337076, 9400)
V/MediaPlayerService(  251): player type = 3
V/AwesomePlayer(  251): setDefault
V/AwesomePlayer(  251): constructor
V/AwesomePlayer(  251): setDefault
V/AwesomePlayer(  251): reset_l()
V/AwesomePlayer(  251): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  251): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  251): mAudioTrackVector clear
V/AwesomePlayer(  251): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  251): mSecMediaClock clear
V/StagefrightPlayer(  251): StagefrightPlayer
V/AwesomePlayer(  251): setListener
V/StagefrightPlayer(  251): initCheck
V/AwesomePlayer(  251): setAudioSink
V/StagefrightPlayer(  251): setDataSource(33, 30337076, 9400)
V/AwesomePlayer(  251): reset_l()
V/AwesomePlayer(  251): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  251): notify(0xb7438968, 8, 0, 0)
V/AudioCache(  251): ignored
V/AwesomePlayer(  251): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  251): mAudioTrackVector clear
V/AwesomePlayer(  251): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  251): mSecMediaClock clear
V/AwesomePlayer(  251): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer(  251): mBitrate = -1 bits/sec
V/AwesomePlayer(  251): current audio track index (0) is added to vector
V/AwesomePlayer(  251): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer(  251): AwesomePlayer::setDataSource_l():: This is not a DRM content
V/MediaPlayerService(  251): prepare
V/AwesomePlayer(  251): prepareAsync
V/MediaPlayerService(  251): wait for prepare
V/AwesomePlayer(  251): onPrepareAsyncEvent
I/SecMediaClock(  251): SecMediaClock constructor
I/SecMediaClock(  251): reset
V/AwesomePlayer(  251): initAudioDecoder
V/AwesomePlayer(  251): checkOffloadExceptions is true
I/OMXCodec(  251): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
I/OMX     (  251): mDispatchers.add
I/OMXCodec(  251): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec(  251): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec(  251): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec(  251): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/OMXCodec(  251): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer(  251): finishAsyncPrepare_l
V/AwesomePlayer(  251): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache(  251): notify(0xb7438968, 200, 973, 0)
V/AudioCache(  251): ignored
V/AwesomePlayer(  251): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  251): notify(0xb7438968, 5, 0, 0)
V/AudioCache(  251): ignored
V/AwesomePlayer(  251): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  251): notify(0xb7438968, 1, 0, 0)
V/AudioCache(  251): prepared
V/AudioCache(  251): wait - success
V/MediaPlayerService(  251): start
V/StagefrightPlayer(  251): start
V/AwesomePlayer(  251): play
V/AwesomePlayer(  251): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer(  251): startAudioPlayer_l, sendErrorNotification (0)
E/memtrack( 4406): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 4406): failed to load memtrack module: -2
I/OMXCodec(  251): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec(  251): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec(  251): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/AudioPlayer(  251):  Audioplayer kKeyAudioPCMFormat:1, 1, 0
I/AudioPlayer(  251):  Audioplayer kKeyAudioPCMFormat read fail(1, 1)
V/AudioCache(  251): open(44100, 1, 0x0, 1, 4)
V/AwesomePlayer(  251): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache(  251): notify(0xb7438968, 6, 0, 0)
V/AudioCache(  251): ignored
V/AwesomePlayer(  251): addBatteryData
V/MediaPlayerService(  251): wait for playback complete
I/ActivityManager(  732): Killing 3077:com.sec.android.app.mt/1000 (adj 15): empty #43
I/SELinux ( 4479): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 4479):  
D/dalvikvm( 4406): Note: class Landroid/app/ActivityManagerNative; has 192 unimplemented (abstract) methods
I/OMXCodec(  251): [OMX.google.vorbis.decoder] End Of Stream
V/AwesomePlayer(  251): postAudioEOS delayUs (0)
V/AwesomePlayer(  251): onCheckAudioStatus
V/AwesomePlayer(  251): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  251): onStreamDone
V/AwesomePlayer(  251): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  251): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  251): notify(0xb7438968, 2, 0, 0)
V/AudioCache(  251): playback complete - thread will wake up later
V/AwesomePlayer(  251): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  251): notify(0xb7438968, 7, 0, 0)
V/AudioCache(  251): ignored
V/AwesomePlayer(  251): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer(  251): addBatteryData
V/AudioCache(  251): wait - success
V/StagefrightPlayer(  251): reset
V/AwesomePlayer(  251): reset_l()
V/AwesomePlayer(  251): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  251): notify(0xb7438968, 8, 0, 0)
V/AudioCache(  251): ignored
V/AwesomePlayer(  251): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  251): mAudioTrackVector clear
I/OMXCodec(  251): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec(  251): [OMX.google.vorbis.decoder] stop() sendCommand(0x3f, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec(  251): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
I/OMXCodec(  251): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/OMX     (  251): instance freeNode
I/AudioPlayer(  251): reset out
V/AwesomePlayer(  251): reset_l() mAudioPlayer successfully deleted
I/SecMediaClock(  251): SecMediaClock destructor
V/AwesomePlayer(  251): mSecMediaClock clear
V/StagefrightPlayer(  251): ~StagefrightPlayer
V/StagefrightPlayer(  251): reset
V/AwesomePlayer(  251): reset_l()
V/AwesomePlayer(  251): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  251): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  251): mAudioTrackVector clear
V/AwesomePlayer(  251): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  251): mSecMediaClock clear
V/AwesomePlayer(  251): destructor
V/AwesomePlayer(  251): reset_l()
V/AwesomePlayer(  251): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  251): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  251): mAudioTrackVector clear
V/AwesomePlayer(  251): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  251): mSecMediaClock clear
V/MediaPlayer( 4386): decode(71, 33925464, 44276)
V/MediaPlayerService(  251): decode(33, 33925464, 44276)
V/MediaPlayerService(  251): player type = 3
V/AwesomePlayer(  251): setDefault
V/AwesomePlayer(  251): constructor
V/AwesomePlayer(  251): setDefault
V/AwesomePlayer(  251): reset_l()
V/AwesomePlayer(  251): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  251): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  251): mAudioTrackVector clear
V/AwesomePlayer(  251): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  251): mSecMediaClock clear
V/StagefrightPlayer(  251): StagefrightPlayer
V/AwesomePlayer(  251): setListener
V/StagefrightPlayer(  251): initCheck
V/AwesomePlayer(  251): setAudioSink
V/StagefrightPlayer(  251): setDataSource(33, 33925464, 44276)
V/AwesomePlayer(  251): reset_l()
V/AwesomePlayer(  251): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  251): notify(0xb7445a60, 8, 0, 0)
V/AudioCache(  251): ignored
V/AwesomePlayer(  251): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  251): mAudioTrackVector clear
V/AwesomePlayer(  251): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  251): mSecMediaClock clear
I/SELinux ( 4479): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 4479):  
I/SELinux ( 4479):  
I/SELinux ( 4479): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 4479): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 4479): >>>>> Normal User
E/dalvikvm( 4479): >>>>> com.policydm [ userId:0 | appId:1000 ]
E/SELinux ( 4479): [DEBUG] seapp_context_lookup: seinfoCategory = platform
I/FileSource(  251): [Read time] time (12114) us > 10000 us, request_size (27), read_size (27)
V/AwesomePlayer(  251): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer(  251): mBitrate = -1 bits/sec
V/AwesomePlayer(  251): current audio track index (0) is added to vector
V/AwesomePlayer(  251): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer(  251): AwesomePlayer::setDataSource_l():: This is not a DRM content
V/MediaPlayerService(  251): prepare
V/AwesomePlayer(  251): prepareAsync
V/MediaPlayerService(  251): wait for prepare
V/AwesomePlayer(  251): onPrepareAsyncEvent
I/SecMediaClock(  251): SecMediaClock constructor
I/SecMediaClock(  251): reset
V/AwesomePlayer(  251): initAudioDecoder
V/AwesomePlayer(  251): checkOffloadExceptions is true
I/OMXCodec(  251): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
I/OMX     (  251): mDispatchers.add
I/OMXCodec(  251): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec(  251): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec(  251): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec(  251): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/OMXCodec(  251): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer(  251): finishAsyncPrepare_l
V/AwesomePlayer(  251): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache(  251): notify(0xb7445a60, 200, 973, 0)
V/AudioCache(  251): ignored
V/AwesomePlayer(  251): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  251): notify(0xb7445a60, 5, 0, 0)
V/AudioCache(  251): ignored
V/AwesomePlayer(  251): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  251): notify(0xb7445a60, 1, 0, 0)
V/AudioCache(  251): prepared
V/AudioCache(  251): wait - success
V/MediaPlayerService(  251): start
V/StagefrightPlayer(  251): start
V/AwesomePlayer(  251): play
V/AwesomePlayer(  251): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer(  251): startAudioPlayer_l, sendErrorNotification (0)
I/OMXCodec(  251): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec(  251): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec(  251): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/AudioPlayer(  251):  Audioplayer kKeyAudioPCMFormat:1, 2, 0
D/AndroidRuntime( 4406): Calling main entry com.android.commands.am.Am
I/AudioPlayer(  251):  Audioplayer kKeyAudioPCMFormat read fail(2, 1)
V/AudioCache(  251): open(44100, 2, 0x0, 1, 4)
V/AwesomePlayer(  251): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache(  251): notify(0xb7445a60, 6, 0, 0)
V/AudioCache(  251): ignored
V/AwesomePlayer(  251): addBatteryData
V/MediaPlayerService(  251): wait for playback complete
I/AudioPlayer(  251): First fillBuffer call!!
D/TimaKeyStoreProvider( 4479): in addTimaSignatureService
D/TimaKeyStoreProvider( 4479): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 4479): Added TimaKesytore provider
I/OMXCodec(  251): [OMX.google.vorbis.decoder] End Of Stream
V/AwesomePlayer(  251): postAudioEOS delayUs (0)
V/AwesomePlayer(  251): onCheckAudioStatus
V/AwesomePlayer(  251): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  251): onStreamDone
V/AwesomePlayer(  251): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  251): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  251): notify(0xb7445a60, 2, 0, 0)
V/AudioCache(  251): playback complete - thread will wake up later
V/AwesomePlayer(  251): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  251): notify(0xb7445a60, 7, 0, 0)
V/AudioCache(  251): ignored
V/AwesomePlayer(  251): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer(  251): addBatteryData
V/AudioCache(  251): wait - success
V/StagefrightPlayer(  251): reset
V/AwesomePlayer(  251): reset_l()
V/AwesomePlayer(  251): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  251): notify(0xb7445a60, 8, 0, 0)
V/AudioCache(  251): ignored
V/AwesomePlayer(  251): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  251): mAudioTrackVector clear
I/OMXCodec(  251): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec(  251): [OMX.google.vorbis.decoder] stop() sendCommand(0x40, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec(  251): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
I/OMXCodec(  251): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/OMX     (  251): instance freeNode
I/AudioPlayer(  251): reset out
V/AwesomePlayer(  251): reset_l() mAudioPlayer successfully deleted
I/SecMediaClock(  251): SecMediaClock destructor
V/AwesomePlayer(  251): mSecMediaClock clear
V/StagefrightPlayer(  251): ~StagefrightPlayer
V/StagefrightPlayer(  251): reset
V/AwesomePlayer(  251): reset_l()
V/AwesomePlayer(  251): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  251): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  251): mAudioTrackVector clear
V/AwesomePlayer(  251): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  251): mSecMediaClock clear
V/AwesomePlayer(  251): destructor
V/AwesomePlayer(  251): reset_l()
V/AwesomePlayer(  251): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  251): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  251): mAudioTrackVector clear
V/AwesomePlayer(  251): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  251): mSecMediaClock clear
V/MediaPlayer( 4386): decode(72, 33885672, 29256)
V/MediaPlayerService(  251): decode(33, 33885672, 29256)
V/MediaPlayerService(  251): player type = 3
V/AwesomePlayer(  251): setDefault
V/AwesomePlayer(  251): constructor
V/AwesomePlayer(  251): setDefault
V/AwesomePlayer(  251): reset_l()
V/AwesomePlayer(  251): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  251): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  251): mAudioTrackVector clear
V/AwesomePlayer(  251): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  251): mSecMediaClock clear
V/StagefrightPlayer(  251): StagefrightPlayer
V/AwesomePlayer(  251): setListener
V/StagefrightPlayer(  251): initCheck
V/AwesomePlayer(  251): setAudioSink
V/StagefrightPlayer(  251): setDataSource(33, 33885672, 29256)
V/AwesomePlayer(  251): reset_l()
V/AwesomePlayer(  251): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  251): notify(0xb743dc40, 8, 0, 0)
V/AudioCache(  251): ignored
V/AwesomePlayer(  251): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  251): mAudioTrackVector clear
V/AwesomePlayer(  251): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  251): mSecMediaClock clear
V/ApplicationPolicy(  732): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
V/AwesomePlayer(  251): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer(  251): mBitrate = -1 bits/sec
V/AwesomePlayer(  251): current audio track index (0) is added to vector
V/AwesomePlayer(  251): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer(  251): AwesomePlayer::setDataSource_l():: This is not a DRM content
V/MediaPlayerService(  251): prepare
V/AwesomePlayer(  251): prepareAsync
V/MediaPlayerService(  251): wait for prepare
V/AwesomePlayer(  251): onPrepareAsyncEvent
I/SecMediaClock(  251): SecMediaClock constructor
I/SecMediaClock(  251): reset
V/AwesomePlayer(  251): initAudioDecoder
V/AwesomePlayer(  251): checkOffloadExceptions is true
I/OMXCodec(  251): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
I/OMX     (  251): mDispatchers.add
I/OMXCodec(  251): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec(  251): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec(  251): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec(  251): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/OMXCodec(  251): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer(  251): finishAsyncPrepare_l
V/AwesomePlayer(  251): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache(  251): notify(0xb743dc40, 200, 973, 0)
V/AudioCache(  251): ignored
V/AwesomePlayer(  251): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  251): notify(0xb743dc40, 5, 0, 0)
V/AudioCache(  251): ignored
V/AwesomePlayer(  251): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  251): notify(0xb743dc40, 1, 0, 0)
V/AudioCache(  251): prepared
V/AudioCache(  251): wait - success
V/MediaPlayerService(  251): start
V/StagefrightPlayer(  251): start
V/AwesomePlayer(  251): play
V/AwesomePlayer(  251): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer(  251): startAudioPlayer_l, sendErrorNotification (0)
I/OMXCodec(  251): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec(  251): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec(  251): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
D/AmoledAdjustTimer(  732): prevTemp = 283, currTemp = 283, prevStep = 4, currStep = 4
D/CustomFrequencyManagerService(  732): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 732  pkgName : ACTIVITY_RESUME_BOOSTER@5
I/AudioPlayer(  251):  Audioplayer kKeyAudioPCMFormat:1, 2, 0
I/AudioPlayer(  251):  Audioplayer kKeyAudioPCMFormat read fail(2, 1)
V/AudioCache(  251): open(44100, 2, 0x0, 1, 4)
V/AwesomePlayer(  251): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache(  251): notify(0xb743dc40, 6, 0, 0)
V/AudioCache(  251): ignored
V/AwesomePlayer(  251): addBatteryData
V/MediaPlayerService(  251): wait for playback complete
W/ActivityManager(  732): mDVFSHelper.acquire()
I/SELinux ( 4501): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 4501):  
D/LockPatternUtils( 1065): isPcwEnable = null
D/AndroidRuntime( 4406): Shutting down VM
D/dalvikvm( 4406): GC_CONCURRENT freed 97K, 13% free 717K/816K, paused 0ms+0ms, total 3ms
I/OMXCodec(  251): [OMX.google.vorbis.decoder] End Of Stream
V/AwesomePlayer(  251): postAudioEOS delayUs (0)
D/dalvikvm(  249): GC_EXPLICIT freed 44K, 51% free 9506K/19028K, paused 2ms+3ms, total 32ms
V/AwesomePlayer(  251): onCheckAudioStatus
V/AwesomePlayer(  251): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  251): onStreamDone
V/AwesomePlayer(  251): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  251): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  251): notify(0xb743dc40, 2, 0, 0)
V/AudioCache(  251): playback complete - thread will wake up later
V/AwesomePlayer(  251): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  251): notify(0xb743dc40, 7, 0, 0)
V/AudioCache(  251): ignored
V/AwesomePlayer(  251): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer(  251): addBatteryData
V/AudioCache(  251): wait - success
V/StagefrightPlayer(  251): reset
I/SELinux ( 4501): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 4501):  
I/SELinux ( 4501):  
I/SELinux ( 4501): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 4501): [DEBUG] seapp_context_lookup: seinfoCategory = default
E/dalvikvm( 4501): >>>>> Normal User
E/dalvikvm( 4501): >>>>> com.test.thalitest [ userId:0 | appId:10179 ]
E/SELinux ( 4501): [DEBUG] seapp_context_lookup: seinfoCategory = default
V/AwesomePlayer(  251): reset_l()
V/AwesomePlayer(  251): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  251): notify(0xb743dc40, 8, 0, 0)
V/AudioCache(  251): ignored
V/AwesomePlayer(  251): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  251): mAudioTrackVector clear
I/OMXCodec(  251): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec(  251): [OMX.google.vorbis.decoder] stop() sendCommand(0x41, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec(  251): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
I/OMXCodec(  251): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/OMX     (  251): instance freeNode
I/AudioPlayer(  251): reset out
V/AwesomePlayer(  251): reset_l() mAudioPlayer successfully deleted
I/SecMediaClock(  251): SecMediaClock destructor
V/AwesomePlayer(  251): mSecMediaClock clear
V/StagefrightPlayer(  251): ~StagefrightPlayer
V/StagefrightPlayer(  251): reset
V/AwesomePlayer(  251): reset_l()
V/AwesomePlayer(  251): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  251): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  251): mAudioTrackVector clear
V/AwesomePlayer(  251): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  251): mSecMediaClock clear
V/AwesomePlayer(  251): destructor
V/AwesomePlayer(  251): reset_l()
V/AwesomePlayer(  251): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  251): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  251): mAudioTrackVector clear
V/AwesomePlayer(  251): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  251): mSecMediaClock clear
V/MediaPlayer( 4386): decode(73, 37491572, 52024)
V/MediaPlayerService(  251): decode(33, 37491572, 52024)
V/MediaPlayerService(  251): player type = 3
V/AwesomePlayer(  251): setDefault
V/AwesomePlayer(  251): constructor
V/AwesomePlayer(  251): setDefault
V/AwesomePlayer(  251): reset_l()
V/AwesomePlayer(  251): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  251): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  251): mAudioTrackVector clear
V/AwesomePlayer(  251): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  251): mSecMediaClock clear
V/StagefrightPlayer(  251): StagefrightPlayer
V/AwesomePlayer(  251): setListener
V/StagefrightPlayer(  251): initCheck
V/AwesomePlayer(  251): setAudioSink
V/StagefrightPlayer(  251): setDataSource(33, 37491572, 52024)
V/AwesomePlayer(  251): reset_l()
V/AwesomePlayer(  251): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  251): notify(0xb7446f48, 8, 0, 0)
V/AudioCache(  251): ignored
V/AwesomePlayer(  251): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  251): mAudioTrackVector clear
V/AwesomePlayer(  251): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  251): mSecMediaClock clear
V/AwesomePlayer(  251): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer(  251): mBitrate = -1 bits/sec
V/AwesomePlayer(  251): current audio track index (0) is added to vector
V/AwesomePlayer(  251): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer(  251): AwesomePlayer::setDataSource_l():: This is not a DRM content
V/MediaPlayerService(  251): prepare
V/AwesomePlayer(  251): prepareAsync
V/MediaPlayerService(  251): wait for prepare
V/AwesomePlayer(  251): onPrepareAsyncEvent
I/SecMediaClock(  251): SecMediaClock constructor
I/SecMediaClock(  251): reset
V/AwesomePlayer(  251): initAudioDecoder
V/AwesomePlayer(  251): checkOffloadExceptions is true
I/OMXCodec(  251): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
D/dalvikvm(  249): GC_EXPLICIT freed <1K, 51% free 9506K/19028K, paused 2ms+3ms, total 27ms
I/OMX     (  251): mDispatchers.add
I/OMXCodec(  251): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec(  251): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec(  251): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec(  251): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/OMXCodec(  251): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer(  251): finishAsyncPrepare_l
V/AwesomePlayer(  251): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache(  251): notify(0xb7446f48, 200, 973, 0)
V/AudioCache(  251): ignored
V/AwesomePlayer(  251): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  251): notify(0xb7446f48, 5, 0, 0)
V/AudioCache(  251): ignored
V/AwesomePlayer(  251): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  251): notify(0xb7446f48, 1, 0, 0)
V/AudioCache(  251): prepared
V/AudioCache(  251): wait - success
V/MediaPlayerService(  251): start
V/StagefrightPlayer(  251): start
V/AwesomePlayer(  251): play
V/AwesomePlayer(  251): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer(  251): startAudioPlayer_l, sendErrorNotification (0)
I/OMXCodec(  251): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec(  251): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec(  251): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/AudioPlayer(  251):  Audioplayer kKeyAudioPCMFormat:1, 2, 0
I/AudioPlayer(  251):  Audioplayer kKeyAudioPCMFormat read fail(2, 1)
V/AudioCache(  251): open(48000, 2, 0x0, 1, 4)
V/AwesomePlayer(  251): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache(  251): notify(0xb7446f48, 6, 0, 0)
V/AudioCache(  251): ignored
V/AwesomePlayer(  251): addBatteryData
V/MediaPlayerService(  251): wait for playback complete
D/dalvikvm(  249): GC_EXPLICIT freed <1K, 51% free 9506K/19028K, paused 2ms+2ms, total 22ms
D/TimaKeyStoreProvider( 4501): in addTimaSignatureService
D/TimaKeyStoreProvider( 4501): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 4501): Added TimaKesytore provider
D/SurfaceWidgetClient$ISurfaceWidgetStub( 1441): [237392/5] Surface widget visibility changed visibility = false on instance = 1
D/LockPatternUtils( 1065): isPcwEnable = null
I/SQLiteSecureOpenHelper( 2017): getWritableDatabase(pwd)
I/SQLiteSecureOpenHelper( 2017): getDatabaseLocked(b,b,pwd)...
I/OMXCodec(  251): [OMX.google.vorbis.decoder] End Of Stream
V/AwesomePlayer(  251): postAudioEOS delayUs (0)
V/AwesomePlayer(  251): onCheckAudioStatus
V/AwesomePlayer(  251): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  251): onStreamDone
V/AwesomePlayer(  251): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  251): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  251): notify(0xb7446f48, 2, 0, 0)
V/AudioCache(  251): playback complete - thread will wake up later
V/AwesomePlayer(  251): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  251): notify(0xb7446f48, 7, 0, 0)
V/AudioCache(  251): ignored
V/AwesomePlayer(  251): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer(  251): addBatteryData
V/AudioCache(  251): wait - success
V/StagefrightPlayer(  251): reset
V/AwesomePlayer(  251): reset_l()
V/AwesomePlayer(  251): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  251): notify(0xb7446f48, 8, 0, 0)
V/AudioCache(  251): ignored
V/AwesomePlayer(  251): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  251): mAudioTrackVector clear
I/OMXCodec(  251): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec(  251): [OMX.google.vorbis.decoder] stop() sendCommand(0x42, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec(  251): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
I/OMXCodec(  251): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/OMX     (  251): instance freeNode
I/AudioPlayer(  251): reset out
V/AwesomePlayer(  251): reset_l() mAudioPlayer successfully deleted
I/SecMediaClock(  251): SecMediaClock destructor
V/AwesomePlayer(  251): mSecMediaClock clear
V/StagefrightPlayer(  251): ~StagefrightPlayer
V/StagefrightPlayer(  251): reset
V/AwesomePlayer(  251): reset_l()
V/AwesomePlayer(  251): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  251): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  251): mAudioTrackVector clear
V/AwesomePlayer(  251): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  251): mSecMediaClock clear
V/AwesomePlayer(  251): destructor
V/AwesomePlayer(  251): reset_l()
V/AwesomePlayer(  251): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  251): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  251): mAudioTrackVector clear
V/AwesomePlayer(  251): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  251): mSecMediaClock clear
V/MediaPlayer( 4386): decode(74, 33969800, 9226)
V/MediaPlayerService(  251): decode(33, 33969800, 9226)
V/MediaPlayerService(  251): player type = 3
V/AwesomePlayer(  251): setDefault
V/AwesomePlayer(  251): constructor
V/AwesomePlayer(  251): setDefault
V/AwesomePlayer(  251): reset_l()
V/AwesomePlayer(  251): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  251): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  251): mAudioTrackVector clear
V/AwesomePlayer(  251): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  251): mSecMediaClock clear
V/StagefrightPlayer(  251): StagefrightPlayer
V/AwesomePlayer(  251): setListener
V/StagefrightPlayer(  251): initCheck
V/AwesomePlayer(  251): setAudioSink
V/StagefrightPlayer(  251): setDataSource(33, 33969800, 9226)
V/AwesomePlayer(  251): reset_l()
V/AwesomePlayer(  251): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  251): notify(0xb74393e0, 8, 0, 0)
V/AudioCache(  251): ignored
V/AwesomePlayer(  251): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  251): mAudioTrackVector clear
V/AwesomePlayer(  251): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  251): mSecMediaClock clear
V/AwesomePlayer(  251): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer(  251): mBitrate = -1 bits/sec
V/AwesomePlayer(  251): current audio track index (0) is added to vector
V/AwesomePlayer(  251): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer(  251): AwesomePlayer::setDataSource_l():: This is not a DRM content
V/MediaPlayerService(  251): prepare
V/AwesomePlayer(  251): prepareAsync
V/MediaPlayerService(  251): wait for prepare
V/AwesomePlayer(  251): onPrepareAsyncEvent
I/SecMediaClock(  251): SecMediaClock constructor
I/SecMediaClock(  251): reset
V/AwesomePlayer(  251): initAudioDecoder
V/AwesomePlayer(  251): checkOffloadExceptions is true
I/OMXCodec(  251): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
I/OMX     (  251): mDispatchers.add
I/OMXCodec(  251): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec(  251): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec(  251): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec(  251): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
D/SurfaceWidgetView( 1241): destroyHardwareResources():1126362448
I/OMXCodec(  251): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer(  251): finishAsyncPrepare_l
V/AwesomePlayer(  251): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache(  251): notify(0xb74393e0, 200, 973, 0)
V/AudioCache(  251): ignored
V/AwesomePlayer(  251): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  251): notify(0xb74393e0, 5, 0, 0)
V/AudioCache(  251): ignored
V/AwesomePlayer(  251): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  251): notify(0xb74393e0, 1, 0, 0)
V/AudioCache(  251): prepared
V/AudioCache(  251): wait - success
V/MediaPlayerService(  251): start
V/StagefrightPlayer(  251): start
V/AwesomePlayer(  251): play
V/AwesomePlayer(  251): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer(  251): startAudioPlayer_l, sendErrorNotification (0)
I/SurfaceFlinger(  248): id=13 Removed CatteryCove (8/12)
I/OMXCodec(  251): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec(  251): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec(  251): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/SurfaceFlinger(  248): id=13 Removed CatteryCove (-2/12)
I/AudioPlayer(  251):  Audioplayer kKeyAudioPCMFormat:1, 2, 0
I/AudioPlayer(  251):  Audioplayer kKeyAudioPCMFormat read fail(2, 1)
V/AudioCache(  251): open(44100, 2, 0x0, 1, 4)
V/AwesomePlayer(  251): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache(  251): notify(0xb74393e0, 6, 0, 0)
V/AudioCache(  251): ignored
V/AwesomePlayer(  251): addBatteryData
V/MediaPlayerService(  251): wait for playback complete
D/KeyguardUpdateMonitor( 1065): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1065): handleKeyguardVisibilityChanged(1)
I/OMXCodec(  251): [OMX.google.vorbis.decoder] End Of Stream
V/AwesomePlayer(  251): postAudioEOS delayUs (0)
V/AwesomePlayer(  251): onCheckAudioStatus
V/AwesomePlayer(  251): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  251): onStreamDone
V/AwesomePlayer(  251): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  251): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  251): notify(0xb74393e0, 2, 0, 0)
V/AudioCache(  251): playback complete - thread will wake up later
V/AwesomePlayer(  251): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  251): notify(0xb74393e0, 7, 0, 0)
V/AudioCache(  251): ignored
V/AwesomePlayer(  251): cancelPlayerEvents (keepNotifications=1)
W/ActivityManager(  732): Permission Denial: getCurrentUser() from pid=4501, uid=10179 requires android.permission.INTERACT_ACROSS_USERS
V/AwesomePlayer(  251): addBatteryData
V/AudioCache(  251): wait - success
V/StagefrightPlayer(  251): reset
V/AwesomePlayer(  251): reset_l()
V/AwesomePlayer(  251): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  251): notify(0xb74393e0, 8, 0, 0)
V/AudioCache(  251): ignored
V/AwesomePlayer(  251): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  251): mAudioTrackVector clear
I/OMXCodec(  251): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec(  251): [OMX.google.vorbis.decoder] stop() sendCommand(0x43, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec(  251): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
I/OMXCodec(  251): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/OMX     (  251): instance freeNode
I/AudioPlayer(  251): reset out
V/AwesomePlayer(  251): reset_l() mAudioPlayer successfully deleted
I/SecMediaClock(  251): SecMediaClock destructor
V/AwesomePlayer(  251): mSecMediaClock clear
V/StagefrightPlayer(  251): ~StagefrightPlayer
V/StagefrightPlayer(  251): reset
V/AwesomePlayer(  251): reset_l()
V/AwesomePlayer(  251): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  251): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  251): mAudioTrackVector clear
V/AwesomePlayer(  251): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  251): mSecMediaClock clear
V/AwesomePlayer(  251): destructor
V/AwesomePlayer(  251): reset_l()
V/AwesomePlayer(  251): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  251): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  251): mAudioTrackVector clear
V/AwesomePlayer(  251): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  251): mSecMediaClock clear
V/MediaPlayer( 4386): decode(75, 30402580, 4509)
V/MediaPlayerService(  251): decode(33, 30402580, 4509)
V/MediaPlayerService(  251): player type = 3
V/AwesomePlayer(  251): setDefault
V/AwesomePlayer(  251): constructor
V/AwesomePlayer(  251): setDefault
V/AwesomePlayer(  251): reset_l()
V/AwesomePlayer(  251): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  251): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  251): mAudioTrackVector clear
V/AwesomePlayer(  251): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  251): mSecMediaClock clear
V/StagefrightPlayer(  251): StagefrightPlayer
V/AwesomePlayer(  251): setListener
V/StagefrightPlayer(  251): initCheck
V/AwesomePlayer(  251): setAudioSink
V/StagefrightPlayer(  251): setDataSource(33, 30402580, 4509)
V/AwesomePlayer(  251): reset_l()
V/AwesomePlayer(  251): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  251): notify(0xb7435658, 8, 0, 0)
V/AudioCache(  251): ignored
V/AwesomePlayer(  251): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  251): mAudioTrackVector clear
V/AwesomePlayer(  251): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  251): mSecMediaClock clear
V/AwesomePlayer(  251): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer(  251): mBitrate = -1 bits/sec
V/AwesomePlayer(  251): current audio track index (0) is added to vector
V/AwesomePlayer(  251): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer(  251): AwesomePlayer::setDataSource_l():: This is not a DRM content
V/MediaPlayerService(  251): prepare
V/AwesomePlayer(  251): prepareAsync
V/MediaPlayerService(  251): wait for prepare
V/AwesomePlayer(  251): onPrepareAsyncEvent
I/SecMediaClock(  251): SecMediaClock constructor
I/SecMediaClock(  251): reset
V/AwesomePlayer(  251): initAudioDecoder
V/AwesomePlayer(  251): checkOffloadExceptions is true
I/OMXCodec(  251): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
I/OMX     (  251): mDispatchers.add
I/OMXCodec(  251): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec(  251): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec(  251): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
W/ActivityManager(  732): Permission Denial: getCurrentUser() from pid=4501, uid=10179 requires android.permission.INTERACT_ACROSS_USERS
I/OMXCodec(  251): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/OMXCodec(  251): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer(  251): finishAsyncPrepare_l
V/AwesomePlayer(  251): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache(  251): notify(0xb7435658, 200, 973, 0)
V/AudioCache(  251): ignored
V/AwesomePlayer(  251): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  251): notify(0xb7435658, 5, 0, 0)
V/AudioCache(  251): ignored
V/AwesomePlayer(  251): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  251): notify(0xb7435658, 1, 0, 0)
V/AudioCache(  251): prepared
V/AudioCache(  251): wait - success
V/MediaPlayerService(  251): start
V/StagefrightPlayer(  251): start
V/AwesomePlayer(  251): play
V/AwesomePlayer(  251): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer(  251): startAudioPlayer_l, sendErrorNotification (0)
I/OMXCodec(  251): [OMX.google.vorbis.decoder] End Of Stream
I/OMXCodec(  251): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec(  251): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec(  251): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/AudioPlayer(  251):  Audioplayer kKeyAudioPCMFormat:1, 2, 0
I/AudioPlayer(  251):  Audioplayer kKeyAudioPCMFormat read fail(2, 1)
V/AudioCache(  251): open(44100, 2, 0x0, 1, 4)
V/AwesomePlayer(  251): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache(  251): notify(0xb7435658, 6, 0, 0)
V/AudioCache(  251): ignored
V/AwesomePlayer(  251): addBatteryData
V/MediaPlayerService(  251): wait for playback complete
I/AudioPlayer(  251): First fillBuffer call!!
V/AwesomePlayer(  251): postAudioEOS delayUs (0)
V/AwesomePlayer(  251): onCheckAudioStatus
V/AwesomePlayer(  251): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  251): onStreamDone
V/AwesomePlayer(  251): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  251): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  251): notify(0xb7435658, 2, 0, 0)
V/AudioCache(  251): playback complete - thread will wake up later
V/AwesomePlayer(  251): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  251): notify(0xb7435658, 7, 0, 0)
V/AudioCache(  251): ignored
V/AwesomePlayer(  251): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer(  251): addBatteryData
V/AudioCache(  251): wait - success
V/StagefrightPlayer(  251): reset
V/AwesomePlayer(  251): reset_l()
V/AwesomePlayer(  251): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  251): notify(0xb7435658, 8, 0, 0)
V/AudioCache(  251): ignored
V/AwesomePlayer(  251): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  251): mAudioTrackVector clear
I/OMXCodec(  251): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec(  251): [OMX.google.vorbis.decoder] stop() sendCommand(0x44, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec(  251): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
I/OMXCodec(  251): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/OMX     (  251): instance freeNode
I/AudioPlayer(  251): reset out
V/AwesomePlayer(  251): reset_l() mAudioPlayer successfully deleted
I/SecMediaClock(  251): SecMediaClock destructor
V/AwesomePlayer(  251): mSecMediaClock clear
V/StagefrightPlayer(  251): ~StagefrightPlayer
V/StagefrightPlayer(  251): reset
V/AwesomePlayer(  251): reset_l()
V/AwesomePlayer(  251): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  251): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  251): mAudioTrackVector clear
V/AwesomePlayer(  251): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  251): mSecMediaClock clear
V/AwesomePlayer(  251): destructor
V/AwesomePlayer(  251): reset_l()
V/AwesomePlayer(  251): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  251): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  251): mAudioTrackVector clear
V/AwesomePlayer(  251): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  251): mSecMediaClock clear
V/WebViewChromium( 4501): Binding Chromium to the background looper Looper (main, tid 1) {423075f8}
I/chromium( 4501): [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserProcessMain( 4501): Initializing chromium process, renderers=0
W/chromium( 4501): [WARNING:proxy_service.cc(888)] PAC support disabled because there is no system implementation
I/SELinux ( 4541): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 4541):  
I/ActivityManager(  732): Killing 3132:com.sec.android.app.camera/u0a147 (adj 15): empty #43
I/SELinux ( 4541): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 4541):  
I/SELinux ( 4541):  
I/SELinux ( 4541): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 4541): [DEBUG] seapp_context_lookup: seinfoCategory = default
E/dalvikvm( 4541): >>>>> Normal User
E/dalvikvm( 4541): >>>>> com.osp.app.signin [ userId:0 | appId:10043 ]
E/SELinux ( 4541): [DEBUG] seapp_context_lookup: seinfoCategory = default
D/TimaKeyStoreProvider( 4541): in addTimaSignatureService
D/TimaKeyStoreProvider( 4541): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 4541): Added TimaKesytore provider
I/SA      ( 4541): [SSP] onCreated
I/SA      ( 4541): [TPM] There is no property file
I/SA      ( 4541): [SCU] isHaveSA() - false
I/SA      ( 4541): [TPM] getModelProperty : null
I/SA      ( 4541): [TPM] getCSCProperty : null
I/SA      ( 4541): [PMR] Received action : android.intent.action.PACKAGE_ADDED
I/SA      ( 4541): [DM] init START
I/SA      ( 4541): [DM] This device is not a Vodafone
I/SA      ( 4541): [DM] getCountryCodeFromCSC : PL
I/SA      ( 4541): support phone number id : false
I/SA      ( 4541): [DM] init END
I/SA      ( 4541): [SUR] onReceive log=[SA = 2.0.0117 V = 19 HWD = 1280X720 2.0 dpi = 320  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = kmini3g P = kmini3gxx I = KOT49H M = SM-G800H OKLEFT false DIS KOT49H.G800HXXU1ANK2 PSS = 4.497045606779314  ]
I/SA      ( 4541): [SUR] onReceive Intent=[ action.PACKAGE_ADDED. package ]
I/ActivityManager(  732): Killing 3220:com.android.email/u0a155 (adj 15): empty #43
D/Mms/PackageInstallReceiver( 3713): loadAuthorityPref(): sEnableAuthority = true
I/IcingCorporaProvider( 2121): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
W/ContextImpl( 2812): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1857 android.content.ContextWrapper.startService:506 android.content.ContextWrapper.startService:506 com.samsung.android.app.assistantmenu.AssistantMenuReceiver.onReceive:153 android.app.ActivityThread.handleReceiver:2698 
I/SELinux ( 4560): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 4560):  
I/SELinux ( 4560): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 4560):  
I/SELinux ( 4560):  
I/SELinux ( 4560): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 4560): [DEBUG] seapp_context_lookup: seinfoCategory = samsung
E/dalvikvm( 4560): >>>>> Normal User
E/dalvikvm( 4560): >>>>> com.sec.android.service.cm [ userId:0 | appId:10078 ]
E/SELinux ( 4560): [DEBUG] seapp_context_lookup: seinfoCategory = samsung
D/TimaKeyStoreProvider( 4560): in addTimaSignatureService
D/TimaKeyStoreProvider( 4560): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 4560): Added TimaKesytore provider
I/IcingCorporaProvider( 2121): UpdateCorporaTask done [took 106 ms] updated apps [took 106 ms] 
I/Adreno-EGL( 4501): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 4501): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 4501): Build Date: 03/21/14 Fri
I/Adreno-EGL( 4501): Local Branch: AU200+patches_03212014
I/Adreno-EGL( 4501): Remote Branch: 
I/Adreno-EGL( 4501): Local Patches: 
I/Adreno-EGL( 4501): Reconstruct Branch: 
I/SurfaceFlinger(  248): id=7 Removed Mauncher (7/11)
I/SurfaceFlinger(  248): id=7 Removed Mauncher (-2/11)
I/SecureStorage(  295): [INFO]: SPID(0x00000003)Secure Storage Daemon finished processing with result: 0
I/SecureStorage(  295): [INFO]: SPID(0x00000003)PID: 4414, TID: 4414
D/KeyguardUpdateMonitor( 1065): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1065): handleKeyguardVisibilityChanged(1)
E/SMD     (  242): DCD ON
D/Launcher( 1241): onTrimMemory. Level: 20
W/ActivityManager(  732): Permission Denial: getCurrentUser() from pid=4560, uid=10078 requires android.permission.INTERACT_ACROSS_USERS
D/CapabilityManagerService New( 4560): Receiver Broadcast:android.intent.action.PACKAGE_ADDED
I/SELinux ( 4573): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 4573):  
I/ActivityManager(  732): Killing 3216:com.samsung.android.provider.shootingmodeprovider/u0a162 (adj 15): empty #43
I/SecureStorage( 4414): [INFO]: SPID(0x00000000)Processing data has been completed
I/SecureStorage( 4414): [INFO]: SPID(0x00000000)WARNING! Failed to find SecureStorageExceptionJNI!..
I/SQLiteSecureOpenHelper( 4414): getWritableDatabase(pwd)
I/SQLiteSecureOpenHelper( 4414): getDatabaseLocked(b,b,pwd)...
I/SQLiteSecureOpenHelper( 4414): Open platform.db in secure mode
I/PowerManagerService(  732): [PWL] Off : 30s ago
I/SELinux ( 4573): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 4573):  
I/SELinux ( 4573):  
I/SELinux ( 4573): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 4573): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 4573): >>>>> Normal User
E/dalvikvm( 4573): >>>>> com.google.android.apps.docs [ userId:0 | appId:10090 ]
,E/SELinux ( 4573): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
I/dalvikvm( 4501): Could not find method android.webkit.CookieManager.setAcceptThirdPartyCookies, referenced from method org.apache.cordova.engine.SystemCookieManager.<init>
W/dalvikvm( 4501): VFY: unable to resolve virtual method 252: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
,D/dalvikvm( 4501): VFY: replacing opcode 0x6e at 0x0016
I/dalvikvm( 4501): Could not find method android.webkit.CookieManager.flush, referenced from method org.apache.cordova.engine.SystemCookieManager.flush
W/dalvikvm( 4501): VFY: unable to resolve virtual method 247: Landroid/webkit/CookieManager;.flush ()V
,D/dalvikvm( 4501): VFY: replacing opcode 0x6e at 0x0008
,W/dalvikvm( 4501): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 4501): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
I/dalvikvm( 4501): Could not find method android.webkit.WebViewClient.onReceivedClientCertRequest, referenced from method org.apache.cordova.engine.SystemWebViewClient.onReceivedClientCertRequest
W/dalvikvm( 4501): VFY: unable to resolve virtual method 305: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
,D/dalvikvm( 4501): VFY: replacing opcode 0x6f at 0x001a
,D/TimaKeyStoreProvider( 4573): in addTimaSignatureService
,W/dalvikvm( 4501): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
I/dalvikvm( 4501): Could not find method android.webkit.PermissionRequest.getResources, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onPermissionRequest
W/dalvikvm( 4501): VFY: unable to resolve virtual method 263: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
D/dalvikvm( 4501): VFY: replacing opcode 0x6e at 0x000d
I/dalvikvm( 4501): Could not find method android.webkit.WebChromeClient$FileChooserParams.createIntent, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onShowFileChooser
W/dalvikvm( 4501): VFY: unable to resolve virtual method 268: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
,D/dalvikvm( 4501): VFY: replacing opcode 0x6e at 0x0000
,D/TimaKeyStoreProvider( 4573): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 4573): Added TimaKesytore provider
,D/SystemWebViewEngine( 4501): CordovaWebView is running on device made by: samsung
,I/SQLiteSecureOpenHelper( 4414): ...getDatabaseLocked(b,b,pwd)
,D/SQLiteSecureOpenHelper( 4414): ...getDatabaseLocked(b,b,pwd)
,I/ActivityManager(  732): Killing 3242:com.sec.modem.settings/1000 (adj 15): empty #43
,V/AlarmManager(  732): waitForAlarm result :4
,I/SurfaceFlinger(  248): id=16 createSurf (1x1),1 flag=404, NainActivit
,D/KeyguardUpdateMonitor( 1065): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1065): handleKeyguardVisibilityChanged(1)
V/AlarmManager(  732): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,D/KeyguardUpdateMonitor( 1065): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1065): handleKeyguardVisibilityChanged(1)
,I/HWUI    ( 4501): EGLImpl-HWUI Protected EGL context created
,D/OpenGLRenderer( 4501): Enabling debug mode 0
D/BatteryService(  732): level:100, scale:100, status:5, health:2, present:true, voltage: 4366, temperature: 283, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:9, charge type:1, power sharing:false
D/BatteryService(  732): Sending ACTION_BATTERY_CHANGED.
D/BatteryService(  732): stay LED for fully charged
,D/UiModeManager(  732): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/OpenGLRenderer( 4501): GL error from OpenGLRenderer: 0x502
,E/OpenGLRenderer( 4501):   GL_INVALID_OPERATION
,D/KeyguardUpdateMonitor( 1065): sendKeyguardVisibilityChanged(true)
,D/SSRMv2:SIOP(  732): SIOP:: AP = 310, Delta = 0
,D/CustomFrequencyManagerService(  732): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 732  pkgName : ACTIVITY_RESUME_BOOSTER@9
D/CustomFrequencyManagerService(  732): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 732  tag : ACTIVITY_RESUME_BOOSTER@5
D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/CustomFrequencyManagerService(  732): FrequencyrequestList.getNextMaxCPUCoreRequest, index: 0
W/ActivityManager(  732): mDVFSHelper.release()
,D/KeyguardUpdateMonitor( 1065): handleKeyguardVisibilityChanged(1)
D/KeyguardUpdateMonitor( 1065): sendKeyguardVisibilityChanged(true)
D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/KeyguardUpdateMonitor( 1065): handleKeyguardVisibilityChanged(1)
D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
W/ActivityManager(  732): Permission Denial: getCurrentUser() from pid=4573, uid=10090 requires android.permission.INTERACT_ACROSS_USERS
,D/JsMessageQueue( 4501): Set native->JS mode to OnlineEventsBridgeMode
,D/dalvikvm( 4501): Trying to load lib /data/app-lib/com.test.thalitest-4/libjxcore.so 0x4262e428
,D/dalvikvm( 4501): Added shared lib /data/app-lib/com.test.thalitest-4/libjxcore.so 0x4262e428
,D/jxcore_app_log( 4501): JniHelper::setJavaVM(0x4175a528), pthread_self() = 2033795296
,I/SELinux ( 4607): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 4607):  
,I/chromium( 4501): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot call method 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
I/ActivityManager(  732): Killing 1335:com.sec.android.provider.badge/u0a72 (adj 15): empty #43
,W/GAV2    ( 4573): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,I/SELinux ( 4607): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 4607):  
I/SELinux ( 4607):  
,I/SELinux ( 4607): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 4607): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 4607): >>>>> Normal User
,E/dalvikvm( 4607): >>>>> com.samsung.android.app.watchmanagerstub [ userId:0 | appId:10100 ]
,E/SELinux ( 4607): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 4607): in addTimaSignatureService
,D/TimaKeyStoreProvider( 4607): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 4607): Added TimaKesytore provider
,D/PackageIntentReceiver( 4607): ACTION_PACKAGE_ADDED
,D/PackageIntentReceiver( 4607): Not GearManger package! 
,I/SELinux ( 4623): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 4623):  
,I/SELinux ( 4623): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 4623):  
I/SELinux ( 4623):  
,I/SELinux ( 4623): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 4623): [DEBUG] seapp_context_lookup: seinfoCategory = release
E/dalvikvm( 4623): >>>>> Normal User
,E/dalvikvm( 4623): >>>>> com.samsung.android.magazine.service [ userId:0 | appId:10106 ]
,E/SELinux ( 4623): [DEBUG] seapp_context_lookup: seinfoCategory = release
,D/TimaKeyStoreProvider( 4623): in addTimaSignatureService
,D/TimaKeyStoreProvider( 4623): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 4623): Added TimaKesytore provider
,D/dalvikvm( 4501): GC_CONCURRENT freed 4953K, 34% free 12734K/19028K, paused 2ms+2ms, total 29ms
,D/dalvikvm( 4501): WAIT_FOR_CONCURRENT_GC blocked 21ms
,D/dalvikvm( 4501): WAIT_FOR_CONCURRENT_GC blocked 20ms
,D/MagazineService Version( 4623): Magazine-Channel: 13
,D/MagazineService Version( 4623): Magazine-Provider: 13
,D/MagazineService Version( 4623): Magazine-Administrator: 11
,D/HeadlinesChannelApplication( 4623): [onCreate]
,D/MagazineService::MagazineBroadcastReceiver( 4623): [onReceive] android.intent.action.PACKAGE_ADDED com.test.thalitest
W/ActivityManager(  732): Permission Denial: getCurrentUser() from pid=4623, uid=10106 requires android.permission.INTERACT_ACROSS_USERS
,I/SELinux ( 4635): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 4635):  
I/MagazineService::MagazineService( 4623): [onHandleIntent] ACTION_PACKAGE_INSTALLED
,D/MagazineService::MagazineService( 4623): [onHandleIntent] Send broadcast to (com.test.thalitest).
I/ActivityManager(  732): Killing 3261:tv.peel.smartremote/u0a163 (adj 15): empty #43
,W/GAV2    ( 4573): Thread[main,5,main]: dispatch call queued.  Need to call GAServiceManager.getInstance().initialize().
I/ActivityManager(  732): Killing 3283:org.simalliance.openmobileapi.service/1101 (adj 15): empty #43
,I/SELinux ( 4635): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 4635):  
I/SELinux ( 4635):  
,I/SELinux ( 4635): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 4635): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 4635): >>>>> Normal User
,E/dalvikvm( 4635): >>>>> com.samsung.helphub [ userId:0 | appId:1000 ]
,E/SELinux ( 4635): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 4635): in addTimaSignatureService
,D/TimaKeyStoreProvider( 4635): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 4635): Added TimaKesytore provider
,I/SELinux ( 4650): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 4650):  
I/ActivityManager(  732): Killing 3339:com.sec.android.app.taskmanager/u0a166 (adj 15): empty #43
,D/CustomFrequencyManagerService(  732): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 732  tag : ACTIVITY_RESUME_BOOSTER@9
,I/SELinux ( 4650): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 4650):  
I/SELinux ( 4650):  
,I/SELinux ( 4650): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 4650): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 4650): >>>>> Normal User
,E/dalvikvm( 4650): >>>>> com.sec.kidsplat.installer [ userId:0 | appId:10158 ]
,E/SELinux ( 4650): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 4650): in addTimaSignatureService
,D/TimaKeyStoreProvider( 4650): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 4650): Added TimaKesytore provider
,W/ActivityManager(  732): Permission Denial: getCurrentUser() from pid=4650, uid=10158 requires android.permission.INTERACT_ACROSS_USERS
,D/KidsPlatformStub( 4650): Package not found : com.sec.android.app.kidshome
,I/SELinux ( 4662): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 4662):  
,I/ActivityManager(  732): Killing 3358:com.samsung.android.service.travel/u0a169 (adj 15): empty #43
,I/SELinux ( 4662): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 4662):  
I/SELinux ( 4662):  
,I/SELinux ( 4662): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 4662): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 4662): >>>>> Normal User
,E/dalvikvm( 4662): >>>>> com.samsung.android.provider.shootingmodeprovider [ userId:0 | appId:10162 ]
,E/SELinux ( 4662): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 4662): in addTimaSignatureService
,D/TimaKeyStoreProvider( 4662): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 4662): Added TimaKesytore provider
,I/SELinux ( 4674): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 4674):  
I/ActivityManager(  732): Killing 3378:com.google.android.youtube/u0a175 (adj 15): empty #43
,I/SELinux ( 4674): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 4674):  
I/SELinux ( 4674):  
,I/SELinux ( 4674): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 4674): [DEBUG] seapp_context_lookup: seinfoCategory = samsung
E/dalvikvm( 4674): >>>>> Normal User
,E/dalvikvm( 4674): >>>>> com.sec.android.app.samsungapps [ userId:0 | appId:10040 ]
,E/SELinux ( 4674): [DEBUG] seapp_context_lookup: seinfoCategory = samsung
,D/TimaKeyStoreProvider( 4674): in addTimaSignatureService
,D/TimaKeyStoreProvider( 4674): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 4674): Added TimaKesytore provider
,D/dalvikvm( 4501): GC_CONCURRENT freed 4681K, 28% free 16227K/22268K, paused 13ms+4ms, total 81ms
,D/dalvikvm( 4501): WAIT_FOR_CONCURRENT_GC blocked 51ms
,D/dalvikvm( 4501): WAIT_FOR_CONCURRENT_GC blocked 50ms
,I/ActivityManager(  732): Killing 3570:com.sec.android.widgetapp.activeapplicationwidget/u0a152 (adj 15): empty #43
,D/Finsky  ( 3452): [1] ExternalReferrer.access$200: Package state data is missing for com.test.thalitest
,D/ChimeraCfgMgr( 1781): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 1781): Loading module APK com.google.android.play.games
,D/PackageBroadcastService( 1781): Received broadcast action=android.intent.action.PACKAGE_ADDED and uri=com.test.thalitest
,I/dalvikvm( 1781): Could not find method android.app.admin.DevicePolicyManager.getProfileOwner, referenced from method com.google.android.gms.auth.WorkAccountAuthenticatorInitializer.a
,W/dalvikvm( 1781): VFY: unable to resolve virtual method 174: Landroid/app/admin/DevicePolicyManager;.getProfileOwner ()Landroid/content/ComponentName;
,D/dalvikvm( 1781): VFY: replacing opcode 0x6e at 0x0053
,I/dalvikvm( 1781): Failed resolving Lcom/google/android/gms/common/permission/PermissionUtils$1; interface 96 'Landroid/content/pm/PackageManager$OnPermissionsChangedListener;'
,W/dalvikvm( 1781): Link of class 'Lcom/google/android/gms/common/permission/PermissionUtils$1;' failed
,E/dalvikvm( 1781): Could not find class 'com.google.android.gms.common.permission.PermissionUtils$1', referenced from method com.google.android.gms.chimera.GmsModuleInitializer.initializeModuleV0
W/dalvikvm( 1781): VFY: unable to resolve new-instance 2374 (Lcom/google/android/gms/common/permission/PermissionUtils$1;) in Lcom/google/android/gms/chimera/GmsModuleInitializer;
,D/dalvikvm( 1781): VFY: replacing opcode 0x22 at 0x001a
I/dalvikvm( 1781): Failed resolving Lcom/google/android/gms/common/permission/PermissionUtils$1; interface 96 'Landroid/content/pm/PackageManager$OnPermissionsChangedListener;'
,W/dalvikvm( 1781): Link of class 'Lcom/google/android/gms/common/permission/PermissionUtils$1;' failed
,D/dalvikvm( 1781): DexOpt: unable to opt direct call 0x338d at 0x1c in Lcom/google/android/gms/chimera/GmsModuleInitializer;.initializeModuleV0
,D/dalvikvm( 1781): GC_CONCURRENT freed 1954K, 41% free 11339K/19028K, paused 3ms+10ms, total 147ms
,D/ChimeraCfgMgr( 1781): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 1781): Module APK com.google.android.play.games already loaded
,D/ChimeraCfgMgr( 1781): Loading module com.google.android.gms.gass from APK com.google.android.gms
,D/AsyncTaskServiceImpl( 1781): Submit a task: k
,D/ChimeraCfgMgr( 1781): Loading module com.google.android.gms.gass from APK com.google.android.gms
,D/ChimeraCfgMgr( 1781): Loading module com.google.android.gms.vision from APK com.google.android.gms
,D/dalvikvm( 4501): GC_FOR_ALLOC freed 5116K, 31% free 17220K/24940K, paused 41ms, total 44ms
,D/dalvikvm( 1304): GC_EXPLICIT freed 962K, 44% free 10758K/19028K, paused 4ms+8ms, total 43ms
,I/dalvikvm-heap( 4501): Grow heap (frag case) to 22.469MB for 2459024-byte allocation
,W/BaseAppContext( 1781): Using Auth Proxy for data requests.
,W/BaseAppContext( 1781): Using Auth Proxy for data requests.
,D/k       ( 1781): Processing package: com.test.thalitest
,D/GassUtils( 1781): Found app info for package com.test.thalitest:18. Hash: 4eebbbb84f07ed56a3e96e5e8f9d6abddaaf154fffa2a65432a1006e0fa38f32
,W/BaseAppContext( 1781): Using Auth Proxy for data requests.
,D/k       ( 1781): Found info for package com.test.thalitest in db.
,W/ContextImpl(  732): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,W/BaseAppContext( 1781): Using Auth Proxy for data requests.
,W/BaseAppContext( 1781): Using Auth Proxy for data requests.
,W/BaseAppContext( 1781): Using Auth Proxy for data requests.
,W/BaseAppContext( 1781): Using Auth Proxy for data requests.
,W/dalvikvm( 1781): VFY: unable to find class referenced in signature (Landroid/app/SharedElementCallback;)
,I/dalvikvm( 1781): Could not find method android.app.Activity.setEnterSharedElementCallback, referenced from method android.support.v4.app.w.setEnterSharedElementCallback
W/dalvikvm( 1781): VFY: unable to resolve virtual method 53: Landroid/app/Activity;.setEnterSharedElementCallback (Landroid/app/SharedElementCallback;)V
,D/dalvikvm( 1781): VFY: replacing opcode 0x6e at 0x000e
W/dalvikvm( 1781): VFY: unable to find class referenced in signature (Landroid/app/SharedElementCallback;)
I/dalvikvm( 1781): Could not find method android.app.Activity.setExitSharedElementCallback, referenced from method android.support.v4.app.w.setExitSharedElementCallback
W/dalvikvm( 1781): VFY: unable to resolve virtual method 54: Landroid/app/Activity;.setExitSharedElementCallback (Landroid/app/SharedElementCallback;)V
,D/dalvikvm( 1781): VFY: replacing opcode 0x6e at 0x000e
I/dalvikvm( 1781): Could not find method android.app.Activity.finishAfterTransition, referenced from method android.support.v4.app.w.supportFinishAfterTransition
W/dalvikvm( 1781): VFY: unable to resolve virtual method 31: Landroid/app/Activity;.finishAfterTransition ()V
D/dalvikvm( 1781): VFY: replacing opcode 0x6e at 0x0006
I/dalvikvm( 1781): Could not find method android.app.Activity.postponeEnterTransition, referenced from method android.support.v4.app.w.supportPostponeEnterTransition
W/dalvikvm( 1781): VFY: unable to resolve virtual method 49: Landroid/app/Activity;.postponeEnterTransition ()V
D/dalvikvm( 1781): VFY: replacing opcode 0x6e at 0x0006
I/dalvikvm( 1781): Could not find method android.app.Activity.startPostponedEnterTransition, referenced from method android.support.v4.app.w.supportStartPostponedEnterTransition
W/dalvikvm( 1781): VFY: unable to resolve virtual method 61: Landroid/app/Activity;.startPostponedEnterTransition ()V
,D/dalvikvm( 1781): VFY: replacing opcode 0x6e at 0x0006
,I/PeopleDatabaseHelper( 1781): cleanUpNonGplusAccounts done.
,D/dalvikvm( 4501): GC_FOR_ALLOC freed 3737K, 35% free 17932K/27344K, paused 34ms, total 35ms
,W/dalvikvm( 1781): VFY: unable to find class referenced in signature (Landroid/util/Size;)
,D/ChimeraCfgMgr( 1781): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 1781): Module APK com.google.android.play.games already loaded
,D/dalvikvm( 4501): GC_FOR_ALLOC freed 1185K, 35% free 17841K/27344K, paused 29ms, total 30ms
,E/SMD     (  242): DCD ON
,D/dalvikvm( 4501): GC_FOR_ALLOC freed 4472K, 39% free 19152K/30948K, paused 32ms, total 33ms
,W/jxcore-log( 4501): Initializing JXcore engine
,W/jxcore-log( 4501): JXcore engine is ready
,W/jxcore-log( 4501): Starting JXcore engine
,W/jxcore-log( 4501): Platform android
W/jxcore-log( 4501): 
,W/jxcore-log( 4501): Process ARCH arm
W/jxcore-log( 4501): 
,I/Icing   ( 1781): Indexing 49CA7E3A917E607C6D98AA15891295369CED2106 from com.google.android.gms
,D/dalvikvm( 1781): GC_CONCURRENT freed 1200K, 37% free 12118K/19028K, paused 5ms+5ms, total 40ms
,I/Icing   ( 1781): Indexing done 49CA7E3A917E607C6D98AA15891295369CED2106
,I/jxcore-log( 4501): JXcore Cordova bridge is ready!
I/jxcore-log( 4501): 
,W/jxcore-log( 4501): JXcore engine is started
,E/jxcore  ( 4501): Error!: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js
E/jxcore  ( 4501): Stack: [{"_fileName":"node.js","_functionName":"$h.require","_lineNumber":"1472","_columnNumber":"1","_msg":"    at $h.require@node.js:1472:1"},{"_fileName":"main.js.js","_functionName":"internal_methods.loadMainFile","_lineNumber":"260","_columnNumber":"5","_msg":"    at internal_methods.loadMainFile@main.js.js:260:5"},{"_fileName":"main.js.js","_functionName":"JXMobile.executeJSON","_lineNumber":"279","_columnNumber":"7","_msg":"    at JXMobile.executeJSON@main.js.js:279:7"},{"_fileName":"JX_Evaluate","_functionName":"","_lineNumber":"1","_columnNumber":"1","_msg":"    at @JX_Evaluate:1:1"},{"_fileName":"node.js","_functionName":"unknown","_lineNumber":"1472","_columnNumber":"1","_msg":""}]
,I/chromium( 4501): [INFO:CONSOLE(37)] "App.js file failed to load : "No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\nError: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\n    at $h.require@node.js:1472:1\n    at internal_methods.loadMainFile@main.js.js:260:5\n    at JXMobile.executeJSON@main.js.js:279:7\n    at @JX_Evaluate:1:1\n"", source: file:///android_asset/www/js/thali_main.js (37)
,D/LockPatternUtils( 1065): isPcwEnable = null
I/ActivityManager(  732): Killing 3612:com.sec.android.app.sns3/u0a36 (adj 15): empty #43
,I/SurfaceFlinger(  248): id=16 Removed NainActivit (7/11)
,I/SurfaceFlinger(  248): id=16 Removed NainActivit (-2/11)
,D/KeyguardUpdateMonitor( 1065): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1065): handleKeyguardVisibilityChanged(1)
,D/KeyguardUpdateMonitor( 1065): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1065): handleKeyguardVisibilityChanged(1)
D/CustomFrequencyManagerService(  732): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 732  pkgName : ACTIVITY_RESUME_BOOSTER@5
,W/ActivityManager(  732): mDVFSHelper.acquire()
D/KeyguardUpdateMonitor( 1065): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1065): handleKeyguardVisibilityChanged(1)
,D/LockPatternUtils( 1065): isPcwEnable = null
,D/SurfaceWidgetView( 1241): destroyHardwareResources():1126362448
,D/KeyguardUpdateMonitor( 1065): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1065): handleKeyguardVisibilityChanged(1)
,D/KeyguardUpdateMonitor( 1065): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1065): handleKeyguardVisibilityChanged(1)
D/Launcher( 1241): onRestart, Launcher: 1114425728
D/Launcher( 1241): onStart, Launcher: 1114425728
,D/Launcher.HomeView( 1241): onStart
,D/SurfaceWidgetClient$ISurfaceWidgetStub( 1441): [237392/5] Surface widget visibility changed visibility = true on instance = 1
,D/SurfaceWidget.Renderer( 1441): [237392/5] SurfaceWidget drawing first frame
,I/SurfaceFlinger(  248): id=17 createSurf (720x1280),1 flag=4, Mauncher
D/KeyguardUpdateMonitor( 1065): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1065): handleKeyguardVisibilityChanged(1)
,I/SurfaceFlinger(  248): id=18 createSurf (1x1),2 flag=404, CatteryCove
D/KeyguardUpdateMonitor( 1065): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1065): handleKeyguardVisibilityChanged(1)
,D/KeyguardUpdateMonitor( 1065): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1065): handleKeyguardVisibilityChanged(1)
,D/Launcher.HomeView( 1241): onStop
,D/KeyguardUpdateMonitor( 1065): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1065): handleKeyguardVisibilityChanged(1)
,D/KeyguardUpdateMonitor( 1065): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1065): handleKeyguardVisibilityChanged(1)
,D/KeyguardUpdateMonitor( 1065): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1065): handleKeyguardVisibilityChanged(1)
D/CustomFrequencyManagerService(  732): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 732  tag : ACTIVITY_RESUME_BOOSTER@5
W/ActivityManager(  732): mDVFSHelper.release()
D/CustomFrequencyManagerService(  732): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 732  pkgName : ACTIVITY_RESUME_BOOSTER@9
,D/CustomFrequencyManagerService(  732): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 732  tag : ACTIVITY_RESUME_BOOSTER@9
,I/GAV2    ( 4573): Thread[GAThread,5,main]: No campaign data found.
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,D/AmoledAdjustTimer(  732): prevTemp = 283, currTemp = 283, prevStep = 4, currStep = 4
,I/HarmonyEASService(  732): Updating for all 1
,D/BatteryService(  732): level:100, scale:100, status:5, health:2, present:true, voltage: 4366, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:7, charge type:1, power sharing:false
,D/BatteryService(  732): stay LED for fully charged
,D/BatteryService(  732): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
D/UiModeManager(  732): mCoverManager.getCoverState() : true
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP(  732): SIOP:: AP = 310, Delta = 0
,D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,E/Watchdog(  732): !@Sync 3
,E/SMD     (  242): DCD ON
,D/AmoledAdjustTimer(  732): prevTemp = 283, currTemp = 285, prevStep = 4, currStep = 4
,I/PowerManagerService(  732): [PWL] Off : 50s ago
,D/SSRMv2:SIOP(  732): SIOP:: AP = 300, Delta = -10
,E/SMD     (  242): DCD ON
,W/ContextImpl(  732): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  242): DCD ON
,V/AlarmManager(  732): waitForAlarm result :4
,V/AlarmManager(  732): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,V/AlarmManager(  732): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,D/BatteryService(  732): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 283, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:9, charge type:1, power sharing:false
,D/BatteryService(  732): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  732): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
D/UiModeManager(  732): mCoverManager.getCoverState() : true
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
,D/dalvikvm(  732): GC_EXPLICIT freed 2906K, 59% free 23518K/56812K, paused 51ms+37ms, total 583ms
,D/FactoryTest( 4024): Not factory mode
,D/FactoryTest( 4024): Not factory mode. isFactoryMode() returend false
,D/MTPRx   ( 4024): DRIVER_TIME_OUT 60s lapsed
,D/MTPRx   ( 4024): still no open session command from host, so toast
W/ContextImpl( 4024): Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1398 android.content.ContextWrapper.startActivity:323 android.content.ContextWrapper.startActivity:323 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:767 android.os.Handler.dispatchMessage:102 
W/ContextImpl( 4024): Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1410 android.app.ContextImpl.startActivity:1399 android.content.ContextWrapper.startActivity:323 android.content.ContextWrapper.startActivity:323 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:767 
,V/ApplicationPolicy(  732): isApplicationStateBlocked userId 0 pkgname com.android.settings
,D/CustomFrequencyManagerService(  732): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 732  pkgName : ACTIVITY_RESUME_BOOSTER@5
,W/ActivityManager(  732): mDVFSHelper.acquire()
,I/SQLiteSecureOpenHelper( 2017): getWritableDatabase(pwd)
,I/SQLiteSecureOpenHelper( 2017): getDatabaseLocked(b,b,pwd)...
,D/LockPatternUtils( 1065): isPcwEnable = null
,D/LockPatternUtils( 1065): isPcwEnable = null
,E/MTPRx   ( 4024): started activity for popup
,D/dalvikvm( 3452): GC_CONCURRENT freed 6684K, 43% free 11003K/19028K, paused 4ms+5ms, total 39ms
,D/dalvikvm( 3452): WAIT_FOR_CONCURRENT_GC blocked 29ms
,E/SettingsReceiverActivity( 4024): PREF_DONT_ASK_AGAIN : true
,D/LockPatternUtils( 1065): isPcwEnable = null
,D/SettingsReceiverActivity( 4024): dev.kiessupport is : TRUE
,D/Finsky  ( 3452): [349] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 3452): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,I/WindowManager(  732): Screenshot max retries 4 of Token{43072f40 ActivityRecord{430e7680 u0 com.sec.android.app.popupuireceiver/.BatteryCover t2}} appWin=Window{430ecb68 u0 com.sec.android.app.popupuireceiver/com.sec.android.app.popupuireceiver.BatteryCover} drawState=4
,W/WindowManager(  732): Screenshot failure taking screenshot for (720x1280) to layer 21005
,D/LockPatternUtils( 1065): isPcwEnable = null
,E/SMD     (  242): DCD ON
,D/CustomFrequencyManagerService(  732): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 732  tag : ACTIVITY_RESUME_BOOSTER@5
,W/ActivityManager(  732): mDVFSHelper.release()
,D/CustomFrequencyManagerService(  732): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 732  pkgName : ACTIVITY_RESUME_BOOSTER@9
,D/AmoledAdjustTimer(  732): prevTemp = 285, currTemp = 283, prevStep = 4, currStep = 4
,E/SMD     (  242): DCD ON
D/CustomFrequencyManagerService(  732): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 732  tag : ACTIVITY_RESUME_BOOSTER@9
,V/AlarmManager(  732): waitForAlarm result :8
,V/AlarmManager(  732): ClockReceiver onReceive() ACTION_TIME_TICK
,V/AlarmManager(  732): ___SyncScheduler (v3) ACTIVATED___
V/AlarmManager(  732): <AppSync3 Whitelist>
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1065): handleTimeUpdate
V/AlarmManager(  732): (AppSync) ### 0 added ###
,D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  732): SIOP:: AP = 300, Delta = 0
,E/SMD     (  242): DCD ON
,D/BatteryService(  732): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:9, charge type:1, power sharing:false
,D/BatteryService(  732): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  732): stay LED for fully charged
,D/UiModeManager(  732): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,D/AmoledAdjustTimer(  732): prevTemp = 283, currTemp = 281, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP(  732): SIOP:: AP = 300, Delta = 0
,E/SMD     (  242): DCD ON
,W/ContextImpl(  732): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  242): DCD ON
,I/PowerManagerService(  732): [PWL] Off : 75s ago
,D/BatteryService(  732): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 280, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:8, charge type:1, power sharing:false
,D/BatteryService(  732): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  732): stay LED for fully charged
,D/UiModeManager(  732): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
,E/Watchdog(  732): !@Sync 4
,V/AlarmManager(  732): waitForAlarm result :8
,D/NtpTrustedTime(  732): forceRefresh() from cache miss
,D/NtpTrustedTime(  732): forceRefresh Fail.
,E/SMD     (  242): DCD ON
,D/AmoledAdjustTimer(  732): prevTemp = 281, currTemp = 280, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP(  732): SIOP:: AP = 300, Delta = 0
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,D/BatteryService(  732): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  732): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  732): mCoverManager.getCoverState() : true
,D/BatteryService(  732): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  242): DCD ON
,D/AmoledAdjustTimer(  732): prevTemp = 280, currTemp = 279, prevStep = 4, currStep = 4
,E/SMD     (  242): DCD ON
,D/SSRMv2:SIOP(  732): SIOP:: AP = 300, Delta = 0
,W/ContextImpl(  732): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  242): DCD ON
,D/BatteryService(  732): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-6, charge type:1, power sharing:false
,D/BatteryService(  732): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  732): stay LED for fully charged
,D/UiModeManager(  732): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,D/AmoledAdjustTimer(  732): prevTemp = 279, currTemp = 278, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP(  732): SIOP:: AP = 300, Delta = 0
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,I/PowerManagerService(  732): [PWL] Off : 105s ago
,D/BatteryService(  732): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService(  732): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  732): mCoverManager.getCoverState() : true
,D/BatteryService(  732): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
,E/Watchdog(  732): !@Sync 5
,E/SMD     (  242): DCD ON
,D/AmoledAdjustTimer(  732): prevTemp = 278, currTemp = 277, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP(  732): SIOP:: AP = 300, Delta = 0
,E/SMD     (  242): DCD ON
,W/ContextImpl(  732): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  242): DCD ON
,D/BatteryService(  732): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:16, charge type:1, power sharing:false
,D/BatteryService(  732): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  732): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
D/BatteryService(  732): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  242): DCD ON
,D/AmoledAdjustTimer(  732): prevTemp = 277, currTemp = 276, prevStep = 4, currStep = 4
,E/SMD     (  242): DCD ON
,V/AlarmManager(  732): waitForAlarm result :8
,V/AlarmManager(  732): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1065): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  732): SIOP:: AP = 300, Delta = 0
,E/SMD     (  242): DCD ON
,D/BatteryService(  732): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:9, charge type:1, power sharing:false
,D/BatteryService(  732): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  732): stay LED for fully charged
,D/UiModeManager(  732): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,D/AmoledAdjustTimer(  732): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP(  732): SIOP:: AP = 300, Delta = 0
,E/SMD     (  242): DCD ON
,W/ContextImpl(  732): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  242): DCD ON
,E/Watchdog(  732): !@Sync 6
,V/AlarmManager(  732): waitForAlarm result :4
,V/AlarmManager(  732): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,D/NtpTrustedTime(  732): forceRefresh() from cache miss
,D/NtpTrustedTime(  732): forceRefresh Fail.
,D/BatteryService(  732): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:8, charge type:1, power sharing:false
,D/BatteryService(  732): stay LED for fully charged
,D/BatteryService(  732): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/UiModeManager(  732): mCoverManager.getCoverState() : true
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  242): DCD ON
,I/VacuumService( 1216): Vacuum at: now=1453857078417 tag=VacuumService
,D/AmoledAdjustTimer(  732): prevTemp = 276, currTemp = 275, prevStep = 4, currStep = 4
,I/PowerManagerService(  732): [PWL] Off : 140s ago
,D/SSRMv2:SIOP(  732): SIOP:: AP = 300, Delta = 0
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,D/BatteryService(  732): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:6, charge type:1, power sharing:false
,D/BatteryService(  732): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  732): stay LED for fully charged
,D/UiModeManager(  732): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
,D/AmoledAdjustTimer(  732): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,E/SMD     (  242): DCD ON
,D/SSRMv2:SIOP(  732): SIOP:: AP = 300, Delta = 0
,W/ContextImpl(  732): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,D/BatteryService(  732): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:8, charge type:1, power sharing:false
,D/BatteryService(  732): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  732): mCoverManager.getCoverState() : true
,D/BatteryService(  732): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  242): DCD ON
,D/AmoledAdjustTimer(  732): prevTemp = 275, currTemp = 274, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP(  732): SIOP:: AP = 300, Delta = 0
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,E/Watchdog(  732): !@Sync 7
,D/BatteryService(  732): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:4, charge type:1, power sharing:false
,D/BatteryService(  732): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  732): stay LED for fully charged
,E/SMD     (  242): DCD ON
,D/UiModeManager(  732): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
,D/AmoledAdjustTimer(  732): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP(  732): SIOP:: AP = 300, Delta = 0
,E/SMD     (  242): DCD ON
,W/ContextImpl(  732): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,D/BatteryService(  732): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-8, charge type:1, power sharing:false
,D/BatteryService(  732): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  732): stay LED for fully charged
,D/UiModeManager(  732): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
,D/AmoledAdjustTimer(  732): prevTemp = 274, currTemp = 273, prevStep = 4, currStep = 4
,V/AlarmManager(  732): waitForAlarm result :8
,E/SMD     (  242): DCD ON
V/AlarmManager(  732): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.TIME_TICK
I/PowerManagerService(  732): [PWL] Off : 180s ago
I/PowerManagerService(  732): [PWL]   PowerManagerService.WakeLocks: ref count=1
I/PowerManagerService(  732): [PWL]     mWakeLockSummary : 0x1
,I/PowerManagerService(  732): [PWL]       PARTIAL_WAKE_LOCK              'AlarmManager' (uid=1000, pid=732, ws=WorkSource{1000}) (elapsedTime=8)
D/KeyguardUpdateMonitor( 1065): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  732): SIOP:: AP = 300, Delta = 0
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,D/BatteryService(  732): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:2, charge type:1, power sharing:false
,D/BatteryService(  732): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  732): stay LED for fully charged
,D/UiModeManager(  732): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  242): DCD ON
,D/AmoledAdjustTimer(  732): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP(  732): SIOP:: AP = 300, Delta = 0
,E/SMD     (  242): DCD ON
,W/ContextImpl(  732): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  242): DCD ON
,E/Watchdog(  732): !@Sync 8
,E/SMD     (  242): DCD ON
,D/BatteryService(  732): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-9, charge type:1, power sharing:false
,D/BatteryService(  732): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  732): stay LED for fully charged
,D/UiModeManager(  732): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
,D/AmoledAdjustTimer(  732): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP(  732): SIOP:: AP = 300, Delta = 0
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,D/BatteryService(  732): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-4, charge type:1, power sharing:false
,D/BatteryService(  732): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  732): mCoverManager.getCoverState() : true
,D/BatteryService(  732): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
,D/AmoledAdjustTimer(  732): prevTemp = 273, currTemp = 272, prevStep = 4, currStep = 4
,E/SMD     (  242): DCD ON
,D/SSRMv2:SIOP(  732): SIOP:: AP = 300, Delta = 0
,W/ContextImpl(  732): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,D/BatteryService(  732): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-1, charge type:1, power sharing:false
,D/BatteryService(  732): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  732): mCoverManager.getCoverState() : true
,D/BatteryService(  732): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  242): DCD ON
,D/AmoledAdjustTimer(  732): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP(  732): SIOP:: AP = 300, Delta = 0
,E/SMD     (  242): DCD ON
,I/PowerManagerService(  732): [PWL] Off : 225s ago
,E/SMD     (  242): DCD ON
,E/Watchdog(  732): !@Sync 9
,E/SMD     (  242): DCD ON
,D/BatteryService(  732): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-4, charge type:1, power sharing:false
,D/BatteryService(  732): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  732): stay LED for fully charged
,D/UiModeManager(  732): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
,D/AmoledAdjustTimer(  732): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP(  732): SIOP:: AP = 300, Delta = 0
,E/SMD     (  242): DCD ON
,W/ContextImpl(  732): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,D/BatteryService(  732): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-4, charge type:1, power sharing:false
,D/BatteryService(  732): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  732): stay LED for fully charged
,D/UiModeManager(  732): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
,D/AmoledAdjustTimer(  732): prevTemp = 272, currTemp = 271, prevStep = 4, currStep = 4
,V/AlarmManager(  732): waitForAlarm result :8
,V/AlarmManager(  732): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1065): handleTimeUpdate
,E/SMD     (  242): DCD ON
D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  732): SIOP:: AP = 300, Delta = 0
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,D/AmoledAdjustTimer(  732): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP(  732): SIOP:: AP = 300, Delta = 0
,D/TimaService(  732): TIMA: TimaService scheduler is intialized. 
,D/TimaService(  732): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService(  732): TimaServiceHandler.handleMessage what =1
,I/TLC_TIMA_PKM_initialize(  732): initializing...
,I/TLC_TIMA_PKM_initialize(  732): root = /firmware/image, root_strlen = 15
,I/TLC_TIMA_PKM_initialize(  732): process = tima_pkm, process_strlen = 8
,I/TZ: qc_tlc_communication(  732): root = /firmware/image, root_len = 15
I/TZ: qc_tlc_communication(  732): process = tima_pkm, process_strlen = 8
,I/TZ: qc_tlc_communication(  732): aligned max_sendmsg_size = 262208 = 0x40040
I/TZ: qc_tlc_communication(  732): aligned max_recvmsg_size = 262208 = 0x40040
,I/TZ: qc_tlc_communication(  732): max_message_size = 524416 = 0x80080
,D/QSEECOMAPI: (  732): QSEECom_get_handle sb_length = 0x80080
,D/QSEECOMAPI: (  732): App is not loaded in QSEE
,D/QSEECOMAPI: (  732): Loaded image: APP id = 2
,I/TZ: qc_tlc_communication(  732): TIMA: path = /firmware/image, fname = tima_pkm, tzapp is loaded
,I/TLC_TIMA_PKM_initialize(  732): Trustlet response is completed
,E/SMD     (  242): DCD ON
,W/ContextImpl(  732): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  242): DCD ON
,I/TLC_TIMA_PKM_measure_kernel(  732): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel(  732): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService(  732): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService(  732): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/Watchdog(  732): !@Sync 10
,E/SMD     (  242): DCD ON
,D/BatteryService(  732): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:2, charge type:1, power sharing:false
,D/BatteryService(  732): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  732): mCoverManager.getCoverState() : true
,D/BatteryService(  732): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
,D/AmoledAdjustTimer(  732): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,E/SMD     (  242): DCD ON
,D/SSRMv2:SIOP(  732): SIOP:: AP = 300, Delta = 0
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,D/AmoledAdjustTimer(  732): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,E/SMD     (  242): DCD ON
,D/SSRMv2:SIOP(  732): SIOP:: AP = 300, Delta = 0
,W/ContextImpl(  732): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  242): DCD ON
,I/PowerManagerService(  732): [PWL] Off : 275s ago
,E/SMD     (  242): DCD ON
,V/AlarmManager(  732): waitForAlarm result :4
,V/AlarmManager(  732): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,I/SELinux ( 4821): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 4821):  
,D/BatteryService(  732): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  732): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  732): stay LED for fully charged
,D/UiModeManager(  732): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/SELinux ( 4821): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 4821):  
I/SELinux ( 4821):  
,I/SELinux ( 4821): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 4821): [DEBUG] seapp_context_lookup: seinfoCategory = default
,E/dalvikvm( 4821): >>>>> Normal User
,E/dalvikvm( 4821): >>>>> com.blurb.checkout [ userId:0 | appId:10075 ]
,E/SELinux ( 4821): [DEBUG] seapp_context_lookup: seinfoCategory = default
,D/TimaKeyStoreProvider( 4821): in addTimaSignatureService
,D/TimaKeyStoreProvider( 4821): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 4821): Added TimaKesytore provider
,W/ActivityManager(  732): Permission Denial: getCurrentUser() from pid=4821, uid=10075 requires android.permission.INTERACT_ACROSS_USERS
,I/ActivityManager(  732): Killing 3655:com.sec.spp.push:RemoteDlcProcess/u0a38 (adj 15): empty #43
,E/SMD     (  242): DCD ON
,D/AmoledAdjustTimer(  732): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP(  732): SIOP:: AP = 300, Delta = 0
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,E/Watchdog(  732): !@Sync 11
,V/GLSActivity( 1304): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1304): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/SMD     (  242): DCD ON
,D/BatteryService(  732): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:2, charge type:1, power sharing:false
,D/BatteryService(  732): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  732): mCoverManager.getCoverState() : true
,D/BatteryService(  732): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
,D/AmoledAdjustTimer(  732): prevTemp = 271, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  242): DCD ON
,D/SSRMv2:SIOP(  732): SIOP:: AP = 300, Delta = 0
,W/ContextImpl(  732): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,D/BatteryService(  732): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:3, charge type:1, power sharing:false
,D/BatteryService(  732): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  732): stay LED for fully charged
,D/UiModeManager(  732): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
,D/AmoledAdjustTimer(  732): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,V/AlarmManager(  732): waitForAlarm result :8
,V/AlarmManager(  732): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1065): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  242): DCD ON
,D/SSRMv2:SIOP(  732): SIOP:: AP = 300, Delta = 0
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,D/BatteryService(  732): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:5, charge type:1, power sharing:false
,D/BatteryService(  732): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  732): mCoverManager.getCoverState() : true
,D/BatteryService(  732): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  242): DCD ON
,D/AmoledAdjustTimer(  732): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP(  732): SIOP:: AP = 300, Delta = 0
,E/SMD     (  242): DCD ON
,W/ContextImpl(  732): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  242): DCD ON
,E/Watchdog(  732): !@Sync 12
,E/SMD     (  242): DCD ON
,D/BatteryService(  732): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:3, charge type:1, power sharing:false
,D/BatteryService(  732): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  732): stay LED for fully charged
,D/UiModeManager(  732): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
,D/AmoledAdjustTimer(  732): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  242): DCD ON
,D/SSRMv2:SIOP(  732): SIOP:: AP = 300, Delta = 0
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,D/BatteryService(  732): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  732): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  732): stay LED for fully charged
,D/UiModeManager(  732): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
,D/AmoledAdjustTimer(  732): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,I/PowerManagerService(  732): [PWL] Off : 330s ago
,E/SMD     (  242): DCD ON
,D/SSRMv2:SIOP(  732): SIOP:: AP = 300, Delta = 0
,W/ContextImpl(  732): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,D/BatteryService(  732): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:2, charge type:1, power sharing:false
,D/BatteryService(  732): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  732): stay LED for fully charged
,D/UiModeManager(  732): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  242): DCD ON
,D/AmoledAdjustTimer(  732): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP(  732): SIOP:: AP = 300, Delta = 0
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,E/Watchdog(  732): !@Sync 13
,E/SMD     (  242): DCD ON
,D/AmoledAdjustTimer(  732): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  242): DCD ON
,D/SSRMv2:SIOP(  732): SIOP:: AP = 300, Delta = 0
,W/ContextImpl(  732): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,D/BatteryService(  732): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  732): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  732): mCoverManager.getCoverState() : true
,D/BatteryService(  732): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
,D/AmoledAdjustTimer(  732): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,V/AlarmManager(  732): waitForAlarm result :8
,V/AlarmManager(  732): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1065): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  242): DCD ON
,D/SSRMv2:SIOP(  732): SIOP:: AP = 300, Delta = 0
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,D/BatteryService(  732): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-2, charge type:1, power sharing:false
,D/BatteryService(  732): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  732): stay LED for fully charged
,D/UiModeManager(  732): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  242): DCD ON
,D/AmoledAdjustTimer(  732): prevTemp = 270, currTemp = 269, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP(  732): SIOP:: AP = 300, Delta = 0
,E/SMD     (  242): DCD ON
,W/ContextImpl(  732): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  242): DCD ON
,E/Watchdog(  732): !@Sync 14
,E/SMD     (  242): DCD ON
,D/BatteryService(  732): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  732): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  732): mCoverManager.getCoverState() : true
,D/BatteryService(  732): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
,D/AmoledAdjustTimer(  732): prevTemp = 269, currTemp = 269, prevStep = 4, currStep = 4
,E/SMD     (  242): DCD ON
,D/SSRMv2:SIOP(  732): SIOP:: AP = 300, Delta = 0
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,D/AmoledAdjustTimer(  732): prevTemp = 269, currTemp = 269, prevStep = 4, currStep = 4
,I/PowerManagerService(  732): [PWL] Off : 390s ago
,E/SMD     (  242): DCD ON
,D/SSRMv2:SIOP(  732): SIOP:: AP = 300, Delta = 0
,W/ContextImpl(  732): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,D/BatteryService(  732): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  732): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  732): mCoverManager.getCoverState() : true
,D/BatteryService(  732): stay LED for fully charged
D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  242): DCD ON
,D/AmoledAdjustTimer(  732): prevTemp = 269, currTemp = 269, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP(  732): SIOP:: AP = 300, Delta = 0
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,E/Watchdog(  732): !@Sync 15
,E/SMD     (  242): DCD ON
,D/BatteryService(  732): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService(  732): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  732): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
D/BatteryService(  732): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
,D/AmoledAdjustTimer(  732): prevTemp = 269, currTemp = 269, prevStep = 4, currStep = 4
,E/SMD     (  242): DCD ON
,D/SSRMv2:SIOP(  732): SIOP:: AP = 300, Delta = 0
,W/ContextImpl(  732): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,D/AmoledAdjustTimer(  732): prevTemp = 269, currTemp = 269, prevStep = 4, currStep = 4
,V/AlarmManager(  732): waitForAlarm result :8
,V/AlarmManager(  732): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1065): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
,D/BatteryService(  732): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-8, charge type:1, power sharing:false
,D/BatteryService(  732): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  732): stay LED for fully charged
,D/UiModeManager(  732): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  242): DCD ON
,D/SSRMv2:SIOP(  732): SIOP:: AP = 300, Delta = 0
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,D/AmoledAdjustTimer(  732): prevTemp = 269, currTemp = 269, prevStep = 4, currStep = 4
,D/BatteryService(  732): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-7, charge type:1, power sharing:false
,D/BatteryService(  732): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  732): stay LED for fully charged
,D/UiModeManager(  732): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  732): SIOP:: AP = 300, Delta = 0
,E/SMD     (  242): DCD ON
,W/ContextImpl(  732): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  242): DCD ON
,E/Watchdog(  732): !@Sync 16
,E/SMD     (  242): DCD ON
,D/AmoledAdjustTimer(  732): prevTemp = 269, currTemp = 269, prevStep = 4, currStep = 4
,D/dalvikvm(  732): GC_CONCURRENT freed 3549K, 59% free 23394K/56812K, paused 23ms+40ms, total 455ms
,D/BatteryService(  732): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-5, charge type:1, power sharing:false
,D/BatteryService(  732): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  732): mCoverManager.getCoverState() : true
,D/BatteryService(  732): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  242): DCD ON
,D/SSRMv2:SIOP(  732): SIOP:: AP = 300, Delta = 0
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,D/AmoledAdjustTimer(  732): prevTemp = 269, currTemp = 269, prevStep = 4, currStep = 4
,E/SMD     (  242): DCD ON
,D/BatteryService(  732): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:14, charge type:1, power sharing:false
,D/BatteryService(  732): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  732): mCoverManager.getCoverState() : true
,D/BatteryService(  732): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  732): SIOP:: AP = 300, Delta = 0
,W/ContextImpl(  732): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  242): DCD ON
,I/PowerManagerService(  732): [PWL] Off : 455s ago
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,D/AmoledAdjustTimer(  732): prevTemp = 269, currTemp = 269, prevStep = 4, currStep = 4
,D/BatteryService(  732): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:7, charge type:1, power sharing:false
,D/BatteryService(  732): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  732): stay LED for fully charged
,D/UiModeManager(  732): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  732): SIOP:: AP = 300, Delta = 0
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,E/Watchdog(  732): !@Sync 17
,E/SMD     (  242): DCD ON
,D/AmoledAdjustTimer(  732): prevTemp = 269, currTemp = 269, prevStep = 4, currStep = 4
,D/BatteryService(  732): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:14, charge type:1, power sharing:false
,D/BatteryService(  732): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  732): stay LED for fully charged
,D/UiModeManager(  732): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  242): DCD ON
,D/SSRMv2:SIOP(  732): SIOP:: AP = 300, Delta = 0
,W/ContextImpl(  732): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,D/AmoledAdjustTimer(  732): prevTemp = 269, currTemp = 269, prevStep = 4, currStep = 4
,V/AlarmManager(  732): waitForAlarm result :8
,V/AlarmManager(  732): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1065): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  242): DCD ON
,D/BatteryService(  732): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-6, charge type:1, power sharing:false
,D/BatteryService(  732): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  732): stay LED for fully charged
,D/UiModeManager(  732): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  732): SIOP:: AP = 300, Delta = 0
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,D/AmoledAdjustTimer(  732): prevTemp = 269, currTemp = 269, prevStep = 4, currStep = 4
,D/BatteryService(  732): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-9, charge type:1, power sharing:false
,D/BatteryService(  732): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  732): mCoverManager.getCoverState() : true
,D/BatteryService(  732): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  732): SIOP:: AP = 300, Delta = 0
,E/SMD     (  242): DCD ON
,W/ContextImpl(  732): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  242): DCD ON
,E/Watchdog(  732): !@Sync 18
,E/SMD     (  242): DCD ON
,D/AmoledAdjustTimer(  732): prevTemp = 269, currTemp = 269, prevStep = 4, currStep = 4
,D/BatteryService(  732): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-9, charge type:1, power sharing:false
,D/BatteryService(  732): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  732): stay LED for fully charged
,D/UiModeManager(  732): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  242): DCD ON
,D/SSRMv2:SIOP(  732): SIOP:: AP = 300, Delta = 0
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,D/AmoledAdjustTimer(  732): prevTemp = 269, currTemp = 269, prevStep = 4, currStep = 4
,E/SMD     (  242): DCD ON
,D/BatteryService(  732): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:4, charge type:1, power sharing:false
,D/BatteryService(  732): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  732): stay LED for fully charged
,D/UiModeManager(  732): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  732): SIOP:: AP = 300, Delta = 0
,W/ContextImpl(  732): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,D/AmoledAdjustTimer(  732): prevTemp = 269, currTemp = 268, prevStep = 4, currStep = 4
,D/BatteryService(  732): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:6, charge type:1, power sharing:false
,D/BatteryService(  732): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  732): mCoverManager.getCoverState() : true
,D/BatteryService(  732): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  732): SIOP:: AP = 300, Delta = 0
,E/SMD     (  242): DCD ON
,I/PowerManagerService(  732): [PWL] Off : 525s ago
,E/SMD     (  242): DCD ON
,E/Watchdog(  732): !@Sync 19
,E/SMD     (  242): DCD ON
,D/AmoledAdjustTimer(  732): prevTemp = 268, currTemp = 268, prevStep = 4, currStep = 4
,E/SMD     (  242): DCD ON
,D/SSRMv2:SIOP(  732): SIOP:: AP = 300, Delta = 0
,W/ContextImpl(  732): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,D/AmoledAdjustTimer(  732): prevTemp = 268, currTemp = 268, prevStep = 4, currStep = 4
,V/AlarmManager(  732): waitForAlarm result :8
,V/AlarmManager(  732): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1065): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  242): DCD ON
,D/BatteryService(  732): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:9, charge type:1, power sharing:false
,D/BatteryService(  732): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  732): stay LED for fully charged
,D/UiModeManager(  732): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  732): SIOP:: AP = 300, Delta = 0
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,D/AmoledAdjustTimer(  732): prevTemp = 268, currTemp = 268, prevStep = 4, currStep = 4
,D/BatteryService(  732): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-9, charge type:1, power sharing:false
,D/BatteryService(  732): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  732): mCoverManager.getCoverState() : true
,D/BatteryService(  732): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
,D/TimaService(  732): TIMA: TimaService scheduler is intialized. 
,D/TimaService(  732): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService(  732): TimaServiceHandler.handleMessage what =1
,D/SSRMv2:SIOP(  732): SIOP:: AP = 300, Delta = 0
,E/SMD     (  242): DCD ON
,W/ContextImpl(  732): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,I/TLC_TIMA_PKM_measure_kernel(  732): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel(  732): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService(  732): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService(  732): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/SMD     (  242): DCD ON
,E/Watchdog(  732): !@Sync 20
,E/SMD     (  242): DCD ON
,D/AmoledAdjustTimer(  732): prevTemp = 268, currTemp = 268, prevStep = 4, currStep = 4
,E/SMD     (  242): DCD ON
,D/SSRMv2:SIOP(  732): SIOP:: AP = 300, Delta = 0
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,D/AmoledAdjustTimer(  732): prevTemp = 268, currTemp = 268, prevStep = 4, currStep = 4
,E/SMD     (  242): DCD ON
,D/BatteryService(  732): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:2, charge type:1, power sharing:false
,D/BatteryService(  732): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  732): stay LED for fully charged
,D/UiModeManager(  732): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  732): SIOP:: AP = 300, Delta = 0
,W/ContextImpl(  732): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,D/AmoledAdjustTimer(  732): prevTemp = 268, currTemp = 268, prevStep = 4, currStep = 4
,D/BatteryService(  732): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:6, charge type:1, power sharing:false
,D/BatteryService(  732): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  732): stay LED for fully charged
,D/UiModeManager(  732): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  242): DCD ON
,D/SSRMv2:SIOP(  732): SIOP:: AP = 300, Delta = 0
,E/SMD     (  242): DCD ON
,E/Watchdog(  732): !@Sync 21
,V/GLSActivity( 1304): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1304): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/SMD     (  242): DCD ON
,D/AmoledAdjustTimer(  732): prevTemp = 268, currTemp = 268, prevStep = 4, currStep = 4
,D/BatteryService(  732): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:3, charge type:1, power sharing:false
,D/BatteryService(  732): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  732): mCoverManager.getCoverState() : true
,D/BatteryService(  732): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  242): DCD ON
,D/SSRMv2:SIOP(  732): SIOP:: AP = 300, Delta = 0
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,D/AmoledAdjustTimer(  732): prevTemp = 268, currTemp = 268, prevStep = 4, currStep = 4
,V/AlarmManager(  732): waitForAlarm result :8
,V/AlarmManager(  732): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1065): handleTimeUpdate
,I/PowerManagerService(  732): [PWL] Off : 600s ago
,I/PowerManagerService(  732): [PWL]   PowerManagerService.WakeLocks: ref count=1
,I/PowerManagerService(  732): [PWL]     mWakeLockSummary : 0x1
,I/PowerManagerService(  732): [PWL]       PARTIAL_WAKE_LOCK              'AlarmManager' (uid=1000, pid=732, ws=WorkSource{1000}) (elapsedTime=29)
,D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  242): DCD ON
,D/BatteryService(  732): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:6, charge type:1, power sharing:false
,D/BatteryService(  732): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  732): stay LED for fully charged
,D/UiModeManager(  732): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  732): SIOP:: AP = 300, Delta = 0
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,D/AmoledAdjustTimer(  732): prevTemp = 268, currTemp = 268, prevStep = 4, currStep = 4
,E/SMD     (  242): DCD ON
,D/SSRMv2:SIOP(  732): SIOP:: AP = 300, Delta = 0
,E/SMD     (  242): DCD ON
,E/Watchdog(  732): !@Sync 22
,E/SMD     (  242): DCD ON
,D/AmoledAdjustTimer(  732): prevTemp = 268, currTemp = 268, prevStep = 4, currStep = 4
,D/BatteryService(  732): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:5, charge type:1, power sharing:false
,D/BatteryService(  732): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  732): stay LED for fully charged
,D/UiModeManager(  732): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  242): DCD ON
,D/SSRMv2:SIOP(  732): SIOP:: AP = 300, Delta = 0
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,D/AmoledAdjustTimer(  732): prevTemp = 268, currTemp = 268, prevStep = 4, currStep = 4
,E/SMD     (  242): DCD ON
,D/SSRMv2:SIOP(  732): SIOP:: AP = 300, Delta = 0
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,D/AmoledAdjustTimer(  732): prevTemp = 268, currTemp = 268, prevStep = 4, currStep = 4
,V/AlarmManager(  732): waitForAlarm result :4
,D/LightsService(  732): [api] onReceive : SvcLEDReceiver re-enables LightSenor and sends MSG_FORCEDSVCLEDTASK
I/SensorManagerA(  732): getReportingMode :: sensor.mType = 5
D/Sensors (  732): LightSensor setDelay = 200000000
D/Sensors (  732): LightSensor setSensorDelay = 200000000
D/Sensors (  732): Light sensor flush: not enabled 0
D/Sensors (  732): LightSensor enable = 1
D/Sensors (  732): LightSensor enableSensor = 1
D/SensorManager(  732): registerListener :: 16, CM36686 Light Sensor, 200000, 0,  
,V/AlarmManager(  732): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,D/BatteryService(  732): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:4, charge type:1, power sharing:false
,D/BatteryService(  732): stay LED for fully charged
,D/Finsky  ( 3452): [1] DailyHygiene.onStartCommand: Beginning daily hygiene
V/AlarmManager(  732): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,D/BatteryService(  732): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  732): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
,D/Sensors (  732): LightSensor enable = 0
,D/Sensors (  732): LightSensor enableSensor = 0
,D/SensorManager(  732): unregisterListener ::   
D/LightsService(  732): [SvcLED]  onSensorChanged::light value = 0
D/LightsService(  732): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,V/GLSActivity( 1304): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1304): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/EventLogService( 1781): Aggregate from 1453855723307 (log), 1453855723307 (data)
,I/System.out( 3452): Thread-336 calls detatch()
,W/Finsky  ( 3452): [1] DailyHygiene$1.onErrorResponse: Unable to preload experiments: com.android.volley.NoConnectionError: java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
,V/GLSActivity( 1304): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1304): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/System.out( 3452): Thread-337 calls detatch()
,V/GLSActivity( 1304): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1304): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/System.out( 3452): Thread-336 calls detatch()
,W/Finsky  ( 3452): [1] LibraryUpdateListener.onErrorResponse: Library replication failed: com.android.volley.NoConnectionError: java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
,D/dalvikvm( 3452): GC_CONCURRENT freed 2005K, 42% free 11044K/19028K, paused 4ms+4ms, total 35ms
,D/dalvikvm( 3452): WAIT_FOR_CONCURRENT_GC blocked 13ms
,V/GLSActivity( 1304): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1304): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/System.out( 3452): Thread-337 calls detatch()
,W/Finsky  ( 3452): [1] UpdateChecker$1$2.onErrorResponse: Update check failed: com.android.volley.NoConnectionError: java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
,D/Finsky  ( 3452): [1] DailyHygiene.access$600: Logging device features
,V/AlarmManager(  732): waitForAlarm result :4
,V/AlarmManager(  732): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,D/Finsky  ( 3452): [1] DailyHygiene.reschedule: Scheduling new run in 31 minutes (failures=2)
,D/WearableService( 1216): callingUid 10011, callindPid: 1216
,D/DeviceConnectionService( 1216): client connected with version: 8296000
,D/Finsky  ( 3452): [1] VerifyInstalledPackagesReceiver.onReceive: Skipping verification because network inactive
,D/Finsky  ( 3452): [1] WearSupportService$8.onConnectionFailed: onConnectionFailed: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/Finsky  ( 3452): [1] WearSupportService.access$100: Dropping command=hygiene due to Gms not connected
,D/Finsky  ( 3452): [365] FlushLogsService.onHandleIntent: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,V/GLSActivity( 1304): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1304): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/SMD     (  242): DCD ON
,D/SSRMv2:SIOP(  732): SIOP:: AP = 300, Delta = 0
,E/SMD     (  242): DCD ON
,E/Watchdog(  732): !@Sync 23
,E/SMD     (  242): DCD ON
,D/AmoledAdjustTimer(  732): prevTemp = 268, currTemp = 268, prevStep = 4, currStep = 4
,E/SMD     (  242): DCD ON
,D/SSRMv2:SIOP(  732): SIOP:: AP = 300, Delta = 0
,E/SMD     (  242): DCD ON
,V/AlarmManager(  732): waitForAlarm result :4
,V/AlarmManager(  732): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,D/BatteryService(  732): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:2, charge type:1, power sharing:false
,D/BatteryService(  732): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  732): stay LED for fully charged
,D/UiModeManager(  732): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
,D/dalvikvm( 3452): GC_CONCURRENT freed 1825K, 42% free 11187K/19028K, paused 10ms+12ms, total 105ms
,D/Finsky  ( 3452): [349] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 3452): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,E/SMD     (  242): DCD ON
,D/AmoledAdjustTimer(  732): prevTemp = 268, currTemp = 268, prevStep = 4, currStep = 4
,V/AlarmManager(  732): waitForAlarm result :8
,V/AlarmManager(  732): ClockReceiver onReceive() ACTION_TIME_TICK
,V/AlarmManager(  732): ___SyncScheduler (v3) ACTIVATED___
,V/AlarmManager(  732): <AppSync3 Whitelist>
,V/AlarmManager(  732): (AppSync) ### 0 added ###
D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.TIME_TICK
D/KeyguardUpdateMonitor( 1065): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  242): DCD ON
,D/SSRMv2:SIOP(  732): SIOP:: AP = 300, Delta = 0
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,D/AmoledAdjustTimer(  732): prevTemp = 268, currTemp = 268, prevStep = 4, currStep = 4
,E/SMD     (  242): DCD ON
,D/SSRMv2:SIOP(  732): SIOP:: AP = 300, Delta = 0
,E/SMD     (  242): DCD ON
,D/BatteryService(  732): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:3, charge type:1, power sharing:false
,D/BatteryService(  732): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  732): stay LED for fully charged
,D/UiModeManager(  732): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
,E/Watchdog(  732): !@Sync 24
,E/SMD     (  242): DCD ON
,D/AmoledAdjustTimer(  732): prevTemp = 268, currTemp = 268, prevStep = 4, currStep = 4
,I/PowerManagerService(  732): [PWL] Off : 680s ago
,E/SMD     (  242): DCD ON
,D/SSRMv2:SIOP(  732): SIOP:: AP = 300, Delta = 0
,E/SMD     (  242): DCD ON
,D/BatteryService(  732): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-8, charge type:1, power sharing:false
,D/BatteryService(  732): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  732): stay LED for fully charged
,D/UiModeManager(  732): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  242): DCD ON
,D/AmoledAdjustTimer(  732): prevTemp = 268, currTemp = 268, prevStep = 4, currStep = 4
,E/SMD     (  242): DCD ON
,D/SSRMv2:SIOP(  732): SIOP:: AP = 300, Delta = 0
,E/SMD     (  242): DCD ON
,D/BatteryService(  732): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-6, charge type:1, power sharing:false
,D/BatteryService(  732): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  732): mCoverManager.getCoverState() : true
,D/BatteryService(  732): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,D/AmoledAdjustTimer(  732): prevTemp = 268, currTemp = 268, prevStep = 4, currStep = 4
,E/SMD     (  242): DCD ON
,D/SSRMv2:SIOP(  732): SIOP:: AP = 300, Delta = 0
,E/SMD     (  242): DCD ON
,D/BatteryService(  732): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-8, charge type:1, power sharing:false
,D/BatteryService(  732): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  732): stay LED for fully charged
,D/UiModeManager(  732): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
,E/Watchdog(  732): !@Sync 25
,E/SMD     (  242): DCD ON
,D/AmoledAdjustTimer(  732): prevTemp = 268, currTemp = 268, prevStep = 4, currStep = 4
,E/SMD     (  242): DCD ON
,D/SSRMv2:SIOP(  732): SIOP:: AP = 300, Delta = 0
,E/SMD     (  242): DCD ON
,D/BatteryService(  732): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:3, charge type:1, power sharing:false
,D/BatteryService(  732): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  732): stay LED for fully charged
,D/UiModeManager(  732): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  242): DCD ON
,D/AmoledAdjustTimer(  732): prevTemp = 268, currTemp = 268, prevStep = 4, currStep = 4
,V/AlarmManager(  732): waitForAlarm result :8
,V/AlarmManager(  732): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1065): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  242): DCD ON
,D/SSRMv2:SIOP(  732): SIOP:: AP = 300, Delta = 0
,E/SMD     (  242): DCD ON
,D/BatteryService(  732): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService(  732): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  732): stay LED for fully charged
,D/UiModeManager(  732): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,D/AmoledAdjustTimer(  732): prevTemp = 268, currTemp = 268, prevStep = 4, currStep = 4
,E/SMD     (  242): DCD ON
,D/SSRMv2:SIOP(  732): SIOP:: AP = 300, Delta = 0
,E/SMD     (  242): DCD ON
,D/BatteryService(  732): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService(  732): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  732): mCoverManager.getCoverState() : true
,D/BatteryService(  732): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
,E/Watchdog(  732): !@Sync 26
,E/SMD     (  242): DCD ON
,D/AmoledAdjustTimer(  732): prevTemp = 268, currTemp = 267, prevStep = 4, currStep = 4
,E/SMD     (  242): DCD ON
,D/SSRMv2:SIOP(  732): SIOP:: AP = 300, Delta = 0
,E/SMD     (  242): DCD ON
,D/BatteryService(  732): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:2, charge type:1, power sharing:false
,D/BatteryService(  732): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  732): mCoverManager.getCoverState() : true
,D/BatteryService(  732): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  242): DCD ON
,D/AmoledAdjustTimer(  732): prevTemp = 267, currTemp = 267, prevStep = 4, currStep = 4
,E/SMD     (  242): DCD ON
,D/SSRMv2:SIOP(  732): SIOP:: AP = 300, Delta = 0
,E/SMD     (  242): DCD ON
,D/BatteryService(  732): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  732): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  732): mCoverManager.getCoverState() : true
,D/BatteryService(  732): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,D/AmoledAdjustTimer(  732): prevTemp = 267, currTemp = 267, prevStep = 4, currStep = 4
,E/SMD     (  242): DCD ON
,D/SSRMv2:SIOP(  732): SIOP:: AP = 300, Delta = 0
,I/PowerManagerService(  732): [PWL] Off : 765s ago
,E/SMD     (  242): DCD ON
,D/BatteryService(  732): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:3, charge type:1, power sharing:false
,D/BatteryService(  732): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  732): stay LED for fully charged
,D/UiModeManager(  732): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
,E/Watchdog(  732): !@Sync 27
,E/SMD     (  242): DCD ON
,D/AmoledAdjustTimer(  732): prevTemp = 267, currTemp = 267, prevStep = 4, currStep = 4
,E/SMD     (  242): DCD ON
,D/SSRMv2:SIOP(  732): SIOP:: AP = 300, Delta = 0
,D/dalvikvm(  732): GC_CONCURRENT freed 3292K, 59% free 23482K/56812K, paused 21ms+40ms, total 421ms
,E/SMD     (  242): DCD ON
,D/BatteryService(  732): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:3, charge type:1, power sharing:false
,D/BatteryService(  732): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  732): stay LED for fully charged
,D/UiModeManager(  732): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  242): DCD ON
,D/AmoledAdjustTimer(  732): prevTemp = 267, currTemp = 267, prevStep = 4, currStep = 4
,V/AlarmManager(  732): waitForAlarm result :8
,V/AlarmManager(  732): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1065): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  242): DCD ON
,D/SSRMv2:SIOP(  732): SIOP:: AP = 300, Delta = 0
,E/SMD     (  242): DCD ON
,D/BatteryService(  732): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-9, charge type:1, power sharing:false
,D/BatteryService(  732): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  732): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
D/BatteryService(  732): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,D/AmoledAdjustTimer(  732): prevTemp = 267, currTemp = 267, prevStep = 4, currStep = 4
,E/SMD     (  242): DCD ON
,D/SSRMv2:SIOP(  732): SIOP:: AP = 300, Delta = 0
,E/SMD     (  242): DCD ON
,E/Watchdog(  732): !@Sync 28
,E/SMD     (  242): DCD ON
,D/AmoledAdjustTimer(  732): prevTemp = 267, currTemp = 267, prevStep = 4, currStep = 4
,E/SMD     (  242): DCD ON
,D/SSRMv2:SIOP(  732): SIOP:: AP = 300, Delta = 0
,E/SMD     (  242): DCD ON
,D/BatteryService(  732): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:3, charge type:1, power sharing:false
,D/BatteryService(  732): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  732): stay LED for fully charged
,D/UiModeManager(  732): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  242): DCD ON
,D/AmoledAdjustTimer(  732): prevTemp = 267, currTemp = 267, prevStep = 4, currStep = 4
,E/SMD     (  242): DCD ON
,D/SSRMv2:SIOP(  732): SIOP:: AP = 300, Delta = 0
,E/SMD     (  242): DCD ON
,D/BatteryService(  732): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService(  732): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  732): stay LED for fully charged
,D/UiModeManager(  732): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,D/AmoledAdjustTimer(  732): prevTemp = 267, currTemp = 267, prevStep = 4, currStep = 4
,E/SMD     (  242): DCD ON
,D/SSRMv2:SIOP(  732): SIOP:: AP = 300, Delta = 0
,E/SMD     (  242): DCD ON
,E/Watchdog(  732): !@Sync 29
,E/SMD     (  242): DCD ON
,D/AmoledAdjustTimer(  732): prevTemp = 267, currTemp = 267, prevStep = 4, currStep = 4
,E/SMD     (  242): DCD ON
,D/SSRMv2:SIOP(  732): SIOP:: AP = 300, Delta = 0
,E/SMD     (  242): DCD ON
,D/BatteryService(  732): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-8, charge type:1, power sharing:false
,D/BatteryService(  732): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  732): stay LED for fully charged
,D/UiModeManager(  732): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  242): DCD ON
,D/AmoledAdjustTimer(  732): prevTemp = 267, currTemp = 267, prevStep = 4, currStep = 4
,V/AlarmManager(  732): waitForAlarm result :8
,V/AlarmManager(  732): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1065): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  242): DCD ON
,D/SSRMv2:SIOP(  732): SIOP:: AP = 300, Delta = 0
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,D/BatteryService(  732): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-7, charge type:1, power sharing:false
,D/BatteryService(  732): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  732): mCoverManager.getCoverState() : true
,D/BatteryService(  732): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  242): DCD ON
,D/AmoledAdjustTimer(  732): prevTemp = 267, currTemp = 267, prevStep = 4, currStep = 4
,D/TimaService(  732): TIMA: TimaService scheduler is intialized. 
,D/TimaService(  732): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService(  732): TimaServiceHandler.handleMessage what =1
,E/SMD     (  242): DCD ON
,D/SSRMv2:SIOP(  732): SIOP:: AP = 300, Delta = 0
,I/PowerManagerService(  732): [PWL] Off : 855s ago
,I/PowerManagerService(  732): [PWL]   PowerManagerService.WakeLocks: ref count=1
,I/PowerManagerService(  732): [PWL]     mWakeLockSummary : 0x1
,I/PowerManagerService(  732): [PWL]       PARTIAL_WAKE_LOCK              'TimaService' (uid=1000, pid=732, ws=null) (elapsedTime=3599)
,I/TLC_TIMA_PKM_measure_kernel(  732): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel(  732): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService(  732): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService(  732): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/SMD     (  242): DCD ON
,D/BatteryService(  732): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-7, charge type:1, power sharing:false
,D/BatteryService(  732): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  732): stay LED for fully charged
,D/UiModeManager(  732): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
,E/Watchdog(  732): !@Sync 30
,E/SMD     (  242): DCD ON
,D/AmoledAdjustTimer(  732): prevTemp = 267, currTemp = 267, prevStep = 4, currStep = 4
,E/SMD     (  242): DCD ON
,D/SSRMv2:SIOP(  732): SIOP:: AP = 300, Delta = 0
,E/SMD     (  242): DCD ON
,D/BatteryService(  732): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  732): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  732): stay LED for fully charged
,D/UiModeManager(  732): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  242): DCD ON
,D/AmoledAdjustTimer(  732): prevTemp = 267, currTemp = 267, prevStep = 4, currStep = 4
,E/SMD     (  242): DCD ON
,D/SSRMv2:SIOP(  732): SIOP:: AP = 300, Delta = 0
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,D/AmoledAdjustTimer(  732): prevTemp = 267, currTemp = 267, prevStep = 4, currStep = 4
,E/SMD     (  242): DCD ON
,D/SSRMv2:SIOP(  732): SIOP:: AP = 300, Delta = 0
,E/SMD     (  242): DCD ON
,E/Watchdog(  732): !@Sync 31
,V/GLSActivity( 1304): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1304): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/SMD     (  242): DCD ON
,D/AmoledAdjustTimer(  732): prevTemp = 267, currTemp = 267, prevStep = 4, currStep = 4
,E/SMD     (  242): DCD ON
,D/SSRMv2:SIOP(  732): SIOP:: AP = 300, Delta = 0
,E/SMD     (  242): DCD ON
,D/BatteryService(  732): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-9, charge type:1, power sharing:false
,D/BatteryService(  732): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  732): stay LED for fully charged
,D/UiModeManager(  732): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  242): DCD ON
,D/AmoledAdjustTimer(  732): prevTemp = 267, currTemp = 267, prevStep = 4, currStep = 4
,V/AlarmManager(  732): waitForAlarm result :8
,V/AlarmManager(  732): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1065): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,D/SSRMv2:SIOP(  732): SIOP:: AP = 300, Delta = 0
,E/SMD     (  242): DCD ON
,D/BatteryService(  732): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-11, charge type:1, power sharing:false
,D/BatteryService(  732): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  732): stay LED for fully charged
,D/UiModeManager(  732): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  242): DCD ON
,D/AmoledAdjustTimer(  732): prevTemp = 267, currTemp = 267, prevStep = 4, currStep = 4
,E/SMD     (  242): DCD ON
,D/SSRMv2:SIOP(  732): SIOP:: AP = 300, Delta = 0
,E/SMD     (  242): DCD ON
,D/BatteryService(  732): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-5, charge type:1, power sharing:false
,D/BatteryService(  732): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  732): stay LED for fully charged
,D/UiModeManager(  732): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
,E/Watchdog(  732): !@Sync 32
,E/SMD     (  242): DCD ON
,D/AmoledAdjustTimer(  732): prevTemp = 267, currTemp = 267, prevStep = 4, currStep = 4
,E/SMD     (  242): DCD ON
,D/SSRMv2:SIOP(  732): SIOP:: AP = 300, Delta = 0
,E/SMD     (  242): DCD ON
,D/BatteryService(  732): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-3, charge type:1, power sharing:false
,D/BatteryService(  732): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  732): mCoverManager.getCoverState() : true
,D/BatteryService(  732): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  242): DCD ON
,D/AmoledAdjustTimer(  732): prevTemp = 267, currTemp = 267, prevStep = 4, currStep = 4
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,D/SSRMv2:SIOP(  732): SIOP:: AP = 300, Delta = 0
,E/SMD     (  242): DCD ON
,D/BatteryService(  732): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-5, charge type:1, power sharing:false
,D/BatteryService(  732): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  732): stay LED for fully charged
,D/UiModeManager(  732): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  242): DCD ON
,D/AmoledAdjustTimer(  732): prevTemp = 267, currTemp = 267, prevStep = 4, currStep = 4
,E/SMD     (  242): DCD ON
,D/SSRMv2:SIOP(  732): SIOP:: AP = 300, Delta = 0
,E/SMD     (  242): DCD ON
,D/BatteryService(  732): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-4, charge type:1, power sharing:false
,D/BatteryService(  732): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  732): stay LED for fully charged
,D/UiModeManager(  732): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
,E/Watchdog(  732): !@Sync 33
,E/SMD     (  242): DCD ON
,D/AmoledAdjustTimer(  732): prevTemp = 267, currTemp = 267, prevStep = 4, currStep = 4
,I/PowerManagerService(  732): [PWL] Off : 950s ago
,E/SMD     (  242): DCD ON
,D/SSRMv2:SIOP(  732): SIOP:: AP = 300, Delta = 0
,E/SMD     (  242): DCD ON
,D/BatteryService(  732): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-10, charge type:1, power sharing:false
,D/BatteryService(  732): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  732): stay LED for fully charged
,D/UiModeManager(  732): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  242): DCD ON
,D/AmoledAdjustTimer(  732): prevTemp = 267, currTemp = 267, prevStep = 4, currStep = 4
,V/AlarmManager(  732): waitForAlarm result :8
,V/AlarmManager(  732): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1065): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,D/SSRMv2:SIOP(  732): SIOP:: AP = 300, Delta = 0
,E/SMD     (  242): DCD ON
,D/BatteryService(  732): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-9, charge type:1, power sharing:false
,D/BatteryService(  732): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  732): mCoverManager.getCoverState() : true
,D/BatteryService(  732): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  242): DCD ON
,D/AmoledAdjustTimer(  732): prevTemp = 267, currTemp = 267, prevStep = 4, currStep = 4
,E/SMD     (  242): DCD ON
,D/SSRMv2:SIOP(  732): SIOP:: AP = 300, Delta = 0
,E/SMD     (  242): DCD ON
,D/BatteryService(  732): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-10, charge type:1, power sharing:false
,D/BatteryService(  732): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  732): mCoverManager.getCoverState() : true
,D/BatteryService(  732): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
,E/Watchdog(  732): !@Sync 34
,E/SMD     (  242): DCD ON
,D/AmoledAdjustTimer(  732): prevTemp = 267, currTemp = 267, prevStep = 4, currStep = 4
,E/SMD     (  242): DCD ON
,D/SSRMv2:SIOP(  732): SIOP:: AP = 300, Delta = 0
,E/SMD     (  242): DCD ON
,D/BatteryService(  732): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-9, charge type:1, power sharing:false
,D/BatteryService(  732): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  732): mCoverManager.getCoverState() : true
,D/BatteryService(  732): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  242): DCD ON
,D/AmoledAdjustTimer(  732): prevTemp = 267, currTemp = 267, prevStep = 4, currStep = 4
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,D/SSRMv2:SIOP(  732): SIOP:: AP = 300, Delta = 0
,E/SMD     (  242): DCD ON
,D/BatteryService(  732): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-9, charge type:1, power sharing:false
,D/BatteryService(  732): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  732): mCoverManager.getCoverState() : true
,D/BatteryService(  732): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  242): DCD ON
,D/AmoledAdjustTimer(  732): prevTemp = 267, currTemp = 267, prevStep = 4, currStep = 4
,E/SMD     (  242): DCD ON
,D/SSRMv2:SIOP(  732): SIOP:: AP = 300, Delta = 0
,E/SMD     (  242): DCD ON
,E/Watchdog(  732): !@Sync 35
,D/BatteryService(  732): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-9, charge type:1, power sharing:false
,D/BatteryService(  732): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  732): stay LED for fully charged
,D/UiModeManager(  732): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  242): DCD ON
,D/AmoledAdjustTimer(  732): prevTemp = 267, currTemp = 267, prevStep = 4, currStep = 4
,E/SMD     (  242): DCD ON
,D/SSRMv2:SIOP(  732): SIOP:: AP = 300, Delta = 0
,E/SMD     (  242): DCD ON
,D/BatteryService(  732): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:4, charge type:1, power sharing:false
,D/BatteryService(  732): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  732): stay LED for fully charged
,D/UiModeManager(  732): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  242): DCD ON
,D/AmoledAdjustTimer(  732): prevTemp = 267, currTemp = 267, prevStep = 4, currStep = 4
,V/AlarmManager(  732): waitForAlarm result :8
,V/AlarmManager(  732): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1065): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,D/SSRMv2:SIOP(  732): SIOP:: AP = 300, Delta = 0
,E/SMD     (  242): DCD ON
,D/BatteryService(  732): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:3, charge type:1, power sharing:false
,D/BatteryService(  732): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  732): stay LED for fully charged
,D/UiModeManager(  732): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  242): DCD ON
,D/AmoledAdjustTimer(  732): prevTemp = 267, currTemp = 267, prevStep = 4, currStep = 4
,E/SMD     (  242): DCD ON
,D/SSRMv2:SIOP(  732): SIOP:: AP = 300, Delta = 0
,E/SMD     (  242): DCD ON
,E/Watchdog(  732): !@Sync 36
,D/BatteryService(  732): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:4, charge type:1, power sharing:false
,D/BatteryService(  732): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  732): mCoverManager.getCoverState() : true
,D/BatteryService(  732): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  242): DCD ON
,D/AmoledAdjustTimer(  732): prevTemp = 267, currTemp = 267, prevStep = 4, currStep = 4
,E/SMD     (  242): DCD ON
,D/SSRMv2:SIOP(  732): SIOP:: AP = 300, Delta = 0
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,D/BatteryService(  732): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:4, charge type:1, power sharing:false
,D/BatteryService(  732): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  732): mCoverManager.getCoverState() : true
,D/BatteryService(  732): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
,D/AmoledAdjustTimer(  732): prevTemp = 267, currTemp = 266, prevStep = 4, currStep = 4
,I/PowerManagerService(  732): [PWL] Off : 1050s ago
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,D/SSRMv2:SIOP(  732): SIOP:: AP = 300, Delta = 0
,E/SMD     (  242): DCD ON
,D/BatteryService(  732): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:5, charge type:1, power sharing:false
,D/BatteryService(  732): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  732): stay LED for fully charged
,D/UiModeManager(  732): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  242): DCD ON
,D/AmoledAdjustTimer(  732): prevTemp = 266, currTemp = 266, prevStep = 4, currStep = 4
,E/SMD     (  242): DCD ON
,D/SSRMv2:SIOP(  732): SIOP:: AP = 300, Delta = 0
,E/SMD     (  242): DCD ON
,E/Watchdog(  732): !@Sync 37
,D/BatteryService(  732): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:3, charge type:1, power sharing:false
,D/BatteryService(  732): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  732): stay LED for fully charged
,D/UiModeManager(  732): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  242): DCD ON
,D/AmoledAdjustTimer(  732): prevTemp = 266, currTemp = 266, prevStep = 4, currStep = 4
,E/SMD     (  242): DCD ON
,D/SSRMv2:SIOP(  732): SIOP:: AP = 300, Delta = 0
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,D/BatteryService(  732): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-14, charge type:1, power sharing:false
,D/BatteryService(  732): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  732): mCoverManager.getCoverState() : true
,D/BatteryService(  732): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
,D/AmoledAdjustTimer(  732): prevTemp = 266, currTemp = 266, prevStep = 4, currStep = 4
,V/AlarmManager(  732): waitForAlarm result :8
,V/AlarmManager(  732): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1065): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,D/SSRMv2:SIOP(  732): SIOP:: AP = 300, Delta = 0
,E/SMD     (  242): DCD ON
,D/BatteryService(  732): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-12, charge type:1, power sharing:false
,D/BatteryService(  732): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  732): stay LED for fully charged
,D/UiModeManager(  732): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  242): DCD ON
,D/AmoledAdjustTimer(  732): prevTemp = 266, currTemp = 266, prevStep = 4, currStep = 4
,E/SMD     (  242): DCD ON
,D/SSRMv2:SIOP(  732): SIOP:: AP = 300, Delta = 0
,E/SMD     (  242): DCD ON
,E/Watchdog(  732): !@Sync 38
,E/SMD     (  242): DCD ON
,D/AmoledAdjustTimer(  732): prevTemp = 266, currTemp = 266, prevStep = 4, currStep = 4
,E/SMD     (  242): DCD ON
,D/SSRMv2:SIOP(  732): SIOP:: AP = 300, Delta = 0
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,D/BatteryService(  732): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  732): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  732): stay LED for fully charged
,D/UiModeManager(  732): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
,D/AmoledAdjustTimer(  732): prevTemp = 266, currTemp = 266, prevStep = 4, currStep = 4
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,D/SSRMv2:SIOP(  732): SIOP:: AP = 300, Delta = 0
,E/SMD     (  242): DCD ON
,D/BatteryService(  732): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  732): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  732): mCoverManager.getCoverState() : true
,D/BatteryService(  732): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  242): DCD ON
,D/AmoledAdjustTimer(  732): prevTemp = 266, currTemp = 266, prevStep = 4, currStep = 4
,E/SMD     (  242): DCD ON
,D/SSRMv2:SIOP(  732): SIOP:: AP = 300, Delta = 0
,E/SMD     (  242): DCD ON
,E/Watchdog(  732): !@Sync 39
,D/BatteryService(  732): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  732): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  732): mCoverManager.getCoverState() : true
,D/BatteryService(  732): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  242): DCD ON
,D/AmoledAdjustTimer(  732): prevTemp = 266, currTemp = 266, prevStep = 4, currStep = 4
,E/SMD     (  242): DCD ON
,D/SSRMv2:SIOP(  732): SIOP:: AP = 300, Delta = 0
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,D/BatteryService(  732): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-10, charge type:1, power sharing:false
,D/BatteryService(  732): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  732): stay LED for fully charged
,D/UiModeManager(  732): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
,D/AmoledAdjustTimer(  732): prevTemp = 266, currTemp = 266, prevStep = 4, currStep = 4
,V/AlarmManager(  732): waitForAlarm result :8
,V/AlarmManager(  732): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1065): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,D/SSRMv2:SIOP(  732): SIOP:: AP = 300, Delta = 0
,E/SMD     (  242): DCD ON
,D/BatteryService(  732): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-6, charge type:1, power sharing:false
,D/BatteryService(  732): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  732): stay LED for fully charged
,D/UiModeManager(  732): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  242): DCD ON
,D/AmoledAdjustTimer(  732): prevTemp = 266, currTemp = 266, prevStep = 4, currStep = 4
,D/TimaService(  732): TIMA: TimaService scheduler is intialized. 
,D/TimaService(  732): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService(  732): TimaServiceHandler.handleMessage what =1
,E/SMD     (  242): DCD ON
,D/SSRMv2:SIOP(  732): SIOP:: AP = 300, Delta = 0
,I/PowerManagerService(  732): [PWL] Off : 1155s ago
,I/PowerManagerService(  732): [PWL]   PowerManagerService.WakeLocks: ref count=1
,I/PowerManagerService(  732): [PWL]     mWakeLockSummary : 0x1
,I/PowerManagerService(  732): [PWL]       PARTIAL_WAKE_LOCK              'TimaService' (uid=1000, pid=732, ws=null) (elapsedTime=3608)
,I/TLC_TIMA_PKM_measure_kernel(  732): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel(  732): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService(  732): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService(  732): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/SMD     (  242): DCD ON
,E/Watchdog(  732): !@Sync 40
,D/BatteryService(  732): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-8, charge type:1, power sharing:false
,D/BatteryService(  732): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  732): mCoverManager.getCoverState() : true
,D/BatteryService(  732): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  242): DCD ON
,D/AmoledAdjustTimer(  732): prevTemp = 266, currTemp = 266, prevStep = 4, currStep = 4
,E/SMD     (  242): DCD ON
,D/SSRMv2:SIOP(  732): SIOP:: AP = 300, Delta = 0
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,D/BatteryService(  732): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-11, charge type:1, power sharing:false
,D/BatteryService(  732): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  732): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
D/BatteryService(  732): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
,D/AmoledAdjustTimer(  732): prevTemp = 266, currTemp = 266, prevStep = 4, currStep = 4
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,D/SSRMv2:SIOP(  732): SIOP:: AP = 300, Delta = 0
,E/SMD     (  242): DCD ON
,D/BatteryService(  732): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-10, charge type:1, power sharing:false
,D/BatteryService(  732): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  732): mCoverManager.getCoverState() : true
,D/BatteryService(  732): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  242): DCD ON
,D/AmoledAdjustTimer(  732): prevTemp = 266, currTemp = 266, prevStep = 4, currStep = 4
,E/SMD     (  242): DCD ON
,D/SSRMv2:SIOP(  732): SIOP:: AP = 300, Delta = 0
,E/SMD     (  242): DCD ON
,E/Watchdog(  732): !@Sync 41
,V/GLSActivity( 1304): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1304): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/SMD     (  242): DCD ON
,D/AmoledAdjustTimer(  732): prevTemp = 266, currTemp = 266, prevStep = 4, currStep = 4
,E/SMD     (  242): DCD ON
,D/SSRMv2:SIOP(  732): SIOP:: AP = 300, Delta = 0
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,D/BatteryService(  732): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-6, charge type:1, power sharing:false
,D/BatteryService(  732): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  732): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
D/BatteryService(  732): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
,D/AmoledAdjustTimer(  732): prevTemp = 266, currTemp = 266, prevStep = 4, currStep = 4
,V/AlarmManager(  732): waitForAlarm result :8
,V/AlarmManager(  732): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1065): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,D/SSRMv2:SIOP(  732): SIOP:: AP = 300, Delta = 0
,E/SMD     (  242): DCD ON
,D/BatteryService(  732): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-10, charge type:1, power sharing:false
,D/BatteryService(  732): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  732): mCoverManager.getCoverState() : true
,D/BatteryService(  732): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  242): DCD ON
,D/AmoledAdjustTimer(  732): prevTemp = 266, currTemp = 266, prevStep = 4, currStep = 4
,E/SMD     (  242): DCD ON
,D/SSRMv2:SIOP(  732): SIOP:: AP = 300, Delta = 0
,E/SMD     (  242): DCD ON
,E/Watchdog(  732): !@Sync 42
,D/BatteryService(  732): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-8, charge type:1, power sharing:false
,D/BatteryService(  732): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  732): stay LED for fully charged
,D/UiModeManager(  732): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  242): DCD ON
,D/AmoledAdjustTimer(  732): prevTemp = 266, currTemp = 266, prevStep = 4, currStep = 4
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,D/SSRMv2:SIOP(  732): SIOP:: AP = 300, Delta = 0
,E/SMD     (  242): DCD ON
,D/BatteryService(  732): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:3, charge type:1, power sharing:false
,D/BatteryService(  732): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  732): mCoverManager.getCoverState() : true
,D/BatteryService(  732): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
,D/AmoledAdjustTimer(  732): prevTemp = 266, currTemp = 266, prevStep = 4, currStep = 4
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,D/SSRMv2:SIOP(  732): SIOP:: AP = 300, Delta = 0
,E/SMD     (  242): DCD ON
,E/SMD     (  242): DCD ON
,V/AlarmManager(  732): waitForAlarm result :8
,D/LightsService(  732): [api] onReceive : SvcLEDReceiver re-enables LightSenor and sends MSG_FORCEDSVCLEDTASK
I/SensorManagerA(  732): getReportingMode :: sensor.mType = 5
D/Sensors (  732): LightSensor setDelay = 200000000
D/Sensors (  732): LightSensor setSensorDelay = 200000000
D/Sensors (  732): Light sensor flush: not enabled 0
D/Sensors (  732): LightSensor enable = 1
D/Sensors (  732): LightSensor enableSensor = 1
D/SensorManager(  732): registerListener :: 16, CM36686 Light Sensor, 200000, 0,  
,D/BatteryService(  732): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:5, charge type:1, power sharing:false
,D/BatteryService(  732): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  732): stay LED for fully charged
,D/UiModeManager(  732): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
,D/AmoledAdjustTimer(  732): prevTemp = 266, currTemp = 266, prevStep = 4, currStep = 4
,D/Sensors (  732): LightSensor enable = 0
,D/Sensors (  732): LightSensor enableSensor = 0
,D/SensorManager(  732): unregisterListener ::   
D/LightsService(  732): [SvcLED]  onSensorChanged::light value = 0
D/LightsService(  732): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,TIME-OUT KILL (timeout was 1200000ms),D/dalvikvm(  732): GC_CONCURRENT freed 3468K, 59% free 23410K/56564K, paused 32ms+40ms, total 432ms
D/AndroidRuntime( 5069): 
D/AndroidRuntime( 5069): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 5069): CheckJNI is OFF
D/AndroidRuntime( 5069): setted country_code = Poland
D/AndroidRuntime( 5069): setted countryiso_code = PL
D/AndroidRuntime( 5069): setted sales_code = XEO
D/AndroidRuntime( 5069): readGMSProperty: start
D/AndroidRuntime( 5069): readGMSProperty: already setted!!
D/AndroidRuntime( 5069): readGMSProperty: end
D/AndroidRuntime( 5069): addProductProperty: start
D/dalvikvm( 5069): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 5069): Added shared lib libjavacore.so 0x0
D/dalvikvm( 5069): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 5069): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 5069): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
E/memtrack( 5069): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 5069): failed to load memtrack module: -2
D/dalvikvm( 5069): Note: class Landroid/app/ActivityManagerNative; has 192 unimplemented (abstract) methods
D/AndroidRuntime( 5069): Calling main entry com.android.commands.pm.Pm
D/PackageManagerService(  732): deletePackageAsUser- pkg:com.test.thalitest, userId:0
D/PersonaManagerService(  732): isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
D/PersonaManagerService(  732): isFromApprovedUnInstaller: isApproved : true
D/PersonaManagerService(  732): isFromApprovedUnInstaller: isApproved before exit: true
D/PackageManager(  732): deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag3
D/PackageManager(  732): deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag3
D/PackageManager(  732): START PACKAGE DELETE: observer{1147585984}
D/PackageManager(  732): pkg{<packageName>}
D/PackageManager(  732): user{0}
D/PackageManager(  732): deletePackageAsUser : uid = 2000 userId = 0
D/PackageManagerService(  732): deletePackage- pkg:com.test.thalitest, edmuserId:0
D/PackageManagerService(  732): deletePackage- pkg:com.test.thalitest, edmuserId:-1
D/ApplicationPolicy(  732): getApplicationUninstallationEnabled
D/ApplicationPolicy(  732): getApplicationUninstallationEnabled :  enabled true
D/PackageManagerService(  732): deletePackageX- pkg:com.test.thalitest, userId:0
D/PackageManager(  732): [MSG] DELETE_PACKAGE_AS_USER
D/PackageManager(  732): !@killApplicatoin: 10179, uninstall pkg
I/ActivityManager(  732): Killing 4501:com.test.thalitest/u0a179 (adj 9): stop com.test.thalitest
D/PackageManager(  732): Sending to user 0: act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000000 Bundle[{android.intent.extra.REMOVED_FOR_ALL_USERS=true, android.intent.extra.UID=10179, android.intent.extra.DATA_REMOVED=true, android.intent.extra.user_handle=0}]
D/AdaptiveEventManager( 1065): action=android.intent.action.PACKAGE_REMOVED
I/InputReader(  732): Reconfiguring input devices.  changes=0x00000010
D/QuickConnect[1.1][2] ( 3091): SconnectManager.onReceiver - action : android.intent.action.PACKAGE_REMOVED, package : com.test.thalitest
I/PackageManager(  732):   Action: "android.intent.action.SENDTO"
I/PackageManager(  732):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  732):   Scheme: "sms"
I/PackageManager(  732): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
D/dalvikvm( 1400): GC_EXPLICIT freed 4283K, 48% free 10017K/19028K, paused 4ms+7ms, total 109ms
I/SELinux ( 5101): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5101):  
D/RCPManagerService(  732): PackageReceiver onReceive()
I/PackageManager(  732):   Action: "android.intent.action.SENDTO"
I/PackageManager(  732):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  732):   Scheme: "smsto"
I/PackageManager(  732): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
I/HarmonyEASService(  732): onReceive : android.intent.action.PACKAGE_REMOVED for 0
I/FPMS_FingerprintManagerService( 1084): onReceive: android.intent.action.PACKAGE_REMOVED
D/dalvikvm(  249): GC_EXPLICIT freed 43K, 51% free 9506K/19028K, paused 3ms+4ms, total 50ms
D/PackageManager(  732): Sending to user 0: act=android.intent.action.PACKAGE_FULLY_REMOVED dat=package:com.test.thalitest flg=0x4000000 Bundle[{android.intent.extra.REMOVED_FOR_ALL_USERS=true, android.intent.extra.UID=10179, android.intent.extra.DATA_REMOVED=true, android.intent.extra.user_handle=0}]
W/GeofencerStateMachine( 1216): Ignoring removeGeofence because network location is disabled.
D/dalvikvm(  249): GC_EXPLICIT freed <1K, 51% free 9506K/19028K, paused 4ms+4ms, total 32ms
I/SELinux ( 5101): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5101):  
I/SELinux ( 5101):  
I/SELinux ( 5101): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 5101): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 5101): >>>>> Normal User
E/dalvikvm( 5101): >>>>> com.sec.esdk.elm [ userId:0 | appId:10094 ]
E/SELinux ( 5101): [DEBUG] seapp_context_lookup: seinfoCategory = platform
D/dalvikvm(  249): GC_EXPLICIT freed <1K, 51% free 9506K/19028K, paused 3ms+5ms, total 33ms
I/PackageManager(  732):   Action: "android.intent.action.SENDTO"
I/PackageManager(  732):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  732):   Scheme: "mms"
I/PackageManager(  732): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
D/TimaKeyStoreProvider( 5101): in addTimaSignatureService
D/TimaKeyStoreProvider( 5101): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 5101): Added TimaKesytore provider
I/PackageManager(  732):   Action: "android.intent.action.SENDTO"
I/PackageManager(  732):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  732):   Scheme: "mmsto"
I/PackageManager(  732): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
D/dalvikvm( 2121): GC_EXPLICIT freed 981K, 43% free 11015K/19028K, paused 9ms+7ms, total 119ms
I/PackageManager(  732):   Action: "android.intent.action.SENDTO"
I/PackageManager(  732):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  732):   Scheme: "sms"
D/dalvikvm( 1781): GC_EXPLICIT freed 692K, 38% free 11866K/19028K, paused 137ms+30ms, total 339ms
I/PackageManager(  732): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
I/PackageManager(  732):   Action: "android.intent.action.SENDTO"
I/PackageManager(  732):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  732):   Scheme: "smsto"
I/PackageManager(  732): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
W/InputMethodInfo(  732): Duplicated subtype definition found: , voice
I/PackageManager(  732):   Action: "android.intent.action.SENDTO"
I/PackageManager(  732):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  732):   Scheme: "mms"
I/PackageManager(  732): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
W/ActivityManager(  732): Permission Denial: getCurrentUser() from pid=5101, uid=10094 requires android.permission.INTERACT_ACROSS_USERS
I/PackageManager(  732):   Action: "android.intent.action.SENDTO"
I/PackageManager(  732):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  732):   Scheme: "mmsto"
I/PackageManager(  732): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
D/elm:14132( 5101): ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
D/elm:14132( 5101): ELMEngine.ELMEngine( context ).
D/elm:14132( 5101): MDMBridge.setEnterpriseBridge()
D/elm:14132( 5101): ELMAbstractReceiver : Receive Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
D/elm:14132( 5101): ElmAgentService : onCreate()
D/elm:14132( 5101): ElmAgentService : onHandleIntent() Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
D/elm:14132( 5101): MainReceiver.listeningToPackageRemoved()
D/elm:14132( 5101): MDMBridge.getInstance()
D/elm:14132( 5101): MDMBridge.getAllLicenseInfoFromSDK()
D/elm:14132( 5101): MDMBridge.getAllLicenseInfoFromSDK()
I/SELinux ( 5115): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5115):  
D/elm:14132( 5101): MainReceiver.listeningToPackageRemoved(). SEND to KLMS. Remove All KNOX/ONS License
D/BackupManagerService(  732): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
D/elm:14132( 5101): ElmAgentService : onDestroy().
V/BackupManagerService(  732): removePackageParticipantsLocked: uid=10179 #1
D/EnterpriseDeviceManagerService(  732): Package has changed for user 0
D/EnterpriseDeviceManagerService(  732): Admin package name: com.google.android.gms
I/SELinux ( 5115): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5115):  
I/SELinux ( 5115):  
I/SELinux ( 5115): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 5115): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 5115): >>>>> Normal User
E/dalvikvm( 5115): >>>>> com.sec.android.app.mss [ userId:0 | appId:10021 ]
E/SELinux ( 5115): [DEBUG] seapp_context_lookup: seinfoCategory = platform
W/Resources(  732): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/TimaKeyStoreProvider( 5115): in addTimaSignatureService
D/TimaKeyStoreProvider( 5115): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 5115): Added TimaKesytore provider
D/dalvikvm(  732): GC_EXPLICIT freed 1971K, 59% free 23563K/56564K, paused 18ms+19ms, total 327ms
W/Resources(  732): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/PackageManager(  732): delete sourFile : 
D/PackageManager(  732): delete native library directory: 
D/PackageManager(  732): return delete result to caller: 1147585984
D/AndroidRuntime( 5069): Shutting down VM
W/Resources(  732): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/dalvikvm( 5069): GC_CONCURRENT freed 96K, 14% free 670K/772K, paused 1ms+0ms, total 4ms
D/PackageManager(  732): returnCode: 1
W/Resources(  732): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
I/PackageManager(  732):   Action: "android.intent.action.SENDTO"
I/PackageManager(  732):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  732):   Scheme: "sms"
I/PackageManager(  732): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
I/PackageManager(  732):   Action: "android.intent.action.SENDTO"
I/PackageManager(  732):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  732):   Scheme: "smsto"
I/PackageManager(  732): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
W/ActivityManager(  732): Permission Denial: getCurrentUser() from pid=5115, uid=10021 requires android.permission.INTERACT_ACROSS_USERS
W/Resources(  732): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
I/PackageManager(  732):   Action: "android.intent.action.SENDTO"
I/PackageManager(  732):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  732):   Scheme: "mms"
I/PackageManager(  732): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
I/PackageManager(  732):   Action: "android.intent.action.SENDTO"
I/PackageManager(  732):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  732):   Scheme: "mmsto"
I/PackageManager(  732): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
I/PCWCLIENTTRACE_PushUtil( 4355): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 4355): sales region : global
I/PCWCLIENTTRACE_PushUtil( 4355): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver( 4355): [onReceive] - android.intent.action.PACKAGE_REMOVED
W/Resources(  732): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
E/SMD     (  242): DCD ON
W/Resources(  732): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  732): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  732): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
I/SA      ( 4541): [SUR] onReceive log=[SA = 2.0.0117 V = 19 HWD = 1280X720 2.0 dpi = 320  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = kmini3g P = kmini3gxx I = KOT49H M = SM-G800H OKLEFT false DIS KOT49H.G800HXXU1ANK2 PSS = 4.497045606779314  ]
I/SA      ( 4541): [SUR] onReceive Intent=[ action_PACKAGE_REMOVED package ]
W/Resources(  732): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  732): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
I/ActivityManager(  732): Killing 3903:com.sec.android.app.videoplayer/u0a52 (adj 15): empty #43
W/Resources(  732): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  732): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  732): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
W/Resources(  732): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  732): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  732): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
I/CrashAnrDetector(  732): onPackageRemoved : com.test.thalitest
D/UsbSettingsManager(  732): clearDefaults: com.test.thalitest
I/IcingCorporaProvider( 2121): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
I/SELinux ( 5137): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5137):  
E/SQLiteLog( 2121): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
W/dalvikvm( 2121): threadid=14: thread exiting with uncaught exception (group=0x41869da0)
E/AndroidRuntime( 2121): FATAL EXCEPTION: IntentService[UpdateCorporaService]
E/AndroidRuntime( 2121): Process: com.google.android.googlequicksearchbox:search, PID: 2121
E/AndroidRuntime( 2121): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 2121): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/AndroidRuntime( 2121): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:745)
E/AndroidRuntime( 2121): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/AndroidRuntime( 2121): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/AndroidRuntime( 2121): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:507)
E/AndroidRuntime( 2121): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:418)
E/AndroidRuntime( 2121): 	at cid.d(PG:186)
E/AndroidRuntime( 2121): 	at clo.g(PG:594)
E/AndroidRuntime( 2121): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider.update(PG:301)
E/AndroidRuntime( 2121): 	at android.content.ContentProvider$Transport.update(ContentProvider.java:287)
E/AndroidRuntime( 2121): 	at android.content.ContentResolver.update(ContentResolver.java:1327)
E/AndroidRuntime( 2121): 	at clp.Rl(PG:910)
E/AndroidRuntime( 2121): 	at clr.tL(PG:827)
E/AndroidRuntime( 2121): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateCorporaService.a(PG:1271)
E/AndroidRuntime( 2121): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateCorporaService.onHandleIntent(PG:1204)
E/AndroidRuntime( 2121): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 2121): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 2121): 	at android.os.Looper.loop(Looper.java:146)
E/AndroidRuntime( 2121): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/Process ( 2121): Sending signal. PID: 2121 SIG: 9
I/SELinux ( 5137): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5137):  
I/SELinux ( 5137):  
I/SELinux ( 5137): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/DropBoxManagerService(  732): Can't write: system_app_crash
E/DropBoxManagerService(  732): java.io.FileNotFoundException: /data/system/dropbox/drop209.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  732): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService(  732): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService(  732): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService(  732): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:218)
E/DropBoxManagerService(  732): 	at android.os.DropBoxManager.addText(DropBoxManager.java:272)
E/DropBoxManagerService(  732): 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12552)
E/DropBoxManagerService(  732): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  732): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  732): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService(  732): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService(  732): 	... 5 more
E/SELinux ( 5137): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 5137): >>>>> Normal User
E/dalvikvm( 5137): >>>>> com.samsung.android.intelligenceservice [ userId:0 | appId:10005 ]
E/SELinux ( 5137): [DEBUG] seapp_context_lookup: seinfoCategory = platform
I/ActivityManager(  732): Process com.google.android.googlequicksearchbox:search (pid 2121) (adj 5) has died.
D/TimaKeyStoreProvider( 5137): in addTimaSignatureService
D/TimaKeyStoreProvider( 5137): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 5137): Added TimaKesytore provider
D/InputReader(  732): Processing first event
I/EventHub(  732): Removing device sec_touchscreen due to epoll hang-up event.
I/EventHub(  732): Removed device: path=/dev/input/event1 name=sec_touchscreen id=6 fd=217 classes=0x94
I/EventHub(  732): Removing device '/dev/input/event1' due to inotify event
I/InputReader(  732): Device removed: id=6, name='sec_touchscreen', sources=0x80001002
D/InputReader(  732): Could not retrieve current multitouch slot index.  status=-1
D/InputReader(  732): MultiTouchMotionAccumulator: initial slot number is -1
I/ActivityManager(  732): Config changes=8 {0 1.0 ?mcc?mnc en_US ldltr sw360dp w360dp h615dp 320dpi nrml long port -touch -keyb/v/h -nav/h s.6}
D/InputDispatcher(  732): setInputDispatchMode: enabled=0, frozen=1
I/SurfaceFlinger(  248): id=19 createSurf (720x1280),2 flag=404, TcreenshotS
D/Mms/MmsApp( 3713): [start]    onConfigurationChanged(),newConfig={0 1.0 ?mcc?mnc en_US ldltr sw360dp w360dp h615dp 320dpi nrml long port -touch -keyb/v/h -nav/h s.6}
D/Mms/MmsApp( 3713): [end]    onConfigurationChanged(),newConfig={0 1.0 ?mcc?mnc en_US ldltr sw360dp w360dp h615dp 320dpi nrml long port -touch -keyb/v/h -nav/h s.6}
D/PermissionCache(  248): checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (261 us)
I/SurfaceFlinger(  248): id=18 Removed CatteryCove (8/13)
D/MenuAppsGridFragment( 1241): onDestroyView
I/SurfaceFlinger(  248): id=18 Removed CatteryCove (-2/13)
W/Launcher.MenuAppsGrid( 1241): Trying to exit a state that hasn't been entered
D/KeyguardUpdateMonitor( 1065): sendKeyguardVisibilityChanged(true)
D/PhoneStatusBar( 1065): mSettingsPanelGravity = 55
D/KeyguardUpdateMonitor( 1065): handleKeyguardVisibilityChanged(1)
D/KeyguardUpdateMonitor( 1065): sendKeyguardVisibilityChanged(true)
E/Tethering(  732): No numeric data
D/KeyguardUpdateMonitor( 1065): sendKeyguardVisibilityChanged(true)
D/PhoneStatusBarView( 1065): marqueeStatusBar:123, mClearCover:0
E/SmartFaceService(  732): onReceive: android.intent.action.CONFIGURATION_CHANGED
E/SmartFaceService(  732): mFolderCoverOpened: (true, true) -> true
D/KeyguardUpdateMonitor( 1065): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1065): handleKeyguardVisibilityChanged(1)
D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
D/KeyguardHostView( 1065): onSaveInstanceState, tstate=1
D/KeyguardGuestSelectorView( 1065): onDetachedFromWindow()
V/KeyguardUpdateMonitor( 1065): *** unregister callback for com.android.keyguard.CarrierText$1@426199d0
D/KeyguardUpdateMonitor( 1065): sendKeyguardVisibilityChanged(true)
V/KeyguardUpdateMonitor( 1065): *** unregister callback for com.android.keyguard.MSimCarrierText$1@42619a38
V/KeyguardUpdateMonitor( 1065): *** unregister callback for com.android.keyguard.CarrierText$1@425e45a8
V/KeyguardUpdateMonitor( 1065): *** unregister callback for com.android.keyguard.EmergencyButton$1@425f10d0
V/KeyguardUpdateMonitor( 1065): *** unregister callback for com.android.keyguard.sec.KeyguardSecurityViewOverlay$1@4254b570
W/ApplicationsProvider( 1400): Could not fetch usage stats
W/ApplicationsProvider( 1400): java.lang.SecurityException: Neither user 10020 nor current process has android.permission.PACKAGE_USAGE_STATS.
W/ApplicationsProvider( 1400): 	at android.os.Parcel.readException(Parcel.java:1465)
W/ApplicationsProvider( 1400): 	at android.os.Parcel.readException(Parcel.java:1419)
W/ApplicationsProvider( 1400): 	at com.android.internal.app.IUsageStats$Stub$Proxy.getAllPkgUsageStats(IUsageStats.java:317)
W/ApplicationsProvider( 1400): 	at android.app.ActivityManager.getAllPackageUsageStats(ActivityManager.java:2543)
W/ApplicationsProvider( 1400): 	at com.android.providers.applications.ApplicationsProvider.fetchUsageStats(ApplicationsProvider.java:681)
W/ApplicationsProvider( 1400): 	at com.android.providers.applications.ApplicationsProvider.updateApplicationsList(ApplicationsProvider.java:519)
W/ApplicationsProvider( 1400): 	at com.android.providers.applications.ApplicationsProvider.access$300(ApplicationsProvider.java:70)
W/ApplicationsProvider( 1400): 	at com.android.providers.applications.ApplicationsProvider$UpdateHandler.handleMessage(ApplicationsProvider.java:209)
W/ApplicationsProvider( 1400): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/ApplicationsProvider( 1400): 	at android.os.Looper.loop(Looper.java:146)
W/ApplicationsProvider( 1400): 	at android.os.HandlerThread.run(HandlerThread.java:61)
V/KeyguardUpdateMonitor( 1065): *** unregister callback for com.android.keyguard.KeyguardHostView$2@4254eb40
E/KeyguardHostView( 1065): KeyguardHostView()
D/ContextualEventManager( 1065): setOnClickHandler()
V/KeyguardHostView( 1065): mIsMultipleLockOn is false
D/KeyguardHostView( 1065): mIsVoiceUnlockOn=false
V/KeyguardHostView( 1065): Initial transport state: 1, pbstate=0
I/KeyguardEffectViewMain( 1065): *** KeyguardEffectView getInstance ***
D/LockPatternUtils( 1065): isPcwEnable = null
D/ContextualEventContainer( 1065): ContextualEventContainer()
V/KeyguardUpdateMonitor( 1065): *** register callback for com.android.keyguard.KeyguardMessageArea$2@42cbabc0
V/KeyguardUpdateMonitor( 1065): *** unregister callback for null
D/ContextualEventContainer( 1065): onFinishInflate()
D/ContextualEventContainer( 1065): update()
D/LockPatternUtils( 1065): isPcwEnable = null
D/LockPatternUtils( 1065): isPcwEnable = null
D/LockPatternUtils( 1065): isPcwEnable = null
D/KeyguardHostView( 1065): mIsFMMEnabled = false, mIsCarrierLockEnabled = false, mIsCarrierLockPlusEnabled = false
D/LockPatternUtils( 1065): isPcwEnable = null
V/KeyguardHostView( 1065): showPrimarySecurityScreen(turningOff=false)
I/MDPP    ( 1065): Property: Empty
D/KeyguardHostView( 1065): showSecurityScreen(None)
V/KeyguardHostView( 1065): inflating id = 2130903095
D/SecuritySelectorView( 1065): explore by touch mode off
I/KeyguardEffectViewMain( 1065): *** KeyguardEffectView getInstance ***
I/KeyguardEffectViewMain( 1065): *** KeyguardEffectView getInstance ***
D/SecCameraShortcut( 1065): shortcutSetting:1
D/SecCameraShortcut( 1065): isKidsMode:false
D/SecCameraShortcut( 1065): isEmergencyMode:false
D/LockPatternUtils( 1065): isPcwEnable = null
D/EmergencyButton( 1065): enabled = false, :0
D/LockPatternUtils( 1065): isPcwEnable = null
I/KeyguardEffectViewMain( 1065): *** KeyguardEffectView getInstance ***
D/SecCameraShortcut( 1065): setCallback(): null
D/KeyguardVoiceEngineThread( 1065): condition = 0
D/SecuritySelectorView( 1065): mIsAirViewEnabled =false
D/SecCameraShortcut( 1065): setCallback(): not null
D/SecuritySelectorView( 1065): hideBouncer mBouncerHelpText != null
D/SecCameraShortcut( 1065): setCallback(): not null
D/SecCameraShortcut( 1065): setCallback(): not null
D/SecuritySelectorView( 1065): hideBouncer mBouncerHelpText != null
D/KeyguardHostView( 1065): mKeyguardHelpOverlay : null
D/KeyguardHostView( 1065): AUTO_WIPE = false , IT Policy = false
D/ContextualEventManager( 1065): setOnClickHandler()
E/LSO     ( 1065): LSO Service is not yet ready!!!
V/KeyguardUpdateMonitor( 1065): *** register callback for com.android.keyguard.KeyguardHostView$2@42cb4950
V/KeyguardUpdateMonitor( 1065): *** unregister callback for null
V/KeyguardHostView( 1065): music state changed: 0
D/KeyguardProperties( 1065): isIgnoreNationalRoaming() = false
D/VisualEffectCircleUnlockEffect( 1065): KeyguardEffectViewNone : Constructor
D/VisualEffectCircleUnlockEffect( 1065): screenWidth : 720
D/VisualEffectCircleUnlockEffect( 1065): screenHeight : 1280

```
