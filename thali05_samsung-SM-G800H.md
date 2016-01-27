#### Test 57348078846ce9d_thali05_samsung-SM-G800H Logs


```
--------- beginning of /dev/log/main
D/GalaxyFinderApplication( 4447): [Slink platform] Version = 29011
D/GalaxyFinderApplication( 4447): [Slink platform] use state of slink location service is [false] to [true]
I/SELinux ( 4466): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 4466):  
--------- beginning of /dev/log/system
I/ActivityManager(  780): Killing 3096:com.LocalFota/u0a110 (adj 15): empty #43
I/SELinux ( 4466): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 4466):  
I/SELinux ( 4466):  
I/SELinux ( 4466): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 4466): [DEBUG] seapp_context_lookup: seinfoCategory = release
E/dalvikvm( 4466): >>>>> Normal User
E/dalvikvm( 4466): >>>>> com.sec.android.app.shealth [ userId:0 | appId:10035 ]
E/SELinux ( 4466): [DEBUG] seapp_context_lookup: seinfoCategory = release
,D/TimaKeyStoreProvider( 4466): in addTimaSignatureService
D/TimaKeyStoreProvider( 4466): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 4466): Added TimaKesytore provider
W/ActivityManager(  780): Permission Denial: getCurrentUser() from pid=4466, uid=10035 requires android.permission.INTERACT_ACROSS_USERS
W/ContextImpl( 4466): Implicit intents with startService are not safe: Intent { act=com.sec.android.service.health.cp.accesscontrol } android.content.ContextWrapper.bindService:529 com.samsung.android.sdk.health.content.ShealthAccessControl.startService:274 com.samsung.android.sdk.health.content.ShealthAccessControl.requestPermission:212 
I/PowerManagerService(  780): [PWL] Off : 30s ago
I/SELinux ( 4492): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 4492):  
E/Device Type Shared Preferences( 4466): Device Type Shared Preferences - getDeviceTypeChecked -true
E/Device Type Shared Preferences( 4466): Device Type Shared Preferences - not connecting to service
E/com.sec.android.app.shealth.SHealthApplication( 4466): ContentProvider is not null
I/SELinux ( 4492): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 4492):  
I/SELinux ( 4492):  
I/SELinux ( 4492): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 4492): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 4492): >>>>> Normal User
E/dalvikvm( 4492): >>>>> com.sec.android.service.health [ userId:0 | appId:10016 ]
E/SELinux ( 4492): [DEBUG] seapp_context_lookup: seinfoCategory = platform
D/TimaKeyStoreProvider( 4492): in addTimaSignatureService
D/TimaKeyStoreProvider( 4492): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 4492): Added TimaKesytore provider
V/MediaPlayer( 4466): decode(61, 33979084, 48105)
V/MediaPlayerService(  254): decode(35, 33979084, 48105)
V/MediaPlayerService(  254): player type = 3
V/AwesomePlayer(  254): setDefault
V/AwesomePlayer(  254): constructor
V/AwesomePlayer(  254): setDefault
V/AwesomePlayer(  254): reset_l()
V/AwesomePlayer(  254): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  254): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  254): mAudioTrackVector clear
V/AwesomePlayer(  254): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  254): mSecMediaClock clear
V/StagefrightPlayer(  254): StagefrightPlayer
V/AwesomePlayer(  254): setListener
V/StagefrightPlayer(  254): initCheck
V/AwesomePlayer(  254): setAudioSink
V/StagefrightPlayer(  254): setDataSource(35, 33979084, 48105)
V/AwesomePlayer(  254): reset_l()
V/AwesomePlayer(  254): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  254): notify(0xb76f7810, 8, 0, 0)
V/AudioCache(  254): ignored
V/AwesomePlayer(  254): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  254): mAudioTrackVector clear
V/AwesomePlayer(  254): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  254): mSecMediaClock clear
V/AwesomePlayer(  254): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer(  254): mBitrate = -1 bits/sec
V/AwesomePlayer(  254): current audio track index (0) is added to vector
V/AwesomePlayer(  254): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer(  254): AwesomePlayer::setDataSource_l():: This is not a DRM content
V/MediaPlayerService(  254): prepare
V/AwesomePlayer(  254): prepareAsync
V/MediaPlayerService(  254): wait for prepare
V/AwesomePlayer(  254): onPrepareAsyncEvent
I/SecMediaClock(  254): SecMediaClock constructor
I/SecMediaClock(  254): reset
V/AwesomePlayer(  254): initAudioDecoder
V/AwesomePlayer(  254): checkOffloadExceptions is true
I/OMXCodec(  254): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
I/OMX     (  254): mDispatchers.add
I/OMXCodec(  254): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec(  254): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec(  254): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec(  254): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/OMXCodec(  254): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer(  254): finishAsyncPrepare_l
V/AwesomePlayer(  254): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache(  254): notify(0xb76f7810, 200, 973, 0)
V/AudioCache(  254): ignored
V/AwesomePlayer(  254): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  254): notify(0xb76f7810, 5, 0, 0)
V/AudioCache(  254): ignored
V/AwesomePlayer(  254): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  254): notify(0xb76f7810, 1, 0, 0)
V/AudioCache(  254): prepared
V/AudioCache(  254): wait - success
V/MediaPlayerService(  254): start
V/StagefrightPlayer(  254): start
V/AwesomePlayer(  254): play
V/AwesomePlayer(  254): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer(  254): startAudioPlayer_l, sendErrorNotification (0)
I/OMXCodec(  254): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec(  254): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec(  254): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/AudioPlayer(  254):  Audioplayer kKeyAudioPCMFormat:1, 2, 0
I/AudioPlayer(  254):  Audioplayer kKeyAudioPCMFormat read fail(2, 1)
V/AudioCache(  254): open(44100, 2, 0x0, 1, 4)
V/AwesomePlayer(  254): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache(  254): notify(0xb76f7810, 6, 0, 0)
V/AudioCache(  254): ignored
V/AwesomePlayer(  254): addBatteryData
V/MediaPlayerService(  254): wait for playback complete
I/OMXCodec(  254): [OMX.google.vorbis.decoder] End Of Stream
V/AwesomePlayer(  254): postAudioEOS delayUs (0)
V/AwesomePlayer(  254): onCheckAudioStatus
V/AwesomePlayer(  254): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  254): onStreamDone
V/AwesomePlayer(  254): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  254): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  254): notify(0xb76f7810, 2, 0, 0)
V/AudioCache(  254): playback complete - thread will wake up later
V/AwesomePlayer(  254): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  254): notify(0xb76f7810, 7, 0, 0)
V/AudioCache(  254): ignored
V/AwesomePlayer(  254): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer(  254): addBatteryData
V/AudioCache(  254): wait - success
V/StagefrightPlayer(  254): reset
V/AwesomePlayer(  254): reset_l()
V/AwesomePlayer(  254): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  254): notify(0xb76f7810, 8, 0, 0)
V/AudioCache(  254): ignored
V/AwesomePlayer(  254): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  254): mAudioTrackVector clear
I/OMXCodec(  254): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec(  254): [OMX.google.vorbis.decoder] stop() sendCommand(0x37, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec(  254): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
I/OMXCodec(  254): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/OMX     (  254): instance freeNode
W/ActivityManager(  780): Permission Denial: getCurrentUser() from pid=4492, uid=10016 requires android.permission.INTERACT_ACROSS_USERS
I/AudioPlayer(  254): reset out
V/AwesomePlayer(  254): reset_l() mAudioPlayer successfully deleted
I/SecMediaClock(  254): SecMediaClock destructor
V/AwesomePlayer(  254): mSecMediaClock clear
V/StagefrightPlayer(  254): ~StagefrightPlayer
V/StagefrightPlayer(  254): reset
V/AwesomePlayer(  254): reset_l()
V/AwesomePlayer(  254): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  254): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  254): mAudioTrackVector clear
V/AwesomePlayer(  254): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  254): mSecMediaClock clear
V/AwesomePlayer(  254): destructor
V/AwesomePlayer(  254): reset_l()
V/AwesomePlayer(  254): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  254): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  254): mAudioTrackVector clear
V/AwesomePlayer(  254): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  254): mSecMediaClock clear
V/MediaPlayer( 4466): decode(63, 33914984, 10421)
V/MediaPlayerService(  254): decode(35, 33914984, 10421)
V/MediaPlayerService(  254): player type = 3
V/AwesomePlayer(  254): setDefault
V/AwesomePlayer(  254): constructor
V/AwesomePlayer(  254): setDefault
V/AwesomePlayer(  254): reset_l()
V/AwesomePlayer(  254): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  254): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  254): mAudioTrackVector clear
V/AwesomePlayer(  254): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  254): mSecMediaClock clear
V/StagefrightPlayer(  254): StagefrightPlayer
V/AwesomePlayer(  254): setListener
V/StagefrightPlayer(  254): initCheck
V/AwesomePlayer(  254): setAudioSink
V/StagefrightPlayer(  254): setDataSource(35, 33914984, 10421)
V/AwesomePlayer(  254): reset_l()
V/AwesomePlayer(  254): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  254): notify(0xb76fee30, 8, 0, 0)
V/AudioCache(  254): ignored
V/AwesomePlayer(  254): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  254): mAudioTrackVector clear
V/AwesomePlayer(  254): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  254): mSecMediaClock clear
V/AwesomePlayer(  254): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer(  254): mBitrate = -1 bits/sec
V/AwesomePlayer(  254): current audio track index (0) is added to vector
V/AwesomePlayer(  254): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer(  254): AwesomePlayer::setDataSource_l():: This is not a DRM content
V/MediaPlayerService(  254): prepare
V/AwesomePlayer(  254): prepareAsync
V/MediaPlayerService(  254): wait for prepare
V/AwesomePlayer(  254): onPrepareAsyncEvent
I/SecMediaClock(  254): SecMediaClock constructor
I/SecMediaClock(  254): reset
V/AwesomePlayer(  254): initAudioDecoder
V/AwesomePlayer(  254): checkOffloadExceptions is true
I/OMXCodec(  254): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
I/OMX     (  254): mDispatchers.add
I/OMXCodec(  254): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec(  254): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec(  254): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec(  254): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/OMXCodec(  254): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer(  254): finishAsyncPrepare_l
V/AwesomePlayer(  254): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache(  254): notify(0xb76fee30, 200, 973, 0)
V/AudioCache(  254): ignored
V/AwesomePlayer(  254): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  254): notify(0xb76fee30, 5, 0, 0)
V/AudioCache(  254): ignored
V/AwesomePlayer(  254): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  254): notify(0xb76fee30, 1, 0, 0)
V/AudioCache(  254): prepared
V/AudioCache(  254): wait - success
V/MediaPlayerService(  254): start
V/StagefrightPlayer(  254): start
V/AwesomePlayer(  254): play
V/AwesomePlayer(  254): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer(  254): startAudioPlayer_l, sendErrorNotification (0)
I/OMXCodec(  254): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec(  254): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec(  254): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/AudioPlayer(  254):  Audioplayer kKeyAudioPCMFormat:1, 2, 0
I/AudioPlayer(  254):  Audioplayer kKeyAudioPCMFormat read fail(2, 1)
V/AudioCache(  254): open(44100, 2, 0x0, 1, 4)
V/AwesomePlayer(  254): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache(  254): notify(0xb76fee30, 6, 0, 0)
V/AudioCache(  254): ignored
V/AwesomePlayer(  254): addBatteryData
V/MediaPlayerService(  254): wait for playback complete
I/OMXCodec(  254): [OMX.google.vorbis.decoder] End Of Stream
V/AwesomePlayer(  254): postAudioEOS delayUs (0)
V/AwesomePlayer(  254): onCheckAudioStatus
V/AwesomePlayer(  254): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  254): onStreamDone
V/AwesomePlayer(  254): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  254): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  254): notify(0xb76fee30, 2, 0, 0)
V/AudioCache(  254): playback complete - thread will wake up later
V/AwesomePlayer(  254): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  254): notify(0xb76fee30, 7, 0, 0)
V/AudioCache(  254): ignored
V/AwesomePlayer(  254): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer(  254): addBatteryData
V/AudioCache(  254): wait - success
V/StagefrightPlayer(  254): reset
V/AwesomePlayer(  254): reset_l()
V/AwesomePlayer(  254): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  254): notify(0xb76fee30, 8, 0, 0)
V/AudioCache(  254): ignored
V/AwesomePlayer(  254): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  254): mAudioTrackVector clear
I/OMXCodec(  254): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec(  254): [OMX.google.vorbis.decoder] stop() sendCommand(0x38, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec(  254): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
I/OMXCodec(  254): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/OMX     (  254): instance freeNode
I/AudioPlayer(  254): reset out
V/AwesomePlayer(  254): reset_l() mAudioPlayer successfully deleted
I/SecMediaClock(  254): SecMediaClock destructor
V/AwesomePlayer(  254): mSecMediaClock clear
V/StagefrightPlayer(  254): ~StagefrightPlayer
V/StagefrightPlayer(  254): reset
V/AwesomePlayer(  254): reset_l()
V/AwesomePlayer(  254): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  254): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  254): mAudioTrackVector clear
V/AwesomePlayer(  254): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  254): mSecMediaClock clear
V/AwesomePlayer(  254): destructor
V/AwesomePlayer(  254): reset_l()
V/AwesomePlayer(  254): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  254): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  254): mAudioTrackVector clear
V/AwesomePlayer(  254): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  254): mSecMediaClock clear
V/MediaPlayer( 4466): decode(64, 37457308, 34198)
V/MediaPlayerService(  254): decode(35, 37457308, 34198)
V/MediaPlayerService(  254): player type = 3
V/AwesomePlayer(  254): setDefault
V/AwesomePlayer(  254): constructor
V/AwesomePlayer(  254): setDefault
V/AwesomePlayer(  254): reset_l()
V/AwesomePlayer(  254): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  254): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  254): mAudioTrackVector clear
V/AwesomePlayer(  254): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  254): mSecMediaClock clear
V/StagefrightPlayer(  254): StagefrightPlayer
V/AwesomePlayer(  254): setListener
V/StagefrightPlayer(  254): initCheck
V/AwesomePlayer(  254): setAudioSink
V/StagefrightPlayer(  254): setDataSource(35, 37457308, 34198)
V/AwesomePlayer(  254): reset_l()
V/AwesomePlayer(  254): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  254): notify(0xb76fa418, 8, 0, 0)
V/AudioCache(  254): ignored
V/AwesomePlayer(  254): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  254): mAudioTrackVector clear
V/AwesomePlayer(  254): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  254): mSecMediaClock clear
D/dalvikvm( 4492): No JNI_OnLoad found in /system/lib/libsecure_storage_jni.so 0x42622b80, skipping init
I/SecureStorage( 4492): [INFO]: SPID(0x00000000)Checking if this device supports Secure Storage
I/SecureStorage( 4492): [INFO]: SPID(0x00000000)This device supports Secure Storage
V/AwesomePlayer(  254): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer(  254): mBitrate = -1 bits/sec
V/AwesomePlayer(  254): current audio track index (0) is added to vector
V/AwesomePlayer(  254): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer(  254): AwesomePlayer::setDataSource_l():: This is not a DRM content
V/MediaPlayerService(  254): prepare
V/AwesomePlayer(  254): prepareAsync
V/MediaPlayerService(  254): wait for prepare
V/AwesomePlayer(  254): onPrepareAsyncEvent
I/SecMediaClock(  254): SecMediaClock constructor
I/SecMediaClock(  254): reset
V/AwesomePlayer(  254): initAudioDecoder
V/AwesomePlayer(  254): checkOffloadExceptions is true
I/OMXCodec(  254): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
I/OMX     (  254): mDispatchers.add
I/OMXCodec(  254): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec(  254): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec(  254): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec(  254): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/OMXCodec(  254): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer(  254): finishAsyncPrepare_l
V/AwesomePlayer(  254): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache(  254): notify(0xb76fa418, 200, 973, 0)
I/SecureStorage(  377): [INFO]: SPID(0x00000003)Credentials: uid 10016, gid 10016, pid 4492
I/SecureStorage(  377): [INFO]: SPID(0x00000003)Received function mask & code: 0000010C
V/AudioCache(  254): ignored
I/SecureStorage( 4492): [INFO]: SPID(0x00000000)SS Daemon is running
V/AwesomePlayer(  254): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  254): notify(0xb76fa418, 5, 0, 0)
V/AudioCache(  254): ignored
V/AwesomePlayer(  254): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  254): notify(0xb76fa418, 1, 0, 0)
V/AudioCache(  254): prepared
V/AudioCache(  254): wait - success
V/MediaPlayerService(  254): start
V/StagefrightPlayer(  254): start
V/AwesomePlayer(  254): play
D/AndroidRuntime( 4484): 
D/AndroidRuntime( 4484): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
V/AwesomePlayer(  254): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer(  254): startAudioPlayer_l, sendErrorNotification (0)
D/AndroidRuntime( 4484): CheckJNI is OFF
I/OMXCodec(  254): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
D/AndroidRuntime( 4484): setted country_code = Poland
I/OMXCodec(  254): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
D/AndroidRuntime( 4484): setted countryiso_code = PL
I/OMXCodec(  254): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
D/AndroidRuntime( 4484): setted sales_code = XEO
D/AndroidRuntime( 4484): readGMSProperty: start
D/AndroidRuntime( 4484): readGMSProperty: already setted!!
D/AndroidRuntime( 4484): readGMSProperty: end
D/AndroidRuntime( 4484): addProductProperty: start
I/AudioPlayer(  254):  Audioplayer kKeyAudioPCMFormat:1, 2, 0
I/AudioPlayer(  254):  Audioplayer kKeyAudioPCMFormat read fail(2, 1)
V/AudioCache(  254): open(44100, 2, 0x0, 1, 4)
V/AwesomePlayer(  254): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache(  254): notify(0xb76fa418, 6, 0, 0)
V/AudioCache(  254): ignored
V/AwesomePlayer(  254): addBatteryData
V/MediaPlayerService(  254): wait for playback complete
I/SecureStorage( 4492): [INFO]: SPID(0x00000000)Processing data
I/SecureStorage(  377): [INFO]: SPID(0x00000003)Credentials: uid 10016, gid 10016, pid 4492
I/SecureStorage(  377): [INFO]: SPID(0x00000003)Received function mask & code: 00000106
D/dalvikvm( 4484): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 4484): Added shared lib libjavacore.so 0x0
D/dalvikvm( 4484): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 4484): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 4484): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
I/OMXCodec(  254): [OMX.google.vorbis.decoder] End Of Stream
V/AwesomePlayer(  254): postAudioEOS delayUs (0)
V/AwesomePlayer(  254): onCheckAudioStatus
V/AwesomePlayer(  254): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  254): onStreamDone
V/AwesomePlayer(  254): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  254): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  254): notify(0xb76fa418, 2, 0, 0)
V/AudioCache(  254): playback complete - thread will wake up later
V/AwesomePlayer(  254): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  254): notify(0xb76fa418, 7, 0, 0)
V/AudioCache(  254): ignored
V/AwesomePlayer(  254): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer(  254): addBatteryData
V/AudioCache(  254): wait - success
V/StagefrightPlayer(  254): reset
V/AwesomePlayer(  254): reset_l()
V/AwesomePlayer(  254): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  254): notify(0xb76fa418, 8, 0, 0)
V/AudioCache(  254): ignored
V/AwesomePlayer(  254): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  254): mAudioTrackVector clear
I/OMXCodec(  254): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec(  254): [OMX.google.vorbis.decoder] stop() sendCommand(0x39, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec(  254): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
I/OMXCodec(  254): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/OMX     (  254): instance freeNode
I/AudioPlayer(  254): reset out
V/AwesomePlayer(  254): reset_l() mAudioPlayer successfully deleted
I/SecMediaClock(  254): SecMediaClock destructor
V/AwesomePlayer(  254): mSecMediaClock clear
V/StagefrightPlayer(  254): ~StagefrightPlayer
V/StagefrightPlayer(  254): reset
V/AwesomePlayer(  254): reset_l()
V/AwesomePlayer(  254): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  254): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  254): mAudioTrackVector clear
V/AwesomePlayer(  254): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  254): mSecMediaClock clear
V/AwesomePlayer(  254): destructor
V/AwesomePlayer(  254): reset_l()
V/AwesomePlayer(  254): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  254): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  254): mAudioTrackVector clear
V/AwesomePlayer(  254): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  254): mSecMediaClock clear
V/MediaPlayer( 4466): decode(65, 33862452, 7405)
V/MediaPlayerService(  254): decode(35, 33862452, 7405)
V/MediaPlayerService(  254): player type = 3
V/AwesomePlayer(  254): setDefault
V/AwesomePlayer(  254): constructor
V/AlarmManager(  780): waitForAlarm result :4
V/AwesomePlayer(  254): setDefault
V/AwesomePlayer(  254): reset_l()
V/AwesomePlayer(  254): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  254): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  254): mAudioTrackVector clear
V/AwesomePlayer(  254): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  254): mSecMediaClock clear
V/StagefrightPlayer(  254): StagefrightPlayer
V/AwesomePlayer(  254): setListener
V/StagefrightPlayer(  254): initCheck
V/AwesomePlayer(  254): setAudioSink
V/StagefrightPlayer(  254): setDataSource(35, 33862452, 7405)
V/AwesomePlayer(  254): reset_l()
V/AwesomePlayer(  254): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  254): notify(0xb76f6b28, 8, 0, 0)
V/AudioCache(  254): ignored
V/AwesomePlayer(  254): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  254): mAudioTrackVector clear
V/AwesomePlayer(  254): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  254): mSecMediaClock clear
V/AwesomePlayer(  254): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer(  254): mBitrate = -1 bits/sec
V/AwesomePlayer(  254): current audio track index (0) is added to vector
V/AwesomePlayer(  254): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer(  254): AwesomePlayer::setDataSource_l():: This is not a DRM content
V/MediaPlayerService(  254): prepare
V/AwesomePlayer(  254): prepareAsync
V/MediaPlayerService(  254): wait for prepare
V/AwesomePlayer(  254): onPrepareAsyncEvent
I/SecMediaClock(  254): SecMediaClock constructor
I/SecMediaClock(  254): reset
V/AwesomePlayer(  254): initAudioDecoder
V/AwesomePlayer(  254): checkOffloadExceptions is true
I/OMXCodec(  254): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
I/OMX     (  254): mDispatchers.add
I/OMXCodec(  254): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec(  254): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec(  254): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec(  254): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/OMXCodec(  254): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer(  254): finishAsyncPrepare_l
V/AwesomePlayer(  254): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache(  254): notify(0xb76f6b28, 200, 973, 0)
V/AudioCache(  254): ignored
V/AwesomePlayer(  254): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  254): notify(0xb76f6b28, 5, 0, 0)
V/AudioCache(  254): ignored
V/AwesomePlayer(  254): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  254): notify(0xb76f6b28, 1, 0, 0)
V/AudioCache(  254): prepared
V/AudioCache(  254): wait - success
V/MediaPlayerService(  254): start
V/StagefrightPlayer(  254): start
V/AwesomePlayer(  254): play
V/AwesomePlayer(  254): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer(  254): startAudioPlayer_l, sendErrorNotification (0)
V/AlarmManager(  780): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
I/OMXCodec(  254): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec(  254): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec(  254): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/AudioPlayer(  254):  Audioplayer kKeyAudioPCMFormat:1, 2, 0
I/AudioPlayer(  254):  Audioplayer kKeyAudioPCMFormat read fail(2, 1)
V/AudioCache(  254): open(44100, 2, 0x0, 1, 4)
V/AwesomePlayer(  254): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache(  254): notify(0xb76f6b28, 6, 0, 0)
V/AudioCache(  254): ignored
V/AwesomePlayer(  254): addBatteryData
V/MediaPlayerService(  254): wait for playback complete
I/OMXCodec(  254): [OMX.google.vorbis.decoder] End Of Stream
V/AwesomePlayer(  254): postAudioEOS delayUs (0)
V/AwesomePlayer(  254): onCheckAudioStatus
V/AwesomePlayer(  254): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  254): onStreamDone
V/AwesomePlayer(  254): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  254): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  254): notify(0xb76f6b28, 2, 0, 0)
V/AudioCache(  254): playback complete - thread will wake up later
V/AwesomePlayer(  254): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  254): notify(0xb76f6b28, 7, 0, 0)
V/AudioCache(  254): ignored
V/AwesomePlayer(  254): cancelPlayerEvents (keepNotifications=1)
V/AudioCache(  254): wait - success
V/StagefrightPlayer(  254): reset
V/AwesomePlayer(  254): addBatteryData
V/AwesomePlayer(  254): reset_l()
V/AwesomePlayer(  254): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  254): notify(0xb76f6b28, 8, 0, 0)
V/AudioCache(  254): ignored
V/AwesomePlayer(  254): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  254): mAudioTrackVector clear
I/OMXCodec(  254): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec(  254): [OMX.google.vorbis.decoder] stop() sendCommand(0x3a, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec(  254): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
I/OMXCodec(  254): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/OMX     (  254): instance freeNode
I/AudioPlayer(  254): reset out
V/AwesomePlayer(  254): reset_l() mAudioPlayer successfully deleted
I/SecMediaClock(  254): SecMediaClock destructor
V/AwesomePlayer(  254): mSecMediaClock clear
V/StagefrightPlayer(  254): ~StagefrightPlayer
V/StagefrightPlayer(  254): reset
V/AwesomePlayer(  254): reset_l()
V/AwesomePlayer(  254): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  254): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  254): mAudioTrackVector clear
V/AwesomePlayer(  254): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  254): mSecMediaClock clear
V/AwesomePlayer(  254): destructor
V/AwesomePlayer(  254): reset_l()
V/AwesomePlayer(  254): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  254): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  254): mAudioTrackVector clear
V/AwesomePlayer(  254): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  254): mSecMediaClock clear
V/MediaPlayer( 4466): decode(66, 37547940, 5555)
V/MediaPlayerService(  254): decode(35, 37547940, 5555)
V/MediaPlayerService(  254): player type = 3
V/AwesomePlayer(  254): setDefault
V/AwesomePlayer(  254): constructor
V/AwesomePlayer(  254): setDefault
V/AwesomePlayer(  254): reset_l()
V/AwesomePlayer(  254): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  254): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  254): mAudioTrackVector clear
V/AwesomePlayer(  254): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  254): mSecMediaClock clear
V/StagefrightPlayer(  254): StagefrightPlayer
V/AwesomePlayer(  254): setListener
V/StagefrightPlayer(  254): initCheck
V/AwesomePlayer(  254): setAudioSink
V/StagefrightPlayer(  254): setDataSource(35, 37547940, 5555)
V/AwesomePlayer(  254): reset_l()
V/AwesomePlayer(  254): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  254): notify(0xb76f8c90, 8, 0, 0)
V/AudioCache(  254): ignored
V/AwesomePlayer(  254): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  254): mAudioTrackVector clear
V/AwesomePlayer(  254): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  254): mSecMediaClock clear
V/AwesomePlayer(  254): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer(  254): mBitrate = -1 bits/sec
V/AwesomePlayer(  254): current audio track index (0) is added to vector
V/AwesomePlayer(  254): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer(  254): AwesomePlayer::setDataSource_l():: This is not a DRM content
V/MediaPlayerService(  254): prepare
V/AwesomePlayer(  254): prepareAsync
V/MediaPlayerService(  254): wait for prepare
V/AwesomePlayer(  254): onPrepareAsyncEvent
I/SecMediaClock(  254): SecMediaClock constructor
I/SecMediaClock(  254): reset
V/AwesomePlayer(  254): initAudioDecoder
V/AwesomePlayer(  254): checkOffloadExceptions is true
I/OMXCodec(  254): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
I/OMX     (  254): mDispatchers.add
I/OMXCodec(  254): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec(  254): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec(  254): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec(  254): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/OMXCodec(  254): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer(  254): finishAsyncPrepare_l
V/AwesomePlayer(  254): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache(  254): notify(0xb76f8c90, 200, 973, 0)
V/AudioCache(  254): ignored
V/AwesomePlayer(  254): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  254): notify(0xb76f8c90, 5, 0, 0)
V/AudioCache(  254): ignored
V/AwesomePlayer(  254): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  254): notify(0xb76f8c90, 1, 0, 0)
V/AudioCache(  254): prepared
V/AudioCache(  254): wait - success
V/MediaPlayerService(  254): start
V/StagefrightPlayer(  254): start
V/AwesomePlayer(  254): play
V/AwesomePlayer(  254): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer(  254): startAudioPlayer_l, sendErrorNotification (0)
I/OMXCodec(  254): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec(  254): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec(  254): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/AudioPlayer(  254):  Audioplayer kKeyAudioPCMFormat:1, 2, 0
I/AudioPlayer(  254):  Audioplayer kKeyAudioPCMFormat read fail(2, 1)
V/AudioCache(  254): open(44100, 2, 0x0, 1, 4)
V/AwesomePlayer(  254): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache(  254): notify(0xb76f8c90, 6, 0, 0)
V/AudioCache(  254): ignored
V/AwesomePlayer(  254): addBatteryData
V/MediaPlayerService(  254): wait for playback complete
I/OMXCodec(  254): [OMX.google.vorbis.decoder] End Of Stream
V/AwesomePlayer(  254): postAudioEOS delayUs (0)
V/AwesomePlayer(  254): onCheckAudioStatus
V/AwesomePlayer(  254): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  254): onStreamDone
V/AwesomePlayer(  254): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  254): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  254): notify(0xb76f8c90, 2, 0, 0)
V/AudioCache(  254): playback complete - thread will wake up later
V/AwesomePlayer(  254): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  254): notify(0xb76f8c90, 7, 0, 0)
V/AudioCache(  254): ignored
V/AwesomePlayer(  254): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer(  254): addBatteryData
V/AudioCache(  254): wait - success
V/StagefrightPlayer(  254): reset
V/AwesomePlayer(  254): reset_l()
V/AwesomePlayer(  254): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  254): notify(0xb76f8c90, 8, 0, 0)
V/AudioCache(  254): ignored
V/AwesomePlayer(  254): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  254): mAudioTrackVector clear
I/OMXCodec(  254): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec(  254): [OMX.google.vorbis.decoder] stop() sendCommand(0x3b, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec(  254): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
I/OMXCodec(  254): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/OMX     (  254): instance freeNode
I/AudioPlayer(  254): reset out
V/AwesomePlayer(  254): reset_l() mAudioPlayer successfully deleted
I/SecMediaClock(  254): SecMediaClock destructor
V/AwesomePlayer(  254): mSecMediaClock clear
V/StagefrightPlayer(  254): ~StagefrightPlayer
V/StagefrightPlayer(  254): reset
V/AwesomePlayer(  254): reset_l()
V/AwesomePlayer(  254): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  254): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  254): mAudioTrackVector clear
V/AwesomePlayer(  254): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  254): mSecMediaClock clear
V/AwesomePlayer(  254): destructor
V/AwesomePlayer(  254): reset_l()
V/AwesomePlayer(  254): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  254): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  254): mAudioTrackVector clear
V/AwesomePlayer(  254): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  254): mSecMediaClock clear
V/MediaPlayer( 4466): decode(67, 30367732, 5085)
V/MediaPlayerService(  254): decode(35, 30367732, 5085)
V/MediaPlayerService(  254): player type = 3
V/AwesomePlayer(  254): setDefault
V/AwesomePlayer(  254): constructor
V/AwesomePlayer(  254): setDefault
V/AwesomePlayer(  254): reset_l()
V/AwesomePlayer(  254): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  254): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  254): mAudioTrackVector clear
V/AwesomePlayer(  254): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  254): mSecMediaClock clear
V/StagefrightPlayer(  254): StagefrightPlayer
V/AwesomePlayer(  254): setListener
V/StagefrightPlayer(  254): initCheck
V/AwesomePlayer(  254): setAudioSink
V/StagefrightPlayer(  254): setDataSource(35, 30367732, 5085)
V/AwesomePlayer(  254): reset_l()
V/AwesomePlayer(  254): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  254): notify(0xb7701d28, 8, 0, 0)
V/AudioCache(  254): ignored
V/AwesomePlayer(  254): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  254): mAudioTrackVector clear
V/AwesomePlayer(  254): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  254): mSecMediaClock clear
D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
D/BatteryService(  780): level:100, scale:100, status:5, health:2, present:true, voltage: 4367, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:8, charge type:1, power sharing:false
D/BatteryService(  780): Sending ACTION_BATTERY_CHANGED.
D/BatteryService(  780): stay LED for fully charged
D/UiModeManager(  780): mCoverManager.getCoverState() : true
V/AwesomePlayer(  254): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer(  254): mBitrate = -1 bits/sec
V/AwesomePlayer(  254): current audio track index (0) is added to vector
V/AwesomePlayer(  254): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer(  254): AwesomePlayer::setDataSource_l():: This is not a DRM content
V/MediaPlayerService(  254): prepare
V/AwesomePlayer(  254): prepareAsync
V/MediaPlayerService(  254): wait for prepare
V/AwesomePlayer(  254): onPrepareAsyncEvent
I/SecMediaClock(  254): SecMediaClock constructor
I/SecMediaClock(  254): reset
V/AwesomePlayer(  254): initAudioDecoder
V/AwesomePlayer(  254): checkOffloadExceptions is true
I/OMXCodec(  254): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
I/OMX     (  254): mDispatchers.add
I/OMXCodec(  254): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec(  254): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec(  254): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec(  254): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/OMXCodec(  254): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer(  254): finishAsyncPrepare_l
V/AwesomePlayer(  254): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache(  254): notify(0xb7701d28, 200, 973, 0)
V/AudioCache(  254): ignored
V/AwesomePlayer(  254): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  254): notify(0xb7701d28, 5, 0, 0)
V/AudioCache(  254): ignored
V/AwesomePlayer(  254): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  254): notify(0xb7701d28, 1, 0, 0)
V/AudioCache(  254): prepared
V/AudioCache(  254): wait - success
V/MediaPlayerService(  254): start
V/StagefrightPlayer(  254): start
V/AwesomePlayer(  254): play
V/AwesomePlayer(  254): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer(  254): startAudioPlayer_l, sendErrorNotification (0)
D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
I/OMXCodec(  254): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec(  254): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec(  254): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/AudioPlayer(  254):  Audioplayer kKeyAudioPCMFormat:1, 2, 0
I/AudioPlayer(  254):  Audioplayer kKeyAudioPCMFormat read fail(2, 1)
V/AudioCache(  254): open(44100, 2, 0x0, 1, 4)
V/AwesomePlayer(  254): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache(  254): notify(0xb7701d28, 6, 0, 0)
V/AudioCache(  254): ignored
V/AwesomePlayer(  254): addBatteryData
V/MediaPlayerService(  254): wait for playback complete
I/AudioPlayer(  254): First fillBuffer call!!
I/OMXCodec(  254): [OMX.google.vorbis.decoder] End Of Stream
V/AwesomePlayer(  254): postAudioEOS delayUs (0)
V/AwesomePlayer(  254): onCheckAudioStatus
V/AwesomePlayer(  254): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  254): onStreamDone
V/AwesomePlayer(  254): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  254): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  254): notify(0xb7701d28, 2, 0, 0)
V/AudioCache(  254): playback complete - thread will wake up later
V/AwesomePlayer(  254): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  254): notify(0xb7701d28, 7, 0, 0)
V/AudioCache(  254): ignored
V/AwesomePlayer(  254): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer(  254): addBatteryData
V/AudioCache(  254): wait - success
V/StagefrightPlayer(  254): reset
V/AwesomePlayer(  254): reset_l()
V/AwesomePlayer(  254): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  254): notify(0xb7701d28, 8, 0, 0)
V/AudioCache(  254): ignored
V/AwesomePlayer(  254): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  254): mAudioTrackVector clear
I/OMXCodec(  254): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec(  254): [OMX.google.vorbis.decoder] stop() sendCommand(0x3c, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec(  254): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
I/OMXCodec(  254): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/OMX     (  254): instance freeNode
I/AudioPlayer(  254): reset out
V/AwesomePlayer(  254): reset_l() mAudioPlayer successfully deleted
I/SecMediaClock(  254): SecMediaClock destructor
V/AwesomePlayer(  254): mSecMediaClock clear
V/StagefrightPlayer(  254): ~StagefrightPlayer
V/StagefrightPlayer(  254): reset
V/AwesomePlayer(  254): reset_l()
V/AwesomePlayer(  254): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  254): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  254): mAudioTrackVector clear
V/AwesomePlayer(  254): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  254): mSecMediaClock clear
V/AwesomePlayer(  254): destructor
V/AwesomePlayer(  254): reset_l()
V/AwesomePlayer(  254): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  254): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  254): mAudioTrackVector clear
V/AwesomePlayer(  254): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  254): mSecMediaClock clear
D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/MediaPlayer( 4466): decode(68, 30372876, 21552)
V/MediaPlayerService(  254): decode(35, 30372876, 21552)
V/MediaPlayerService(  254): player type = 3
V/AwesomePlayer(  254): setDefault
V/AwesomePlayer(  254): constructor
V/AwesomePlayer(  254): setDefault
V/AwesomePlayer(  254): reset_l()
V/AwesomePlayer(  254): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  254): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  254): mAudioTrackVector clear
V/AwesomePlayer(  254): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  254): mSecMediaClock clear
V/StagefrightPlayer(  254): StagefrightPlayer
V/AwesomePlayer(  254): setListener
V/StagefrightPlayer(  254): initCheck
V/AwesomePlayer(  254): setAudioSink
V/StagefrightPlayer(  254): setDataSource(35, 30372876, 21552)
V/AwesomePlayer(  254): reset_l()
V/AwesomePlayer(  254): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  254): notify(0xb76fc178, 8, 0, 0)
V/AudioCache(  254): ignored
V/AwesomePlayer(  254): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  254): mAudioTrackVector clear
V/AwesomePlayer(  254): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  254): mSecMediaClock clear
V/AwesomePlayer(  254): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer(  254): mBitrate = -1 bits/sec
V/AwesomePlayer(  254): current audio track index (0) is added to vector
V/AwesomePlayer(  254): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer(  254): AwesomePlayer::setDataSource_l():: This is not a DRM content
V/MediaPlayerService(  254): prepare
V/AwesomePlayer(  254): prepareAsync
V/MediaPlayerService(  254): wait for prepare
V/AwesomePlayer(  254): onPrepareAsyncEvent
I/SecMediaClock(  254): SecMediaClock constructor
I/SecMediaClock(  254): reset
V/AwesomePlayer(  254): initAudioDecoder
V/AwesomePlayer(  254): checkOffloadExceptions is true
I/OMXCodec(  254): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
I/OMX     (  254): mDispatchers.add
I/OMXCodec(  254): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec(  254): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec(  254): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec(  254): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/OMXCodec(  254): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer(  254): finishAsyncPrepare_l
V/AwesomePlayer(  254): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache(  254): notify(0xb76fc178, 200, 973, 0)
V/AudioCache(  254): ignored
V/AwesomePlayer(  254): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  254): notify(0xb76fc178, 5, 0, 0)
V/AudioCache(  254): ignored
V/AwesomePlayer(  254): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  254): notify(0xb76fc178, 1, 0, 0)
V/AudioCache(  254): prepared
V/AudioCache(  254): wait - success
V/MediaPlayerService(  254): start
V/StagefrightPlayer(  254): start
V/AwesomePlayer(  254): play
V/AwesomePlayer(  254): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer(  254): startAudioPlayer_l, sendErrorNotification (0)
I/OMXCodec(  254): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec(  254): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec(  254): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/AudioPlayer(  254):  Audioplayer kKeyAudioPCMFormat:1, 2, 0
I/AudioPlayer(  254):  Audioplayer kKeyAudioPCMFormat read fail(2, 1)
V/AudioCache(  254): open(44100, 2, 0x0, 1, 4)
V/AwesomePlayer(  254): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache(  254): notify(0xb76fc178, 6, 0, 0)
V/AudioCache(  254): ignored
V/AwesomePlayer(  254): addBatteryData
V/MediaPlayerService(  254): wait for playback complete
D/SSRMv2:SIOP(  780): SIOP:: AP = 310, Delta = 0
E/memtrack( 4484): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 4484): failed to load memtrack module: -2
I/OMXCodec(  254): [OMX.google.vorbis.decoder] End Of Stream
V/AwesomePlayer(  254): postAudioEOS delayUs (0)
V/AwesomePlayer(  254): onCheckAudioStatus
V/AwesomePlayer(  254): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  254): onStreamDone
V/AwesomePlayer(  254): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  254): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  254): notify(0xb76fc178, 2, 0, 0)
V/AudioCache(  254): playback complete - thread will wake up later
V/AwesomePlayer(  254): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  254): notify(0xb76fc178, 7, 0, 0)
V/AudioCache(  254): ignored
V/AwesomePlayer(  254): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer(  254): addBatteryData
V/AudioCache(  254): wait - success
V/StagefrightPlayer(  254): reset
V/AwesomePlayer(  254): reset_l()
V/AwesomePlayer(  254): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  254): notify(0xb76fc178, 8, 0, 0)
V/AudioCache(  254): ignored
V/AwesomePlayer(  254): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  254): mAudioTrackVector clear
I/OMXCodec(  254): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec(  254): [OMX.google.vorbis.decoder] stop() sendCommand(0x3d, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec(  254): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
I/OMXCodec(  254): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/OMX     (  254): instance freeNode
D/dalvikvm( 4484): Note: class Landroid/app/ActivityManagerNative; has 192 unimplemented (abstract) methods
I/AudioPlayer(  254): reset out
V/AwesomePlayer(  254): reset_l() mAudioPlayer successfully deleted
I/SecMediaClock(  254): SecMediaClock destructor
V/AwesomePlayer(  254): mSecMediaClock clear
V/StagefrightPlayer(  254): ~StagefrightPlayer
V/StagefrightPlayer(  254): reset
V/AwesomePlayer(  254): reset_l()
V/AwesomePlayer(  254): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  254): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  254): mAudioTrackVector clear
V/AwesomePlayer(  254): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  254): mSecMediaClock clear
V/AwesomePlayer(  254): destructor
V/AwesomePlayer(  254): reset_l()
V/AwesomePlayer(  254): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  254): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  254): mAudioTrackVector clear
V/AwesomePlayer(  254): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  254): mSecMediaClock clear
V/MediaPlayer( 4466): decode(69, 37543652, 4230)
V/MediaPlayerService(  254): decode(36, 37543652, 4230)
V/MediaPlayerService(  254): player type = 3
V/AwesomePlayer(  254): setDefault
V/AwesomePlayer(  254): constructor
V/AwesomePlayer(  254): setDefault
V/AwesomePlayer(  254): reset_l()
V/AwesomePlayer(  254): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  254): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  254): mAudioTrackVector clear
V/AwesomePlayer(  254): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  254): mSecMediaClock clear
V/StagefrightPlayer(  254): StagefrightPlayer
V/AwesomePlayer(  254): setListener
V/StagefrightPlayer(  254): initCheck
V/AwesomePlayer(  254): setAudioSink
V/StagefrightPlayer(  254): setDataSource(36, 37543652, 4230)
V/AwesomePlayer(  254): reset_l()
V/AwesomePlayer(  254): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  254): notify(0xb76f45d0, 8, 0, 0)
V/AudioCache(  254): ignored
V/AwesomePlayer(  254): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  254): mAudioTrackVector clear
V/AwesomePlayer(  254): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  254): mSecMediaClock clear
V/AwesomePlayer(  254): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer(  254): mBitrate = -1 bits/sec
V/AwesomePlayer(  254): current audio track index (0) is added to vector
V/AwesomePlayer(  254): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer(  254): AwesomePlayer::setDataSource_l():: This is not a DRM content
V/MediaPlayerService(  254): prepare
V/AwesomePlayer(  254): prepareAsync
V/MediaPlayerService(  254): wait for prepare
V/AwesomePlayer(  254): onPrepareAsyncEvent
I/SecMediaClock(  254): SecMediaClock constructor
I/SecMediaClock(  254): reset
V/AwesomePlayer(  254): initAudioDecoder
V/AwesomePlayer(  254): checkOffloadExceptions is true
I/OMXCodec(  254): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
I/OMX     (  254): mDispatchers.add
I/OMXCodec(  254): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec(  254): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec(  254): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec(  254): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/OMXCodec(  254): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer(  254): finishAsyncPrepare_l
V/AwesomePlayer(  254): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache(  254): notify(0xb76f45d0, 200, 973, 0)
V/AudioCache(  254): ignored
V/AwesomePlayer(  254): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  254): notify(0xb76f45d0, 5, 0, 0)
V/AudioCache(  254): ignored
V/AwesomePlayer(  254): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  254): notify(0xb76f45d0, 1, 0, 0)
V/AudioCache(  254): prepared
V/AudioCache(  254): wait - success
V/MediaPlayerService(  254): start
V/StagefrightPlayer(  254): start
V/AwesomePlayer(  254): play
V/AwesomePlayer(  254): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer(  254): startAudioPlayer_l, sendErrorNotification (0)
I/OMXCodec(  254): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec(  254): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec(  254): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/OMXCodec(  254): [OMX.google.vorbis.decoder] End Of Stream
I/AudioPlayer(  254):  Audioplayer kKeyAudioPCMFormat:1, 1, 0
I/AudioPlayer(  254):  Audioplayer kKeyAudioPCMFormat read fail(1, 1)
V/AudioCache(  254): open(44100, 1, 0x0, 1, 4)
V/AwesomePlayer(  254): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache(  254): notify(0xb76f45d0, 6, 0, 0)
V/AudioCache(  254): ignored
V/AwesomePlayer(  254): addBatteryData
V/MediaPlayerService(  254): wait for playback complete
V/AwesomePlayer(  254): postAudioEOS delayUs (0)
V/AwesomePlayer(  254): onCheckAudioStatus
V/AwesomePlayer(  254): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  254): onStreamDone
V/AwesomePlayer(  254): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  254): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  254): notify(0xb76f45d0, 2, 0, 0)
V/AudioCache(  254): playback complete - thread will wake up later
V/AwesomePlayer(  254): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  254): notify(0xb76f45d0, 7, 0, 0)
V/AudioCache(  254): ignored
V/AwesomePlayer(  254): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer(  254): addBatteryData
V/AudioCache(  254): wait - success
V/StagefrightPlayer(  254): reset
V/AwesomePlayer(  254): reset_l()
V/AwesomePlayer(  254): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  254): notify(0xb76f45d0, 8, 0, 0)
V/AudioCache(  254): ignored
V/AwesomePlayer(  254): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  254): mAudioTrackVector clear
I/OMXCodec(  254): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec(  254): [OMX.google.vorbis.decoder] stop() sendCommand(0x3e, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec(  254): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
I/OMXCodec(  254): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/OMX     (  254): instance freeNode
I/AudioPlayer(  254): reset out
V/AwesomePlayer(  254): reset_l() mAudioPlayer successfully deleted
I/SecMediaClock(  254): SecMediaClock destructor
V/AwesomePlayer(  254): mSecMediaClock clear
V/StagefrightPlayer(  254): ~StagefrightPlayer
V/StagefrightPlayer(  254): reset
V/AwesomePlayer(  254): reset_l()
V/AwesomePlayer(  254): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  254): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  254): mAudioTrackVector clear
V/AwesomePlayer(  254): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  254): mSecMediaClock clear
V/AwesomePlayer(  254): destructor
V/AwesomePlayer(  254): reset_l()
V/AwesomePlayer(  254): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  254): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  254): mAudioTrackVector clear
V/AwesomePlayer(  254): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  254): mSecMediaClock clear
V/MediaPlayer( 4466): decode(70, 30337076, 9400)
V/MediaPlayerService(  254): decode(35, 30337076, 9400)
V/MediaPlayerService(  254): player type = 3
V/AwesomePlayer(  254): setDefault
V/AwesomePlayer(  254): constructor
V/AwesomePlayer(  254): setDefault
V/AwesomePlayer(  254): reset_l()
V/AwesomePlayer(  254): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  254): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  254): mAudioTrackVector clear
V/AwesomePlayer(  254): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  254): mSecMediaClock clear
V/StagefrightPlayer(  254): StagefrightPlayer
V/AwesomePlayer(  254): setListener
V/StagefrightPlayer(  254): initCheck
V/AwesomePlayer(  254): setAudioSink
V/StagefrightPlayer(  254): setDataSource(35, 30337076, 9400)
V/AwesomePlayer(  254): reset_l()
V/AwesomePlayer(  254): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  254): notify(0xb7706158, 8, 0, 0)
V/AudioCache(  254): ignored
V/AwesomePlayer(  254): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  254): mAudioTrackVector clear
V/AwesomePlayer(  254): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  254): mSecMediaClock clear
V/AwesomePlayer(  254): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer(  254): mBitrate = -1 bits/sec
V/AwesomePlayer(  254): current audio track index (0) is added to vector
V/AwesomePlayer(  254): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer(  254): AwesomePlayer::setDataSource_l():: This is not a DRM content
V/MediaPlayerService(  254): prepare
V/AwesomePlayer(  254): prepareAsync
V/MediaPlayerService(  254): wait for prepare
V/AwesomePlayer(  254): onPrepareAsyncEvent
I/SecMediaClock(  254): SecMediaClock constructor
I/SecMediaClock(  254): reset
V/AwesomePlayer(  254): initAudioDecoder
V/AwesomePlayer(  254): checkOffloadExceptions is true
I/OMXCodec(  254): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
I/OMX     (  254): mDispatchers.add
I/OMXCodec(  254): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec(  254): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec(  254): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec(  254): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/OMXCodec(  254): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer(  254): finishAsyncPrepare_l
V/AwesomePlayer(  254): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache(  254): notify(0xb7706158, 200, 973, 0)
V/AudioCache(  254): ignored
V/AwesomePlayer(  254): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  254): notify(0xb7706158, 5, 0, 0)
V/AudioCache(  254): ignored
V/AwesomePlayer(  254): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  254): notify(0xb7706158, 1, 0, 0)
V/AudioCache(  254): prepared
V/AudioCache(  254): wait - success
V/MediaPlayerService(  254): start
V/StagefrightPlayer(  254): start
V/AwesomePlayer(  254): play
V/AwesomePlayer(  254): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer(  254): startAudioPlayer_l, sendErrorNotification (0)
I/OMXCodec(  254): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec(  254): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec(  254): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/AudioPlayer(  254):  Audioplayer kKeyAudioPCMFormat:1, 1, 0
I/AudioPlayer(  254):  Audioplayer kKeyAudioPCMFormat read fail(1, 1)
V/AudioCache(  254): open(44100, 1, 0x0, 1, 4)
V/AwesomePlayer(  254): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache(  254): notify(0xb7706158, 6, 0, 0)
V/AudioCache(  254): ignored
V/AwesomePlayer(  254): addBatteryData
V/MediaPlayerService(  254): wait for playback complete
D/AndroidRuntime( 4484): Calling main entry com.android.commands.am.Am
I/AudioPlayer(  254): First fillBuffer call!!
I/SELinux ( 4561): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 4561):  
I/OMXCodec(  254): [OMX.google.vorbis.decoder] End Of Stream
V/AwesomePlayer(  254): postAudioEOS delayUs (0)
V/AwesomePlayer(  254): onCheckAudioStatus
V/AwesomePlayer(  254): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  254): onStreamDone
V/AwesomePlayer(  254): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  254): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  254): notify(0xb7706158, 2, 0, 0)
V/AudioCache(  254): playback complete - thread will wake up later
V/AwesomePlayer(  254): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  254): notify(0xb7706158, 7, 0, 0)
V/AudioCache(  254): ignored
V/AwesomePlayer(  254): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer(  254): addBatteryData
V/AudioCache(  254): wait - success
V/StagefrightPlayer(  254): reset
V/AwesomePlayer(  254): reset_l()
V/AwesomePlayer(  254): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  254): notify(0xb7706158, 8, 0, 0)
V/AudioCache(  254): ignored
V/AwesomePlayer(  254): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  254): mAudioTrackVector clear
I/OMXCodec(  254): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec(  254): [OMX.google.vorbis.decoder] stop() sendCommand(0x3f, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec(  254): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
I/OMXCodec(  254): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/OMX     (  254): instance freeNode
I/AudioPlayer(  254): reset out
V/AwesomePlayer(  254): reset_l() mAudioPlayer successfully deleted
I/SecMediaClock(  254): SecMediaClock destructor
V/AwesomePlayer(  254): mSecMediaClock clear
V/StagefrightPlayer(  254): ~StagefrightPlayer
V/StagefrightPlayer(  254): reset
V/AwesomePlayer(  254): reset_l()
V/AwesomePlayer(  254): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  254): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  254): mAudioTrackVector clear
V/AwesomePlayer(  254): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  254): mSecMediaClock clear
V/AwesomePlayer(  254): destructor
V/AwesomePlayer(  254): reset_l()
V/AwesomePlayer(  254): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  254): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  254): mAudioTrackVector clear
V/AwesomePlayer(  254): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  254): mSecMediaClock clear
V/MediaPlayer( 4466): decode(71, 33925464, 44276)
V/MediaPlayerService(  254): decode(35, 33925464, 44276)
V/MediaPlayerService(  254): player type = 3
V/AwesomePlayer(  254): setDefault
V/AwesomePlayer(  254): constructor
V/AwesomePlayer(  254): setDefault
V/AwesomePlayer(  254): reset_l()
V/AwesomePlayer(  254): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  254): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  254): mAudioTrackVector clear
V/AwesomePlayer(  254): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  254): mSecMediaClo,ck clear
V/StagefrightPlayer(  254): StagefrightPlayer
V/AwesomePlayer(  254): setListener
V/StagefrightPlayer(  254): initCheck
V/AwesomePlayer(  254): setAudioSink
V/StagefrightPlayer(  254): setDataSource(35, 33925464, 44276)
V/AwesomePlayer(  254): reset_l()
V/AwesomePlayer(  254): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  254): notify(0xb7704468, 8, 0, 0)
V/AudioCache(  254): ignored
V/AwesomePlayer(  254): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  254): mAudioTrackVector clear
V/AwesomePlayer(  254): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  254): mSecMediaClock clear
E/SMD     (  240): DCD OFF
I/ActivityManager(  780): Killing 3111:com.sec.android.app.mt/1000 (adj 15): empty #43
V/AwesomePlayer(  254): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer(  254): mBitrate = -1 bits/sec
V/AwesomePlayer(  254): current audio track index (0) is added to vector
V/AwesomePlayer(  254): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer(  254): AwesomePlayer::setDataSource_l():: This is not a DRM content
V/MediaPlayerService(  254): prepare
V/AwesomePlayer(  254): prepareAsync
V/MediaPlayerService(  254): wait for prepare
V/AwesomePlayer(  254): onPrepareAsyncEvent
I/SecMediaClock(  254): SecMediaClock constructor
I/SecMediaClock(  254): reset
V/AwesomePlayer(  254): initAudioDecoder
V/AwesomePlayer(  254): checkOffloadExceptions is true
I/OMXCodec(  254): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
I/OMX     (  254): mDispatchers.add
I/OMXCodec(  254): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec(  254): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec(  254): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec(  254): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/OMXCodec(  254): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer(  254): finishAsyncPrepare_l
V/AwesomePlayer(  254): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache(  254): notify(0xb7704468, 200, 973, 0)
V/AudioCache(  254): ignored
V/AwesomePlayer(  254): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  254): notify(0xb7704468, 5, 0, 0)
V/AudioCache(  254): ignored
V/AwesomePlayer(  254): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  254): notify(0xb7704468, 1, 0, 0)
V/AudioCache(  254): prepared
V/AudioCache(  254): wait - success
V/MediaPlayerService(  254): start
V/StagefrightPlayer(  254): start
V/ApplicationPolicy(  780): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
V/AwesomePlayer(  254): play
V/AwesomePlayer(  254): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer(  254): startAudioPlayer_l, sendErrorNotification (0)
I/SELinux ( 4561): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 4561):  
I/SELinux ( 4561):  
I/SELinux ( 4561): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
I/OMXCodec(  254): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec(  254): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec(  254): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
E/SELinux ( 4561): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 4561): >>>>> Normal User
E/dalvikvm( 4561): >>>>> com.policydm [ userId:0 | appId:1000 ]
I/AudioPlayer(  254):  Audioplayer kKeyAudioPCMFormat:1, 2, 0
I/AudioPlayer(  254):  Audioplayer kKeyAudioPCMFormat read fail(2, 1)
V/AudioCache(  254): open(44100, 2, 0x0, 1, 4)
V/AwesomePlayer(  254): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache(  254): notify(0xb7704468, 6, 0, 0)
V/AudioCache(  254): ignored
V/AwesomePlayer(  254): addBatteryData
E/SELinux ( 4561): [DEBUG] seapp_context_lookup: seinfoCategory = platform
V/MediaPlayerService(  254): wait for playback complete
D/CustomFrequencyManagerService(  780): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 780  pkgName : ACTIVITY_RESUME_BOOSTER@5
D/TimaKeyStoreProvider( 4561): in addTimaSignatureService
D/TimaKeyStoreProvider( 4561): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 4561): Added TimaKesytore provider
W/ActivityManager(  780): mDVFSHelper.acquire()
I/SELinux ( 4577): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 4577):  
D/LockPatternUtils( 1065): isPcwEnable = null
D/AndroidRuntime( 4484): Shutting down VM
D/dalvikvm(  251): GC_EXPLICIT freed 45K, 50% free 9507K/18792K, paused 2ms+2ms, total 29ms
I/OMXCodec(  254): [OMX.google.vorbis.decoder] End Of Stream
D/dalvikvm( 4484): GC_CONCURRENT freed 97K, 13% free 717K/816K, paused 0ms+0ms, total 3ms
D/dalvikvm(  251): GC_EXPLICIT freed <1K, 50% free 9507K/18792K, paused 1ms+3ms, total 18ms
V/AwesomePlayer(  254): postAudioEOS delayUs (0)
I/SELinux ( 4577): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 4577):  
I/SELinux ( 4577):  
I/SELinux ( 4577): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
V/AwesomePlayer(  254): onCheckAudioStatus
V/AwesomePlayer(  254): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  254): onStreamDone
V/AwesomePlayer(  254): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  254): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  254): notify(0xb7704468, 2, 0, 0)
V/AudioCache(  254): playback complete - thread will wake up later
V/AwesomePlayer(  254): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  254): notify(0xb7704468, 7, 0, 0)
V/AudioCache(  254): ignored
V/AwesomePlayer(  254): cancelPlayerEvents (keepNotifications=1)
E/SELinux ( 4577): [DEBUG] seapp_context_lookup: seinfoCategory = default
V/AwesomePlayer(  254): addBatteryData
E/dalvikvm( 4577): >>>>> Normal User
E/dalvikvm( 4577): >>>>> com.test.thalitest [ userId:0 | appId:10179 ]
V/AudioCache(  254): wait - success
V/StagefrightPlayer(  254): reset
V/AwesomePlayer(  254): reset_l()
V/AwesomePlayer(  254): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  254): notify(0xb7704468, 8, 0, 0)
V/AudioCache(  254): ignored
V/AwesomePlayer(  254): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  254): mAudioTrackVector clear
I/OMXCodec(  254): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec(  254): [OMX.google.vorbis.decoder] stop() sendCommand(0x40, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec(  254): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
E/SELinux ( 4577): [DEBUG] seapp_context_lookup: seinfoCategory = default
I/OMXCodec(  254): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/OMX     (  254): instance freeNode
I/AudioPlayer(  254): reset out
V/AwesomePlayer(  254): reset_l() mAudioPlayer successfully deleted
I/SecMediaClock(  254): SecMediaClock destructor
V/AwesomePlayer(  254): mSecMediaClock clear
V/StagefrightPlayer(  254): ~StagefrightPlayer
V/StagefrightPlayer(  254): reset
V/AwesomePlayer(  254): reset_l()
V/AwesomePlayer(  254): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  254): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  254): mAudioTrackVector clear
V/AwesomePlayer(  254): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  254): mSecMediaClock clear
V/AwesomePlayer(  254): destructor
V/AwesomePlayer(  254): reset_l()
V/AwesomePlayer(  254): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  254): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  254): mAudioTrackVector clear
V/AwesomePlayer(  254): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  254): mSecMediaClock clear
V/MediaPlayer( 4466): decode(72, 33885672, 29256)
V/MediaPlayerService(  254): decode(35, 33885672, 29256)
D/dalvikvm(  251): GC_EXPLICIT freed <1K, 50% free 9507K/18792K, paused 2ms+2ms, total 19ms
V/MediaPlayerService(  254): player type = 3
V/AwesomePlayer(  254): setDefault
V/AwesomePlayer(  254): constructor
V/AwesomePlayer(  254): setDefault
V/AwesomePlayer(  254): reset_l()
V/AwesomePlayer(  254): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  254): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  254): mAudioTrackVector clear
V/AwesomePlayer(  254): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  254): mSecMediaClock clear
V/StagefrightPlayer(  254): StagefrightPlayer
V/AwesomePlayer(  254): setListener
V/StagefrightPlayer(  254): initCheck
V/AwesomePlayer(  254): setAudioSink
V/StagefrightPlayer(  254): setDataSource(35, 33885672, 29256)
V/AwesomePlayer(  254): reset_l()
V/AwesomePlayer(  254): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  254): notify(0xb76f1c48, 8, 0, 0)
V/AudioCache(  254): ignored
V/AwesomePlayer(  254): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  254): mAudioTrackVector clear
V/AwesomePlayer(  254): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  254): mSecMediaClock clear
V/AwesomePlayer(  254): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer(  254): mBitrate = -1 bits/sec
V/AwesomePlayer(  254): current audio track index (0) is added to vector
V/AwesomePlayer(  254): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer(  254): AwesomePlayer::setDataSource_l():: This is not a DRM content
V/MediaPlayerService(  254): prepare
V/AwesomePlayer(  254): prepareAsync
V/MediaPlayerService(  254): wait for prepare
V/AwesomePlayer(  254): onPrepareAsyncEvent
I/SecMediaClock(  254): SecMediaClock constructor
I/SecMediaClock(  254): reset
V/AwesomePlayer(  254): initAudioDecoder
V/AwesomePlayer(  254): checkOffloadExceptions is true
I/OMXCodec(  254): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
I/OMX     (  254): mDispatchers.add
I/OMXCodec(  254): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec(  254): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec(  254): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec(  254): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
D/TimaKeyStoreProvider( 4577): in addTimaSignatureService
I/OMXCodec(  254): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer(  254): finishAsyncPrepare_l
V/AwesomePlayer(  254): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache(  254): notify(0xb76f1c48, 200, 973, 0)
V/AudioCache(  254): ignored
V/AwesomePlayer(  254): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  254): notify(0xb76f1c48, 5, 0, 0)
V/AudioCache(  254): ignored
V/AwesomePlayer(  254): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  254): notify(0xb76f1c48, 1, 0, 0)
V/AudioCache(  254): prepared
V/AudioCache(  254): wait - success
V/MediaPlayerService(  254): start
V/StagefrightPlayer(  254): start
V/AwesomePlayer(  254): play
V/AwesomePlayer(  254): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer(  254): startAudioPlayer_l, sendErrorNotification (0)
D/TimaKeyStoreProvider( 4577): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 4577): Added TimaKesytore provider
I/OMXCodec(  254): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec(  254): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec(  254): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/AudioPlayer(  254):  Audioplayer kKeyAudioPCMFormat:1, 2, 0
I/AudioPlayer(  254):  Audioplayer kKeyAudioPCMFormat read fail(2, 1)
V/AudioCache(  254): open(44100, 2, 0x0, 1, 4)
V/AwesomePlayer(  254): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache(  254): notify(0xb76f1c48, 6, 0, 0)
V/AudioCache(  254): ignored
V/AwesomePlayer(  254): addBatteryData
I/AudioPlayer(  254): First fillBuffer call!!
V/MediaPlayerService(  254): wait for playback complete
I/OMXCodec(  254): [OMX.google.vorbis.decoder] End Of Stream
V/AwesomePlayer(  254): postAudioEOS delayUs (0)
V/AwesomePlayer(  254): onCheckAudioStatus
V/AwesomePlayer(  254): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  254): onStreamDone
V/AwesomePlayer(  254): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  254): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  254): notify(0xb76f1c48, 2, 0, 0)
V/AudioCache(  254): playback complete - thread will wake up later
V/AwesomePlayer(  254): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  254): notify(0xb76f1c48, 7, 0, 0)
V/AudioCache(  254): ignored
V/AwesomePlayer(  254): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer(  254): addBatteryData
V/AudioCache(  254): wait - success
V/StagefrightPlayer(  254): reset
V/AwesomePlayer(  254): reset_l()
V/AwesomePlayer(  254): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  254): notify(0xb76f1c48, 8, 0, 0)
V/AudioCache(  254): ignored
V/AwesomePlayer(  254): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  254): mAudioTrackVector clear
I/OMXCodec(  254): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec(  254): [OMX.google.vorbis.decoder] stop() sendCommand(0x41, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec(  254): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
I/OMXCodec(  254): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/OMX     (  254): instance freeNode
D/LockPatternUtils( 1065): isPcwEnable = null
I/AudioPlayer(  254): reset out
V/AwesomePlayer(  254): reset_l() mAudioPlayer successfully deleted
I/SecMediaClock(  254): SecMediaClock destructor
V/AwesomePlayer(  254): mSecMediaClock clear
V/StagefrightPlayer(  254): ~StagefrightPlayer
V/StagefrightPlayer(  254): reset
V/AwesomePlayer(  254): reset_l()
V/AwesomePlayer(  254): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  254): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  254): mAudioTrackVector clear
V/AwesomePlayer(  254): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  254): mSecMediaClock clear
V/AwesomePlayer(  254): destructor
V/AwesomePlayer(  254): reset_l()
V/AwesomePlayer(  254): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  254): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  254): mAudioTrackVector clear
V/AwesomePlayer(  254): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  254): mSecMediaClock clear
V/MediaPlayer( 4466): decode(73, 37491572, 52024)
I/SurfaceFlinger(  249): id=13 Removed CatteryCove (8/12)
I/SurfaceFlinger(  249): id=13 Removed CatteryCove (-2/12)
V/MediaPlayerService(  254): decode(35, 37491572, 52024)
V/MediaPlayerService(  254): player type = 3
V/AwesomePlayer(  254): setDefault
V/AwesomePlayer(  254): constructor
V/AwesomePlayer(  254): setDefault
V/AwesomePlayer(  254): reset_l()
V/AwesomePlayer(  254): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  254): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  254): mAudioTrackVector clear
V/AwesomePlayer(  254): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  254): mSecMediaClock clear
V/StagefrightPlayer(  254): StagefrightPlayer
V/AwesomePlayer(  254): setListener
V/StagefrightPlayer(  254): initCheck
V/AwesomePlayer(  254): setAudioSink
V/StagefrightPlayer(  254): setDataSource(35, 37491572, 52024)
V/AwesomePlayer(  254): reset_l()
V/AwesomePlayer(  254): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  254): notify(0xb76f45d0, 8, 0, 0)
V/AudioCache(  254): ignored
V/AwesomePlayer(  254): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  254): mAudioTrackVector clear
V/AwesomePlayer(  254): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  254): mSecMediaClock clear
D/KeyguardUpdateMonitor( 1065): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1065): handleKeyguardVisibilityChanged(1)
V/AwesomePlayer(  254): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer(  254): mBitrate = -1 bits/sec
V/AwesomePlayer(  254): current audio track index (0) is added to vector
V/AwesomePlayer(  254): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer(  254): AwesomePlayer::setDataSource_l():: This is not a DRM content
V/MediaPlayerService(  254): prepare
V/AwesomePlayer(  254): prepareAsync
V/MediaPlayerService(  254): wait for prepare
V/AwesomePlayer(  254): onPrepareAsyncEvent
I/SecMediaClock(  254): SecMediaClock constructor
I/SecMediaClock(  254): reset
V/AwesomePlayer(  254): initAudioDecoder
V/AwesomePlayer(  254): checkOffloadExceptions is true
I/OMXCodec(  254): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
I/OMX     (  254): mDispatchers.add
I/OMXCodec(  254): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec(  254): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec(  254): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec(  254): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/OMXCodec(  254): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer(  254): finishAsyncPrepare_l
V/AwesomePlayer(  254): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache(  254): notify(0xb76f45d0, 200, 973, 0)
V/AudioCache(  254): ignored
V/AwesomePlayer(  254): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  254): notify(0xb76f45d0, 5, 0, 0)
V/AudioCache(  254): ignored
V/AwesomePlayer(  254): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  254): notify(0xb76f45d0, 1, 0, 0)
V/AudioCache(  254): prepared
V/AudioCache(  254): wait - success
V/MediaPlayerService(  254): start
V/StagefrightPlayer(  254): start
V/AwesomePlayer(  254): play
V/AwesomePlayer(  254): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer(  254): startAudioPlayer_l, sendErrorNotification (0)
I/OMXCodec(  254): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec(  254): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec(  254): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/SQLiteSecureOpenHelper( 2041): getWritableDatabase(pwd)
I/SQLiteSecureOpenHelper( 2041): getDatabaseLocked(b,b,pwd)...
I/AudioPlayer(  254):  Audioplayer kKeyAudioPCMFormat:1, 2, 0
I/AudioPlayer(  254):  Audioplayer kKeyAudioPCMFormat read fail(2, 1)
V/AudioCache(  254): open(48000, 2, 0x0, 1, 4)
V/AwesomePlayer(  254): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache(  254): notify(0xb76f45d0, 6, 0, 0)
V/AudioCache(  254): ignored
V/AwesomePlayer(  254): addBatteryData
V/MediaPlayerService(  254): wait for playback complete
D/SurfaceWidgetView( 1257): destroyHardwareResources():1126320720
I/OMXCodec(  254): [OMX.google.vorbis.decoder] End Of Stream
V/AwesomePlayer(  254): postAudioEOS delayUs (0)
V/AwesomePlayer(  254): onCheckAudioStatus
V/AwesomePlayer(  254): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  254): onStreamDone
V/AwesomePlayer(  254): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  254): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  254): notify(0xb76f45d0, 2, 0, 0)
V/AudioCache(  254): playback complete - thread will wake up later
V/AwesomePlayer(  254): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  254): notify(0xb76f45d0, 7, 0, 0)
V/AudioCache(  254): ignored
V/AwesomePlayer(  254): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer(  254): addBatteryData
V/AudioCache(  254): wait - success
V/StagefrightPlayer(  254): reset
V/AwesomePlayer(  254): reset_l()
V/AwesomePlayer(  254): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  254): notify(0xb76f45d0, 8, 0, 0)
V/AudioCache(  254): ignored
V/AwesomePlayer(  254): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  254): mAudioTrackVector clear
I/OMXCodec(  254): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec(  254): [OMX.google.vorbis.decoder] stop() sendCommand(0x42, OMX_CommandStateSet, OMX_StateIdle)
W/ActivityManager(  780): Permission Denial: getCurrentUser() from pid=4577, uid=10179 requires android.permission.INTERACT_ACROSS_USERS
I/OMXCodec(  254): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
I/OMXCodec(  254): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/OMX     (  254): instance freeNode
I/AudioPlayer(  254): reset out
V/AwesomePlayer(  254): reset_l() mAudioPlayer successfully deleted
I/SecMediaClock(  254): SecMediaClock destructor
V/AwesomePlayer(  254): mSecMediaClock clear
V/StagefrightPlayer(  254): ~StagefrightPlayer
V/StagefrightPlayer(  254): reset
V/AwesomePlayer(  254): reset_l()
V/AwesomePlayer(  254): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  254): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  254): mAudioTrackVector clear
V/AwesomePlayer(  254): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  254): mSecMediaClock clear
V/AwesomePlayer(  254): destructor
V/AwesomePlayer(  254): reset_l()
V/AwesomePlayer(  254): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  254): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  254): mAudioTrackVector clear
V/AwesomePlayer(  254): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  254): mSecMediaClock clear
V/MediaPlayer( 4466): decode(74, 33969800, 9226)
V/MediaPlayerService(  254): decode(35, 33969800, 9226)
V/MediaPlayerService(  254): player type = 3
V/AwesomePlayer(  254): setDefault
V/AwesomePlayer(  254): constructor
V/AwesomePlayer(  254): setDefault
V/AwesomePlayer(  254): reset_l()
V/AwesomePlayer(  254): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  254): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  254): mAudioTrackVector clear
V/AwesomePlayer(  254): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  254): mSecMediaClock clear
V/StagefrightPlayer(  254): StagefrightPlayer
V/AwesomePlayer(  254): setListener
V/StagefrightPlayer(  254): initCheck
V/AwesomePlayer(  254): setAudioSink
V/StagefrightPlayer(  254): setDataSource(35, 33969800, 9226)
V/AwesomePlayer(  254): reset_l()
V/AwesomePlayer(  254): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  254): notify(0xb76fc1c0, 8, 0, 0)
V/AudioCache(  254): ignored
V/AwesomePlayer(  254): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  254): mAudioTrackVector clear
V/AwesomePlayer(  254): reset_l() mAudioPlayer successfully deleted
,V/AwesomePlayer(  254): mSecMediaClock clear
,V/AwesomePlayer(  254): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer(  254): mBitrate = -1 bits/sec
,W/ActivityManager(  780): Permission Denial: getCurrentUser() from pid=4577, uid=10179 requires android.permission.INTERACT_ACROSS_USERS
V/AwesomePlayer(  254): current audio track index (0) is added to vector
V/AwesomePlayer(  254): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer(  254): AwesomePlayer::setDataSource_l():: This is not a DRM content
V/MediaPlayerService(  254): prepare
V/AwesomePlayer(  254): prepareAsync
V/MediaPlayerService(  254): wait for prepare
V/AwesomePlayer(  254): onPrepareAsyncEvent
I/SecMediaClock(  254): SecMediaClock constructor
I/SecMediaClock(  254): reset
V/AwesomePlayer(  254): initAudioDecoder
V/AwesomePlayer(  254): checkOffloadExceptions is true
I/OMXCodec(  254): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
I/OMX     (  254): mDispatchers.add
I/OMXCodec(  254): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec(  254): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec(  254): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec(  254): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/OMXCodec(  254): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer(  254): finishAsyncPrepare_l
V/AwesomePlayer(  254): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache(  254): notify(0xb76fc1c0, 200, 973, 0)
V/AudioCache(  254): ignored
V/AwesomePlayer(  254): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  254): notify(0xb76fc1c0, 5, 0, 0)
V/AudioCache(  254): ignored
V/AwesomePlayer(  254): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  254): notify(0xb76fc1c0, 1, 0, 0)
V/AudioCache(  254): prepared
V/AudioCache(  254): wait - success
V/MediaPlayerService(  254): start
V/StagefrightPlayer(  254): start
V/AwesomePlayer(  254): play
V/AwesomePlayer(  254): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer(  254): startAudioPlayer_l, sendErrorNotification (0)
I/OMXCodec(  254): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec(  254): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec(  254): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/AudioPlayer(  254):  Audioplayer kKeyAudioPCMFormat:1, 2, 0
I/AudioPlayer(  254):  Audioplayer kKeyAudioPCMFormat read fail(2, 1)
V/AudioCache(  254): open(44100, 2, 0x0, 1, 4)
V/AwesomePlayer(  254): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache(  254): notify(0xb76fc1c0, 6, 0, 0)
V/AudioCache(  254): ignored
V/AwesomePlayer(  254): addBatteryData
V/MediaPlayerService(  254): wait for playback complete
I/AudioPlayer(  254): First fillBuffer call!!
,I/OMXCodec(  254): [OMX.google.vorbis.decoder] End Of Stream
,V/WebViewChromium( 4577): Binding Chromium to the background looper Looper (main, tid 1) {422fd698}
,I/chromium( 4577): [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
,V/AwesomePlayer(  254): postAudioEOS delayUs (0)
V/AwesomePlayer(  254): onCheckAudioStatus
V/AwesomePlayer(  254): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  254): onStreamDone
V/AwesomePlayer(  254): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  254): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  254): notify(0xb76fc1c0, 2, 0, 0)
V/AudioCache(  254): playback complete - thread will wake up later
V/AwesomePlayer(  254): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  254): notify(0xb76fc1c0, 7, 0, 0)
V/AudioCache(  254): ignored
V/AwesomePlayer(  254): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer(  254): addBatteryData
V/AudioCache(  254): wait - success
V/StagefrightPlayer(  254): reset
V/AwesomePlayer(  254): reset_l()
V/AwesomePlayer(  254): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  254): notify(0xb76fc1c0, 8, 0, 0)
V/AudioCache(  254): ignored
V/AwesomePlayer(  254): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  254): mAudioTrackVector clear
I/OMXCodec(  254): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec(  254): [OMX.google.vorbis.decoder] stop() sendCommand(0x43, OMX_CommandStateSet, OMX_StateIdle)
,I/OMXCodec(  254): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
I/OMXCodec(  254): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
,I/OMX     (  254): instance freeNode
,I/BrowserProcessMain( 4577): Initializing chromium process, renderers=0
I/AudioPlayer(  254): reset out
V/AwesomePlayer(  254): reset_l() mAudioPlayer successfully deleted
I/SecMediaClock(  254): SecMediaClock destructor
V/AwesomePlayer(  254): mSecMediaClock clear
V/StagefrightPlayer(  254): ~StagefrightPlayer
V/StagefrightPlayer(  254): reset
V/AwesomePlayer(  254): reset_l()
V/AwesomePlayer(  254): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  254): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  254): mAudioTrackVector clear
V/AwesomePlayer(  254): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  254): mSecMediaClock clear
,V/AwesomePlayer(  254): destructor
V/AwesomePlayer(  254): reset_l()
V/AwesomePlayer(  254): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  254): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  254): mAudioTrackVector clear
V/AwesomePlayer(  254): reset_l() mAudioPlayer successfully deleted
,V/AwesomePlayer(  254): mSecMediaClock clear
V/MediaPlayer( 4466): decode(75, 30402580, 4509)
,V/MediaPlayerService(  254): decode(35, 30402580, 4509)
V/MediaPlayerService(  254): player type = 3
V/AwesomePlayer(  254): setDefault
,V/AwesomePlayer(  254): constructor
V/AwesomePlayer(  254): setDefault
V/AwesomePlayer(  254): reset_l()
V/AwesomePlayer(  254): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  254): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  254): mAudioTrackVector clear
V/AwesomePlayer(  254): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  254): mSecMediaClock clear
V/StagefrightPlayer(  254): StagefrightPlayer
V/AwesomePlayer(  254): setListener
V/StagefrightPlayer(  254): initCheck
V/AwesomePlayer(  254): setAudioSink
V/StagefrightPlayer(  254): setDataSource(35, 30402580, 4509)
V/AwesomePlayer(  254): reset_l()
V/AwesomePlayer(  254): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  254): notify(0xb76f6b28, 8, 0, 0)
V/AudioCache(  254): ignored
V/AwesomePlayer(  254): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  254): mAudioTrackVector clear
V/AwesomePlayer(  254): reset_l() mAudioPlayer successfully deleted
,V/AwesomePlayer(  254): mSecMediaClock clear
V/AwesomePlayer(  254): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer(  254): mBitrate = -1 bits/sec
V/AwesomePlayer(  254): current audio track index (0) is added to vector
V/AwesomePlayer(  254): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer(  254): AwesomePlayer::setDataSource_l():: This is not a DRM content
V/MediaPlayerService(  254): prepare
V/AwesomePlayer(  254): prepareAsync
,V/MediaPlayerService(  254): wait for prepare
,V/AwesomePlayer(  254): onPrepareAsyncEvent
,I/SecMediaClock(  254): SecMediaClock constructor
I/SecMediaClock(  254): reset
V/AwesomePlayer(  254): initAudioDecoder
V/AwesomePlayer(  254): checkOffloadExceptions is true
,I/OMXCodec(  254): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
,I/OMX     (  254): mDispatchers.add
I/OMXCodec(  254): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec(  254): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
,I/OMXCodec(  254): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec(  254): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/OMXCodec(  254): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
,V/AwesomePlayer(  254): finishAsyncPrepare_l
V/AwesomePlayer(  254): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache(  254): notify(0xb76f6b28, 200, 973, 0)
V/AudioCache(  254): ignored
V/AwesomePlayer(  254): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
,V/AudioCache(  254): notify(0xb76f6b28, 5, 0, 0)
V/AudioCache(  254): ignored
V/AwesomePlayer(  254): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  254): notify(0xb76f6b28, 1, 0, 0)
V/AudioCache(  254): prepared
V/AudioCache(  254): wait - success
V/MediaPlayerService(  254): start
V/StagefrightPlayer(  254): start
V/AwesomePlayer(  254): play
V/AwesomePlayer(  254): AwesomePlayer::play_l():: This is not a DRM content
,V/AwesomePlayer(  254): startAudioPlayer_l, sendErrorNotification (0)
,I/OMXCodec(  254): [OMX.google.vorbis.decoder] End Of Stream
I/OMXCodec(  254): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec(  254): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec(  254): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,W/chromium( 4577): [WARNING:proxy_service.cc(888)] PAC support disabled because there is no system implementation
I/AudioPlayer(  254):  Audioplayer kKeyAudioPCMFormat:1, 2, 0
I/AudioPlayer(  254):  Audioplayer kKeyAudioPCMFormat read fail(2, 1)
V/AudioCache(  254): open(44100, 2, 0x0, 1, 4)
V/AwesomePlayer(  254): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache(  254): notify(0xb76f6b28, 6, 0, 0)
V/AudioCache(  254): ignored
V/AwesomePlayer(  254): addBatteryData
,V/MediaPlayerService(  254): wait for playback complete
,V/AwesomePlayer(  254): postAudioEOS delayUs (0)
V/AwesomePlayer(  254): onCheckAudioStatus
V/AwesomePlayer(  254): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  254): onStreamDone
V/AwesomePlayer(  254): MEDIA_PLAYBACK_COMPLETE
,V/AwesomePlayer(  254): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  254): notify(0xb76f6b28, 2, 0, 0)
V/AudioCache(  254): playback complete - thread will wake up later
V/AwesomePlayer(  254): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  254): notify(0xb76f6b28, 7, 0, 0)
V/AudioCache(  254): ignored
,V/AwesomePlayer(  254): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer(  254): addBatteryData
V/AudioCache(  254): wait - success
V/StagefrightPlayer(  254): reset
V/AwesomePlayer(  254): reset_l()
V/AwesomePlayer(  254): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  254): notify(0xb76f6b28, 8, 0, 0)
V/AudioCache(  254): ignored
V/AwesomePlayer(  254): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  254): mAudioTrackVector clear
I/OMXCodec(  254): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec(  254): [OMX.google.vorbis.decoder] stop() sendCommand(0x44, OMX_CommandStateSet, OMX_StateIdle)
,I/OMXCodec(  254): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
I/OMXCodec(  254): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/OMX     (  254): instance freeNode
I/AudioPlayer(  254): reset out
V/AwesomePlayer(  254): reset_l() mAudioPlayer successfully deleted
I/SecMediaClock(  254): SecMediaClock destructor
V/AwesomePlayer(  254): mSecMediaClock clear
V/StagefrightPlayer(  254): ~StagefrightPlayer
V/StagefrightPlayer(  254): reset
V/AwesomePlayer(  254): reset_l()
,V/AwesomePlayer(  254): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  254): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  254): mAudioTrackVector clear
V/AwesomePlayer(  254): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  254): mSecMediaClock clear
V/AwesomePlayer(  254): destructor
,V/AwesomePlayer(  254): reset_l()
V/AwesomePlayer(  254): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  254): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  254): mAudioTrackVector clear
V/AwesomePlayer(  254): reset_l() mAudioPlayer successfully deleted
,V/AwesomePlayer(  254): mSecMediaClock clear
,I/SELinux ( 4622): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 4622):  
I/ActivityManager(  780): Killing 3182:com.sec.android.app.camera/u0a147 (adj 15): empty #43
,I/SELinux ( 4622): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 4622):  
I/SELinux ( 4622):  
,I/SELinux ( 4622): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 4622): [DEBUG] seapp_context_lookup: seinfoCategory = default
E/dalvikvm( 4622): >>>>> Normal User
,E/dalvikvm( 4622): >>>>> com.osp.app.signin [ userId:0 | appId:10043 ]
,E/SELinux ( 4622): [DEBUG] seapp_context_lookup: seinfoCategory = default
,D/TimaKeyStoreProvider( 4622): in addTimaSignatureService
D/TimaKeyStoreProvider( 4622): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 4622): Added TimaKesytore provider
,I/SA      ( 4622): [SSP] onCreated
,I/SA      ( 4622): [TPM] There is no property file
,I/SA      ( 4622): [SCU] isHaveSA() - false
I/SA      ( 4622): [TPM] getModelProperty : null
,I/SA      ( 4622): [TPM] getCSCProperty : null
,I/SA      ( 4622): [PMR] Received action : android.intent.action.PACKAGE_ADDED
,I/SA      ( 4622): [DM] init START
,I/SA      ( 4622): [DM] This device is not a Vodafone
,I/SA      ( 4622): [DM] getCountryCodeFromCSC : PL
I/SA      ( 4622): support phone number id : false
,I/SA      ( 4622): [DM] init END
,I/SA      ( 4622): [SUR] onReceive log=[SA = 2.0.0117 V = 19 HWD = 1280X720 2.0 dpi = 320  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = kmini3g P = kmini3gxx I = KOT49H M = SM-G800H OKLEFT false DIS KOT49H.G800HXXU1ANK2 PSS = 4.497045606779314  ]
,I/SA      ( 4622): [SUR] onReceive Intent=[ action.PACKAGE_ADDED. package ]
I/ActivityManager(  780): Killing 3289:com.android.email/u0a155 (adj 15): empty #43
,D/Mms/PackageInstallReceiver( 3784): loadAuthorityPref(): sEnableAuthority = true
,I/IcingCorporaProvider( 2112): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
W/ContextImpl( 2827): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1857 android.content.ContextWrapper.startService:506 android.content.ContextWrapper.startService:506 com.samsung.android.app.assistantmenu.AssistantMenuReceiver.onReceive:153 android.app.ActivityThread.handleReceiver:2698 
,I/SELinux ( 4640): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 4640):  
,I/SELinux ( 4640): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 4640):  
I/SELinux ( 4640):  
,I/SELinux ( 4640): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 4640): [DEBUG] seapp_context_lookup: seinfoCategory = samsung
E/dalvikvm( 4640): >>>>> Normal User
,E/dalvikvm( 4640): >>>>> com.sec.android.service.cm [ userId:0 | appId:10078 ]
,E/SELinux ( 4640): [DEBUG] seapp_context_lookup: seinfoCategory = samsung
,D/TimaKeyStoreProvider( 4640): in addTimaSignatureService
,D/TimaKeyStoreProvider( 4640): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 4640): Added TimaKesytore provider
,W/ActivityManager(  780): Permission Denial: getCurrentUser() from pid=4640, uid=10078 requires android.permission.INTERACT_ACROSS_USERS
,D/CapabilityManagerService New( 4640): Receiver Broadcast:android.intent.action.PACKAGE_ADDED
,I/IcingCorporaProvider( 2112): UpdateCorporaTask done [took 161 ms] updated apps [took 160 ms] 
,I/SELinux ( 4653): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 4653):  
I/ActivityManager(  780): Killing 3285:com.samsung.android.provider.shootingmodeprovider/u0a162 (adj 15): empty #43
,I/SELinux ( 4653): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 4653):  
I/SELinux ( 4653):  
,I/SELinux ( 4653): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 4653): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 4653): >>>>> Normal User
,E/dalvikvm( 4653): >>>>> com.google.android.apps.docs [ userId:0 | appId:10090 ]
,E/SELinux ( 4653): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
,D/TimaKeyStoreProvider( 4653): in addTimaSignatureService
,D/TimaKeyStoreProvider( 4653): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 4653): Added TimaKesytore provider
,I/Adreno-EGL( 4577): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 4577): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 4577): Build Date: 03/21/14 Fri
I/Adreno-EGL( 4577): Local Branch: AU200+patches_03212014
I/Adreno-EGL( 4577): Remote Branch: 
I/Adreno-EGL( 4577): Local Patches: 
I/Adreno-EGL( 4577): Reconstruct Branch: 
,I/SecureStorage(  377): [INFO]: SPID(0x00000003)Secure Storage Daemon finished processing with result: 0
,I/SecureStorage(  377): [INFO]: SPID(0x00000003)PID: 4492, TID: 4492
,I/SurfaceFlinger(  249): id=7 Removed Mauncher (7/11)
,I/SurfaceFlinger(  249): id=7 Removed Mauncher (-2/11)
D/KeyguardUpdateMonitor( 1065): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1065): handleKeyguardVisibilityChanged(1)
,D/SurfaceWidgetClient$ISurfaceWidgetStub( 1450): [237392/5] Surface widget visibility changed visibility = false on instance = 1
,D/Launcher( 1257): onTrimMemory. Level: 20
,I/SecureStorage( 4492): [INFO]: SPID(0x00000000)Processing data has been completed
,I/SecureStorage( 4492): [INFO]: SPID(0x00000000)WARNING! Failed to find SecureStorageExceptionJNI!..
I/SQLiteSecureOpenHelper( 4492): getWritableDatabase(pwd)
I/SQLiteSecureOpenHelper( 4492): getDatabaseLocked(b,b,pwd)...
,I/SQLiteSecureOpenHelper( 4492): Open platform.db in secure mode
,I/dalvikvm( 4577): Could not find method android.webkit.CookieManager.setAcceptThirdPartyCookies, referenced from method org.apache.cordova.engine.SystemCookieManager.<init>
W/dalvikvm( 4577): VFY: unable to resolve virtual method 252: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
D/dalvikvm( 4577): VFY: replacing opcode 0x6e at 0x0016
I/dalvikvm( 4577): Could not find method android.webkit.CookieManager.flush, referenced from method org.apache.cordova.engine.SystemCookieManager.flush
W/dalvikvm( 4577): VFY: unable to resolve virtual method 247: Landroid/webkit/CookieManager;.flush ()V
,D/dalvikvm( 4577): VFY: replacing opcode 0x6e at 0x0008
,W/dalvikvm( 4577): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 4577): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
I/dalvikvm( 4577): Could not find method android.webkit.WebViewClient.onReceivedClientCertRequest, referenced from method org.apache.cordova.engine.SystemWebViewClient.onReceivedClientCertRequest
W/dalvikvm( 4577): VFY: unable to resolve virtual method 305: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
,D/dalvikvm( 4577): VFY: replacing opcode 0x6f at 0x001a
,W/dalvikvm( 4577): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
I/dalvikvm( 4577): Could not find method android.webkit.PermissionRequest.getResources, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onPermissionRequest
W/dalvikvm( 4577): VFY: unable to resolve virtual method 263: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
D/dalvikvm( 4577): VFY: replacing opcode 0x6e at 0x000d
I/dalvikvm( 4577): Could not find method android.webkit.WebChromeClient$FileChooserParams.createIntent, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onShowFileChooser
W/dalvikvm( 4577): VFY: unable to resolve virtual method 268: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
,D/dalvikvm( 4577): VFY: replacing opcode 0x6e at 0x0000
,D/SystemWebViewEngine( 4577): CordovaWebView is running on device made by: samsung
,W/ActivityManager(  780): Permission Denial: getCurrentUser() from pid=4653, uid=10090 requires android.permission.INTERACT_ACROSS_USERS
,I/SurfaceFlinger(  249): id=16 createSurf (1x1),1 flag=404, NainActivit
,D/KeyguardUpdateMonitor( 1065): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1065): handleKeyguardVisibilityChanged(1)
I/SQLiteSecureOpenHelper( 4492): ...getDatabaseLocked(b,b,pwd)
,D/SQLiteSecureOpenHelper( 4492): ...getDatabaseLocked(b,b,pwd)
,D/KeyguardUpdateMonitor( 1065): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1065): handleKeyguardVisibilityChanged(1)
,I/HWUI    ( 4577): EGLImpl-HWUI Protected EGL context created
,I/ActivityManager(  780): Killing 1336:com.sec.android.provider.badge/u0a72 (adj 15): empty #43
,D/OpenGLRenderer( 4577): Enabling debug mode 0
,D/OpenGLRenderer( 4577): GL error from OpenGLRenderer: 0x502
,E/OpenGLRenderer( 4577):   GL_INVALID_OPERATION
,D/KeyguardUpdateMonitor( 1065): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1065): handleKeyguardVisibilityChanged(1)
,D/CustomFrequencyManagerService(  780): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 780  tag : ACTIVITY_RESUME_BOOSTER@5
,W/ActivityManager(  780): mDVFSHelper.release()
,D/KeyguardUpdateMonitor( 1065): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1065): handleKeyguardVisibilityChanged(1)
D/CustomFrequencyManagerService(  780): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 780  pkgName : ACTIVITY_RESUME_BOOSTER@9
,W/ContextImpl(  780): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/JsMessageQueue( 4577): Set native->JS mode to OnlineEventsBridgeMode
,W/GAV2    ( 4653): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,I/SELinux ( 4688): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 4688):  
,I/SELinux ( 4688): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 4688):  
I/SELinux ( 4688):  
,I/SELinux ( 4688): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,D/dalvikvm( 4577): Trying to load lib /data/app-lib/com.test.thalitest-7/libjxcore.so 0x42624490
E/SELinux ( 4688): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 4688): >>>>> Normal User
,E/dalvikvm( 4688): >>>>> com.samsung.android.app.watchmanagerstub [ userId:0 | appId:10100 ]
,E/SELinux ( 4688): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/dalvikvm( 4577): Added shared lib /data/app-lib/com.test.thalitest-7/libjxcore.so 0x42624490
,D/jxcore_app_log( 4577): JniHelper::setJavaVM(0x4178b528), pthread_self() = 2034075320
,D/TimaKeyStoreProvider( 4688): in addTimaSignatureService
,D/TimaKeyStoreProvider( 4688): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 4688): Added TimaKesytore provider
,I/chromium( 4577): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot call method 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,D/PackageIntentReceiver( 4688): ACTION_PACKAGE_ADDED
,D/PackageIntentReceiver( 4688): Not GearManger package! 
,I/SELinux ( 4704): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 4704):  
I/ActivityManager(  780): Killing 3311:com.sec.modem.settings/1000 (adj 15): empty #43
,I/SELinux ( 4704): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 4704):  
I/SELinux ( 4704):  
,I/SELinux ( 4704): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 4704): [DEBUG] seapp_context_lookup: seinfoCategory = release
E/dalvikvm( 4704): >>>>> Normal User
,E/dalvikvm( 4704): >>>>> com.samsung.android.magazine.service [ userId:0 | appId:10106 ]
,E/SELinux ( 4704): [DEBUG] seapp_context_lookup: seinfoCategory = release
,D/TimaKeyStoreProvider( 4704): in addTimaSignatureService
,D/TimaKeyStoreProvider( 4704): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 4704): Added TimaKesytore provider
,D/MagazineService Version( 4704): Magazine-Channel: 13
,D/MagazineService Version( 4704): Magazine-Provider: 13
,D/MagazineService Version( 4704): Magazine-Administrator: 11
,D/HeadlinesChannelApplication( 4704): [onCreate]
,D/MagazineService::MagazineBroadcastReceiver( 4704): [onReceive] android.intent.action.PACKAGE_ADDED com.test.thalitest
W/ActivityManager(  780): Permission Denial: getCurrentUser() from pid=4704, uid=10106 requires android.permission.INTERACT_ACROSS_USERS
,I/Icing   ( 1646): Indexing 04B0A0E440E57B3CEEF518675F9B8A06EBE0353B from com.google.android.googlequicksearchbox
,I/MagazineService::MagazineService( 4704): [onHandleIntent] ACTION_PACKAGE_INSTALLED
,I/SELinux ( 4717): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 4717):  
,D/MagazineService::MagazineService( 4704): [onHandleIntent] Send broadcast to (com.test.thalitest).
I/ActivityManager(  780): Killing 3332:tv.peel.smartremote/u0a163 (adj 15): empty #43
,I/SELinux ( 4717): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 4717):  
I/SELinux ( 4717):  
,I/SELinux ( 4717): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 4717): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 4717): >>>>> Normal User
,E/dalvikvm( 4717): >>>>> com.samsung.helphub [ userId:0 | appId:1000 ]
,E/SELinux ( 4717): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,W/GAV2    ( 4653): Thread[main,5,main]: dispatch call queued.  Need to call GAServiceManager.getInstance().initialize().
,I/ActivityManager(  780): Killing 3354:org.simalliance.openmobileapi.service/1101 (adj 15): empty #43
D/dalvikvm( 4577): GC_CONCURRENT freed 4953K, 33% free 12735K/18792K, paused 3ms+3ms, total 44ms
D/dalvikvm( 4577): WAIT_FOR_CONCURRENT_GC blocked 26ms
D/dalvikvm( 4577): WAIT_FOR_CONCURRENT_GC blocked 17ms
D/TimaKeyStoreProvider( 4717): in addTimaSignatureService
D/TimaKeyStoreProvider( 4717): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 4717): Added TimaKesytore provider
,I/Icing   ( 1646): Indexing done 04B0A0E440E57B3CEEF518675F9B8A06EBE0353B
,I/SELinux ( 4732): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 4732):  
I/ActivityManager(  780): Killing 3414:com.sec.android.app.taskmanager/u0a166 (adj 15): empty #43
,I/SELinux ( 4732): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 4732):  
I/SELinux ( 4732):  
,I/SELinux ( 4732): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 4732): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 4732): >>>>> Normal User
,E/dalvikvm( 4732): >>>>> com.sec.kidsplat.installer [ userId:0 | appId:10158 ]
,E/SELinux ( 4732): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 4732): in addTimaSignatureService
,D/TimaKeyStoreProvider( 4732): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 4732): Added TimaKesytore provider
,W/ActivityManager(  780): Permission Denial: getCurrentUser() from pid=4732, uid=10158 requires android.permission.INTERACT_ACROSS_USERS
,D/KidsPlatformStub( 4732): Package not found : com.sec.android.app.kidshome
,I/SELinux ( 4744): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 4744):  
I/ActivityManager(  780): Killing 3426:com.samsung.android.service.travel/u0a169 (adj 15): empty #43
,D/CustomFrequencyManagerService(  780): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 780  tag : ACTIVITY_RESUME_BOOSTER@9
,I/SELinux ( 4744): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 4744):  
I/SELinux ( 4744):  
,I/SELinux ( 4744): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 4744): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 4744): >>>>> Normal User
E/dalvikvm( 4744): >>>>> com.samsung.android.provider.shootingmodeprovider [ userId:0 | appId:10162 ]
,E/SELinux ( 4744): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 4744): in addTimaSignatureService
,D/TimaKeyStoreProvider( 4744): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 4744): Added TimaKesytore provider
,I/SELinux ( 4756): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 4756):  
I/ActivityManager(  780): Killing 3444:com.google.android.youtube/u0a175 (adj 15): empty #43
,I/SELinux ( 4756): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 4756):  
I/SELinux ( 4756):  
,I/SELinux ( 4756): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 4756): [DEBUG] seapp_context_lookup: seinfoCategory = samsung
E/dalvikvm( 4756): >>>>> Normal User
,E/dalvikvm( 4756): >>>>> com.sec.android.app.samsungapps [ userId:0 | appId:10040 ]
,E/SELinux ( 4756): [DEBUG] seapp_context_lookup: seinfoCategory = samsung
,D/TimaKeyStoreProvider( 4756): in addTimaSignatureService
,D/TimaKeyStoreProvider( 4756): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 4756): Added TimaKesytore provider
,D/dalvikvm( 4577): GC_CONCURRENT freed 4661K, 27% free 16249K/22032K, paused 2ms+5ms, total 40ms
,D/dalvikvm( 4577): WAIT_FOR_CONCURRENT_GC blocked 29ms
,D/dalvikvm( 4577): WAIT_FOR_CONCURRENT_GC blocked 28ms
,I/ActivityManager(  780): Killing 3637:com.sec.android.widgetapp.activeapplicationwidget/u0a152 (adj 15): empty #43
,D/PackageBroadcastService( 1646): Received broadcast action=android.intent.action.PACKAGE_ADDED and uri=com.test.thalitest
,D/ChimeraCfgMgr( 1646): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 1646): Loading module APK com.google.android.play.games
,D/Finsky  ( 3522): [1] ExternalReferrer.access$200: Package state data is missing for com.test.thalitest
I/dalvikvm( 1646): Could not find method android.app.admin.DevicePolicyManager.getProfileOwner, referenced from method com.google.android.gms.auth.WorkAccountAuthenticatorInitializer.a
W/dalvikvm( 1646): VFY: unable to resolve virtual method 174: Landroid/app/admin/DevicePolicyManager;.getProfileOwner ()Landroid/content/ComponentName;
,D/dalvikvm( 1646): VFY: replacing opcode 0x6e at 0x0053
,I/dalvikvm( 1646): Failed resolving Lcom/google/android/gms/common/permission/PermissionUtils$1; interface 96 'Landroid/content/pm/PackageManager$OnPermissionsChangedListener;'
,W/dalvikvm( 1646): Link of class 'Lcom/google/android/gms/common/permission/PermissionUtils$1;' failed
E/dalvikvm( 1646): Could not find class 'com.google.android.gms.common.permission.PermissionUtils$1', referenced from method com.google.android.gms.chimera.GmsModuleInitializer.initializeModuleV0
W/dalvikvm( 1646): VFY: unable to resolve new-instance 2374 (Lcom/google/android/gms/common/permission/PermissionUtils$1;) in Lcom/google/android/gms/chimera/GmsModuleInitializer;
,D/dalvikvm( 1646): VFY: replacing opcode 0x22 at 0x001a
I/dalvikvm( 1646): Failed resolving Lcom/google/android/gms/common/permission/PermissionUtils$1; interface 96 'Landroid/content/pm/PackageManager$OnPermissionsChangedListener;'
W/dalvikvm( 1646): Link of class 'Lcom/google/android/gms/common/permission/PermissionUtils$1;' failed
,D/dalvikvm( 1646): DexOpt: unable to opt direct call 0x338d at 0x1c in Lcom/google/android/gms/chimera/GmsModuleInitializer;.initializeModuleV0
,D/ChimeraCfgMgr( 1646): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 1646): Module APK com.google.android.play.games already loaded
,D/ChimeraCfgMgr( 1646): Loading module com.google.android.gms.gass from APK com.google.android.gms
,D/AsyncTaskServiceImpl( 1646): Submit a task: k
,D/ChimeraCfgMgr( 1646): Loading module com.google.android.gms.gass from APK com.google.android.gms
,D/ChimeraCfgMgr( 1646): Loading module com.google.android.gms.vision from APK com.google.android.gms
,D/dalvikvm( 1287): GC_EXPLICIT freed 1010K, 43% free 10787K/18792K, paused 2ms+6ms, total 37ms
,D/k       ( 1646): Processing package: com.test.thalitest
,D/GassUtils( 1646): Found app info for package com.test.thalitest:18. Hash: 4eebbbb84f07ed56a3e96e5e8f9d6abddaaf154fffa2a65432a1006e0fa38f32
,D/k       ( 1646): Found info for package com.test.thalitest in db.
,E/SMD     (  240): DCD OFF
,D/dalvikvm(  780): GC_EXPLICIT freed 2301K, 59% free 23437K/56740K, paused 9ms+13ms, total 143ms
,W/BaseAppContext( 1646): Using Auth Proxy for data requests.
,W/BaseAppContext( 1646): Using Auth Proxy for data requests.
,D/dalvikvm( 4577): GC_FOR_ALLOC freed 5142K, 31% free 17244K/24704K, paused 37ms, total 38ms
,I/dalvikvm-heap( 4577): Grow heap (frag case) to 22.262MB for 2459024-byte allocation
,W/BaseAppContext( 1646): Using Auth Proxy for data requests.
,W/dalvikvm( 1646): VFY: unable to find class referenced in signature (Landroid/app/SharedElementCallback;)
I/dalvikvm( 1646): Could not find method android.app.Activity.setEnterSharedElementCallback, referenced from method android.support.v4.app.w.setEnterSharedElementCallback
W/dalvikvm( 1646): VFY: unable to resolve virtual method 53: Landroid/app/Activity;.setEnterSharedElementCallback (Landroid/app/SharedElementCallback;)V
,D/dalvikvm( 1646): VFY: replacing opcode 0x6e at 0x000e
W/dalvikvm( 1646): VFY: unable to find class referenced in signature (Landroid/app/SharedElementCallback;)
I/dalvikvm( 1646): Could not find method android.app.Activity.setExitSharedElementCallback, referenced from method android.support.v4.app.w.setExitSharedElementCallback
W/dalvikvm( 1646): VFY: unable to resolve virtual method 54: Landroid/app/Activity;.setExitSharedElementCallback (Landroid/app/SharedElementCallback;)V
D/dalvikvm( 1646): VFY: replacing opcode 0x6e at 0x000e
I/dalvikvm( 1646): Could not find method android.app.Activity.finishAfterTransition, referenced from method android.support.v4.app.w.supportFinishAfterTransition
W/dalvikvm( 1646): VFY: unable to resolve virtual method 31: Landroid/app/Activity;.finishAfterTransition ()V
D/dalvikvm( 1646): VFY: replacing opcode 0x6e at 0x0006
I/dalvikvm( 1646): Could not find method android.app.Activity.postponeEnterTransition, referenced from method android.support.v4.app.w.supportPostponeEnterTransition
W/dalvikvm( 1646): VFY: unable to resolve virtual method 49: Landroid/app/Activity;.postponeEnterTransition ()V
D/dalvikvm( 1646): VFY: replacing opcode 0x6e at 0x0006
I/dalvikvm( 1646): Could not find method android.app.Activity.startPostponedEnterTransition, referenced from method android.support.v4.app.w.supportStartPostponedEnterTransition
W/dalvikvm( 1646): VFY: unable to resolve virtual method 61: Landroid/app/Activity;.startPostponedEnterTransition ()V
,D/dalvikvm( 1646): VFY: replacing opcode 0x6e at 0x0006
,W/BaseAppContext( 1646): Using Auth Proxy for data requests.
,W/BaseAppContext( 1646): Using Auth Proxy for data requests.
,W/BaseAppContext( 1646): Using Auth Proxy for data requests.
,W/BaseAppContext( 1646): Using Auth Proxy for data requests.
,I/PeopleDatabaseHelper( 1646): cleanUpNonGplusAccounts done.
,D/dalvikvm( 4577): GC_FOR_ALLOC freed 3738K, 34% free 17955K/27108K, paused 32ms, total 34ms
,W/dalvikvm( 1646): VFY: unable to find class referenced in signature (Landroid/util/Size;)
,D/ChimeraCfgMgr( 1646): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 1646): Module APK com.google.android.play.games already loaded
,D/dalvikvm( 4577): GC_FOR_ALLOC freed 1184K, 35% free 17863K/27108K, paused 29ms, total 29ms
,D/dalvikvm( 4577): GC_FOR_ALLOC freed 4508K, 38% free 19182K/30712K, paused 32ms, total 32ms
,W/jxcore-log( 4577): Initializing JXcore engine
,W/jxcore-log( 4577): JXcore engine is ready
,W/jxcore-log( 4577): Starting JXcore engine
,I/Icing   ( 1646): Indexing 49CA7E3A917E607C6D98AA15891295369CED2106 from com.google.android.gms
,W/jxcore-log( 4577): Platform android
W/jxcore-log( 4577): 
,D/dalvikvm( 1646): GC_CONCURRENT freed 1422K, 37% free 11851K/18792K, paused 4ms+6ms, total 41ms
,W/jxcore-log( 4577): Process ARCH arm
W/jxcore-log( 4577): 
,I/Icing   ( 1646): Indexing done 49CA7E3A917E607C6D98AA15891295369CED2106
,I/jxcore-log( 4577): JXcore Cordova bridge is ready!
I/jxcore-log( 4577): 
,W/jxcore-log( 4577): JXcore engine is started
,E/jxcore  ( 4577): Error!: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js
E/jxcore  ( 4577): Stack: [{"_fileName":"node.js","_functionName":"$h.require","_lineNumber":"1472","_columnNumber":"1","_msg":"    at $h.require@node.js:1472:1"},{"_fileName":"main.js.js","_functionName":"internal_methods.loadMainFile","_lineNumber":"260","_columnNumber":"5","_msg":"    at internal_methods.loadMainFile@main.js.js:260:5"},{"_fileName":"main.js.js","_functionName":"JXMobile.executeJSON","_lineNumber":"279","_columnNumber":"7","_msg":"    at JXMobile.executeJSON@main.js.js:279:7"},{"_fileName":"JX_Evaluate","_functionName":"","_lineNumber":"1","_columnNumber":"1","_msg":"    at @JX_Evaluate:1:1"},{"_fileName":"node.js","_functionName":"unknown","_lineNumber":"1472","_columnNumber":"1","_msg":""}]
,I/chromium( 4577): [INFO:CONSOLE(37)] "App.js file failed to load : "No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\nError: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\n    at $h.require@node.js:1472:1\n    at internal_methods.loadMainFile@main.js.js:260:5\n    at JXMobile.executeJSON@main.js.js:279:7\n    at @JX_Evaluate:1:1\n"", source: file:///android_asset/www/js/thali_main.js (37)
,D/LockPatternUtils( 1065): isPcwEnable = null
I/ActivityManager(  780): Killing 3685:com.sec.android.app.sns3/u0a36 (adj 15): empty #43
,W/PluginManager( 4577): THREAD WARNING: exec() call to CoreAndroid.exitApp blocked the main thread for 18ms. Plugin should use CordovaInterface.getThreadPool().
,I/SurfaceFlinger(  249): id=16 Removed NainActivit (7/11)
,I/SurfaceFlinger(  249): id=16 Removed NainActivit (-2/11)
,D/KeyguardUpdateMonitor( 1065): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1065): handleKeyguardVisibilityChanged(1)
D/CustomFrequencyManagerService(  780): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 780  pkgName : ACTIVITY_RESUME_BOOSTER@5
,W/ActivityManager(  780): mDVFSHelper.acquire()
D/KeyguardUpdateMonitor( 1065): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1065): handleKeyguardVisibilityChanged(1)
,D/KeyguardUpdateMonitor( 1065): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1065): handleKeyguardVisibilityChanged(1)
,D/LockPatternUtils( 1065): isPcwEnable = null
,D/SurfaceWidgetView( 1257): destroyHardwareResources():1126320720
,D/KeyguardUpdateMonitor( 1065): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1065): handleKeyguardVisibilityChanged(1)
,D/KeyguardUpdateMonitor( 1065): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1065): handleKeyguardVisibilityChanged(1)
D/Launcher( 1257): onRestart, Launcher: 1114384960
D/Launcher( 1257): onStart, Launcher: 1114384960
,D/Launcher.HomeView( 1257): onStart
,D/SurfaceWidgetClient$ISurfaceWidgetStub( 1450): [237392/5] Surface widget visibility changed visibility = true on instance = 1
,D/SurfaceWidget.Renderer( 1450): [237392/5] SurfaceWidget drawing first frame
,I/SurfaceFlinger(  249): id=17 createSurf (720x1280),1 flag=4, Mauncher
,D/KeyguardUpdateMonitor( 1065): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1065): handleKeyguardVisibilityChanged(1)
,I/SurfaceFlinger(  249): id=18 createSurf (1x1),2 flag=404, CatteryCove
D/KeyguardUpdateMonitor( 1065): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1065): handleKeyguardVisibilityChanged(1)
,D/KeyguardUpdateMonitor( 1065): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1065): handleKeyguardVisibilityChanged(1)
,D/Launcher.HomeView( 1257): onStop
D/KeyguardUpdateMonitor( 1065): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1065): handleKeyguardVisibilityChanged(1)
,D/KeyguardUpdateMonitor( 1065): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1065): handleKeyguardVisibilityChanged(1)
D/KeyguardUpdateMonitor( 1065): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1065): handleKeyguardVisibilityChanged(1)
D/CustomFrequencyManagerService(  780): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 780  pkgName : ACTIVITY_RESUME_BOOSTER@9
D/CustomFrequencyManagerService(  780): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 780  tag : ACTIVITY_RESUME_BOOSTER@5
D/CustomFrequencyManagerService(  780): FrequencyrequestList.getNextMaxCPUCoreRequest, index: 0
W/ActivityManager(  780): mDVFSHelper.release()
,E/SMD     (  240): DCD OFF
,D/CustomFrequencyManagerService(  780): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 780  tag : ACTIVITY_RESUME_BOOSTER@9
,I/GAV2    ( 4653): Thread[GAThread,5,main]: No campaign data found.
,D/AmoledAdjustTimer(  780): prevTemp = 286, currTemp = 285, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD OFF
,D/BatteryService(  780): level:100, scale:100, status:5, health:2, present:true, voltage: 4367, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:7, charge type:1, power sharing:false
,D/BatteryService(  780): stay LED for fully charged
,D/BatteryService(  780): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
D/UiModeManager(  780): mCoverManager.getCoverState() : true
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP(  780): SIOP:: AP = 310, Delta = 0
,D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
,I/HarmonyEASService(  780): Updating for all 1
,E/SMD     (  240): DCD OFF
,E/SMD     (  240): DCD OFF
,E/Watchdog(  780): !@Sync 3
,E/SMD     (  240): DCD OFF
,D/AmoledAdjustTimer(  780): prevTemp = 285, currTemp = 287, prevStep = 4, currStep = 4
,I/PowerManagerService(  780): [PWL] Off : 50s ago
,D/SSRMv2:SIOP(  780): SIOP:: AP = 300, Delta = -10
,E/SMD     (  240): DCD OFF
,W/ContextImpl(  780): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  240): DCD OFF
,V/AlarmManager(  780): waitForAlarm result :4
,V/AlarmManager(  780): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,V/AlarmManager(  780): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,D/BatteryService(  780): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:8, charge type:1, power sharing:false
,D/BatteryService(  780): stay LED for fully charged
,D/BatteryService(  780): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  780): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
,D/FactoryTest( 4087): Not factory mode
,D/FactoryTest( 4087): Not factory mode. isFactoryMode() returend false
,D/MTPRx   ( 4087): DRIVER_TIME_OUT 60s lapsed
,D/MTPRx   ( 4087): still no open session command from host, so toast
W/ContextImpl( 4087): Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1398 android.content.ContextWrapper.startActivity:323 android.content.ContextWrapper.startActivity:323 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:767 android.os.Handler.dispatchMessage:102 
,W/ContextImpl( 4087): Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1410 android.app.ContextImpl.startActivity:1399 android.content.ContextWrapper.startActivity:323 android.content.ContextWrapper.startActivity:323 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:767 
,V/ApplicationPolicy(  780): isApplicationStateBlocked userId 0 pkgname com.android.settings
,D/CustomFrequencyManagerService(  780): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 780  pkgName : ACTIVITY_RESUME_BOOSTER@5
,W/ActivityManager(  780): mDVFSHelper.acquire()
,D/LockPatternUtils( 1065): isPcwEnable = null
,D/LockPatternUtils( 1065): isPcwEnable = null
,E/MTPRx   ( 4087): started activity for popup
,E/SettingsReceiverActivity( 4087): PREF_DONT_ASK_AGAIN : true
,D/LockPatternUtils( 1065): isPcwEnable = null
I/SQLiteSecureOpenHelper( 2041): getWritableDatabase(pwd)
,I/SQLiteSecureOpenHelper( 2041): getDatabaseLocked(b,b,pwd)...
,D/dalvikvm( 3522): GC_CONCURRENT freed 6655K, 42% free 11011K/18792K, paused 16ms+5ms, total 255ms
,D/SettingsReceiverActivity( 4087): dev.kiessupport is : TRUE
,D/Finsky  ( 3522): [349] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 3522): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,I/WindowManager(  780): Screenshot max retries 4 of Token{42fbedc8 ActivityRecord{424040a8 u0 com.sec.android.app.popupuireceiver/.BatteryCover t2}} appWin=Window{42c26fc8 u0 com.sec.android.app.popupuireceiver/com.sec.android.app.popupuireceiver.BatteryCover} drawState=4
,D/LockPatternUtils( 1065): isPcwEnable = null
W/WindowManager(  780): Screenshot failure taking screenshot for (720x1280) to layer 21005
,E/SMD     (  240): DCD OFF
,V/AlarmManager(  780): waitForAlarm result :8
,V/AlarmManager(  780): ClockReceiver onReceive() ACTION_TIME_TICK
,V/AlarmManager(  780): ___SyncScheduler (v3) ACTIVATED___
V/AlarmManager(  780): <AppSync3 Whitelist>
,V/AlarmManager(  780): (AppSync) ### 0 added ###
D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.TIME_TICK
D/KeyguardUpdateMonitor( 1065): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
,D/AmoledAdjustTimer(  780): prevTemp = 287, currTemp = 285, prevStep = 4, currStep = 4
,D/CustomFrequencyManagerService(  780): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 780  tag : ACTIVITY_RESUME_BOOSTER@5
,W/ActivityManager(  780): mDVFSHelper.release()
,D/CustomFrequencyManagerService(  780): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 780  pkgName : ACTIVITY_RESUME_BOOSTER@9
,D/SSRMv2:SIOP(  780): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD OFF
,D/CustomFrequencyManagerService(  780): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 780  tag : ACTIVITY_RESUME_BOOSTER@9
,E/SMD     (  240): DCD OFF
,D/BatteryService(  780): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 284, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:6, charge type:1, power sharing:false
,D/BatteryService(  780): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  780): stay LED for fully charged
,D/UiModeManager(  780): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  240): DCD OFF
,D/AmoledAdjustTimer(  780): prevTemp = 285, currTemp = 284, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD OFF
,D/SSRMv2:SIOP(  780): SIOP:: AP = 300, Delta = 0
,W/ContextImpl(  780): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  240): DCD OFF
,I/PowerManagerService(  780): [PWL] Off : 75s ago
,E/SMD     (  240): DCD OFF
,D/BatteryService(  780): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:6, charge type:1, power sharing:false
,D/BatteryService(  780): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  780): stay LED for fully charged
,D/UiModeManager(  780): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
,E/Watchdog(  780): !@Sync 4
,V/AlarmManager(  780): waitForAlarm result :8
,D/NtpTrustedTime(  780): forceRefresh() from cache miss
,D/NtpTrustedTime(  780): forceRefresh Fail.
,E/SMD     (  240): DCD OFF
,D/AmoledAdjustTimer(  780): prevTemp = 284, currTemp = 282, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP(  780): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD OFF
,E/SMD     (  240): DCD OFF
,D/BatteryService(  780): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:4, charge type:1, power sharing:false
,D/BatteryService(  780): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  780): stay LED for fully charged
,D/UiModeManager(  780): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  240): DCD OFF
,D/AmoledAdjustTimer(  780): prevTemp = 282, currTemp = 281, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD OFF
,D/SSRMv2:SIOP(  780): SIOP:: AP = 300, Delta = 0
,W/ContextImpl(  780): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  240): DCD OFF
,D/BatteryService(  780): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 280, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:2, charge type:1, power sharing:false
,D/BatteryService(  780): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  780): mCoverManager.getCoverState() : true
,D/BatteryService(  780): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  240): DCD OFF
,D/AmoledAdjustTimer(  780): prevTemp = 281, currTemp = 280, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD OFF
,D/SSRMv2:SIOP(  780): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD OFF
,I/PowerManagerService(  780): [PWL] Off : 105s ago
,E/SMD     (  240): DCD OFF
,D/BatteryService(  780): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 280, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:3, charge type:1, power sharing:false
,D/BatteryService(  780): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  780): stay LED for fully charged
,D/UiModeManager(  780): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
,E/Watchdog(  780): !@Sync 5
,E/SMD     (  240): DCD OFF
,D/AmoledAdjustTimer(  780): prevTemp = 280, currTemp = 280, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP(  780): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD OFF
,W/ContextImpl(  780): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  240): DCD OFF
,E/SMD     (  240): DCD OFF
,V/AlarmManager(  780): waitForAlarm result :8
,V/AlarmManager(  780): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1065): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
,D/BatteryService(  780): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:14, charge type:1, power sharing:false
,D/BatteryService(  780): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  780): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
D/UiModeManager(  780): mCoverManager.getCoverState() : true
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
,D/AmoledAdjustTimer(  780): prevTemp = 280, currTemp = 279, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD OFF
,D/SSRMv2:SIOP(  780): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD OFF
,E/SMD     (  240): DCD OFF
,D/BatteryService(  780): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:13, charge type:1, power sharing:false
,D/BatteryService(  780): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  780): stay LED for fully charged
,D/UiModeManager(  780): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
,D/AmoledAdjustTimer(  780): prevTemp = 279, currTemp = 278, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD OFF
,D/SSRMv2:SIOP(  780): SIOP:: AP = 300, Delta = 0
,W/ContextImpl(  780): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  240): DCD OFF
,E/SMD     (  240): DCD OFF
,E/Watchdog(  780): !@Sync 6
,V/AlarmManager(  780): waitForAlarm result :4
,V/AlarmManager(  780): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,D/NtpTrustedTime(  780): forceRefresh() from cache miss
,D/NtpTrustedTime(  780): forceRefresh Fail.
,D/BatteryService(  780): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:14, charge type:1, power sharing:false
,D/BatteryService(  780): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  780): stay LED for fully charged
,D/UiModeManager(  780): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
,I/ClearcutLoggerApiImpl( 1287): disconnect managed GoogleApiClient
,E/SMD     (  240): DCD OFF
,I/VacuumService( 1214): Vacuum at: now=1453903100988 tag=VacuumService
,D/AmoledAdjustTimer(  780): prevTemp = 278, currTemp = 278, prevStep = 4, currStep = 4
,I/PowerManagerService(  780): [PWL] Off : 140s ago
,D/SSRMv2:SIOP(  780): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD OFF
,E/SMD     (  240): DCD OFF
,E/SMD     (  240): DCD OFF
,D/BatteryService(  780): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:5, charge type:1, power sharing:false
,D/BatteryService(  780): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  780): mCoverManager.getCoverState() : true
,D/BatteryService(  780): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
,D/AmoledAdjustTimer(  780): prevTemp = 278, currTemp = 277, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD OFF
,D/SSRMv2:SIOP(  780): SIOP:: AP = 300, Delta = 0
,W/ContextImpl(  780): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  240): DCD OFF
,E/SMD     (  240): DCD OFF
,D/BatteryService(  780): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:7, charge type:1, power sharing:false
,D/BatteryService(  780): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  780): stay LED for fully charged
,D/UiModeManager(  780): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
,D/AmoledAdjustTimer(  780): prevTemp = 277, currTemp = 277, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD OFF
,D/SSRMv2:SIOP(  780): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD OFF
,E/SMD     (  240): DCD OFF
,E/Watchdog(  780): !@Sync 7
,D/BatteryService(  780): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:6, charge type:1, power sharing:false
,D/BatteryService(  780): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  780): mCoverManager.getCoverState() : true
,D/BatteryService(  780): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  240): DCD OFF
,D/AmoledAdjustTimer(  780): prevTemp = 277, currTemp = 276, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP(  780): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD OFF
,W/ContextImpl(  780): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  240): DCD OFF
,E/SMD     (  240): DCD OFF
,V/AlarmManager(  780): waitForAlarm result :8
,V/AlarmManager(  780): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1065): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
,D/BatteryService(  780): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:16, charge type:1, power sharing:false
,D/BatteryService(  780): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  780): mCoverManager.getCoverState() : true
,D/BatteryService(  780): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
,D/AmoledAdjustTimer(  780): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,I/PowerManagerService(  780): [PWL] Off : 180s ago
,E/SMD     (  240): DCD OFF
,D/SSRMv2:SIOP(  780): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD OFF
,E/SMD     (  240): DCD OFF
,D/BatteryService(  780): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:13, charge type:1, power sharing:false
,D/BatteryService(  780): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  780): stay LED for fully charged
,D/UiModeManager(  780): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
,D/AmoledAdjustTimer(  780): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD OFF
,D/SSRMv2:SIOP(  780): SIOP:: AP = 300, Delta = 0
,W/ContextImpl(  780): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  240): DCD OFF
,E/SMD     (  240): DCD OFF
,E/Watchdog(  780): !@Sync 8
,D/BatteryService(  780): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:13, charge type:1, power sharing:false
,D/BatteryService(  780): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  780): stay LED for fully charged
,D/UiModeManager(  780): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  240): DCD OFF
,D/AmoledAdjustTimer(  780): prevTemp = 276, currTemp = 275, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP(  780): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD OFF
,E/SMD     (  240): DCD OFF
,E/SMD     (  240): DCD OFF
,D/BatteryService(  780): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:5, charge type:1, power sharing:false
,D/BatteryService(  780): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  780): mCoverManager.getCoverState() : true
,D/BatteryService(  780): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
,D/AmoledAdjustTimer(  780): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD OFF
,D/SSRMv2:SIOP(  780): SIOP:: AP = 300, Delta = 0
,W/ContextImpl(  780): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  240): DCD OFF
,E/SMD     (  240): DCD OFF
,D/BatteryService(  780): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:17, charge type:1, power sharing:false
,D/BatteryService(  780): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  780): stay LED for fully charged
,D/UiModeManager(  780): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
,D/AmoledAdjustTimer(  780): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD OFF
,D/SSRMv2:SIOP(  780): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD OFF
,I/PowerManagerService(  780): [PWL] Off : 225s ago
,E/SMD     (  240): DCD OFF
,E/Watchdog(  780): !@Sync 9
,D/BatteryService(  780): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:18, charge type:1, power sharing:false
,D/BatteryService(  780): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  780): stay LED for fully charged
,D/UiModeManager(  780): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  240): DCD OFF
,D/AmoledAdjustTimer(  780): prevTemp = 275, currTemp = 274, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP(  780): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD OFF
,W/ContextImpl(  780): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  240): DCD OFF
,E/SMD     (  240): DCD OFF
,V/AlarmManager(  780): waitForAlarm result :8
,V/AlarmManager(  780): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1065): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
,D/BatteryService(  780): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:4, charge type:1, power sharing:false
,D/BatteryService(  780): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  780): stay LED for fully charged
,D/UiModeManager(  780): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
,D/AmoledAdjustTimer(  780): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD OFF
,D/SSRMv2:SIOP(  780): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD OFF
,E/SMD     (  240): DCD OFF
,D/BatteryService(  780): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:5, charge type:1, power sharing:false
,D/BatteryService(  780): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  780): mCoverManager.getCoverState() : true
,D/BatteryService(  780): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
,D/AmoledAdjustTimer(  780): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD OFF
,D/SSRMv2:SIOP(  780): SIOP:: AP = 300, Delta = 0
,D/TimaService(  780): TIMA: TimaService scheduler is intialized. 
,D/TimaService(  780): TimaServiceHandler.handleMessage what =1
,D/TimaService(  780): TIMA: checkEvent, operation: 50000 subject: 10000
,I/TLC_TIMA_PKM_initialize(  780): initializing...
,I/TLC_TIMA_PKM_initialize(  780): root = /firmware/image, root_strlen = 15
,I/TLC_TIMA_PKM_initialize(  780): process = tima_pkm, process_strlen = 8
,I/TZ: qc_tlc_communication(  780): root = /firmware/image, root_len = 15
,I/TZ: qc_tlc_communication(  780): process = tima_pkm, process_strlen = 8
,I/TZ: qc_tlc_communication(  780): aligned max_sendmsg_size = 262208 = 0x40040
,I/TZ: qc_tlc_communication(  780): aligned max_recvmsg_size = 262208 = 0x40040
,I/TZ: qc_tlc_communication(  780): max_message_size = 524416 = 0x80080
,D/QSEECOMAPI: (  780): QSEECom_get_handle sb_length = 0x80080
,D/QSEECOMAPI: (  780): App is not loaded in QSEE
,D/QSEECOMAPI: (  780): Loaded image: APP id = 3
,I/TZ: qc_tlc_communication(  780): TIMA: path = /firmware/image, fname = tima_pkm, tzapp is loaded
,I/TLC_TIMA_PKM_initialize(  780): Trustlet response is completed
,W/ContextImpl(  780): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  240): DCD OFF
,I/TLC_TIMA_PKM_measure_kernel(  780): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel(  780): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService(  780): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService(  780): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/SMD     (  240): DCD OFF
,E/Watchdog(  780): !@Sync 10
,E/SMD     (  240): DCD OFF
,D/BatteryService(  780): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:5, charge type:1, power sharing:false
,D/BatteryService(  780): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  780): stay LED for fully charged
,D/UiModeManager(  780): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
,D/AmoledAdjustTimer(  780): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP(  780): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD OFF
,E/SMD     (  240): DCD OFF
,E/SMD     (  240): DCD OFF
,D/AmoledAdjustTimer(  780): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD OFF
,D/SSRMv2:SIOP(  780): SIOP:: AP = 300, Delta = 0
,W/ContextImpl(  780): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  240): DCD OFF
,I/PowerManagerService(  780): [PWL] Off : 275s ago
,E/SMD     (  240): DCD OFF
,V/AlarmManager(  780): waitForAlarm result :4
,V/AlarmManager(  780): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,I/SELinux ( 4892): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 4892):  
,D/BatteryService(  780): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  780): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  780): stay LED for fully charged
,D/UiModeManager(  780): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/SELinux ( 4892): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 4892):  
I/SELinux ( 4892):  
,I/SELinux ( 4892): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 4892): [DEBUG] seapp_context_lookup: seinfoCategory = default
,E/dalvikvm( 4892): >>>>> Normal User
,E/dalvikvm( 4892): >>>>> com.blurb.checkout [ userId:0 | appId:10075 ]
,E/SELinux ( 4892): [DEBUG] seapp_context_lookup: seinfoCategory = default
,D/TimaKeyStoreProvider( 4892): in addTimaSignatureService
,D/TimaKeyStoreProvider( 4892): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 4892): Added TimaKesytore provider
,W/ActivityManager(  780): Permission Denial: getCurrentUser() from pid=4892, uid=10075 requires android.permission.INTERACT_ACROSS_USERS
,I/ActivityManager(  780): Killing 3730:com.sec.spp.push:RemoteDlcProcess/u0a38 (adj 15): empty #43
,D/AmoledAdjustTimer(  780): prevTemp = 274, currTemp = 273, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD OFF
,D/SSRMv2:SIOP(  780): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD OFF
,E/SMD     (  240): DCD OFF
,E/Watchdog(  780): !@Sync 11
,V/GLSActivity( 1287): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1287): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/SMD     (  240): DCD OFF
,D/AmoledAdjustTimer(  780): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP(  780): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD OFF
,W/ContextImpl(  780): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  240): DCD OFF
,V/AlarmManager(  780): waitForAlarm result :8
,V/AlarmManager(  780): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1065): handleTimeUpdate
,E/SMD     (  240): DCD OFF
,D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
,D/BatteryService(  780): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:5, charge type:1, power sharing:false
,D/BatteryService(  780): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  780): mCoverManager.getCoverState() : true
,D/BatteryService(  780): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
,D/AmoledAdjustTimer(  780): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD OFF
,D/SSRMv2:SIOP(  780): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD OFF
,E/SMD     (  240): DCD OFF
,D/BatteryService(  780): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:5, charge type:1, power sharing:false
,D/BatteryService(  780): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  780): mCoverManager.getCoverState() : true
,D/BatteryService(  780): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
,D/AmoledAdjustTimer(  780): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD OFF
,D/SSRMv2:SIOP(  780): SIOP:: AP = 300, Delta = 0
,W/ContextImpl(  780): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  240): DCD OFF
,E/SMD     (  240): DCD OFF
,E/Watchdog(  780): !@Sync 12
,D/BatteryService(  780): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:4, charge type:1, power sharing:false
,D/BatteryService(  780): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  780): stay LED for fully charged
,D/UiModeManager(  780): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  240): DCD OFF
,D/AmoledAdjustTimer(  780): prevTemp = 273, currTemp = 272, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP(  780): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD OFF
,E/SMD     (  240): DCD OFF
,E/SMD     (  240): DCD OFF
,D/BatteryService(  780): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:3, charge type:1, power sharing:false
,D/BatteryService(  780): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  780): stay LED for fully charged
,D/UiModeManager(  780): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
,D/AmoledAdjustTimer(  780): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,I/PowerManagerService(  780): [PWL] Off : 330s ago
,E/SMD     (  240): DCD OFF
,D/SSRMv2:SIOP(  780): SIOP:: AP = 300, Delta = 0
,W/ContextImpl(  780): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  240): DCD OFF
,E/SMD     (  240): DCD OFF
,D/BatteryService(  780): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:2, charge type:1, power sharing:false
,D/BatteryService(  780): stay LED for fully charged
,D/BatteryService(  780): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  780): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/dalvikvm(  780): GC_CONCURRENT freed 3365K, 59% free 23467K/56740K, paused 44ms+41ms, total 501ms
,D/AmoledAdjustTimer(  780): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD OFF
,D/SSRMv2:SIOP(  780): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD OFF
,E/SMD     (  240): DCD OFF
,E/Watchdog(  780): !@Sync 13
,D/BatteryService(  780): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:3, charge type:1, power sharing:false
,D/BatteryService(  780): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  780): mCoverManager.getCoverState() : true
,D/BatteryService(  780): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  240): DCD OFF
,D/AmoledAdjustTimer(  780): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP(  780): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD OFF
,W/ContextImpl(  780): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  240): DCD OFF
,V/AlarmManager(  780): waitForAlarm result :8
,V/AlarmManager(  780): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1065): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  240): DCD OFF
,D/BatteryService(  780): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:3, charge type:1, power sharing:false
,D/BatteryService(  780): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  780): stay LED for fully charged
,D/UiModeManager(  780): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
,D/AmoledAdjustTimer(  780): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD OFF
,D/SSRMv2:SIOP(  780): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD OFF
,E/SMD     (  240): DCD OFF
,D/BatteryService(  780): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:2, charge type:1, power sharing:false
,D/BatteryService(  780): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  780): stay LED for fully charged
,D/UiModeManager(  780): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
,D/AmoledAdjustTimer(  780): prevTemp = 272, currTemp = 271, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD OFF
,D/SSRMv2:SIOP(  780): SIOP:: AP = 300, Delta = 0
,W/ContextImpl(  780): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  240): DCD OFF
,E/SMD     (  240): DCD OFF
,E/Watchdog(  780): !@Sync 14
,D/BatteryService(  780): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  780): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  780): mCoverManager.getCoverState() : true
,D/BatteryService(  780): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  240): DCD OFF
,D/AmoledAdjustTimer(  780): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP(  780): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD OFF
,E/SMD     (  240): DCD OFF
,E/SMD     (  240): DCD OFF
,D/BatteryService(  780): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService(  780): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  780): stay LED for fully charged
,D/UiModeManager(  780): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
,D/AmoledAdjustTimer(  780): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,I/PowerManagerService(  780): [PWL] Off : 390s ago
,E/SMD     (  240): DCD OFF
,D/SSRMv2:SIOP(  780): SIOP:: AP = 300, Delta = 0
,W/ContextImpl(  780): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  240): DCD OFF
,E/SMD     (  240): DCD OFF
,D/BatteryService(  780): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:4, charge type:1, power sharing:false
,D/BatteryService(  780): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  780): stay LED for fully charged
,D/UiModeManager(  780): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
,D/AmoledAdjustTimer(  780): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD OFF
,D/SSRMv2:SIOP(  780): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD OFF
,E/SMD     (  240): DCD OFF
,E/Watchdog(  780): !@Sync 15
,D/BatteryService(  780): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:5, charge type:1, power sharing:false
,D/BatteryService(  780): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  780): mCoverManager.getCoverState() : true
,D/BatteryService(  780): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,E/SMD     (  240): DCD OFF
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
,D/AmoledAdjustTimer(  780): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP(  780): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD OFF
,W/ContextImpl(  780): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  240): DCD OFF
,V/AlarmManager(  780): waitForAlarm result :8
,V/AlarmManager(  780): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1065): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  240): DCD OFF
,D/BatteryService(  780): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:9, charge type:1, power sharing:false
,D/BatteryService(  780): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  780): stay LED for fully charged
,D/UiModeManager(  780): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
,D/AmoledAdjustTimer(  780): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD OFF
,D/SSRMv2:SIOP(  780): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD OFF
,E/SMD     (  240): DCD OFF
,D/BatteryService(  780): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:7, charge type:1, power sharing:false
,D/BatteryService(  780): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  780): stay LED for fully charged
,D/UiModeManager(  780): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
,D/AmoledAdjustTimer(  780): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD OFF
,D/SSRMv2:SIOP(  780): SIOP:: AP = 300, Delta = 0
,W/ContextImpl(  780): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  240): DCD OFF
,E/SMD     (  240): DCD OFF
,E/Watchdog(  780): !@Sync 16
,E/SMD     (  240): DCD OFF
,D/BatteryService(  780): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:6, charge type:1, power sharing:false
,D/BatteryService(  780): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  780): stay LED for fully charged
,D/UiModeManager(  780): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
,D/AmoledAdjustTimer(  780): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD OFF
,D/SSRMv2:SIOP(  780): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD OFF
,E/SMD     (  240): DCD OFF
,D/BatteryService(  780): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:2, charge type:1, power sharing:false
,D/BatteryService(  780): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  780): stay LED for fully charged
,D/UiModeManager(  780): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
,D/AmoledAdjustTimer(  780): prevTemp = 271, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD OFF
,D/SSRMv2:SIOP(  780): SIOP:: AP = 300, Delta = 0
,W/ContextImpl(  780): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  240): DCD OFF
,I/PowerManagerService(  780): [PWL] Off : 455s ago
,E/SMD     (  240): DCD OFF
,D/BatteryService(  780): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:2, charge type:1, power sharing:false
,D/BatteryService(  780): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  780): stay LED for fully charged
,D/UiModeManager(  780): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
,D/AmoledAdjustTimer(  780): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD OFF
,D/SSRMv2:SIOP(  780): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD OFF
,E/SMD     (  240): DCD OFF
,E/Watchdog(  780): !@Sync 17
,E/SMD     (  240): DCD OFF
,D/BatteryService(  780): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  780): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  780): mCoverManager.getCoverState() : true
,D/BatteryService(  780): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
,D/AmoledAdjustTimer(  780): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD OFF
,D/SSRMv2:SIOP(  780): SIOP:: AP = 300, Delta = 0
,W/ContextImpl(  780): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  240): DCD OFF
,V/AlarmManager(  780): waitForAlarm result :8
,V/AlarmManager(  780): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1065): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  240): DCD OFF
,D/BatteryService(  780): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:9, charge type:1, power sharing:false
,D/BatteryService(  780): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  780): mCoverManager.getCoverState() : true
,D/BatteryService(  780): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
,D/AmoledAdjustTimer(  780): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD OFF
,D/SSRMv2:SIOP(  780): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD OFF
,E/SMD     (  240): DCD OFF
,D/BatteryService(  780): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-2, charge type:1, power sharing:false
,D/BatteryService(  780): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  780): mCoverManager.getCoverState() : true
,D/BatteryService(  780): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
,D/AmoledAdjustTimer(  780): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD OFF
,W/ContextImpl(  780): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/SSRMv2:SIOP(  780): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD OFF
,E/SMD     (  240): DCD OFF
,E/Watchdog(  780): !@Sync 18
,E/SMD     (  240): DCD OFF
,D/BatteryService(  780): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  780): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  780): stay LED for fully charged
,D/UiModeManager(  780): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
,D/AmoledAdjustTimer(  780): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD OFF
,D/SSRMv2:SIOP(  780): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD OFF
,E/SMD     (  240): DCD OFF
,D/BatteryService(  780): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  780): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  780): stay LED for fully charged
,D/UiModeManager(  780): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
,D/AmoledAdjustTimer(  780): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD OFF
,W/ContextImpl(  780): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/SSRMv2:SIOP(  780): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD OFF
,E/SMD     (  240): DCD OFF
,D/BatteryService(  780): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService(  780): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  780): mCoverManager.getCoverState() : true
,D/BatteryService(  780): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
,D/AmoledAdjustTimer(  780): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD OFF
,D/SSRMv2:SIOP(  780): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD OFF
,I/PowerManagerService(  780): [PWL] Off : 525s ago
,E/SMD     (  240): DCD OFF
,E/Watchdog(  780): !@Sync 19
,E/SMD     (  240): DCD OFF
,D/BatteryService(  780): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  780): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  780): mCoverManager.getCoverState() : true
,D/BatteryService(  780): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
,D/AmoledAdjustTimer(  780): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD OFF
,W/ContextImpl(  780): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/SSRMv2:SIOP(  780): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD OFF
,V/AlarmManager(  780): waitForAlarm result :8
,V/AlarmManager(  780): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1065): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  240): DCD OFF
,D/BatteryService(  780): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:14, charge type:1, power sharing:false
,D/BatteryService(  780): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  780): mCoverManager.getCoverState() : true
,D/BatteryService(  780): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
,D/AmoledAdjustTimer(  780): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD OFF
,D/SSRMv2:SIOP(  780): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD OFF
,E/SMD     (  240): DCD OFF
,D/BatteryService(  780): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:3, charge type:1, power sharing:false
,D/BatteryService(  780): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  780): stay LED for fully charged
,D/UiModeManager(  780): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
,D/AmoledAdjustTimer(  780): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD OFF
,D/TimaService(  780): TIMA: TimaService scheduler is intialized. 
,D/TimaService(  780): TimaServiceHandler.handleMessage what =1
,D/TimaService(  780): TIMA: checkEvent, operation: 50000 subject: 10000
,W/ContextImpl(  780): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/SSRMv2:SIOP(  780): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD OFF
,I/TLC_TIMA_PKM_measure_kernel(  780): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel(  780): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService(  780): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService(  780): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/SMD     (  240): DCD OFF
,E/Watchdog(  780): !@Sync 20
,E/SMD     (  240): DCD OFF
,D/BatteryService(  780): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:2, charge type:1, power sharing:false
,D/BatteryService(  780): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  780): stay LED for fully charged
,D/UiModeManager(  780): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer(  780): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  240): DCD OFF
,D/SSRMv2:SIOP(  780): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD OFF
,E/SMD     (  240): DCD OFF
,D/BatteryService(  780): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  780): Sending ACTION_BATTERY_CHANGED.
,D/AmoledAdjustTimer(  780): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,D/UiModeManager(  780): mCoverManager.getCoverState() : true
,D/BatteryService(  780): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  240): DCD OFF
,W/ContextImpl(  780): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/SSRMv2:SIOP(  780): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD OFF
,E/SMD     (  240): DCD OFF
,D/BatteryService(  780): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/AmoledAdjustTimer(  780): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,D/BatteryService(  780): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  780): stay LED for fully charged
,D/UiModeManager(  780): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  240): DCD OFF
,D/SSRMv2:SIOP(  780): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD OFF
,E/SMD     (  240): DCD OFF
,E/Watchdog(  780): !@Sync 21
,V/GLSActivity( 1287): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1287): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/SMD     (  240): DCD OFF
,D/AmoledAdjustTimer(  780): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,D/BatteryService(  780): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:3, charge type:1, power sharing:false
,D/BatteryService(  780): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  780): mCoverManager.getCoverState() : true
,D/BatteryService(  780): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  240): DCD OFF
,D/SSRMv2:SIOP(  780): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD OFF
,V/AlarmManager(  780): waitForAlarm result :8
,V/AlarmManager(  780): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1065): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  240): DCD OFF
,D/AmoledAdjustTimer(  780): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,D/BatteryService(  780): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  780): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  780): mCoverManager.getCoverState() : true
,D/BatteryService(  780): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
,I/PowerManagerService(  780): [PWL] Off : 600s ago
,E/SMD     (  240): DCD OFF
,D/SSRMv2:SIOP(  780): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD OFF
,E/SMD     (  240): DCD OFF
,D/AmoledAdjustTimer(  780): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD OFF
,D/SSRMv2:SIOP(  780): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD OFF
,E/SMD     (  240): DCD OFF
,E/Watchdog(  780): !@Sync 22
,E/SMD     (  240): DCD OFF
,D/AmoledAdjustTimer(  780): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,D/BatteryService(  780): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  780): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  780): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/BatteryService(  780): stay LED for fully charged
D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  240): DCD OFF
,D/SSRMv2:SIOP(  780): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD OFF
,E/SMD     (  240): DCD OFF
,D/AmoledAdjustTimer(  780): prevTemp = 270, currTemp = 269, prevStep = 4, currStep = 4
,D/BatteryService(  780): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:11, charge type:1, power sharing:false
,D/BatteryService(  780): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  780): stay LED for fully charged
,D/UiModeManager(  780): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  240): DCD OFF
,D/SSRMv2:SIOP(  780): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD OFF
,E/SMD     (  240): DCD OFF
,D/AmoledAdjustTimer(  780): prevTemp = 269, currTemp = 269, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD OFF
,D/BatteryService(  780): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:2, charge type:1, power sharing:false
,D/BatteryService(  780): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  780): mCoverManager.getCoverState() : true
,D/BatteryService(  780): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  780): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD OFF
,E/SMD     (  240): DCD OFF
,E/Watchdog(  780): !@Sync 23
,E/SMD     (  240): DCD OFF
,D/AmoledAdjustTimer(  780): prevTemp = 269, currTemp = 269, prevStep = 4, currStep = 4
,D/BatteryService(  780): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  780): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  780): stay LED for fully charged
,D/UiModeManager(  780): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  240): DCD OFF
,D/SSRMv2:SIOP(  780): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD OFF
,V/AlarmManager(  780): waitForAlarm result :8
,V/AlarmManager(  780): ClockReceiver onReceive() ACTION_TIME_TICK
,V/AlarmManager(  780): ___SyncScheduler (v3) ACTIVATED___
,V/AlarmManager(  780): <AppSync3 Whitelist>
,V/AlarmManager(  780): (AppSync) ### 0 added ###
D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.TIME_TICK
D/KeyguardUpdateMonitor( 1065): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  240): DCD OFF
,D/AmoledAdjustTimer(  780): prevTemp = 269, currTemp = 269, prevStep = 4, currStep = 4
,D/BatteryService(  780): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:14, charge type:1, power sharing:false
,D/BatteryService(  780): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  780): mCoverManager.getCoverState() : true
,D/BatteryService(  780): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  240): DCD OFF
,D/SSRMv2:SIOP(  780): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD OFF
,E/SMD     (  240): DCD OFF
,D/AmoledAdjustTimer(  780): prevTemp = 269, currTemp = 269, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD OFF
,D/BatteryService(  780): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:13, charge type:1, power sharing:false
,D/BatteryService(  780): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  780): stay LED for fully charged
,D/UiModeManager(  780): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  780): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD OFF
,E/SMD     (  240): DCD OFF
,E/Watchdog(  780): !@Sync 24
,E/SMD     (  240): DCD OFF
,D/AmoledAdjustTimer(  780): prevTemp = 269, currTemp = 269, prevStep = 4, currStep = 4
,I/PowerManagerService(  780): [PWL] Off : 680s ago
,D/BatteryService(  780): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:2, charge type:1, power sharing:false
,D/BatteryService(  780): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  780): stay LED for fully charged
,D/UiModeManager(  780): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  240): DCD OFF
,D/SSRMv2:SIOP(  780): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD OFF
,E/SMD     (  240): DCD OFF
,D/AmoledAdjustTimer(  780): prevTemp = 269, currTemp = 269, prevStep = 4, currStep = 4
,D/BatteryService(  780): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  780): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  780): mCoverManager.getCoverState() : true
,D/BatteryService(  780): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  240): DCD OFF
,D/SSRMv2:SIOP(  780): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD OFF
,E/SMD     (  240): DCD OFF
,D/AmoledAdjustTimer(  780): prevTemp = 269, currTemp = 269, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD OFF
,D/SSRMv2:SIOP(  780): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD OFF
,E/SMD     (  240): DCD OFF
,E/Watchdog(  780): !@Sync 25
,I/ClearcutLoggerApiImpl( 1287): disconnect managed GoogleApiClient
,E/SMD     (  240): DCD OFF
,V/AlarmManager(  780): waitForAlarm result :4
,I/SensorManagerA(  780): getReportingMode :: sensor.mType = 5
,D/LightsService(  780): [api] onReceive : SvcLEDReceiver re-enables LightSenor and sends MSG_FORCEDSVCLEDTASK
D/Sensors (  780): LightSensor setDelay = 200000000
D/Sensors (  780): LightSensor setSensorDelay = 200000000
D/Sensors (  780): Light sensor flush: not enabled 0
D/Sensors (  780): LightSensor enable = 1
D/Sensors (  780): LightSensor enableSensor = 1
,D/SensorManager(  780): registerListener :: 16, CM36686 Light Sensor, 200000, 0,  
,V/AlarmManager(  780): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,D/BatteryService(  780): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  780): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  780): mCoverManager.getCoverState() : true
,D/BatteryService(  780): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
,D/Sensors (  780): LightSensor enable = 0
,D/Sensors (  780): LightSensor enableSensor = 0
,D/SensorManager(  780): unregisterListener ::   
D/LightsService(  780): [SvcLED]  onSensorChanged::light value = 5
D/LightsService(  780): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,I/EventLogService( 1646): Aggregate from 1453901871522 (log), 1453901871522 (data)
,D/AmoledAdjustTimer(  780): prevTemp = 269, currTemp = 269, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD OFF
,D/SSRMv2:SIOP(  780): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD OFF
,V/AlarmManager(  780): waitForAlarm result :8
,V/AlarmManager(  780): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1065): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  240): DCD OFF
,D/AmoledAdjustTimer(  780): prevTemp = 269, currTemp = 269, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD OFF
,D/SSRMv2:SIOP(  780): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD OFF
,E/SMD     (  240): DCD OFF
,D/BatteryService(  780): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-2, charge type:1, power sharing:false
,D/BatteryService(  780): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  780): stay LED for fully charged
,D/UiModeManager(  780): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
,D/AmoledAdjustTimer(  780): prevTemp = 269, currTemp = 269, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD OFF
,D/SSRMv2:SIOP(  780): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD OFF
,E/SMD     (  240): DCD OFF
,E/Watchdog(  780): !@Sync 26
,E/SMD     (  240): DCD OFF
,D/BatteryService(  780): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  780): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  780): mCoverManager.getCoverState() : true
,D/BatteryService(  780): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
,D/AmoledAdjustTimer(  780): prevTemp = 269, currTemp = 269, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD OFF
,D/SSRMv2:SIOP(  780): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD OFF
,E/SMD     (  240): DCD OFF
,D/BatteryService(  780): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:4, charge type:1, power sharing:false
,D/BatteryService(  780): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  780): mCoverManager.getCoverState() : true
,D/BatteryService(  780): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
,D/AmoledAdjustTimer(  780): prevTemp = 269, currTemp = 269, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD OFF
,D/SSRMv2:SIOP(  780): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD OFF
,E/SMD     (  240): DCD OFF
,D/BatteryService(  780): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:2, charge type:1, power sharing:false
,D/BatteryService(  780): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  780): mCoverManager.getCoverState() : true
,D/BatteryService(  780): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
,D/AmoledAdjustTimer(  780): prevTemp = 269, currTemp = 269, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD OFF
,E/SMD     (  240): DCD OFF
D/SSRMv2:SIOP(  780): SIOP:: AP = 300, Delta = 0
,I/PowerManagerService(  780): [PWL] Off : 765s ago
,E/SMD     (  240): DCD OFF
,E/Watchdog(  780): !@Sync 27
,E/SMD     (  240): DCD OFF
,D/BatteryService(  780): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:4, charge type:1, power sharing:false
,D/BatteryService(  780): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  780): mCoverManager.getCoverState() : true
,D/BatteryService(  780): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
,D/AmoledAdjustTimer(  780): prevTemp = 269, currTemp = 269, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD OFF
,D/SSRMv2:SIOP(  780): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD OFF
,V/AlarmManager(  780): waitForAlarm result :8
,V/AlarmManager(  780): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1065): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  240): DCD OFF
,D/dalvikvm(  780): GC_CONCURRENT freed 3449K, 59% free 23413K/56740K, paused 28ms+33ms, total 494ms
,D/BatteryService(  780): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:11, charge type:1, power sharing:false
,D/BatteryService(  780): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  780): mCoverManager.getCoverState() : true
,D/BatteryService(  780): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer(  780): prevTemp = 269, currTemp = 269, prevStep = 4, currStep = 4
,D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  240): DCD OFF
,D/SSRMv2:SIOP(  780): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD OFF
,E/SMD     (  240): DCD OFF
,D/BatteryService(  780): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-2, charge type:1, power sharing:false
,D/BatteryService(  780): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  780): stay LED for fully charged
,D/UiModeManager(  780): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer(  780): prevTemp = 269, currTemp = 269, prevStep = 4, currStep = 4
,D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  240): DCD OFF
,E/SMD     (  240): DCD OFF
,D/SSRMv2:SIOP(  780): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD OFF
,E/Watchdog(  780): !@Sync 28
,E/SMD     (  240): DCD OFF
,D/BatteryService(  780): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:11, charge type:1, power sharing:false
,D/BatteryService(  780): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  780): mCoverManager.getCoverState() : true
,D/BatteryService(  780): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/AmoledAdjustTimer(  780): prevTemp = 269, currTemp = 269, prevStep = 4, currStep = 4
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  240): DCD OFF
,D/SSRMv2:SIOP(  780): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD OFF
,E/SMD     (  240): DCD OFF
,D/AmoledAdjustTimer(  780): prevTemp = 269, currTemp = 269, prevStep = 4, currStep = 4
,D/BatteryService(  780): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-2, charge type:1, power sharing:false
,D/BatteryService(  780): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  780): stay LED for fully charged
,D/UiModeManager(  780): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  240): DCD OFF
,D/SSRMv2:SIOP(  780): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD OFF
,E/SMD     (  240): DCD OFF
,E/SMD     (  240): DCD OFF
D/AmoledAdjustTimer(  780): prevTemp = 269, currTemp = 269, prevStep = 4, currStep = 4
,D/BatteryService(  780): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-2, charge type:1, power sharing:false
,D/BatteryService(  780): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  780): stay LED for fully charged
,D/UiModeManager(  780): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  240): DCD OFF
,D/SSRMv2:SIOP(  780): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD OFF
,E/Watchdog(  780): !@Sync 29
,E/SMD     (  240): DCD OFF
,D/AmoledAdjustTimer(  780): prevTemp = 269, currTemp = 269, prevStep = 4, currStep = 4
,D/BatteryService(  780): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-1, charge type:1, power sharing:false
,D/BatteryService(  780): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  780): mCoverManager.getCoverState() : true
,D/BatteryService(  780): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  240): DCD OFF
,D/SSRMv2:SIOP(  780): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD OFF
,V/AlarmManager(  780): waitForAlarm result :8
,V/AlarmManager(  780): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1065): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  240): DCD OFF
,D/AmoledAdjustTimer(  780): prevTemp = 269, currTemp = 269, prevStep = 4, currStep = 4
,D/BatteryService(  780): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:3, charge type:1, power sharing:false
,D/BatteryService(  780): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  780): mCoverManager.getCoverState() : true
,D/BatteryService(  780): stay LED for fully charged
D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  240): DCD OFF
,D/SSRMv2:SIOP(  780): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD OFF
,E/SMD     (  240): DCD OFF
,E/SMD     (  240): DCD OFF
,D/AmoledAdjustTimer(  780): prevTemp = 269, currTemp = 269, prevStep = 4, currStep = 4
,D/BatteryService(  780): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:9, charge type:1, power sharing:false
,D/BatteryService(  780): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  780): mCoverManager.getCoverState() : true
,D/BatteryService(  780): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
,D/TimaService(  780): TIMA: TimaService scheduler is intialized. 
,D/TimaService(  780): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService(  780): TimaServiceHandler.handleMessage what =1
,E/SMD     (  240): DCD OFF
,D/SSRMv2:SIOP(  780): SIOP:: AP = 300, Delta = 0
,I/PowerManagerService(  780): [PWL] Off : 855s ago
,I/PowerManagerService(  780): [PWL]   PowerManagerService.WakeLocks: ref count=1
,I/PowerManagerService(  780): [PWL]     mWakeLockSummary : 0x1
,I/PowerManagerService(  780): [PWL]       PARTIAL_WAKE_LOCK              'TimaService' (uid=1000, pid=780, ws=null) (elapsedTime=3158)
,I/TLC_TIMA_PKM_measure_kernel(  780): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel(  780): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService(  780): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService(  780): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/SMD     (  240): DCD OFF
,E/Watchdog(  780): !@Sync 30
,E/SMD     (  240): DCD OFF
,D/AmoledAdjustTimer(  780): prevTemp = 269, currTemp = 269, prevStep = 4, currStep = 4
,D/BatteryService(  780): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:10, charge type:1, power sharing:false
,D/BatteryService(  780): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  780): mCoverManager.getCoverState() : true
,D/BatteryService(  780): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  240): DCD OFF
,D/SSRMv2:SIOP(  780): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD OFF
,E/SMD     (  240): DCD OFF
,D/AmoledAdjustTimer(  780): prevTemp = 269, currTemp = 269, prevStep = 4, currStep = 4
,D/BatteryService(  780): level:100, scale:100, status:5, health:2, present:true, voltage: 4371, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:3, charge type:1, power sharing:false
,D/BatteryService(  780): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  780): stay LED for fully charged
,D/UiModeManager(  780): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  240): DCD OFF
,D/SSRMv2:SIOP(  780): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD OFF
,E/SMD     (  240): DCD OFF
,E/SMD     (  240): DCD OFF
,D/AmoledAdjustTimer(  780): prevTemp = 269, currTemp = 269, prevStep = 4, currStep = 4
,D/BatteryService(  780): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:5, charge type:1, power sharing:false
,D/BatteryService(  780): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  780): mCoverManager.getCoverState() : true
,D/BatteryService(  780): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  240): DCD OFF
,D/SSRMv2:SIOP(  780): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD OFF
,E/Watchdog(  780): !@Sync 31
,V/GLSActivity( 1287): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1287): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/SMD     (  240): DCD OFF
,D/AmoledAdjustTimer(  780): prevTemp = 269, currTemp = 268, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD OFF
,D/SSRMv2:SIOP(  780): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD OFF
,V/AlarmManager(  780): waitForAlarm result :8
,V/AlarmManager(  780): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1065): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  240): DCD OFF
,D/AmoledAdjustTimer(  780): prevTemp = 268, currTemp = 268, prevStep = 4, currStep = 4
,D/BatteryService(  780): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:11, charge type:1, power sharing:false
,D/BatteryService(  780): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  780): stay LED for fully charged
,D/UiModeManager(  780): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  240): DCD OFF
,D/SSRMv2:SIOP(  780): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD OFF
,E/SMD     (  240): DCD OFF
,E/SMD     (  240): DCD OFF
,D/AmoledAdjustTimer(  780): prevTemp = 268, currTemp = 268, prevStep = 4, currStep = 4
,D/BatteryService(  780): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:12, charge type:1, power sharing:false
,D/BatteryService(  780): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  780): stay LED for fully charged
,D/UiModeManager(  780): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  240): DCD OFF
,D/SSRMv2:SIOP(  780): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD OFF
,E/Watchdog(  780): !@Sync 32
,E/SMD     (  240): DCD OFF
,D/AmoledAdjustTimer(  780): prevTemp = 268, currTemp = 268, prevStep = 4, currStep = 4
,D/BatteryService(  780): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:11, charge type:1, power sharing:false
,D/BatteryService(  780): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  780): stay LED for fully charged
,D/UiModeManager(  780): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  240): DCD OFF
,D/SSRMv2:SIOP(  780): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD OFF
,E/SMD     (  240): DCD OFF
,D/AmoledAdjustTimer(  780): prevTemp = 268, currTemp = 268, prevStep = 4, currStep = 4
,D/BatteryService(  780): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:2, charge type:1, power sharing:false
,D/BatteryService(  780): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  780): stay LED for fully charged
,D/UiModeManager(  780): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  240): DCD OFF
,D/SSRMv2:SIOP(  780): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD OFF
,E/SMD     (  240): DCD OFF
,E/SMD     (  240): DCD OFF
,D/AmoledAdjustTimer(  780): prevTemp = 268, currTemp = 268, prevStep = 4, currStep = 4
,D/BatteryService(  780): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:13, charge type:1, power sharing:false
,D/BatteryService(  780): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  780): stay LED for fully charged
,D/UiModeManager(  780): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  240): DCD OFF
,D/SSRMv2:SIOP(  780): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD OFF
,E/Watchdog(  780): !@Sync 33
,E/SMD     (  240): DCD OFF
,I/PowerManagerService(  780): [PWL] Off : 950s ago
,D/AmoledAdjustTimer(  780): prevTemp = 268, currTemp = 268, prevStep = 4, currStep = 4
,D/BatteryService(  780): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:11, charge type:1, power sharing:false
,D/BatteryService(  780): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  780): stay LED for fully charged
,D/UiModeManager(  780): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  240): DCD OFF
,D/SSRMv2:SIOP(  780): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD OFF
,V/AlarmManager(  780): waitForAlarm result :8
,V/AlarmManager(  780): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1065): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  240): DCD OFF
,D/AmoledAdjustTimer(  780): prevTemp = 268, currTemp = 268, prevStep = 4, currStep = 4
,D/BatteryService(  780): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:14, charge type:1, power sharing:false
,D/BatteryService(  780): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  780): stay LED for fully charged
,D/UiModeManager(  780): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  240): DCD OFF
,D/SSRMv2:SIOP(  780): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD OFF
,E/SMD     (  240): DCD OFF
,E/SMD     (  240): DCD OFF
,D/AmoledAdjustTimer(  780): prevTemp = 268, currTemp = 268, prevStep = 4, currStep = 4
,D/BatteryService(  780): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:13, charge type:1, power sharing:false
,D/BatteryService(  780): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  780): mCoverManager.getCoverState() : true
,D/BatteryService(  780): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  240): DCD OFF
,D/SSRMv2:SIOP(  780): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD OFF
,E/Watchdog(  780): !@Sync 34
,E/SMD     (  240): DCD OFF
,D/AmoledAdjustTimer(  780): prevTemp = 268, currTemp = 268, prevStep = 4, currStep = 4
,D/BatteryService(  780): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:4, charge type:1, power sharing:false
,D/BatteryService(  780): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  780): stay LED for fully charged
,D/UiModeManager(  780): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  240): DCD OFF
,D/SSRMv2:SIOP(  780): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD OFF
,E/SMD     (  240): DCD OFF
,D/AmoledAdjustTimer(  780): prevTemp = 268, currTemp = 268, prevStep = 4, currStep = 4
,D/BatteryService(  780): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService(  780): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  780): mCoverManager.getCoverState() : true
,D/BatteryService(  780): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  240): DCD OFF
,D/SSRMv2:SIOP(  780): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD OFF
,E/SMD     (  240): DCD OFF
,E/SMD     (  240): DCD OFF
,D/AmoledAdjustTimer(  780): prevTemp = 268, currTemp = 268, prevStep = 4, currStep = 4
,D/BatteryService(  780): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:2, charge type:1, power sharing:false
,D/BatteryService(  780): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  780): mCoverManager.getCoverState() : true
,D/BatteryService(  780): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  240): DCD OFF
,D/SSRMv2:SIOP(  780): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD OFF
,E/Watchdog(  780): !@Sync 35
,E/SMD     (  240): DCD OFF
,D/AmoledAdjustTimer(  780): prevTemp = 268, currTemp = 268, prevStep = 4, currStep = 4
,D/BatteryService(  780): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  780): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  780): stay LED for fully charged
,D/UiModeManager(  780): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  240): DCD OFF
,D/SSRMv2:SIOP(  780): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD OFF
,V/AlarmManager(  780): waitForAlarm result :8
,V/AlarmManager(  780): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1065): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  240): DCD OFF
,D/AmoledAdjustTimer(  780): prevTemp = 268, currTemp = 268, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD OFF
,D/BatteryService(  780): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:2, charge type:1, power sharing:false
,D/BatteryService(  780): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  780): mCoverManager.getCoverState() : true
,D/BatteryService(  780): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  780): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD OFF
,E/SMD     (  240): DCD OFF
,E/SMD     (  240): DCD OFF
,D/AmoledAdjustTimer(  780): prevTemp = 268, currTemp = 268, prevStep = 4, currStep = 4
,D/BatteryService(  780): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService(  780): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  780): mCoverManager.getCoverState() : true
,D/BatteryService(  780): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  240): DCD OFF
,D/SSRMv2:SIOP(  780): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD OFF
,E/Watchdog(  780): !@Sync 36
,E/SMD     (  240): DCD OFF
,D/AmoledAdjustTimer(  780): prevTemp = 268, currTemp = 268, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD OFF
,D/SSRMv2:SIOP(  780): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD OFF
,E/SMD     (  240): DCD OFF
,I/PowerManagerService(  780): [PWL] Off : 1050s ago
,D/AmoledAdjustTimer(  780): prevTemp = 268, currTemp = 268, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD OFF
,D/BatteryService(  780): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:12, charge type:1, power sharing:false
,D/BatteryService(  780): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  780): stay LED for fully charged
,D/UiModeManager(  780): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  780): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD OFF
,E/SMD     (  240): DCD OFF
,E/SMD     (  240): DCD OFF
,D/AmoledAdjustTimer(  780): prevTemp = 268, currTemp = 268, prevStep = 4, currStep = 4
,D/BatteryService(  780): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:10, charge type:1, power sharing:false
,D/BatteryService(  780): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  780): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
D/BatteryService(  780): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  240): DCD OFF
,D/SSRMv2:SIOP(  780): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD OFF
,E/Watchdog(  780): !@Sync 37
,E/SMD     (  240): DCD OFF
,D/AmoledAdjustTimer(  780): prevTemp = 268, currTemp = 268, prevStep = 4, currStep = 4
,D/BatteryService(  780): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:11, charge type:1, power sharing:false
,D/BatteryService(  780): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  780): mCoverManager.getCoverState() : true
,D/BatteryService(  780): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  240): DCD OFF
,D/SSRMv2:SIOP(  780): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD OFF
,V/AlarmManager(  780): waitForAlarm result :8
,V/AlarmManager(  780): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1065): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  240): DCD OFF
,D/AmoledAdjustTimer(  780): prevTemp = 268, currTemp = 268, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD OFF
,D/BatteryService(  780): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:10, charge type:1, power sharing:false
,D/BatteryService(  780): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  780): stay LED for fully charged
,D/UiModeManager(  780): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  780): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD OFF
,E/SMD     (  240): DCD OFF
,E/SMD     (  240): DCD OFF
,D/AmoledAdjustTimer(  780): prevTemp = 268, currTemp = 268, prevStep = 4, currStep = 4
,D/BatteryService(  780): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:12, charge type:1, power sharing:false
,D/BatteryService(  780): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  780): stay LED for fully charged
,D/UiModeManager(  780): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  240): DCD OFF
,D/SSRMv2:SIOP(  780): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD OFF
,E/Watchdog(  780): !@Sync 38
,E/SMD     (  240): DCD OFF
,D/AmoledAdjustTimer(  780): prevTemp = 268, currTemp = 268, prevStep = 4, currStep = 4
,D/BatteryService(  780): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:11, charge type:1, power sharing:false
,D/BatteryService(  780): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  780): mCoverManager.getCoverState() : true
,D/BatteryService(  780): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  240): DCD OFF
,D/SSRMv2:SIOP(  780): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD OFF
,E/SMD     (  240): DCD OFF
,D/AmoledAdjustTimer(  780): prevTemp = 268, currTemp = 268, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD OFF
,D/BatteryService(  780): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  780): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  780): stay LED for fully charged
,D/UiModeManager(  780): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  240): DCD OFF
,D/SSRMv2:SIOP(  780): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD OFF
,E/SMD     (  240): DCD OFF
,D/AmoledAdjustTimer(  780): prevTemp = 268, currTemp = 268, prevStep = 4, currStep = 4
,D/BatteryService(  780): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:3, charge type:1, power sharing:false
,D/BatteryService(  780): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  780): stay LED for fully charged
,D/UiModeManager(  780): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  240): DCD OFF
,D/SSRMv2:SIOP(  780): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD OFF
,E/Watchdog(  780): !@Sync 39
,E/SMD     (  240): DCD OFF
,D/AmoledAdjustTimer(  780): prevTemp = 268, currTemp = 268, prevStep = 4, currStep = 4
,D/BatteryService(  780): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:2, charge type:1, power sharing:false
,D/BatteryService(  780): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  780): mCoverManager.getCoverState() : true
,D/BatteryService(  780): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  240): DCD OFF
,D/SSRMv2:SIOP(  780): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD OFF
,V/AlarmManager(  780): waitForAlarm result :8
,V/AlarmManager(  780): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1065): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  240): DCD OFF
,D/AmoledAdjustTimer(  780): prevTemp = 268, currTemp = 268, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD OFF
,D/BatteryService(  780): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:2, charge type:1, power sharing:false
,D/BatteryService(  780): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  780): mCoverManager.getCoverState() : true
,D/BatteryService(  780): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  240): DCD OFF
,D/SSRMv2:SIOP(  780): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD OFF
,E/SMD     (  240): DCD OFF
,D/AmoledAdjustTimer(  780): prevTemp = 268, currTemp = 268, prevStep = 4, currStep = 4
,D/TimaService(  780): TIMA: TimaService scheduler is intialized. 
,D/TimaService(  780): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService(  780): TimaServiceHandler.handleMessage what =1
,D/BatteryService(  780): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:8, charge type:1, power sharing:false
,D/BatteryService(  780): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  780): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
D/BatteryService(  780): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  240): DCD OFF
,D/SSRMv2:SIOP(  780): SIOP:: AP = 300, Delta = 0
,I/PowerManagerService(  780): [PWL] Off : 1155s ago
,I/PowerManagerService(  780): [PWL]   PowerManagerService.WakeLocks: ref count=1
,I/PowerManagerService(  780): [PWL]     mWakeLockSummary : 0x1
,I/PowerManagerService(  780): [PWL]       PARTIAL_WAKE_LOCK              'TimaService' (uid=1000, pid=780, ws=null) (elapsedTime=3168)
,I/TLC_TIMA_PKM_measure_kernel(  780): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel(  780): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService(  780): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService(  780): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/SMD     (  240): DCD OFF
,E/Watchdog(  780): !@Sync 40
,E/SMD     (  240): DCD OFF
,D/AmoledAdjustTimer(  780): prevTemp = 268, currTemp = 268, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD OFF
,D/SSRMv2:SIOP(  780): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD OFF
,E/SMD     (  240): DCD OFF
,D/AmoledAdjustTimer(  780): prevTemp = 268, currTemp = 268, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD OFF
,D/BatteryService(  780): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:2, charge type:1, power sharing:false
,D/BatteryService(  780): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  780): stay LED for fully charged
,D/UiModeManager(  780): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  240): DCD OFF
,D/SSRMv2:SIOP(  780): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD OFF
,E/SMD     (  240): DCD OFF
,D/AmoledAdjustTimer(  780): prevTemp = 268, currTemp = 268, prevStep = 4, currStep = 4
,D/BatteryService(  780): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:2, charge type:1, power sharing:false
,D/BatteryService(  780): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  780): stay LED for fully charged
,D/UiModeManager(  780): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  240): DCD OFF
,D/SSRMv2:SIOP(  780): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD OFF
,E/Watchdog(  780): !@Sync 41
,E/SMD     (  240): DCD OFF
,V/GLSActivity( 1287): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1287): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/AmoledAdjustTimer(  780): prevTemp = 268, currTemp = 268, prevStep = 4, currStep = 4
,D/BatteryService(  780): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService(  780): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  780): stay LED for fully charged
,D/UiModeManager(  780): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  240): DCD OFF
,D/SSRMv2:SIOP(  780): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD OFF
,V/AlarmManager(  780): waitForAlarm result :8
,V/AlarmManager(  780): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1065): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  240): DCD OFF
,D/AmoledAdjustTimer(  780): prevTemp = 268, currTemp = 268, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD OFF
,D/BatteryService(  780): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  780): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  780): stay LED for fully charged
,D/UiModeManager(  780): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  240): DCD OFF
,D/SSRMv2:SIOP(  780): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD OFF
,E/SMD     (  240): DCD OFF
,D/AmoledAdjustTimer(  780): prevTemp = 268, currTemp = 268, prevStep = 4, currStep = 4
,D/BatteryService(  780): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-1, charge type:1, power sharing:false
,D/BatteryService(  780): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  780): stay LED for fully charged
,D/UiModeManager(  780): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  240): DCD OFF
,D/SSRMv2:SIOP(  780): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD OFF
,E/Watchdog(  780): !@Sync 42
,E/SMD     (  240): DCD OFF
,D/AmoledAdjustTimer(  780): prevTemp = 268, currTemp = 268, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD OFF
,D/BatteryService(  780): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:9, charge type:1, power sharing:false
,D/BatteryService(  780): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  780): stay LED for fully charged
,D/UiModeManager(  780): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  780): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD OFF
,E/SMD     (  240): DCD OFF
,D/AmoledAdjustTimer(  780): prevTemp = 268, currTemp = 268, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD OFF
,D/BatteryService(  780): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:2, charge type:1, power sharing:false
,D/BatteryService(  780): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
D/UiModeManager(  780): mCoverManager.getCoverState() : true
,D/BatteryService(  780): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  240): DCD OFF
,D/SSRMv2:SIOP(  780): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD OFF
,E/SMD     (  240): DCD OFF
,D/AmoledAdjustTimer(  780): prevTemp = 268, currTemp = 267, prevStep = 4, currStep = 4
,D/dalvikvm(  780): GC_CONCURRENT freed 3381K, 59% free 23428K/56740K, paused 21ms+33ms, total 402ms
,D/BatteryService(  780): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:2, charge type:1, power sharing:false
,D/BatteryService(  780): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  780): stay LED for fully charged
,D/UiModeManager(  780): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  240): DCD OFF
,D/SSRMv2:SIOP(  780): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD OFF
,E/Watchdog(  780): !@Sync 43
,E/SMD     (  240): DCD OFF
,D/AmoledAdjustTimer(  780): prevTemp = 267, currTemp = 268, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD OFF
,D/BatteryService(  780): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:3, charge type:1, power sharing:false
,D/BatteryService(  780): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  780): stay LED for fully charged
,D/UiModeManager(  780): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1065): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1065): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1065):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1065): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
,TIME-OUT KILL (timeout was 1200000ms),D/AndroidRuntime( 5120): 
D/AndroidRuntime( 5120): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 5120): CheckJNI is OFF
D/AndroidRuntime( 5120): setted country_code = Poland
D/AndroidRuntime( 5120): setted countryiso_code = PL
D/AndroidRuntime( 5120): setted sales_code = XEO
D/AndroidRuntime( 5120): readGMSProperty: start
D/AndroidRuntime( 5120): readGMSProperty: already setted!!
D/AndroidRuntime( 5120): readGMSProperty: end
D/AndroidRuntime( 5120): addProductProperty: start
D/dalvikvm( 5120): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 5120): Added shared lib libjavacore.so 0x0
D/dalvikvm( 5120): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 5120): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 5120): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
E/memtrack( 5120): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 5120): failed to load memtrack module: -2
D/dalvikvm( 5120): Note: class Landroid/app/ActivityManagerNative; has 192 unimplemented (abstract) methods
D/AndroidRuntime( 5120): Calling main entry com.android.commands.pm.Pm
D/PackageManagerService(  780): deletePackageAsUser- pkg:com.test.thalitest, userId:0
D/PersonaManagerService(  780): isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
D/PersonaManagerService(  780): isFromApprovedUnInstaller: isApproved : true
D/PersonaManagerService(  780): isFromApprovedUnInstaller: isApproved before exit: true
D/PackageManager(  780): deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag3
D/PackageManager(  780): deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag3
D/PackageManagerService(  780): deletePackage- pkg:com.test.thalitest, edmuserId:0
D/PackageManagerService(  780): deletePackage- pkg:com.test.thalitest, edmuserId:-1
D/ApplicationPolicy(  780): getApplicationUninstallationEnabled
D/ApplicationPolicy(  780): getApplicationUninstallationEnabled :  enabled true
D/PackageManagerService(  780): deletePackageX- pkg:com.test.thalitest, userId:0
D/PackageManager(  780): START PACKAGE DELETE: observer{1135572864}
D/PackageManager(  780): pkg{<packageName>}
D/PackageManager(  780): user{0}
D/PackageManager(  780): deletePackageAsUser : uid = 2000 userId = 0
D/PackageManager(  780): [MSG] DELETE_PACKAGE_AS_USER
D/PackageManager(  780): !@killApplicatoin: 10179, uninstall pkg
I/ActivityManager(  780): Killing 4577:com.test.thalitest/u0a179 (adj 9): stop com.test.thalitest
D/PackageManager(  780): Sending to user 0: act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000000 Bundle[{android.intent.extra.REMOVED_FOR_ALL_USERS=true, android.intent.extra.UID=10179, android.intent.extra.DATA_REMOVED=true, android.intent.extra.user_handle=0}]
D/PackageManager(  780): Sending to user 0: act=android.intent.action.PACKAGE_FULLY_REMOVED dat=package:com.test.thalitest flg=0x4000000 Bundle[{android.intent.extra.REMOVED_FOR_ALL_USERS=true, android.intent.extra.UID=10179, android.intent.extra.DATA_REMOVED=true, android.intent.extra.user_handle=0}]
D/dalvikvm( 1410): GC_EXPLICIT freed 4288K, 47% free 10019K/18792K, paused 3ms+4ms, total 68ms
D/AdaptiveEventManager( 1065): action=android.intent.action.PACKAGE_REMOVED
I/InputReader(  780): Reconfiguring input devices.  changes=0x00000010
D/QuickConnect[1.1][2] ( 3128): SconnectManager.onReceiver - action : android.intent.action.PACKAGE_REMOVED, package : com.test.thalitest
I/PackageManager(  780):   Action: "android.intent.action.SENDTO"
I/PackageManager(  780):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  780):   Scheme: "sms"
I/SELinux ( 5151): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5151):  
I/PackageManager(  780): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
W/GeofencerStateMachine( 1214): Ignoring removeGeofence because network location is disabled.
D/dalvikvm(  251): GC_EXPLICIT freed 43K, 50% free 9507K/18792K, paused 2ms+3ms, total 28ms
I/PackageManager(  780):   Action: "android.intent.action.SENDTO"
I/PackageManager(  780):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  780):   Scheme: "smsto"
I/PackageManager(  780): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
I/SELinux ( 5151): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5151):  
I/SELinux ( 5151):  
I/SELinux ( 5151): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 5151): [DEBUG] seapp_context_lookup: seinfoCategory = platform
I/PackageManager(  780):   Action: "android.intent.action.SENDTO"
I/PackageManager(  780):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  780):   Scheme: "mms"
D/dalvikvm(  251): GC_EXPLICIT freed <1K, 50% free 9507K/18792K, paused 2ms+3ms, total 19ms
E/dalvikvm( 5151): >>>>> Normal User
E/dalvikvm( 5151): >>>>> com.sec.esdk.elm [ userId:0 | appId:10094 ]
E/SELinux ( 5151): [DEBUG] seapp_context_lookup: seinfoCategory = platform
I/PackageManager(  780): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
D/dalvikvm( 1646): GC_EXPLICIT freed 713K, 37% free 11863K/18792K, paused 4ms+36ms, total 204ms
D/dalvikvm(  251): GC_EXPLICIT freed <1K, 50% free 9507K/18792K, paused 2ms+3ms, total 20ms
D/TimaKeyStoreProvider( 5151): in addTimaSignatureService
D/dalvikvm( 2112): GC_EXPLICIT freed 1127K, 42% free 11033K/18792K, paused 12ms+46ms, total 198ms
D/TimaKeyStoreProvider( 5151): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 5151): Added TimaKesytore provider
I/PackageManager(  780):   Action: "android.intent.action.SENDTO"
I/PackageManager(  780):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  780):   Scheme: "mmsto"
I/PackageManager(  780): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
I/FPMS_FingerprintManagerService( 1084): onReceive: android.intent.action.PACKAGE_REMOVED
D/SSRMv2:SIOP(  780): SIOP:: AP = 300, Delta = 0
D/dalvikvm(  780): GC_EXPLICIT freed 1186K, 59% free 23495K/56740K, paused 14ms+14ms, total 211ms
I/PackageManager(  780):   Action: "android.intent.action.SENDTO"
I/PackageManager(  780):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  780):   Scheme: "sms"
I/PackageManager(  780): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
I/PackageManager(  780):   Action: "android.intent.action.SENDTO"
I/PackageManager(  780):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  780):   Scheme: "smsto"
I/PackageManager(  780): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
D/RCPManagerService(  780): PackageReceiver onReceive()
I/PackageManager(  780):   Action: "android.intent.action.SENDTO"
I/PackageManager(  780):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  780):   Scheme: "mms"
I/HarmonyEASService(  780): onReceive : android.intent.action.PACKAGE_REMOVED for 0
W/InputMethodInfo(  780): Duplicated subtype definition found: , voice
I/PackageManager(  780): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
W/ActivityManager(  780): Permission Denial: getCurrentUser() from pid=5151, uid=10094 requires android.permission.INTERACT_ACROSS_USERS
I/PackageManager(  780):   Action: "android.intent.action.SENDTO"
I/PackageManager(  780):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  780):   Scheme: "mmsto"
I/PackageManager(  780): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
D/elm:14132( 5151): ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
D/elm:14132( 5151): ELMEngine.ELMEngine( context ).
D/elm:14132( 5151): MDMBridge.setEnterpriseBridge()
D/elm:14132( 5151): ELMAbstractReceiver : Receive Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
D/elm:14132( 5151): ElmAgentService : onCreate()
D/elm:14132( 5151): ElmAgentService : onHandleIntent() Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
D/elm:14132( 5151): MainReceiver.listeningToPackageRemoved()
D/elm:14132( 5151): MDMBridge.getInstance()
D/elm:14132( 5151): MDMBridge.getAllLicenseInfoFromSDK()
D/elm:14132( 5151): MDMBridge.getAllLicenseInfoFromSDK()
I/SELinux ( 5165): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5165):  
D/elm:14132( 5151): MainReceiver.listeningToPackageRemoved(). SEND to KLMS. Remove All KNOX/ONS License
D/elm:14132( 5151): ElmAgentService : onDestroy().
D/EnterpriseDeviceManagerService(  780): Package has changed for user 0
D/EnterpriseDeviceManagerService(  780): Admin package name: com.google.android.gms
I/SELinux ( 5165): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5165):  
I/SELinux ( 5165):  
I/SELinux ( 5165): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 5165): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 5165): >>>>> Normal User
E/dalvikvm( 5165): >>>>> com.sec.android.app.mss [ userId:0 | appId:10021 ]
E/SELinux ( 5165): [DEBUG] seapp_context_lookup: seinfoCategory = platform
D/TimaKeyStoreProvider( 5165): in addTimaSignatureService
D/TimaKeyStoreProvider( 5165): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 5165): Added TimaKesytore provider
W/Resources(  780): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/BackupManagerService(  780): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
V/BackupManagerService(  780): removePackageParticipantsLocked: uid=10179 #1
D/dalvikvm(  780): GC_EXPLICIT freed 881K, 59% free 23630K/56740K, paused 5ms+21ms, total 231ms
W/Resources(  780): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/PackageManager(  780): delete sourFile : 
D/PackageManager(  780): delete native library directory: 
D/PackageManager(  780): return delete result to caller: 1135572864
D/AndroidRuntime( 5120): Shutting down VM
D/dalvikvm( 5120): GC_CONCURRENT freed 96K, 14% free 670K/772K, paused 0ms+0ms, total 3ms
D/PackageManager(  780): returnCode: 1
W/Resources(  780): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  780): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
I/PackageManager(  780):   Action: "android.intent.action.SENDTO"
I/PackageManager(  780):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  780):   Scheme: "sms"
I/PackageManager(  780): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
I/PackageManager(  780):   Action: "android.intent.action.SENDTO"
I/PackageManager(  780):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  780):   Scheme: "smsto"
I/PackageManager(  780): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
W/ActivityManager(  780): Permission Denial: getCurrentUser() from pid=5165, uid=10021 requires android.permission.INTERACT_ACROSS_USERS
I/PackageManager(  780):   Action: "android.intent.action.SENDTO"
I/PackageManager(  780):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  780):   Scheme: "mms"
I/PackageManager(  780): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
I/PackageManager(  780):   Action: "android.intent.action.SENDTO"
I/PackageManager(  780):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  780):   Scheme: "mmsto"
I/PackageManager(  780): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
W/Resources(  780): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
I/PCWCLIENTTRACE_PushUtil( 4435): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 4435): sales region : global
I/PCWCLIENTTRACE_PushUtil( 4435): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver( 4435): [onReceive] - android.intent.action.PACKAGE_REMOVED
W/Resources(  780): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
E/SMD     (  240): DCD OFF
W/Resources(  780): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  780): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  780): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
I/SA      ( 4622): [SUR] onReceive log=[SA = 2.0.0117 V = 19 HWD = 1280X720 2.0 dpi = 320  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = kmini3g P = kmini3gxx I = KOT49H M = SM-G800H OKLEFT false DIS KOT49H.G800HXXU1ANK2 PSS = 4.497045606779314  ]
I/SA      ( 4622): [SUR] onReceive Intent=[ action_PACKAGE_REMOVED package ]
I/ActivityManager(  780): Killing 3978:com.sec.android.app.videoplayer/u0a52 (adj 15): empty #43
W/Resources(  780): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  780): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
W/Resources(  780): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  780): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  780): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
W/Resources(  780): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  780): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  780): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
I/IcingCorporaProvider( 2112): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
I/CrashAnrDetector(  780): onPackageRemoved : com.test.thalitest
D/UsbSettingsManager(  780): clearDefaults: com.test.thalitest
I/SELinux ( 5185): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5185):  
I/SELinux ( 5185): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5185):  
I/SELinux ( 5185):  
I/SELinux ( 5185): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 5185): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 5185): >>>>> Normal User
E/dalvikvm( 5185): >>>>> com.samsung.android.intelligenceservice [ userId:0 | appId:10005 ]
E/SELinux ( 5185): [DEBUG] seapp_context_lookup: seinfoCategory = platform
D/TimaKeyStoreProvider( 5185): in addTimaSignatureService
D/TimaKeyStoreProvider( 5185): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 5185): Added TimaKesytore provider
E/SQLiteLog( 2112): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
E/IcingCorporaProvider( 2112): Exception thrown from notifyTableChanged
E/IcingCorporaProvider( 2112): java.lang.RuntimeException: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/IcingCorporaProvider( 2112): 	at apg.a(PG:301)
E/IcingCorporaProvider( 2112): 	at apg.c(PG:222)
E/IcingCorporaProvider( 2112): 	at clo.b(PG:660)
E/IcingCorporaProvider( 2112): 	at clo.a(PG:651)
E/IcingCorporaProvider( 2112): 	at clo.g(PG:597)
E/IcingCorporaProvider( 2112): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider.update(PG:301)
E/IcingCorporaProvider( 2112): 	at android.content.ContentProvider$Transport.update(ContentProvider.java:287)
E/IcingCorporaProvider( 2112): 	at android.content.ContentResolver.update(ContentResolver.java:1327)
E/IcingCorporaProvider( 2112): 	at clp.Rl(PG:910)
E/IcingCorporaProvider( 2112): 	at clr.tL(PG:827)
E/IcingCorporaProvider( 2112): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateCorporaService.a(PG:1271)
E/IcingCorporaProvider( 2112): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateCorporaService.onHandleIntent(PG:1204)
E/IcingCorporaProvider( 2112): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/IcingCorporaProvider( 2112): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/IcingCorporaProvider( 2112): 	at android.os.Looper.loop(Looper.java:146)
E/IcingCorporaProvider( 2112): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/IcingCorporaProvider( 2112): Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/IcingCorporaProvider( 2112): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/IcingCorporaProvider( 2112): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:745)
E/IcingCorporaProvider( 2112): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/IcingCorporaProvider( 2112): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/IcingCorporaProvider( 2112): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:507)
E/IcingCorporaProvider( 2112): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:418)
E/IcingCorporaProvider( 2112): 	at apa.a(PG:382)
E/IcingCorporaProvider( 2112): 	at apg.i(PG:325)
E/IcingCorporaProvider( 2112): 	at aph.call(PG:215)
E/IcingCorporaProvider( 2112): 	at apg.a(PG:299)
E/IcingCorporaProvider( 2112): 	... 15 more
W/IcingCorporaProvider( 2112): notifyTableChanged failed.
W/IcingCorporaProvider( 2112): Table change notification failed for TableStorageSpec[applications]
I/IcingCorporaProvider( 2112): UpdateCorporaTask done [took 133 ms] updated apps [took 133 ms] 
D/InputReader(  780): Processing first event
D/UserAnalysis.PlaceProvider( 5185): Create SecureDbHelper
I/EventHub(  780): Removing device sec_touchscreen due to epoll hang-up event.
I/EventHub(  780): Removed device: path=/dev/input/event1 name=sec_touchscreen id=6 fd=215 classes=0x94
D/UserAnalysis.UserAnalysisBroadcastReceiver( 5185): Create SecureDbHelper
W/ActivityManager(  780): Permission Denial: getCurrentUser() from pid=5185, uid=10005 requires android.permission.INTERACT_ACROSS_USERS
I/InputReader(  780): Device removed: id=6, name='sec_touchscreen', sources=0x80001002
D/InputReader(  780): Could not retrieve current multitouch slot index.  status=-1
D/InputReader(  780): MultiTouchMotionAccumulator: initial slot number is -1
I/EventHub(  780): Removing device '/dev/input/event1' due to inotify event
I/ActivityManager(  780): Config changes=8 {0 1.0 ?mcc?mnc en_US ldltr sw360dp w360dp h615dp 320dpi nrml long port -touch -keyb/v/h -nav/h s.6}
D/InputDispatcher(  780): setInputDispatchMode: enabled=0, frozen=1
I/SurfaceFlinger(  249): id=19 createSurf (720x1280),2 flag=404, TcreenshotS
D/Mms/MmsApp( 3784): [start]    onConfigurationChanged(),newConfig={0 1.0 ?mcc?mnc en_US ldltr sw360dp w360dp h615dp 320dpi nrml long port -touch -keyb/v/h -nav/h s.6}
D/Mms/MmsApp( 3784): [end]    onConfigurationChanged(),newConfig={0 1.0 ?mcc?mnc en_US ldltr sw360dp w360dp h615dp 320dpi nrml long port -touch -keyb/v/h -nav/h s.6}
D/PermissionCache(  249): checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (323 us)
D/PhoneStatusBar( 1065): mSettingsPanelGravity = 55
D/PhoneStatusBarView( 1065): marqueeStatusBar:123, mClearCover:0
D/MenuAppsGridFragment( 1257): onDestroyView
W/Launcher.MenuAppsGrid( 1257): Trying to exit a state that hasn't been entered
D/KeyguardUpdateMonitor( 1065): sendKeyguardVisibilityChanged(true)
I/SurfaceFlinger(  249): id=18 Removed CatteryCove (8/13)
I/SurfaceFlinger(  249): id=18 Removed CatteryCove (-2/13)
E/Tethering(  780): No numeric data
D/KeyguardUpdateMonitor( 1065): sendKeyguardVisibilityChanged(true)
E/SmartFaceService(  780): onReceive: android.intent.action.CONFIGURATION_CHANGED
E/SmartFaceService(  780): mFolderCoverOpened: (true, true) -> true
D/KeyguardUpdateMonitor( 1065): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1065): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1065): handleKeyguardVisibilityChanged(1)
D/KeyguardHostView( 1065): onSaveInstanceState, tstate=1
D/KeyguardGuestSelectorView( 1065): onDetachedFromWindow()
V/KeyguardUpdateMonitor( 1065): *** unregister callback for com.android.keyguard.CarrierText$1@425f5b50
D/KeyguardUpdateMonitor( 1065): sendKeyguardVisibilityChanged(true)
V/KeyguardUpdateMonitor( 1065): *** unregister callback for com.android.keyguard.MSimCarrierText$1@425f5bb8
V/KeyguardUpdateMonitor( 1065): *** unregister callback for com.android.keyguard.CarrierText$1@425567c0
V/KeyguardUpdateMonitor( 1065): *** unregister callback for com.android.keyguard.EmergencyButton$1@425dab98
V/KeyguardUpdateMonitor( 1065): *** unregister callback for com.android.keyguard.sec.KeyguardSecurityViewOverlay$1@425667e0
D/STATUSBAR-IconMerger( 1065): checkOverflow(384), More:false, Req:false Child:2
V/KeyguardUpdateMonitor( 1065): *** unregister callback for com.android.keyguard.KeyguardHostView$2@425969d0
E/KeyguardHostView( 1065): KeyguardHostView()
D/ContextualEventManager( 1065): setOnClickHandler()
V/KeyguardHostView( 1065): mIsMultipleLockOn is false
D/KeyguardHostView( 1065): mIsVoiceUnlockOn=false
V/KeyguardHostView( 1065): Initial transport state: 1, pbstate=0
I/KeyguardEffectViewMain( 1065): *** KeyguardEffectView getInstance ***
D/LockPatternUtils( 1065): isPcwEnable = null
D/ContextualEventContainer( 1065): ContextualEventContainer()
V/KeyguardUpdateMonitor( 1065): *** register callback for com.android.keyguard.KeyguardMessageArea$2@42cce5b8
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
V/KeyguardUpdateMonitor( 1065): *** register callback for com.android.keyguard.KeyguardHostView$2@42cc8348
V/KeyguardUpdateMonitor( 1065): *** unregister callback for null
V/KeyguardHostView( 1065): music state changed: 0
D/KeyguardProperties( 1065): isIgnoreNationalRoaming() = false
D/VisualEffectCircleUnlockEffect( 1065): KeyguardEffectViewNone : Constructor
D/VisualEffectCircleUnlockEffect( 1065): screenWidth : 720
D/VisualEffectCircleUnlockEffect( 1065): screenHeight : 1280
D/VisualEffectCircleUnlockEffect( 1065): ratio : 0.6666667
D/VisualEffectCircleUnlockEffect( 1065): Constructor
D/VisualEffectCircleUnlockEffect( 1065): arrowImageId = 2130837796
D/VisualEffectCircleUnlockEffect( 1065): circleUnlockMaxWidth = 576
D/VisualEffectCircleUnlockEffect( 1065): circleUnlockMinWidth = 172
D/VisualEffectCircleUnlockEffect( 1065): outerStrokeWidth = 2
D/VisualEffectCircleUnlockEffect( 1065): innerStrokeWidth = 4
D/VisualEffectCircleUnlockEffect( 1065): lockSequenceTotal = 30
V/KeyguardUpdateMonitor( 1065): *** register callback for com.android.keyguard.sec.KeyguardSecurityViewOverlay$1@42cd2da0
V/KeyguardUpdateMonitor( 1065): *** unregister callback for null
V/KeyguardUpdateMonitor( 1065): *** register callback for com.android.keyguard.MSimCarrierText$1@42ce0960
V/KeyguardUpdateMonitor( 1065): *** unregister callback for null
D/MSimCarrierText( 1065):  onRefreshCarrierInfo:: PLMN : nullSPN:null SUB: 0
D/CarrierText( 1065): getCarrierTextForSimState: status = Normal
D/CarrierText( 1065): getCarrierTextForSimState: status = Normal
D/MSimCarrierText( 1065): updateCarrierText: text = 
D/CarrierText( 1065): getCarrierTextForSimState: status = SimNotReady
D/CarrierText( 1065): getCarrierTextForSimState: status = Normal
D/MSimCarrierText( 1065): updateCarrierText: text = 
D/MSimCarrierText( 1065):  onRefreshCarrierInfo:: PLMN : nullSPN:null SUB: 1
D/CarrierText( 1065): getCarrierTextForSimState: status = SimNotReady
D/CarrierText( 1065): getCarrierTextForSimState: status = Normal
D/MSimCarrierText( 1065): updateCarrierText: text = 
D/CarrierText( 1065): getCarrierTextForSimState: status = SimNotReady
D/CarrierText( 1065): getCarrierTextForSimState: status = SimNotReady
D/MSimCarrierText( 1065): updateCarrierText: text = null
V/KeyguardUpdateMonitor( 1065): *** register callback for com.android.keyguard.EmergencyButton$1@42cde010
V/KeyguardUpdateMonitor( 1065): *** unregister callback for null
D/LockPatternUtils( 1065): isPcwEnable = null
D/EmergencyButton( 1065): enabled = false, :0
D/SecCameraShortcut( 1065): setCallback(): not null
D/SecuritySelectorView( 1065): hideBouncer mBouncerHelpText != null
D/KeyguardViewManager( 1065): mWindowLayoutParams not null
D/KeyguardHostView( 1065): onRestoreInstanceState, transport=1
D/VisualEffectParticleEffect( 1065): onConfigurationChanged
D/VisualEffectParticleEffect( 1065): resetOrientation
D/VisualEffectParticleEffect( 1065): stage : 720.0 x 1280.0
D/STATUSBAR-QuickSettingPanel( 1065): setSingleLine:true
D/STATUSBAR-QuickSettingPanel( 1065): updateButtonInfo mButtonWidth : 144 mColumnNumber:5 orien: 1
D/STATUSBAR-QuickSettingPanel( 1065): onConfigurationChanged - dynamicallyReduceTextSize
D/STATUSBAR-QuickSettingButton( 1065): dynamicallyReduceTextSize: 144
D/STATUSBAR-QuickSettingButton( 1065): dynamicallyReduceTextSize: 144
D/STATUSBAR-QuickSettingButton( 1065): dynamicallyReduceTextSize: 144
D/STATUSBAR-QuickSettingButton( 1065): dynamicallyReduceTextSize: 144
D/STATUSBAR-QuickSettingButton( 1065): dynamicallyReduceTextSize: 144
D/STATUSBAR-QuickSettingButton( 1065): dynamicallyReduceTextSize: 144
D/STATUSBAR-QuickSettingButton( 1065): dynamicallyReduceTextSize: 144
D/STATUSBAR-QuickSettingButton( 1065): dynamicallyReduceTextSize: 144
D/STATUSBAR-QuickSettingButton( 1065): dynamicallyReduceTextSize: 144
D/STATUSBAR-QuickSettingButton( 1065): dynamicallyReduceTextSize: 144
D/STATUSBAR-QuickSettingButton( 1065): dynamicallyReduceTextSize: 144
D/STATUSBAR-QuickSettingButton( 1065): dynamicallyReduceTextSize: 144
D/STATUSBAR-QuickSettingButton( 1065): dynamicallyReduceTextSize: 144
D/STATUSBAR-QuickSettingButton( 1065): dynamicallyReduceTextSize: 144
D/STATUSBAR-QuickSettingButton( 1065): dynamicallyReduceTextSize: 144
D/STATUSBAR-QuickSettingButton( 1065): dynamicallyReduceTextSize: 144
D/STATUSBAR-QuickSettingButton( 1065): dynamicallyReduceTextSize: 144
D/STATUSBAR-NetworkController_dual( 1065): onReceive() - ACTION_CONFIGURATION_CHANGED
D/StatusBar.NetworkController_dual( 1065): mMobileLabelViews start
D/StatusBar.NetworkController_dual( 1065): mMobileLabelViews set mobileLabel[SIM_0] =No service.
D/StatusBar.NetworkController_dual( 1065): mMobileLabelViews GONE
D/StatusBar.NetworkController_dual( 1065): mMobileLabelViews2 set mobileLabel[SIM_1] =No service.
D/StatusBar.NetworkController_dual( 1065): mMobileLabelViews2 GONE
D/StatusBar.NetworkController_dual( 1065): mSingleMobileLabelViews set : simMode = 0
D/KeyguardUpdateMonitor( 1065): handleKeyguardVisibilityChanged(1)
D/KeyguardUpdateMonitor( 1065): handleKeyguardVisibilityChanged(1)
D/KeyguardUpdateMonitor( 1065): handleKeyguardVisibilityChanged(1)
D/StatusBar.NetworkController_dual( 1065): mSingleMobileLabelViews set as slot1`s

```
