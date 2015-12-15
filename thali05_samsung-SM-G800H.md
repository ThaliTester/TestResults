#### Test 50650278654db8c_thali05_samsung-SM-G800H Logs


```
--------- beginning of /dev/log/system
W/ActivityManager(  749): Permission Denial: getCurrentUser() from pid=4541, uid=10035 requires android.permission.INTERACT_ACROSS_USERS
--------- beginning of /dev/log/main
W/ContextImpl( 4541): Implicit intents with startService are not safe: Intent { act=com.sec.android.service.health.cp.accesscontrol } android.content.ContextWrapper.bindService:529 com.samsung.android.sdk.health.content.ShealthAccessControl.startService:274 com.samsung.android.sdk.health.content.ShealthAccessControl.requestPermission:212 
I/SELinux ( 4563): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 4563):  
E/Device Type Shared Preferences( 4541): Device Type Shared Preferences - getDeviceTypeChecked -true
E/Device Type Shared Preferences( 4541): Device Type Shared Preferences - not connecting to service
E/com.sec.android.app.shealth.SHealthApplication( 4541): ContentProvider is not null
,I/SELinux ( 4563): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 4563):  
I/SELinux ( 4563):  
I/SELinux ( 4563): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 4563): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 4563): >>>>> Normal User
E/dalvikvm( 4563): >>>>> com.sec.android.service.health [ userId:0 | appId:10016 ]
E/SELinux ( 4563): [DEBUG] seapp_context_lookup: seinfoCategory = platform
D/TimaKeyStoreProvider( 4563): in addTimaSignatureService
D/TimaKeyStoreProvider( 4563): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 4563): Added TimaKesytore provider
V/MediaPlayer( 4541): decode(61, 33979084, 48105)
V/MediaPlayerService(  249): decode(33, 33979084, 48105)
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
V/StagefrightPlayer(  249): setDataSource(33, 33979084, 48105)
V/AwesomePlayer(  249): reset_l()
V/AwesomePlayer(  249): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  249): notify(0xb809c160, 8, 0, 0)
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
V/AudioCache(  249): notify(0xb809c160, 200, 973, 0)
V/AudioCache(  249): ignored
V/AwesomePlayer(  249): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  249): notify(0xb809c160, 5, 0, 0)
V/AudioCache(  249): ignored
V/AwesomePlayer(  249): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  249): notify(0xb809c160, 1, 0, 0)
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
V/AudioCache(  249): notify(0xb809c160, 6, 0, 0)
V/AudioCache(  249): ignored
V/AwesomePlayer(  249): addBatteryData
V/MediaPlayerService(  249): wait for playback complete
W/ActivityManager(  749): Permission Denial: getCurrentUser() from pid=4563, uid=10016 requires android.permission.INTERACT_ACROSS_USERS
D/dalvikvm( 4563): No JNI_OnLoad found in /system/lib/libsecure_storage_jni.so 0x4258cc30, skipping init
I/SecureStorage( 4563): [INFO]: SPID(0x00000000)Checking if this device supports Secure Storage
I/SecureStorage( 4563): [INFO]: SPID(0x00000000)This device supports Secure Storage
I/SecureStorage(  294): [INFO]: SPID(0x00000003)Credentials: uid 10016, gid 10016, pid 4563
I/SecureStorage(  294): [INFO]: SPID(0x00000003)Received function mask & code: 0000010C
I/SecureStorage( 4563): [INFO]: SPID(0x00000000)SS Daemon is running
I/OMXCodec(  249): [OMX.google.vorbis.decoder] End Of Stream
I/SecureStorage( 4563): [INFO]: SPID(0x00000000)Processing data
I/SecureStorage(  294): [INFO]: SPID(0x00000003)Credentials: uid 10016, gid 10016, pid 4563
I/SecureStorage(  294): [INFO]: SPID(0x00000003)Received function mask & code: 00000106
V/AwesomePlayer(  249): postAudioEOS delayUs (0)
V/AwesomePlayer(  249): onCheckAudioStatus
V/AwesomePlayer(  249): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  249): onStreamDone
V/AwesomePlayer(  249): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  249): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  249): notify(0xb809c160, 2, 0, 0)
V/AudioCache(  249): playback complete - thread will wake up later
V/AwesomePlayer(  249): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  249): notify(0xb809c160, 7, 0, 0)
V/AudioCache(  249): ignored
V/AwesomePlayer(  249): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer(  249): addBatteryData
V/AudioCache(  249): wait - success
V/StagefrightPlayer(  249): reset
V/AwesomePlayer(  249): reset_l()
V/AwesomePlayer(  249): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  249): notify(0xb809c160, 8, 0, 0)
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
V/MediaPlayer( 4541): decode(63, 33914984, 10421)
V/MediaPlayerService(  249): decode(33, 33914984, 10421)
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
V/StagefrightPlayer(  249): setDataSource(33, 33914984, 10421)
V/AwesomePlayer(  249): reset_l()
V/AwesomePlayer(  249): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  249): notify(0xb8093200, 8, 0, 0)
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
V/AudioCache(  249): notify(0xb8093200, 200, 973, 0)
V/AudioCache(  249): ignored
V/AwesomePlayer(  249): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  249): notify(0xb8093200, 5, 0, 0)
V/AudioCache(  249): ignored
V/AwesomePlayer(  249): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  249): notify(0xb8093200, 1, 0, 0)
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
V/AudioCache(  249): notify(0xb8093200, 6, 0, 0)
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
V/AudioCache(  249): notify(0xb8093200, 2, 0, 0)
V/AudioCache(  249): playback complete - thread will wake up later
V/AwesomePlayer(  249): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  249): notify(0xb8093200, 7, 0, 0)
V/AudioCache(  249): ignored
V/AwesomePlayer(  249): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer(  249): addBatteryData
V/AudioCache(  249): wait - success
V/StagefrightPlayer(  249): reset
V/AwesomePlayer(  249): reset_l()
V/AwesomePlayer(  249): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  249): notify(0xb8093200, 8, 0, 0)
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
V/MediaPlayer( 4541): decode(64, 37457308, 34198)
V/MediaPlayerService(  249): decode(34, 37457308, 34198)
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
V/StagefrightPlayer(  249): setDataSource(34, 37457308, 34198)
V/AwesomePlayer(  249): reset_l()
V/AwesomePlayer(  249): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  249): notify(0xb808d280, 8, 0, 0)
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
V/AudioCache(  249): notify(0xb808d280, 200, 973, 0)
V/AudioCache(  249): ignored
V/AwesomePlayer(  249): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  249): notify(0xb808d280, 5, 0, 0)
V/AudioCache(  249): ignored
V/AwesomePlayer(  249): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  249): notify(0xb808d280, 1, 0, 0)
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
V/AudioCache(  249): notify(0xb808d280, 6, 0, 0)
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
V/AudioCache(  249): notify(0xb808d280, 2, 0, 0)
V/AudioCache(  249): playback complete - thread will wake up later
V/AwesomePlayer(  249): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  249): notify(0xb808d280, 7, 0, 0)
V/AudioCache(  249): ignored
V/AwesomePlayer(  249): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer(  249): addBatteryData
V/AudioCache(  249): wait - success
V/StagefrightPlayer(  249): reset
V/AwesomePlayer(  249): reset_l()
V/AwesomePlayer(  249): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  249): notify(0xb808d280, 8, 0, 0)
V/AudioCache(  249): ignored
V/AwesomePlayer(  249): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  249): mAudioTrackVector clear
I/OMXCodec(  249): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec(  249): [OMX.google.vorbis.decoder] stop() sendCommand(0x39, OMX_CommandStateSet, OMX_StateIdle)
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
V/MediaPlayer( 4541): decode(65, 33862452, 7405)
V/MediaPlayerService(  249): decode(33, 33862452, 7405)
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
V/StagefrightPlayer(  249): setDataSource(33, 33862452, 7405)
V/AwesomePlayer(  249): reset_l()
V/AwesomePlayer(  249): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  249): notify(0xb808b648, 8, 0, 0)
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
V/AudioCache(  249): notify(0xb808b648, 200, 973, 0)
V/AudioCache(  249): ignored
V/AwesomePlayer(  249): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  249): notify(0xb808b648, 5, 0, 0)
V/AudioCache(  249): ignored
V/AwesomePlayer(  249): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  249): notify(0xb808b648, 1, 0, 0)
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
V/AudioCache(  249): notify(0xb808b648, 6, 0, 0)
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
V/AudioCache(  249): notify(0xb808b648, 2, 0, 0)
V/AudioCache(  249): playback complete - thread will wake up later
V/AwesomePlayer(  249): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  249): notify(0xb808b648, 7, 0, 0)
V/AudioCache(  249): ignored
V/AwesomePlayer(  249): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer(  249): addBatteryData
V/AudioCache(  249): wait - success
V/StagefrightPlayer(  249): reset
V/AwesomePlayer(  249): reset_l()
V/AwesomePlayer(  249): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  249): notify(0xb808b648, 8, 0, 0)
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
V/MediaPlayer( 4541): decode(66, 37547940, 5555)
V/MediaPlayerService(  249): decode(33, 37547940, 5555)
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
V/StagefrightPlayer(  249): setDataSource(33, 37547940, 5555)
V/AwesomePlayer(  249): reset_l()
V/AwesomePlayer(  249): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  249): notify(0xb8091378, 8, 0, 0)
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
V/AudioCache(  249): notify(0xb8091378, 200, 973, 0)
V/AudioCache(  249): ignored
V/AwesomePlayer(  249): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  249): notify(0xb8091378, 5, 0, 0)
V/AudioCache(  249): ignored
V/AwesomePlayer(  249): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  249): notify(0xb8091378, 1, 0, 0)
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
V/AudioCache(  249): notify(0xb8091378, 6, 0, 0)
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
V/AudioCache(  249): notify(0xb8091378, 2, 0, 0)
V/AudioCache(  249): playback complete - thread will wake up later
V/AwesomePlayer(  249): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  249): notify(0xb8091378, 7, 0, 0)
V/AudioCache(  249): ignored
V/AwesomePlayer(  249): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer(  249): addBatteryData
V/AudioCache(  249): wait - success
V/StagefrightPlayer(  249): reset
V/AwesomePlayer(  249): reset_l()
V/AwesomePlayer(  249): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  249): notify(0xb8091378, 8, 0, 0)
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
V/MediaPlayer( 4541): decode(67, 30367732, 5085)
V/MediaPlayerService(  249): decode(34, 30367732, 5085)
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
V/StagefrightPlayer(  249): setDataSource(34, 30367732, 5085)
V/AwesomePlayer(  249): reset_l()
V/AwesomePlayer(  249): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  249): notify(0xb8092bb8, 8, 0, 0)
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
V/AudioCache(  249): notify(0xb8092bb8, 200, 973, 0)
V/AudioCache(  249): ignored
V/AwesomePlayer(  249): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  249): notify(0xb8092bb8, 5, 0, 0)
V/AudioCache(  249): ignored
V/AwesomePlayer(  249): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  249): notify(0xb8092bb8, 1, 0, 0)
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
V/AudioCache(  249): notify(0xb8092bb8, 6, 0, 0)
V/AudioCache(  249): ignored
V/AwesomePlayer(  249): addBatteryData
V/MediaPlayerService(  249): wait for playback complete
I/AudioPlayer(  249): First fillBuffer call!!
I/OMXCodec(  249): [OMX.google.vorbis.decoder] End Of Stream
V/AwesomePlayer(  249): postAudioEOS delayUs (0)
D/AndroidRuntime( 4576): 
D/AndroidRuntime( 4576): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 4576): CheckJNI is OFF
D/AndroidRuntime( 4576): setted country_code = Poland
D/AndroidRuntime( 4576): setted countryiso_code = PL
V/AwesomePlayer(  249): onCheckAudioStatus
V/AwesomePlayer(  249): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  249): onStreamDone
V/AwesomePlayer(  249): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  249): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  249): notify(0xb8092bb8, 2, 0, 0)
V/AudioCache(  249): playback complete - thread will wake up later
V/AwesomePlayer(  249): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  249): notify(0xb8092bb8, 7, 0, 0)
V/AudioCache(  249): ignored
V/AwesomePlayer(  249): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer(  249): addBatteryData
V/AudioCache(  249): wait - success
V/StagefrightPlayer(  249): reset
V/AwesomePlayer(  249): reset_l()
V/AwesomePlayer(  249): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  249): notify(0xb8092bb8, 8, 0, 0)
V/AudioCache(  249): ignored
V/AwesomePlayer(  249): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  249): mAudioTrackVector clear
I/OMXCodec(  249): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec(  249): [OMX.google.vorbis.decoder] stop() sendCommand(0x3c, OMX_CommandStateSet, OMX_StateIdle)
D/AndroidRuntime( 4576): setted sales_code = XEO
D/AndroidRuntime( 4576): readGMSProperty: start
D/AndroidRuntime( 4576): readGMSProperty: already setted!!
I/OMXCodec(  249): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
D/AndroidRuntime( 4576): readGMSProperty: end
D/AndroidRuntime( 4576): addProductProperty: start
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
V/MediaPlayer( 4541): decode(68, 30372876, 21552)
V/MediaPlayerService(  249): decode(33, 30372876, 21552)
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
V/StagefrightPlayer(  249): setDataSource(33, 30372876, 21552)
V/AwesomePlayer(  249): reset_l()
V/AwesomePlayer(  249): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  249): notify(0xb8099740, 8, 0, 0)
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
V/AudioCache(  249): notify(0xb8099740, 200, 973, 0)
V/AudioCache(  249): ignored
V/AwesomePlayer(  249): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  249): notify(0xb8099740, 5, 0, 0)
V/AudioCache(  249): ignored
V/AwesomePlayer(  249): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  249): notify(0xb8099740, 1, 0, 0)
V/AudioCache(  249): prepared
V/AudioCache(  249): wait - success
V/MediaPlayerService(  249): start
V/StagefrightPlayer(  249): start
V/AwesomePlayer(  249): play
V/AwesomePlayer(  249): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer(  249): startAudioPlayer_l, sendErrorNotification (0)
D/dalvikvm( 4576): Trying to load lib libjavacore.so 0x0
I/OMXCodec(  249): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec(  249): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec(  249): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
D/dalvikvm( 4576): Added shared lib libjavacore.so 0x0
I/AudioPlayer(  249):  Audioplayer kKeyAudioPCMFormat:1, 2, 0
I/AudioPlayer(  249):  Audioplayer kKeyAudioPCMFormat read fail(2, 1)
V/AudioCache(  249): open(44100, 2, 0x0, 1, 4)
V/AwesomePlayer(  249): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache(  249): notify(0xb8099740, 6, 0, 0)
V/AudioCache(  249): ignored
V/AwesomePlayer(  249): addBatteryData
I/AudioPlayer(  249): First fillBuffer call!!
V/MediaPlayerService(  249): wait for playback complete
D/dalvikvm( 4576): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 4576): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 4576): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
I/OMXCodec(  249): [OMX.google.vorbis.decoder] End Of Stream
V/AwesomePlayer(  249): postAudioEOS delayUs (0)
V/AwesomePlayer(  249): onCheckAudioStatus
V/AwesomePlayer(  249): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  249): onStreamDone
V/AwesomePlayer(  249): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  249): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  249): notify(0xb8099740, 2, 0, 0)
V/AudioCache(  249): playback complete - thread will wake up later
V/AwesomePlayer(  249): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  249): notify(0xb8099740, 7, 0, 0)
V/AudioCache(  249): ignored
V/AwesomePlayer(  249): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer(  249): addBatteryData
V/AudioCache(  249): wait - success
V/StagefrightPlayer(  249): reset
V/AwesomePlayer(  249): reset_l()
V/AwesomePlayer(  249): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  249): notify(0xb8099740, 8, 0, 0)
V/AudioCache(  249): ignored
V/AwesomePlayer(  249): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  249): mAudioTrackVector clear
I/OMXCodec(  249): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec(  249): [OMX.google.vorbis.decoder] stop() sendCommand(0x3d, OMX_CommandStateSet, OMX_StateIdle)
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
V/MediaPlayer( 4541): decode(69, 37543652, 4230)
V/MediaPlayerService(  249): decode(33, 37543652, 4230)
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
V/StagefrightPlayer(  249): setDataSource(33, 37543652, 4230)
V/AwesomePlayer(  249): reset_l()
V/AwesomePlayer(  249): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  249): notify(0xb8099b10, 8, 0, 0)
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
V/AudioCache(  249): notify(0xb8099b10, 200, 973, 0)
V/AudioCache(  249): ignored
V/AwesomePlayer(  249): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  249): notify(0xb8099b10, 5, 0, 0)
V/AudioCache(  249): ignored
V/AwesomePlayer(  249): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  249): notify(0xb8099b10, 1, 0, 0)
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
V/AudioCache(  249): notify(0xb8099b10, 6, 0, 0)
V/AudioCache(  249): ignored
V/AwesomePlayer(  249): addBatteryData
V/MediaPlayerService(  249): wait for playback complete
V/AwesomePlayer(  249): postAudioEOS delayUs (0)
V/AwesomePlayer(  249): onCheckAudioStatus
V/AwesomePlayer(  249): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  249): onStreamDone
V/AwesomePlayer(  249): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  249): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  249): notify(0xb8099b10, 2, 0, 0)
V/AudioCache(  249): playback complete - thread will wake up later
V/AwesomePlayer(  249): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  249): notify(0xb8099b10, 7, 0, 0)
V/AudioCache(  249): ignored
V/AwesomePlayer(  249): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer(  249): addBatteryData
V/AudioCache(  249): wait - success
V/StagefrightPlayer(  249): reset
V/AwesomePlayer(  249): reset_l()
V/AwesomePlayer(  249): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  249): notify(0xb8099b10, 8, 0, 0)
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
V/MediaPlayer( 4541): decode(70, 30337076, 9400)
V/MediaPlayerService(  249): decode(33, 30337076, 9400)
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
V/StagefrightPlayer(  249): setDataSource(33, 30337076, 9400)
V/AwesomePlayer(  249): reset_l()
V/AwesomePlayer(  249): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  249): notify(0xb809b9f0, 8, 0, 0)
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
V/AudioCache(  249): notify(0xb809b9f0, 200, 973, 0)
V/AudioCache(  249): ignored
V/AwesomePlayer(  249): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  249): notify(0xb809b9f0, 5, 0, 0)
V/AudioCache(  249): ignored
V/AwesomePlayer(  249): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  249): notify(0xb809b9f0, 1, 0, 0)
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
V/AudioCache(  249): notify(0xb809b9f0, 6, 0, 0)
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
V/AudioCache(  249): notify(0xb809b9f0, 2, 0, 0)
V/AudioCache(  249): playback complete - thread will wake up later
V/AwesomePlayer(  249): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  249): notify(0xb809b9f0, 7, 0, 0)
V/AudioCache(  249): ignored
V/AwesomePlayer(  249): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer(  249): addBatteryData
V/AudioCache(  249): wait - success
V/StagefrightPlayer(  249): reset
V/AwesomePlayer(  249): reset_l()
V/AwesomePlayer(  249): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  249): notify(0xb809b9f0, 8, 0, 0)
V/AudioCache(  249): ignored
V/AwesomePlayer(  249): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  249): mAudioTrackVector clear
I/OMXCodec(  249): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec(  249): [OMX.google.vorbis.decoder] stop() sendCommand(0x3f, OMX_CommandStateSet, OMX_StateIdle)
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
V/MediaPlayer( 4541): decode(71, 33925464, 44276)
V/MediaPlayerService(  249): decode(33, 33925464, 44276)
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
V/StagefrightPlayer(  249): setDataSource(33, 33925464, 44276)
V/AwesomePlayer(  249): reset_l()
V/AwesomePlayer(  249): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  249): notify(0xb8093718, 8, 0, 0)
V/AudioCache(  249): ignored
V/AwesomePlayer(  249): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  249): mAudioTrackVector clear
V/AwesomePlayer(  249): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  249): mSecMediaClock clear
I/SELinux ( 4635): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 4635):  
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
I/ActivityManager(  749): Killing 3148:com.sec.android.app.mt/1000 (adj 15): empty #43
I/OMX     (  249): mDispatchers.add
I/OMXCodec(  249): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec(  249): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec(  249): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec(  249): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
E/memtrack( 4576): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 4576): failed to load memtrack module: -2
I/OMXCodec(  249): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer(  249): finishAsyncPrepare_l
V/AwesomePlayer(  249): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache(  249): notify(0xb8093718, 200, 973, 0)
V/AudioCache(  249): ignored
V/AwesomePlayer(  249): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  249): notify(0xb8093718, 5, 0, 0)
V/AudioCache(  249): ig,nored
V/AwesomePlayer(  249): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  249): notify(0xb8093718, 1, 0, 0)
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
V/AudioCache(  249): notify(0xb8093718, 6, 0, 0)
V/AudioCache(  249): ignored
V/AwesomePlayer(  249): addBatteryData
V/MediaPlayerService(  249): wait for playback complete
D/dalvikvm( 4576): Note: class Landroid/app/ActivityManagerNative; has 192 unimplemented (abstract) methods
I/AudioPlayer(  249): First fillBuffer call!!
I/SELinux ( 4635): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 4635):  
I/SELinux ( 4635):  
I/SELinux ( 4635): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 4635): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 4635): >>>>> Normal User
E/dalvikvm( 4635): >>>>> com.policydm [ userId:0 | appId:1000 ]
E/SELinux ( 4635): [DEBUG] seapp_context_lookup: seinfoCategory = platform
D/TimaKeyStoreProvider( 4635): in addTimaSignatureService
D/TimaKeyStoreProvider( 4635): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 4635): Added TimaKesytore provider
I/OMXCodec(  249): [OMX.google.vorbis.decoder] End Of Stream
V/AwesomePlayer(  249): postAudioEOS delayUs (0)
D/AndroidRuntime( 4576): Calling main entry com.android.commands.am.Am
V/AwesomePlayer(  249): onCheckAudioStatus
V/AwesomePlayer(  249): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  249): onStreamDone
V/AwesomePlayer(  249): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  249): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  249): notify(0xb8093718, 2, 0, 0)
V/AudioCache(  249): playback complete - thread will wake up later
V/AwesomePlayer(  249): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  249): notify(0xb8093718, 7, 0, 0)
V/AudioCache(  249): ignored
V/AwesomePlayer(  249): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer(  249): addBatteryData
V/AudioCache(  249): wait - success
V/StagefrightPlayer(  249): reset
V/AwesomePlayer(  249): reset_l()
V/AwesomePlayer(  249): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  249): notify(0xb8093718, 8, 0, 0)
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
V/MediaPlayer( 4541): decode(72, 33885672, 29256)
V/MediaPlayerService(  249): decode(33, 33885672, 29256)
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
V/StagefrightPlayer(  249): setDataSource(33, 33885672, 29256)
V/AwesomePlayer(  249): reset_l()
V/AwesomePlayer(  249): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  249): notify(0xb809cbf0, 8, 0, 0)
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
V/AudioCache(  249): notify(0xb809cbf0, 200, 973, 0)
V/AudioCache(  249): ignored
V/AwesomePlayer(  249): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  249): notify(0xb809cbf0, 5, 0, 0)
V/AudioCache(  249): ignored
V/AwesomePlayer(  249): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  249): notify(0xb809cbf0, 1, 0, 0)
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
V/AudioCache(  249): notify(0xb809cbf0, 6, 0, 0)
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
V/AudioCache(  249): notify(0xb809cbf0, 2, 0, 0)
V/AudioCache(  249): playback complete - thread will wake up later
V/AwesomePlayer(  249): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  249): notify(0xb809cbf0, 7, 0, 0)
V/AudioCache(  249): ignored
V/AwesomePlayer(  249): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer(  249): addBatteryData
V/AudioCache(  249): wait - success
V/StagefrightPlayer(  249): reset
V/AwesomePlayer(  249): reset_l()
V/AwesomePlayer(  249): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  249): notify(0xb809cbf0, 8, 0, 0)
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
V/MediaPlayer( 4541): decode(73, 37491572, 52024)
V/MediaPlayerService(  249): decode(33, 37491572, 52024)
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
V/StagefrightPlayer(  249): setDataSource(33, 37491572, 52024)
V/AwesomePlayer(  249): reset_l()
V/AwesomePlayer(  249): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  249): notify(0xb80859b8, 8, 0, 0)
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
V/AudioCache(  249): notify(0xb80859b8, 200, 973, 0)
V/AudioCache(  249): ignored
V/AwesomePlayer(  249): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  249): notify(0xb80859b8, 5, 0, 0)
V/AudioCache(  249): ignored
V/AwesomePlayer(  249): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  249): notify(0xb80859b8, 1, 0, 0)
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
V/ApplicationPolicy(  749): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
V/AwesomePlayer(  249): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache(  249): notify(0xb80859b8, 6, 0, 0)
V/AudioCache(  249): ignored
V/AwesomePlayer(  249): addBatteryData
V/MediaPlayerService(  249): wait for playback complete
D/CustomFrequencyManagerService(  749): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 749  pkgName : ACTIVITY_RESUME_BOOSTER@5
W/ActivityManager(  749): mDVFSHelper.acquire()
I/SELinux ( 4661): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 4661):  
D/dalvikvm(  247): GC_EXPLICIT freed 45K, 49% free 9511K/18408K, paused 2ms+3ms, total 32ms
D/LockPatternUtils( 1064): isPcwEnable = null
I/SELinux ( 4661): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 4661):  
I/SELinux ( 4661):  
I/SELinux ( 4661): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 4661): [DEBUG] seapp_context_lookup: seinfoCategory = default
E/dalvikvm( 4661): >>>>> Normal User
E/dalvikvm( 4661): >>>>> com.test.thalitest [ userId:0 | appId:10179 ]
E/SELinux ( 4661): [DEBUG] seapp_context_lookup: seinfoCategory = default
D/AndroidRuntime( 4576): Shutting down VM
D/dalvikvm(  247): GC_EXPLICIT freed <1K, 49% free 9511K/18408K, paused 2ms+2ms, total 19ms
D/dalvikvm( 4576): GC_CONCURRENT freed 97K, 13% free 717K/816K, paused 0ms+0ms, total 2ms
D/TimaKeyStoreProvider( 4661): in addTimaSignatureService
D/dalvikvm(  247): GC_EXPLICIT freed <1K, 49% free 9511K/18408K, paused 2ms+2ms, total 20ms
D/TimaKeyStoreProvider( 4661): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 4661): Added TimaKesytore provider
D/LockPatternUtils( 1064): isPcwEnable = null
D/SurfaceWidgetView( 1241): destroyHardwareResources():1125703448
I/OMXCodec(  249): [OMX.google.vorbis.decoder] End Of Stream
V/AwesomePlayer(  249): postAudioEOS delayUs (0)
V/AwesomePlayer(  249): onCheckAudioStatus
V/AwesomePlayer(  249): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  249): onStreamDone
V/AwesomePlayer(  249): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  249): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  249): notify(0xb80859b8, 2, 0, 0)
V/AudioCache(  249): playback complete - thread will wake up later
V/AwesomePlayer(  249): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  249): notify(0xb80859b8, 7, 0, 0)
V/AudioCache(  249): ignored
V/AwesomePlayer(  249): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer(  249): addBatteryData
V/AudioCache(  249): wait - success
V/StagefrightPlayer(  249): reset
V/AwesomePlayer(  249): reset_l()
V/AwesomePlayer(  249): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  249): notify(0xb80859b8, 8, 0, 0)
V/AudioCache(  249): ignored
V/AwesomePlayer(  249): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  249): mAudioTrackVector clear
I/OMXCodec(  249): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec(  249): [OMX.google.vorbis.decoder] stop() sendCommand(0x42, OMX_CommandStateSet, OMX_StateIdle)
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
V/MediaPlayer( 4541): decode(74, 33969800, 9226)
V/MediaPlayerService(  249): decode(33, 33969800, 9226)
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
V/StagefrightPlayer(  249): setDataSource(33, 33969800, 9226)
V/AwesomePlayer(  249): reset_l()
V/AwesomePlayer(  249): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  249): notify(0xb8091378, 8, 0, 0)
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
I/SurfaceFlinger(  246): id=14 Removed CatteryCove (8/13)
I/SurfaceFlinger(  246): id=14 Removed CatteryCove (-2/13)
I/SQLiteSecureOpenHelper( 2014): getWritableDatabase(pwd)
I/SQLiteSecureOpenHelper( 2014): getDatabaseLocked(b,b,pwd)...
V/AwesomePlayer(  249): onPrepareAsyncEvent
I/SecMediaClock(  249): SecMediaClock constructor
I/SecMediaClock(  249): reset
V/AwesomePlayer(  249): initAudioDecoder
D/KeyguardUpdateMonitor( 1064): sendKeyguardVisibilityChanged(true)
V/AwesomePlayer(  249): checkOffloadExceptions is true
D/KeyguardUpdateMonitor( 1064): handleKeyguardVisibilityChanged(1)
I/OMXCodec(  249): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
I/OMX     (  249): mDispatchers.add
I/OMXCodec(  249): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec(  249): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec(  249): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec(  249): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/OMXCodec(  249): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer(  249): finishAsyncPrepare_l
V/AwesomePlayer(  249): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache(  249): notify(0xb8091378, 200, 973, 0)
V/AudioCache(  249): ignored
V/AwesomePlayer(  249): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  249): notify(0xb8091378, 5, 0, 0)
V/AudioCache(  249): ignored
V/AwesomePlayer(  249): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  249): notify(0xb8091378, 1, 0, 0)
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
V/AudioCache(  249): notify(0xb8091378, 6, 0, 0)
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
V/AudioCache(  249): notify(0xb8091378, 2, 0, 0)
V/AudioCache(  249): playback complete - thread will wake up later
V/AwesomePlayer(  249): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  249): notify(0xb8091378, 7, 0, 0)
V/AudioCache(  249): ignored
V/AwesomePlayer(  249): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer(  249): addBatteryData
V/AudioCache(  249): wait - success
V/StagefrightPlayer(  249): reset
V/AwesomePlayer(  249): reset_l()
V/AwesomePlayer(  249): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  249): notify(0xb8091378, 8, 0, 0)
V/AudioCache(  249): ignored
V/AwesomePlayer(  249): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  249): mAudioTrackVector clear
I/OMXCodec(  249): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec(  249): [OMX.google.vorbis.decoder] stop() sendCommand(0x43, OMX_CommandStateSet, OMX_StateIdle)
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
V/MediaPlayer( 4541): decode(75, 30402580, 4509)
V/MediaPlayerService(  249): decode(33, 30402580, 4509)
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
V/StagefrightPlayer(  249): setDataSource(33, 30402580, 4509)
V/AwesomePlayer(  249): reset_l()
V/AwesomePlayer(  249): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  249): notify(0xb809afd0, 8, 0, 0)
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
V/AudioCache(  249): notify(0xb809afd0, 200, 973, 0)
V/AudioCache(  249): ignored
V/AwesomePlayer(  249): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  249): notify(0xb809afd0, 5, 0, 0)
V/AudioCache(  249): ignored
V/AwesomePlayer(  249): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  249): notify(0xb809afd0, 1, 0, 0)
V/AudioCache(  249): prepared
V/AudioCache(  249): wait - success
V/MediaPlayerService(  249): start
V/StagefrightPlayer(  249): start
V/AwesomePlayer(  249): play
V/AwesomePlayer(  249): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer(  249): startAudioPlayer_l, sendErrorNotification (0)
W/ActivityManager(  749): Permission Denial: getCurrentUser() from pid=4661, uid=10179 requires android.permission.INTERACT_ACROSS_USERS
I/OMXCodec(  249): [OMX.google.vorbis.decoder] End Of Stream
I/OMXCodec(  249): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec(  249): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec(  249): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/AudioPlayer(  249):  Audioplayer kKeyAudioPCMFormat:1, 2, 0
I/AudioPlayer(  249):  Audioplayer kKeyAudioPCMFormat read fail(2, 1)
V/AudioCache(  249): open(44100, 2, 0x0, 1, 4)
V/AwesomePlayer(  249): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache(  249): notify(0xb809afd0, 6, 0, 0)
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
V/AudioCache(  249): notify(0xb809afd0, 2, 0, 0)
V/AudioCache(  249): playback complete - thread will wake up later
V/AwesomePlayer(  249): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  249): notify(0xb809afd0, 7, 0, 0)
V/AudioCache(  249): ignored
V/AwesomePlayer(  249): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer(  249): addBatteryData
V/AudioCache(  249): wait - success
V/StagefrightPlayer(  249): reset
V/AwesomePlayer(  249): reset_l()
V/AwesomePlayer(  249): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  249): notify(0xb809afd0, 8, 0, 0)
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
E/SMD     (  240): DCD ON
W/ActivityManager(  749): Permission Denial: getCurrentUser() from pid=4661, uid=10179 requires android.permission.INTERACT_ACROSS_USERS
V/WebViewChromium( 4661): Binding Chromium to the background looper Looper (main, tid 1) {42267790}
I/chromium( 4661): [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserProcessMain( 4661): Initializing chromium process, renderers=0
W/chromium( 4661): [WARNING:proxy_service.cc(888)] PAC support disabled because there is no system implementation
D/CustomFrequencyManagerService(  749): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 749  tag : ACTIVITY_RESUME_BOOSTER@5
W/ActivityManager(  749): mDVFSHelper.release()
D/CustomFrequencyManagerService(  749): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 749  pkgName : ACTIVITY_RESUME_BOOSTER@9
,I/SELinux ( 4697): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 4697):  
I/ActivityManager(  749): Killing 3210:com.sec.android.app.camera/u0a147 (adj 15): empty #43
,I/SELinux ( 4697): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 4697):  
I/SELinux ( 4697):  
,I/SELinux ( 4697): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 4697): [DEBUG] seapp_context_lookup: seinfoCategory = default
E/dalvikvm( 4697): >>>>> Normal User
,E/dalvikvm( 4697): >>>>> com.osp.app.signin [ userId:0 | appId:10043 ]
,E/SELinux ( 4697): [DEBUG] seapp_context_lookup: seinfoCategory = default
,D/TimaKeyStoreProvider( 4697): in addTimaSignatureService
,D/TimaKeyStoreProvider( 4697): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 4697): Added TimaKesytore provider
,I/SA      ( 4697): [SSP] onCreated
,I/SA      ( 4697): [TPM] There is no property file
,I/SA      ( 4697): [SCU] isHaveSA() - false
,I/SA      ( 4697): [TPM] getModelProperty : null
,I/SA      ( 4697): [TPM] getCSCProperty : null
,I/SA      ( 4697): [PMR] Received action : android.intent.action.PACKAGE_ADDED
,I/SA      ( 4697): [DM] init START
,I/SA      ( 4697): [DM] This device is not a Vodafone
,I/SA      ( 4697): [DM] getCountryCodeFromCSC : PL
I/SA      ( 4697): support phone number id : false
,I/SA      ( 4697): [DM] init END
,I/SA      ( 4697): [SUR] onReceive log=[SA = 2.0.0117 V = 19 HWD = 1280X720 2.0 dpi = 320  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = kmini3g P = kmini3gxx I = KOT49H M = SM-G800H OKLEFT false DIS KOT49H.G800HXXU1ANK2 PSS = 4.497045606779314  ]
,I/SA      ( 4697): [SUR] onReceive Intent=[ action.PACKAGE_ADDED. package ]
I/ActivityManager(  749): Killing 3317:com.android.email/u0a155 (adj 15): empty #43
,D/Mms/PackageInstallReceiver( 3829): loadAuthorityPref(): sEnableAuthority = true
,I/IcingCorporaProvider( 2119): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
,W/ContextImpl( 2845): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1857 android.content.ContextWrapper.startService:506 android.content.ContextWrapper.startService:506 com.samsung.android.app.assistantmenu.AssistantMenuReceiver.onReceive:153 android.app.ActivityThread.handleReceiver:2698 
,I/SELinux ( 4716): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 4716):  
,I/SELinux ( 4716): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 4716):  
I/SELinux ( 4716):  
,I/SELinux ( 4716): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 4716): [DEBUG] seapp_context_lookup: seinfoCategory = samsung
E/dalvikvm( 4716): >>>>> Normal User
,E/dalvikvm( 4716): >>>>> com.sec.android.service.cm [ userId:0 | appId:10078 ]
,E/SELinux ( 4716): [DEBUG] seapp_context_lookup: seinfoCategory = samsung
,I/IcingCorporaProvider( 2119): UpdateCorporaTask done [took 89 ms] updated apps [took 89 ms] 
,D/TimaKeyStoreProvider( 4716): in addTimaSignatureService
,D/TimaKeyStoreProvider( 4716): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 4716): Added TimaKesytore provider
,D/CapabilityManagerService New( 4716): Receiver Broadcast:android.intent.action.PACKAGE_ADDED
W/ActivityManager(  749): Permission Denial: getCurrentUser() from pid=4716, uid=10078 requires android.permission.INTERACT_ACROSS_USERS
,I/SELinux ( 4728): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 4728):  
,I/ActivityManager(  749): Killing 3313:com.samsung.android.provider.shootingmodeprovider/u0a162 (adj 15): empty #43
,I/SELinux ( 4728): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 4728):  
I/SELinux ( 4728):  
,I/SELinux ( 4728): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 4728): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 4728): >>>>> Normal User
E/dalvikvm( 4728): >>>>> com.google.android.apps.docs [ userId:0 | appId:10090 ]
E/SELinux ( 4728): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
D/TimaKeyStoreProvider( 4728): in addTimaSignatureService
D/TimaKeyStoreProvider( 4728): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 4728): Added TimaKesytore provider
,I/Adreno-EGL( 4661): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 4661): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 4661): Build Date: 03/21/14 Fri
I/Adreno-EGL( 4661): Local Branch: AU200+patches_03212014
I/Adreno-EGL( 4661): Remote Branch: 
I/Adreno-EGL( 4661): Local Patches: 
I/Adreno-EGL( 4661): Reconstruct Branch: 
,I/SurfaceFlinger(  246): id=17 Removed TettingsRec (8/12)
,I/SurfaceFlinger(  246): id=17 Removed TettingsRec (-2/12)
,D/KeyguardUpdateMonitor( 1064): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1064): handleKeyguardVisibilityChanged(1)
,I/SurfaceFlinger(  246): id=8 Removed Mauncher (7/11)
,I/SurfaceFlinger(  246): id=8 Removed Mauncher (-2/11)
I/SecureStorage(  294): [INFO]: SPID(0x00000003)Secure Storage Daemon finished processing with result: 0
,I/SecureStorage(  294): [INFO]: SPID(0x00000003)PID: 4563, TID: 4563
,D/KeyguardUpdateMonitor( 1064): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1064): handleKeyguardVisibilityChanged(1)
,D/SurfaceWidgetClient$ISurfaceWidgetStub( 1441): [237392/5] Surface widget visibility changed visibility = false on instance = 1
,D/Launcher( 1241): onTrimMemory. Level: 20
,I/dalvikvm( 4661): Could not find method android.webkit.CookieManager.setAcceptThirdPartyCookies, referenced from method org.apache.cordova.engine.SystemCookieManager.<init>
W/dalvikvm( 4661): VFY: unable to resolve virtual method 218: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
D/dalvikvm( 4661): VFY: replacing opcode 0x6e at 0x0016
I/dalvikvm( 4661): Could not find method android.webkit.CookieManager.flush, referenced from method org.apache.cordova.engine.SystemCookieManager.flush
W/dalvikvm( 4661): VFY: unable to resolve virtual method 213: Landroid/webkit/CookieManager;.flush ()V
D/dalvikvm( 4661): VFY: replacing opcode 0x6e at 0x0008
W/dalvikvm( 4661): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
I/SecureStorage( 4563): [INFO]: SPID(0x00000000)Processing data has been completed
W/dalvikvm( 4661): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
I/SecureStorage( 4563): [INFO]: SPID(0x00000000)WARNING! Failed to find SecureStorageExceptionJNI!..
I/SQLiteSecureOpenHelper( 4563): getWritableDatabase(pwd)
I/SQLiteSecureOpenHelper( 4563): getDatabaseLocked(b,b,pwd)...
I/SQLiteSecureOpenHelper( 4563): Open platform.db in secure mode
I/dalvikvm( 4661): Could not find method android.webkit.WebViewClient.onReceivedClientCertRequest, referenced from method org.apache.cordova.engine.SystemWebViewClient.onReceivedClientCertRequest
W/dalvikvm( 4661): VFY: unable to resolve virtual method 271: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
D/dalvikvm( 4661): VFY: replacing opcode 0x6f at 0x001a
W/dalvikvm( 4661): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
I/dalvikvm( 4661): Could not find method android.webkit.PermissionRequest.getResources, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onPermissionRequest
W/dalvikvm( 4661): VFY: unable to resolve virtual method 229: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
D/dalvikvm( 4661): VFY: replacing opcode 0x6e at 0x000d
I/dalvikvm( 4661): Could not find method android.webkit.WebChromeClient$FileChooserParams.createIntent, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onShowFileChooser
W/dalvikvm( 4661): VFY: unable to resolve virtual method 234: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
D/dalvikvm( 4661): VFY: replacing opcode 0x6e at 0x0000
D/SystemWebViewEngine( 4661): CordovaWebView is running on device made by: samsung
W/ActivityManager(  749): Permission Denial: getCurrentUser() from pid=4728, uid=10090 requires android.permission.INTERACT_ACROSS_USERS
I/SurfaceFlinger(  246): id=18 createSurf (1x1),1 flag=404, NainActivit
D/KeyguardUpdateMonitor( 1064): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1064): handleKeyguardVisibilityChanged(1)
D/KeyguardUpdateMonitor( 1064): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1064): handleKeyguardVisibilityChanged(1)
I/HWUI    ( 4661): EGLImpl-HWUI Protected EGL context created
I/SQLiteSecureOpenHelper( 4563): ...getDatabaseLocked(b,b,pwd)
D/SQLiteSecureOpenHelper( 4563): ...getDatabaseLocked(b,b,pwd)
D/OpenGLRenderer( 4661): Enabling debug mode 0
D/OpenGLRenderer( 4661): GL error from OpenGLRenderer: 0x502
E/OpenGLRenderer( 4661):   GL_INVALID_OPERATION
D/KeyguardUpdateMonitor( 1064): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1064): handleKeyguardVisibilityChanged(1)
I/ActivityManager(  749): Killing 3342:com.sec.modem.settings/1000 (adj 15): empty #43
D/KeyguardUpdateMonitor( 1064): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1064): handleKeyguardVisibilityChanged(1)
D/CustomFrequencyManagerService(  749): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 749  tag : ACTIVITY_RESUME_BOOSTER@9
D/JsMessageQueue( 4661): Set native->JS mode to OnlineEventsBridgeMode
W/GAV2    ( 4728): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
I/SELinux ( 4763): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 4763):  
I/SELinux ( 4763): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 4763):  
I/SELinux ( 4763):  
I/SELinux ( 4763): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 4763): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 4763): >>>>> Normal User
E/dalvikvm( 4763): >>>>> com.samsung.android.app.watchmanagerstub [ userId:0 | appId:10100 ]
E/SELinux ( 4763): [DEBUG] seapp_context_lookup: seinfoCategory = platform
D/dalvikvm( 4661): Trying to load lib /data/app-lib/com.test.thalitest-47/libjxcore.so 0x4258e570
D/dalvikvm( 4661): Added shared lib /data/app-lib/com.test.thalitest-47/libjxcore.so 0x4258e570
D/jxcore_app_log( 4661): JniHelper::setJavaVM(0x41755528), pthread_self() = 2033297472
D/JX-Cordova( 4661): jxcore cordova android initializing
D/TimaKeyStoreProvider( 4763): in addTimaSignatureService
D/TimaKeyStoreProvider( 4763): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 4763): Added TimaKesytore provider
D/PackageIntentReceiver( 4763): ACTION_PACKAGE_ADDED
D/PackageIntentReceiver( 4763): Not GearManger package! 
I/SELinux ( 4778): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 4778):  
I/ActivityManager(  749): Killing 1332:com.sec.android.provider.badge/u0a72 (adj 15): empty #43
I/SELinux ( 4778): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 4778):  
I/SELinux ( 4778):  
I/SELinux ( 4778): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 4778): [DEBUG] seapp_context_lookup: seinfoCategory = release
E/dalvikvm( 4778): >>>>> Normal User
E/dalvikvm( 4778): >>>>> com.samsung.android.magazine.service [ userId:0 | appId:10106 ]
E/SELinux ( 4778): [DEBUG] seapp_context_lookup: seinfoCategory = release
D/TimaKeyStoreProvider( 4778): in addTimaSignatureService
D/TimaKeyStoreProvider( 4778): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 4778): Added TimaKesytore provider
D/MagazineService Version( 4778): Magazine-Channel: 13
D/MagazineService Version( 4778): Magazine-Provider: 13
D/MagazineService Version( 4778): Magazine-Administrator: 11
D/HeadlinesChannelApplication( 4778): [onCreate]
D/MagazineService::MagazineBroadcastReceiver( 4778): [onReceive] android.intent.action.PACKAGE_ADDED com.test.thalitest
W/ActivityManager(  749): Permission Denial: getCurrentUser() from pid=4778, uid=10106 requires android.permission.INTERACT_ACROSS_USERS
I/MagazineService::MagazineService( 4778): [onHandleIntent] ACTION_PACKAGE_INSTALLED
I/SELinux ( 4791): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 4791):  
D/MagazineService::MagazineService( 4778): [onHandleIntent] Send broadcast to (com.test.thalitest).
I/ActivityManager(  749): Killing 3366:tv.peel.smartremote/u0a163 (adj 15): empty #43
,I/SELinux ( 4791): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 4791):  
I/SELinux ( 4791):  
,I/SELinux ( 4791): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 4791): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 4791): >>>>> Normal User
,E/dalvikvm( 4791): >>>>> com.samsung.helphub [ userId:0 | appId:1000 ]
,E/SELinux ( 4791): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 4791): in addTimaSignatureService
,D/TimaKeyStoreProvider( 4791): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 4791): Added TimaKesytore provider
,D/dalvikvm( 4661): GC_CONCURRENT freed 4933K, 31% free 12759K/18408K, paused 3ms+3ms, total 46ms
,D/dalvikvm( 4661): WAIT_FOR_CONCURRENT_GC blocked 23ms
,W/GAV2    ( 4728): Thread[main,5,main]: dispatch call queued.  Need to call GAServiceManager.getInstance().initialize().
I/ActivityManager(  749): Killing 3391:org.simalliance.openmobileapi.service/1101 (adj 15): empty #43
,I/SELinux ( 4805): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 4805):  
,I/ActivityManager(  749): Killing 3451:com.sec.android.app.taskmanager/u0a166 (adj 15): empty #43
,I/SELinux ( 4805): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 4805):  
I/SELinux ( 4805):  
,I/SELinux ( 4805): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 4805): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 4805): >>>>> Normal User
,E/dalvikvm( 4805): >>>>> com.sec.kidsplat.installer [ userId:0 | appId:10158 ]
,E/SELinux ( 4805): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 4805): in addTimaSignatureService
,D/TimaKeyStoreProvider( 4805): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 4805): Added TimaKesytore provider
,W/ActivityManager(  749): Permission Denial: getCurrentUser() from pid=4805, uid=10158 requires android.permission.INTERACT_ACROSS_USERS
,D/KidsPlatformStub( 4805): Package not found : com.sec.android.app.kidshome
,I/SELinux ( 4817): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 4817):  
I/ActivityManager(  749): Killing 3470:com.samsung.android.service.travel/u0a169 (adj 15): empty #43
,I/SELinux ( 4817): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 4817):  
I/SELinux ( 4817):  
,I/SELinux ( 4817): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 4817): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 4817): >>>>> Normal User
,E/dalvikvm( 4817): >>>>> com.samsung.android.provider.shootingmodeprovider [ userId:0 | appId:10162 ]
,E/SELinux ( 4817): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 4817): in addTimaSignatureService
,D/TimaKeyStoreProvider( 4817): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 4817): Added TimaKesytore provider
,I/SELinux ( 4829): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 4829):  
,I/ActivityManager(  749): Killing 3483:com.google.android.youtube/u0a175 (adj 15): empty #43
,I/SELinux ( 4829): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 4829):  
I/SELinux ( 4829):  
,I/SELinux ( 4829): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 4829): [DEBUG] seapp_context_lookup: seinfoCategory = samsung
E/dalvikvm( 4829): >>>>> Normal User
E/dalvikvm( 4829): >>>>> com.sec.android.app.samsungapps [ userId:0 | appId:10040 ]
E/SELinux ( 4829): [DEBUG] seapp_context_lookup: seinfoCategory = samsung
,D/TimaKeyStoreProvider( 4829): in addTimaSignatureService
,D/TimaKeyStoreProvider( 4829): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 4829): Added TimaKesytore provider
,D/dalvikvm( 4661): GC_FOR_ALLOC freed 4695K, 26% free 15770K/21204K, paused 37ms, total 37ms
,D/AmoledAdjustTimer(  749): prevTemp = 286, currTemp = 287, prevStep = 4, currStep = 4
,I/ActivityManager(  749): Killing 3672:com.sec.android.widgetapp.activeapplicationwidget/u0a152 (adj 15): empty #43
,D/Finsky  ( 3555): [1] ExternalReferrer.access$200: Package state data is missing for com.test.thalitest
,D/ChimeraCfgMgr( 1784): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 1784): Loading module APK com.google.android.play.games
,D/PackageBroadcastService( 1784): Received broadcast action=android.intent.action.PACKAGE_ADDED and uri=com.test.thalitest
I/dalvikvm( 1784): Could not find method android.app.admin.DevicePolicyManager.getProfileOwner, referenced from method com.google.android.gms.auth.WorkAccountAuthenticatorInitializer.a
W/dalvikvm( 1784): VFY: unable to resolve virtual method 174: Landroid/app/admin/DevicePolicyManager;.getProfileOwner ()Landroid/content/ComponentName;
,D/dalvikvm( 1784): VFY: replacing opcode 0x6e at 0x0053
,I/dalvikvm( 1784): Failed resolving Lcom/google/android/gms/common/permission/PermissionUtils$1; interface 96 'Landroid/content/pm/PackageManager$OnPermissionsChangedListener;'
,W/dalvikvm( 1784): Link of class 'Lcom/google/android/gms/common/permission/PermissionUtils$1;' failed
E/dalvikvm( 1784): Could not find class 'com.google.android.gms.common.permission.PermissionUtils$1', referenced from method com.google.android.gms.chimera.GmsModuleInitializer.initializeModuleV0
W/dalvikvm( 1784): VFY: unable to resolve new-instance 2374 (Lcom/google/android/gms/common/permission/PermissionUtils$1;) in Lcom/google/android/gms/chimera/GmsModuleInitializer;
,D/dalvikvm( 1784): VFY: replacing opcode 0x22 at 0x001a
I/dalvikvm( 1784): Failed resolving Lcom/google/android/gms/common/permission/PermissionUtils$1; interface 96 'Landroid/content/pm/PackageManager$OnPermissionsChangedListener;'
W/dalvikvm( 1784): Link of class 'Lcom/google/android/gms/common/permission/PermissionUtils$1;' failed
,D/dalvikvm( 1784): DexOpt: unable to opt direct call 0x338d at 0x1c in Lcom/google/android/gms/chimera/GmsModuleInitializer;.initializeModuleV0
,D/dalvikvm( 1784): GC_CONCURRENT freed 1922K, 38% free 11419K/18408K, paused 6ms+12ms, total 119ms
,D/ChimeraCfgMgr( 1784): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 1784): Module APK com.google.android.play.games already loaded
,D/ChimeraCfgMgr( 1784): Loading module com.google.android.gms.gass from APK com.google.android.gms
,D/AsyncTaskServiceImpl( 1784): Submit a task: k
,D/ChimeraCfgMgr( 1784): Loading module com.google.android.gms.gass from APK com.google.android.gms
,D/ChimeraCfgMgr( 1784): Loading module com.google.android.gms.vision from APK com.google.android.gms
,D/k       ( 1784): Processing package: com.test.thalitest
,D/GassUtils( 1784): Found app info for package com.test.thalitest:18. Hash: 4eebbbb84f07ed56a3e96e5e8f9d6abddaaf154fffa2a65432a1006e0fa38f32
,D/k       ( 1784): Found info for package com.test.thalitest in db.
,D/dalvikvm( 4661): GC_FOR_ALLOC freed 5056K, 30% free 16783K/23892K, paused 36ms, total 37ms
,W/BaseAppContext( 1784): Using Auth Proxy for data requests.
,W/BaseAppContext( 1784): Using Auth Proxy for data requests.
,I/dalvikvm-heap( 4661): Grow heap (frag case) to 21.448MB for 2475476-byte allocation
,D/dalvikvm( 1319): GC_EXPLICIT freed 954K, 42% free 10755K/18408K, paused 5ms+10ms, total 64ms
,W/BaseAppContext( 1784): Using Auth Proxy for data requests.
,W/dalvikvm( 1784): VFY: unable to find class referenced in signature (Landroid/app/SharedElementCallback;)
I/dalvikvm( 1784): Could not find method android.app.Activity.setEnterSharedElementCallback, referenced from method android.support.v4.app.w.setEnterSharedElementCallback
W/dalvikvm( 1784): VFY: unable to resolve virtual method 53: Landroid/app/Activity;.setEnterSharedElementCallback (Landroid/app/SharedElementCallback;)V
,D/dalvikvm( 1784): VFY: replacing opcode 0x6e at 0x000e
W/dalvikvm( 1784): VFY: unable to find class referenced in signature (Landroid/app/SharedElementCallback;)
I/dalvikvm( 1784): Could not find method android.app.Activity.setExitSharedElementCallback, referenced from method android.support.v4.app.w.setExitSharedElementCallback
W/dalvikvm( 1784): VFY: unable to resolve virtual method 54: Landroid/app/Activity;.setExitSharedElementCallback (Landroid/app/SharedElementCallback;)V
D/dalvikvm( 1784): VFY: replacing opcode 0x6e at 0x000e
I/dalvikvm( 1784): Could not find method android.app.Activity.finishAfterTransition, referenced from method android.support.v4.app.w.supportFinishAfterTransition
W/dalvikvm( 1784): VFY: unable to resolve virtual method 31: Landroid/app/Activity;.finishAfterTransition ()V
D/dalvikvm( 1784): VFY: replacing opcode 0x6e at 0x0006
I/dalvikvm( 1784): Could not find method android.app.Activity.postponeEnterTransition, referenced from method android.support.v4.app.w.supportPostponeEnterTransition
W/dalvikvm( 1784): VFY: unable to resolve virtual method 49: Landroid/app/Activity;.postponeEnterTransition ()V
D/dalvikvm( 1784): VFY: replacing opcode 0x6e at 0x0006
I/dalvikvm( 1784): Could not find method android.app.Activity.startPostponedEnterTransition, referenced from method android.support.v4.app.w.supportStartPostponedEnterTransition
W/dalvikvm( 1784): VFY: unable to resolve virtual method 61: Landroid/app/Activity;.startPostponedEnterTransition ()V
,D/dalvikvm( 1784): VFY: replacing opcode 0x6e at 0x0006
,W/BaseAppContext( 1784): Using Auth Proxy for data requests.
,W/BaseAppContext( 1784): Using Auth Proxy for data requests.
,W/BaseAppContext( 1784): Using Auth Proxy for data requests.
,W/BaseAppContext( 1784): Using Auth Proxy for data requests.
,I/PeopleDatabaseHelper( 1784): cleanUpNonGplusAccounts done.
,D/dalvikvm( 4661): GC_FOR_ALLOC freed 3777K, 34% free 17471K/26312K, paused 32ms, total 32ms
,E/SMD     (  240): DCD ON
,W/dalvikvm( 1784): VFY: unable to find class referenced in signature (Landroid/util/Size;)
,D/dalvikvm( 4661): GC_FOR_ALLOC freed 1222K, 34% free 17371K/26312K, paused 29ms, total 29ms
,D/ChimeraCfgMgr( 1784): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 1784): Module APK com.google.android.play.games already loaded
,W/jxcore-log( 4661): Initializing JXcore engine
,W/jxcore-log( 4661): JXcore engine is ready
,W/jxcore-log( 4661): Starting JXcore engine
,D/BatteryService(  749): level:100, scale:100, status:5, health:2, present:true, voltage: 4365, temperature: 288, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:5, charge type:1, power sharing:false
,D/BatteryService(  749): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  749): stay LED for fully charged
,D/UiModeManager(  749): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 1064): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1064): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1064):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1064): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP(  749): SIOP:: AP = 310, Delta = 10
,D/STATUSBAR-IconMerger( 1064): checkOverflow(384), More:false, Req:false Child:2
,W/jxcore-log( 4661): Platform android
W/jxcore-log( 4661): 
,W/jxcore-log( 4661): Process ARCH arm
W/jxcore-log( 4661): 
,I/Icing   ( 1784): Indexing 49CA7E3A917E607C6D98AA15891295369CED2106 from com.google.android.gms
,D/dalvikvm(  749): GC_EXPLICIT freed 2177K, 60% free 23363K/57632K, paused 5ms+14ms, total 124ms
,D/dalvikvm( 1784): GC_CONCURRENT freed 1635K, 36% free 11812K/18408K, paused 3ms+3ms, total 27ms
,I/Icing   ( 1784): Indexing done 49CA7E3A917E607C6D98AA15891295369CED2106
,I/jxcore-log( 4661): JXcore Cordova bridge is ready!
I/jxcore-log( 4661): 
,W/jxcore-log( 4661): JXcore engine is started
,I/chromium( 4661): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot call method 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,E/SMD     (  240): DCD ON
,I/jxcore-log( 4661): Toggling radios to true
I/jxcore-log( 4661): 
,W/ActivityManager(  749): Permission Denial: getCurrentUser() from pid=4661, uid=10179 requires android.permission.INTERACT_ACROSS_USERS
,W/BluetoothManagerService(  749): Failed getting userId using ActivityManagerNative
W/BluetoothManagerService(  749): java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=4661, uid=10179 requires android.permission.INTERACT_ACROSS_USERS
W/BluetoothManagerService(  749): 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:20710)
W/BluetoothManagerService(  749): 	at com.android.server.BluetoothManagerService.enable(BluetoothManagerService.java:620)
W/BluetoothManagerService(  749): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:98)
W/BluetoothManagerService(  749): 	at android.os.Binder.execTransact(Binder.java:404)
W/BluetoothManagerService(  749): 	at dalvik.system.NativeStart.run(Native Method)
E/DevicePolicyManagerService(  749): getAllowBluetoothMode - value retunrs : 2
,D/BluetoothManagerService(  749): foregroundUser: 0
,E/BluetoothManagerService(  749): Package is exist.
D/BluetoothAdapterState( 3191): CURRENT_STATE=OFF, MSG = USER_TURN_ON
,I/BluetoothAdapterState( 3191): Bluetooth adapter state changed: 10-> 11
,D/BluetoothAdapterService( 3191): Bluetooth PBAP supproted is true
D/BluetoothAdapterService( 3191): updateAdapterState state is 11
,D/BluetoothAdapterService( 3191): Broadcasting updateAdapterState() to 1 receivers.
D/BluetoothAdapterService( 3191): Autoconnection is available 
,D/BluetoothAdapterService( 3191): updateAdapterState prevState = 10newState = 11
D/BtConfig.SecureMode( 3191): isSecureModeOn:false
,D/BtSettings.ProfileConfig( 3191): getProfileSaveSetting: com.android.bluetooth.gatt.GattService
,W/BluetoothAdapterService( 3191): isProfileEnabled(): profile com.android.bluetooth.gatt.GattService, state= 12
,D/BtSettings.ProfileConfig( 3191): getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
,W/BluetoothAdapterService( 3191): isProfileEnabled(): profile not found com.android.bluetooth.hfp.HeadsetService
,D/BtSettings.ProfileConfig( 3191): getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
,W/BluetoothAdapterService( 3191): isProfileEnabled(): profile not found com.android.bluetooth.a2dp.A2dpService
,D/BtSettings.ProfileConfig( 3191): getProfileSaveSetting: com.android.bluetooth.hid.HidService
,W/BluetoothAdapterService( 3191): isProfileEnabled(): profile not found com.android.bluetooth.hid.HidService
,D/BtSettings.ProfileConfig( 3191): getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
,W/BluetoothAdapterService( 3191): isProfileEnabled(): profile not found com.android.bluetooth.hdp.HealthService
,D/BtSettings.ProfileConfig( 3191): getProfileSaveSetting: com.android.bluetooth.pan.PanService
,W/BluetoothAdapterService( 3191): isProfileEnabled(): profile not found com.android.bluetooth.pan.PanService
,D/BtSettings.ProfileConfig( 3191): getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
,W/BluetoothAdapterService( 3191): isProfileEnabled(): profile not found com.android.bluetooth.map.BluetoothMapService
,W/BluetoothAdapterService( 3191): Unable to stop service com.android.bluetooth.gatt.GattService. Invalid state: 12
W/BluetoothAdapterService( 3191): check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.hfp.HeadsetService
,D/BtSettings.ProfileConfig( 3191): getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
,W/BluetoothAdapterService( 3191): Not skipping com.android.bluetooth.hfp.HeadsetService
,W/InputMethodManagerService(  749): InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
,I/InputMethodManagerService(  749): [BT Setting State] State =11
D/PhoneApp( 1237): mReceiver: BluetoothAdapter.ACTION_STATE_CHANGED: 11
I/QuickConnect[1.1][2] ( 3162): BluetoothHelper.ACTION_STATE_CHANGED - STATE_TURNING_ON
W/BluetoothAdapterService( 3191): check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.a2dp.A2dpService
D/BtSettings.ProfileConfig( 3191): getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
W/BluetoothAdapterService( 3191): Not skipping com.android.bluetooth.a2dp.A2dpService
I/WifiManager( 4661): packageName : com.test.thalitest
I/WifiManager( 4661): setWifiEnabled : true
,I/WifiService(  749): setWifiEnabled: true pid=4661, uid=10179
,D/HeadsetService( 3191): Received start request. Starting profile...
,I/BluetoothHeadsetServiceJni( 3191): classInitNative: succeeds
D/HeadsetStateMachine( 3191): Version 1.6
,D/HeadsetStateMachine( 3191): make
,E/HeadsetStateMachine( 3191): # of Max HF connection is 2
,D/QuickConnect[1.1][2] ( 3162): HeadsetProfile.onServiceConnected - Bluetooth service connected
W/ActivityManager(  749): Permission Denial: getCurrentUser() from pid=4661, uid=10179 requires android.permission.INTERACT_ACROSS_USERS
,W/WifiService(  749): Failed getting userId using ActivityManagerNative
W/WifiService(  749): java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=4661, uid=10179 requires android.permission.INTERACT_ACROSS_USERS
W/WifiService(  749): 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:20710)
W/WifiService(  749): 	at com.android.server.wifi.WifiService.setWifiEnabled(WifiService.java:2348)
W/WifiService(  749): 	at com.android.server.wifi.WifiService.setWifiEnabled(WifiService.java:2336)
W/WifiService(  749): 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:178)
W/WifiService(  749): 	at android.os.Binder.execTransact(Binder.java:404)
W/WifiService(  749): 	at dalvik.system.NativeStart.run(Native Method)
,I/bluedroid( 3191): get_profile_interface handsfree
,D/BluetoothAtMessage( 3191): createCMTIContentObservers
,D/HeadsetStateMachine( 3191): Enter Disconnected: -2
,E/HeadsetStateMachine( 3191): set to mRemoteBrsf = 0
,E/WifiHW  (  749): ##################### set firmware type 0 #####################
D/HeadsetStateMachine( 3191): map size, before remove : 0
D/HeadsetStateMachine( 3191): map size, after remove: 0
,D/HeadsetStateMachine( 3191): mNextConnectingDevice : null
W/BluetoothAdapterService( 3191): check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.hid.HidService
,I/WifiService(  749): disconnect: pid=4661, uid=10179
D/BtSettings.ProfileConfig( 3191): getProfileSaveSetting: com.android.bluetooth.hid.HidService
,W/BluetoothAdapterService( 3191): Not skipping com.android.bluetooth.hid.HidService
,I/jxcore-log( 4661): Radios toggled
I/jxcore-log( 4661): 
,D/HeadsetStateMachine( 3191): Try to query the phonestate on bind
,D/BluetoothPhoneService( 1237): handleMessage: 4
,V/BluetoothPhoneService( 1237): Call state Converted2: IDLE/IDLE -> 6
,W/BluetoothHeadset( 1237): Proxy not attached to service
,D/HeadsetPhoneState( 3191): sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=0
,D/HeadsetStateMachine( 3191): Disconnected process message: 11
,I/jxcore-log( 4661): Got Device Bluetooth address: 38:94:96:B5:06:DC
I/jxcore-log( 4661): 
W/BluetoothAdapterService( 3191): check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.hdp.HealthService
,D/BtSettings.ProfileConfig( 3191): getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
,W/BluetoothAdapterService( 3191): Not skipping com.android.bluetooth.hdp.HealthService
D/A2dpService( 3191): Received start request. Starting profile...
I/BluetoothA2dpServiceJni( 3191): classInitNative: succeeds
D/BluetoothA2dp(  749): Proxy object connected
,D/A2dpStateMachine( 3191): make
,D/BluetoothA2dp( 3162): Proxy object connected
,I/jxcore-log( 4661): Perf Test app loaded loaded
I/jxcore-log( 4661): 
,D/QuickConnect[1.1][2] ( 3162): A2dpProfile.onServiceConnected - Bluetooth service connected
,I/bluedroid( 3191): get_profile_interface a2dp
W/BluetoothAdapterService( 3191): check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.pan.PanService
,D/BtSettings.ProfileConfig( 3191): getProfileSaveSetting: com.android.bluetooth.pan.PanService
I/GKI_LINUX( 3191): gki_task_entry: gki_task_entry task_id=2 [A2DP-MEDIA] starting
,W/BluetoothAdapterService( 3191): Not skipping com.android.bluetooth.pan.PanService
,W/BluetoothAdapterService( 3191): check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.map.BluetoothMapService
,D/BtSettings.ProfileConfig( 3191): getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
,W/BluetoothAdapterService( 3191): Not skipping com.android.bluetooth.map.BluetoothMapService
,D/BluetoothA2dp( 2014): Proxy object connected
,I/BluetoothAdapterState( 3191): Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
,I/BluetoothAvrcpServiceJni( 3191): classInitNative: succeeds
I/bluedroid( 3191): get_profile_interface avrcp
D/A2dpStateMachine( 3191): Enter Disconnected: -2
D/MediaFocusControl(  749): >>> registerRemoteControlDisplay
E/MediaFocusControl(  749): Error updating focussed RCC to RCD 
E/MediaFocusControl(  749): java.util.EmptyStackException
E/MediaFocusControl(  749): 	at java.util.Stack.peek(Stack.java:57)
E/MediaFocusControl(  749): 	at android.media.MediaFocusControl.registerRemoteControlDisplay_int(MediaFocusControl.java:2308)
E/MediaFocusControl(  749): 	at android.media.MediaFocusControl.registerRemoteControlDisplay(MediaFocusControl.java:250)
E/MediaFocusControl(  749): 	at android.media.AudioService.registerRemoteControlDisplay(AudioService.java:6425)
E/MediaFocusControl(  749): 	at android.media.IAudioService$Stub.onTransact(IAudioService.java:593)
E/MediaFocusControl(  749): 	at android.os.Binder.execTransact(Binder.java:404)
E/MediaFocusControl(  749): 	at dalvik.system.NativeStart.run(Native Method)
D/HeadsetStateMachine( 3191): Proxy object connected
I/GAV2    ( 4728): Thread[GAThread,5,main]: No campaign data found.
D/HeadsetPhoneState( 3191): sendDeviceDataStateChanged
D/HeadsetStateMachine( 3191): Disconnected process message: 20
D/HeadsetPhoneState( 3191): Signal level : previous=0 curr=0
V/HeadsetService( 3191): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 3191): Disconnected process message: 10
I/jxcore-log( 4661): check test folder
I/jxcore-log( 4661): 
D/HeadsetPhoneState( 3191): sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
D/HeadsetStateMachine( 3191): Disconnected process message: 11
D/BluetoothAdapterService( 3191): Profile still not running:com.android.bluetooth.hdp.HealthService
I/BluetoothHidServiceJni( 3191): classInitNative: succeeds
I/jxcore-log( 4661): found test : ./testFindPeers.js
I/jxcore-log( 4661): 
D/HidService( 3191): Received start request. Starting profile...
I/bluedroid( 3191): get_profile_interface hidhost
D/HidService( 3191): setHidService(): set to: null
I/BluetoothHealthServiceJni( 3191): classInitNative: succeeds
D/BluetoothInputDevice( 3162): Proxy object connected
D/HealthService( 3191): Received start request. Starting profile...
I/bluedroid( 3191): get_profile_interface health
I/BluetoothPanServiceJni( 3191): classInitNative(L105): succeeds
D/QuickConnect[1.1][2] ( 3162): HidProfile.onServiceConnected - Bluetooth service connected
D/BluetoothPan(  749): BluetoothPAN Proxy object connected
D/PanService( 3191): Received start request. Starting profile...
D/BluetoothPanServiceJni( 3191): initializeNative(L110): pan
,I/bluedroid( 3191): get_profile_interface pan
,D/BluetoothTethering(  749): got CMD_CHANNEL_HALF_CONNECTED
D/BluetoothMapService( 3191): Received start request. Starting profile...
,D/BluetoothNotiBroadcastReceiver( 1303): onReceive
,W/BluetoothMapMasInstance( 3191): mAccount : null
,D/BluetoothAdapterService( 3191): Profile still not running:com.android.bluetooth.hdp.HealthService
D/BluetoothAdapterService( 3191): Profile still not running:com.android.bluetooth.hdp.HealthService
D/BluetoothAdapterService( 3191): Profile still not running:com.android.bluetooth.map.BluetoothMapService
,D/BluetoothAdapterService( 3191): Profile still not running:com.android.bluetooth.map.BluetoothMapService
,D/BluetoothAdapterState( 3191): CURRENT_STATE=PENDING, MSG = STARTED, isTurningOn=true, isTurningOff=false
,I/bluedroid( 3191): enable
D/GKI_LINUX( 3191): acquire_my_wake_lock(), g_wake_lock_fd:-1, g_wake_unlock_fd:-1, wake_lock_acquired:0
E/bt-btif ( 3191): Calling BTA_HhEnable
,E/bt-btif ( 3191): btif_storage_get_adapter_property service_mask:0x140040
E/BluetoothServiceJni( 3191): populateRssiValuesNative
I/bluedroid( 3191): getModelRssiValues
,E/BluetoothServiceJni( 3191): model_rssi_values_callback: low = -70, mid = -60, high = 127
,I/jxcore-log( 4661): found test : ./testSendData.js
I/jxcore-log( 4661): 
,D/AuthorizationBluetoothService( 1319): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,E/BluetoothRemoteDevices( 3191): devicePropertyChangedCallback: bdDevice: 08:EC:A9:50:75:41, value is empty for type: 10
,D/BtConfig.SecureMode( 3191): isSecureModeOn:false
,E/BluetoothRemoteDevices( 3191): devicePropertyChangedCallback: bdDevice: 08:EC:A9:50:75:41, value is empty for type: 241
,E/BluetoothRemoteDevices( 3191): devicePropertyChangedCallback: bdDevice: 80:01:84:8A:B3:68, value is empty for type: 10
,D/BtConfig.SecureMode( 3191): isSecureModeOn:false
,E/BluetoothRemoteDevices( 3191): devicePropertyChangedCallback: bdDevice: 80:01:84:8A:B3:68, value is empty for type: 241
E/BluetoothRemoteDevices( 3191): devicePropertyChangedCallback: bdDevice: 44:80:EB:7B:5A:05, value is empty for type: 10
,D/BtConfig.SecureMode( 3191): isSecureModeOn:false
,E/BluetoothRemoteDevices( 3191): devicePropertyChangedCallback: bdDevice: 44:80:EB:7B:5A:05, value is empty for type: 241
,E/BluetoothRemoteDevices( 3191): devicePropertyChangedCallback: bdDevice: F8:95:C7:87:85:54, value is empty for type: 10
,D/BtConfig.SecureMode( 3191): isSecureModeOn:false
,E/BluetoothRemoteDevices( 3191): devicePropertyChangedCallback: bdDevice: F8:95:C7:87:85:54, value is empty for type: 241
,E/BluetoothRemoteDevices( 3191): devicePropertyChangedCallback: bdDevice: B0:C5:59:3F:75:69, value is empty for type: 10
,D/BtConfig.SecureMode( 3191): isSecureModeOn:false
,E/BluetoothRemoteDevices( 3191): devicePropertyChangedCallback: bdDevice: B0:C5:59:3F:75:69, value is empty for type: 241
,D/GKI_LINUX( 3191): release_my_wake_lock(), g_wake_lock_fd:-1, g_wake_unlock_fd:-1, wake_lock_acquired:0
,E/BluetoothRemoteDevices( 3191): devicePropertyChangedCallback: bdDevice: 00:F4:6F:30:E0:6C, value is empty for type: 10
,D/BtConfig.SecureMode( 3191): isSecureModeOn:false
,E/BluetoothRemoteDevices( 3191): devicePropertyChangedCallback: bdDevice: 00:F4:6F:30:E0:6C, value is empty for type: 241
,E/BluetoothRemoteDevices( 3191): devicePropertyChangedCallback: bdDevice: 34:FC:EF:9D:93:0B, value is empty for type: 10
,D/BtConfig.SecureMode( 3191): isSecureModeOn:false
,E/BluetoothRemoteDevices( 3191): devicePropertyChangedCallback: bdDevice: 34:FC:EF:9D:93:0B, value is empty for type: 241
,E/BluetoothRemoteDevices( 3191): devicePropertyChangedCallback: bdDevice: 7C:F9:0E:51:18:22, value is empty for type: 10
,D/BtConfig.SecureMode( 3191): isSecureModeOn:false
,E/BluetoothRemoteDevices( 3191): devicePropertyChangedCallback: bdDevice: 7C:F9:0E:51:18:22, value is empty for type: 241
,E/BluetoothRemoteDevices( 3191): devicePropertyChangedCallback: bdDevice: B4:CE:F6:AB:A4:6A, value is empty for type: 10
,D/BtConfig.SecureMode( 3191): isSecureModeOn:false
,E/BluetoothRemoteDevices( 3191): devicePropertyChangedCallback: bdDevice: B4:CE:F6:AB:A4:6A, value is empty for type: 241
,E/BluetoothRemoteDevices( 3191): devicePropertyChangedCallback: bdDevice: 34:FC:EF:11:AE:67, value is empty for type: 10
,D/BtConfig.SecureMode( 3191): isSecureModeOn:false
,E/BluetoothRemoteDevices( 3191): devicePropertyChangedCallback: bdDevice: 34:FC:EF:11:AE:67, value is empty for type: 241
,E/BluetoothRemoteDevices( 3191): devicePropertyChangedCallback: bdDevice: 34:FC:EF:11:B1:66, value is empty for type: 10
,D/BtConfig.SecureMode( 3191): isSecureModeOn:false
,E/BluetoothRemoteDevices( 3191): devicePropertyChangedCallback: bdDevice: 34:FC:EF:11:B1:66, value is empty for type: 241
,E/BluetoothRemoteDevices( 3191): devicePropertyChangedCallback: bdDevice: 90:E7:C4:F6:69:77, value is empty for type: 10
,D/BtConfig.SecureMode( 3191): isSecureModeOn:false
,E/BluetoothRemoteDevices( 3191): devicePropertyChangedCallback: bdDevice: 90:E7:C4:F6:69:77, value is empty for type: 241
E/bt-btif ( 3191): btif_handle_bluetooth_enable_evt: btif_core_radio_ref_count:2
E/bt-btif ( 3191): btif_sock_init, radio_req:0, rfc_init:0, vhci_init:1
E/bt-btif ( 3191): btif_sock_init: !radio_req && !rfc_init
,D/IOP_DB_BT( 3191): db_open: file /etc/bluetooth/iop_bt.db
,D/IOP_DB_BT( 3191): db_open: db_open : handle 2012574488l, read 9734 bytes onto local cache
D/IOP_DB_BT( 3191): db_query: id __IOPFLAGS :: key __KEY_ENABLE_VERBOSE, value 1
D/IOP_DB_BT( 3191): db_query: result 1
I/        ( 3191): iop_db_open: iop_db_open status 0
,D/GKI_LINUX( 3191): acquire_my_wake_lock(), g_wake_lock_fd:-1, g_wake_unlock_fd:-1, wake_lock_acquired:0
I/bte_conf( 3191): Attempt to load did conf from /etc/bluetooth/bt_did.conf
I/bte_conf( 3191): [1] primary_record=1 vendor_id=0x0075 vendor_id_source=0x0001 product_id=0x0100 version=0x0200
,I/bte_conf( 3191): Attempt to load did conf from /etc/bluetooth/bt_did.conf
I/bte_conf( 3191): Attempt to load did conf from /etc/bluetooth/bt_did.conf
,D/BluetoothAdapterState( 3191): CURRENT_STATE=PENDING, MSG = ENABLE_READY, isTurningOn=true, isTurningOff=false
D/BluetoothAdapterProperties( 3191): ScanMode =  20
,D/BluetoothAdapterProperties( 3191): State =  11
,D/BtConfig.SecureMode( 3191): isSecureModeOn:false
D/BtConfig.SecureMode( 3191): isSecureModeOn:false
D/BtConfig.SecureMode( 3191): isSecureModeOn:false
D/BtConfig.SecureMode( 3191): isSecureModeOn:false
D/BtConfig.SecureMode( 3191): isSecureModeOn:false
D/BtConfig.SecureMode( 3191): isSecureModeOn:false
D/BtConfig.SecureMode( 3191): isSecureModeOn:false
D/BtConfig.SecureMode( 3191): isSecureModeOn:false
,D/BtConfig.SecureMode( 3191): isSecureModeOn:false
D/BtConfig.SecureMode( 3191): isSecureModeOn:false
D/BtConfig.SecureMode( 3191): isSecureModeOn:false
D/BtConfig.SecureMode( 3191): isSecureModeOn:false
,I/BluetoothAdapterState( 3191): Bluetooth adapter state changed: 11-> 12
,D/BluetoothAdapterService( 3191): Bluetooth PBAP supproted is true
,D/BluetoothAdapterService( 3191): updateAdapterState state is 12
,D/BluetoothAdapterService( 3191): Broadcasting updateAdapterState() to 1 receivers.
,D/BluetoothInputDevice( 3162): onBluetoothStateChange: up=true
,D/BluetoothAdapterService(1113169560)( 3191): Register RemoteMessageListener
D/BluetoothA2dp(  749): onBluetoothStateChange: up=true
,D/BluetoothA2dp( 3162): onBluetoothStateChange: up=true
,D/HeadsetService( 3191): registerMessageListener
D/HeadsetStateMachine( 3191): Disconnected process message: 70
D/HeadsetStateMachine( 3191): processRegisterMessageListener : 2, com.android.bluetooth.btservice.RemoteDevices$1@425e3e58
D/BluetoothAdapterService( 3191): Autoconnection is available 
,D/BluetoothA2dp( 2014): onBluetoothStateChange: up=true
D/BluetoothAdapterService( 3191): updateAdapterState prevState = 11newState = 12
,D/BluetoothAdapterService( 3191): starting service from this receiver
,D/BluetoothAdapterService( 3191): initWakeLock, pfd lock: {ParcelFileDescriptor: FileDescriptor[91]}, pfd unlock: {ParcelFileDescriptor: FileDescriptor[92]}
,D/bluedroid( 3191): init_wake_lock lock_fd:91, unlock_fd:92
,I/WifiTrafficPoller(  749): mBoosterFLAG : 2
,I/WifiTrafficPoller(  749): current booster mode : BTCoexMode
,D/PhoneApp( 1237): mReceiver: BluetoothAdapter.ACTION_STATE_CHANGED: 12
,I/QuickConnect[1.1][2] ( 3162): BluetoothHelper.ACTION_STATE_CHANGED - STATE_ON
W/InputMethodManagerService(  749): InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
I/InputMethodManagerService(  749): [BT Setting State] State =12
I/InputMethodManagerService(  749): [BT Setting off -> on] mBTKeyboardCount =0, KEYBOARD_BT(0)
,W/ContextImpl( 3191): Implicit intents with startService are not safe: Intent { act=com.samsung.ble.ACTION_SERVICE_BLE_AUTO_CONNECT } android.content.ContextWrapper.startService:506 com.android.bluetooth.btservice.AdapterService.updateAdapterState:653 com.android.bluetooth.btservice.AdapterState.notifyAdapterStateChange:586 
,D/BluetoothAdapterService(1113169560)( 3191): Get Bonded Devices being called
,D/BluetoothHeadset( 1237): registerListener : 11, listenercom.android.phone.PhoneGlobals$MessageListener@422c4f28, true
,D/BluetoothHeadset( 1237): registerMessageListener
,I/BluetoothAdapterState( 3191): Entering On State from state = 11
,I/chromium( 4661): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
D/HeadsetService( 3191): registerMessageListener
,I/BluetoothPbapService( 3191): action: android.bluetooth.adapter.action.STATE_CHANGED, state: 12
D/HeadsetService( 3191): registerMessageListener
D/HeadsetStateMachine( 3191): Disconnected process message: 70
,D/HeadsetStateMachine( 3191): processRegisterMessageListener : 11, com.samsung.bt.hfp.IMessageListener$Stub$Proxy@4267e9b8
,D/PhoneApp( 1237): registerMessageListener
,D/BluetoothPanServiceJni( 3191): control_state_callback(L61): state:0, local_role:0, ifname:bt-pan
,I/BluetoothPbapService( 3191): Handler(): got msg=1
,D/STATUSBAR-IconMerger( 1064): checkOverflow(336), More:false, Req:false Child:2
V/BluetoothPbapService( 3191): PBAP Service initSocket try: 0
,W/BluetoothAdapter( 3191): getBluetoothService() called with no BluetoothManagerCallback
,E/BluetoothServiceJni( 3191): SOCK FLAG = 1 ***********************
,D/BluetoothPbapService( 3191): PBAP Socket is BluetoothServerSocket
,D/BluetoothMapMasInstance( 3191): set MAP SDP message type : 1
,W/BluetoothAdapter( 3191): getBluetoothService() called with no BluetoothManagerCallback
,W/ContextImpl( 1303): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1857 android.content.ContextWrapper.startService:506 android.content.ContextWrapper.startService:506 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
E/BluetoothServiceJni( 3191): SOCK FLAG = 3 ***********************
,D/LocalBluetoothProfileManager( 1303): Adding local A2DP profile
,D/LocalBluetoothProfileManager( 1303): Adding local HEADSET profile
W/ContextImpl( 1303): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1930 android.content.ContextWrapper.bindService:529 android.bluetooth.BluetoothA2dp.doBind:221 android.bluetooth.BluetoothA2dp.<init>:214 android.bluetooth.BluetoothAdapter.getProfileProxy:1412 
,E/BluetoothHeadset( 1303): BTStateChangeCB is registed
,E/BluetoothHeadset( 1303): BluetoothHeadset service is binded
W/ContextImpl( 1303): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1930 android.content.ContextWrapper.bindService:529 android.bluetooth.BluetoothHeadset.doBind:304 android.bluetooth.BluetoothHeadset.<init>:297 android.bluetooth.BluetoothAdapter.getProfileProxy:1409 
,D/Bluetoothsap( 1303): bindService called to Bluetooth SAP Service
W/ContextImpl( 1303): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1930 android.content.ContextWrapper.bindService:529 com.broadcom.bt.service.sap.BluetoothSap.doBind:186 com.broadcom.bt.service.sap.BluetoothSap.<init>:179 com.android.settings.bluetooth.SapProfile.<init>:129 
,W/ContextImpl( 1303): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1930 android.content.ContextWrapper.bindService:529 android.bluetooth.BluetoothInputDevice.doBind:245 android.bluetooth.BluetoothInputDevice.<init>:238 android.bluetooth.BluetoothAdapter.getProfileProxy:1415 
,W/ContextImpl( 1303): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1930 android.content.ContextWrapper.bindService:529 android.bluetooth.BluetoothPan.doBind:173 android.bluetooth.BluetoothPan.<init>:162 android.bluetooth.BluetoothAdapter.getProfileProxy:1418 
D/LocalBluetoothProfileManager( 1303): PANU : true
D/LocalBluetoothProfileManager( 1303): Adding local MAP profile
,D/BluetoothMap( 1303): Create BluetoothMap proxy object
W/ContextImpl( 1303): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1930 android.content.ContextWrapper.bindService:529 android.bluetooth.BluetoothMap.doBind:109 android.bluetooth.BluetoothMap.<init>:102 android.bluetooth.BluetoothAdapter.getProfileProxy:1424 
,D/GKI_LINUX( 3191): release_my_wake_lock(), g_wake_lock_fd:91, g_wake_unlock_fd:92, wake_lock_acquired:0
D/Bluetoothsap( 1303): bindService called to Bluetooth SAP Service
D/LocalBluetoothProfileManager( 1303): LocalBluetoothProfileManager construction complete
W/ContextImpl( 1303): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1930 android.content.ContextWrapper.bindService:529 android.bluetooth.BluetoothPbap.doBind:164 android.bluetooth.BluetoothPbap.<init>:157 com.android.settings.bluetooth.PbapServerProfile.<init>:68 
,W/ContextImpl( 1303): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1930 android.content.ContextWrapper.bindService:529 com.broadcom.bt.service.sap.BluetoothSap.doBind:186 com.broadcom.bt.service.sap.BluetoothSap.<init>:179 com.android.settings.bluetooth.SapProfile.<init>:129 
D/DockEventReceiver( 1303): finishStartingService: stopping service
D/BluetoothNotiBroadcastReceiver( 1303): onReceive
D/BluetoothA2dp( 1303): Proxy object connected
D/BtConfig.SecureMode( 3191): isSecureModeOn:false
D/A2dpProfile( 1303): Bluetooth service connected
D/AuthorizationBluetoothService( 1319): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
E/AuthorizationBluetoothService( 1319): Proximity feature is not enabled.
,D/HeadsetProfile( 1303): Bluetooth service connected
,D/BluetoothInputDevice( 1303): Proxy object connected
,D/HidProfile( 1303): Bluetooth service connected
,D/BluetoothPan( 1303): BluetoothPAN Proxy object connected
,D/PanProfile( 1303): Bluetooth service connected
,D/BluetoothMap( 1303): Proxy object connected
,D/MapProfile( 1303): Bluetooth service connected
,D/BluetoothPbap( 1303): Proxy object connected
,D/PbapServerProfile( 1303): Bluetooth service connected
,W/BluetoothAdapter( 3191): getBluetoothService() called with no BluetoothManagerCallback
,E/BluetoothServiceJni( 3191): SOCK FLAG = 0 ***********************
,D/GKI_LINUX( 3191): acquire_my_wake_lock(), g_wake_lock_fd:91, g_wake_unlock_fd:92, wake_lock_acquired:0
,I/BtOppRfcommListener( 3191): Accept thread started.
,D/Tethering(  749): interfaceAdded wlan0
,E/Tethering(  749): No numeric data
,D/Tethering(  749): sendTetherStateChangedBroadcast 1, 0, 0
,D/NtpTrustedTime(  749): forceRefresh() from cache miss
,I/ConnectivityService(  749): defaultVal : 1, tetherEnabledInSettings : true
D/Tethering(  749): interfaceLinkStateChanged wlan0, false
D/Tethering(  749): interfaceStatusChanged wlan0, false
D/NtpTrustedTime(  749): forceRefresh Fail.
,D/Tethering(  749): InitialState.processMessage what=4
,E/Tethering(  749): No numeric data
,D/Tethering(  749): interfaceAdded p2p0
,D/Tethering(  749): p2p0 is not a tetherable iface, ignoring
,D/Tethering(  749): sendTetherStateChangedBroadcast 0, 0, 0
V/NetworkStats(  749): performPollLocked(flags=0x1)
,I/ConnectivityService(  749): defaultVal : 1, tetherEnabledInSettings : true
D/Tethering(  749): interfaceLinkStateChanged p2p0, false
D/Tethering(  749): interfaceStatusChanged p2p0, false
,I/WifiHW  (  237): wifi_change_fw_path(): fwpath = sta
,D/SoftapController(  237): Softap fwReload - Ok
,D/NtpTrustedTime(  749): forceRefresh() from cache miss
D/NtpTrustedTime(  749): forceRefresh Fail.
,D/NtpTrustedTime(  749): forceRefresh() from cache miss
,D/NtpTrustedTime(  749): forceRefresh Fail.
V/NetworkStats(  749): performPollLocked() took 19ms
V/NetworkStats(  749): performPollLocked(flags=0x1)
,D/GKI_LINUX( 3191): release_my_wake_lock(), g_wake_lock_fd:91, g_wake_unlock_fd:92, wake_lock_acquired:1
D/CommandListener(  237): Setting iface cfg
,D/CommandListener(  237): Trying to bring down wlan0
,D/NtpTrustedTime(  749): forceRefresh() from cache miss
,D/NtpTrustedTime(  749): forceRefresh Fail.
V/NetworkStats(  749): performPollLocked() took 15ms
,D/WifiHW  (  749): Skip the update_ctrl_interface
,D/WifiHW  (  749): Skip the update_ctrl_interface
,E/WifiHW  (  749): supplicant_name : p2p_supplicant
,I/wpa_supplicant( 4932): wpa_supplicant v2.1-devel-4.4.22014-11-04/18:06:52
,I/wpa_supplicant( 4932): [wpa_supplicant_init]: use SECRIL
I/wpa_supplicant( 4932): Successfully initialized wpa_supplicant
,I/wpa_supplicant( 4932): >>>>> Not GET KEY, IV <<<<<
,E/wpa_supplicant( 4932): getIMSI cannot open file
,E/wpa_supplicant( 4932): Interworking config: - SIM READ ERROR
,D/WifiMonitor(  749): startMonitoring(wlan0) with mConnected = false
D/STATUSBAR-NetworkController_dual( 1064): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
D/StatusBar.NetworkController_dual( 1064): mMobileLabelViews start
D/StatusBar.NetworkController_dual( 1064): mMobileLabelViews set mobileLabel[SIM_0] =No service.
D/StatusBar.NetworkController_dual( 1064): mMobileLabelViews GONE
D/StatusBar.NetworkController_dual( 1064): mMobileLabelViews2 set mobileLabel[SIM_1] =No service.
D/StatusBar.NetworkController_dual( 1064): mMobileLabelViews2 GONE
D/StatusBar.NetworkController_dual( 1064): mSingleMobileLabelViews set : simMode = 0
D/StatusBar.NetworkController_dual( 1064): mSingleMobileLabelViews set as slot1`s
,I/knox    ( 3100): MainReceiver.onReceive() : Intent { act=android.net.wifi.WIFI_STATE_CHANGED flg=0x4000010 cmp=com.sec.knox.seandroid/.receiver.MainReceiver (has extras) }
,W/ContextImpl( 3100): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1857 android.content.ContextWrapper.startService:506 android.content.ContextWrapper.startService:506 com.sec.knox.seandroid.receiver.MainReceiver.onReceive:142 android.app.ActivityThread.handleReceiver:2698 
I/knox    ( 3100): MainReceiver.onReceive() END - - - - - : Intent { act=android.net.wifi.WIFI_STATE_CHANGED flg=0x4000010 cmp=com.sec.knox.seandroid/.receiver.MainReceiver (has extras) }
D/knox    ( 3100): KNOXAgentService : onCreate()
D/knox    ( 3100): KNOXAgentService : set alarms for deniallog and usage data upload
D/knox    ( 3100): KNOXAgentService. startJobThread() start
D/knox    ( 3100): KNOXAgentService. JobThread()
D/knox    ( 3100): KNOXAgentService. JobThread. notifyAll().
D/knox    ( 3100): KNOXAgentService. startJobThread() wait
,I/wpa_supplicant( 4932): >>>>> Not GET KEY, IV <<<<<
E/wpa_supplicant( 4932): getIMSI cannot open file
,E/wpa_supplicant( 4932): Interworking config: - SIM READ ERROR
,I/wpa_supplicant( 4932): >>>>> Not GET KEY, IV <<<<<
,I/wpa_supplicant( 4932): rfkill: Cannot open RFKILL control device
,D/Tethering(  749): interfaceLinkStateChanged wlan0, false
,D/Tethering(  749): interfaceStatusChanged wlan0, false
,I/SELinux ( 4935): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 4935):  
,D/knox    ( 3100): KNOXAgentService : onDestroy().
,D/knox    ( 3100): ModuleBase.cancelAllAlarmManageModule()
,I/SELinux ( 4935): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 4935):  
I/SELinux ( 4935):  
,I/SELinux ( 4935): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 4935): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
,E/dalvikvm( 4935): >>>>> Normal User
,E/dalvikvm( 4935): >>>>> tv.peel.smartremote [ userId:0 | appId:10163 ]
,E/SELinux ( 4935): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
,I/wpa_supplicant( 4932): wlan0: Setting scan request: 0 sec 100000 usec
,D/TimaKeyStoreProvider( 4935): in addTimaSignatureService
,D/TimaKeyStoreProvider( 4935): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 4935): Added TimaKesytore provider
,W/ActivityManager(  749): Permission Denial: getCurrentUser() from pid=4935, uid=10163 requires android.permission.INTERACT_ACROSS_USERS
,I/wpa_supplicant( 4932): >>>>> Not GET KEY, IV <<<<<
,I/wpa_supplicant( 4932): >>>>> Not GET KEY, IV <<<<<
,I/wpa_supplicant( 4932): rfkill: Cannot open RFKILL control device
D/Tethering(  749): interfaceLinkStateChanged p2p0, false
,D/Tethering(  749): interfaceStatusChanged p2p0, false
D/Tethering(  749): interfaceLinkStateChanged p2p0, false
,D/Tethering(  749): interfaceStatusChanged p2p0, false
,I/wpa_supplicant( 4932): CTRL-EVENT-STATE-CHANGE id=-1 state=2 BSSID=00.00.00 SSID=
,I/wpa_supplicant( 4932): P2P: initialized channels: 81:1,2,3,4,5,6,7,8,9,10,11,12,13 115:36,40,44,48 116:36,44 117:40,48
I/wpa_supplicant( 4932): CTRL-EVENT-STATE-CHANGE id=-1 state=0 BSSID=00.00.00 SSID=
,I/wpa_supplicant( 4932): Skip scan - bUseNetwork false
,D/WifiStateMachine(  749): skipWifiStateBroadcast:false, LastBroadcastedWifiState:2
,D/WifiNative(  749): callSECApiString - ID [21]
D/STATUSBAR-NetworkController_dual( 1064): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
D/SignalClusterView_dual( 1064): wifi: GONE sig=0 act=0
D/SignalClusterView_dual( 1064): mMobileDataState=0 mMobileDataState2=0
D/SignalClusterView_dual( 1064): apply() mSeparateMobileGroup=8
D/STATUSBAR-NetworkController_dual( 1064): refreshSignalCluster - setNWBoosterIndicators(false)
D/SignalClusterView_dual( 1064): wifi: GONE sig=2130837981 act=0
D/SignalClusterView_dual( 1064): mMobileDataState=0 mMobileDataState2=0
D/SignalClusterView_dual( 1064): apply() mSeparateMobileGroup=8
D/SignalClusterView_dual( 1064): wifi: GONE sig=2130837981 act=0
D/SignalClusterView_dual( 1064): mMobileDataState=0 mMobileDataState2=0
D/SignalClusterView_dual( 1064): apply() mSeparateMobileGroup=8
D/SignalClusterView_dual( 1064): wifi: GONE sig=2130837981 act=0
D/SignalClusterView_dual( 1064): mMobileDataState=0 mMobileDataState2=0
D/SignalClusterView_dual( 1064): apply() mSeparateMobileGroup=8
D/SignalClusterView_dual( 1064): wifi: GONE sig=2130837981 act=0
D/SignalClusterView_dual( 1064): mMobileDataState=0 mMobileDataState2=0
D/SignalClusterView_dual( 1064): apply() mSeparateMobileGroup=8
D/StatusBar.NetworkController_dual( 1064): mMobileLabelViews start
D/StatusBar.NetworkController_dual( 1064): mMobileLabelViews set mobileLabel[SIM_0] =No service.
D/StatusBar.NetworkController_dual( 1064): mMobileLabelViews GONE
D/StatusBar.NetworkController_dual( 1064): mMobileLabelViews2 set mobileLabel[SIM_1] =No service.
D/StatusBar.NetworkController_dual( 1064): mMobileLabelViews2 GONE
D/StatusBar.NetworkController_dual( 1064): mSingleMobileLabelViews set : simMode = 0
D/StatusBar.NetworkController_dual( 1064): mSingleMobileLabelViews set as slot1`s
,I/wpa_supplicant( 4932): HOTSPOT20_ENABLE called
,I/wpa_supplicant( 4932): wlan0: HS20_DISABLED_COMPLETE normal
,I/knox    ( 3100): MainReceiver.onReceive() : Intent { act=android.net.wifi.WIFI_STATE_CHANGED flg=0x4000010 cmp=com.sec.knox.seandroid/.receiver.MainReceiver (has extras) }
,I/knox    ( 3100): MainReceiver.onReceive() END - - - - - : Intent { act=android.net.wifi.WIFI_STATE_CHANGED flg=0x4000010 cmp=com.sec.knox.seandroid/.receiver.MainReceiver (has extras) }
I/ActivityManager(  749): Killing 3719:com.sec.android.app.sns3/u0a36 (adj 15): empty #43
,W/ContextImpl( 3100): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1857 android.content.ContextWrapper.startService:506 android.content.ContextWrapper.startService:506 com.sec.knox.seandroid.receiver.MainReceiver.onReceive:142 android.app.ActivityThread.handleReceiver:2698 
D/knox    ( 3100): KNOXAgentService : onCreate()
D/knox    ( 3100): KNOXAgentService : set alarms for deniallog and usage data upload
D/knox    ( 3100): GSLBThreadManager.NetworkStateChanged : NETWORK_STATE_CHAGED. Upload Call Log Data
D/WifiNative(  749): callSECApiInt - ID [65]
D/knox    ( 3100): KNOXAgentService. startJobThread() start
D/knox    ( 3100): KNOXAgentService. JobThread()
D/knox    ( 3100): KNOXAgentService. JobThread. notifyAll().
D/knox    ( 3100): KNOXAgentService. startJobThread() wait
D/knox    ( 3100): KNOXAgentService : onDestroy().
D/knox    ( 3100): ModuleBase.cancelAllAlarmManageModule()
E/WifiConfigStore(  749): Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
,D/WifiNative(  749): callSECApiBoolean - ID [13]
,I/wpa_supplicant( 4932): USE_NETWORK : USE_NETWORK ON
I/wpa_supplicant( 4932): reset timer : RESET_TIMER 0
I/wpa_supplicant( 4932): wlan0: Setting scan request: 0 sec 0 usec
I/wpa_supplicant( 4932): CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00.00.00 SSID=
I/wpa_supplicant( 4932): First Scan Start
,I/wpa_supplicant( 4932): Scan requested (ret=0) - scan timeout 30 seconds
,W/Settings( 3055): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,E/WifiStateMachine(  749): Set the Nv default ccode
,D/WifiStateMachine(  749): skipWifiStateBroadcast:false, LastBroadcastedWifiState:3
,E/WifiStateMachine(  749): HS20_DISABLED_COMPLETEnormal
D/WifiP2pService(  749): P2pDisabledState{ what=131203 }
,I/wpa_supplicant( 4932): P2P: updated channels: 81:1,2,3,4,5,6,7,8,9,10,11,12,13 115:36,40,44,48 116:36,44 117:40,48
W/ContextImpl(  749): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.android.server.enterprise.wifi.WifiPolicy.asyncEnableNetwork:3065 com.android.server.enterprise.wifi.WifiPolicy.edmUpdateConfiguredNetworks:2530 com.android.server.enterprise.wifi.WifiPolicy$2$2.run:3022 java.lang.Thread.run:841 
,D/CommandListener(  237): Setting iface cfg
,D/CommandListener(  237): Trying to bring up p2p0
,D/WifiMonitor(  749): startMonitoring(p2p0) with mConnected = true
D/WifiP2pService(  749): P2pEnablingState
D/WifiP2pService(  749): P2pEnablingState{ what=147457 }
D/WifiP2pService(  749): P2p socket connection successful
,D/QuickConnect[1.1][2] ( 3162): SconnectManager.INetworkStateListener, onEnabled - mNetworkState : 4
,D/QuickConnect[1.1][2] ( 3162): P2pHelper.onReceive - ACTION_WIFI_DISPLAY_STATUS_CHANGED :0
D/WifiP2pService(  749): P2pEnabledState
D/WifiP2pService(  749): sending p2p connection changed broadcast: IDLE
D/WifiDisplayController(  749): Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=true
D/WifiDisplayController(  749): updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
D/WifiDisplayController(  749): disconnect
D/WifiDisplayController(  749): updateConnection
D/WifiDisplayController(  749): updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
D/WifiDisplayAdapter(  749): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
D/WifiDisplayAdapter(  749): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,D/QuickConnect[1.1][2] ( 3162): P2pHelper.onReceive - P2P_CONNECTION_CHANGED : 
D/WifiDisplayController(  749): Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=NetworkInfo: type: WIFI_P2P[], state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/QuickConnect[1.1][2] ( 3162): SconnectManager.INetworkStateListener, onDisconnected - networkType : 4
,D/NearbySettings( 1303): MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,V/NearbySettings( 1303): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 1303): DMSUtil.isNetworkConnected - WIFI: IDLE
I/NearbySettings( 1303): DMSUtil.isNetworkConnected - P2P: IDLE
,I/NearbySettings( 1303): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1303): MountReceiver.onReceive - Set preference state off
,V/NearbySettings( 1303): MountReceiver.mPrefHandler - 7002
D/WifiDisplayController(  749): Received WIFI_P2P_THIS_DEVICE_CHANGED_ACTION: mThisDevice= Device: Galaxy S5-2
D/WifiDisplayController(  749):  deviceAddress: 3a:94:96:b5:06:dd
D/WifiDisplayController(  749):  primary type: 10-0050F204-5
D/WifiDisplayController(  749):  secondary type: null
D/WifiDisplayController(  749):  wps: 0
D/WifiDisplayController(  749):  grpcapab: 0
D/WifiDisplayController(  749):  devcapab: 0
D/WifiDisplayController(  749):  status: 3
D/WifiDisplayController(  749):  wfdInfo: null
D/WifiDisplayController(  749):  groupownerAddress: null
D/WifiDisplayController(  749):  GOdeviceName: null
D/WifiDisplayController(  749):  interfaceAddress: 
D/WifiDisplayController(  749):  SConnectInfo : null
,D/WifiP2pService(  749): DeviceAddress: 3a:06:dd
,D/FileShare-Server( 4214): ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,D/QuickConnect[1.1][2] ( 3162): P2pHelper.requestGroupInfo  - onGroupInfoAvailable- null
,E/WifiStateMachine(  749): BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
D/WifiP2pService(  749): sending p2p persistent groups changed broadcast
D/WifiP2pService(  749): InactiveState
D/WifiP2pService(  749): InactiveState{ what=139287 }
D/WifiP2pService(  749): P2pEnabledState{ what=139287 }
D/WifiP2pService(  749): DefaultState{ what=139287 }
,D/FileShare-Server( 4214): ServerBroadcastReceiver.onReceive - netInfo.getDetailedState() IDLE
W/WifiP2pStateTracker(  749): WifiP2pStateReceiver : android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,D/Tethering(  749): interfaceLinkStateChanged p2p0, false
,D/Tethering(  749): interfaceStatusChanged p2p0, false
,I/wpa_supplicant( 4932): P2P: updated channels: 81:1,2,3,4,5,6,7,8,9,10,11,12,13 115:36,40,44,48 116:36,44 117:40,48
,I/wpa_supplicant( 4932): P2P: updated channels: 81:1,2,3,4,5,6,7,8,9,10,11,12,13 115:36,40,44,48 116:36,44 117:40,48
,I/wpa_supplicant( 4932): nl80211: Received scan results (8 BSSes)
,I/wpa_supplicant( 4932): wlan0: Setting scan request: 8 sec 0 usec
I/wpa_supplicant( 4932): Trying to associate with SSID '4E47373030'
I/wpa_supplicant( 4932): Trying to associate with  'G700'
,I/wpa_supplicant( 4932): CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00.00.00 SSID=
,E/wpa_supplicant( 4932): Cmd 35609 not handled
D/Tethering(  749): interfaceLinkStateChanged wlan0, false
,D/Tethering(  749): interfaceStatusChanged wlan0, false
,E/WifiStateMachine(  749): Error! unhandled message{ when=-10ms what=135188 target=com.android.internal.util.StateMachine$SmHandler }
,E/wpa_supplicant( 4932): Cmd 35605 not handled
I/wpa_supplicant( 4932): CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00.00.00 SSID=4E47373030
I/wpa_supplicant( 4932): Associated with C0.AA.48
,I/wpa_supplicant( 4932): CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=C0.AA.48 SSID=4E47373030
,E/wpa_supplicant( 4932): Cmd 35847 not handled
E/wpa_supplicant( 4932): Cmd 35848 not handled
,E/wpa_supplicant( 4932): Cmd 35605 not handled
D/Tethering(  749): interfaceLinkStateChanged wlan0, false
,D/Tethering(  749): interfaceStatusChanged wlan0, false
D/Tethering(  749): interfaceLinkStateChanged wlan0, false
,D/Tethering(  749): interfaceStatusChanged wlan0, false
,I/wpa_supplicant( 4932): CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=C0.AA.48 SSID=4E47373030
D/Tethering(  749): interfaceLinkStateChanged wlan0, false
I/wpa_supplicant( 4932): WPA: Key negotiation completed with C0.AA.48 [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 4932): CTRL-EVENT-CONNECTED - Connection to C0.AA.48 completed (auth) [id=0 id_str=]
,D/Tethering(  749): interfaceStatusChanged wlan0, false
,I/wpa_supplicant( 4932): CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=C0.AA.48 SSID=4E47373030
,D/Tethering(  749): interfaceLinkStateChanged wlan0, true
,D/Tethering(  749): interfaceStatusChanged wlan0, true
,E/Tethering(  749): No numeric data
,I/ConnectivityService(  749): defaultVal : 1, tetherEnabledInSettings : true
D/Tethering(  749): sendTetherStateChangedBroadcast 1, 0, 0
D/NtpTrustedTime(  749): forceRefresh() from cache miss
D/NtpTrustedTime(  749): forceRefresh Fail.
D/Tethering(  749): interfaceLinkStateChanged wlan0, true
,D/Tethering(  749): interfaceStatusChanged wlan0, true
,D/Tethering(  749): interfaceLinkStateChanged wlan0, true
D/Tethering(  749): interfaceStatusChanged wlan0, true
,D/WifiNative(  749): callSECApiVoid - ID [50]
V/NetworkStats(  749): performPollLocked(flags=0x1)
,D/Tethering(  749): interfaceLinkStateChanged wlan0, true
,D/Tethering(  749): interfaceStatusChanged wlan0, true
,D/STATUSBAR-NetworkController_dual( 1064): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
D/StatusBar.NetworkController_dual( 1064): mMobileLabelViews start
D/StatusBar.NetworkController_dual( 1064): mMobileLabelViews set mobileLabel[SIM_0] =No service.
D/StatusBar.NetworkController_dual( 1064): mMobileLabelViews GONE
D/StatusBar.NetworkController_dual( 1064): mMobileLabelViews2 set mobileLabel[SIM_1] =No service.
,D/StatusBar.NetworkController_dual( 1064): mMobileLabelViews2 GONE
,D/StatusBar.NetworkController_dual( 1064): mSingleMobileLabelViews set : simMode = 0
,D/StatusBar.NetworkController_dual( 1064): mSingleMobileLabelViews set as slot1`s
,D/Tethering(  749): interfaceLinkStateChanged wlan0, true
,D/Tethering(  749): interfaceStatusChanged wlan0, true
V/NetworkStats(  749): performPollLocked() took 50ms
,I/SELinux ( 4965): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 4965):  
,D/NtpTrustedTime(  749): forceRefresh() from cache miss
,D/NtpTrustedTime(  749): forceRefresh Fail.
,D/STATUSBAR-NetworkController_dual( 1064): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
,D/StatusBar.NetworkController_dual( 1064): mMobileLabelViews start
D/StatusBar.NetworkController_dual( 1064): mMobileLabelViews set mobileLabel[SIM_0] =No service.
,D/StatusBar.NetworkController_dual( 1064): mMobileLabelViews GONE
D/StatusBar.NetworkController_dual( 1064): mMobileLabelViews2 set mobileLabel[SIM_1] =No service.
D/StatusBar.NetworkController_dual( 1064): mMobileLabelViews2 GONE
,D/StatusBar.NetworkController_dual( 1064): mSingleMobileLabelViews set : simMode = 0
,D/dalvikvm(  247): GC_EXPLICIT freed 43K, 49% free 9511K/18408K, paused 2ms+3ms, total 32ms
D/StatusBar.NetworkController_dual( 1064): mSingleMobileLabelViews set as slot1`s
D/STATUSBAR-NetworkController_dual( 1064): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
D/StatusBar.NetworkController_dual( 1064): mMobileLabelViews start
D/StatusBar.NetworkController_dual( 1064): mMobileLabelViews set mobileLabel[SIM_0] =No service.
D/StatusBar.NetworkController_dual( 1064): mMobileLabelViews GONE
D/StatusBar.NetworkController_dual( 1064): mMobileLabelViews2 set mobileLabel[SIM_1] =No service.
D/StatusBar.NetworkController_dual( 1064): mMobileLabelViews2 GONE
D/StatusBar.NetworkController_dual( 1064): mSingleMobileLabelViews set : simMode = 0
D/StatusBar.NetworkController_dual( 1064): mSingleMobileLabelViews set as slot1`s
,D/WifiP2pService(  749): InactiveState{ what=143375 }
,D/dalvikvm(  247): GC_EXPLICIT freed <1K, 49% free 9511K/18408K, paused 2ms+3ms, total 19ms
D/WifiP2pService(  749): P2pEnabledState{ what=143375 }
,I/SELinux ( 4965): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 4965):  
I/SELinux ( 4965):  
,I/SELinux ( 4965): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 4965): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 4965): >>>>> Normal User
,E/dalvikvm( 4965): >>>>> com.vlingo.midas [ userId:0 | appId:10033 ]
,E/SELinux ( 4965): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
,D/dalvikvm(  247): GC_EXPLICIT freed <1K, 49% free 9511K/18408K, paused 1ms+3ms, total 18ms
,D/TimaKeyStoreProvider( 4965): in addTimaSignatureService
,D/TimaKeyStoreProvider( 4965): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 4965): Added TimaKesytore provider
,I/System.out( 4965): Inside WakeupProvider
,I/System.out( 4965): Inside onCreate() of WakeupTriggerProvide
,E/SMD     (  240): DCD ON
,I/VlingoApplication( 4965): VlingoApplication appVersion ='11.4.0.3.34005', ro.csc.sales_code=XEO
,D/VlingoApplication( 4965): Couldn't create com.nuance.nuancedebugutilpackage context for host settings utility
,D/VlingoApplication( 4965): Couldn't create com.vlingo.midas.lmttutilitypackage context for host settings utility
,I/dhcpcd  ( 4986): if(wlan0) info get Success. (MAC : C0.AA.48)
,I/dhcpcd  ( 4986): bssid match
,D/NearbySettings( 1303): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 1303): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 1303): DMSUtil.isNetworkConnected - WIFI: OBTAINING_IPADDR
I/NearbySettings( 1303): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1303): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
,I/NearbySettings( 1303): MountReceiver.onReceive - Set preference state off
,V/NearbySettings( 1303): MountReceiver.mPrefHandler - 7002
,D/DialogFlow( 4965): initQueue()
I/ActivityManager(  749): Killing 3767:com.sec.spp.push:RemoteDlcProcess/u0a38 (adj 15): empty #43
,D/WifiP2pService(  749): InactiveState{ what=143375 }
,D/WifiP2pService(  749): P2pEnabledState{ what=143375 }
,D/STATUSBAR-NetworkController_dual( 1064): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
,D/StatusBar.NetworkController_dual( 1064): mMobileLabelViews start
D/StatusBar.NetworkController_dual( 1064): mMobileLabelViews set mobileLabel[SIM_0] =No service.
,D/StatusBar.NetworkController_dual( 1064): mMobileLabelViews GONE
D/StatusBar.NetworkController_dual( 1064): mMobileLabelViews2 set mobileLabel[SIM_1] =No service.
D/StatusBar.NetworkController_dual( 1064): mMobileLabelViews2 GONE
,D/StatusBar.NetworkController_dual( 1064): mSingleMobileLabelViews set : simMode = 0
,D/WifiStateMachine(  749): VerifyingLinkState enter
D/StatusBar.NetworkController_dual( 1064): mSingleMobileLabelViews set as slot1`s
,D/STATUSBAR-NetworkController_dual( 1064): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
,D/StatusBar.NetworkController_dual( 1064): mMobileLabelViews start
,D/StatusBar.NetworkController_dual( 1064): mMobileLabelViews set mobileLabel[SIM_0] =No service.
D/StatusBar.NetworkController_dual( 1064): mMobileLabelViews GONE
D/StatusBar.NetworkController_dual( 1064): mMobileLabelViews2 set mobileLabel[SIM_1] =No service.
,D/StatusBar.NetworkController_dual( 1064): mMobileLabelViews2 GONE
,D/StatusBar.NetworkController_dual( 1064): mSingleMobileLabelViews set : simMode = 0
,D/StatusBar.NetworkController_dual( 1064): mSingleMobileLabelViews set as slot1`s
,D/NearbySettings( 1303): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,I/NearbySettings( 1303): MountReceiver.onReceive - Keep current state
,D/WifiStateMachine(  749): VerifyingLinkState GOOD_LINK_DETECTED: transition to captive portal check
,D/WifiStateMachine(  749): CaptivePortalCheckState enter
,I/WifiTrafficPoller(  749): evaluateTrafficStatsPolling
D/ConnectivityService(  749): Captive portal check NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService(  749): handleCaptivePortalTrackerCheck: call captivePortalCheckComplete ni=NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/STATUSBAR-NetworkController_dual( 1064): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
D/StatusBar.NetworkController_dual( 1064): mMobileLabelViews start
D/StatusBar.NetworkController_dual( 1064): mMobileLabelViews set mobileLabel[SIM_0] =No service.
D/StatusBar.NetworkController_dual( 1064): mMobileLabelViews GONE
D/StatusBar.NetworkController_dual( 1064): mMobileLabelViews2 set mobileLabel[SIM_1] =No service.
D/StatusBar.NetworkController_dual( 1064): mMobileLabelViews2 GONE
D/StatusBar.NetworkController_dual( 1064): mSingleMobileLabelViews set : simMode = 0
,D/StatusBar.NetworkController_dual( 1064): mSingleMobileLabelViews set as slot1`s
D/WifiStateMachine(  749): CaptivePortalCheckState CMD_CAPTIVE_CHECK_COMPLETE
,D/STATUSBAR-NetworkController_dual( 1064): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
,D/SignalClusterView_dual( 1064): wifi: GONE sig=2130837981 act=0
D/SignalClusterView_dual( 1064): mMobileDataState=0 mMobileDataState2=0
D/SignalClusterView_dual( 1064): apply() mSeparateMobileGroup=8
,I/WifiTrafficPoller(  749): evaluateTrafficStatsPolling
I/WifiTrafficPoller(  749): mBoosterFLAG : 2
,I/WifiTrafficPoller(  749): current booster mode : BTCoexMode
D/STATUSBAR-NetworkController_dual( 1064): refreshSignalCluster - setNWBoosterIndicators(false)
D/SignalClusterView_dual( 1064): wifi: VISIBLE sig=2130837979 act=2130837939
D/ConnectivityService(  749): ConnectivityChange for WIFI: CONNECTED/CONNECTED
D/SignalClusterView_dual( 1064): mMobileDataState=0 mMobileDataState2=0
D/SignalClusterView_dual( 1064): apply() mSeparateMobileGroup=8
E/ConnectivityService(  749): net.tcp.usercfg.wifi not found in system properties. Using defaults
E/ConnectivityService(  749): net.tcp.delack.wifi not found in system properties. Using defaults
D/SignalClusterView_dual( 1064): wifi: VISIBLE sig=2130837979 act=2130837939
D/SignalClusterView_dual( 1064): mMobileDataState=0 mMobileDataState2=0
D/SignalClusterView_dual( 1064): apply() mSeparateMobileGroup=8
D/SignalClusterView_dual( 1064): wifi: VISIBLE sig=2130837979 act=2130837939
D/SignalClusterView_dual( 1064): mMobileDataState=0 mMobileDataState2=0
D/SignalClusterView_dual( 1064): apply() mSeparateMobileGroup=8
D/SignalClusterView_dual( 1064): wifi: VISIBLE sig=2130837979 act=2130837939
D/SignalClusterView_dual( 1064): mMobileDataState=0 mMobileDataState2=0
D/SignalClusterView_dual( 1064): apply() mSeparateMobileGroup=8
D/StatusBar.NetworkController_dual( 1064): mMobileLabelViews start
D/StatusBar.NetworkController_dual( 1064): mMobileLabelViews set mobileLabel[SIM_0] =
D/StatusBar.NetworkController_dual( 1064): mMobileLabelViews GONE
D/StatusBar.NetworkController_dual( 1064): mMobileLabelViews2 set mobileLabel[SIM_1] =
D/StatusBar.NetworkController_dual( 1064): mMobileLabelViews2 GONE
D/StatusBar.NetworkController_dual( 1064): mSingleMobileLabelViews set : simMode = 0
D/StatusBar.NetworkController_dual( 1064): mSingleMobileLabelViews set as slot1`s
,D/NearbySettings( 1303): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 1303): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 1303): DMSUtil.isNetworkConnected - WIFI: CONNECTED
I/NearbySettings( 1303): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1303): DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
,I/NearbySettings( 1303): MountReceiver.onReceive - Keep current state
D/STATUSBAR-IconMerger( 1064): checkOverflow(288), More:false, Req:false Child:2
,D/ConnectivityService(  749): handleConnectivityChange: setting default proxy info 
,V/RouteController(  237): /system/bin/ip -4 route replace default via 192.168.1.1 dev wlan0 scope global table 2 2>&1
,V/RouteController(  237): /system/bin/ip -4 rule del table 2 2>&1
,V/RouteController(  237): RTNETLINK answers: No such file or directory
,V/RouteController(  237): /system/bin/ip -4 rule add from 192.168.1.143 lookup 2 prio 150 2>&1
D/Toast   ( 1303):  checkMirrorLinkEnabled returns : false
,D/Toast   ( 1303): showing allowed
,D/NearbySettings( 1303): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,I/NearbySettings( 1303): MountReceiver.onReceive - Keep current state
,V/RouteController(  237): /system/bin/ip route flush cached 2>&1
,V/RouteController(  237): /system/bin/ip route del 192.168.1.0/24 table 2 2>&1
,I/SurfaceFlinger(  246): id=19 createSurf (1x1),1 flag=4, Uoast
,D/KeyguardUpdateMonitor( 1064): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1064): handleKeyguardVisibilityChanged(1)
,V/RouteController(  237): RTNETLINK answers: No such process
,V/RouteController(  237): /system/bin/ip route add 192.168.1.0/24 dev wlan0 table 2 metric 0 2>&1
,D/KeyguardUpdateMonitor( 1064): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1064): handleKeyguardVisibilityChanged(1)
D/PowerManagerService(  749): [api] acquire WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=749
,V/RouteController(  237): /system/bin/ip route flush cached 2>&1
,D/NtpTrustedTime(  749): forceRefresh() from cache miss
V/NetworkStats(  749): updateIfacesLocked()
V/NetworkStats(  749): performPollLocked(flags=0x1)
,D/KeyguardUpdateMonitor( 1064): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1064): handleKeyguardVisibilityChanged(1)
V/NetworkStats(  749): performPollLocked() took 18ms
,D/KeyguardUpdateMonitor( 1064): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1064): handleKeyguardVisibilityChanged(1)
,D/NtpTrustedTime(  749): requestTime Success from server:2.android.pool.ntp.org mCachedNtpTime : 1450201714992 mCachedNtpElapsedRealtime : 129106 mCachedNtpCertainty : 55
,D/NtpTrustedTime(  749): currentTimeMillis() cache hit
,D/NtpTrustedTime(  749): currentTimeMillis() cache hit
D/NtpTrustedTime(  749): currentTimeMillis() cache hit
,D/NtpTrustedTime(  749): currentTimeMillis() cache hit
D/NtpTrustedTime(  749): currentTimeMillis() cache hit
,D/NtpTrustedTime(  749): currentTimeMillis() cache hit
V/NetworkStats(  749): advisePersistThreshold() given 9223372036854775, clamped to 2097152
,D/Tethering(  749): Tethering got CONNECTIVITY_ACTION
,D/Tethering(  749): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker(  749): NoActiveNetworkState{ when=0 what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
,D/NtpTrustedTime(  749): currentTimeMillis() cache hit
D/        (  749): Setting time of day to sec=1450201715
,D/        (  749): Trying to open a file
D/        (  749): File Open Success
,D/        (  749): File Close Success
,W/        (  749): Unable to set rtc to 1450201715: Invalid argument
,V/AlarmManager(  749): waitForAlarm result :65536
I/        (  749): DRM_TIME_PATH CHMOD 660 for resetState done 
,D/STATUSBAR-NetworkController_dual( 1064): onReceive() - CONNECTIVITY_ACTION, INET_CONDITION_ACTION
,D/StatusBar.NetworkController_dual( 1064): mMobileLabelViews start
D/StatusBar.NetworkController_dual( 1064): mMobileLabelViews set mobileLabel[SIM_0] =
D/StatusBar.NetworkController_dual( 1064): mMobileLabelViews GONE
,D/StatusBar.NetworkController_dual( 1064): mMobileLabelViews2 set mobileLabel[SIM_1] =
D/StatusBar.NetworkController_dual( 1064): mMobileLabelViews2 GONE
,D/StatusBar.NetworkController_dual( 1064): mSingleMobileLabelViews set : simMode = 0
,D/StatusBar.NetworkController_dual( 1064): mSingleMobileLabelViews set as slot1`s
,D/accuweather( 1441): [KK AccuPhone]>>> SWW:64 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/KeyguardUpdateMonitor( 1064): received broadcast android.intent.action.TIME_SET
,D/KeyguardUpdateMonitor( 1064): handleTimeUpdate
D/StatusBar-DoNotDistrub( 1064): Received intent with android.intent.action.TIME_SET action
D/StatusBar-DoNotDistrub( 1064): Not data shared android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
,I/AudioService(  749): getStreamVolume 5 index 110
D/StatusBar-DoNotDistrub( 1064): sendBroadcast android.intent.action.DORMANT_MODE_OFF
D/StatusBar-DoNotDistrub( 1064): The STREAM NOTIFICATION volume is 0
D/STATUSBAR-StatusBarManagerService(  749): manageDisableList what=0x0 pkg=com.android.systemui
,W/Settings(  749): Setting auto_time has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
V/AlarmManager(  749): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
V/AlarmManager(  749): waitForAlarm result :4
,W/SEC_DRM_PLUGIN_Playready(  248): PlayreadyPlugIn::onAcquireDrmInfo : case TYPE_UPDATE_SECURE_CLOCK after: 1450201715 after conversion: 1450201715
,W/SEC_DRM_PLUGIN_Playready(  248): PlayreadyPlugIn::onAcquireDrmInfo : case TYPE_UPDATE_SECURE_CLOCK before: 1450201715 after conversion: 1450201715
,I/SensorManagerA(  749): getReportingMode :: sensor.mType = 5
D/STATUSBAR-IconMerger( 1064): checkOverflow(288), More:false, Req:false Child:2
D/STATUSBAR-NotificationService(  749): received android.intent.action.DORMANT_MODE_OFF
D/LightsService(  749): [api] [SvcLED] turnOff:: id = 4 (uid: 1000 pid: 749) 
,D/LightsService(  749): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x40 -> 0x40 | SvcLED(id=4) set Off
D/Sensors (  749): LightSensor setDelay = 200000000
D/Sensors (  749): LightSensor setSensorDelay = 200000000
D/Sensors (  749): Light sensor flush: not enabled 0
D/Sensors (  749): LightSensor enable = 1
D/Sensors (  749): LightSensor enableSensor = 1
D/SensorManager(  749): registerListener :: 16, CM36686 Light Sensor, 200000, 0,  
D/LocSvc_java(  749): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/LocSvc_java(  749): getAGpsConnectionInfo connType - 4
D/LocSvc_java(  749): ignore wifi update if we are not in OPENING or CLOSING
D/accuweather( 1441): [KK AccuPhone]>>> SWW:64 [0:0] action : androidintentactionTIME_SET
D/accuweather( 1441): [KK AccuPhone]>>> SWW:452 [0:0] doChangeDayOrNight : 1
D/accuweather( 1441): [KK AccuPhone]>>> SWW:338 [0:0] getWeatherRenderer : 1
,I/PCWCLIENTTRACE_PushUtil( 4510): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 4510): sales region : global
I/PCWCLIENTTRACE_PushUtil( 4510): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver( 4510): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,I/NetworkMonitor( 3799): type=WIFI subType= reason=null isConnected=true
,I/SELinux ( 5072): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5072):  
,I/SELinux ( 5072): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5072):  
I/SELinux ( 5072):  
,I/SELinux ( 5072): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5072): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 5072): >>>>> Normal User
,E/dalvikvm( 5072): >>>>> com.sec.android.cloudagent [ userId:0 | appId:10002 ]
,E/SELinux ( 5072): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,I/SELinux ( 5079): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5079):  
,D/TimaKeyStoreProvider( 5072): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5072): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5072): Added TimaKesytore provider
,I/SELinux ( 5079): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5079):  
I/SELinux ( 5079):  
,I/SELinux ( 5079): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5079): [DEBUG] seapp_context_lookup: seinfoCategory = chrome
E/dalvikvm( 5079): >>>>> Normal User
,E/dalvikvm( 5079): >>>>> com.android.chrome [ userId:0 | appId:10081 ]
,E/SELinux ( 5079): [DEBUG] seapp_context_lookup: seinfoCategory = chrome
,D/TimaKeyStoreProvider( 5079): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5079): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5079): Added TimaKesytore provider
,D/Sensors (  749): LightSensor enable = 0
,D/Sensors (  749): LightSensor enableSensor = 0
,D/SensorManager(  749): unregisterListener ::   
D/LightsService(  749): [SvcLED]  onSensorChanged::light value = 0
D/LightsService(  749): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,E/ActivityThread( 1784): Failed to find provider info for com.android.contacts.metadata
,D/SyncManager(  749): failed sync operation 
,D/SyncManager(  749): not retrying sync operation because the error is a hard error: 
,W/ActivityManager(  749): Permission Denial: getCurrentUser() from pid=5072, uid=10002 requires android.permission.INTERACT_ACROSS_USERS
,I/dalvikvm( 1784): Could not find method android.os.PowerManager.isInteractive, referenced from method com.google.android.gms.common.util.y.a
W/dalvikvm( 1784): VFY: unable to resolve virtual method 1378: Landroid/os/PowerManager;.isInteractive ()Z
,D/dalvikvm( 1784): VFY: replacing opcode 0x6e at 0x003d
,W/ActivityManager(  749): Permission Denial: getCurrentUser() from pid=5079, uid=10081 requires android.permission.INTERACT_ACROSS_USERS
,D/DelayedSyncController( 5079): Delaying sync.
,I/SELinux ( 5112): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5112):  
,D/PicasaService( 3890): start picasa sync
,D/PicasaService( 3890): end picasa sync
,I/SELinux ( 5112): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5112):  
I/SELinux ( 5112):  
I/SELinux ( 5112): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 5112): [DEBUG] seapp_context_lookup: seinfoCategory = release
E/dalvikvm( 5112): >>>>> Normal User
E/dalvikvm( 5112): >>>>> com.sec.android.fotaclient [ userId:0 | appId:10010 ]
,E/SELinux ( 5112): [DEBUG] seapp_context_lookup: seinfoCategory = release
,D/TimaKeyStoreProvider( 5112): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5112): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5112): Added TimaKesytore provider
,D/DelayedSyncController( 5079): Delaying sync.
,W/ActivityManager(  749): Permission Denial: getCurrentUser() from pid=5112, uid=10010 requires android.permission.INTERACT_ACROSS_USERS
,I/ActivityManager(  749): Killing 3785:com.sec.spp.push:RemoteNotiProcess/u0a38 (adj 15): empty #43
,I/ActivityManager(  749): Killing 3994:com.sec.android.app.videoplayer/u0a52 (adj 15): empty #43
,D/dalvikvm(  749): GC_EXPLICIT freed 2698K, 60% free 23471K/57632K, paused 7ms+14ms, total 147ms
,I/SELinux ( 5128): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5128):  
,I/jxcore-log( 4661): BLE advertisement not supported: Bluetooth LE advertising is not supported
I/jxcore-log( 4661): 
,I/SELinux ( 5128): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5128):  
I/SELinux ( 5128):  
,I/SELinux ( 5128): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5128): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 5128): >>>>> Normal User
,E/dalvikvm( 5128): >>>>> com.samsung.klmsagent [ userId:0 | appId:10018 ]
,E/SELinux ( 5128): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 5128): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5128): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5128): Added TimaKesytore provider
,W/ActivityManager(  749): Permission Denial: getCurrentUser() from pid=5128, uid=10018 requires android.permission.INTERACT_ACROSS_USERS
,D/KLMS-2.3.201 : ( 5128): KLMSValidator() : checkQATesting()
,I/KLMS-2.3.201 : ( 5128): MainReciver() : EventNotificationReciver- method called: AppActivityListner onReceive for Intent Action : android.net.conn.CONNECTIVITY_CHANGE , timestamp: 1450201716311
,I/KLMS-2.3.201 : ( 5128): KLMSUtility() : isNetworkAvailable() - WIFI : true| MOBILE : false
,I/ActivityManager(  749): Killing 4023:com.sec.android.app.voicenote/1000 (adj 15): empty #43
W/DriveInitializer( 1784): Awaiting to be initialized
W/DriveInitializer( 1784): Background init thread started
,I/SELinux ( 5143): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5143):  
,I/LocationTagReadyService( 2357): onStartCommand : Action = com.samsung.android.app.galaxyfinder.tag.start_location_convert
,D/GalaxyFinderApplication( 2357): [Slink platform] The state of Slink geocode service is true
D/GalaxyFinderApplication( 2357): [Slink platform] The state of Slink geocode service is true
,D/GalaxyFinderApplication( 2357): [Slink platform] The state of Slink geocode service is true
,I/GallerySearchProvider( 3890): query content://com.sec.android.gallery3d.provider.GallerySearchProvider/search_suggest_tag_query
,I/SELinux ( 5147): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5147):  
,I/SELinux ( 5143): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5143):  
I/SELinux ( 5143):  
,I/SELinux ( 5143): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5143): [DEBUG] seapp_context_lookup: seinfoCategory = release
E/dalvikvm( 5143): >>>>> Normal User
,E/dalvikvm( 5143): >>>>> com.sec.android.soagent [ userId:0 | appId:10037 ]
,E/SELinux ( 5143): [DEBUG] seapp_context_lookup: seinfoCategory = release
,E/cutils  (  227): Failed to mkdirat(/storage/extSdCard/Android): Read-only file system
,W/ContextImpl( 1784): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.gms/files
W/Vold    (  227): Returning OperationFailed - no handler for errno 30
,D/TimaKeyStoreProvider( 5143): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5143): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5143): Added TimaKesytore provider
,I/SELinux ( 5147): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5147):  
I/SELinux ( 5147):  
,I/SELinux ( 5147): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5147): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 5147): >>>>> Normal User
,E/dalvikvm( 5147): >>>>> com.sec.android.app.videoplayer [ userId:0 | appId:10052 ]
,E/SELinux ( 5147): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 5147): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5147): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5147): Added TimaKesytore provider
,I/SELinux ( 5169): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5169):  
,I/SELinux ( 5169): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5169):  
I/SELinux ( 5169):  
,I/SELinux ( 5169): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5169): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 5169): >>>>> Normal User
,E/dalvikvm( 5169): >>>>> com.sec.android.app.voicenote [ userId:0 | appId:1000 ]
,W/ActivityManager(  749): Permission Denial: getCurrentUser() from pid=5143, uid=10037 requires android.permission.INTERACT_ACROSS_USERS
E/SELinux ( 5169): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,W/DriveInitializer( 1784): Background init thread ended
,D/TimaKeyStoreProvider( 5169): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5169): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5169): Added TimaKesytore provider
,D/SO_AGENT( 5143): [AccRegisterReceiver.java(Line:56/Method:onReceive)] Receive broadcast meassage:android.net.conn.CONNECTIVITY_CHANGE
,I/SO_AGENT( 5143): [AccRegisterReceiver.java(Line:87/Method:onReceive)] Need to accessory setup...
,D/dalvikvm( 1204): GC_EXPLICIT freed 438K, 46% free 10048K/18408K, paused 3ms+6ms, total 55ms
,V/KVNProvider( 5169): query uri : content://com.sec.android.app.voicenote.common.util.VNProvider/search_suggest_tag_query
,V/KVNProvider( 5169): getFindoCursor query string : 
I/ActivityManager(  749): Killing 4055:com.android.providers.calendar/u0a44 (adj 15): empty #43
,V/KVNProvider( 5169): getTagSearchCursor() tagSearchCursor count : 0
,I/ActivityManager(  749): Killing 4019:com.android.calendar/u0a142 (adj 15): empty #43
,I/SA      ( 4697): [OR] onReceive log=[SA = 2.0.0117 V = 19 HWD = 1280X720 2.0 dpi = 320  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = kmini3g P = kmini3gxx I = KOT49H M = SM-G800H OKLEFT false DIS KOT49H.G800HXXU1ANK2 PSS = 4.497045606779314  ]
,I/SA      ( 4697): [BDLM] already registered in spp
I/SA      ( 4697): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. ]
,I/SA      ( 4697): [OR] == ACTION_CONNECTIVITY_CHANGE ==
,D/STATUSBAR-NetworkController_dual( 1064): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
D/StatusBar.NetworkController_dual( 1064): mMobileLabelViews start
D/StatusBar.NetworkController_dual( 1064): mMobileLabelViews set mobileLabel[SIM_0] =
D/StatusBar.NetworkController_dual( 1064): mMobileLabelViews GONE
D/StatusBar.NetworkController_dual( 1064): mMobileLabelViews2 set mobileLabel[SIM_1] =
D/StatusBar.NetworkController_dual( 1064): mMobileLabelViews2 GONE
,D/StatusBar.NetworkController_dual( 1064): mSingleMobileLabelViews set : simMode = 0
,D/StatusBar.NetworkController_dual( 1064): mSingleMobileLabelViews set as slot1`s
,I/SA      ( 4697): [SLFUCHKMGR] constructor called
I/SA      ( 4697): [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
,I/SA      ( 4697): [OR] == isSIMCardReady false ==
I/SA      ( 4697): [SCU] == networkStateCheck == true
,I/SA      ( 4697): [DM] getCountryCodeFromCSC : PL
I/SA      ( 4697): isChinaCountryCode : false
,I/SA      ( 4697): [OR] == networkStateCheck true ==
,I/dalvikvm( 4635): Total arena pages for JIT: 11
,I/dalvikvm( 4635): Total arena pages for JIT: 12
I/dalvikvm( 4635): Total arena pages for JIT: 13
,I/dalvikvm( 4635): Total arena pages for JIT: 14
,I/SA      ( 4697): [OR] GetMyCountryZoneTask
,I/SA      ( 4697): [OR] onReceive END
,I/SA      ( 4697): [SRS] prepareGetMyCountryZone
I/ActivityManager(  749): Killing 4059:com.sec.android.widgetapp.SPlannerAppWidget/u0a143 (adj 15): empty #43
,I/SA      ( 4697): [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
,D/PhoneNumberLocatorBootCompletedReceiver( 1237): onReceive
,D/PhoneNumberLocatorBootCompletedReceiver( 1237): Phone number locator feature is dsiabled
,I/SA      ( 4697): [SSP] query invoked
,I/SELinux ( 5202): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5202):  
,I/SA      ( 4697): [TPMU] GetMccFromDB : null
,I/SA      ( 4697): [SCU] getMccFromPreferece mcc = 260
,I/SA      ( 4697): [TPM] isNoProxy(default) : true
,I/SA      ( 4697): [RC New] Execute method=[GET] start
,I/SELinux ( 5202): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5202):  
I/SELinux ( 5202):  
,I/SELinux ( 5202): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5202): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 5202): >>>>> Normal User
,E/dalvikvm( 5202): >>>>> com.samsung.android.scloud.backup [ userId:0 | appId:10060 ]
,E/SELinux ( 5202): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 5202): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5202): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5202): Added TimaKesytore provider
,E/SMD     (  240): DCD ON
,I/System.out( 4697): Thread-449(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
,I/sCloudBackupApp( 5202): sCloudBackupApp Version Info : 3.7.3.KK_APP
,I/SCloudBackupReceiver( 5202): Other Intent
,I/System.out( 4697): Thread-449(ApacheHTTPLog):isShipBuild true
,I/System.out( 4697): Thread-449(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,I/ActivityManager(  749): Killing 3978:com.sec.phone/1001 (adj 15): empty #43
D/com.samsung.app( 1441): [KK_EASY_Accu]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
D/com.samsung.app( 1441): [KK_EASY_Accu]>>> WC:37 [0:0] oR : create UI manager : start
,D/com.samsung.app( 1441): [KK_EASY_Accu]>>> UIMEM:89 [0:0] getInstance
,D/com.samsung.app( 1441): [KK_EASY_Accu]>>> UIMEM:77 [0:0] UIManager : create ui manager
,D/accuweather( 1441): [KK AccuPhone]>>> RM:73 [0:0] RefreshManager : create
,D/accuweather( 1441): [KK AccuPhone]>>> RM:136 [0:0]  V init 
,D/daemonapp( 1461): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/accuweather( 1441): [KK AccuPhone]>>> RM:128 [0:0] updateCityList
,D/daemonapp( 1461): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,D/accuweather( 1441): [KK AccuPhone]>>> DBH:3047 [0:0] gADWI : count = 0
,D/daemonapp( 1461): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/com.samsung.app( 1441): [KK_EASY_Accu]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
,D/com.samsung.app( 1441): [KK_EASY_Accu]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
,I/SELinux ( 5216): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5216):  
,I/SELinux ( 5216): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5216):  
I/SELinux ( 5216):  
,I/SELinux ( 5216): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5216): [DEBUG] seapp_context_lookup: seinfoCategory = release
E/dalvikvm( 5216): >>>>> Normal User
E/dalvikvm( 5216): >>>>> com.samsung.android.internal.headlines [ userId:0 | appId:10106 ]
,I/HarmonyEASService(  749): Updating for all 1
,E/SELinux ( 5216): [DEBUG] seapp_context_lookup: seinfoCategory = release
,D/TimaKeyStoreProvider( 5216): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5216): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5216): Added TimaKesytore provider
,D/AmoledAdjustTimer(  749): prevTemp = 287, currTemp = 288, prevStep = 4, currStep = 4
,D/HeadlinesChannelApplication( 5216): [onCreate]
,D/Headlines( 5216): HeadlinesSystemBroadcastReceiver onReceive android.net.conn.CONNECTIVITY_CHANGE
W/ActivityManager(  749): Permission Denial: getCurrentUser() from pid=5216, uid=10106 requires android.permission.INTERACT_ACROSS_USERS
,D/HeadlinesChannelUtil( 5216): getCountryCode(): countryCode = PL
,D/Headlines( 5216): Breath.onCreate
,D/HeadlinesCardManager( 5216): HeadlinesCardManager : constructor
,E/HeadlinesCardManager( 5216): HeadlinesCardManager : ctor = image_cache size is 42MB
,D/SA Version( 5216): CardProvider Library : 13
,I/SELinux ( 5228): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5228):  
,D/MagazineService::CardProviderContentProvider( 4778): insertProvider: provider already exists.: com.samsung.android.app.headlines
,D/MagazineService::CardProviderContentProvider( 4778): insertProvider: provider is updated.: com.samsung.android.app.headlines
,D/com.samsung.android.magazine.cardprovider.ConfigurationManager( 5216): registerCardProvider: provider already exists.
,I/Headlines( 5216): HeadlinesDataCenter ctor
I/Headlines( 5216): HeadlinesDataCenter. mLocale = en_US
,D/HeadlinesChannelUtil( 5216): getCountryCode(): countryCode = PL
,D/HeadlinesCardManager( 5216): HeadlinesCardManager : constructor welcome :YES
,D/Headlines( 5216): Breath timer started. interval : 30000
,D/Headlines( 5216): Breath.onStartCommand : com.samsung.android.internal.headlines.UPDATE_WELCOME_CARD flag : 0
D/HeadlinesCardManager( 5216): updateCategory : HeadlinesCardManager:updateCategory() category size == 0
D/HeadlinesCardManager( 5216): updateCategory : HeadlinesCardManager:updateCategory() try to query category list
D/Headlines( 5216): queryCategory.  mRequest is not initialized.
,I/SELinux ( 5228): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5228):  
I/SELinux ( 5228):  
I/SELinux ( 5228): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
D/HeadlinesCardManager( 5216): updateCategory : HeadlinesCardManager:updateCategory() reponse : false
D/HeadlinesCardManager( 5216): requestUpdateNewsWelcomeCard : request update welcome card to content card.
,D/HeadlinesDataCenter( 5216): requestUpdateNewsWelcomeCard !!! no welcome card
E/SELinux ( 5228): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 5228): >>>>> Normal User
,E/dalvikvm( 5228): >>>>> com.google.android.apps.magazines [ userId:0 | appId:10112 ]
,E/SELinux ( 5228): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
,D/TimaKeyStoreProvider( 5228): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5228): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5228): Added TimaKesytore provider
,E/cutils  (  227): Failed to mkdirat(/storage/extSdCard/Android): Read-only file system
,W/ContextImpl( 5228): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,W/Vold    (  227): Returning OperationFailed - no handler for errno 30
W/GAV2    ( 5228): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,E/cutils  (  227): Failed to mkdirat(/storage/extSdCard/Android): Read-only file system
,W/ContextImpl( 5228): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
W/Vold    (  227): Returning OperationFailed - no handler for errno 30
,E/cutils  (  227): Failed to mkdirat(/storage/extSdCard/Android): Read-only file system
,W/ContextImpl( 5228): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,E/cutils  (  227): Failed to mkdirat(/storage/extSdCard/Android): Read-only file system
,W/ContextImpl( 5228): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
W/Vold    (  227): Returning OperationFailed - no handler for errno 30
W/Vold    (  227): Returning OperationFailed - no handler for errno 30
,D/btif_config_util( 3191): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,V/WebViewChromium( 5228): Binding Chromium to the main looper Looper (main, tid 1) {422660d0}
,I/chromium( 5228): [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserProcessMain( 5228): Initializing chromium process, renderers=0
,W/chromium( 5228): [WARNING:proxy_service.cc(888)] PAC support disabled because there is no system implementation
,I/Adreno-EGL( 5228): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 5228): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 5228): Build Date: 03/21/14 Fri
I/Adreno-EGL( 5228): Local Branch: AU200+patches_03212014
I/Adreno-EGL( 5228): Remote Branch: 
I/Adreno-EGL( 5228): Local Patches: 
I/Adreno-EGL( 5228): Reconstruct Branch: 
,I/SA      ( 4697): [RC New] [v2liruge] api execute + 836
,I/SA      ( 4697): [RC New] executeRequest [v2liruge] httpResponse : HTTP/1.1 200 OK
,I/System.out( 4697): AsyncTask #1 calls detatch()
,I/SA      ( 4697): [TPMU] getNetworkMcc : 
,I/NSApplication( 5228): Starting up...
,W/ActivityManager(  749): Permission Denial: getCurrentUser() from pid=5228, uid=10112 requires android.permission.INTERACT_ACROSS_USERS
,I/SA      ( 4697): [SCU] saveMccToPreferece Start
,I/SA      ( 4697): [SCU] RegionMCC : 260
,I/SA      ( 4697): [SSP] query invoked
,I/SA      ( 4697): [TPMU] GetMccFromDB : null
,I/SA      ( 4697): [SCU] getMccFromPreferece mcc = 260
,I/SA      ( 4697): [SCU] saveMccToPreferece End
,I/SA      ( 4697): [RC New] executeRequest [v2liruge] end. 928
,I/SA      ( 4697): [RC New] Execute end
,I/SA      ( 4697): [OR] GetMyCountryZoneTask mcc = 260
,I/SA      ( 4697): [OR] GetMyCountryZoneTask Success
I/ActivityManager(  749): Killing 3928:com.sec.android.app.music:service/u0a150 (adj 15): empty #43
,D/QuickConnect[1.1][2] ( 3162): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,I/QuickConnect[1.1][2] ( 3162): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
,V/QuickConnect[1.1][2] ( 3162): SconnectManager.getInstance - () return existing instance com.samsung.android.sconnect.SconnectManager@4259b030
,I/SELinux ( 5280): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5280):  
,D/dalvikvm(  247): GC_EXPLICIT freed 43K, 49% free 9511K/18408K, paused 5ms+3ms, total 28ms
,D/dalvikvm(  247): GC_EXPLICIT freed <1K, 49% free 9511K/18408K, paused 1ms+2ms, total 18ms
I/SELinux ( 5280): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5280):  
I/SELinux ( 5280):  
,I/SELinux ( 5280): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5280): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 5280): >>>>> Normal User
,E/dalvikvm( 5280): >>>>> com.android.email [ userId:0 | appId:10155 ]
,E/SELinux ( 5280): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 5280): in addTimaSignatureService
,D/dalvikvm(  247): GC_EXPLICIT freed <1K, 49% free 9511K/18408K, paused 2ms+3ms, total 20ms
,D/TimaKeyStoreProvider( 5280): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5280): Added TimaKesytore provider
,D/RCPManagerService(  749): exchangeData() failure , invalid userId
,D/RCPManagerService(  749): exchangeData() failure , invalid userId
,D/RCPManagerService(  749): exchangeData() failure , invalid userId
,D/RCPManagerService(  749): exchangeData() failure , invalid userId
,E/WifiStateMachine(  749): CAPTIVE_PORTAL_EVENT_AUTHENTICATED
,D/RCPManagerService(  749): exchangeData() failure , invalid userId
,D/RCPManagerService(  749): exchangeData() failure , invalid userId
,I/SELinux ( 5303): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5303):  
I/ActivityManager(  749): Killing 3055:com.google.android.talk/u0a105 (adj 15): empty #43
W/ActivityManager(  749): Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
,I/SELinux ( 5307): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5307):  
,I/SELinux ( 5303): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5303):  
I/SELinux ( 5303):  
,I/SELinux ( 5303): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5303): [DEBUG] seapp_context_lookup: seinfoCategory = shared
E/dalvikvm( 5303): >>>>> Normal User
,E/dalvikvm( 5303): >>>>> com.samsung.android.service.travel [ userId:0 | appId:10169 ]
,E/SELinux ( 5303): [DEBUG] seapp_context_lookup: seinfoCategory = shared
,D/TimaKeyStoreProvider( 5303): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5303): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5303): Added TimaKesytore provider
I/SELinux ( 5307): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5307):  
I/SELinux ( 5307):  
,I/SELinux ( 5307): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 5307): [DEBUG] seapp_context_lookup: seinfoCategory = release
E/dalvikvm( 5307): >>>>> Normal User
,E/dalvikvm( 5307): >>>>> com.sec.android.provider.badge [ userId:0 | appId:10072 ]
,E/SELinux ( 5307): [DEBUG] seapp_context_lookup: seinfoCategory = release
,D/TimaKeyStoreProvider( 5307): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5307): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5307): Added TimaKesytore provider
,I/ActivityManager(  749): Killing 4079:com.sec.providers.settingsearch/u0a160 (adj 15): empty #43
,W/ActivityManager(  749): Permission Denial: getCurrentUser() from pid=5303, uid=10169 requires android.permission.INTERACT_ACROSS_USERS
,D/WaitQueueForNetworkActivate( 4829): notifyNetworkActivated
,D/BadgeProvider( 5307): onCreate
,D/BadgeProvider( 5307): DatabaseHelper
W/ActivityManager(  749): Permission Denial: getCurrentUser() from pid=5307, uid=10072 requires android.permission.INTERACT_ACROSS_USERS
,D/BadgeProvider( 5307): query, [selection] : package='com.android.email' AND class='com.android.email.activity.Welcome' AND extraData='base_extra_badge'
,W/ContextImpl( 4829): Implicit intents with startService are not safe: Intent { act=com.sec.knox.containeragent.service.containermanager.ContainerManagerService } android.content.ContextWrapper.bindService:529 com.sec.knox.containeragent.ContainerManager.<init>:49 com.sec.android.app.samsungapps.vlibrary2.knoxmode.KNOXAPI.<init>:20 
D/BadgeProvider( 5307): sendNotify entered. [uri] : content://com.sec.badge/apps/1
D/BadgeProvider( 5307): sendNotify, [notify] : null
D/BadgeProvider( 5307): update, [uri] : content://com.sec.badge/apps/1
D/BadgeProvider( 5307): update, [BadgeCount] : badgecount=0
D/BadgeProvider( 5307): update, [UpdateCount] : 1
,D/Launcher.Model( 1241): reloadBadges entered.
W/ActivityManager(  749): Unable to start service Intent { act=com.sec.knox.containeragent.service.containermanager.ContainerManagerService } U=0: not found
,I/SurfaceFlinger(  246): id=19 Removed Uoast (11/12)
,I/SurfaceFlinger(  246): id=19 Removed Uoast (-2/12)
,D/KeyguardUpdateMonitor( 1064): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1064): handleKeyguardVisibilityChanged(1)
I/ActivityManager(  749): Killing 2892:com.sec.knox.bridge/1000 (adj 15): empty #43
D/PowerManagerService(  749): [api] release WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=749 (0x0)
D/PowerManagerService(  749): [api] applyWakeLockFlagsOnReleaseLocked : userActivityNoUpdateLocked is called : SCREEN_BRIGHT_WAKE_LOCK        'WindowManager' ON_AFTER_RELEASE (uid=1000, pid=749, ws=WorkSource{1000}) (elapsedTime=3469)
,D/hcjo    ( 4829): AutoUpdateManager:IDLE:execute
,I/dalvikvm( 4829): Could not find method android.view.Window.setStatusBarColor, referenced from method com.sec.android.app.samsungapps.CommonActivity.onCreate
W/dalvikvm( 4829): VFY: unable to resolve virtual method 14867: Landroid/view/Window;.setStatusBarColor (I)V
,D/dalvikvm( 4829): VFY: replacing opcode 0x6e at 0x0024
,D/InitializeManagerStateMachine( 4829): execute::IDLE:EXECUTE
D/InitializeManagerStateMachine( 4829): exit::IDLE
,D/InitializeManagerStateMachine( 4829): entry::NETWORK_CHECK
,D/InitializeManagerStateMachine( 4829): execute::NETWORK_CHECK:NETWORK_STATE_OK
D/InitializeManagerStateMachine( 4829): exit::NETWORK_CHECK
D/InitializeManagerStateMachine( 4829): entry::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 4829): execute::CHECK_COUNTRY_INFO:COUNTRY_INFO_OK
D/InitializeManagerStateMachine( 4829): exit::CHECK_COUNTRY_INFO
,D/InitializeManagerStateMachine( 4829): entry::SUCCESS
,D/hcjo    ( 4829): AutoUpdateManager:INITCHECK:onInitializeSuccess
,D/hcjo    ( 4829): AutoUpdateTriggerManager:IDLE:setInterval:345600000
,D/hcjo    ( 4829): AutoUpdateTriggerManager:IDLE:notifyNextTime
,D/hcjo    ( 4829): AutoUpdateManager:UPD_CHECK_TIMING:onNoUpdateTime
,D/SSRMv2:SIOP(  749): SIOP:: AP = 320, Delta = 10
D/InitializeManagerStateMachine( 4829): exit::SUCCESS
,D/InitializeManagerStateMachine( 4829): entry::IDLE
I/ActivityManager(  749): Killing 4278:com.wssyncmldm/1000 (adj 15): empty #43
,I/iu.SyncManager( 1784): SYNC; picasa accounts
,D/NetworkLogImpl( 1784): Loaded NetworkSpeedPredictor
,I/iu.Environment( 1784): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,I/iu.UploadsManager( 1784): num queued entries: 0
,I/iu.UploadsManager( 1784): num updated entries: 0
,I/iu.SyncManager( 1784): NEXT; no task
,I/SELinux ( 5342): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5342):  
,I/SELinux ( 5342): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5342):  
I/SELinux ( 5342):  
,I/SELinux ( 5342): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5342): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 5342): >>>>> Normal User
,E/dalvikvm( 5342): >>>>> com.android.calendar [ userId:0 | appId:10142 ]
,E/SELinux ( 5342): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 5342): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5342): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5342): Added TimaKesytore provider
,I/GCM     ( 1319): GCM config loaded
,D/dalvikvm(  749): GC_EXPLICIT freed 1316K, 60% free 23380K/57632K, paused 6ms+11ms, total 122ms
,D/BootCompletedReceiver(  749): onReceive
I/ActivityManager(  749): Killing 4421:com.android.defcontainer/u0a6 (adj 15): empty #43
,I/KLMS-2.3.201 : ( 5128): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,I/KLMS-2.3.201 : ( 5128): MainReciver() : EventNotificationReciver- method called: AppActivityListner onReceive for Intent Action : android.intent.action.TIME_SET , timestamp: 1450201718870
,I/KLMS-2.3.201 : ( 5128): StateImplV2() : dateTimeChanged() : Tue Dec 15 18:48:38 CET 2015
,D/SO_AGENT( 5143): [ServerTimeReceiver.java(Line:44/Method:onReceive)] Receive broadcast meassage:android.intent.action.TIME_SET
,I/SO_AGENT( 5143): [ServerTimeReceiver.java(Line:47/Method:onReceive)] No action is available before server time settings
,I/SA      ( 4697): [SBR] StdBroadcastReceiver received Intent of  action.TIME_SET.
,D/Mms/MessagingNotification( 3829): [start]    nonBlockingUpdateMessageIndicator()
,D/Mms/MessagingNotification( 3829): sDisableVibrateForCamera = false
,D/Mms/MessagingNotification( 3829): isBlockingModeEnable() = false
,D/Mms/TelephonyPermission( 3829): isDefault true
,I/SELinux ( 5372): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5372):  
,D/TP/MmsSmsProvider( 1237): match 200:Elapsed time : 1.267 ms
,D/BadgeProvider( 5307): query, [selection] : package='com.android.mms' AND class='com.android.mms.ui.ConversationComposer' AND extraData='base_extra_badge'
,D/Launcher.Model( 1241): reloadBadges entered.
D/BadgeProvider( 5307): sendNotify entered. [uri] : content://com.sec.badge/apps/2
D/BadgeProvider( 5307): sendNotify, [notify] : null
D/BadgeProvider( 5307): update, [uri] : content://com.sec.badge/apps/2
D/BadgeProvider( 5307): update, [BadgeCount] : badgecount=0
,D/BadgeProvider( 5307): update, [UpdateCount] : 1
,D/Mms/MessagingNotification( 3829): setBadgeCount(), count=0
,D/TP/MmsSmsProvider( 1237): match 8:Elapsed time : 30.886 ms
,D/MessagingNotification( 3829): remove alarm
,I/SELinux ( 5372): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5372):  
I/SELinux ( 5372):  
,I/SELinux ( 5372): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5372): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 5372): >>>>> Normal User
,E/dalvikvm( 5372): >>>>> com.samsung.android.scloud.sync [ userId:0 | appId:10062 ]
,E/SELinux ( 5372): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/Mms/MessagingNotification( 3829): updateAllHistoryAsRead()
,D/Mms/MessagingNotification( 3829): [end]    nonBlockingUpdateMessageIndicator()
,D/TimaKeyStoreProvider( 5372): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5372): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5372): Added TimaKesytore provider
,W/ActivityManager(  749): Permission Denial: getCurrentUser() from pid=5372, uid=10062 requires android.permission.INTERACT_ACROSS_USERS
,D/com.samsung.app( 1441): [KK_EASY_Accu]>>> WC:30 [0:0] action : androidintentactionTIME_SET
,D/com.samsung.app( 1441): [KK_EASY_Accu]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
,I/ Time Manager ( 5372): Time Difference not stored. TIME_DIFFERENCE
I/ActivityManager(  749): Killing 3228:com.sec.android.inputmethod/1000 (adj 15): empty #43
,I/SELinux ( 5397): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5397):  
,I/SELinux ( 5397): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5397):  
I/SELinux ( 5397):  
,I/SELinux ( 5397): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5397): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 5397): >>>>> Normal User
,E/dalvikvm( 5397): >>>>> com.sec.android.app.clockpackage [ userId:0 | appId:10084 ]
,E/SELinux ( 5397): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 5397): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5397): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5397): Added TimaKesytore provider
,D/ConnectivityService(  749): handleInetConditionHoldEnd: net=1, condition=100, published condition=0
,D/STATUSBAR-NetworkController_dual( 1064): onReceive() - CONNECTIVITY_ACTION, INET_CONDITION_ACTION
D/StatusBar.NetworkController_dual( 1064): mMobileLabelViews start
D/StatusBar.NetworkController_dual( 1064): mMobileLabelViews set mobileLabel[SIM_0] =
D/StatusBar.NetworkController_dual( 1064): mMobileLabelViews GONE
D/StatusBar.NetworkController_dual( 1064): mMobileLabelViews2 set mobileLabel[SIM_1] =
D/StatusBar.NetworkController_dual( 1064): mMobileLabelViews2 GONE
,D/StatusBar.NetworkController_dual( 1064): mSingleMobileLabelViews set : simMode = 0
,D/StatusBar.NetworkController_dual( 1064): mSingleMobileLabelViews set as slot1`s
,I/SELinux ( 5415): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5415):  
,I/ActivityManager(  749): Killing 4467:com.google.android.partnersetup/u0a14 (adj 15): empty #43
,I/SELinux ( 5415): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5415):  
I/SELinux ( 5415):  
,I/SELinux ( 5415): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5415): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 5415): >>>>> Normal User
,E/dalvikvm( 5415): >>>>> com.sec.esdk.elm [ userId:0 | appId:10094 ]
,E/SELinux ( 5415): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 5415): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5415): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5415): Added TimaKesytore provider
,W/WifiP2pStateTracker(  749): WifiP2pStateReceiver : android.net.wifi.LINK_CONFIGURATION_CHANGED
,D/ConnectivityService(  749): handleConnectivityChange: addresses changed linkProperty[1]: resetMask=0
D/ConnectivityService(  749):    car=removed=[] added=[fe80::3a94:96ff:feb5:6dd/64,]
,D/ConnectivityService(  749): handleConnectivityChange: setting default proxy info 
,D/ConnectivityService(  749): updateSourceRoutes : no source routing conditions
,W/ActivityManager(  749): Permission Denial: getCurrentUser() from pid=5415, uid=10094 requires android.permission.INTERACT_ACROSS_USERS
,D/elm:14132( 5415): ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver }
,D/elm:14132( 5415): ELMEngine.ELMEngine( context ).
,D/elm:14132( 5415): MDMBridge.setEnterpriseBridge()
,D/elm:14132( 5415): ELMAbstractReceiver : Receive Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.sec.esdk.elm/.service.ElmAgentService } END.
,I/knox    ( 3100): MainReceiver.onReceive() : Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.sec.knox.seandroid/.receiver.MainReceiver }
,W/ContextImpl( 3100): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1857 android.content.ContextWrapper.startService:506 android.content.ContextWrapper.startService:506 com.sec.knox.seandroid.receiver.MainReceiver.onReceive:142 android.app.ActivityThread.handleReceiver:2698 
D/knox    ( 3100): MainReceiver.listeningToTimeDateChanges( context, intent ).
I/knox    ( 3100): MainReceiver.onReceive() END - - - - - : Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.sec.knox.seandroid/.receiver.MainReceiver }
D/elm:14132( 5415): ElmAgentService : onCreate()
D/knox    ( 3100): KNOXAgentService : onCreate()
D/elm:14132( 5415): ElmAgentService : onHandleIntent() Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.sec.esdk.elm/.service.ElmAgentService }
D/knox    ( 3100): KNOXAgentService : set alarms for deniallog and usage data upload
D/knox    ( 3100): KNOXAgentService. startJobThread() start
D/knox    ( 3100): KNOXAgentService. JobThread()
D/knox    ( 3100): KNOXAgentService. JobThread. notifyAll().
D/knox    ( 3100): KNOXAgentService. startJobThread() wait
I/SELinux ( 5430): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5430):  
D/knox    ( 3100): KNOXAgentService : onDestroy().
D/knox    ( 3100): ModuleBase.cancelAllAlarmManageModule()
D/elm:14132( 5415): ELMAgentService.listeningToTimeDateChanges( context, intent ).
D/elm:14132( 5415): ELMEngine.ServiceHandler.handleMessage( ALARM_MODIFY ). 
D/elm:14132( 5415): ModuleBase.resetCalllogAPIAlarm()
,D/elm:14132( 5415): ModuleBase.ModifySetAlarm()
,D/elm:14132( 5415): MDMBridge.getInstance()
,D/elm:14132( 5415): MDMBridge.getAllLicenseInfoFromSDK()
,D/elm:14132( 5415): ElmAgentService : onDestroy().
I/ActivityManager(  749): Killing 4482:com.samsung.groupcast/u0a15 (adj 15): empty #43
,I/SELinux ( 5430): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5430):  
I/SELinux ( 5430):  
,I/SELinux ( 5430): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5430): [DEBUG] seapp_context_lookup: seinfoCategory = shared
E/dalvikvm( 5430): >>>>> Normal User
,E/dalvikvm( 5430): >>>>> com.sec.android.widgetapp.SPlannerAppWidget [ userId:0 | appId:10143 ]
,E/SELinux ( 5430): [DEBUG] seapp_context_lookup: seinfoCategory = shared
,D/TimaKeyStoreProvider( 5430): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5430): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5430): Added TimaKesytore provider
,W/ActivityManager(  749): Permission Denial: getCurrentUser() from pid=5430, uid=10143 requires android.permission.INTERACT_ACROSS_USERS
,I/SELinux ( 5442): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5442):  
I/ActivityManager(  749): Killing 4496:com.android.musicfx/u0a24 (adj 15): empty #43
D/STATUSBAR-NetworkController_dual( 1064): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
D/StatusBar.NetworkController_dual( 1064): mMobileLabelViews start
D/StatusBar.NetworkController_dual( 1064): mMobileLabelViews set mobileLabel[SIM_0] =
D/StatusBar.NetworkController_dual( 1064): mMobileLabelViews GONE
D/StatusBar.NetworkController_dual( 1064): mMobileLabelViews2 set mobileLabel[SIM_1] =
D/StatusBar.NetworkController_dual( 1064): mMobileLabelViews2 GONE
D/StatusBar.NetworkController_dual( 1064): mSingleMobileLabelViews set : simMode = 0
D/StatusBar.NetworkController_dual( 1064): mSingleMobileLabelViews set as slot1`s
,I/SELinux ( 5442): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5442):  
I/SELinux ( 5442):  
,I/SELinux ( 5442): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5442): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 5442): >>>>> Normal User
,E/dalvikvm( 5442): >>>>> com.sec.android.app.taskmanager [ userId:0 | appId:10166 ]
,E/SELinux ( 5442): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 5442): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5442): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5442): Added TimaKesytore provider
,W/ActivityManager(  749): Permission Denial: getCurrentUser() from pid=5442, uid=10166 requires android.permission.INTERACT_ACROSS_USERS
,I/SELinux ( 5454): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5454):  
I/ActivityManager(  749): Killing 4524:com.samsung.android.app.galaxyfinder/u0a34 (adj 15): empty #43
,I/SELinux ( 5454): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5454):  
I/SELinux ( 5454):  
,I/SELinux ( 5454): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5454): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 5454): >>>>> Normal User
,E/dalvikvm( 5454): >>>>> com.qualcomm.timeservice [ userId:0 | appId:10168 ]
,E/SELinux ( 5454): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 5454): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5454): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5454): Added TimaKesytore provider
,E/SMD     (  240): DCD ON
,W/ActivityManager(  749): Permission Denial: getCurrentUser() from pid=5454, uid=10168 requires android.permission.INTERACT_ACROSS_USERS
,D/dalvikvm( 5454): No JNI_OnLoad found in /vendor/lib/libTimeService.so 0x4258b9d0, skipping init
,D/TimeService( 5454): Receivedandroid.intent.action.TIME_SET intent. Current Time is 1450201720004
D/        ( 5454): TimeServiceNative: User Time to be set is 1450201720005
D/QC-time-services( 5454): Lib:time_genoff_operation: pargs->base = 2
,D/QC-time-services( 5454): Lib:time_genoff_operation: pargs->operation = 0
,D/QC-time-services( 5454): Lib:time_genoff_operation: pargs->ts_val = 1450201720005
D/QC-time-services(  285): Daemon: Connection accepted:time_genoff
,D/QC-time-services( 5454): Lib:time_genoff_operation: Send to server  passed!!
D/QC-time-services(  285): Daemon: genoff_handler: Process name is omm.timeservice
,D/QC-time-services(  285): Daemon:Received base = 2, unit = 1, operation = 0,value = 1450201720005
D/QC-time-services(  285): Daemon:genoff_opr: Base = 2, val = 1450201720005, operation = 0
,D/QC-time-services(  285): Daemon:rtc_get: Time read from RTC -- MM/DD/YY HH:MM:SS0/19/70 9:45:45
D/QC-time-services(  285): Daemon:Value read from RTC seconds = 1590345000
D/QC-time-services(  285): Daemon:new time 1450201720005 
D/QC-time-services(  285): Daemon: delta 1448611375005 genoff 1448611375005 
,D/QC-time-services(  285): Daemon:genoff_persistent_update: Writing genoff = 1448611375005 to memory
D/QC-time-services(  285): Daemon:Opening File: /data/time/ats_2
,D/QC-time-services(  285): Daemon:time_persistent_memory_opr:Genoff write operation 
,D/QC-time-services(  285): Updating the TOD offset
D/QC-time-services(  285): Daemon:genoff_persistent_update: Writing genoff = 1448611375005 to memory
D/QC-time-services(  285): Daemon:Opening File: /data/time/ats_1
,D/QC-time-services(  285): Daemon:time_persistent_memory_opr:Genoff write operation 
,E/QC-time-services(  285): Daemon:Update to modem bit set
D/QC-time-services(  285): Daemon:genoff_send_modem: Sending data to MODEM !
D/QC-time-services(  285): Daemon: Base = 2, Value being sent to MODEM = 1134236920005
,E/QC-time-services( 5454): Receive Passed == base = 2, unit = 1, operation = 0, result = 0
,E/QC-time-services(  285): Daemon: Time-services: Waiting to acceptconnection
,E/QC-time-services(  285): Daemon:tod_update_ind_cb: Got Update from modem msg_id 40
I/ActivityManager(  749): Killing 4563:com.sec.android.service.health/u0a16 (adj 15): empty #43
,D/daemonapp( 1461): [MSC_Daemon]>>> WU:236 [0:0] regintype : EUR
,D/daemonapp( 1461): [MSC_Daemon]>>> WU:292 [0:0] cp type is : cp_eng
,D/daemonapp( 1461): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/daemonapp( 1461): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,D/daemonapp( 1461): [MSC_Daemon]>>> WDSM:44 [0:0] Act : androidintentactionTIME_SET, run:true
,D/comsamsunglog( 1461): [MSC_Daemon]>>> ====================================================================================================================
D/comsamsunglog( 1461): [MSC_Daemon]>>> daemonapp [Version : 14052601 ] [ 1 ] 
D/comsamsunglog( 1461): [MSC_Daemon]>>> Header set to : ===> "daemonapp" <===
,D/comsamsunglog( 1461): [MSC_Daemon]>>> ====================================================================================================================
,D/daemonapp( 1461): [MSC_Daemon]>>> WDSM:85 [0:0] c:null, r:3
,D/daemonapp( 1461): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/packagename
,D/daemonapp( 1461): [MSC_Daemon]>>> WU:1485 [0:0] PakNme size = 2
,D/daemonapp( 1461): [MSC_Daemon]>>> WU:236 [0:0] regintype : EUR
,D/daemonapp( 1461): [MSC_Daemon]>>> WU:292 [0:0] cp type is : cp_eng
,D/daemonapp( 1461): [MSC_Daemon]>>> WU:1488 [0:0] CP Name cp_eng
,D/daemonapp( 1461): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/packagename
,D/comdaemonstockapp( 1461): [Daemon_Stock]>>> StockclockDaemonService.java:60 [0:0] onReceive: androidintentactionTIME_SET
,D/comdaemonstockapp( 1461): [Daemon_Stock]>>> StockclockDaemonService.java:61 [0:0] appServiceStatus: 0
,I/CheckinService( 1784): Checkin interval check for package: unspecified last checkin: 1450164630465 min interval config: 0 actual interval: 37089646
,D/Mms/MessagesLockscreen( 3829): onReceive() action = com.android.mms.ui.MessagesLockscreenmSimSlot : [0] Mms = false count = 0
,D/ContextualEventManager( 1064): removeContextualEvent(): requestClass=com.android.mms
D/ContextualEventManager( 1064): removeMissedEventView rq=com.android.mms[cFlag, mFlag]=[false, false]
D/ContextualEventManager( 1064): updateContainer()
D/ContextualEventContainer( 1064): update()
D/ContextualEventContainer( 1064): handleUpdate()
D/ContextualEventManager( 1064): getTopEventView()
,D/ContextualEventManager( 1064): getTopContextualEvent()
,D/ContextualEventManager( 1064): top view = flightmode
I/KeyguardEffectViewMain( 1064): *** KeyguardEffectView getInstance ***
D/ContextualEventManager( 1064): getTopEventClass()
,D/ContextualEventManager( 1064): getTopContextualEvent()
,D/ContextualEventManager( 1064): !isClockTop
D/ContextualEventManager( 1064): getTopEventClass()
,D/ContextualEventManager( 1064): getTopContextualEvent()
D/ContextualEventManager( 1064): !isClockTop
D/ContextualEventManager( 1064): getTopEventClass()
,D/ContextualEventManager( 1064): getTopContextualEvent()
D/UsbManager( 1064):  :::: isUsb30Available :: return = false from pid = 1064
,D/SecContextualClockFlightMode( 1064): handleUpdateClock()
,D/KeyguardProperties( 1064): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
W/ContextImpl(  749): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,I/VacuumService( 1216): Vacuum at: now=1450201720387 tag=VacuumService
,I/PCWCLIENTTRACE_SYSTEMReceiver( 4510): mConnectivityHandler : connected
,V/AlarmManager(  749): waitForAlarm result :4
,V/AlarmManager(  749): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,D/dalvikvm( 1784): GC_CONCURRENT freed 1462K, 34% free 12289K/18408K, paused 8ms+5ms, total 59ms
,I/SELinux ( 5472): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5472):  
,W/PCWCLIENTTRACE_AccountUtil( 4510): [hasSamungAccount] - No Samsung Account
,D/BatteryService(  749): level:100, scale:100, status:5, health:2, present:true, voltage: 4366, temperature: 292, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:4, charge type:1, power sharing:false
D/BatteryService(  749): stay LED for fully charged
,D/BatteryService(  749): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1064): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1064): handleBatteryUpdate
I/SELinux ( 5472): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5472):  
I/SELinux ( 5472):  
,I/SELinux ( 5472): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,D/UiModeManager(  749): mCoverManager.getCoverState() : true
E/SELinux ( 5472): [DEBUG] seapp_context_lookup: seinfoCategory = release
E/dalvikvm( 5472): >>>>> Normal User
E/dalvikvm( 5472): >>>>> com.android.providers.calendar [ userId:0 | appId:10044 ]
V/HeadsetService( 3191): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 3191): Disconnected process message: 10
E/SELinux ( 5472): [DEBUG] seapp_context_lookup: seinfoCategory = release
,D/STATUSBAR-PhoneStatusBar( 1064):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1064): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/TimaKeyStoreProvider( 5472): in addTimaSignatureService
D/TimaKeyStoreProvider( 5472): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 5472): Added TimaKesytore provider
,D/STATUSBAR-IconMerger( 1064): checkOverflow(288), More:false, Req:false Child:2
,W/linker  ( 4510): libterrier.so has text relocations. This is wasting memory and is a security risk. Please fix.
,I/CSTORAGE( 4510): ================================================
I/CSTORAGE( 4510):  CSTORAGE_SKM_LIB v1.0.14
I/CSTORAGE( 4510): ================================================
D/dalvikvm( 4510): No JNI_OnLoad found in /system/lib/libterrier.so 0x4258b110, skipping init
,I/PCWCLIENTTRACE_SecurePreferencesJNI( 4510): [GetString-S]
,I/terrier ( 4510): v1.1.3q com.sec.pcw.device: getString function called
D/QSEECOMAPI: ( 4510): QSEECom_get_handle sb_length = 0x2040
,D/QSEECOMAPI: ( 4510): App is not loaded in QSEE
,D/QSEECOMAPI: ( 4510): Loaded image: APP id = 4
,D/QSEECOMAPI: ( 4510): QSEECom_dealloc_memory 
,D/QSEECOMAPI: ( 4510): QSEECom_shutdown_app, app_id = 4
E/terrier ( 4510): com.sec.pcw.device: getString: failed to get string(-1)
,I/PCWCLIENTTRACE_SecurePreferencesJNI( 4510): [GetString-E]
,I/PCWCLIENTTRACE_PushUtil( 4510): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 4510): sales region : global
I/PCWCLIENTTRACE_PushUtil( 4510): getPushTypeList : [SPP, GCM]
,E/PCWCLIENTTRACE_PCWHandler( 4510): [ensureRegistration] - No Samsung account
,W/ActivityManager(  749): Permission Denial: getCurrentUser() from pid=5472, uid=10044 requires android.permission.INTERACT_ACROSS_USERS
,D/Headlines( 5216): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE
D/Headlines( 5216): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0
,D/Headlines( 5216): Breath 3616 latestRequest time : 1450201717302 current time : 1450201720918
,V/AlarmManager(  749): waitForAlarm result :4
,V/AlarmManager(  749): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,I/ActivityManager(  749): Killing 3903:com.samsung.android.sdk.samsunglink/u0a42 (adj 15): empty #43
,I/GAV2    ( 5228): Thread[GAThread,5,main]: No campaign data found.
,D/STATUSBAR-NetworkController_dual( 1064): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
,D/StatusBar.NetworkController_dual( 1064): mMobileLabelViews start
D/StatusBar.NetworkController_dual( 1064): mMobileLabelViews set mobileLabel[SIM_0] =
D/StatusBar.NetworkController_dual( 1064): mMobileLabelViews GONE
D/StatusBar.NetworkController_dual( 1064): mMobileLabelViews2 set mobileLabel[SIM_1] =
,D/StatusBar.NetworkController_dual( 1064): mMobileLabelViews2 GONE
D/StatusBar.NetworkController_dual( 1064): mSingleMobileLabelViews set : simMode = 0
,D/StatusBar.NetworkController_dual( 1064): mSingleMobileLabelViews set as slot1`s
,D/Finsky  ( 3555): [349] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 3555): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,E/SMD     (  240): DCD ON
,I/PowerManagerService(  749): [PWL] Off : 75s ago
,E/Watchdog(  749): !@Sync 4
,D/CaptivePortalTracker(  749): DelayedCaptiveCheckState{ when=-1ms what=2 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  749): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,D/CaptivePortalTracker(  749): Checking http://216.58.209.46/generate_204
,W/ActivityThread(  749): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,I/System.out(  749): Thread-164(HTTPLog):isShipBuild true
,I/System.out(  749): Thread-164(HTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,D/CaptivePortalTracker(  749): Don't send network conditions - lacking user consent.
,D/CaptivePortalTracker(  749): isCaptivePortal: ret=false rspCode=204
,D/CaptivePortalTracker(  749): Not captive network NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/CaptivePortalTracker(  749): notifyPortalCheckCompleted: captive=false ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService(  749): captivePortalCheckCompleted: ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false captive=false
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  749): prevTemp = 288, currTemp = 292, prevStep = 4, currStep = 4
,D/PreloadUpdateManagerStateMachine( 4829): execute::IDLE:EXECUTE
,D/PreloadUpdateManagerStateMachine( 4829): exit::IDLE
,D/PreloadUpdateManagerStateMachine( 4829): entry::CHECK_TIMEOUT_FOR_UPDATE
,D/hcjo    ( 4829): AutoUpdateTriggerManager:IDLE:setInterval:86400000
D/SSRMv2:SIOP(  749): SIOP:: AP = 300, Delta = -20
,D/hcjo    ( 4829): AutoUpdateTriggerManager:IDLE:notifyNextTime
,D/PreloadUpdateManagerStateMachine( 4829): execute::CHECK_TIMEOUT_FOR_UPDATE:NO_TIMED_OUT
,D/PreloadUpdateManagerStateMachine( 4829): exit::CHECK_TIMEOUT_FOR_UPDATE
,D/PreloadUpdateManagerStateMachine( 4829): entry::IDLE
,E/SMD     (  240): DCD ON
,D/BatteryService(  749): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 292, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:2, charge type:1, power sharing:false
,D/BatteryService(  749): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  749): stay LED for fully charged
,D/UiModeManager(  749): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1064): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1064): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1064):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1064): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1064): checkOverflow(288), More:false, Req:false Child:2
,V/HeadsetService( 3191): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3191): Disconnected process message: 10
,E/SMD     (  240): DCD ON
,I/ActivityManager(  749): Waited long enough for: ServiceRecord{43c5eea8 u0 com.samsung.android.app.headlines/com.samsung.android.internal.headlines.HeadlinesService}
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  749): prevTemp = 292, currTemp = 292, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  749): SIOP:: AP = 300, Delta = 0
,V/AlarmManager(  749): waitForAlarm result :8
,V/AlarmManager(  749): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1064): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1064): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1064): checkOverflow(288), More:false, Req:false Child:2
,W/ContextImpl(  749): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  749): prevTemp = 292, currTemp = 292, prevStep = 4, currStep = 4
,V/AlarmManager(  749): waitForAlarm result :4
,V/AlarmManager(  749): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,D/Headlines( 5216): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE
,D/BatteryService(  749): level:100, scale:100, status:5, health:2, present:true, voltage: 4367, temperature: 289, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:3, charge type:1, power sharing:false
,D/BatteryService(  749): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  749): stay LED for fully charged
,D/UiModeManager(  749): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1064): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1064): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1064):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1064): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3191): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3191): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1064): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  749): SIOP:: AP = 300, Delta = 0
,D/Headlines( 5216): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0
,D/Headlines( 5216): Breath 31279 latestRequest time : 1450201717302 current time : 1450201748581
,E/ActivityThread( 1784): Failed to find provider info for com.android.contacts.metadata
,D/SyncManager(  749): failed sync operation 
,D/SyncManager(  749): not retrying sync operation because the error is a hard error: 
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,I/PowerManagerService(  749): [PWL] Off : 105s ago
,E/Watchdog(  749): !@Sync 5
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  749): prevTemp = 292, currTemp = 289, prevStep = 4, currStep = 4
,D/BatteryService(  749): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 288, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:2, charge type:1, power sharing:false
,D/BatteryService(  749): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  749): mCoverManager.getCoverState() : true
,D/BatteryService(  749): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1064): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1064): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1064):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1064): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3191): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3191): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1064): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  749): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,W/ContextImpl(  749): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  749): prevTemp = 289, currTemp = 288, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,D/BatteryService(  749): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  749): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  749): mCoverManager.getCoverState() : true
,D/BatteryService(  749): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1064): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1064): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1064):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3191): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3191): Disconnected process message: 10
D/STATUSBAR-IconMerger( 1064): checkOverflow(288), More:false, Req:false Child:2
D/BatteryMeterView( 1064): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SSRMv2:SIOP(  749): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  749): prevTemp = 288, currTemp = 287, prevStep = 4, currStep = 4
,V/AlarmManager(  749): waitForAlarm result :8
,V/AlarmManager(  749): waitForAlarm result :4
,V/AlarmManager(  749): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,D/Headlines( 5216): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE
,D/BatteryService(  749): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:4, charge type:1, power sharing:false
,D/BatteryService(  749): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  749): stay LED for fully charged
,D/SSRMv2:SIOP(  749): SIOP:: AP = 300, Delta = 0
,D/UiModeManager(  749): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1064): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1064): handleBatteryUpdate
,D/Headlines( 5216): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0
,D/STATUSBAR-PhoneStatusBar( 1064):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1064): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3191): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3191): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1064): checkOverflow(288), More:false, Req:false Child:2
,D/Headlines( 5216): Breath 61547 latestRequest time : 1450201717302 current time : 1450201778849
,E/SMD     (  240): DCD ON
,W/ContextImpl(  749): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  240): DCD ON
,E/Watchdog(  749): !@Sync 6
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  749): prevTemp = 287, currTemp = 286, prevStep = 4, currStep = 4
,I/PowerManagerService(  749): [PWL] Off : 140s ago
,D/BatteryService(  749): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:3, charge type:1, power sharing:false
,D/BatteryService(  749): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  749): stay LED for fully charged
,D/UiModeManager(  749): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1064): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1064): handleBatteryUpdate
,D/SSRMv2:SIOP(  749): SIOP:: AP = 300, Delta = 0
,D/STATUSBAR-PhoneStatusBar( 1064):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1064): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3191): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3191): Disconnected process message: 10
D/STATUSBAR-IconMerger( 1064): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  749): prevTemp = 286, currTemp = 285, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  749): SIOP:: AP = 300, Delta = 0
,V/AlarmManager(  749): waitForAlarm result :8
,V/AlarmManager(  749): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1064): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1064): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1064): checkOverflow(288), More:false, Req:false Child:2
,D/BatteryService(  749): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  749): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  749): stay LED for fully charged
,D/UiModeManager(  749): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1064): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1064): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1064):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1064): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3191): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3191): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1064): checkOverflow(288), More:false, Req:false Child:2
,W/ContextImpl(  749): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  749): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,V/AlarmManager(  749): waitForAlarm result :8
,D/Headlines( 5216): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE
,D/Headlines( 5216): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0
,D/Headlines( 5216): Breath 90058 latestRequest time : 1450201717302 current time : 1450201807361
,D/SSRMv2:SIOP(  749): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,D/BatteryService(  749): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 284, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  749): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  749): stay LED for fully charged
,D/UiModeManager(  749): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1064): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1064): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1064):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1064): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1064): checkOverflow(288), More:false, Req:false Child:2
V/HeadsetService( 3191): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 3191): Disconnected process message: 10
,E/SMD     (  240): DCD ON
,E/Watchdog(  749): !@Sync 7
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  749): prevTemp = 285, currTemp = 284, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP(  749): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,D/BatteryService(  749): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 284, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:6, charge type:1, power sharing:false
,D/BatteryService(  749): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  749): stay LED for fully charged
,D/UiModeManager(  749): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1064): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1064): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1064):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1064): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3191): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3191): Disconnected process message: 10
D/STATUSBAR-IconMerger( 1064): checkOverflow(288), More:false, Req:false Child:2
W/ContextImpl(  749): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  749): prevTemp = 284, currTemp = 284, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,I/PowerManagerService(  749): [PWL] Off : 180s ago
,D/SSRMv2:SIOP(  749): SIOP:: AP = 300, Delta = 0
,D/BatteryService(  749): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 283, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:6, charge type:1, power sharing:false
,D/BatteryService(  749): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  749): mCoverManager.getCoverState() : true
,D/BatteryService(  749): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1064): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1064): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1064):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1064): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3191): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3191): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1064): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  749): prevTemp = 284, currTemp = 283, prevStep = 4, currStep = 4
,V/AlarmManager(  749): waitForAlarm result :8
,D/Headlines( 5216): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE
,D/Headlines( 5216): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0
,D/Headlines( 5216): Breath 120035 latestRequest time : 1450201717302 current time : 1450201837338
,D/Headlines( 5216): stop 
,D/Headlines( 5216): Breath.onDestroy : 
,I/ActivityManager(  749): Killing 2845:com.samsung.android.app.assistantmenu/1000 (adj 15): empty #43
,D/SSRMv2:SIOP(  749): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,W/ContextImpl(  749): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/BatteryService(  749): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 283, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:8, charge type:1, power sharing:false
,D/BatteryService(  749): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  749): stay LED for fully charged
,D/UiModeManager(  749): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1064): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1064): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1064):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1064): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3191): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3191): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1064): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,E/Watchdog(  749): !@Sync 8
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  749): prevTemp = 283, currTemp = 283, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  749): SIOP:: AP = 300, Delta = 0
,D/BatteryService(  749): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:4, charge type:1, power sharing:false
,D/BatteryService(  749): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  749): mCoverManager.getCoverState() : true
,D/BatteryService(  749): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1064): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1064): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1064):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1064): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3191): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3191): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1064): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  749): prevTemp = 283, currTemp = 282, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  749): SIOP:: AP = 300, Delta = 0
,V/AlarmManager(  749): waitForAlarm result :8
,V/AlarmManager(  749): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1064): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1064): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1064): checkOverflow(288), More:false, Req:false Child:2
,W/ContextImpl(  749): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/BatteryService(  749): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:6, charge type:1, power sharing:false
,D/BatteryService(  749): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  749): stay LED for fully charged
,D/UiModeManager(  749): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1064): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1064): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1064):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1064): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1064): checkOverflow(288), More:false, Req:false Child:2
,V/HeadsetService( 3191): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3191): Disconnected process message: 10
,D/dalvikvm(  749): GC_CONCURRENT freed 3079K, 59% free 23671K/57632K, paused 44ms+20ms, total 485ms
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  749): prevTemp = 282, currTemp = 282, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP(  749): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,D/BatteryService(  749): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:5, charge type:1, power sharing:false
,D/BatteryService(  749): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  749): mCoverManager.getCoverState() : true
,D/BatteryService(  749): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1064): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1064): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1064):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1064): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3191): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3191): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1064): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,I/PowerManagerService(  749): [PWL] Off : 225s ago
,E/Watchdog(  749): !@Sync 9
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  749): prevTemp = 282, currTemp = 282, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  749): SIOP:: AP = 300, Delta = 0
,W/ContextImpl(  749): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/BatteryService(  749): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  749): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  749): stay LED for fully charged
,D/UiModeManager(  749): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1064): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1064): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1064):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1064): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3191): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3191): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1064): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  749): prevTemp = 282, currTemp = 282, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  749): SIOP:: AP = 300, Delta = 0
,D/BatteryService(  749): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  749): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  749): mCoverManager.getCoverState() : true
,D/BatteryService(  749): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1064): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1064): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1064):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1064): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3191): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3191): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1064): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  749): prevTemp = 282, currTemp = 281, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP(  749): SIOP:: AP = 300, Delta = 0
,D/TimaService(  749): TIMA: TimaService scheduler is intialized. 
,D/TimaService(  749): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService(  749): TimaServiceHandler.handleMessage what =1
,I/TLC_TIMA_PKM_initialize(  749): initializing...
,I/TLC_TIMA_PKM_initialize(  749): root = /firmware/image, root_strlen = 15
,I/TLC_TIMA_PKM_initialize(  749): process = tima_pkm, process_strlen = 8
,I/TZ: qc_tlc_communication(  749): root = /firmware/image, root_len = 15
,I/TZ: qc_tlc_communication(  749): process = tima_pkm, process_strlen = 8
,I/TZ: qc_tlc_communication(  749): aligned max_sendmsg_size = 262208 = 0x40040
,I/TZ: qc_tlc_communication(  749): aligned max_recvmsg_size = 262208 = 0x40040
,I/TZ: qc_tlc_communication(  749): max_message_size = 524416 = 0x80080
,D/QSEECOMAPI: (  749): QSEECom_get_handle sb_length = 0x80080
,D/QSEECOMAPI: (  749): App is not loaded in QSEE
,D/QSEECOMAPI: (  749): Loaded image: APP id = 4
,I/TZ: qc_tlc_communication(  749): TIMA: path = /firmware/image, fname = tima_pkm, tzapp is loaded
,I/TLC_TIMA_PKM_initialize(  749): Trustlet response is completed
,E/SMD     (  240): DCD ON
,W/ContextImpl(  749): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/BatteryService(  749): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:3, charge type:1, power sharing:false
,D/BatteryService(  749): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  749): mCoverManager.getCoverState() : true
,D/BatteryService(  749): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1064): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1064): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1064):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1064): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1064): checkOverflow(288), More:false, Req:false Child:2
,V/HeadsetService( 3191): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3191): Disconnected process message: 10
,E/SMD     (  240): DCD ON
,I/TLC_TIMA_PKM_measure_kernel(  749): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel(  749): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService(  749): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService(  749): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/Watchdog(  749): !@Sync 10
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  749): prevTemp = 281, currTemp = 281, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  749): SIOP:: AP = 300, Delta = 0
,D/BatteryService(  749): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  749): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  749): mCoverManager.getCoverState() : true
,D/BatteryService(  749): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1064): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1064): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1064):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1064): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3191): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3191): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1064): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  749): prevTemp = 281, currTemp = 281, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  749): SIOP:: AP = 300, Delta = 0
,V/AlarmManager(  749): waitForAlarm result :8
,V/AlarmManager(  749): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1064): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1064): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1064): checkOverflow(288), More:false, Req:false Child:2
,W/ContextImpl(  749): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  240): DCD ON
,I/PowerManagerService(  749): [PWL] Off : 275s ago
,E/SMD     (  240): DCD ON
,V/AlarmManager(  749): waitForAlarm result :4
,V/AlarmManager(  749): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,I/SELinux ( 5581): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5581):  
D/BatteryService(  749): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 280, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
D/BatteryService(  749): Sending ACTION_BATTERY_CHANGED.
D/BatteryService(  749): stay LED for fully charged
,D/UiModeManager(  749): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1064): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1064): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1064):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 1064): checkOverflow(288), More:false, Req:false Child:2
,D/BatteryMeterView( 1064): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3191): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3191): Disconnected process message: 10
,D/dalvikvm(  247): GC_EXPLICIT freed 41K, 49% free 9511K/18408K, paused 23ms+29ms, total 291ms
,D/dalvikvm(  247): GC_EXPLICIT freed <1K, 49% free 9511K/18408K, paused 17ms+27ms, total 188ms
,I/SELinux ( 5581): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5581):  
I/SELinux ( 5581):  
,I/SELinux ( 5581): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5581): [DEBUG] seapp_context_lookup: seinfoCategory = default
,E/dalvikvm( 5581): >>>>> Normal User
,E/dalvikvm( 5581): >>>>> com.blurb.checkout [ userId:0 | appId:10075 ]
,E/SELinux ( 5581): [DEBUG] seapp_context_lookup: seinfoCategory = default
,D/dalvikvm(  247): GC_EXPLICIT freed <1K, 49% free 9511K/18408K, paused 18ms+22ms, total 204ms
,D/TimaKeyStoreProvider( 5581): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5581): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5581): Added TimaKesytore provider
,W/ActivityManager(  749): Permission Denial: getCurrentUser() from pid=5581, uid=10075 requires android.permission.INTERACT_ACROSS_USERS
,I/ActivityManager(  749): Killing 4716:com.sec.android.service.cm/u0a78 (adj 15): empty #43
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  749): prevTemp = 281, currTemp = 280, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP(  749): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,V/GLSActivity( 1319): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1319): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/dalvikvm( 1319): GC_EXPLICIT freed 1212K, 42% free 10777K/18408K, paused 18ms+23ms, total 160ms
,D/dalvikvm( 3555): GC_CONCURRENT freed 2765K, 44% free 10443K/18408K, paused 5ms+6ms, total 59ms
,E/Watchdog(  749): !@Sync 11
,D/BatteryService(  749): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:2, charge type:1, power sharing:false
,D/BatteryService(  749): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  749): stay LED for fully charged
,D/UiModeManager(  749): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1064): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1064): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1064):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3191): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3191): Disconnected process message: 10
D/STATUSBAR-IconMerger( 1064): checkOverflow(288), More:false, Req:false Child:2
D/BatteryMeterView( 1064): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  749): prevTemp = 280, currTemp = 281, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  749): SIOP:: AP = 300, Delta = 0
,W/ContextImpl(  749): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/BatteryService(  749): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 280, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  749): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  749): mCoverManager.getCoverState() : true
,D/BatteryService(  749): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1064): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1064): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1064):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1064): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3191): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/STATUSBAR-IconMerger( 1064): checkOverflow(288), More:false, Req:false Child:2
D/HeadsetStateMachine( 3191): Disconnected process message: 10
,D/AmoledAdjustTimer(  749): prevTemp = 281, currTemp = 280, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  749): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/BatteryService(  749): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 280, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService(  749): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  749): mCoverManager.getCoverState() : true
,D/BatteryService(  749): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1064): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1064): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1064):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1064): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3191): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3191): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1064): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  749): prevTemp = 280, currTemp = 280, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP(  749): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,W/ContextImpl(  749): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  240): DCD ON
,E/Watchdog(  749): !@Sync 12
,D/BatteryService(  749): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 280, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:2, charge type:1, power sharing:false
,D/BatteryService(  749): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  749): stay LED for fully charged
,D/UiModeManager(  749): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1064): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1064): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1064):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1064): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3191): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3191): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1064): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  749): prevTemp = 280, currTemp = 280, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  749): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/BatteryService(  749): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 280, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:2, charge type:1, power sharing:false
,D/BatteryService(  749): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  749): mCoverManager.getCoverState() : true
,D/BatteryService(  749): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1064): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1064): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1064):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1064): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3191): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3191): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1064): checkOverflow(288), More:false, Req:false Child:2
,D/AmoledAdjustTimer(  749): prevTemp = 280, currTemp = 280, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,I/PowerManagerService(  749): [PWL] Off : 330s ago
,D/SSRMv2:SIOP(  749): SIOP:: AP = 300, Delta = 0
,V/AlarmManager(  749): waitForAlarm result :8
,V/AlarmManager(  749): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1064): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1064): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1064): checkOverflow(288), More:false, Req:false Child:2
,W/ContextImpl(  749): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,I/jxcore-log( 4661): Connected to the server!
I/jxcore-log( 4661): 
,I/chromium( 4661): [INFO:CONSOLE(63)] "logCallback Connected to the server", source: file:///android_asset/www/js/thali_main.js (63)
,D/BatteryService(  749): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:3, charge type:1, power sharing:false
,D/BatteryService(  749): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  749): stay LED for fully charged
,D/UiModeManager(  749): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1064): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1064): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1064):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1064): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3191): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3191): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1064): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  749): prevTemp = 280, currTemp = 279, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP(  749): SIOP:: AP = 300, Delta = 0
,I/jxcore-log( 4661): --- start :testFindPeers.js---
I/jxcore-log( 4661): 
,I/jxcore-log( 4661): testFindPeers created [object Object]
I/jxcore-log( 4661): 
,I/jxcore-log( 4661): serverPort is 8876
I/jxcore-log( 4661): 
,I/dalvikvm( 4661): Could not find method android.bluetooth.BluetoothAdapter.isMultipleAdvertisementSupported, referenced from method org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager.isBleAdvertisingSupported
,W/dalvikvm( 4661): VFY: unable to resolve virtual method 52: Landroid/bluetooth/BluetoothAdapter;.isMultipleAdvertisementSupported ()Z
,D/dalvikvm( 4661): VFY: replacing opcode 0x6e at 0x0019
,I/dalvikvm( 4661): Could not find method android.bluetooth.BluetoothAdapter.isMultipleAdvertisementSupported, referenced from method org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager.isBleAdvertisingSupported
W/dalvikvm( 4661): VFY: unable to resolve virtual method 52: Landroid/bluetooth/BluetoothAdapter;.isMultipleAdvertisementSupported ()Z
,D/dalvikvm( 4661): VFY: replacing opcode 0x6e at 0x0020
,D/AndroidRuntime( 4661): Shutting down VM
,W/dalvikvm( 4661): threadid=1: thread exiting with uncaught exception (group=0x41864da0)
,E/AndroidRuntime( 4661): FATAL EXCEPTION: main
E/AndroidRuntime( 4661): Process: com.test.thalitest, PID: 4661
E/AndroidRuntime( 4661): java.lang.NoSuchMethodError: android.bluetooth.BluetoothAdapter.isMultipleAdvertisementSupported
E/AndroidRuntime( 4661): 	at org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager.isBleAdvertisingSupported(BluetoothManager.java:134)
E/AndroidRuntime( 4661): 	at org.thaliproject.p2p.btconnectorlib.DiscoveryManager.setDiscoveryMode(DiscoveryManager.java:133)
E/AndroidRuntime( 4661): 	at org.thaliproject.p2p.btconnectorlib.DiscoveryManager.setDiscoveryMode(DiscoveryManager.java:183)
E/AndroidRuntime( 4661): 	at org.thaliproject.p2p.btconnectorlib.DiscoveryManager.<init>(DiscoveryManager.java:95)
E/AndroidRuntime( 4661): 	at io.jxcore.node.ConnectionHelper.start(ConnectionHelper.java:92)
E/AndroidRuntime( 4661): 	at io.jxcore.node.JXcoreExtension$5.Receiver(JXcoreExtension.java:155)
E/AndroidRuntime( 4661): 	at io.jxcore.node.jxcore.javaCall(jxcore.java:228)
E/AndroidRuntime( 4661): 	at io.jxcore.node.jxcore.loopOnce(Native Method)
E/AndroidRuntime( 4661): 	at io.jxcore.node.jxcore$4.run(jxcore.java:196)
E/AndroidRuntime( 4661): 	at android.os.Handler.handleCallback(Handler.java:733)
E/AndroidRuntime( 4661): 	at android.os.Handler.dispatchMessage(Handler.java:95)
E/AndroidRuntime( 4661): 	at android.os.Looper.loop(Looper.java:146)
E/AndroidRuntime( 4661): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/AndroidRuntime( 4661): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime( 4661): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime( 4661): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/AndroidRuntime( 4661): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/AndroidRuntime( 4661): 	at dalvik.system.NativeStart.main(Native Method)
,W/ActivityManager(  749):   Force finishing activity com.test.thalitest/.MainActivity
,D/LockPatternUtils( 1064): isPcwEnable = null
,I/ActivityManager(  749): Killing 4728:com.google.android.apps.docs/u0a90 (adj 15): empty #43
,D/CrashAnrDetector(  749): processName: com.test.thalitest
,D/CrashAnrDetector(  749): broadcastEvent : com.test.thalitest data_app_crash
,W/ContextImpl(  749): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1515 com.android.server.analytics.data.collection.application.CrashAnrDetector.broadcastEvent:296 com.android.server.analytics.data.collection.application.CrashAnrDetector.processDropBoxEntry:254 com.android.server.analytics.data.collection.application.CrashAnrDetector.access$100:60 com.android.server.analytics.data.collection.application.CrashAnrDetector$1.onReceive:102 
,I/Process ( 4661): Sending signal. PID: 4661 SIG: 9
,D/CustomFrequencyManagerService(  749): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 749  pkgName : ACTIVITY_RESUME_BOOSTER@5
,W/ActivityManager(  749): mDVFSHelper.acquire()
,D/KeyguardUpdateMonitor( 1064): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1064): handleKeyguardVisibilityChanged(1)
,D/KeyguardUpdateMonitor( 1064): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1064): handleKeyguardVisibilityChanged(1)
,D/KeyguardUpdateMonitor( 1064): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1064): handleKeyguardVisibilityChanged(1)
,D/LockPatternUtils( 1064): isPcwEnable = null
,D/Launcher( 1241): onRestart, Launcher: 1113769872
,D/Launcher( 1241): onStart, Launcher: 1113769872
,D/Launcher.HomeView( 1241): onStart
,D/KeyguardUpdateMonitor( 1064): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1064): handleKeyguardVisibilityChanged(1)
,D/SurfaceWidgetClient$ISurfaceWidgetStub( 1441): [237392/5] Surface widget visibility changed visibility = true on instance = 1
,D/SurfaceWidget.Renderer( 1441): [237392/5] SurfaceWidget drawing first frame
,I/SurfaceFlinger(  246): id=20 createSurf (1x1),2 flag=404, CatteryCove
,D/KeyguardUpdateMonitor( 1064): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1064): handleKeyguardVisibilityChanged(1)
,I/SurfaceFlinger(  246): id=21 createSurf (720x1280),1 flag=4, Mauncher
,D/KeyguardUpdateMonitor( 1064): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1064): handleKeyguardVisibilityChanged(1)
,E/SMD     (  240): DCD ON
,I/SurfaceFlinger(  246): id=22 createSurf (707x984),1 flag=4, TettingsRec
,D/KeyguardUpdateMonitor( 1064): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1064): handleKeyguardVisibilityChanged(1)
,D/KeyguardUpdateMonitor( 1064): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1064): handleKeyguardVisibilityChanged(1)
,D/KeyguardUpdateMonitor( 1064): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1064): handleKeyguardVisibilityChanged(1)
,I/ActivityManager(  749): Process com.test.thalitest (pid 4661) (adj 9) has died.
,I/SurfaceFlinger(  246): id=18 Removed NainActivit (10/14)
,I/SurfaceFlinger(  246): id=18 Removed NainActivit (-2/14)
,I/WindowState(  749): WIN DEATH: Window{43156290 u0 com.test.thalitest/com.test.thalitest.MainActivity}
D/KeyguardUpdateMonitor( 1064): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1064): handleKeyguardVisibilityChanged(1)
I/SurfaceFlinger(  246): id=18 Removed NainActivit (-2/14)
,D/Launcher.HomeView( 1241): onStop
D/CustomFrequencyManagerService(  749): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 749  tag : ACTIVITY_RESUME_BOOSTER@5
W/ActivityManager(  749): mDVFSHelper.release()
,D/CustomFrequencyManagerService(  749): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 749  pkgName : ACTIVITY_RESUME_BOOSTER@9
D/KeyguardUpdateMonitor( 1064): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1064): handleKeyguardVisibilityChanged(1)
D/KeyguardUpdateMonitor( 1064): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1064): handleKeyguardVisibilityChanged(1)
,D/KeyguardUpdateMonitor( 1064): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1064): handleKeyguardVisibilityChanged(1)
,D/CustomFrequencyManagerService(  749): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 749  tag : ACTIVITY_RESUME_BOOSTER@9
,E/SMD     (  240): DCD ON
,E/Watchdog(  749): !@Sync 13
,D/BatteryService(  749): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  749): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  749): mCoverManager.getCoverState() : true
,D/BatteryService(  749): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1064): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1064): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1064):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1064): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 3191): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 3191): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1064): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  749): prevTemp = 279, currTemp = 279, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  749): SIOP:: AP = 300, Delta = 0
,W/ContextImpl(  749): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  749): prevTemp = 279, currTemp = 279, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  749): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  749): prevTemp = 279, currTemp = 279, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP(  749): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,W/ContextImpl(  749): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  240): DCD ON
,E/Watchdog(  749): !@Sync 14
,E/SMD     (  240): DCD ON
,D/BatteryService(  749): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService(  749): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  749): mCoverManager.getCoverState() : true
,D/BatteryService(  749): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1064): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1064): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1064):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3191): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3191): Disconnected process message: 10
D/BatteryMeterView( 1064): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1064): checkOverflow(288), More:false, Req:false Child:2
,D/AmoledAdjustTimer(  749): prevTemp = 279, currTemp = 278, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  749): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/BatteryService(  749): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:3, charge type:1, power sharing:false
,D/BatteryService(  749): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  749): mCoverManager.getCoverState() : true
,D/BatteryService(  749): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1064): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1064): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1064):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1064): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 3191): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 3191): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1064): checkOverflow(288), More:false, Req:false Child:2
,D/AmoledAdjustTimer(  749): prevTemp = 278, currTemp = 278, prevStep = 4, currStep = 4
,I/PowerManagerService(  749): [PWL] Off : 390s ago
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  749): SIOP:: AP = 300, Delta = 0
,V/AlarmManager(  749): waitForAlarm result :8
,V/AlarmManager(  749): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1064): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1064): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1064): checkOverflow(288), More:false, Req:false Child:2
,W/ContextImpl(  749): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/BatteryService(  749): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:3, charge type:1, power sharing:false
,D/BatteryService(  749): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  749): mCoverManager.getCoverState() : true
,D/BatteryService(  749): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1064): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1064): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1064):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1064): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 3191): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 3191): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1064): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  749): prevTemp = 278, currTemp = 278, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP(  749): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,E/Watchdog(  749): !@Sync 15
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  749): prevTemp = 278, currTemp = 278, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  749): SIOP:: AP = 300, Delta = 0
,W/ContextImpl(  749): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/BatteryService(  749): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:5, charge type:1, power sharing:false
,D/BatteryService(  749): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  749): mCoverManager.getCoverState() : true
,D/BatteryService(  749): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1064): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1064): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1064):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3191): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3191): Disconnected process message: 10
D/BatteryMeterView( 1064): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1064): checkOverflow(288), More:false, Req:false Child:2
,D/AmoledAdjustTimer(  749): prevTemp = 278, currTemp = 277, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  749): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/BatteryService(  749): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:4, charge type:1, power sharing:false
,D/BatteryService(  749): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  749): mCoverManager.getCoverState() : true
,D/BatteryService(  749): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1064): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1064): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1064):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1064): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3191): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3191): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1064): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  749): prevTemp = 277, currTemp = 277, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP(  749): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,W/ContextImpl(  749): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  240): DCD ON
,E/Watchdog(  749): !@Sync 16
,E/SMD     (  240): DCD ON
,D/BatteryService(  749): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:3, charge type:1, power sharing:false
,D/BatteryService(  749): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  749): mCoverManager.getCoverState() : true
,D/BatteryService(  749): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1064): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1064): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1064):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3191): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3191): Disconnected process message: 10
D/BatteryMeterView( 1064): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1064): checkOverflow(288), More:false, Req:false Child:2
,D/AmoledAdjustTimer(  749): prevTemp = 277, currTemp = 277, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  749): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/BatteryService(  749): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  749): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  749): stay LED for fully charged
,D/UiModeManager(  749): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1064): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1064): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1064):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1064): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 3191): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 3191): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1064): checkOverflow(288), More:false, Req:false Child:2
,D/AmoledAdjustTimer(  749): prevTemp = 277, currTemp = 277, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,V/AlarmManager(  749): waitForAlarm result :8
,V/AlarmManager(  749): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1064): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1064): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1064): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  749): SIOP:: AP = 300, Delta = 0
,W/ContextImpl(  749): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  240): DCD ON
,I/PowerManagerService(  749): [PWL] Off : 455s ago
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/BatteryService(  749): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  749): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  749): stay LED for fully charged
,D/UiModeManager(  749): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1064): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1064): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1064):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3191): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3191): Disconnected process message: 10
D/BatteryMeterView( 1064): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer(  749): prevTemp = 277, currTemp = 277, prevStep = 4, currStep = 4
,D/STATUSBAR-IconMerger( 1064): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  749): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,E/Watchdog(  749): !@Sync 17
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  749): prevTemp = 277, currTemp = 277, prevStep = 4, currStep = 4
,D/BatteryService(  749): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-1, charge type:1, power sharing:false
,D/BatteryService(  749): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  749): stay LED for fully charged
,D/UiModeManager(  749): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1064): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1064): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1064):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1064): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 3191): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 3191): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1064): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  749): SIOP:: AP = 300, Delta = 0
,W/ContextImpl(  749): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  749): prevTemp = 277, currTemp = 277, prevStep = 4, currStep = 4
,D/BatteryService(  749): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:6, charge type:1, power sharing:false
,D/BatteryService(  749): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  749): mCoverManager.getCoverState() : true
,D/BatteryService(  749): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1064): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1064): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1064):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1064): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3191): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3191): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1064): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  749): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  749): prevTemp = 277, currTemp = 276, prevStep = 4, currStep = 4
,D/BatteryService(  749): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:8, charge type:1, power sharing:false
,D/BatteryService(  749): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  749): mCoverManager.getCoverState() : true
,D/BatteryService(  749): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1064): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1064): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1064):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3191): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3191): Disconnected process message: 10
D/BatteryMeterView( 1064): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1064): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  749): SIOP:: AP = 300, Delta = 0
,W/ContextImpl(  749): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  240): DCD ON
,E/Watchdog(  749): !@Sync 18
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  749): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,D/BatteryService(  749): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:5, charge type:1, power sharing:false
,D/BatteryService(  749): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  749): mCoverManager.getCoverState() : true
,D/BatteryService(  749): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1064): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1064): handleBatteryUpdate
,V/HeadsetService( 3191): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1064):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/HeadsetStateMachine( 3191): Disconnected process message: 10
D/BatteryMeterView( 1064): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1064): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  749): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  749): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,D/BatteryService(  749): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:8, charge type:1, power sharing:false
,D/BatteryService(  749): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  749): mCoverManager.getCoverState() : true
,D/BatteryService(  749): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1064): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1064): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1064):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1064): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 3191): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 3191): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1064): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,V/AlarmManager(  749): waitForAlarm result :8
,V/AlarmManager(  749): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1064): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1064): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1064): checkOverflow(288), More:false, Req:false Child:2
,W/ContextImpl(  749): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/SSRMv2:SIOP(  749): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  749): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  749): SIOP:: AP = 300, Delta = 0
,I/PowerManagerService(  749): [PWL] Off : 525s ago
,E/SMD     (  240): DCD ON
,E/Watchdog(  749): !@Sync 19
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  749): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,D/BatteryService(  749): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:10, charge type:1, power sharing:false
,D/BatteryService(  749): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  749): mCoverManager.getCoverState() : true
,D/BatteryService(  749): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1064): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1064): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1064):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3191): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3191): Disconnected process message: 10
D/BatteryMeterView( 1064): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1064): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,W/ContextImpl(  749): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/SSRMv2:SIOP(  749): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  749): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,D/BatteryService(  749): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:2, charge type:1, power sharing:false
,D/BatteryService(  749): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  749): stay LED for fully charged
,D/UiModeManager(  749): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1064): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1064): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1064):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1064): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 3191): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 3191): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1064): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  749): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  749): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,D/BatteryService(  749): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService(  749): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  749): stay LED for fully charged
,D/UiModeManager(  749): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1064): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1064): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1064):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3191): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/BatteryMeterView( 1064): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/HeadsetStateMachine( 3191): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1064): checkOverflow(288), More:false, Req:false Child:2
,D/TimaService(  749): TIMA: TimaService scheduler is intialized. 
,D/TimaService(  749): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService(  749): TimaServiceHandler.handleMessage what =1
,E/SMD     (  240): DCD ON
,W/ContextImpl(  749): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/SSRMv2:SIOP(  749): SIOP:: AP = 300, Delta = 0
,I/TLC_TIMA_PKM_measure_kernel(  749): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel(  749): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService(  749): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService(  749): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/SMD     (  240): DCD ON
,E/Watchdog(  749): !@Sync 20
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  749): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,D/BatteryService(  749): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  749): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  749): mCoverManager.getCoverState() : true
,D/BatteryService(  749): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1064): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1064): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1064):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1064): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 3191): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 3191): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1064): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  749): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  749): prevTemp = 276, currTemp = 275, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,V/AlarmManager(  749): waitForAlarm result :8
,V/AlarmManager(  749): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1064): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1064): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1064): checkOverflow(288), More:false, Req:false Child:2
,W/ContextImpl(  749): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/SSRMv2:SIOP(  749): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  749): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,D/BatteryService(  749): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  749): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  749): mCoverManager.getCoverState() : true
,E/SMD     (  240): DCD ON
,D/KeyguardUpdateMonitor( 1064): received broadcast android.intent.action.BATTERY_CHANGED
,D/BatteryService(  749): stay LED for fully charged
D/KeyguardUpdateMonitor( 1064): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1064):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3191): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3191): Disconnected process message: 10
D/BatteryMeterView( 1064): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1064): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  749): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,E/Watchdog(  749): !@Sync 21
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  749): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,D/BatteryService(  749): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:5, charge type:1, power sharing:false
,D/BatteryService(  749): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  749): mCoverManager.getCoverState() : true
,D/BatteryService(  749): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1064): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1064): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1064):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3191): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/BatteryMeterView( 1064): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/HeadsetStateMachine( 3191): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1064): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  749): SIOP:: AP = 300, Delta = 0
,D/dalvikvm(  749): GC_CONCURRENT freed 3513K, 59% free 23642K/57632K, paused 36ms+39ms, total 515ms
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  749): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,I/PowerManagerService(  749): [PWL] Off : 600s ago
,E/SMD     (  240): DCD ON
,D/BatteryService(  749): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:6, charge type:1, power sharing:false
,D/BatteryService(  749): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  749): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1064): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1064): handleBatteryUpdate
D/BatteryService(  749): stay LED for fully charged
,V/HeadsetService( 3191): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1064):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/HeadsetStateMachine( 3191): Disconnected process message: 10
D/BatteryMeterView( 1064): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1064): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  749): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  749): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,D/BatteryService(  749): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:4, charge type:1, power sharing:false
,D/BatteryService(  749): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1064): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1064): handleBatteryUpdate
D/BatteryService(  749): stay LED for fully charged
,D/UiModeManager(  749): mCoverManager.getCoverState() : true
,D/STATUSBAR-PhoneStatusBar( 1064):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1064): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3191): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3191): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1064): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  749): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,E/Watchdog(  749): !@Sync 22
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  749): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,D/BatteryService(  749): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:5, charge type:1, power sharing:false
,D/BatteryService(  749): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  749): stay LED for fully charged
,D/UiModeManager(  749): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1064): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1064): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1064):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1064): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3191): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3191): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1064): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  749): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  749): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,V/AlarmManager(  749): waitForAlarm result :8
,V/AlarmManager(  749): ClockReceiver onReceive() ACTION_TIME_TICK
,V/AlarmManager(  749): ___SyncScheduler (v3) ACTIVATED___
,V/AlarmManager(  749): <AppSync3 Whitelist>
,V/AlarmManager(  749): (AppSync) ### 0 added ###
D/KeyguardUpdateMonitor( 1064): received broadcast android.intent.action.TIME_TICK
D/KeyguardUpdateMonitor( 1064): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1064): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  749): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  749): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,D/BatteryService(  749): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:5, charge type:1, power sharing:false
,D/BatteryService(  749): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  749): stay LED for fully charged
,D/UiModeManager(  749): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1064): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1064): handleBatteryUpdate
,V/HeadsetService( 3191): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1064):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/HeadsetStateMachine( 3191): Disconnected process message: 10
D/BatteryMeterView( 1064): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1064): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  749): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,E/Watchdog(  749): !@Sync 23
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  749): prevTemp = 275, currTemp = 274, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,D/BatteryService(  749): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  749): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  749): mCoverManager.getCoverState() : true
,D/BatteryService(  749): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1064): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1064): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1064):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1064): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 3191): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 3191): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1064): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  749): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  749): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  749): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  749): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  749): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,E/Watchdog(  749): !@Sync 24
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  749): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,I/PowerManagerService(  749): [PWL] Off : 680s ago
,E/SMD     (  240): DCD ON
,D/BatteryService(  749): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:9, charge type:1, power sharing:false
,D/BatteryService(  749): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  749): stay LED for fully charged
,D/UiModeManager(  749): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1064): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1064): handleBatteryUpdate
,D/SSRMv2:SIOP(  749): SIOP:: AP = 300, Delta = 0
,D/STATUSBAR-PhoneStatusBar( 1064):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1064): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 3191): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 3191): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1064): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  749): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,V/AlarmManager(  749): waitForAlarm result :8
,V/AlarmManager(  749): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1064): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1064): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1064): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  749): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  749): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,D/BatteryService(  749): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:10, charge type:1, power sharing:false
,D/BatteryService(  749): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  749): mCoverManager.getCoverState() : true
,D/BatteryService(  749): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1064): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1064): handleBatteryUpdate
,D/SSRMv2:SIOP(  749): SIOP:: AP = 300, Delta = 0
,D/STATUSBAR-PhoneStatusBar( 1064):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1064): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3191): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3191): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1064): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,E/Watchdog(  749): !@Sync 25
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  749): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,D/BatteryService(  749): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService(  749): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  749): stay LED for fully charged
,D/UiModeManager(  749): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1064): received broadcast android.intent.action.BATTERY_CHANGED,
,D/KeyguardUpdateMonitor( 1064): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1064):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1064): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3191): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3191): Disconnected process message: 10
D/SSRMv2:SIOP(  749): SIOP:: AP = 300, Delta = 0
,D/STATUSBAR-IconMerger( 1064): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  749): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/BatteryService(  749): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:2, charge type:1, power sharing:false
,D/BatteryService(  749): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  749): stay LED for fully charged
,D/UiModeManager(  749): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1064): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1064): handleBatteryUpdate
,D/SSRMv2:SIOP(  749): SIOP:: AP = 300, Delta = 0
,D/STATUSBAR-PhoneStatusBar( 1064):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1064): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3191): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3191): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1064): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  749): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  749): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,E/Watchdog(  749): !@Sync 26
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  749): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,D/BatteryService(  749): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  749): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  749): stay LED for fully charged
,D/UiModeManager(  749): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1064): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1064): handleBatteryUpdate
,D/SSRMv2:SIOP(  749): SIOP:: AP = 300, Delta = 0
,D/STATUSBAR-PhoneStatusBar( 1064):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1064): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3191): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3191): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1064): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  749): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,V/AlarmManager(  749): waitForAlarm result :8
,V/AlarmManager(  749): ClockReceiver onReceive() ACTION_TIME_TICK
D/KeyguardUpdateMonitor( 1064): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1064): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1064): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,D/BatteryService(  749): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  749): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  749): mCoverManager.getCoverState() : true
,D/BatteryService(  749): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1064): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1064): handleBatteryUpdate
,D/SSRMv2:SIOP(  749): SIOP:: AP = 300, Delta = 0
,D/STATUSBAR-PhoneStatusBar( 1064):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1064): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3191): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3191): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1064): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  749): prevTemp = 274, currTemp = 273, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  749): SIOP:: AP = 300, Delta = 0
,I/PowerManagerService(  749): [PWL] Off : 765s ago
,E/SMD     (  240): DCD ON
,E/Watchdog(  749): !@Sync 27
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  749): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,D/BatteryService(  749): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-1, charge type:1, power sharing:false
,D/BatteryService(  749): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  749): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1064): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1064): handleBatteryUpdate
D/BatteryService(  749): stay LED for fully charged
,D/SSRMv2:SIOP(  749): SIOP:: AP = 300, Delta = 0
,D/STATUSBAR-PhoneStatusBar( 1064):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1064): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3191): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3191): Disconnected process message: 10
D/STATUSBAR-IconMerger( 1064): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  749): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,D/BatteryService(  749): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-2, charge type:1, power sharing:false
,D/BatteryService(  749): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  749): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1064): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1064): handleBatteryUpdate
D/BatteryService(  749): stay LED for fully charged
,D/SSRMv2:SIOP(  749): SIOP:: AP = 300, Delta = 0
,D/STATUSBAR-PhoneStatusBar( 1064):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3191): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3191): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1064): checkOverflow(288), More:false, Req:false Child:2
,D/BatteryMeterView( 1064): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  749): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,D/BatteryService(  749): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:6, charge type:1, power sharing:false
,D/BatteryService(  749): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  749): stay LED for fully charged
,D/UiModeManager(  749): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1064): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1064): handleBatteryUpdate
,D/SSRMv2:SIOP(  749): SIOP:: AP = 300, Delta = 0
,D/STATUSBAR-PhoneStatusBar( 1064):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3191): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3191): Disconnected process message: 10
D/BatteryMeterView( 1064): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1064): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,E/Watchdog(  749): !@Sync 28
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  749): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/BatteryService(  749): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  749): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  749): stay LED for fully charged
,D/UiModeManager(  749): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1064): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1064): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1064):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3191): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3191): Disconnected process message: 10
D/BatteryMeterView( 1064): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SSRMv2:SIOP(  749): SIOP:: AP = 300, Delta = 0
,D/STATUSBAR-IconMerger( 1064): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  749): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,V/AlarmManager(  749): waitForAlarm result :8
,V/AlarmManager(  749): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1064): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1064): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1064): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,D/BatteryService(  749): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService(  749): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  749): stay LED for fully charged
,D/UiModeManager(  749): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1064): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1064): handleBatteryUpdate
,D/SSRMv2:SIOP(  749): SIOP:: AP = 300, Delta = 0
,D/STATUSBAR-PhoneStatusBar( 1064):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1064): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1064): checkOverflow(288), More:false, Req:false Child:2
,V/HeadsetService( 3191): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3191): Disconnected process message: 10
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  749): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,D/BatteryService(  749): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:2, charge type:1, power sharing:false
,D/BatteryService(  749): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  749): stay LED for fully charged
,D/UiModeManager(  749): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1064): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1064): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1064):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/SSRMv2:SIOP(  749): SIOP:: AP = 300, Delta = 0
,D/STATUSBAR-IconMerger( 1064): checkOverflow(288), More:false, Req:false Child:2
,D/BatteryMeterView( 1064): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3191): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3191): Disconnected process message: 10
,E/SMD     (  240): DCD ON
,E/Watchdog(  749): !@Sync 29
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  749): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/BatteryService(  749): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:4, charge type:1, power sharing:false
,D/BatteryService(  749): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  749): stay LED for fully charged
,D/UiModeManager(  749): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1064): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1064): handleBatteryUpdate
,D/SSRMv2:SIOP(  749): SIOP:: AP = 300, Delta = 0
,D/STATUSBAR-PhoneStatusBar( 1064):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1064): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3191): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3191): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1064): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  749): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,D/BatteryService(  749): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  749): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  749): stay LED for fully charged
,D/UiModeManager(  749): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1064): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1064): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1064):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1064): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3191): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3191): Disconnected process message: 10
D/SSRMv2:SIOP(  749): SIOP:: AP = 300, Delta = 0
,D/STATUSBAR-IconMerger( 1064): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  749): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,D/TimaService(  749): TIMA: TimaService scheduler is intialized. 
,D/TimaService(  749): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService(  749): TimaServiceHandler.handleMessage what =1
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  749): SIOP:: AP = 300, Delta = 0
,I/TLC_TIMA_PKM_measure_kernel(  749): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel(  749): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService(  749): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService(  749): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,I/PowerManagerService(  749): [PWL] Off : 855s ago
,E/SMD     (  240): DCD ON
,E/Watchdog(  749): !@Sync 30
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  749): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/BatteryService(  749): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-3, charge type:1, power sharing:false
,D/BatteryService(  749): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  749): stay LED for fully charged
,D/UiModeManager(  749): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1064): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1064): handleBatteryUpdate
,D/SSRMv2:SIOP(  749): SIOP:: AP = 300, Delta = 0
,D/STATUSBAR-PhoneStatusBar( 1064):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1064): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3191): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3191): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1064): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  749): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,V/AlarmManager(  749): waitForAlarm result :8
,V/AlarmManager(  749): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1064): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1064): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1064): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,D/BatteryService(  749): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-1, charge type:1, power sharing:false
,D/BatteryService(  749): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  749): stay LED for fully charged
,D/UiModeManager(  749): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1064): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1064): handleBatteryUpdate
,D/SSRMv2:SIOP(  749): SIOP:: AP = 300, Delta = 0
,D/STATUSBAR-PhoneStatusBar( 1064):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1064): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3191): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3191): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1064): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  749): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,D/BatteryService(  749): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  749): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  749): stay LED for fully charged
,D/UiModeManager(  749): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1064): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1064): handleBatteryUpdate
,D/SSRMv2:SIOP(  749): SIOP:: AP = 300, Delta = 0
,D/STATUSBAR-PhoneStatusBar( 1064):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1064): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3191): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3191): Disconnected process message: 10
,E/SMD     (  240): DCD ON
D/STATUSBAR-IconMerger( 1064): checkOverflow(288), More:false, Req:false Child:2
,E/Watchdog(  749): !@Sync 31
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  749): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  749): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  749): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,D/BatteryService(  749): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:3, charge type:1, power sharing:false
,D/BatteryService(  749): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  749): mCoverManager.getCoverState() : true
,D/BatteryService(  749): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1064): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1064): handleBatteryUpdate
,D/SSRMv2:SIOP(  749): SIOP:: AP = 300, Delta = 0
,D/STATUSBAR-PhoneStatusBar( 1064):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1064): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3191): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3191): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1064): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  749): prevTemp = 273, currTemp = 272, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/BatteryService(  749): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:4, charge type:1, power sharing:false
,D/BatteryService(  749): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  749): stay LED for fully charged
,D/UiModeManager(  749): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1064): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1064): handleBatteryUpdate
,V/HeadsetService( 3191): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/SSRMv2:SIOP(  749): SIOP:: AP = 300, Delta = 0
,D/STATUSBAR-PhoneStatusBar( 1064):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/HeadsetStateMachine( 3191): Disconnected process message: 10
D/BatteryMeterView( 1064): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1064): checkOverflow(288), More:false, Req:false Child:2
,E/Watchdog(  749): !@Sync 32
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  749): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/BatteryService(  749): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  749): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  749): stay LED for fully charged
,D/UiModeManager(  749): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1064): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1064): handleBatteryUpdate
,D/SSRMv2:SIOP(  749): SIOP:: AP = 300, Delta = 0
,D/STATUSBAR-PhoneStatusBar( 1064):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
D/BatteryMeterView( 1064): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 3191): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3191): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1064): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  749): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,V/AlarmManager(  749): waitForAlarm result :8
,V/AlarmManager(  749): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1064): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1064): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1064): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,D/BatteryService(  749): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService(  749): stay LED for fully charged
,D/BatteryService(  749): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  749): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1064): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1064): handleBatteryUpdate
,V/HeadsetService( 3191): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1064):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/HeadsetStateMachine( 3191): Disconnected process message: 10
D/BatteryMeterView( 1064): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP(  749): SIOP:: AP = 300, Delta = 0
,D/STATUSBAR-IconMerger( 1064): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  749): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/BatteryService(  749): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:2, charge type:1, power sharing:false
,D/BatteryService(  749): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  749): mCoverManager.getCoverState() : true
,D/BatteryService(  749): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1064): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1064): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1064):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3191): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3191): Disconnected process message: 10
D/BatteryMeterView( 1064): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1064): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  749): SIOP:: AP = 300, Delta = 0
,E/Watchdog(  749): !@Sync 33
,E/SMD     (  240): DCD ON
,I/PowerManagerService(  749): [PWL] Off : 950s ago
,D/AmoledAdjustTimer(  749): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/BatteryService(  749): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  749): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  749): mCoverManager.getCoverState() : true
,D/BatteryService(  749): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1064): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1064): handleBatteryUpdate
,V/HeadsetService( 3191): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1064):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/HeadsetStateMachine( 3191): Disconnected process message: 10
D/BatteryMeterView( 1064): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP(  749): SIOP:: AP = 300, Delta = 0
,D/STATUSBAR-IconMerger( 1064): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  749): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  749): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,V/AlarmManager(  749): waitForAlarm result :4
,I/SensorManagerA(  749): getReportingMode :: sensor.mType = 5
,D/Sensors (  749): LightSensor setDelay = 200000000
,D/Sensors (  749): LightSensor setSensorDelay = 200000000
,D/Sensors (  749): Light sensor flush: not enabled 0
,D/LightsService(  749): [api] onReceive : SvcLEDReceiver re-enables LightSenor and sends MSG_FORCEDSVCLEDTASK
D/Sensors (  749): LightSensor enable = 1
D/Sensors (  749): LightSensor enableSensor = 1
D/SensorManager(  749): registerListener :: 16, CM36686 Light Sensor, 200000, 0,  
,V/AlarmManager(  749): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,D/AmoledAdjustTimer(  749): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,D/Sensors (  749): LightSensor enable = 0
,D/Sensors (  749): LightSensor enableSensor = 0
,D/LightsService(  749): [SvcLED]  onSensorChanged::light value = 0
,D/SensorManager(  749): unregisterListener ::   
D/LightsService(  749): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,D/ConnectivityService(  749): handleInetConditionHoldEnd: net=1, condition=100, published condition=100
,D/STATUSBAR-NetworkController_dual( 1064): onReceive() - CONNECTIVITY_ACTION, INET_CONDITION_ACTION
,D/StatusBar.NetworkController_dual( 1064): mMobileLabelViews start
,D/StatusBar.NetworkController_dual( 1064): mMobileLabelViews set mobileLabel[SIM_0] =
D/StatusBar.NetworkController_dual( 1064): mMobileLabelViews GONE
,D/StatusBar.NetworkController_dual( 1064): mMobileLabelViews2 set mobileLabel[SIM_1] =
,D/StatusBar.NetworkController_dual( 1064): mMobileLabelViews2 GONE
,D/StatusBar.NetworkController_dual( 1064): mSingleMobileLabelViews set : simMode = 0
,D/StatusBar.NetworkController_dual( 1064): mSingleMobileLabelViews set as slot1`s
,I/PhenotypeConfigurator( 1216): Scheduling Phenotype for one-off execution 7749 seconds from now (1450202619627)
,D/GetConfigurationSnapshotOperation( 1216): no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,I/PhenotypeFlagCommitter( 1216): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,W/dalvikvm( 1216): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 1216): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 1216): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,I/dalvikvm( 1216): Could not find method android.net.Network.openConnection, referenced from method com.google.android.gms.http.g.a
W/dalvikvm( 1216): VFY: unable to resolve virtual method 1007: Landroid/net/Network;.openConnection (Ljava/net/URL;)Ljava/net/URLConnection;
,D/dalvikvm( 1216): VFY: replacing opcode 0x6e at 0x00bb
,I/GoogleURLConnFactory( 1216): Using platform SSLCertificateSocketFactory
,D/LocationManagerService(  749): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,I/dalvikvm( 1216): Could not find method android.os.PowerManager.isInteractive, referenced from method com.google.android.gms.common.util.y.a
,W/dalvikvm( 1216): VFY: unable to resolve virtual method 1378: Landroid/os/PowerManager;.isInteractive ()Z
,D/dalvikvm( 1216): VFY: replacing opcode 0x6e at 0x003d
,I/System.out( 1216): Thread-108(HTTPLog):isShipBuild true
,I/System.out( 1216): Thread-108(HTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,D/dalvikvm( 1216): GC_CONCURRENT freed 1477K, 36% free 11838K/18408K, paused 6ms+10ms, total 79ms
,D/LocationManagerService(  749): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,E/SMD     (  240): DCD ON
,D/LocationManagerService(  749): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/LocationManagerService(  749): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  749): SIOP:: AP = 300, Delta = 0
,D/dalvikvm(  749): GC_CONCURRENT freed 3474K, 60% free 23603K/57632K, paused 21ms+37ms, total 410ms
,E/Watchdog(  749): !@Sync 34
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  749): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,D/BatteryService(  749): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  749): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  749): stay LED for fully charged
,D/UiModeManager(  749): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1064): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1064): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1064):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1064): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3191): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3191): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1064): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  749): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  749): prevTemp = 272, currTemp = 273, prevStep = 4, currStep = 4
,V/AlarmManager(  749): waitForAlarm result :8
,V/AlarmManager(  749): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1064): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1064): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1064): checkOverflow(288), More:false, Req:false Child:2
,D/BatteryService(  749): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-1, charge type:1, power sharing:false
,D/BatteryService(  749): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  749): stay LED for fully charged
,D/UiModeManager(  749): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 1064): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1064): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1064):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3191): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3191): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1064): checkOverflow(288), More:false, Req:false Child:2
,D/BatteryMeterView( 1064): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  749): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  749): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,D/BatteryService(  749): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  749): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  749): stay LED for fully charged
,D/UiModeManager(  749): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1064): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1064): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1064):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1064): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3191): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3191): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1064): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  749): SIOP:: AP = 300, Delta = 0
,E/Watchdog(  749): !@Sync 35
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  749): prevTemp = 273, currTemp = 272, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,D/BatteryService(  749): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  749): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  749): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1064): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1064): handleBatteryUpdate
D/UiModeManager(  749): mCoverManager.getCoverState() : true
,D/STATUSBAR-PhoneStatusBar( 1064):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1064): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 3191): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 3191): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1064): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  749): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  749): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,D/BatteryService(  749): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:4, charge type:1, power sharing:false
,D/BatteryService(  749): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  749): stay LED for fully charged
,D/UiModeManager(  749): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1064): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1064): handleBatteryUpdate
,V/HeadsetService( 3191): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1064):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/HeadsetStateMachine( 3191): Disconnected process message: 10
D/BatteryMeterView( 1064): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1064): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  749): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  749): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,D/BatteryService(  749): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:3, charge type:1, power sharing:false
,D/BatteryService(  749): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  749): stay LED for fully charged
,D/UiModeManager(  749): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1064): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1064): handleBatteryUpdate
,V/HeadsetService( 3191): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1064):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/HeadsetStateMachine( 3191): Disconnected process message: 10
D/BatteryMeterView( 1064): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1064): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  749): SIOP:: AP = 300, Delta = 0
,E/Watchdog(  749): !@Sync 36
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  749): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  749): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,I/PowerManagerService(  749): [PWL] Off : 1050s ago
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  749): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,V/AlarmManager(  749): waitForAlarm result :8
,V/AlarmManager(  749): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1064): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1064): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1064): checkOverflow(288), More:false, Req:false Child:2
,D/BatteryService(  749): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  749): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  749): stay LED for fully charged
,D/UiModeManager(  749): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1064): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1064): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1064):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1064): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 3191): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 3191): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1064): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  749): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  749): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,D/BatteryService(  749): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:3, charge type:1, power sharing:false
,D/BatteryService(  749): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  749): mCoverManager.getCoverState() : true
,D/BatteryService(  749): stay LED for fully charged
D/KeyguardUpdateMonitor( 1064): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1064): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1064):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1064): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3191): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3191): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1064): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  749): SIOP:: AP = 300, Delta = 0
,E/Watchdog(  749): !@Sync 37
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  749): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,D/BatteryService(  749): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  749): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  749): stay LED for fully charged
,D/UiModeManager(  749): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1064): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1064): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1064):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1064): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 3191): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 3191): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1064): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  749): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  749): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,D/BatteryService(  749): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-3, charge type:1, power sharing:false
,D/BatteryService(  749): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  749): stay LED for fully charged
,D/UiModeManager(  749): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1064): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1064): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1064):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1064): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 3191): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 3191): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1064): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  749): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  749): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,D/BatteryService(  749): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-1, charge type:1, power sharing:false
,D/BatteryService(  749): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  749): stay LED for fully charged
,D/UiModeManager(  749): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1064): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1064): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1064):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3191): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3191): Disconnected process message: 10
D/BatteryMeterView( 1064): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1064): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  749): SIOP:: AP = 300, Delta = 0
,E/Watchdog(  749): !@Sync 38
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  749): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,D/BatteryService(  749): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-3, charge type:1, power sharing:false
,D/BatteryService(  749): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  749): stay LED for fully charged
,D/UiModeManager(  749): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1064): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1064): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1064):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1064): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 3191): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 3191): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1064): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  749): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  749): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,V/AlarmManager(  749): waitForAlarm result :8
,V/AlarmManager(  749): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1064): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1064): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1064): checkOverflow(288), More:false, Req:false Child:2
,D/BatteryService(  749): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-3, charge type:1, power sharing:false
,D/BatteryService(  749): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  749): stay LED for fully charged
,D/UiModeManager(  749): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1064): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1064): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1064):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1064): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 3191): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 3191): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1064): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  749): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  749): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,D/BatteryService(  749): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-1, charge type:1, power sharing:false
,D/BatteryService(  749): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  749): mCoverManager.getCoverState() : true
,D/BatteryService(  749): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1064): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1064): handleBatteryUpdate
,V/HeadsetService( 3191): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1064):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1064): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/HeadsetStateMachine( 3191): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1064): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  749): SIOP:: AP = 300, Delta = 0
,E/Watchdog(  749): !@Sync 39
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  749): prevTemp = 272, currTemp = 271, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  749): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  749): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,D/BatteryService(  749): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:2, charge type:1, power sharing:false
,D/BatteryService(  749): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  749): stay LED for fully charged
,D/UiModeManager(  749): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1064): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1064): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1064):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3191): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/BatteryMeterView( 1064): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/HeadsetStateMachine( 3191): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1064): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  749): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  749): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,D/TimaService(  749): TIMA: TimaService scheduler is intialized. 
,D/TimaService(  749): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService(  749): TimaServiceHandler.handleMessage what =1
,E/SMD     (  240): DCD ON
,D/BatteryService(  749): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  749): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  749): mCoverManager.getCoverState() : true
,D/BatteryService(  749): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1064): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1064): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1064):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1064): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3191): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3191): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1064): checkOverflow(288), More:false, Req:false Child:2
,I/TLC_TIMA_PKM_measure_kernel(  749): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel(  749): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService(  749): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService(  749): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,I/PowerManagerService(  749): [PWL] Off : 1155s ago
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  749): SIOP:: AP = 300, Delta = 0
,E/Watchdog(  749): !@Sync 40
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  749): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,D/BatteryService(  749): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService(  749): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  749): stay LED for fully charged
,D/UiModeManager(  749): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1064): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1064): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1064):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3191): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3191): Disconnected process message: 10
D/BatteryMeterView( 1064): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1064): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  749): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  749): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,V/AlarmManager(  749): waitForAlarm result :8
,V/AlarmManager(  749): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1064): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1064): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1064): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,D/BatteryService(  749): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  749): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  749): mCoverManager.getCoverState() : true
,D/BatteryService(  749): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1064): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1064): handleBatteryUpdate
,V/HeadsetService( 3191): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1064):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/HeadsetStateMachine( 3191): Disconnected process message: 10
D/BatteryMeterView( 1064): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1064): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  749): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  749): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,E/Watchdog(  749): !@Sync 41
,D/SSRMv2:SIOP(  749): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  749): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  749): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  749): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,D/BatteryService(  749): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:2, charge type:1, power sharing:false
,D/BatteryService(  749): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  749): mCoverManager.getCoverState() : true
,D/BatteryService(  749): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1064): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1064): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1064):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1064): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 3191): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 3191): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1064): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  749): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  749): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,D/BatteryService(  749): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  749): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  749): mCoverManager.getCoverState() : true
,D/BatteryService(  749): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1064): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1064): handleBatteryUpdate
,V/HeadsetService( 3191): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1064):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/HeadsetStateMachine( 3191): Disconnected process message: 10
D/BatteryMeterView( 1064): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1064): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,E/Watchdog(  749): !@Sync 42
,D/SSRMv2:SIOP(  749): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  749): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/BatteryService(  749): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:5, charge type:1, power sharing:false
,D/BatteryService(  749): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  749): mCoverManager.getCoverState() : true
,D/BatteryService(  749): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1064): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1064): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1064):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3191): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3191): Disconnected process message: 10
D/BatteryMeterView( 1064): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1064): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  749): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  749): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,V/AlarmManager(  749): waitForAlarm result :8
,V/AlarmManager(  749): ClockReceiver onReceive() ACTION_TIME_TICK
,V/AlarmManager(  749): ___SyncScheduler (v3) ACTIVATED___
,V/AlarmManager(  749): <AppSync3 Whitelist>
,D/KeyguardUpdateMonitor( 1064): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1064): handleTimeUpdate
V/AlarmManager(  749): (AppSync) ### 0 added ###
,D/STATUSBAR-IconMerger( 1064): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,D/BatteryService(  749): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:5, charge type:1, power sharing:false
,D/BatteryService(  749): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  749): stay LED for fully charged
,D/UiModeManager(  749): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1064): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1064): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1064):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1064): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 3191): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 3191): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1064): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  749): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  749): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,D/BatteryService(  749): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:4, charge type:1, power sharing:false
,D/BatteryService(  749): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  749): stay LED for fully charged
,D/UiModeManager(  749): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1064): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1064): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1064):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3191): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3191): Disconnected process message: 10
D/BatteryMeterView( 1064): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1064): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,E/Watchdog(  749): !@Sync 43
,D/SSRMv2:SIOP(  749): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  749): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/BatteryService(  749): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:3, charge type:1, power sharing:false
,D/BatteryService(  749): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  749): stay LED for fully charged
,D/UiModeManager(  749): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1064): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1064): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1064):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1064): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 3191): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 3191): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1064): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  749): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  749): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,I/PowerManagerService(  749): [PWL] Off : 1265s ago
,D/BatteryService(  749): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:4, charge type:1, power sharing:false
,D/BatteryService(  749): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  749): stay LED for fully charged
,D/UiModeManager(  749): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1064): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1064): handleBatteryUpdate
,V/HeadsetService( 3191): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/STATUSBAR-PhoneStatusBar( 1064):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/HeadsetStateMachine( 3191): Disconnected process message: 10
D/BatteryMeterView( 1064): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1064): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  749): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  749): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,D/BatteryService(  749): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:3, charge type:1, power sharing:false
,D/BatteryService(  749): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  749): stay LED for fully charged
,D/UiModeManager(  749): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1064): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1064): handleBatteryUpdate
,V/HeadsetService( 3191): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1064):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/HeadsetStateMachine( 3191): Disconnected process message: 10
D/BatteryMeterView( 1064): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1064): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,E/Watchdog(  749): !@Sync 44
,D/SSRMv2:SIOP(  749): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  749): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/BatteryService(  749): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:10, charge type:1, power sharing:false
,D/BatteryService(  749): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  749): mCoverManager.getCoverState() : true
,D/BatteryService(  749): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1064): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1064): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1064):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1064): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 3191): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 3191): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1064): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  749): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  749): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,V/AlarmManager(  749): waitForAlarm result :8
,V/AlarmManager(  749): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1064): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1064): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1064): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,D/BatteryService(  749): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:10, charge type:1, power sharing:false
,D/BatteryService(  749): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  749): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1064): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1064): handleBatteryUpdate
D/BatteryService(  749): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1064):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1064): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3191): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3191): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1064): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  749): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  749): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/BatteryService(  749): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:5, charge type:1, power sharing:false
,D/BatteryService(  749): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  749): stay LED for fully charged
,D/UiModeManager(  749): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1064): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1064): handleBatteryUpdate
,V/HeadsetService( 3191): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1064):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/HeadsetStateMachine( 3191): Disconnected process message: 10
D/BatteryMeterView( 1064): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1064): checkOverflow(288), More:false, Req:false Child:2
,E/Watchdog(  749): !@Sync 45
,D/SSRMv2:SIOP(  749): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  749): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/BatteryService(  749): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:4, charge type:1, power sharing:false
,D/BatteryService(  749): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  749): stay LED for fully charged
,D/UiModeManager(  749): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1064): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1064): handleBatteryUpdate
,V/HeadsetService( 3191): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1064):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1064): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/HeadsetStateMachine( 3191): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1064): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  749): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  749): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,D/BatteryService(  749): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:5, charge type:1, power sharing:false
,D/BatteryService(  749): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  749): mCoverManager.getCoverState() : true
,D/BatteryService(  749): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1064): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1064): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1064):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3191): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3191): Disconnected process message: 10
D/BatteryMeterView( 1064): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1064): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  749): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  749): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/BatteryService(  749): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:5, charge type:1, power sharing:false
,D/BatteryService(  749): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  749): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1064): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1064): handleBatteryUpdate
D/BatteryService(  749): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1064):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1064): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3191): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3191): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1064): checkOverflow(288), More:false, Req:false Child:2
,E/Watchdog(  749): !@Sync 46
,D/SSRMv2:SIOP(  749): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  749): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/BatteryService(  749): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-3, charge type:1, power sharing:false
,D/BatteryService(  749): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  749): mCoverManager.getCoverState() : true
,D/BatteryService(  749): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1064): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1064): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1064):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3191): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3191): Disconnected process message: 10
D/BatteryMeterView( 1064): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1064): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  749): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  749): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,V/AlarmManager(  749): waitForAlarm result :8
,V/AlarmManager(  749): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1064): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1064): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1064): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,D/BatteryService(  749): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  749): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  749): stay LED for fully charged
,D/UiModeManager(  749): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1064): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1064): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1064):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1064): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 3191): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 3191): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1064): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  749): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  749): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/BatteryService(  749): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-2, charge type:1, power sharing:false
,D/BatteryService(  749): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  749): stay LED for fully charged
,D/UiModeManager(  749): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1064): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1064): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1064):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1064): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3191): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3191): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1064): checkOverflow(288), More:false, Req:false Child:2
,E/Watchdog(  749): !@Sync 47
,D/SSRMv2:SIOP(  749): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  749): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/BatteryService(  749): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-1, charge type:1, power sharing:false
,D/BatteryService(  749): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  749): stay LED for fully charged
,D/UiModeManager(  749): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1064): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1064): handleBatteryUpdate
,V/HeadsetService( 3191): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1064):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/HeadsetStateMachine( 3191): Disconnected process message: 10
D/BatteryMeterView( 1064): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1064): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  749): SIOP:: AP = 300, Delta = 0
,I/PowerManagerService(  749): [PWL] Off : 1380s ago
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  749): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/BatteryService(  749): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  749): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  749): stay LED for fully charged
,D/UiModeManager(  749): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1064): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1064): handleBatteryUpdate
,V/HeadsetService( 3191): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1064):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/HeadsetStateMachine( 3191): Disconnected process message: 10
D/BatteryMeterView( 1064): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1064): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  749): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  749): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/dalvikvm(  749): GC_CONCURRENT freed 3430K, 60% free 23594K/57632K, paused 20ms+40ms, total 402ms
,E/Watchdog(  749): !@Sync 48
,D/SSRMv2:SIOP(  749): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  749): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/BatteryService(  749): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  749): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  749): stay LED for fully charged
,D/UiModeManager(  749): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1064): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1064): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1064):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1064): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 3191): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 3191): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1064): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  749): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  749): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,V/AlarmManager(  749): waitForAlarm result :8
,V/AlarmManager(  749): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1064): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1064): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1064): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  749): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  749): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,E/Watchdog(  749): !@Sync 49
,D/BatteryService(  749): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:2, charge type:1, power sharing:false
,D/BatteryService(  749): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  749): mCoverManager.getCoverState() : true
,D/BatteryService(  749): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1064): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1064): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1064):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1064): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 3191): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 3191): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1064): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  749): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  749): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/BatteryService(  749): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:5, charge type:1, power sharing:false
,D/BatteryService(  749): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  749): stay LED for fully charged
,D/UiModeManager(  749): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1064): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1064): handleBatteryUpdate
,V/HeadsetService( 3191): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1064):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/HeadsetStateMachine( 3191): Disconnected process message: 10
,E/SMD     (  240): DCD ON
D/BatteryMeterView( 1064): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1064): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  749): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  749): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/BatteryService(  749): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  749): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  749): stay LED for fully charged
,D/UiModeManager(  749): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1064): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1064): handleBatteryUpdate
,V/HeadsetService( 3191): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1064):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/HeadsetStateMachine( 3191): Disconnected process message: 10
D/BatteryMeterView( 1064): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1064): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  749): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,D/TimaService(  749): TIMA: TimaService scheduler is intialized. 
,D/TimaService(  749): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService(  749): TimaServiceHandler.handleMessage what =1
,D/AmoledAdjustTimer(  749): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,I/TLC_TIMA_PKM_measure_kernel(  749): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel(  749): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService(  749): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService(  749): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/SMD     (  240): DCD ON
,E/Watchdog(  749): !@Sync 50
,D/SSRMv2:SIOP(  749): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  749): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  749): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  749): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,V/AlarmManager(  749): waitForAlarm result :8
,V/AlarmManager(  749): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1064): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1064): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1064): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/BatteryService(  749): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  749): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  749): stay LED for fully charged
,D/UiModeManager(  749): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1064): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1064): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1064):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3191): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3191): Disconnected process message: 10
D/BatteryMeterView( 1064): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1064): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  749): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  749): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,E/Watchdog(  749): !@Sync 51
,D/SSRMv2:SIOP(  749): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  749): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/BatteryService(  749): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:3, charge type:1, power sharing:false
,D/BatteryService(  749): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  749): stay LED for fully charged
,D/UiModeManager(  749): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1064): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1064): handleBatteryUpdate
,V/HeadsetService( 3191): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/STATUSBAR-PhoneStatusBar( 1064):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/HeadsetStateMachine( 3191): Disconnected process message: 10
D/BatteryMeterView( 1064): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1064): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  749): SIOP:: AP = 300, Delta = 0
,I/PowerManagerService(  749): [PWL] Off : 1500s ago
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  749): prevTemp = 271, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/BatteryService(  749): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService(  749): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  749): stay LED for fully charged
,D/UiModeManager(  749): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1064): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1064): handleBatteryUpdate
,V/HeadsetService( 3191): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1064):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/HeadsetStateMachine( 3191): Disconnected process message: 10
D/BatteryMeterView( 1064): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1064): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  749): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  749): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,E/Watchdog(  749): !@Sync 52
,D/BatteryService(  749): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:3, charge type:1, power sharing:false
,D/BatteryService(  749): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  749): stay LED for fully charged
,D/UiModeManager(  749): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1064): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1064): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1064):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1064): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 3191): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 3191): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1064): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  749): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  749): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/BatteryService(  749): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:6, charge type:1, power sharing:false
,D/BatteryService(  749): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  749): stay LED for fully charged
,D/UiModeManager(  749): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1064): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1064): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1064):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3191): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3191): Disconnected process message: 10
D/BatteryMeterView( 1064): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1064): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  749): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  749): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,V/AlarmManager(  749): waitForAlarm result :8
,V/AlarmManager(  749): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1064): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1064): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1064): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/BatteryService(  749): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:3, charge type:1, power sharing:false
,D/BatteryService(  749): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  749): mCoverManager.getCoverState() : true
,D/BatteryService(  749): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1064): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1064): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1064):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3191): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3191): Disconnected process message: 10
D/BatteryMeterView( 1064): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1064): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  749): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  749): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,E/Watchdog(  749): !@Sync 53
,E/SMD     (  240): DCD ON
,D/BatteryService(  749): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:5, charge type:1, power sharing:false
,D/BatteryService(  749): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  749): stay LED for fully charged
,D/UiModeManager(  749): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1064): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1064): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1064):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1064): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP(  749): SIOP:: AP = 300, Delta = 0
,V/HeadsetService( 3191): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3191): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1064): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  749): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/BatteryService(  749): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-1, charge type:1, power sharing:false
,D/BatteryService(  749): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  749): mCoverManager.getCoverState() : true
,D/BatteryService(  749): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1064): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1064): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1064):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3191): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3191): Disconnected process message: 10
D/BatteryMeterView( 1064): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SSRMv2:SIOP(  749): SIOP:: AP = 300, Delta = 0
,D/STATUSBAR-IconMerger( 1064): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  749): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/BatteryService(  749): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-1, charge type:1, power sharing:false
,D/BatteryService(  749): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  749): stay LED for fully charged
,D/UiModeManager(  749): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1064): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1064): handleBatteryUpdate
,D/SSRMv2:SIOP(  749): SIOP:: AP = 300, Delta = 0
,D/STATUSBAR-PhoneStatusBar( 1064):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1064): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 3191): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 3191): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1064): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  749): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,E/Watchdog(  749): !@Sync 54
,E/SMD     (  240): DCD ON
,D/BatteryService(  749): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  749): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  749): stay LED for fully charged
,D/UiModeManager(  749): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1064): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1064): handleBatteryUpdate
,D/SSRMv2:SIOP(  749): SIOP:: AP = 300, Delta = 0
,D/STATUSBAR-PhoneStatusBar( 1064):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1064): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3191): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3191): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1064): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  749): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/BatteryService(  749): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-2, charge type:1, power sharing:false
,D/BatteryService(  749): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  749): stay LED for fully charged
,D/UiModeManager(  749): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1064): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1064): handleBatteryUpdate
,D/SSRMv2:SIOP(  749): SIOP:: AP = 300, Delta = 0
,D/STATUSBAR-PhoneStatusBar( 1064):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1064): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3191): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3191): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1064): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,V/AlarmManager(  749): waitForAlarm result :8
,V/AlarmManager(  749): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1064): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1064): handleTimeUpdate
,D/AmoledAdjustTimer(  749): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,D/STATUSBAR-IconMerger( 1064): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  749): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  749): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,E/Watchdog(  749): !@Sync 55
,E/SMD     (  240): DCD ON
,D/BatteryService(  749): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-2, charge type:1, power sharing:false
,D/BatteryService(  749): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  749): stay LED for fully charged
,D/UiModeManager(  749): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1064): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1064): handleBatteryUpdate
,D/SSRMv2:SIOP(  749): SIOP:: AP = 300, Delta = 0
,D/STATUSBAR-PhoneStatusBar( 1064):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1064): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 3191): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 3191): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1064): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  749): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/BatteryService(  749): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:3, charge type:1, power sharing:false
,D/BatteryService(  749): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  749): stay LED for fully charged
,D/UiModeManager(  749): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1064): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1064): handleBatteryUpdate
,D/SSRMv2:SIOP(  749): SIOP:: AP = 300, Delta = 0
,D/STATUSBAR-PhoneStatusBar( 1064):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3191): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3191): Disconnected process message: 10
D/BatteryMeterView( 1064): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1064): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  749): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,I/PowerManagerService(  749): [PWL] Off : 1625s ago
,E/SMD     (  240): DCD ON
,D/BatteryService(  749): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:3, charge type:1, power sharing:false
,D/BatteryService(  749): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  749): stay LED for fully charged
,D/UiModeManager(  749): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1064): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1064): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1064):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1064): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3191): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3191): Disconnected process message: 10
D/SSRMv2:SIOP(  749): SIOP:: AP = 300, Delta = 0
,D/STATUSBAR-IconMerger( 1064): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  749): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,E/Watchdog(  749): !@Sync 56
,E/SMD     (  240): DCD ON
,D/BatteryService(  749): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService(  749): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  749): stay LED for fully charged
,D/UiModeManager(  749): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1064): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1064): handleBatteryUpdate
,D/SSRMv2:SIOP(  749): SIOP:: AP = 300, Delta = 0
,D/STATUSBAR-PhoneStatusBar( 1064):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1064): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3191): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3191): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1064): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  749): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/BatteryService(  749): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  749): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  749): stay LED for fully charged
,D/UiModeManager(  749): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1064): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1064): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1064):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1064): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP(  749): SIOP:: AP = 300, Delta = 0
,V/HeadsetService( 3191): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3191): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1064): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,V/AlarmManager(  749): waitForAlarm result :8
,V/AlarmManager(  749): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1064): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1064): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1064): checkOverflow(288), More:false, Req:false Child:2
,D/AmoledAdjustTimer(  749): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/BatteryService(  749): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:2, charge type:1, power sharing:false
,D/BatteryService(  749): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  749): stay LED for fully charged
,D/UiModeManager(  749): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1064): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1064): handleBatteryUpdate
,D/SSRMv2:SIOP(  749): SIOP:: AP = 300, Delta = 0
,D/STATUSBAR-PhoneStatusBar( 1064):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1064): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3191): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3191): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1064): checkOverflow(288), More:false, Req:false Child:2
,D/AmoledAdjustTimer(  749): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,E/Watchdog(  749): !@Sync 57
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  749): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  749): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  749): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  749): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  749): SIOP:: AP = 300, Delta = 0
,D/BatteryService(  749): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:4, charge type:1, power sharing:false
,D/BatteryService(  749): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  749): mCoverManager.getCoverState() : true
,D/BatteryService(  749): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1064): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1064): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1064):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1064): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3191): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3191): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1064): checkOverflow(288), More:false, Req:false Child:2
,D/AmoledAdjustTimer(  749): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,E/Watchdog(  749): !@Sync 58
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  749): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  749): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  749): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,V/AlarmManager(  749): waitForAlarm result :8
,V/AlarmManager(  749): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1064): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1064): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1064): checkOverflow(288), More:false, Req:false Child:2
,D/BatteryService(  749): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  749): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  749): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1064): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1064): handleBatteryUpdate
D/UiModeManager(  749): mCoverManager.getCoverState() : true
,D/STATUSBAR-PhoneStatusBar( 1064):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1064): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 3191): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 3191): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1064): checkOverflow(288), More:false, Req:false Child:2
,D/AmoledAdjustTimer(  749): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  749): SIOP:: AP = 300, Delta = 0
,D/BatteryService(  749): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:2, charge type:1, power sharing:false
,D/BatteryService(  749): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  749): stay LED for fully charged
,D/UiModeManager(  749): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1064): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1064): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1064):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1064): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 3191): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 3191): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1064): checkOverflow(288), More:false, Req:false Child:2
,D/AmoledAdjustTimer(  749): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,E/Watchdog(  749): !@Sync 59
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  749): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  749): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,D/BatteryService(  749): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  749): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  749): stay LED for fully charged
,D/UiModeManager(  749): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1064): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1064): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1064):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3191): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3191): Disconnected process message: 10
D/BatteryMeterView( 1064): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1064): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  749): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  749): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,D/BatteryService(  749): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService(  749): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  749): mCoverManager.getCoverState() : true
,D/BatteryService(  749): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1064): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1064): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1064):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1064): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 3191): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 3191): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1064): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  749): SIOP:: AP = 300, Delta = 0
,D/TimaService(  749): TIMA: TimaService scheduler is intialized. 
,D/TimaService(  749): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService(  749): TimaServiceHandler.handleMessage what =1
,D/AmoledAdjustTimer(  749): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,D/BatteryService(  749): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  749): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  749): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1064): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1064): handleBatteryUpdate
D/BatteryService(  749): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1064):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1064): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3191): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3191): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1064): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,I/TLC_TIMA_PKM_measure_kernel(  749): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel(  749): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService(  749): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService(  749): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,I/PowerManagerService(  749): [PWL] Off : 1755s ago
,E/SMD     (  240): DCD ON
,E/Watchdog(  749): !@Sync 60
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  749): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  749): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,D/BatteryService(  749): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:4, charge type:1, power sharing:false
,D/BatteryService(  749): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  749): stay LED for fully charged
,D/UiModeManager(  749): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1064): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1064): handleBatteryUpdate
,V/HeadsetService( 3191): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3191): Disconnected process message: 10
D/STATUSBAR-PhoneStatusBar( 1064):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
D/BatteryMeterView( 1064): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1064): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  749): SIOP:: AP = 300, Delta = 0
,V/AlarmManager(  749): waitForAlarm result :8
,V/AlarmManager(  749): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1064): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1064): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1064): checkOverflow(288), More:false, Req:false Child:2
,I/ProcessStatsService(  749): Prepared write state in 109ms
,D/AmoledAdjustTimer(  749): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,I/ProcessStatsService(  749): Prepared write state in 96ms
,I/ProcessStatsService(  749): Pruning old procstats: /data/system/procstats/state-2015-12-15-05-01-42.bin
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  749): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  749): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,D/dalvikvm(  749): GC_CONCURRENT freed 3401K, 60% free 23620K/57632K, paused 22ms+36ms, total 403ms
,D/BatteryService(  749): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:5, charge type:1, power sharing:false
,D/BatteryService(  749): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  749): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1064): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1064): handleBatteryUpdate
D/BatteryService(  749): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1064):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1064): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 3191): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 3191): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1064): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,E/Watchdog(  749): !@Sync 61
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  749): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  749): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,D/BatteryService(  749): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:7, charge type:1, power sharing:false
,D/BatteryService(  749): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  749): stay LED for fully charged
,D/UiModeManager(  749): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1064): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1064): handleBatteryUpdate
,V/HeadsetService( 3191): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1064):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/HeadsetStateMachine( 3191): Disconnected process message: 10
D/BatteryMeterView( 1064): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1064): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  749): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  749): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,D/BatteryService(  749): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:2, charge type:1, power sharing:false
,D/BatteryService(  749): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  749): mCoverManager.getCoverState() : true
,D/BatteryService(  749): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1064): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1064): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1064):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1064): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3191): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3191): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1064): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  749): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  749): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,D/BatteryService(  749): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:10, charge type:1, power sharing:false
,D/BatteryService(  749): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  749): mCoverManager.getCoverState() : true
,D/BatteryService(  749): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1064): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1064): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1064):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3191): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3191): Disconnected process message: 10
D/BatteryMeterView( 1064): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1064): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,E/Watchdog(  749): !@Sync 62
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  749): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  749): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,D/BatteryService(  749): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:7, charge type:1, power sharing:false
,D/BatteryService(  749): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  749): mCoverManager.getCoverState() : true
,D/BatteryService(  749): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1064): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1064): handleBatteryUpdate
,V/HeadsetService( 3191): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/STATUSBAR-PhoneStatusBar( 1064):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/HeadsetStateMachine( 3191): Disconnected process message: 10
D/BatteryMeterView( 1064): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1064): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  749): SIOP:: AP = 300, Delta = 0
,V/AlarmManager(  749): waitForAlarm result :8
,V/AlarmManager(  749): ClockReceiver onReceive() ACTION_TIME_TICK
,V/AlarmManager(  749): ___SyncScheduler (v3) ACTIVATED___
,V/AlarmManager(  749): <AppSync3 Whitelist>
,V/AlarmManager(  749): (AppSync) ### 0 added ###
D/KeyguardUpdateMonitor( 1064): received broadcast android.intent.action.TIME_TICK
D/KeyguardUpdateMonitor( 1064): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1064): checkOverflow(288), More:false, Req:false Child:2
,D/AmoledAdjustTimer(  749): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,D/BatteryService(  749): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:8, charge type:1, power sharing:false
,D/BatteryService(  749): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1064): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1064): handleBatteryUpdate
D/UiModeManager(  749): mCoverManager.getCoverState() : true
D/BatteryService(  749): stay LED for fully charged
,V/HeadsetService( 3191): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3191): Disconnected process message: 10
,D/STATUSBAR-PhoneStatusBar( 1064):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1064): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1064): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  749): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  749): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,D/BatteryService(  749): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:8, charge type:1, power sharing:false
,D/BatteryService(  749): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  749): stay LED for fully charged
,D/UiModeManager(  749): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1064): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1064): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1064):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1064): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3191): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3191): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1064): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,E/Watchdog(  749): !@Sync 63
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  749): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  749): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,D/BatteryService(  749): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  749): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  749): mCoverManager.getCoverState() : true
,D/BatteryService(  749): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1064): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1064): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1064):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3191): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/BatteryMeterView( 1064): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/HeadsetStateMachine( 3191): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1064): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  749): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  749): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,V/AlarmManager(  749): waitForAlarm result :4
,I/SensorManagerA(  749): getReportingMode :: sensor.mType = 5
,D/Sensors (  749): LightSensor setDelay = 200000000
,D/Sensors (  749): LightSensor setSensorDelay = 200000000
,D/Sensors (  749): Light sensor flush: not enabled 0
,D/Sensors (  749): LightSensor enable = 1
,D/LightsService(  749): [api] onReceive : SvcLEDReceiver re-enables LightSenor and sends MSG_FORCEDSVCLEDTASK
D/Sensors (  749): LightSensor enableSensor = 1
,D/SensorManager(  749): registerListener :: 16, CM36686 Light Sensor, 200000, 0,  
,I/ActivityManager(  749): Killing 4541:com.sec.android.app.shealth/u0a35 (adj 15): empty for 1800s
,I/ActivityManager(  749): Killing 5128:com.samsung.klmsagent/u0a18 (adj 15): empty for 1800s
,I/ActivityManager(  749): Killing 5112:com.sec.android.fotaclient/u0a10 (adj 15): empty for 1800s
,I/ActivityManager(  749): Killing 5307:com.sec.android.provider.badge/u0a72 (adj 15): empty for 1800s
,I/ActivityManager(  749): Killing 5303:com.samsung.android.service.travel/u0a169 (adj 15): empty for 1800s
,I/ActivityManager(  749): Killing 4935:tv.peel.smartremote/u0a163 (adj 15): empty for 1800s
,I/ActivityManager(  749): Killing 5280:com.android.email/u0a155 (adj 15): empty for 1801s
,I/ActivityManager(  749): Killing 4229:com.google.android.apps.plus/u0a130 (adj 15): empty for 1801s
,I/ActivityManager(  749): Killing 5228:com.google.android.apps.magazines/u0a112 (adj 15): empty for 1801s
,I/ActivityManager(  749): Killing 4778:com.samsung.android.magazine.service/u0a106 (adj 15): empty for 1801s
,I/ActivityManager(  749): Killing 5079:com.android.chrome/u0a81 (adj 15): empty for 1801s
,I/ActivityManager(  749): Killing 5202:com.samsung.android.scloud.backup/u0a60 (adj 15): empty for 1802s
,I/ActivityManager(  749): Killing 3753:com.sec.spp.push/u0a38 (adj 15): empty for 1802s
,I/ActivityManager(  749): Killing 4635:com.policydm/1000 (adj 15): empty for 1802s
,D/BatteryService(  749): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  749): stay LED for fully charged
,I/ActivityManager(  749): Killing 5169:com.sec.android.app.voicenote/1000 (adj 15): empty for 1802s
,I/ActivityManager(  749): Killing 5147:com.sec.android.app.videoplayer/u0a52 (adj 15): empty for 1802s
,I/ActivityManager(  749): Killing 4965:com.vlingo.midas/u0a33 (adj 15): empty for 1802s
,I/ActivityManager(  749): Killing 4266:com.sec.android.diagmonagent/1000 (adj 15): empty for 1803s
,I/ActivityManager(  749): Killing 5072:com.sec.android.cloudagent/u0a2 (adj 15): empty for 1803s
,I/ActivityManager(  749): Killing 3799:com.google.android.music:main/u0a122 (adj 15): empty for 1803s
,I/ActivityManager(  749): Killing 4510:com.sec.pcw.device/1000 (adj 15): empty for 1803s
,I/ActivityManager(  749): Killing 4214:com.sec.android.app.FileShareServer/u0a69 (adj 15): empty for 1806s
,I/ActivityManager(  749): Killing 4817:com.samsung.android.provider.shootingmodeprovider/u0a162 (adj 15): empty for 1812s
,I/ActivityManager(  749): Killing 4805:com.sec.kidsplat.installer/u0a158 (adj 15): empty for 1812s
,I/ActivityManager(  749): Killing 4791:com.samsung.helphub/1000 (adj 15): empty for 1812s
,I/ActivityManager(  749): Killing 4763:com.samsung.android.app.watchmanagerstub/u0a100 (adj 15): empty for 1812s
,D/NtpTrustedTime(  749): currentTimeMillis() cache hit
V/NetworkStats(  749): performPollLocked(flags=0x3)
,V/AlarmManager(  749): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,V/AlarmManager(  749): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,D/BatteryService(  749): Sending ACTION_BATTERY_CHANGED.
,D/Sensors (  749): LightSensor enable = 0
,D/LightsService(  749): [SvcLED]  onSensorChanged::light value = 0
D/Sensors (  749): LightSensor enableSensor = 0
,D/SensorManager(  749): unregisterListener ::   
D/UiModeManager(  749): mCoverManager.getCoverState() : true
D/LightsService(  749): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,D/KeyguardUpdateMonitor( 1064): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1064): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1064):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1064): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3191): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3191): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1064): checkOverflow(288), More:false, Req:false Child:2
,D/NtpTrustedTime(  749): currentTimeMillis() cache hit
V/NetworkStats(  749): performPollLocked() took 203ms
,D/NtpTrustedTime(  749): currentTimeMillis() cache hit
,D/NtpTrustedTime(  749): currentTimeMillis() cache hit
,V/GLSActivity( 1319): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1319): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/SSRMv2:SIOP(  749): SIOP:: AP = 300, Delta = 0
,I/EventLogService( 1784): Aggregate from 1450201500804 (log), 1450201500804 (data)
,W/dalvikvm( 1319): VFY: unable to find class referenced in signature (Landroid/net/Network;)
E/dalvikvm( 1319): Could not find class 'android.net.Network', referenced from method com.google.android.gms.http.l.a
W/dalvikvm( 1319): VFY: unable to resolve check-cast 229 (Landroid/net/Network;) in Lcom/google/android/gms/http/l;
,D/dalvikvm( 1319): VFY: replacing opcode 0x1f at 0x0011
I/dalvikvm( 1319): Could not find method android.os.PowerManager.isInteractive, referenced from method com.google.android.gms.common.util.y.a
W/dalvikvm( 1319): VFY: unable to resolve virtual method 1378: Landroid/os/PowerManager;.isInteractive ()Z
,D/dalvikvm( 1319): VFY: replacing opcode 0x6e at 0x003d
,I/System.out( 1319): Thread-57(HTTPLog):isShipBuild true
,I/System.out( 1319): Thread-57(HTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,D/ConnectivityService(  749): handleInetConditionHoldEnd: net=1, condition=100, published condition=100
,D/STATUSBAR-NetworkController_dual( 1064): onReceive() - CONNECTIVITY_ACTION, INET_CONDITION_ACTION
,D/StatusBar.NetworkController_dual( 1064): mMobileLabelViews start
D/StatusBar.NetworkController_dual( 1064): mMobileLabelViews set mobileLabel[SIM_0] =
D/StatusBar.NetworkController_dual( 1064): mMobileLabelViews GONE
D/StatusBar.NetworkController_dual( 1064): mMobileLabelViews2 set mobileLabel[SIM_1] =
,D/StatusBar.NetworkController_dual( 1064): mMobileLabelViews2 GONE
,D/StatusBar.NetworkController_dual( 1064): mSingleMobileLabelViews set : simMode = 0
,D/StatusBar.NetworkController_dual( 1064): mSingleMobileLabelViews set as slot1`s
,D/AmoledAdjustTimer(  749): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,E/Watchdog(  749): !@Sync 64
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  749): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  749): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,TIME-OUT KILL (timeout was 1800000ms),E/SMD     (  240): DCD ON
I/PowerManagerService(  749): [PWL] Off : 1890s ago
E/SMD     (  240): DCD ON
V/AlarmManager(  749): waitForAlarm result :8
V/AlarmManager(  749): ClockReceiver onReceive() ACTION_TIME_TICK
D/KeyguardUpdateMonitor( 1064): received broadcast android.intent.action.TIME_TICK
D/KeyguardUpdateMonitor( 1064): handleTimeUpdate
D/STATUSBAR-IconMerger( 1064): checkOverflow(288), More:false, Req:false Child:2
D/SSRMv2:SIOP(  749): SIOP:: AP = 300, Delta = 0
D/AmoledAdjustTimer(  749): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
D/AndroidRuntime( 6021): 
D/AndroidRuntime( 6021): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 6021): CheckJNI is OFF
D/AndroidRuntime( 6021): setted country_code = Poland
D/AndroidRuntime( 6021): setted countryiso_code = PL
D/AndroidRuntime( 6021): setted sales_code = XEO
D/AndroidRuntime( 6021): readGMSProperty: start
D/AndroidRuntime( 6021): readGMSProperty: already setted!!
D/AndroidRuntime( 6021): readGMSProperty: end
D/AndroidRuntime( 6021): addProductProperty: start
D/dalvikvm( 6021): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 6021): Added shared lib libjavacore.so 0x0
D/dalvikvm( 6021): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 6021): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 6021): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
E/memtrack( 6021): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 6021): failed to load memtrack module: -2
D/dalvikvm( 6021): Note: class Landroid/app/ActivityManagerNative; has 192 unimplemented (abstract) methods
D/AndroidRuntime( 6021): Calling main entry com.android.commands.pm.Pm
D/PackageManagerService(  749): deletePackageAsUser- pkg:com.test.thalitest, userId:0
D/PersonaManagerService(  749): isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
D/PersonaManagerService(  749): isFromApprovedUnInstaller: isApproved : true
D/PersonaManagerService(  749): isFromApprovedUnInstaller: isApproved before exit: true
D/PackageManager(  749): deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag3
D/PackageManager(  749): deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag3
D/PackageManager(  749): START PACKAGE DELETE: observer{1122029144}
D/PackageManager(  749): pkg{<packageName>}
D/PackageManager(  749): user{0}
D/PackageManager(  749): deletePackageAsUser : uid = 2000 userId = 0
D/PackageManagerService(  749): deletePackage- pkg:com.test.thalitest, edmuserId:0
D/PackageManagerService(  749): deletePackage- pkg:com.test.thalitest, edmuserId:-1
D/ApplicationPolicy(  749): getApplicationUninstallationEnabled
D/ApplicationPolicy(  749): getApplicationUninstallationEnabled :  enabled true
D/PackageManagerService(  749): deletePackageX- pkg:com.test.thalitest, userId:0
D/PackageManager(  749): [MSG] DELETE_PACKAGE_AS_USER
D/PackageManager(  749): !@killApplicatoin: 10179, uninstall pkg
W/PackageSettings(  749): Skipping PackageSetting{42949748 com.example.hello/10181} due to missing metadata
D/PackageManager(  749): Sending to user 0: act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000000 Bundle[{android.intent.extra.REMOVED_FOR_ALL_USERS=true, android.intent.extra.UID=10179, android.intent.extra.DATA_REMOVED=true, android.intent.extra.user_handle=0}]
D/dalvikvm( 1784): GC_EXPLICIT freed 545K, 33% free 12335K/18408K, paused 5ms+18ms, total 76ms
W/SQLiteConnectionPool( 1784): A SQLiteConnection object for database '+data+data+com_google_android_gms+databases+networkstatistics_sqlite' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
D/dalvikvm( 2119): GC_EXPLICIT freed 1079K, 40% free 11206K/18408K, paused 3ms+4ms, total 98ms
D/dalvikvm( 1401): GC_EXPLICIT freed 4293K, 46% free 10022K/18408K, paused 4ms+5ms, total 74ms
D/PackageManager(  749): Sending to user 0: act=android.intent.action.PACKAGE_FULLY_REMOVED dat=package:com.test.thalitest flg=0x4000000 Bundle[{android.intent.extra.REMOVED_FOR_ALL_USERS=true, android.intent.extra.UID=10179, android.intent.extra.DATA_REMOVED=true, android.intent.extra.user_handle=0}]
D/AdaptiveEventManager( 1064): action=android.intent.action.PACKAGE_REMOVED
D/QuickConnect[1.1][2] ( 3162): SconnectManager.onReceiver - action : android.intent.action.PACKAGE_REMOVED, package : com.test.thalitest
I/InputReader(  749): Reconfiguring input devices.  changes=0x00000010
I/FPMS_FingerprintManagerService( 1083): onReceive: android.intent.action.PACKAGE_REMOVED
D/elm:14132( 5415): ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
I/PackageManager(  749):   Action: "android.intent.action.SENDTO"
I/PackageManager(  749):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  749):   Scheme: "sms"
I/PackageManager(  749): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
W/GeofencerStateMachine( 1216): Ignoring removeGeofence because network location is disabled.
I/PackageManager(  749):   Action: "android.intent.action.SENDTO"
I/PackageManager(  749):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  749):   Scheme: "smsto"
I/PackageManager(  749): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
D/EnterpriseDeviceManagerService(  749): Package has changed for user 0
D/EnterpriseDeviceManagerService(  749): Admin package name: com.google.android.gms
D/elm:14132( 5415): ELMAbstractReceiver : Receive Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
I/PackageManager(  749):   Action: "android.intent.action.SENDTO"
I/PackageManager(  749):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  749):   Scheme: "mms"
I/PackageManager(  749): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
D/elm:14132( 5415): ElmAgentService : onCreate()
D/elm:14132( 5415): ElmAgentService : onHandleIntent() Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
D/elm:14132( 5415): MainReceiver.listeningToPackageRemoved()
D/elm:14132( 5415): MDMBridge.getInstance()
D/elm:14132( 5415): MDMBridge.getAllLicenseInfoFromSDK()
D/elm:14132( 5415): MDMBridge.getAllLicenseInfoFromSDK()
I/PackageManager(  749):   Action: "android.intent.action.SENDTO"
I/PackageManager(  749):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  749):   Scheme: "mmsto"
I/PackageManager(  749): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
I/SELinux ( 6064): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 6064):  
D/elm:14132( 5415): MainReceiver.listeningToPackageRemoved(). SEND to KLMS. Remove All KNOX/ONS License
D/dalvikvm(  749): GC_EXPLICIT freed 2608K, 59% free 23739K/57632K, paused 74ms+18ms, total 278ms
D/elm:14132( 5415): ElmAgentService : onDestroy().
D/dalvikvm(  749): WAIT_FOR_CONCURRENT_GC blocked 83ms
I/PackageManager(  749):   Action: "android.intent.action.SENDTO"
I/PackageManager(  749):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  749):   Scheme: "sms"
I/SELinux ( 6064): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 6064):  
I/SELinux ( 6064):  
I/SELinux ( 6064): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 6064): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 6064): >>>>> Normal User
E/dalvikvm( 6064): >>>>> com.sec.android.service.health [ userId:0 | appId:10016 ]
E/SELinux ( 6064): [DEBUG] seapp_context_lookup: seinfoCategory = platform
I/PackageManager(  749): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
W/Resources(  749): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
I/PackageManager(  749):   Action: "android.intent.action.SENDTO"
I/PackageManager(  749):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  749):   Scheme: "smsto"
D/TimaKeyStoreProvider( 6064): in addTimaSignatureService
D/RCPManagerService(  749): PackageReceiver onReceive()
I/PackageManager(  749): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
D/TimaKeyStoreProvider( 6064): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 6064): Added TimaKesytore provider
I/PackageManager(  749):   Action: "android.intent.action.SENDTO"
I/PackageManager(  749):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  749):   Scheme: "mms"
I/HarmonyEASService(  749): onReceive : android.intent.action.PACKAGE_REMOVED for 0
I/PackageManager(  749): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
W/Resources(  749): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
I/PackageManager(  749):   Action: "android.intent.action.SENDTO"
I/PackageManager(  749):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  749):   Scheme: "mmsto"
I/PackageManager(  749): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
W/ActivityManager(  749): Permission Denial: getCurrentUser() from pid=6064, uid=10016 requires android.permission.INTERACT_ACROSS_USERS
W/Resources(  749): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/dalvikvm(  749): GC_EXPLICIT freed 768K, 59% free 23639K/57632K, paused 7ms+19ms, total 189ms
D/PackageManager(  749): delete sourFile : 
D/dalvikvm( 6064): No JNI_OnLoad found in /system/lib/libsecure_storage_jni.so 0x42584d58, skipping init
I/SecureStorage( 6064): [INFO]: SPID(0x00000000)Checking if this device supports Secure Storage
I/SecureStorage( 6064): [INFO]: SPID(0x00000000)This device supports Secure Storage
I/SecureStorage(  294): [INFO]: SPID(0x00000004)Credentials: uid 10016, gid 10016, pid 6064
I/SecureStorage(  294): [INFO]: SPID(0x00000004)Received function mask & code: 0000010C
I/SecureStorage( 6064): [INFO]: SPID(0x00000000)SS Daemon is running
W/Resources(  749): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/BackupManagerService(  749): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
V/BackupManagerService(  749): removePackageParticipantsLocked: uid=10179 #1
I/SecureStorage( 6064): [INFO]: SPID(0x00000000)Processing data
I/SecureStorage(  294): [INFO]: SPID(0x00000004)Credentials: uid 10016, gid 10016, pid 6064
I/SecureStorage(  294): [INFO]: SPID(0x00000004)Received function mask & code: 00000106
W/Resources(  749): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/PackageManager(  749): delete native library directory: 
D/PackageManager(  749): return delete result to caller: 1122029144
D/PackageManager(  749): returnCode: 1
D/AndroidRuntime( 6021): Shutting down VM
D/dalvikvm( 6021): GC_CONCURRENT freed 96K, 14% free 670K/772K, paused 1ms+0ms, total 3ms
I/PackageManager(  749):   Action: "android.intent.action.SENDTO"
I/PackageManager(  749):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  749):   Scheme: "sms"
I/PackageManager(  749): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
I/PackageManager(  749):   Action: "android.intent.action.SENDTO"
I/PackageManager(  749):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  749):   Scheme: "smsto"
I/PackageManager(  749): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
I/PackageManager(  749):   Action: "android.intent.action.SENDTO"
I/PackageManager(  749):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  749):   Scheme: "mms"
I/PackageManager(  749): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
W/Resources(  749): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
I/PackageManager(  749):   Action: "android.intent.action.SENDTO"
I/PackageManager(  749):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  749):   Scheme: "mmsto"
I/PackageManager(  749): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
W/Resources(  749): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  749): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  749): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  749): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  749): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
W/Resources(  749): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  749): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  749): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
W/Resources(  749): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  749): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  749): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
I/CrashAnrDetector(  749): onPackageRemoved : com.test.thalitest
D/UsbSettingsManager(  749): clearDefaults: com.test.thalitest
D/InputReader(  749): Processing first event
E/SMD     (  240): DCD ON
W/ApplicationsProvider( 1401): Could not fetch usage stats
W/ApplicationsProvider( 1401): java.lang.SecurityException: Neither user 10020 nor current process has android.permission.PACKAGE_USAGE_STATS.
W/ApplicationsProvider( 1401): 	at android.os.Parcel.readException(Parcel.java:1465)
W/ApplicationsProvider( 1401): 	at android.os.Parcel.readException(Parcel.java:1419)
W/ApplicationsProvider( 1401): 	at com.android.internal.app.IUsageStats$Stub$Proxy.getAllPkgUsageStats(IUsageStats.java:317)
W/ApplicationsProvider( 1401): 	at android.app.ActivityManager.getAllPackageUsageStats(ActivityManager.java:2543)
W/ApplicationsProvider( 1401): 	at com.android.providers.applications.ApplicationsProvider.fetchUsageStats(ApplicationsProvider.java:681)
W/ApplicationsProvider( 1401): 	at com.android.providers.applications.ApplicationsProvider.updateApplicationsList(ApplicationsProvider.java:519)
W/ApplicationsProvider( 1401): 	at com.android.providers.applications.ApplicationsProvider.access$300(ApplicationsProvider.java:70)
W/ApplicationsProvider( 1401): 	at com.android.providers.applications.ApplicationsProvider$UpdateHandler.handleMessage(ApplicationsProvider.java:209)
W/ApplicationsProvider( 1401): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/ApplicationsProvider( 1401): 	at android.os.Looper.loop(Looper.java:146)
W/ApplicationsProvider( 1401): 	at android.os.HandlerThread.run(HandlerThread.java:61)

```
