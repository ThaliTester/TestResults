#### Test 564496604206eac_thali05_samsung-SM-G800H Logs


```
--------- beginning of /dev/log/system
W/ActivityManager(  766): Permission Denial: getCurrentUser() from pid=4461, uid=10035 requires android.permission.INTERACT_ACROSS_USERS
--------- beginning of /dev/log/main
W/ContextImpl( 4461): Implicit intents with startService are not safe: Intent { act=com.sec.android.service.health.cp.accesscontrol } android.content.ContextWrapper.bindService:529 com.samsung.android.sdk.health.content.ShealthAccessControl.startService:274 com.samsung.android.sdk.health.content.ShealthAccessControl.requestPermission:212 
,I/SELinux ( 4483): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 4483):  
E/Device Type Shared Preferences( 4461): Device Type Shared Preferences - getDeviceTypeChecked -true
E/Device Type Shared Preferences( 4461): Device Type Shared Preferences - not connecting to service
E/com.sec.android.app.shealth.SHealthApplication( 4461): ContentProvider is not null
I/SELinux ( 4483): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 4483):  
I/SELinux ( 4483):  
I/SELinux ( 4483): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 4483): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 4483): >>>>> Normal User
E/dalvikvm( 4483): >>>>> com.sec.android.service.health [ userId:0 | appId:10016 ]
E/SELinux ( 4483): [DEBUG] seapp_context_lookup: seinfoCategory = platform
D/TimaKeyStoreProvider( 4483): in addTimaSignatureService
D/TimaKeyStoreProvider( 4483): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 4483): Added TimaKesytore provider
V/MediaPlayer( 4461): decode(61, 33979084, 48105)
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
V/AudioCache(  254): notify(0xb720dc80, 8, 0, 0)
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
V/AudioCache(  254): notify(0xb720dc80, 200, 973, 0)
V/AudioCache(  254): ignored
V/AwesomePlayer(  254): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  254): notify(0xb720dc80, 5, 0, 0)
V/AudioCache(  254): ignored
V/AwesomePlayer(  254): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  254): notify(0xb720dc80, 1, 0, 0)
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
V/AudioCache(  254): notify(0xb720dc80, 6, 0, 0)
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
V/AudioCache(  254): notify(0xb720dc80, 2, 0, 0)
V/AudioCache(  254): playback complete - thread will wake up later
V/AwesomePlayer(  254): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  254): notify(0xb720dc80, 7, 0, 0)
V/AudioCache(  254): ignored
V/AwesomePlayer(  254): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer(  254): addBatteryData
V/AudioCache(  254): wait - success
V/StagefrightPlayer(  254): reset
V/AwesomePlayer(  254): reset_l()
V/AwesomePlayer(  254): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  254): notify(0xb720dc80, 8, 0, 0)
V/AudioCache(  254): ignored
V/AwesomePlayer(  254): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  254): mAudioTrackVector clear
I/OMXCodec(  254): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec(  254): [OMX.google.vorbis.decoder] stop() sendCommand(0x37, OMX_CommandStateSet, OMX_StateIdle)
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
V/MediaPlayer( 4461): decode(62, 33914984, 10421)
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
V/AudioCache(  254): notify(0xb7204138, 8, 0, 0)
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
V/AudioCache(  254): notify(0xb7204138, 200, 973, 0)
V/AudioCache(  254): ignored
V/AwesomePlayer(  254): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  254): notify(0xb7204138, 5, 0, 0)
V/AudioCache(  254): ignored
V/AwesomePlayer(  254): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  254): notify(0xb7204138, 1, 0, 0)
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
V/AudioCache(  254): notify(0xb7204138, 6, 0, 0)
V/AudioCache(  254): ignored
V/AwesomePlayer(  254): addBatteryData
V/MediaPlayerService(  254): wait for playback complete
I/OMXCodec(  254): [OMX.google.vorbis.decoder] End Of Stream
V/AwesomePlayer(  254): postAudioEOS delayUs (0)
W/ActivityManager(  766): Permission Denial: getCurrentUser() from pid=4483, uid=10016 requires android.permission.INTERACT_ACROSS_USERS
V/AwesomePlayer(  254): onCheckAudioStatus
V/AwesomePlayer(  254): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  254): onStreamDone
V/AwesomePlayer(  254): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  254): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  254): notify(0xb7204138, 2, 0, 0)
V/AudioCache(  254): playback complete - thread will wake up later
V/AwesomePlayer(  254): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  254): notify(0xb7204138, 7, 0, 0)
V/AudioCache(  254): ignored
V/AwesomePlayer(  254): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer(  254): addBatteryData
V/AudioCache(  254): wait - success
V/StagefrightPlayer(  254): reset
V/AwesomePlayer(  254): reset_l()
V/AwesomePlayer(  254): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  254): notify(0xb7204138, 8, 0, 0)
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
V/MediaPlayer( 4461): decode(63, 37457308, 34198)
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
V/AudioCache(  254): notify(0xb71ffed8, 8, 0, 0)
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
V/AudioCache(  254): notify(0xb71ffed8, 200, 973, 0)
V/AudioCache(  254): ignored
V/AwesomePlayer(  254): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  254): notify(0xb71ffed8, 5, 0, 0)
V/AudioCache(  254): ignored
V/AwesomePlayer(  254): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  254): notify(0xb71ffed8, 1, 0, 0)
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
V/AudioCache(  254): notify(0xb71ffed8, 6, 0, 0)
V/AudioCache(  254): ignored
V/AwesomePlayer(  254): addBatteryData
V/MediaPlayerService(  254): wait for playback complete
I/AudioPlayer(  254): First fillBuffer call!!
D/dalvikvm( 4483): No JNI_OnLoad found in /system/lib/libsecure_storage_jni.so 0x42665cb0, skipping init
I/SecureStorage( 4483): [INFO]: SPID(0x00000000)Checking if this device supports Secure Storage
I/SecureStorage( 4483): [INFO]: SPID(0x00000000)This device supports Secure Storage
I/SecureStorage(  378): [INFO]: SPID(0x00000003)Credentials: uid 10016, gid 10016, pid 4483
I/SecureStorage(  378): [INFO]: SPID(0x00000003)Received function mask & code: 0000010C
I/SecureStorage( 4483): [INFO]: SPID(0x00000000)SS Daemon is running
I/OMXCodec(  254): [OMX.google.vorbis.decoder] End Of Stream
V/AwesomePlayer(  254): postAudioEOS delayUs (0)
I/SecureStorage( 4483): [INFO]: SPID(0x00000000)Processing data
I/SecureStorage(  378): [INFO]: SPID(0x00000003)Credentials: uid 10016, gid 10016, pid 4483
I/SecureStorage(  378): [INFO]: SPID(0x00000003)Received function mask & code: 00000106
V/AwesomePlayer(  254): onCheckAudioStatus
V/AwesomePlayer(  254): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  254): onStreamDone
V/AwesomePlayer(  254): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  254): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  254): notify(0xb71ffed8, 2, 0, 0)
V/AudioCache(  254): playback complete - thread will wake up later
V/AwesomePlayer(  254): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  254): notify(0xb71ffed8, 7, 0, 0)
V/AudioCache(  254): ignored
V/AwesomePlayer(  254): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer(  254): addBatteryData
V/AudioCache(  254): wait - success
V/StagefrightPlayer(  254): reset
V/AwesomePlayer(  254): reset_l()
V/AwesomePlayer(  254): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  254): notify(0xb71ffed8, 8, 0, 0)
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
V/MediaPlayer( 4461): decode(65, 33862452, 7405)
V/MediaPlayerService(  254): decode(35, 33862452, 7405)
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
V/StagefrightPlayer(  254): setDataSource(35, 33862452, 7405)
V/AwesomePlayer(  254): reset_l()
V/AwesomePlayer(  254): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  254): notify(0xb71f1760, 8, 0, 0)
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
V/AudioCache(  254): notify(0xb71f1760, 200, 973, 0)
V/AudioCache(  254): ignored
V/AwesomePlayer(  254): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  254): notify(0xb71f1760, 5, 0, 0)
V/AudioCache(  254): ignored
V/AwesomePlayer(  254): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  254): notify(0xb71f1760, 1, 0, 0)
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
V/AudioCache(  254): notify(0xb71f1760, 6, 0, 0)
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
V/AudioCache(  254): notify(0xb71f1760, 2, 0, 0)
V/AudioCache(  254): playback complete - thread will wake up later
V/AwesomePlayer(  254): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  254): notify(0xb71f1760, 7, 0, 0)
V/AudioCache(  254): ignored
V/AwesomePlayer(  254): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer(  254): addBatteryData
V/AudioCache(  254): wait - success
V/StagefrightPlayer(  254): reset
V/AwesomePlayer(  254): reset_l()
V/AwesomePlayer(  254): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  254): notify(0xb71f1760, 8, 0, 0)
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
V/MediaPlayer( 4461): decode(66, 37547940, 5555)
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
V/AudioCache(  254): notify(0xb71f1ad8, 8, 0, 0)
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
V/AudioCache(  254): notify(0xb71f1ad8, 200, 973, 0)
V/AudioCache(  254): ignored
V/AwesomePlayer(  254): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  254): notify(0xb71f1ad8, 5, 0, 0)
V/AudioCache(  254): ignored
V/AwesomePlayer(  254): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  254): notify(0xb71f1ad8, 1, 0, 0)
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
V/AudioCache(  254): notify(0xb71f1ad8, 6, 0, 0)
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
V/AudioCache(  254): notify(0xb71f1ad8, 2, 0, 0)
V/AudioCache(  254): playback complete - thread will wake up later
V/AwesomePlayer(  254): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  254): notify(0xb71f1ad8, 7, 0, 0)
V/AudioCache(  254): ignored
V/AwesomePlayer(  254): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer(  254): addBatteryData
V/AudioCache(  254): wait - success
V/StagefrightPlayer(  254): reset
V/AwesomePlayer(  254): reset_l()
V/AwesomePlayer(  254): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  254): notify(0xb71f1ad8, 8, 0, 0)
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
V/MediaPlayer( 4461): decode(67, 30367732, 5085)
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
V/AudioCache(  254): notify(0xb720a558, 8, 0, 0)
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
V/AudioCache(  254): notify(0xb720a558, 200, 973, 0)
V/AudioCache(  254): ignored
V/AwesomePlayer(  254): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  254): notify(0xb720a558, 5, 0, 0)
V/AudioCache(  254): ignored
V/AwesomePlayer(  254): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  254): notify(0xb720a558, 1, 0, 0)
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
V/AudioCache(  254): notify(0xb720a558, 6, 0, 0)
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
V/AudioCache(  254): notify(0xb720a558, 2, 0, 0)
V/AudioCache(  254): playback complete - thread will wake up later
V/AwesomePlayer(  254): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  254): notify(0xb720a558, 7, 0, 0)
V/AudioCache(  254): ignored
V/AwesomePlayer(  254): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer(  254): addBatteryData
V/AudioCache(  254): wait - success
V/StagefrightPlayer(  254): reset
V/AwesomePlayer(  254): reset_l()
V/AwesomePlayer(  254): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  254): notify(0xb720a558, 8, 0, 0)
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
V/MediaPlayer( 4461): decode(68, 30372876, 21552)
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
V/AudioCache(  254): notify(0xb71f42b8, 8, 0, 0)
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
V/AudioCache(  254): notify(0xb71f42b8, 200, 973, 0)
V/AudioCache(  254): ignored
V/AwesomePlayer(  254): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  254): notify(0xb71f42b8, 5, 0, 0)
V/AudioCache(  254): ignored
V/AwesomePlayer(  254): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  254): notify(0xb71f42b8, 1, 0, 0)
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
V/AudioCache(  254): notify(0xb71f42b8, 6, 0, 0)
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
V/AudioCache(  254): notify(0xb71f42b8, 2, 0, 0)
V/AudioCache(  254): playback complete - thread will wake up later
V/AwesomePlayer(  254): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  254): notify(0xb71f42b8, 7, 0, 0)
V/AudioCache(  254): ignored
V/AwesomePlayer(  254): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer(  254): addBatteryData
V/AudioCache(  254): wait - success
V/StagefrightPlayer(  254): reset
V/AwesomePlayer(  254): reset_l()
V/AwesomePlayer(  254): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  254): notify(0xb71f42b8, 8, 0, 0)
V/AudioCache(  254): ignored
V/AwesomePlayer(  254): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  254): mAudioTrackVector clear
I/OMXCodec(  254): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec(  254): [OMX.google.vorbis.decoder] stop() sendCommand(0x3d, OMX_CommandStateSet, OMX_StateIdle)
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
V/MediaPlayer( 4461): decode(69, 37543652, 4230)
V/MediaPlayerService(  254): decode(35, 37543652, 4230)
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
V/StagefrightPlayer(  254): setDataSource(35, 37543652, 4230)
V/AwesomePlayer(  254): reset_l()
V/AwesomePlayer(  254): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  254): notify(0xb71f1ad8, 8, 0, 0)
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
V/AudioCache(  254): notify(0xb71f1ad8, 200, 973, 0)
V/AudioCache(  254): ignored
V/AwesomePlayer(  254): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  254): notify(0xb71f1ad8, 5, 0, 0)
V/AudioCache(  254): ignored
V/AwesomePlayer(  254): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  254): notify(0xb71f1ad8, 1, 0, 0)
V/AudioCache(  254): prepared
V/AudioCache(  254): wait - success
V/MediaPlayerService(  254): start
V/StagefrightPlayer(  254): start
V/AwesomePlayer(  254): play
V/AwesomePlayer(  254): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer(  254): startAudioPlayer_l, sendErrorNotification (0)
D/AndroidRuntime( 4494): 
D/AndroidRuntime( 4494): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 4494): CheckJNI is OFF
I/OMXCodec(  254): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec(  254): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec(  254): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
D/AndroidRuntime( 4494): setted country_code = Poland
D/AndroidRuntime( 4494): setted countryiso_code = PL
I/OMXCodec(  254): [OMX.google.vorbis.decoder] End Of Stream
I/AudioPlayer(  254):  Audioplayer kKeyAudioPCMFormat:1, 1, 0
I/AudioPlayer(  254):  Audioplayer kKeyAudioPCMFormat read fail(1, 1)
V/AudioCache(  254): open(44100, 1, 0x0, 1, 4)
D/AndroidRuntime( 4494): setted sales_code = XEO
D/AndroidRuntime( 4494): readGMSProperty: start
D/AndroidRuntime( 4494): readGMSProperty: already setted!!
D/AndroidRuntime( 4494): readGMSProperty: end
V/AwesomePlayer(  254): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
D/AndroidRuntime( 4494): addProductProperty: start
V/AudioCache(  254): notify(0xb71f1ad8, 6, 0, 0)
V/AudioCache(  254): ignored
V/AwesomePlayer(  254): addBatteryData
V/MediaPlayerService(  254): wait for playback complete
V/AwesomePlayer(  254): postAudioEOS delayUs (0)
V/AwesomePlayer(  254): onCheckAudioStatus
V/AwesomePlayer(  254): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  254): onStreamDone
V/AwesomePlayer(  254): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  254): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  254): notify(0xb71f1ad8, 2, 0, 0)
V/AudioCache(  254): playback complete - thread will wake up later
V/AwesomePlayer(  254): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  254): notify(0xb71f1ad8, 7, 0, 0)
V/AudioCache(  254): ignored
V/AwesomePlayer(  254): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer(  254): addBatteryData
V/AudioCache(  254): wait - success
V/StagefrightPlayer(  254): reset
V/AwesomePlayer(  254): reset_l()
V/AwesomePlayer(  254): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  254): notify(0xb71f1ad8, 8, 0, 0)
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
,V/AwesomePlayer(  254): mAudioTrackVector clear
V/AwesomePlayer(  254): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  254): mSecMediaClock clear
V/AwesomePlayer(  254): destructor
V/AwesomePlayer(  254): reset_l()
V/AwesomePlayer(  254): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  254): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  254): mAudioTrackVector clear
V/AwesomePlayer(  254): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  254): mSecMediaClock clear
V/MediaPlayer( 4461): decode(70, 30337076, 9400)
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
V/AudioCache(  254): notify(0xb71fb2d0, 8, 0, 0)
V/AudioCache(  254): ignored
V/AwesomePlayer(  254): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  254): mAudioTrackVector clear
V/AwesomePlayer(  254): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  254): mSecMediaClock clear
D/dalvikvm( 4494): Trying to load lib libjavacore.so 0x0
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
D/dalvikvm( 4494): Added shared lib libjavacore.so 0x0
I/OMX     (  254): mDispatchers.add
I/OMXCodec(  254): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec(  254): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec(  254): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec(  254): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/OMXCodec(  254): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer(  254): finishAsyncPrepare_l
V/AwesomePlayer(  254): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache(  254): notify(0xb71fb2d0, 200, 973, 0)
V/AudioCache(  254): ignored
V/AwesomePlayer(  254): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  254): notify(0xb71fb2d0, 5, 0, 0)
V/AudioCache(  254): ignored
V/AwesomePlayer(  254): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  254): notify(0xb71fb2d0, 1, 0, 0)
V/AudioCache(  254): prepared
V/AudioCache(  254): wait - success
V/MediaPlayerService(  254): start
V/StagefrightPlayer(  254): start
V/AwesomePlayer(  254): play
V/AwesomePlayer(  254): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer(  254): startAudioPlayer_l, sendErrorNotification (0)
D/dalvikvm( 4494): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 4494): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 4494): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
I/OMXCodec(  254): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec(  254): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec(  254): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/AudioPlayer(  254):  Audioplayer kKeyAudioPCMFormat:1, 1, 0
I/AudioPlayer(  254):  Audioplayer kKeyAudioPCMFormat read fail(1, 1)
V/AudioCache(  254): open(44100, 1, 0x0, 1, 4)
V/AwesomePlayer(  254): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache(  254): notify(0xb71fb2d0, 6, 0, 0)
V/AudioCache(  254): ignored
V/AwesomePlayer(  254): addBatteryData
V/MediaPlayerService(  254): wait for playback complete
I/SELinux ( 4543): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 4543):  
I/OMXCodec(  254): [OMX.google.vorbis.decoder] End Of Stream
V/AwesomePlayer(  254): postAudioEOS delayUs (0)
V/AwesomePlayer(  254): onCheckAudioStatus
V/AwesomePlayer(  254): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  254): onStreamDone
V/AwesomePlayer(  254): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  254): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  254): notify(0xb71fb2d0, 2, 0, 0)
V/AudioCache(  254): playback complete - thread will wake up later
V/AwesomePlayer(  254): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  254): notify(0xb71fb2d0, 7, 0, 0)
V/AudioCache(  254): ignored
V/AwesomePlayer(  254): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer(  254): addBatteryData
V/AudioCache(  254): wait - success
V/StagefrightPlayer(  254): reset
V/AwesomePlayer(  254): reset_l()
V/AwesomePlayer(  254): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  254): notify(0xb71fb2d0, 8, 0, 0)
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
V/MediaPlayer( 4461): decode(71, 33925464, 44276)
V/MediaPlayerService(  254): decode(35, 33925464, 44276)
I/ActivityManager(  766): Killing 3118:com.sec.android.app.mt/1000 (adj 15): empty #43
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
V/StagefrightPlayer(  254): setDataSource(35, 33925464, 44276)
V/AwesomePlayer(  254): reset_l()
V/AwesomePlayer(  254): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  254): notify(0xb71f1ad8, 8, 0, 0)
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
V/AudioCache(  254): notify(0xb71f1ad8, 200, 973, 0)
V/AudioCache(  254): ignored
V/AwesomePlayer(  254): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  254): notify(0xb71f1ad8, 5, 0, 0)
V/AudioCache(  254): ignored
V/AwesomePlayer(  254): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  254): notify(0xb71f1ad8, 1, 0, 0)
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
I/SELinux ( 4543): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 4543):  
I/SELinux ( 4543):  
I/SELinux ( 4543): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 4543): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 4543): >>>>> Normal User
E/dalvikvm( 4543): >>>>> com.policydm [ userId:0 | appId:1000 ]
I/AudioPlayer(  254):  Audioplayer kKeyAudioPCMFormat:1, 2, 0
I/AudioPlayer(  254):  Audioplayer kKeyAudioPCMFormat read fail(2, 1)
V/AudioCache(  254): open(44100, 2, 0x0, 1, 4)
E/SELinux ( 4543): [DEBUG] seapp_context_lookup: seinfoCategory = platform
V/AwesomePlayer(  254): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache(  254): notify(0xb71f1ad8, 6, 0, 0)
V/AudioCache(  254): ignored
V/AwesomePlayer(  254): addBatteryData
V/MediaPlayerService(  254): wait for playback complete
D/TimaKeyStoreProvider( 4543): in addTimaSignatureService
I/OMXCodec(  254): [OMX.google.vorbis.decoder] End Of Stream
V/AwesomePlayer(  254): postAudioEOS delayUs (0)
V/AwesomePlayer(  254): onCheckAudioStatus
V/AwesomePlayer(  254): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  254): onStreamDone
V/AwesomePlayer(  254): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  254): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  254): notify(0xb71f1ad8, 2, 0, 0)
V/AudioCache(  254): playback complete - thread will wake up later
V/AwesomePlayer(  254): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  254): notify(0xb71f1ad8, 7, 0, 0)
V/AudioCache(  254): ignored
V/AwesomePlayer(  254): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer(  254): addBatteryData
V/AudioCache(  254): wait - success
V/StagefrightPlayer(  254): reset
V/AwesomePlayer(  254): reset_l()
V/AwesomePlayer(  254): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  254): notify(0xb71f1ad8, 8, 0, 0)
V/AudioCache(  254): ignored
V/AwesomePlayer(  254): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  254): mAudioTrackVector clear
I/OMXCodec(  254): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec(  254): [OMX.google.vorbis.decoder] stop() sendCommand(0x40, OMX_CommandStateSet, OMX_StateIdle)
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
V/MediaPlayer( 4461): decode(72, 33885672, 29256)
V/MediaPlayerService(  254): decode(35, 33885672, 29256)
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
V/AudioCache(  254): notify(0xb71f1ad8, 8, 0, 0)
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
D/TimaKeyStoreProvider( 4543): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 4543): Added TimaKesytore provider
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
V/AudioCache(  254): notify(0xb71f1ad8, 200, 973, 0)
V/AudioCache(  254): ignored
V/AwesomePlayer(  254): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  254): notify(0xb71f1ad8, 5, 0, 0)
V/AudioCache(  254): ignored
V/AwesomePlayer(  254): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  254): notify(0xb71f1ad8, 1, 0, 0)
V/AudioCache(  254): prepared
V/AudioCache(  254): wait - success
V/MediaPlayerService(  254): start
V/StagefrightPlayer(  254): start
V/AwesomePlayer(  254): play
V/AwesomePlayer(  254): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer(  254): startAudioPlayer_l, sendErrorNotification (0)
E/memtrack( 4494): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 4494): failed to load memtrack module: -2
I/OMXCodec(  254): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec(  254): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec(  254): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/AudioPlayer(  254):  Audioplayer kKeyAudioPCMFormat:1, 2, 0
I/AudioPlayer(  254):  Audioplayer kKeyAudioPCMFormat read fail(2, 1)
V/AudioCache(  254): open(44100, 2, 0x0, 1, 4)
V/AwesomePlayer(  254): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache(  254): notify(0xb71f1ad8, 6, 0, 0)
V/AudioCache(  254): ignored
V/AwesomePlayer(  254): addBatteryData
V/MediaPlayerService(  254): wait for playback complete
I/OMXCodec(  254): [OMX.google.vorbis.decoder] End Of Stream
D/dalvikvm( 4494): Note: class Landroid/app/ActivityManagerNative; has 192 unimplemented (abstract) methods
V/AwesomePlayer(  254): postAudioEOS delayUs (0)
V/AwesomePlayer(  254): onCheckAudioStatus
V/AwesomePlayer(  254): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  254): onStreamDone
V/AwesomePlayer(  254): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  254): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  254): notify(0xb71f1ad8, 2, 0, 0)
V/AudioCache(  254): playback complete - thread will wake up later
V/AwesomePlayer(  254): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  254): notify(0xb71f1ad8, 7, 0, 0)
V/AudioCache(  254): ignored
V/AwesomePlayer(  254): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer(  254): addBatteryData
V/AudioCache(  254): wait - success
V/StagefrightPlayer(  254): reset
V/AwesomePlayer(  254): reset_l()
V/AwesomePlayer(  254): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  254): notify(0xb71f1ad8, 8, 0, 0)
V/AudioCache(  254): ignored
V/AwesomePlayer(  254): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  254): mAudioTrackVector clear
I/OMXCodec(  254): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec(  254): [OMX.google.vorbis.decoder] stop() sendCommand(0x41, OMX_CommandStateSet, OMX_StateIdle)
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
V/MediaPlayer( 4461): decode(73, 37491572, 52024)
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
V/AudioCache(  254): notify(0xb71f3eb0, 8, 0, 0)
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
V/AudioCache(  254): notify(0xb71f3eb0, 200, 973, 0)
V/AudioCache(  254): ignored
V/AwesomePlayer(  254): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  254): notify(0xb71f3eb0, 5, 0, 0)
V/AudioCache(  254): ignored
V/AwesomePlayer(  254): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  254): notify(0xb71f3eb0, 1, 0, 0)
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
V/AudioCache(  254): open(48000, 2, 0x0, 1, 4)
V/AwesomePlayer(  254): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache(  254): notify(0xb71f3eb0, 6, 0, 0)
V/AudioCache(  254): ignored
V/AwesomePlayer(  254): addBatteryData
V/MediaPlayerService(  254): wait for playback complete
D/AndroidRuntime( 4494): Calling main entry com.android.commands.am.Am
I/OMXCodec(  254): [OMX.google.vorbis.decoder] End Of Stream
V/AwesomePlayer(  254): postAudioEOS delayUs (0)
V/AwesomePlayer(  254): onCheckAudioStatus
V/AwesomePlayer(  254): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  254): onStreamDone
V/AwesomePlayer(  254): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  254): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  254): notify(0xb71f3eb0, 2, 0, 0)
V/AudioCache(  254): playback complete - thread will wake up later
V/AwesomePlayer(  254): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  254): notify(0xb71f3eb0, 7, 0, 0)
V/AudioCache(  254): ignored
V/AwesomePlayer(  254): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer(  254): addBatteryData
V/AudioCache(  254): wait - success
V/StagefrightPlayer(  254): reset
V/AwesomePlayer(  254): reset_l()
V/AwesomePlayer(  254): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  254): notify(0xb71f3eb0, 8, 0, 0)
V/AudioCache(  254): ignored
V/AwesomePlayer(  254): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  254): mAudioTrackVector clear
I/OMXCodec(  254): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec(  254): [OMX.google.vorbis.decoder] stop() sendCommand(0x42, OMX_CommandStateSet, OMX_StateIdle)
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
V/MediaPlayer( 4461): decode(74, 33969800, 9226)
V/MediaPlayerService(  254): decode(35, 33969800, 9226)
V/ApplicationPolicy(  766): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
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
V/AudioCache(  254): notify(0xb71f1ad8, 8, 0, 0)
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
V/AudioCache(  254): notify(0xb71f1ad8, 200, 973, 0)
V/AudioCache(  254): ignored
V/AwesomePlayer(  254): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  254): notify(0xb71f1ad8, 5, 0, 0)
V/AudioCache(  254): ignored
V/AwesomePlayer(  254): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  254): notify(0xb71f1ad8, 1, 0, 0)
V/AudioCache(  254): prepared
V/AudioCache(  254): wait - success
V/MediaPlayerService(  254): start
V/StagefrightPlayer(  254): start
V/AwesomePlayer(  254): play
V/AwesomePlayer(  254): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer(  254): startAudioPlayer_l, sendErrorNotification (0)
D/CustomFrequencyManagerService(  766): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 766  pkgName : ACTIVITY_RESUME_BOOSTER@5
W/ActivityManager(  766): mDVFSHelper.acquire()
I/OMXCodec(  254): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec(  254): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec(  254): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/AudioPlayer(  254):  Audioplayer kKeyAudioPCMFormat:1, 2, 0
I/AudioPlayer(  254):  Audioplayer kKeyAudioPCMFormat read fail(2, 1)
V/AudioCache(  254): open(44100, 2, 0x0, 1, 4)
V/AwesomePlayer(  254): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache(  254): notify(0xb71f1ad8, 6, 0, 0)
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
V/AudioCache(  254): notify(0xb71f1ad8, 2, 0, 0)
V/AudioCache(  254): playback complete - thread will wake up later
V/AwesomePlayer(  254): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  254): notify(0xb71f1ad8, 7, 0, 0)
V/AudioCache(  254): ignored
V/AwesomePlayer(  254): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer(  254): addBatteryData
V/AudioCache(  254): wait - success
V/StagefrightPlayer(  254): reset
V/AwesomePlayer(  254): reset_l()
V/AwesomePlayer(  254): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  254): notify(0xb71f1ad8, 8, 0, 0)
V/AudioCache(  254): ignored
V/AwesomePlayer(  254): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  254): mAudioTrackVector clear
I/OMXCodec(  254): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec(  254): [OMX.google.vorbis.decoder] stop() sendCommand(0x43, OMX_CommandStateSet, OMX_StateIdle)
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
V/MediaPlayer( 4461): decode(75, 30402580, 4509)
V/MediaPlayerService(  254): decode(35, 30402580, 4509)
V/MediaPlayerService(  254): player type = 3
V/AwesomePlayer(  254): setDefault
V/AwesomePlayer(  254): constructor
I/SELinux ( 4580): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 4580):  
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
V/AudioCache(  254): notify(0xb71f84f8, 8, 0, 0)
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
V/AudioCache(  254): notify(0xb71f84f8, 200, 973, 0)
V/AudioCache(  254): ignored
V/AwesomePlayer(  254): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  254): notify(0xb71f84f8, 5, 0, 0)
V/AudioCache(  254): ignored
V/AwesomePlayer(  254): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  254): notify(0xb71f84f8, 1, 0, 0)
V/AudioCache(  254): prepared
V/AudioCache(  254): wait - success
V/MediaPlayerService(  254): start
V/StagefrightPlayer(  254): start
D/dalvikvm(  250): GC_EXPLICIT freed 45K, 51% free 9508K/19208K, paused 3ms+2ms, total 31ms
D/LockPatternUtils( 1063): isPcwEnable = null
V/AwesomePlayer(  254): play
V/AwesomePlayer(  254): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer(  254): startAudioPlayer_l, sendErrorNotification (0)
I/SELinux ( 4580): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 4580):  
I/SELinux ( 4580):  
I/SELinux ( 4580): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
I/OMXCodec(  254): [OMX.google.vorbis.decoder] End Of Stream
E/SELinux ( 4580): [DEBUG] seapp_context_lookup: seinfoCategory = default
E/dalvikvm( 4580): >>>>> Normal User
E/dalvikvm( 4580): >>>>> com.test.thalitest [ userId:0 | appId:10179 ]
D/AndroidRuntime( 4494): Shutting down VM
E/SELinux ( 4580): [DEBUG] seapp_context_lookup: seinfoCategory = default
D/dalvikvm( 4494): GC_CONCURRENT freed 97K, 13% free 717K/816K, paused 1ms+1ms, total 3ms
I/OMXCodec(  254): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec(  254): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec(  254): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/AudioPlayer(  254):  Audioplayer kKeyAudioPCMFormat:1, 2, 0
I/AudioPlayer(  254):  Audioplayer kKeyAudioPCMFormat read fail(2, 1)
V/AudioCache(  254): open(44100, 2, 0x0, 1, 4)
V/AwesomePlayer(  254): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache(  254): notify(0xb71f84f8, 6, 0, 0)
V/AudioCache(  254): ignored
V/AwesomePlayer(  254): addBatteryData
V/MediaPlayerService(  254): wait for playback complete
D/dalvikvm(  250): GC_EXPLICIT freed <1K, 51% free 9508K/19208K, paused 2ms+3ms, total 23ms
D/TimaKeyStoreProvider( 4580): in addTimaSignatureService
I/AudioPlayer(  254): First fillBuffer call!!
V/AwesomePlayer(  254): postAudioEOS delayUs (0)
V/AwesomePlayer(  254): onCheckAudioStatus
V/AwesomePlayer(  254): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  254): onStreamDone
V/AwesomePlayer(  254): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  254): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  254): notify(0xb71f84f8, 2, 0, 0)
V/AudioCache(  254): playback complete - thread will wake up later
V/AwesomePlayer(  254): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  254): notify(0xb71f84f8, 7, 0, 0)
V/AudioCache(  254): ignored
V/AwesomePlayer(  254): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer(  254): addBatteryData
V/AudioCache(  254): wait - success
V/StagefrightPlayer(  254): reset
V/AwesomePlayer(  254): reset_l()
V/AwesomePlayer(  254): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  254): notify(0xb71f84f8, 8, 0, 0)
V/AudioCache(  254): ignored
V/AwesomePlayer(  254): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  254): mAudioTrackVector clear
I/OMXCodec(  254): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec(  254): [OMX.google.vorbis.decoder] stop() sendCommand(0x44, OMX_CommandStateSet, OMX_StateIdle)
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
D/TimaKeyStoreProvider( 4580): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 4580): Added TimaKesytore provider
D/dalvikvm(  250): GC_EXPLICIT freed <1K, 51% free 9508K/19208K, paused 1ms+3ms, total 18ms
D/LockPatternUtils( 1063): isPcwEnable = null
I/SurfaceFlinger(  249): id=13 Removed CatteryCove (8/12)
I/SurfaceFlinger(  249): id=13 Removed CatteryCove (-2/12)
D/KeyguardUpdateMonitor( 1063): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1063): handleKeyguardVisibilityChanged(1)
I/SQLiteSecureOpenHelper( 2011): getWritableDatabase(pwd)
I/SQLiteSecureOpenHelper( 2011): getDatabaseLocked(b,b,pwd)...
D/SurfaceWidgetView( 1247): destroyHardwareResources():1126594224
W/ActivityManager(  766): Permission Denial: getCurrentUser() from pid=4580, uid=10179 requires android.permission.INTERACT_ACROSS_USERS
W/ActivityManager(  766): Permission Denial: getCurrentUser() from pid=4580, uid=10179 requires android.permission.INTERACT_ACROSS_USERS
W/ContextImpl(  766): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
I/SELinux ( 4602): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 4602):  
I/ActivityManager(  766): Killing 3180:com.sec.android.app.camera/u0a147 (adj 15): empty #43
V/WebViewChromium( 4580): Binding Chromium to the background looper Looper (main, tid 1) {42340918}
I/chromium( 4580): [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserProcessMain( 4580): Initializing chromium process, renderers=0
,I/SELinux ( 4602): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 4602):  
I/SELinux ( 4602):  
,I/SELinux ( 4602): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 4602): [DEBUG] seapp_context_lookup: seinfoCategory = default
E/dalvikvm( 4602): >>>>> Normal User
,E/dalvikvm( 4602): >>>>> com.osp.app.signin [ userId:0 | appId:10043 ]
,E/SELinux ( 4602): [DEBUG] seapp_context_lookup: seinfoCategory = default
,W/chromium( 4580): [WARNING:proxy_service.cc(888)] PAC support disabled because there is no system implementation
,D/TimaKeyStoreProvider( 4602): in addTimaSignatureService
,D/TimaKeyStoreProvider( 4602): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 4602): Added TimaKesytore provider
,I/SA      ( 4602): [SSP] onCreated
,I/SA      ( 4602): [TPM] There is no property file
,I/SA      ( 4602): [SCU] isHaveSA() - false
,I/SA      ( 4602): [TPM] getModelProperty : null
,I/SA      ( 4602): [TPM] getCSCProperty : null
,I/SA      ( 4602): [PMR] Received action : android.intent.action.PACKAGE_ADDED
,I/SA      ( 4602): [DM] init START
,I/SA      ( 4602): [DM] This device is not a Vodafone
,I/SA      ( 4602): [DM] getCountryCodeFromCSC : PL
I/SA      ( 4602): support phone number id : false
,I/SA      ( 4602): [DM] init END
,I/SA      ( 4602): [SUR] onReceive log=[SA = 2.0.0117 V = 19 HWD = 1280X720 2.0 dpi = 320  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = kmini3g P = kmini3gxx I = KOT49H M = SM-G800H OKLEFT false DIS KOT49H.G800HXXU1ANK2 PSS = 4.497045606779314  ]
,I/SA      ( 4602): [SUR] onReceive Intent=[ action.PACKAGE_ADDED. package ]
I/ActivityManager(  766): Killing 3272:com.samsung.android.provider.shootingmodeprovider/u0a162 (adj 15): empty #43
,D/Mms/PackageInstallReceiver( 3782): loadAuthorityPref(): sEnableAuthority = true
,I/IcingCorporaProvider( 2113): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
W/ContextImpl( 2846): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1857 android.content.ContextWrapper.startService:506 android.content.ContextWrapper.startService:506 com.samsung.android.app.assistantmenu.AssistantMenuReceiver.onReceive:153 android.app.ActivityThread.handleReceiver:2698 
,I/SELinux ( 4632): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 4632):  
,I/IcingCorporaProvider( 2113): UpdateCorporaTask done [took 92 ms] updated apps [took 92 ms] 
,I/SELinux ( 4632): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 4632):  
I/SELinux ( 4632):  
,I/SELinux ( 4632): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 4632): [DEBUG] seapp_context_lookup: seinfoCategory = samsung
E/dalvikvm( 4632): >>>>> Normal User
,E/dalvikvm( 4632): >>>>> com.sec.android.service.cm [ userId:0 | appId:10078 ]
,E/SELinux ( 4632): [DEBUG] seapp_context_lookup: seinfoCategory = samsung
,D/TimaKeyStoreProvider( 4632): in addTimaSignatureService
,D/TimaKeyStoreProvider( 4632): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 4632): Added TimaKesytore provider
,D/CapabilityManagerService New( 4632): Receiver Broadcast:android.intent.action.PACKAGE_ADDED
W/ActivityManager(  766): Permission Denial: getCurrentUser() from pid=4632, uid=10078 requires android.permission.INTERACT_ACROSS_USERS
,I/SELinux ( 4644): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 4644):  
,I/ActivityManager(  766): Killing 3277:com.android.email/u0a155 (adj 15): empty #43
,I/SELinux ( 4644): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 4644):  
I/SELinux ( 4644):  
,I/SELinux ( 4644): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 4644): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 4644): >>>>> Normal User
,E/dalvikvm( 4644): >>>>> com.google.android.apps.docs [ userId:0 | appId:10090 ]
E/SELinux ( 4644): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/SMD     (  240): DCD ON
D/TimaKeyStoreProvider( 4644): in addTimaSignatureService
D/TimaKeyStoreProvider( 4644): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 4644): Added TimaKesytore provider
,I/Adreno-EGL( 4580): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 4580): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 4580): Build Date: 03/21/14 Fri
I/Adreno-EGL( 4580): Local Branch: AU200+patches_03212014
I/Adreno-EGL( 4580): Remote Branch: 
I/Adreno-EGL( 4580): Local Patches: 
I/Adreno-EGL( 4580): Reconstruct Branch: 
,I/SurfaceFlinger(  249): id=7 Removed Mauncher (7/11)
,I/SurfaceFlinger(  249): id=7 Removed Mauncher (-2/11)
V/AlarmManager(  766): waitForAlarm result :4
,I/SecureStorage(  378): [INFO]: SPID(0x00000003)Secure Storage Daemon finished processing with result: 0
,I/SecureStorage(  378): [INFO]: SPID(0x00000003)PID: 4483, TID: 4483
,D/KeyguardUpdateMonitor( 1063): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1063): handleKeyguardVisibilityChanged(1)
,V/AlarmManager(  766): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
D/SurfaceWidgetClient$ISurfaceWidgetStub( 1442): [237392/5] Surface widget visibility changed visibility = false on instance = 1
,D/Launcher( 1247): onTrimMemory. Level: 20
,D/BatteryService(  766): level:100, scale:100, status:5, health:2, present:true, voltage: 4366, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:7, charge type:1, power sharing:false
,D/BatteryService(  766): stay LED for fully charged
,D/BatteryService(  766): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1063): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1063): handleBatteryUpdate
D/UiModeManager(  766): mCoverManager.getCoverState() : true
,I/dalvikvm( 4580): Could not find method android.webkit.CookieManager.setAcceptThirdPartyCookies, referenced from method org.apache.cordova.engine.SystemCookieManager.<init>
W/dalvikvm( 4580): VFY: unable to resolve virtual method 252: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
D/dalvikvm( 4580): VFY: replacing opcode 0x6e at 0x0016
I/dalvikvm( 4580): Could not find method android.webkit.CookieManager.flush, referenced from method org.apache.cordova.engine.SystemCookieManager.flush
W/dalvikvm( 4580): VFY: unable to resolve virtual method 247: Landroid/webkit/CookieManager;.flush ()V
,D/dalvikvm( 4580): VFY: replacing opcode 0x6e at 0x0008
,W/dalvikvm( 4580): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 4580): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
I/dalvikvm( 4580): Could not find method android.webkit.WebViewClient.onReceivedClientCertRequest, referenced from method org.apache.cordova.engine.SystemWebViewClient.onReceivedClientCertRequest
W/dalvikvm( 4580): VFY: unable to resolve virtual method 305: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
,D/dalvikvm( 4580): VFY: replacing opcode 0x6f at 0x001a
,W/dalvikvm( 4580): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
I/dalvikvm( 4580): Could not find method android.webkit.PermissionRequest.getResources, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onPermissionRequest
W/dalvikvm( 4580): VFY: unable to resolve virtual method 263: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
,D/dalvikvm( 4580): VFY: replacing opcode 0x6e at 0x000d
I/dalvikvm( 4580): Could not find method android.webkit.WebChromeClient$FileChooserParams.createIntent, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onShowFileChooser
,W/dalvikvm( 4580): VFY: unable to resolve virtual method 268: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
,D/dalvikvm( 4580): VFY: replacing opcode 0x6e at 0x0000
,D/SystemWebViewEngine( 4580): CordovaWebView is running on device made by: samsung
D/STATUSBAR-PhoneStatusBar( 1063):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
D/BatteryMeterView( 1063): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1063): checkOverflow(384), More:false, Req:false Child:2
,I/SecureStorage( 4483): [INFO]: SPID(0x00000000)Processing data has been completed
I/SecureStorage( 4483): [INFO]: SPID(0x00000000)WARNING! Failed to find SecureStorageExceptionJNI!..
I/SQLiteSecureOpenHelper( 4483): getWritableDatabase(pwd)
I/SQLiteSecureOpenHelper( 4483): getDatabaseLocked(b,b,pwd)...
,I/SQLiteSecureOpenHelper( 4483): Open platform.db in secure mode
,D/dalvikvm( 3513): GC_CONCURRENT freed 6674K, 43% free 10969K/19208K, paused 5ms+8ms, total 94ms
,I/SurfaceFlinger(  249): id=15 createSurf (1x1),1 flag=404, NainActivit
,D/KeyguardUpdateMonitor( 1063): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1063): handleKeyguardVisibilityChanged(1)
,W/ActivityManager(  766): Permission Denial: getCurrentUser() from pid=4644, uid=10090 requires android.permission.INTERACT_ACROSS_USERS
,D/KeyguardUpdateMonitor( 1063): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1063): handleKeyguardVisibilityChanged(1)
,I/HWUI    ( 4580): EGLImpl-HWUI Protected EGL context created
,D/OpenGLRenderer( 4580): Enabling debug mode 0
,D/OpenGLRenderer( 4580): GL error from OpenGLRenderer: 0x502
,E/OpenGLRenderer( 4580):   GL_INVALID_OPERATION
,D/KeyguardUpdateMonitor( 1063): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1063): handleKeyguardVisibilityChanged(1)
,D/CustomFrequencyManagerService(  766): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 766  tag : ACTIVITY_RESUME_BOOSTER@5
,W/ActivityManager(  766): mDVFSHelper.release()
,D/KeyguardUpdateMonitor( 1063): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1063): handleKeyguardVisibilityChanged(1)
D/CustomFrequencyManagerService(  766): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 766  pkgName : ACTIVITY_RESUME_BOOSTER@9
,I/SQLiteSecureOpenHelper( 4483): ...getDatabaseLocked(b,b,pwd)
,D/SQLiteSecureOpenHelper( 4483): ...getDatabaseLocked(b,b,pwd)
,I/ActivityManager(  766): Killing 3303:com.sec.modem.settings/1000 (adj 15): empty #43
,D/JsMessageQueue( 4580): Set native->JS mode to OnlineEventsBridgeMode
,D/Finsky  ( 3513): [349] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 3513): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,I/SELinux ( 4678): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 4678):  
I/ActivityManager(  766): Killing 1334:com.sec.android.provider.badge/u0a72 (adj 15): empty #43
,W/GAV2    ( 4644): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,D/dalvikvm( 4580): Trying to load lib /data/app-lib/com.test.thalitest-6/libjxcore.so 0x42667658
,D/dalvikvm( 4580): Added shared lib /data/app-lib/com.test.thalitest-6/libjxcore.so 0x42667658
,D/jxcore_app_log( 4580): JniHelper::setJavaVM(0x41766528), pthread_self() = 2033855088
,I/SELinux ( 4678): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 4678):  
I/SELinux ( 4678):  
,I/SELinux ( 4678): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 4678): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 4678): >>>>> Normal User
,E/dalvikvm( 4678): >>>>> com.samsung.android.app.watchmanagerstub [ userId:0 | appId:10100 ]
,E/SELinux ( 4678): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 4678): in addTimaSignatureService
,D/TimaKeyStoreProvider( 4678): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 4678): Added TimaKesytore provider
,I/chromium( 4580): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot call method 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,D/PackageIntentReceiver( 4678): ACTION_PACKAGE_ADDED
,D/PackageIntentReceiver( 4678): Not GearManger package! 
,I/SELinux ( 4696): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 4696):  
,I/SELinux ( 4696): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 4696):  
I/SELinux ( 4696):  
,I/SELinux ( 4696): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 4696): [DEBUG] seapp_context_lookup: seinfoCategory = release
E/dalvikvm( 4696): >>>>> Normal User
,E/dalvikvm( 4696): >>>>> com.samsung.android.magazine.service [ userId:0 | appId:10106 ]
E/SELinux ( 4696): [DEBUG] seapp_context_lookup: seinfoCategory = release
,D/TimaKeyStoreProvider( 4696): in addTimaSignatureService
,D/TimaKeyStoreProvider( 4696): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 4696): Added TimaKesytore provider
,D/MagazineService Version( 4696): Magazine-Channel: 13
,D/MagazineService Version( 4696): Magazine-Provider: 13
,D/MagazineService Version( 4696): Magazine-Administrator: 11
,D/HeadlinesChannelApplication( 4696): [onCreate]
,W/ActivityManager(  766): Permission Denial: getCurrentUser() from pid=4696, uid=10106 requires android.permission.INTERACT_ACROSS_USERS
D/MagazineService::MagazineBroadcastReceiver( 4696): [onReceive] android.intent.action.PACKAGE_ADDED com.test.thalitest
,D/dalvikvm( 4580): GC_CONCURRENT freed 4951K, 34% free 12738K/19208K, paused 3ms+3ms, total 41ms
,D/dalvikvm( 4580): WAIT_FOR_CONCURRENT_GC blocked 22ms
,I/SELinux ( 4709): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 4709):  
,W/GAV2    ( 4644): Thread[main,5,main]: dispatch call queued.  Need to call GAServiceManager.getInstance().initialize().
I/ActivityManager(  766): Killing 3319:tv.peel.smartremote/u0a163 (adj 15): empty #43
,I/SELinux ( 4709): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 4709):  
I/SELinux ( 4709):  
,I/SELinux ( 4709): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 4709): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 4709): >>>>> Normal User
,E/dalvikvm( 4709): >>>>> com.samsung.helphub [ userId:0 | appId:1000 ]
,E/SELinux ( 4709): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,I/MagazineService::MagazineService( 4696): [onHandleIntent] ACTION_PACKAGE_INSTALLED
,D/MagazineService::MagazineService( 4696): [onHandleIntent] Send broadcast to (com.test.thalitest).
,I/ActivityManager(  766): Killing 3353:org.simalliance.openmobileapi.service/1101 (adj 15): empty #43
D/TimaKeyStoreProvider( 4709): in addTimaSignatureService
,D/TimaKeyStoreProvider( 4709): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 4709): Added TimaKesytore provider
,I/SELinux ( 4723): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 4723):  
I/ActivityManager(  766): Killing 3415:com.sec.android.app.taskmanager/u0a166 (adj 15): empty #43
,I/SELinux ( 4723): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 4723):  
I/SELinux ( 4723):  
,I/SELinux ( 4723): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 4723): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 4723): >>>>> Normal User
,E/dalvikvm( 4723): >>>>> com.sec.kidsplat.installer [ userId:0 | appId:10158 ]
,E/SELinux ( 4723): [DEBUG] seapp_context_lookup: seinfoCategory = platform
D/CustomFrequencyManagerService(  766): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 766  tag : ACTIVITY_RESUME_BOOSTER@9
,D/TimaKeyStoreProvider( 4723): in addTimaSignatureService
,D/TimaKeyStoreProvider( 4723): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 4723): Added TimaKesytore provider
,W/ActivityManager(  766): Permission Denial: getCurrentUser() from pid=4723, uid=10158 requires android.permission.INTERACT_ACROSS_USERS
,D/KidsPlatformStub( 4723): Package not found : com.sec.android.app.kidshome
,I/SELinux ( 4735): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 4735):  
,I/ActivityManager(  766): Killing 3428:com.samsung.android.service.travel/u0a169 (adj 15): empty #43
,I/SELinux ( 4735): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 4735):  
I/SELinux ( 4735):  
,I/SELinux ( 4735): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 4735): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 4735): >>>>> Normal User
,E/dalvikvm( 4735): >>>>> com.samsung.android.provider.shootingmodeprovider [ userId:0 | appId:10162 ]
,E/SELinux ( 4735): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 4735): in addTimaSignatureService
,D/TimaKeyStoreProvider( 4735): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 4735): Added TimaKesytore provider
,I/SELinux ( 4747): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 4747):  
,I/ActivityManager(  766): Killing 3444:com.google.android.youtube/u0a175 (adj 15): empty #43
,I/SELinux ( 4747): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 4747):  
I/SELinux ( 4747):  
,I/SELinux ( 4747): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 4747): [DEBUG] seapp_context_lookup: seinfoCategory = samsung
E/dalvikvm( 4747): >>>>> Normal User
,E/dalvikvm( 4747): >>>>> com.sec.android.app.samsungapps [ userId:0 | appId:10040 ]
,E/SELinux ( 4747): [DEBUG] seapp_context_lookup: seinfoCategory = samsung
,D/TimaKeyStoreProvider( 4747): in addTimaSignatureService
,D/TimaKeyStoreProvider( 4747): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 4747): Added TimaKesytore provider
,D/dalvikvm( 4580): GC_CONCURRENT freed 4684K, 28% free 16227K/22448K, paused 1ms+6ms, total 50ms
D/dalvikvm( 4580): WAIT_FOR_CONCURRENT_GC blocked 38ms
,D/dalvikvm( 4580): WAIT_FOR_CONCURRENT_GC blocked 40ms
,I/ActivityManager(  766): Killing 3630:com.sec.android.widgetapp.activeapplicationwidget/u0a152 (adj 15): empty #43
D/Finsky  ( 3513): [1] ExternalReferrer.access$200: Package state data is missing for com.test.thalitest
D/ChimeraCfgMgr( 1783): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1783): Loading module APK com.google.android.play.games
D/PackageBroadcastService( 1783): Received broadcast action=android.intent.action.PACKAGE_ADDED and uri=com.test.thalitest
I/dalvikvm( 1783): Could not find method android.app.admin.DevicePolicyManager.getProfileOwner, referenced from method com.google.android.gms.auth.WorkAccountAuthenticatorInitializer.a
W/dalvikvm( 1783): VFY: unable to resolve virtual method 174: Landroid/app/admin/DevicePolicyManager;.getProfileOwner ()Landroid/content/ComponentName;
D/dalvikvm( 1783): VFY: replacing opcode 0x6e at 0x0053
I/dalvikvm( 1783): Failed resolving Lcom/google/android/gms/common/permission/PermissionUtils$1; interface 96 'Landroid/content/pm/PackageManager$OnPermissionsChangedListener;'
W/dalvikvm( 1783): Link of class 'Lcom/google/android/gms/common/permission/PermissionUtils$1;' failed
E/dalvikvm( 1783): Could not find class 'com.google.android.gms.common.permission.PermissionUtils$1', referenced from method com.google.android.gms.chimera.GmsModuleInitializer.initializeModuleV0
W/dalvikvm( 1783): VFY: unable to resolve new-instance 2374 (Lcom/google/android/gms/common/permission/PermissionUtils$1;) in Lcom/google/android/gms/chimera/GmsModuleInitializer;
D/dalvikvm( 1783): VFY: replacing opcode 0x22 at 0x001a
I/dalvikvm( 1783): Failed resolving Lcom/google/android/gms/common/permission/PermissionUtils$1; interface 96 'Landroid/content/pm/PackageManager$OnPermissionsChangedListener;'
W/dalvikvm( 1783): Link of class 'Lcom/google/android/gms/common/permission/PermissionUtils$1;' failed
D/dalvikvm( 1783): DexOpt: unable to opt direct call 0x338d at 0x1c in Lcom/google/android/gms/chimera/GmsModuleInitializer;.initializeModuleV0
D/ChimeraCfgMgr( 1783): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1783): Module APK com.google.android.play.games already loaded
D/ChimeraCfgMgr( 1783): Loading module com.google.android.gms.gass from APK com.google.android.gms
D/AsyncTaskServiceImpl( 1783): Submit a task: k
D/ChimeraCfgMgr( 1783): Loading module com.google.android.gms.gass from APK com.google.android.gms
D/ChimeraCfgMgr( 1783): Loading module com.google.android.gms.vision from APK com.google.android.gms
D/k       ( 1783): Processing package: com.test.thalitest
D/GassUtils( 1783): Found app info for package com.test.thalitest:18. Hash: 4eebbbb84f07ed56a3e96e5e8f9d6abddaaf154fffa2a65432a1006e0fa38f32
W/BaseAppContext( 1783): Using Auth Proxy for data requests.
W/BaseAppContext( 1783): Using Auth Proxy for data requests.
D/k       ( 1783): Found info for package com.test.thalitest in db.
D/dalvikvm( 4580): GC_FOR_ALLOC freed 5105K, 32% free 17219K/25120K, paused 38ms, total 39ms
I/dalvikvm-heap( 4580): Grow heap (frag case) to 22.642MB for 2459024-byte allocation
D/dalvikvm(  766): GC_EXPLICIT freed 2114K, 59% free 23423K/56956K, paused 7ms+14ms, total 139ms
D/dalvikvm( 1298): GC_EXPLICIT freed 961K, 45% free 10755K/19208K, paused 2ms+6ms, total 43ms
W/dalvikvm( 1783): VFY: unable to find class referenced in signature (Landroid/app/SharedElementCallback;)
I/dalvikvm( 1783): Could not find method android.app.Activity.setEnterSharedElementCallback, referenced from method android.support.v4.app.w.setEnterSharedElementCallback
W/dalvikvm( 1783): VFY: unable to resolve virtual method 53: Landroid/app/Activity;.setEnterSharedElementCallback (Landroid/app/SharedElementCallback;)V
D/dalvikvm( 1783): VFY: replacing opcode 0x6e at 0x000e
W/BaseAppContext( 1783): Using Auth Proxy for data requests.
W/dalvikvm( 1783): VFY: unable to find class referenced in signature (Landroid/app/SharedElementCallback;)
I/dalvikvm( 1783): Could not find method android.app.Activity.setExitSharedElementCallback, referenced from method android.support.v4.app.w.setExitSharedElementCallback
W/dalvikvm( 1783): VFY: unable to resolve virtual method 54: Landroid/app/Activity;.setExitSharedElementCallback (Landroid/app/SharedElementCallback;)V
D/dalvikvm( 1783): VFY: replacing opcode 0x6e at 0x000e
I/dalvikvm( 1783): Could not find method android.app.Activity.finishAfterTransition, referenced from method android.support.v4.app.w.supportFinishAfterTransition
W/dalvikvm( 1783): VFY: unable to resolve virtual method 31: Landroid/app/Activity;.finishAfterTransition ()V
D/dalvikvm( 1783): VFY: replacing opcode 0x6e at 0x0006
I/dalvikvm( 1783): Could not find method android.app.Activity.postponeEnterTransition, referenced from method android.support.v4.app.w.supportPostponeEnterTransition
W/dalvikvm( 1783): VFY: unable to resolve virtual method 49: Landroid/app/Activity;.postponeEnterTransition ()V
D/dalvikvm( 1783): VFY: replacing opcode 0x6e at 0x0006
I/dalvikvm( 1783): Could not find method android.app.Activity.startPostponedEnterTransition, referenced from method android.support.v4.app.w.supportStartPostponedEnterTransition
W/dalvikvm( 1783): VFY: unable to resolve virtual method 61: Landroid/app/Activity;.startPostponedEnterTransition ()V
D/dalvikvm( 1783): VFY: replacing opcode 0x6e at 0x0006
,W/BaseAppContext( 1783): Using Auth Proxy for data requests.
,W/BaseAppContext( 1783): Using Auth Proxy for data requests.
,I/PeopleDatabaseHelper( 1783): cleanUpNonGplusAccounts done.
,W/BaseAppContext( 1783): Using Auth Proxy for data requests.
,W/BaseAppContext( 1783): Using Auth Proxy for data requests.
,D/dalvikvm( 4580): GC_FOR_ALLOC freed 3737K, 35% free 17931K/27524K, paused 34ms, total 35ms
,W/dalvikvm( 1783): VFY: unable to find class referenced in signature (Landroid/util/Size;)
,D/dalvikvm( 4580): GC_FOR_ALLOC freed 1183K, 36% free 17840K/27524K, paused 29ms, total 29ms
,D/ChimeraCfgMgr( 1783): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 1783): Module APK com.google.android.play.games already loaded
,E/SMD     (  240): DCD ON
,D/dalvikvm( 4580): GC_FOR_ALLOC freed 4467K, 39% free 19151K/31128K, paused 32ms, total 33ms
,W/jxcore-log( 4580): Initializing JXcore engine
,W/jxcore-log( 4580): JXcore engine is ready
,W/jxcore-log( 4580): Starting JXcore engine
,W/jxcore-log( 4580): Platform android
W/jxcore-log( 4580): 
,W/jxcore-log( 4580): Process ARCH arm
W/jxcore-log( 4580): 
,I/Icing   ( 1783): Indexing 49CA7E3A917E607C6D98AA15891295369CED2106 from com.google.android.gms
,D/dalvikvm( 1783): GC_CONCURRENT freed 1451K, 39% free 11780K/19208K, paused 4ms+5ms, total 52ms
,I/Icing   ( 1783): Indexing done 49CA7E3A917E607C6D98AA15891295369CED2106
,I/jxcore-log( 4580): JXcore Cordova bridge is ready!
I/jxcore-log( 4580): 
,W/jxcore-log( 4580): JXcore engine is started
,E/jxcore  ( 4580): Error!: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js
E/jxcore  ( 4580): Stack: [{"_fileName":"node.js","_functionName":"$h.require","_lineNumber":"1472","_columnNumber":"1","_msg":"    at $h.require@node.js:1472:1"},{"_fileName":"main.js.js","_functionName":"internal_methods.loadMainFile","_lineNumber":"260","_columnNumber":"5","_msg":"    at internal_methods.loadMainFile@main.js.js:260:5"},{"_fileName":"main.js.js","_functionName":"JXMobile.executeJSON","_lineNumber":"279","_columnNumber":"7","_msg":"    at JXMobile.executeJSON@main.js.js:279:7"},{"_fileName":"JX_Evaluate","_functionName":"","_lineNumber":"1","_columnNumber":"1","_msg":"    at @JX_Evaluate:1:1"},{"_fileName":"node.js","_functionName":"unknown","_lineNumber":"1472","_columnNumber":"1","_msg":""}]
,I/chromium( 4580): [INFO:CONSOLE(37)] "App.js file failed to load : "No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\nError: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\n    at $h.require@node.js:1472:1\n    at internal_methods.loadMainFile@main.js.js:260:5\n    at JXMobile.executeJSON@main.js.js:279:7\n    at @JX_Evaluate:1:1\n"", source: file:///android_asset/www/js/thali_main.js (37)
,D/LockPatternUtils( 1063): isPcwEnable = null
I/ActivityManager(  766): Killing 3673:com.sec.android.app.sns3/u0a36 (adj 15): empty #43
,I/SurfaceFlinger(  249): id=15 Removed NainActivit (7/11)
,I/SurfaceFlinger(  249): id=15 Removed NainActivit (-2/11)
,D/KeyguardUpdateMonitor( 1063): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1063): handleKeyguardVisibilityChanged(1)
,D/KeyguardUpdateMonitor( 1063): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1063): handleKeyguardVisibilityChanged(1)
D/CustomFrequencyManagerService(  766): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 766  pkgName : ACTIVITY_RESUME_BOOSTER@5
W/ActivityManager(  766): mDVFSHelper.acquire()
,D/KeyguardUpdateMonitor( 1063): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1063): handleKeyguardVisibilityChanged(1)
,D/LockPatternUtils( 1063): isPcwEnable = null
,D/SurfaceWidgetView( 1247): destroyHardwareResources():1126594224
,D/KeyguardUpdateMonitor( 1063): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1063): handleKeyguardVisibilityChanged(1)
,D/KeyguardUpdateMonitor( 1063): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1063): handleKeyguardVisibilityChanged(1)
,D/Launcher( 1247): onRestart, Launcher: 1114658752
D/Launcher( 1247): onStart, Launcher: 1114658752
,D/Launcher.HomeView( 1247): onStart
,D/SurfaceWidgetClient$ISurfaceWidgetStub( 1442): [237392/5] Surface widget visibility changed visibility = true on instance = 1
,D/SurfaceWidget.Renderer( 1442): [237392/5] SurfaceWidget drawing first frame
,I/SurfaceFlinger(  249): id=16 createSurf (1x1),2 flag=404, CatteryCove
,D/KeyguardUpdateMonitor( 1063): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1063): handleKeyguardVisibilityChanged(1)
,I/SurfaceFlinger(  249): id=17 createSurf (720x1280),1 flag=4, Mauncher
,D/KeyguardUpdateMonitor( 1063): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1063): handleKeyguardVisibilityChanged(1)
,D/Launcher.HomeView( 1247): onStop
,D/KeyguardUpdateMonitor( 1063): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1063): handleKeyguardVisibilityChanged(1)
,D/KeyguardUpdateMonitor( 1063): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1063): handleKeyguardVisibilityChanged(1)
,D/KeyguardUpdateMonitor( 1063): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1063): handleKeyguardVisibilityChanged(1)
,D/KeyguardUpdateMonitor( 1063): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1063): handleKeyguardVisibilityChanged(1)
D/CustomFrequencyManagerService(  766): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 766  pkgName : ACTIVITY_RESUME_BOOSTER@9
D/CustomFrequencyManagerService(  766): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 766  tag : ACTIVITY_RESUME_BOOSTER@5
D/CustomFrequencyManagerService(  766): FrequencyrequestList.getNextMaxCPUCoreRequest, index: 0
W/ActivityManager(  766): mDVFSHelper.release()
,D/CustomFrequencyManagerService(  766): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 766  tag : ACTIVITY_RESUME_BOOSTER@9
,I/GAV2    ( 4644): Thread[GAThread,5,main]: No campaign data found.
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  766): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP(  766): SIOP:: AP = 310, Delta = 0
,E/SMD     (  240): DCD ON
,I/HarmonyEASService(  766): Updating for all 1
,E/SMD     (  240): DCD ON
,E/Watchdog(  766): !@Sync 3
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  766): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,V/AlarmManager(  766): waitForAlarm result :4
,V/AlarmManager(  766): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,D/BatteryService(  766): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 288, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:3, charge type:1, power sharing:false
,D/BatteryService(  766): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  766): stay LED for fully charged
,D/UiModeManager(  766): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1063): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1063): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1063):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1063): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1063): checkOverflow(384), More:false, Req:false Child:2
,D/dalvikvm( 3513): GC_CONCURRENT freed 1720K, 42% free 11189K/19208K, paused 3ms+4ms, total 35ms
,D/Finsky  ( 3513): [349] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 3513): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  766): SIOP:: AP = 300, Delta = -10
,W/ContextImpl(  766): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  240): DCD ON
,I/PowerManagerService(  766): [PWL] Off : 75s ago
,D/FactoryTest( 4100): Not factory mode
,D/FactoryTest( 4100): Not factory mode. isFactoryMode() returend false
,D/MTPRx   ( 4100): DRIVER_TIME_OUT 60s lapsed
,D/MTPRx   ( 4100): still no open session command from host, so toast
,W/ContextImpl( 4100): Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1398 android.content.ContextWrapper.startActivity:323 android.content.ContextWrapper.startActivity:323 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:767 android.os.Handler.dispatchMessage:102 
,W/ContextImpl( 4100): Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1410 android.app.ContextImpl.startActivity:1399 android.content.ContextWrapper.startActivity:323 android.content.ContextWrapper.startActivity:323 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:767 
,V/ApplicationPolicy(  766): isApplicationStateBlocked userId 0 pkgname com.android.settings
,D/CustomFrequencyManagerService(  766): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 766  pkgName : ACTIVITY_RESUME_BOOSTER@5
,W/ActivityManager(  766): mDVFSHelper.acquire()
,D/LockPatternUtils( 1063): isPcwEnable = null
,I/SQLiteSecureOpenHelper( 2011): getWritableDatabase(pwd)
,D/LockPatternUtils( 1063): isPcwEnable = null
,E/MTPRx   ( 4100): started activity for popup
,I/SQLiteSecureOpenHelper( 2011): getDatabaseLocked(b,b,pwd)...
,E/SettingsReceiverActivity( 4100): PREF_DONT_ASK_AGAIN : true
,D/LockPatternUtils( 1063): isPcwEnable = null
,D/SettingsReceiverActivity( 4100): dev.kiessupport is : TRUE
,E/SMD     (  240): DCD ON
I/WindowManager(  766): Screenshot max retries 4 of Token{430378e0 ActivityRecord{42f86bd0 u0 com.sec.android.app.popupuireceiver/.BatteryCover t2}} appWin=Window{42ca6288 u0 com.sec.android.app.popupuireceiver/com.sec.android.app.popupuireceiver.BatteryCover} drawState=4
,W/WindowManager(  766): Screenshot failure taking screenshot for (720x1280) to layer 21005
D/LockPatternUtils( 1063): isPcwEnable = null
,D/AmoledAdjustTimer(  766): prevTemp = 286, currTemp = 288, prevStep = 4, currStep = 4
,D/CustomFrequencyManagerService(  766): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 766  tag : ACTIVITY_RESUME_BOOSTER@5
,W/ActivityManager(  766): mDVFSHelper.release()
,D/CustomFrequencyManagerService(  766): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 766  pkgName : ACTIVITY_RESUME_BOOSTER@9
,D/BatteryService(  766): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:5, charge type:1, power sharing:false
,D/BatteryService(  766): stay LED for fully charged
,D/BatteryService(  766): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1063): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1063): handleBatteryUpdate
D/UiModeManager(  766): mCoverManager.getCoverState() : true
,E/SMD     (  240): DCD ON
,D/STATUSBAR-PhoneStatusBar( 1063):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1063): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1063): checkOverflow(384), More:false, Req:false Child:2
,D/CustomFrequencyManagerService(  766): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 766  tag : ACTIVITY_RESUME_BOOSTER@9
,D/SSRMv2:SIOP(  766): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  766): prevTemp = 288, currTemp = 286, prevStep = 4, currStep = 4
,V/AlarmManager(  766): waitForAlarm result :8
,V/AlarmManager(  766): ClockReceiver onReceive() ACTION_TIME_TICK
,V/AlarmManager(  766): ___SyncScheduler (v3) ACTIVATED___
,V/AlarmManager(  766): <AppSync3 Whitelist>
,D/KeyguardUpdateMonitor( 1063): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1063): handleTimeUpdate
V/AlarmManager(  766): (AppSync) ### 0 added ###
,D/STATUSBAR-IconMerger( 1063): checkOverflow(384), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  766): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,W/ContextImpl(  766): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  240): DCD ON
,E/Watchdog(  766): !@Sync 4
,V/AlarmManager(  766): waitForAlarm result :4
,V/AlarmManager(  766): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,D/NtpTrustedTime(  766): forceRefresh() from cache miss
,D/NtpTrustedTime(  766): forceRefresh Fail.
,D/BatteryService(  766): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 284, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:3, charge type:1, power sharing:false
,D/BatteryService(  766): stay LED for fully charged
,D/BatteryService(  766): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1063): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1063): handleBatteryUpdate
,D/UiModeManager(  766): mCoverManager.getCoverState() : true
,D/STATUSBAR-PhoneStatusBar( 1063):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1063): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1063): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  766): prevTemp = 286, currTemp = 284, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  766): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,I/PowerManagerService(  766): [PWL] Off : 105s ago
,E/SMD     (  240): DCD ON
,D/BatteryService(  766): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 283, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-11, charge type:1, power sharing:false
,D/BatteryService(  766): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  766): stay LED for fully charged
,D/UiModeManager(  766): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1063): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1063): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1063):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1063): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1063): checkOverflow(384), More:false, Req:false Child:2
,D/AmoledAdjustTimer(  766): prevTemp = 284, currTemp = 283, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  766): SIOP:: AP = 300, Delta = 0
,W/ContextImpl(  766): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/BatteryService(  766): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-10, charge type:1, power sharing:false
,D/BatteryService(  766): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  766): mCoverManager.getCoverState() : true
,D/BatteryService(  766): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1063): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1063): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1063):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1063): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1063): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  766): prevTemp = 283, currTemp = 282, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP(  766): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,E/Watchdog(  766): !@Sync 5
,D/BatteryService(  766): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  766): Sending ACTION_BATTERY_CHANGED.
,E/SMD     (  240): DCD ON
,D/KeyguardUpdateMonitor( 1063): received broadcast android.intent.action.BATTERY_CHANGED
D/BatteryService(  766): stay LED for fully charged
,D/UiModeManager(  766): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 1063): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1063):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1063): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1063): checkOverflow(384), More:false, Req:false Child:2
,D/AmoledAdjustTimer(  766): prevTemp = 282, currTemp = 282, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  766): SIOP:: AP = 300, Delta = 0
,W/ContextImpl(  766): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/BatteryService(  766): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-3, charge type:1, power sharing:false
,D/BatteryService(  766): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  766): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1063): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1063): handleBatteryUpdate
D/BatteryService(  766): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1063):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1063): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1063): checkOverflow(384), More:false, Req:false Child:2
,D/AmoledAdjustTimer(  766): prevTemp = 282, currTemp = 281, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,I/PowerManagerService(  766): [PWL] Off : 140s ago
,D/SSRMv2:SIOP(  766): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  766): prevTemp = 281, currTemp = 281, prevStep = 4, currStep = 4
,V/AlarmManager(  766): waitForAlarm result :8
,V/AlarmManager(  766): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1063): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1063): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1063): checkOverflow(384), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  766): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,W/ContextImpl(  766): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  240): DCD ON
,E/Watchdog(  766): !@Sync 6
,V/AlarmManager(  766): waitForAlarm result :4
,V/AlarmManager(  766): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,D/NtpTrustedTime(  766): forceRefresh() from cache miss
,D/NtpTrustedTime(  766): forceRefresh Fail.
,D/BatteryService(  766): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 280, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:6, charge type:1, power sharing:false
,D/BatteryService(  766): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  766): stay LED for fully charged
,D/UiModeManager(  766): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1063): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1063): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1063):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1063): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1063): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,I/VacuumService( 1207): Vacuum at: now=1453885628117 tag=VacuumService
,D/AmoledAdjustTimer(  766): prevTemp = 281, currTemp = 280, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  766): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/BatteryService(  766): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  766): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  766): stay LED for fully charged
,D/UiModeManager(  766): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1063): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1063): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1063):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1063): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1063): checkOverflow(384), More:false, Req:false Child:2
,D/AmoledAdjustTimer(  766): prevTemp = 280, currTemp = 279, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  766): SIOP:: AP = 300, Delta = 0
,W/ContextImpl(  766): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  766): prevTemp = 279, currTemp = 279, prevStep = 4, currStep = 4
,I/PowerManagerService(  766): [PWL] Off : 180s ago
,D/SSRMv2:SIOP(  766): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,E/Watchdog(  766): !@Sync 7
,E/SMD     (  240): DCD ON
D/BatteryService(  766): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
D/BatteryService(  766): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  766): mCoverManager.getCoverState() : true
,D/BatteryService(  766): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1063): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1063): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1063):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1063): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1063): checkOverflow(384), More:false, Req:false Child:2
,D/AmoledAdjustTimer(  766): prevTemp = 279, currTemp = 279, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  766): SIOP:: AP = 300, Delta = 0
,W/ContextImpl(  766): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/BatteryService(  766): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:2, charge type:1, power sharing:false
,D/BatteryService(  766): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  766): stay LED for fully charged
,D/UiModeManager(  766): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1063): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1063): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1063):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1063): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1063): checkOverflow(384), More:false, Req:false Child:2
,D/AmoledAdjustTimer(  766): prevTemp = 279, currTemp = 278, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  766): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  766): prevTemp = 278, currTemp = 278, prevStep = 4, currStep = 4
,V/AlarmManager(  766): waitForAlarm result :8
,V/AlarmManager(  766): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1063): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1063): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1063): checkOverflow(384), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  766): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,W/ContextImpl(  766): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  240): DCD ON
,E/Watchdog(  766): !@Sync 8
,E/SMD     (  240): DCD ON
,D/BatteryService(  766): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:3, charge type:1, power sharing:false
,D/BatteryService(  766): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  766): stay LED for fully charged
,D/UiModeManager(  766): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1063): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1063): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1063):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1063): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1063): checkOverflow(384), More:false, Req:false Child:2
,D/AmoledAdjustTimer(  766): prevTemp = 278, currTemp = 278, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  766): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,I/PowerManagerService(  766): [PWL] Off : 225s ago
,E/SMD     (  240): DCD ON
,D/BatteryService(  766): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:2, charge type:1, power sharing:false
,D/BatteryService(  766): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  766): stay LED for fully charged
,D/UiModeManager(  766): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1063): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1063): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1063):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1063): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1063): checkOverflow(384), More:false, Req:false Child:2
,D/AmoledAdjustTimer(  766): prevTemp = 278, currTemp = 277, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  766): SIOP:: AP = 300, Delta = 0
,W/ContextImpl(  766): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/BatteryService(  766): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:3, charge type:1, power sharing:false
,D/BatteryService(  766): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  766): mCoverManager.getCoverState() : true
,D/BatteryService(  766): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1063): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1063): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1063):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1063): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1063): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  766): prevTemp = 277, currTemp = 277, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP(  766): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,E/Watchdog(  766): !@Sync 9
,E/SMD     (  240): DCD ON
,D/BatteryService(  766): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:8, charge type:1, power sharing:false
,D/BatteryService(  766): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  766): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1063): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1063): handleBatteryUpdate
D/BatteryService(  766): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1063):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1063): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1063): checkOverflow(384), More:false, Req:false Child:2
,D/AmoledAdjustTimer(  766): prevTemp = 277, currTemp = 277, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  766): SIOP:: AP = 300, Delta = 0
,W/ContextImpl(  766): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/BatteryService(  766): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:7, charge type:1, power sharing:false
,D/BatteryService(  766): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  766): stay LED for fully charged
,D/UiModeManager(  766): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1063): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1063): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1063):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1063): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1063): checkOverflow(384), More:false, Req:false Child:2
,D/AmoledAdjustTimer(  766): prevTemp = 277, currTemp = 277, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  766): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/BatteryService(  766): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  766): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  766): mCoverManager.getCoverState() : true
,D/BatteryService(  766): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1063): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1063): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1063):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1063): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1063): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  766): prevTemp = 277, currTemp = 276, prevStep = 4, currStep = 4
,V/AlarmManager(  766): waitForAlarm result :8
,V/AlarmManager(  766): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1063): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1063): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1063): checkOverflow(384), More:false, Req:false Child:2
,D/TimaService(  766): TIMA: TimaService scheduler is intialized. 
,D/TimaService(  766): TimaServiceHandler.handleMessage what =1
,D/TimaService(  766): TIMA: checkEvent, operation: 50000 subject: 10000
,I/TLC_TIMA_PKM_initialize(  766): initializing...
,I/TLC_TIMA_PKM_initialize(  766): root = /firmware/image, root_strlen = 15
I/TLC_TIMA_PKM_initialize(  766): process = tima_pkm, process_strlen = 8
,I/TZ: qc_tlc_communication(  766): root = /firmware/image, root_len = 15
I/TZ: qc_tlc_communication(  766): process = tima_pkm, process_strlen = 8
,I/TZ: qc_tlc_communication(  766): aligned max_sendmsg_size = 262208 = 0x40040
,I/TZ: qc_tlc_communication(  766): aligned max_recvmsg_size = 262208 = 0x40040
,I/TZ: qc_tlc_communication(  766): max_message_size = 524416 = 0x80080
,D/QSEECOMAPI: (  766): QSEECom_get_handle sb_length = 0x80080
,D/QSEECOMAPI: (  766): App is not loaded in QSEE
,D/QSEECOMAPI: (  766): Loaded image: APP id = 3
,I/TZ: qc_tlc_communication(  766): TIMA: path = /firmware/image, fname = tima_pkm, tzapp is loaded
,I/TLC_TIMA_PKM_initialize(  766): Trustlet response is completed
,D/SSRMv2:SIOP(  766): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,W/ContextImpl(  766): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,I/PowerManagerService(  766): [PWL] Off : 275s ago
,I/PowerManagerService(  766): [PWL]   PowerManagerService.WakeLocks: ref count=1
,I/PowerManagerService(  766): [PWL]     mWakeLockSummary : 0x1
,I/PowerManagerService(  766): [PWL]       PARTIAL_WAKE_LOCK              'TimaService' (uid=1000, pid=766, ws=null) (elapsedTime=3389)
,E/SMD     (  240): DCD ON
,I/TLC_TIMA_PKM_measure_kernel(  766): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel(  766): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService(  766): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService(  766): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/Watchdog(  766): !@Sync 10
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  766): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  766): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  766): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  766): SIOP:: AP = 300, Delta = 0
,W/ContextImpl(  766): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,V/AlarmManager(  766): waitForAlarm result :4
,V/AlarmManager(  766): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,D/BatteryService(  766): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:3, charge type:1, power sharing:false
,D/BatteryService(  766): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  766): stay LED for fully charged
,I/SELinux ( 4900): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 4900):  
,D/UiModeManager(  766): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1063): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1063): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1063):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 1063): checkOverflow(384), More:false, Req:false Child:2
,D/BatteryMeterView( 1063): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/SELinux ( 4900): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 4900):  
I/SELinux ( 4900):  
,I/SELinux ( 4900): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 4900): [DEBUG] seapp_context_lookup: seinfoCategory = default
,E/dalvikvm( 4900): >>>>> Normal User
,E/dalvikvm( 4900): >>>>> com.blurb.checkout [ userId:0 | appId:10075 ]
,E/SELinux ( 4900): [DEBUG] seapp_context_lookup: seinfoCategory = default
,D/TimaKeyStoreProvider( 4900): in addTimaSignatureService
,D/TimaKeyStoreProvider( 4900): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 4900): Added TimaKesytore provider
,W/ActivityManager(  766): Permission Denial: getCurrentUser() from pid=4900, uid=10075 requires android.permission.INTERACT_ACROSS_USERS
,I/ActivityManager(  766): Killing 3722:com.sec.spp.push:RemoteDlcProcess/u0a38 (adj 15): empty #43
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  766): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP(  766): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,E/Watchdog(  766): !@Sync 11
,V/GLSActivity( 1298): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1298): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/SocketClient(  237): write error (Broken pipe)
,D/BatteryService(  766): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:2, charge type:1, power sharing:false
,D/BatteryService(  766): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  766): stay LED for fully charged
,D/UiModeManager(  766): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1063): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1063): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1063):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1063): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1063): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  766): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  766): SIOP:: AP = 300, Delta = 0
,W/ContextImpl(  766): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/BatteryService(  766): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  766): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  766): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1063): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1063): handleBatteryUpdate
D/UiModeManager(  766): mCoverManager.getCoverState() : true
,D/STATUSBAR-PhoneStatusBar( 1063):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1063): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1063): checkOverflow(384), More:false, Req:false Child:2
,D/AmoledAdjustTimer(  766): prevTemp = 276, currTemp = 275, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  766): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/BatteryService(  766): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-1, charge type:1, power sharing:false
,D/BatteryService(  766): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  766): stay LED for fully charged
,D/UiModeManager(  766): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1063): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1063): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1063):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1063): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1063): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  766): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,I/PowerManagerService(  766): [PWL] Off : 330s ago
,V/AlarmManager(  766): waitForAlarm result :8
,V/AlarmManager(  766): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1063): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1063): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1063): checkOverflow(384), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  766): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,W/ContextImpl(  766): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  240): DCD ON
,E/Watchdog(  766): !@Sync 12
,E/SMD     (  240): DCD ON
,D/BatteryService(  766): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-2, charge type:1, power sharing:false
,D/BatteryService(  766): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  766): stay LED for fully charged
,D/UiModeManager(  766): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1063): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1063): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1063):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1063): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1063): checkOverflow(384), More:false, Req:false Child:2
,D/AmoledAdjustTimer(  766): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  766): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/BatteryService(  766): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-4, charge type:1, power sharing:false
,D/BatteryService(  766): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  766): stay LED for fully charged
,D/UiModeManager(  766): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1063): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1063): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1063):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1063): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1063): checkOverflow(384), More:false, Req:false Child:2
,D/AmoledAdjustTimer(  766): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  766): SIOP:: AP = 300, Delta = 0
,W/ContextImpl(  766): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  766): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  766): SIOP:: AP = 300, Delta = 0
,D/dalvikvm(  766): GC_CONCURRENT freed 3363K, 59% free 23439K/56956K, paused 21ms+40ms, total 427ms
,E/SMD     (  240): DCD ON
,E/Watchdog(  766): !@Sync 13
,E/SMD     (  240): DCD ON
,D/BatteryService(  766): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-6, charge type:1, power sharing:false
,D/BatteryService(  766): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  766): mCoverManager.getCoverState() : true
,D/BatteryService(  766): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1063): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1063): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1063):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1063): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1063): checkOverflow(384), More:false, Req:false Child:2
,D/AmoledAdjustTimer(  766): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  766): SIOP:: AP = 300, Delta = 0
,W/ContextImpl(  766): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/BatteryService(  766): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-8, charge type:1, power sharing:false
,D/BatteryService(  766): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  766): stay LED for fully charged
,D/UiModeManager(  766): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1063): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1063): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1063):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1063): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1063): checkOverflow(384), More:false, Req:false Child:2
,D/AmoledAdjustTimer(  766): prevTemp = 275, currTemp = 274, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  766): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/BatteryService(  766): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-3, charge type:1, power sharing:false
,D/BatteryService(  766): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  766): stay LED for fully charged
,D/UiModeManager(  766): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1063): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1063): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1063):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1063): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1063): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  766): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,I/PowerManagerService(  766): [PWL] Off : 390s ago
,V/AlarmManager(  766): waitForAlarm result :8
,V/AlarmManager(  766): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1063): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1063): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1063): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  766): SIOP:: AP = 300, Delta = 0
,W/ContextImpl(  766): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  240): DCD ON
,E/Watchdog(  766): !@Sync 14
,E/SMD     (  240): DCD ON
,D/BatteryService(  766): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-6, charge type:1, power sharing:false
,D/BatteryService(  766): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  766): stay LED for fully charged
,D/UiModeManager(  766): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1063): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1063): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1063):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1063): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1063): checkOverflow(384), More:false, Req:false Child:2
,D/AmoledAdjustTimer(  766): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  766): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/BatteryService(  766): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  766): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  766): stay LED for fully charged
,D/UiModeManager(  766): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1063): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1063): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1063):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1063): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1063): checkOverflow(384), More:false, Req:false Child:2
,D/AmoledAdjustTimer(  766): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  766): SIOP:: AP = 300, Delta = 0
,W/ContextImpl(  766): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/BatteryService(  766): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:5, charge type:1, power sharing:false
,D/BatteryService(  766): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  766): mCoverManager.getCoverState() : true
,D/BatteryService(  766): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1063): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1063): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1063):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1063): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1063): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  766): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  766): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,E/Watchdog(  766): !@Sync 15
,E/SMD     (  240): DCD ON
,D/BatteryService(  766): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-3, charge type:1, power sharing:false
,D/BatteryService(  766): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  766): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1063): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1063): handleBatteryUpdate
D/BatteryService(  766): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1063):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1063): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1063): checkOverflow(384), More:false, Req:false Child:2
,D/AmoledAdjustTimer(  766): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  766): SIOP:: AP = 300, Delta = 0
,W/ContextImpl(  766): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/BatteryService(  766): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-12, charge type:1, power sharing:false
,D/BatteryService(  766): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  766): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 1063): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1063): handleBatteryUpdate
D/BatteryService(  766): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1063):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1063): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1063): checkOverflow(384), More:false, Req:false Child:2
,D/AmoledAdjustTimer(  766): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  766): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/BatteryService(  766): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-11, charge type:1, power sharing:false
,D/BatteryService(  766): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  766): mCoverManager.getCoverState() : true
,D/BatteryService(  766): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1063): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1063): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1063):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1063): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1063): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  766): prevTemp = 274, currTemp = 273, prevStep = 4, currStep = 4
,V/AlarmManager(  766): waitForAlarm result :8
,V/AlarmManager(  766): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1063): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1063): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1063): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,W/ContextImpl(  766): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/SSRMv2:SIOP(  766): SIOP:: AP = 300, Delta = 0
,I/PowerManagerService(  766): [PWL] Off : 455s ago
,E/SMD     (  240): DCD ON
,E/Watchdog(  766): !@Sync 16
,E/SMD     (  240): DCD ON
,D/BatteryService(  766): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  766): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  766): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1063): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1063): handleBatteryUpdate
D/BatteryService(  766): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1063):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1063): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1063): checkOverflow(384), More:false, Req:false Child:2
,D/AmoledAdjustTimer(  766): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  766): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/BatteryService(  766): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-9, charge type:1, power sharing:false
,D/BatteryService(  766): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  766): stay LED for fully charged
,D/UiModeManager(  766): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1063): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1063): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1063):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1063): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1063): checkOverflow(384), More:false, Req:false Child:2
,D/AmoledAdjustTimer(  766): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,W/ContextImpl(  766): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/SSRMv2:SIOP(  766): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/BatteryService(  766): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-10, charge type:1, power sharing:false
,D/BatteryService(  766): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  766): stay LED for fully charged
,D/UiModeManager(  766): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1063): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1063): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1063):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1063): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1063): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  766): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  766): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,E/Watchdog(  766): !@Sync 17
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  766): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,W/ContextImpl(  766): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/SSRMv2:SIOP(  766): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/BatteryService(  766): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:2, charge type:1, power sharing:false
,D/BatteryService(  766): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  766): stay LED for fully charged
,D/UiModeManager(  766): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1063): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1063): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1063):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1063): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1063): checkOverflow(384), More:false, Req:false Child:2
,D/AmoledAdjustTimer(  766): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  766): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  766): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,V/AlarmManager(  766): waitForAlarm result :8
,V/AlarmManager(  766): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1063): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1063): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1063): checkOverflow(384), More:false, Req:false Child:2
,D/BatteryService(  766): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:2, charge type:1, power sharing:false
,D/BatteryService(  766): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  766): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1063): received broadcast android.intent.action.BATTERY_CHANGED
,D/UiModeManager(  766): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 1063): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1063):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1063): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1063): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,W/ContextImpl(  766): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/SSRMv2:SIOP(  766): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,E/Watchdog(  766): !@Sync 18
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  766): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  766): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,I/PowerManagerService(  766): [PWL] Off : 525s ago
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  766): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,D/BatteryService(  766): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-2, charge type:1, power sharing:false
,D/BatteryService(  766): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  766): mCoverManager.getCoverState() : true
,D/BatteryService(  766): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1063): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1063): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1063):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1063): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1063): checkOverflow(384), More:false, Req:false Child:2
,W/ContextImpl(  766): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/SSRMv2:SIOP(  766): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  766): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,D/BatteryService(  766): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-3, charge type:1, power sharing:false
,D/BatteryService(  766): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  766): mCoverManager.getCoverState() : true
,D/BatteryService(  766): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1063): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1063): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1063):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1063): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1063): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  766): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,E/Watchdog(  766): !@Sync 19
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  766): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,D/BatteryService(  766): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-2, charge type:1, power sharing:false
,D/BatteryService(  766): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  766): mCoverManager.getCoverState() : true
,D/BatteryService(  766): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1063): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1063): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1063):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1063): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1063): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,W/ContextImpl(  766): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/SSRMv2:SIOP(  766): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  766): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,D/BatteryService(  766): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-12, charge type:1, power sharing:false
,D/BatteryService(  766): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  766): mCoverManager.getCoverState() : true
,D/BatteryService(  766): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1063): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1063): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1063):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1063): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1063): checkOverflow(384), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  766): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  766): prevTemp = 273, currTemp = 272, prevStep = 4, currStep = 4
,V/AlarmManager(  766): waitForAlarm result :8
,V/AlarmManager(  766): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1063): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1063): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1063): checkOverflow(384), More:false, Req:false Child:2
,D/BatteryService(  766): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:3, charge type:1, power sharing:false
,D/BatteryService(  766): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  766): mCoverManager.getCoverState() : true
,D/BatteryService(  766): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1063): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1063): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1063):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1063): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1063): checkOverflow(384), More:false, Req:false Child:2
,D/TimaService(  766): TIMA: TimaService scheduler is intialized. 
,D/TimaService(  766): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService(  766): TimaServiceHandler.handleMessage what =1
,E/SMD     (  240): DCD ON
,W/ContextImpl(  766): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/SSRMv2:SIOP(  766): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,I/TLC_TIMA_PKM_measure_kernel(  766): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel(  766): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService(  766): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService(  766): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/Watchdog(  766): !@Sync 20
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  766): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,D/BatteryService(  766): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  766): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  766): stay LED for fully charged
,D/UiModeManager(  766): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1063): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1063): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1063):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1063): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1063): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  766): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  766): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,D/BatteryService(  766): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-8, charge type:1, power sharing:false
,D/BatteryService(  766): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  766): mCoverManager.getCoverState() : true
,D/BatteryService(  766): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1063): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1063): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1063):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1063): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1063): checkOverflow(384), More:false, Req:false Child:2
,W/ContextImpl(  766): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/SSRMv2:SIOP(  766): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  766): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,I/PowerManagerService(  766): [PWL] Off : 600s ago
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  766): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,E/Watchdog(  766): !@Sync 21
,V/GLSActivity( 1298): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1298): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/SocketClient(  237): write error (Broken pipe)
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  766): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,D/BatteryService(  766): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-3, charge type:1, power sharing:false
,D/BatteryService(  766): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  766): stay LED for fully charged
,D/UiModeManager(  766): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1063): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1063): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1063):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1063): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1063): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  766): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  766): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  766): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,V/AlarmManager(  766): waitForAlarm result :4
,D/LightsService(  766): [api] onReceive : SvcLEDReceiver re-enables LightSenor and sends MSG_FORCEDSVCLEDTASK
I/SensorManagerA(  766): getReportingMode :: sensor.mType = 5
D/Sensors (  766): LightSensor setDelay = 200000000
D/Sensors (  766): LightSensor setSensorDelay = 200000000
D/Sensors (  766): Light sensor flush: not enabled 0
D/Sensors (  766): LightSensor enable = 1
D/Sensors (  766): LightSensor enableSensor = 1
D/SensorManager(  766): registerListener :: 16, CM36686 Light Sensor, 200000, 0,  
,D/Finsky  ( 3513): [1] DailyHygiene.onStartCommand: Beginning daily hygiene
,V/AlarmManager(  766): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,D/BatteryService(  766): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-8, charge type:1, power sharing:false
,D/BatteryService(  766): stay LED for fully charged
,D/BatteryService(  766): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  766): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 1063): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1063): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1063):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1063): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1063): checkOverflow(384), More:false, Req:false Child:2
,V/GLSActivity( 1298): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Sensors (  766): LightSensor enable = 0
,D/Sensors (  766): LightSensor enableSensor = 0
,D/SensorManager(  766): unregisterListener ::   
D/LightsService(  766): [SvcLED]  onSensorChanged::light value = 10
,D/LightsService(  766): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
V/GLSActivity( 1298): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/SMD     (  240): DCD ON
,I/System.out( 3513): Thread-336 calls detatch()
,W/Finsky  ( 3513): [1] DailyHygiene$1.onErrorResponse: Unable to preload experiments: com.android.volley.NoConnectionError: java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
,V/GLSActivity( 1298): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1298): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/System.out( 3513): Thread-337 calls detatch()
,D/AmoledAdjustTimer(  766): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,V/GLSActivity( 1298): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1298): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/System.out( 3513): Thread-336 calls detatch()
,W/Finsky  ( 3513): [1] LibraryUpdateListener.onErrorResponse: Library replication failed: com.android.volley.NoConnectionError: java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
,D/dalvikvm( 3513): GC_CONCURRENT freed 1946K, 42% free 11250K/19208K, paused 4ms+5ms, total 62ms
,V/GLSActivity( 1298): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1298): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/AlarmManager(  766): waitForAlarm result :8
,V/AlarmManager(  766): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1063): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1063): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1063): checkOverflow(384), More:false, Req:false Child:2
,I/System.out( 3513): Thread-337 calls detatch()
,W/Finsky  ( 3513): [1] UpdateChecker$1$2.onErrorResponse: Update check failed: com.android.volley.NoConnectionError: java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
,D/Finsky  ( 3513): [1] DailyHygiene.access$600: Logging device features
,V/AlarmManager(  766): waitForAlarm result :4
,V/AlarmManager(  766): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
D/Finsky  ( 3513): [1] DailyHygiene.reschedule: Scheduling new run in 32 minutes (failures=2)
,D/DeviceConnectionService( 1207): client connected with version: 8296000
,D/WearableService( 1207): callingUid 10011, callindPid: 1207
,D/Finsky  ( 3513): [364] FlushLogsService.onHandleIntent: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 3513): [1] VerifyInstalledPackagesReceiver.onReceive: Skipping verification because network inactive
,D/Finsky  ( 3513): [1] WearSupportService$8.onConnectionFailed: onConnectionFailed: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/Finsky  ( 3513): [1] WearSupportService.access$100: Dropping command=hygiene due to Gms not connected
,V/GLSActivity( 1298): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1298): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  766): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,E/Watchdog(  766): !@Sync 22
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  766): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  766): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,V/AlarmManager(  766): waitForAlarm result :4
,V/AlarmManager(  766): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,D/BatteryService(  766): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-12, charge type:1, power sharing:false
,D/BatteryService(  766): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  766): mCoverManager.getCoverState() : true
,D/BatteryService(  766): stay LED for fully charged
D/KeyguardUpdateMonitor( 1063): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1063): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1063):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1063): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1063): checkOverflow(384), More:false, Req:false Child:2
,D/dalvikvm( 3513): GC_CONCURRENT freed 1938K, 42% free 11240K/19208K, paused 4ms+4ms, total 49ms
,D/Finsky  ( 3513): [349] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 3513): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  766): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  766): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,D/BatteryService(  766): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-11, charge type:1, power sharing:false
,D/BatteryService(  766): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  766): mCoverManager.getCoverState() : true
,D/BatteryService(  766): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1063): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1063): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1063):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1063): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1063): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  766): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  766): SIOP:: AP = 300, Delta = 0
,D/BatteryService(  766): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-11, charge type:1, power sharing:false
,D/BatteryService(  766): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  766): stay LED for fully charged
,D/UiModeManager(  766): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1063): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1063): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1063):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1063): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1063): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,E/Watchdog(  766): !@Sync 23
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  766): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  766): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,D/BatteryService(  766): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-10, charge type:1, power sharing:false
,D/BatteryService(  766): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  766): stay LED for fully charged
,D/UiModeManager(  766): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1063): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1063): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1063):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1063): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1063): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  766): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,I/PowerManagerService(  766): [PWL] Off : 680s ago
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  766): SIOP:: AP = 300, Delta = 0
,D/BatteryService(  766): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-10, charge type:1, power sharing:false
,D/BatteryService(  766): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  766): stay LED for fully charged
,D/UiModeManager(  766): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1063): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1063): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1063):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1063): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1063): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  766): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,V/AlarmManager(  766): waitForAlarm result :8
,V/AlarmManager(  766): ClockReceiver onReceive() ACTION_TIME_TICK
,V/AlarmManager(  766): ___SyncScheduler (v3) ACTIVATED___
,V/AlarmManager(  766): <AppSync3 Whitelist>
,D/KeyguardUpdateMonitor( 1063): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1063): handleTimeUpdate
V/AlarmManager(  766): (AppSync) ### 0 added ###
,D/STATUSBAR-IconMerger( 1063): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  766): SIOP:: AP = 300, Delta = 0
,D/BatteryService(  766): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-10, charge type:1, power sharing:false
,D/BatteryService(  766): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  766): mCoverManager.getCoverState() : true
,D/BatteryService(  766): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1063): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1063): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1063):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1063): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1063): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,E/Watchdog(  766): !@Sync 24
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  766): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  766): SIOP:: AP = 300, Delta = 0
,D/dalvikvm(  766): GC_CONCURRENT freed 3423K, 59% free 23396K/56944K, paused 19ms+39ms, total 424ms
,E/SMD     (  240): DCD ON
,D/BatteryService(  766): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  766): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  766): stay LED for fully charged
,D/UiModeManager(  766): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1063): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1063): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1063):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1063): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1063): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  766): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  766): SIOP:: AP = 300, Delta = 0
,D/BatteryService(  766): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:6, charge type:1, power sharing:false
,D/BatteryService(  766): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  766): stay LED for fully charged
,D/UiModeManager(  766): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1063): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1063): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1063):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1063): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1063): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  766): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  766): SIOP:: AP = 300, Delta = 0
,D/BatteryService(  766): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  766): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  766): mCoverManager.getCoverState() : true
,D/BatteryService(  766): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1063): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1063): handleBatteryUpdate
,E/SMD     (  240): DCD ON
,D/STATUSBAR-PhoneStatusBar( 1063):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1063): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1063): checkOverflow(384), More:false, Req:false Child:2
,E/Watchdog(  766): !@Sync 25
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  766): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  766): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,D/BatteryService(  766): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-10, charge type:1, power sharing:false
,D/BatteryService(  766): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  766): stay LED for fully charged
,D/UiModeManager(  766): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1063): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1063): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1063):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1063): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1063): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  766): prevTemp = 272, currTemp = 271, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  766): SIOP:: AP = 300, Delta = 0
,D/BatteryService(  766): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-9, charge type:1, power sharing:false
,D/BatteryService(  766): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  766): stay LED for fully charged
,D/UiModeManager(  766): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1063): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1063): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1063):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1063): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1063): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  766): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,V/AlarmManager(  766): waitForAlarm result :8
,V/AlarmManager(  766): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1063): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1063): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1063): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  766): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,D/BatteryService(  766): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-10, charge type:1, power sharing:false
,D/BatteryService(  766): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  766): stay LED for fully charged
,D/UiModeManager(  766): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1063): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1063): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1063):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1063): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1063): checkOverflow(384), More:false, Req:false Child:2
,E/Watchdog(  766): !@Sync 26
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  766): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  766): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,I/PowerManagerService(  766): [PWL] Off : 765s ago
,D/BatteryService(  766): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService(  766): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  766): stay LED for fully charged
,D/UiModeManager(  766): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1063): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1063): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1063):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1063): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1063): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  766): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  766): SIOP:: AP = 300, Delta = 0
,D/BatteryService(  766): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  766): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  766): stay LED for fully charged
,D/UiModeManager(  766): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1063): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1063): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1063):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1063): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1063): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  766): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  766): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,D/BatteryService(  766): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  766): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  766): mCoverManager.getCoverState() : true
,D/BatteryService(  766): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1063): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1063): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1063):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1063): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1063): checkOverflow(384), More:false, Req:false Child:2
,E/Watchdog(  766): !@Sync 27
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  766): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  766): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,D/BatteryService(  766): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-8, charge type:1, power sharing:false
,D/BatteryService(  766): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  766): mCoverManager.getCoverState() : true
,D/BatteryService(  766): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1063): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1063): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1063):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1063): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1063): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  766): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  766): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  766): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,V/AlarmManager(  766): waitForAlarm result :8
,V/AlarmManager(  766): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1063): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1063): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1063): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  766): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,D/BatteryService(  766): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-4, charge type:1, power sharing:false
,D/BatteryService(  766): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  766): stay LED for fully charged
,D/UiModeManager(  766): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1063): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1063): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1063):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1063): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1063): checkOverflow(384), More:false, Req:false Child:2
,E/Watchdog(  766): !@Sync 28
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  766): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  766): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,D/BatteryService(  766): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:4, charge type:1, power sharing:false
,D/BatteryService(  766): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  766): stay LED for fully charged
,D/UiModeManager(  766): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1063): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1063): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1063):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1063): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1063): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  766): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  766): SIOP:: AP = 300, Delta = 0
,D/BatteryService(  766): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:5, charge type:1, power sharing:false
,D/BatteryService(  766): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  766): stay LED for fully charged
,D/UiModeManager(  766): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1063): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1063): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1063):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1063): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1063): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  766): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  766): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,D/BatteryService(  766): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:4, charge type:1, power sharing:false
,D/BatteryService(  766): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  766): mCoverManager.getCoverState() : true
,D/BatteryService(  766): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1063): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1063): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1063):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1063): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1063): checkOverflow(384), More:false, Req:false Child:2
,E/Watchdog(  766): !@Sync 29
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  766): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  766): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,I/PowerManagerService(  766): [PWL] Off : 855s ago
,D/BatteryService(  766): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-9, charge type:1, power sharing:false
,D/BatteryService(  766): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  766): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1063): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1063): handleBatteryUpdate
D/UiModeManager(  766): mCoverManager.getCoverState() : true
,D/STATUSBAR-PhoneStatusBar( 1063):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1063): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1063): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  766): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  766): SIOP:: AP = 300, Delta = 0
,D/BatteryService(  766): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-2, charge type:1, power sharing:false
,D/BatteryService(  766): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  766): stay LED for fully charged
,D/UiModeManager(  766): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1063): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1063): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1063):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1063): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1063): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  766): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,V/AlarmManager(  766): waitForAlarm result :8
,V/AlarmManager(  766): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1063): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1063): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1063): checkOverflow(384), More:false, Req:false Child:2
,D/TimaService(  766): TIMA: TimaService scheduler is intialized. 
,D/TimaService(  766): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService(  766): TimaServiceHandler.handleMessage what =1
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  766): SIOP:: AP = 300, Delta = 0
,I/TLC_TIMA_PKM_measure_kernel(  766): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel(  766): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService(  766): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService(  766): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/SMD     (  240): DCD ON
,D/BatteryService(  766): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  766): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  766): stay LED for fully charged
,D/UiModeManager(  766): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1063): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1063): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1063):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1063): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1063): checkOverflow(384), More:false, Req:false Child:2
,E/Watchdog(  766): !@Sync 30
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  766): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  766): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,D/BatteryService(  766): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-12, charge type:1, power sharing:false
,D/BatteryService(  766): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  766): stay LED for fully charged
,D/UiModeManager(  766): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1063): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1063): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1063):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1063): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1063): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  766): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  766): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  766): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  766): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,E/Watchdog(  766): !@Sync 31
,V/GLSActivity( 1298): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1298): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  766): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  766): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,D/BatteryService(  766): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-1, charge type:1, power sharing:false
,D/BatteryService(  766): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  766): stay LED for fully charged
,D/UiModeManager(  766): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1063): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1063): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1063):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1063): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1063): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  766): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  766): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  766): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,V/AlarmManager(  766): waitForAlarm result :8
,V/AlarmManager(  766): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1063): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1063): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1063): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  766): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,D/BatteryService(  766): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  766): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  766): stay LED for fully charged
,D/UiModeManager(  766): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1063): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1063): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1063):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1063): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1063): checkOverflow(384), More:false, Req:false Child:2
,E/Watchdog(  766): !@Sync 32
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  766): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  766): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  766): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,I/PowerManagerService(  766): [PWL] Off : 950s ago
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  766): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,D/BatteryService(  766): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  766): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  766): mCoverManager.getCoverState() : true
,D/BatteryService(  766): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1063): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1063): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1063):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1063): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1063): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  766): prevTemp = 271, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  766): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,E/Watchdog(  766): !@Sync 33
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  766): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  766): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,D/BatteryService(  766): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-9, charge type:1, power sharing:false
,D/BatteryService(  766): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  766): mCoverManager.getCoverState() : true
,D/BatteryService(  766): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1063): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1063): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1063):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1063): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1063): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  766): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  766): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,D/BatteryService(  766): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-10, charge type:1, power sharing:false
,D/BatteryService(  766): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  766): mCoverManager.getCoverState() : true
,D/BatteryService(  766): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1063): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1063): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1063):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1063): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1063): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  766): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,V/AlarmManager(  766): waitForAlarm result :8
,V/AlarmManager(  766): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1063): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1063): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1063): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  766): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,E/Watchdog(  766): !@Sync 34
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  766): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  766): SIOP:: AP = 300, Delta = 0
,D/BatteryService(  766): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-3, charge type:1, power sharing:false
,D/BatteryService(  766): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  766): mCoverManager.getCoverState() : true
,D/BatteryService(  766): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1063): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1063): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1063):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1063): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1063): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  766): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  766): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  766): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  766): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,D/BatteryService(  766): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-2, charge type:1, power sharing:false
,D/BatteryService(  766): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  766): stay LED for fully charged
,D/UiModeManager(  766): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1063): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1063): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1063):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1063): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1063): checkOverflow(384), More:false, Req:false Child:2
,E/Watchdog(  766): !@Sync 35
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  766): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  766): SIOP:: AP = 300, Delta = 0
,D/BatteryService(  766): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:8, charge type:1, power sharing:false
,D/BatteryService(  766): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  766): stay LED for fully charged
,D/UiModeManager(  766): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1063): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1063): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1063):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1063): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1063): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  766): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  766): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,D/BatteryService(  766): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService(  766): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  766): stay LED for fully charged
,D/UiModeManager(  766): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1063): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1063): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1063):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1063): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1063): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  766): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,I/PowerManagerService(  766): [PWL] Off : 1050s ago
,V/AlarmManager(  766): waitForAlarm result :8
,V/AlarmManager(  766): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1063): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1063): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1063): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  766): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,D/BatteryService(  766): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  766): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  766): stay LED for fully charged
,D/UiModeManager(  766): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1063): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1063): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1063):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1063): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1063): checkOverflow(384), More:false, Req:false Child:2
,E/Watchdog(  766): !@Sync 36
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  766): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  766): SIOP:: AP = 300, Delta = 0
,D/BatteryService(  766): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-12, charge type:1, power sharing:false
,D/BatteryService(  766): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  766): mCoverManager.getCoverState() : true
,D/BatteryService(  766): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1063): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1063): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1063):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1063): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1063): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  766): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  766): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  766): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  766): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,E/Watchdog(  766): !@Sync 37
,D/BatteryService(  766): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-13, charge type:1, power sharing:false
,D/BatteryService(  766): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  766): stay LED for fully charged
,D/UiModeManager(  766): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1063): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1063): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1063):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1063): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1063): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  766): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  766): SIOP:: AP = 300, Delta = 0
,D/BatteryService(  766): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-11, charge type:1, power sharing:false
,D/BatteryService(  766): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  766): stay LED for fully charged
,D/UiModeManager(  766): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1063): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1063): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1063):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1063): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1063): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  766): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  766): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  766): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,V/AlarmManager(  766): waitForAlarm result :8
,V/AlarmManager(  766): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1063): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1063): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1063): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  766): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,E/Watchdog(  766): !@Sync 38
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  766): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  766): SIOP:: AP = 300, Delta = 0
,D/BatteryService(  766): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,E/SMD     (  240): DCD ON
D/BatteryService(  766): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  766): mCoverManager.getCoverState() : true
,D/BatteryService(  766): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1063): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1063): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1063):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1063): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1063): checkOverflow(384), More:false, Req:false Child:2
,D/AmoledAdjustTimer(  766): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  766): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,D/BatteryService(  766): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:2, charge type:1, power sharing:false
,D/BatteryService(  766): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  766): stay LED for fully charged
,D/UiModeManager(  766): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1063): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1063): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1063):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1063): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1063): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  766): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  766): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,E/Watchdog(  766): !@Sync 39
,D/BatteryService(  766): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  766): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  766): stay LED for fully charged
,D/UiModeManager(  766): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1063): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1063): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1063):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1063): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1063): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  766): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,I/PowerManagerService(  766): [PWL] Off : 1155s ago
,D/SSRMv2:SIOP(  766): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,D/BatteryService(  766): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-14, charge type:1, power sharing:false
,D/BatteryService(  766): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  766): stay LED for fully charged
,D/UiModeManager(  766): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1063): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1063): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1063):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1063): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1063): checkOverflow(384), More:false, Req:false Child:2
,D/AmoledAdjustTimer(  766): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  766): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,D/BatteryService(  766): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-1, charge type:1, power sharing:false
,D/BatteryService(  766): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  766): stay LED for fully charged
,D/UiModeManager(  766): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1063): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1063): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1063):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1063): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1063): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  766): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,V/AlarmManager(  766): waitForAlarm result :8
,V/AlarmManager(  766): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1063): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1063): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1063): checkOverflow(384), More:false, Req:false Child:2
,D/TimaService(  766): TIMA: TimaService scheduler is intialized. 
,D/TimaService(  766): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService(  766): TimaServiceHandler.handleMessage what =1
,E/SMD     (  240): DCD ON
,I/TLC_TIMA_PKM_measure_kernel(  766): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel(  766): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
D/SSRMv2:SIOP(  766): SIOP:: AP = 300, Delta = 0
,D/TimaService(  766): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService(  766): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/SMD     (  240): DCD ON
,E/Watchdog(  766): !@Sync 40
,D/BatteryService(  766): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  766): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  766): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1063): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1063): handleBatteryUpdate
D/UiModeManager(  766): mCoverManager.getCoverState() : true
,D/STATUSBAR-PhoneStatusBar( 1063):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1063): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1063): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  766): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  766): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,D/BatteryService(  766): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-9, charge type:1, power sharing:false
,D/BatteryService(  766): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  766): stay LED for fully charged
,D/UiModeManager(  766): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1063): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1063): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1063):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1063): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1063): checkOverflow(384), More:false, Req:false Child:2
,D/AmoledAdjustTimer(  766): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,D/dalvikvm(  766): GC_CONCURRENT freed 3433K, 60% free 23345K/56944K, paused 20ms+33ms, total 401ms
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  766): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,D/BatteryService(  766): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-10, charge type:1, power sharing:false
,D/BatteryService(  766): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  766): mCoverManager.getCoverState() : true
,D/BatteryService(  766): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1063): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1063): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1063):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1063): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1063): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  766): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  766): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,E/Watchdog(  766): !@Sync 41
,D/BatteryService(  766): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-9, charge type:1, power sharing:false
,D/BatteryService(  766): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  766): stay LED for fully charged
,D/UiModeManager(  766): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1063): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1063): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1063):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1063): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1063): checkOverflow(384), More:false, Req:false Child:2
,V/GLSActivity( 1298): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1298): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  766): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  766): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,D/BatteryService(  766): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-10, charge type:1, power sharing:false
,D/BatteryService(  766): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  766): mCoverManager.getCoverState() : true
,D/BatteryService(  766): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1063): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1063): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1063):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1063): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1063): checkOverflow(384), More:false, Req:false Child:2
,D/AmoledAdjustTimer(  766): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  766): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,V/AlarmManager(  766): waitForAlarm result :8
,I/SensorManagerA(  766): getReportingMode :: sensor.mType = 5
,D/Sensors (  766): LightSensor setDelay = 200000000
,D/Sensors (  766): LightSensor setSensorDelay = 200000000
,D/Sensors (  766): Light sensor flush: not enabled 0
,D/Sensors (  766): LightSensor enable = 1
,D/LightsService(  766): [api] onReceive : SvcLEDReceiver re-enables LightSenor and sends MSG_FORCEDSVCLEDTASK
D/Sensors (  766): LightSensor enableSensor = 1
D/SensorManager(  766): registerListener :: 16, CM36686 Light Sensor, 200000, 0,  
,D/BatteryService(  766): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-11, charge type:1, power sharing:false
,D/BatteryService(  766): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  766): stay LED for fully charged
,D/UiModeManager(  766): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1063): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1063): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1063):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1063): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1063): checkOverflow(384), More:false, Req:false Child:2
,D/Sensors (  766): LightSensor enable = 0
,D/Sensors (  766): LightSensor enableSensor = 0
,D/LightsService(  766): [SvcLED]  onSensorChanged::light value = 18
,D/SensorManager(  766): unregisterListener ::   
D/LightsService(  766): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  766): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,V/AlarmManager(  766): waitForAlarm result :8
,V/AlarmManager(  766): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1063): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1063): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1063): checkOverflow(384), More:false, Req:false Child:2
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  766): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,E/Watchdog(  766): !@Sync 42
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  766): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  766): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  766): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/SSRMv2:SIOP(  766): SIOP:: AP = 300, Delta = 0
,E/SMD     (  240): DCD ON
,E/SMD     (  240): DCD ON
,D/AmoledAdjustTimer(  766): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  240): DCD ON
,I/PowerManagerService(  766): [PWL] Off : 1265s ago
,TIME-OUT KILL (timeout was 1200000ms),E/SMD     (  240): DCD ON
D/SSRMv2:SIOP(  766): SIOP:: AP = 300, Delta = 0
D/AndroidRuntime( 5146): 
D/AndroidRuntime( 5146): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 5146): CheckJNI is OFF
D/AndroidRuntime( 5146): setted country_code = Poland
D/AndroidRuntime( 5146): setted countryiso_code = PL
D/AndroidRuntime( 5146): setted sales_code = XEO
D/AndroidRuntime( 5146): readGMSProperty: start
D/AndroidRuntime( 5146): readGMSProperty: already setted!!
D/AndroidRuntime( 5146): readGMSProperty: end
D/AndroidRuntime( 5146): addProductProperty: start
D/dalvikvm( 5146): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 5146): Added shared lib libjavacore.so 0x0
D/dalvikvm( 5146): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 5146): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 5146): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
E/memtrack( 5146): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 5146): failed to load memtrack module: -2
D/dalvikvm( 5146): Note: class Landroid/app/ActivityManagerNative; has 192 unimplemented (abstract) methods
D/AndroidRuntime( 5146): Calling main entry com.android.commands.pm.Pm
D/PackageManagerService(  766): deletePackageAsUser- pkg:com.test.thalitest, userId:0
D/PersonaManagerService(  766): isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
D/PersonaManagerService(  766): isFromApprovedUnInstaller: isApproved : true
D/PersonaManagerService(  766): isFromApprovedUnInstaller: isApproved before exit: true
D/PackageManager(  766): deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag3
D/PackageManager(  766): deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag3
D/PackageManagerService(  766): deletePackage- pkg:com.test.thalitest, edmuserId:0
D/PackageManagerService(  766): deletePackage- pkg:com.test.thalitest, edmuserId:-1
D/ApplicationPolicy(  766): getApplicationUninstallationEnabled
D/ApplicationPolicy(  766): getApplicationUninstallationEnabled :  enabled true
D/PackageManagerService(  766): deletePackageX- pkg:com.test.thalitest, userId:0
D/PackageManager(  766): START PACKAGE DELETE: observer{1122587176}
D/PackageManager(  766): pkg{<packageName>}
D/PackageManager(  766): user{0}
D/PackageManager(  766): deletePackageAsUser : uid = 2000 userId = 0
D/PackageManager(  766): [MSG] DELETE_PACKAGE_AS_USER
D/PackageManager(  766): !@killApplicatoin: 10179, uninstall pkg
I/ActivityManager(  766): Killing 4580:com.test.thalitest/u0a179 (adj 9): stop com.test.thalitest
E/Watchdog(  766): !@Sync 43
D/PackageManager(  766): Sending to user 0: act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000000 Bundle[{android.intent.extra.REMOVED_FOR_ALL_USERS=true, android.intent.extra.UID=10179, android.intent.extra.DATA_REMOVED=true, android.intent.extra.user_handle=0}]
D/PackageManager(  766): Sending to user 0: act=android.intent.action.PACKAGE_FULLY_REMOVED dat=package:com.test.thalitest flg=0x4000000 Bundle[{android.intent.extra.REMOVED_FOR_ALL_USERS=true, android.intent.extra.UID=10179, android.intent.extra.DATA_REMOVED=true, android.intent.extra.user_handle=0}]
D/dalvikvm( 1783): GC_EXPLICIT freed 626K, 40% free 11698K/19208K, paused 35ms+15ms, total 81ms
D/AdaptiveEventManager( 1063): action=android.intent.action.PACKAGE_REMOVED
I/FPMS_FingerprintManagerService( 1082): onReceive: android.intent.action.PACKAGE_REMOVED
I/InputReader(  766): Reconfiguring input devices.  changes=0x00000010
D/dalvikvm( 1403): GC_EXPLICIT freed 4287K, 48% free 10022K/19208K, paused 10ms+4ms, total 79ms
W/GeofencerStateMachine( 1207): Ignoring removeGeofence because network location is disabled.
D/QuickConnect[1.1][2] ( 3135): SconnectManager.onReceiver - action : android.intent.action.PACKAGE_REMOVED, package : com.test.thalitest
I/PackageManager(  766):   Action: "android.intent.action.SENDTO"
I/PackageManager(  766):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  766):   Scheme: "sms"
I/PackageManager(  766): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
I/SELinux ( 5171): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5171):  
W/InputMethodInfo(  766): Duplicated subtype definition found: , voice
I/PackageManager(  766):   Action: "android.intent.action.SENDTO"
I/PackageManager(  766):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  766):   Scheme: "smsto"
I/PackageManager(  766): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
I/PackageManager(  766):   Action: "android.intent.action.SENDTO"
I/PackageManager(  766):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  766):   Scheme: "mms"
I/PackageManager(  766): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
D/dalvikvm(  250): GC_EXPLICIT freed 42K, 51% free 9508K/19208K, paused 2ms+3ms, total 28ms
I/PackageManager(  766):   Action: "android.intent.action.SENDTO"
I/PackageManager(  766):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  766):   Scheme: "mmsto"
I/SELinux ( 5171): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5171):  
I/SELinux ( 5171):  
I/SELinux ( 5171): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 5171): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 5171): >>>>> Normal User
E/dalvikvm( 5171): >>>>> com.sec.esdk.elm [ userId:0 | appId:10094 ]
I/PackageManager(  766): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
E/SELinux ( 5171): [DEBUG] seapp_context_lookup: seinfoCategory = platform
D/dalvikvm(  250): GC_EXPLICIT freed <1K, 51% free 9508K/19208K, paused 2ms+3ms, total 21ms
D/dalvikvm(  250): GC_EXPLICIT freed <1K, 51% free 9508K/19208K, paused 2ms+3ms, total 20ms
D/TimaKeyStoreProvider( 5171): in addTimaSignatureService
I/PackageManager(  766):   Action: "android.intent.action.SENDTO"
I/PackageManager(  766):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  766):   Scheme: "sms"
D/TimaKeyStoreProvider( 5171): Cannot add TimaSignature Service, License check Failed
I/PackageManager(  766): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
D/ActivityThread( 5171): Added TimaKesytore provider
D/dalvikvm( 2113): GC_EXPLICIT freed 1057K, 42% free 11227K/19208K, paused 3ms+4ms, total 220ms
D/dalvikvm(  766): GC_EXPLICIT freed 1712K, 59% free 23436K/56944K, paused 6ms+13ms, total 225ms
I/PackageManager(  766):   Action: "android.intent.action.SENDTO"
I/PackageManager(  766):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  766):   Scheme: "smsto"
I/PackageManager(  766): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
I/PackageManager(  766):   Action: "android.intent.action.SENDTO"
I/PackageManager(  766):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  766):   Scheme: "mms"
I/PackageManager(  766): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
D/RCPManagerService(  766): PackageReceiver onReceive()
I/PackageManager(  766):   Action: "android.intent.action.SENDTO"
I/PackageManager(  766):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  766):   Scheme: "mmsto"
I/HarmonyEASService(  766): onReceive : android.intent.action.PACKAGE_REMOVED for 0
I/PackageManager(  766): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
W/ActivityManager(  766): Permission Denial: getCurrentUser() from pid=5171, uid=10094 requires android.permission.INTERACT_ACROSS_USERS
D/elm:14132( 5171): ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
D/elm:14132( 5171): ELMEngine.ELMEngine( context ).
D/elm:14132( 5171): MDMBridge.setEnterpriseBridge()
D/elm:14132( 5171): ELMAbstractReceiver : Receive Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
D/elm:14132( 5171): ElmAgentService : onCreate()
D/elm:14132( 5171): ElmAgentService : onHandleIntent() Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
D/elm:14132( 5171): MainReceiver.listeningToPackageRemoved()
D/elm:14132( 5171): MDMBridge.getInstance()
D/elm:14132( 5171): MDMBridge.getAllLicenseInfoFromSDK()
D/elm:14132( 5171): MDMBridge.getAllLicenseInfoFromSDK()
D/EnterpriseDeviceManagerService(  766): Package has changed for user 0
D/EnterpriseDeviceManagerService(  766): Admin package name: com.google.android.gms
W/Resources(  766): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
I/SELinux ( 5186): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5186):  
D/elm:14132( 5171): MainReceiver.listeningToPackageRemoved(). SEND to KLMS. Remove All KNOX/ONS License
D/elm:14132( 5171): ElmAgentService : onDestroy().
W/Resources(  766): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
I/SELinux ( 5186): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5186):  
I/SELinux ( 5186):  
I/SELinux ( 5186): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 5186): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 5186): >>>>> Normal User
E/dalvikvm( 5186): >>>>> com.sec.android.app.mss [ userId:0 | appId:10021 ]
E/SELinux ( 5186): [DEBUG] seapp_context_lookup: seinfoCategory = platform
D/TimaKeyStoreProvider( 5186): in addTimaSignatureService
D/TimaKeyStoreProvider( 5186): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 5186): Added TimaKesytore provider
D/BackupManagerService(  766): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
V/BackupManagerService(  766): removePackageParticipantsLocked: uid=10179 #1
D/dalvikvm(  766): GC_EXPLICIT freed 794K, 59% free 23598K/56944K, paused 6ms+19ms, total 237ms
W/Resources(  766): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/PackageManager(  766): delete sourFile : 
W/Resources(  766): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/PackageManager(  766): delete native library directory: 
D/PackageManager(  766): return delete result to caller: 1122587176
D/AndroidRuntime( 5146): Shutting down VM
D/dalvikvm( 5146): GC_CONCURRENT freed 96K, 14% free 670K/772K, paused 0ms+0ms, total 2ms
D/PackageManager(  766): returnCode: 1
I/PackageManager(  766):   Action: "android.intent.action.SENDTO"
I/PackageManager(  766):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  766):   Scheme: "sms"
I/PackageManager(  766): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
W/ActivityManager(  766): Permission Denial: getCurrentUser() from pid=5186, uid=10021 requires android.permission.INTERACT_ACROSS_USERS
I/PackageManager(  766):   Action: "android.intent.action.SENDTO"
I/PackageManager(  766):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  766):   Scheme: "smsto"
I/PackageManager(  766): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
I/PackageManager(  766):   Action: "android.intent.action.SENDTO"
I/PackageManager(  766):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  766):   Scheme: "mms"
I/PackageManager(  766): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
W/Resources(  766): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
I/PackageManager(  766):   Action: "android.intent.action.SENDTO"
I/PackageManager(  766):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  766):   Scheme: "mmsto"
I/PackageManager(  766): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
I/PCWCLIENTTRACE_PushUtil( 4431): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 4431): sales region : global
I/PCWCLIENTTRACE_PushUtil( 4431): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver( 4431): [onReceive] - android.intent.action.PACKAGE_REMOVED
W/Resources(  766): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  766): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  766): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  766): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
I/SA      ( 4602): [SUR] onReceive log=[SA = 2.0.0117 V = 19 HWD = 1280X720 2.0 dpi = 320  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = kmini3g P = kmini3gxx I = KOT49H M = SM-G800H OKLEFT false DIS KOT49H.G800HXXU1ANK2 PSS = 4.497045606779314  ]
I/SA      ( 4602): [SUR] onReceive Intent=[ action_PACKAGE_REMOVED package ]
W/Resources(  766): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  766): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
I/ActivityManager(  766): Killing 3982:com.sec.android.app.videoplayer/u0a52 (adj 15): empty #43
W/Resources(  766): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  766): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  766): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
W/Resources(  766): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  766): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  766): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
I/IcingCorporaProvider( 2113): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
I/SELinux ( 5207): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5207):  
I/CrashAnrDetector(  766): onPackageRemoved : com.test.thalitest
D/UsbSettingsManager(  766): clearDefaults: com.test.thalitest
I/SELinux ( 5207): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5207):  
I/SELinux ( 5207):  
I/SELinux ( 5207): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 5207): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 5207): >>>>> Normal User
E/dalvikvm( 5207): >>>>> com.samsung.android.intelligenceservice [ userId:0 | appId:10005 ]
E/SELinux ( 5207): [DEBUG] seapp_context_lookup: seinfoCategory = platform
D/TimaKeyStoreProvider( 5207): in addTimaSignatureService
E/SQLiteLog( 2113): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
D/TimaKeyStoreProvider( 5207): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 5207): Added TimaKesytore provider
E/IcingCorporaProvider( 2113): Exception thrown from notifyTableChanged
E/IcingCorporaProvider( 2113): java.lang.RuntimeException: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/IcingCorporaProvider( 2113): 	at apg.a(PG:301)
E/IcingCorporaProvider( 2113): 	at apg.c(PG:222)
E/IcingCorporaProvider( 2113): 	at clo.b(PG:660)
E/IcingCorporaProvider( 2113): 	at clo.a(PG:651)
E/IcingCorporaProvider( 2113): 	at clo.g(PG:597)
E/IcingCorporaProvider( 2113): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider.update(PG:301)
E/IcingCorporaProvider( 2113): 	at android.content.ContentProvider$Transport.update(ContentProvider.java:287)
E/IcingCorporaProvider( 2113): 	at android.content.ContentResolver.update(ContentResolver.java:1327)
E/IcingCorporaProvider( 2113): 	at clp.Rl(PG:910)
E/IcingCorporaProvider( 2113): 	at clr.tL(PG:827)
E/IcingCorporaProvider( 2113): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateCorporaService.a(PG:1271)
E/IcingCorporaProvider( 2113): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateCorporaService.onHandleIntent(PG:1204)
E/IcingCorporaProvider( 2113): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/IcingCorporaProvider( 2113): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/IcingCorporaProvider( 2113): 	at android.os.Looper.loop(Looper.java:146)
E/IcingCorporaProvider( 2113): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/IcingCorporaProvider( 2113): Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/IcingCorporaProvider( 2113): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/IcingCorporaProvider( 2113): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:745)
E/IcingCorporaProvider( 2113): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/IcingCorporaProvider( 2113): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/IcingCorporaProvider( 2113): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:507)
E/IcingCorporaProvider( 2113): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:418)
E/IcingCorporaProvider( 2113): 	at apa.a(PG:382)
E/IcingCorporaProvider( 2113): 	at apg.i(PG:325)
E/IcingCorporaProvider( 2113): 	at aph.call(PG:215)
E/IcingCorporaProvider( 2113): 	at apg.a(PG:299)
E/IcingCorporaProvider( 2113): 	... 15 more
W/IcingCorporaProvider( 2113): notifyTableChanged failed.
W/IcingCorporaProvider( 2113): Table change notification failed for TableStorageSpec[applications]
I/IcingCorporaProvider( 2113): UpdateCorporaTask done [took 125 ms] updated apps [took 125 ms] 
D/InputReader(  766): Processing first event
I/EventHub(  766): Removing device sec_touchscreen due to epoll hang-up event.
I/EventHub(  766): Removed device: path=/dev/input/event1 name=sec_touchscreen id=6 fd=216 classes=0x94
D/UserAnalysis.PlaceProvider( 5207): Create SecureDbHelper
D/UserAnalysis.UserAnalysisBroadcastReceiver( 5207): Create SecureDbHelper
W/ActivityManager(  766): Permission Denial: getCurrentUser() from pid=5207, uid=10005 requires android.permission.INTERACT_ACROSS_USERS
I/InputReader(  766): Device removed: id=6, name='sec_touchscreen', sources=0x80001002
D/InputReader(  766): Could not retrieve current multitouch slot index.  status=-1
D/InputReader(  766): MultiTouchMotionAccumulator: initial slot number is -1
I/EventHub(  766): Removing device '/dev/input/event1' due to inotify event
I/ActivityManager(  766): Config changes=8 {0 1.0 ?mcc?mnc en_US ldltr sw360dp w360dp h615dp 320dpi nrml long port -touch -keyb/v/h -nav/h s.5}
D/Mms/MmsApp( 3782): [start]    onConfigurationChanged(),newConfig={0 1.0 ?mcc?mnc en_US ldltr sw360dp w360dp h615dp 320dpi nrml long port -touch -keyb/v/h -nav/h s.5}
D/Mms/MmsApp( 3782): [end]    onConfigurationChanged(),newConfig={0 1.0 ?mcc?mnc en_US ldltr sw360dp w360dp h615dp 320dpi nrml long port -touch -keyb/v/h -nav/h s.5}
D/InputDispatcher(  766): setInputDispatchMode: enabled=0, frozen=1
I/SurfaceFlinger(  249): id=18 createSurf (720x1280),2 flag=404, TcreenshotS
D/PermissionCache(  249): checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (228 us)
D/PhoneStatusBar( 1063): mSettingsPanelGravity = 55
D/MenuAppsGridFragment( 1247): onDestroyView
D/PhoneStatusBarView( 1063): marqueeStatusBar:122, mClearCover:0
W/Launcher.MenuAppsGrid( 1247): Trying to exit a state that hasn't been entered
D/KeyguardUpdateMonitor( 1063): sendKeyguardVisibilityChanged(true)
I/SurfaceFlinger(  249): id=16 Removed CatteryCove (8/13)
I/SurfaceFlinger(  249): id=16 Removed CatteryCove (-2/13)
E/Tethering(  766): No numeric data
D/KeyguardUpdateMonitor( 1063): sendKeyguardVisibilityChanged(true)
E/SmartFaceService(  766): onReceive: android.intent.action.CONFIGURATION_CHANGED
E/SmartFaceService(  766): mFolderCoverOpened: (true, true) -> true
D/KeyguardUpdateMonitor( 1063): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1063): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1063): handleKeyguardVisibilityChanged(1)
D/KeyguardHostView( 1063): onSaveInstanceState, tstate=1
D/KeyguardGuestSelectorView( 1063): onDetachedFromWindow()
V/KeyguardUpdateMonitor( 1063): *** unregister callback for com.android.keyguard.CarrierText$1@42342690
V/KeyguardUpdateMonitor( 1063): *** unregister callback for com.android.keyguard.MSimCarrierText$1@423426f8
V/KeyguardUpdateMonitor( 1063): *** unregister callback for com.android.keyguard.CarrierText$1@4243ff68
V/KeyguardUpdateMonitor( 1063): *** unregister callback for com.android.keyguard.EmergencyButton$1@424a58d8
D/KeyguardUpdateMonitor( 1063): sendKeyguardVisibilityChanged(true)
V/KeyguardUpdateMonitor( 1063): *** unregister callback for com.android.keyguard.sec.KeyguardSecurityViewOverlay$1@428d47b0
V/KeyguardUpdateMonitor( 1063): *** unregister callback for com.android.keyguard.KeyguardHostView$2@42677488
D/STATUSBAR-IconMerger( 1063): checkOverflow(384), More:false, Req:false Child:2
E/KeyguardHostView( 1063): KeyguardHostView()
D/ContextualEventManager( 1063): setOnClickHandler()
V/KeyguardHostView( 1063): mIsMultipleLockOn is false
D/KeyguardHostView( 1063): mIsVoiceUnlockOn=false
V/KeyguardHostView( 1063): Initial transport state: 1, pbstate=0
I/KeyguardEffectViewMain( 1063): *** KeyguardEffectView getInstance ***
D/LockPatternUtils( 1063): isPcwEnable = null
D/ContextualEventContainer( 1063): ContextualEventContainer()
V/KeyguardUpdateMonitor( 1063): *** register callback for com.android.keyguard.KeyguardMessageArea$2@42c61958
V/KeyguardUpdateMonitor( 1063): *** unregister callback for null
D/ContextualEventContainer( 1063): onFinishInflate()
D/ContextualEventContainer( 1063): update()
W/ResourceType( 1063): No package identifier when getting name for resource number 0x00000000
D/LockPatternUtils( 1063): isPcwEnable = null
E/Resources( 1063): NotFoundException : Unable to find resource ID #0x0
D/LockPatternUtils( 1063): isPcwEnable = null
D/LockPatternUtils( 1063): isPcwEnable = null
D/KeyguardHostView( 1063): mIsFMMEnabled = false, mIsCarrierLockEnabled = false, mIsCarrierLockPlusEnabled = false
D/LockPatternUtils( 1063): isPcwEnable = null
V/KeyguardHostView( 1063): showPrimarySecurityScreen(turningOff=false)
I/MDPP    ( 1063): Property: Empty
D/KeyguardHostView( 1063): showSecurityScreen(None)
V/KeyguardHostView( 1063): inflating id = 2130903095
D/SecuritySelectorView( 1063): explore by touch mode off
W/ResourceType( 1063): No package identifier when getting name for resource number 0x00000000
E/Resources( 1063): NotFoundException : Unable to find resource ID #0x0
I/KeyguardEffectViewMain( 1063): *** KeyguardEffectView getInstance ***
I/KeyguardEffectViewMain( 1063): *** KeyguardEffectView getInstance ***
D/SecCameraShortcut( 1063): shortcutSetting:1
D/SecCameraShortcut( 1063): isKidsMode:false
D/SecCameraShortcut( 1063): isEmergencyMode:false
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
