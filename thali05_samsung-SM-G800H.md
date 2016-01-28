#### Test 573480784751f5c_thali05_samsung-SM-G800H Logs


```
--------- beginning of /dev/log/system
W/ActivityManager(  761): Permission Denial: getCurrentUser() from pid=4442, uid=10035 requires android.permission.INTERACT_ACROSS_USERS
--------- beginning of /dev/log/main
W/ContextImpl( 4442): Implicit intents with startService are not safe: Intent { act=com.sec.android.service.health.cp.accesscontrol } android.content.ContextWrapper.bindService:529 com.samsung.android.sdk.health.content.ShealthAccessControl.startService:274 com.samsung.android.sdk.health.content.ShealthAccessControl.requestPermission:212 
,I/SELinux ( 4464): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 4464):  
E/Device Type Shared Preferences( 4442): Device Type Shared Preferences - getDeviceTypeChecked -true
E/Device Type Shared Preferences( 4442): Device Type Shared Preferences - not connecting to service
E/com.sec.android.app.shealth.SHealthApplication( 4442): ContentProvider is not null
I/SELinux ( 4464): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 4464):  
I/SELinux ( 4464):  
I/SELinux ( 4464): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 4464): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 4464): >>>>> Normal User
E/dalvikvm( 4464): >>>>> com.sec.android.service.health [ userId:0 | appId:10016 ]
E/SELinux ( 4464): [DEBUG] seapp_context_lookup: seinfoCategory = platform
D/TimaKeyStoreProvider( 4464): in addTimaSignatureService
D/TimaKeyStoreProvider( 4464): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 4464): Added TimaKesytore provider
V/MediaPlayer( 4442): decode(61, 33979084, 48105)
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
V/AudioCache(  251): notify(0xb7932fd0, 8, 0, 0)
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
V/AudioCache(  251): notify(0xb7932fd0, 200, 973, 0)
V/AudioCache(  251): ignored
V/AwesomePlayer(  251): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  251): notify(0xb7932fd0, 5, 0, 0)
V/AudioCache(  251): ignored
V/AwesomePlayer(  251): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  251): notify(0xb7932fd0, 1, 0, 0)
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
V/AudioCache(  251): notify(0xb7932fd0, 6, 0, 0)
V/AudioCache(  251): ignored
V/AwesomePlayer(  251): addBatteryData
V/MediaPlayerService(  251): wait for playback complete
I/OMXCodec(  251): [OMX.google.vorbis.decoder] End Of Stream
V/AwesomePlayer(  251): postAudioEOS delayUs (0)
W/ActivityManager(  761): Permission Denial: getCurrentUser() from pid=4464, uid=10016 requires android.permission.INTERACT_ACROSS_USERS
V/AwesomePlayer(  251): onCheckAudioStatus
V/AwesomePlayer(  251): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  251): onStreamDone
V/AwesomePlayer(  251): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  251): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  251): notify(0xb7932fd0, 2, 0, 0)
V/AudioCache(  251): playback complete - thread will wake up later
V/AwesomePlayer(  251): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  251): notify(0xb7932fd0, 7, 0, 0)
V/AudioCache(  251): ignored
V/AwesomePlayer(  251): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer(  251): addBatteryData
V/AudioCache(  251): wait - success
V/StagefrightPlayer(  251): reset
V/AwesomePlayer(  251): reset_l()
V/AwesomePlayer(  251): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  251): notify(0xb7932fd0, 8, 0, 0)
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
V/MediaPlayer( 4442): decode(62, 33914984, 10421)
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
V/AudioCache(  251): notify(0xb7932660, 8, 0, 0)
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
V/AudioCache(  251): notify(0xb7932660, 200, 973, 0)
V/AudioCache(  251): ignored
V/AwesomePlayer(  251): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  251): notify(0xb7932660, 5, 0, 0)
V/AudioCache(  251): ignored
V/AwesomePlayer(  251): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  251): notify(0xb7932660, 1, 0, 0)
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
V/AudioCache(  251): notify(0xb7932660, 6, 0, 0)
V/AudioCache(  251): ignored
V/AwesomePlayer(  251): addBatteryData
V/MediaPlayerService(  251): wait for playback complete
I/AudioPlayer(  251): First fillBuffer call!!
D/dalvikvm( 4464): No JNI_OnLoad found in /system/lib/libsecure_storage_jni.so 0x4264bc50, skipping init
I/SecureStorage( 4464): [INFO]: SPID(0x00000000)Checking if this device supports Secure Storage
I/SecureStorage( 4464): [INFO]: SPID(0x00000000)This device supports Secure Storage
I/SecureStorage(  301): [INFO]: SPID(0x00000003)Credentials: uid 10016, gid 10016, pid 4464
I/SecureStorage(  301): [INFO]: SPID(0x00000003)Received function mask & code: 0000010C
I/SecureStorage( 4464): [INFO]: SPID(0x00000000)SS Daemon is running
I/OMXCodec(  251): [OMX.google.vorbis.decoder] End Of Stream
V/AwesomePlayer(  251): postAudioEOS delayUs (0)
V/AwesomePlayer(  251): onCheckAudioStatus
V/AwesomePlayer(  251): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  251): onStreamDone
V/AwesomePlayer(  251): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  251): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  251): notify(0xb7932660, 2, 0, 0)
V/AudioCache(  251): playback complete - thread will wake up later
V/AwesomePlayer(  251): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  251): notify(0xb7932660, 7, 0, 0)
V/AudioCache(  251): ignored
V/AwesomePlayer(  251): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer(  251): addBatteryData
V/AudioCache(  251): wait - success
V/StagefrightPlayer(  251): reset
V/AwesomePlayer(  251): reset_l()
V/AwesomePlayer(  251): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  251): notify(0xb7932660, 8, 0, 0)
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
V/MediaPlayer( 4442): decode(63, 37457308, 34198)
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
V/AudioCache(  251): notify(0xb791b650, 8, 0, 0)
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
V/AudioCache(  251): notify(0xb791b650, 200, 973, 0)
V/AudioCache(  251): ignored
V/AwesomePlayer(  251): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  251): notify(0xb791b650, 5, 0, 0)
V/AudioCache(  251): ignored
V/AwesomePlayer(  251): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  251): notify(0xb791b650, 1, 0, 0)
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
I/SecureStorage( 4464): [INFO]: SPID(0x00000000)Processing data
I/SecureStorage(  301): [INFO]: SPID(0x00000003)Credentials: uid 10016, gid 10016, pid 4464
I/SecureStorage(  301): [INFO]: SPID(0x00000003)Received function mask & code: 00000106
I/AudioPlayer(  251):  Audioplayer kKeyAudioPCMFormat:1, 2, 0
I/AudioPlayer(  251):  Audioplayer kKeyAudioPCMFormat read fail(2, 1)
V/AudioCache(  251): open(44100, 2, 0x0, 1, 4)
V/AwesomePlayer(  251): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache(  251): notify(0xb791b650, 6, 0, 0)
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
V/AudioCache(  251): notify(0xb791b650, 2, 0, 0)
V/AudioCache(  251): playback complete - thread will wake up later
V/AwesomePlayer(  251): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  251): notify(0xb791b650, 7, 0, 0)
V/AudioCache(  251): ignored
V/AwesomePlayer(  251): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer(  251): addBatteryData
V/AudioCache(  251): wait - success
V/StagefrightPlayer(  251): reset
V/AwesomePlayer(  251): reset_l()
V/AwesomePlayer(  251): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  251): notify(0xb791b650, 8, 0, 0)
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
V/MediaPlayer( 4442): decode(64, 33862452, 7405)
V/MediaPlayerService(  251): decode(33, 33862452, 7405)
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
V/AudioCache(  251): notify(0xb7932120, 8, 0, 0)
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
V/AudioCache(  251): notify(0xb7932120, 200, 973, 0)
V/AudioCache(  251): ignored
V/AwesomePlayer(  251): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  251): notify(0xb7932120, 5, 0, 0)
V/AudioCache(  251): ignored
V/AwesomePlayer(  251): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  251): notify(0xb7932120, 1, 0, 0)
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
V/AudioCache(  251): notify(0xb7932120, 6, 0, 0)
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
V/AudioCache(  251): notify(0xb7932120, 2, 0, 0)
V/AudioCache(  251): playback complete - thread will wake up later
V/AwesomePlayer(  251): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  251): notify(0xb7932120, 7, 0, 0)
V/AudioCache(  251): ignored
V/AwesomePlayer(  251): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer(  251): addBatteryData
V/AudioCache(  251): wait - success
V/StagefrightPlayer(  251): reset
V/AwesomePlayer(  251): reset_l()
V/AwesomePlayer(  251): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  251): notify(0xb7932120, 8, 0, 0)
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
V/MediaPlayer( 4442): decode(66, 37547940, 5555)
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
V/AudioCache(  251): notify(0xb792d808, 8, 0, 0)
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
V/AudioCache(  251): notify(0xb792d808, 200, 973, 0)
V/AudioCache(  251): ignored
V/AwesomePlayer(  251): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  251): notify(0xb792d808, 5, 0, 0)
V/AudioCache(  251): ignored
V/AwesomePlayer(  251): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  251): notify(0xb792d808, 1, 0, 0)
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
V/AudioCache(  251): notify(0xb792d808, 6, 0, 0)
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
V/AudioCache(  251): notify(0xb792d808, 2, 0, 0)
V/AudioCache(  251): playback complete - thread will wake up later
V/AwesomePlayer(  251): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  251): notify(0xb792d808, 7, 0, 0)
V/AudioCache(  251): ignored
V/AwesomePlayer(  251): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer(  251): addBatteryData
V/AudioCache(  251): wait - success
V/StagefrightPlayer(  251): reset
V/AwesomePlayer(  251): reset_l()
V/AwesomePlayer(  251): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  251): notify(0xb792d808, 8, 0, 0)
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
V/MediaPlayer( 4442): decode(67, 30367732, 5085)
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
V/AudioCache(  251): notify(0xb79229a8, 8, 0, 0)
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
V/AudioCache(  251): notify(0xb79229a8, 200, 973, 0)
V/AudioCache(  251): ignored
V/AwesomePlayer(  251): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  251): notify(0xb79229a8, 5, 0, 0)
V/AudioCache(  251): ignored
V/AwesomePlayer(  251): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  251): notify(0xb79229a8, 1, 0, 0)
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
V/AudioCache(  251): notify(0xb79229a8, 6, 0, 0)
I/AudioPlayer(  251): First fillBuffer call!!
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
V/AudioCache(  251): notify(0xb79229a8, 2, 0, 0)
V/AudioCache(  251): playback complete - thread will wake up later
V/AwesomePlayer(  251): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  251): notify(0xb79229a8, 7, 0, 0)
V/AudioCache(  251): ignored
V/AwesomePlayer(  251): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer(  251): addBatteryData
V/AudioCache(  251): wait - success
V/StagefrightPlayer(  251): reset
V/AwesomePlayer(  251): reset_l()
V/AwesomePlayer(  251): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  251): notify(0xb79229a8, 8, 0, 0)
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
V/MediaPlayer( 4442): decode(68, 30372876, 21552)
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
V/AudioCache(  251): notify(0xb792bd58, 8, 0, 0)
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
V/AudioCache(  251): notify(0xb792bd58, 200, 973, 0)
V/AudioCache(  251): ignored
V/AwesomePlayer(  251): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  251): notify(0xb792bd58, 5, 0, 0)
V/AudioCache(  251): ignored
V/AwesomePlayer(  251): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  251): notify(0xb792bd58, 1, 0, 0)
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
V/AudioCache(  251): notify(0xb792bd58, 6, 0, 0)
V/AudioCache(  251): ignored
V/AwesomePlayer(  251): addBatteryData
V/MediaPlayerService(  251): wait for playback complete
D/AndroidRuntime( 4469): 
D/AndroidRuntime( 4469): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 4469): CheckJNI is OFF
D/AndroidRuntime( 4469): setted country_code = Poland
D/AndroidRuntime( 4469): setted countryiso_code = PL
I/OMXCodec(  251): [OMX.google.vorbis.decoder] End Of Stream
D/AndroidRuntime( 4469): setted sales_code = XEO
D/AndroidRuntime( 4469): readGMSProperty: start
D/AndroidRuntime( 4469): readGMSProperty: already setted!!
D/AndroidRuntime( 4469): readGMSProperty: end
D/AndroidRuntime( 4469): addProductProperty: start
V/AwesomePlayer(  251): postAudioEOS delayUs (0)
V/AwesomePlayer(  251): onCheckAudioStatus
V/AwesomePlayer(  251): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  251): onStreamDone
V/AwesomePlayer(  251): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  251): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  251): notify(0xb792bd58, 2, 0, 0)
V/AudioCache(  251): playback complete - thread will wake up later
V/AwesomePlayer(  251): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  251): notify(0xb792bd58, 7, 0, 0)
V/AudioCache(  251): ignored
V/AwesomePlayer(  251): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer(  251): addBatteryData
V/AudioCache(  251): wait - success
V/StagefrightPlayer(  251): reset
V/AwesomePlayer(  251): reset_l()
V/AwesomePlayer(  251): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  251): notify(0xb792bd58, 8, 0, 0)
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
V/MediaPlayer( 4442): decode(69, 37543652, 4230)
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
V/AudioCache(  251): notify(0xb7922a28, 8, 0, 0)
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
V/AudioCache(  251): notify(0xb7922a28, 200, 973, 0)
V/AudioCache(  251): ignored
V/AwesomePlayer(  251): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  251): notify(0xb7922a28, 5, 0, 0)
V/AudioCache(  251): ignored
V/AwesomePlayer(  251): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  251): notify(0xb7922a28, 1, 0, 0)
V/AudioCache(  251): prepared
V/AudioCache(  251): wait - success
V/MediaPlayerService(  251): start
D/dalvikvm( 4469): Trying to load lib libjavacore.so 0x0
V/StagefrightPlayer(  251): start
V/AwesomePlayer(  251): play
V/AwesomePlayer(  251): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer(  251): startAudioPlayer_l, sendErrorNotification (0)
D/dalvikvm( 4469): Added shared lib libjavacore.so 0x0
I/OMXCodec(  251): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec(  251): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec(  251): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/OMXCodec(  251): [OMX.google.vorbis.decoder] End Of Stream
I/AudioPlayer(  251):  Audioplayer kKeyAudioPCMFormat:1, 1, 0
I/AudioPlayer(  251):  Audioplayer kKeyAudioPCMFormat read fail(1, 1)
V/AudioCache(  251): open(44100, 1, 0x0, 1, 4)
V/AwesomePlayer(  251): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache(  251): notify(0xb7922a28, 6, 0, 0)
V/AudioCache(  251): ignored
V/AwesomePlayer(  251): addBatteryData
V/MediaPlayerService(  251): wait for playback complete
D/dalvikvm( 4469): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 4469): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 4469): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
V/AwesomePlayer(  251): postAudioEOS delayUs (0)
V/AwesomePlayer(  251): onCheckAudioStatus
V/AwesomePlayer(  251): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  251): onStreamDone
V/AwesomePlayer(  251): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  251): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  251): notify(0xb7922a28, 2, 0, 0)
V/AudioCache(  251): playback complete - thread will wake up later
V/AwesomePlayer(  251): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  251): notify(0xb7922a28, 7, 0, 0)
V/AudioCache(  251): ignored
V/AwesomePlayer(  251): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer(  251): addBatteryData
V/AudioCache(  251): wait - success
V/StagefrightPlayer(  251): reset
V/AwesomePlayer(  251): reset_l()
V/AwesomePlayer(  251): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  251): notify(0xb7922a28, 8, 0, 0)
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
V/MediaPlayer( 4442): decode(70, 30337076, 9400)
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
V/AudioCache(  251): notify(0xb79353a0, 8, 0, 0)
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
V/AudioCache(  251): notify(0xb79353a0, 200, 973, 0)
V/AudioCache(  251): ignored
V/AwesomePlayer(  251): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  251): notify(0xb79353a0, 5, 0, 0)
V/AudioCache(  251): ignored
V/AwesomePlayer(  251): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  251): notify(0xb79353a0, 1, 0, 0)
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
I/AudioPlayer(  251):  Audioplayer kKeyAudioPCMFormat:1, 1, 0
I/AudioPlayer(  251):  Audioplayer kKeyAudioPCMFormat read fail(1, 1)
V/AudioCache(  251): open(44100, 1, 0x0, 1, 4)
V/AwesomePlayer(  251): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache(  251): notify(0xb79353a0, 6, 0, 0)
V/AudioCache(  251): ignored
V/AwesomePlayer(  251): addBatteryData
V/MediaPlayerService(  251): wait for playback complete
I/AudioPlayer(  251): First fillBuffer call!!
I/SELinux ( 4532): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 4532):  
I/ActivityManager(  761): Killing 3128:com.sec.android.app.mt/1000 (adj 15): empty #43
I/SELinux ( 4532): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 4532):  
I/SELinux ( 4532):  
I/SELinux ( 4532): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 4532): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 4532): >>>>> Normal User
E/dalvikvm( 4532): >>>>> com.policydm [ userId:0 | appId:1000 ]
E/SELinux ( 4532): [DEBUG] seapp_context_lookup: seinfoCategory = platform
I/OMXCodec(  251): [OMX.google.vorbis.decoder] End Of Stream
V/AwesomePlayer(  251): postAudioEOS delayUs (0)
V/AwesomePlayer(  251): onCheckAudioStatus
V/AwesomePlayer(  251): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  251): onStreamDone
V/AwesomePlayer(  251): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  251): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  251): notify(0xb79353a0, 2, 0, 0)
V/AudioCache(  251): playback complete - thread will wake up later
V/AwesomePlayer(  251): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  251): notify(0xb79353a0, 7, 0, 0)
V/AudioCache(  251): ignored
V/AwesomePlayer(  251): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer(  251): addBatteryData
V/AudioCache(  251): wait - success
V/StagefrightPlayer(  251): reset
V/AwesomePlayer(  251): reset_l()
V/AwesomePlayer(  251): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  251): notify(0xb79353a0, 8, 0, 0)
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
V/MediaPlayer( 4442): decode(71, 33925464, 44276)
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
V/AudioCache(  251): notify(0xb79359b0, 8, 0, 0)
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
D/TimaKeyStoreProvider( 4532): in addTimaSignatureService
V/AwesomePlayer(  251): onPrepareAsyncEvent
I/SecMediaClock(  251): SecMediaClock constructor
I/SecMediaClock(  251): reset
V/AwesomePlayer(  251): initAudioDecoder
V/AwesomePlayer(  251): checkOffloadExceptions is ,true
I/OMXCodec(  251): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
I/OMX     (  251): mDispatchers.add
I/OMXCodec(  251): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec(  251): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec(  251): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec(  251): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/OMXCodec(  251): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer(  251): finishAsyncPrepare_l
V/AwesomePlayer(  251): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache(  251): notify(0xb79359b0, 200, 973, 0)
V/AudioCache(  251): ignored
V/AwesomePlayer(  251): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  251): notify(0xb79359b0, 5, 0, 0)
V/AudioCache(  251): ignored
V/AwesomePlayer(  251): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  251): notify(0xb79359b0, 1, 0, 0)
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
V/AudioCache(  251): notify(0xb79359b0, 6, 0, 0)
V/AudioCache(  251): ignored
V/AwesomePlayer(  251): addBatteryData
V/MediaPlayerService(  251): wait for playback complete
D/TimaKeyStoreProvider( 4532): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 4532): Added TimaKesytore provider
E/memtrack( 4469): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 4469): failed to load memtrack module: -2
I/OMXCodec(  251): [OMX.google.vorbis.decoder] End Of Stream
V/AwesomePlayer(  251): postAudioEOS delayUs (0)
V/AwesomePlayer(  251): onCheckAudioStatus
V/AwesomePlayer(  251): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  251): onStreamDone
V/AwesomePlayer(  251): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  251): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  251): notify(0xb79359b0, 2, 0, 0)
V/AudioCache(  251): playback complete - thread will wake up later
V/AwesomePlayer(  251): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  251): notify(0xb79359b0, 7, 0, 0)
V/AudioCache(  251): ignored
V/AwesomePlayer(  251): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer(  251): addBatteryData
V/AudioCache(  251): wait - success
V/StagefrightPlayer(  251): reset
V/AwesomePlayer(  251): reset_l()
V/AwesomePlayer(  251): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  251): notify(0xb79359b0, 8, 0, 0)
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
D/dalvikvm( 4469): Note: class Landroid/app/ActivityManagerNative; has 192 unimplemented (abstract) methods
V/AwesomePlayer(  251): destructor
V/AwesomePlayer(  251): reset_l()
V/AwesomePlayer(  251): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  251): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  251): mAudioTrackVector clear
V/AwesomePlayer(  251): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  251): mSecMediaClock clear
V/MediaPlayer( 4442): decode(72, 33885672, 29256)
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
V/AudioCache(  251): notify(0xb7933198, 8, 0, 0)
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
V/AudioCache(  251): notify(0xb7933198, 200, 973, 0)
V/AudioCache(  251): ignored
V/AwesomePlayer(  251): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  251): notify(0xb7933198, 5, 0, 0)
V/AudioCache(  251): ignored
V/AwesomePlayer(  251): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  251): notify(0xb7933198, 1, 0, 0)
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
V/AudioCache(  251): notify(0xb7933198, 6, 0, 0)
V/AudioCache(  251): ignored
V/AwesomePlayer(  251): addBatteryData
V/MediaPlayerService(  251): wait for playback complete
D/AndroidRuntime( 4469): Calling main entry com.android.commands.am.Am
I/OMXCodec(  251): [OMX.google.vorbis.decoder] End Of Stream
V/AwesomePlayer(  251): postAudioEOS delayUs (0)
V/AwesomePlayer(  251): onCheckAudioStatus
V/AwesomePlayer(  251): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  251): onStreamDone
V/AwesomePlayer(  251): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  251): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  251): notify(0xb7933198, 2, 0, 0)
V/AudioCache(  251): playback complete - thread will wake up later
V/AwesomePlayer(  251): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  251): notify(0xb7933198, 7, 0, 0)
V/AudioCache(  251): ignored
V/AwesomePlayer(  251): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer(  251): addBatteryData
V/AudioCache(  251): wait - success
V/StagefrightPlayer(  251): reset
V/AwesomePlayer(  251): reset_l()
V/AwesomePlayer(  251): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  251): notify(0xb7933198, 8, 0, 0)
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
V/MediaPlayer( 4442): decode(73, 37491572, 52024)
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
V/AudioCache(  251): notify(0xb7935fc0, 8, 0, 0)
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
V/AudioCache(  251): notify(0xb7935fc0, 200, 973, 0)
V/AudioCache(  251): ignored
V/AwesomePlayer(  251): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  251): notify(0xb7935fc0, 5, 0, 0)
V/AudioCache(  251): ignored
V/AwesomePlayer(  251): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  251): notify(0xb7935fc0, 1, 0, 0)
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
V/AudioCache(  251): notify(0xb7935fc0, 6, 0, 0)
V/AudioCache(  251): ignored
V/AwesomePlayer(  251): addBatteryData
V/MediaPlayerService(  251): wait for playback complete
V/ApplicationPolicy(  761): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
D/CustomFrequencyManagerService(  761): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 761  pkgName : ACTIVITY_RESUME_BOOSTER@5
W/ActivityManager(  761): mDVFSHelper.acquire()
I/SELinux ( 4558): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 4558):  
D/dalvikvm(  249): GC_EXPLICIT freed 45K, 51% free 9510K/19088K, paused 2ms+2ms, total 30ms
D/dalvikvm(  249): GC_EXPLICIT freed <1K, 51% free 9510K/19088K, paused 2ms+2ms, total 19ms
D/LockPatternUtils( 1069): isPcwEnable = null
I/SELinux ( 4558): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 4558):  
I/SELinux ( 4558):  
I/SELinux ( 4558): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 4558): [DEBUG] seapp_context_lookup: seinfoCategory = default
E/dalvikvm( 4558): >>>>> Normal User
E/dalvikvm( 4558): >>>>> com.test.thalitest [ userId:0 | appId:10179 ]
E/SELinux ( 4558): [DEBUG] seapp_context_lookup: seinfoCategory = default
D/AndroidRuntime( 4469): Shutting down VM
I/OMXCodec(  251): [OMX.google.vorbis.decoder] End Of Stream
D/dalvikvm( 4469): GC_CONCURRENT freed 97K, 13% free 717K/816K, paused 1ms+1ms, total 3ms
V/AwesomePlayer(  251): postAudioEOS delayUs (0)
V/AwesomePlayer(  251): onCheckAudioStatus
V/AwesomePlayer(  251): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  251): onStreamDone
V/AwesomePlayer(  251): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  251): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  251): notify(0xb7935fc0, 2, 0, 0)
V/AudioCache(  251): playback complete - thread will wake up later
V/AwesomePlayer(  251): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  251): notify(0xb7935fc0, 7, 0, 0)
V/AudioCache(  251): ignored
V/AwesomePlayer(  251): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer(  251): addBatteryData
V/AudioCache(  251): wait - success
V/StagefrightPlayer(  251): reset
V/AwesomePlayer(  251): reset_l()
V/AwesomePlayer(  251): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  251): notify(0xb7935fc0, 8, 0, 0)
V/AudioCache(  251): ignored
V/AwesomePlayer(  251): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  251): mAudioTrackVector clear
I/OMXCodec(  251): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec(  251): [OMX.google.vorbis.decoder] stop() sendCommand(0x42, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec(  251): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
I/OMXCodec(  251): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/OMX     (  251): instance freeNode
D/dalvikvm(  249): GC_EXPLICIT freed <1K, 51% free 9510K/19088K, paused 2ms+5ms, total 25ms
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
V/MediaPlayer( 4442): decode(74, 33969800, 9226)
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
D/TimaKeyStoreProvider( 4558): in addTimaSignatureService
V/AwesomePlayer(  251): reset_l()
V/AwesomePlayer(  251): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  251): notify(0xb7937b38, 8, 0, 0)
V/AudioCache(  251): ignored
V/AwesomePlayer(  251): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  251): mAudioTrackVector clear
V/AwesomePlayer(  251): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  251): mSecMediaClock clear
D/TimaKeyStoreProvider( 4558): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 4558): Added TimaKesytore provider
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
V/AudioCache(  251): notify(0xb7937b38, 200, 973, 0)
V/AudioCache(  251): ignored
V/AwesomePlayer(  251): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  251): notify(0xb7937b38, 5, 0, 0)
V/AudioCache(  251): ignored
V/AwesomePlayer(  251): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  251): notify(0xb7937b38, 1, 0, 0)
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
W/ContextImpl(  761): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
I/AudioPlayer(  251):  Audioplayer kKeyAudioPCMFormat:1, 2, 0
I/AudioPlayer(  251):  Audioplayer kKeyAudioPCMFormat read fail(2, 1)
V/AudioCache(  251): open(44100, 2, 0x0, 1, 4)
V/AwesomePlayer(  251): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache(  251): notify(0xb7937b38, 6, 0, 0)
V/AudioCache(  251): ignored
V/AwesomePlayer(  251): addBatteryData
V/MediaPlayerService(  251): wait for playback complete
D/LockPatternUtils( 1069): isPcwEnable = null
I/OMXCodec(  251): [OMX.google.vorbis.decoder] End Of Stream
V/AwesomePlayer(  251): postAudioEOS delayUs (0)
V/AwesomePlayer(  251): onCheckAudioStatus
V/AwesomePlayer(  251): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  251): onStreamDone
V/AwesomePlayer(  251): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  251): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  251): notify(0xb7937b38, 2, 0, 0)
V/AudioCache(  251): playback complete - thread will wake up later
V/AwesomePlayer(  251): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  251): notify(0xb7937b38, 7, 0, 0)
V/AudioCache(  251): ignored
V/AwesomePlayer(  251): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer(  251): addBatteryData
V/AudioCache(  251): wait - success
V/StagefrightPlayer(  251): reset
V/AwesomePlayer(  251): reset_l()
V/AwesomePlayer(  251): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  251): notify(0xb7937b38, 8, 0, 0)
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
V/MediaPlayer( 4442): decode(75, 30402580, 4509)
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
V/AudioCache(  251): notify(0xb791e260, 8, 0, 0)
V/AudioCache(  251): ignored
V/AwesomePlayer(  251): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  251): mAudioTrackVector clear
V/AwesomePlayer(  251): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  251): mSecMediaClock clear
I/SurfaceFlinger(  248): id=14 Removed CatteryCove (8/12)
I/SurfaceFlinger(  248): id=14 Removed CatteryCove (-2/12)
D/KeyguardUpdateMonitor( 1069): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1069): handleKeyguardVisibilityChanged(1)
V/AwesomePlayer(  251): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer(  251): mBitrate = -1 bits/sec
V/AwesomePlayer(  251): current audio track index (0) is added to vector
V/AwesomePlayer(  251): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer(  251): AwesomePlayer::setDataSource_l():: This is not a DRM content
V/MediaPlayerService(  251): prepare
V/AwesomePlayer(  251): prepareAsync
V/MediaPlayerService(  251): wait for prepare
D/SurfaceWidgetView( 1252): destroyHardwareResources():1126486904
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
V/AudioCache(  251): notify(0xb791e260, 200, 973, 0)
V/AudioCache(  251): ignored
V/AwesomePlayer(  251): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  251): notify(0xb791e260, 5, 0, 0)
V/AudioCache(  251): ignored
V/AwesomePlayer(  251): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  251): notify(0xb791e260, 1, 0, 0)
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
V/AudioCache(  251): notify(0xb791e260, 6, 0, 0)
V/AudioCache(  251): ignored
V/AwesomePlayer(  251): addBatteryData
V/MediaPlayerService(  251): wait for playback complete
V/AwesomePlayer(  251): postAudioEOS delayUs (0)
V/AwesomePlayer(  251): onCheckAudioStatus
V/AwesomePlayer(  251): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  251): onStreamDone
V/AwesomePlayer(  251): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  251): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  251): notify(0xb791e260, 2, 0, 0)
V/AudioCache(  251): playback complete - thread will wake up later
V/AwesomePlayer(  251): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  251): notify(0xb791e260, 7, 0, 0)
V/AudioCache(  251): ignored
V/AwesomePlayer(  251): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer(  251): addBatteryData
V/AudioCache(  251): wait - success
V/StagefrightPlayer(  251): reset
V/AwesomePlayer(  251): reset_l()
V/AwesomePlayer(  251): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  251): notify(0xb791e260, 8, 0, 0)
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
W/ActivityManager(  761): Permission Denial: getCurrentUser() from pid=4558, uid=10179 requires android.permission.INTERACT_ACROSS_USERS
W/ActivityManager(  761): Permission Denial: getCurrentUser() from pid=4558, uid=10179 requires android.permission.INTERACT_ACROSS_USERS
V/WebViewChromium( 4558): Binding Chromium to the background looper Looper (main, tid 1) {42326848}
I/chromium( 4558): [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserProcessMain( 4558): Initializing chromium process, renderers=0
I/SQLiteSecureOpenHelper( 2025): getWritableDatabase(pwd)
I/SQLiteSecureOpenHelper( 2025): getDatabaseLocked(b,b,pwd)...
,W/chromium( 4558): [WARNING:proxy_service.cc(888)] PAC support disabled because there is no system implementation
,I/SELinux ( 4594): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 4594):  
,I/ActivityManager(  761): Killing 3191:com.sec.android.app.camera/u0a147 (adj 15): empty #43
,I/SELinux ( 4594): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 4594):  
I/SELinux ( 4594):  
,I/SELinux ( 4594): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 4594): [DEBUG] seapp_context_lookup: seinfoCategory = default
E/dalvikvm( 4594): >>>>> Normal User
,E/dalvikvm( 4594): >>>>> com.osp.app.signin [ userId:0 | appId:10043 ]
,E/SELinux ( 4594): [DEBUG] seapp_context_lookup: seinfoCategory = default
,D/TimaKeyStoreProvider( 4594): in addTimaSignatureService
,D/TimaKeyStoreProvider( 4594): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 4594): Added TimaKesytore provider
,E/SMD     (  242): DCD OFF
,I/SA      ( 4594): [SSP] onCreated
,I/SA      ( 4594): [TPM] There is no property file
,I/SA      ( 4594): [SCU] isHaveSA() - false
,I/SA      ( 4594): [TPM] getModelProperty : null
,I/SA      ( 4594): [TPM] getCSCProperty : null
,I/SA      ( 4594): [PMR] Received action : android.intent.action.PACKAGE_ADDED
,I/SA      ( 4594): [DM] init START
,I/SA      ( 4594): [DM] This device is not a Vodafone
I/SA      ( 4594): [DM] getCountryCodeFromCSC : PL
,I/SA      ( 4594): support phone number id : false
I/SA      ( 4594): [DM] init END
,I/SA      ( 4594): [SUR] onReceive log=[SA = 2.0.0117 V = 19 HWD = 1280X720 2.0 dpi = 320  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = kmini3g P = kmini3gxx I = KOT49H M = SM-G800H OKLEFT false DIS KOT49H.G800HXXU1ANK2 PSS = 4.497045606779314  ]
,I/SA      ( 4594): [SUR] onReceive Intent=[ action.PACKAGE_ADDED. package ]
I/ActivityManager(  761): Killing 3288:com.android.email/u0a155 (adj 15): empty #43
V/AlarmManager(  761): waitForAlarm result :4
,V/AlarmManager(  761): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,D/Mms/PackageInstallReceiver( 3818): loadAuthorityPref(): sEnableAuthority = true
,I/IcingCorporaProvider( 2125): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
I/Adreno-EGL( 4558): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 4558): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 4558): Build Date: 03/21/14 Fri
I/Adreno-EGL( 4558): Local Branch: AU200+patches_03212014
I/Adreno-EGL( 4558): Remote Branch: 
I/Adreno-EGL( 4558): Local Patches: 
I/Adreno-EGL( 4558): Reconstruct Branch: 
W/ContextImpl( 2858): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1857 android.content.ContextWrapper.startService:506 android.content.ContextWrapper.startService:506 com.samsung.android.app.assistantmenu.AssistantMenuReceiver.onReceive:153 android.app.ActivityThread.handleReceiver:2698 
I/SecureStorage(  301): [INFO]: SPID(0x00000003)Secure Storage Daemon finished processing with result: 0
I/SecureStorage(  301): [INFO]: SPID(0x00000003)PID: 4464, TID: 4464
I/SurfaceFlinger(  248): id=7 Removed Mauncher (7/11)
I/SurfaceFlinger(  248): id=7 Removed Mauncher (-2/11)
D/KeyguardUpdateMonitor( 1069): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1069): handleKeyguardVisibilityChanged(1)
D/SurfaceWidgetClient$ISurfaceWidgetStub( 1447): [237392/5] Surface widget visibility changed visibility = false on instance = 1
D/Launcher( 1252): onTrimMemory. Level: 20
I/SELinux ( 4613): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 4613):  
D/dalvikvm( 3531): GC_CONCURRENT freed 6652K, 43% free 10979K/19088K, paused 6ms+23ms, total 81ms
I/SELinux ( 4613): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 4613):  
I/SELinux ( 4613):  
I/SELinux ( 4613): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 4613): [DEBUG] seapp_context_lookup: seinfoCategory = samsung
E/dalvikvm( 4613): >>>>> Normal User
E/dalvikvm( 4613): >>>>> com.sec.android.service.cm [ userId:0 | appId:10078 ]
E/SELinux ( 4613): [DEBUG] seapp_context_lookup: seinfoCategory = samsung
I/dalvikvm( 4558): Could not find method android.webkit.CookieManager.setAcceptThirdPartyCookies, referenced from method org.apache.cordova.engine.SystemCookieManager.<init>
W/dalvikvm( 4558): VFY: unable to resolve virtual method 252: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
D/dalvikvm( 4558): VFY: replacing opcode 0x6e at 0x0016
I/dalvikvm( 4558): Could not find method android.webkit.CookieManager.flush, referenced from method org.apache.cordova.engine.SystemCookieManager.flush
W/dalvikvm( 4558): VFY: unable to resolve virtual method 247: Landroid/webkit/CookieManager;.flush ()V
D/dalvikvm( 4558): VFY: replacing opcode 0x6e at 0x0008
D/TimaKeyStoreProvider( 4613): in addTimaSignatureService
D/TimaKeyStoreProvider( 4613): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 4613): Added TimaKesytore provider
I/IcingCorporaProvider( 2125): UpdateCorporaTask done [took 150 ms] updated apps [took 150 ms] 
W/dalvikvm( 4558): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 4558): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
I/dalvikvm( 4558): Could not find method android.webkit.WebViewClient.onReceivedClientCertRequest, referenced from method org.apache.cordova.engine.SystemWebViewClient.onReceivedClientCertRequest
W/dalvikvm( 4558): VFY: unable to resolve virtual method 305: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
D/dalvikvm( 4558): VFY: replacing opcode 0x6f at 0x001a
W/dalvikvm( 4558): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
I/dalvikvm( 4558): Could not find method android.webkit.PermissionRequest.getResources, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onPermissionRequest
W/dalvikvm( 4558): VFY: unable to resolve virtual method 263: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
D/dalvikvm( 4558): VFY: replacing opcode 0x6e at 0x000d
I/dalvikvm( 4558): Could not find method android.webkit.WebChromeClient$FileChooserParams.createIntent, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onShowFileChooser
W/dalvikvm( 4558): VFY: unable to resolve virtual method 268: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
D/dalvikvm( 4558): VFY: replacing opcode 0x6e at 0x0000
D/SystemWebViewEngine( 4558): CordovaWebView is running on device made by: samsung
I/SecureStorage( 4464): [INFO]: SPID(0x00000000)Processing data has been completed
I/SecureStorage( 4464): [INFO]: SPID(0x00000000)WARNING! Failed to find SecureStorageExceptionJNI!..
I/SQLiteSecureOpenHelper( 4464): getWritableDatabase(pwd)
I/SQLiteSecureOpenHelper( 4464): getDatabaseLocked(b,b,pwd)...
I/SQLiteSecureOpenHelper( 4464): Open platform.db in secure mode
D/CapabilityManagerService New( 4613): Receiver Broadcast:android.intent.action.PACKAGE_ADDED
W/ActivityManager(  761): Permission Denial: getCurrentUser() from pid=4613, uid=10078 requires android.permission.INTERACT_ACROSS_USERS
I/SELinux ( 4630): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 4630):  
I/ActivityManager(  761): Killing 3284:com.samsung.android.provider.shootingmodeprovider/u0a162 (adj 15): empty #43
I/SurfaceFlinger(  248): id=17 createSurf (1x1),1 flag=404, NainActivit
D/KeyguardUpdateMonitor( 1069): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1069): handleKeyguardVisibilityChanged(1)
I/SELinux ( 4630): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 4630):  
I/SELinux ( 4630):  
I/SELinux ( 4630): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 4630): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 4630): >>>>> Normal User
E/dalvikvm( 4630): >>>>> com.google.android.apps.docs [ userId:0 | appId:10090 ]
E/SELinux ( 4630): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
D/KeyguardUpdateMonitor( 1069): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1069): handleKeyguardVisibilityChanged(1)
I/HWUI    ( 4558): EGLImpl-HWUI Protected EGL context created
D/TimaKeyStoreProvider( 4630): in addTimaSignatureService
D/TimaKeyStoreProvider( 4630): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 4630): Added TimaKesytore provider
D/OpenGLRenderer( 4558): Enabling debug mode 0
D/OpenGLRenderer( 4558): GL error from OpenGLRenderer: 0x502
E/OpenGLRenderer( 4558):   GL_INVALID_OPERATION
D/KeyguardUpdateMonitor( 1069): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1069): handleKeyguardVisibilityChanged(1)
I/SQLiteSecureOpenHelper( 4464): ...getDatabaseLocked(b,b,pwd)
D/SQLiteSecureOpenHelper( 4464): ...getDatabaseLocked(b,b,pwd)
D/CustomFrequencyManagerService(  761): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 761  tag : ACTIVITY_RESUME_BOOSTER@5
W/ActivityManager(  761): mDVFSHelper.release()
D/CustomFrequencyManagerService(  761): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 761  pkgName : ACTIVITY_RESUME_BOOSTER@9
D/KeyguardUpdateMonitor( 1069): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1069): handleKeyguardVisibilityChanged(1)
I/ActivityManager(  761): Killing 3314:com.sec.modem.settings/1000 (adj 15): empty #43
W/ActivityManager(  761): Permission Denial: getCurrentUser() from pid=4630, uid=10090 requires android.permission.INTERACT_ACROSS_USERS
D/Finsky  ( 3531): [349] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 3531): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,D/JsMessageQueue( 4558): Set native->JS mode to OnlineEventsBridgeMode
,D/dalvikvm( 4558): Trying to load lib /data/app-lib/com.test.thalitest-9/libjxcore.so 0x4264d550
,D/dalvikvm( 4558): Added shared lib /data/app-lib/com.test.thalitest-9/libjxcore.so 0x4264d550
,D/jxcore_app_log( 4558): JniHelper::setJavaVM(0x4176a528), pthread_self() = 2033768280
,I/chromium( 4558): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot call method 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,W/GAV2    ( 4630): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,I/SELinux ( 4663): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 4663):  
,I/SELinux ( 4663): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 4663):  
I/SELinux ( 4663):  
I/SELinux ( 4663): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 4663): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 4663): >>>>> Normal User
,E/dalvikvm( 4663): >>>>> com.samsung.android.app.watchmanagerstub [ userId:0 | appId:10100 ]
,E/SELinux ( 4663): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 4663): in addTimaSignatureService
,D/TimaKeyStoreProvider( 4663): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 4663): Added TimaKesytore provider
,D/PackageIntentReceiver( 4663): ACTION_PACKAGE_ADDED
,D/PackageIntentReceiver( 4663): Not GearManger package! 
,I/SELinux ( 4676): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 4676):  
I/ActivityManager(  761): Killing 1335:com.sec.android.provider.badge/u0a72 (adj 15): empty #43
,I/SELinux ( 4676): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 4676):  
I/SELinux ( 4676):  
,I/SELinux ( 4676): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 4676): [DEBUG] seapp_context_lookup: seinfoCategory = release
E/dalvikvm( 4676): >>>>> Normal User
E/dalvikvm( 4676): >>>>> com.samsung.android.magazine.service [ userId:0 | appId:10106 ]
,E/SELinux ( 4676): [DEBUG] seapp_context_lookup: seinfoCategory = release
D/dalvikvm( 4558): GC_CONCURRENT freed 4952K, 34% free 12738K/19088K, paused 3ms+3ms, total 37ms
,D/dalvikvm( 4558): WAIT_FOR_CONCURRENT_GC blocked 23ms
,D/dalvikvm( 4558): WAIT_FOR_CONCURRENT_GC blocked 17ms
,D/TimaKeyStoreProvider( 4676): in addTimaSignatureService
,D/TimaKeyStoreProvider( 4676): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 4676): Added TimaKesytore provider
,D/MagazineService Version( 4676): Magazine-Channel: 13
,D/MagazineService Version( 4676): Magazine-Provider: 13
,D/MagazineService Version( 4676): Magazine-Administrator: 11
,D/HeadlinesChannelApplication( 4676): [onCreate]
,D/MagazineService::MagazineBroadcastReceiver( 4676): [onReceive] android.intent.action.PACKAGE_ADDED com.test.thalitest
W/ActivityManager(  761): Permission Denial: getCurrentUser() from pid=4676, uid=10106 requires android.permission.INTERACT_ACROSS_USERS
,I/MagazineService::MagazineService( 4676): [onHandleIntent] ACTION_PACKAGE_INSTALLED
,I/SELinux ( 4689): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 4689):  
,D/MagazineService::MagazineService( 4676): [onHandleIntent] Send broadcast to (com.test.thalitest).
I/ActivityManager(  761): Killing 3339:tv.peel.smartremote/u0a163 (adj 15): empty #43
,W/GAV2    ( 4630): Thread[main,5,main]: dispatch call queued.  Need to call GAServiceManager.getInstance().initialize().
I/ActivityManager(  761): Killing 3361:org.simalliance.openmobileapi.service/1101 (adj 15): empty #43
,I/SELinux ( 4689): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 4689):  
I/SELinux ( 4689):  
,I/SELinux ( 4689): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 4689): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 4689): >>>>> Normal User
,E/dalvikvm( 4689): >>>>> com.samsung.helphub [ userId:0 | appId:1000 ]
,E/SELinux ( 4689): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 4689): in addTimaSignatureService
,D/TimaKeyStoreProvider( 4689): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 4689): Added TimaKesytore provider
,D/CustomFrequencyManagerService(  761): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 761  tag : ACTIVITY_RESUME_BOOSTER@9
,I/SELinux ( 4703): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 4703):  
I/ActivityManager(  761): Killing 3417:com.sec.android.app.taskmanager/u0a166 (adj 15): empty #43
,I/SELinux ( 4703): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 4703):  
I/SELinux ( 4703):  
,I/SELinux ( 4703): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 4703): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 4703): >>>>> Normal User
,E/dalvikvm( 4703): >>>>> com.sec.kidsplat.installer [ userId:0 | appId:10158 ]
,E/SELinux ( 4703): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 4703): in addTimaSignatureService
,D/TimaKeyStoreProvider( 4703): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 4703): Added TimaKesytore provider
,W/ActivityManager(  761): Permission Denial: getCurrentUser() from pid=4703, uid=10158 requires android.permission.INTERACT_ACROSS_USERS
,D/KidsPlatformStub( 4703): Package not found : com.sec.android.app.kidshome
,I/SELinux ( 4715): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 4715):  
I/ActivityManager(  761): Killing 3432:com.samsung.android.service.travel/u0a169 (adj 15): empty #43
,I/SELinux ( 4715): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 4715):  
I/SELinux ( 4715):  
,I/SELinux ( 4715): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 4715): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 4715): >>>>> Normal User
E/dalvikvm( 4715): >>>>> com.samsung.android.provider.shootingmodeprovider [ userId:0 | appId:10162 ]
,E/SELinux ( 4715): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/dalvikvm( 4558): GC_CONCURRENT freed 4639K, 28% free 16273K/22328K, paused 2ms+5ms, total 43ms
,D/dalvikvm( 4558): WAIT_FOR_CONCURRENT_GC blocked 21ms
,D/TimaKeyStoreProvider( 4715): in addTimaSignatureService
,D/dalvikvm( 4558): WAIT_FOR_CONCURRENT_GC blocked 24ms
,D/TimaKeyStoreProvider( 4715): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 4715): Added TimaKesytore provider
,I/SELinux ( 4727): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 4727):  
I/ActivityManager(  761): Killing 3456:com.google.android.youtube/u0a175 (adj 15): empty #43
,I/SELinux ( 4727): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 4727):  
I/SELinux ( 4727):  
,I/SELinux ( 4727): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 4727): [DEBUG] seapp_context_lookup: seinfoCategory = samsung
E/dalvikvm( 4727): >>>>> Normal User
,E/dalvikvm( 4727): >>>>> com.sec.android.app.samsungapps [ userId:0 | appId:10040 ]
,E/SELinux ( 4727): [DEBUG] seapp_context_lookup: seinfoCategory = samsung
,D/TimaKeyStoreProvider( 4727): in addTimaSignatureService
,D/TimaKeyStoreProvider( 4727): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 4727): Added TimaKesytore provider
,I/ActivityManager(  761): Killing 3658:com.sec.android.widgetapp.activeapplicationwidget/u0a152 (adj 15): empty #43
,D/Finsky  ( 3531): [1] ExternalReferrer.access$200: Package state data is missing for com.test.thalitest
,D/PackageBroadcastService( 1758): Received broadcast action=android.intent.action.PACKAGE_ADDED and uri=com.test.thalitest
D/ChimeraCfgMgr( 1758): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 1758): Loading module APK com.google.android.play.games
I/dalvikvm( 1758): Could not find method android.app.admin.DevicePolicyManager.getProfileOwner, referenced from method com.google.android.gms.auth.WorkAccountAuthenticatorInitializer.a
,W/dalvikvm( 1758): VFY: unable to resolve virtual method 174: Landroid/app/admin/DevicePolicyManager;.getProfileOwner ()Landroid/content/ComponentName;
,D/dalvikvm( 1758): VFY: replacing opcode 0x6e at 0x0053
,I/dalvikvm( 1758): Failed resolving Lcom/google/android/gms/common/permission/PermissionUtils$1; interface 96 'Landroid/content/pm/PackageManager$OnPermissionsChangedListener;'
W/dalvikvm( 1758): Link of class 'Lcom/google/android/gms/common/permission/PermissionUtils$1;' failed
,E/dalvikvm( 1758): Could not find class 'com.google.android.gms.common.permission.PermissionUtils$1', referenced from method com.google.android.gms.chimera.GmsModuleInitializer.initializeModuleV0
W/dalvikvm( 1758): VFY: unable to resolve new-instance 2374 (Lcom/google/android/gms/common/permission/PermissionUtils$1;) in Lcom/google/android/gms/chimera/GmsModuleInitializer;
,D/dalvikvm( 1758): VFY: replacing opcode 0x22 at 0x001a
I/dalvikvm( 1758): Failed resolving Lcom/google/android/gms/common/permission/PermissionUtils$1; interface 96 'Landroid/content/pm/PackageManager$OnPermissionsChangedListener;'
,W/dalvikvm( 1758): Link of class 'Lcom/google/android/gms/common/permission/PermissionUtils$1;' failed
,D/dalvikvm( 1758): DexOpt: unable to opt direct call 0x338d at 0x1c in Lcom/google/android/gms/chimera/GmsModuleInitializer;.initializeModuleV0
,D/ChimeraCfgMgr( 1758): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 1758): Module APK com.google.android.play.games already loaded
,D/ChimeraCfgMgr( 1758): Loading module com.google.android.gms.gass from APK com.google.android.gms
,D/dalvikvm( 4558): GC_FOR_ALLOC freed 5165K, 31% free 17272K/25000K, paused 43ms, total 43ms
,D/AsyncTaskServiceImpl( 1758): Submit a task: k
,I/dalvikvm-heap( 4558): Grow heap (frag case) to 22.576MB for 2459024-byte allocation
,D/ChimeraCfgMgr( 1758): Loading module com.google.android.gms.gass from APK com.google.android.gms
,D/ChimeraCfgMgr( 1758): Loading module com.google.android.gms.vision from APK com.google.android.gms
W/BaseAppContext( 1758): Using Auth Proxy for data requests.
,W/BaseAppContext( 1758): Using Auth Proxy for data requests.
,D/k       ( 1758): Processing package: com.test.thalitest
,D/GassUtils( 1758): Found app info for package com.test.thalitest:18. Hash: 4eebbbb84f07ed56a3e96e5e8f9d6abddaaf154fffa2a65432a1006e0fa38f32
,D/k       ( 1758): Found info for package com.test.thalitest in db.
,W/BaseAppContext( 1758): Using Auth Proxy for data requests.
,W/BaseAppContext( 1758): Using Auth Proxy for data requests.
,W/BaseAppContext( 1758): Using Auth Proxy for data requests.
,W/BaseAppContext( 1758): Using Auth Proxy for data requests.
,W/BaseAppContext( 1758): Using Auth Proxy for data requests.
,D/dalvikvm(  761): GC_EXPLICIT freed 2273K, 59% free 23456K/57084K, paused 6ms+16ms, total 146ms
,W/dalvikvm( 1758): VFY: unable to find class referenced in signature (Landroid/app/SharedElementCallback;)
,I/dalvikvm( 1758): Could not find method android.app.Activity.setEnterSharedElementCallback, referenced from method android.support.v4.app.w.setEnterSharedElementCallback
W/dalvikvm( 1758): VFY: unable to resolve virtual method 53: Landroid/app/Activity;.setEnterSharedElementCallback (Landroid/app/SharedElementCallback;)V
,D/dalvikvm( 1758): VFY: replacing opcode 0x6e at 0x000e
W/dalvikvm( 1758): VFY: unable to find class referenced in signature (Landroid/app/SharedElementCallback;)
I/dalvikvm( 1758): Could not find method android.app.Activity.setExitSharedElementCallback, referenced from method android.support.v4.app.w.setExitSharedElementCallback
W/dalvikvm( 1758): VFY: unable to resolve virtual method 54: Landroid/app/Activity;.setExitSharedElementCallback (Landroid/app/SharedElementCallback;)V
D/dalvikvm( 1758): VFY: replacing opcode 0x6e at 0x000e
I/dalvikvm( 1758): Could not find method android.app.Activity.finishAfterTransition, referenced from method android.support.v4.app.w.supportFinishAfterTransition
W/dalvikvm( 1758): VFY: unable to resolve virtual method 31: Landroid/app/Activity;.finishAfterTransition ()V
D/dalvikvm( 1758): VFY: replacing opcode 0x6e at 0x0006
I/dalvikvm( 1758): Could not find method android.app.Activity.postponeEnterTransition, referenced from method android.support.v4.app.w.supportPostponeEnterTransition
W/dalvikvm( 1758): VFY: unable to resolve virtual method 49: Landroid/app/Activity;.postponeEnterTransition ()V
D/dalvikvm( 1758): VFY: replacing opcode 0x6e at 0x0006
I/dalvikvm( 1758): Could not find method android.app.Activity.startPostponedEnterTransition, referenced from method android.support.v4.app.w.supportStartPostponedEnterTransition
W/dalvikvm( 1758): VFY: unable to resolve virtual method 61: Landroid/app/Activity;.startPostponedEnterTransition ()V
,D/dalvikvm( 1758): VFY: replacing opcode 0x6e at 0x0006
,I/PeopleDatabaseHelper( 1758): cleanUpNonGplusAccounts done.
,D/dalvikvm( 4558): GC_FOR_ALLOC freed 3741K, 35% free 17980K/27404K, paused 34ms, total 37ms
,W/dalvikvm( 1758): VFY: unable to find class referenced in signature (Landroid/util/Size;)
,D/ChimeraCfgMgr( 1758): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 1758): Module APK com.google.android.play.games already loaded
,D/dalvikvm( 4558): GC_FOR_ALLOC freed 1186K, 35% free 17890K/27404K, paused 31ms, total 32ms
,E/SMD     (  242): DCD OFF
,D/dalvikvm( 4558): GC_FOR_ALLOC freed 4545K, 39% free 19213K/31008K, paused 34ms, total 35ms
,W/jxcore-log( 4558): Initializing JXcore engine
,W/jxcore-log( 4558): JXcore engine is ready
,W/jxcore-log( 4558): Starting JXcore engine
,W/jxcore-log( 4558): Platform android
W/jxcore-log( 4558): 
,W/jxcore-log( 4558): Process ARCH arm
W/jxcore-log( 4558): 
,I/Icing   ( 1758): Indexing 49CA7E3A917E607C6D98AA15891295369CED2106 from com.google.android.gms
,D/dalvikvm( 1758): GC_CONCURRENT freed 1844K, 38% free 11858K/19088K, paused 4ms+6ms, total 48ms
,I/Icing   ( 1758): Indexing done 49CA7E3A917E607C6D98AA15891295369CED2106
,I/jxcore-log( 4558): JXcore Cordova bridge is ready!
I/jxcore-log( 4558): 
,W/jxcore-log( 4558): JXcore engine is started
,I/jxcore-log( 4558): Toggling radios to true
I/jxcore-log( 4558): 
,W/ActivityManager(  761): Permission Denial: getCurrentUser() from pid=4558, uid=10179 requires android.permission.INTERACT_ACROSS_USERS
,W/BluetoothManagerService(  761): Failed getting userId using ActivityManagerNative
W/BluetoothManagerService(  761): java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=4558, uid=10179 requires android.permission.INTERACT_ACROSS_USERS
W/BluetoothManagerService(  761): 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:20710)
W/BluetoothManagerService(  761): 	at com.android.server.BluetoothManagerService.enable(BluetoothManagerService.java:620)
W/BluetoothManagerService(  761): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:98)
W/BluetoothManagerService(  761): 	at android.os.Binder.execTransact(Binder.java:404)
W/BluetoothManagerService(  761): 	at dalvik.system.NativeStart.run(Native Method)
E/DevicePolicyManagerService(  761): getAllowBluetoothMode - value retunrs : 2
,D/BluetoothManagerService(  761): foregroundUser: 0
,E/BluetoothManagerService(  761): Package is exist.
,D/BluetoothAdapterState( 3171): CURRENT_STATE=OFF, MSG = USER_TURN_ON
,I/BluetoothAdapterState( 3171): Bluetooth adapter state changed: 10-> 11
D/BluetoothAdapterService( 3171): Bluetooth PBAP supproted is true
,D/BluetoothAdapterService( 3171): updateAdapterState state is 11
,D/BluetoothAdapterService( 3171): Broadcasting updateAdapterState() to 1 receivers.
D/BluetoothAdapterService( 3171): Autoconnection is available 
,D/BluetoothAdapterService( 3171): updateAdapterState prevState = 10newState = 11
D/BtConfig.SecureMode( 3171): isSecureModeOn:false
,D/BtSettings.ProfileConfig( 3171): getProfileSaveSetting: com.android.bluetooth.gatt.GattService
,W/BluetoothAdapterService( 3171): isProfileEnabled(): profile com.android.bluetooth.gatt.GattService, state= 12
,D/BtSettings.ProfileConfig( 3171): getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
,W/BluetoothAdapterService( 3171): isProfileEnabled(): profile not found com.android.bluetooth.hfp.HeadsetService
,D/BtSettings.ProfileConfig( 3171): getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
,I/WifiManager( 4558): packageName : com.test.thalitest
I/WifiManager( 4558): setWifiEnabled : true
,I/WifiService(  761): setWifiEnabled: true pid=4558, uid=10179
W/BluetoothAdapterService( 3171): isProfileEnabled(): profile not found com.android.bluetooth.a2dp.A2dpService
,D/BtSettings.ProfileConfig( 3171): getProfileSaveSetting: com.android.bluetooth.hid.HidService
,W/BluetoothAdapterService( 3171): isProfileEnabled(): profile not found com.android.bluetooth.hid.HidService
,D/BtSettings.ProfileConfig( 3171): getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
,W/WifiService(  761): Failed getting userId using ActivityManagerNative
W/WifiService(  761): java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=4558, uid=10179 requires android.permission.INTERACT_ACROSS_USERS
W/WifiService(  761): 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:20710)
W/WifiService(  761): 	at com.android.server.wifi.WifiService.setWifiEnabled(WifiService.java:2348)
W/WifiService(  761): 	at com.android.server.wifi.WifiService.setWifiEnabled(WifiService.java:2336)
W/WifiService(  761): 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:178)
W/WifiService(  761): 	at android.os.Binder.execTransact(Binder.java:404)
W/WifiService(  761): 	at dalvik.system.NativeStart.run(Native Method)
W/ActivityManager(  761): Permission Denial: getCurrentUser() from pid=4558, uid=10179 requires android.permission.INTERACT_ACROSS_USERS
W/InputMethodManagerService(  761): InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
,I/InputMethodManagerService(  761): [BT Setting State] State =11
D/PhoneApp( 1241): mReceiver: BluetoothAdapter.ACTION_STATE_CHANGED: 11
I/QuickConnect[1.1][2] ( 3142): BluetoothHelper.ACTION_STATE_CHANGED - STATE_TURNING_ON
W/BluetoothAdapterService( 3171): isProfileEnabled(): profile not found com.android.bluetooth.hdp.HealthService
D/BtSettings.ProfileConfig( 3171): getProfileSaveSetting: com.android.bluetooth.pan.PanService
,W/BluetoothAdapterService( 3171): isProfileEnabled(): profile not found com.android.bluetooth.pan.PanService
,D/BtSettings.ProfileConfig( 3171): getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
,W/BluetoothAdapterService( 3171): isProfileEnabled(): profile not found com.android.bluetooth.map.BluetoothMapService
W/BluetoothAdapterService( 3171): Unable to stop service com.android.bluetooth.gatt.GattService. Invalid state: 12
W/BluetoothAdapterService( 3171): check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.hfp.HeadsetService
D/BtSettings.ProfileConfig( 3171): getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
,I/WifiService(  761): disconnect: pid=4558, uid=10179
,W/BluetoothAdapterService( 3171): Not skipping com.android.bluetooth.hfp.HeadsetService
E/WifiHW  (  761): ##################### set firmware type 0 #####################
,I/jxcore-log( 4558): Radios toggled
I/jxcore-log( 4558): 
,I/jxcore-log( 4558): My device name is: samsung-SM-G800H
I/jxcore-log( 4558): 
,W/BluetoothAdapterService( 3171): check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.a2dp.A2dpService
,D/BtSettings.ProfileConfig( 3171): getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
,W/BluetoothAdapterService( 3171): Not skipping com.android.bluetooth.a2dp.A2dpService
,W/BluetoothAdapterService( 3171): check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.hid.HidService
D/BtSettings.ProfileConfig( 3171): getProfileSaveSetting: com.android.bluetooth.hid.HidService
,W/BluetoothAdapterService( 3171): Not skipping com.android.bluetooth.hid.HidService
,W/BluetoothAdapterService( 3171): check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.hdp.HealthService
D/BtSettings.ProfileConfig( 3171): getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
,W/BluetoothAdapterService( 3171): Not skipping com.android.bluetooth.hdp.HealthService
,W/BluetoothAdapterService( 3171): check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.pan.PanService
,D/BtSettings.ProfileConfig( 3171): getProfileSaveSetting: com.android.bluetooth.pan.PanService
,W/BluetoothAdapterService( 3171): Not skipping com.android.bluetooth.pan.PanService
,D/HeadsetService( 3171): Received start request. Starting profile...
I/BluetoothHeadsetServiceJni( 3171): classInitNative: succeeds
D/HeadsetStateMachine( 3171): Version 1.6
,D/HeadsetStateMachine( 3171): make
,D/QuickConnect[1.1][2] ( 3142): HeadsetProfile.onServiceConnected - Bluetooth service connected
,E/HeadsetStateMachine( 3171): # of Max HF connection is 2
,W/BluetoothAdapterService( 3171): check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.map.BluetoothMapService
,D/BtSettings.ProfileConfig( 3171): getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
,W/BluetoothAdapterService( 3171): Not skipping com.android.bluetooth.map.BluetoothMapService
,I/BluetoothAdapterState( 3171): Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
,I/bluedroid( 3171): get_profile_interface handsfree
,D/BluetoothAtMessage( 3171): createCMTIContentObservers
,D/HeadsetStateMachine( 3171): Enter Disconnected: -2
,E/HeadsetStateMachine( 3171): set to mRemoteBrsf = 0
,D/HeadsetStateMachine( 3171): map size, before remove : 0
D/HeadsetStateMachine( 3171): map size, after remove: 0
,D/HeadsetStateMachine( 3171): mNextConnectingDevice : null
D/BluetoothA2dp(  761): Proxy object connected
,D/BluetoothA2dp( 3142): Proxy object connected
,D/QuickConnect[1.1][2] ( 3142): A2dpProfile.onServiceConnected - Bluetooth service connected
D/A2dpService( 3171): Received start request. Starting profile...
,I/BluetoothA2dpServiceJni( 3171): classInitNative: succeeds
,D/A2dpStateMachine( 3171): make
,I/bluedroid( 3171): get_profile_interface a2dp
,I/GKI_LINUX( 3171): gki_task_entry: gki_task_entry task_id=2 [A2DP-MEDIA] starting
,D/BluetoothA2dp( 2025): Proxy object connected
,I/BluetoothAvrcpServiceJni( 3171): classInitNative: succeeds
,I/bluedroid( 3171): get_profile_interface avrcp
,D/A2dpStateMachine( 3171): Enter Disconnected: -2
,D/MediaFocusControl(  761): >>> registerRemoteControlDisplay
,E/MediaFocusControl(  761): Error updating focussed RCC to RCD 
E/MediaFocusControl(  761): java.util.EmptyStackException
E/MediaFocusControl(  761): 	at java.util.Stack.peek(Stack.java:57)
E/MediaFocusControl(  761): 	at android.media.MediaFocusControl.registerRemoteControlDisplay_int(MediaFocusControl.java:2308)
E/MediaFocusControl(  761): 	at android.media.MediaFocusControl.registerRemoteControlDisplay(MediaFocusControl.java:250)
E/MediaFocusControl(  761): 	at android.media.AudioService.registerRemoteControlDisplay(AudioService.java:6425)
E/MediaFocusControl(  761): 	at android.media.IAudioService$Stub.onTransact(IAudioService.java:593)
E/MediaFocusControl(  761): 	at android.os.Binder.execTransact(Binder.java:404)
E/MediaFocusControl(  761): 	at dalvik.system.NativeStart.run(Native Method)
,I/BluetoothHidServiceJni( 3171): classInitNative: succeeds
,D/BluetoothInputDevice( 3142): Proxy object connected
,D/QuickConnect[1.1][2] ( 3142): HidProfile.onServiceConnected - Bluetooth service connected
D/HidService( 3171): Received start request. Starting profile...
I/bluedroid( 3171): get_profile_interface hidhost
,D/HidService( 3171): setHidService(): set to: null
,I/BluetoothHealthServiceJni( 3171): classInitNative: succeeds
,D/HealthService( 3171): Received start request. Starting profile...
,I/bluedroid( 3171): get_profile_interface health
,I/BluetoothPanServiceJni( 3171): classInitNative(L105): succeeds
,D/BluetoothPan(  761): BluetoothPAN Proxy object connected
,D/PanService( 3171): Received start request. Starting profile...
D/BluetoothPanServiceJni( 3171): initializeNative(L110): pan
,I/bluedroid( 3171): get_profile_interface pan
,D/BluetoothTethering(  761): got CMD_CHANNEL_HALF_CONNECTED
,D/BluetoothMapService( 3171): Received start request. Starting profile...
,D/BluetoothNotiBroadcastReceiver( 1307): onReceive
,W/BluetoothMapMasInstance( 3171): mAccount : null
,D/HeadsetStateMachine( 3171): Try to query the phonestate on bind
,D/BluetoothPhoneService( 1241): handleMessage: 4
V/BluetoothPhoneService( 1241): Call state Converted2: IDLE/IDLE -> 6
,D/HeadsetStateMachine( 3171): Proxy object connected
,W/BluetoothHeadset( 1241): Proxy not attached to service
,D/HeadsetPhoneState( 3171): sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=0
D/HeadsetStateMachine( 3171): Disconnected process message: 11
D/HeadsetPhoneState( 3171): sendDeviceDataStateChanged
,D/HeadsetStateMachine( 3171): Disconnected process message: 20
,D/HeadsetPhoneState( 3171): Signal level : previous=0 curr=0
D/BluetoothAdapterService( 3171): Profile still not running:com.android.bluetooth.hdp.HealthService
V/HeadsetService( 3171): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3171): Disconnected process message: 10
,D/HeadsetPhoneState( 3171): sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
,D/HeadsetStateMachine( 3171): Disconnected process message: 11
D/BluetoothAdapterService( 3171): Profile still not running:com.android.bluetooth.hdp.HealthService
D/BluetoothAdapterService( 3171): Profile still not running:com.android.bluetooth.hdp.HealthService
,D/BluetoothAdapterService( 3171): Profile still not running:com.android.bluetooth.map.BluetoothMapService
,D/BluetoothAdapterService( 3171): Profile still not running:com.android.bluetooth.map.BluetoothMapService
,D/BluetoothAdapterState( 3171): CURRENT_STATE=PENDING, MSG = STARTED, isTurningOn=true, isTurningOff=false
,I/bluedroid( 3171): enable
,D/GKI_LINUX( 3171): acquire_my_wake_lock(), g_wake_lock_fd:-1, g_wake_unlock_fd:-1, wake_lock_acquired:0
E/bt-btif ( 3171): Calling BTA_HhEnable
,E/bt-btif ( 3171): btif_storage_get_adapter_property service_mask:0x140040
E/BluetoothServiceJni( 3171): populateRssiValuesNative
I/bluedroid( 3171): getModelRssiValues
,E/BluetoothServiceJni( 3171): model_rssi_values_callback: low = -70, mid = -60, high = 127
,D/AuthorizationBluetoothService( 1312): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,E/BluetoothRemoteDevices( 3171): devicePropertyChangedCallback: bdDevice: 08:EC:A9:50:75:41, value is empty for type: 10
,D/BtConfig.SecureMode( 3171): isSecureModeOn:false
,E/BluetoothRemoteDevices( 3171): devicePropertyChangedCallback: bdDevice: 08:EC:A9:50:75:41, value is empty for type: 241
,E/BluetoothRemoteDevices( 3171): devicePropertyChangedCallback: bdDevice: 80:01:84:8A:B3:68, value is empty for type: 10
,D/BtConfig.SecureMode( 3171): isSecureModeOn:false
,E/BluetoothRemoteDevices( 3171): devicePropertyChangedCallback: bdDevice: 80:01:84:8A:B3:68, value is empty for type: 241
,E/BluetoothRemoteDevices( 3171): devicePropertyChangedCallback: bdDevice: 44:80:EB:7B:5A:05, value is empty for type: 10
,D/BtConfig.SecureMode( 3171): isSecureModeOn:false
,E/BluetoothRemoteDevices( 3171): devicePropertyChangedCallback: bdDevice: 44:80:EB:7B:5A:05, value is empty for type: 241
,E/BluetoothRemoteDevices( 3171): devicePropertyChangedCallback: bdDevice: F8:95:C7:87:85:54, value is empty for type: 10
,D/BtConfig.SecureMode( 3171): isSecureModeOn:false
,E/BluetoothRemoteDevices( 3171): devicePropertyChangedCallback: bdDevice: F8:95:C7:87:85:54, value is empty for type: 241
,E/BluetoothRemoteDevices( 3171): devicePropertyChangedCallback: bdDevice: B0:C5:59:3F:75:69, value is empty for type: 10
,D/BtConfig.SecureMode( 3171): isSecureModeOn:false
,E/BluetoothRemoteDevices( 3171): devicePropertyChangedCallback: bdDevice: B0:C5:59:3F:75:69, value is empty for type: 241
,E/BluetoothRemoteDevices( 3171): devicePropertyChangedCallback: bdDevice: 00:F4:6F:30:E0:6C, value is empty for type: 10
,D/BtConfig.SecureMode( 3171): isSecureModeOn:false
,E/BluetoothRemoteDevices( 3171): devicePropertyChangedCallback: bdDevice: 00:F4:6F:30:E0:6C, value is empty for type: 241
,E/BluetoothRemoteDevices( 3171): devicePropertyChangedCallback: bdDevice: 34:FC:EF:9D:93:0B, value is empty for type: 10
,D/BtConfig.SecureMode( 3171): isSecureModeOn:false
,E/BluetoothRemoteDevices( 3171): devicePropertyChangedCallback: bdDevice: 34:FC:EF:9D:93:0B, value is empty for type: 241
,E/BluetoothRemoteDevices( 3171): devicePropertyChangedCallback: bdDevice: 7C:F9:0E:51:18:22, value is empty for type: 10
,D/BtConfig.SecureMode( 3171): isSecureModeOn:false
,E/BluetoothRemoteDevices( 3171): devicePropertyChangedCallback: bdDevice: 7C:F9:0E:51:18:22, value is empty for type: 241
,E/BluetoothRemoteDevices( 3171): devicePropertyChangedCallback: bdDevice: B4:CE:F6:AB:A4:6A, value is empty for type: 10
,D/BtConfig.SecureMode( 3171): isSecureModeOn:false
,E/BluetoothRemoteDevices( 3171): devicePropertyChangedCallback: bdDevice: B4:CE:F6:AB:A4:6A, value is empty for type: 241
E/BluetoothRemoteDevices( 3171): devicePropertyChangedCallback: bdDevice: 34:FC:EF:11:AE:67, value is empty for type: 10
D/BtConfig.SecureMode( 3171): isSecureModeOn:false
,E/BluetoothRemoteDevices( 3171): devicePropertyChangedCallback: bdDevice: 34:FC:EF:11:AE:67, value is empty for type: 241
,E/BluetoothRemoteDevices( 3171): devicePropertyChangedCallback: bdDevice: 34:FC:EF:11:B1:66, value is empty for type: 10
,D/BtConfig.SecureMode( 3171): isSecureModeOn:false
,E/BluetoothRemoteDevices( 3171): devicePropertyChangedCallback: bdDevice: 34:FC:EF:11:B1:66, value is empty for type: 241
,E/BluetoothRemoteDevices( 3171): devicePropertyChangedCallback: bdDevice: 90:E7:C4:F6:69:77, value is empty for type: 10
,D/BtConfig.SecureMode( 3171): isSecureModeOn:false
,E/BluetoothRemoteDevices( 3171): devicePropertyChangedCallback: bdDevice: 90:E7:C4:F6:69:77, value is empty for type: 241
E/bt-btif ( 3171): btif_handle_bluetooth_enable_evt: btif_core_radio_ref_count:2
E/bt-btif ( 3171): btif_sock_init, radio_req:0, rfc_init:0, vhci_init:1
E/bt-btif ( 3171): btif_sock_init: !radio_req && !rfc_init
,D/IOP_DB_BT( 3171): db_open: file /etc/bluetooth/iop_bt.db
D/IOP_DB_BT( 3171): db_open: db_open : handle 2012996376l, read 9734 bytes onto local cache
D/IOP_DB_BT( 3171): db_query: id __IOPFLAGS :: key __KEY_ENABLE_VERBOSE, value 1
D/IOP_DB_BT( 3171): db_query: result 1
I/        ( 3171): iop_db_open: iop_db_open status 0
I/bte_conf( 3171): Attempt to load did conf from /etc/bluetooth/bt_did.conf
I/bte_conf( 3171): [1] primary_record=1 vendor_id=0x0075 vendor_id_source=0x0001 product_id=0x0100 version=0x0200
I/bte_conf( 3171): Attempt to load did conf from /etc/bluetooth/bt_did.conf
I/bte_conf( 3171): Attempt to load did conf from /etc/bluetooth/bt_did.conf
D/BluetoothAdapterState( 3171): CURRENT_STATE=PENDING, MSG = ENABLE_READY, isTurningOn=true, isTurningOff=false
,D/BluetoothAdapterProperties( 3171): ScanMode =  20
,D/BluetoothAdapterProperties( 3171): State =  11
,D/BtConfig.SecureMode( 3171): isSecureModeOn:false
D/BtConfig.SecureMode( 3171): isSecureModeOn:false
D/BtConfig.SecureMode( 3171): isSecureModeOn:false
D/BtConfig.SecureMode( 3171): isSecureModeOn:false
D/BtConfig.SecureMode( 3171): isSecureModeOn:false
D/BtConfig.SecureMode( 3171): isSecureModeOn:false
D/BtConfig.SecureMode( 3171): isSecureModeOn:false
D/BtConfig.SecureMode( 3171): isSecureModeOn:false
D/BtConfig.SecureMode( 3171): isSecureModeOn:false
D/BtConfig.SecureMode( 3171): isSecureModeOn:false
D/BtConfig.SecureMode( 3171): isSecureModeOn:false
D/BtConfig.SecureMode( 3171): isSecureModeOn:false
I/BluetoothAdapterState( 3171): Bluetooth adapter state changed: 11-> 12
D/BluetoothAdapterService( 3171): Bluetooth PBAP supproted is true
,D/BluetoothAdapterService( 3171): updateAdapterState state is 12
,D/BluetoothAdapterService( 3171): Broadcasting updateAdapterState() to 1 receivers.
D/BluetoothAdapterService(1113951808)( 3171): Register RemoteMessageListener
D/BluetoothA2dp(  761): onBluetoothStateChange: up=true
D/HeadsetService( 3171): registerMessageListener
D/BluetoothAdapterService( 3171): Autoconnection is available 
D/HeadsetStateMachine( 3171): Disconnected process message: 70
D/HeadsetStateMachine( 3171): processRegisterMessageListener : 2, com.android.bluetooth.btservice.RemoteDevices$1@426a3110
D/BluetoothAdapterService( 3171): updateAdapterState prevState = 11newState = 12
D/BluetoothA2dp( 3142): onBluetoothStateChange: up=true
D/BluetoothAdapterService( 3171): starting service from this receiver
D/BluetoothInputDevice( 3142): onBluetoothStateChange: up=true
D/BluetoothA2dp( 2025): onBluetoothStateChange: up=true
W/ContextImpl( 3171): Implicit intents with startService are not safe: Intent { act=com.samsung.ble.ACTION_SERVICE_BLE_AUTO_CONNECT } android.content.ContextWrapper.startService:506 com.android.bluetooth.btservice.AdapterService.updateAdapterState:653 com.android.bluetooth.btservice.AdapterState.notifyAdapterStateChange:586 
,I/BluetoothAdapterState( 3171): Entering On State from state = 11
,D/BluetoothAdapterService( 3171): initWakeLock, pfd lock: {ParcelFileDescriptor: FileDescriptor[91]}, pfd unlock: {ParcelFileDescriptor: FileDescriptor[92]}
,D/bluedroid( 3171): init_wake_lock lock_fd:91, unlock_fd:92
I/WifiTrafficPoller(  761): mBoosterFLAG : 2
,I/WifiTrafficPoller(  761): current booster mode : BTCoexMode
D/BluetoothAdapterService(1113951808)( 3171): Get Bonded Devices being called
D/PhoneApp( 1241): mReceiver: BluetoothAdapter.ACTION_STATE_CHANGED: 12
D/BluetoothHeadset( 1241): registerListener : 11, listenercom.android.phone.PhoneGlobals$MessageListener@4282c208, true
D/BluetoothHeadset( 1241): registerMessageListener
W/InputMethodManagerService(  761): InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
I/InputMethodManagerService(  761): [BT Setting State] State =12
,I/InputMethodManagerService(  761): [BT Setting off -> on] mBTKeyboardCount =0, KEYBOARD_BT(0)
I/QuickConnect[1.1][2] ( 3142): BluetoothHelper.ACTION_STATE_CHANGED - STATE_ON
D/HeadsetService( 3171): registerMessageListener
D/HeadsetService( 3171): registerMessageListener
D/HeadsetStateMachine( 3171): Disconnected process message: 70
D/HeadsetStateMachine( 3171): processRegisterMessageListener : 11, com.samsung.bt.hfp.IMessageListener$Stub$Proxy@427421f0
D/PhoneApp( 1241): registerMessageListener
I/BluetoothPbapService( 3171): action: android.bluetooth.adapter.action.STATE_CHANGED, state: 12
,D/BluetoothPanServiceJni( 3171): control_state_callback(L61): state:0, local_role:0, ifname:bt-pan
W/ContextImpl( 1307): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1857 android.content.ContextWrapper.startService:506 android.content.ContextWrapper.startService:506 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,D/STATUSBAR-IconMerger( 1069): checkOverflow(336), More:false, Req:false Child:2
,I/BluetoothPbapService( 3171): Handler(): got msg=1
,D/GKI_LINUX( 3171): release_my_wake_lock(), g_wake_lock_fd:91, g_wake_unlock_fd:92, wake_lock_acquired:0
,V/BluetoothPbapService( 3171): PBAP Service initSocket try: 0
,W/BluetoothAdapter( 3171): getBluetoothService() called with no BluetoothManagerCallback
,D/BluetoothMapMasInstance( 3171): set MAP SDP message type : 1
,E/BluetoothServiceJni( 3171): SOCK FLAG = 1 ***********************
D/GKI_LINUX( 3171): acquire_my_wake_lock(), g_wake_lock_fd:91, g_wake_unlock_fd:92, wake_lock_acquired:0
,W/BluetoothAdapter( 3171): getBluetoothService() called with no BluetoothManagerCallback
E/BluetoothServiceJni( 3171): SOCK FLAG = 3 ***********************
,D/BluetoothPbapService( 3171): PBAP Socket is BluetoothServerSocket
,D/GKI_LINUX( 3171): release_my_wake_lock(), g_wake_lock_fd:91, g_wake_unlock_fd:92, wake_lock_acquired:1
,D/LocalBluetoothProfileManager( 1307): Adding local A2DP profile
,W/ContextImpl( 1307): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1930 android.content.ContextWrapper.bindService:529 android.bluetooth.BluetoothA2dp.doBind:221 android.bluetooth.BluetoothA2dp.<init>:214 android.bluetooth.BluetoothAdapter.getProfileProxy:1412 
D/LocalBluetoothProfileManager( 1307): Adding local HEADSET profile
,E/BluetoothHeadset( 1307): BTStateChangeCB is registed
,E/BluetoothHeadset( 1307): BluetoothHeadset service is binded
W/ContextImpl( 1307): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1930 android.content.ContextWrapper.bindService:529 android.bluetooth.BluetoothHeadset.doBind:304 android.bluetooth.BluetoothHeadset.<init>:297 android.bluetooth.BluetoothAdapter.getProfileProxy:1409 
,D/Bluetoothsap( 1307): bindService called to Bluetooth SAP Service
W/ContextImpl( 1307): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1930 android.content.ContextWrapper.bindService:529 com.broadcom.bt.service.sap.BluetoothSap.doBind:186 com.broadcom.bt.service.sap.BluetoothSap.<init>:179 com.android.settings.bluetooth.SapProfile.<init>:129 
W/ContextImpl( 1307): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1930 android.content.ContextWrapper.bindService:529 android.bluetooth.BluetoothInputDevice.doBind:245 android.bluetooth.BluetoothInputDevice.<init>:238 android.bluetooth.BluetoothAdapter.getProfileProxy:1415 
,D/LocalBluetoothProfileManager( 1307): PANU : true
,D/LocalBluetoothProfileManager( 1307): Adding local MAP profile
,D/BluetoothMap( 1307): Create BluetoothMap proxy object
W/ContextImpl( 1307): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1930 android.content.ContextWrapper.bindService:529 android.bluetooth.BluetoothPan.doBind:173 android.bluetooth.BluetoothPan.<init>:162 android.bluetooth.BluetoothAdapter.getProfileProxy:1418 
W/ContextImpl( 1307): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1930 android.content.ContextWrapper.bindService:529 android.bluetooth.BluetoothMap.doBind:109 android.bluetooth.BluetoothMap.<init>:102 android.bluetooth.BluetoothAdapter.getProfileProxy:1424 
,W/ContextImpl( 1307): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1930 android.content.ContextWrapper.bindService:529 android.bluetooth.BluetoothPbap.doBind:164 android.bluetooth.BluetoothPbap.<init>:157 com.android.settings.bluetooth.PbapServerProfile.<init>:68 
,D/Bluetoothsap( 1307): bindService called to Bluetooth SAP Service
,D/LocalBluetoothProfileManager( 1307): LocalBluetoothProfileManager construction complete
,D/DockEventReceiver( 1307): finishStartingService: stopping service
,D/BluetoothNotiBroadcastReceiver( 1307): onReceive
,W/ContextImpl( 1307): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1930 android.content.ContextWrapper.bindService:529 com.broadcom.bt.service.sap.BluetoothSap.doBind:186 com.broadcom.bt.service.sap.BluetoothSap.<init>:179 com.android.settings.bluetooth.SapProfile.<init>:129 
D/BluetoothA2dp( 1307): Proxy object connected
D/BtConfig.SecureMode( 3171): isSecureModeOn:false
D/A2dpProfile( 1307): Bluetooth service connected
D/AuthorizationBluetoothService( 1312): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
E/AuthorizationBluetoothService( 1312): Proximity feature is not enabled.
,D/HeadsetProfile( 1307): Bluetooth service connected
,D/BluetoothInputDevice( 1307): Proxy object connected
,D/HidProfile( 1307): Bluetooth service connected
,D/BluetoothPan( 1307): BluetoothPAN Proxy object connected
,D/PanProfile( 1307): Bluetooth service connected
,D/BluetoothMap( 1307): Proxy object connected
,D/MapProfile( 1307): Bluetooth service connected
,D/BluetoothPbap( 1307): Proxy object connected
,D/PbapServerProfile( 1307): Bluetooth service connected
,W/BluetoothAdapter( 3171): getBluetoothService() called with no BluetoothManagerCallback
,E/BluetoothServiceJni( 3171): SOCK FLAG = 0 ***********************
,D/GKI_LINUX( 3171): acquire_my_wake_lock(), g_wake_lock_fd:91, g_wake_unlock_fd:92, wake_lock_acquired:0
,I/BtOppRfcommListener( 3171): Accept thread started.
,D/Tethering(  761): interfaceAdded wlan0
,E/Tethering(  761): No numeric data
,I/ConnectivityService(  761): defaultVal : 1, tetherEnabledInSettings : true
D/Tethering(  761): sendTetherStateChangedBroadcast 1, 0, 0
D/NtpTrustedTime(  761): forceRefresh() from cache miss
,D/Tethering(  761): interfaceLinkStateChanged wlan0, false
,D/Tethering(  761): interfaceStatusChanged wlan0, false
,D/NtpTrustedTime(  761): forceRefresh Fail.
,D/Tethering(  761): InitialState.processMessage what=4
,E/Tethering(  761): No numeric data
D/Tethering(  761): sendTetherStateChangedBroadcast 0, 0, 0
,D/Tethering(  761): interfaceAdded p2p0
,D/Tethering(  761): p2p0 is not a tetherable iface, ignoring
V/NetworkStats(  761): performPollLocked(flags=0x1)
I/ConnectivityService(  761): defaultVal : 1, tetherEnabledInSettings : true
,D/Tethering(  761): interfaceLinkStateChanged p2p0, false
,D/Tethering(  761): interfaceStatusChanged p2p0, false
,D/NtpTrustedTime(  761): forceRefresh() from cache miss
,D/NtpTrustedTime(  761): forceRefresh Fail.
,D/NtpTrustedTime(  761): forceRefresh() from cache miss
,D/NtpTrustedTime(  761): forceRefresh Fail.
V/NetworkStats(  761): performPollLocked() took 20ms
V/NetworkStats(  761): performPollLocked(flags=0x1)
,I/WifiHW  (  239): wifi_change_fw_path(): fwpath = sta
,D/SoftapController(  239): Softap fwReload - Ok
D/CommandListener(  239): Setting iface cfg
,D/CommandListener(  239): Trying to bring down wlan0
,V/NetworkStats(  761): performPollLocked() took 18ms
D/NtpTrustedTime(  761): forceRefresh() from cache miss
D/NtpTrustedTime(  761): forceRefresh Fail.
D/WifiHW  (  761): Skip the update_ctrl_interface
D/WifiHW  (  761): Skip the update_ctrl_interface
E/WifiHW  (  761): supplicant_name : p2p_supplicant
,D/STATUSBAR-NetworkController_dual( 1069): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
,D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews start
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews set mobileLabel[SIM_0] =No service.
,D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews GONE
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews2 set mobileLabel[SIM_1] =No service.
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews2 GONE
,D/StatusBar.NetworkController_dual( 1069): mSingleMobileLabelViews set : simMode = 0
,D/StatusBar.NetworkController_dual( 1069): mSingleMobileLabelViews set as slot1`s
D/GKI_LINUX( 3171): release_my_wake_lock(), g_wake_lock_fd:91, g_wake_unlock_fd:92, wake_lock_acquired:1
,D/WifiMonitor(  761): startMonitoring(wlan0) with mConnected = false
,I/wpa_supplicant( 4813): wpa_supplicant v2.1-devel-4.4.22014-11-04/18:06:52
I/wpa_supplicant( 4813): [wpa_supplicant_init]: use SECRIL
I/wpa_supplicant( 4813): Successfully initialized wpa_supplicant
,I/wpa_supplicant( 4813): >>>>> Not GET KEY, IV <<<<<
E/wpa_supplicant( 4813): getIMSI cannot open file
,E/wpa_supplicant( 4813): Interworking config: - SIM READ ERROR
,I/knox    ( 3081): MainReceiver.onReceive() : Intent { act=android.net.wifi.WIFI_STATE_CHANGED flg=0x4000010 cmp=com.sec.knox.seandroid/.receiver.MainReceiver (has extras) }
W/ContextImpl( 3081): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1857 android.content.ContextWrapper.startService:506 android.content.ContextWrapper.startService:506 com.sec.knox.seandroid.receiver.MainReceiver.onReceive:142 android.app.ActivityThread.handleReceiver:2698 
,I/knox    ( 3081): MainReceiver.onReceive() END - - - - - : Intent { act=android.net.wifi.WIFI_STATE_CHANGED flg=0x4000010 cmp=com.sec.knox.seandroid/.receiver.MainReceiver (has extras) }
,I/wpa_supplicant( 4813): >>>>> Not GET KEY, IV <<<<<
E/wpa_supplicant( 4813): getIMSI cannot open file
,E/wpa_supplicant( 4813): Interworking config: - SIM READ ERROR
,I/wpa_supplicant( 4813): >>>>> Not GET KEY, IV <<<<<
,I/wpa_supplicant( 4813): rfkill: Cannot open RFKILL control device
,D/Tethering(  761): interfaceLinkStateChanged wlan0, false
,D/Tethering(  761): interfaceStatusChanged wlan0, false
,I/SELinux ( 4814): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 4814):  
D/knox    ( 3081): KNOXAgentService : onCreate()
D/knox    ( 3081): KNOXAgentService : set alarms for deniallog and usage data upload
D/knox    ( 3081): KNOXAgentService. startJobThread() start
D/knox    ( 3081): KNOXAgentService. JobThread()
D/knox    ( 3081): KNOXAgentService. JobThread. notifyAll().
D/knox    ( 3081): KNOXAgentService. startJobThread() wait
D/knox    ( 3081): KNOXAgentService : onDestroy().
,D/knox    ( 3081): ModuleBase.cancelAllAlarmManageModule()
,I/SELinux ( 4814): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 4814):  
I/SELinux ( 4814):  
,I/SELinux ( 4814): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 4814): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 4814): >>>>> Normal User
,E/dalvikvm( 4814): >>>>> tv.peel.smartremote [ userId:0 | appId:10163 ]
,E/SELinux ( 4814): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
,I/wpa_supplicant( 4813): wlan0: Setting scan request: 0 sec 100000 usec
,D/TimaKeyStoreProvider( 4814): in addTimaSignatureService
,D/TimaKeyStoreProvider( 4814): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 4814): Added TimaKesytore provider
,W/ActivityManager(  761): Permission Denial: getCurrentUser() from pid=4814, uid=10163 requires android.permission.INTERACT_ACROSS_USERS
,I/wpa_supplicant( 4813): >>>>> Not GET KEY, IV <<<<<
,I/wpa_supplicant( 4813): >>>>> Not GET KEY, IV <<<<<
I/wpa_supplicant( 4813): rfkill: Cannot open RFKILL control device
D/Tethering(  761): interfaceLinkStateChanged p2p0, false
,D/Tethering(  761): interfaceStatusChanged p2p0, false
D/Tethering(  761): interfaceLinkStateChanged p2p0, false
,D/Tethering(  761): interfaceStatusChanged p2p0, false
,I/wpa_supplicant( 4813): CTRL-EVENT-STATE-CHANGE id=-1 state=2 BSSID=00.00.00 SSID=
,I/ActivityManager(  761): Killing 3707:com.sec.android.app.sns3/u0a36 (adj 15): empty #43
,I/wpa_supplicant( 4813): P2P: initialized channels: 81:1,2,3,4,5,6,7,8,9,10,11,12,13 115:36,40,44,48 116:36,44 117:40,48
I/wpa_supplicant( 4813): CTRL-EVENT-STATE-CHANGE id=-1 state=0 BSSID=00.00.00 SSID=
,I/wpa_supplicant( 4813): Skip scan - bUseNetwork false
,D/WifiStateMachine(  761): skipWifiStateBroadcast:false, LastBroadcastedWifiState:2
,D/WifiNative(  761): callSECApiString - ID [21]
I/wpa_supplicant( 4813): HOTSPOT20_ENABLE called
,I/wpa_supplicant( 4813): wlan0: HS20_DISABLED_COMPLETE normal
D/STATUSBAR-NetworkController_dual( 1069): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
D/SignalClusterView_dual( 1069): wifi: GONE sig=0 act=0
D/SignalClusterView_dual( 1069): mMobileDataState=0 mMobileDataState2=0
D/SignalClusterView_dual( 1069): apply() mSeparateMobileGroup=8
D/STATUSBAR-NetworkController_dual( 1069): refreshSignalCluster - setNWBoosterIndicators(false)
D/SignalClusterView_dual( 1069): wifi: GONE sig=2130837981 act=0
D/SignalClusterView_dual( 1069): mMobileDataState=0 mMobileDataState2=0
D/SignalClusterView_dual( 1069): apply() mSeparateMobileGroup=8
D/SignalClusterView_dual( 1069): wifi: GONE sig=2130837981 act=0
D/SignalClusterView_dual( 1069): mMobileDataState=0 mMobileDataState2=0
D/SignalClusterView_dual( 1069): apply() mSeparateMobileGroup=8
D/SignalClusterView_dual( 1069): wifi: GONE sig=2130837981 act=0
D/SignalClusterView_dual( 1069): mMobileDataState=0 mMobileDataState2=0
D/SignalClusterView_dual( 1069): apply() mSeparateMobileGroup=8
D/SignalClusterView_dual( 1069): wifi: GONE sig=2130837981 act=0
D/SignalClusterView_dual( 1069): mMobileDataState=0 mMobileDataState2=0
D/SignalClusterView_dual( 1069): apply() mSeparateMobileGroup=8
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews start
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews set mobileLabel[SIM_0] =No service.
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews GONE
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews2 set mobileLabel[SIM_1] =No service.
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews2 GONE
D/StatusBar.NetworkController_dual( 1069): mSingleMobileLabelViews set : simMode = 0
D/StatusBar.NetworkController_dual( 1069): mSingleMobileLabelViews set as slot1`s
,I/knox    ( 3081): MainReceiver.onReceive() : Intent { act=android.net.wifi.WIFI_STATE_CHANGED flg=0x4000010 cmp=com.sec.knox.seandroid/.receiver.MainReceiver (has extras) }
,D/WifiNative(  761): callSECApiInt - ID [65]
W/ContextImpl( 3081): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1857 android.content.ContextWrapper.startService:506 android.content.ContextWrapper.startService:506 com.sec.knox.seandroid.receiver.MainReceiver.onReceive:142 android.app.ActivityThread.handleReceiver:2698 
,E/WifiConfigStore(  761): Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
,I/knox    ( 3081): MainReceiver.onReceive() END - - - - - : Intent { act=android.net.wifi.WIFI_STATE_CHANGED flg=0x4000010 cmp=com.sec.knox.seandroid/.receiver.MainReceiver (has extras) }
,D/WifiNative(  761): callSECApiBoolean - ID [13]
,I/wpa_supplicant( 4813): USE_NETWORK : USE_NETWORK ON
I/wpa_supplicant( 4813): reset timer : RESET_TIMER 0
I/wpa_supplicant( 4813): wlan0: Setting scan request: 0 sec 0 usec
I/wpa_supplicant( 4813): CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00.00.00 SSID=
,I/wpa_supplicant( 4813): First Scan Start
,I/wpa_supplicant( 4813): Scan requested (ret=0) - scan timeout 30 seconds
,E/WifiStateMachine(  761): Set the Nv default ccode
,W/Settings( 3040): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/knox    ( 3081): KNOXAgentService : onCreate()
,D/knox    ( 3081): KNOXAgentService : set alarms for deniallog and usage data upload
D/knox    ( 3081): KNOXAgentService. startJobThread() start
,D/knox    ( 3081): KNOXAgentService. JobThread()
D/knox    ( 3081): KNOXAgentService. JobThread. notifyAll().
,D/knox    ( 3081): KNOXAgentService. startJobThread() wait
,D/WifiP2pService(  761): P2pDisabledState{ what=131203 }
D/knox    ( 3081): KNOXAgentService : onDestroy().
D/knox    ( 3081): ModuleBase.cancelAllAlarmManageModule()
D/CommandListener(  239): Setting iface cfg
D/CommandListener(  239): Trying to bring up p2p0
D/WifiStateMachine(  761): skipWifiStateBroadcast:false, LastBroadcastedWifiState:3
E/WifiStateMachine(  761): HS20_DISABLED_COMPLETEnormal
,D/WifiMonitor(  761): startMonitoring(p2p0) with mConnected = true
,D/knox    ( 3081): GSLBThreadManager.NetworkStateChanged : NETWORK_STATE_CHAGED. Upload Call Log Data
D/WifiP2pService(  761): P2pEnablingState
D/WifiP2pService(  761): P2pEnablingState{ what=147457 }
D/WifiP2pService(  761): P2p socket connection successful
D/WifiP2pService(  761): P2pEnabledState
,E/WifiStateMachine(  761): BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
D/QuickConnect[1.1][2] ( 3142): SconnectManager.INetworkStateListener, onEnabled - mNetworkState : 4
,I/wpa_supplicant( 4813): P2P: updated channels: 81:1,2,3,4,5,6,7,8,9,10,11,12,13 115:36,40,44,48 116:36,44 117:40,48
,D/QuickConnect[1.1][2] ( 3142): P2pHelper.onReceive - ACTION_WIFI_DISPLAY_STATUS_CHANGED :0
D/WifiP2pService(  761): sending p2p connection changed broadcast: IDLE
D/WifiDisplayController(  761): Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=true
D/WifiDisplayController(  761): updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
D/WifiDisplayController(  761): disconnect
D/WifiDisplayController(  761): updateConnection
D/WifiDisplayController(  761): updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
D/WifiDisplayAdapter(  761): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
W/ContextImpl(  761): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.android.server.enterprise.wifi.WifiPolicy.asyncEnableNetwork:3065 com.android.server.enterprise.wifi.WifiPolicy.edmUpdateConfiguredNetworks:2530 com.android.server.enterprise.wifi.WifiPolicy$2$2.run:3022 java.lang.Thread.run:841 
D/WifiDisplayAdapter(  761): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,D/QuickConnect[1.1][2] ( 3142): P2pHelper.onReceive - P2P_CONNECTION_CHANGED : 
W/WifiP2pStateTracker(  761): WifiP2pStateReceiver : android.net.wifi.p2p.CONNECTION_STATE_CHANGE
D/WifiDisplayController(  761): Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=NetworkInfo: type: WIFI_P2P[], state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/QuickConnect[1.1][2] ( 3142): SconnectManager.INetworkStateListener, onDisconnected - networkType : 4
D/WifiP2pService(  761): DeviceAddress: 3a:06:dd
,D/WifiP2pService(  761): sending p2p persistent groups changed broadcast
,D/WifiDisplayController(  761): Received WIFI_P2P_THIS_DEVICE_CHANGED_ACTION: mThisDevice= Device: Galaxy S5-2
D/WifiDisplayController(  761):  deviceAddress: 3a:94:96:b5:06:dd
D/WifiDisplayController(  761):  primary type: 10-0050F204-5
D/WifiDisplayController(  761):  secondary type: null
D/WifiDisplayController(  761):  wps: 0
D/WifiDisplayController(  761):  grpcapab: 0
D/WifiDisplayController(  761):  devcapab: 0
D/WifiDisplayController(  761):  status: 3
D/WifiDisplayController(  761):  wfdInfo: null
D/WifiDisplayController(  761):  groupownerAddress: null
D/WifiDisplayController(  761):  GOdeviceName: null
D/WifiDisplayController(  761):  interfaceAddress: 
D/WifiDisplayController(  761):  SConnectInfo : null
,D/WifiP2pService(  761): InactiveState
D/WifiP2pService(  761): InactiveState{ what=139287 }
D/WifiP2pService(  761): P2pEnabledState{ what=139287 }
,D/NearbySettings( 1307): MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,D/QuickConnect[1.1][2] ( 3142): P2pHelper.requestGroupInfo  - onGroupInfoAvailable- null
D/WifiP2pService(  761): DefaultState{ what=139287 }
,V/NearbySettings( 1307): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 1307): DMSUtil.isNetworkConnected - WIFI: IDLE
I/NearbySettings( 1307): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1307): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
,I/NearbySettings( 1307): MountReceiver.onReceive - Set preference state off
,V/NearbySettings( 1307): MountReceiver.mPrefHandler - 7002
,D/FileShare-Server( 4178): ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,D/FileShare-Server( 4178): ServerBroadcastReceiver.onReceive - netInfo.getDetailedState() IDLE
,E/SMD     (  242): DCD OFF
,I/GAV2    ( 4630): Thread[GAThread,5,main]: No campaign data found.
,D/Tethering(  761): interfaceLinkStateChanged p2p0, false
,D/Tethering(  761): interfaceStatusChanged p2p0, false
,I/wpa_supplicant( 4813): P2P: updated channels: 81:1,2,3,4,5,6,7,8,9,10,11,12,13 115:36,40,44,48 116:36,44 117:40,48
,I/wpa_supplicant( 4813): P2P: updated channels: 81:1,2,3,4,5,6,7,8,9,10,11,12,13 115:36,40,44,48 116:36,44 117:40,48
,I/wpa_supplicant( 4813): nl80211: Received scan results (2 BSSes)
,I/wpa_supplicant( 4813): wlan0: Setting scan request: 8 sec 0 usec
I/wpa_supplicant( 4813): Trying to associate with SSID '4E47373030'
I/wpa_supplicant( 4813): Trying to associate with  'G700'
,I/wpa_supplicant( 4813): CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00.00.00 SSID=
,E/wpa_supplicant( 4813): Cmd 35609 not handled
D/Tethering(  761): interfaceLinkStateChanged wlan0, false
,D/Tethering(  761): interfaceStatusChanged wlan0, false
,D/AmoledAdjustTimer(  761): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
E/WifiStateMachine(  761): Error! unhandled message{ when=-21ms what=135188 target=com.android.internal.util.StateMachine$SmHandler }
,E/wpa_supplicant( 4813): Cmd 35605 not handled
I/wpa_supplicant( 4813): CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00.00.00 SSID=4E47373030
I/wpa_supplicant( 4813): Associated with C0.AA.48
,I/wpa_supplicant( 4813): CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=C0.AA.48 SSID=4E47373030
,E/wpa_supplicant( 4813): Cmd 35847 not handled
E/wpa_supplicant( 4813): Cmd 35848 not handled
,E/wpa_supplicant( 4813): Cmd 35605 not handled
,D/Tethering(  761): interfaceLinkStateChanged wlan0, false
,D/Tethering(  761): interfaceStatusChanged wlan0, false
I/wpa_supplicant( 4813): CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=C0.AA.48 SSID=4E47373030
I/wpa_supplicant( 4813): WPA: Key negotiation completed with C0.AA.48 [PTK=CCMP GTK=CCMP]
,I/wpa_supplicant( 4813): CTRL-EVENT-CONNECTED - Connection to C0.AA.48 completed (auth) [id=0 id_str=]
,I/wpa_supplicant( 4813): CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=C0.AA.48 SSID=4E47373030
,D/WifiNative(  761): callSECApiVoid - ID [50]
D/Tethering(  761): interfaceLinkStateChanged wlan0, false
,D/Tethering(  761): interfaceStatusChanged wlan0, false
,D/Tethering(  761): interfaceLinkStateChanged wlan0, false
,D/Tethering(  761): interfaceStatusChanged wlan0, false
,D/STATUSBAR-NetworkController_dual( 1069): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
,D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews start
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews set mobileLabel[SIM_0] =No service.
,D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews GONE
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews2 set mobileLabel[SIM_1] =No service.
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews2 GONE
,D/StatusBar.NetworkController_dual( 1069): mSingleMobileLabelViews set : simMode = 0
,D/StatusBar.NetworkController_dual( 1069): mSingleMobileLabelViews set as slot1`s
,I/SELinux ( 4853): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 4853):  
,D/Tethering(  761): interfaceLinkStateChanged wlan0, true
,D/Tethering(  761): interfaceStatusChanged wlan0, true
,D/dalvikvm(  249): GC_EXPLICIT freed 43K, 51% free 9510K/19088K, paused 2ms+2ms, total 28ms
,E/Tethering(  761): No numeric data
I/ConnectivityService(  761): defaultVal : 1, tetherEnabledInSettings : true
,D/Tethering(  761): sendTetherStateChangedBroadcast 1, 0, 0
,D/NtpTrustedTime(  761): forceRefresh() from cache miss
,D/NtpTrustedTime(  761): forceRefresh Fail.
,D/Tethering(  761): interfaceLinkStateChanged wlan0, true
,D/Tethering(  761): interfaceStatusChanged wlan0, true
,V/NetworkStats(  761): performPollLocked(flags=0x1)
I/SELinux ( 4853): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 4853):  
I/SELinux ( 4853):  
D/Tethering(  761): interfaceLinkStateChanged wlan0, true
D/Tethering(  761): interfaceStatusChanged wlan0, true
I/SELinux ( 4853): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 4853): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 4853): >>>>> Normal User
E/dalvikvm( 4853): >>>>> com.vlingo.midas [ userId:0 | appId:10033 ]
D/Tethering(  761): interfaceLinkStateChanged wlan0, true
D/Tethering(  761): interfaceStatusChanged wlan0, true
D/Tethering(  761): interfaceLinkStateChanged wlan0, true
D/Tethering(  761): interfaceStatusChanged wlan0, true
E/SELinux ( 4853): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
,D/dalvikvm(  249): GC_EXPLICIT freed <1K, 51% free 9510K/19088K, paused 2ms+11ms, total 30ms
,D/NtpTrustedTime(  761): forceRefresh() from cache miss
,D/NtpTrustedTime(  761): forceRefresh Fail.
V/NetworkStats(  761): performPollLocked() took 19ms
,D/dalvikvm(  249): GC_EXPLICIT freed <1K, 51% free 9510K/19088K, paused 2ms+3ms, total 21ms
,D/STATUSBAR-NetworkController_dual( 1069): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
,D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews start
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews set mobileLabel[SIM_0] =No service.
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews GONE
,D/TimaKeyStoreProvider( 4853): in addTimaSignatureService
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews2 set mobileLabel[SIM_1] =No service.
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews2 GONE
D/StatusBar.NetworkController_dual( 1069): mSingleMobileLabelViews set : simMode = 0
D/StatusBar.NetworkController_dual( 1069): mSingleMobileLabelViews set as slot1`s
,D/TimaKeyStoreProvider( 4853): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 4853): Added TimaKesytore provider
D/STATUSBAR-NetworkController_dual( 1069): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews start
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews set mobileLabel[SIM_0] =No service.
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews GONE
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews2 set mobileLabel[SIM_1] =No service.
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews2 GONE
D/StatusBar.NetworkController_dual( 1069): mSingleMobileLabelViews set : simMode = 0
D/StatusBar.NetworkController_dual( 1069): mSingleMobileLabelViews set as slot1`s
D/WifiP2pService(  761): InactiveState{ what=143375 }
D/WifiP2pService(  761): P2pEnabledState{ what=143375 }
,I/System.out( 4853): Inside WakeupProvider
,I/System.out( 4853): Inside onCreate() of WakeupTriggerProvide
,I/VlingoApplication( 4853): VlingoApplication appVersion ='11.4.0.3.34005', ro.csc.sales_code=XEO
,D/VlingoApplication( 4853): Couldn't create com.nuance.nuancedebugutilpackage context for host settings utility
,D/VlingoApplication( 4853): Couldn't create com.vlingo.midas.lmttutilitypackage context for host settings utility
,I/dhcpcd  ( 4874): if(wlan0) info get Success. (MAC : C0.AA.48)
,I/dhcpcd  ( 4874): bssid match
,D/NearbySettings( 1307): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 1307): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 1307): DMSUtil.isNetworkConnected - WIFI: OBTAINING_IPADDR
,I/NearbySettings( 1307): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1307): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1307): MountReceiver.onReceive - Set preference state off
,V/NearbySettings( 1307): MountReceiver.mPrefHandler - 7002
I/ActivityManager(  761): Killing 3763:com.sec.spp.push:RemoteDlcProcess/u0a38 (adj 15): empty #43
,D/DialogFlow( 4853): initQueue()
,D/SSRMv2:SIOP(  761): SIOP:: AP = 320, Delta = 10
,E/SMD     (  242): DCD OFF
,D/WifiP2pService(  761): InactiveState{ what=143375 }
,D/WifiP2pService(  761): P2pEnabledState{ what=143375 }
,D/WifiStateMachine(  761): VerifyingLinkState enter
D/STATUSBAR-NetworkController_dual( 1069): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews start
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews set mobileLabel[SIM_0] =No service.
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews GONE
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews2 set mobileLabel[SIM_1] =No service.
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews2 GONE
D/StatusBar.NetworkController_dual( 1069): mSingleMobileLabelViews set : simMode = 0
D/StatusBar.NetworkController_dual( 1069): mSingleMobileLabelViews set as slot1`s
,D/STATUSBAR-NetworkController_dual( 1069): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
,D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews start
,D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews set mobileLabel[SIM_0] =No service.
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews GONE
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews2 set mobileLabel[SIM_1] =No service.
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews2 GONE
,D/StatusBar.NetworkController_dual( 1069): mSingleMobileLabelViews set : simMode = 0
,D/WifiStateMachine(  761): VerifyingLinkState GOOD_LINK_DETECTED: transition to captive portal check
,D/StatusBar.NetworkController_dual( 1069): mSingleMobileLabelViews set as slot1`s
D/WifiStateMachine(  761): CaptivePortalCheckState enter
,I/WifiTrafficPoller(  761): evaluateTrafficStatsPolling
,D/WifiStateMachine(  761): CaptivePortalCheckState CMD_CAPTIVE_CHECK_COMPLETE
D/ConnectivityService(  761): Captive portal check NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService(  761): handleCaptivePortalTrackerCheck: call captivePortalCheckComplete ni=NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/STATUSBAR-NetworkController_dual( 1069): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews start
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews set mobileLabel[SIM_0] =No service.
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews GONE
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews2 set mobileLabel[SIM_1] =No service.
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews2 GONE
D/StatusBar.NetworkController_dual( 1069): mSingleMobileLabelViews set : simMode = 0
D/StatusBar.NetworkController_dual( 1069): mSingleMobileLabelViews set as slot1`s
,I/WifiTrafficPoller(  761): evaluateTrafficStatsPolling
I/WifiTrafficPoller(  761): mBoosterFLAG : 2
,I/WifiTrafficPoller(  761): current booster mode : BTCoexMode
D/ConnectivityService(  761): ConnectivityChange for WIFI: CONNECTED/CONNECTED
E/ConnectivityService(  761): net.tcp.usercfg.wifi not found in system properties. Using defaults
E/ConnectivityService(  761): net.tcp.delack.wifi not found in system properties. Using defaults
D/STATUSBAR-NetworkController_dual( 1069): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
D/SignalClusterView_dual( 1069): wifi: GONE sig=2130837981 act=0
D/SignalClusterView_dual( 1069): mMobileDataState=0 mMobileDataState2=0
D/SignalClusterView_dual( 1069): apply() mSeparateMobileGroup=8
D/STATUSBAR-NetworkController_dual( 1069): refreshSignalCluster - setNWBoosterIndicators(false)
D/SignalClusterView_dual( 1069): wifi: VISIBLE sig=2130837979 act=2130837939
D/SignalClusterView_dual( 1069): mMobileDataState=0 mMobileDataState2=0
D/SignalClusterView_dual( 1069): apply() mSeparateMobileGroup=8
D/SignalClusterView_dual( 1069): wifi: VISIBLE sig=2130837979 act=2130837939
D/SignalClusterView_dual( 1069): mMobileDataState=0 mMobileDataState2=0
D/SignalClusterView_dual( 1069): apply() mSeparateMobileGroup=8
D/SignalClusterView_dual( 1069): wifi: VISIBLE sig=2130837979 act=2130837939
D/SignalClusterView_dual( 1069): mMobileDataState=0 mMobileDataState2=0
D/SignalClusterView_dual( 1069): apply() mSeparateMobileGroup=8
D/SignalClusterView_dual( 1069): wifi: VISIBLE sig=2130837979 act=2130837939
D/SignalClusterView_dual( 1069): mMobileDataState=0 mMobileDataState2=0
D/SignalClusterView_dual( 1069): apply() mSeparateMobileGroup=8
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews start
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews set mobileLabel[SIM_0] =
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews GONE
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews2 set mobileLabel[SIM_1] =
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews2 GONE
D/StatusBar.NetworkController_dual( 1069): mSingleMobileLabelViews set : simMode = 0
D/StatusBar.NetworkController_dual( 1069): mSingleMobileLabelViews set as slot1`s
,D/NearbySettings( 1307): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,I/NearbySettings( 1307): MountReceiver.onReceive - Keep current state
D/ConnectivityService(  761): handleConnectivityChange: setting default proxy info 
D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,V/RouteController(  239): /system/bin/ip -4 route replace default via 192.168.1.1 dev wlan0 scope global table 2 2>&1
,V/RouteController(  239): /system/bin/ip -4 rule del table 2 2>&1
,D/NearbySettings( 1307): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 1307): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 1307): DMSUtil.isNetworkConnected - WIFI: CONNECTED
,I/NearbySettings( 1307): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1307): DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
,I/NearbySettings( 1307): MountReceiver.onReceive - Keep current state
V/RouteController(  239): RTNETLINK answers: No such file or directory
,V/RouteController(  239): /system/bin/ip -4 rule add from 192.168.1.143 lookup 2 prio 150 2>&1
,V/RouteController(  239): /system/bin/ip route flush cached 2>&1
,V/RouteController(  239): /system/bin/ip route del 192.168.1.0/24 table 2 2>&1
,V/RouteController(  239): RTNETLINK answers: No such process
,V/RouteController(  239): /system/bin/ip route add 192.168.1.0/24 dev wlan0 table 2 metric 0 2>&1
,D/Toast   ( 1307):  checkMirrorLinkEnabled returns : false
,D/Toast   ( 1307): showing allowed
,V/RouteController(  239): /system/bin/ip route flush cached 2>&1
,D/NearbySettings( 1307): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
I/NearbySettings( 1307): MountReceiver.onReceive - Keep current state
,D/NtpTrustedTime(  761): forceRefresh() from cache miss
V/NetworkStats(  761): updateIfacesLocked()
V/NetworkStats(  761): performPollLocked(flags=0x1)
,V/NetworkStats(  761): performPollLocked() took 17ms
,I/SurfaceFlinger(  248): id=18 createSurf (1x1),1 flag=4, Uoast
,D/KeyguardUpdateMonitor( 1069): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1069): handleKeyguardVisibilityChanged(1)
,D/PowerManagerService(  761): [api] acquire WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=761
,D/KeyguardUpdateMonitor( 1069): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1069): handleKeyguardVisibilityChanged(1)
,D/KeyguardUpdateMonitor( 1069): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1069): handleKeyguardVisibilityChanged(1)
,D/NtpTrustedTime(  761): requestTime Success from server:2.android.pool.ntp.org mCachedNtpTime : 1453985570391 mCachedNtpElapsedRealtime : 104504 mCachedNtpCertainty : 12
,D/NtpTrustedTime(  761): currentTimeMillis() cache hit
,D/NtpTrustedTime(  761): currentTimeMillis() cache hit
,D/NtpTrustedTime(  761): currentTimeMillis() cache hit
D/NtpTrustedTime(  761): currentTimeMillis() cache hit
D/NtpTrustedTime(  761): currentTimeMillis() cache hit
,D/NtpTrustedTime(  761): currentTimeMillis() cache hit
V/NetworkStats(  761): advisePersistThreshold() given 9223372036854775, clamped to 2097152
,D/KeyguardUpdateMonitor( 1069): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1069): handleKeyguardVisibilityChanged(1)
,D/KeyguardUpdateMonitor( 1069): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1069): handleKeyguardVisibilityChanged(1)
,D/Tethering(  761): Tethering got CONNECTIVITY_ACTION
,D/Tethering(  761): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker(  761): NoActiveNetworkState{ when=0 what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
D/NtpTrustedTime(  761): currentTimeMillis() cache hit
D/        (  761): Setting time of day to sec=1453985570
,D/        (  761): Trying to open a file
,D/        (  761): File Open Success
,D/        (  761): File Close Success
,W/        (  761): Unable to set rtc to 1453985570: Invalid argument
,V/AlarmManager(  761): waitForAlarm result :65536
,D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews start
,D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews set mobileLabel[SIM_0] =
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews GONE
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews2 set mobileLabel[SIM_1] =
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews2 GONE
D/StatusBar.NetworkController_dual( 1069): mSingleMobileLabelViews set : simMode = 0
,D/StatusBar.NetworkController_dual( 1069): mSingleMobileLabelViews set as slot1`s
,D/accuweather( 1447): [KK AccuPhone]>>> SWW:64 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,I/        (  761): DRM_TIME_PATH CHMOD 660 for resetState done 
D/STATUSBAR-NetworkController_dual( 1069): onReceive() - CONNECTIVITY_ACTION, INET_CONDITION_ACTION
,D/STATUSBAR-NetworkController_dual( 1069): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
,D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews start
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews set mobileLabel[SIM_0] =
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews GONE
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews2 set mobileLabel[SIM_1] =
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews2 GONE
,D/StatusBar.NetworkController_dual( 1069): mSingleMobileLabelViews set : simMode = 0
,D/StatusBar.NetworkController_dual( 1069): mSingleMobileLabelViews set as slot1`s
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.TIME_SET
,D/KeyguardUpdateMonitor( 1069): handleTimeUpdate
,I/AudioService(  761): getStreamVolume 5 index 110
D/StatusBar-DoNotDistrub( 1069): Received intent with android.intent.action.TIME_SET action
D/StatusBar-DoNotDistrub( 1069): Not data shared android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
D/StatusBar-DoNotDistrub( 1069): sendBroadcast android.intent.action.DORMANT_MODE_OFF
D/StatusBar-DoNotDistrub( 1069): The STREAM NOTIFICATION volume is 0
D/STATUSBAR-StatusBarManagerService(  761): manageDisableList what=0x0 pkg=com.android.systemui
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,D/BatteryService(  761): level:100, scale:100, status:5, health:2, present:true, voltage: 4366, temperature: 288, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:5, charge type:1, power sharing:false
,D/BatteryService(  761): stay LED for fully charged
,W/Settings(  761): Setting auto_time has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/PCWCLIENTTRACE_PushUtil( 4411): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 4411): sales region : global
I/PCWCLIENTTRACE_PushUtil( 4411): getPushTypeList : [SPP, GCM]
,I/PCWCLIENTTRACE_SYSTEMReceiver( 4411): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,D/accuweather( 1447): [KK AccuPhone]>>> SWW:64 [0:0] action : androidintentactionTIME_SET
,D/accuweather( 1447): [KK AccuPhone]>>> SWW:452 [0:0] doChangeDayOrNight : 1
,W/SEC_DRM_PLUGIN_Playready(  250): PlayreadyPlugIn::onAcquireDrmInfo : case TYPE_UPDATE_SECURE_CLOCK after: 1453985571 after conversion: 1453985571
,W/SEC_DRM_PLUGIN_Playready(  250): PlayreadyPlugIn::onAcquireDrmInfo : case TYPE_UPDATE_SECURE_CLOCK before: 1453985570 after conversion: 1453985570
,I/NetworkMonitor( 3796): type=WIFI subType= reason=null isConnected=true
D/STATUSBAR-NotificationService(  761): received android.intent.action.DORMANT_MODE_OFF
D/LightsService(  761): [api] [SvcLED] turnOff:: id = 4 (uid: 1000 pid: 761) 
,D/LightsService(  761): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x40 -> 0x40 | SvcLED(id=4) set Off
I/SensorManagerA(  761): getReportingMode :: sensor.mType = 5
D/Sensors (  761): LightSensor setDelay = 200000000
D/Sensors (  761): LightSensor setSensorDelay = 200000000
D/Sensors (  761): Light sensor flush: not enabled 0
D/Sensors (  761): LightSensor enable = 1
D/Sensors (  761): LightSensor enableSensor = 1
,D/SensorManager(  761): registerListener :: 16, CM36686 Light Sensor, 200000, 0,  
,D/LocSvc_java(  761): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/LocSvc_java(  761): getAGpsConnectionInfo connType - 4
,D/LocSvc_java(  761): ignore wifi update if we are not in OPENING or CLOSING
,D/accuweather( 1447): [KK AccuPhone]>>> SWW:338 [0:0] getWeatherRenderer : 1
D/BatteryService(  761): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  761): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,V/HeadsetService( 3171): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3171): Disconnected process message: 10
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
I/SELinux ( 4956): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 4956):  
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,I/SELinux ( 4956): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 4956):  
I/SELinux ( 4956):  
,I/SELinux ( 4956): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
D/ChimeraCfgMgr( 1758): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 1758): Module APK com.google.android.play.games already loaded
E/SELinux ( 4956): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 4956): >>>>> Normal User
,E/dalvikvm( 4956): >>>>> com.sec.android.cloudagent [ userId:0 | appId:10002 ]
,E/SELinux ( 4956): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 4956): in addTimaSignatureService
,D/TimaKeyStoreProvider( 4956): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 4956): Added TimaKesytore provider
,I/GamesSyncServiceMain( 1758): Found unexpected GCM tag when scheduling; aborting
,W/GamesSyncServiceMain( 1758): Failed to execute periodic sync, missing client context - aborting
,D/Sensors (  761): LightSensor enable = 0
D/Sensors (  761): LightSensor enableSensor = 0
,D/SensorManager(  761): unregisterListener ::   
D/LightsService(  761): [SvcLED]  onSensorChanged::light value = 16
D/LightsService(  761): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,W/dalvikvm( 1220): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 1220): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 1220): VFY: unable to find class referenced in signature (Landroid/net/Network;)
I/dalvikvm( 1220): Could not find method android.net.Network.openConnection, referenced from method com.google.android.gms.http.g.a
W/dalvikvm( 1220): VFY: unable to resolve virtual method 1007: Landroid/net/Network;.openConnection (Ljava/net/URL;)Ljava/net/URLConnection;
,D/dalvikvm( 1220): VFY: replacing opcode 0x6e at 0x00bb
,I/GoogleURLConnFactory( 1220): Using platform SSLCertificateSocketFactory
,I/SELinux ( 4976): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 4976):  
,I/SELinux ( 4976): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 4976):  
I/SELinux ( 4976):  
,I/SELinux ( 4976): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 4976): [DEBUG] seapp_context_lookup: seinfoCategory = chrome
E/dalvikvm( 4976): >>>>> Normal User
,E/dalvikvm( 4976): >>>>> com.android.chrome [ userId:0 | appId:10081 ]
,E/SELinux ( 4976): [DEBUG] seapp_context_lookup: seinfoCategory = chrome
,D/TimaKeyStoreProvider( 4976): in addTimaSignatureService
,D/TimaKeyStoreProvider( 4976): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 4976): Added TimaKesytore provider
,W/ActivityManager(  761): Permission Denial: getCurrentUser() from pid=4956, uid=10002 requires android.permission.INTERACT_ACROSS_USERS
,D/dalvikvm(  761): GC_EXPLICIT freed 2612K, 59% free 23658K/57084K, paused 8ms+16ms, total 194ms
W/ActivityManager(  761): Permission Denial: getCurrentUser() from pid=4976, uid=10081 requires android.permission.INTERACT_ACROSS_USERS
,I/dalvikvm( 1758): Could not find method android.os.PowerManager.isInteractive, referenced from method com.google.android.gms.common.util.y.a
W/dalvikvm( 1758): VFY: unable to resolve virtual method 1378: Landroid/os/PowerManager;.isInteractive ()Z
,D/dalvikvm( 1758): VFY: replacing opcode 0x6e at 0x003d
,D/btif_config_util( 3171): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,D/DelayedSyncController( 4976): Delaying sync.
,I/SELinux ( 5003): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5003):  
,I/SELinux ( 5007): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5007):  
,I/SELinux ( 5003): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5003):  
I/SELinux ( 5003):  
,I/SELinux ( 5003): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 5003): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
,E/dalvikvm( 5003): >>>>> Normal User
,E/dalvikvm( 5003): >>>>> com.google.android.gms.unstable [ userId:0 | appId:10011 ]
,E/SELinux ( 5003): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
,E/ActivityThread( 1758): Failed to find provider info for com.android.contacts.metadata
,D/TimaKeyStoreProvider( 5003): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5003): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5003): Added TimaKesytore provider
,I/SELinux ( 5007): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5007):  
I/SELinux ( 5007):  
,I/SELinux ( 5007): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5007): [DEBUG] seapp_context_lookup: seinfoCategory = release
E/dalvikvm( 5007): >>>>> Normal User
,E/dalvikvm( 5007): >>>>> com.sec.android.fotaclient [ userId:0 | appId:10010 ]
,E/SELinux ( 5007): [DEBUG] seapp_context_lookup: seinfoCategory = release
,D/TimaKeyStoreProvider( 5007): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5007): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5007): Added TimaKesytore provider
,W/ActivityManager(  761): Permission Denial: getCurrentUser() from pid=5007, uid=10010 requires android.permission.INTERACT_ACROSS_USERS
,D/SyncManager(  761): failed sync operation 
,D/SyncManager(  761): not retrying sync operation because the error is a hard error: 
,I/ActivityManager(  761): Killing 3779:com.sec.spp.push:RemoteNotiProcess/u0a38 (adj 15): empty #43
,W/dalvikvm( 5003): VFY: unable to resolve static field 560 (PR_SET_DUMPABLE) in Landroid/system/OsConstants;
,D/dalvikvm( 5003): VFY: replacing opcode 0x60 at 0x000b
,I/dalvikvm( 5003): Could not find method com.google.android.gms.common.app.GmsApplication.getSystemService, referenced from method com.google.android.gms.common.app.GmsApplication.onCreate
W/dalvikvm( 5003): VFY: unable to resolve virtual method 11562: Lcom/google/android/gms/common/app/GmsApplication;.getSystemService (Ljava/lang/Class;)Ljava/lang/Object;
,D/dalvikvm( 5003): VFY: replacing opcode 0x6e at 0x00cd
I/MultiDex( 5003): VM with version 1.6.0 does not have multidex support
,I/MultiDex( 5003): install
,I/MultiDex( 5003): MultiDexExtractor.load(/data/app/com.google.android.gms-2.apk, false)
,I/MultiDex( 5003): loading existing secondary dex files
,I/MultiDex( 5003): load found 3 secondary dex files
,I/MultiDex( 5003): install done
,D/dalvikvm( 5003): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
,W/dalvikvm( 5003): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 5003): VFY: replacing opcode 0x62 at 0x000a
,D/dalvikvm( 5003): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
W/dalvikvm( 5003): VFY: unable to resolve instance field 36
,D/dalvikvm( 5003): VFY: replacing opcode 0x54 at 0x005f
,D/dalvikvm( 5003): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 5003): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 5003): VFY: replacing opcode 0x62 at 0x0047
,D/dalvikvm( 5003): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
,I/dalvikvm( 5003): DexOpt: unable to optimize instance field ref 0x0024 at 0x63 in Lcom/google/android/gms/common/util/ay;.b
,D/dalvikvm( 5003): Trying to load lib /data/app-lib/com.google.android.gms-2/libgmscore.so 0x42645be0
,D/dalvikvm( 5003): Added shared lib /data/app-lib/com.google.android.gms-2/libgmscore.so 0x42645be0
,D/dalvikvm( 5003): No JNI_OnLoad found in /data/app-lib/com.google.android.gms-2/libgmscore.so 0x42645be0, skipping init
,D/dalvikvm( 5003): Trying to load lib /data/app-lib/com.google.android.gms-2/libconscrypt_gmscore_jni.so 0x42645be0
,D/dalvikvm( 5003): Added shared lib /data/app-lib/com.google.android.gms-2/libconscrypt_gmscore_jni.so 0x42645be0
,V/JNIHelp ( 5003): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,I/SELinux ( 5031): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5031):  
,I/HarmonyEASService(  761): Updating for all 1
,I/SELinux ( 5031): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5031):  
I/SELinux ( 5031):  
,I/SELinux ( 5031): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5031): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 5031): >>>>> Normal User
,E/dalvikvm( 5031): >>>>> com.samsung.klmsagent [ userId:0 | appId:10018 ]
,E/SELinux ( 5031): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/dalvikvm( 5003): Trying to load lib /data/app-lib/com.google.android.gms-2/libgmscore.so 0x42645be0
,D/dalvikvm( 5003): Shared lib '/data/app-lib/com.google.android.gms-2/libgmscore.so' already loaded in same CL 0x42645be0
D/dalvikvm( 5003): Trying to load lib /data/app-lib/com.google.android.gms-2/libconscrypt_gmscore_jni.so 0x42645be0
,D/dalvikvm( 5003): Shared lib '/data/app-lib/com.google.android.gms-2/libconscrypt_gmscore_jni.so' already loaded in same CL 0x42645be0
,D/TimaKeyStoreProvider( 5031): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5031): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5031): Added TimaKesytore provider
,I/dalvikvm( 1220): Could not find method android.os.PowerManager.isInteractive, referenced from method com.google.android.gms.common.util.y.a
W/dalvikvm( 1220): VFY: unable to resolve virtual method 1378: Landroid/os/PowerManager;.isInteractive ()Z
,D/dalvikvm( 1220): VFY: replacing opcode 0x6e at 0x003d
,W/ActivityManager(  761): Permission Denial: getCurrentUser() from pid=5031, uid=10018 requires android.permission.INTERACT_ACROSS_USERS
,D/KLMS-2.3.201 : ( 5031): KLMSValidator() : checkQATesting()
,D/PicasaService( 3882): start picasa sync
,D/DelayedSyncController( 4976): Delaying sync.
,D/PicasaService( 3882): end picasa sync
,I/KLMS-2.3.201 : ( 5031): MainReciver() : EventNotificationReciver- method called: AppActivityListner onReceive for Intent Action : android.net.conn.CONNECTIVITY_CHANGE , timestamp: 1453985572356
,I/ProviderInstaller( 5003): Installed default security provider GmsCore_OpenSSL
,I/KLMS-2.3.201 : ( 5031): KLMSUtility() : isNetworkAvailable() - WIFI : true| MOBILE : false
,I/ActivityManager(  761): Killing 4003:com.sec.android.app.videoplayer/u0a52 (adj 15): empty #43
,I/SELinux ( 5051): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5051):  
,I/System.out( 1220): Thread-104(HTTPLog):isShipBuild true
,I/System.out( 1220): Thread-104(HTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,I/LocationTagReadyService( 2368): onStartCommand : Action = com.samsung.android.app.galaxyfinder.tag.start_location_convert
,D/GalaxyFinderApplication( 2368): [Slink platform] The state of Slink geocode service is true
,W/ActivityManager(  761): ProcessRecord{431e3470 4003:com.sec.android.app.videoplayer/u0a52} is already killed by Am(background process)
,D/GalaxyFinderApplication( 2368): [Slink platform] The state of Slink geocode service is true
I/ActivityManager(  761): Existing provider com.sec.android.app.videoplayer/.db.FinDoProvider is crashing; detaching ProcessRecord{431365a8 2368:com.samsung.android.app.galaxyfinder:tagService/u0a34}
,I/SELinux ( 5051): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5051):  
I/SELinux ( 5051):  
,I/SELinux ( 5051): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5051): [DEBUG] seapp_context_lookup: seinfoCategory = release
E/dalvikvm( 5051): >>>>> Normal User
,E/dalvikvm( 5051): >>>>> com.sec.android.soagent [ userId:0 | appId:10037 ]
I/dalvikvm( 5003): Could not find method android.app.Notification$Builder.setLocalOnly, referenced from method com.google.android.gms.common.mz.b
W/dalvikvm( 5003): VFY: unable to resolve virtual method 141: Landroid/app/Notification$Builder;.setLocalOnly (Z)Landroid/app/Notification$Builder;
D/dalvikvm( 5003): VFY: replacing opcode 0x6e at 0x00ce
,E/SELinux ( 5051): [DEBUG] seapp_context_lookup: seinfoCategory = release
,D/GalaxyFinderApplication( 2368): [Slink platform] The state of Slink geocode service is true
,D/TimaKeyStoreProvider( 5051): in addTimaSignatureService
,I/SELinux ( 5063): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5063):  
,D/TimaKeyStoreProvider( 5051): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5051): Added TimaKesytore provider
,I/GallerySearchProvider( 3882): query content://com.sec.android.gallery3d.provider.GallerySearchProvider/search_suggest_tag_query
,I/dalvikvm( 5003): Could not find method android.content.pm.PackageManager.getPackageInstaller, referenced from method com.google.android.gms.common.nb.a
W/dalvikvm( 5003): VFY: unable to resolve virtual method 424: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,D/dalvikvm( 5003): VFY: replacing opcode 0x6e at 0x000d
,I/SELinux ( 5063): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5063):  
I/SELinux ( 5063):  
,I/SELinux ( 5063): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5063): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 5063): >>>>> Normal User
,E/dalvikvm( 5063): >>>>> com.sec.android.app.videoplayer [ userId:0 | appId:10052 ]
,E/SELinux ( 5063): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 5063): in addTimaSignatureService
,I/dalvikvm( 5003): Failed resolving Lcom/google/android/gms/common/j/c; interface 122 'Landroid/content/pm/PackageManager$OnPermissionsChangedListener;'
,D/TimaKeyStoreProvider( 5063): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5063): Added TimaKesytore provider
W/dalvikvm( 5003): Link of class 'Lcom/google/android/gms/common/j/c;' failed
E/dalvikvm( 5003): Could not find class 'com.google.android.gms.common.j.c', referenced from method com.google.android.gms.common.j.b.a
,W/dalvikvm( 5003): VFY: unable to resolve new-instance 2797 (Lcom/google/android/gms/common/j/c;) in Lcom/google/android/gms/common/j/b;
D/dalvikvm( 5003): VFY: replacing opcode 0x22 at 0x0000
I/dalvikvm( 5003): Could not find method android.content.Context.checkSelfPermission, referenced from method com.google.android.gms.common.j.b.b
W/dalvikvm( 5003): VFY: unable to resolve virtual method 274: Landroid/content/Context;.checkSelfPermission (Ljava/lang/String;)I
,D/dalvikvm( 5003): VFY: replacing opcode 0x6e at 0x0036
,I/dalvikvm( 5003): Failed resolving Lcom/google/android/gms/common/j/c; interface 122 'Landroid/content/pm/PackageManager$OnPermissionsChangedListener;'
,W/dalvikvm( 5003): Link of class 'Lcom/google/android/gms/common/j/c;' failed
,D/dalvikvm( 5003): DexOpt: unable to opt direct call 0x32c7 at 0x02 in Lcom/google/android/gms/common/j/b;.a
,W/ActivityManager(  761): Permission Denial: getCurrentUser() from pid=5051, uid=10037 requires android.permission.INTERACT_ACROSS_USERS
,V/KVNProvider( 4026): query uri : content://com.sec.android.app.voicenote.common.util.VNProvider/search_suggest_tag_query
,V/KVNProvider( 4026): getFindoCursor query string : 
,D/SO_AGENT( 5051): [AccRegisterReceiver.java(Line:56/Method:onReceive)] Receive broadcast meassage:android.net.conn.CONNECTIVITY_CHANGE
,I/SO_AGENT( 5051): [AccRegisterReceiver.java(Line:87/Method:onReceive)] Need to accessory setup...
,V/KVNProvider( 4026): getTagSearchCursor() tagSearchCursor count : 0
,I/ActivityManager(  761): Killing 3985:com.android.calendar/u0a142 (adj 15): empty #43
,I/SA      ( 4594): [OR] onReceive log=[SA = 2.0.0117 V = 19 HWD = 1280X720 2.0 dpi = 320  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = kmini3g P = kmini3gxx I = KOT49H M = SM-G800H OKLEFT false DIS KOT49H.G800HXXU1ANK2 PSS = 4.497045606779314  ]
D/WVCdm   (  251): Instantiating CDM.
,I/WVCdm   (  251): Level3 Library Nov 20 2013 18:09:31
,D/DrmWidevineDash(  251): calling OEMCrypto_Initialize, g_qsee_apps_version = 7
,D/QSEECOMAPI: (  251): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  251): App is not loaded in QSEE
E/QSEECOMAPI: (  251): Error::Cannot open the file /vendor/firmware/widevine.mdt
E/QSEECOMAPI: (  251): Error::Loading image failed with ret = -1
D/QSEECOMAPI: (  251): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  251): App is not loaded in QSEE
E/QSEECOMAPI: (  251): Error::Cannot open the file /system/etc/firmware/widevine.mdt
E/QSEECOMAPI: (  251): Error::Loading image failed with ret = -1
D/QSEECOMAPI: (  251): QSEECom_get_handle sb_length = 0x19000
,D/QSEECOMAPI: (  251): App is not loaded in QSEE
,I/SA      ( 4594): [BDLM] already registered in spp
,I/SA      ( 4594): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. ]
,I/SA      ( 4594): [OR] == ACTION_CONNECTIVITY_CHANGE ==
,D/QSEECOMAPI: (  251): Loaded image: APP id = 3
D/DrmWidevineDash(  251): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb22c8000
,E/DrmWidevineDash(  251): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb22c8000
,I/SA      ( 4594): [SLFUCHKMGR] constructor called
I/dalvikvm( 5003): Could not find method android.os.PowerManager.isInteractive, referenced from method com.google.android.gms.common.util.y.a
W/dalvikvm( 5003): VFY: unable to resolve virtual method 1378: Landroid/os/PowerManager;.isInteractive ()Z
,D/dalvikvm( 5003): VFY: replacing opcode 0x6e at 0x003d
D/DrmWidevineDash(  251): OEMCrypto_Initialize exit returns 0
,D/DrmWidevineDash(  251): calling OEMCrypto_APIVersion...
D/DrmWidevineDash(  251): OEMCrypto_APIVersion = 8
,D/DrmWidevineDash(  251): calling OEMCrypto_IsKeyboxValid...
,W/dalvikvm( 5003): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 5003): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 5003): VFY: unable to find class referenced in signature (Landroid/net/Network;)
I/dalvikvm( 5003): Could not find method android.net.Network.openConnection, referenced from method com.google.android.gms.http.g.a
W/dalvikvm( 5003): VFY: unable to resolve virtual method 1007: Landroid/net/Network;.openConnection (Ljava/net/URL;)Ljava/net/URLConnection;
,D/dalvikvm( 5003): VFY: replacing opcode 0x6e at 0x00bb
I/SA      ( 4594): [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
,I/SA      ( 4594): [OR] == isSIMCardReady false ==
D/DrmWidevineDash(  251): OEMCrypto_IsKeyboxValid returns 0
,D/WVCdm   (  251): OEMCrypto_Initialize Level 1 success. I will use level 1.
I/WVCdm   (  251): CdmEngine::OpenSession
,D/DrmWidevineDash(  251): calling OEMCrypto_OpenSession...
,I/GoogleURLConnFactory( 5003): Using platform SSLCertificateSocketFactory
,D/DrmWidevineDash(  251): OEMCrypto_OpenSession SID = 1
,D/DrmWidevineDash(  251): OEMCrypto_OpenSession returns 0
,I/SA      ( 4594): [SCU] == networkStateCheck == true
I/SA      ( 4594): [DM] getCountryCodeFromCSC : PL
I/SA      ( 4594): isChinaCountryCode : false
,I/SA      ( 4594): [OR] == networkStateCheck true ==
,I/WVCdm   (  251): CdmEngine::QueryKeyControlInfo
I/WVCdm   (  251): CdmEngine::GenerateKeyRequest
,D/DrmWidevineDash(  251): calling OEMCrypto_LoadDeviceRSAKey. SID = 1
,D/DrmWidevineDash(  251): OEMCrypto_LoadDeviceRSAKey returns 0
,D/DrmWidevineDash(  251): calling OEMCrypto_GetDeviceID...
,I/SA      ( 4594): [OR] GetMyCountryZoneTask
,I/SA      ( 4594): [OR] onReceive END
,I/System.out( 5003): Thread-482(HTTPLog):isShipBuild true
,I/System.out( 5003): Thread-482(HTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
D/DrmWidevineDash(  251): OEMCrypto_GetDeviceID returns 0
,D/DrmWidevineDash(  251): calling OEMCrypto_GenerateNonce. SID = 1
D/DrmWidevineDash(  251): OEMCrypto_GenerateNonce returns 0
D/WVCdm   (  251): PrepareKeyRequest: nonce=1762478484
,D/DrmWidevineDash(  251): calling OEMCrypto_GenerateRSASignature. SID = 1
,I/ActivityManager(  761): Killing 4050:com.android.providers.calendar/u0a44 (adj 15): empty #43
D/DrmWidevineDash(  251): OEMCrypto_GenerateRSASignature needs buffer size = 256
D/DrmWidevineDash(  251): OEMCrypto_GenerateRSASignature returns 7
D/DrmWidevineDash(  251): calling OEMCrypto_GenerateRSASignature. SID = 1
,I/SA      ( 4594): [SRS] prepareGetMyCountryZone
,I/dalvikvm( 4532): Total arena pages for JIT: 11
,I/dalvikvm( 4532): Total arena pages for JIT: 12
I/dalvikvm( 4532): Total arena pages for JIT: 13
,I/dalvikvm( 4532): Total arena pages for JIT: 14
,D/PhoneNumberLocatorBootCompletedReceiver( 1241): onReceive
,D/PhoneNumberLocatorBootCompletedReceiver( 1241): Phone number locator feature is dsiabled
,E/SMD     (  242): DCD OFF
,I/SELinux ( 5091): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5091):  
,I/jxcore-log( 4558): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMultiplex.js
I/jxcore-log( 4558): 
,I/SA      ( 4594): [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
,I/SA      ( 4594): [SSP] query invoked
,I/SELinux ( 5091): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5091):  
I/SELinux ( 5091):  
,I/SELinux ( 5091): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5091): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 5091): >>>>> Normal User
,E/dalvikvm( 5091): >>>>> com.samsung.android.scloud.backup [ userId:0 | appId:10060 ]
,E/SELinux ( 5091): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 5091): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5091): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5091): Added TimaKesytore provider
,I/SA      ( 4594): [TPMU] GetMccFromDB : null
I/SA      ( 4594): [SCU] getMccFromPreferece mcc = 260
,I/SA      ( 4594): [TPM] isNoProxy(default) : true
,D/DrmWidevineDash(  251): OEMCrypto_GenerateRSASignature returns 0
I/WVCdm   (  251): CdmEngine::CloseSession
,D/DrmWidevineDash(  251): calling OEMCrypto_CloseSession. SID = 1
,D/DrmWidevineDash(  251): OEMCrypto_CloseSession returns 0
,I/SA      ( 4594): [RC New] Execute method=[GET] start
,I/System.out( 5007): Thread-486(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
,I/System.out( 5007): Thread-486(ApacheHTTPLog):isShipBuild true
,I/System.out( 5007): Thread-486(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,W/ActivityThread( 4532): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,D/NativeLibraryUtils( 5003): Install completed successfully. count=14 extracted=0
,I/sCloudBackupApp( 5091): sCloudBackupApp Version Info : 3.7.3.KK_APP
,I/SCloudBackupReceiver( 5091): Other Intent
I/ActivityManager(  761): Killing 4055:com.sec.android.widgetapp.SPlannerAppWidget/u0a143 (adj 15): empty #43
,D/com.samsung.app( 1447): [KK_EASY_Accu]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/com.samsung.app( 1447): [KK_EASY_Accu]>>> WC:37 [0:0] oR : create UI manager : start
,D/com.samsung.app( 1447): [KK_EASY_Accu]>>> UIMEM:89 [0:0] getInstance
,D/com.samsung.app( 1447): [KK_EASY_Accu]>>> UIMEM:77 [0:0] UIManager : create ui manager
,D/accuweather( 1447): [KK AccuPhone]>>> RM:73 [0:0] RefreshManager : create
,D/accuweather( 1447): [KK AccuPhone]>>> RM:136 [0:0]  V init 
,D/daemonapp( 1465): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/accuweather( 1447): [KK AccuPhone]>>> RM:128 [0:0] updateCityList
,D/daemonapp( 1465): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,D/accuweather( 1447): [KK AccuPhone]>>> DBH:3047 [0:0] gADWI : count = 0
,D/daemonapp( 1465): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/com.samsung.app( 1447): [KK_EASY_Accu]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
,D/com.samsung.app( 1447): [KK_EASY_Accu]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
,I/SELinux ( 5107): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5107):  
,I/System.out( 4532): Thread-444(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
,I/System.out( 4532): Thread-444(ApacheHTTPLog):isShipBuild true
,I/System.out( 4532): Thread-444(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,I/SELinux ( 5107): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5107):  
I/SELinux ( 5107):  
,I/SELinux ( 5107): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5107): [DEBUG] seapp_context_lookup: seinfoCategory = release
E/dalvikvm( 5107): >>>>> Normal User
,E/dalvikvm( 5107): >>>>> com.samsung.android.internal.headlines [ userId:0 | appId:10106 ]
,E/SELinux ( 5107): [DEBUG] seapp_context_lookup: seinfoCategory = release
,I/System.out( 5007): AsyncTask #1 calls detatch()
,D/TimaKeyStoreProvider( 5107): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5107): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5107): Added TimaKesytore provider
,W/System.err( 5007): com.sec.android.fota.osp.http.RestClientException
,W/System.err( 5007): 	at com.sec.android.fota.osp.http.RestClient.execute(RestClient.java:293)
W/System.err( 5007): 	at com.sec.android.fotaclient.network.NetConnect$1.doInBackground(NetConnect.java:50)
W/System.err( 5007): 	at com.sec.android.fotaclient.network.NetConnect$1.doInBackground(NetConnect.java:36)
W/System.err( 5007): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
,D/HeadlinesChannelApplication( 5107): [onCreate]
W/System.err( 5007): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
,W/System.err( 5007): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
,W/ActivityManager(  761): Permission Denial: getCurrentUser() from pid=5107, uid=10106 requires android.permission.INTERACT_ACROSS_USERS
W/System.err( 5007): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
D/Headlines( 5107): HeadlinesSystemBroadcastReceiver onReceive android.net.conn.CONNECTIVITY_CHANGE
W/System.err( 5007): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/System.err( 5007): 	at java.lang.Thread.run(Thread.java:841)
W/System.err( 5007): Caused by: java.lang.NullPointerException
W/System.err( 5007): 	at com.sec.android.fota.osp.util.AuthUtil.normalizeUrl(AuthUtil.java:239)
W/System.err( 5007): 	at com.sec.android.fota.osp.util.AuthUtil.getSignSourceString(AuthUtil.java:157)
W/System.err( 5007): 	at com.sec.android.fota.osp.util.HeaderUtil.generateAuthorizationHeader(HeaderUtil.java:124)
W/System.err( 5007): 	at com.sec.android.fota.osp.http.RestClient.execute(RestClient.java:132)
W/System.err( 5007): 	... 8 more
,D/HeadlinesChannelUtil( 5107): getCountryCode(): countryCode = PL
,I/ActivityManager(  761): Killing 3991:com.sec.phone/1001 (adj 15): empty #43
D/Headlines( 5107): Breath.onCreate
D/HeadlinesCardManager( 5107): HeadlinesCardManager : constructor
E/HeadlinesCardManager( 5107): HeadlinesCardManager : ctor = image_cache size is 42MB
D/SA Version( 5107): CardProvider Library : 13
,I/SELinux ( 5120): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5120):  
,D/MagazineService::CardProviderContentProvider( 4676): insertProvider: provider already exists.: com.samsung.android.app.headlines
,I/SELinux ( 5120): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5120):  
I/SELinux ( 5120):  
,I/SELinux ( 5120): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5120): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 5120): >>>>> Normal User
E/dalvikvm( 5120): >>>>> com.google.android.apps.magazines [ userId:0 | appId:10112 ]
,D/MagazineService::CardProviderContentProvider( 4676): insertProvider: provider is updated.: com.samsung.android.app.headlines
,D/com.samsung.android.magazine.cardprovider.ConfigurationManager( 5107): registerCardProvider: provider already exists.
,E/SELinux ( 5120): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
,I/Headlines( 5107): HeadlinesDataCenter ctor
I/Headlines( 5107): HeadlinesDataCenter. mLocale = en_US
,D/HeadlinesChannelUtil( 5107): getCountryCode(): countryCode = PL
,D/HeadlinesCardManager( 5107): HeadlinesCardManager : constructor welcome :YES
,D/TimaKeyStoreProvider( 5120): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5120): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5120): Added TimaKesytore provider
,D/Headlines( 5107): Breath timer started. interval : 30000
D/Headlines( 5107): Breath.onStartCommand : com.samsung.android.internal.headlines.UPDATE_WELCOME_CARD flag : 0
D/HeadlinesCardManager( 5107): updateCategory : HeadlinesCardManager:updateCategory() category size == 0
,D/HeadlinesCardManager( 5107): updateCategory : HeadlinesCardManager:updateCategory() try to query category list
D/Headlines( 5107): queryCategory.  mRequest is not initialized.
D/HeadlinesCardManager( 5107): updateCategory : HeadlinesCardManager:updateCategory() reponse : false
D/HeadlinesCardManager( 5107): requestUpdateNewsWelcomeCard : request update welcome card to content card.
,D/HeadlinesDataCenter( 5107): requestUpdateNewsWelcomeCard !!! no welcome card
,I/System.out( 4594): Thread-449(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
,D/dalvikvm( 5003): GC_CONCURRENT freed 5953K, 39% free 11756K/19088K, paused 13ms+5ms, total 105ms
,E/WifiStateMachine(  761): CAPTIVE_PORTAL_EVENT_AUTHENTICATED
,D/dalvikvm( 1312): GC_EXPLICIT freed 914K, 44% free 10820K/19088K, paused 44ms+48ms, total 167ms
,D/dalvikvm( 5003): Trying to load lib /data/data/com.google.android.gms/app_dg_cache/69C93D89AA87E126AABFDE6B8111A5045CA28EB7/lib/libd24C93342F304.so 0x429b97b0
D/dalvikvm( 5003): Added shared lib /data/data/com.google.android.gms/app_dg_cache/69C93D89AA87E126AABFDE6B8111A5045CA28EB7/lib/libd24C93342F304.so 0x429b97b0
,D/dalvikvm( 5003): No JNI_OnLoad found in /data/data/com.google.android.gms/app_dg_cache/69C93D89AA87E126AABFDE6B8111A5045CA28EB7/lib/libd24C93342F304.so 0x429b97b0, skipping init
,I/ActivityManager(  761): Killing 3932:com.sec.android.app.music:service/u0a150 (adj 15): empty #43
,I/SurfaceFlinger(  248): id=18 Removed Uoast (11/12)
,I/SurfaceFlinger(  248): id=18 Removed Uoast (-2/12)
,D/KeyguardUpdateMonitor( 1069): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1069): handleKeyguardVisibilityChanged(1)
D/PowerManagerService(  761): [api] release WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=761 (0x0)
D/PowerManagerService(  761): [api] applyWakeLockFlagsOnReleaseLocked : userActivityNoUpdateLocked is called : SCREEN_BRIGHT_WAKE_LOCK        'WindowManager' ON_AFTER_RELEASE (uid=1000, pid=761, ws=WorkSource{1000}) (elapsedTime=3469)
,I/System.out( 4594): Thread-449(ApacheHTTPLog):isShipBuild true
,I/System.out( 4594): Thread-449(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,E/cutils  (  229): Failed to mkdirat(/storage/extSdCard/Android): Read-only file system
,W/Vold    (  229): Returning OperationFailed - no handler for errno 30
,W/ContextImpl( 5120): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,E/cutils  (  229): Failed to mkdirat(/storage/extSdCard/Android): Read-only file system
,W/GAV2    ( 5120): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,W/ContextImpl( 5120): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
D/STATUSBAR-NetworkController_dual( 1069): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews start
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews set mobileLabel[SIM_0] =
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews GONE
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews2 set mobileLabel[SIM_1] =
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews2 GONE
D/StatusBar.NetworkController_dual( 1069): mSingleMobileLabelViews set : simMode = 0
D/StatusBar.NetworkController_dual( 1069): mSingleMobileLabelViews set as slot1`s
W/Vold    (  229): Returning OperationFailed - no handler for errno 30
,E/cutils  (  229): Failed to mkdirat(/storage/extSdCard/Android): Read-only file system
,W/ContextImpl( 5120): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
W/Vold    (  229): Returning OperationFailed - no handler for errno 30
,E/cutils  (  229): Failed to mkdirat(/storage/extSdCard/Android): Read-only file system
,W/ContextImpl( 5120): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,D/dalvikvm( 5003): DexOpt: --- BEGIN 'f.apk' (bootstrap=0) ---
W/Vold    (  229): Returning OperationFailed - no handler for errno 30
,W/DriveInitializer( 1758): Awaiting to be initialized
,W/DriveInitializer( 1758): Background init thread started
,E/cutils  (  229): Failed to mkdirat(/storage/extSdCard/Android): Read-only file system
,W/ContextImpl( 1758): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.gms/files
W/Vold    (  229): Returning OperationFailed - no handler for errno 30
,D/dalvikvm( 5143): DexOpt: load 4ms, verify+opt 5ms, 128252 bytes
,D/dalvikvm( 5003): DexOpt: --- END 'f.apk' (success) ---
,D/dalvikvm( 5003): DEX prep '/data/data/com.google.android.gms/app_fb/f.apk': unzip in 0ms, rewrite 134ms
,W/DriveInitializer( 1758): Background init thread ended
,I/Adreno-EGL( 5003): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 5003): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 5003): Build Date: 03/21/14 Fri
I/Adreno-EGL( 5003): Local Branch: AU200+patches_03212014
I/Adreno-EGL( 5003): Remote Branch: 
I/Adreno-EGL( 5003): Local Patches: 
I/Adreno-EGL( 5003): Reconstruct Branch: 
,V/WebViewChromium( 5120): Binding Chromium to the main looper Looper (main, tid 1) {423251f8}
,I/chromium( 5120): [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserProcessMain( 5120): Initializing chromium process, renderers=0
,D/dalvikvm( 1758): GC_CONCURRENT freed 1664K, 36% free 12233K/19088K, paused 8ms+4ms, total 81ms
,W/chromium( 5120): [WARNING:proxy_service.cc(888)] PAC support disabled because there is no system implementation
,I/dalvikvm( 1312): Total arena pages for JIT: 11
,I/dalvikvm( 1312): Total arena pages for JIT: 12
I/dalvikvm( 1312): Total arena pages for JIT: 13
,I/dalvikvm( 1312): Total arena pages for JIT: 14
,I/Adreno-EGL( 5120): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 5120): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 5120): Build Date: 03/21/14 Fri
I/Adreno-EGL( 5120): Local Branch: AU200+patches_03212014
I/Adreno-EGL( 5120): Remote Branch: 
I/Adreno-EGL( 5120): Local Patches: 
I/Adreno-EGL( 5120): Reconstruct Branch: 
,I/dalvikvm( 1312): Could not find method android.os.PowerManager.isInteractive, referenced from method com.google.android.gms.common.util.y.a
W/dalvikvm( 1312): VFY: unable to resolve virtual method 1378: Landroid/os/PowerManager;.isInteractive ()Z
,D/dalvikvm( 1312): VFY: replacing opcode 0x6e at 0x003d
,I/jxcore-log( 4558): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js
I/jxcore-log( 4558): 
,I/System.out( 4532): Thread-444 calls detatch()
,I/System.out( 1312): Thread-89(HTTPLog):isShipBuild true
,I/System.out( 1312): Thread-89(HTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,I/dalvikvm( 4532): Total arena pages for JIT: 15
,I/dalvikvm( 4532): Total arena pages for JIT: 16
I/dalvikvm( 4532): Total arena pages for JIT: 17
,I/dalvikvm( 4532): Total arena pages for JIT: 18
I/dalvikvm( 4532): Total arena pages for JIT: 19
I/dalvikvm( 4532): Total arena pages for JIT: 20
,I/dalvikvm( 4532): Total arena pages for JIT: 21
,I/dalvikvm( 4532): Total arena pages for JIT: 22
I/dalvikvm( 4532): Total arena pages for JIT: 23
I/dalvikvm( 4532): Total arena pages for JIT: 24
,I/dalvikvm( 4532): Total arena pages for JIT: 25
,I/dalvikvm( 4532): Total arena pages for JIT: 26
I/dalvikvm( 4532): Total arena pages for JIT: 27
,I/dalvikvm( 4532): Total arena pages for JIT: 28
,I/dalvikvm( 4532): Total arena pages for JIT: 29
,I/dalvikvm( 4532): Total arena pages for JIT: 30
,I/dalvikvm( 4532): Total arena pages for JIT: 31
,I/dalvikvm( 4532): Total arena pages for JIT: 32
I/dalvikvm( 4532): Total arena pages for JIT: 33
,I/dalvikvm( 4532): Total arena pages for JIT: 34
I/dalvikvm( 4532): Total arena pages for JIT: 35
,I/dalvikvm( 4532): Total arena pages for JIT: 36
I/dalvikvm( 4532): Total arena pages for JIT: 37
I/dalvikvm( 4532): Total arena pages for JIT: 38
,I/dalvikvm( 4532): Total arena pages for JIT: 39
,I/dalvikvm( 4532): Total arena pages for JIT: 40
,I/dalvikvm( 4532): Total arena pages for JIT: 41
,I/dalvikvm( 4532): Total arena pages for JIT: 42
,I/dalvikvm( 4532): Total arena pages for JIT: 43
I/dalvikvm( 4532): Total arena pages for JIT: 44
,I/dalvikvm( 4532): Total arena pages for JIT: 45
,I/jxcore-log( 4558): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
I/jxcore-log( 4558): 
,I/jxcore-log( 4558): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliCryptoManager.js
I/jxcore-log( 4558): 
,D/dalvikvm(  761): GC_EXPLICIT freed 1600K, 59% free 23539K/57084K, paused 7ms+12ms, total 145ms
,I/NSApplication( 5120): Starting up...
,W/ActivityManager(  761): Permission Denial: getCurrentUser() from pid=5120, uid=10112 requires android.permission.INTERACT_ACROSS_USERS
,D/QuickConnect[1.1][2] ( 3142): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,I/QuickConnect[1.1][2] ( 3142): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
,V/QuickConnect[1.1][2] ( 3142): SconnectManager.getInstance - () return existing instance com.samsung.android.sconnect.SconnectManager@42659df0
,I/jxcore-log( 4558): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliEmitter.js
I/jxcore-log( 4558): 
I/ActivityManager(  761): Killing 3040:com.google.android.talk/u0a105 (adj 15): empty #43
,D/dalvikvm( 4193): GC_FOR_ALLOC freed 4063K, 38% free 11949K/19088K, paused 29ms, total 31ms
,I/SELinux ( 5179): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5179):  
,I/jxcore-log( 4558): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNativeLayer.js
I/jxcore-log( 4558): 
,D/dalvikvm(  249): GC_EXPLICIT freed 43K, 51% free 9510K/19088K, paused 3ms+2ms, total 27ms
,I/dalvikvm-heap( 4193): Grow heap (frag case) to 17.063MB for 2129936-byte allocation
,I/jxcore-log( 4558): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationManager.js
I/jxcore-log( 4558): 
,D/dalvikvm(  249): GC_EXPLICIT freed <1K, 51% free 9510K/19088K, paused 2ms+2ms, total 20ms
,I/jxcore-log( 4558): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
I/jxcore-log( 4558): 
,D/dalvikvm( 4193): GC_CONCURRENT freed 32K, 27% free 14009K/19088K, paused 3ms+3ms, total 20ms
I/SELinux ( 5179): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5179):  
I/SELinux ( 5179):  
,I/SELinux ( 5179): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5179): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 5179): >>>>> Normal User
,E/dalvikvm( 5179): >>>>> com.android.email [ userId:0 | appId:10155 ]
,E/SELinux ( 5179): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/dalvikvm(  249): GC_EXPLICIT freed <1K, 51% free 9510K/19088K, paused 2ms+3ms, total 21ms
,D/TimaKeyStoreProvider( 5179): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5179): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5179): Added TimaKesytore provider
,W/PhenotypeConfigurator( 1220): Server returned 404
,D/RCPManagerService(  761): exchangeData() failure , invalid userId
,D/RCPManagerService(  761): exchangeData() failure , invalid userId
,D/RCPManagerService(  761): exchangeData() failure , invalid userId
,W/WifiP2pStateTracker(  761): WifiP2pStateReceiver : android.net.wifi.LINK_CONFIGURATION_CHANGED
,D/ConnectivityService(  761): handleConnectivityChange: addresses changed linkProperty[1]: resetMask=0
D/ConnectivityService(  761):    car=removed=[] added=[fe80::3a94:96ff:feb5:6dd/64,]
,D/ConnectivityService(  761): handleConnectivityChange: setting default proxy info 
,D/ConnectivityService(  761): updateSourceRoutes : no source routing conditions
,D/RCPManagerService(  761): exchangeData() failure , invalid userId
,I/SELinux ( 5197): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5197):  
,W/ActivityManager(  761): Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
,D/RCPManagerService(  761): exchangeData() failure , invalid userId
,D/RCPManagerService(  761): exchangeData() failure , invalid userId
,I/SELinux ( 5197): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5197):  
I/SELinux ( 5197):  
,I/SELinux ( 5197): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5197): [DEBUG] seapp_context_lookup: seinfoCategory = release
E/dalvikvm( 5197): >>>>> Normal User
,E/dalvikvm( 5197): >>>>> com.sec.android.provider.badge [ userId:0 | appId:10072 ]
,E/SELinux ( 5197): [DEBUG] seapp_context_lookup: seinfoCategory = release
,I/SELinux ( 5212): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5212):  
,D/TimaKeyStoreProvider( 5197): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5197): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5197): Added TimaKesytore provider
I/ActivityManager(  761): Killing 4075:com.sec.providers.settingsearch/u0a160 (adj 15): empty #43
,I/ActivityManager(  761): Killing 2905:com.sec.knox.bridge/1000 (adj 15): empty #43
,I/SELinux ( 5212): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5212):  
I/SELinux ( 5212):  
,I/SELinux ( 5212): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5212): [DEBUG] seapp_context_lookup: seinfoCategory = shared
E/dalvikvm( 5212): >>>>> Normal User
,E/dalvikvm( 5212): >>>>> com.samsung.android.service.travel [ userId:0 | appId:10169 ]
,E/SELinux ( 5212): [DEBUG] seapp_context_lookup: seinfoCategory = shared
,D/TimaKeyStoreProvider( 5212): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5212): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5212): Added TimaKesytore provider
,D/BadgeProvider( 5197): onCreate
,D/BadgeProvider( 5197): DatabaseHelper
W/ActivityManager(  761): Permission Denial: getCurrentUser() from pid=5197, uid=10072 requires android.permission.INTERACT_ACROSS_USERS
,D/BadgeProvider( 5197): query, [selection] : package='com.android.email' AND class='com.android.email.activity.Welcome' AND extraData='base_extra_badge'
,D/BadgeProvider( 5197): sendNotify entered. [uri] : content://com.sec.badge/apps/1
D/BadgeProvider( 5197): sendNotify, [notify] : null
D/BadgeProvider( 5197): update, [uri] : content://com.sec.badge/apps/1
D/BadgeProvider( 5197): update, [BadgeCount] : badgecount=0
,D/BadgeProvider( 5197): update, [UpdateCount] : 1
,D/Launcher.Model( 1252): reloadBadges entered.
W/ActivityManager(  761): Permission Denial: getCurrentUser() from pid=5212, uid=10169 requires android.permission.INTERACT_ACROSS_USERS
,D/WaitQueueForNetworkActivate( 4727): notifyNetworkActivated
,W/ContextImpl( 4727): Implicit intents with startService are not safe: Intent { act=com.sec.knox.containeragent.service.containermanager.ContainerManagerService } android.content.ContextWrapper.bindService:529 com.sec.knox.containeragent.ContainerManager.<init>:49 com.sec.android.app.samsungapps.vlibrary2.knoxmode.KNOXAPI.<init>:20 
W/ActivityManager(  761): Unable to start service Intent { act=com.sec.knox.containeragent.service.containermanager.ContainerManagerService } U=0: not found
,I/SA      ( 4594): [RC New] [v2liruge] api execute + 1919
,I/SA      ( 4594): [RC New] executeRequest [v2liruge] httpResponse : HTTP/1.1 200 OK
,I/System.out( 4594): AsyncTask #1 calls detatch()
,I/SA      ( 4594): [TPMU] getNetworkMcc : 
,I/SA      ( 4594): [SCU] saveMccToPreferece Start
,I/SA      ( 4594): [SCU] RegionMCC : 260
,I/SA      ( 4594): [SSP] query invoked
I/SA      ( 4594): [TPMU] GetMccFromDB : null
,I/SA      ( 4594): [SCU] getMccFromPreferece mcc = 260
,I/SA      ( 4594): [SCU] saveMccToPreferece End
,I/SA      ( 4594): [RC New] executeRequest [v2liruge] end. 1939
,I/SA      ( 4594): [RC New] Execute end
,I/SA      ( 4594): [OR] GetMyCountryZoneTask mcc = 260
,I/SA      ( 4594): [OR] GetMyCountryZoneTask Success
,V/GLSActivity( 1312): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1312): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/dalvikvm( 1312): VFY: unable to find class referenced in signature (Landroid/net/Network;)
E/dalvikvm( 1312): Could not find class 'android.net.Network', referenced from method com.google.android.gms.http.l.a
W/dalvikvm( 1312): VFY: unable to resolve check-cast 229 (Landroid/net/Network;) in Lcom/google/android/gms/http/l;
,D/dalvikvm( 1312): VFY: replacing opcode 0x1f at 0x0011
,D/hcjo    ( 4727): AutoUpdateManager:IDLE:execute
,I/dalvikvm( 4727): Could not find method android.view.Window.setStatusBarColor, referenced from method com.sec.android.app.samsungapps.CommonActivity.onCreate
,W/dalvikvm( 4727): VFY: unable to resolve virtual method 14867: Landroid/view/Window;.setStatusBarColor (I)V
,D/dalvikvm( 4727): VFY: replacing opcode 0x6e at 0x0024
,I/CheckinService( 1758): Checkin interval check for package: unspecified last checkin: 1452516764897 min interval config: 0 actual interval: 1468810290
D/InitializeManagerStateMachine( 4727): execute::IDLE:EXECUTE
,D/InitializeManagerStateMachine( 4727): exit::IDLE
,D/InitializeManagerStateMachine( 4727): entry::NETWORK_CHECK
,D/InitializeManagerStateMachine( 4727): execute::NETWORK_CHECK:NETWORK_STATE_OK
D/InitializeManagerStateMachine( 4727): exit::NETWORK_CHECK
D/InitializeManagerStateMachine( 4727): entry::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 4727): execute::CHECK_COUNTRY_INFO:COUNTRY_INFO_OK
D/InitializeManagerStateMachine( 4727): exit::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 4727): entry::SUCCESS
,D/hcjo    ( 4727): AutoUpdateManager:INITCHECK:onInitializeSuccess
,D/hcjo    ( 4727): AutoUpdateTriggerManager:REQUEST2:requestInterval
,I/CheckinService( 1758): Checking schedule, now: 1453985575217 next: 1453104290804
,I/CheckinService( 1758): active receiver: enabled
,I/Volley  ( 4727): RestApi Request Add : 2307
,E/File    ( 4727): fail readDirectory() errno=2
,I/CheckinService( 1758): Preparing to send checkin request
,I/EventLogService( 1758): Accumulating logs since 1453985517813
,E/Watchdog(  761): !@Sync 3
,I/iu.SyncManager( 1758): SYNC; picasa accounts
,D/NetworkLogImpl( 1758): Loaded NetworkSpeedPredictor
,I/iu.Environment( 1758): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,I/iu.UploadsManager( 1758): num queued entries: 0
,I/iu.UploadsManager( 1758): num updated entries: 0
,I/iu.SyncManager( 1758): NEXT; no task
,I/SELinux ( 5238): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5238):  
,I/SELinux ( 5238): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5238):  
I/SELinux ( 5238):  
,I/SELinux ( 5238): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5238): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 5238): >>>>> Normal User
,E/dalvikvm( 5238): >>>>> com.android.calendar [ userId:0 | appId:10142 ]
,E/SELinux ( 5238): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,I/CheckinRequestBuilder( 1758): Checkin reason type: 12 attempt count: 1
,D/TimaKeyStoreProvider( 5238): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5238): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5238): Added TimaKesytore provider
E/ActivityThread( 1758): Failed to find provider info for com.google.android.wearable.settings
,D/dalvikvm( 1312): GC_CONCURRENT freed 1921K, 43% free 10908K/19088K, paused 11ms+5ms, total 36ms
,I/GCM     ( 1312): GCM config loaded
,I/VacuumService( 1220): Vacuum at: now=1453985575621 tag=VacuumService
I/ActivityManager(  761): Killing 4243:com.wssyncmldm/1000 (adj 15): empty #43
,D/GCM     ( 1312): GcmService start Intent { act=com.google.android.c2dm.intent.REGISTER pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.c2dm.intent.REGISTER
,D/BootCompletedReceiver(  761): onReceive
,W/InstanceID/Rpc( 1312): Found 10011
,I/KLMS-2.3.201 : ( 5031): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,I/dalvikvm( 1758): Could not find method android.security.NetworkSecurityPolicy.getInstance, referenced from method com.google.android.gms.ads.internal.t.e.a
,W/dalvikvm( 1758): VFY: unable to resolve static method 1032: Landroid/security/NetworkSecurityPolicy;.getInstance ()Landroid/security/NetworkSecurityPolicy;
,D/dalvikvm( 1758): VFY: replacing opcode 0x71 at 0x004e
,D/dalvikvm( 1758): DexOpt: --- BEGIN 'ads1363035432.jar' (bootstrap=0) ---
,D/dalvikvm( 1220): GC_CONCURRENT freed 1576K, 39% free 11760K/19088K, paused 5ms+5ms, total 47ms
,I/KLMS-2.3.201 : ( 5031): MainReciver() : EventNotificationReciver- method called: AppActivityListner onReceive for Intent Action : android.intent.action.TIME_SET , timestamp: 1453985575779
,I/KLMS-2.3.201 : ( 5031): StateImplV2() : dateTimeChanged() : Thu Jan 28 13:52:55 CET 2016
,D/SO_AGENT( 5051): [ServerTimeReceiver.java(Line:44/Method:onReceive)] Receive broadcast meassage:android.intent.action.TIME_SET
,I/SO_AGENT( 5051): [ServerTimeReceiver.java(Line:47/Method:onReceive)] No action is available before server time settings
,I/SA      ( 4594): [SBR] StdBroadcastReceiver received Intent of  action.TIME_SET.
,D/Mms/MessagingNotification( 3818): [start]    nonBlockingUpdateMessageIndicator()
,D/Mms/MessagingNotification( 3818): sDisableVibrateForCamera = false
,D/Mms/MessagingNotification( 3818): isBlockingModeEnable() = false
,D/Mms/TelephonyPermission( 3818): isDefault true
,D/TP/MmsSmsProvider( 1241): match 8:Elapsed time : 11.016 ms
,I/SELinux ( 5274): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5274):  
,D/TP/MmsSmsProvider( 1241): match 200:Elapsed time : 1.347 ms
,E/SMD     (  242): DCD OFF
V/AlarmManager(  761): waitForAlarm result :4
V/AlarmManager(  761): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,I/PCWCLIENTTRACE_SYSTEMReceiver( 4411): mConnectivityHandler : connected
,I/SELinux ( 5274): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5274):  
I/SELinux ( 5274):  
,I/SELinux ( 5274): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5274): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 5274): >>>>> Normal User
,E/dalvikvm( 5274): >>>>> com.samsung.android.scloud.sync [ userId:0 | appId:10062 ]
,E/SELinux ( 5274): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,W/PCWCLIENTTRACE_AccountUtil( 4411): [hasSamungAccount] - No Samsung Account
,I/GCM     ( 1312): GCM message com.google.android.gms 0:1452698630707545%136ddda6f9fd7ecd
,D/TimaKeyStoreProvider( 5274): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5274): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5274): Added TimaKesytore provider
,D/BadgeProvider( 5197): query, [selection] : package='com.android.mms' AND class='com.android.mms.ui.ConversationComposer' AND extraData='base_extra_badge'
,I/GCM     ( 1312): GCM message com.google.android.gms 0:1452758501254490%136ddda6f9fd7ecd
,I/dalvikvm( 1758): Could not find method android.content.Context.getNoBackupFilesDir, referenced from method com.google.android.gms.iid.n.<init>
W/dalvikvm( 1758): VFY: unable to resolve virtual method 378: Landroid/content/Context;.getNoBackupFilesDir ()Ljava/io/File;
,D/dalvikvm( 1758): VFY: replacing opcode 0x6e at 0x002c
I/dalvikvm( 1758): Could not find method android.content.Context.getDrawable, referenced from method android.support.v4.content.g.a
W/dalvikvm( 1758): VFY: unable to resolve virtual method 287: Landroid/content/Context;.getDrawable (I)Landroid/graphics/drawable/Drawable;
,D/dalvikvm( 1758): VFY: replacing opcode 0x6e at 0x0006
I/dalvikvm( 1758): Could not find method android.content.Context.getColor, referenced from method android.support.v4.content.g.b
W/dalvikvm( 1758): VFY: unable to resolve virtual method 283: Landroid/content/Context;.getColor (I)I
,D/dalvikvm( 1758): VFY: replacing opcode 0x6e at 0x0006
,D/BadgeProvider( 5197): sendNotify entered. [uri] : content://com.sec.badge/apps/2
D/BadgeProvider( 5197): sendNotify, [notify] : null
D/BadgeProvider( 5197): update, [uri] : content://com.sec.badge/apps/2
D/BadgeProvider( 5197): update, [BadgeCount] : badgecount=0
,D/BadgeProvider( 5197): update, [UpdateCount] : 1
,D/Launcher.Model( 1252): reloadBadges entered.
,I/GCM     ( 1312): GCM message com.google.android.gms 0:1452824098059201%136ddda6f9fd7ecd
,D/ConnectivityService(  761): handleInetConditionHoldEnd: net=1, condition=100, published condition=0
,D/Mms/MessagingNotification( 3818): setBadgeCount(), count=0
D/STATUSBAR-NetworkController_dual( 1069): onReceive() - CONNECTIVITY_ACTION, INET_CONDITION_ACTION
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews start
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews set mobileLabel[SIM_0] =
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews GONE
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews2 set mobileLabel[SIM_1] =
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews2 GONE
D/StatusBar.NetworkController_dual( 1069): mSingleMobileLabelViews set : simMode = 0
D/StatusBar.NetworkController_dual( 1069): mSingleMobileLabelViews set as slot1`s
,D/MessagingNotification( 3818): remove alarm
,D/Mms/MessagingNotification( 3818): updateAllHistoryAsRead()
,D/Mms/MessagingNotification( 3818): [end]    nonBlockingUpdateMessageIndicator()
,W/linker  ( 4411): libterrier.so has text relocations. This is wasting memory and is a security risk. Please fix.
,I/CSTORAGE( 4411): ================================================
I/CSTORAGE( 4411):  CSTORAGE_SKM_LIB v1.0.14
I/CSTORAGE( 4411): ================================================
D/dalvikvm( 4411): No JNI_OnLoad found in /system/lib/libterrier.so 0x4264a0e0, skipping init
,I/PCWCLIENTTRACE_SecurePreferencesJNI( 4411): [GetString-S]
I/terrier ( 4411): v1.1.3q com.sec.pcw.device: getString function called
,D/QSEECOMAPI: ( 4411): QSEECom_get_handle sb_length = 0x2040
,D/QSEECOMAPI: ( 4411): App is not loaded in QSEE
,W/ActivityManager(  761): Permission Denial: getCurrentUser() from pid=5274, uid=10062 requires android.permission.INTERACT_ACROSS_USERS
,D/QSEECOMAPI: ( 4411): Loaded image: APP id = 6
I/ActivityManager(  761): Killing 4295:com.android.defcontainer/u0a6 (adj 15): empty #43
,D/com.samsung.app( 1447): [KK_EASY_Accu]>>> WC:30 [0:0] action : androidintentactionTIME_SET
,D/com.samsung.app( 1447): [KK_EASY_Accu]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
,I/SELinux ( 5293): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5293):  
,D/QSEECOMAPI: ( 4411): QSEECom_dealloc_memory 
D/QSEECOMAPI: ( 4411): QSEECom_shutdown_app, app_id = 6
E/terrier ( 4411): com.sec.pcw.device: getString: failed to get string(-1)
I/PCWCLIENTTRACE_SecurePreferencesJNI( 4411): [GetString-E]
I/PCWCLIENTTRACE_PushUtil( 4411): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 4411): sales region : global
I/PCWCLIENTTRACE_PushUtil( 4411): getPushTypeList : [SPP, GCM]
,E/PCWCLIENTTRACE_PCWHandler( 4411): [ensureRegistration] - No Samsung account
,I/SELinux ( 5293): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5293):  
I/SELinux ( 5293):  
,I/SELinux ( 5293): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 5293): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 5293): >>>>> Normal User
E/dalvikvm( 5293): >>>>> com.sec.android.app.clockpackage [ userId:0 | appId:10084 ]
,E/SELinux ( 5293): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 5293): in addTimaSignatureService
,D/dalvikvm( 5265): DexOpt: load 8ms, verify+opt 11ms, 197964 bytes
,D/TimaKeyStoreProvider( 5293): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5293): Added TimaKesytore provider
,D/dalvikvm( 1758): DexOpt: --- END 'ads1363035432.jar' (success) ---
,D/dalvikvm( 1758): DEX prep '/data/data/com.google.android.gms/cache/ads1363035432.jar': unzip in 0ms, rewrite 632ms
,D/dalvikvm(  761): GC_EXPLICIT freed 1570K, 59% free 23573K/57084K, paused 6ms+14ms, total 147ms
,I/ Time Manager ( 5274): Time Difference not stored. TIME_DIFFERENCE
,D/dalvikvm( 4727): GC_CONCURRENT freed 7561K, 47% free 10179K/19088K, paused 3ms+4ms, total 88ms
,I/SELinux ( 5309): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5309):  
,I/ActivityManager(  761): Killing 3206:com.sec.android.inputmethod/1000 (adj 15): empty #43
,I/SELinux ( 5309): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5309):  
I/SELinux ( 5309):  
,I/SELinux ( 5309): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5309): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 5309): >>>>> Normal User
,E/dalvikvm( 5309): >>>>> com.sec.esdk.elm [ userId:0 | appId:10094 ]
E/SELinux ( 5309): [DEBUG] seapp_context_lookup: seinfoCategory = platform
I/WVCdm   (  251): CdmEngine::OpenSession
,D/DrmWidevineDash(  251): calling OEMCrypto_OpenSession...
D/DrmWidevineDash(  251): OEMCrypto_OpenSession SID = 1
,D/DrmWidevineDash(  251): OEMCrypto_OpenSession returns 0
,I/WVCdm   (  251): CdmEngine::QueryKeyControlInfo
I/WVCdm   (  251): CdmEngine::GenerateKeyRequest
,D/DrmWidevineDash(  251): calling OEMCrypto_LoadDeviceRSAKey. SID = 1
,D/DrmWidevineDash(  251): OEMCrypto_LoadDeviceRSAKey returns 0
,D/DrmWidevineDash(  251): calling OEMCrypto_GetDeviceID...
,I/GoogleURLConnFactory( 5003): Using platform SSLCertificateSocketFactory
,D/DrmWidevineDash(  251): OEMCrypto_GetDeviceID returns 0
,D/DrmWidevineDash(  251): calling OEMCrypto_GenerateNonce. SID = 1
D/DrmWidevineDash(  251): OEMCrypto_GenerateNonce returns 0
D/WVCdm   (  251): PrepareKeyRequest: nonce=2451863873
,D/DrmWidevineDash(  251): calling OEMCrypto_GenerateRSASignature. SID = 1
D/DrmWidevineDash(  251): OEMCrypto_GenerateRSASignature needs buffer size = 256
D/DrmWidevineDash(  251): OEMCrypto_GenerateRSASignature returns 7
,D/DrmWidevineDash(  251): calling OEMCrypto_GenerateRSASignature. SID = 1
,D/TimaKeyStoreProvider( 5309): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5309): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5309): Added TimaKesytore provider
,D/STATUSBAR-NetworkController_dual( 1069): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
,D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews start
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews set mobileLabel[SIM_0] =
,D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews GONE
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews2 set mobileLabel[SIM_1] =
D/StatusBar.NetworkController_dual( 1069): mMobileLabelViews2 GONE
,D/StatusBar.NetworkController_dual( 1069): mSingleMobileLabelViews set : simMode = 0
,D/StatusBar.NetworkController_dual( 1069): mSingleMobileLabelViews set as slot1`s
,W/ActivityManager(  761): Permission Denial: getCurrentUser() from pid=5309, uid=10094 requires android.permission.INTERACT_ACROSS_USERS
,D/elm:14132( 5309): ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver }
,D/elm:14132( 5309): ELMEngine.ELMEngine( context ).
,D/elm:14132( 5309): MDMBridge.setEnterpriseBridge()
,D/elm:14132( 5309): ELMAbstractReceiver : Receive Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.sec.esdk.elm/.service.ElmAgentService } END.
,I/knox    ( 3081): MainReceiver.onReceive() : Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.sec.knox.seandroid/.receiver.MainReceiver }
,D/elm:14132( 5309): ElmAgentService : onCreate()
,D/elm:14132( 5309): ElmAgentService : onHandleIntent() Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.sec.esdk.elm/.service.ElmAgentService }
,D/knox    ( 3081): MainReceiver.listeningToTimeDateChanges( context, intent ).
,I/knox    ( 3081): MainReceiver.onReceive() END - - - - - : Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.sec.knox.seandroid/.receiver.MainReceiver }
,D/knox    ( 3081): KNOXAgentService : onCreate()
,D/knox    ( 3081): KNOXAgentService : set alarms for deniallog and usage data upload
,W/ContextImpl( 3081): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1857 android.content.ContextWrapper.startService:506 android.content.ContextWrapper.startService:506 com.sec.knox.seandroid.receiver.MainReceiver.onReceive:142 android.app.ActivityThread.handleReceiver:2698 
D/elm:14132( 5309): ELMAgentService.listeningToTimeDateChanges( context, intent ).
D/elm:14132( 5309): ELMEngine.ServiceHandler.handleMessage( ALARM_MODIFY ). 
D/elm:14132( 5309): ModuleBase.resetCalllogAPIAlarm()
,D/knox    ( 3081): KNOXAgentService. startJobThread() start
D/knox    ( 3081): KNOXAgentService. JobThread()
,D/knox    ( 3081): KNOXAgentService. JobThread. notifyAll().
,D/knox    ( 3081): KNOXAgentService. startJobThread() wait
,I/SELinux ( 5325): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5325):  
D/knox    ( 3081): KNOXAgentService : onDestroy().
,D/knox    ( 3081): ModuleBase.cancelAllAlarmManageModule()
D/elm:14132( 5309): ModuleBase.ModifySetAlarm()
D/elm:14132( 5309): MDMBridge.getInstance()
,D/elm:14132( 5309): MDMBridge.getAllLicenseInfoFromSDK()
,D/elm:14132( 5309): ElmAgentService : onDestroy().
I/ActivityManager(  761): Killing 4371:com.google.android.partnersetup/u0a14 (adj 15): empty #43
,I/SELinux ( 5325): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5325):  
I/SELinux ( 5325):  
,I/SELinux ( 5325): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5325): [DEBUG] seapp_context_lookup: seinfoCategory = shared
E/dalvikvm( 5325): >>>>> Normal User
,E/dalvikvm( 5325): >>>>> com.sec.android.widgetapp.SPlannerAppWidget [ userId:0 | appId:10143 ]
,E/SELinux ( 5325): [DEBUG] seapp_context_lookup: seinfoCategory = shared
,D/TimaKeyStoreProvider( 5325): in addTimaSignatureService
,D/DrmWidevineDash(  251): OEMCrypto_GenerateRSASignature returns 0
,I/WVCdm   (  251): CdmEngine::CloseSession
,D/DrmWidevineDash(  251): calling OEMCrypto_CloseSession. SID = 1
,D/TimaKeyStoreProvider( 5325): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5325): Added TimaKesytore provider
,D/DrmWidevineDash(  251): OEMCrypto_CloseSession returns 0
,W/ActivityManager(  761): Permission Denial: getCurrentUser() from pid=5325, uid=10143 requires android.permission.INTERACT_ACROSS_USERS
,I/SELinux ( 5337): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5337):  
I/ActivityManager(  761): Killing 4386:com.samsung.groupcast/u0a15 (adj 15): empty #43
,I/SELinux ( 5337): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5337):  
I/SELinux ( 5337):  
,I/SELinux ( 5337): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5337): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 5337): >>>>> Normal User
,E/dalvikvm( 5337): >>>>> com.sec.android.app.taskmanager [ userId:0 | appId:10166 ]
,E/SELinux ( 5337): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 5337): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5337): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5337): Added TimaKesytore provider
,W/ActivityManager(  761): Permission Denial: getCurrentUser() from pid=5337, uid=10166 requires android.permission.INTERACT_ACROSS_USERS
,I/SELinux ( 5349): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5349):  
I/ActivityManager(  761): Killing 4399:com.android.musicfx/u0a24 (adj 15): empty #43
,D/dalvikvm( 4727): GC_CONCURRENT freed 1990K, 47% free 10219K/19088K, paused 3ms+24ms, total 54ms
,I/SELinux ( 5349): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5349):  
I/SELinux ( 5349):  
,I/SELinux ( 5349): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5349): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 5349): >>>>> Normal User
,E/dalvikvm( 5349): >>>>> com.qualcomm.timeservice [ userId:0 | appId:10168 ]
,E/SELinux ( 5349): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 5349): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5349): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5349): Added TimaKesytore provider
,W/ActivityManager(  761): Permission Denial: getCurrentUser() from pid=5349, uid=10168 requires android.permission.INTERACT_ACROSS_USERS
,D/dalvikvm( 5349): No JNI_OnLoad found in /vendor/lib/libTimeService.so 0x4264ab48, skipping init
,D/TimeService( 5349): Receivedandroid.intent.action.TIME_SET intent. Current Time is 1453985577404
D/        ( 5349): TimeServiceNative: User Time to be set is 1453985577404
D/QC-time-services( 5349): Lib:time_genoff_operation: pargs->base = 2
D/QC-time-services( 5349): Lib:time_genoff_operation: pargs->operation = 0
,D/QC-time-services( 5349): Lib:time_genoff_operation: pargs->ts_val = 1453985577404
D/QC-time-services(  293): Daemon: Connection accepted:time_genoff
,D/QC-time-services( 5349): Lib:time_genoff_operation: Send to server  passed!!
,D/InitializeManagerStateMachine( 4727): exit::SUCCESS
,D/InitializeManagerStateMachine( 4727): entry::IDLE
D/QC-time-services(  293): Daemon: genoff_handler: Process name is omm.timeservice
D/QC-time-services(  293): Daemon:Received base = 2, unit = 1, operation = 0,value = 1453985577404
,D/QC-time-services(  293): Daemon:genoff_opr: Base = 2, val = 1453985577404, operation = 0
D/QC-time-services(  293): Daemon:rtc_get: Time read from RTC -- MM/DD/YY HH:MM:SS2/4/70 4:49:42
D/QC-time-services(  293): Daemon:Value read from RTC seconds = 5374182000
D/QC-time-services(  293): Daemon:new time 1453985577404 
D/QC-time-services(  293): Daemon: delta 1448611395404 genoff 1448611395404 
D/QC-time-services(  293): Daemon:genoff_persistent_update: Writing genoff = 1448611395404 to memory
D/QC-time-services(  293): Daemon:Opening File: /data/time/ats_2
,D/QC-time-services(  293): Daemon:time_persistent_memory_opr:Genoff write operation 
D/QC-time-services(  293): Updating the TOD offset
D/QC-time-services(  293): Daemon:genoff_persistent_update: Writing genoff = 1448611395404 to memory
D/QC-time-services(  293): Daemon:Opening File: /data/time/ats_1
,D/QC-time-services(  293): Daemon:time_persistent_memory_opr:Genoff write operation 
E/QC-time-services(  293): Daemon:Update to modem bit set
D/QC-time-services(  293): Daemon:genoff_send_modem: Sending data to MODEM !
,D/QC-time-services(  293): Daemon: Base = 2, Value being sent to MODEM = 1138020777404
,E/QC-time-services(  293): Daemon: Time-services: Waiting to acceptconnection
,E/QC-time-services(  293): Daemon:tod_update_ind_cb: Got Update from modem msg_id 40
,E/QC-time-services( 5349): Receive Passed == base = 2, unit = 1, operation = 0, result = 0
,I/System.out( 4727): Thread-472(HTTPLog):isShipBuild true
,I/System.out( 4727): Thread-472(HTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
I/ActivityManager(  761): Killing 4428:com.samsung.android.app.galaxyfinder/u0a34 (adj 15): empty #43
,D/daemonapp( 1465): [MSC_Daemon]>>> WU:236 [0:0] regintype : EUR
,D/daemonapp( 1465): [MSC_Daemon]>>> WU:292 [0:0] cp type is : cp_eng
,D/daemonapp( 1465): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/daemonapp( 1465): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,D/daemonapp( 1465): [MSC_Daemon]>>> WDSM:44 [0:0] Act : androidintentactionTIME_SET, run:true
,D/comsamsunglog( 1465): [MSC_Daemon]>>> ====================================================================================================================
,D/comsamsunglog( 1465): [MSC_Daemon]>>> daemonapp [Version : 14052601 ] [ 1 ] 
D/comsamsunglog( 1465): [MSC_Daemon]>>> Header set to : ===> "daemonapp" <===
,D/comsamsunglog( 1465): [MSC_Daemon]>>> ====================================================================================================================
,D/daemonapp( 1465): [MSC_Daemon]>>> WDSM:85 [0:0] c:null, r:3
,D/daemonapp( 1465): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/packagename
,D/daemonapp( 1465): [MSC_Daemon]>>> WU:1485 [0:0] PakNme size = 2
,D/daemonapp( 1465): [MSC_Daemon]>>> WU:236 [0:0] regintype : EUR
,D/daemonapp( 1465): [MSC_Daemon]>>> WU:292 [0:0] cp type is : cp_eng
,D/daemonapp( 1465): [MSC_Daemon]>>> WU:1488 [0:0] CP Name cp_eng
,D/daemonapp( 1465): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/packagename
,D/comdaemonstockapp( 1465): [Daemon_Stock]>>> StockclockDaemonService.java:60 [0:0] onReceive: androidintentactionTIME_SET
,D/comdaemonstockapp( 1465): [Daemon_Stock]>>> StockclockDaemonService.java:61 [0:0] appServiceStatus: 0
,I/rmt_storage(  300): rmt_storage_connect_cb: clnt_h=0x5 conn_h=0xb8ac4178
I/rmt_storage(  300): rmt_storage_rw_iovec_cb: /boot/modem_fs2: clnt_h=0x2: req_h=0xa msg_id=3: R/W request received
I/rmt_storage(  300): wakelock acquired: 1, error no: 42
,I/rmt_storage(  300): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 Unblock worker thread (th_id: -1196670408)
,I/CheckinService( 1758): Checkin interval check for package: unspecified last checkin: 1452516764897 min interval config: 0 actual interval: 1468812648
,D/WVMDrmPlugIn(  250): WVMDrmPlugin::onInitialize : 931
,D/WVMDrmPlugIn(  250): WVMDrmPlugin::onSetOnInfoListener : add 931
,D/WVMDrmPlugIn(  250): WVMDrmPlugin::onGetSupportInfo : 0
D/AmoledAdjustTimer(  761): prevTemp = 285, currTemp = 288, prevStep = 4, currStep = 4
,I/WVCdm   (  251): CdmEngine::OpenSession
,D/DrmWidevineDash(  251): calling OEMCrypto_OpenSession...
D/DrmWidevineDash(  251): OEMCrypto_OpenSession SID = 1
,D/DrmWidevineDash(  251): OEMCrypto_OpenSession returns 0
,I/WVCdm   (  251): CdmEngine::QueryKeyControlInfo
,I/WVCdm   (  251): CdmEngine::GenerateKeyRequest
,D/DrmWidevineDash(  251): calling OEMCrypto_LoadDeviceRSAKey. SID = 1
,D/DrmWidevineDash(  251): OEMCrypto_LoadDeviceRSAKey returns 0
,D/DrmWidevineDash(  251): calling OEMCrypto_GetDeviceID...
,I/rmt_storage(  300): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0xa msg_id=3: Bytes written = 1572864
,I/rmt_storage(  300): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0xa msg_id=3: Send response: res=0 err=0
,I/rmt_storage(  300): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 About to block rmt_storage client thread (th_id: -1196670408) wakelock released: 1, error no: 0
I/rmt_storage(  300): 
,I/rmt_storage(  300): rmt_storage_disconnect_cb: clnt_h=0x0x5 conn_h=0x0xb8ac4178
D/DrmWidevineDash(  251): OEMCrypto_GetDeviceID returns 0
,D/DrmWidevineDash(  251): calling OEMCrypto_GenerateNonce. SID = 1
D/DrmWidevineDash(  251): OEMCrypto_GenerateNonce returns 0
D/WVCdm   (  251): PrepareKeyRequest: nonce=2263837866
,D/DrmWidevineDash(  251): calling OEMCrypto_GenerateRSASignature. SID = 1
D/DrmWidevineDash(  251): OEMCrypto_GenerateRSASignature needs buffer size = 256
D/DrmWidevineDash(  251): OEMCrypto_GenerateRSASignature returns 7
,D/DrmWidevineDash(  251): calling OEMCrypto_GenerateRSASignature. SID = 1
,D/WearableService( 1220): callingUid 10011, callindPid: 1220
,E/MDM     ( 1220): [111] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/AuthorizationBluetoothService( 1312): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,E/AuthorizationBluetoothService( 1312): Proximity feature is not enabled.
,D/LocationInitializer( 1758): Restart initialization of location
,V/GLSActivity( 1312): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/SELinux ( 5378): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5378):  
,W/GCoreFlp( 1220): No location to return for getLastLocation()
,W/FusedLocationProvider( 1220): location=null
,I/SELinux ( 5378): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5378):  
I/SELinux ( 5378):  
,I/SELinux ( 5378): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,D/DrmWidevineDash(  251): OEMCrypto_GenerateRSASignature returns 0
E/SELinux ( 5378): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 5378): >>>>> Normal User
E/dalvikvm( 5378): >>>>> com.google.android.talk [ userId:0 | appId:10105 ]
I/WVCdm   (  251): CdmEngine::CloseSession
,D/DrmWidevineDash(  251): calling OEMCrypto_CloseSession. SID = 1
,E/SELinux ( 5378): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
,D/DrmWidevineDash(  251): OEMCrypto_CloseSession returns 0
,D/TimaKeyStoreProvider( 5378): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5378): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5378): Added TimaKesytore provider
,W/ActivityManager(  761): Permission Denial: getCurrentUser() from pid=5378, uid=10105 requires android.permission.INTERACT_ACROSS_USERS
,I/Babel   ( 5378): MmsConfig: mnc/mcc: 0/0
,I/Babel   ( 5378): MmsConfig.loadMmsSettings
,I/Babel   ( 5378): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=SAMSUNG-ANDROID-MMS/SM-G800H, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-G800H.xml
,I/Babel   ( 5378): MmsConfig.loadFromDatabase
,E/Babel   ( 5378): canonicalizeMccMnc: invalid mccmnc 
,W/Settings( 5378): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel   ( 5378): MmsConfig.loadFromResources
,E/Babel   ( 5378): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel   ( 5378): MmsConfig.loadMmsSettings: mUserAgent=SAMSUNG-ANDROID-MMS/SM-G800H, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-G800H.xml
,D/hcjo    ( 4727): AutoUpdateTriggerManager:REQUEST2:setInterval:345600000
,I/SELinux ( 5402): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5402):  
,D/dalvikvm(  249): GC_EXPLICIT freed 42K, 51% free 9510K/19088K, paused 2ms+2ms, total 26ms
,D/dalvikvm(  249): GC_EXPLICIT freed <1K, 51% free 9510K/19088K, paused 2ms+2ms, total 19ms
,I/SELinux ( 5402): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5402):  
I/SELinux ( 5402):  
,I/SELinux ( 5402): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5402): [DEBUG] seapp_context_lookup: seinfoCategory = release
E/dalvikvm( 5402): >>>>> Normal User
D/dalvikvm(  249): GC_EXPLICIT freed <1K, 51% free 9510K/19088K, paused 2ms+3ms, total 19ms
,E/dalvikvm( 5402): >>>>> com.android.providers.calendar [ userId:0 | appId:10044 ]
,D/hcjo    ( 4727): AutoUpdateTriggerManager:REQUEST2:notifyTimedOutAndWriteUpdateCheckedTime
,E/SELinux ( 5402): [DEBUG] seapp_context_lookup: seinfoCategory = release
,D/hcjo    ( 4727): AutoUpdateManager:UPD_CHECK_TIMING:onUpdateTime
,D/hcjo    ( 4727): SelfUpdateManager:IDLE:execute
,D/TimaKeyStoreProvider( 5402): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5402): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5402): Added TimaKesytore provider
,I/PowerManagerService(  761): [PWL] Off : 50s ago
I/PowerManagerService(  761): [PWL]   PowerManagerService.WakeLocks: ref count=1
I/PowerManagerService(  761): [PWL]     mWakeLockSummary : 0x1
I/PowerManagerService(  761): [PWL]       PARTIAL_WAKE_LOCK              '*net_scheduler*' (uid=10011, pid=1312, ws=WorkSource{10011 com.google.android.gms}) (elapsedTime=3358)
,I/PowerManagerService(  761): [PWL]       PARTIAL_WAKE_LOCK              'Checkin Service' (uid=10011, pid=1758, ws=WorkSource{10011 com.google.android.gms}) (elapsedTime=3147)
,I/PowerManagerService(  761): [PWL]       PARTIAL_WAKE_LOCK              'AlarmManager' (uid=1000, pid=761, ws=WorkSource{10044}) (elapsedTime=2387)
I/PowerManagerService(  761): [PWL]       PARTIAL_WAKE_LOCK              'GOOGLE_C2DM' (uid=10011, pid=1312, ws=WorkSource{0 com.google.android.gms}) (elapsedTime=2293)
,I/PowerManagerService(  761): [PWL]       PARTIAL_WAKE_LOCK              'AlarmReceiver' (uid=10084, pid=5293, ws=null) (elapsedTime=1797)
,D/hcjo    ( 4727): SelfUpdateManager:CONDITION_CHECK:onUpdateCondition
,D/dalvikvm( 5003): GC_CONCURRENT freed 2241K, 40% free 11454K/19088K, paused 1ms+4ms, total 29ms
D/dalvikvm( 5378): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 5378): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 5378): VFY: replacing opcode 0x62 at 0x000a
,D/WVMDrmPlugIn(  250): WVMDrmPlugin::onTerminate : 931
,D/dalvikvm( 5378): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
W/dalvikvm( 5378): VFY: unable to resolve instance field 36
,D/dalvikvm( 5378): VFY: replacing opcode 0x54 at 0x005f
D/dalvikvm( 5378): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 5378): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 5378): VFY: replacing opcode 0x62 at 0x0047
D/dalvikvm( 5378): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
,I/dalvikvm( 5378): DexOpt: unable to optimize instance field ref 0x0024 at 0x63 in Lcom/google/android/gms/common/util/ay;.b
,D/dalvikvm( 5378): Trying to load lib /data/app-lib/com.google.android.gms-2/libgmscore.so 0x427d5a20
,I/Volley  ( 4727): RestApi Request Add : 2346
,D/dalvikvm( 5378): Added shared lib /data/app-lib/com.google.android.gms-2/libgmscore.so 0x427d5a20
,D/dalvikvm( 5378): No JNI_OnLoad found in /data/app-lib/com.google.android.gms-2/libgmscore.so 0x427d5a20, skipping init
,D/dalvikvm( 5378): Trying to load lib /data/app-lib/com.google.android.gms-2/libconscrypt_gmscore_jni.so 0x427d5a20
D/dalvikvm( 5378): Added shared lib /data/app-lib/com.google.android.gms-2/libconscrypt_gmscore_jni.so 0x427d5a20
,V/JNIHelp ( 5378): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,D/dalvikvm( 5378): Trying to load lib /data/app-lib/com.google.android.gms-2/libgmscore.so 0x427d5a20
,D/dalvikvm( 5378): Shared lib '/data/app-lib/com.google.android.gms-2/libgmscore.so' already loaded in same CL 0x427d5a20
D/dalvikvm( 5378): Trying to load lib /data/app-lib/com.google.android.gms-2/libconscrypt_gmscore_jni.so 0x427d5a20
,D/dalvikvm( 5378): Shared lib '/data/app-lib/com.google.android.gms-2/libconscrypt_gmscore_jni.so' already loaded in same CL 0x427d5a20
,W/Settings( 5003): Setting install_non_market_apps has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/Adreno-EGL( 5003): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 5003): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 5003): Build Date: 03/21/14 Fri
I/Adreno-EGL( 5003): Local Branch: AU200+patches_03212014
I/Adreno-EGL( 5003): Remote Branch: 
I/Adreno-EGL( 5003): Local Patches: 
I/Adreno-EGL( 5003): Reconstruct Branch: 
,I/ProviderInstaller( 5378): Installed default security provider GmsCore_OpenSSL
,I/Adreno-EGL( 5003): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 5003): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 5003): Build Date: 03/21/14 Fri
I/Adreno-EGL( 5003): Local Branch: AU200+patches_03212014
I/Adreno-EGL( 5003): Remote Branch: 
I/Adreno-EGL( 5003): Local Patches: 
I/Adreno-EGL( 5003): Reconstruct Branch: 
,I/Adreno-EGL( 5003): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 5003): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 5003): Build Date: 03/21/14 Fri
I/Adreno-EGL( 5003): Local Branch: AU200+patches_03212014
I/Adreno-EGL( 5003): Remote Branch: 
I/Adreno-EGL( 5003): Local Patches: 
I/Adreno-EGL( 5003): Reconstruct Branch: 
,I/CheckinRequestBuilder( 1758): Classify the device as Phone.
W/ActivityManager(  761): Permission Denial: getCurrentUser() from pid=5402, uid=10044 requires android.permission.INTERACT_ACROSS_USERS
,D/Headlines( 5107): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE
,D/Headlines( 5107): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0
,D/Headlines( 5107): Breath 5164 latestRequest time : 1453985573701 current time : 1453985578866
,I/GCM     ( 1758): Message from 745476177629 null
,V/AlarmManager(  761): waitForAlarm result :8
D/Mms/MessagesLockscreen( 3818): onReceive() action = com.android.mms.ui.MessagesLockscreenmSimSlot : [0] Mms = false count = 0
D/ContextualEventManager( 1069): removeContextualEvent(): requestClass=com.android.mms
D/ContextualEventManager( 1069): removeMissedEventView rq=com.android.mms[cFlag, mFlag]=[false, false]
D/ContextualEventManager( 1069): updateContainer()
D/ContextualEventContainer( 1069): update()
D/ContextualEventContainer( 1069): handleUpdate()
D/ContextualEventManager( 1069): getTopEventView()
D/ContextualEventManager( 1069): getTopContextualEvent()
,I/GAV2    ( 5120): Thread[GAThread,5,main]: No campaign data found.
D/ContextualEventManager( 1069): top view = flightmode
I/KeyguardEffectViewMain( 1069): *** KeyguardEffectView getInstance ***
D/ContextualEventManager( 1069): getTopEventClass()
,D/ContextualEventManager( 1069): getTopContextualEvent()
D/ContextualEventManager( 1069): !isClockTop
D/ContextualEventManager( 1069): getTopEventClass()
,D/ContextualEventManager( 1069): getTopContextualEvent()
D/ContextualEventManager( 1069): !isClockTop
D/ContextualEventManager( 1069): getTopEventClass()
,D/ContextualEventManager( 1069): getTopContextualEvent()
,I/GCM     ( 1758): Message from 745476177629 null
D/UsbManager( 1069):  :::: isUsb30Available :: return = false from pid = 1069
,I/GCM     ( 1758): Message from 745476177629 null
,D/SecContextualClockFlightMode( 1069): handleUpdateClock()
,D/KeyguardProperties( 1069): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,I/GCoreUlr( 1220): GCM message received Intent { act=com.google.android.c2dm.intent.RECEIVE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.location.reporting.service.GcmBroadcastReceiver (has extras) }
,I/GCoreUlr( 1220): Received GCM notification for account#2# timestamp:1452698630699
,E/SMD     (  242): DCD OFF
,I/GCoreUlr( 1220): Starting service, intent=Intent { act=com.google.android.location.reporting.ACTION_INSISTENT_SYNC cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) }, extras=Bundle[{account=Account {name=thalitester@gmail.com, type=com.google}, label=GcmBroadcastReceiver}]
,D/GCM     ( 1312): GcmService start Intent { act=com.google.android.gcm.intent.SEND flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.gcm.intent.SEND
,I/GCoreUlr( 1220): DispatchingService.onCreate()
,I/ActivityManager(  761): Killing 4464:com.sec.android.service.health/u0a16 (adj 15): empty #43
,I/dalvikvm( 1220): Could not find method android.os.PowerManager.isInteractive, referenced from method com.google.android.location.reporting.k.a
W/dalvikvm( 1220): VFY: unable to resolve virtual method 1378: Landroid/os/PowerManager;.isInteractive ()Z
,D/dalvikvm( 1220): VFY: replacing opcode 0x6e at 0x0352
,I/GCoreUlr( 1220): GCM message received Intent { act=com.google.android.c2dm.intent.RECEIVE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.location.reporting.service.GcmBroadcastReceiver (has extras) }
,I/GCoreUlr( 1220): Received GCM notification for account#2# timestamp:1452698630699
,I/GCoreUlr( 1220): Starting service, intent=Intent { act=com.google.android.location.reporting.ACTION_INSISTENT_SYNC cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) }, extras=Bundle[{account=Account {name=thalitester@gmail.com, type=com.google}, label=GcmBroadcastReceiver}]
,I/GCoreUlr( 1220): GCM message received Intent { act=com.google.android.c2dm.intent.RECEIVE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.location.reporting.service.GcmBroadcastReceiver (has extras) }
,I/GCoreUlr( 1220): Received GCM notification for account#2# timestamp:1452698630699
,I/GCoreUlr( 1220): Starting service, intent=Intent { act=com.google.android.location.reporting.ACTION_INSISTENT_SYNC cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) }, extras=Bundle[{account=Account {name=thalitester@gmail.com, type=com.google}, label=GcmBroadcastReceiver}]
,I/GCoreUlr( 1220): Uploading GCM registration ID for account#2#
,W/BaseAppContext( 1220): Using Auth Proxy for data requests.
,E/BaseAppContext( 1220): Tried to stop global GMSCore RequestQueue. This is likely unintended, so ignoring.
V/AlarmManager(  761): waitForAlarm result :4
,V/AlarmManager(  761): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,D/SSRMv2:SIOP(  761): SIOP:: AP = 340, Delta = 20
,I/System.out( 5378): Thread-552(HTTPLog):isShipBuild true
,I/System.out( 5378): Thread-552(HTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,I/qtaguid ( 4727): Failed write_ctrl(u -1) res=-1 errno=9
I/qtaguid ( 4727): Untagging socket -1 failed errno=-9
,W/NetworkManagementSocketTagger( 4727): untagSocket(-1) failed with errno -9
,D/hcjo    ( 4727): SelfUpdateManager:REQUEST_UPD_CHECK:onUpdateCheckSuccessAndNoNeedUpdate
,D/hcjo    ( 4727): AutoUpdateManager:CHECK_SELF_UPD:onSelfUpdateResult:T
,D/hcjo    ( 4727): SellerAppAutoUpdate:clearFlag
,D/SellerAppAutoUpdateManagerStateMachine( 4727): execute::IDLE:EXECUTE
D/SellerAppAutoUpdateManagerStateMachine( 4727): exit::IDLE
,D/SellerAppAutoUpdateManagerStateMachine( 4727): entry::TOKENCHECK
,D/SellerAppAutoUpdateManagerStateMachine( 4727): execute::TOKENCHECK:TOKEN_RECEIVED
D/SellerAppAutoUpdateManagerStateMachine( 4727): exit::TOKENCHECK
D/SellerAppAutoUpdateManagerStateMachine( 4727): entry::FAILED
D/hcjo    ( 4727): AutoUpdateManager:SELLER_UPD:onSellerAutoUpdateFailed
D/SellerAppAutoUpdateManagerStateMachine( 4727): exit::FAILED
,D/SellerAppAutoUpdateManagerStateMachine( 4727): entry::IDLE
,I/System.out( 1758): Thread-215(HTTPLog):isShipBuild true
,I/System.out( 1758): Thread-215(HTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,D/dalvikvm( 3531): GC_CONCURRENT freed 1767K, 42% free 11201K/19088K, paused 3ms+2ms, total 36ms
,D/dalvikvm( 1758): GC_CONCURRENT freed 1684K, 35% free 12497K/19088K, paused 4ms+7ms, total 39ms
,D/dalvikvm( 1312): GC_CONCURRENT freed 1856K, 43% free 10981K/19088K, paused 3ms+11ms, total 35ms
,D/Finsky  ( 3531): [349] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 3531): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,I/CheckinTask( 1758): Sending checkin request (12766 bytes)
,V/AlarmManager(  761): waitForAlarm result :8
,V/AlarmManager(  761): ClockReceiver onReceive() ACTION_TIME_TICK
,V/AlarmManager(  761): ___SyncScheduler (v3) ACTIVATED___
,V/AlarmManager(  761): <AppSync3 Whitelist>
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1069): handleTimeUpdate
V/AlarmManager(  761): (AppSync) ### 0 added ###
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,I/ActivityManager(  761): Killing 3895:com.samsung.android.sdk.samsunglink/u0a42 (adj 15): empty #43
,I/GCoreUlr( 1220): GCM ID uploaded for account#2#
,I/GCoreUlr( 1220): Starting service, intent=Intent { act=com.google.android.location.reporting.ACTION_UPDATE_ACTIVE_STATE cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) }, extras=Bundle[{source=sync_server_wins}]
,I/GCoreUlr( 1220): DispatchingService.updateActiveState+sync_server_wins: Ensuring that reporting is stopped because of reasons: {account#2#=[InactiveReason{mVersionCode=0, mIdentifier=12, mName='LocationDisabled'}, InactiveReason{mVersionCode=0, mIdentifier=6, mName='ReportingNotEnabled'}, InactiveReason{mVersionCode=0, mIdentifier=14, mName='HistoryNotEnabled'}]}
,W/BaseAppContext( 1220): Using Auth Proxy for data requests.
,I/GCoreUlr( 1220): Unbound from all location providers
,I/GCoreUlr( 1220): Place inference reporting - stopped
,I/GCoreUlr( 1220): DispatchingService.onDestroy()
I/GCoreUlr( 1220): Stopping handler for UlrDispSvcFast
,I/GCoreUlr( 1220): Stopping handler for UlrDispSvcSlow
,I/GCoreUlr( 1220): Unbound from all location providers
,I/GCoreUlr( 1220): Place inference reporting - stopped
,I/CheckinResponseProcessor( 1758): From server: 25 gservices updates and 6 deletes
,I/Babel   ( 5378): Account registration complete:Redacted-21
,W/ContextImpl(  761): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,I/GCoreUlr( 1220): Starting service, intent=Intent { act=com.google.android.location.reporting.ACTION_UPDATE_ACTIVE_STATE cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) }, extras=Bundle[{source=sync_server_wins}]
,I/GCoreUlr( 1220): DispatchingService.onCreate()
,I/GCoreUlr( 1220): DispatchingService.updateActiveState+sync_server_wins: Ensuring that reporting is stopped because of reasons: {account#2#=[InactiveReason{mVersionCode=0, mIdentifier=12, mName='LocationDisabled'}, InactiveReason{mVersionCode=0, mIdentifier=6, mName='ReportingNotEnabled'}, InactiveReason{mVersionCode=0, mIdentifier=14, mName='HistoryNotEnabled'}]}
,D/CaptivePortalTracker(  761): DelayedCaptiveCheckState{ when=-10ms what=2 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  761): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
I/CertBlacklister(  761): Certificate blacklist changed, updating...
,I/CertBlacklister(  761): Certificate blacklist updated
,D/CaptivePortalTracker(  761): Checking http://216.58.209.46/generate_204
W/ActivityThread(  761): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,I/GservicesProvider( 1312): main difference update completed
,D/dalvikvm(  761): GC_EXPLICIT freed 1873K, 59% free 23795K/57084K, paused 5ms+15ms, total 150ms
,I/SELinux ( 5464): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5464):  
,I/CheckinRequestBuilder( 1758): Checkin reason type: 12 attempt count: 1
,D/BatteryService(  761): level:100, scale:100, status:5, health:2, present:true, voltage: 4365, temperature: 293, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:9, charge type:1, power sharing:false
D/BatteryService(  761): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  761): stay LED for fully charged
,D/UiModeManager(  761): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,V/HeadsetService( 3171): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3171): Disconnected process message: 10
,I/System.out(  761): Thread-163(HTTPLog):isShipBuild true
,I/System.out(  761): Thread-163(HTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
I/SELinux ( 5464): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5464):  
I/SELinux ( 5464):  
,I/SELinux ( 5464): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5464): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 5464): >>>>> Normal User
,E/dalvikvm( 5464): >>>>> com.google.android.configupdater [ userId:0 | appId:10003 ]
D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/ActivityThread( 1758): Failed to find provider info for com.google.android.wearable.settings
E/SELinux ( 5464): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
I/GCoreUlr( 1220): Unbound from all location providers
I/GCoreUlr( 1220): Place inference reporting - stopped
,D/TimaKeyStoreProvider( 5464): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5464): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5464): Added TimaKesytore provider
,D/dalvikvm( 1220): GC_CONCURRENT freed 1911K, 39% free 11794K/19088K, paused 6ms+4ms, total 49ms
,D/CaptivePortalTracker(  761): Don't send network conditions - lacking user consent.
,D/CaptivePortalTracker(  761): isCaptivePortal: ret=false rspCode=204
D/CaptivePortalTracker(  761): Not captive network NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/CaptivePortalTracker(  761): notifyPortalCheckCompleted: captive=false ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
W/ActivityManager(  761): Permission Denial: getCurrentUser() from pid=5464, uid=10003 requires android.permission.INTERACT_ACROSS_USERS
D/ConnectivityService(  761): captivePortalCheckCompleted: ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false captive=false
,I/GCoreUlr( 1220): DispatchingService.onDestroy()
,I/GCoreUlr( 1220): Stopping handler for UlrDispSvcFast
,I/GCoreUlr( 1220): Unbound from all location providers
,I/GCoreUlr( 1220): Place inference reporting - stopped
,W/ContextImpl( 5464): Implicit intents with startService are not safe: Intent { act=com.google.android.configupdater.CertPin.START (has extras) } android.content.ContextWrapper.startService:506 android.content.ContextWrapper.startService:506 com.google.android.configupdater.UpdateRequestReceiver.startUpdate:219 
,I/UpdateFetcherService( 5464): Update started
,E/UpdateRequestReceiver( 5464): Received malformed URL while handling Gservices.CHANGED_ACTION
,W/ContextImpl( 5464): Implicit intents with startService are not safe: Intent { act=com.google.android.configupdater.SmsShortCodes.START (has extras) } android.content.ContextWrapper.startService:506 android.content.ContextWrapper.startService:506 com.google.android.configupdater.UpdateRequestReceiver.startUpdate:219 
,I/UpdateFetcherService( 5464): Update started
,I/CheckinRequestBuilder( 1758): Classify the device as Phone.
,I/CheckinTask( 1758): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,I/CheckinService( 1758): Checking schedule, now: 1453985581307 next: 1454573107295
,I/CheckinService( 1758): active receiver: disabled
,D/EnterpriseDeviceManagerService(  761): Creating context as user 0
,I/DownloadManager( 1208): Download 47 starting
,D/CheckinService( 1758): Recording last checkin time for package unspecified as 1453985581353
,E/UpdateRequestReceiver( 5464): Received malformed URL while handling Gservices.CHANGED_ACTION
W/ActivityThread( 1208): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,I/DownloadManager( 1208): Download 48 starting
,E/UpdateRequestReceiver( 5464): Received malformed URL while handling Gservices.CHANGED_ACTION
,E/UpdateRequestReceiver( 5464): Received malformed URL while handling Gservices.CHANGED_ACTION
,I/SELinux ( 5502): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5502):  
I/ActivityManager(  761): Killing 2858:com.samsung.android.app.assistantmenu/1000 (adj 15): empty #43
,I/SELinux ( 5502): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5502):  
I/SELinux ( 5502):  
,I/SELinux ( 5502): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5502): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 5502): >>>>> Normal User
,E/dalvikvm( 5502): >>>>> com.google.android.partnersetup [ userId:0 | appId:10014 ]
,E/SELinux ( 5502): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
,D/TimaKeyStoreProvider( 5502): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5502): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5502): Added TimaKesytore provider
,I/System.out( 1208): Thread-52(HTTPLog):isShipBuild true
,I/System.out( 1208): Thread-52(HTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,I/System.out( 1208): Thread-53(HTTPLog):isShipBuild true
,I/System.out( 1208): Thread-53(HTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
W/ActivityManager(  761): Permission Denial: getCurrentUser() from pid=5502, uid=10014 requires android.permission.INTERACT_ACROSS_USERS
,I/ContactAccountLoggerTas( 2125): canRun() : Opted Out
,I/Search.GservicesUpdateTask( 2125): Updating Gservices keys
,I/DownloadManager( 1208): Ignoring Content-Length since Transfer-Encoding is also defined
,I/ActivityManager(  761): Killing 4613:com.sec.android.service.cm/u0a78 (adj 15): empty #43
,D/dalvikvm( 4193): GC_FOR_ALLOC freed 134K, 27% free 14106K/19088K, paused 18ms, total 19ms
,I/dalvikvm-heap( 4193): Grow heap (frag case) to 19.169MB for 2129936-byte allocation
,I/CheckinService( 1758): Checkin interval check for package: unspecified last checkin: 1453985581353 min interval config: 0 actual interval: 427
,D/dalvikvm( 4193): GC_CONCURRENT freed 9K, 24% free 16185K/21172K, paused 4ms+5ms, total 24ms
,I/CheckinService( 1758): Checking schedule, now: 1453985581806 next: 1454573107295
,I/CheckinService( 1758): active receiver: disabled
,I/ContactAccountLoggerTas( 2125): canRun() : Opted Out
,I/SystemUpdateService( 1758): receiver: Intent { act=com.google.gservices.intent.action.GSERVICES_CHANGED flg=0x10 cmp=com.google.android.gms/.update.SystemUpdateService$Receiver }
,I/ContactAccountLoggerTas( 2125): canRun() : Opted Out
,D/SystemUpdateService( 1758): onCreate
,D/SystemUpdateService( 1758): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/ContactAccountLoggerTas( 2125): canRun() : Opted Out
,D/dalvikvm( 4193): GC_FOR_ALLOC freed 10K, 24% free 16192K/21172K, paused 34ms, total 35ms
,D/dalvikvm( 1312): GC_EXPLICIT freed 903K, 43% free 10971K/19088K, paused 3ms+6ms, total 37ms
,V/DownloadManager( 1208): MIME Type = text/plain
,I/SystemUpdateService( 1758): cancelUpdate (empty URL)
,I/SystemUpdateService( 1758): active receiver: disabled
,I/DownloadManager( 1208): Download 48 finished with status SUCCESS
,E/SMD     (  242): DCD OFF
,I/DownloadManager( 1208): Ignoring Content-Length since Transfer-Encoding is also defined
,D/dalvikvm( 1758): GC_EXPLICIT freed 1556K, 35% free 12452K/19088K, paused 4ms+6ms, total 45ms
,W/SQLiteConnectionPool( 1758): A SQLiteConnection object for database '+data+data+com_google_android_gms+databases+networkstatistics_sqlite' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
,V/DownloadManager( 1208): MIME Type = text/plain
,I/DownloadManager( 1208): Download 47 finished with status SUCCESS
,D/dalvikvm( 1312): GC_EXPLICIT freed 244K, 43% free 10972K/19088K, paused 3ms+5ms, total 30ms
,D/SystemUpdateService( 1758): onDestroy
,E/DynamiteModule( 1758): Failed to load IDynamiteLoader from GmsCore
E/DynamiteModule( 1758): java.lang.ClassNotFoundException: Didn't find class "com.google.android.gms.chimera.container.DynamiteLoaderImpl" on path: DexPathList[[zip file "/system/framework/com.android.location.provider.jar", zip file "/system/framework/com.android.media.remotedisplay.jar", zip file "/data/app/com.google.android.gms-2.apk", zip file "/data/data/com.google.android.gms/code_cache/secondary-dexes/com.google.android.gms-2.apk.classes2.zip", zip file "/data/data/com.google.android.gms/code_cache/secondary-dexes/com.google.android.gms-2.apk.classes3.zip", zip file "/data/data/com.google.android.gms/code_cache/secondary-dexes/com.google.android.gms-2.apk.classes4.zip"],nativeLibraryDirectories=[/data/app-lib/com.google.android.gms-2, /data/app-lib/com.google.android.gms-2, /data/app-lib/com.google.android.gms-2, /data/app-lib/com.google.android.gms-2, /data/app-lib/com.google.android.gms-2, /vendor/lib, /system/lib]]
E/DynamiteModule( 1758): 	at dalvik.system.BaseDexClassLoader.findClass(BaseDexClassLoader.java:67)
E/DynamiteModule( 1758): 	at java.lang.ClassLoader.loadClass(ClassLoader.java:497)
E/DynamiteModule( 1758): 	at java.lang.ClassLoader.loadClass(ClassLoader.java:457)
E/DynamiteModule( 1758): 	at com.google.android.gms.dynamite.a.a(SourceFile:212)
E/DynamiteModule( 1758): 	at com.google.android.gms.dynamite.a.a(SourceFile:169)
E/DynamiteModule( 1758): 	at com.google.android.gms.dynamite.a.a(SourceFile:122)
E/DynamiteModule( 1758): 	at com.google.android.gms.flags.a.a.a(SourceFile:58)
E/DynamiteModule( 1758): 	at com.google.android.gms.flags.h.a(SourceFile:16)
E/DynamiteModule( 1758): 	at com.google.android.gms.flags.GServicesChangedReceiver.onReceive(SourceFile:11)
E/DynamiteModule( 1758): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2698)
E/DynamiteModule( 1758): 	at android.app.ActivityThread.access$1800(ActivityThread.java:172)
E/DynamiteModule( 1758): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1384)
E/DynamiteModule( 1758): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/DynamiteModule( 1758): 	at android.os.Looper.loop(Looper.java:146)
E/DynamiteModule( 1758): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/DynamiteModule( 1758): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/DynamiteModule( 1758): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/DynamiteModule( 1758): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/DynamiteModule( 1758): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/DynamiteModule( 1758): 	at dalvik.system.NativeStart.main(Native Method)
I/DynamiteModule( 1758): Considering local module com.google.android.gms.flags:1 and remote module com.google.android.gms.flags:0
,I/DynamiteModule( 1758): Selected local version of com.google.android.gms.flags
,D/SystemEventReceiver( 1758): Received GSERVICES_CHANGED broadcast
,I/OcrUtils( 1758): Updating ocr activity enabled=false
,I/ContactAccountLoggerTas( 2125): canRun() : Opted Out
,D/dalvikvm(  761): GC_EXPLICIT freed 1931K, 59% free 23765K/57084K, paused 6ms+13ms, total 160ms
,W/ActivityManager(  761): Unable to start service Intent { cmp=com.google.android.gms/.measurement.service.b } U=0: not found
,D/GCM     ( 1312): GcmService start Intent { act=com.google.gservices.intent.action.GSERVICES_CHANGED flg=0x10 cmp=com.google.android.gms/.gcm.GcmService } com.google.gservices.intent.action.GSERVICES_CHANGED
,D/OcrModelManager( 1758): Updating downloaded model state (gservices changed)
,E/File    ( 1758): fail readDirectory() errno=2
,E/dalvikvm( 1220): Could not find class 'android.app.usage.UsageStatsManager', referenced from method com.google.android.contextmanager.m.a.az.i
,W/dalvikvm( 1220): VFY: unable to resolve check-cast 57 (Landroid/app/usage/UsageStatsManager;) in Lcom/google/android/contextmanager/m/a/az;
D/dalvikvm( 1220): VFY: replacing opcode 0x1f at 0x001a
,D/dalvikvm( 1220): DexOpt: unable to opt direct call 0x00e3 at 0x2b in Lcom/google/android/contextmanager/m/a/az;.i
,I/dalvikvm( 1220): Could not find method android.os.PowerManager.isInteractive, referenced from method com.google.android.contextmanager.m.a.bc.b
,W/dalvikvm( 1220): VFY: unable to resolve virtual method 1378: Landroid/os/PowerManager;.isInteractive ()Z
,D/dalvikvm( 1220): VFY: replacing opcode 0x6e at 0x0012
,I/GCoreUlr( 1220): Starting service, intent=Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) }, extras=Bundle[{receiverAction=com.google.gservices.intent.action.GSERVICES_CHANGED}]
,I/GCoreUlr( 1220): DispatchingService.onCreate()
,D/GCM     ( 1312): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,D/dalvikvm( 1312): GC_EXPLICIT freed 382K, 43% free 10983K/19088K, paused 3ms+7ms, total 36ms
,I/GCoreUlr( 1220): WorldUpdater received intent Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) } with receiverAction com.google.gservices.intent.action.GSERVICES_CHANGED
,D/GCM     ( 1312): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,W/ContextImpl( 5464): Implicit intents with startService are not safe: Intent { act=com.google.android.configupdater.SmsShortCodes.NEW_METADATA (has extras) } android.content.ContextWrapper.startService:506 android.content.ContextWrapper.startService:506 com.google.android.configupdater.UpdateRequestReceiver.handleMetadataDownload:244 
,W/GeofencerStateMachine( 1220): Ignoring removeGeofence because network location is disabled.
,E/ctxmgr  ( 1220): [FenceManager]Could not remove all geofences. status=Status{statusCode=unknown status code: 1000, resolution=null}
,W/ContextImpl( 5464): Implicit intents with startService are not safe: Intent { act=com.google.android.configupdater.CertPin.NEW_METADATA (has extras) } android.content.ContextWrapper.startService:506 android.content.ContextWrapper.startService:506 com.google.android.configupdater.UpdateRequestReceiver.handleMetadataDownload:244 
,I/DownloadManager( 1208): Download 49 starting
,W/ctxmgr  ( 1220): [AclManager]checkPermissionTypeStatus: no inject permission for { uid=10011, packageName=com.google.android.gms }. Returned permission was: PACKAGE_NOT_WHITELISTED for context name=POWER_CONNECTION, account=account#-517948760#
,E/ctxmgr  ( 1220): [PowerConnectionProducer]Could not write powerInfo=Plug state: 2 BatteryLevel: 1.0, status=Status{statusCode=unknown status code: 7503, resolution=null}
,I/DownloadManager( 1208): Download 50 starting
,I/GCoreUlr( 1220): WorldUpdater:com.google.gservices.intent.action.GSERVICES_CHANGED: Ensuring that reporting is stopped because of reasons: {account#2#=[InactiveReason{mVersionCode=0, mIdentifier=12, mName='LocationDisabled'}, InactiveReason{mVersionCode=0, mIdentifier=6, mName='ReportingNotEnabled'}, InactiveReason{mVersionCode=0, mIdentifier=14, mName='HistoryNotEnabled'}]}
,I/GCoreUlr( 1220): Unbound from all location providers
,I/GCoreUlr( 1220): Place inference reporting - stopped
,I/GCoreUlr( 1220): DispatchingService.onDestroy()
,I/GCoreUlr( 1220): Stopping handler for UlrDispSvcFast
,I/GCoreUlr( 1220): Unbound from all location providers
,I/GCoreUlr( 1220): Place inference reporting - stopped
,D/dalvikvm( 1208): GC_CONCURRENT freed 1550K, 46% free 10425K/19088K, paused 7ms+6ms, total 61ms
,I/DownloadManager( 1208): Ignoring Content-Length since Transfer-Encoding is also defined
,I/DownloadManager( 1208): Ignoring Content-Length since Transfer-Encoding is also defined
,V/DownloadManager( 1208): MIME Type = text/plain
,I/DownloadManager( 1208): Download 49 finished with status SUCCESS
,W/ContextImpl( 5464): Implicit intents with startService are not safe: Intent { act=com.google.android.configupdater.SmsShortCodes.NEW_CONTENT (has extras) } android.content.ContextWrapper.startService:506 android.content.ContextWrapper.startService:506 com.google.android.configupdater.UpdateRequestReceiver.handleContentDownload:231 
,I/UpdateFetcherService( 5464): Update downloaded, starting installation
,I/UpdateFetcherService( 5464): Started installation
,I/ConfigUpdateInstallReceiver(  761): Couldn't find current metadata, assuming first update
,I/ConfigUpdateInstallReceiver(  761): Failed to read current content, assuming first update!
,V/DownloadManager( 1208): MIME Type = text/plain
,I/DownloadManager( 1208): Download 50 finished with status SUCCESS
,W/ContextImpl( 5464): Implicit intents with startService are not safe: Intent { act=com.google.android.configupdater.CertPin.NEW_CONTENT (has extras) } android.content.ContextWrapper.startService:506 android.content.ContextWrapper.startService:506 com.google.android.configupdater.UpdateRequestReceiver.handleContentDownload:231 
,I/UpdateFetcherService( 5464): Update downloaded, starting installation
,I/UpdateFetcherService( 5464): Started installation
,I/ConfigUpdateInstallReceiver(  761): Not installing, new version is <= current version
,I/ActivityManager(  761): Killing 4630:com.google.android.apps.docs/u0a90 (adj 15): empty #43
,I/jxcore-log( 4558): Test app app.js loaded
I/jxcore-log( 4558): 
,I/dalvikvm( 4558): Could not find method android.bluetooth.BluetoothAdapter.isMultipleAdvertisementSupported, referenced from method org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager.isBleAdvertisingSupported
,W/dalvikvm( 4558): VFY: unable to resolve virtual method 54: Landroid/bluetooth/BluetoothAdapter;.isMultipleAdvertisementSupported ()Z
,D/dalvikvm( 4558): VFY: replacing opcode 0x6e at 0x0002
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 4558): setDiscoveryMode: Mode set to BLE
,I/jxcore-log( 4558): BLE advertisement is supported
I/jxcore-log( 4558): 
,I/chromium( 4558): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,D/FactoryTest( 4117): Not factory mode
,D/FactoryTest( 4117): Not factory mode. isFactoryMode() returend false
D/MTPRx   ( 4117): DRIVER_TIME_OUT 60s lapsed
,D/MTPRx   ( 4117): still no open session command from host, so toast
W/ContextImpl( 4117): Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1398 android.content.ContextWrapper.startActivity:323 android.content.ContextWrapper.startActivity:323 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:767 android.os.Handler.dispatchMessage:102 
W/ContextImpl( 4117): Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1410 android.app.ContextImpl.startActivity:1399 android.content.ContextWrapper.startActivity:323 android.content.ContextWrapper.startActivity:323 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:767 
,V/ApplicationPolicy(  761): isApplicationStateBlocked userId 0 pkgname com.android.settings
,D/CustomFrequencyManagerService(  761): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 761  pkgName : ACTIVITY_RESUME_BOOSTER@5
,W/ActivityManager(  761): mDVFSHelper.acquire()
,D/LockPatternUtils( 1069): isPcwEnable = null
,D/LockPatternUtils( 1069): isPcwEnable = null
,E/MTPRx   ( 4117): started activity for popup
,I/SQLiteSecureOpenHelper( 2025): getWritableDatabase(pwd)
,I/SQLiteSecureOpenHelper( 2025): getDatabaseLocked(b,b,pwd)...
,E/SMD     (  242): DCD OFF
,E/SettingsReceiverActivity( 4117): PREF_DONT_ASK_AGAIN : true
,D/LockPatternUtils( 1069): isPcwEnable = null
,D/SettingsReceiverActivity( 4117): dev.kiessupport is : TRUE
,I/WindowManager(  761): Screenshot max retries 4 of Token{42eccbe0 ActivityRecord{4315f800 u0 com.test.thalitest/.MainActivity t3}} appWin=Window{4469ad08 u0 com.test.thalitest/com.test.thalitest.MainActivity} drawState=4
,W/WindowManager(  761): Screenshot failure taking screenshot for (720x1280) to layer 21010
D/LockPatternUtils( 1069): isPcwEnable = null
,D/PreloadUpdateManagerStateMachine( 4727): execute::IDLE:EXECUTE
D/PreloadUpdateManagerStateMachine( 4727): exit::IDLE
,D/PreloadUpdateManagerStateMachine( 4727): entry::CHECK_TIMEOUT_FOR_UPDATE
,D/hcjo    ( 4727): AutoUpdateTriggerManager:REQUEST2:requestInterval
,D/hcjo    ( 4727): AutoUpdateTriggerManager:REQUEST2:setInterval:86400000
,D/hcjo    ( 4727): AutoUpdateTriggerManager:REQUEST2:notifyTimedOutAndWriteUpdateCheckedTime
,D/PreloadUpdateManagerStateMachine( 4727): execute::CHECK_TIMEOUT_FOR_UPDATE:TIMED_OUT
D/PreloadUpdateManagerStateMachine( 4727): exit::CHECK_TIMEOUT_FOR_UPDATE
,D/PreloadUpdateManagerStateMachine( 4727): entry::REQ_UPDATE_CHECK
,I/Volley  ( 4727): RestApi Request Add : 2315
,I/qtaguid ( 4727): Failed write_ctrl(t -1 8764893202948816896 -1) res=-1 errno=9
,I/qtaguid ( 4727): Tagging socket -1 with tag 79a327ee00000000(2040735726) for uid -1 failed errno=-9
,I/NetworkManagementSocketTagger( 4727): tagSocketFd(-1, 2040735726, -1) failed with errno-9
,I/GAV4    ( 5378): Thread[GAThread,5,main]: No campaign data found.
,D/EnterpriseDeviceManagerService(  761): Creating context as user 0
,I/qtaguid ( 4727): Failed write_ctrl(u -1) res=-1 errno=9
,I/qtaguid ( 4727): Untagging socket -1 failed errno=-9
,W/NetworkManagementSocketTagger( 4727): untagSocket(-1) failed with errno -9
,D/PreloadUpdateManagerStateMachine( 4727): execute::REQ_UPDATE_CHECK:REQUEST_SUCCESS
D/PreloadUpdateManagerStateMachine( 4727): exit::REQ_UPDATE_CHECK
D/PreloadUpdateManagerStateMachine( 4727): entry::NOTIFY_NOTIFICATION
D/PreloadUpdateManagerStateMachine( 4727): exit::NOTIFY_NOTIFICATION
,D/PreloadUpdateManagerStateMachine( 4727): entry::FINISH
D/PreloadUpdateManagerStateMachine( 4727): exit::FINISH
,D/PreloadUpdateManagerStateMachine( 4727): entry::IDLE
I/ActivityManager(  761): Killing 4663:com.samsung.android.app.watchmanagerstub/u0a100 (adj 15): empty #43
,I/GAV2    ( 4193): Thread[GAThread,5,main]: No campaign data found.
,D/dalvikvm( 4193): GC_FOR_ALLOC freed 20K, 22% free 18294K/23256K, paused 20ms, total 21ms
,I/dalvikvm-heap( 4193): Grow heap (frag case) to 23.260MB for 2129936-byte allocation
,D/AmoledAdjustTimer(  761): prevTemp = 288, currTemp = 293, prevStep = 4, currStep = 4
,D/CustomFrequencyManagerService(  761): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 761  tag : ACTIVITY_RESUME_BOOSTER@5
,W/ActivityManager(  761): mDVFSHelper.release()
,D/CustomFrequencyManagerService(  761): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 761  pkgName : ACTIVITY_RESUME_BOOSTER@9
,E/SMD     (  242): DCD OFF
,I/ActivityManager(  761): Waited long enough for: ServiceRecord{42b2bef0 u0 com.samsung.android.app.headlines/com.samsung.android.internal.headlines.HeadlinesService}
,D/CustomFrequencyManagerService(  761): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 761  tag : ACTIVITY_RESUME_BOOSTER@9
,D/SSRMv2:SIOP(  761): SIOP:: AP = 320, Delta = -20
,E/SMD     (  242): DCD OFF
,D/BatteryService(  761): level:100, scale:100, status:5, health:2, present:true, voltage: 4367, temperature: 293, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:6, charge type:1, power sharing:false
,D/BatteryService(  761): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  761): mCoverManager.getCoverState() : true
,D/BatteryService(  761): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3171): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3171): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,D/PackageManager(  761): [MSG] SEND_PENDING_BROADCAST
,D/PackageManager(  761): Sending to user 0: act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.talk flg=0x4000000 Bundle[{android.intent.extra.changed_component_name=com.google.android.apps.babel.realtimechat.RequestWriter$NetworkStateReceiver, android.intent.extra.DONT_KILL_APP=true, android.intent.extra.UID=10105, android.intent.extra.changed_component_name_list=[Ljava.lang.String;@439f1ca8, com.samsung.android.intent.extra.SECRET_APP=false, android.intent.extra.user_handle=0}]
,D/PackageManager(  761): Sending to user 0: act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000000 Bundle[{android.intent.extra.changed_component_name=com.google.android.gms.checkin.CheckinService$ActiveReceiver, android.intent.extra.DONT_KILL_APP=true, android.intent.extra.UID=10011, android.intent.extra.changed_component_name_list=[Ljava.lang.String;@43079e68, com.samsung.android.intent.extra.SECRET_APP=false, android.intent.extra.user_handle=0}]
,I/InputReader(  761): Reconfiguring input devices.  changes=0x00000010
,I/PackageManager(  761):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  761):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  761):   Scheme: "sms"
I/PackageManager(  761): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,I/PackageManager(  761): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
I/PackageManager(  761):   Action: "android.intent.action.SENDTO"
I/PackageManager(  761):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  761):   Scheme: "smsto"
,I/InputReader(  761): Reconfiguring input devices.  changes=0x00000010
,V/ApplicationPolicy(  761): isApplicationStateBlocked userId 0 pkgname com.google.android.talk
,I/PackageManager(  761):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  761):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  761):   Scheme: "mms"
I/PackageManager(  761): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,D/PackageManager(  761): [MSG] WRITE_SETTINGS
,W/InputMethodInfo(  761): Duplicated subtype definition found: , voice
,D/PackageManager(  761): getApplicationInfo - Execution time: 165 ms
,I/PackageManager(  761):   Action: "android.intent.action.SENDTO"
I/PackageManager(  761):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  761):   Scheme: "mmsto"
I/PackageManager(  761): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,I/IcingCorporaProvider( 2125): Updating corpora: APPS=com.google.android.talk, CONTACTS=MAYBE
,I/PackageManager(  761):   Action: "android.intent.action.SENDTO"
I/PackageManager(  761):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  761):   Scheme: "sms"
I/PackageManager(  761): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,D/FileShare-Server( 4178): ServerBroadcastReceiver.onReceive - action android.intent.action.PACKAGE_CHANGED // package:com.google.android.talk
,I/PackageManager(  761):   Action: "android.intent.action.SENDTO"
I/PackageManager(  761):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  761):   Scheme: "smsto"
I/PackageManager(  761): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,I/PackageManager(  761):   Action: "android.intent.action.SENDTO"
I/PackageManager(  761):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  761):   Scheme: "mms"
I/PackageManager(  761): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,I/Launcher.Workspace( 1252): isBadgeUpdate : false
,I/SELinux ( 5641): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5641):  
,I/PackageManager(  761):   Action: "android.intent.action.SENDTO"
I/PackageManager(  761):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  761):   Scheme: "mmsto"
I/PackageManager(  761): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,I/SELinux ( 5641): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5641):  
I/SELinux ( 5641):  
,I/SELinux ( 5641): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5641): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 5641): >>>>> Normal User
,E/dalvikvm( 5641): >>>>> com.sec.knox.bridge [ userId:0 | appId:1000 ]
E/SELinux ( 5641): [DEBUG] seapp_context_lookup: seinfoCategory = platform
I/PackageManager(  761):   Action: "android.intent.action.SENDTO"
I/PackageManager(  761):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  761):   Scheme: "sms"
I/PackageManager(  761): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,D/TimaKeyStoreProvider( 5641): in addTimaSignatureService
I/PackageManager(  761):   Action: "android.intent.action.SENDTO"
I/PackageManager(  761):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  761):   Scheme: "smsto"
,D/TimaKeyStoreProvider( 5641): Cannot add TimaSignature Service, License check Failed
,I/PackageManager(  761): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
I/IcingCorporaProvider( 2125): UpdateCorporaTask done [took 206 ms] updated apps [took 206 ms] 
D/ActivityThread( 5641): Added TimaKesytore provider
,W/Resources(  761): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
I/PackageManager(  761):   Action: "android.intent.action.SENDTO"
I/PackageManager(  761):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  761):   Scheme: "mms"
I/PackageManager(  761): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,I/PackageManager(  761):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  761):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  761):   Scheme: "mmsto"
I/PackageManager(  761): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,D/dalvikvm( 2125): GC_CONCURRENT freed 1470K, 39% free 11767K/19088K, paused 16ms+6ms, total 102ms
,W/Resources(  761): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,I/PackageManager(  761):   Action: "android.intent.action.SENDTO"
I/PackageManager(  761):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  761):   Scheme: "sms"
I/PackageManager(  761): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,I/PackageManager(  761):   Action: "android.intent.action.SENDTO"
I/PackageManager(  761):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  761):   Scheme: "smsto"
I/PackageManager(  761): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,I/PackageManager(  761): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,I/PackageManager(  761):   Action: "android.intent.action.SENDTO"
I/PackageManager(  761):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  761):   Scheme: "mms"
,I/PackageManager(  761):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  761):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  761):   Scheme: "mmsto"
I/PackageManager(  761): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,W/Resources(  761): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  761): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/BezelQuickConnect( 3154): BezelBroadcastReceiver - onReceive : android.intent.action.PACKAGE_CHANGED
,D/BezelQuickConnect( 3154): BezelBroadcastReceiver - packageName : com.google.android.talk
,D/dalvikvm( 4193): GC_FOR_ALLOC freed 11K, 20% free 20376K/25332K, paused 13ms, total 13ms
,I/dalvikvm-heap( 4193): Grow heap (frag case) to 25.292MB for 2129936-byte allocation
,D/dalvikvm(  761): GC_CONCURRENT freed 3412K, 59% free 23942K/57084K, paused 5ms+12ms, total 124ms
,D/dalvikvm(  761): WAIT_FOR_CONCURRENT_GC blocked 80ms
D/dalvikvm(  761): WAIT_FOR_CONCURRENT_GC blocked 80ms
D/dalvikvm(  761): WAIT_FOR_CONCURRENT_GC blocked 80ms
,D/dalvikvm(  761): WAIT_FOR_CONCURRENT_GC blocked 63ms
,I/ActivityManager(  761): Killing 4689:com.samsung.helphub/1000 (adj 15): empty #43
,W/Resources(  761): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/PackageBroadcastService( 1758): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.talk
,W/Resources(  761): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  761): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,I/IcingCorporaProvider( 2125): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,D/FileShare-Server( 4178): ServerBroadcastReceiver.onReceive - action android.intent.action.PACKAGE_CHANGED // package:com.google.android.gms
,D/BezelQuickConnect( 3154): BezelBroadcastReceiver - onReceive : android.intent.action.PACKAGE_CHANGED
,D/BezelQuickConnect( 3154): BezelBroadcastReceiver - packageName : com.google.android.gms
,D/PackageBroadcastService( 1758): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,I/PackageBroadcastService( 1758): Null package name or gms related package.  Ignoreing.
,W/Resources(  761): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  761): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  761): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  761): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,I/Icing   ( 1758): updateResources: need to parse f{com.google.android.gms}
,W/Resources(  761): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  761): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  761): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,W/Resources(  761): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  761): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  761): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,W/ApplicationsProvider( 1412): Could not fetch usage stats
W/ApplicationsProvider( 1412): java.lang.SecurityException: Neither user 10020 nor current process has android.permission.PACKAGE_USAGE_STATS.
W/ApplicationsProvider( 1412): 	at android.os.Parcel.readException(Parcel.java:1465)
W/ApplicationsProvider( 1412): 	at android.os.Parcel.readException(Parcel.java:1419)
W/ApplicationsProvider( 1412): 	at com.android.internal.app.IUsageStats$Stub$Proxy.getAllPkgUsageStats(IUsageStats.java:317)
W/ApplicationsProvider( 1412): 	at android.app.ActivityManager.getAllPackageUsageStats(ActivityManager.java:2543)
W/ApplicationsProvider( 1412): 	at com.android.providers.applications.ApplicationsProvider.fetchUsageStats(ApplicationsProvider.java:681)
W/ApplicationsProvider( 1412): 	at com.android.providers.applications.ApplicationsProvider.updateApplicationsList(ApplicationsProvider.java:519)
W/ApplicationsProvider( 1412): 	at com.android.providers.applications.ApplicationsProvider.access$300(ApplicationsProvider.java:70)
W/ApplicationsProvider( 1412): 	at com.android.providers.applications.ApplicationsProvider$UpdateHandler.handleMessage(ApplicationsProvider.java:212)
W/ApplicationsProvider( 1412): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/ApplicationsProvider( 1412): 	at android.os.Looper.loop(Looper.java:146)
W/ApplicationsProvider( 1412): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,W/ApplicationsProvider( 1412): Could not fetch usage stats
W/ApplicationsProvider( 1412): java.lang.SecurityException: Neither user 10020 nor current process has android.permission.PACKAGE_USAGE_STATS.
W/ApplicationsProvider( 1412): 	at android.os.Parcel.readException(Parcel.java:1465)
W/ApplicationsProvider( 1412): 	at android.os.Parcel.readException(Parcel.java:1419)
W/ApplicationsProvider( 1412): 	at com.android.internal.app.IUsageStats$Stub$Proxy.getAllPkgUsageStats(IUsageStats.java:317)
W/ApplicationsProvider( 1412): 	at android.app.ActivityManager.getAllPackageUsageStats(ActivityManager.java:2543)
W/ApplicationsProvider( 1412): 	at com.android.providers.applications.ApplicationsProvider.fetchUsageStats(ApplicationsProvider.java:681)
W/ApplicationsProvider( 1412): 	at com.android.providers.applications.ApplicationsProvider.updateApplicationsList(ApplicationsProvider.java:519)
W/ApplicationsProvider( 1412): 	at com.android.providers.applications.ApplicationsProvider.access$300(ApplicationsProvider.java:70)
W/ApplicationsProvider( 1412): 	at com.android.providers.applications.ApplicationsProvider$UpdateHandler.handleMessage(ApplicationsProvider.java:212)
W/ApplicationsProvider( 1412): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/ApplicationsProvider( 1412): 	at android.os.Looper.loop(Looper.java:146)
W/ApplicationsProvider( 1412): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,D/dalvikvm( 1758): GC_CONCURRENT freed 1927K, 35% free 12525K/19088K, paused 5ms+4ms, total 41ms
,I/IcingCorporaProvider( 2125): UpdateCorporaTask done [took 395 ms] updated apps [took 395 ms] 
,W/InputMethodInfo(  761): Duplicated subtype definition found: , voice
,W/Resources(  761): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  761): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  761): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  761): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  761): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  761): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  761): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  761): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  761): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  761): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  761): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,W/Resources(  761): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  761): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  761): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
W/Resources(  761): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  761): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  761): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,I/GCoreNlp( 1220): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,D/LocationProviderProxy(  761): applying state to connected service
,D/LocationProviderProxy(  761): applying state to connected service
,E/SMD     (  242): DCD OFF
,I/Icing   ( 1758): Indexing 49CA7E3A917E607C6D98AA15891295369CED2106 from com.google.android.gms
,D/Icing   ( 1758): Loaded CLD2 Version V2.0 - 20141016
,I/Icing   ( 1758): Indexing done 49CA7E3A917E607C6D98AA15891295369CED2106
,E/SMD     (  242): DCD OFF
,D/AmoledAdjustTimer(  761): prevTemp = 293, currTemp = 293, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP(  761): SIOP:: AP = 310, Delta = -10
,E/SMD     (  242): DCD OFF
,W/ContextImpl(  761): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  242): DCD OFF
,I/PowerManagerService(  761): [PWL] Off : 75s ago
,V/AlarmManager(  761): waitForAlarm result :4
,V/AlarmManager(  761): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,D/Headlines( 5107): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE
,D/BatteryService(  761): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 290, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:5, charge type:1, power sharing:false
,D/BatteryService(  761): stay LED for fully charged
,D/Headlines( 5107): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0
,D/Headlines( 5107): Breath 30259 latestRequest time : 1453985573701 current time : 1453985603960
D/BatteryService(  761): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/UiModeManager(  761): mCoverManager.getCoverState() : true
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,V/HeadsetService( 3171): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3171): Disconnected process message: 10
D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog(  761): !@Sync 4
,E/ActivityThread( 1758): Failed to find provider info for com.android.contacts.metadata
,D/SyncManager(  761): failed sync operation 
,D/SyncManager(  761): not retrying sync operation because the error is a hard error: 
,E/SMD     (  242): DCD OFF
,D/AmoledAdjustTimer(  761): prevTemp = 293, currTemp = 290, prevStep = 4, currStep = 4
,E/SMD     (  242): DCD OFF
,D/SSRMv2:SIOP(  761): SIOP:: AP = 300, Delta = -10
,E/SMD     (  242): DCD OFF
,D/BatteryService(  761): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 288, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-4, charge type:1, power sharing:false
,D/BatteryService(  761): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  761): stay LED for fully charged
,D/UiModeManager(  761): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3171): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3171): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  242): DCD OFF
,D/AmoledAdjustTimer(  761): prevTemp = 290, currTemp = 288, prevStep = 4, currStep = 4
,E/SMD     (  242): DCD OFF
,D/SSRMv2:SIOP(  761): SIOP:: AP = 300, Delta = 0
,W/ContextImpl(  761): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  242): DCD OFF
,E/SMD     (  242): DCD OFF
,D/BatteryService(  761): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-4, charge type:1, power sharing:false
,D/BatteryService(  761): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  761): stay LED for fully charged
,D/UiModeManager(  761): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3171): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3171): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  242): DCD OFF
,D/AmoledAdjustTimer(  761): prevTemp = 288, currTemp = 286, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP(  761): SIOP:: AP = 300, Delta = 0
,E/SMD     (  242): DCD OFF
,E/SMD     (  242): DCD OFF
,I/PowerManagerService(  761): [PWL] Off : 105s ago
,V/AlarmManager(  761): waitForAlarm result :8
,V/AlarmManager(  761): waitForAlarm result :4
,V/AlarmManager(  761): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,D/Headlines( 5107): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE
,D/BatteryService(  761): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 284, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-6, charge type:1, power sharing:false
,D/BatteryService(  761): Sending ACTION_BATTERY_CHANGED.
,E/Watchdog(  761): !@Sync 5
,D/BatteryService(  761): stay LED for fully charged
,D/UiModeManager(  761): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3171): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3171): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,D/Headlines( 5107): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0
,D/Headlines( 5107): Breath 61634 latestRequest time : 1453985573701 current time : 1453985635335
,E/SMD     (  242): DCD OFF
,D/AmoledAdjustTimer(  761): prevTemp = 286, currTemp = 284, prevStep = 4, currStep = 4
,E/SMD     (  242): DCD OFF
,D/SSRMv2:SIOP(  761): SIOP:: AP = 300, Delta = 0
,V/AlarmManager(  761): waitForAlarm result :8
,V/AlarmManager(  761): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1069): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,W/ContextImpl(  761): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  242): DCD OFF
,E/SMD     (  242): DCD OFF
,D/BatteryService(  761): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 284, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:2, charge type:1, power sharing:false
,D/BatteryService(  761): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  761): stay LED for fully charged
,D/UiModeManager(  761): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3171): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3171): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,D/AmoledAdjustTimer(  761): prevTemp = 284, currTemp = 284, prevStep = 4, currStep = 4
,E/SMD     (  242): DCD OFF
,D/SSRMv2:SIOP(  761): SIOP:: AP = 300, Delta = 0
,E/SMD     (  242): DCD OFF
,E/SMD     (  242): DCD OFF
,D/BatteryService(  761): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 283, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService(  761): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  761): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
D/BatteryService(  761): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3171): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3171): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  242): DCD OFF
,D/AmoledAdjustTimer(  761): prevTemp = 284, currTemp = 283, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP(  761): SIOP:: AP = 300, Delta = 0
,E/SMD     (  242): DCD OFF
,W/ContextImpl(  761): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  242): DCD OFF
,V/AlarmManager(  761): waitForAlarm result :8
,D/Headlines( 5107): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE
,D/Headlines( 5107): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0
,D/Headlines( 5107): Breath 90042 latestRequest time : 1453985573701 current time : 1453985663743
,E/Watchdog(  761): !@Sync 6
,D/BatteryService(  761): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  761): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  761): mCoverManager.getCoverState() : true
,D/BatteryService(  761): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3171): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3171): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  242): DCD OFF
,D/AmoledAdjustTimer(  761): prevTemp = 283, currTemp = 282, prevStep = 4, currStep = 4
,I/PowerManagerService(  761): [PWL] Off : 140s ago
,E/SMD     (  242): DCD OFF
,D/SSRMv2:SIOP(  761): SIOP:: AP = 300, Delta = 0
,E/SMD     (  242): DCD OFF
,E/SMD     (  242): DCD OFF
,D/BatteryService(  761): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-2, charge type:1, power sharing:false
,D/BatteryService(  761): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  761): stay LED for fully charged
,D/UiModeManager(  761): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3171): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3171): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer(  761): prevTemp = 282, currTemp = 281, prevStep = 4, currStep = 4
,E/SMD     (  242): DCD OFF
,D/SSRMv2:SIOP(  761): SIOP:: AP = 300, Delta = 0
,W/ContextImpl(  761): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  242): DCD OFF
,E/SMD     (  242): DCD OFF
,D/BatteryService(  761): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-3, charge type:1, power sharing:false
,D/BatteryService(  761): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  761): mCoverManager.getCoverState() : true
,D/BatteryService(  761): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3171): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3171): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  242): DCD OFF
,D/AmoledAdjustTimer(  761): prevTemp = 281, currTemp = 281, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP(  761): SIOP:: AP = 300, Delta = 0
,E/SMD     (  242): DCD OFF
,E/SMD     (  242): DCD OFF
,V/AlarmManager(  761): waitForAlarm result :8
,D/Headlines( 5107): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE
,D/Headlines( 5107): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0
,D/Headlines( 5107): Breath 120043 latestRequest time : 1453985573701 current time : 1453985693744
,D/Headlines( 5107): stop 
,D/Headlines( 5107): Breath.onDestroy : 
,I/ActivityManager(  761): Killing 4703:com.sec.kidsplat.installer/u0a158 (adj 15): empty #43
,I/ClearcutLoggerApiImpl( 1312): disconnect managed GoogleApiClient
,E/Watchdog(  761): !@Sync 7
,D/BatteryService(  761): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 280, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-2, charge type:1, power sharing:false
,D/BatteryService(  761): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  761): mCoverManager.getCoverState() : true
,D/BatteryService(  761): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3171): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
D/HeadsetStateMachine( 3171): Disconnected process message: 10
,E/SMD     (  242): DCD OFF
,D/AmoledAdjustTimer(  761): prevTemp = 281, currTemp = 280, prevStep = 4, currStep = 4
,E/SMD     (  242): DCD OFF
,D/SSRMv2:SIOP(  761): SIOP:: AP = 300, Delta = 0
,V/AlarmManager(  761): waitForAlarm result :8
,V/AlarmManager(  761): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1069): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,W/ContextImpl(  761): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  242): DCD OFF
,E/SMD     (  242): DCD OFF
,D/BatteryService(  761): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-9, charge type:1, power sharing:false
,D/BatteryService(  761): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  761): mCoverManager.getCoverState() : true
,D/BatteryService(  761): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3171): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3171): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,D/AmoledAdjustTimer(  761): prevTemp = 280, currTemp = 279, prevStep = 4, currStep = 4
,E/SMD     (  242): DCD OFF
,I/PowerManagerService(  761): [PWL] Off : 180s ago
,D/SSRMv2:SIOP(  761): SIOP:: AP = 300, Delta = 0
,E/SMD     (  242): DCD OFF
,E/SMD     (  242): DCD OFF
,D/BatteryService(  761): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-7, charge type:1, power sharing:false
,D/BatteryService(  761): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  761): stay LED for fully charged
,D/UiModeManager(  761): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3171): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3171): Disconnected process message: 10
D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  242): DCD OFF
,D/AmoledAdjustTimer(  761): prevTemp = 279, currTemp = 279, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP(  761): SIOP:: AP = 300, Delta = 0
,E/SMD     (  242): DCD OFF
,W/ContextImpl(  761): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  242): DCD OFF
,E/Watchdog(  761): !@Sync 8
,D/BatteryService(  761): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  761): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  761): mCoverManager.getCoverState() : true
,D/BatteryService(  761): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3171): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3171): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  242): DCD OFF
,D/AmoledAdjustTimer(  761): prevTemp = 279, currTemp = 278, prevStep = 4, currStep = 4
,E/SMD     (  242): DCD OFF
,D/SSRMv2:SIOP(  761): SIOP:: AP = 300, Delta = 0
,E/SMD     (  242): DCD OFF
,E/SMD     (  242): DCD OFF
,D/BatteryService(  761): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-5, charge type:1, power sharing:false
,D/BatteryService(  761): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  761): mCoverManager.getCoverState() : true
,D/BatteryService(  761): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3171): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3171): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,D/AmoledAdjustTimer(  761): prevTemp = 278, currTemp = 278, prevStep = 4, currStep = 4
,E/SMD     (  242): DCD OFF
,D/SSRMv2:SIOP(  761): SIOP:: AP = 300, Delta = 0
,W/ContextImpl(  761): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  242): DCD OFF
,E/SMD     (  242): DCD OFF
,D/BatteryService(  761): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-5, charge type:1, power sharing:false
,D/BatteryService(  761): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  761): mCoverManager.getCoverState() : true
,D/BatteryService(  761): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3171): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3171): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  242): DCD OFF
,D/AmoledAdjustTimer(  761): prevTemp = 278, currTemp = 278, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP(  761): SIOP:: AP = 300, Delta = 0
,E/SMD     (  242): DCD OFF
,E/SMD     (  242): DCD OFF
,I/PowerManagerService(  761): [PWL] Off : 225s ago
,E/Watchdog(  761): !@Sync 9
,D/BatteryService(  761): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-5, charge type:1, power sharing:false
,D/BatteryService(  761): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  761): mCoverManager.getCoverState() : true
,D/BatteryService(  761): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3171): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3171): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  242): DCD OFF
,D/AmoledAdjustTimer(  761): prevTemp = 278, currTemp = 277, prevStep = 4, currStep = 4
,E/SMD     (  242): DCD OFF
,D/SSRMv2:SIOP(  761): SIOP:: AP = 300, Delta = 0
,V/AlarmManager(  761): waitForAlarm result :8
,V/AlarmManager(  761): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1069): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,W/ContextImpl(  761): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  242): DCD OFF
,E/SMD     (  242): DCD OFF
,D/BatteryService(  761): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:3, charge type:1, power sharing:false
,D/BatteryService(  761): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  761): stay LED for fully charged
,D/UiModeManager(  761): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3171): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3171): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,D/AmoledAdjustTimer(  761): prevTemp = 277, currTemp = 277, prevStep = 4, currStep = 4
,E/SMD     (  242): DCD OFF
,D/SSRMv2:SIOP(  761): SIOP:: AP = 300, Delta = 0
,E/SMD     (  242): DCD OFF
,I/jxcore-log( 4558): --= Surplus to requirements =--
I/jxcore-log( 4558): 
,I/jxcore-log( 4558): ****TEST TOOK:  ms ****
I/jxcore-log( 4558): 
,I/jxcore-log( 4558): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 4558): 
,E/SMD     (  242): DCD OFF
,D/AndroidRuntime( 5737): 
D/AndroidRuntime( 5737): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/AndroidRuntime( 5737): CheckJNI is OFF
,D/AndroidRuntime( 5737): setted country_code = Poland
,D/AndroidRuntime( 5737): setted countryiso_code = PL
,D/AndroidRuntime( 5737): setted sales_code = XEO
D/AndroidRuntime( 5737): readGMSProperty: start
,D/AndroidRuntime( 5737): readGMSProperty: already setted!!
D/AndroidRuntime( 5737): readGMSProperty: end
,D/AndroidRuntime( 5737): addProductProperty: start
,D/dalvikvm( 5737): Trying to load lib libjavacore.so 0x0
,D/dalvikvm( 5737): Added shared lib libjavacore.so 0x0
,D/dalvikvm( 5737): Trying to load lib libnativehelper.so 0x0
,D/dalvikvm( 5737): Added shared lib libnativehelper.so 0x0
,D/dalvikvm( 5737): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
,E/memtrack( 5737): Couldn't load memtrack module (No such file or directory)
,E/android.os.Debug( 5737): failed to load memtrack module: -2
,D/dalvikvm( 5737): Note: class Landroid/app/ActivityManagerNative; has 192 unimplemented (abstract) methods
,D/AndroidRuntime( 5737): Calling main entry com.android.commands.pm.Pm
,D/PackageManagerService(  761): deletePackageAsUser- pkg:com.test.thalitest, userId:0
,D/PersonaManagerService(  761): isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
D/PersonaManagerService(  761): isFromApprovedUnInstaller: isApproved : true
D/PersonaManagerService(  761): isFromApprovedUnInstaller: isApproved before exit: true
D/PackageManager(  761): deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag3
,D/PackageManager(  761): deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag3
,D/PackageManagerService(  761): deletePackage- pkg:com.test.thalitest, edmuserId:0
D/PackageManagerService(  761): deletePackage- pkg:com.test.thalitest, edmuserId:-1
,D/ApplicationPolicy(  761): getApplicationUninstallationEnabled
D/PackageManager(  761): START PACKAGE DELETE: observer{1125490984}
D/PackageManager(  761): pkg{<packageName>}
D/PackageManager(  761): user{0}
D/PackageManager(  761): deletePackageAsUser : uid = 2000 userId = 0
,D/PackageManager(  761): [MSG] DELETE_PACKAGE_AS_USER
D/ApplicationPolicy(  761): getApplicationUninstallationEnabled :  enabled true
D/PackageManagerService(  761): deletePackageX- pkg:com.test.thalitest, userId:0
,D/PackageManager(  761): !@killApplicatoin: 10179, uninstall pkg
,I/ActivityManager(  761): Killing 4558:com.test.thalitest/u0a179 (adj 0): stop com.test.thalitest
,D/CustomFrequencyManagerService(  761): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 761  pkgName : ACTIVITY_RESUME_BOOSTER@5
,W/ActivityManager(  761): mDVFSHelper.acquire()
,D/KeyguardUpdateMonitor( 1069): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1069): handleKeyguardVisibilityChanged(1)
,D/KeyguardUpdateMonitor( 1069): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1069): handleKeyguardVisibilityChanged(1)
,D/Launcher( 1252): onRestart, Launcher: 1114552488
D/Launcher( 1252): onStart, Launcher: 1114552488
,D/Launcher.HomeView( 1252): onStart
,D/SurfaceWidgetClient$ISurfaceWidgetStub( 1447): [237392/5] Surface widget visibility changed visibility = true on instance = 1
,D/SurfaceWidget.Renderer( 1447): [237392/5] SurfaceWidget drawing first frame
,I/SurfaceFlinger(  248): id=17 Removed NainActivit (7/11)
,I/WindowState(  761): WIN DEATH: Window{4469ad08 u0 com.test.thalitest/com.test.thalitest.MainActivity}
I/SurfaceFlinger(  248): id=17 Removed NainActivit (-2/11)
D/KeyguardUpdateMonitor( 1069): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1069): handleKeyguardVisibilityChanged(1)
I/SurfaceFlinger(  248): id=17 Removed NainActivit (-2/11)
,D/PackageManager(  761): checkUidPermission - Execution time: 107 ms
,D/PackageManager(  761): queryIntentReceivers - Execution time: 137 ms
,D/LockPatternUtils( 1069): isPcwEnable = null
,I/SurfaceFlinger(  248): id=19 createSurf (720x1280),1 flag=4, Mauncher
,D/PackageManager(  761): Sending to user 0: act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000000 Bundle[{android.intent.extra.REMOVED_FOR_ALL_USERS=true, android.intent.extra.UID=10179, android.intent.extra.DATA_REMOVED=true, android.intent.extra.user_handle=0}]
D/KeyguardUpdateMonitor( 1069): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1069): handleKeyguardVisibilityChanged(1)
D/KeyguardUpdateMonitor( 1069): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1069): handleKeyguardVisibilityChanged(1)
,D/dalvikvm( 2125): GC_EXPLICIT freed 1014K, 42% free 11247K/19088K, paused 3ms+3ms, total 41ms
,D/dalvikvm( 1758): GC_EXPLICIT freed 1160K, 35% free 12408K/19088K, paused 5ms+5ms, total 55ms
,I/SurfaceFlinger(  248): id=20 createSurf (1x1),2 flag=404, CatteryCove
D/PackageManager(  761): Sending to user 0: act=android.intent.action.PACKAGE_FULLY_REMOVED dat=package:com.test.thalitest flg=0x4000000 Bundle[{android.intent.extra.REMOVED_FOR_ALL_USERS=true, android.intent.extra.UID=10179, android.intent.extra.DATA_REMOVED=true, android.intent.extra.user_handle=0}]
,D/KeyguardUpdateMonitor( 1069): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1069): handleKeyguardVisibilityChanged(1)
,D/KeyguardUpdateMonitor( 1069): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1069): handleKeyguardVisibilityChanged(1)
D/KeyguardUpdateMonitor( 1069): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1069): handleKeyguardVisibilityChanged(1)
W/InputMethodInfo(  761): Duplicated subtype definition found: , voice
,D/AdaptiveEventManager( 1069): action=android.intent.action.PACKAGE_REMOVED
,D/dalvikvm( 1412): GC_EXPLICIT freed 4430K, 48% free 10019K/19088K, paused 4ms+4ms, total 87ms
,D/QuickConnect[1.1][2] ( 3142): SconnectManager.onReceiver - action : android.intent.action.PACKAGE_REMOVED, package : com.test.thalitest
I/PackageManager(  761):   Action: "android.intent.action.SENDTO"
I/PackageManager(  761):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  761):   Scheme: "sms"
I/PackageManager(  761): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,I/FPMS_FingerprintManagerService( 1088): onReceive: android.intent.action.PACKAGE_REMOVED
,W/GeofencerStateMachine( 1220): Ignoring removeGeofence because network location is disabled.
D/elm:14132( 5309): ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
I/PackageManager(  761):   Action: "android.intent.action.SENDTO"
I/PackageManager(  761):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  761):   Scheme: "smsto"
I/PackageManager(  761): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,D/EnterpriseDeviceManagerService(  761): Package has changed for user 0
,D/EnterpriseDeviceManagerService(  761): Admin package name: com.google.android.gms
D/dalvikvm(  761): GC_EXPLICIT freed 4077K, 58% free 24022K/56128K, paused 6ms+15ms, total 157ms
,D/dalvikvm(  761): WAIT_FOR_CONCURRENT_GC blocked 105ms
,I/PackageManager(  761):   Action: "android.intent.action.SENDTO"
I/PackageManager(  761):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  761):   Scheme: "mms"
I/PackageManager(  761): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,I/InputReader(  761): Reconfiguring input devices.  changes=0x00000010
,D/elm:14132( 5309): ELMAbstractReceiver : Receive Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
D/elm:14132( 5309): ElmAgentService : onCreate()
D/elm:14132( 5309): ElmAgentService : onHandleIntent() Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
D/elm:14132( 5309): MainReceiver.listeningToPackageRemoved()
D/elm:14132( 5309): MDMBridge.getInstance()
,D/elm:14132( 5309): MDMBridge.getAllLicenseInfoFromSDK()
D/CustomFrequencyManagerService(  761): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 761  tag : ACTIVITY_RESUME_BOOSTER@5
W/ActivityManager(  761): mDVFSHelper.release()
D/CustomFrequencyManagerService(  761): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 761  pkgName : ACTIVITY_RESUME_BOOSTER@9
,D/KeyguardUpdateMonitor( 1069): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1069): handleKeyguardVisibilityChanged(1)
,D/Launcher.HomeView( 1252): onStop
I/PackageManager(  761):   Action: "android.intent.action.SENDTO"
I/PackageManager(  761):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  761):   Scheme: "mmsto"
,D/elm:14132( 5309): MDMBridge.getAllLicenseInfoFromSDK()
,I/SELinux ( 5775): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5775):  
I/PackageManager(  761): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,D/KeyguardUpdateMonitor( 1069): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1069): handleKeyguardVisibilityChanged(1)
,I/PackageManager(  761):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  761):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  761):   Scheme: "sms"
,D/RCPManagerService(  761): PackageReceiver onReceive()
I/PackageManager(  761): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,I/PackageManager(  761):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  761):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  761):   Scheme: "smsto"
,I/PackageManager(  761): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
I/HarmonyEASService(  761): onReceive : android.intent.action.PACKAGE_REMOVED for 0
D/elm:14132( 5309): MainReceiver.listeningToPackageRemoved(). SEND to KLMS. Remove All KNOX/ONS License
I/SELinux ( 5775): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5775):  
I/SELinux ( 5775):  
I/SELinux ( 5775): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 5775): [DEBUG] seapp_context_lookup: seinfoCategory = platform
D/elm:14132( 5309): ElmAgentService : onDestroy().
E/dalvikvm( 5775): >>>>> Normal User
E/dalvikvm( 5775): >>>>> com.sec.android.service.health [ userId:0 | appId:10016 ]
E/SELinux ( 5775): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,W/Resources(  761): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/TimaKeyStoreProvider( 5775): in addTimaSignatureService
I/PackageManager(  761):   Action: "android.intent.action.SENDTO"
I/PackageManager(  761):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  761):   Scheme: "mms"
,D/TimaKeyStoreProvider( 5775): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5775): Added TimaKesytore provider
I/PackageManager(  761): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,I/PackageManager(  761):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  761):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  761):   Scheme: "mmsto"
I/PackageManager(  761): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,W/Resources(  761): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/dalvikvm( 1252): GC_CONCURRENT freed 6591K, 34% free 18116K/27228K, paused 6ms+4ms, total 91ms
,W/Resources(  761): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  761): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/ActivityManager(  761): Permission Denial: getCurrentUser() from pid=5775, uid=10016 requires android.permission.INTERACT_ACROSS_USERS
,D/BackupManagerService(  761): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
,V/BackupManagerService(  761): removePackageParticipantsLocked: uid=10179 #1
,W/Resources(  761): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/BatteryService(  761): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
D/BatteryService(  761): stay LED for fully charged
,D/dalvikvm(  761): GC_EXPLICIT freed 1220K, 58% free 23963K/56128K, paused 7ms+21ms, total 304ms
,D/BatteryService(  761): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
V/HeadsetService( 3171): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/UiModeManager(  761): mCoverManager.getCoverState() : true
D/HeadsetStateMachine( 3171): Disconnected process message: 10
,D/dalvikvm( 5775): No JNI_OnLoad found in /system/lib/libsecure_storage_jni.so 0x42646d90, skipping init
I/SecureStorage( 5775): [INFO]: SPID(0x00000000)Checking if this device supports Secure Storage
,I/SecureStorage( 5775): [INFO]: SPID(0x00000000)This device supports Secure Storage
I/SecureStorage(  301): [INFO]: SPID(0x00000004)Credentials: uid 10016, gid 10016, pid 5775
I/SecureStorage(  301): [INFO]: SPID(0x00000004)Received function mask & code: 0000010C
,I/SecureStorage( 5775): [INFO]: SPID(0x00000000)SS Daemon is running
,D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/SecureStorage( 5775): [INFO]: SPID(0x00000000)Processing data
I/SecureStorage(  301): [INFO]: SPID(0x00000004)Credentials: uid 10016, gid 10016, pid 5775
,I/SecureStorage(  301): [INFO]: SPID(0x00000004)Received function mask & code: 00000106
,W/Resources(  761): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/STATUSBAR-IconMerger( 1069): checkOverflow(288), More:false, Req:false Child:2
,W/Resources(  761): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/PackageManager(  761): delete sourFile : 
,D/PackageManager(  761): delete native library directory: 
,D/PackageManager(  761): return delete result to caller: 1125490984
,D/AndroidRuntime( 5737): Shutting down VM
,D/dalvikvm( 5737): GC_CONCURRENT freed 96K, 14% free 670K/772K, paused 1ms+0ms, total 3ms
D/PackageManager(  761): returnCode: 1
,I/PackageManager(  761):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  761):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  761):   Scheme: "sms"
I/PackageManager(  761): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,I/PackageManager(  761):   Action: "android.intent.action.SENDTO"
I/PackageManager(  761):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  761):   Scheme: "smsto"
I/PackageManager(  761): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,I/PackageManager(  761):   Action: "android.intent.action.SENDTO"
I/PackageManager(  761):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  761):   Scheme: "mms"
I/PackageManager(  761): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,I/PackageManager(  761):   Action: "android.intent.action.SENDTO"
I/PackageManager(  761):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  761):   Scheme: "mmsto"
I/PackageManager(  761): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,W/Resources(  761): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  761): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  761): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  761): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,W/Resources(  761): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  761): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  761): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,W/Resources(  761): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  761): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  761): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,I/CrashAnrDetector(  761): onPackageRemoved : com.test.thalitest
D/UsbSettingsManager(  761): clearDefaults: com.test.thalitest
,D/InputReader(  761): Processing first event
,W/ApplicationsProvider( 1412): Could not fetch usage stats
W/ApplicationsProvider( 1412): java.lang.SecurityException: Neither user 10020 nor current process has android.permission.PACKAGE_USAGE_STATS.
W/ApplicationsProvider( 1412): 	at android.os.Parcel.readException(Parcel.java:1465)
W/ApplicationsProvider( 1412): 	at android.os.Parcel.readException(Parcel.java:1419)
W/ApplicationsProvider( 1412): 	at com.android.internal.app.IUsageStats$Stub$Proxy.getAllPkgUsageStats(IUsageStats.java:317)
W/ApplicationsProvider( 1412): 	at android.app.ActivityManager.getAllPackageUsageStats(ActivityManager.java:2543)
W/ApplicationsProvider( 1412): 	at com.android.providers.applications.ApplicationsProvider.fetchUsageStats(ApplicationsProvider.java:681)
W/ApplicationsProvider( 1412): 	at com.android.providers.applications.ApplicationsProvider.updateApplicationsList(ApplicationsProvider.java:519)
W/ApplicationsProvider( 1412): 	at com.android.providers.applications.ApplicationsProvider.access$300(ApplicationsProvider.java:70)
W/ApplicationsProvider( 1412): 	at com.android.providers.applications.ApplicationsProvider$UpdateHandler.handleMessage(ApplicationsProvider.java:209)
W/ApplicationsProvider( 1412): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/ApplicationsProvider( 1412): 	at android.os.Looper.loop(Looper.java:146)
W/ApplicationsProvider( 1412): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,D/CustomFrequencyManagerService(  761): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 761  tag : ACTIVITY_RESUME_BOOSTER@9

```
