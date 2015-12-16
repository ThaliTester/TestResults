#### Test 50650278dbf8a2a_thali05_samsung-SM-G800H Logs


```
--------- beginning of /dev/log/system
W/ActivityManager(  745): Permission Denial: getCurrentUser() from pid=4538, uid=10035 requires android.permission.INTERACT_ACROSS_USERS
--------- beginning of /dev/log/main
W/ContextImpl( 4538): Implicit intents with startService are not safe: Intent { act=com.sec.android.service.health.cp.accesscontrol } android.content.ContextWrapper.bindService:529 com.samsung.android.sdk.health.content.ShealthAccessControl.startService:274 com.samsung.android.sdk.health.content.ShealthAccessControl.requestPermission:212 
I/SELinux ( 4558): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 4558):  
E/Device Type Shared Preferences( 4538): Device Type Shared Preferences - getDeviceTypeChecked -true
E/Device Type Shared Preferences( 4538): Device Type Shared Preferences - not connecting to service
E/com.sec.android.app.shealth.SHealthApplication( 4538): ContentProvider is not null
I/SELinux ( 4558): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 4558):  
I/SELinux ( 4558):  
I/SELinux ( 4558): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 4558): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 4558): >>>>> Normal User
E/dalvikvm( 4558): >>>>> com.sec.android.service.health [ userId:0 | appId:10016 ]
E/SELinux ( 4558): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 4558): in addTimaSignatureService
D/TimaKeyStoreProvider( 4558): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 4558): Added TimaKesytore provider
V/MediaPlayer( 4538): decode(61, 33979084, 48105)
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
V/AudioCache(  249): notify(0xb89c70b8, 8, 0, 0)
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
V/AudioCache(  249): notify(0xb89c70b8, 200, 973, 0)
V/AudioCache(  249): ignored
V/AwesomePlayer(  249): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  249): notify(0xb89c70b8, 5, 0, 0)
V/AudioCache(  249): ignored
V/AwesomePlayer(  249): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  249): notify(0xb89c70b8, 1, 0, 0)
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
V/AudioCache(  249): notify(0xb89c70b8, 6, 0, 0)
V/AudioCache(  249): ignored
V/AwesomePlayer(  249): addBatteryData
V/MediaPlayerService(  249): wait for playback complete
W/ActivityManager(  745): Permission Denial: getCurrentUser() from pid=4558, uid=10016 requires android.permission.INTERACT_ACROSS_USERS
I/OMXCodec(  249): [OMX.google.vorbis.decoder] End Of Stream
V/AwesomePlayer(  249): postAudioEOS delayUs (0)
V/AwesomePlayer(  249): onCheckAudioStatus
V/AwesomePlayer(  249): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  249): onStreamDone
V/AwesomePlayer(  249): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  249): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  249): notify(0xb89c70b8, 2, 0, 0)
V/AudioCache(  249): playback complete - thread will wake up later
V/AwesomePlayer(  249): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  249): notify(0xb89c70b8, 7, 0, 0)
V/AudioCache(  249): ignored
V/AwesomePlayer(  249): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer(  249): addBatteryData
V/AudioCache(  249): wait - success
V/StagefrightPlayer(  249): reset
V/AwesomePlayer(  249): reset_l()
V/AwesomePlayer(  249): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  249): notify(0xb89c70b8, 8, 0, 0)
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
V/MediaPlayer( 4538): decode(63, 33914984, 10421)
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
V/AudioCache(  249): notify(0xb89be000, 8, 0, 0)
V/AudioCache(  249): ignored
V/AwesomePlayer(  249): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  249): mAudioTrackVector clear
V/AwesomePlayer(  249): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  249): mSecMediaClock clear
D/dalvikvm( 4558): No JNI_OnLoad found in /system/lib/libsecure_storage_jni.so 0x42614b78, skipping init
I/SecureStorage( 4558): [INFO]: SPID(0x00000000)Checking if this device supports Secure Storage
I/SecureStorage( 4558): [INFO]: SPID(0x00000000)This device supports Secure Storage
V/AwesomePlayer(  249): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer(  249): mBitrate = -1 bits/sec
V/AwesomePlayer(  249): current audio track index (0) is added to vector
V/AwesomePlayer(  249): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer(  249): AwesomePlayer::setDataSource_l():: This is not a DRM content
V/MediaPlayerService(  249): prepare
V/AwesomePlayer(  249): prepareAsync
V/MediaPlayerService(  249): wait for prepare
I/SecureStorage(  316): [INFO]: SPID(0x00000003)Credentials: uid 10016, gid 10016, pid 4558
I/SecureStorage(  316): [INFO]: SPID(0x00000003)Received function mask & code: 0000010C
V/AwesomePlayer(  249): onPrepareAsyncEvent
I/SecMediaClock(  249): SecMediaClock constructor
I/SecureStorage( 4558): [INFO]: SPID(0x00000000)SS Daemon is running
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
V/AudioCache(  249): notify(0xb89be000, 200, 973, 0)
V/AudioCache(  249): ignored
V/AwesomePlayer(  249): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  249): notify(0xb89be000, 5, 0, 0)
V/AudioCache(  249): ignored
V/AwesomePlayer(  249): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  249): notify(0xb89be000, 1, 0, 0)
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
V/AudioCache(  249): notify(0xb89be000, 6, 0, 0)
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
V/AudioCache(  249): notify(0xb89be000, 2, 0, 0)
V/AudioCache(  249): playback complete - thread will wake up later
V/AwesomePlayer(  249): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  249): notify(0xb89be000, 7, 0, 0)
V/AudioCache(  249): ignored
V/AwesomePlayer(  249): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer(  249): addBatteryData
V/AudioCache(  249): wait - success
V/StagefrightPlayer(  249): reset
V/AwesomePlayer(  249): reset_l()
V/AwesomePlayer(  249): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  249): notify(0xb89be000, 8, 0, 0)
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
I/SecureStorage( 4558): [INFO]: SPID(0x00000000)Processing data
V/AwesomePlayer(  249): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  249): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  249): mAudioTrackVector clear
V/AwesomePlayer(  249): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  249): mSecMediaClock clear
I/SecureStorage(  316): [INFO]: SPID(0x00000003)Credentials: uid 10016, gid 10016, pid 4558
I/SecureStorage(  316): [INFO]: SPID(0x00000003)Received function mask & code: 00000106
V/AwesomePlayer(  249): destructor
V/AwesomePlayer(  249): reset_l()
V/AwesomePlayer(  249): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  249): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  249): mAudioTrackVector clear
V/AwesomePlayer(  249): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  249): mSecMediaClock clear
V/MediaPlayer( 4538): decode(64, 37457308, 34198)
V/MediaPlayerService(  249): decode(33, 37457308, 34198)
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
V/StagefrightPlayer(  249): setDataSource(33, 37457308, 34198)
V/AwesomePlayer(  249): reset_l()
V/AwesomePlayer(  249): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  249): notify(0xb89b8858, 8, 0, 0)
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
V/AudioCache(  249): notify(0xb89b8858, 200, 973, 0)
V/AudioCache(  249): ignored
V/AwesomePlayer(  249): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  249): notify(0xb89b8858, 5, 0, 0)
V/AudioCache(  249): ignored
V/AwesomePlayer(  249): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  249): notify(0xb89b8858, 1, 0, 0)
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
V/AudioCache(  249): notify(0xb89b8858, 6, 0, 0)
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
V/AudioCache(  249): notify(0xb89b8858, 2, 0, 0)
V/AudioCache(  249): playback complete - thread will wake up later
V/AwesomePlayer(  249): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  249): notify(0xb89b8858, 7, 0, 0)
V/AudioCache(  249): ignored
V/AwesomePlayer(  249): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer(  249): addBatteryData
V/AudioCache(  249): wait - success
V/StagefrightPlayer(  249): reset
V/AwesomePlayer(  249): reset_l()
V/AwesomePlayer(  249): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  249): notify(0xb89b8858, 8, 0, 0)
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
V/MediaPlayer( 4538): decode(65, 33862452, 7405)
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
V/AudioCache(  249): notify(0xb89b82f0, 8, 0, 0)
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
V/AudioCache(  249): notify(0xb89b82f0, 200, 973, 0)
V/AudioCache(  249): ignored
V/AwesomePlayer(  249): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  249): notify(0xb89b82f0, 5, 0, 0)
V/AudioCache(  249): ignored
V/AwesomePlayer(  249): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  249): notify(0xb89b82f0, 1, 0, 0)
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
V/AudioCache(  249): notify(0xb89b82f0, 6, 0, 0)
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
V/AudioCache(  249): notify(0xb89b82f0, 2, 0, 0)
V/AudioCache(  249): playback complete - thread will wake up later
V/AwesomePlayer(  249): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  249): notify(0xb89b82f0, 7, 0, 0)
V/AudioCache(  249): ignored
V/AwesomePlayer(  249): cancelPlayerEvents (keepNotifications=1)
V/AudioCache(  249): wait - success
V/StagefrightPlayer(  249): reset
V/AwesomePlayer(  249): addBatteryData
V/AwesomePlayer(  249): reset_l()
V/AwesomePlayer(  249): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  249): notify(0xb89b82f0, 8, 0, 0)
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
V/MediaPlayer( 4538): decode(66, 37547940, 5555)
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
V/AudioCache(  249): notify(0xb89c70b8, 8, 0, 0)
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
V/AudioCache(  249): notify(0xb89c70b8, 200, 973, 0)
V/AudioCache(  249): ignored
V/AwesomePlayer(  249): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  249): notify(0xb89c70b8, 5, 0, 0)
V/AudioCache(  249): ignored
V/AwesomePlayer(  249): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  249): notify(0xb89c70b8, 1, 0, 0)
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
V/AudioCache(  249): notify(0xb89c70b8, 6, 0, 0)
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
V/AudioCache(  249): notify(0xb89c70b8, 2, 0, 0)
V/AudioCache(  249): playback complete - thread will wake up later
V/AwesomePlayer(  249): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  249): notify(0xb89c70b8, 7, 0, 0)
V/AudioCache(  249): ignored
V/AwesomePlayer(  249): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer(  249): addBatteryData
V/AudioCache(  249): wait - success
V/StagefrightPlayer(  249): reset
V/AwesomePlayer(  249): reset_l()
V/AwesomePlayer(  249): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  249): notify(0xb89c70b8, 8, 0, 0)
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
V/MediaPlayer( 4538): decode(67, 30367732, 5085)
V/MediaPlayerService(  249): decode(33, 30367732, 5085)
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
V/StagefrightPlayer(  249): setDataSource(33, 30367732, 5085)
V/AwesomePlayer(  249): reset_l()
V/AwesomePlayer(  249): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  249): notify(0xb89c8700, 8, 0, 0)
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
V/AudioCache(  249): notify(0xb89c8700, 200, 973, 0)
V/AudioCache(  249): ignored
V/AwesomePlayer(  249): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  249): notify(0xb89c8700, 5, 0, 0)
V/AudioCache(  249): ignored
V/AwesomePlayer(  249): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  249): notify(0xb89c8700, 1, 0, 0)
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
V/AudioCache(  249): notify(0xb89c8700, 6, 0, 0)
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
V/AudioCache(  249): notify(0xb89c8700, 2, 0, 0)
V/AudioCache(  249): playback complete - thread will wake up later
V/AwesomePlayer(  249): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  249): notify(0xb89c8700, 7, 0, 0)
V/AudioCache(  249): ignored
V/AwesomePlayer(  249): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer(  249): addBatteryData
V/AudioCache(  249): wait - success
V/StagefrightPlayer(  249): reset
V/AwesomePlayer(  249): reset_l()
V/AwesomePlayer(  249): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  249): notify(0xb89c8700, 8, 0, 0)
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
V/MediaPlayer( 4538): decode(68, 30372876, 21552)
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
V/AudioCache(  249): notify(0xb89b9dd0, 8, 0, 0)
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
V/AudioCache(  249): notify(0xb89b9dd0, 200, 973, 0)
V/AudioCache(  249): ignored
V/AwesomePlayer(  249): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  249): notify(0xb89b9dd0, 5, 0, 0)
V/AudioCache(  249): ignored
V/AwesomePlayer(  249): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  249): notify(0xb89b9dd0, 1, 0, 0)
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
V/AudioCache(  249): notify(0xb89b9dd0, 6, 0, 0)
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
V/AudioCache(  249): notify(0xb89b9dd0, 2, 0, 0)
V/AudioCache(  249): playback complete - thread will wake up later
V/AwesomePlayer(  249): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  249): notify(0xb89b9dd0, 7, 0, 0)
V/AudioCache(  249): ignored
V/AwesomePlayer(  249): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer(  249): addBatteryData
V/AudioCache(  249): wait - success
V/StagefrightPlayer(  249): reset
V/AwesomePlayer(  249): reset_l()
V/AwesomePlayer(  249): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  249): notify(0xb89b9dd0, 8, 0, 0)
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
V/MediaPlayer( 4538): decode(69, 37543652, 4230)
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
V/AudioCache(  249): notify(0xb89bdf88, 8, 0, 0)
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
V/AudioCache(  249): notify(0xb89bdf88, 200, 973, 0)
V/AudioCache(  249): ignored
V/AwesomePlayer(  249): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  249): notify(0xb89bdf88, 5, 0, 0)
V/AudioCache(  249): ignored
V/AwesomePlayer(  249): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  249): notify(0xb89bdf88, 1, 0, 0)
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
V/AudioCache(  249): notify(0xb89bdf88, 6, 0, 0)
V/AudioCache(  249): ignored
V/AwesomePlayer(  249): addBatteryData
V/MediaPlayerService(  249): wait for playback complete
V/AwesomePlayer(  249): postAudioEOS delayUs (0)
V/AwesomePlayer(  249): onCheckAudioStatus
V/AwesomePlayer(  249): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  249): onStreamDone
V/AwesomePlayer(  249): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  249): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  249): notify(0xb89bdf88, 2, 0, 0)
V/AudioCache(  249): playback complete - thread will wake up later
V/AwesomePlayer(  249): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  249): notify(0xb89bdf88, 7, 0, 0)
V/AudioCache(  249): ignored
V/AwesomePlayer(  249): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer(  249): addBatteryData
V/AudioCache(  249): wait - success
V/StagefrightPlayer(  249): reset
V/AwesomePlayer(  249): reset_l()
V/AwesomePlayer(  249): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  249): notify(0xb89bdf88, 8, 0, 0)
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
V/MediaPlayer( 4538): decode(70, 30337076, 9400)
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
V/AudioCache(  249): notify(0xb89bc468, 8, 0, 0)
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
V/AudioCache(  249): notify(0xb89bc468, 200, 973, 0)
V/AudioCache(  249): ignored
V/AwesomePlayer(  249): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  249): notify(0xb89bc468, 5, 0, 0)
V/AudioCache(  249): ignored
V/AwesomePlayer(  249): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  249): notify(0xb89bc468, 1, 0, 0)
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
V/AudioCache(  249): notify(0xb89bc468, 6, 0, 0)
D/AndroidRuntime( 4578): 
D/AndroidRuntime( 4578): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
V/AudioCache(  249): ignored
V/AwesomePlayer(  249): addBatteryData
V/MediaPlayerService(  249): wait for playback complete
D/AndroidRuntime( 4578): CheckJNI is OFF
D/AndroidRuntime( 4578): setted country_code = Poland
D/AndroidRuntime( 4578): setted countryiso_code = PL
D/AndroidRuntime( 4578): setted sales_code = XEO
D/AndroidRuntime( 4578): readGMSProperty: start
D/AndroidRuntime( 4578): readGMSProperty: already setted!!
D/AndroidRuntime( 4578): readGMSProperty: end
D/AndroidRuntime( 4578): addProductProperty: start
I/SELinux ( 4625): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 4625):  
I/ActivityManager(  745): Killing 3108:com.sec.android.app.mt/1000 (adj 15): empty #43
D/dalvikvm( 4578): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 4578): Added shared lib libjavacore.so 0x0
D/dalvikvm( 4578): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 4578): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 4578): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
I/OMXCodec(  249): [OMX.google.vorbis.decoder] End Of Stream
V/AwesomePlayer(  249): postAudioEOS delayUs (0)
V/AwesomePlayer(  249): onCheckAudioStatus
V/AwesomePlayer(  249): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  249): onStreamDone
V/AwesomePlayer(  249): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  249): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  249): notify(0xb89bc468, 2, 0, 0)
V/AudioCache(  249): playback complete - thread will wake up later
V/AwesomePlayer(  249): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  249): notify(0xb89bc468, 7, 0, 0)
V/AudioCache(  249): ignored
V/AwesomePlayer(  249): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer(  249): addBatteryData
V/AudioCache(  249): wait - success
V/StagefrightPlayer(  249): reset
V/AwesomePlayer(  249): reset_l()
V/AwesomePlayer(  249): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  249): notify(0xb89bc468, 8, 0, 0)
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
V/MediaPlayer( 4538): decode(71, 33925464, 44276)
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
V/AudioCache(  249): notify(0xb89c6fb0, 8, 0, 0)
V/AudioCache(  249): ignored
V/AwesomePlayer(  249): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  249): mAudioTrackVector clear
V/AwesomePlayer(  249): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  249): mSecMediaClock clear
I/SELinux ( 4625): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 4625):  
I/SELinux ( 4625):  
I/SELinux ( 4625): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 4625): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 4625): >>>>> Normal User
E/dalvikvm( 4625): >>>>> com.policydm [ userId:0 | appId:1000 ]
E/SELinux ( 4625): [DEBUG] seapp_context_lookup: seinfoCategory = platform
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
V/AudioCache(  249): notify(0xb89c6fb0, 200, 973, 0)
V/AudioCache(  249): ignored
V/AwesomePlayer(  249): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  249): notify(0xb89c6fb0, 5, 0, 0)
V/AudioCache(  249): ignored
V/AwesomePlayer(  249): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  249): notify(0xb89c6fb0, 1, 0, 0)
V/AudioCache(  249): prepared
V/AudioCache(  249): wait - success
V/MediaPlayerService(  249): start
V/StagefrightPlayer(  249): start
V/AwesomePlayer(  2,49): play
V/AwesomePlayer(  249): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer(  249): startAudioPlayer_l, sendErrorNotification (0)
I/OMXCodec(  249): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec(  249): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec(  249): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/AudioPlayer(  249):  Audioplayer kKeyAudioPCMFormat:1, 2, 0
I/AudioPlayer(  249):  Audioplayer kKeyAudioPCMFormat read fail(2, 1)
V/AudioCache(  249): open(44100, 2, 0x0, 1, 4)
V/AwesomePlayer(  249): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache(  249): notify(0xb89c6fb0, 6, 0, 0)
V/AudioCache(  249): ignored
V/AwesomePlayer(  249): addBatteryData
V/MediaPlayerService(  249): wait for playback complete
D/TimaKeyStoreProvider( 4625): in addTimaSignatureService
D/TimaKeyStoreProvider( 4625): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 4625): Added TimaKesytore provider
I/OMXCodec(  249): [OMX.google.vorbis.decoder] End Of Stream
V/AwesomePlayer(  249): postAudioEOS delayUs (0)
V/AwesomePlayer(  249): onCheckAudioStatus
V/AwesomePlayer(  249): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  249): onStreamDone
V/AwesomePlayer(  249): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  249): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  249): notify(0xb89c6fb0, 2, 0, 0)
V/AudioCache(  249): playback complete - thread will wake up later
V/AwesomePlayer(  249): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  249): notify(0xb89c6fb0, 7, 0, 0)
V/AudioCache(  249): ignored
V/AwesomePlayer(  249): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer(  249): addBatteryData
V/AudioCache(  249): wait - success
V/StagefrightPlayer(  249): reset
V/AwesomePlayer(  249): reset_l()
V/AwesomePlayer(  249): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  249): notify(0xb89c6fb0, 8, 0, 0)
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
V/MediaPlayer( 4538): decode(72, 33885672, 29256)
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
V/AudioCache(  249): notify(0xb89ca9e0, 8, 0, 0)
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
E/memtrack( 4578): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 4578): failed to load memtrack module: -2
I/OMXCodec(  249): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer(  249): finishAsyncPrepare_l
V/AwesomePlayer(  249): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache(  249): notify(0xb89ca9e0, 200, 973, 0)
V/AudioCache(  249): ignored
V/AwesomePlayer(  249): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  249): notify(0xb89ca9e0, 5, 0, 0)
V/AudioCache(  249): ignored
V/AwesomePlayer(  249): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  249): notify(0xb89ca9e0, 1, 0, 0)
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
V/AudioCache(  249): notify(0xb89ca9e0, 6, 0, 0)
V/AudioCache(  249): ignored
V/AwesomePlayer(  249): addBatteryData
V/MediaPlayerService(  249): wait for playback complete
D/dalvikvm( 4578): Note: class Landroid/app/ActivityManagerNative; has 192 unimplemented (abstract) methods
I/OMXCodec(  249): [OMX.google.vorbis.decoder] End Of Stream
V/AwesomePlayer(  249): postAudioEOS delayUs (0)
V/AwesomePlayer(  249): onCheckAudioStatus
V/AwesomePlayer(  249): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  249): onStreamDone
V/AwesomePlayer(  249): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  249): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  249): notify(0xb89ca9e0, 2, 0, 0)
V/AudioCache(  249): playback complete - thread will wake up later
V/AwesomePlayer(  249): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  249): notify(0xb89ca9e0, 7, 0, 0)
V/AudioCache(  249): ignored
V/AwesomePlayer(  249): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer(  249): addBatteryData
V/AudioCache(  249): wait - success
V/StagefrightPlayer(  249): reset
V/AwesomePlayer(  249): reset_l()
V/AwesomePlayer(  249): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  249): notify(0xb89ca9e0, 8, 0, 0)
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
V/MediaPlayer( 4538): decode(73, 37491572, 52024)
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
V/AudioCache(  249): notify(0xb89c70b8, 8, 0, 0)
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
V/AudioCache(  249): notify(0xb89c70b8, 200, 973, 0)
V/AudioCache(  249): ignored
V/AwesomePlayer(  249): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  249): notify(0xb89c70b8, 5, 0, 0)
V/AudioCache(  249): ignored
V/AwesomePlayer(  249): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  249): notify(0xb89c70b8, 1, 0, 0)
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
V/AudioCache(  249): notify(0xb89c70b8, 6, 0, 0)
V/AudioCache(  249): ignored
V/AwesomePlayer(  249): addBatteryData
V/MediaPlayerService(  249): wait for playback complete
I/AudioPlayer(  249): First fillBuffer call!!
D/AndroidRuntime( 4578): Calling main entry com.android.commands.am.Am
I/OMXCodec(  249): [OMX.google.vorbis.decoder] End Of Stream
V/AwesomePlayer(  249): postAudioEOS delayUs (0)
V/AwesomePlayer(  249): onCheckAudioStatus
V/AwesomePlayer(  249): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  249): onStreamDone
V/AwesomePlayer(  249): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  249): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  249): notify(0xb89c70b8, 2, 0, 0)
V/AudioCache(  249): playback complete - thread will wake up later
V/AwesomePlayer(  249): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  249): notify(0xb89c70b8, 7, 0, 0)
V/AudioCache(  249): ignored
V/AwesomePlayer(  249): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer(  249): addBatteryData
V/AudioCache(  249): wait - success
V/StagefrightPlayer(  249): reset
V/AwesomePlayer(  249): reset_l()
V/AwesomePlayer(  249): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  249): notify(0xb89c70b8, 8, 0, 0)
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
V/MediaPlayer( 4538): decode(74, 33969800, 9226)
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
V/AudioCache(  249): notify(0xb89ba818, 8, 0, 0)
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
V/AudioCache(  249): notify(0xb89ba818, 200, 973, 0)
V/AudioCache(  249): ignored
V/AwesomePlayer(  249): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  249): notify(0xb89ba818, 5, 0, 0)
V/AudioCache(  249): ignored
V/AwesomePlayer(  249): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  249): notify(0xb89ba818, 1, 0, 0)
V/AudioCache(  249): prepared
V/AudioCache(  249): wait - success
V/MediaPlayerService(  249): start
V/StagefrightPlayer(  249): start
V/AwesomePlayer(  249): play
V/ApplicationPolicy(  745): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
V/AwesomePlayer(  249): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer(  249): startAudioPlayer_l, sendErrorNotification (0)
I/OMXCodec(  249): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec(  249): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec(  249): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/AudioPlayer(  249):  Audioplayer kKeyAudioPCMFormat:1, 2, 0
I/AudioPlayer(  249):  Audioplayer kKeyAudioPCMFormat read fail(2, 1)
V/AudioCache(  249): open(44100, 2, 0x0, 1, 4)
V/AwesomePlayer(  249): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache(  249): notify(0xb89ba818, 6, 0, 0)
V/AudioCache(  249): ignored
V/AwesomePlayer(  249): addBatteryData
V/MediaPlayerService(  249): wait for playback complete
D/CustomFrequencyManagerService(  745): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 745  pkgName : ACTIVITY_RESUME_BOOSTER@5
I/OMXCodec(  249): [OMX.google.vorbis.decoder] End Of Stream
W/ActivityManager(  745): mDVFSHelper.acquire()
V/AwesomePlayer(  249): postAudioEOS delayUs (0)
V/AwesomePlayer(  249): onCheckAudioStatus
V/AwesomePlayer(  249): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  249): onStreamDone
V/AwesomePlayer(  249): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  249): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  249): notify(0xb89ba818, 2, 0, 0)
V/AudioCache(  249): playback complete - thread will wake up later
V/AwesomePlayer(  249): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  249): notify(0xb89ba818, 7, 0, 0)
V/AudioCache(  249): ignored
V/AwesomePlayer(  249): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer(  249): addBatteryData
V/AudioCache(  249): wait - success
V/StagefrightPlayer(  249): reset
V/AwesomePlayer(  249): reset_l()
V/AwesomePlayer(  249): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  249): notify(0xb89ba818, 8, 0, 0)
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
V/MediaPlayer( 4538): decode(75, 30402580, 4509)
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
V/AudioCache(  249): notify(0xb89bc468, 8, 0, 0)
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
V/AudioCache(  249): notify(0xb89bc468, 200, 973, 0)
V/AudioCache(  249): ignored
V/AwesomePlayer(  249): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  249): notify(0xb89bc468, 5, 0, 0)
V/AudioCache(  249): ignored
V/AwesomePlayer(  249): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  249): notify(0xb89bc468, 1, 0, 0)
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
V/AudioCache(  249): notify(0xb89bc468, 6, 0, 0)
V/AudioCache(  249): ignored
V/AwesomePlayer(  249): addBatteryData
V/MediaPlayerService(  249): wait for playback complete
I/SELinux ( 4670): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 4670):  
I/AudioPlayer(  249): First fillBuffer call!!
V/AwesomePlayer(  249): postAudioEOS delayUs (0)
V/AwesomePlayer(  249): onCheckAudioStatus
V/AwesomePlayer(  249): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  249): onStreamDone
V/AwesomePlayer(  249): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  249): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  249): notify(0xb89bc468, 2, 0, 0)
V/AudioCache(  249): playback complete - thread will wake up later
V/AwesomePlayer(  249): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  249): notify(0xb89bc468, 7, 0, 0)
V/AudioCache(  249): ignored
V/AwesomePlayer(  249): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer(  249): addBatteryData
V/AudioCache(  249): wait - success
V/StagefrightPlayer(  249): reset
V/AwesomePlayer(  249): reset_l()
V/AwesomePlayer(  249): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  249): notify(0xb89bc468, 8, 0, 0)
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
D/dalvikvm(  245): GC_EXPLICIT freed 45K, 50% free 9513K/18912K, paused 2ms+2ms, total 29ms
I/SELinux ( 4670): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 4670):  
I/SELinux ( 4670):  
I/SELinux ( 4670): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 4670): [DEBUG] seapp_context_lookup: seinfoCategory = default
E/dalvikvm( 4670): >>>>> Normal User
E/dalvikvm( 4670): >>>>> com.test.thalitest [ userId:0 | appId:10179 ]
E/SELinux ( 4670): [DEBUG] seapp_context_lookup: seinfoCategory = default
D/dalvikvm(  245): GC_EXPLICIT freed <1K, 50% free 9513K/18912K, paused 2ms+2ms, total 19ms
D/LockPatternUtils( 1063): isPcwEnable = null
D/AndroidRuntime( 4578): Shutting down VM
D/dalvikvm( 4578): GC_CONCURRENT freed 97K, 13% free 717K/816K, paused 0ms+0ms, total 2ms
D/TimaKeyStoreProvider( 4670): in addTimaSignatureService
D/TimaKeyStoreProvider( 4670): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 4670): Added TimaKesytore provider
D/dalvikvm(  245): GC_EXPLICIT freed <1K, 50% free 9513K/18912K, paused 2ms+3ms, total 23ms
D/SurfaceWidgetClient$ISurfaceWidgetStub( 1442): [237392/5] Surface widget visibility changed visibility = false on instance = 1
D/LockPatternUtils( 1063): isPcwEnable = null
I/SurfaceFlinger(  244): id=14 Removed CatteryCove (8/13)
I/SurfaceFlinger(  244): id=14 Removed CatteryCove (-2/13)
I/SQLiteSecureOpenHelper( 2012): getWritableDatabase(pwd)
I/SQLiteSecureOpenHelper( 2012): getDatabaseLocked(b,b,pwd)...
D/KeyguardUpdateMonitor( 1063): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1063): handleKeyguardVisibilityChanged(1)
D/SurfaceWidgetView( 1259): destroyHardwareResources():1126261096
I/SELinux ( 4684): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 4684):  
W/ActivityManager(  745): Permission Denial: getCurrentUser() from pid=4670, uid=10179 requires android.permission.INTERACT_ACROSS_USERS
I/ActivityManager(  745): Killing 3173:com.sec.android.app.camera/u0a147 (adj 15): empty #43
W/ActivityManager(  745): Permission Denial: getCurrentUser() from pid=4670, uid=10179 requires android.permission.INTERACT_ACROSS_USERS
V/WebViewChromium( 4670): Binding Chromium to the background looper Looper (main, tid 1) {422ef8a0}
I/chromium( 4670): [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserProcessMain( 4670): Initializing chromium process, renderers=0
I/SELinux ( 4684): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 4684):  
I/SELinux ( 4684):  
I/SELinux ( 4684): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 4684): [DEBUG] seapp_context_lookup: seinfoCategory = default
E/dalvikvm( 4684): >>>>> Normal User
E/dalvikvm( 4684): >>>>> com.osp.app.signin [ userId:0 | appId:10043 ]
E/SELinux ( 4684): [DEBUG] seapp_context_lookup: seinfoCategory = default
W/chromium( 4670): [WARNING:proxy_service.cc(888)] PAC support disabled because there is no system implementation
D/TimaKeyStoreProvider( 4684): in addTimaSignatureService
D/TimaKeyStoreProvider( 4684): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 4684): Added TimaKesytore provider
,I/SA      ( 4684): [SSP] onCreated
,I/SA      ( 4684): [TPM] There is no property file
,I/SA      ( 4684): [SCU] isHaveSA() - false
I/SA      ( 4684): [TPM] getModelProperty : null
,I/SA      ( 4684): [TPM] getCSCProperty : null
,I/SA      ( 4684): [PMR] Received action : android.intent.action.PACKAGE_ADDED
,I/SA      ( 4684): [DM] init START
,I/SA      ( 4684): [DM] This device is not a Vodafone
I/SA      ( 4684): [DM] getCountryCodeFromCSC : PL
,I/SA      ( 4684): support phone number id : false
I/SA      ( 4684): [DM] init END
,I/SA      ( 4684): [SUR] onReceive log=[SA = 2.0.0117 V = 19 HWD = 1280X720 2.0 dpi = 320  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = kmini3g P = kmini3gxx I = KOT49H M = SM-G800H OKLEFT false DIS KOT49H.G800HXXU1ANK2 PSS = 4.497045606779314  ]
,I/SA      ( 4684): [SUR] onReceive Intent=[ action.PACKAGE_ADDED. package ]
I/ActivityManager(  745): Killing 3270:com.android.email/u0a155 (adj 15): empty #43
,D/Mms/PackageInstallReceiver( 3777): loadAuthorityPref(): sEnableAuthority = true
,I/IcingCorporaProvider( 2116): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
,W/ContextImpl( 2831): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1857 android.content.ContextWrapper.startService:506 android.content.ContextWrapper.startService:506 com.samsung.android.app.assistantmenu.AssistantMenuReceiver.onReceive:153 android.app.ActivityThread.handleReceiver:2698 
,I/SELinux ( 4713): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 4713):  
,I/SELinux ( 4713): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 4713):  
I/SELinux ( 4713):  
,I/SELinux ( 4713): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 4713): [DEBUG] seapp_context_lookup: seinfoCategory = samsung
E/dalvikvm( 4713): >>>>> Normal User
,E/dalvikvm( 4713): >>>>> com.sec.android.service.cm [ userId:0 | appId:10078 ]
,E/SELinux ( 4713): [DEBUG] seapp_context_lookup: seinfoCategory = samsung
,D/TimaKeyStoreProvider( 4713): in addTimaSignatureService
,I/IcingCorporaProvider( 2116): UpdateCorporaTask done [took 100 ms] updated apps [took 100 ms] 
,D/TimaKeyStoreProvider( 4713): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 4713): Added TimaKesytore provider
,D/CapabilityManagerService New( 4713): Receiver Broadcast:android.intent.action.PACKAGE_ADDED
W/ActivityManager(  745): Permission Denial: getCurrentUser() from pid=4713, uid=10078 requires android.permission.INTERACT_ACROSS_USERS
,I/SELinux ( 4725): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 4725):  
I/ActivityManager(  745): Killing 3266:com.samsung.android.provider.shootingmodeprovider/u0a162 (adj 15): empty #43
,I/SELinux ( 4725): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 4725):  
I/SELinux ( 4725):  
,I/SELinux ( 4725): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 4725): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 4725): >>>>> Normal User
,E/dalvikvm( 4725): >>>>> com.google.android.apps.docs [ userId:0 | appId:10090 ]
,E/SELinux ( 4725): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
,D/TimaKeyStoreProvider( 4725): in addTimaSignatureService
,D/TimaKeyStoreProvider( 4725): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 4725): Added TimaKesytore provider
,W/ActivityManager(  745): Permission Denial: getCurrentUser() from pid=4725, uid=10090 requires android.permission.INTERACT_ACROSS_USERS
,I/Adreno-EGL( 4670): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 4670): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 4670): Build Date: 03/21/14 Fri
I/Adreno-EGL( 4670): Local Branch: AU200+patches_03212014
I/Adreno-EGL( 4670): Remote Branch: 
I/Adreno-EGL( 4670): Local Patches: 
I/Adreno-EGL( 4670): Reconstruct Branch: 
,I/SurfaceFlinger(  244): id=17 Removed TettingsRec (8/12)
I/SecureStorage(  316): [INFO]: SPID(0x00000003)Secure Storage Daemon finished processing with result: 0
,I/SecureStorage(  316): [INFO]: SPID(0x00000003)PID: 4558, TID: 4558
,I/SurfaceFlinger(  244): id=17 Removed TettingsRec (-2/12)
D/KeyguardUpdateMonitor( 1063): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1063): handleKeyguardVisibilityChanged(1)
I/SurfaceFlinger(  244): id=7 Removed Mauncher (7/11)
I/SurfaceFlinger(  244): id=7 Removed Mauncher (-2/11)
D/KeyguardUpdateMonitor( 1063): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1063): handleKeyguardVisibilityChanged(1)
,D/Launcher( 1259): onTrimMemory. Level: 20
,I/dalvikvm( 4670): Could not find method android.webkit.CookieManager.setAcceptThirdPartyCookies, referenced from method org.apache.cordova.engine.SystemCookieManager.<init>
W/dalvikvm( 4670): VFY: unable to resolve virtual method 218: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
,D/dalvikvm( 4670): VFY: replacing opcode 0x6e at 0x0016
I/dalvikvm( 4670): Could not find method android.webkit.CookieManager.flush, referenced from method org.apache.cordova.engine.SystemCookieManager.flush
W/dalvikvm( 4670): VFY: unable to resolve virtual method 213: Landroid/webkit/CookieManager;.flush ()V
,D/dalvikvm( 4670): VFY: replacing opcode 0x6e at 0x0008
,W/dalvikvm( 4670): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 4670): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
I/dalvikvm( 4670): Could not find method android.webkit.WebViewClient.onReceivedClientCertRequest, referenced from method org.apache.cordova.engine.SystemWebViewClient.onReceivedClientCertRequest
W/dalvikvm( 4670): VFY: unable to resolve virtual method 271: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
,D/dalvikvm( 4670): VFY: replacing opcode 0x6f at 0x001a
,W/dalvikvm( 4670): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
I/dalvikvm( 4670): Could not find method android.webkit.PermissionRequest.getResources, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onPermissionRequest
W/dalvikvm( 4670): VFY: unable to resolve virtual method 229: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
D/dalvikvm( 4670): VFY: replacing opcode 0x6e at 0x000d
I/dalvikvm( 4670): Could not find method android.webkit.WebChromeClient$FileChooserParams.createIntent, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onShowFileChooser
W/dalvikvm( 4670): VFY: unable to resolve virtual method 234: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
,D/dalvikvm( 4670): VFY: replacing opcode 0x6e at 0x0000
,D/SystemWebViewEngine( 4670): CordovaWebView is running on device made by: samsung
,I/SecureStorage( 4558): [INFO]: SPID(0x00000000)Processing data has been completed
,I/SecureStorage( 4558): [INFO]: SPID(0x00000000)WARNING! Failed to find SecureStorageExceptionJNI!..
I/SQLiteSecureOpenHelper( 4558): getWritableDatabase(pwd)
,I/SQLiteSecureOpenHelper( 4558): getDatabaseLocked(b,b,pwd)...
,I/SQLiteSecureOpenHelper( 4558): Open platform.db in secure mode
,I/SurfaceFlinger(  244): id=18 createSurf (1x1),1 flag=404, NainActivit
,D/KeyguardUpdateMonitor( 1063): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1063): handleKeyguardVisibilityChanged(1)
,D/KeyguardUpdateMonitor( 1063): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1063): handleKeyguardVisibilityChanged(1)
,I/HWUI    ( 4670): EGLImpl-HWUI Protected EGL context created
,D/OpenGLRenderer( 4670): Enabling debug mode 0
,D/OpenGLRenderer( 4670): GL error from OpenGLRenderer: 0x502
,E/OpenGLRenderer( 4670):   GL_INVALID_OPERATION
D/KeyguardUpdateMonitor( 1063): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1063): handleKeyguardVisibilityChanged(1)
,D/CustomFrequencyManagerService(  745): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 745  tag : ACTIVITY_RESUME_BOOSTER@5
,W/ActivityManager(  745): mDVFSHelper.release()
,D/KeyguardUpdateMonitor( 1063): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1063): handleKeyguardVisibilityChanged(1)
D/CustomFrequencyManagerService(  745): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 745  pkgName : ACTIVITY_RESUME_BOOSTER@9
,I/SQLiteSecureOpenHelper( 4558): ...getDatabaseLocked(b,b,pwd)
,D/SQLiteSecureOpenHelper( 4558): ...getDatabaseLocked(b,b,pwd)
,I/ActivityManager(  745): Killing 3298:com.sec.modem.settings/1000 (adj 15): empty #43
,D/AmoledAdjustTimer(  745): prevTemp = 282, currTemp = 283, prevStep = 4, currStep = 4
,W/GAV2    ( 4725): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,I/SELinux ( 4768): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 4768):  
,I/SELinux ( 4768): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 4768):  
I/SELinux ( 4768):  
,I/SELinux ( 4768): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 4768): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 4768): >>>>> Normal User
,E/dalvikvm( 4768): >>>>> com.samsung.android.app.watchmanagerstub [ userId:0 | appId:10100 ]
,E/SELinux ( 4768): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 4768): in addTimaSignatureService
,D/TimaKeyStoreProvider( 4768): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 4768): Added TimaKesytore provider
,D/PackageIntentReceiver( 4768): ACTION_PACKAGE_ADDED
,D/PackageIntentReceiver( 4768): Not GearManger package! 
,D/JsMessageQueue( 4670): Set native->JS mode to OnlineEventsBridgeMode
,I/SELinux ( 4785): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 4785):  
I/ActivityManager(  745): Killing 1337:com.sec.android.provider.badge/u0a72 (adj 15): empty #43
,I/SELinux ( 4785): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 4785):  
I/SELinux ( 4785):  
,I/SELinux ( 4785): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 4785): [DEBUG] seapp_context_lookup: seinfoCategory = release
E/dalvikvm( 4785): >>>>> Normal User
,E/dalvikvm( 4785): >>>>> com.samsung.android.magazine.service [ userId:0 | appId:10106 ]
,E/SELinux ( 4785): [DEBUG] seapp_context_lookup: seinfoCategory = release
,D/TimaKeyStoreProvider( 4785): in addTimaSignatureService
,D/TimaKeyStoreProvider( 4785): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 4785): Added TimaKesytore provider
,D/dalvikvm( 4670): Trying to load lib /data/app-lib/com.test.thalitest-48/libjxcore.so 0x426165d8
,D/dalvikvm( 4670): Added shared lib /data/app-lib/com.test.thalitest-48/libjxcore.so 0x426165d8
D/jxcore_app_log( 4670): JniHelper::setJavaVM(0x4175f528), pthread_self() = 1948950536
,D/JX-Cordova( 4670): jxcore cordova android initializing
D/MagazineService Version( 4785): Magazine-Channel: 13
D/MagazineService Version( 4785): Magazine-Provider: 13
D/MagazineService Version( 4785): Magazine-Administrator: 11
D/HeadlinesChannelApplication( 4785): [onCreate]
D/MagazineService::MagazineBroadcastReceiver( 4785): [onReceive] android.intent.action.PACKAGE_ADDED com.test.thalitest
W/ActivityManager(  745): Permission Denial: getCurrentUser() from pid=4785, uid=10106 requires android.permission.INTERACT_ACROSS_USERS
I/MagazineService::MagazineService( 4785): [onHandleIntent] ACTION_PACKAGE_INSTALLED
I/SELinux ( 4798): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 4798):  
D/MagazineService::MagazineService( 4785): [onHandleIntent] Send broadcast to (com.test.thalitest).
I/ActivityManager(  745): Killing 3321:tv.peel.smartremote/u0a163 (adj 15): empty #43
W/GAV2    ( 4725): Thread[main,5,main]: dispatch call queued.  Need to call GAServiceManager.getInstance().initialize().
I/ActivityManager(  745): Killing 3349:org.simalliance.openmobileapi.service/1101 (adj 15): empty #43
I/SELinux ( 4798): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 4798):  
I/SELinux ( 4798):  
I/SELinux ( 4798): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 4798): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 4798): >>>>> Normal User
E/dalvikvm( 4798): >>>>> com.samsung.helphub [ userId:0 | appId:1000 ]
E/SELinux ( 4798): [DEBUG] seapp_context_lookup: seinfoCategory = platform
D/TimaKeyStoreProvider( 4798): in addTimaSignatureService
D/TimaKeyStoreProvider( 4798): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 4798): Added TimaKesytore provider
I/SELinux ( 4813): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 4813):  
I/ActivityManager(  745): Killing 3420:com.sec.android.app.taskmanager/u0a166 (adj 15): empty #43
E/SMD     (  238): DCD ON
I/SELinux ( 4813): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 4813):  
I/SELinux ( 4813):  
I/SELinux ( 4813): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 4813): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 4813): >>>>> Normal User
E/dalvikvm( 4813): >>>>> com.sec.kidsplat.installer [ userId:0 | appId:10158 ]
E/SELinux ( 4813): [DEBUG] seapp_context_lookup: seinfoCategory = platform
D/dalvikvm( 4670): GC_CONCURRENT freed 4944K, 33% free 12750K/18912K, paused 3ms+2ms, total 35ms
D/dalvikvm( 4670): WAIT_FOR_CONCURRENT_GC blocked 19ms
D/TimaKeyStoreProvider( 4813): in addTimaSignatureService
D/dalvikvm( 4670): WAIT_FOR_CONCURRENT_GC blocked 17ms
D/TimaKeyStoreProvider( 4813): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 4813): Added TimaKesytore provider
W/ActivityManager(  745): Permission Denial: getCurrentUser() from pid=4813, uid=10158 requires android.permission.INTERACT_ACROSS_USERS
D/KidsPlatformStub( 4813): Package not found : com.sec.android.app.kidshome
I/SELinux ( 4825): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 4825):  
I/ActivityManager(  745): Killing 3435:com.samsung.android.service.travel/u0a169 (adj 15): empty #43
I/SELinux ( 4825): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 4825):  
I/SELinux ( 4825):  
I/SELinux ( 4825): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 4825): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 4825): >>>>> Normal User
E/dalvikvm( 4825): >>>>> com.samsung.android.provider.shootingmodeprovider [ userId:0 | appId:10162 ]
E/SELinux ( 4825): [DEBUG] seapp_context_lookup: seinfoCategory = platform
D/TimaKeyStoreProvider( 4825): in addTimaSignatureService
D/TimaKeyStoreProvider( 4825): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 4825): Added TimaKesytore provider
I/SELinux ( 4837): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 4837):  
I/ActivityManager(  745): Killing 3449:com.google.android.youtube/u0a175 (adj 15): empty #43
I/SELinux ( 4837): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 4837):  
I/SELinux ( 4837):  
I/SELinux ( 4837): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 4837): [DEBUG] seapp_context_lookup: seinfoCategory = samsung
D/CustomFrequencyManagerService(  745): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 745  tag : ACTIVITY_RESUME_BOOSTER@9
E/dalvikvm( 4837): >>>>> Normal User
E/dalvikvm( 4837): >>>>> com.sec.android.app.samsungapps [ userId:0 | appId:10040 ]
E/SELinux ( 4837): [DEBUG] seapp_context_lookup: seinfoCategory = samsung
D/TimaKeyStoreProvider( 4837): in addTimaSignatureService
D/TimaKeyStoreProvider( 4837): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 4837): Added TimaKesytore provider
I/ActivityManager(  745): Killing 3625:com.sec.android.widgetapp.activeapplicationwidget/u0a152 (adj 15): empty #43
D/Finsky  ( 3513): [1] ExternalReferrer.access$200: Package state data is missing for com.test.thalitest
,D/ChimeraCfgMgr( 1780): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 1780): Loading module APK com.google.android.play.games
,D/PackageBroadcastService( 1780): Received broadcast action=android.intent.action.PACKAGE_ADDED and uri=com.test.thalitest
I/dalvikvm( 1780): Could not find method android.app.admin.DevicePolicyManager.getProfileOwner, referenced from method com.google.android.gms.auth.WorkAccountAuthenticatorInitializer.a
W/dalvikvm( 1780): VFY: unable to resolve virtual method 174: Landroid/app/admin/DevicePolicyManager;.getProfileOwner ()Landroid/content/ComponentName;
,D/dalvikvm( 1780): VFY: replacing opcode 0x6e at 0x0053
,I/dalvikvm( 1780): Failed resolving Lcom/google/android/gms/common/permission/PermissionUtils$1; interface 96 'Landroid/content/pm/PackageManager$OnPermissionsChangedListener;'
,W/dalvikvm( 1780): Link of class 'Lcom/google/android/gms/common/permission/PermissionUtils$1;' failed
E/dalvikvm( 1780): Could not find class 'com.google.android.gms.common.permission.PermissionUtils$1', referenced from method com.google.android.gms.chimera.GmsModuleInitializer.initializeModuleV0
W/dalvikvm( 1780): VFY: unable to resolve new-instance 2374 (Lcom/google/android/gms/common/permission/PermissionUtils$1;) in Lcom/google/android/gms/chimera/GmsModuleInitializer;
,D/dalvikvm( 1780): VFY: replacing opcode 0x22 at 0x001a
I/dalvikvm( 1780): Failed resolving Lcom/google/android/gms/common/permission/PermissionUtils$1; interface 96 'Landroid/content/pm/PackageManager$OnPermissionsChangedListener;'
,W/dalvikvm( 1780): Link of class 'Lcom/google/android/gms/common/permission/PermissionUtils$1;' failed
,D/dalvikvm( 1780): DexOpt: unable to opt direct call 0x338d at 0x1c in Lcom/google/android/gms/chimera/GmsModuleInitializer;.initializeModuleV0
,D/SSRMv2:SIOP(  745): SIOP:: AP = 310, Delta = 10
,D/BatteryService(  745): level:100, scale:100, status:5, health:2, present:true, voltage: 4366, temperature: 284, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:8, charge type:1, power sharing:false
D/BatteryService(  745): stay LED for fully charged
,D/BatteryService(  745): Sending ACTION_BATTERY_CHANGED.
D/UiModeManager(  745): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 1063): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1063): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 1063):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
D/BatteryMeterView( 1063): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1063): checkOverflow(384), More:false, Req:false Child:2
,D/dalvikvm( 4670): GC_FOR_ALLOC freed 4729K, 28% free 15766K/21732K, paused 35ms, total 35ms
,D/ChimeraCfgMgr( 1780): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 1780): Module APK com.google.android.play.games already loaded
,D/ChimeraCfgMgr( 1780): Loading module com.google.android.gms.gass from APK com.google.android.gms
,D/AsyncTaskServiceImpl( 1780): Submit a task: k
,D/ChimeraCfgMgr( 1780): Loading module com.google.android.gms.gass from APK com.google.android.gms
,D/ChimeraCfgMgr( 1780): Loading module com.google.android.gms.vision from APK com.google.android.gms
,D/k       ( 1780): Processing package: com.test.thalitest
,W/BaseAppContext( 1780): Using Auth Proxy for data requests.
,W/BaseAppContext( 1780): Using Auth Proxy for data requests.
,D/GassUtils( 1780): Found app info for package com.test.thalitest:18. Hash: 4eebbbb84f07ed56a3e96e5e8f9d6abddaaf154fffa2a65432a1006e0fa38f32
,D/k       ( 1780): Found info for package com.test.thalitest in db.
,D/dalvikvm( 1303): GC_EXPLICIT freed 1018K, 44% free 10758K/18912K, paused 4ms+8ms, total 52ms
,W/BaseAppContext( 1780): Using Auth Proxy for data requests.
,W/BaseAppContext( 1780): Using Auth Proxy for data requests.
,W/BaseAppContext( 1780): Using Auth Proxy for data requests.
,W/BaseAppContext( 1780): Using Auth Proxy for data requests.
,W/BaseAppContext( 1780): Using Auth Proxy for data requests.
,W/dalvikvm( 1780): VFY: unable to find class referenced in signature (Landroid/app/SharedElementCallback;)
,I/dalvikvm( 1780): Could not find method android.app.Activity.setEnterSharedElementCallback, referenced from method android.support.v4.app.w.setEnterSharedElementCallback
,W/dalvikvm( 1780): VFY: unable to resolve virtual method 53: Landroid/app/Activity;.setEnterSharedElementCallback (Landroid/app/SharedElementCallback;)V
,D/dalvikvm( 1780): VFY: replacing opcode 0x6e at 0x000e
,W/dalvikvm( 1780): VFY: unable to find class referenced in signature (Landroid/app/SharedElementCallback;)
,I/dalvikvm( 1780): Could not find method android.app.Activity.setExitSharedElementCallback, referenced from method android.support.v4.app.w.setExitSharedElementCallback
,W/dalvikvm( 1780): VFY: unable to resolve virtual method 54: Landroid/app/Activity;.setExitSharedElementCallback (Landroid/app/SharedElementCallback;)V
D/dalvikvm( 1780): VFY: replacing opcode 0x6e at 0x000e
I/dalvikvm( 1780): Could not find method android.app.Activity.finishAfterTransition, referenced from method android.support.v4.app.w.supportFinishAfterTransition
W/dalvikvm( 1780): VFY: unable to resolve virtual method 31: Landroid/app/Activity;.finishAfterTransition ()V
,D/dalvikvm( 1780): VFY: replacing opcode 0x6e at 0x0006
I/dalvikvm( 1780): Could not find method android.app.Activity.postponeEnterTransition, referenced from method android.support.v4.app.w.supportPostponeEnterTransition
W/dalvikvm( 1780): VFY: unable to resolve virtual method 49: Landroid/app/Activity;.postponeEnterTransition ()V
D/dalvikvm( 1780): VFY: replacing opcode 0x6e at 0x0006
,I/dalvikvm( 1780): Could not find method android.app.Activity.startPostponedEnterTransition, referenced from method android.support.v4.app.w.supportStartPostponedEnterTransition
,W/dalvikvm( 1780): VFY: unable to resolve virtual method 61: Landroid/app/Activity;.startPostponedEnterTransition ()V
,D/dalvikvm( 1780): VFY: replacing opcode 0x6e at 0x0006
,I/PeopleDatabaseHelper( 1780): cleanUpNonGplusAccounts done.
,D/dalvikvm( 4670): GC_FOR_ALLOC freed 5082K, 32% free 16779K/24420K, paused 36ms, total 39ms
,I/dalvikvm-heap( 4670): Grow heap (frag case) to 21.934MB for 2475476-byte allocation
,W/dalvikvm( 1780): VFY: unable to find class referenced in signature (Landroid/util/Size;)
,D/ChimeraCfgMgr( 1780): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 1780): Module APK com.google.android.play.games already loaded
,D/dalvikvm( 4670): GC_FOR_ALLOC freed 3779K, 35% free 17464K/26840K, paused 32ms, total 35ms
,D/dalvikvm(  745): GC_EXPLICIT freed 2031K, 58% free 23306K/55200K, paused 7ms+16ms, total 158ms
,D/dalvikvm( 1780): GC_CONCURRENT freed 1838K, 38% free 11763K/18912K, paused 5ms+5ms, total 46ms
,D/dalvikvm( 4670): GC_FOR_ALLOC freed 1241K, 36% free 17368K/26840K, paused 28ms, total 28ms
,W/jxcore-log( 4670): Initializing JXcore engine
,W/jxcore-log( 4670): JXcore engine is ready
,W/jxcore-log( 4670): Starting JXcore engine
,I/Icing   ( 1780): Indexing 49CA7E3A917E607C6D98AA15891295369CED2106 from com.google.android.gms
,I/Icing   ( 1780): Indexing done 49CA7E3A917E607C6D98AA15891295369CED2106
,W/jxcore-log( 4670): Platform android
W/jxcore-log( 4670): 
,W/jxcore-log( 4670): Process ARCH arm
W/jxcore-log( 4670): 
,E/SMD     (  238): DCD ON
,I/jxcore-log( 4670): JXcore Cordova bridge is ready!
I/jxcore-log( 4670): 
,W/jxcore-log( 4670): JXcore engine is started
,I/chromium( 4670): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot call method 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/GAV2    ( 4725): Thread[GAThread,5,main]: No campaign data found.
,I/jxcore-log( 4670): Toggling radios to true
I/jxcore-log( 4670): 
,W/ActivityManager(  745): Permission Denial: getCurrentUser() from pid=4670, uid=10179 requires android.permission.INTERACT_ACROSS_USERS
,W/BluetoothManagerService(  745): Failed getting userId using ActivityManagerNative
W/BluetoothManagerService(  745): java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=4670, uid=10179 requires android.permission.INTERACT_ACROSS_USERS
W/BluetoothManagerService(  745): 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:20710)
W/BluetoothManagerService(  745): 	at com.android.server.BluetoothManagerService.enable(BluetoothManagerService.java:620)
W/BluetoothManagerService(  745): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:98)
W/BluetoothManagerService(  745): 	at android.os.Binder.execTransact(Binder.java:404)
W/BluetoothManagerService(  745): 	at dalvik.system.NativeStart.run(Native Method)
E/DevicePolicyManagerService(  745): getAllowBluetoothMode - value retunrs : 2
,D/BluetoothManagerService(  745): foregroundUser: 0
,E/BluetoothManagerService(  745): Package is exist.
,D/BluetoothAdapterState( 3154): CURRENT_STATE=OFF, MSG = USER_TURN_ON
I/BluetoothAdapterState( 3154): Bluetooth adapter state changed: 10-> 11
,D/BluetoothAdapterService( 3154): Bluetooth PBAP supproted is true
D/BluetoothAdapterService( 3154): updateAdapterState state is 11
,D/BluetoothAdapterService( 3154): Broadcasting updateAdapterState() to 1 receivers.
D/BluetoothAdapterService( 3154): Autoconnection is available 
,D/BluetoothAdapterService( 3154): updateAdapterState prevState = 10newState = 11
D/BtConfig.SecureMode( 3154): isSecureModeOn:false
,D/BtSettings.ProfileConfig( 3154): getProfileSaveSetting: com.android.bluetooth.gatt.GattService
,W/BluetoothAdapterService( 3154): isProfileEnabled(): profile com.android.bluetooth.gatt.GattService, state= 12
,D/BtSettings.ProfileConfig( 3154): getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
,W/BluetoothAdapterService( 3154): isProfileEnabled(): profile not found com.android.bluetooth.hfp.HeadsetService
,D/BtSettings.ProfileConfig( 3154): getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
,W/BluetoothAdapterService( 3154): isProfileEnabled(): profile not found com.android.bluetooth.a2dp.A2dpService
,D/BtSettings.ProfileConfig( 3154): getProfileSaveSetting: com.android.bluetooth.hid.HidService
,W/BluetoothAdapterService( 3154): isProfileEnabled(): profile not found com.android.bluetooth.hid.HidService
,D/BtSettings.ProfileConfig( 3154): getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
,W/BluetoothAdapterService( 3154): isProfileEnabled(): profile not found com.android.bluetooth.hdp.HealthService
,D/BtSettings.ProfileConfig( 3154): getProfileSaveSetting: com.android.bluetooth.pan.PanService
,W/BluetoothAdapterService( 3154): isProfileEnabled(): profile not found com.android.bluetooth.pan.PanService
,D/BtSettings.ProfileConfig( 3154): getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
,W/BluetoothAdapterService( 3154): isProfileEnabled(): profile not found com.android.bluetooth.map.BluetoothMapService
W/BluetoothAdapterService( 3154): Unable to stop service com.android.bluetooth.gatt.GattService. Invalid state: 12
W/BluetoothAdapterService( 3154): check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.hfp.HeadsetService
,D/BtSettings.ProfileConfig( 3154): getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
,W/BluetoothAdapterService( 3154): Not skipping com.android.bluetooth.hfp.HeadsetService
,W/InputMethodManagerService(  745): InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
,I/InputMethodManagerService(  745): [BT Setting State] State =11
W/BluetoothAdapterService( 3154): check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.a2dp.A2dpService
D/BtSettings.ProfileConfig( 3154): getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
W/BluetoothAdapterService( 3154): Not skipping com.android.bluetooth.a2dp.A2dpService
I/WifiManager( 4670): packageName : com.test.thalitest
I/WifiManager( 4670): setWifiEnabled : true
D/PhoneApp( 1237): mReceiver: BluetoothAdapter.ACTION_STATE_CHANGED: 11
I/WifiService(  745): setWifiEnabled: true pid=4670, uid=10179
,I/QuickConnect[1.1][2] ( 3125): BluetoothHelper.ACTION_STATE_CHANGED - STATE_TURNING_ON
W/ActivityManager(  745): Permission Denial: getCurrentUser() from pid=4670, uid=10179 requires android.permission.INTERACT_ACROSS_USERS
,W/WifiService(  745): Failed getting userId using ActivityManagerNative
W/WifiService(  745): java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=4670, uid=10179 requires android.permission.INTERACT_ACROSS_USERS
W/WifiService(  745): 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:20710)
W/WifiService(  745): 	at com.android.server.wifi.WifiService.setWifiEnabled(WifiService.java:2348)
W/WifiService(  745): 	at com.android.server.wifi.WifiService.setWifiEnabled(WifiService.java:2336)
W/WifiService(  745): 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:178)
W/WifiService(  745): 	at android.os.Binder.execTransact(Binder.java:404)
W/WifiService(  745): 	at dalvik.system.NativeStart.run(Native Method)
,D/QuickConnect[1.1][2] ( 3125): HeadsetProfile.onServiceConnected - Bluetooth service connected
,D/HeadsetService( 3154): Received start request. Starting profile...
,I/BluetoothHeadsetServiceJni( 3154): classInitNative: succeeds
D/HeadsetStateMachine( 3154): Version 1.6
,D/HeadsetStateMachine( 3154): make
W/BluetoothAdapterService( 3154): check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.hid.HidService
D/BtSettings.ProfileConfig( 3154): getProfileSaveSetting: com.android.bluetooth.hid.HidService
,W/BluetoothAdapterService( 3154): Not skipping com.android.bluetooth.hid.HidService
,E/HeadsetStateMachine( 3154): # of Max HF connection is 2
,W/BluetoothAdapterService( 3154): check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.hdp.HealthService
,D/BtSettings.ProfileConfig( 3154): getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
,W/BluetoothAdapterService( 3154): Not skipping com.android.bluetooth.hdp.HealthService
,W/BluetoothAdapterService( 3154): check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.pan.PanService
,D/BtSettings.ProfileConfig( 3154): getProfileSaveSetting: com.android.bluetooth.pan.PanService
,W/BluetoothAdapterService( 3154): Not skipping com.android.bluetooth.pan.PanService
,D/BluetoothNotiBroadcastReceiver( 1307): onReceive
,E/WifiHW  (  745): ##################### set firmware type 0 #####################
,W/BluetoothAdapterService( 3154): check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.map.BluetoothMapService
I/bluedroid( 3154): get_profile_interface handsfree
,D/BtSettings.ProfileConfig( 3154): getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
,W/BluetoothAdapterService( 3154): Not skipping com.android.bluetooth.map.BluetoothMapService
,I/WifiService(  745): disconnect: pid=4670, uid=10179
,I/jxcore-log( 4670): Radios toggled
I/jxcore-log( 4670): 
,D/BluetoothAtMessage( 3154): createCMTIContentObservers
,I/BluetoothAdapterState( 3154): Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
,D/HeadsetStateMachine( 3154): Enter Disconnected: -2
,E/HeadsetStateMachine( 3154): set to mRemoteBrsf = 0
D/HeadsetStateMachine( 3154): map size, before remove : 0
D/HeadsetStateMachine( 3154): map size, after remove: 0
,D/HeadsetStateMachine( 3154): mNextConnectingDevice : null
,I/jxcore-log( 4670): Got Device Bluetooth address: 38:94:96:B5:06:DC
I/jxcore-log( 4670): 
,I/jxcore-log( 4670): Perf Test app loaded loaded
I/jxcore-log( 4670): 
D/BluetoothA2dp(  745): Proxy object connected
,D/BluetoothA2dp( 3125): Proxy object connected
,D/BluetoothA2dp( 2012): Proxy object connected
D/A2dpService( 3154): Received start request. Starting profile...
I/BluetoothA2dpServiceJni( 3154): classInitNative: succeeds
,D/A2dpStateMachine( 3154): make
,I/jxcore-log( 4670): check test folder
I/jxcore-log( 4670): 
,D/QuickConnect[1.1][2] ( 3125): A2dpProfile.onServiceConnected - Bluetooth service connected
,I/jxcore-log( 4670): found test : ./testFindPeers.js
I/jxcore-log( 4670): 
,I/bluedroid( 3154): get_profile_interface a2dp
I/GKI_LINUX( 3154): gki_task_entry: gki_task_entry task_id=2 [A2DP-MEDIA] starting
I/BluetoothAvrcpServiceJni( 3154): classInitNative: succeeds
D/A2dpStateMachine( 3154): Enter Disconnected: -2
,I/bluedroid( 3154): get_profile_interface avrcp
,D/MediaFocusControl(  745): >>> registerRemoteControlDisplay
,E/MediaFocusControl(  745): Error updating focussed RCC to RCD 
E/MediaFocusControl(  745): java.util.EmptyStackException
E/MediaFocusControl(  745): 	at java.util.Stack.peek(Stack.java:57)
E/MediaFocusControl(  745): 	at android.media.MediaFocusControl.registerRemoteControlDisplay_int(MediaFocusControl.java:2308)
E/MediaFocusControl(  745): 	at android.media.MediaFocusControl.registerRemoteControlDisplay(MediaFocusControl.java:250)
E/MediaFocusControl(  745): 	at android.media.AudioService.registerRemoteControlDisplay(AudioService.java:6425)
E/MediaFocusControl(  745): 	at android.media.IAudioService$Stub.onTransact(IAudioService.java:593)
E/MediaFocusControl(  745): 	at android.os.Binder.execTransact(Binder.java:404)
E/MediaFocusControl(  745): 	at dalvik.system.NativeStart.run(Native Method)
,I/BluetoothHidServiceJni( 3154): classInitNative: succeeds
,D/BluetoothInputDevice( 3125): Proxy object connected
D/HidService( 3154): Received start request. Starting profile...
I/bluedroid( 3154): get_profile_interface hidhost
,D/HidService( 3154): setHidService(): set to: null
I/BluetoothHealthServiceJni( 3154): classInitNative: succeeds
D/QuickConnect[1.1][2] ( 3125): HidProfile.onServiceConnected - Bluetooth service connected
,D/HealthService( 3154): Received start request. Starting profile...
,I/bluedroid( 3154): get_profile_interface health
,I/BluetoothPanServiceJni( 3154): classInitNative(L105): succeeds
D/BluetoothPan(  745): BluetoothPAN Proxy object connected
D/PanService( 3154): Received start request. Starting profile...
D/BluetoothPanServiceJni( 3154): initializeNative(L110): pan
I/bluedroid( 3154): get_profile_interface pan
D/BluetoothTethering(  745): got CMD_CHANNEL_HALF_CONNECTED
D/HeadsetStateMachine( 3154): Try to query the phonestate on bind
D/BluetoothPhoneService( 1237): handleMessage: 4
V/BluetoothPhoneService( 1237): Call state Converted2: IDLE/IDLE -> 6
W/BluetoothHeadset( 1237): Proxy not attached to service
D/HeadsetStateMachine( 3154): Proxy object connected
I/jxcore-log( 4670): found test : ./testSendData.js
I/jxcore-log( 4670): 
D/HeadsetPhoneState( 3154): sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=0
D/HeadsetStateMachine( 3154): Disconnected process message: 11
D/HeadsetPhoneState( 3154): sendDeviceDataStateChanged
D/HeadsetStateMachine( 3154): Disconnected process message: 20
D/HeadsetPhoneState( 3154): Signal level : previous=0 curr=0
D/BluetoothMapService( 3154): Received start request. Starting profile...
,D/AuthorizationBluetoothService( 1303): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,W/BluetoothMapMasInstance( 3154): mAccount : null
,V/HeadsetService( 3154): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3154): Disconnected process message: 10
D/HeadsetPhoneState( 3154): sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
,D/HeadsetStateMachine( 3154): Disconnected process message: 11
D/BluetoothAdapterService( 3154): Profile still not running:com.android.bluetooth.hdp.HealthService
D/BluetoothAdapterService( 3154): Profile still not running:com.android.bluetooth.hdp.HealthService
D/BluetoothAdapterService( 3154): Profile still not running:com.android.bluetooth.hdp.HealthService
D/BluetoothAdapterService( 3154): Profile still not running:com.android.bluetooth.map.BluetoothMapService
D/BluetoothAdapterService( 3154): Profile still not running:com.android.bluetooth.map.BluetoothMapService
D/BluetoothAdapterState( 3154): CURRENT_STATE=PENDING, MSG = STARTED, isTurningOn=true, isTurningOff=false
I/bluedroid( 3154): enable
D/GKI_LINUX( 3154): acquire_my_wake_lock(), g_wake_lock_fd:-1, g_wake_unlock_fd:-1, wake_lock_acquired:0
E/bt-btif ( 3154): Calling BTA_HhEnable
,E/bt-btif ( 3154): btif_storage_get_adapter_property service_mask:0x140040
,E/BluetoothServiceJni( 3154): populateRssiValuesNative
I/bluedroid( 3154): getModelRssiValues
,E/BluetoothServiceJni( 3154): model_rssi_values_callback: low = -70, mid = -60, high = 127
,E/BluetoothRemoteDevices( 3154): devicePropertyChangedCallback: bdDevice: 08:EC:A9:50:75:41, value is empty for type: 10
,D/BtConfig.SecureMode( 3154): isSecureModeOn:false
,E/BluetoothRemoteDevices( 3154): devicePropertyChangedCallback: bdDevice: 08:EC:A9:50:75:41, value is empty for type: 241
,E/BluetoothRemoteDevices( 3154): devicePropertyChangedCallback: bdDevice: 80:01:84:8A:B3:68, value is empty for type: 10
,D/BtConfig.SecureMode( 3154): isSecureModeOn:false
,E/BluetoothRemoteDevices( 3154): devicePropertyChangedCallback: bdDevice: 80:01:84:8A:B3:68, value is empty for type: 241
,E/BluetoothRemoteDevices( 3154): devicePropertyChangedCallback: bdDevice: 44:80:EB:7B:5A:05, value is empty for type: 10
D/BtConfig.SecureMode( 3154): isSecureModeOn:false
,E/BluetoothRemoteDevices( 3154): devicePropertyChangedCallback: bdDevice: 44:80:EB:7B:5A:05, value is empty for type: 241
,E/BluetoothRemoteDevices( 3154): devicePropertyChangedCallback: bdDevice: F8:95:C7:87:85:54, value is empty for type: 10
,D/BtConfig.SecureMode( 3154): isSecureModeOn:false
,E/BluetoothRemoteDevices( 3154): devicePropertyChangedCallback: bdDevice: F8:95:C7:87:85:54, value is empty for type: 241
,E/BluetoothRemoteDevices( 3154): devicePropertyChangedCallback: bdDevice: B0:C5:59:3F:75:69, value is empty for type: 10
,D/BtConfig.SecureMode( 3154): isSecureModeOn:false
,E/BluetoothRemoteDevices( 3154): devicePropertyChangedCallback: bdDevice: B0:C5:59:3F:75:69, value is empty for type: 241
,E/BluetoothRemoteDevices( 3154): devicePropertyChangedCallback: bdDevice: 00:F4:6F:30:E0:6C, value is empty for type: 10
,D/BtConfig.SecureMode( 3154): isSecureModeOn:false
,E/BluetoothRemoteDevices( 3154): devicePropertyChangedCallback: bdDevice: 00:F4:6F:30:E0:6C, value is empty for type: 241
,E/BluetoothRemoteDevices( 3154): devicePropertyChangedCallback: bdDevice: 34:FC:EF:9D:93:0B, value is empty for type: 10
,D/BtConfig.SecureMode( 3154): isSecureModeOn:false
,E/BluetoothRemoteDevices( 3154): devicePropertyChangedCallback: bdDevice: 34:FC:EF:9D:93:0B, value is empty for type: 241
,E/BluetoothRemoteDevices( 3154): devicePropertyChangedCallback: bdDevice: 7C:F9:0E:51:18:22, value is empty for type: 10
,D/BtConfig.SecureMode( 3154): isSecureModeOn:false
,E/BluetoothRemoteDevices( 3154): devicePropertyChangedCallback: bdDevice: 7C:F9:0E:51:18:22, value is empty for type: 241
,E/BluetoothRemoteDevices( 3154): devicePropertyChangedCallback: bdDevice: B4:CE:F6:AB:A4:6A, value is empty for type: 10
,D/BtConfig.SecureMode( 3154): isSecureModeOn:false
,E/BluetoothRemoteDevices( 3154): devicePropertyChangedCallback: bdDevice: B4:CE:F6:AB:A4:6A, value is empty for type: 241
D/GKI_LINUX( 3154): release_my_wake_lock(), g_wake_lock_fd:-1, g_wake_unlock_fd:-1, wake_lock_acquired:0
,E/BluetoothRemoteDevices( 3154): devicePropertyChangedCallback: bdDevice: 34:FC:EF:11:AE:67, value is empty for type: 10
,D/BtConfig.SecureMode( 3154): isSecureModeOn:false
,E/BluetoothRemoteDevices( 3154): devicePropertyChangedCallback: bdDevice: 34:FC:EF:11:AE:67, value is empty for type: 241
,E/BluetoothRemoteDevices( 3154): devicePropertyChangedCallback: bdDevice: 34:FC:EF:11:B1:66, value is empty for type: 10
,D/BtConfig.SecureMode( 3154): isSecureModeOn:false
,E/BluetoothRemoteDevices( 3154): devicePropertyChangedCallback: bdDevice: 34:FC:EF:11:B1:66, value is empty for type: 241
E/BluetoothRemoteDevices( 3154): devicePropertyChangedCallback: bdDevice: 90:E7:C4:F6:69:77, value is empty for type: 10
,D/BtConfig.SecureMode( 3154): isSecureModeOn:false
,E/BluetoothRemoteDevices( 3154): devicePropertyChangedCallback: bdDevice: 90:E7:C4:F6:69:77, value is empty for type: 241
E/bt-btif ( 3154): btif_handle_bluetooth_enable_evt: btif_core_radio_ref_count:2
E/bt-btif ( 3154): btif_sock_init, radio_req:0, rfc_init:0, vhci_init:1
E/bt-btif ( 3154): btif_sock_init: !radio_req && !rfc_init
,D/IOP_DB_BT( 3154): db_open: file /etc/bluetooth/iop_bt.db
D/IOP_DB_BT( 3154): db_open: db_open : handle 2012828440l, read 9734 bytes onto local cache
,D/IOP_DB_BT( 3154): db_query: id __IOPFLAGS :: key __KEY_ENABLE_VERBOSE, value 1
D/IOP_DB_BT( 3154): db_query: result 1
I/        ( 3154): iop_db_open: iop_db_open status 0
D/GKI_LINUX( 3154): acquire_my_wake_lock(), g_wake_lock_fd:-1, g_wake_unlock_fd:-1, wake_lock_acquired:0
,I/bte_conf( 3154): Attempt to load did conf from /etc/bluetooth/bt_did.conf
,I/bte_conf( 3154): [1] primary_record=1 vendor_id=0x0075 vendor_id_source=0x0001 product_id=0x0100 version=0x0200
I/bte_conf( 3154): Attempt to load did conf from /etc/bluetooth/bt_did.conf
,I/bte_conf( 3154): Attempt to load did conf from /etc/bluetooth/bt_did.conf
D/BluetoothAdapterState( 3154): CURRENT_STATE=PENDING, MSG = ENABLE_READY, isTurningOn=true, isTurningOff=false
D/BluetoothAdapterProperties( 3154): ScanMode =  20
,D/BluetoothAdapterProperties( 3154): State =  11
D/BtConfig.SecureMode( 3154): isSecureModeOn:false
D/BtConfig.SecureMode( 3154): isSecureModeOn:false
D/BtConfig.SecureMode( 3154): isSecureModeOn:false
D/BtConfig.SecureMode( 3154): isSecureModeOn:false
D/BtConfig.SecureMode( 3154): isSecureModeOn:false
D/BtConfig.SecureMode( 3154): isSecureModeOn:false
D/BtConfig.SecureMode( 3154): isSecureModeOn:false
D/BtConfig.SecureMode( 3154): isSecureModeOn:false
D/BtConfig.SecureMode( 3154): isSecureModeOn:false
D/BtConfig.SecureMode( 3154): isSecureModeOn:false
D/BtConfig.SecureMode( 3154): isSecureModeOn:false
D/BtConfig.SecureMode( 3154): isSecureModeOn:false
,I/BluetoothAdapterState( 3154): Bluetooth adapter state changed: 11-> 12
D/BluetoothAdapterService( 3154): Bluetooth PBAP supproted is true
,D/BluetoothAdapterService( 3154): updateAdapterState state is 12
,D/BluetoothAdapterService( 3154): Broadcasting updateAdapterState() to 1 receivers.
,D/BluetoothAdapterService(1113726080)( 3154): Register RemoteMessageListener
D/HeadsetService( 3154): registerMessageListener
D/BluetoothAdapterService( 3154): Autoconnection is available 
,D/BluetoothA2dp(  745): onBluetoothStateChange: up=true
D/HeadsetStateMachine( 3154): Disconnected process message: 70
D/HeadsetStateMachine( 3154): processRegisterMessageListener : 2, com.android.bluetooth.btservice.RemoteDevices$1@4266bc40
D/BluetoothAdapterService( 3154): updateAdapterState prevState = 11newState = 12
,D/BluetoothAdapterService( 3154): starting service from this receiver
,D/BluetoothA2dp( 3125): onBluetoothStateChange: up=true
,D/BluetoothInputDevice( 3125): onBluetoothStateChange: up=true
,D/BluetoothA2dp( 2012): onBluetoothStateChange: up=true
,D/BluetoothAdapterService( 3154): initWakeLock, pfd lock: {ParcelFileDescriptor: FileDescriptor[91]}, pfd unlock: {ParcelFileDescriptor: FileDescriptor[92]}
W/ContextImpl( 3154): Implicit intents with startService are not safe: Intent { act=com.samsung.ble.ACTION_SERVICE_BLE_AUTO_CONNECT } android.content.ContextWrapper.startService:506 com.android.bluetooth.btservice.AdapterService.updateAdapterState:653 com.android.bluetooth.btservice.AdapterState.notifyAdapterStateChange:586 
,D/bluedroid( 3154): init_wake_lock lock_fd:91, unlock_fd:92
,W/InputMethodManagerService(  745): InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
I/InputMethodManagerService(  745): [BT Setting State] State =12
,I/WifiTrafficPoller(  745): mBoosterFLAG : 2
,I/WifiTrafficPoller(  745): current booster mode : BTCoexMode
,D/PhoneApp( 1237): mReceiver: BluetoothAdapter.ACTION_STATE_CHANGED: 12
,I/InputMethodManagerService(  745): [BT Setting off -> on] mBTKeyboardCount =0, KEYBOARD_BT(0)
I/BluetoothAdapterState( 3154): Entering On State from state = 11
D/BluetoothHeadset( 1237): registerListener : 11, listenercom.android.phone.PhoneGlobals$MessageListener@42341b80, true
I/QuickConnect[1.1][2] ( 3125): BluetoothHelper.ACTION_STATE_CHANGED - STATE_ON
D/BluetoothHeadset( 1237): registerMessageListener
D/HeadsetService( 3154): registerMessageListener
D/HeadsetService( 3154): registerMessageListener
D/HeadsetStateMachine( 3154): Disconnected process message: 70
D/HeadsetStateMachine( 3154): processRegisterMessageListener : 11, com.samsung.bt.hfp.IMessageListener$Stub$Proxy@42705ac8
D/PhoneApp( 1237): registerMessageListener
D/BluetoothAdapterService(1113726080)( 3154): Get Bonded Devices being called
,D/BluetoothPanServiceJni( 3154): control_state_callback(L61): state:0, local_role:0, ifname:bt-pan
,I/BluetoothPbapService( 3154): action: android.bluetooth.adapter.action.STATE_CHANGED, state: 12
,W/ContextImpl( 1307): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1857 android.content.ContextWrapper.startService:506 android.content.ContextWrapper.startService:506 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,I/BluetoothPbapService( 3154): Handler(): got msg=1
,V/BluetoothPbapService( 3154): PBAP Service initSocket try: 0
D/STATUSBAR-IconMerger( 1063): checkOverflow(336), More:false, Req:false Child:2
,I/chromium( 4670): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,W/BluetoothAdapter( 3154): getBluetoothService() called with no BluetoothManagerCallback
,D/BluetoothMapMasInstance( 3154): set MAP SDP message type : 1
E/BluetoothServiceJni( 3154): SOCK FLAG = 1 ***********************
,D/BluetoothPbapService( 3154): PBAP Socket is BluetoothServerSocket
,W/BluetoothAdapter( 3154): getBluetoothService() called with no BluetoothManagerCallback
,E/BluetoothServiceJni( 3154): SOCK FLAG = 3 ***********************
,D/LocalBluetoothProfileManager( 1307): Adding local A2DP profile
,W/ContextImpl( 1307): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1930 android.content.ContextWrapper.bindService:529 android.bluetooth.BluetoothA2dp.doBind:221 android.bluetooth.BluetoothA2dp.<init>:214 android.bluetooth.BluetoothAdapter.getProfileProxy:1412 
D/LocalBluetoothProfileManager( 1307): Adding local HEADSET profile
,E/BluetoothHeadset( 1307): BTStateChangeCB is registed
,W/ContextImpl( 1307): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1930 android.content.ContextWrapper.bindService:529 android.bluetooth.BluetoothHeadset.doBind:304 android.bluetooth.BluetoothHeadset.<init>:297 android.bluetooth.BluetoothAdapter.getProfileProxy:1409 
E/BluetoothHeadset( 1307): BluetoothHeadset service is binded
,D/Bluetoothsap( 1307): bindService called to Bluetooth SAP Service
W/ContextImpl( 1307): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1930 android.content.ContextWrapper.bindService:529 com.broadcom.bt.service.sap.BluetoothSap.doBind:186 com.broadcom.bt.service.sap.BluetoothSap.<init>:179 com.android.settings.bluetooth.SapProfile.<init>:129 
,W/ContextImpl( 1307): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1930 android.content.ContextWrapper.bindService:529 android.bluetooth.BluetoothInputDevice.doBind:245 android.bluetooth.BluetoothInputDevice.<init>:238 android.bluetooth.BluetoothAdapter.getProfileProxy:1415 
,W/ContextImpl( 1307): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1930 android.content.ContextWrapper.bindService:529 android.bluetooth.BluetoothPan.doBind:173 android.bluetooth.BluetoothPan.<init>:162 android.bluetooth.BluetoothAdapter.getProfileProxy:1418 
D/LocalBluetoothProfileManager( 1307): PANU : true
D/LocalBluetoothProfileManager( 1307): Adding local MAP profile
,D/BluetoothMap( 1307): Create BluetoothMap proxy object
W/ContextImpl( 1307): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1930 android.content.ContextWrapper.bindService:529 android.bluetooth.BluetoothMap.doBind:109 android.bluetooth.BluetoothMap.<init>:102 android.bluetooth.BluetoothAdapter.getProfileProxy:1424 
,W/ContextImpl( 1307): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1930 android.content.ContextWrapper.bindService:529 android.bluetooth.BluetoothPbap.doBind:164 android.bluetooth.BluetoothPbap.<init>:157 com.android.settings.bluetooth.PbapServerProfile.<init>:68 
,D/Bluetoothsap( 1307): bindService called to Bluetooth SAP Service
,D/LocalBluetoothProfileManager( 1307): LocalBluetoothProfileManager construction complete
,D/DockEventReceiver( 1307): finishStartingService: stopping service
,D/BluetoothNotiBroadcastReceiver( 1307): onReceive
,D/BluetoothA2dp( 1307): Proxy object connected
,D/BtConfig.SecureMode( 3154): isSecureModeOn:false
,D/A2dpProfile( 1307): Bluetooth service connected
,W/ContextImpl( 1307): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1930 android.content.ContextWrapper.bindService:529 com.broadcom.bt.service.sap.BluetoothSap.doBind:186 com.broadcom.bt.service.sap.BluetoothSap.<init>:179 com.android.settings.bluetooth.SapProfile.<init>:129 
D/GKI_LINUX( 3154): release_my_wake_lock(), g_wake_lock_fd:91, g_wake_unlock_fd:92, wake_lock_acquired:0
,D/AuthorizationBluetoothService( 1303): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,E/AuthorizationBluetoothService( 1303): Proximity feature is not enabled.
,D/HeadsetProfile( 1307): Bluetooth service connected
,D/BluetoothInputDevice( 1307): Proxy object connected
,D/HidProfile( 1307): Bluetooth service connected
D/BluetoothPan( 1307): BluetoothPAN Proxy object connected
D/PanProfile( 1307): Bluetooth service connected
D/BluetoothMap( 1307): Proxy object connected
D/MapProfile( 1307): Bluetooth service connected
D/BluetoothPbap( 1307): Proxy object connected
,D/PbapServerProfile( 1307): Bluetooth service connected
,W/BluetoothAdapter( 3154): getBluetoothService() called with no BluetoothManagerCallback
,E/BluetoothServiceJni( 3154): SOCK FLAG = 0 ***********************
D/GKI_LINUX( 3154): acquire_my_wake_lock(), g_wake_lock_fd:91, g_wake_unlock_fd:92, wake_lock_acquired:0
,I/BtOppRfcommListener( 3154): Accept thread started.
,D/Tethering(  745): interfaceAdded wlan0
,E/Tethering(  745): No numeric data
,D/Tethering(  745): sendTetherStateChangedBroadcast 1, 0, 0
,D/NtpTrustedTime(  745): forceRefresh() from cache miss
,D/NtpTrustedTime(  745): forceRefresh Fail.
D/Tethering(  745): interfaceLinkStateChanged wlan0, false
,D/Tethering(  745): interfaceStatusChanged wlan0, false
D/Tethering(  745): InitialState.processMessage what=4
,E/Tethering(  745): No numeric data
I/ConnectivityService(  745): defaultVal : 1, tetherEnabledInSettings : true
V/NetworkStats(  745): performPollLocked(flags=0x1)
,I/ConnectivityService(  745): defaultVal : 1, tetherEnabledInSettings : true
D/Tethering(  745): sendTetherStateChangedBroadcast 0, 0, 0
D/Tethering(  745): interfaceAdded p2p0
D/Tethering(  745): p2p0 is not a tetherable iface, ignoring
D/Tethering(  745): interfaceLinkStateChanged p2p0, false
,D/Tethering(  745): interfaceStatusChanged p2p0, false
,I/WifiHW  (  235): wifi_change_fw_path(): fwpath = sta
,D/SoftapController(  235): Softap fwReload - Ok
,D/NtpTrustedTime(  745): forceRefresh() from cache miss
,V/NetworkStats(  745): performPollLocked() took 21ms
D/NtpTrustedTime(  745): forceRefresh Fail.
D/NtpTrustedTime(  745): forceRefresh() from cache miss
D/NtpTrustedTime(  745): forceRefresh Fail.
,D/GKI_LINUX( 3154): release_my_wake_lock(), g_wake_lock_fd:91, g_wake_unlock_fd:92, wake_lock_acquired:1
D/CommandListener(  235): Setting iface cfg
,D/CommandListener(  235): Trying to bring down wlan0
V/NetworkStats(  745): performPollLocked(flags=0x1)
,D/NtpTrustedTime(  745): forceRefresh() from cache miss
,D/NtpTrustedTime(  745): forceRefresh Fail.
,V/NetworkStats(  745): performPollLocked() took 15ms
D/WifiHW  (  745): Skip the update_ctrl_interface
D/WifiHW  (  745): Skip the update_ctrl_interface
E/WifiHW  (  745): supplicant_name : p2p_supplicant
,D/WifiMonitor(  745): startMonitoring(wlan0) with mConnected = false
D/STATUSBAR-NetworkController_dual( 1063): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
D/StatusBar.NetworkController_dual( 1063): mMobileLabelViews start
D/StatusBar.NetworkController_dual( 1063): mMobileLabelViews set mobileLabel[SIM_0] =No service.
D/StatusBar.NetworkController_dual( 1063): mMobileLabelViews GONE
D/StatusBar.NetworkController_dual( 1063): mMobileLabelViews2 set mobileLabel[SIM_1] =No service.
D/StatusBar.NetworkController_dual( 1063): mMobileLabelViews2 GONE
D/StatusBar.NetworkController_dual( 1063): mSingleMobileLabelViews set : simMode = 0
D/StatusBar.NetworkController_dual( 1063): mSingleMobileLabelViews set as slot1`s
,I/knox    ( 3064): MainReceiver.onReceive() : Intent { act=android.net.wifi.WIFI_STATE_CHANGED flg=0x4000010 cmp=com.sec.knox.seandroid/.receiver.MainReceiver (has extras) }
,I/knox    ( 3064): MainReceiver.onReceive() END - - - - - : Intent { act=android.net.wifi.WIFI_STATE_CHANGED flg=0x4000010 cmp=com.sec.knox.seandroid/.receiver.MainReceiver (has extras) }
,W/ContextImpl( 3064): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1857 android.content.ContextWrapper.startService:506 android.content.ContextWrapper.startService:506 com.sec.knox.seandroid.receiver.MainReceiver.onReceive:142 android.app.ActivityThread.handleReceiver:2698 
D/knox    ( 3064): KNOXAgentService : onCreate()
D/knox    ( 3064): KNOXAgentService : set alarms for deniallog and usage data upload
D/knox    ( 3064): KNOXAgentService. startJobThread() start
D/knox    ( 3064): KNOXAgentService. JobThread()
D/knox    ( 3064): KNOXAgentService. JobThread. notifyAll().
D/knox    ( 3064): KNOXAgentService. startJobThread() wait
,I/SELinux ( 4955): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 4955):  
,D/knox    ( 3064): KNOXAgentService : onDestroy().
,D/knox    ( 3064): ModuleBase.cancelAllAlarmManageModule()
,I/wpa_supplicant( 4952): wpa_supplicant v2.1-devel-4.4.22014-11-04/18:06:52
I/wpa_supplicant( 4952): [wpa_supplicant_init]: use SECRIL
I/wpa_supplicant( 4952): Successfully initialized wpa_supplicant
,I/wpa_supplicant( 4952): >>>>> Not GET KEY, IV <<<<<
,E/wpa_supplicant( 4952): getIMSI cannot open file
,E/wpa_supplicant( 4952): Interworking config: - SIM READ ERROR
,I/SELinux ( 4955): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 4955):  
I/SELinux ( 4955):  
,I/SELinux ( 4955): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 4955): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 4955): >>>>> Normal User
,E/dalvikvm( 4955): >>>>> tv.peel.smartremote [ userId:0 | appId:10163 ]
,E/SELinux ( 4955): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
,D/TimaKeyStoreProvider( 4955): in addTimaSignatureService
,D/TimaKeyStoreProvider( 4955): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 4955): Added TimaKesytore provider
,I/wpa_supplicant( 4952): >>>>> Not GET KEY, IV <<<<<
,E/wpa_supplicant( 4952): getIMSI cannot open file
E/wpa_supplicant( 4952): Interworking config: - SIM READ ERROR
,I/wpa_supplicant( 4952): >>>>> Not GET KEY, IV <<<<<
,I/wpa_supplicant( 4952): rfkill: Cannot open RFKILL control device
,D/Tethering(  745): interfaceLinkStateChanged wlan0, false
,D/Tethering(  745): interfaceStatusChanged wlan0, false
,W/ActivityManager(  745): Permission Denial: getCurrentUser() from pid=4955, uid=10163 requires android.permission.INTERACT_ACROSS_USERS
,I/wpa_supplicant( 4952): wlan0: Setting scan request: 0 sec 100000 usec
,I/wpa_supplicant( 4952): >>>>> Not GET KEY, IV <<<<<
,I/wpa_supplicant( 4952): >>>>> Not GET KEY, IV <<<<<
,I/wpa_supplicant( 4952): rfkill: Cannot open RFKILL control device
D/Tethering(  745): interfaceLinkStateChanged p2p0, false
,D/Tethering(  745): interfaceStatusChanged p2p0, false
D/Tethering(  745): interfaceLinkStateChanged p2p0, false
,D/Tethering(  745): interfaceStatusChanged p2p0, false
I/ActivityManager(  745): Killing 3672:com.sec.android.app.sns3/u0a36 (adj 15): empty #43
,I/wpa_supplicant( 4952): CTRL-EVENT-STATE-CHANGE id=-1 state=2 BSSID=00.00.00 SSID=
,E/SMD     (  238): DCD ON
,I/wpa_supplicant( 4952): P2P: initialized channels: 81:1,2,3,4,5,6,7,8,9,10,11,12,13 115:36,40,44,48 116:36,44 117:40,48
,I/wpa_supplicant( 4952): CTRL-EVENT-STATE-CHANGE id=-1 state=0 BSSID=00.00.00 SSID=
,I/wpa_supplicant( 4952): Skip scan - bUseNetwork false
,D/WifiStateMachine(  745): skipWifiStateBroadcast:false, LastBroadcastedWifiState:2
,D/WifiNative(  745): callSECApiString - ID [21]
I/wpa_supplicant( 4952): HOTSPOT20_ENABLE called
,I/wpa_supplicant( 4952): wlan0: HS20_DISABLED_COMPLETE normal
D/STATUSBAR-NetworkController_dual( 1063): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
D/SignalClusterView_dual( 1063): wifi: GONE sig=0 act=0
D/SignalClusterView_dual( 1063): mMobileDataState=0 mMobileDataState2=0
D/SignalClusterView_dual( 1063): apply() mSeparateMobileGroup=8
D/STATUSBAR-NetworkController_dual( 1063): refreshSignalCluster - setNWBoosterIndicators(false)
D/SignalClusterView_dual( 1063): wifi: GONE sig=2130837981 act=0
D/SignalClusterView_dual( 1063): mMobileDataState=0 mMobileDataState2=0
D/SignalClusterView_dual( 1063): apply() mSeparateMobileGroup=8
D/SignalClusterView_dual( 1063): wifi: GONE sig=2130837981 act=0
D/SignalClusterView_dual( 1063): mMobileDataState=0 mMobileDataState2=0
D/SignalClusterView_dual( 1063): apply() mSeparateMobileGroup=8
D/SignalClusterView_dual( 1063): wifi: GONE sig=2130837981 act=0
D/SignalClusterView_dual( 1063): mMobileDataState=0 mMobileDataState2=0
D/SignalClusterView_dual( 1063): apply() mSeparateMobileGroup=8
D/SignalClusterView_dual( 1063): wifi: GONE sig=2130837981 act=0
D/SignalClusterView_dual( 1063): mMobileDataState=0 mMobileDataState2=0
D/SignalClusterView_dual( 1063): apply() mSeparateMobileGroup=8
D/StatusBar.NetworkController_dual( 1063): mMobileLabelViews start
D/StatusBar.NetworkController_dual( 1063): mMobileLabelViews set mobileLabel[SIM_0] =No service.
D/StatusBar.NetworkController_dual( 1063): mMobileLabelViews GONE
D/StatusBar.NetworkController_dual( 1063): mMobileLabelViews2 set mobileLabel[SIM_1] =No service.
D/StatusBar.NetworkController_dual( 1063): mMobileLabelViews2 GONE
D/StatusBar.NetworkController_dual( 1063): mSingleMobileLabelViews set : simMode = 0
D/StatusBar.NetworkController_dual( 1063): mSingleMobileLabelViews set as slot1`s
,D/WifiNative(  745): callSECApiInt - ID [65]
,I/knox    ( 3064): MainReceiver.onReceive() : Intent { act=android.net.wifi.WIFI_STATE_CHANGED flg=0x4000010 cmp=com.sec.knox.seandroid/.receiver.MainReceiver (has extras) }
,E/WifiConfigStore(  745): Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
,I/knox    ( 3064): MainReceiver.onReceive() END - - - - - : Intent { act=android.net.wifi.WIFI_STATE_CHANGED flg=0x4000010 cmp=com.sec.knox.seandroid/.receiver.MainReceiver (has extras) }
,D/knox    ( 3064): GSLBThreadManager.NetworkStateChanged : NETWORK_STATE_CHAGED. Upload Call Log Data
,W/ContextImpl( 3064): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1857 android.content.ContextWrapper.startService:506 android.content.ContextWrapper.startService:506 com.sec.knox.seandroid.receiver.MainReceiver.onReceive:142 android.app.ActivityThread.handleReceiver:2698 
D/WifiNative(  745): callSECApiBoolean - ID [13]
I/wpa_supplicant( 4952): USE_NETWORK : USE_NETWORK ON
D/knox    ( 3064): KNOXAgentService : onCreate()
D/knox    ( 3064): KNOXAgentService : set alarms for deniallog and usage data upload
I/wpa_supplicant( 4952): reset timer : RESET_TIMER 0
I/wpa_supplicant( 4952): wlan0: Setting scan request: 0 sec 0 usec
I/wpa_supplicant( 4952): CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00.00.00 SSID=
I/wpa_supplicant( 4952): First Scan Start
D/knox    ( 3064): KNOXAgentService. startJobThread() start
I/wpa_supplicant( 4952): Scan requested (ret=0) - scan timeout 30 seconds
D/knox    ( 3064): KNOXAgentService. JobThread()
D/knox    ( 3064): KNOXAgentService. JobThread. notifyAll().
D/knox    ( 3064): KNOXAgentService. startJobThread() wait
E/WifiStateMachine(  745): Set the Nv default ccode
W/Settings( 3023): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/knox    ( 3064): KNOXAgentService : onDestroy().
D/knox    ( 3064): ModuleBase.cancelAllAlarmManageModule()
,D/WifiP2pService(  745): P2pDisabledState{ what=131203 }
D/WifiStateMachine(  745): skipWifiStateBroadcast:false, LastBroadcastedWifiState:3
E/WifiStateMachine(  745): HS20_DISABLED_COMPLETEnormal
,W/ContextImpl(  745): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.android.server.enterprise.wifi.WifiPolicy.asyncEnableNetwork:3065 com.android.server.enterprise.wifi.WifiPolicy.edmUpdateConfiguredNetworks:2530 com.android.server.enterprise.wifi.WifiPolicy$2$2.run:3022 java.lang.Thread.run:841 
D/CommandListener(  235): Setting iface cfg
D/CommandListener(  235): Trying to bring up p2p0
I/wpa_supplicant( 4952): P2P: updated channels: 81:1,2,3,4,5,6,7,8,9,10,11,12,13 115:36,40,44,48 116:36,44 117:40,48
,D/WifiMonitor(  745): startMonitoring(p2p0) with mConnected = true
D/WifiP2pService(  745): P2pEnablingState
D/WifiP2pService(  745): P2pEnablingState{ what=147457 }
D/WifiP2pService(  745): P2p socket connection successful
D/WifiP2pService(  745): P2pEnabledState
D/WifiP2pService(  745): sending p2p connection changed broadcast: IDLE
D/WifiDisplayController(  745): Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=true
D/WifiDisplayController(  745): updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
D/WifiDisplayController(  745): disconnect
D/WifiDisplayController(  745): updateConnection
D/WifiDisplayController(  745): updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
,D/WifiDisplayAdapter(  745): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,D/QuickConnect[1.1][2] ( 3125): SconnectManager.INetworkStateListener, onEnabled - mNetworkState : 4
,D/QuickConnect[1.1][2] ( 3125): P2pHelper.onReceive - ACTION_WIFI_DISPLAY_STATUS_CHANGED :0
,D/QuickConnect[1.1][2] ( 3125): P2pHelper.onReceive - P2P_CONNECTION_CHANGED : 
D/WifiDisplayAdapter(  745): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,D/WifiDisplayController(  745): Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=NetworkInfo: type: WIFI_P2P[], state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/NearbySettings( 1307): MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
V/NearbySettings( 1307): DMSUtil.isNetworkConnected - flag-null, state-null
D/QuickConnect[1.1][2] ( 3125): SconnectManager.INetworkStateListener, onDisconnected - networkType : 4
,I/NearbySettings( 1307): DMSUtil.isNetworkConnected - WIFI: IDLE
I/NearbySettings( 1307): DMSUtil.isNetworkConnected - P2P: IDLE
,I/NearbySettings( 1307): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
,I/NearbySettings( 1307): MountReceiver.onReceive - Set preference state off
,E/WifiStateMachine(  745): BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
,V/NearbySettings( 1307): MountReceiver.mPrefHandler - 7002
D/WifiDisplayController(  745): Received WIFI_P2P_THIS_DEVICE_CHANGED_ACTION: mThisDevice= Device: Galaxy S5-2
D/WifiDisplayController(  745):  deviceAddress: 3a:94:96:b5:06:dd
D/WifiDisplayController(  745):  primary type: 10-0050F204-5
D/WifiDisplayController(  745):  secondary type: null
D/WifiDisplayController(  745):  wps: 0
D/WifiDisplayController(  745):  grpcapab: 0
D/WifiDisplayController(  745):  devcapab: 0
D/WifiDisplayController(  745):  status: 3
D/WifiDisplayController(  745):  wfdInfo: null
D/WifiDisplayController(  745):  groupownerAddress: null
D/WifiDisplayController(  745):  GOdeviceName: null
D/WifiDisplayController(  745):  interfaceAddress: 
D/WifiDisplayController(  745):  SConnectInfo : null
D/WifiP2pService(  745): DeviceAddress: 3a:06:dd
W/WifiP2pStateTracker(  745): WifiP2pStateReceiver : android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,D/WifiP2pService(  745): sending p2p persistent groups changed broadcast
,D/FileShare-Server( 4168): ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,D/QuickConnect[1.1][2] ( 3125): P2pHelper.requestGroupInfo  - onGroupInfoAvailable- null
,D/FileShare-Server( 4168): ServerBroadcastReceiver.onReceive - netInfo.getDetailedState() IDLE
D/WifiP2pService(  745): InactiveState
D/WifiP2pService(  745): InactiveState{ what=139287 }
D/WifiP2pService(  745): P2pEnabledState{ what=139287 }
D/WifiP2pService(  745): DefaultState{ what=139287 }
,D/Tethering(  745): interfaceLinkStateChanged p2p0, false
,D/Tethering(  745): interfaceStatusChanged p2p0, false
,I/wpa_supplicant( 4952): P2P: updated channels: 81:1,2,3,4,5,6,7,8,9,10,11,12,13 115:36,40,44,48 116:36,44 117:40,48
,I/wpa_supplicant( 4952): P2P: updated channels: 81:1,2,3,4,5,6,7,8,9,10,11,12,13 115:36,40,44,48 116:36,44 117:40,48
,I/wpa_supplicant( 4952): nl80211: Received scan results (8 BSSes)
I/wpa_supplicant( 4952): wlan0: Setting scan request: 8 sec 0 usec
I/wpa_supplicant( 4952): Trying to associate with SSID '4E47373030'
I/wpa_supplicant( 4952): Trying to associate with  'G700'
,I/wpa_supplicant( 4952): CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00.00.00 SSID=
,E/wpa_supplicant( 4952): Cmd 35609 not handled
,D/Tethering(  745): interfaceLinkStateChanged wlan0, false
,D/Tethering(  745): interfaceStatusChanged wlan0, false
,E/WifiStateMachine(  745): Error! unhandled message{ when=-5ms what=135188 target=com.android.internal.util.StateMachine$SmHandler }
,E/wpa_supplicant( 4952): Cmd 35605 not handled
E/wpa_supplicant( 4952): Cmd 35847 not handled
E/wpa_supplicant( 4952): Cmd 35848 not handled
,E/wpa_supplicant( 4952): Cmd 35605 not handled
I/wpa_supplicant( 4952): CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00.00.00 SSID=4E47373030
I/wpa_supplicant( 4952): Associated with C0.AA.48
,I/wpa_supplicant( 4952): CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=C0.AA.48 SSID=4E47373030
,D/Tethering(  745): interfaceLinkStateChanged wlan0, false
,D/Tethering(  745): interfaceStatusChanged wlan0, false
,D/Tethering(  745): interfaceLinkStateChanged wlan0, false
,D/Tethering(  745): interfaceStatusChanged wlan0, false
,D/Tethering(  745): interfaceLinkStateChanged wlan0, false
,D/Tethering(  745): interfaceStatusChanged wlan0, false
,D/Tethering(  745): interfaceLinkStateChanged wlan0, true
,D/Tethering(  745): interfaceStatusChanged wlan0, true
E/Tethering(  745): No numeric data
,I/wpa_supplicant( 4952): CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=C0.AA.48 SSID=4E47373030
I/wpa_supplicant( 4952): WPA: Key negotiation completed with C0.AA.48 [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 4952): CTRL-EVENT-CONNECTED - Connection to C0.AA.48 completed (auth) [id=0 id_str=]
,I/wpa_supplicant( 4952): CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=C0.AA.48 SSID=4E47373030
,D/Tethering(  745): sendTetherStateChangedBroadcast 1, 0, 0
,I/ConnectivityService(  745): defaultVal : 1, tetherEnabledInSettings : true
D/NtpTrustedTime(  745): forceRefresh() from cache miss
,D/NtpTrustedTime(  745): forceRefresh Fail.
,D/WifiNative(  745): callSECApiVoid - ID [50]
,V/NetworkStats(  745): performPollLocked(flags=0x1)
D/Tethering(  745): interfaceLinkStateChanged wlan0, true
D/Tethering(  745): interfaceStatusChanged wlan0, true
,D/Tethering(  745): interfaceLinkStateChanged wlan0, true
,D/Tethering(  745): interfaceStatusChanged wlan0, true
,D/STATUSBAR-NetworkController_dual( 1063): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
D/Tethering(  745): interfaceLinkStateChanged wlan0, true
D/Tethering(  745): interfaceStatusChanged wlan0, true
D/Tethering(  745): interfaceLinkStateChanged wlan0, true
,D/Tethering(  745): interfaceStatusChanged wlan0, true
V/NetworkStats(  745): performPollLocked() took 42ms
,I/SELinux ( 4985): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 4985):  
D/StatusBar.NetworkController_dual( 1063): mMobileLabelViews start
D/StatusBar.NetworkController_dual( 1063): mMobileLabelViews set mobileLabel[SIM_0] =No service.
D/StatusBar.NetworkController_dual( 1063): mMobileLabelViews GONE
D/StatusBar.NetworkController_dual( 1063): mMobileLabelViews2 set mobileLabel[SIM_1] =No service.
D/StatusBar.NetworkController_dual( 1063): mMobileLabelViews2 GONE
D/StatusBar.NetworkController_dual( 1063): mSingleMobileLabelViews set : simMode = 0
D/StatusBar.NetworkController_dual( 1063): mSingleMobileLabelViews set as slot1`s
,D/NtpTrustedTime(  745): forceRefresh() from cache miss
,D/NtpTrustedTime(  745): forceRefresh Fail.
,D/dalvikvm(  245): GC_EXPLICIT freed 43K, 50% free 9513K/18912K, paused 2ms+3ms, total 34ms
D/STATUSBAR-NetworkController_dual( 1063): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
D/StatusBar.NetworkController_dual( 1063): mMobileLabelViews start
D/StatusBar.NetworkController_dual( 1063): mMobileLabelViews set mobileLabel[SIM_0] =No service.
D/StatusBar.NetworkController_dual( 1063): mMobileLabelViews GONE
D/StatusBar.NetworkController_dual( 1063): mMobileLabelViews2 set mobileLabel[SIM_1] =No service.
D/StatusBar.NetworkController_dual( 1063): mMobileLabelViews2 GONE
D/StatusBar.NetworkController_dual( 1063): mSingleMobileLabelViews set : simMode = 0
D/StatusBar.NetworkController_dual( 1063): mSingleMobileLabelViews set as slot1`s
,D/STATUSBAR-NetworkController_dual( 1063): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
D/StatusBar.NetworkController_dual( 1063): mMobileLabelViews start
D/StatusBar.NetworkController_dual( 1063): mMobileLabelViews set mobileLabel[SIM_0] =No service.
D/StatusBar.NetworkController_dual( 1063): mMobileLabelViews GONE
D/StatusBar.NetworkController_dual( 1063): mMobileLabelViews2 set mobileLabel[SIM_1] =No service.
,D/StatusBar.NetworkController_dual( 1063): mMobileLabelViews2 GONE
D/StatusBar.NetworkController_dual( 1063): mSingleMobileLabelViews set : simMode = 0
,D/dalvikvm(  245): GC_EXPLICIT freed <1K, 50% free 9513K/18912K, paused 2ms+3ms, total 21ms
D/StatusBar.NetworkController_dual( 1063): mSingleMobileLabelViews set as slot1`s
D/WifiP2pService(  745): InactiveState{ what=143375 }
D/WifiP2pService(  745): P2pEnabledState{ what=143375 }
,I/SELinux ( 4985): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 4985):  
I/SELinux ( 4985):  
,I/SELinux ( 4985): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 4985): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 4985): >>>>> Normal User
,E/dalvikvm( 4985): >>>>> com.vlingo.midas [ userId:0 | appId:10033 ]
,E/SELinux ( 4985): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
,D/dalvikvm(  245): GC_EXPLICIT freed <1K, 50% free 9513K/18912K, paused 2ms+2ms, total 20ms
,D/TimaKeyStoreProvider( 4985): in addTimaSignatureService
,D/TimaKeyStoreProvider( 4985): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 4985): Added TimaKesytore provider
,I/System.out( 4985): Inside WakeupProvider
,I/System.out( 4985): Inside onCreate() of WakeupTriggerProvide
,I/VlingoApplication( 4985): VlingoApplication appVersion ='11.4.0.3.34005', ro.csc.sales_code=XEO
,D/VlingoApplication( 4985): Couldn't create com.nuance.nuancedebugutilpackage context for host settings utility
,D/VlingoApplication( 4985): Couldn't create com.vlingo.midas.lmttutilitypackage context for host settings utility
,I/dhcpcd  ( 5007): if(wlan0) info get Success. (MAC : C0.AA.48)
,I/dhcpcd  ( 5007): bssid match
,D/NearbySettings( 1307): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 1307): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 1307): DMSUtil.isNetworkConnected - WIFI: OBTAINING_IPADDR
,I/NearbySettings( 1307): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1307): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1307): MountReceiver.onReceive - Set preference state off
,V/NearbySettings( 1307): MountReceiver.mPrefHandler - 7002
I/ActivityManager(  745): Killing 3720:com.sec.spp.push:RemoteDlcProcess/u0a38 (adj 15): empty #43
,D/DialogFlow( 4985): initQueue()
,D/WifiP2pService(  745): InactiveState{ what=143375 }
,D/WifiP2pService(  745): P2pEnabledState{ what=143375 }
,D/WifiStateMachine(  745): VerifyingLinkState enter
D/STATUSBAR-NetworkController_dual( 1063): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
D/StatusBar.NetworkController_dual( 1063): mMobileLabelViews start
D/StatusBar.NetworkController_dual( 1063): mMobileLabelViews set mobileLabel[SIM_0] =No service.
D/StatusBar.NetworkController_dual( 1063): mMobileLabelViews GONE
D/StatusBar.NetworkController_dual( 1063): mMobileLabelViews2 set mobileLabel[SIM_1] =No service.
D/StatusBar.NetworkController_dual( 1063): mMobileLabelViews2 GONE
D/StatusBar.NetworkController_dual( 1063): mSingleMobileLabelViews set : simMode = 0
D/StatusBar.NetworkController_dual( 1063): mSingleMobileLabelViews set as slot1`s
,D/STATUSBAR-NetworkController_dual( 1063): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
,D/StatusBar.NetworkController_dual( 1063): mMobileLabelViews start
D/StatusBar.NetworkController_dual( 1063): mMobileLabelViews set mobileLabel[SIM_0] =No service.
D/StatusBar.NetworkController_dual( 1063): mMobileLabelViews GONE
,D/StatusBar.NetworkController_dual( 1063): mMobileLabelViews2 set mobileLabel[SIM_1] =No service.
D/StatusBar.NetworkController_dual( 1063): mMobileLabelViews2 GONE
D/StatusBar.NetworkController_dual( 1063): mSingleMobileLabelViews set : simMode = 0
,D/StatusBar.NetworkController_dual( 1063): mSingleMobileLabelViews set as slot1`s
,D/WifiStateMachine(  745): VerifyingLinkState GOOD_LINK_DETECTED: transition to captive portal check
,D/WifiStateMachine(  745): CaptivePortalCheckState enter
,I/WifiTrafficPoller(  745): evaluateTrafficStatsPolling
D/ConnectivityService(  745): Captive portal check NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService(  745): handleCaptivePortalTrackerCheck: call captivePortalCheckComplete ni=NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/STATUSBAR-NetworkController_dual( 1063): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
D/StatusBar.NetworkController_dual( 1063): mMobileLabelViews start
D/StatusBar.NetworkController_dual( 1063): mMobileLabelViews set mobileLabel[SIM_0] =No service.
D/StatusBar.NetworkController_dual( 1063): mMobileLabelViews GONE
D/StatusBar.NetworkController_dual( 1063): mMobileLabelViews2 set mobileLabel[SIM_1] =No service.
D/StatusBar.NetworkController_dual( 1063): mMobileLabelViews2 GONE
D/StatusBar.NetworkController_dual( 1063): mSingleMobileLabelViews set : simMode = 0
,D/StatusBar.NetworkController_dual( 1063): mSingleMobileLabelViews set as slot1`s
D/WifiStateMachine(  745): CaptivePortalCheckState CMD_CAPTIVE_CHECK_COMPLETE
,I/WifiTrafficPoller(  745): evaluateTrafficStatsPolling
,I/WifiTrafficPoller(  745): mBoosterFLAG : 2
,I/WifiTrafficPoller(  745): current booster mode : BTCoexMode
D/ConnectivityService(  745): ConnectivityChange for WIFI: CONNECTED/CONNECTED
E/ConnectivityService(  745): net.tcp.usercfg.wifi not found in system properties. Using defaults
E/ConnectivityService(  745): net.tcp.delack.wifi not found in system properties. Using defaults
D/STATUSBAR-NetworkController_dual( 1063): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
D/SignalClusterView_dual( 1063): wifi: GONE sig=2130837981 act=0
D/SignalClusterView_dual( 1063): mMobileDataState=0 mMobileDataState2=0
D/SignalClusterView_dual( 1063): apply() mSeparateMobileGroup=8
D/STATUSBAR-NetworkController_dual( 1063): refreshSignalCluster - setNWBoosterIndicators(false)
D/ConnectivityService(  745): handleConnectivityChange: setting default proxy info 
D/SignalClusterView_dual( 1063): wifi: VISIBLE sig=2130837979 act=2130837939
D/SignalClusterView_dual( 1063): mMobileDataState=0 mMobileDataState2=0
D/SignalClusterView_dual( 1063): apply() mSeparateMobileGroup=8
D/SignalClusterView_dual( 1063): wifi: VISIBLE sig=2130837979 act=2130837939
D/SignalClusterView_dual( 1063): mMobileDataState=0 mMobileDataState2=0
D/SignalClusterView_dual( 1063): apply() mSeparateMobileGroup=8
D/SignalClusterView_dual( 1063): wifi: VISIBLE sig=2130837979 act=2130837939
D/SignalClusterView_dual( 1063): mMobileDataState=0 mMobileDataState2=0
D/SignalClusterView_dual( 1063): apply() mSeparateMobileGroup=8
D/SignalClusterView_dual( 1063): wifi: VISIBLE sig=2130837979 act=2130837939
D/SignalClusterView_dual( 1063): mMobileDataState=0 mMobileDataState2=0
D/SignalClusterView_dual( 1063): apply() mSeparateMobileGroup=8
D/StatusBar.NetworkController_dual( 1063): mMobileLabelViews start
D/StatusBar.NetworkController_dual( 1063): mMobileLabelViews set mobileLabel[SIM_0] =
D/StatusBar.NetworkController_dual( 1063): mMobileLabelViews GONE
D/StatusBar.NetworkController_dual( 1063): mMobileLabelViews2 set mobileLabel[SIM_1] =
D/StatusBar.NetworkController_dual( 1063): mMobileLabelViews2 GONE
D/StatusBar.NetworkController_dual( 1063): mSingleMobileLabelViews set : simMode = 0
D/StatusBar.NetworkController_dual( 1063): mSingleMobileLabelViews set as slot1`s
,V/RouteController(  235): /system/bin/ip -4 route replace default via 192.168.1.1 dev wlan0 scope global table 2 2>&1
D/STATUSBAR-IconMerger( 1063): checkOverflow(288), More:false, Req:false Child:2
,V/RouteController(  235): /system/bin/ip -4 rule del table 2 2>&1
,V/RouteController(  235): RTNETLINK answers: No such file or directory
,V/RouteController(  235): /system/bin/ip -4 rule add from 192.168.1.143 lookup 2 prio 150 2>&1
,V/RouteController(  235): /system/bin/ip route flush cached 2>&1
,D/NearbySettings( 1307): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,I/NearbySettings( 1307): MountReceiver.onReceive - Keep current state
,V/RouteController(  235): /system/bin/ip route del 192.168.1.0/24 table 2 2>&1
,D/NearbySettings( 1307): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 1307): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 1307): DMSUtil.isNetworkConnected - WIFI: CONNECTED
I/NearbySettings( 1307): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1307): DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
,I/NearbySettings( 1307): MountReceiver.onReceive - Keep current state
,V/RouteController(  235): RTNETLINK answers: No such process
,V/RouteController(  235): /system/bin/ip route add 192.168.1.0/24 dev wlan0 table 2 metric 0 2>&1
,V/RouteController(  235): /system/bin/ip route flush cached 2>&1
,D/Toast   ( 1307):  checkMirrorLinkEnabled returns : false
,D/Toast   ( 1307): showing allowed
,V/NetworkStats(  745): updateIfacesLocked()
,D/NtpTrustedTime(  745): forceRefresh() from cache miss
V/NetworkStats(  745): performPollLocked(flags=0x1)
,D/NearbySettings( 1307): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,I/NearbySettings( 1307): MountReceiver.onReceive - Keep current state
,V/NetworkStats(  745): performPollLocked() took 17ms
,I/SurfaceFlinger(  244): id=19 createSurf (1x1),1 flag=4, Uoast
D/KeyguardUpdateMonitor( 1063): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1063): handleKeyguardVisibilityChanged(1)
,D/KeyguardUpdateMonitor( 1063): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1063): handleKeyguardVisibilityChanged(1)
,D/PowerManagerService(  745): [api] acquire WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=745
D/KeyguardUpdateMonitor( 1063): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1063): handleKeyguardVisibilityChanged(1)
,D/NtpTrustedTime(  745): requestTime Success from server:2.android.pool.ntp.org mCachedNtpTime : 1450226423586 mCachedNtpElapsedRealtime : 130636 mCachedNtpCertainty : 9
,D/NtpTrustedTime(  745): currentTimeMillis() cache hit
,D/NtpTrustedTime(  745): currentTimeMillis() cache hit
D/NtpTrustedTime(  745): currentTimeMillis() cache hit
D/NtpTrustedTime(  745): currentTimeMillis() cache hit
,D/NtpTrustedTime(  745): currentTimeMillis() cache hit
,D/NtpTrustedTime(  745): currentTimeMillis() cache hit
V/NetworkStats(  745): advisePersistThreshold() given 9223372036854775, clamped to 2097152
,D/KeyguardUpdateMonitor( 1063): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1063): handleKeyguardVisibilityChanged(1)
,D/KeyguardUpdateMonitor( 1063): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1063): handleKeyguardVisibilityChanged(1)
,E/SMD     (  238): DCD ON
,D/Tethering(  745): Tethering got CONNECTIVITY_ACTION
,D/Tethering(  745): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker(  745): NoActiveNetworkState{ when=0 what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
,D/NtpTrustedTime(  745): currentTimeMillis() cache hit
D/        (  745): Setting time of day to sec=1450226424
D/        (  745): Trying to open a file
,D/        (  745): File Open Success
D/        (  745): File Close Success
I/        (  745): DRM_TIME_PATH CHMOD 660 for resetState done 
D/STATUSBAR-NetworkController_dual( 1063): onReceive() - CONNECTIVITY_ACTION, INET_CONDITION_ACTION
D/StatusBar.NetworkController_dual( 1063): mMobileLabelViews start
D/StatusBar.NetworkController_dual( 1063): mMobileLabelViews set mobileLabel[SIM_0] =
D/StatusBar.NetworkController_dual( 1063): mMobileLabelViews GONE
D/StatusBar.NetworkController_dual( 1063): mMobileLabelViews2 set mobileLabel[SIM_1] =
D/StatusBar.NetworkController_dual( 1063): mMobileLabelViews2 GONE
D/StatusBar.NetworkController_dual( 1063): mSingleMobileLabelViews set : simMode = 0
D/StatusBar.NetworkController_dual( 1063): mSingleMobileLabelViews set as slot1`s
,W/        (  745): Unable to set rtc to 1450226424: Invalid argument
V/AlarmManager(  745): waitForAlarm result :65536
,D/accuweather( 1442): [KK AccuPhone]>>> SWW:64 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/KeyguardUpdateMonitor( 1063): received broadcast android.intent.action.TIME_SET
,D/KeyguardUpdateMonitor( 1063): handleTimeUpdate
D/StatusBar-DoNotDistrub( 1063): Received intent with android.intent.action.TIME_SET action
D/StatusBar-DoNotDistrub( 1063): Not data shared android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
,D/StatusBar-DoNotDistrub( 1063): sendBroadcast android.intent.action.DORMANT_MODE_OFF
,I/AudioService(  745): getStreamVolume 5 index 110
D/StatusBar-DoNotDistrub( 1063): The STREAM NOTIFICATION volume is 0
D/STATUSBAR-StatusBarManagerService(  745): manageDisableList what=0x0 pkg=com.android.systemui
,W/Settings(  745): Setting auto_time has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
V/AlarmManager(  745): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,V/AlarmManager(  745): waitForAlarm result :4
D/accuweather( 1442): [KK AccuPhone]>>> SWW:64 [0:0] action : androidintentactionTIME_SET
D/accuweather( 1442): [KK AccuPhone]>>> SWW:452 [0:0] doChangeDayOrNight : 1
D/accuweather( 1442): [KK AccuPhone]>>> SWW:338 [0:0] getWeatherRenderer : 1
,W/SEC_DRM_PLUGIN_Playready(  248): PlayreadyPlugIn::onAcquireDrmInfo : case TYPE_UPDATE_SECURE_CLOCK after: 1450226423 after conversion: 1450226423
,W/SEC_DRM_PLUGIN_Playready(  248): PlayreadyPlugIn::onAcquireDrmInfo : case TYPE_UPDATE_SECURE_CLOCK before: 1450226424 after conversion: 1450226424
D/STATUSBAR-IconMerger( 1063): checkOverflow(288), More:false, Req:false Child:2
D/STATUSBAR-NotificationService(  745): received android.intent.action.DORMANT_MODE_OFF
D/LightsService(  745): [api] [SvcLED] turnOff:: id = 4 (uid: 1000 pid: 745) 
,D/LightsService(  745): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x40 -> 0x40 | SvcLED(id=4) set Off
I/SensorManagerA(  745): getReportingMode :: sensor.mType = 5
D/Sensors (  745): LightSensor setDelay = 200000000
D/Sensors (  745): LightSensor setSensorDelay = 200000000
D/Sensors (  745): Light sensor flush: not enabled 0
D/Sensors (  745): LightSensor enable = 1
D/Sensors (  745): LightSensor enableSensor = 1
D/SensorManager(  745): registerListener :: 16, CM36686 Light Sensor, 200000, 0,  
D/LocSvc_java(  745): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/LocSvc_java(  745): getAGpsConnectionInfo connType - 4
D/LocSvc_java(  745): ignore wifi update if we are not in OPENING or CLOSING
I/NetworkMonitor( 3753): type=WIFI subType= reason=null isConnected=true
,I/PCWCLIENTTRACE_PushUtil( 4507): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 4507): sales region : global
I/PCWCLIENTTRACE_PushUtil( 4507): getPushTypeList : [SPP, GCM]
,I/PCWCLIENTTRACE_SYSTEMReceiver( 4507): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,I/SELinux ( 5084): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5084):  
,I/SELinux ( 5084): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5084):  
I/SELinux ( 5084):  
,I/SELinux ( 5084): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5084): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 5084): >>>>> Normal User
,E/dalvikvm( 5084): >>>>> com.sec.android.cloudagent [ userId:0 | appId:10002 ]
,E/SELinux ( 5084): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 5084): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5084): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5084): Added TimaKesytore provider
,I/SELinux ( 5099): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5099):  
,W/dalvikvm( 1215): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 1215): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 1215): VFY: unable to find class referenced in signature (Landroid/net/Network;)
I/dalvikvm( 1215): Could not find method android.net.Network.openConnection, referenced from method com.google.android.gms.http.g.a
W/dalvikvm( 1215): VFY: unable to resolve virtual method 1007: Landroid/net/Network;.openConnection (Ljava/net/URL;)Ljava/net/URLConnection;
,D/dalvikvm( 1215): VFY: replacing opcode 0x6e at 0x00bb
,I/GoogleURLConnFactory( 1215): Using platform SSLCertificateSocketFactory
,I/SELinux ( 5099): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5099):  
I/SELinux ( 5099):  
,I/SELinux ( 5099): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5099): [DEBUG] seapp_context_lookup: seinfoCategory = chrome
E/dalvikvm( 5099): >>>>> Normal User
,E/dalvikvm( 5099): >>>>> com.android.chrome [ userId:0 | appId:10081 ]
D/AmoledAdjustTimer(  745): prevTemp = 283, currTemp = 284, prevStep = 4, currStep = 4
D/Sensors (  745): LightSensor enable = 0
,D/Sensors (  745): LightSensor enableSensor = 0
,D/SensorManager(  745): unregisterListener ::   
,E/SELinux ( 5099): [DEBUG] seapp_context_lookup: seinfoCategory = chrome
D/LightsService(  745): [SvcLED]  onSensorChanged::light value = 0
D/LightsService(  745): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,D/TimaKeyStoreProvider( 5099): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5099): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5099): Added TimaKesytore provider
I/dalvikvm( 1780): Could not find method android.os.PowerManager.isInteractive, referenced from method com.google.android.gms.common.util.y.a
,W/dalvikvm( 1780): VFY: unable to resolve virtual method 1378: Landroid/os/PowerManager;.isInteractive ()Z
,D/dalvikvm( 1780): VFY: replacing opcode 0x6e at 0x003d
,W/ActivityManager(  745): Permission Denial: getCurrentUser() from pid=5099, uid=10081 requires android.permission.INTERACT_ACROSS_USERS
,D/dalvikvm(  745): GC_EXPLICIT freed 2592K, 58% free 23518K/55200K, paused 8ms+16ms, total 139ms
W/ActivityManager(  745): Permission Denial: getCurrentUser() from pid=5084, uid=10002 requires android.permission.INTERACT_ACROSS_USERS
,E/ActivityThread( 1780): Failed to find provider info for com.android.contacts.metadata
,D/DelayedSyncController( 5099): Delaying sync.
,D/SyncManager(  745): failed sync operation 
,D/SyncManager(  745): not retrying sync operation because the error is a hard error: 
,D/PicasaService( 3836): start picasa sync
,D/PicasaService( 3836): end picasa sync
,I/SELinux ( 5133): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5133):  
,D/DelayedSyncController( 5099): Delaying sync.
I/SELinux ( 5133): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5133):  
I/SELinux ( 5133):  
,I/SELinux ( 5133): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5133): [DEBUG] seapp_context_lookup: seinfoCategory = release
E/dalvikvm( 5133): >>>>> Normal User
,E/dalvikvm( 5133): >>>>> com.sec.android.fotaclient [ userId:0 | appId:10010 ]
,E/SELinux ( 5133): [DEBUG] seapp_context_lookup: seinfoCategory = release
,I/dalvikvm( 1215): Could not find method android.os.PowerManager.isInteractive, referenced from method com.google.android.gms.common.util.y.a
W/dalvikvm( 1215): VFY: unable to resolve virtual method 1378: Landroid/os/PowerManager;.isInteractive ()Z
,D/dalvikvm( 1215): VFY: replacing opcode 0x6e at 0x003d
,D/TimaKeyStoreProvider( 5133): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5133): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5133): Added TimaKesytore provider
,I/jxcore-log( 4670): BLE advertisement not supported: Bluetooth LE advertising is not supported
I/jxcore-log( 4670): 
,W/ActivityManager(  745): Permission Denial: getCurrentUser() from pid=5133, uid=10010 requires android.permission.INTERACT_ACROSS_USERS
,I/ActivityManager(  745): Killing 3738:com.sec.spp.push:RemoteNotiProcess/u0a38 (adj 15): empty #43
,I/System.out( 1215): Thread-104(HTTPLog):isShipBuild true
,I/System.out( 1215): Thread-104(HTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,I/ActivityManager(  745): Killing 3959:com.sec.android.app.videoplayer/u0a52 (adj 15): empty #43
,I/SELinux ( 5150): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5150):  
,I/SELinux ( 5150): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5150):  
I/SELinux ( 5150):  
,I/SELinux ( 5150): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5150): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 5150): >>>>> Normal User
,E/dalvikvm( 5150): >>>>> com.samsung.klmsagent [ userId:0 | appId:10018 ]
,E/SELinux ( 5150): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 5150): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5150): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5150): Added TimaKesytore provider
,I/HarmonyEASService(  745): Updating for all 1
,W/ActivityManager(  745): Permission Denial: getCurrentUser() from pid=5150, uid=10018 requires android.permission.INTERACT_ACROSS_USERS
W/DriveInitializer( 1780): Background init thread started
W/DriveInitializer( 1780): Awaiting to be initialized
,D/KLMS-2.3.201 : ( 5150): KLMSValidator() : checkQATesting()
,E/cutils  (  225): Failed to mkdirat(/storage/extSdCard/Android): Read-only file system
,W/Vold    (  225): Returning OperationFailed - no handler for errno 30
W/ContextImpl( 1780): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.gms/files
,I/KLMS-2.3.201 : ( 5150): MainReciver() : EventNotificationReciver- method called: AppActivityListner onReceive for Intent Action : android.net.conn.CONNECTIVITY_CHANGE , timestamp: 1450226425199
,I/KLMS-2.3.201 : ( 5150): KLMSUtility() : isNetworkAvailable() - WIFI : true| MOBILE : false
,I/ActivityManager(  745): Killing 3987:com.sec.android.app.voicenote/1000 (adj 15): empty #43
,W/DriveInitializer( 1780): Background init thread ended
,I/SELinux ( 5174): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5174):  
,I/LocationTagReadyService( 2346): onStartCommand : Action = com.samsung.android.app.galaxyfinder.tag.start_location_convert
,D/GalaxyFinderApplication( 2346): [Slink platform] The state of Slink geocode service is true
,D/GalaxyFinderApplication( 2346): [Slink platform] The state of Slink geocode service is true
D/STATUSBAR-NetworkController_dual( 1063): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
D/StatusBar.NetworkController_dual( 1063): mMobileLabelViews start
D/StatusBar.NetworkController_dual( 1063): mMobileLabelViews set mobileLabel[SIM_0] =
D/StatusBar.NetworkController_dual( 1063): mMobileLabelViews GONE
D/StatusBar.NetworkController_dual( 1063): mMobileLabelViews2 set mobileLabel[SIM_1] =
D/StatusBar.NetworkController_dual( 1063): mMobileLabelViews2 GONE
D/StatusBar.NetworkController_dual( 1063): mSingleMobileLabelViews set : simMode = 0
,D/StatusBar.NetworkController_dual( 1063): mSingleMobileLabelViews set as slot1`s
D/GalaxyFinderApplication( 2346): [Slink platform] The state of Slink geocode service is true
,D/dalvikvm( 1780): GC_CONCURRENT freed 1654K, 36% free 12152K/18912K, paused 4ms+8ms, total 62ms
,D/dalvikvm( 1780): WAIT_FOR_CONCURRENT_GC blocked 9ms
,I/SELinux ( 5174): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5174):  
I/SELinux ( 5174):  
,I/SELinux ( 5174): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5174): [DEBUG] seapp_context_lookup: seinfoCategory = release
E/dalvikvm( 5174): >>>>> Normal User
,E/dalvikvm( 5174): >>>>> com.sec.android.soagent [ userId:0 | appId:10037 ]
,E/SELinux ( 5174): [DEBUG] seapp_context_lookup: seinfoCategory = release
,I/SELinux ( 5186): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5186):  
,D/TimaKeyStoreProvider( 5174): in addTimaSignatureService
,I/GallerySearchProvider( 3836): query content://com.sec.android.gallery3d.provider.GallerySearchProvider/search_suggest_tag_query
,D/TimaKeyStoreProvider( 5174): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5174): Added TimaKesytore provider
,I/SELinux ( 5186): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5186):  
I/SELinux ( 5186):  
,I/SELinux ( 5186): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5186): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 5186): >>>>> Normal User
,E/dalvikvm( 5186): >>>>> com.sec.android.app.videoplayer [ userId:0 | appId:10052 ]
,I/SELinux ( 5194): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5194):  
,E/SELinux ( 5186): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,W/ActivityManager(  745): Permission Denial: getCurrentUser() from pid=5174, uid=10037 requires android.permission.INTERACT_ACROSS_USERS
D/SO_AGENT( 5174): [AccRegisterReceiver.java(Line:56/Method:onReceive)] Receive broadcast meassage:android.net.conn.CONNECTIVITY_CHANGE
D/TimaKeyStoreProvider( 5186): in addTimaSignatureService
I/SO_AGENT( 5174): [AccRegisterReceiver.java(Line:87/Method:onReceive)] Need to accessory setup...
D/TimaKeyStoreProvider( 5186): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 5186): Added TimaKesytore provider
,I/SELinux ( 5194): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5194):  
I/SELinux ( 5194):  
,I/SELinux ( 5194): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5194): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 5194): >>>>> Normal User
E/dalvikvm( 5194): >>>>> com.sec.android.app.voicenote [ userId:0 | appId:1000 ]
,E/SELinux ( 5194): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 5194): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5194): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5194): Added TimaKesytore provider
,V/KVNProvider( 5194): query uri : content://com.sec.android.app.voicenote.common.util.VNProvider/search_suggest_tag_query
,V/KVNProvider( 5194): getFindoCursor query string : 
I/ActivityManager(  745): Killing 3955:com.android.calendar/u0a142 (adj 15): empty #43
,I/SA      ( 4684): [OR] onReceive log=[SA = 2.0.0117 V = 19 HWD = 1280X720 2.0 dpi = 320  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = kmini3g P = kmini3gxx I = KOT49H M = SM-G800H OKLEFT false DIS KOT49H.G800HXXU1ANK2 PSS = 4.497045606779314  ]
,V/KVNProvider( 5194): getTagSearchCursor() tagSearchCursor count : 0
,I/SA      ( 4684): [BDLM] already registered in spp
,I/SA      ( 4684): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. ]
,I/SA      ( 4684): [OR] == ACTION_CONNECTIVITY_CHANGE ==
,I/ActivityManager(  745): Killing 4006:com.android.providers.calendar/u0a44 (adj 15): empty #43
,I/SA      ( 4684): [SLFUCHKMGR] constructor called
I/SA      ( 4684): [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
,I/SA      ( 4684): [OR] == isSIMCardReady false ==
I/SA      ( 4684): [SCU] == networkStateCheck == true
,I/SA      ( 4684): [DM] getCountryCodeFromCSC : PL
I/SA      ( 4684): isChinaCountryCode : false
,I/SA      ( 4684): [OR] == networkStateCheck true ==
,I/SA      ( 4684): [OR] GetMyCountryZoneTask
,I/SA      ( 4684): [OR] onReceive END
,I/SA      ( 4684): [SRS] prepareGetMyCountryZone
,I/ActivityManager(  745): Killing 4010:com.sec.android.widgetapp.SPlannerAppWidget/u0a143 (adj 15): empty #43
I/dalvikvm( 4625): Total arena pages for JIT: 11
I/dalvikvm( 4625): Total arena pages for JIT: 12
I/dalvikvm( 4625): Total arena pages for JIT: 13
,I/dalvikvm( 4625): Total arena pages for JIT: 14
,I/SA      ( 4684): [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
,I/SA      ( 4684): [SSP] query invoked
D/SSRMv2:SIOP(  745): SIOP:: AP = 310, Delta = 0
,I/SA      ( 4684): [TPMU] GetMccFromDB : null
,I/SA      ( 4684): [SCU] getMccFromPreferece mcc = 260
,I/SA      ( 4684): [TPM] isNoProxy(default) : true
,I/SA      ( 4684): [RC New] Execute method=[GET] start
D/PhoneNumberLocatorBootCompletedReceiver( 1237): onReceive
,D/PhoneNumberLocatorBootCompletedReceiver( 1237): Phone number locator feature is dsiabled
,I/SELinux ( 5223): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5223):  
,I/SELinux ( 5223): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5223):  
I/SELinux ( 5223):  
,I/SELinux ( 5223): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5223): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,E/dalvikvm( 5223): >>>>> Normal User
,E/dalvikvm( 5223): >>>>> com.samsung.android.scloud.backup [ userId:0 | appId:10060 ]
,E/SELinux ( 5223): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 5223): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5223): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5223): Added TimaKesytore provider
,I/System.out( 4684): Thread-449(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
,I/System.out( 4684): Thread-449(ApacheHTTPLog):isShipBuild true
,I/System.out( 4684): Thread-449(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,I/sCloudBackupApp( 5223): sCloudBackupApp Version Info : 3.7.3.KK_APP
,I/SCloudBackupReceiver( 5223): Other Intent
,I/ActivityManager(  745): Killing 3935:com.sec.phone/1001 (adj 15): empty #43
D/com.samsung.app( 1442): [KK_EASY_Accu]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
D/com.samsung.app( 1442): [KK_EASY_Accu]>>> WC:37 [0:0] oR : create UI manager : start
D/com.samsung.app( 1442): [KK_EASY_Accu]>>> UIMEM:89 [0:0] getInstance
D/com.samsung.app( 1442): [KK_EASY_Accu]>>> UIMEM:77 [0:0] UIManager : create ui manager
D/accuweather( 1442): [KK AccuPhone]>>> RM:73 [0:0] RefreshManager : create
D/accuweather( 1442): [KK AccuPhone]>>> RM:136 [0:0]  V init 
D/daemonapp( 1462): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/accuweather( 1442): [KK AccuPhone]>>> RM:128 [0:0] updateCityList
,D/daemonapp( 1462): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,D/accuweather( 1442): [KK AccuPhone]>>> DBH:3047 [0:0] gADWI : count = 0
,D/daemonapp( 1462): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/com.samsung.app( 1442): [KK_EASY_Accu]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
,D/com.samsung.app( 1442): [KK_EASY_Accu]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
,I/SELinux ( 5237): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5237):  
,D/dalvikvm( 1215): GC_CONCURRENT freed 1582K, 38% free 11782K/18912K, paused 5ms+5ms, total 52ms
,I/SELinux ( 5237): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5237):  
I/SELinux ( 5237):  
,I/SELinux ( 5237): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5237): [DEBUG] seapp_context_lookup: seinfoCategory = release
E/dalvikvm( 5237): >>>>> Normal User
,E/dalvikvm( 5237): >>>>> com.samsung.android.internal.headlines [ userId:0 | appId:10106 ]
,E/SELinux ( 5237): [DEBUG] seapp_context_lookup: seinfoCategory = release
,D/TimaKeyStoreProvider( 5237): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5237): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5237): Added TimaKesytore provider
,D/HeadlinesChannelApplication( 5237): [onCreate]
,D/Headlines( 5237): HeadlinesSystemBroadcastReceiver onReceive android.net.conn.CONNECTIVITY_CHANGE
,W/ActivityManager(  745): Permission Denial: getCurrentUser() from pid=5237, uid=10106 requires android.permission.INTERACT_ACROSS_USERS
W/PhenotypeConfigurator( 1215): Server returned 404
,D/HeadlinesChannelUtil( 5237): getCountryCode(): countryCode = PL
,D/Headlines( 5237): Breath.onCreate
,D/HeadlinesCardManager( 5237): HeadlinesCardManager : constructor
,E/HeadlinesCardManager( 5237): HeadlinesCardManager : ctor = image_cache size is 42MB
,D/SA Version( 5237): CardProvider Library : 13
,I/SELinux ( 5249): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5249):  
,D/MagazineService::CardProviderContentProvider( 4785): insertProvider: provider already exists.: com.samsung.android.app.headlines
,D/MagazineService::CardProviderContentProvider( 4785): insertProvider: provider is updated.: com.samsung.android.app.headlines
,D/com.samsung.android.magazine.cardprovider.ConfigurationManager( 5237): registerCardProvider: provider already exists.
I/Headlines( 5237): HeadlinesDataCenter ctor
I/Headlines( 5237): HeadlinesDataCenter. mLocale = en_US
,D/HeadlinesChannelUtil( 5237): getCountryCode(): countryCode = PL
,D/HeadlinesCardManager( 5237): HeadlinesCardManager : constructor welcome :YES
,D/Headlines( 5237): Breath timer started. interval : 30000
D/Headlines( 5237): Breath.onStartCommand : com.samsung.android.internal.headlines.UPDATE_WELCOME_CARD flag : 0
D/HeadlinesCardManager( 5237): updateCategory : HeadlinesCardManager:updateCategory() category size == 0
D/HeadlinesCardManager( 5237): updateCategory : HeadlinesCardManager:updateCategory() try to query category list
D/Headlines( 5237): queryCategory.  mRequest is not initialized.
,D/HeadlinesCardManager( 5237): updateCategory : HeadlinesCardManager:updateCategory() reponse : false
D/HeadlinesCardManager( 5237): requestUpdateNewsWelcomeCard : request update welcome card to content card.
,D/HeadlinesDataCenter( 5237): requestUpdateNewsWelcomeCard !!! no welcome card
,I/SELinux ( 5249): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5249):  
I/SELinux ( 5249):  
,I/SELinux ( 5249): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 5249): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 5249): >>>>> Normal User
,E/dalvikvm( 5249): >>>>> com.google.android.apps.magazines [ userId:0 | appId:10112 ]
,E/SELinux ( 5249): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
,D/TimaKeyStoreProvider( 5249): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5249): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5249): Added TimaKesytore provider
,E/cutils  (  225): Failed to mkdirat(/storage/extSdCard/Android): Read-only file system
,W/ContextImpl( 5249): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,E/cutils  (  225): Failed to mkdirat(/storage/extSdCard/Android): Read-only file system
W/Vold    (  225): Returning OperationFailed - no handler for errno 30
,W/Vold    (  225): Returning OperationFailed - no handler for errno 30
W/GAV2    ( 5249): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
W/ContextImpl( 5249): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,D/btif_config_util( 3154): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,E/cutils  (  225): Failed to mkdirat(/storage/extSdCard/Android): Read-only file system
,W/ContextImpl( 5249): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,E/cutils  (  225): Failed to mkdirat(/storage/extSdCard/Android): Read-only file system
,W/ContextImpl( 5249): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
W/Vold    (  225): Returning OperationFailed - no handler for errno 30
W/Vold    (  225): Returning OperationFailed - no handler for errno 30
,V/WebViewChromium( 5249): Binding Chromium to the main looper Looper (main, tid 1) {422ee128}
,I/chromium( 5249): [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserProcessMain( 5249): Initializing chromium process, renderers=0
,W/chromium( 5249): [WARNING:proxy_service.cc(888)] PAC support disabled because there is no system implementation
,I/Adreno-EGL( 5249): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 5249): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 5249): Build Date: 03/21/14 Fri
I/Adreno-EGL( 5249): Local Branch: AU200+patches_03212014
I/Adreno-EGL( 5249): Remote Branch: 
I/Adreno-EGL( 5249): Local Patches: 
I/Adreno-EGL( 5249): Reconstruct Branch: 
,I/NSApplication( 5249): Starting up...
,W/ActivityManager(  745): Permission Denial: getCurrentUser() from pid=5249, uid=10112 requires android.permission.INTERACT_ACROSS_USERS
,D/QuickConnect[1.1][2] ( 3125): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,I/QuickConnect[1.1][2] ( 3125): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
,V/QuickConnect[1.1][2] ( 3125): SconnectManager.getInstance - () return existing instance com.samsung.android.sconnect.SconnectManager@42622c60
I/ActivityManager(  745): Killing 3876:com.sec.android.app.music:service/u0a150 (adj 15): empty #43
,I/SA      ( 4684): [RC New] [v2liruge] api execute + 838
,I/SA      ( 4684): [RC New] executeRequest [v2liruge] httpResponse : HTTP/1.1 200 OK
,I/System.out( 4684): AsyncTask #1 calls detatch()
,I/SA      ( 4684): [TPMU] getNetworkMcc : 
,I/SA      ( 4684): [SCU] saveMccToPreferece Start
,I/SA      ( 4684): [SCU] RegionMCC : 260
,I/SA      ( 4684): [SSP] query invoked
,I/SELinux ( 5286): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5286):  
,I/SA      ( 4684): [TPMU] GetMccFromDB : null
I/SA      ( 4684): [SCU] getMccFromPreferece mcc = 260
,I/SA      ( 4684): [SCU] saveMccToPreferece End
,I/SA      ( 4684): [RC New] executeRequest [v2liruge] end. 857
,I/SA      ( 4684): [RC New] Execute end
,I/SA      ( 4684): [OR] GetMyCountryZoneTask mcc = 260
,I/SA      ( 4684): [OR] GetMyCountryZoneTask Success
,D/dalvikvm(  245): GC_EXPLICIT freed 43K, 50% free 9513K/18912K, paused 2ms+2ms, total 25ms
,D/dalvikvm(  245): GC_EXPLICIT freed <1K, 50% free 9513K/18912K, paused 1ms+3ms, total 17ms
,I/SELinux ( 5286): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5286):  
I/SELinux ( 5286):  
,I/SELinux ( 5286): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5286): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 5286): >>>>> Normal User
,E/dalvikvm( 5286): >>>>> com.android.email [ userId:0 | appId:10155 ]
,E/SELinux ( 5286): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/dalvikvm(  245): GC_EXPLICIT freed <1K, 50% free 9513K/18912K, paused 1ms+2ms, total 18ms
,D/TimaKeyStoreProvider( 5286): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5286): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5286): Added TimaKesytore provider
,D/RCPManagerService(  745): exchangeData() failure , invalid userId
,D/RCPManagerService(  745): exchangeData() failure , invalid userId
,D/RCPManagerService(  745): exchangeData() failure , invalid userId
,D/RCPManagerService(  745): exchangeData() failure , invalid userId
,E/WifiStateMachine(  745): CAPTIVE_PORTAL_EVENT_AUTHENTICATED
,D/dalvikvm(  745): GC_EXPLICIT freed 1680K, 58% free 23409K/55200K, paused 6ms+10ms, total 130ms
,D/RCPManagerService(  745): exchangeData() failure , invalid userId
,D/RCPManagerService(  745): exchangeData() failure , invalid userId
,I/SELinux ( 5309): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5309):  
,W/ActivityManager(  745): Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
,I/SELinux ( 5313): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5313):  
I/ActivityManager(  745): Killing 3023:com.google.android.talk/u0a105 (adj 15): empty #43
,I/SELinux ( 5309): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5309):  
I/SELinux ( 5309):  
,I/SELinux ( 5309): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5309): [DEBUG] seapp_context_lookup: seinfoCategory = release
E/dalvikvm( 5309): >>>>> Normal User
,E/dalvikvm( 5309): >>>>> com.sec.android.provider.badge [ userId:0 | appId:10072 ]
,E/SELinux ( 5309): [DEBUG] seapp_context_lookup: seinfoCategory = release
,D/TimaKeyStoreProvider( 5309): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5309): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5309): Added TimaKesytore provider
,I/ActivityManager(  745): Killing 4031:com.sec.providers.settingsearch/u0a160 (adj 15): empty #43
,I/SELinux ( 5313): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5313):  
I/SELinux ( 5313):  
,I/SELinux ( 5313): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5313): [DEBUG] seapp_context_lookup: seinfoCategory = shared
E/dalvikvm( 5313): >>>>> Normal User
,E/dalvikvm( 5313): >>>>> com.samsung.android.service.travel [ userId:0 | appId:10169 ]
,E/SELinux ( 5313): [DEBUG] seapp_context_lookup: seinfoCategory = shared
,D/TimaKeyStoreProvider( 5313): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5313): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5313): Added TimaKesytore provider
,D/BadgeProvider( 5309): onCreate
,D/BadgeProvider( 5309): DatabaseHelper
W/ActivityManager(  745): Permission Denial: getCurrentUser() from pid=5309, uid=10072 requires android.permission.INTERACT_ACROSS_USERS
,D/BadgeProvider( 5309): query, [selection] : package='com.android.email' AND class='com.android.email.activity.Welcome' AND extraData='base_extra_badge'
,E/SMD     (  238): DCD ON
D/BadgeProvider( 5309): sendNotify entered. [uri] : content://com.sec.badge/apps/1
D/Launcher.Model( 1259): reloadBadges entered.
D/BadgeProvider( 5309): sendNotify, [notify] : null
D/BadgeProvider( 5309): update, [uri] : content://com.sec.badge/apps/1
D/BadgeProvider( 5309): update, [BadgeCount] : badgecount=0
,D/BadgeProvider( 5309): update, [UpdateCount] : 1
,W/ActivityManager(  745): Permission Denial: getCurrentUser() from pid=5313, uid=10169 requires android.permission.INTERACT_ACROSS_USERS
,D/WaitQueueForNetworkActivate( 4837): notifyNetworkActivated
,W/ContextImpl( 4837): Implicit intents with startService are not safe: Intent { act=com.sec.knox.containeragent.service.containermanager.ContainerManagerService } android.content.ContextWrapper.bindService:529 com.sec.knox.containeragent.ContainerManager.<init>:49 com.sec.android.app.samsungapps.vlibrary2.knoxmode.KNOXAPI.<init>:20 
,I/SurfaceFlinger(  244): id=19 Removed Uoast (11/12)
,I/SurfaceFlinger(  244): id=19 Removed Uoast (-2/12)
W/ActivityManager(  745): Unable to start service Intent { act=com.sec.knox.containeragent.service.containermanager.ContainerManagerService } U=0: not found
,I/ActivityManager(  745): Killing 2880:com.sec.knox.bridge/1000 (adj 15): empty #43
,D/KeyguardUpdateMonitor( 1063): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1063): handleKeyguardVisibilityChanged(1)
D/PowerManagerService(  745): [api] release WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=745 (0x0)
D/PowerManagerService(  745): [api] applyWakeLockFlagsOnReleaseLocked : userActivityNoUpdateLocked is called : SCREEN_BRIGHT_WAKE_LOCK        'WindowManager' ON_AFTER_RELEASE (uid=1000, pid=745, ws=WorkSource{1000}) (elapsedTime=3457)
,D/hcjo    ( 4837): AutoUpdateManager:IDLE:execute
,I/dalvikvm( 4837): Could not find method android.view.Window.setStatusBarColor, referenced from method com.sec.android.app.samsungapps.CommonActivity.onCreate
W/dalvikvm( 4837): VFY: unable to resolve virtual method 14867: Landroid/view/Window;.setStatusBarColor (I)V
,D/dalvikvm( 4837): VFY: replacing opcode 0x6e at 0x0024
,D/InitializeManagerStateMachine( 4837): execute::IDLE:EXECUTE
D/InitializeManagerStateMachine( 4837): exit::IDLE
,D/InitializeManagerStateMachine( 4837): entry::NETWORK_CHECK
,D/InitializeManagerStateMachine( 4837): execute::NETWORK_CHECK:NETWORK_STATE_OK
D/InitializeManagerStateMachine( 4837): exit::NETWORK_CHECK
D/InitializeManagerStateMachine( 4837): entry::CHECK_COUNTRY_INFO
,D/InitializeManagerStateMachine( 4837): execute::CHECK_COUNTRY_INFO:COUNTRY_INFO_OK
D/InitializeManagerStateMachine( 4837): exit::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 4837): entry::SUCCESS
D/hcjo    ( 4837): AutoUpdateManager:INITCHECK:onInitializeSuccess
,D/hcjo    ( 4837): AutoUpdateTriggerManager:IDLE:setInterval:345600000
,D/hcjo    ( 4837): AutoUpdateTriggerManager:IDLE:notifyNextTime
,D/hcjo    ( 4837): AutoUpdateManager:UPD_CHECK_TIMING:onNoUpdateTime
D/InitializeManagerStateMachine( 4837): exit::SUCCESS
,D/InitializeManagerStateMachine( 4837): entry::IDLE
I/ActivityManager(  745): Killing 4234:com.wssyncmldm/1000 (adj 15): empty #43
,D/dalvikvm( 1303): GC_EXPLICIT freed 776K, 44% free 10748K/18912K, paused 3ms+5ms, total 40ms
,I/iu.SyncManager( 1780): SYNC; picasa accounts
,D/NetworkLogImpl( 1780): Loaded NetworkSpeedPredictor
,I/iu.Environment( 1780): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,I/iu.UploadsManager( 1780): num queued entries: 0
,I/iu.UploadsManager( 1780): num updated entries: 0
,I/iu.SyncManager( 1780): NEXT; no task
W/ContextImpl(  745): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,I/SELinux ( 5344): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5344):  
,I/SELinux ( 5344): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5344):  
I/SELinux ( 5344):  
,I/SELinux ( 5344): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5344): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 5344): >>>>> Normal User
,E/dalvikvm( 5344): >>>>> com.android.calendar [ userId:0 | appId:10142 ]
,E/SELinux ( 5344): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 5344): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5344): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5344): Added TimaKesytore provider
,I/ActivityManager(  745): Killing 4412:com.android.defcontainer/u0a6 (adj 15): empty #43
,D/BootCompletedReceiver(  745): onReceive
,I/KLMS-2.3.201 : ( 5150): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,I/GCM     ( 1303): GCM config loaded
,I/KLMS-2.3.201 : ( 5150): MainReciver() : EventNotificationReciver- method called: AppActivityListner onReceive for Intent Action : android.intent.action.TIME_SET , timestamp: 1450226427745
,I/KLMS-2.3.201 : ( 5150): StateImplV2() : dateTimeChanged() : Wed Dec 16 01:40:27 CET 2015
,D/SO_AGENT( 5174): [ServerTimeReceiver.java(Line:44/Method:onReceive)] Receive broadcast meassage:android.intent.action.TIME_SET
,I/SO_AGENT( 5174): [ServerTimeReceiver.java(Line:47/Method:onReceive)] No action is available before server time settings
,I/SA      ( 4684): [SBR] StdBroadcastReceiver received Intent of  action.TIME_SET.
,I/VacuumService( 1215): Vacuum at: now=1450226427863 tag=VacuumService
,D/Mms/MessagingNotification( 3777): [start]    nonBlockingUpdateMessageIndicator()
,D/Mms/MessagingNotification( 3777): sDisableVibrateForCamera = false
,W/WifiP2pStateTracker(  745): WifiP2pStateReceiver : android.net.wifi.LINK_CONFIGURATION_CHANGED
D/Mms/MessagingNotification( 3777): isBlockingModeEnable() = false
D/Mms/TelephonyPermission( 3777): isDefault true
,D/ConnectivityService(  745): handleConnectivityChange: addresses changed linkProperty[1]: resetMask=0
D/ConnectivityService(  745):    car=removed=[] added=[fe80::3a94:96ff:feb5:6dd/64,]
,D/ConnectivityService(  745): handleConnectivityChange: setting default proxy info 
,D/ConnectivityService(  745): updateSourceRoutes : no source routing conditions
,D/TP/MmsSmsProvider( 1237): match 8:Elapsed time : 12.029 ms
,I/SELinux ( 5378): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5378):  
,D/TP/MmsSmsProvider( 1237): match 200:Elapsed time : 1.379 ms
,D/BadgeProvider( 5309): query, [selection] : package='com.android.mms' AND class='com.android.mms.ui.ConversationComposer' AND extraData='base_extra_badge'
,I/SELinux ( 5378): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5378):  
I/SELinux ( 5378):  
,I/SELinux ( 5378): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 5378): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 5378): >>>>> Normal User
,E/dalvikvm( 5378): >>>>> com.samsung.android.scloud.sync [ userId:0 | appId:10062 ]
,E/SELinux ( 5378): [DEBUG] seapp_context_lookup: seinfoCategory = platform
D/BadgeProvider( 5309): sendNotify entered. [uri] : content://com.sec.badge/apps/2
D/BadgeProvider( 5309): sendNotify, [notify] : null
,D/BadgeProvider( 5309): update, [uri] : content://com.sec.badge/apps/2
,D/Launcher.Model( 1259): reloadBadges entered.
D/BadgeProvider( 5309): update, [BadgeCount] : badgecount=0
,D/BadgeProvider( 5309): update, [UpdateCount] : 1
,D/Mms/MessagingNotification( 3777): setBadgeCount(), count=0
,D/MessagingNotification( 3777): remove alarm
,D/TimaKeyStoreProvider( 5378): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5378): Cannot add TimaSignature Service, License check Failed
,D/Mms/MessagingNotification( 3777): [end]    nonBlockingUpdateMessageIndicator()
,D/ActivityThread( 5378): Added TimaKesytore provider
,D/Mms/MessagingNotification( 3777): updateAllHistoryAsRead()
,W/ActivityManager(  745): Permission Denial: getCurrentUser() from pid=5378, uid=10062 requires android.permission.INTERACT_ACROSS_USERS
,D/com.samsung.app( 1442): [KK_EASY_Accu]>>> WC:30 [0:0] action : androidintentactionTIME_SET
,D/com.samsung.app( 1442): [KK_EASY_Accu]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
,I/ActivityManager(  745): Killing 3187:com.sec.android.inputmethod/1000 (adj 15): empty #43
I/ Time Manager ( 5378): Time Difference not stored. TIME_DIFFERENCE
,I/SELinux ( 5397): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5397):  
,D/STATUSBAR-NetworkController_dual( 1063): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
,D/StatusBar.NetworkController_dual( 1063): mMobileLabelViews start
D/StatusBar.NetworkController_dual( 1063): mMobileLabelViews set mobileLabel[SIM_0] =
,D/StatusBar.NetworkController_dual( 1063): mMobileLabelViews GONE
D/StatusBar.NetworkController_dual( 1063): mMobileLabelViews2 set mobileLabel[SIM_1] =
,D/StatusBar.NetworkController_dual( 1063): mMobileLabelViews2 GONE
,D/StatusBar.NetworkController_dual( 1063): mSingleMobileLabelViews set : simMode = 0
,D/StatusBar.NetworkController_dual( 1063): mSingleMobileLabelViews set as slot1`s
,I/SELinux ( 5397): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5397):  
I/SELinux ( 5397):  
,I/SELinux ( 5397): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5397): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 5397): >>>>> Normal User
,E/dalvikvm( 5397): >>>>> com.sec.android.app.clockpackage [ userId:0 | appId:10084 ]
,E/SELinux ( 5397): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/ConnectivityService(  745): handleInetConditionHoldEnd: net=1, condition=100, published condition=0
,D/STATUSBAR-NetworkController_dual( 1063): onReceive() - CONNECTIVITY_ACTION, INET_CONDITION_ACTION
,D/StatusBar.NetworkController_dual( 1063): mMobileLabelViews start
D/StatusBar.NetworkController_dual( 1063): mMobileLabelViews set mobileLabel[SIM_0] =
D/StatusBar.NetworkController_dual( 1063): mMobileLabelViews GONE
D/StatusBar.NetworkController_dual( 1063): mMobileLabelViews2 set mobileLabel[SIM_1] =
,D/StatusBar.NetworkController_dual( 1063): mMobileLabelViews2 GONE
,D/StatusBar.NetworkController_dual( 1063): mSingleMobileLabelViews set : simMode = 0
,D/StatusBar.NetworkController_dual( 1063): mSingleMobileLabelViews set as slot1`s
,D/TimaKeyStoreProvider( 5397): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5397): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5397): Added TimaKesytore provider
,I/SELinux ( 5415): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5415):  
I/ActivityManager(  745): Killing 4464:com.google.android.partnersetup/u0a14 (adj 15): empty #43
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
,W/ActivityManager(  745): Permission Denial: getCurrentUser() from pid=5415, uid=10094 requires android.permission.INTERACT_ACROSS_USERS
,D/elm:14132( 5415): ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver }
,D/elm:14132( 5415): ELMEngine.ELMEngine( context ).
,D/elm:14132( 5415): MDMBridge.setEnterpriseBridge()
,D/elm:14132( 5415): ELMAbstractReceiver : Receive Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.sec.esdk.elm/.service.ElmAgentService } END.
,I/knox    ( 3064): MainReceiver.onReceive() : Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.sec.knox.seandroid/.receiver.MainReceiver }
,D/elm:14132( 5415): ElmAgentService : onCreate()
,W/ContextImpl( 3064): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1857 android.content.ContextWrapper.startService:506 android.content.ContextWrapper.startService:506 com.sec.knox.seandroid.receiver.MainReceiver.onReceive:142 android.app.ActivityThread.handleReceiver:2698 
D/elm:14132( 5415): ElmAgentService : onHandleIntent() Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.sec.esdk.elm/.service.ElmAgentService }
D/knox    ( 3064): MainReceiver.listeningToTimeDateChanges( context, intent ).
I/knox    ( 3064): MainReceiver.onReceive() END - - - - - : Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.sec.knox.seandroid/.receiver.MainReceiver }
D/knox    ( 3064): KNOXAgentService : onCreate()
D/knox    ( 3064): KNOXAgentService : set alarms for deniallog and usage data upload
D/knox    ( 3064): KNOXAgentService. startJobThread() start
D/knox    ( 3064): KNOXAgentService. JobThread()
D/knox    ( 3064): KNOXAgentService. JobThread. notifyAll().
D/knox    ( 3064): KNOXAgentService. startJobThread() wait
,D/elm:14132( 5415): ELMAgentService.listeningToTimeDateChanges( context, intent ).
,D/elm:14132( 5415): ELMEngine.ServiceHandler.handleMessage( ALARM_MODIFY ). 
,D/elm:14132( 5415): ModuleBase.resetCalllogAPIAlarm()
,I/SELinux ( 5430): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5430):  
,D/knox    ( 3064): KNOXAgentService : onDestroy().
,D/knox    ( 3064): ModuleBase.cancelAllAlarmManageModule()
,D/elm:14132( 5415): ModuleBase.ModifySetAlarm()
,D/elm:14132( 5415): MDMBridge.getInstance()
,D/elm:14132( 5415): MDMBridge.getAllLicenseInfoFromSDK()
,D/elm:14132( 5415): ElmAgentService : onDestroy().
I/ActivityManager(  745): Killing 4480:com.samsung.groupcast/u0a15 (adj 15): empty #43
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
,W/ActivityManager(  745): Permission Denial: getCurrentUser() from pid=5430, uid=10143 requires android.permission.INTERACT_ACROSS_USERS
,I/SELinux ( 5442): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5442):  
I/ActivityManager(  745): Killing 4493:com.android.musicfx/u0a24 (adj 15): empty #43
V/AlarmManager(  745): waitForAlarm result :4
,V/AlarmManager(  745): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
I/PCWCLIENTTRACE_SYSTEMReceiver( 4507): mConnectivityHandler : connected
,W/PCWCLIENTTRACE_AccountUtil( 4507): [hasSamungAccount] - No Samsung Account
,D/BatteryService(  745): level:100, scale:100, status:5, health:2, present:true, voltage: 4367, temperature: 289, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:8, charge type:1, power sharing:false
,D/BatteryService(  745): stay LED for fully charged
,D/BatteryService(  745): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1063): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1063): handleBatteryUpdate
,I/SELinux ( 5442): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5442):  
I/SELinux ( 5442):  
,I/SELinux ( 5442): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5442): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 5442): >>>>> Normal User
,E/dalvikvm( 5442): >>>>> com.sec.android.app.taskmanager [ userId:0 | appId:10166 ]
,V/HeadsetService( 3154): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
E/SELinux ( 5442): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/HeadsetStateMachine( 3154): Disconnected process message: 10
D/UiModeManager(  745): mCoverManager.getCoverState() : true
,D/STATUSBAR-PhoneStatusBar( 1063):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1063): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/TimaKeyStoreProvider( 5442): in addTimaSignatureService
D/STATUSBAR-IconMerger( 1063): checkOverflow(288), More:false, Req:false Child:2
,D/TimaKeyStoreProvider( 5442): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5442): Added TimaKesytore provider
,W/linker  ( 4507): libterrier.so has text relocations. This is wasting memory and is a security risk. Please fix.
I/CSTORAGE( 4507): ================================================
I/CSTORAGE( 4507):  CSTORAGE_SKM_LIB v1.0.14
I/CSTORAGE( 4507): ================================================
D/dalvikvm( 4507): No JNI_OnLoad found in /system/lib/libterrier.so 0x42613140, skipping init
I/PCWCLIENTTRACE_SecurePreferencesJNI( 4507): [GetString-S]
,I/terrier ( 4507): v1.1.3q com.sec.pcw.device: getString function called
,D/QSEECOMAPI: ( 4507): QSEECom_get_handle sb_length = 0x2040
,D/QSEECOMAPI: ( 4507): App is not loaded in QSEE
,D/QSEECOMAPI: ( 4507): Loaded image: APP id = 4
W/ActivityManager(  745): Permission Denial: getCurrentUser() from pid=5442, uid=10166 requires android.permission.INTERACT_ACROSS_USERS
,D/QSEECOMAPI: ( 4507): QSEECom_dealloc_memory 
,D/QSEECOMAPI: ( 4507): QSEECom_shutdown_app, app_id = 4
E/terrier ( 4507): com.sec.pcw.device: getString: failed to get string(-1)
,I/PCWCLIENTTRACE_SecurePreferencesJNI( 4507): [GetString-E]
,I/PCWCLIENTTRACE_PushUtil( 4507): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 4507): sales region : global
I/PCWCLIENTTRACE_PushUtil( 4507): getPushTypeList : [SPP, GCM]
,E/PCWCLIENTTRACE_PCWHandler( 4507): [ensureRegistration] - No Samsung account
,I/SELinux ( 5466): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5466):  
I/ActivityManager(  745): Killing 4521:com.samsung.android.app.galaxyfinder/u0a34 (adj 15): empty #43
,I/SELinux ( 5466): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5466):  
I/SELinux ( 5466):  
,I/SELinux ( 5466): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5466): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 5466): >>>>> Normal User
,E/dalvikvm( 5466): >>>>> com.qualcomm.timeservice [ userId:0 | appId:10168 ]
,E/SELinux ( 5466): [DEBUG] seapp_context_lookup: seinfoCategory = platform
V/AlarmManager(  745): waitForAlarm result :4
V/AlarmManager(  745): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,D/TimaKeyStoreProvider( 5466): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5466): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5466): Added TimaKesytore provider
,W/ActivityManager(  745): Permission Denial: getCurrentUser() from pid=5466, uid=10168 requires android.permission.INTERACT_ACROSS_USERS
,D/dalvikvm( 5466): No JNI_OnLoad found in /vendor/lib/libTimeService.so 0x42613980, skipping init
,D/TimeService( 5466): Receivedandroid.intent.action.TIME_SET intent. Current Time is 1450226429563
D/        ( 5466): TimeServiceNative: User Time to be set is 1450226429564
,D/QC-time-services( 5466): Lib:time_genoff_operation: pargs->base = 2
D/QC-time-services( 5466): Lib:time_genoff_operation: pargs->operation = 0
,D/QC-time-services( 5466): Lib:time_genoff_operation: pargs->ts_val = 1450226429564
,D/QC-time-services( 5466): Lib:time_genoff_operation: Send to server  passed!!
,D/QC-time-services(  288): Daemon: Connection accepted:time_genoff
D/QC-time-services(  288): Daemon: genoff_handler: Process name is omm.timeservice
,D/QC-time-services(  288): Daemon:Received base = 2, unit = 1, operation = 0,value = 1450226429564
D/QC-time-services(  288): Daemon:genoff_opr: Base = 2, val = 1450226429564, operation = 0
D/QC-time-services(  288): Daemon:rtc_get: Time read from RTC -- MM/DD/YY HH:MM:SS0/19/70 16:37:34
,D/QC-time-services(  288): Daemon:Value read from RTC seconds = 1615054000
D/QC-time-services(  288): Daemon:new time 1450226429564 
D/QC-time-services(  288): Daemon: delta 1448611375564 genoff 1448611375564 
D/QC-time-services(  288): Daemon:genoff_persistent_update: Writing genoff = 1448611375564 to memory
,D/QC-time-services(  288): Daemon:Opening File: /data/time/ats_2
,D/QC-time-services(  288): Daemon:time_persistent_memory_opr:Genoff write operation 
,D/QC-time-services(  288): Updating the TOD offset
,D/QC-time-services(  288): Daemon:genoff_persistent_update: Writing genoff = 1448611375564 to memory
D/QC-time-services(  288): Daemon:Opening File: /data/time/ats_1
,D/QC-time-services(  288): Daemon:time_persistent_memory_opr:Genoff write operation 
,E/QC-time-services(  288): Daemon:Update to modem bit set
E/QC-time-services( 5466): Receive Passed == base = 2, unit = 1, operation = 0, result = 0
,D/QC-time-services(  288): Daemon:genoff_send_modem: Sending data to MODEM !
,D/QC-time-services(  288): Daemon: Base = 2, Value being sent to MODEM = 1134261629564
,E/QC-time-services(  288): Daemon: Time-services: Waiting to acceptconnection
,E/QC-time-services(  288): Daemon:tod_update_ind_cb: Got Update from modem msg_id 40
I/ActivityManager(  745): Killing 4558:com.sec.android.service.health/u0a16 (adj 15): empty #43
,D/daemonapp( 1462): [MSC_Daemon]>>> WU:236 [0:0] regintype : EUR
,D/daemonapp( 1462): [MSC_Daemon]>>> WU:292 [0:0] cp type is : cp_eng
,D/daemonapp( 1462): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/daemonapp( 1462): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,D/daemonapp( 1462): [MSC_Daemon]>>> WDSM:44 [0:0] Act : androidintentactionTIME_SET, run:true
,D/comsamsunglog( 1462): [MSC_Daemon]>>> ====================================================================================================================
,D/comsamsunglog( 1462): [MSC_Daemon]>>> daemonapp [Version : 14052601 ] [ 1 ] 
D/comsamsunglog( 1462): [MSC_Daemon]>>> Header set to : ===> "daemonapp" <===
,D/comsamsunglog( 1462): [MSC_Daemon]>>> ====================================================================================================================
,D/daemonapp( 1462): [MSC_Daemon]>>> WDSM:85 [0:0] c:null, r:3
,D/daemonapp( 1462): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/packagename
,D/daemonapp( 1462): [MSC_Daemon]>>> WU:1485 [0:0] PakNme size = 2
,D/daemonapp( 1462): [MSC_Daemon]>>> WU:236 [0:0] regintype : EUR
,D/daemonapp( 1462): [MSC_Daemon]>>> WU:292 [0:0] cp type is : cp_eng
,D/daemonapp( 1462): [MSC_Daemon]>>> WU:1488 [0:0] CP Name cp_eng
,D/daemonapp( 1462): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/packagename
,D/comdaemonstockapp( 1462): [Daemon_Stock]>>> StockclockDaemonService.java:60 [0:0] onReceive: androidintentactionTIME_SET
,D/comdaemonstockapp( 1462): [Daemon_Stock]>>> StockclockDaemonService.java:61 [0:0] appServiceStatus: 0
,I/CheckinService( 1780): Checkin interval check for package: unspecified last checkin: 1450164630465 min interval config: 0 actual interval: 61799252
,E/SMD     (  238): DCD ON
,D/Mms/MessagesLockscreen( 3777): onReceive() action = com.android.mms.ui.MessagesLockscreenmSimSlot : [0] Mms = false count = 0
,D/ContextualEventManager( 1063): removeContextualEvent(): requestClass=com.android.mms
D/ContextualEventManager( 1063): removeMissedEventView rq=com.android.mms[cFlag, mFlag]=[false, false]
D/ContextualEventManager( 1063): updateContainer()
D/ContextualEventContainer( 1063): update()
D/ContextualEventContainer( 1063): handleUpdate()
D/ContextualEventManager( 1063): getTopEventView()
,D/ContextualEventManager( 1063): getTopContextualEvent()
,D/Finsky  ( 3513): [349] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 3513): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,I/SELinux ( 5489): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5489):  
,D/ContextualEventManager( 1063): top view = flightmode
I/KeyguardEffectViewMain( 1063): *** KeyguardEffectView getInstance ***
D/ContextualEventManager( 1063): getTopEventClass()
,D/ContextualEventManager( 1063): getTopContextualEvent()
D/ContextualEventManager( 1063): !isClockTop
D/ContextualEventManager( 1063): getTopEventClass()
,D/ContextualEventManager( 1063): getTopContextualEvent()
D/ContextualEventManager( 1063): !isClockTop
D/ContextualEventManager( 1063): getTopEventClass()
,D/ContextualEventManager( 1063): getTopContextualEvent()
D/UsbManager( 1063):  :::: isUsb30Available :: return = false from pid = 1063
,D/SecContextualClockFlightMode( 1063): handleUpdateClock()
,D/KeyguardProperties( 1063): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,I/SELinux ( 5489): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5489):  
I/SELinux ( 5489):  
,I/SELinux ( 5489): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5489): [DEBUG] seapp_context_lookup: seinfoCategory = release
E/dalvikvm( 5489): >>>>> Normal User
,E/dalvikvm( 5489): >>>>> com.android.providers.calendar [ userId:0 | appId:10044 ]
,E/SELinux ( 5489): [DEBUG] seapp_context_lookup: seinfoCategory = release
,D/TimaKeyStoreProvider( 5489): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5489): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5489): Added TimaKesytore provider
,I/PowerManagerService(  745): [PWL] Off : 75s ago
I/PowerManagerService(  745): [PWL]   PowerManagerService.WakeLocks: ref count=1
,I/PowerManagerService(  745): [PWL]     mWakeLockSummary : 0x1
I/PowerManagerService(  745): [PWL]       PARTIAL_WAKE_LOCK              'AlarmManager' (uid=1000, pid=745, ws=WorkSource{10044}) (elapsedTime=6070)
,I/PowerManagerService(  745): [PWL]       PARTIAL_WAKE_LOCK              'AlarmReceiver' (uid=10084, pid=5397, ws=null) (elapsedTime=1621)
,W/ActivityManager(  745): Permission Denial: getCurrentUser() from pid=5489, uid=10044 requires android.permission.INTERACT_ACROSS_USERS
,D/Headlines( 5237): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE
,D/Headlines( 5237): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0
,D/Headlines( 5237): Breath 4620 latestRequest time : 1450226426049 current time : 1450226430669
,D/dalvikvm(  745): GC_EXPLICIT freed 1341K, 58% free 23419K/55200K, paused 10ms+22ms, total 235ms
,I/GAV2    ( 5249): Thread[GAThread,5,main]: No campaign data found.
D/STATUSBAR-NetworkController_dual( 1063): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
D/StatusBar.NetworkController_dual( 1063): mMobileLabelViews start
D/StatusBar.NetworkController_dual( 1063): mMobileLabelViews set mobileLabel[SIM_0] =
D/StatusBar.NetworkController_dual( 1063): mMobileLabelViews GONE
D/StatusBar.NetworkController_dual( 1063): mMobileLabelViews2 set mobileLabel[SIM_1] =
D/StatusBar.NetworkController_dual( 1063): mMobileLabelViews2 GONE
D/StatusBar.NetworkController_dual( 1063): mSingleMobileLabelViews set : simMode = 0
D/StatusBar.NetworkController_dual( 1063): mSingleMobileLabelViews set as slot1`s
,I/ActivityManager(  745): Killing 3851:com.samsung.android.sdk.samsunglink/u0a42 (adj 15): empty #43
,E/Watchdog(  745): !@Sync 4
,E/SMD     (  238): DCD ON
,D/CaptivePortalTracker(  745): DelayedCaptiveCheckState{ when=-1ms what=2 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  745): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,D/CaptivePortalTracker(  745): Checking http://216.58.209.46/generate_204
W/ActivityThread(  745): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,D/AmoledAdjustTimer(  745): prevTemp = 284, currTemp = 289, prevStep = 4, currStep = 4
,I/System.out(  745): Thread-164(HTTPLog):isShipBuild true
,I/System.out(  745): Thread-164(HTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,D/CaptivePortalTracker(  745): Don't send network conditions - lacking user consent.
,D/CaptivePortalTracker(  745): isCaptivePortal: ret=false rspCode=204
,D/CaptivePortalTracker(  745): Not captive network NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/CaptivePortalTracker(  745): notifyPortalCheckCompleted: captive=false ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService(  745): captivePortalCheckCompleted: ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false captive=false
,W/ProcessCpuTracker(  745): Skipping unknown process pid 5521
,D/SSRMv2:SIOP(  745): SIOP:: AP = 300, Delta = -10
,E/SMD     (  238): DCD ON
,D/PreloadUpdateManagerStateMachine( 4837): execute::IDLE:EXECUTE
,D/PreloadUpdateManagerStateMachine( 4837): exit::IDLE
,D/PreloadUpdateManagerStateMachine( 4837): entry::CHECK_TIMEOUT_FOR_UPDATE
,D/hcjo    ( 4837): AutoUpdateTriggerManager:IDLE:setInterval:86400000
,D/hcjo    ( 4837): AutoUpdateTriggerManager:IDLE:notifyNextTime
,D/PreloadUpdateManagerStateMachine( 4837): execute::CHECK_TIMEOUT_FOR_UPDATE:NO_TIMED_OUT
,D/PreloadUpdateManagerStateMachine( 4837): exit::CHECK_TIMEOUT_FOR_UPDATE
,D/PreloadUpdateManagerStateMachine( 4837): entry::IDLE
,E/SMD     (  238): DCD ON
,D/BatteryService(  745): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 288, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:3, charge type:1, power sharing:false
,D/BatteryService(  745): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  745): mCoverManager.getCoverState() : true
,D/BatteryService(  745): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1063): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1063): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1063):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1063): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1063): checkOverflow(288), More:false, Req:false Child:2
,V/HeadsetService( 3154): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3154): Disconnected process message: 10
,I/ActivityManager(  745): Waited long enough for: ServiceRecord{42cb9d50 u0 com.samsung.android.app.headlines/com.samsung.android.internal.headlines.HeadlinesService}
,E/SMD     (  238): DCD ON
,I/SELinux ( 5527): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5527):  
,D/dalvikvm(  245): GC_EXPLICIT freed 42K, 50% free 9513K/18912K, paused 19ms+26ms, total 235ms
,D/dalvikvm(  245): GC_EXPLICIT freed <1K, 50% free 9513K/18912K, paused 19ms+18ms, total 190ms
,I/SELinux ( 5527): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5527):  
I/SELinux ( 5527):  
,I/SELinux ( 5527): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5527): [DEBUG] seapp_context_lookup: seinfoCategory = samsung
,E/dalvikvm( 5527): >>>>> Normal User
,E/dalvikvm( 5527): >>>>> com.sec.spp.push:RemoteDlcProcess [ userId:0 | appId:10038 ]
,E/SELinux ( 5527): [DEBUG] seapp_context_lookup: seinfoCategory = samsung
,D/dalvikvm(  245): GC_EXPLICIT freed <1K, 50% free 9513K/18912K, paused 17ms+16ms, total 154ms
,D/TimaKeyStoreProvider( 5527): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5527): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5527): Added TimaKesytore provider
,E/SPPClientService( 5527): ============PushLog. commonIsShipBuild. stop!
,E/SPPClientService( 5527): [PushClientApplication] Push log off : This is Ship build version
,D/SPPClientService( 5527): PushLog.txt file is not deleted.
,D/SPPClientService( 5527): PushLog.txt file is not deleted.
,D/SPPClientService( 5527): ============PushLog. stop!
,I/ActivityManager(  745): Killing 2831:com.samsung.android.app.assistantmenu/1000 (adj 15): empty #43
,D/AmoledAdjustTimer(  745): prevTemp = 289, currTemp = 288, prevStep = 4, currStep = 4
,E/SMD     (  238): DCD ON
,D/SSRMv2:SIOP(  745): SIOP:: AP = 300, Delta = 0
,W/ContextImpl(  745): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  238): DCD ON
,E/SMD     (  238): DCD ON
,E/SMD     (  238): DCD ON
,D/AmoledAdjustTimer(  745): prevTemp = 288, currTemp = 288, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP(  745): SIOP:: AP = 300, Delta = 0
,V/AlarmManager(  745): waitForAlarm result :4
,V/AlarmManager(  745): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,D/Headlines( 5237): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE
,D/BatteryService(  745): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:2, charge type:1, power sharing:false
,D/BatteryService(  745): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  745): mCoverManager.getCoverState() : true
,D/BatteryService(  745): stay LED for fully charged
D/KeyguardUpdateMonitor( 1063): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1063): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1063):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1063): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3154): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3154): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1063): checkOverflow(288), More:false, Req:false Child:2
,D/Headlines( 5237): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0
,D/Headlines( 5237): Breath 30605 latestRequest time : 1450226426049 current time : 1450226456654
,E/SMD     (  238): DCD ON
,E/ActivityThread( 1780): Failed to find provider info for com.android.contacts.metadata
,D/SyncManager(  745): failed sync operation 
,D/SyncManager(  745): not retrying sync operation because the error is a hard error: 
,E/SMD     (  238): DCD ON
,V/AlarmManager(  745): waitForAlarm result :8
,V/AlarmManager(  745): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1063): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1063): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1063): checkOverflow(288), More:false, Req:false Child:2
,I/PowerManagerService(  745): [PWL] Off : 105s ago
,E/Watchdog(  745): !@Sync 5
,E/SMD     (  238): DCD ON
,D/AmoledAdjustTimer(  745): prevTemp = 288, currTemp = 285, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP(  745): SIOP:: AP = 300, Delta = 0
,E/SMD     (  238): DCD ON
,D/BatteryService(  745): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 284, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService(  745): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  745): mCoverManager.getCoverState() : true
,D/BatteryService(  745): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1063): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1063): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1063):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 1063): checkOverflow(288), More:false, Req:false Child:2
,D/BatteryMeterView( 1063): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 3154): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 3154): Disconnected process message: 10
,W/ContextImpl(  745): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  238): DCD ON
,E/SMD     (  238): DCD ON
,D/AmoledAdjustTimer(  745): prevTemp = 285, currTemp = 284, prevStep = 4, currStep = 4
,E/SMD     (  238): DCD ON
,D/SSRMv2:SIOP(  745): SIOP:: AP = 300, Delta = 0
,D/BatteryService(  745): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 283, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  745): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  745): mCoverManager.getCoverState() : true
,D/BatteryService(  745): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1063): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1063): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1063):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1063): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3154): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3154): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1063): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  238): DCD ON
,E/SMD     (  238): DCD ON
,E/SMD     (  238): DCD ON
,D/AmoledAdjustTimer(  745): prevTemp = 284, currTemp = 283, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP(  745): SIOP:: AP = 300, Delta = 0
,V/AlarmManager(  745): waitForAlarm result :4
,V/AlarmManager(  745): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,D/Headlines( 5237): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE
,D/BatteryService(  745): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:2, charge type:1, power sharing:false
,D/BatteryService(  745): stay LED for fully charged
,D/BatteryService(  745): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  745): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1063): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1063): handleBatteryUpdate
,D/Headlines( 5237): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0
,D/STATUSBAR-PhoneStatusBar( 1063):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3154): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3154): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1063): checkOverflow(288), More:false, Req:false Child:2
,D/BatteryMeterView( 1063): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/Headlines( 5237): Breath 60851 latestRequest time : 1450226426049 current time : 1450226486900
,E/SMD     (  238): DCD ON
,W/ContextImpl(  745): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  238): DCD ON
,E/Watchdog(  745): !@Sync 6
,E/SMD     (  238): DCD ON
,D/AmoledAdjustTimer(  745): prevTemp = 283, currTemp = 282, prevStep = 4, currStep = 4
,I/PowerManagerService(  745): [PWL] Off : 140s ago
,D/SSRMv2:SIOP(  745): SIOP:: AP = 300, Delta = 0
,E/SMD     (  238): DCD ON
,D/BatteryService(  745): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  745): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  745): stay LED for fully charged
,D/UiModeManager(  745): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1063): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1063): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1063):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1063): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3154): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3154): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1063): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  238): DCD ON
,E/SMD     (  238): DCD ON
,D/AmoledAdjustTimer(  745): prevTemp = 282, currTemp = 282, prevStep = 4, currStep = 4
,E/SMD     (  238): DCD ON
,D/SSRMv2:SIOP(  745): SIOP:: AP = 300, Delta = 0
,D/BatteryService(  745): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:4, charge type:1, power sharing:false
,D/BatteryService(  745): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  745): mCoverManager.getCoverState() : true
,D/BatteryService(  745): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1063): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1063): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1063):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1063): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3154): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3154): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1063): checkOverflow(288), More:false, Req:false Child:2
,W/ContextImpl(  745): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  238): DCD ON
,E/SMD     (  238): DCD ON
,E/SMD     (  238): DCD ON
,D/AmoledAdjustTimer(  745): prevTemp = 282, currTemp = 281, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP(  745): SIOP:: AP = 300, Delta = 0
,V/AlarmManager(  745): waitForAlarm result :8
,D/Headlines( 5237): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE
,D/Headlines( 5237): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0
,D/Headlines( 5237): Breath 90040 latestRequest time : 1450226426049 current time : 1450226516089
,E/SMD     (  238): DCD ON
,E/SMD     (  238): DCD ON
V/AlarmManager(  745): waitForAlarm result :8
V/AlarmManager(  745): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1063): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1063): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1063): checkOverflow(288), More:false, Req:false Child:2
,E/Watchdog(  745): !@Sync 7
,E/SMD     (  238): DCD ON
,D/AmoledAdjustTimer(  745): prevTemp = 281, currTemp = 281, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP(  745): SIOP:: AP = 300, Delta = 0
,E/SMD     (  238): DCD ON
,D/BatteryService(  745): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 280, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:7, charge type:1, power sharing:false
,D/BatteryService(  745): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  745): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1063): received broadcast android.intent.action.BATTERY_CHANGED
,D/UiModeManager(  745): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 1063): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1063):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1063): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3154): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3154): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1063): checkOverflow(288), More:false, Req:false Child:2
,W/ContextImpl(  745): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  238): DCD ON
,E/SMD     (  238): DCD ON
,D/AmoledAdjustTimer(  745): prevTemp = 281, currTemp = 280, prevStep = 4, currStep = 4
,E/SMD     (  238): DCD ON
,I/PowerManagerService(  745): [PWL] Off : 180s ago
,D/SSRMv2:SIOP(  745): SIOP:: AP = 300, Delta = 0
,D/BatteryService(  745): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 280, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:8, charge type:1, power sharing:false
,D/BatteryService(  745): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  745): stay LED for fully charged
,D/UiModeManager(  745): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1063): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1063): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1063):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1063): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3154): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3154): Disconnected process message: 10
D/STATUSBAR-IconMerger( 1063): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  238): DCD ON
,E/SMD     (  238): DCD ON
,E/SMD     (  238): DCD ON
,D/AmoledAdjustTimer(  745): prevTemp = 280, currTemp = 280, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP(  745): SIOP:: AP = 300, Delta = 0
,V/AlarmManager(  745): waitForAlarm result :8
,D/Headlines( 5237): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE
,D/Headlines( 5237): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0
,D/Headlines( 5237): Breath 120039 latestRequest time : 1450226426049 current time : 1450226546092
,D/Headlines( 5237): stop 
,D/Headlines( 5237): Breath.onDestroy : 
,I/ActivityManager(  745): Killing 4713:com.sec.android.service.cm/u0a78 (adj 15): empty #43
,E/SMD     (  238): DCD ON
,D/BatteryService(  745): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:7, charge type:1, power sharing:false
,D/BatteryService(  745): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  745): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1063): received broadcast android.intent.action.BATTERY_CHANGED
,D/BatteryService(  745): stay LED for fully charged
D/KeyguardUpdateMonitor( 1063): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1063):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1063): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3154): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/STATUSBAR-IconMerger( 1063): checkOverflow(288), More:false, Req:false Child:2
D/HeadsetStateMachine( 3154): Disconnected process message: 10
,W/ContextImpl(  745): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  238): DCD ON
,E/Watchdog(  745): !@Sync 8
,E/SMD     (  238): DCD ON
,D/AmoledAdjustTimer(  745): prevTemp = 280, currTemp = 279, prevStep = 4, currStep = 4
,E/SMD     (  238): DCD ON
,D/SSRMv2:SIOP(  745): SIOP:: AP = 300, Delta = 0
,D/BatteryService(  745): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:4, charge type:1, power sharing:false
,D/BatteryService(  745): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  745): stay LED for fully charged
,D/UiModeManager(  745): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1063): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1063): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1063):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1063): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3154): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3154): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1063): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  238): DCD ON
,E/SMD     (  238): DCD ON
,D/AmoledAdjustTimer(  745): prevTemp = 279, currTemp = 279, prevStep = 4, currStep = 4
,E/SMD     (  238): DCD ON
,D/SSRMv2:SIOP(  745): SIOP:: AP = 300, Delta = 0
,D/BatteryService(  745): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:5, charge type:1, power sharing:false
,D/BatteryService(  745): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  745): stay LED for fully charged
,D/UiModeManager(  745): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1063): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1063): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1063):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1063): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3154): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3154): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1063): checkOverflow(288), More:false, Req:false Child:2
,W/ContextImpl(  745): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  238): DCD ON
,E/SMD     (  238): DCD ON
,E/SMD     (  238): DCD ON
,D/AmoledAdjustTimer(  745): prevTemp = 279, currTemp = 279, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP(  745): SIOP:: AP = 300, Delta = 0
,E/SMD     (  238): DCD ON
,D/BatteryService(  745): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:4, charge type:1, power sharing:false
,D/BatteryService(  745): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  745): stay LED for fully charged
,D/UiModeManager(  745): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1063): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1063): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1063):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1063): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3154): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3154): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1063): checkOverflow(288), More:false, Req:false Child:2
,V/AlarmManager(  745): waitForAlarm result :8
,V/AlarmManager(  745): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1063): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1063): handleTimeUpdate
,E/SMD     (  238): DCD ON
,D/STATUSBAR-IconMerger( 1063): checkOverflow(288), More:false, Req:false Child:2
,I/PowerManagerService(  745): [PWL] Off : 225s ago
,E/Watchdog(  745): !@Sync 9
,E/SMD     (  238): DCD ON
,D/AmoledAdjustTimer(  745): prevTemp = 279, currTemp = 278, prevStep = 4, currStep = 4
,E/SMD     (  238): DCD ON
,D/SSRMv2:SIOP(  745): SIOP:: AP = 300, Delta = 0
,D/BatteryService(  745): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:2, charge type:1, power sharing:false
,D/BatteryService(  745): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  745): stay LED for fully charged
,D/UiModeManager(  745): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1063): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1063): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1063):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1063): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ContextImpl(  745): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/STATUSBAR-IconMerger( 1063): checkOverflow(288), More:false, Req:false Child:2
V/HeadsetService( 3154): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 3154): Disconnected process message: 10
,E/SMD     (  238): DCD ON
,E/SMD     (  238): DCD ON
,D/AmoledAdjustTimer(  745): prevTemp = 278, currTemp = 278, prevStep = 4, currStep = 4
,E/SMD     (  238): DCD ON
,D/SSRMv2:SIOP(  745): SIOP:: AP = 300, Delta = 0
,D/BatteryService(  745): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:6, charge type:1, power sharing:false
,D/BatteryService(  745): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  745): mCoverManager.getCoverState() : true
,D/BatteryService(  745): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1063): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1063): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1063):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1063): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3154): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3154): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1063): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  238): DCD ON
,E/SMD     (  238): DCD ON
,E/SMD     (  238): DCD ON
,D/AmoledAdjustTimer(  745): prevTemp = 278, currTemp = 278, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP(  745): SIOP:: AP = 300, Delta = 0
,D/TimaService(  745): TIMA: TimaService scheduler is intialized. 
,D/TimaService(  745): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService(  745): TimaServiceHandler.handleMessage what =1
,I/TLC_TIMA_PKM_initialize(  745): initializing...
,I/TLC_TIMA_PKM_initialize(  745): root = /firmware/image, root_strlen = 15
,I/TLC_TIMA_PKM_initialize(  745): process = tima_pkm, process_strlen = 8
,I/TZ: qc_tlc_communication(  745): root = /firmware/image, root_len = 15
,I/TZ: qc_tlc_communication(  745): process = tima_pkm, process_strlen = 8
I/TZ: qc_tlc_communication(  745): aligned max_sendmsg_size = 262208 = 0x40040
,I/TZ: qc_tlc_communication(  745): aligned max_recvmsg_size = 262208 = 0x40040
,I/TZ: qc_tlc_communication(  745): max_message_size = 524416 = 0x80080
,D/QSEECOMAPI: (  745): QSEECom_get_handle sb_length = 0x80080
,D/QSEECOMAPI: (  745): App is not loaded in QSEE
,D/QSEECOMAPI: (  745): Loaded image: APP id = 4
,I/TZ: qc_tlc_communication(  745): TIMA: path = /firmware/image, fname = tima_pkm, tzapp is loaded
,I/TLC_TIMA_PKM_initialize(  745): Trustlet response is completed
,E/SMD     (  238): DCD ON
,W/ContextImpl(  745): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/BatteryService(  745): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:10, charge type:1, power sharing:false
,D/BatteryService(  745): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  745): mCoverManager.getCoverState() : true
,D/BatteryService(  745): stay LED for fully charged
D/KeyguardUpdateMonitor( 1063): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1063): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1063):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 1063): checkOverflow(288), More:false, Req:false Child:2
,D/BatteryMeterView( 1063): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 3154): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 3154): Disconnected process message: 10
,E/SMD     (  238): DCD ON
,I/TLC_TIMA_PKM_measure_kernel(  745): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel(  745): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService(  745): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService(  745): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/Watchdog(  745): !@Sync 10
,E/SMD     (  238): DCD ON
,D/AmoledAdjustTimer(  745): prevTemp = 278, currTemp = 278, prevStep = 4, currStep = 4
,E/SMD     (  238): DCD ON
,D/SSRMv2:SIOP(  745): SIOP:: AP = 300, Delta = 0
,D/BatteryService(  745): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  745): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  745): mCoverManager.getCoverState() : true
,D/BatteryService(  745): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1063): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1063): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1063):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1063): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3154): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3154): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1063): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  238): DCD ON
,E/SMD     (  238): DCD ON
,D/AmoledAdjustTimer(  745): prevTemp = 278, currTemp = 277, prevStep = 4, currStep = 4
,E/SMD     (  238): DCD ON
,D/SSRMv2:SIOP(  745): SIOP:: AP = 300, Delta = 0
,W/ContextImpl(  745): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  238): DCD ON
,I/PowerManagerService(  745): [PWL] Off : 275s ago
,E/SMD     (  238): DCD ON
,V/AlarmManager(  745): waitForAlarm result :4
,V/AlarmManager(  745): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,I/SELinux ( 5598): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5598):  
D/BatteryService(  745): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
D/BatteryService(  745): Sending ACTION_BATTERY_CHANGED.
D/BatteryService(  745): stay LED for fully charged
,D/UiModeManager(  745): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1063): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1063): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1063):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 1063): checkOverflow(288), More:false, Req:false Child:2
,D/BatteryMeterView( 1063): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3154): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3154): Disconnected process message: 10
,I/SELinux ( 5598): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5598):  
I/SELinux ( 5598):  
,I/SELinux ( 5598): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5598): [DEBUG] seapp_context_lookup: seinfoCategory = default
,E/dalvikvm( 5598): >>>>> Normal User
,E/dalvikvm( 5598): >>>>> com.blurb.checkout [ userId:0 | appId:10075 ]
,E/SELinux ( 5598): [DEBUG] seapp_context_lookup: seinfoCategory = default
,D/TimaKeyStoreProvider( 5598): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5598): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5598): Added TimaKesytore provider
,W/ActivityManager(  745): Permission Denial: getCurrentUser() from pid=5598, uid=10075 requires android.permission.INTERACT_ACROSS_USERS
,I/ActivityManager(  745): Killing 4725:com.google.android.apps.docs/u0a90 (adj 15): empty #43
,E/SMD     (  238): DCD ON
,D/AmoledAdjustTimer(  745): prevTemp = 277, currTemp = 277, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP(  745): SIOP:: AP = 300, Delta = 0
,E/SMD     (  238): DCD ON
,V/AlarmManager(  745): waitForAlarm result :8
,V/AlarmManager(  745): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1063): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1063): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1063): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  238): DCD ON
,V/GLSActivity( 1303): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1303): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/dalvikvm( 3513): GC_CONCURRENT freed 2757K, 45% free 10436K/18912K, paused 14ms+16ms, total 184ms
,E/Watchdog(  745): !@Sync 11
,D/BatteryService(  745): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-2, charge type:1, power sharing:false
,D/BatteryService(  745): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  745): mCoverManager.getCoverState() : true
,D/BatteryService(  745): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1063): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1063): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1063):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1063): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3154): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3154): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1063): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  238): DCD ON
,D/AmoledAdjustTimer(  745): prevTemp = 277, currTemp = 277, prevStep = 4, currStep = 4
,E/SMD     (  238): DCD ON
,D/SSRMv2:SIOP(  745): SIOP:: AP = 300, Delta = 0
,W/ContextImpl(  745): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  238): DCD ON
,E/SMD     (  238): DCD ON
,D/BatteryService(  745): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:11, charge type:1, power sharing:false
,D/BatteryService(  745): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  745): mCoverManager.getCoverState() : true
,D/BatteryService(  745): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1063): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1063): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1063):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1063): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3154): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3154): Disconnected process message: 10
D/STATUSBAR-IconMerger( 1063): checkOverflow(288), More:false, Req:false Child:2
,D/AmoledAdjustTimer(  745): prevTemp = 277, currTemp = 277, prevStep = 4, currStep = 4
,E/SMD     (  238): DCD ON
,D/SSRMv2:SIOP(  745): SIOP:: AP = 300, Delta = 0
,E/SMD     (  238): DCD ON
,E/SMD     (  238): DCD ON
,D/BatteryService(  745): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:9, charge type:1, power sharing:false
,D/BatteryService(  745): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  745): mCoverManager.getCoverState() : true
,D/BatteryService(  745): stay LED for fully charged
D/KeyguardUpdateMonitor( 1063): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1063): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1063):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1063): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3154): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3154): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1063): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  238): DCD ON
,D/AmoledAdjustTimer(  745): prevTemp = 277, currTemp = 276, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP(  745): SIOP:: AP = 300, Delta = 0
,E/SMD     (  238): DCD ON
,W/ContextImpl(  745): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  238): DCD ON
,E/Watchdog(  745): !@Sync 12
,D/BatteryService(  745): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:10, charge type:1, power sharing:false
,D/BatteryService(  745): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  745): mCoverManager.getCoverState() : true
,D/BatteryService(  745): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1063): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1063): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1063):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1063): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3154): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3154): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1063): checkOverflow(288), More:false, Req:false Child:2
E/SMD     (  238): DCD ON
,D/AmoledAdjustTimer(  745): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,E/SMD     (  238): DCD ON
,D/SSRMv2:SIOP(  745): SIOP:: AP = 300, Delta = 0
,E/SMD     (  238): DCD ON
,E/SMD     (  238): DCD ON
,D/BatteryService(  745): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:3, charge type:1, power sharing:false
,D/BatteryService(  745): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  745): stay LED for fully charged
,D/UiModeManager(  745): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1063): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1063): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1063):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1063): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3154): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3154): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1063): checkOverflow(288), More:false, Req:false Child:2
,D/AmoledAdjustTimer(  745): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,E/SMD     (  238): DCD ON
,I/PowerManagerService(  745): [PWL] Off : 330s ago
,D/SSRMv2:SIOP(  745): SIOP:: AP = 300, Delta = 0
,W/ContextImpl(  745): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  238): DCD ON
,I/jxcore-log( 4670): Connected to the server!
I/jxcore-log( 4670): 
,I/chromium( 4670): [INFO:CONSOLE(63)] "logCallback Connected to the server", source: file:///android_asset/www/js/thali_main.js (63)
,E/SMD     (  238): DCD ON
,I/jxcore-log( 4670): --- start :testFindPeers.js---
I/jxcore-log( 4670): 
,I/jxcore-log( 4670): testFindPeers created [object Object]
I/jxcore-log( 4670): 
,I/jxcore-log( 4670): serverPort is 8876
I/jxcore-log( 4670): 
,I/dalvikvm( 4670): Could not find method android.bluetooth.BluetoothAdapter.isMultipleAdvertisementSupported, referenced from method org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager.isBleAdvertisingSupported
,W/dalvikvm( 4670): VFY: unable to resolve virtual method 52: Landroid/bluetooth/BluetoothAdapter;.isMultipleAdvertisementSupported ()Z
,D/dalvikvm( 4670): VFY: replacing opcode 0x6e at 0x0019
,I/dalvikvm( 4670): Could not find method android.bluetooth.BluetoothAdapter.isMultipleAdvertisementSupported, referenced from method org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager.isBleAdvertisingSupported
W/dalvikvm( 4670): VFY: unable to resolve virtual method 52: Landroid/bluetooth/BluetoothAdapter;.isMultipleAdvertisementSupported ()Z
,D/dalvikvm( 4670): VFY: replacing opcode 0x6e at 0x0020
,D/AndroidRuntime( 4670): Shutting down VM
,W/dalvikvm( 4670): threadid=1: thread exiting with uncaught exception (group=0x4186eda0)
,E/AndroidRuntime( 4670): FATAL EXCEPTION: main
E/AndroidRuntime( 4670): Process: com.test.thalitest, PID: 4670
E/AndroidRuntime( 4670): java.lang.NoSuchMethodError: android.bluetooth.BluetoothAdapter.isMultipleAdvertisementSupported
E/AndroidRuntime( 4670): 	at org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager.isBleAdvertisingSupported(BluetoothManager.java:134)
E/AndroidRuntime( 4670): 	at org.thaliproject.p2p.btconnectorlib.DiscoveryManager.setDiscoveryMode(DiscoveryManager.java:133)
E/AndroidRuntime( 4670): 	at org.thaliproject.p2p.btconnectorlib.DiscoveryManager.setDiscoveryMode(DiscoveryManager.java:183)
E/AndroidRuntime( 4670): 	at org.thaliproject.p2p.btconnectorlib.DiscoveryManager.<init>(DiscoveryManager.java:95)
E/AndroidRuntime( 4670): 	at io.jxcore.node.ConnectionHelper.start(ConnectionHelper.java:92)
E/AndroidRuntime( 4670): 	at io.jxcore.node.JXcoreExtension$5.Receiver(JXcoreExtension.java:155)
E/AndroidRuntime( 4670): 	at io.jxcore.node.jxcore.javaCall(jxcore.java:228)
E/AndroidRuntime( 4670): 	at io.jxcore.node.jxcore.loopOnce(Native Method)
E/AndroidRuntime( 4670): 	at io.jxcore.node.jxcore$4.run(jxcore.java:196)
E/AndroidRuntime( 4670): 	at android.os.Handler.handleCallback(Handler.java:733)
E/AndroidRuntime( 4670): 	at android.os.Handler.dispatchMessage(Handler.java:95)
E/AndroidRuntime( 4670): 	at android.os.Looper.loop(Looper.java:146)
E/AndroidRuntime( 4670): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/AndroidRuntime( 4670): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime( 4670): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime( 4670): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/AndroidRuntime( 4670): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/AndroidRuntime( 4670): 	at dalvik.system.NativeStart.main(Native Method)
,W/ActivityManager(  745):   Force finishing activity com.test.thalitest/.MainActivity
,D/LockPatternUtils( 1063): isPcwEnable = null
,I/ActivityManager(  745): Killing 4768:com.samsung.android.app.watchmanagerstub/u0a100 (adj 15): empty #43
,D/CrashAnrDetector(  745): processName: com.test.thalitest
,D/CrashAnrDetector(  745): broadcastEvent : com.test.thalitest data_app_crash
,W/ContextImpl(  745): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1515 com.android.server.analytics.data.collection.application.CrashAnrDetector.broadcastEvent:296 com.android.server.analytics.data.collection.application.CrashAnrDetector.processDropBoxEntry:254 com.android.server.analytics.data.collection.application.CrashAnrDetector.access$100:60 com.android.server.analytics.data.collection.application.CrashAnrDetector$1.onReceive:102 
,I/Process ( 4670): Sending signal. PID: 4670 SIG: 9
,D/CustomFrequencyManagerService(  745): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 745  pkgName : ACTIVITY_RESUME_BOOSTER@5
,W/ActivityManager(  745): mDVFSHelper.acquire()
,D/KeyguardUpdateMonitor( 1063): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1063): handleKeyguardVisibilityChanged(1)
,D/KeyguardUpdateMonitor( 1063): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1063): handleKeyguardVisibilityChanged(1)
,D/KeyguardUpdateMonitor( 1063): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1063): handleKeyguardVisibilityChanged(1)
,D/LockPatternUtils( 1063): isPcwEnable = null
,D/Launcher( 1259): onRestart, Launcher: 1114327080
,D/Launcher( 1259): onStart, Launcher: 1114327080
,D/Launcher.HomeView( 1259): onStart
,D/SurfaceWidgetClient$ISurfaceWidgetStub( 1442): [237392/5] Surface widget visibility changed visibility = true on instance = 1
,D/SurfaceWidget.Renderer( 1442): [237392/5] SurfaceWidget drawing first frame
,D/KeyguardUpdateMonitor( 1063): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1063): handleKeyguardVisibilityChanged(1)
,I/SurfaceFlinger(  244): id=20 createSurf (1x1),2 flag=404, CatteryCove
,D/KeyguardUpdateMonitor( 1063): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1063): handleKeyguardVisibilityChanged(1)
,I/SurfaceFlinger(  244): id=21 createSurf (720x1280),1 flag=4, Mauncher
,D/KeyguardUpdateMonitor( 1063): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1063): handleKeyguardVisibilityChanged(1)
,D/KeyguardUpdateMonitor( 1063): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1063): handleKeyguardVisibilityChanged(1)
,I/SurfaceFlinger(  244): id=18 Removed NainActivit (9/13)
,I/SurfaceFlinger(  244): id=18 Removed NainActivit (-2/13)
,D/KeyguardUpdateMonitor( 1063): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1063): handleKeyguardVisibilityChanged(1)
I/ActivityManager(  745): Process com.test.thalitest (pid 4670) (adj 9) has died.
,I/WindowState(  745): WIN DEATH: Window{4317be68 u0 com.test.thalitest/com.test.thalitest.MainActivity}
I/SurfaceFlinger(  244): id=22 createSurf (707x984),1 flag=4, TettingsRec
D/KeyguardUpdateMonitor( 1063): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1063): handleKeyguardVisibilityChanged(1)
,D/KeyguardUpdateMonitor( 1063): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1063): handleKeyguardVisibilityChanged(1)
D/CustomFrequencyManagerService(  745): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 745  tag : ACTIVITY_RESUME_BOOSTER@5
W/ActivityManager(  745): mDVFSHelper.release()
D/CustomFrequencyManagerService(  745): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 745  pkgName : ACTIVITY_RESUME_BOOSTER@9
,D/Launcher.HomeView( 1259): onStop
,D/KeyguardUpdateMonitor( 1063): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1063): handleKeyguardVisibilityChanged(1)
,D/KeyguardUpdateMonitor( 1063): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1063): handleKeyguardVisibilityChanged(1)
,D/KeyguardUpdateMonitor( 1063): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1063): handleKeyguardVisibilityChanged(1)
,D/KeyguardUpdateMonitor( 1063): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1063): handleKeyguardVisibilityChanged(1)
,D/BatteryService(  745): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:2, charge type:1, power sharing:false
,D/BatteryService(  745): stay LED for fully charged
,D/BatteryService(  745): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  745): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 1063): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1063): handleBatteryUpdate
,V/HeadsetService( 3154): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3154): Disconnected process message: 10
,D/STATUSBAR-PhoneStatusBar( 1063):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1063): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1063): checkOverflow(288), More:false, Req:false Child:2
,D/CustomFrequencyManagerService(  745): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 745  tag : ACTIVITY_RESUME_BOOSTER@9
,E/SMD     (  238): DCD ON
,D/AmoledAdjustTimer(  745): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP(  745): SIOP:: AP = 300, Delta = 0
,D/dalvikvm(  745): GC_CONCURRENT freed 3151K, 58% free 23656K/55200K, paused 21ms+41ms, total 424ms
,E/SMD     (  238): DCD ON
,V/AlarmManager(  745): waitForAlarm result :8
,V/AlarmManager(  745): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1063): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1063): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1063): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  238): DCD ON
,E/Watchdog(  745): !@Sync 13
,E/SMD     (  238): DCD ON
,D/BatteryService(  745): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:4, charge type:1, power sharing:false
,D/BatteryService(  745): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  745): mCoverManager.getCoverState() : true
,D/BatteryService(  745): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1063): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1063): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1063):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1063): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3154): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3154): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1063): checkOverflow(288), More:false, Req:false Child:2
,D/AmoledAdjustTimer(  745): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,E/SMD     (  238): DCD ON
,D/SSRMv2:SIOP(  745): SIOP:: AP = 300, Delta = 0
,W/ContextImpl(  745): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  238): DCD ON
,E/SMD     (  238): DCD ON
,D/BatteryService(  745): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:3, charge type:1, power sharing:false
,D/BatteryService(  745): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  745): stay LED for fully charged
,D/UiModeManager(  745): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1063): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1063): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1063):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1063): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 3154): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 3154): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1063): checkOverflow(288), More:false, Req:false Child:2
,D/AmoledAdjustTimer(  745): prevTemp = 276, currTemp = 275, prevStep = 4, currStep = 4
,E/SMD     (  238): DCD ON
,D/SSRMv2:SIOP(  745): SIOP:: AP = 300, Delta = 0
,E/SMD     (  238): DCD ON
,E/SMD     (  238): DCD ON
,D/BatteryService(  745): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  745): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  745): stay LED for fully charged
,D/UiModeManager(  745): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1063): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1063): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1063):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3154): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3154): Disconnected process message: 10
D/BatteryMeterView( 1063): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1063): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  238): DCD ON
,D/AmoledAdjustTimer(  745): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP(  745): SIOP:: AP = 300, Delta = 0
,E/SMD     (  238): DCD ON
,W/ContextImpl(  745): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  238): DCD ON
,E/Watchdog(  745): !@Sync 14
,E/SMD     (  238): DCD ON
,D/BatteryService(  745): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService(  745): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  745): mCoverManager.getCoverState() : true
,D/BatteryService(  745): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1063): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1063): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1063):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3154): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3154): Disconnected process message: 10
D/BatteryMeterView( 1063): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1063): checkOverflow(288), More:false, Req:false Child:2
,D/AmoledAdjustTimer(  745): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,E/SMD     (  238): DCD ON
,D/SSRMv2:SIOP(  745): SIOP:: AP = 300, Delta = 0
,E/SMD     (  238): DCD ON
,E/SMD     (  238): DCD ON
,D/BatteryService(  745): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:3, charge type:1, power sharing:false
,D/BatteryService(  745): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  745): stay LED for fully charged
,D/UiModeManager(  745): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1063): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1063): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1063):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1063): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 3154): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 3154): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1063): checkOverflow(288), More:false, Req:false Child:2
,D/AmoledAdjustTimer(  745): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,E/SMD     (  238): DCD ON
,I/PowerManagerService(  745): [PWL] Off : 390s ago
,D/SSRMv2:SIOP(  745): SIOP:: AP = 300, Delta = 0
,W/ContextImpl(  745): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  238): DCD ON
,E/SMD     (  238): DCD ON
,D/BatteryService(  745): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:2, charge type:1, power sharing:false
,D/BatteryService(  745): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  745): stay LED for fully charged
,D/UiModeManager(  745): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1063): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1063): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1063):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1063): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3154): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3154): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1063): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  238): DCD ON
,D/AmoledAdjustTimer(  745): prevTemp = 275, currTemp = 274, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP(  745): SIOP:: AP = 300, Delta = 0
,E/SMD     (  238): DCD ON
,V/AlarmManager(  745): waitForAlarm result :8
,V/AlarmManager(  745): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1063): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1063): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1063): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  238): DCD ON
,E/Watchdog(  745): !@Sync 15
,E/SMD     (  238): DCD ON
,D/BatteryService(  745): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:3, charge type:1, power sharing:false
,D/BatteryService(  745): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  745): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1063): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1063): handleBatteryUpdate
D/UiModeManager(  745): mCoverManager.getCoverState() : true
,D/STATUSBAR-PhoneStatusBar( 1063):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1063): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 3154): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 3154): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1063): checkOverflow(288), More:false, Req:false Child:2
,D/AmoledAdjustTimer(  745): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,E/SMD     (  238): DCD ON
,D/SSRMv2:SIOP(  745): SIOP:: AP = 300, Delta = 0
,W/ContextImpl(  745): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  238): DCD ON
,E/SMD     (  238): DCD ON
,D/BatteryService(  745): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:4, charge type:1, power sharing:false
,D/BatteryService(  745): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  745): mCoverManager.getCoverState() : true
,D/BatteryService(  745): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1063): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1063): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1063):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3154): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3154): Disconnected process message: 10
D/BatteryMeterView( 1063): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1063): checkOverflow(288), More:false, Req:false Child:2
,D/AmoledAdjustTimer(  745): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,E/SMD     (  238): DCD ON
,D/SSRMv2:SIOP(  745): SIOP:: AP = 300, Delta = 0
,E/SMD     (  238): DCD ON
,E/SMD     (  238): DCD ON
,E/SMD     (  238): DCD ON
,D/BatteryService(  745): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:3, charge type:1, power sharing:false
,D/BatteryService(  745): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  745): mCoverManager.getCoverState() : true
,D/BatteryService(  745): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1063): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1063): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1063):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1063): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3154): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3154): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1063): checkOverflow(288), More:false, Req:false Child:2
,D/AmoledAdjustTimer(  745): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP(  745): SIOP:: AP = 300, Delta = 0
,E/SMD     (  238): DCD ON
,W/ContextImpl(  745): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  238): DCD ON
,E/Watchdog(  745): !@Sync 16
,E/SMD     (  238): DCD ON
,D/BatteryService(  745): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:6, charge type:1, power sharing:false
,D/BatteryService(  745): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  745): mCoverManager.getCoverState() : true
,D/BatteryService(  745): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1063): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1063): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1063):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1063): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 3154): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 3154): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1063): checkOverflow(288), More:false, Req:false Child:2
,D/AmoledAdjustTimer(  745): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,E/SMD     (  238): DCD ON
,D/SSRMv2:SIOP(  745): SIOP:: AP = 300, Delta = 0
,E/SMD     (  238): DCD ON
,E/SMD     (  238): DCD ON
,D/BatteryService(  745): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:2, charge type:1, power sharing:false
,D/BatteryService(  745): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  745): stay LED for fully charged
,D/UiModeManager(  745): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1063): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1063): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1063):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1063): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 3154): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 3154): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1063): checkOverflow(288), More:false, Req:false Child:2
,D/AmoledAdjustTimer(  745): prevTemp = 274, currTemp = 273, prevStep = 4, currStep = 4
,E/SMD     (  238): DCD ON
,D/SSRMv2:SIOP(  745): SIOP:: AP = 300, Delta = 0
,W/ContextImpl(  745): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  238): DCD ON
,I/PowerManagerService(  745): [PWL] Off : 455s ago
,E/SMD     (  238): DCD ON
,E/SMD     (  238): DCD ON
,D/AmoledAdjustTimer(  745): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP(  745): SIOP:: AP = 300, Delta = 0
,E/SMD     (  238): DCD ON
,V/AlarmManager(  745): waitForAlarm result :8
,V/AlarmManager(  745): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1063): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1063): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1063): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  238): DCD ON
,E/Watchdog(  745): !@Sync 17
,E/SMD     (  238): DCD ON
,D/AmoledAdjustTimer(  745): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,E/SMD     (  238): DCD ON
,D/SSRMv2:SIOP(  745): SIOP:: AP = 300, Delta = 0
,W/ContextImpl(  745): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  238): DCD ON
,E/SMD     (  238): DCD ON
,D/AmoledAdjustTimer(  745): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,D/BatteryService(  745): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:8, charge type:1, power sharing:false
,D/BatteryService(  745): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  745): mCoverManager.getCoverState() : true
,D/BatteryService(  745): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1063): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1063): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1063):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3154): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3154): Disconnected process message: 10
D/BatteryMeterView( 1063): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1063): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  238): DCD ON
,D/SSRMv2:SIOP(  745): SIOP:: AP = 300, Delta = 0
,E/SMD     (  238): DCD ON
,E/SMD     (  238): DCD ON
,E/SMD     (  238): DCD ON
,D/AmoledAdjustTimer(  745): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,D/BatteryService(  745): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:6, charge type:1, power sharing:false
,D/BatteryService(  745): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  745): mCoverManager.getCoverState() : true
,D/BatteryService(  745): stay LED for fully charged
D/KeyguardUpdateMonitor( 1063): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1063): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1063):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3154): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3154): Disconnected process message: 10
D/BatteryMeterView( 1063): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1063): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  745): SIOP:: AP = 300, Delta = 0
,E/SMD     (  238): DCD ON
,W/ContextImpl(  745): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  238): DCD ON
,E/Watchdog(  745): !@Sync 18
,E/SMD     (  238): DCD ON
,D/AmoledAdjustTimer(  745): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,D/BatteryService(  745): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:7, charge type:1, power sharing:false
,D/BatteryService(  745): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  745): mCoverManager.getCoverState() : true
,D/BatteryService(  745): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1063): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1063): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1063):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1063): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 3154): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 3154): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1063): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  238): DCD ON
,D/SSRMv2:SIOP(  745): SIOP:: AP = 300, Delta = 0
,E/SMD     (  238): DCD ON
,E/SMD     (  238): DCD ON
,D/AmoledAdjustTimer(  745): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,D/BatteryService(  745): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:6, charge type:1, power sharing:false
,D/BatteryService(  745): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  745): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1063): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1063): handleBatteryUpdate
D/BatteryService(  745): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1063):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1063): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 3154): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 3154): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1063): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  238): DCD ON
,D/SSRMv2:SIOP(  745): SIOP:: AP = 300, Delta = 0
,W/ContextImpl(  745): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  238): DCD ON
,E/SMD     (  238): DCD ON
,E/SMD     (  238): DCD ON
,D/AmoledAdjustTimer(  745): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,D/BatteryService(  745): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:10, charge type:1, power sharing:false
,D/BatteryService(  745): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  745): mCoverManager.getCoverState() : true
,D/BatteryService(  745): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1063): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1063): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1063):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1063): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3154): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3154): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1063): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  238): DCD ON
,D/SSRMv2:SIOP(  745): SIOP:: AP = 300, Delta = 0
,V/AlarmManager(  745): waitForAlarm result :8
,V/AlarmManager(  745): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1063): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1063): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1063): checkOverflow(288), More:false, Req:false Child:2
,I/PowerManagerService(  745): [PWL] Off : 525s ago
,E/SMD     (  238): DCD ON
,E/Watchdog(  745): !@Sync 19
,E/SMD     (  238): DCD ON
,D/AmoledAdjustTimer(  745): prevTemp = 273, currTemp = 272, prevStep = 4, currStep = 4
,D/BatteryService(  745): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:7, charge type:1, power sharing:false
,D/BatteryService(  745): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  745): mCoverManager.getCoverState() : true
,D/BatteryService(  745): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1063): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1063): handleBatteryUpdate
,V/HeadsetService( 3154): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1063):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/HeadsetStateMachine( 3154): Disconnected process message: 10
D/BatteryMeterView( 1063): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1063): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  238): DCD ON
,D/SSRMv2:SIOP(  745): SIOP:: AP = 300, Delta = 0
,W/ContextImpl(  745): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  238): DCD ON
,E/SMD     (  238): DCD ON
,D/AmoledAdjustTimer(  745): prevTemp = 272, currTemp = 273, prevStep = 4, currStep = 4
,E/SMD     (  238): DCD ON
,D/BatteryService(  745): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  745): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  745): mCoverManager.getCoverState() : true
,D/BatteryService(  745): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1063): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1063): handleBatteryUpdate
,V/HeadsetService( 3154): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3154): Disconnected process message: 10
,D/STATUSBAR-PhoneStatusBar( 1063):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1063): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1063): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  745): SIOP:: AP = 300, Delta = 0
,E/SMD     (  238): DCD ON
,E/SMD     (  238): DCD ON
,E/SMD     (  238): DCD ON
,D/AmoledAdjustTimer(  745): prevTemp = 273, currTemp = 272, prevStep = 4, currStep = 4
,D/BatteryService(  745): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:10, charge type:1, power sharing:false
,D/BatteryService(  745): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  745): stay LED for fully charged
,D/UiModeManager(  745): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1063): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1063): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1063):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1063): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1063): checkOverflow(288), More:false, Req:false Child:2
,V/HeadsetService( 3154): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3154): Disconnected process message: 10
,D/TimaService(  745): TIMA: TimaService scheduler is intialized. 
,D/TimaService(  745): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService(  745): TimaServiceHandler.handleMessage what =1
,E/SMD     (  238): DCD ON
,D/SSRMv2:SIOP(  745): SIOP:: AP = 300, Delta = 0
,W/ContextImpl(  745): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,I/TLC_TIMA_PKM_measure_kernel(  745): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel(  745): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService(  745): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService(  745): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/SMD     (  238): DCD ON
,E/Watchdog(  745): !@Sync 20
,E/SMD     (  238): DCD ON
,D/AmoledAdjustTimer(  745): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,E/SMD     (  238): DCD ON
,D/SSRMv2:SIOP(  745): SIOP:: AP = 300, Delta = 0
,E/SMD     (  238): DCD ON
,E/SMD     (  238): DCD ON
,D/AmoledAdjustTimer(  745): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,E/SMD     (  238): DCD ON
,D/BatteryService(  745): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  745): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  745): mCoverManager.getCoverState() : true
,D/BatteryService(  745): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1063): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1063): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1063):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3154): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3154): Disconnected process message: 10
D/BatteryMeterView( 1063): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1063): checkOverflow(288), More:false, Req:false Child:2
,W/ContextImpl(  745): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/SSRMv2:SIOP(  745): SIOP:: AP = 300, Delta = 0
,E/SMD     (  238): DCD ON
,E/SMD     (  238): DCD ON
,E/SMD     (  238): DCD ON
,D/AmoledAdjustTimer(  745): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,E/SMD     (  238): DCD ON
,D/SSRMv2:SIOP(  745): SIOP:: AP = 300, Delta = 0
,V/AlarmManager(  745): waitForAlarm result :8
,V/AlarmManager(  745): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1063): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1063): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1063): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  238): DCD ON
,E/Watchdog(  745): !@Sync 21
,E/SMD     (  238): DCD ON
,D/AmoledAdjustTimer(  745): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,E/SMD     (  238): DCD ON
,D/SSRMv2:SIOP(  745): SIOP:: AP = 300, Delta = 0
,E/SMD     (  238): DCD ON
,E/SMD     (  238): DCD ON
,D/AmoledAdjustTimer(  745): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,I/PowerManagerService(  745): [PWL] Off : 600s ago
,E/SMD     (  238): DCD ON
,D/BatteryService(  745): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:4, charge type:1, power sharing:false
,D/BatteryService(  745): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  745): mCoverManager.getCoverState() : true
,D/BatteryService(  745): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1063): received broadcast android.intent.action.BATTERY_CHANGED,
,D/KeyguardUpdateMonitor( 1063): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1063):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3154): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3154): Disconnected process message: 10
D/BatteryMeterView( 1063): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1063): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  745): SIOP:: AP = 300, Delta = 0
,E/SMD     (  238): DCD ON
,E/SMD     (  238): DCD ON
,E/SMD     (  238): DCD ON
,D/AmoledAdjustTimer(  745): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,D/BatteryService(  745): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:3, charge type:1, power sharing:false
,D/BatteryService(  745): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  745): mCoverManager.getCoverState() : true
,D/BatteryService(  745): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1063): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1063): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1063):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1063): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3154): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3154): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1063): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  238): DCD ON
,D/SSRMv2:SIOP(  745): SIOP:: AP = 300, Delta = 0
,E/SMD     (  238): DCD ON
,E/Watchdog(  745): !@Sync 22
,E/SMD     (  238): DCD ON
,D/AmoledAdjustTimer(  745): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,E/SMD     (  238): DCD ON
,D/BatteryService(  745): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:5, charge type:1, power sharing:false
,D/BatteryService(  745): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  745): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1063): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1063): handleBatteryUpdate
D/BatteryService(  745): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1063):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1063): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3154): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3154): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1063): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  745): SIOP:: AP = 300, Delta = 0
,E/SMD     (  238): DCD ON
,E/SMD     (  238): DCD ON
,D/AmoledAdjustTimer(  745): prevTemp = 272, currTemp = 271, prevStep = 4, currStep = 4
,E/SMD     (  238): DCD ON
,D/BatteryService(  745): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService(  745): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  745): mCoverManager.getCoverState() : true
,D/BatteryService(  745): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1063): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1063): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1063):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3154): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3154): Disconnected process message: 10
D/BatteryMeterView( 1063): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1063): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  745): SIOP:: AP = 300, Delta = 0
,E/SMD     (  238): DCD ON
,E/SMD     (  238): DCD ON
,E/SMD     (  238): DCD ON
,D/AmoledAdjustTimer(  745): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,D/BatteryService(  745): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-1, charge type:1, power sharing:false
,D/BatteryService(  745): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  745): mCoverManager.getCoverState() : true
,D/BatteryService(  745): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1063): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1063): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1063):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3154): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3154): Disconnected process message: 10
D/BatteryMeterView( 1063): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1063): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  238): DCD ON
,D/SSRMv2:SIOP(  745): SIOP:: AP = 300, Delta = 0
,V/AlarmManager(  745): waitForAlarm result :8
,V/AlarmManager(  745): ClockReceiver onReceive() ACTION_TIME_TICK
,V/AlarmManager(  745): ___SyncScheduler (v3) ACTIVATED___
,V/AlarmManager(  745): <AppSync3 Whitelist>
,D/KeyguardUpdateMonitor( 1063): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1063): handleTimeUpdate
V/AlarmManager(  745): (AppSync) ### 0 added ###
,D/STATUSBAR-IconMerger( 1063): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  238): DCD ON
,E/Watchdog(  745): !@Sync 23
,E/SMD     (  238): DCD ON
,D/AmoledAdjustTimer(  745): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,E/SMD     (  238): DCD ON
,D/BatteryService(  745): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  745): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  745): mCoverManager.getCoverState() : true
,D/BatteryService(  745): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1063): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1063): handleBatteryUpdate
,V/HeadsetService( 3154): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3154): Disconnected process message: 10
,D/STATUSBAR-PhoneStatusBar( 1063):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1063): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1063): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  745): SIOP:: AP = 300, Delta = 0
,E/SMD     (  238): DCD ON
,E/SMD     (  238): DCD ON
,D/AmoledAdjustTimer(  745): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,E/SMD     (  238): DCD ON
,D/BatteryService(  745): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:9, charge type:1, power sharing:false
,D/BatteryService(  745): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  745): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1063): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1063): handleBatteryUpdate
D/BatteryService(  745): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1063):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1063): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3154): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3154): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1063): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  745): SIOP:: AP = 300, Delta = 0
,E/SMD     (  238): DCD ON
,E/SMD     (  238): DCD ON
,E/SMD     (  238): DCD ON
,D/AmoledAdjustTimer(  745): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,D/BatteryService(  745): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:7, charge type:1, power sharing:false
,D/BatteryService(  745): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  745): stay LED for fully charged
,D/UiModeManager(  745): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1063): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1063): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1063):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1063): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 3154): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 3154): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1063): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  238): DCD ON
,D/SSRMv2:SIOP(  745): SIOP:: AP = 300, Delta = 0
,E/SMD     (  238): DCD ON
,E/Watchdog(  745): !@Sync 24
,E/SMD     (  238): DCD ON
,I/PowerManagerService(  745): [PWL] Off : 680s ago
,D/AmoledAdjustTimer(  745): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,E/SMD     (  238): DCD ON
,D/BatteryService(  745): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:11, charge type:1, power sharing:false
,D/BatteryService(  745): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  745): mCoverManager.getCoverState() : true
,D/BatteryService(  745): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1063): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1063): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1063):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1063): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 3154): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 3154): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1063): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  745): SIOP:: AP = 300, Delta = 0
,E/SMD     (  238): DCD ON
,E/SMD     (  238): DCD ON
,D/AmoledAdjustTimer(  745): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,E/SMD     (  238): DCD ON
,D/BatteryService(  745): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-2, charge type:1, power sharing:false
,D/BatteryService(  745): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  745): mCoverManager.getCoverState() : true
,D/BatteryService(  745): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1063): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1063): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1063):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3154): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/BatteryMeterView( 1063): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/HeadsetStateMachine( 3154): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1063): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  745): SIOP:: AP = 300, Delta = 0
,E/SMD     (  238): DCD ON
,E/SMD     (  238): DCD ON
,E/SMD     (  238): DCD ON
,D/AmoledAdjustTimer(  745): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,E/SMD     (  238): DCD ON
,D/BatteryService(  745): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-1, charge type:1, power sharing:false
,D/BatteryService(  745): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  745): stay LED for fully charged
,D/UiModeManager(  745): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1063): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1063): handleBatteryUpdate
,V/HeadsetService( 3154): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1063):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/HeadsetStateMachine( 3154): Disconnected process message: 10
D/BatteryMeterView( 1063): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1063): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  745): SIOP:: AP = 300, Delta = 0
,V/AlarmManager(  745): waitForAlarm result :8
,V/AlarmManager(  745): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1063): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1063): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1063): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  238): DCD ON
,E/Watchdog(  745): !@Sync 25
,E/SMD     (  238): DCD ON
,D/AmoledAdjustTimer(  745): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,E/SMD     (  238): DCD ON
,D/SSRMv2:SIOP(  745): SIOP:: AP = 300, Delta = 0
,E/SMD     (  238): DCD ON
,E/SMD     (  238): DCD ON
,E/SMD     (  238): DCD ON
,D/AmoledAdjustTimer(  745): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,D/BatteryService(  745): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:3, charge type:1, power sharing:false
,D/BatteryService(  745): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  745): mCoverManager.getCoverState() : true
,D/BatteryService(  745): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1063): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1063): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1063):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1063): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3154): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3154): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1063): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  745): SIOP:: AP = 300, Delta = 0
,E/SMD     (  238): DCD ON
,E/SMD     (  238): DCD ON
,E/SMD     (  238): DCD ON
,D/AmoledAdjustTimer(  745): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,E/SMD     (  238): DCD ON
,D/BatteryService(  745): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:8, charge type:1, power sharing:false
,D/BatteryService(  745): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  745): mCoverManager.getCoverState() : true
,D/BatteryService(  745): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1063): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1063): handleBatteryUpdate
,V/HeadsetService( 3154): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1063):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1063): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/HeadsetStateMachine( 3154): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1063): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  745): SIOP:: AP = 300, Delta = 0
,E/SMD     (  238): DCD ON
,E/Watchdog(  745): !@Sync 26
,E/SMD     (  238): DCD ON
,D/AmoledAdjustTimer(  745): prevTemp = 271, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  238): DCD ON
,D/BatteryService(  745): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  745): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  745): mCoverManager.getCoverState() : true
,D/BatteryService(  745): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1063): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1063): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1063):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1063): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 3154): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 3154): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1063): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  745): SIOP:: AP = 300, Delta = 0
,E/SMD     (  238): DCD ON
,E/SMD     (  238): DCD ON
,E/SMD     (  238): DCD ON
,D/AmoledAdjustTimer(  745): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP(  745): SIOP:: AP = 300, Delta = 0
,E/SMD     (  238): DCD ON
,E/SMD     (  238): DCD ON
,E/SMD     (  238): DCD ON
,D/AmoledAdjustTimer(  745): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,D/dalvikvm(  745): GC_CONCURRENT freed 3556K, 57% free 23561K/54428K, paused 21ms+37ms, total 454ms
,E/SMD     (  238): DCD ON
,D/BatteryService(  745): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-1, charge type:1, power sharing:false
,D/BatteryService(  745): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  745): stay LED for fully charged
,D/UiModeManager(  745): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1063): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1063): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1063):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1063): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 3154): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 3154): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1063): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  745): SIOP:: AP = 300, Delta = 0
,V/AlarmManager(  745): waitForAlarm result :8
,V/AlarmManager(  745): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1063): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1063): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1063): checkOverflow(288), More:false, Req:false Child:2
,I/PowerManagerService(  745): [PWL] Off : 765s ago
,E/SMD     (  238): DCD ON
,E/Watchdog(  745): !@Sync 27
,E/SMD     (  238): DCD ON
,D/AmoledAdjustTimer(  745): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  238): DCD ON
,D/BatteryService(  745): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:10, charge type:1, power sharing:false
,D/BatteryService(  745): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  745): mCoverManager.getCoverState() : true
,D/BatteryService(  745): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1063): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1063): handleBatteryUpdate
,V/HeadsetService( 3154): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3154): Disconnected process message: 10
,D/STATUSBAR-PhoneStatusBar( 1063):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1063): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1063): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  745): SIOP:: AP = 300, Delta = 0
,E/SMD     (  238): DCD ON
,E/SMD     (  238): DCD ON
,E/SMD     (  238): DCD ON
,D/AmoledAdjustTimer(  745): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  238): DCD ON
,D/BatteryService(  745): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:8, charge type:1, power sharing:false
,D/BatteryService(  745): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  745): mCoverManager.getCoverState() : true
,D/BatteryService(  745): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1063): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1063): handleBatteryUpdate
,D/SSRMv2:SIOP(  745): SIOP:: AP = 300, Delta = 0
,D/STATUSBAR-PhoneStatusBar( 1063):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1063): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3154): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3154): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1063): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  238): DCD ON
,E/SMD     (  238): DCD ON
,D/AmoledAdjustTimer(  745): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  238): DCD ON
,D/BatteryService(  745): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:10, charge type:1, power sharing:false
,D/BatteryService(  745): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  745): stay LED for fully charged
,D/UiModeManager(  745): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1063): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1063): handleBatteryUpdate
,D/SSRMv2:SIOP(  745): SIOP:: AP = 300, Delta = 0
,D/STATUSBAR-PhoneStatusBar( 1063):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3154): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3154): Disconnected process message: 10
D/BatteryMeterView( 1063): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1063): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  238): DCD ON
,E/Watchdog(  745): !@Sync 28
,E/SMD     (  238): DCD ON
,D/AmoledAdjustTimer(  745): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  238): DCD ON
,D/BatteryService(  745): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:2, charge type:1, power sharing:false
,D/BatteryService(  745): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  745): mCoverManager.getCoverState() : true
,D/BatteryService(  745): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1063): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1063): handleBatteryUpdate
,D/SSRMv2:SIOP(  745): SIOP:: AP = 300, Delta = 0
,D/STATUSBAR-PhoneStatusBar( 1063):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1063): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3154): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3154): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1063): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  238): DCD ON
,E/SMD     (  238): DCD ON
,E/SMD     (  238): DCD ON
,D/AmoledAdjustTimer(  745): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  238): DCD ON
,D/BatteryService(  745): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:2, charge type:1, power sharing:false
,D/BatteryService(  745): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  745): mCoverManager.getCoverState() : true
,D/BatteryService(  745): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1063): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1063): handleBatteryUpdate
,D/SSRMv2:SIOP(  745): SIOP:: AP = 300, Delta = 0
,D/STATUSBAR-PhoneStatusBar( 1063):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1063): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3154): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3154): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1063): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  238): DCD ON
,E/SMD     (  238): DCD ON
,D/AmoledAdjustTimer(  745): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  238): DCD ON
,D/SSRMv2:SIOP(  745): SIOP:: AP = 300, Delta = 0
,V/AlarmManager(  745): waitForAlarm result :8
,V/AlarmManager(  745): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1063): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1063): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1063): checkOverflow(288), More:false, Req:false Child:2
,D/BatteryService(  745): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:3, charge type:1, power sharing:false
,D/BatteryService(  745): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  745): stay LED for fully charged
,D/UiModeManager(  745): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 1063): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1063): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1063):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3154): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3154): Disconnected process message: 10
D/BatteryMeterView( 1063): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1063): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  238): DCD ON
,E/Watchdog(  745): !@Sync 29
,E/SMD     (  238): DCD ON
,D/AmoledAdjustTimer(  745): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  238): DCD ON
,D/SSRMv2:SIOP(  745): SIOP:: AP = 300, Delta = 0
,E/SMD     (  238): DCD ON
,D/BatteryService(  745): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  745): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  745): mCoverManager.getCoverState() : true
,D/BatteryService(  745): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1063): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1063): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1063):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3154): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3154): Disconnected process message: 10
D/BatteryMeterView( 1063): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1063): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  238): DCD ON
,E/SMD     (  238): DCD ON
,D/AmoledAdjustTimer(  745): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  238): DCD ON
,D/SSRMv2:SIOP(  745): SIOP:: AP = 300, Delta = 0
,D/BatteryService(  745): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-2, charge type:1, power sharing:false
,D/BatteryService(  745): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  745): mCoverManager.getCoverState() : true
,D/BatteryService(  745): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1063): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1063): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1063):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3154): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3154): Disconnected process message: 10
D/BatteryMeterView( 1063): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1063): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  238): DCD ON
,E/SMD     (  238): DCD ON
,D/AmoledAdjustTimer(  745): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,D/TimaService(  745): TIMA: TimaService scheduler is intialized. 
,D/TimaService(  745): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService(  745): TimaServiceHandler.handleMessage what =1
,E/SMD     (  238): DCD ON
,D/SSRMv2:SIOP(  745): SIOP:: AP = 300, Delta = 0
,I/TLC_TIMA_PKM_measure_kernel(  745): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel(  745): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService(  745): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService(  745): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,I/PowerManagerService(  745): [PWL] Off : 855s ago
,D/BatteryService(  745): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  745): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  745): stay LED for fully charged
,D/UiModeManager(  745): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1063): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1063): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1063):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1063): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3154): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/STATUSBAR-IconMerger( 1063): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  238): DCD ON
,D/HeadsetStateMachine( 3154): Disconnected process message: 10
,E/Watchdog(  745): !@Sync 30
,E/SMD     (  238): DCD ON
,D/AmoledAdjustTimer(  745): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  238): DCD ON
,D/SSRMv2:SIOP(  745): SIOP:: AP = 300, Delta = 0
,E/SMD     (  238): DCD ON
,D/BatteryService(  745): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService(  745): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  745): mCoverManager.getCoverState() : true
,D/BatteryService(  745): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1063): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1063): handleBatteryUpdate
,V/HeadsetService( 3154): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1063):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/HeadsetStateMachine( 3154): Disconnected process message: 10
D/BatteryMeterView( 1063): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1063): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  238): DCD ON
,E/SMD     (  238): DCD ON
,D/AmoledAdjustTimer(  745): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  238): DCD ON
,D/SSRMv2:SIOP(  745): SIOP:: AP = 300, Delta = 0
,D/BatteryService(  745): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  745): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  745): mCoverManager.getCoverState() : true
,D/BatteryService(  745): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1063): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1063): handleBatteryUpdate
,V/HeadsetService( 3154): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1063):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/HeadsetStateMachine( 3154): Disconnected process message: 10
D/BatteryMeterView( 1063): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1063): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  238): DCD ON
,E/SMD     (  238): DCD ON
,D/AmoledAdjustTimer(  745): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  238): DCD ON
,D/SSRMv2:SIOP(  745): SIOP:: AP = 300, Delta = 0
,V/AlarmManager(  745): waitForAlarm result :8
,V/AlarmManager(  745): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1063): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1063): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1063): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  238): DCD ON
,E/Watchdog(  745): !@Sync 31
,E/SMD     (  238): DCD ON
,D/AmoledAdjustTimer(  745): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  238): DCD ON
,D/SSRMv2:SIOP(  745): SIOP:: AP = 300, Delta = 0
,E/SMD     (  238): DCD ON
,E/SMD     (  238): DCD ON
,E/SMD     (  238): DCD ON
,D/AmoledAdjustTimer(  745): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  238): DCD ON
,D/SSRMv2:SIOP(  745): SIOP:: AP = 300, Delta = 0
,D/BatteryService(  745): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  745): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  745): stay LED for fully charged
,D/UiModeManager(  745): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1063): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1063): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1063):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1063): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3154): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3154): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1063): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  238): DCD ON
,E/SMD     (  238): DCD ON
,D/AmoledAdjustTimer(  745): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  238): DCD ON
,D/SSRMv2:SIOP(  745): SIOP:: AP = 300, Delta = 0
,E/SMD     (  238): DCD ON
,D/BatteryService(  745): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  745): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  745): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1063): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1063): handleBatteryUpdate
D/BatteryService(  745): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1063):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1063): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3154): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3154): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1063): checkOverflow(288), More:false, Req:false Child:2
,E/Watchdog(  745): !@Sync 32
,E/SMD     (  238): DCD ON
,D/AmoledAdjustTimer(  745): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  238): DCD ON
,D/SSRMv2:SIOP(  745): SIOP:: AP = 300, Delta = 0
,E/SMD     (  238): DCD ON
,D/BatteryService(  745): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:3, charge type:1, power sharing:false
,D/BatteryService(  745): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  745): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1063): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1063): handleBatteryUpdate
D/BatteryService(  745): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1063):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1063): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 3154): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 3154): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1063): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  238): DCD ON
,E/SMD     (  238): DCD ON
,D/AmoledAdjustTimer(  745): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  238): DCD ON
,D/SSRMv2:SIOP(  745): SIOP:: AP = 300, Delta = 0
,E/SMD     (  238): DCD ON
,E/SMD     (  238): DCD ON
,D/AmoledAdjustTimer(  745): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  238): DCD ON
,D/SSRMv2:SIOP(  745): SIOP:: AP = 300, Delta = 0
,V/AlarmManager(  745): waitForAlarm result :8
,V/AlarmManager(  745): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1063): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1063): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1063): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  238): DCD ON
,D/BatteryService(  745): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:5, charge type:1, power sharing:false
,D/BatteryService(  745): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  745): stay LED for fully charged
,D/UiModeManager(  745): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1063): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1063): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1063):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1063): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3154): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3154): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1063): checkOverflow(288), More:false, Req:false Child:2
,E/Watchdog(  745): !@Sync 33
,E/SMD     (  238): DCD ON
,I/PowerManagerService(  745): [PWL] Off : 950s ago
,D/AmoledAdjustTimer(  745): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  238): DCD ON
,E/SMD     (  238): DCD ON
,D/SSRMv2:SIOP(  745): SIOP:: AP = 300, Delta = 0
,D/BatteryService(  745): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:8, charge type:1, power sharing:false
,D/BatteryService(  745): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  745): mCoverManager.getCoverState() : true
,D/BatteryService(  745): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1063): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1063): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1063):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3154): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3154): Disconnected process message: 10
D/BatteryMeterView( 1063): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1063): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  238): DCD ON
,E/SMD     (  238): DCD ON
,D/AmoledAdjustTimer(  745): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  238): DCD ON
,D/SSRMv2:SIOP(  745): SIOP:: AP = 300, Delta = 0
,E/SMD     (  238): DCD ON
,E/SMD     (  238): DCD ON
,D/AmoledAdjustTimer(  745): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  238): DCD ON
,V/AlarmManager(  745): waitForAlarm result :4
,D/LightsService(  745): [api] onReceive : SvcLEDReceiver re-enables LightSenor and sends MSG_FORCEDSVCLEDTASK
I/SensorManagerA(  745): getReportingMode :: sensor.mType = 5
D/Sensors (  745): LightSensor setDelay = 200000000
D/Sensors (  745): LightSensor setSensorDelay = 200000000
D/Sensors (  745): Light sensor flush: not enabled 0
D/Sensors (  745): LightSensor enable = 1
D/Sensors (  745): LightSensor enableSensor = 1
,D/SensorManager(  745): registerListener :: 16, CM36686 Light Sensor, 200000, 0,  
,V/AlarmManager(  745): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,V/AlarmManager(  745): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,D/Sensors (  745): LightSensor enable = 0
,D/Sensors (  745): LightSensor enableSensor = 0
,D/LightsService(  745): [SvcLED]  onSensorChanged::light value = 0
,D/SensorManager(  745): unregisterListener ::   
D/LightsService(  745): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,I/EventLogService( 1780): Aggregate from 1450225269374 (log), 1450225269374 (data)
,D/ConnectivityService(  745): handleInetConditionHoldEnd: net=1, condition=100, published condition=100
,D/STATUSBAR-NetworkController_dual( 1063): onReceive() - CONNECTIVITY_ACTION, INET_CONDITION_ACTION
,D/StatusBar.NetworkController_dual( 1063): mMobileLabelViews start
,D/StatusBar.NetworkController_dual( 1063): mMobileLabelViews set mobileLabel[SIM_0] =
,D/StatusBar.NetworkController_dual( 1063): mMobileLabelViews GONE
D/StatusBar.NetworkController_dual( 1063): mMobileLabelViews2 set mobileLabel[SIM_1] =
,D/StatusBar.NetworkController_dual( 1063): mMobileLabelViews2 GONE
,D/StatusBar.NetworkController_dual( 1063): mSingleMobileLabelViews set : simMode = 0
,D/StatusBar.NetworkController_dual( 1063): mSingleMobileLabelViews set as slot1`s
,I/PhenotypeConfigurator( 1215): Scheduling Phenotype for one-off execution 9095 seconds from now (1450227328962)
,D/GetConfigurationSnapshotOperation( 1215): no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,I/PhenotypeFlagCommitter( 1215): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,I/GoogleURLConnFactory( 1215): Using platform SSLCertificateSocketFactory
,D/LocationManagerService(  745): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/LocationManagerService(  745): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/SSRMv2:SIOP(  745): SIOP:: AP = 300, Delta = 0
,D/LocationManagerService(  745): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/LocationManagerService(  745): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/LocationManagerService(  745): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/dalvikvm( 1215): GC_CONCURRENT freed 1817K, 37% free 11921K/18912K, paused 49ms+9ms, total 139ms
,E/SMD     (  238): DCD ON
,E/Watchdog(  745): !@Sync 34
,E/SMD     (  238): DCD ON
,D/AmoledAdjustTimer(  745): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  238): DCD ON
,D/BatteryService(  745): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-2, charge type:1, power sharing:false
,D/BatteryService(  745): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  745): stay LED for fully charged
,D/UiModeManager(  745): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1063): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1063): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1063):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1063): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3154): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3154): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1063): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  238): DCD ON
,D/SSRMv2:SIOP(  745): SIOP:: AP = 300, Delta = 0
,E/SMD     (  238): DCD ON
,E/SMD     (  238): DCD ON
,D/AmoledAdjustTimer(  745): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,D/BatteryService(  745): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-2, charge type:1, power sharing:false
,D/BatteryService(  745): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  745): stay LED for fully charged
,D/UiModeManager(  745): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1063): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1063): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1063):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1063): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 3154): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 3154): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1063): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  238): DCD ON
,D/SSRMv2:SIOP(  745): SIOP:: AP = 300, Delta = 0
,E/SMD     (  238): DCD ON
,E/SMD     (  238): DCD ON
,D/AmoledAdjustTimer(  745): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  238): DCD ON
,D/BatteryService(  745): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-2, charge type:1, power sharing:false
,D/BatteryService(  745): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  745): stay LED for fully charged
,D/UiModeManager(  745): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1063): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1063): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1063):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1063): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 3154): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 3154): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1063): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  745): SIOP:: AP = 300, Delta = 0
,V/AlarmManager(  745): waitForAlarm result :8
,V/AlarmManager(  745): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1063): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1063): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1063): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  238): DCD ON
,E/Watchdog(  745): !@Sync 35
,E/SMD     (  238): DCD ON
,D/AmoledAdjustTimer(  745): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  238): DCD ON
,D/BatteryService(  745): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:9, charge type:1, power sharing:false
,D/BatteryService(  745): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  745): mCoverManager.getCoverState() : true
,D/BatteryService(  745): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1063): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1063): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1063):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3154): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3154): Disconnected process message: 10
D/BatteryMeterView( 1063): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1063): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  238): DCD ON
,D/SSRMv2:SIOP(  745): SIOP:: AP = 300, Delta = 0
,E/SMD     (  238): DCD ON
,E/SMD     (  238): DCD ON
,D/AmoledAdjustTimer(  745): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  238): DCD ON
,D/SSRMv2:SIOP(  745): SIOP:: AP = 300, Delta = 0
,E/SMD     (  238): DCD ON
,E/SMD     (  238): DCD ON
,D/AmoledAdjustTimer(  745): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  238): DCD ON
,D/BatteryService(  745): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService(  745): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  745): mCoverManager.getCoverState() : true
,D/BatteryService(  745): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1063): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1063): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1063):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1063): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 3154): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 3154): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1063): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  745): SIOP:: AP = 300, Delta = 0
,E/SMD     (  238): DCD ON
,E/Watchdog(  745): !@Sync 36
,E/SMD     (  238): DCD ON
,D/AmoledAdjustTimer(  745): prevTemp = 270, currTemp = 269, prevStep = 4, currStep = 4
,E/SMD     (  238): DCD ON
,D/BatteryService(  745): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:11, charge type:1, power sharing:false
,D/BatteryService(  745): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  745): stay LED for fully charged
,D/UiModeManager(  745): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1063): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1063): handleBatteryUpdate
,V/HeadsetService( 3154): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3154): Disconnected process message: 10
,D/STATUSBAR-PhoneStatusBar( 1063):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1063): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1063): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  238): DCD ON
,D/SSRMv2:SIOP(  745): SIOP:: AP = 300, Delta = 0
,E/SMD     (  238): DCD ON
,I/PowerManagerService(  745): [PWL] Off : 1050s ago
,E/SMD     (  238): DCD ON
,D/AmoledAdjustTimer(  745): prevTemp = 269, currTemp = 269, prevStep = 4, currStep = 4
,E/SMD     (  238): DCD ON
,D/BatteryService(  745): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:9, charge type:1, power sharing:false
,D/BatteryService(  745): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  745): stay LED for fully charged
,D/UiModeManager(  745): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1063): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1063): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1063):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1063): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3154): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3154): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1063): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  745): SIOP:: AP = 300, Delta = 0
,E/SMD     (  238): DCD ON
,E/SMD     (  238): DCD ON
,D/AmoledAdjustTimer(  745): prevTemp = 269, currTemp = 269, prevStep = 4, currStep = 4
,E/SMD     (  238): DCD ON
,V/AlarmManager(  745): waitForAlarm result :8
,V/AlarmManager(  745): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1063): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1063): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1063): checkOverflow(288), More:false, Req:false Child:2
,D/BatteryService(  745): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:10, charge type:1, power sharing:false
,D/BatteryService(  745): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  745): mCoverManager.getCoverState() : true
,D/SSRMv2:SIOP(  745): SIOP:: AP = 300, Delta = 0
D/KeyguardUpdateMonitor( 1063): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1063): handleBatteryUpdate
D/BatteryService(  745): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1063):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1063): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3154): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3154): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1063): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  238): DCD ON
,E/Watchdog(  745): !@Sync 37
,E/SMD     (  238): DCD ON
,D/AmoledAdjustTimer(  745): prevTemp = 269, currTemp = 269, prevStep = 4, currStep = 4
,E/SMD     (  238): DCD ON
,E/SMD     (  238): DCD ON
,D/BatteryService(  745): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:12, charge type:1, power sharing:false
,D/BatteryService(  745): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  745): stay LED for fully charged
,D/UiModeManager(  745): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1063): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1063): handleBatteryUpdate
,D/SSRMv2:SIOP(  745): SIOP:: AP = 300, Delta = 0
,D/STATUSBAR-PhoneStatusBar( 1063):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1063): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 3154): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 3154): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1063): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  238): DCD ON
,E/SMD     (  238): DCD ON
,D/AmoledAdjustTimer(  745): prevTemp = 269, currTemp = 269, prevStep = 4, currStep = 4
,E/SMD     (  238): DCD ON
,D/BatteryService(  745): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:9, charge type:1, power sharing:false
,D/BatteryService(  745): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  745): stay LED for fully charged
,D/UiModeManager(  745): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1063): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1063): handleBatteryUpdate
,V/HeadsetService( 3154): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1063):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/HeadsetStateMachine( 3154): Disconnected process message: 10
D/BatteryMeterView( 1063): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SSRMv2:SIOP(  745): SIOP:: AP = 300, Delta = 0
,D/STATUSBAR-IconMerger( 1063): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  238): DCD ON
,E/SMD     (  238): DCD ON
,D/AmoledAdjustTimer(  745): prevTemp = 269, currTemp = 269, prevStep = 4, currStep = 4
,E/SMD     (  238): DCD ON
,D/BatteryService(  745): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:13, charge type:1, power sharing:false
,D/BatteryService(  745): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  745): stay LED for fully charged
,D/UiModeManager(  745): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1063): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1063): handleBatteryUpdate
,D/SSRMv2:SIOP(  745): SIOP:: AP = 300, Delta = 0
,D/STATUSBAR-PhoneStatusBar( 1063):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 1063): checkOverflow(288), More:false, Req:false Child:2
,D/BatteryMeterView( 1063): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3154): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3154): Disconnected process message: 10
,E/SMD     (  238): DCD ON
,E/Watchdog(  745): !@Sync 38
,E/SMD     (  238): DCD ON
,D/AmoledAdjustTimer(  745): prevTemp = 269, currTemp = 269, prevStep = 4, currStep = 4
,E/SMD     (  238): DCD ON
,E/SMD     (  238): DCD ON
,D/BatteryService(  745): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  745): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  745): stay LED for fully charged
,D/UiModeManager(  745): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1063): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1063): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1063):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1063): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3154): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3154): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1063): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  745): SIOP:: AP = 300, Delta = 0
,E/SMD     (  238): DCD ON
,E/SMD     (  238): DCD ON
,D/AmoledAdjustTimer(  745): prevTemp = 269, currTemp = 269, prevStep = 4, currStep = 4
,E/SMD     (  238): DCD ON
,D/BatteryService(  745): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  745): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  745): stay LED for fully charged
,D/UiModeManager(  745): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1063): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1063): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1063):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1063): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3154): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3154): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1063): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  745): SIOP:: AP = 300, Delta = 0
,D/dalvikvm(  745): GC_CONCURRENT freed 3355K, 57% free 23625K/54428K, paused 60ms+36ms, total 479ms
,E/SMD     (  238): DCD ON
,E/SMD     (  238): DCD ON
,D/AmoledAdjustTimer(  745): prevTemp = 269, currTemp = 269, prevStep = 4, currStep = 4
,E/SMD     (  238): DCD ON
,V/AlarmManager(  745): waitForAlarm result :8
,V/AlarmManager(  745): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1063): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1063): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1063): checkOverflow(288), More:false, Req:false Child:2
,D/BatteryService(  745): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  745): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  745): mCoverManager.getCoverState() : true
,D/BatteryService(  745): stay LED for fully charged
D/KeyguardUpdateMonitor( 1063): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1063): handleBatteryUpdate
,V/HeadsetService( 3154): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3154): Disconnected process message: 10
,D/STATUSBAR-PhoneStatusBar( 1063):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1063): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1063): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  238): DCD ON
D/SSRMv2:SIOP(  745): SIOP:: AP = 300, Delta = 0
,E/Watchdog(  745): !@Sync 39
,E/SMD     (  238): DCD ON
,D/AmoledAdjustTimer(  745): prevTemp = 269, currTemp = 269, prevStep = 4, currStep = 4
,E/SMD     (  238): DCD ON
,E/SMD     (  238): DCD ON
,D/BatteryService(  745): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  745): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  745): stay LED for fully charged
,D/UiModeManager(  745): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1063): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1063): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1063):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3154): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3154): Disconnected process message: 10
D/BatteryMeterView( 1063): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SSRMv2:SIOP(  745): SIOP:: AP = 300, Delta = 0
,D/STATUSBAR-IconMerger( 1063): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  238): DCD ON
,E/SMD     (  238): DCD ON
,D/AmoledAdjustTimer(  745): prevTemp = 269, currTemp = 269, prevStep = 4, currStep = 4
,E/SMD     (  238): DCD ON
,D/BatteryService(  745): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  745): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  745): stay LED for fully charged
,D/UiModeManager(  745): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1063): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1063): handleBatteryUpdate
,D/SSRMv2:SIOP(  745): SIOP:: AP = 300, Delta = 0
,D/STATUSBAR-PhoneStatusBar( 1063):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1063): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3154): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/STATUSBAR-IconMerger( 1063): checkOverflow(288), More:false, Req:false Child:2
,D/HeadsetStateMachine( 3154): Disconnected process message: 10
,E/SMD     (  238): DCD ON
,E/SMD     (  238): DCD ON
,D/TimaService(  745): TIMA: TimaService scheduler is intialized. 
,D/TimaService(  745): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService(  745): TimaServiceHandler.handleMessage what =1
,D/AmoledAdjustTimer(  745): prevTemp = 269, currTemp = 269, prevStep = 4, currStep = 4
,E/SMD     (  238): DCD ON
,I/TLC_TIMA_PKM_measure_kernel(  745): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel(  745): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService(  745): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService(  745): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,I/PowerManagerService(  745): [PWL] Off : 1155s ago
,E/SMD     (  238): DCD ON
,D/SSRMv2:SIOP(  745): SIOP:: AP = 300, Delta = 0
,E/Watchdog(  745): !@Sync 40
,E/SMD     (  238): DCD ON
,D/AmoledAdjustTimer(  745): prevTemp = 269, currTemp = 269, prevStep = 4, currStep = 4
,E/SMD     (  238): DCD ON
,E/SMD     (  238): DCD ON
,D/BatteryService(  745): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:6, charge type:1, power sharing:false
,D/BatteryService(  745): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  745): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1063): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1063): handleBatteryUpdate
D/UiModeManager(  745): mCoverManager.getCoverState() : true
,D/SSRMv2:SIOP(  745): SIOP:: AP = 300, Delta = 0
,D/STATUSBAR-PhoneStatusBar( 1063):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1063): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3154): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3154): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1063): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  238): DCD ON
,E/SMD     (  238): DCD ON
,D/AmoledAdjustTimer(  745): prevTemp = 269, currTemp = 269, prevStep = 4, currStep = 4
,E/SMD     (  238): DCD ON
,D/BatteryService(  745): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:7, charge type:1, power sharing:false
,D/BatteryService(  745): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  745): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1063): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1063): handleBatteryUpdate
D/BatteryService(  745): stay LED for fully charged
,D/SSRMv2:SIOP(  745): SIOP:: AP = 300, Delta = 0
,D/STATUSBAR-PhoneStatusBar( 1063):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3154): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3154): Disconnected process message: 10
D/BatteryMeterView( 1063): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1063): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  238): DCD ON
,E/SMD     (  238): DCD ON
,D/AmoledAdjustTimer(  745): prevTemp = 269, currTemp = 269, prevStep = 4, currStep = 4
,E/SMD     (  238): DCD ON
,V/AlarmManager(  745): waitForAlarm result :8
,V/AlarmManager(  745): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1063): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1063): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1063): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  238): DCD ON
,D/BatteryService(  745): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:3, charge type:1, power sharing:false
,D/BatteryService(  745): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  745): mCoverManager.getCoverState() : true
,D/BatteryService(  745): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1063): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1063): handleBatteryUpdate
,D/SSRMv2:SIOP(  745): SIOP:: AP = 300, Delta = 0
,D/STATUSBAR-PhoneStatusBar( 1063):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1063): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3154): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3154): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1063): checkOverflow(288), More:false, Req:false Child:2
,E/Watchdog(  745): !@Sync 41
,E/SMD     (  238): DCD ON
,D/AmoledAdjustTimer(  745): prevTemp = 269, currTemp = 269, prevStep = 4, currStep = 4
,E/SMD     (  238): DCD ON
,E/SMD     (  238): DCD ON
,D/BatteryService(  745): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  745): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  745): stay LED for fully charged
,D/UiModeManager(  745): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1063): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1063): handleBatteryUpdate
,D/SSRMv2:SIOP(  745): SIOP:: AP = 300, Delta = 0
,D/STATUSBAR-PhoneStatusBar( 1063):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1063): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3154): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3154): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1063): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  238): DCD ON
,E/SMD     (  238): DCD ON
,D/AmoledAdjustTimer(  745): prevTemp = 269, currTemp = 269, prevStep = 4, currStep = 4
,E/SMD     (  238): DCD ON
,D/SSRMv2:SIOP(  745): SIOP:: AP = 300, Delta = 0
,E/SMD     (  238): DCD ON
,E/SMD     (  238): DCD ON
,D/AmoledAdjustTimer(  745): prevTemp = 269, currTemp = 269, prevStep = 4, currStep = 4
,E/SMD     (  238): DCD ON
,E/SMD     (  238): DCD ON
,D/SSRMv2:SIOP(  745): SIOP:: AP = 300, Delta = 0
,E/Watchdog(  745): !@Sync 42
,E/SMD     (  238): DCD ON
,D/AmoledAdjustTimer(  745): prevTemp = 269, currTemp = 269, prevStep = 4, currStep = 4
,E/SMD     (  238): DCD ON
,E/SMD     (  238): DCD ON
,D/BatteryService(  745): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:10, charge type:1, power sharing:false
,D/BatteryService(  745): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  745): stay LED for fully charged
,D/UiModeManager(  745): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1063): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1063): handleBatteryUpdate
,D/SSRMv2:SIOP(  745): SIOP:: AP = 300, Delta = 0
,D/STATUSBAR-PhoneStatusBar( 1063):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1063): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3154): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3154): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1063): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  238): DCD ON
,E/SMD     (  238): DCD ON
,D/AmoledAdjustTimer(  745): prevTemp = 269, currTemp = 269, prevStep = 4, currStep = 4
,E/SMD     (  238): DCD ON
,E/SMD     (  238): DCD ON
,D/BatteryService(  745): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:12, charge type:1, power sharing:false
,D/BatteryService(  745): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  745): mCoverManager.getCoverState() : true
,D/BatteryService(  745): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1063): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1063): handleBatteryUpdate
,D/SSRMv2:SIOP(  745): SIOP:: AP = 300, Delta = 0
,D/STATUSBAR-PhoneStatusBar( 1063):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3154): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/BatteryMeterView( 1063): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/HeadsetStateMachine( 3154): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1063): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  238): DCD ON
,D/AmoledAdjustTimer(  745): prevTemp = 269, currTemp = 269, prevStep = 4, currStep = 4
,E/SMD     (  238): DCD ON
,V/AlarmManager(  745): waitForAlarm result :8
,V/AlarmManager(  745): ClockReceiver onReceive() ACTION_TIME_TICK
,V/AlarmManager(  745): ___SyncScheduler (v3) ACTIVATED___
,V/AlarmManager(  745): <AppSync3 Whitelist>
,D/KeyguardUpdateMonitor( 1063): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1063): handleTimeUpdate
V/AlarmManager(  745): (AppSync) ### 0 added ###
,D/STATUSBAR-IconMerger( 1063): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  238): DCD ON
,D/SSRMv2:SIOP(  745): SIOP:: AP = 300, Delta = 0
,E/Watchdog(  745): !@Sync 43
,E/SMD     (  238): DCD ON
,D/AmoledAdjustTimer(  745): prevTemp = 269, currTemp = 269, prevStep = 4, currStep = 4
,E/SMD     (  238): DCD ON
,E/SMD     (  238): DCD ON
,D/BatteryService(  745): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:6, charge type:1, power sharing:false
,D/BatteryService(  745): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  745): stay LED for fully charged
,D/UiModeManager(  745): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1063): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1063): handleBatteryUpdate
,D/SSRMv2:SIOP(  745): SIOP:: AP = 300, Delta = 0
,D/STATUSBAR-PhoneStatusBar( 1063):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1063): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 3154): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 3154): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1063): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  238): DCD ON
,E/SMD     (  238): DCD ON
,D/AmoledAdjustTimer(  745): prevTemp = 269, currTemp = 269, prevStep = 4, currStep = 4
,E/SMD     (  238): DCD ON
,I/PowerManagerService(  745): [PWL] Off : 1265s ago
,E/SMD     (  238): DCD ON
,D/SSRMv2:SIOP(  745): SIOP:: AP = 300, Delta = 0
,E/SMD     (  238): DCD ON
,D/AmoledAdjustTimer(  745): prevTemp = 269, currTemp = 269, prevStep = 4, currStep = 4
,E/SMD     (  238): DCD ON
,E/SMD     (  238): DCD ON
,D/BatteryService(  745): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:5, charge type:1, power sharing:false
,D/BatteryService(  745): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  745): stay LED for fully charged
,D/UiModeManager(  745): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1063): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1063): handleBatteryUpdate
,D/SSRMv2:SIOP(  745): SIOP:: AP = 300, Delta = 0
,D/STATUSBAR-PhoneStatusBar( 1063):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3154): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3154): Disconnected process message: 10
D/BatteryMeterView( 1063): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1063): checkOverflow(288), More:false, Req:false Child:2
,E/Watchdog(  745): !@Sync 44
,E/SMD     (  238): DCD ON
,D/AmoledAdjustTimer(  745): prevTemp = 269, currTemp = 269, prevStep = 4, currStep = 4
,E/SMD     (  238): DCD ON
,E/SMD     (  238): DCD ON
,D/BatteryService(  745): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:12, charge type:1, power sharing:false
,D/BatteryService(  745): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  745): stay LED for fully charged
,D/UiModeManager(  745): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1063): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1063): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1063):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1063): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3154): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3154): Disconnected process message: 10
D/SSRMv2:SIOP(  745): SIOP:: AP = 300, Delta = 0
,D/STATUSBAR-IconMerger( 1063): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  238): DCD ON
,E/SMD     (  238): DCD ON
,D/AmoledAdjustTimer(  745): prevTemp = 269, currTemp = 269, prevStep = 4, currStep = 4
,E/SMD     (  238): DCD ON
,E/SMD     (  238): DCD ON
,D/SSRMv2:SIOP(  745): SIOP:: AP = 300, Delta = 0
,E/SMD     (  238): DCD ON
,D/AmoledAdjustTimer(  745): prevTemp = 269, currTemp = 269, prevStep = 4, currStep = 4
,E/SMD     (  238): DCD ON
,V/AlarmManager(  745): waitForAlarm result :8
,V/AlarmManager(  745): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1063): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1063): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1063): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  238): DCD ON
,E/Watchdog(  745): !@Sync 45
,D/BatteryService(  745): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:11, charge type:1, power sharing:false
,D/BatteryService(  745): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  745): stay LED for fully charged
,D/UiModeManager(  745): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1063): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1063): handleBatteryUpdate
,D/SSRMv2:SIOP(  745): SIOP:: AP = 300, Delta = 0
,D/STATUSBAR-PhoneStatusBar( 1063):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3154): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3154): Disconnected process message: 10
D/BatteryMeterView( 1063): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1063): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  238): DCD ON
,E/SMD     (  238): DCD ON
,D/AmoledAdjustTimer(  745): prevTemp = 269, currTemp = 269, prevStep = 4, currStep = 4
,E/SMD     (  238): DCD ON
,D/BatteryService(  745): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:2, charge type:1, power sharing:false
,D/BatteryService(  745): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  745): mCoverManager.getCoverState() : true
,D/BatteryService(  745): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1063): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1063): handleBatteryUpdate
,D/SSRMv2:SIOP(  745): SIOP:: AP = 300, Delta = 0
,D/STATUSBAR-PhoneStatusBar( 1063):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3154): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3154): Disconnected process message: 10
D/BatteryMeterView( 1063): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1063): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  238): DCD ON
,E/SMD     (  238): DCD ON
,D/AmoledAdjustTimer(  745): prevTemp = 269, currTemp = 269, prevStep = 4, currStep = 4
,E/SMD     (  238): DCD ON
,E/SMD     (  238): DCD ON
,D/BatteryService(  745): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:3, charge type:1, power sharing:false
,D/BatteryService(  745): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  745): mCoverManager.getCoverState() : true
,D/BatteryService(  745): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1063): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1063): handleBatteryUpdate
,D/SSRMv2:SIOP(  745): SIOP:: AP = 300, Delta = 0
,D/STATUSBAR-PhoneStatusBar( 1063):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1063): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3154): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3154): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1063): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  238): DCD ON
,D/AmoledAdjustTimer(  745): prevTemp = 269, currTemp = 269, prevStep = 4, currStep = 4
,E/SMD     (  238): DCD ON
,E/SMD     (  238): DCD ON
,E/Watchdog(  745): !@Sync 46
,D/SSRMv2:SIOP(  745): SIOP:: AP = 300, Delta = 0
,E/SMD     (  238): DCD ON
,E/SMD     (  238): DCD ON
,D/AmoledAdjustTimer(  745): prevTemp = 269, currTemp = 269, prevStep = 4, currStep = 4
,E/SMD     (  238): DCD ON
,E/SMD     (  238): DCD ON
,D/BatteryService(  745): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-2, charge type:1, power sharing:false
,D/BatteryService(  745): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  745): stay LED for fully charged
,D/UiModeManager(  745): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1063): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1063): handleBatteryUpdate
,D/SSRMv2:SIOP(  745): SIOP:: AP = 300, Delta = 0
,D/STATUSBAR-PhoneStatusBar( 1063):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1063): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3154): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3154): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1063): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  238): DCD ON
,D/AmoledAdjustTimer(  745): prevTemp = 269, currTemp = 269, prevStep = 4, currStep = 4
,E/SMD     (  238): DCD ON
,E/SMD     (  238): DCD ON
,D/SSRMv2:SIOP(  745): SIOP:: AP = 300, Delta = 0
,E/SMD     (  238): DCD ON
,D/AmoledAdjustTimer(  745): prevTemp = 269, currTemp = 269, prevStep = 4, currStep = 4
,E/SMD     (  238): DCD ON
,V/AlarmManager(  745): waitForAlarm result :8
,V/AlarmManager(  745): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1063): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1063): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1063): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  238): DCD ON
,E/Watchdog(  745): !@Sync 47
,D/BatteryService(  745): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  745): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1063): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1063): handleBatteryUpdate
D/BatteryService(  745): stay LED for fully charged
,D/UiModeManager(  745): mCoverManager.getCoverState() : true
,D/SSRMv2:SIOP(  745): SIOP:: AP = 300, Delta = 0
,D/STATUSBAR-PhoneStatusBar( 1063):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1063): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3154): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3154): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1063): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  238): DCD ON
,E/SMD     (  238): DCD ON
,D/AmoledAdjustTimer(  745): prevTemp = 269, currTemp = 269, prevStep = 4, currStep = 4
,E/SMD     (  238): DCD ON
,E/SMD     (  238): DCD ON
,D/BatteryService(  745): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:8, charge type:1, power sharing:false
,D/BatteryService(  745): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  745): stay LED for fully charged
,D/UiModeManager(  745): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1063): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1063): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1063):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1063): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP(  745): SIOP:: AP = 300, Delta = 0
,V/HeadsetService( 3154): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3154): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1063): checkOverflow(288), More:false, Req:false Child:2
,I/PowerManagerService(  745): [PWL] Off : 1380s ago
,E/SMD     (  238): DCD ON
,D/AmoledAdjustTimer(  745): prevTemp = 269, currTemp = 269, prevStep = 4, currStep = 4
,E/SMD     (  238): DCD ON
,E/SMD     (  238): DCD ON
,D/SSRMv2:SIOP(  745): SIOP:: AP = 300, Delta = 0
,E/SMD     (  238): DCD ON
,D/AmoledAdjustTimer(  745): prevTemp = 269, currTemp = 269, prevStep = 4, currStep = 4
,E/SMD     (  238): DCD ON
,E/SMD     (  238): DCD ON
,E/Watchdog(  745): !@Sync 48
,D/SSRMv2:SIOP(  745): SIOP:: AP = 300, Delta = 0
,E/SMD     (  238): DCD ON
,E/SMD     (  238): DCD ON
,D/AmoledAdjustTimer(  745): prevTemp = 269, currTemp = 269, prevStep = 4, currStep = 4
,E/SMD     (  238): DCD ON
,E/SMD     (  238): DCD ON
,D/BatteryService(  745): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:9, charge type:1, power sharing:false
,D/BatteryService(  745): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  745): stay LED for fully charged
,D/UiModeManager(  745): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1063): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1063): handleBatteryUpdate
,D/SSRMv2:SIOP(  745): SIOP:: AP = 300, Delta = 0
,D/STATUSBAR-PhoneStatusBar( 1063):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3154): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3154): Disconnected process message: 10
D/BatteryMeterView( 1063): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1063): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  238): DCD ON
,D/AmoledAdjustTimer(  745): prevTemp = 269, currTemp = 268, prevStep = 4, currStep = 4
,E/SMD     (  238): DCD ON
,E/SMD     (  238): DCD ON
,D/BatteryService(  745): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:8, charge type:1, power sharing:false
,D/BatteryService(  745): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  745): stay LED for fully charged
,D/UiModeManager(  745): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1063): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1063): handleBatteryUpdate
,D/SSRMv2:SIOP(  745): SIOP:: AP = 300, Delta = 0
,D/STATUSBAR-PhoneStatusBar( 1063):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1063): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3154): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3154): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1063): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  238): DCD ON
,D/AmoledAdjustTimer(  745): prevTemp = 268, currTemp = 268, prevStep = 4, currStep = 4
,E/SMD     (  238): DCD ON
,V/AlarmManager(  745): waitForAlarm result :8
,V/AlarmManager(  745): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1063): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1063): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1063): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  238): DCD ON
,E/Watchdog(  745): !@Sync 49
,D/BatteryService(  745): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:9, charge type:1, power sharing:false
,D/BatteryService(  745): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  745): stay LED for fully charged
,D/UiModeManager(  745): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1063): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1063): handleBatteryUpdate
,D/SSRMv2:SIOP(  745): SIOP:: AP = 300, Delta = 0
,D/STATUSBAR-PhoneStatusBar( 1063):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3154): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3154): Disconnected process message: 10
D/BatteryMeterView( 1063): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1063): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  238): DCD ON
,E/SMD     (  238): DCD ON
,D/AmoledAdjustTimer(  745): prevTemp = 268, currTemp = 268, prevStep = 4, currStep = 4
,E/SMD     (  238): DCD ON
,E/SMD     (  238): DCD ON
,D/BatteryService(  745): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:10, charge type:1, power sharing:false
,D/BatteryService(  745): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  745): mCoverManager.getCoverState() : true
,D/BatteryService(  745): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1063): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1063): handleBatteryUpdate
,D/SSRMv2:SIOP(  745): SIOP:: AP = 300, Delta = 0
,D/STATUSBAR-PhoneStatusBar( 1063):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1063): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 3154): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 3154): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1063): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  238): DCD ON
,D/AmoledAdjustTimer(  745): prevTemp = 268, currTemp = 268, prevStep = 4, currStep = 4
,E/SMD     (  238): DCD ON
,E/SMD     (  238): DCD ON
,D/BatteryService(  745): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:3, charge type:1, power sharing:false
,D/BatteryService(  745): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  745): mCoverManager.getCoverState() : true
,D/BatteryService(  745): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1063): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1063): handleBatteryUpdate
,D/SSRMv2:SIOP(  745): SIOP:: AP = 300, Delta = 0
,D/STATUSBAR-PhoneStatusBar( 1063):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1063): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3154): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3154): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1063): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  238): DCD ON
,D/TimaService(  745): TIMA: TimaService scheduler is intialized. 
,D/TimaService(  745): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService(  745): TimaServiceHandler.handleMessage what =1
,D/AmoledAdjustTimer(  745): prevTemp = 268, currTemp = 268, prevStep = 4, currStep = 4
,E/SMD     (  238): DCD ON
,I/TLC_TIMA_PKM_measure_kernel(  745): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel(  745): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService(  745): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService(  745): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/SMD     (  238): DCD ON
,E/Watchdog(  745): !@Sync 50
,E/SMD     (  238): DCD ON
,D/BatteryService(  745): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  745): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  745): stay LED for fully charged
,D/UiModeManager(  745): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1063): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1063): handleBatteryUpdate
,D/SSRMv2:SIOP(  745): SIOP:: AP = 300, Delta = 0
,D/STATUSBAR-PhoneStatusBar( 1063):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1063): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3154): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3154): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1063): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  238): DCD ON
,D/AmoledAdjustTimer(  745): prevTemp = 268, currTemp = 268, prevStep = 4, currStep = 4
,E/SMD     (  238): DCD ON
,E/SMD     (  238): DCD ON
,D/SSRMv2:SIOP(  745): SIOP:: AP = 300, Delta = 0
,E/SMD     (  238): DCD ON
,D/AmoledAdjustTimer(  745): prevTemp = 268, currTemp = 268, prevStep = 4, currStep = 4
,E/SMD     (  238): DCD ON
,E/SMD     (  238): DCD ON
,D/BatteryService(  745): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:6, charge type:1, power sharing:false
,D/BatteryService(  745): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  745): stay LED for fully charged
,D/UiModeManager(  745): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1063): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1063): handleBatteryUpdate
,D/SSRMv2:SIOP(  745): SIOP:: AP = 300, Delta = 0
,D/STATUSBAR-PhoneStatusBar( 1063):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3154): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3154): Disconnected process message: 10
D/BatteryMeterView( 1063): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1063): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  238): DCD ON
,D/AmoledAdjustTimer(  745): prevTemp = 268, currTemp = 268, prevStep = 4, currStep = 4
,E/SMD     (  238): DCD ON
,V/AlarmManager(  745): waitForAlarm result :8
,V/AlarmManager(  745): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1063): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1063): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1063): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  238): DCD ON
,E/Watchdog(  745): !@Sync 51
,E/SMD     (  238): DCD ON
,D/BatteryService(  745): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:7, charge type:1, power sharing:false
,D/BatteryService(  745): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  745): mCoverManager.getCoverState() : true
,D/BatteryService(  745): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1063): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1063): handleBatteryUpdate
,D/SSRMv2:SIOP(  745): SIOP:: AP = 300, Delta = 0
,D/STATUSBAR-PhoneStatusBar( 1063):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1063): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 3154): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 3154): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1063): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  238): DCD ON
,D/AmoledAdjustTimer(  745): prevTemp = 268, currTemp = 268, prevStep = 4, currStep = 4
,E/SMD     (  238): DCD ON
,E/SMD     (  238): DCD ON
,D/BatteryService(  745): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:9, charge type:1, power sharing:false
,D/BatteryService(  745): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  745): stay LED for fully charged
,D/UiModeManager(  745): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1063): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1063): handleBatteryUpdate
,D/SSRMv2:SIOP(  745): SIOP:: AP = 300, Delta = 0
,D/STATUSBAR-PhoneStatusBar( 1063):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1063): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3154): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3154): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1063): checkOverflow(288), More:false, Req:false Child:2
,I/PowerManagerService(  745): [PWL] Off : 1500s ago
,E/SMD     (  238): DCD ON
,D/AmoledAdjustTimer(  745): prevTemp = 268, currTemp = 268, prevStep = 4, currStep = 4
,E/SMD     (  238): DCD ON
,E/SMD     (  238): DCD ON
,D/BatteryService(  745): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:11, charge type:1, power sharing:false
,D/BatteryService(  745): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  745): stay LED for fully charged
,D/UiModeManager(  745): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1063): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1063): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1063):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1063): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3154): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3154): Disconnected process message: 10
D/SSRMv2:SIOP(  745): SIOP:: AP = 300, Delta = 0
,D/STATUSBAR-IconMerger( 1063): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  238): DCD ON
,D/AmoledAdjustTimer(  745): prevTemp = 268, currTemp = 268, prevStep = 4, currStep = 4
,E/SMD     (  238): DCD ON
,E/SMD     (  238): DCD ON
,E/Watchdog(  745): !@Sync 52
,E/SMD     (  238): DCD ON
,D/BatteryService(  745): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:8, charge type:1, power sharing:false
,D/BatteryService(  745): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  745): stay LED for fully charged
,D/UiModeManager(  745): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1063): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1063): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1063):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1063): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3154): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3154): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1063): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  745): SIOP:: AP = 300, Delta = 0
,E/SMD     (  238): DCD ON
,D/AmoledAdjustTimer(  745): prevTemp = 268, currTemp = 268, prevStep = 4, currStep = 4
,E/SMD     (  238): DCD ON
,E/SMD     (  238): DCD ON
,D/BatteryService(  745): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:2, charge type:1, power sharing:false
,D/BatteryService(  745): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  745): stay LED for fully charged
,D/UiModeManager(  745): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1063): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1063): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1063):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1063): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3154): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/SSRMv2:SIOP(  745): SIOP:: AP = 300, Delta = 0
D/HeadsetStateMachine( 3154): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1063): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  238): DCD ON
,D/AmoledAdjustTimer(  745): prevTemp = 268, currTemp = 268, prevStep = 4, currStep = 4
,E/SMD     (  238): DCD ON
,E/SMD     (  238): DCD ON
,D/SSRMv2:SIOP(  745): SIOP:: AP = 300, Delta = 0
,E/SMD     (  238): DCD ON
,D/AmoledAdjustTimer(  745): prevTemp = 268, currTemp = 268, prevStep = 4, currStep = 4
,E/SMD     (  238): DCD ON
,V/AlarmManager(  745): waitForAlarm result :8
,V/AlarmManager(  745): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1063): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1063): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1063): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  238): DCD ON
,E/Watchdog(  745): !@Sync 53
,E/SMD     (  238): DCD ON
,D/BatteryService(  745): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  745): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  745): stay LED for fully charged
,D/UiModeManager(  745): mCoverManager.getCoverState() : true
,D/SSRMv2:SIOP(  745): SIOP:: AP = 300, Delta = 0
D/KeyguardUpdateMonitor( 1063): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1063): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1063):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3154): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3154): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1063): checkOverflow(288), More:false, Req:false Child:2
,D/BatteryMeterView( 1063): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/dalvikvm(  745): GC_CONCURRENT freed 3435K, 57% free 23627K/54428K, paused 40ms+36ms, total 579ms
,E/SMD     (  238): DCD ON
,D/AmoledAdjustTimer(  745): prevTemp = 268, currTemp = 268, prevStep = 4, currStep = 4
,E/SMD     (  238): DCD ON
,E/SMD     (  238): DCD ON
,D/BatteryService(  745): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:15, charge type:1, power sharing:false
,D/BatteryService(  745): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  745): stay LED for fully charged
,D/UiModeManager(  745): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1063): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1063): handleBatteryUpdate
,D/SSRMv2:SIOP(  745): SIOP:: AP = 300, Delta = 0
,D/STATUSBAR-PhoneStatusBar( 1063):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1063): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3154): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3154): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1063): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  238): DCD ON
,D/AmoledAdjustTimer(  745): prevTemp = 268, currTemp = 268, prevStep = 4, currStep = 4
,E/SMD     (  238): DCD ON
,E/SMD     (  238): DCD ON
,E/SMD     (  238): DCD ON
,D/BatteryService(  745): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:13, charge type:1, power sharing:false
,D/BatteryService(  745): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  745): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1063): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1063): handleBatteryUpdate
D/BatteryService(  745): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1063):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1063): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 3154): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 3154): Disconnected process message: 10
,D/SSRMv2:SIOP(  745): SIOP:: AP = 300, Delta = 0
,D/STATUSBAR-IconMerger( 1063): checkOverflow(288), More:false, Req:false Child:2
,D/AmoledAdjustTimer(  745): prevTemp = 268, currTemp = 268, prevStep = 4, currStep = 4
,E/SMD     (  238): DCD ON
,E/SMD     (  238): DCD ON,
,E/Watchdog(  745): !@Sync 54
,E/SMD     (  238): DCD ON
,D/BatteryService(  745): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:14, charge type:1, power sharing:false
,D/BatteryService(  745): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  745): stay LED for fully charged
,D/UiModeManager(  745): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1063): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1063): handleBatteryUpdate
,V/HeadsetService( 3154): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1063):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/HeadsetStateMachine( 3154): Disconnected process message: 10
D/BatteryMeterView( 1063): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1063): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  745): SIOP:: AP = 300, Delta = 0
,E/SMD     (  238): DCD ON
,D/AmoledAdjustTimer(  745): prevTemp = 268, currTemp = 268, prevStep = 4, currStep = 4
,E/SMD     (  238): DCD ON
,E/SMD     (  238): DCD ON
,D/BatteryService(  745): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  745): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  745): mCoverManager.getCoverState() : true
,D/BatteryService(  745): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1063): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1063): handleBatteryUpdate
,D/SSRMv2:SIOP(  745): SIOP:: AP = 300, Delta = 0
,D/STATUSBAR-PhoneStatusBar( 1063):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1063): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3154): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3154): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1063): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  238): DCD ON
,D/AmoledAdjustTimer(  745): prevTemp = 268, currTemp = 268, prevStep = 4, currStep = 4
,E/SMD     (  238): DCD ON
,E/SMD     (  238): DCD ON
,E/SMD     (  238): DCD ON
,D/BatteryService(  745): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  745): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  745): stay LED for fully charged
,D/UiModeManager(  745): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1063): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1063): handleBatteryUpdate
,D/SSRMv2:SIOP(  745): SIOP:: AP = 300, Delta = 0
,D/STATUSBAR-PhoneStatusBar( 1063):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3154): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/BatteryMeterView( 1063): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/HeadsetStateMachine( 3154): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1063): checkOverflow(288), More:false, Req:false Child:2
,D/AmoledAdjustTimer(  745): prevTemp = 268, currTemp = 268, prevStep = 4, currStep = 4
,E/SMD     (  238): DCD ON
,V/AlarmManager(  745): waitForAlarm result :8
,V/AlarmManager(  745): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1063): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1063): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1063): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  238): DCD ON
,E/Watchdog(  745): !@Sync 55
,E/SMD     (  238): DCD ON
,D/BatteryService(  745): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  745): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  745): stay LED for fully charged
,D/UiModeManager(  745): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1063): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1063): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1063):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3154): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3154): Disconnected process message: 10
D/BatteryMeterView( 1063): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1063): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  745): SIOP:: AP = 300, Delta = 0
,E/SMD     (  238): DCD ON
,D/AmoledAdjustTimer(  745): prevTemp = 268, currTemp = 268, prevStep = 4, currStep = 4
,E/SMD     (  238): DCD ON
,E/SMD     (  238): DCD ON
,D/BatteryService(  745): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:2, charge type:1, power sharing:false
,D/BatteryService(  745): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  745): stay LED for fully charged
,D/UiModeManager(  745): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1063): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1063): handleBatteryUpdate
,D/SSRMv2:SIOP(  745): SIOP:: AP = 300, Delta = 0
,D/STATUSBAR-PhoneStatusBar( 1063):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3154): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/BatteryMeterView( 1063): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/HeadsetStateMachine( 3154): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1063): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  238): DCD ON
,D/AmoledAdjustTimer(  745): prevTemp = 268, currTemp = 268, prevStep = 4, currStep = 4
,E/SMD     (  238): DCD ON
,I/PowerManagerService(  745): [PWL] Off : 1625s ago
,E/SMD     (  238): DCD ON
,E/SMD     (  238): DCD ON
,D/BatteryService(  745): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  745): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  745): stay LED for fully charged
,D/UiModeManager(  745): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1063): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1063): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1063):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/SSRMv2:SIOP(  745): SIOP:: AP = 300, Delta = 0
,V/HeadsetService( 3154): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3154): Disconnected process message: 10
D/STATUSBAR-IconMerger( 1063): checkOverflow(288), More:false, Req:false Child:2
D/BatteryMeterView( 1063): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer(  745): prevTemp = 268, currTemp = 268, prevStep = 4, currStep = 4
,E/SMD     (  238): DCD ON
,E/SMD     (  238): DCD ON
,E/Watchdog(  745): !@Sync 56
,E/SMD     (  238): DCD ON
,D/BatteryService(  745): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService(  745): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  745): mCoverManager.getCoverState() : true
,D/BatteryService(  745): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1063): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1063): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1063):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3154): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3154): Disconnected process message: 10
D/BatteryMeterView( 1063): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1063): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  745): SIOP:: AP = 300, Delta = 0
,E/SMD     (  238): DCD ON
,D/AmoledAdjustTimer(  745): prevTemp = 268, currTemp = 268, prevStep = 4, currStep = 4
,E/SMD     (  238): DCD ON
,E/SMD     (  238): DCD ON
,E/SMD     (  238): DCD ON
,D/BatteryService(  745): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  745): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  745): stay LED for fully charged
,D/UiModeManager(  745): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1063): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1063): handleBatteryUpdate
,D/SSRMv2:SIOP(  745): SIOP:: AP = 300, Delta = 0
,D/STATUSBAR-PhoneStatusBar( 1063):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1063): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 3154): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 3154): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1063): checkOverflow(288), More:false, Req:false Child:2
,D/AmoledAdjustTimer(  745): prevTemp = 268, currTemp = 268, prevStep = 4, currStep = 4
,E/SMD     (  238): DCD ON
,E/SMD     (  238): DCD ON
,E/SMD     (  238): DCD ON
,D/SSRMv2:SIOP(  745): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  745): prevTemp = 268, currTemp = 268, prevStep = 4, currStep = 4
,E/SMD     (  238): DCD ON
,V/AlarmManager(  745): waitForAlarm result :8
,V/AlarmManager(  745): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1063): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1063): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1063): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  238): DCD ON
,E/Watchdog(  745): !@Sync 57
,E/SMD     (  238): DCD ON
,D/BatteryService(  745): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:4, charge type:1, power sharing:false
,D/BatteryService(  745): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  745): stay LED for fully charged
,D/UiModeManager(  745): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1063): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1063): handleBatteryUpdate
,D/SSRMv2:SIOP(  745): SIOP:: AP = 300, Delta = 0
,D/STATUSBAR-PhoneStatusBar( 1063):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1063): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3154): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3154): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1063): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  238): DCD ON
,D/AmoledAdjustTimer(  745): prevTemp = 268, currTemp = 268, prevStep = 4, currStep = 4
,E/SMD     (  238): DCD ON
,E/SMD     (  238): DCD ON
,E/SMD     (  238): DCD ON
,D/BatteryService(  745): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService(  745): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  745): stay LED for fully charged
,D/UiModeManager(  745): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1063): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1063): handleBatteryUpdate
,D/SSRMv2:SIOP(  745): SIOP:: AP = 300, Delta = 0
,D/STATUSBAR-PhoneStatusBar( 1063):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1063): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3154): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3154): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1063): checkOverflow(288), More:false, Req:false Child:2
,D/AmoledAdjustTimer(  745): prevTemp = 268, currTemp = 268, prevStep = 4, currStep = 4
,E/SMD     (  238): DCD ON
,E/SMD     (  238): DCD ON
,E/SMD     (  238): DCD ON
,D/BatteryService(  745): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  745): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  745): mCoverManager.getCoverState() : true
,D/BatteryService(  745): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1063): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1063): handleBatteryUpdate
,D/SSRMv2:SIOP(  745): SIOP:: AP = 300, Delta = 0
,D/STATUSBAR-PhoneStatusBar( 1063):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1063): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3154): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3154): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1063): checkOverflow(288), More:false, Req:false Child:2
,D/AmoledAdjustTimer(  745): prevTemp = 268, currTemp = 268, prevStep = 4, currStep = 4
,E/SMD     (  238): DCD ON
,E/SMD     (  238): DCD ON
,E/Watchdog(  745): !@Sync 58
,E/SMD     (  238): DCD ON
,D/SSRMv2:SIOP(  745): SIOP:: AP = 300, Delta = 0
,E/SMD     (  238): DCD ON
,D/AmoledAdjustTimer(  745): prevTemp = 268, currTemp = 268, prevStep = 4, currStep = 4
,E/SMD     (  238): DCD ON
,E/SMD     (  238): DCD ON
,E/SMD     (  238): DCD ON
,D/BatteryService(  745): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-1, charge type:1, power sharing:false
,D/BatteryService(  745): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  745): mCoverManager.getCoverState() : true
,D/BatteryService(  745): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1063): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1063): handleBatteryUpdate
,D/SSRMv2:SIOP(  745): SIOP:: AP = 300, Delta = 0
,D/STATUSBAR-PhoneStatusBar( 1063):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3154): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3154): Disconnected process message: 10
D/BatteryMeterView( 1063): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1063): checkOverflow(288), More:false, Req:false Child:2
,D/AmoledAdjustTimer(  745): prevTemp = 268, currTemp = 268, prevStep = 4, currStep = 4
,E/SMD     (  238): DCD ON
,E/SMD     (  238): DCD ON
,E/SMD     (  238): DCD ON
,D/BatteryService(  745): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-2, charge type:1, power sharing:false
,D/BatteryService(  745): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  745): mCoverManager.getCoverState() : true
,D/BatteryService(  745): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1063): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1063): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1063):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1063): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP(  745): SIOP:: AP = 300, Delta = 0
,V/HeadsetService( 3154): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3154): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1063): checkOverflow(288), More:false, Req:false Child:2
,D/AmoledAdjustTimer(  745): prevTemp = 268, currTemp = 268, prevStep = 4, currStep = 4
,E/SMD     (  238): DCD ON
,V/AlarmManager(  745): waitForAlarm result :8
,V/AlarmManager(  745): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1063): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1063): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1063): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  238): DCD ON
,E/Watchdog(  745): !@Sync 59
,E/SMD     (  238): DCD ON
,D/SSRMv2:SIOP(  745): SIOP:: AP = 300, Delta = 0
,E/SMD     (  238): DCD ON
,D/AmoledAdjustTimer(  745): prevTemp = 268, currTemp = 268, prevStep = 4, currStep = 4
,E/SMD     (  238): DCD ON
,E/SMD     (  238): DCD ON
,E/SMD     (  238): DCD ON
,D/BatteryService(  745): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:3, charge type:1, power sharing:false
,D/BatteryService(  745): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  745): mCoverManager.getCoverState() : true
,D/BatteryService(  745): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1063): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1063): handleBatteryUpdate
,D/SSRMv2:SIOP(  745): SIOP:: AP = 300, Delta = 0
,D/STATUSBAR-PhoneStatusBar( 1063):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1063): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3154): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3154): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1063): checkOverflow(288), More:false, Req:false Child:2
,D/AmoledAdjustTimer(  745): prevTemp = 268, currTemp = 268, prevStep = 4, currStep = 4
,E/SMD     (  238): DCD ON
,E/SMD     (  238): DCD ON
,E/SMD     (  238): DCD ON
,D/TimaService(  745): TIMA: TimaService scheduler is intialized. 
,D/TimaService(  745): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService(  745): TimaServiceHandler.handleMessage what =1
,D/BatteryService(  745): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:8, charge type:1, power sharing:false
,D/BatteryService(  745): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  745): mCoverManager.getCoverState() : true
,D/BatteryService(  745): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1063): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1063): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1063):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1063): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3154): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3154): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1063): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  745): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  745): prevTemp = 268, currTemp = 268, prevStep = 4, currStep = 4
,E/SMD     (  238): DCD ON
,I/TLC_TIMA_PKM_measure_kernel(  745): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel(  745): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService(  745): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,I/PowerManagerService(  745): [PWL] Off : 1755s ago
,D/TimaService(  745): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/SMD     (  238): DCD ON
,E/Watchdog(  745): !@Sync 60
,E/SMD     (  238): DCD ON
,E/SMD     (  238): DCD ON
,D/BatteryService(  745): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  745): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  745): mCoverManager.getCoverState() : true
,D/BatteryService(  745): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1063): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1063): handleBatteryUpdate
,V/HeadsetService( 3154): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3154): Disconnected process message: 10
,D/STATUSBAR-PhoneStatusBar( 1063):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1063): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1063): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  745): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  745): prevTemp = 268, currTemp = 268, prevStep = 4, currStep = 4
,E/SMD     (  238): DCD ON
,E/SMD     (  238): DCD ON
,E/SMD     (  238): DCD ON
,D/BatteryService(  745): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:3, charge type:1, power sharing:false
,D/BatteryService(  745): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  745): stay LED for fully charged
,D/UiModeManager(  745): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1063): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1063): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1063):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1063): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 3154): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 3154): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1063): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  745): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  745): prevTemp = 268, currTemp = 268, prevStep = 4, currStep = 4
,E/SMD     (  238): DCD ON
,E/SMD     (  238): DCD ON
,E/SMD     (  238): DCD ON
,D/BatteryService(  745): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService(  745): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  745): mCoverManager.getCoverState() : true
,D/BatteryService(  745): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1063): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1063): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1063):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1063): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 3154): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 3154): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1063): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  745): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  745): prevTemp = 268, currTemp = 268, prevStep = 4, currStep = 4
,E/SMD     (  238): DCD ON
,V/AlarmManager(  745): waitForAlarm result :8
,V/AlarmManager(  745): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1063): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1063): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1063): checkOverflow(288), More:false, Req:false Child:2
,I/ProcessStatsService(  745): Prepared write state in 141ms
,I/ProcessStatsService(  745): Prepared write state in 100ms
,I/ProcessStatsService(  745): Pruning old procstats: /data/system/procstats/state-2015-12-15-12-15-23.bin
,E/SMD     (  238): DCD ON
,E/Watchdog(  745): !@Sync 61
,E/SMD     (  238): DCD ON
,E/SMD     (  238): DCD ON
,D/BatteryService(  745): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  745): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  745): stay LED for fully charged
,D/UiModeManager(  745): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1063): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1063): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1063):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1063): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 3154): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 3154): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1063): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  745): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  745): prevTemp = 268, currTemp = 268, prevStep = 4, currStep = 4
,E/SMD     (  238): DCD ON
,E/SMD     (  238): DCD ON
,E/SMD     (  238): DCD ON
,D/BatteryService(  745): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-2, charge type:1, power sharing:false
,D/BatteryService(  745): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  745): mCoverManager.getCoverState() : true
,D/BatteryService(  745): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1063): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1063): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1063):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1063): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 3154): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 3154): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1063): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  745): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  745): prevTemp = 268, currTemp = 268, prevStep = 4, currStep = 4
,E/SMD     (  238): DCD ON
,E/SMD     (  238): DCD ON
,E/SMD     (  238): DCD ON
,D/BatteryService(  745): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-2, charge type:1, power sharing:false
,D/BatteryService(  745): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  745): stay LED for fully charged
,D/UiModeManager(  745): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1063): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1063): handleBatteryUpdate
,D/SSRMv2:SIOP(  745): SIOP:: AP = 300, Delta = 0
,D/STATUSBAR-PhoneStatusBar( 1063):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1063): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3154): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3154): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1063): checkOverflow(288), More:false, Req:false Child:2
,D/AmoledAdjustTimer(  745): prevTemp = 268, currTemp = 268, prevStep = 4, currStep = 4
,E/SMD     (  238): DCD ON
,E/SMD     (  238): DCD ON
,E/Watchdog(  745): !@Sync 62
,E/SMD     (  238): DCD ON
,E/SMD     (  238): DCD ON
,D/BatteryService(  745): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  745): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  745): stay LED for fully charged
,D/UiModeManager(  745): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1063): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1063): handleBatteryUpdate
,D/SSRMv2:SIOP(  745): SIOP:: AP = 300, Delta = 0
,D/STATUSBAR-PhoneStatusBar( 1063):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1063): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3154): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3154): Disconnected process message: 10
D/AmoledAdjustTimer(  745): prevTemp = 268, currTemp = 268, prevStep = 4, currStep = 4
,D/STATUSBAR-IconMerger( 1063): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  238): DCD ON
,E/SMD     (  238): DCD ON
,E/SMD     (  238): DCD ON
,D/SSRMv2:SIOP(  745): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  745): prevTemp = 268, currTemp = 268, prevStep = 4, currStep = 4
,E/SMD     (  238): DCD ON
,E/SMD     (  238): DCD ON
,E/SMD     (  238): DCD ON
,D/SSRMv2:SIOP(  745): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  745): prevTemp = 268, currTemp = 268, prevStep = 4, currStep = 4
,E/SMD     (  238): DCD ON
,V/AlarmManager(  745): waitForAlarm result :8
,V/AlarmManager(  745): ClockReceiver onReceive() ACTION_TIME_TICK
,V/AlarmManager(  745): ___SyncScheduler (v3) ACTIVATED___
V/AlarmManager(  745): <AppSync3 Whitelist>
,D/KeyguardUpdateMonitor( 1063): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1063): handleTimeUpdate
V/AlarmManager(  745): (AppSync) ### 0 added ###
,D/STATUSBAR-IconMerger( 1063): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  238): DCD ON
,E/Watchdog(  745): !@Sync 63
,E/SMD     (  238): DCD ON
,E/SMD     (  238): DCD ON
,D/BatteryService(  745): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:7, charge type:1, power sharing:false
,D/BatteryService(  745): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  745): stay LED for fully charged
,D/UiModeManager(  745): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1063): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1063): handleBatteryUpdate
,D/SSRMv2:SIOP(  745): SIOP:: AP = 300, Delta = 0
,D/STATUSBAR-PhoneStatusBar( 1063):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1063): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer(  745): prevTemp = 268, currTemp = 268, prevStep = 4, currStep = 4
,V/HeadsetService( 3154): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3154): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1063): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  238): DCD ON
,E/SMD     (  238): DCD ON
,E/SMD     (  238): DCD ON
,D/SSRMv2:SIOP(  745): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  745): prevTemp = 268, currTemp = 268, prevStep = 4, currStep = 4
,E/SMD     (  238): DCD ON
,E/SMD     (  238): DCD ON
,E/SMD     (  238): DCD ON
,V/AlarmManager(  745): waitForAlarm result :4
,I/SensorManagerA(  745): getReportingMode :: sensor.mType = 5
,D/Sensors (  745): LightSensor setDelay = 200000000
,D/LightsService(  745): [api] onReceive : SvcLEDReceiver re-enables LightSenor and sends MSG_FORCEDSVCLEDTASK
D/Sensors (  745): LightSensor setSensorDelay = 200000000
D/Sensors (  745): Light sensor flush: not enabled 0
D/Sensors (  745): LightSensor enable = 1
D/Sensors (  745): LightSensor enableSensor = 1
D/SensorManager(  745): registerListener :: 16, CM36686 Light Sensor, 200000, 0,  
,I/ActivityManager(  745): Killing 5174:com.sec.android.soagent/u0a37 (adj 15): empty for 1800s
,I/ActivityManager(  745): Killing 4538:com.sec.android.app.shealth/u0a35 (adj 15): empty for 1800s
,I/ActivityManager(  745): Killing 5150:com.samsung.klmsagent/u0a18 (adj 15): empty for 1800s
,I/ActivityManager(  745): Killing 5133:com.sec.android.fotaclient/u0a10 (adj 15): empty for 1800s
,I/ActivityManager(  745): Killing 5313:com.samsung.android.service.travel/u0a169 (adj 15): empty for 1801s
,I/ActivityManager(  745): Killing 5309:com.sec.android.provider.badge/u0a72 (adj 15): empty for 1801s
,I/ActivityManager(  745): Killing 4955:tv.peel.smartremote/u0a163 (adj 15): empty for 1801s
,I/ActivityManager(  745): Killing 5286:com.android.email/u0a155 (adj 15): empty for 1801s
,I/ActivityManager(  745): Killing 4183:com.google.android.apps.plus/u0a130 (adj 15): empty for 1801s
,I/ActivityManager(  745): Killing 5249:com.google.android.apps.magazines/u0a112 (adj 15): empty for 1801s
,I/ActivityManager(  745): Killing 4785:com.samsung.android.magazine.service/u0a106 (adj 15): empty for 1802s
,I/ActivityManager(  745): Killing 5099:com.android.chrome/u0a81 (adj 15): empty for 1802s
,I/ActivityManager(  745): Killing 5223:com.samsung.android.scloud.backup/u0a60 (adj 15): empty for 1802s
,I/ActivityManager(  745): Killing 5194:com.sec.android.app.voicenote/1000 (adj 15): empty for 1802s
,I/ActivityManager(  745): Killing 3701:com.sec.spp.push/u0a38 (adj 15): empty for 1802s
,I/ActivityManager(  745): Killing 5186:com.sec.android.app.videoplayer/u0a52 (adj 15): empty for 1802s
,D/BatteryService(  745): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:6, charge type:1, power sharing:false
,D/BatteryService(  745): stay LED for fully charged
,I/ActivityManager(  745): Killing 4625:com.policydm/1000 (adj 15): empty for 1802s
,I/ActivityManager(  745): Killing 4985:com.vlingo.midas/u0a33 (adj 15): empty for 1802s
,I/ActivityManager(  745): Killing 4222:com.sec.android.diagmonagent/1000 (adj 15): empty for 1803s
,I/ActivityManager(  745): Killing 5084:com.sec.android.cloudagent/u0a2 (adj 15): empty for 1803s
,I/ActivityManager(  745): Killing 3753:com.google.android.music:main/u0a122 (adj 15): empty for 1803s
,I/ActivityManager(  745): Killing 4507:com.sec.pcw.device/1000 (adj 15): empty for 1803s
,I/ActivityManager(  745): Killing 4168:com.sec.android.app.FileShareServer/u0a69 (adj 15): empty for 1806s
,I/ActivityManager(  745): Killing 4825:com.samsung.android.provider.shootingmodeprovider/u0a162 (adj 15): empty for 1812s
,I/ActivityManager(  745): Killing 4813:com.sec.kidsplat.installer/u0a158 (adj 15): empty for 1813s
,I/ActivityManager(  745): Killing 4798:com.samsung.helphub/1000 (adj 15): empty for 1813s
,V/NetworkStats(  745): performPollLocked(flags=0x3)
D/NtpTrustedTime(  745): currentTimeMillis() cache hit
,E/SMD     (  238): DCD ON
,V/AlarmManager(  745): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,D/Sensors (  745): LightSensor enable = 0
,D/Sensors (  745): LightSensor enableSensor = 0
,D/LightsService(  745): [SvcLED]  onSensorChanged::light value = 0
,D/SensorManager(  745): unregisterListener ::   
D/LightsService(  745): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,V/AlarmManager(  745): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,D/NtpTrustedTime(  745): currentTimeMillis() cache hit
V/NetworkStats(  745): performPollLocked() took 185ms
,D/BatteryService(  745): Sending ACTION_BATTERY_CHANGED.
,D/SSRMv2:SIOP(  745): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  745): prevTemp = 268, currTemp = 268, prevStep = 4, currStep = 4
,D/NtpTrustedTime(  745): currentTimeMillis() cache hit
,D/NtpTrustedTime(  745): currentTimeMillis() cache hit
,D/UiModeManager(  745): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1063): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1063): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1063):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1063): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3154): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3154): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1063): checkOverflow(288), More:false, Req:false Child:2
,I/Icing   ( 1780): Performing maintenance.
,V/GLSActivity( 1303): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1303): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/dalvikvm( 1303): VFY: unable to find class referenced in signature (Landroid/net/Network;)
E/dalvikvm( 1303): Could not find class 'android.net.Network', referenced from method com.google.android.gms.http.l.a
W/dalvikvm( 1303): VFY: unable to resolve check-cast 229 (Landroid/net/Network;) in Lcom/google/android/gms/http/l;
,D/dalvikvm( 1303): VFY: replacing opcode 0x1f at 0x0011
I/dalvikvm( 1303): Could not find method android.os.PowerManager.isInteractive, referenced from method com.google.android.gms.common.util.y.a
W/dalvikvm( 1303): VFY: unable to resolve virtual method 1378: Landroid/os/PowerManager;.isInteractive ()Z
,D/dalvikvm( 1303): VFY: replacing opcode 0x6e at 0x003d
,I/System.out( 1303): Thread-75(HTTPLog):isShipBuild true
,I/System.out( 1303): Thread-75(HTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,I/Icing   ( 1780): updateResources: need to parse f{com.google.android.gms}
,D/dalvikvm(  745): GC_CONCURRENT freed 3451K, 57% free 23665K/54428K, paused 16ms+13ms, total 192ms
,D/dalvikvm( 1780): GC_CONCURRENT freed 1265K, 32% free 12872K/18912K, paused 4ms+8ms, total 46ms
,I/Icing   ( 1780): Performing maintenance usage 1782527 budget 5449681279 free 99.967% index free 99.979% purge? false target 3814776895
,D/dalvikvm( 1303): GC_CONCURRENT freed 1953K, 43% free 10842K/18912K, paused 2ms+4ms, total 33ms
,D/dalvikvm( 1303): WAIT_FOR_CONCURRENT_GC blocked 15ms
,I/Icing   ( 1780): Query from com.google.android.gms package restrict com.google.android.gms start 0 num 100
,D/ConnectivityService(  745): handleInetConditionHoldEnd: net=1, condition=100, published condition=100
,D/STATUSBAR-NetworkController_dual( 1063): onReceive() - CONNECTIVITY_ACTION, INET_CONDITION_ACTION
D/StatusBar.NetworkController_dual( 1063): mMobileLabelViews start
D/StatusBar.NetworkController_dual( 1063): mMobileLabelViews set mobileLabel[SIM_0] =
D/StatusBar.NetworkController_dual( 1063): mMobileLabelViews GONE
D/StatusBar.NetworkController_dual( 1063): mMobileLabelViews2 set mobileLabel[SIM_1] =
D/StatusBar.NetworkController_dual( 1063): mMobileLabelViews2 GONE
,D/StatusBar.NetworkController_dual( 1063): mSingleMobileLabelViews set : simMode = 0
,D/StatusBar.NetworkController_dual( 1063): mSingleMobileLabelViews set as slot1`s
,I/Icing   ( 1780): Indexing 49CA7E3A917E607C6D98AA15891295369CED2106 from com.google.android.gms
,I/Icing   ( 1780): Indexing done 49CA7E3A917E607C6D98AA15891295369CED2106
,E/SMD     (  238): DCD ON
,E/Watchdog(  745): !@Sync 64
,E/SMD     (  238): DCD ON
,E/SMD     (  238): DCD ON
,D/BatteryService(  745): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService(  745): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  745): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1063): received broadcast android.intent.action.BATTERY_CHANGED
,D/UiModeManager(  745): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 1063): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1063):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1063): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3154): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3154): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1063): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  745): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  745): prevTemp = 268, currTemp = 268, prevStep = 4, currStep = 4
,E/SMD     (  238): DCD ON
,TIME-OUT KILL (timeout was 1800000ms),E/SMD     (  238): DCD ON
I/PowerManagerService(  745): [PWL] Off : 1890s ago
E/SMD     (  238): DCD ON
D/BatteryService(  745): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:2, charge type:1, power sharing:false
D/BatteryService(  745): Sending ACTION_BATTERY_CHANGED.
D/BatteryService(  745): stay LED for fully charged
D/UiModeManager(  745): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 1063): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1063): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 1063):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
V/HeadsetService( 3154): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 3154): Disconnected process message: 10
D/BatteryMeterView( 1063): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/STATUSBAR-IconMerger( 1063): checkOverflow(288), More:false, Req:false Child:2
D/SSRMv2:SIOP(  745): SIOP:: AP = 300, Delta = 0
D/AmoledAdjustTimer(  745): prevTemp = 268, currTemp = 268, prevStep = 4, currStep = 4
E/SMD     (  238): DCD ON
E/SMD     (  238): DCD ON
D/AndroidRuntime( 6073): 
D/AndroidRuntime( 6073): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 6073): CheckJNI is OFF
D/AndroidRuntime( 6073): setted country_code = Poland
D/AndroidRuntime( 6073): setted countryiso_code = PL
D/AndroidRuntime( 6073): setted sales_code = XEO
D/AndroidRuntime( 6073): readGMSProperty: start
D/AndroidRuntime( 6073): readGMSProperty: already setted!!
D/AndroidRuntime( 6073): readGMSProperty: end
D/AndroidRuntime( 6073): addProductProperty: start
D/dalvikvm( 6073): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 6073): Added shared lib libjavacore.so 0x0
D/dalvikvm( 6073): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 6073): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 6073): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
E/memtrack( 6073): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 6073): failed to load memtrack module: -2
D/dalvikvm( 6073): Note: class Landroid/app/ActivityManagerNative; has 192 unimplemented (abstract) methods
D/AndroidRuntime( 6073): Calling main entry com.android.commands.pm.Pm
D/PackageManagerService(  745): deletePackageAsUser- pkg:com.test.thalitest, userId:0
D/PersonaManagerService(  745): isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
D/PersonaManagerService(  745): isFromApprovedUnInstaller: isApproved : true
D/PersonaManagerService(  745): isFromApprovedUnInstaller: isApproved before exit: true
D/PackageManager(  745): deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag3
D/PackageManager(  745): deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag3
D/PackageManagerService(  745): deletePackage- pkg:com.test.thalitest, edmuserId:0
D/PackageManagerService(  745): deletePackage- pkg:com.test.thalitest, edmuserId:-1
D/ApplicationPolicy(  745): getApplicationUninstallationEnabled
D/ApplicationPolicy(  745): getApplicationUninstallationEnabled :  enabled true
D/PackageManagerService(  745): deletePackageX- pkg:com.test.thalitest, userId:0
D/PackageManager(  745): START PACKAGE DELETE: observer{1121528432}
D/PackageManager(  745): pkg{<packageName>}
D/PackageManager(  745): user{0}
D/PackageManager(  745): deletePackageAsUser : uid = 2000 userId = 0
D/PackageManager(  745): [MSG] DELETE_PACKAGE_AS_USER
D/PackageManager(  745): !@killApplicatoin: 10179, uninstall pkg
W/PackageSettings(  745): Skipping PackageSetting{427ee608 com.example.hello/10181} due to missing metadata
D/PackageManager(  745): Sending to user 0: act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000000 Bundle[{android.intent.extra.REMOVED_FOR_ALL_USERS=true, android.intent.extra.UID=10179, android.intent.extra.DATA_REMOVED=true, android.intent.extra.user_handle=0}]
D/dalvikvm( 1780): GC_EXPLICIT freed 1177K, 36% free 12240K/18912K, paused 4ms+5ms, total 47ms
D/dalvikvm( 1403): GC_EXPLICIT freed 4297K, 47% free 10025K/18912K, paused 6ms+4ms, total 61ms
I/FPMS_FingerprintManagerService( 1082): onReceive: android.intent.action.PACKAGE_REMOVED
D/AdaptiveEventManager( 1063): action=android.intent.action.PACKAGE_REMOVED
D/PackageManager(  745): Sending to user 0: act=android.intent.action.PACKAGE_FULLY_REMOVED dat=package:com.test.thalitest flg=0x4000000 Bundle[{android.intent.extra.REMOVED_FOR_ALL_USERS=true, android.intent.extra.UID=10179, android.intent.extra.DATA_REMOVED=true, android.intent.extra.user_handle=0}]
I/InputReader(  745): Reconfiguring input devices.  changes=0x00000010
D/dalvikvm( 2116): GC_EXPLICIT freed 1116K, 41% free 11210K/18912K, paused 2ms+4ms, total 126ms
D/QuickConnect[1.1][2] ( 3125): SconnectManager.onReceiver - action : android.intent.action.PACKAGE_REMOVED, package : com.test.thalitest
I/PackageManager(  745):   Action: "android.intent.action.SENDTO"
I/PackageManager(  745):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  745):   Scheme: "sms"
I/PackageManager(  745): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
D/elm:14132( 5415): ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
D/dalvikvm(  745): GC_EXPLICIT freed 1364K, 57% free 23682K/54428K, paused 7ms+14ms, total 153ms
W/GeofencerStateMachine( 1215): Ignoring removeGeofence because network location is disabled.
I/PackageManager(  745):   Action: "android.intent.action.SENDTO"
I/PackageManager(  745):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  745):   Scheme: "smsto"
I/PackageManager(  745): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
I/PackageManager(  745):   Action: "android.intent.action.SENDTO"
I/PackageManager(  745):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  745):   Scheme: "mms"
I/PackageManager(  745): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
D/RCPManagerService(  745): PackageReceiver onReceive()
D/elm:14132( 5415): ELMAbstractReceiver : Receive Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
D/elm:14132( 5415): ElmAgentService : onCreate()
I/PackageManager(  745):   Action: "android.intent.action.SENDTO"
I/PackageManager(  745):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  745):   Scheme: "mmsto"
D/elm:14132( 5415): ElmAgentService : onHandleIntent() Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
D/elm:14132( 5415): MainReceiver.listeningToPackageRemoved()
D/elm:14132( 5415): MDMBridge.getInstance()
I/HarmonyEASService(  745): onReceive : android.intent.action.PACKAGE_REMOVED for 0
D/elm:14132( 5415): MDMBridge.getAllLicenseInfoFromSDK()
I/PackageManager(  745): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
I/SELinux ( 6100): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 6100):  
D/elm:14132( 5415): MDMBridge.getAllLicenseInfoFromSDK()
I/PackageManager(  745):   Action: "android.intent.action.SENDTO"
I/PackageManager(  745):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  745):   Scheme: "sms"
I/PackageManager(  745): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
D/elm:14132( 5415): MainReceiver.listeningToPackageRemoved(). SEND to KLMS. Remove All KNOX/ONS License
D/elm:14132( 5415): ElmAgentService : onDestroy().
I/PackageManager(  745):   Action: "android.intent.action.SENDTO"
I/PackageManager(  745):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  745):   Scheme: "smsto"
I/SELinux ( 6100): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 6100):  
I/SELinux ( 6100):  
I/SELinux ( 6100): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 6100): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 6100): >>>>> Normal User
E/dalvikvm( 6100): >>>>> com.sec.android.service.health [ userId:0 | appId:10016 ]
I/PackageManager(  745): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
E/SELinux ( 6100): [DEBUG] seapp_context_lookup: seinfoCategory = platform
D/TimaKeyStoreProvider( 6100): in addTimaSignatureService
D/TimaKeyStoreProvider( 6100): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 6100): Added TimaKesytore provider
D/dalvikvm(  745): GC_EXPLICIT freed 685K, 57% free 23606K/54428K, paused 6ms+19ms, total 180ms
I/PackageManager(  745):   Action: "android.intent.action.SENDTO"
I/PackageManager(  745):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  745):   Scheme: "mms"
I/PackageManager(  745): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
D/PackageManager(  745): delete sourFile : 
D/EnterpriseDeviceManagerService(  745): Package has changed for user 0
D/EnterpriseDeviceManagerService(  745): Admin package name: com.google.android.gms
I/PackageManager(  745):   Action: "android.intent.action.SENDTO"
I/PackageManager(  745):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  745):   Scheme: "mmsto"
I/PackageManager(  745): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
D/PackageManager(  745): delete native library directory: 
D/PackageManager(  745): return delete result to caller: 1121528432
D/PackageManager(  745): returnCode: 1
D/AndroidRuntime( 6073): Shutting down VM
D/dalvikvm( 6073): GC_CONCURRENT freed 96K, 14% free 670K/772K, paused 1ms+0ms, total 3ms
D/BackupManagerService(  745): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
V/BackupManagerService(  745): removePackageParticipantsLocked: uid=10179 #1
W/Resources(  745): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
I/PackageManager(  745):   Action: "android.intent.action.SENDTO"
I/PackageManager(  745):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  745):   Scheme: "sms"
I/PackageManager(  745): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
W/Resources(  745): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
I/PackageManager(  745):   Action: "android.intent.action.SENDTO"
I/PackageManager(  745):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  745):   Scheme: "smsto"
I/PackageManager(  745): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
I/PackageManager(  745):   Action: "android.intent.action.SENDTO"
I/PackageManager(  745):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  745):   Scheme: "mms"
I/PackageManager(  745): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
W/ActivityManager(  745): Permission Denial: getCurrentUser() from pid=6100, uid=10016 requires android.permission.INTERACT_ACROSS_USERS
W/Resources(  745): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
I/PackageManager(  745):   Action: "android.intent.action.SENDTO"
I/PackageManager(  745):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  745):   Scheme: "mmsto"
I/PackageManager(  745): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
W/Resources(  745): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/dalvikvm( 6100): No JNI_OnLoad found in /system/lib/libsecure_storage_jni.so 0x4260dbc8, skipping init
I/SecureStorage( 6100): [INFO]: SPID(0x00000000)Checking if this device supports Secure Storage
I/SecureStorage( 6100): [INFO]: SPID(0x00000000)This device supports Secure Storage
I/SecureStorage(  316): [INFO]: SPID(0x00000004)Credentials: uid 10016, gid 10016, pid 6100
I/SecureStorage(  316): [INFO]: SPID(0x00000004)Received function mask & code: 0000010C
I/SecureStorage( 6100): [INFO]: SPID(0x00000000)SS Daemon is running
W/Resources(  745): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
I/SecureStorage( 6100): [INFO]: SPID(0x00000000)Processing data
I/SecureStorage(  316): [INFO]: SPID(0x00000004)Credentials: uid 10016, gid 10016, pid 6100
I/SecureStorage(  316): [INFO]: SPID(0x00000004)Received function mask & code: 00000106
W/Resources(  745): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  745): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  745): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  745): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  745): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  745): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
W/Resources(  745): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  745): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  745): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
W/Resources(  745): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  745): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  745): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
I/CrashAnrDetector(  745): onPackageRemoved : com.test.thalitest
D/UsbSettingsManager(  745): clearDefaults: com.test.thalitest
D/InputReader(  745): Processing first event
W/ApplicationsProvider( 1403): Could not fetch usage stats
W/ApplicationsProvider( 1403): java.lang.SecurityException: Neither user 10020 nor current process has android.permission.PACKAGE_USAGE_STATS.
W/ApplicationsProvider( 1403): 	at android.os.Parcel.readException(Parcel.java:1465)
W/ApplicationsProvider( 1403): 	at android.os.Parcel.readException(Parcel.java:1419)
W/ApplicationsProvider( 1403): 	at com.android.internal.app.IUsageStats$Stub$Proxy.getAllPkgUsageStats(IUsageStats.java:317)
W/ApplicationsProvider( 1403): 	at android.app.ActivityManager.getAllPackageUsageStats(ActivityManager.java:2543)
W/ApplicationsProvider( 1403): 	at com.android.providers.applications.ApplicationsProvider.fetchUsageStats(ApplicationsProvider.java:681)
W/ApplicationsProvider( 1403): 	at com.android.providers.applications.ApplicationsProvider.updateApplicationsList(ApplicationsProvider.java:519)
W/ApplicationsProvider( 1403): 	at com.android.providers.applications.ApplicationsProvider.access$300(ApplicationsProvider.java:70)
W/ApplicationsProvider( 1403): 	at com.android.providers.applications.ApplicationsProvider$UpdateHandler.handleMessage(ApplicationsProvider.java:209)
W/ApplicationsProvider( 1403): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/ApplicationsProvider( 1403): 	at android.os.Looper.loop(Looper.java:146)
W/ApplicationsProvider( 1403): 	at android.os.HandlerThread.run(HandlerThread.java:61)

```
