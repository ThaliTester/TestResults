#### Test 50650278e3ff7c2_thali05_samsung-SM-G800H Logs


```
--------- beginning of /dev/log/main
I/SELinux ( 4632): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 4632):  
I/SELinux ( 4632):  
I/SELinux ( 4632): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 4632): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 4632): >>>>> Normal User
E/dalvikvm( 4632): >>>>> com.sec.android.service.health [ userId:0 | appId:10016 ]
D/dalvikvm(  242): GC_EXPLICIT freed <1K, 50% free 9506K/19008K, paused 2ms+3ms, total 19ms
E/SELinux ( 4632): [DEBUG] seapp_context_lookup: seinfoCategory = platform
D/TimaKeyStoreProvider( 4632): in addTimaSignatureService
D/TimaKeyStoreProvider( 4632): Cannot add TimaSignature Service, License check Failed
D/dalvikvm(  242): GC_EXPLICIT freed <1K, 50% free 9506K/19008K, paused 3ms+2ms, total 20ms
D/ActivityThread( 4632): Added TimaKesytore provider
,V/MediaPlayer( 4609): decode(61, 33979084, 48105)
V/MediaPlayerService(  245): decode(35, 33979084, 48105)
V/MediaPlayerService(  245): player type = 3
V/AwesomePlayer(  245): setDefault
V/AwesomePlayer(  245): constructor
V/AwesomePlayer(  245): setDefault
V/AwesomePlayer(  245): reset_l()
V/AwesomePlayer(  245): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  245): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  245): mAudioTrackVector clear
V/AwesomePlayer(  245): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  245): mSecMediaClock clear
V/StagefrightPlayer(  245): StagefrightPlayer
V/AwesomePlayer(  245): setListener
V/StagefrightPlayer(  245): initCheck
V/AwesomePlayer(  245): setAudioSink
V/StagefrightPlayer(  245): setDataSource(35, 33979084, 48105)
V/AwesomePlayer(  245): reset_l()
V/AwesomePlayer(  245): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  245): notify(0xb8994c10, 8, 0, 0)
V/AudioCache(  245): ignored
V/AwesomePlayer(  245): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  245): mAudioTrackVector clear
V/AwesomePlayer(  245): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  245): mSecMediaClock clear
V/AwesomePlayer(  245): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer(  245): mBitrate = -1 bits/sec
V/AwesomePlayer(  245): current audio track index (0) is added to vector
V/AwesomePlayer(  245): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer(  245): AwesomePlayer::setDataSource_l():: This is not a DRM content
V/MediaPlayerService(  245): prepare
V/AwesomePlayer(  245): prepareAsync
V/MediaPlayerService(  245): wait for prepare
V/AwesomePlayer(  245): onPrepareAsyncEvent
I/SecMediaClock(  245): SecMediaClock constructor
I/SecMediaClock(  245): reset
V/AwesomePlayer(  245): initAudioDecoder
V/AwesomePlayer(  245): checkOffloadExceptions is true
I/OMXCodec(  245): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
I/OMX     (  245): mDispatchers.add
I/OMXCodec(  245): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec(  245): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec(  245): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec(  245): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/OMXCodec(  245): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer(  245): finishAsyncPrepare_l
V/AwesomePlayer(  245): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache(  245): notify(0xb8994c10, 200, 973, 0)
V/AudioCache(  245): ignored
V/AwesomePlayer(  245): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  245): notify(0xb8994c10, 5, 0, 0)
V/AudioCache(  245): ignored
V/AwesomePlayer(  245): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  245): notify(0xb8994c10, 1, 0, 0)
V/AudioCache(  245): prepared
V/AudioCache(  245): wait - success
V/MediaPlayerService(  245): start
V/StagefrightPlayer(  245): start
V/AwesomePlayer(  245): play
V/AwesomePlayer(  245): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer(  245): startAudioPlayer_l, sendErrorNotification (0)
I/OMXCodec(  245): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec(  245): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec(  245): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/AudioPlayer(  245):  Audioplayer kKeyAudioPCMFormat:1, 2, 0
I/AudioPlayer(  245):  Audioplayer kKeyAudioPCMFormat read fail(2, 1)
V/AudioCache(  245): open(44100, 2, 0x0, 1, 4)
V/AwesomePlayer(  245): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache(  245): notify(0xb8994c10, 6, 0, 0)
V/AudioCache(  245): ignored
V/AwesomePlayer(  245): addBatteryData
V/MediaPlayerService(  245): wait for playback complete
--------- beginning of /dev/log/system
W/ActivityManager(  775): Permission Denial: getCurrentUser() from pid=4632, uid=10016 requires android.permission.INTERACT_ACROSS_USERS
I/OMXCodec(  245): [OMX.google.vorbis.decoder] End Of Stream
V/AwesomePlayer(  245): postAudioEOS delayUs (0)
V/AwesomePlayer(  245): onCheckAudioStatus
V/AwesomePlayer(  245): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  245): onStreamDone
V/AwesomePlayer(  245): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  245): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  245): notify(0xb8994c10, 2, 0, 0)
V/AudioCache(  245): playback complete - thread will wake up later
V/AwesomePlayer(  245): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  245): notify(0xb8994c10, 7, 0, 0)
V/AudioCache(  245): ignored
V/AwesomePlayer(  245): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer(  245): addBatteryData
V/AudioCache(  245): wait - success
V/StagefrightPlayer(  245): reset
V/AwesomePlayer(  245): reset_l()
V/AwesomePlayer(  245): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  245): notify(0xb8994c10, 8, 0, 0)
V/AudioCache(  245): ignored
V/AwesomePlayer(  245): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  245): mAudioTrackVector clear
I/OMXCodec(  245): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec(  245): [OMX.google.vorbis.decoder] stop() sendCommand(0x37, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec(  245): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
I/OMXCodec(  245): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/OMX     (  245): instance freeNode
I/AudioPlayer(  245): reset out
V/AwesomePlayer(  245): reset_l() mAudioPlayer successfully deleted
I/SecMediaClock(  245): SecMediaClock destructor
V/AwesomePlayer(  245): mSecMediaClock clear
V/StagefrightPlayer(  245): ~StagefrightPlayer
V/StagefrightPlayer(  245): reset
V/AwesomePlayer(  245): reset_l()
V/AwesomePlayer(  245): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  245): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  245): mAudioTrackVector clear
V/AwesomePlayer(  245): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  245): mSecMediaClock clear
V/AwesomePlayer(  245): destructor
V/AwesomePlayer(  245): reset_l()
V/AwesomePlayer(  245): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  245): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  245): mAudioTrackVector clear
V/AwesomePlayer(  245): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  245): mSecMediaClock clear
V/MediaPlayer( 4609): decode(63, 33914984, 10421)
V/MediaPlayerService(  245): decode(35, 33914984, 10421)
V/MediaPlayerService(  245): player type = 3
V/AwesomePlayer(  245): setDefault
V/AwesomePlayer(  245): constructor
V/AwesomePlayer(  245): setDefault
V/AwesomePlayer(  245): reset_l()
V/AwesomePlayer(  245): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  245): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  245): mAudioTrackVector clear
V/AwesomePlayer(  245): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  245): mSecMediaClock clear
V/StagefrightPlayer(  245): StagefrightPlayer
V/AwesomePlayer(  245): setListener
V/StagefrightPlayer(  245): initCheck
V/AwesomePlayer(  245): setAudioSink
V/StagefrightPlayer(  245): setDataSource(35, 33914984, 10421)
V/AwesomePlayer(  245): reset_l()
V/AwesomePlayer(  245): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  245): notify(0xb8987928, 8, 0, 0)
V/AudioCache(  245): ignored
V/AwesomePlayer(  245): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  245): mAudioTrackVector clear
V/AwesomePlayer(  245): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  245): mSecMediaClock clear
V/AwesomePlayer(  245): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer(  245): mBitrate = -1 bits/sec
V/AwesomePlayer(  245): current audio track index (0) is added to vector
V/AwesomePlayer(  245): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer(  245): AwesomePlayer::setDataSource_l():: This is not a DRM content
V/MediaPlayerService(  245): prepare
V/AwesomePlayer(  245): prepareAsync
V/MediaPlayerService(  245): wait for prepare
V/AwesomePlayer(  245): onPrepareAsyncEvent
I/SecMediaClock(  245): SecMediaClock constructor
I/SecMediaClock(  245): reset
V/AwesomePlayer(  245): initAudioDecoder
V/AwesomePlayer(  245): checkOffloadExceptions is true
I/OMXCodec(  245): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
I/OMX     (  245): mDispatchers.add
I/OMXCodec(  245): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec(  245): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec(  245): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec(  245): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/OMXCodec(  245): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer(  245): finishAsyncPrepare_l
V/AwesomePlayer(  245): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache(  245): notify(0xb8987928, 200, 973, 0)
V/AudioCache(  245): ignored
V/AwesomePlayer(  245): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  245): notify(0xb8987928, 5, 0, 0)
V/AudioCache(  245): ignored
V/AwesomePlayer(  245): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  245): notify(0xb8987928, 1, 0, 0)
V/AudioCache(  245): prepared
V/AudioCache(  245): wait - success
V/MediaPlayerService(  245): start
V/StagefrightPlayer(  245): start
V/AwesomePlayer(  245): play
V/AwesomePlayer(  245): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer(  245): startAudioPlayer_l, sendErrorNotification (0)
I/OMXCodec(  245): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec(  245): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec(  245): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/AudioPlayer(  245):  Audioplayer kKeyAudioPCMFormat:1, 2, 0
I/AudioPlayer(  245):  Audioplayer kKeyAudioPCMFormat read fail(2, 1)
V/AudioCache(  245): open(44100, 2, 0x0, 1, 4)
V/AwesomePlayer(  245): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache(  245): notify(0xb8987928, 6, 0, 0)
V/AudioCache(  245): ignored
V/AwesomePlayer(  245): addBatteryData
V/MediaPlayerService(  245): wait for playback complete
I/OMXCodec(  245): [OMX.google.vorbis.decoder] End Of Stream
V/AwesomePlayer(  245): postAudioEOS delayUs (0)
V/AwesomePlayer(  245): onCheckAudioStatus
V/AwesomePlayer(  245): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  245): onStreamDone
V/AwesomePlayer(  245): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  245): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  245): notify(0xb8987928, 2, 0, 0)
V/AudioCache(  245): playback complete - thread will wake up later
V/AwesomePlayer(  245): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  245): notify(0xb8987928, 7, 0, 0)
V/AudioCache(  245): ignored
V/AwesomePlayer(  245): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer(  245): addBatteryData
V/AudioCache(  245): wait - success
V/StagefrightPlayer(  245): reset
V/AwesomePlayer(  245): reset_l()
V/AwesomePlayer(  245): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  245): notify(0xb8987928, 8, 0, 0)
V/AudioCache(  245): ignored
V/AwesomePlayer(  245): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  245): mAudioTrackVector clear
I/OMXCodec(  245): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec(  245): [OMX.google.vorbis.decoder] stop() sendCommand(0x38, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec(  245): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
I/OMXCodec(  245): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/OMX     (  245): instance freeNode
D/dalvikvm( 4632): No JNI_OnLoad found in /system/lib/libsecure_storage_jni.so 0x42835e40, skipping init
I/SecureStorage( 4632): [INFO]: SPID(0x00000000)Checking if this device supports Secure Storage
I/SecureStorage( 4632): [INFO]: SPID(0x00000000)This device supports Secure Storage
I/AudioPlayer(  245): reset out
V/AwesomePlayer(  245): reset_l() mAudioPlayer successfully deleted
I/SecMediaClock(  245): SecMediaClock destructor
V/AwesomePlayer(  245): mSecMediaClock clear
V/StagefrightPlayer(  245): ~StagefrightPlayer
V/StagefrightPlayer(  245): reset
V/AwesomePlayer(  245): reset_l()
V/AwesomePlayer(  245): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  245): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  245): mAudioTrackVector clear
V/AwesomePlayer(  245): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  245): mSecMediaClock clear
V/AwesomePlayer(  245): destructor
V/AwesomePlayer(  245): reset_l()
V/AwesomePlayer(  245): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  245): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  245): mAudioTrackVector clear
V/AwesomePlayer(  245): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  245): mSecMediaClock clear
V/MediaPlayer( 4609): decode(64, 37457308, 34198)
V/MediaPlayerService(  245): decode(35, 37457308, 34198)
V/MediaPlayerService(  245): player type = 3
V/AwesomePlayer(  245): setDefault
V/AwesomePlayer(  245): constructor
V/AwesomePlayer(  245): setDefault
V/AwesomePlayer(  245): reset_l()
V/AwesomePlayer(  245): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  245): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  245): mAudioTrackVector clear
V/AwesomePlayer(  245): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  245): mSecMediaClock clear
V/StagefrightPlayer(  245): StagefrightPlayer
V/AwesomePlayer(  245): setListener
V/StagefrightPlayer(  245): initCheck
V/AwesomePlayer(  245): setAudioSink
V/StagefrightPlayer(  245): setDataSource(35, 37457308, 34198)
V/AwesomePlayer(  245): reset_l()
V/AwesomePlayer(  245): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  245): notify(0xb8983558, 8, 0, 0)
V/AudioCache(  245): ignored
V/AwesomePlayer(  245): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  245): mAudioTrackVector clear
V/AwesomePlayer(  245): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  245): mSecMediaClock clear
I/SecureStorage(  294): [INFO]: SPID(0x00000003)Credentials: uid 10016, gid 10016, pid 4632
I/SecureStorage(  294): [INFO]: SPID(0x00000003)Received function mask & code: 0000010C
I/SecureStorage( 4632): [INFO]: SPID(0x00000000)SS Daemon is running
V/AwesomePlayer(  245): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer(  245): mBitrate = -1 bits/sec
V/AwesomePlayer(  245): current audio track index (0) is added to vector
V/AwesomePlayer(  245): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer(  245): AwesomePlayer::setDataSource_l():: This is not a DRM content
V/MediaPlayerService(  245): prepare
V/AwesomePlayer(  245): prepareAsync
V/MediaPlayerService(  245): wait for prepare
V/AwesomePlayer(  245): onPrepareAsyncEvent
I/SecMediaClock(  245): SecMediaClock constructor
I/SecMediaClock(  245): reset
V/AwesomePlayer(  245): initAudioDecoder
V/AwesomePlayer(  245): checkOffloadExceptions is true
I/OMXCodec(  245): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
I/OMX     (  245): mDispatchers.add
I/OMXCodec(  245): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec(  245): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec(  245): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec(  245): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/OMXCodec(  245): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer(  245): finishAsyncPrepare_l
V/AwesomePlayer(  245): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache(  245): notify(0xb8983558, 200, 973, 0)
V/AudioCache(  245): ignored
V/AwesomePlayer(  245): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  245): notify(0xb8983558, 5, 0, 0)
V/AudioCache(  245): ignored
V/AwesomePlayer(  245): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  245): notify(0xb8983558, 1, 0, 0)
V/AudioCache(  245): prepared
V/AudioCache(  245): wait - success
V/MediaPlayerService(  245): start
V/StagefrightPlayer(  245): start
V/AwesomePlayer(  245): play
V/AwesomePlayer(  245): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer(  245): startAudioPlayer_l, sendErrorNotification (0)
I/OMXCodec(  245): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec(  245): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec(  245): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/AudioPlayer(  245):  Audioplayer kKeyAudioPCMFormat:1, 2, 0
I/AudioPlayer(  245):  Audioplayer kKeyAudioPCMFormat read fail(2, 1)
V/AudioCache(  245): open(44100, 2, 0x0, 1, 4)
V/AwesomePlayer(  245): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache(  245): notify(0xb8983558, 6, 0, 0)
V/AudioCache(  245): ignored
V/AwesomePlayer(  245): addBatteryData
V/MediaPlayerService(  245): wait for playback complete
I/SecureStorage( 4632): [INFO]: SPID(0x00000000)Processing data
I/SecureStorage(  294): [INFO]: SPID(0x00000003)Credentials: uid 10016, gid 10016, pid 4632
I/SecureStorage(  294): [INFO]: SPID(0x00000003)Received function mask & code: 00000106
I/OMXCodec(  245): [OMX.google.vorbis.decoder] End Of Stream
V/AwesomePlayer(  245): postAudioEOS delayUs (0)
V/AwesomePlayer(  245): onCheckAudioStatus
V/AwesomePlayer(  245): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  245): onStreamDone
V/AwesomePlayer(  245): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  245): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  245): notify(0xb8983558, 2, 0, 0)
V/AudioCache(  245): playback complete - thread will wake up later
V/AwesomePlayer(  245): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  245): notify(0xb8983558, 7, 0, 0)
V/AudioCache(  245): ignored
V/AwesomePlayer(  245): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer(  245): addBatteryData
V/AudioCache(  245): wait - success
V/StagefrightPlayer(  245): reset
V/AwesomePlayer(  245): reset_l()
V/AwesomePlayer(  245): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  245): notify(0xb8983558, 8, 0, 0)
V/AudioCache(  245): ignored
V/AwesomePlayer(  245): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  245): mAudioTrackVector clear
I/OMXCodec(  245): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec(  245): [OMX.google.vorbis.decoder] stop() sendCommand(0x39, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec(  245): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
I/OMXCodec(  245): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/OMX     (  245): instance freeNode
I/AudioPlayer(  245): reset out
V/AwesomePlayer(  245): reset_l() mAudioPlayer successfully deleted
I/SecMediaClock(  245): SecMediaClock destructor
V/AwesomePlayer(  245): mSecMediaClock clear
V/StagefrightPlayer(  245): ~StagefrightPlayer
V/StagefrightPlayer(  245): reset
V/AwesomePlayer(  245): reset_l()
V/AwesomePlayer(  245): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  245): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  245): mAudioTrackVector clear
V/AwesomePlayer(  245): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  245): mSecMediaClock clear
V/AwesomePlayer(  245): destructor
V/AwesomePlayer(  245): reset_l()
V/AwesomePlayer(  245): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  245): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  245): mAudioTrackVector clear
V/AwesomePlayer(  245): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  245): mSecMediaClock clear
V/MediaPlayer( 4609): decode(65, 33862452, 7405)
V/MediaPlayerService(  245): decode(35, 33862452, 7405)
V/MediaPlayerService(  245): player type = 3
V/AwesomePlayer(  245): setDefault
V/AwesomePlayer(  245): constructor
V/AwesomePlayer(  245): setDefault
V/AwesomePlayer(  245): reset_l()
V/AwesomePlayer(  245): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  245): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  245): mAudioTrackVector clear
V/AwesomePlayer(  245): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  245): mSecMediaClock clear
V/StagefrightPlayer(  245): StagefrightPlayer
V/AwesomePlayer(  245): setListener
V/StagefrightPlayer(  245): initCheck
V/AwesomePlayer(  245): setAudioSink
V/StagefrightPlayer(  245): setDataSource(35, 33862452, 7405)
V/AwesomePlayer(  245): reset_l()
V/AwesomePlayer(  245): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  245): notify(0xb897c660, 8, 0, 0)
V/AudioCache(  245): ignored
V/AwesomePlayer(  245): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  245): mAudioTrackVector clear
V/AwesomePlayer(  245): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  245): mSecMediaClock clear
V/AwesomePlayer(  245): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer(  245): mBitrate = -1 bits/sec
V/AwesomePlayer(  245): current audio track index (0) is added to vector
V/AwesomePlayer(  245): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer(  245): AwesomePlayer::setDataSource_l():: This is not a DRM content
V/MediaPlayerService(  245): prepare
V/AwesomePlayer(  245): prepareAsync
V/MediaPlayerService(  245): wait for prepare
V/AwesomePlayer(  245): onPrepareAsyncEvent
I/SecMediaClock(  245): SecMediaClock constructor
I/SecMediaClock(  245): reset
V/AwesomePlayer(  245): initAudioDecoder
V/AwesomePlayer(  245): checkOffloadExceptions is true
I/OMXCodec(  245): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
I/OMX     (  245): mDispatchers.add
I/OMXCodec(  245): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec(  245): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec(  245): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec(  245): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/OMXCodec(  245): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer(  245): finishAsyncPrepare_l
V/AwesomePlayer(  245): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache(  245): notify(0xb897c660, 200, 973, 0)
V/AudioCache(  245): ignored
V/AwesomePlayer(  245): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  245): notify(0xb897c660, 5, 0, 0)
V/AudioCache(  245): ignored
V/AwesomePlayer(  245): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  245): notify(0xb897c660, 1, 0, 0)
V/AudioCache(  245): prepared
V/AudioCache(  245): wait - success
V/MediaPlayerService(  245): start
V/StagefrightPlayer(  245): start
V/AwesomePlayer(  245): play
V/AwesomePlayer(  245): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer(  245): startAudioPlayer_l, sendErrorNotification (0)
I/OMXCodec(  245): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec(  245): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec(  245): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/AudioPlayer(  245):  Audioplayer kKeyAudioPCMFormat:1, 2, 0
I/AudioPlayer(  245):  Audioplayer kKeyAudioPCMFormat read fail(2, 1)
V/AudioCache(  245): open(44100, 2, 0x0, 1, 4)
V/AwesomePlayer(  245): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache(  245): notify(0xb897c660, 6, 0, 0)
I/AudioPlayer(  245): First fillBuffer call!!
V/AudioCache(  245): ignored
V/AwesomePlayer(  245): addBatteryData
V/MediaPlayerService(  245): wait for playback complete
I/OMXCodec(  245): [OMX.google.vorbis.decoder] End Of Stream
V/AwesomePlayer(  245): postAudioEOS delayUs (0)
V/AwesomePlayer(  245): onCheckAudioStatus
V/AwesomePlayer(  245): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  245): onStreamDone
V/AwesomePlayer(  245): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  245): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  245): notify(0xb897c660, 2, 0, 0)
V/AudioCache(  245): playback complete - thread will wake up later
V/AwesomePlayer(  245): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  245): notify(0xb897c660, 7, 0, 0)
V/AudioCache(  245): ignored
V/AwesomePlayer(  245): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer(  245): addBatteryData
V/AudioCache(  245): wait - success
V/StagefrightPlayer(  245): reset
V/AwesomePlayer(  245): reset_l()
V/AwesomePlayer(  245): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  245): notify(0xb897c660, 8, 0, 0)
V/AudioCache(  245): ignored
V/AwesomePlayer(  245): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  245): mAudioTrackVector clear
I/OMXCodec(  245): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec(  245): [OMX.google.vorbis.decoder] stop() sendCommand(0x3a, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec(  245): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
I/OMXCodec(  245): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/OMX     (  245): instance freeNode
I/AudioPlayer(  245): reset out
V/AwesomePlayer(  245): reset_l() mAudioPlayer successfully deleted
I/SecMediaClock(  245): SecMediaClock destructor
V/AwesomePlayer(  245): mSecMediaClock clear
V/StagefrightPlayer(  245): ~StagefrightPlayer
V/StagefrightPlayer(  245): reset
V/AwesomePlayer(  245): reset_l()
V/AwesomePlayer(  245): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  245): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  245): mAudioTrackVector clear
V/AwesomePlayer(  245): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  245): mSecMediaClock clear
V/AwesomePlayer(  245): destructor
V/AwesomePlayer(  245): reset_l()
V/AwesomePlayer(  245): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  245): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  245): mAudioTrackVector clear
V/AwesomePlayer(  245): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  245): mSecMediaClock clear
V/MediaPlayer( 4609): decode(66, 37547940, 5555)
V/MediaPlayerService(  245): decode(35, 37547940, 5555)
V/MediaPlayerService(  245): player type = 3
V/AwesomePlayer(  245): setDefault
V/AwesomePlayer(  245): constructor
V/AwesomePlayer(  245): setDefault
V/AwesomePlayer(  245): reset_l()
V/AwesomePlayer(  245): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  245): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  245): mAudioTrackVector clear
V/AwesomePlayer(  245): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  245): mSecMediaClock clear
V/StagefrightPlayer(  245): StagefrightPlayer
V/AwesomePlayer(  245): setListener
V/StagefrightPlayer(  245): initCheck
V/AwesomePlayer(  245): setAudioSink
V/StagefrightPlayer(  245): setDataSource(35, 37547940, 5555)
V/AwesomePlayer(  245): reset_l()
V/AwesomePlayer(  245): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  245): notify(0xb8992858, 8, 0, 0)
V/AudioCache(  245): ignored
V/AwesomePlayer(  245): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  245): mAudioTrackVector clear
V/AwesomePlayer(  245): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  245): mSecMediaClock clear
V/AwesomePlayer(  245): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer(  245): mBitrate = -1 bits/sec
V/AwesomePlayer(  245): current audio track index (0) is added to vector
V/AwesomePlayer(  245): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer(  245): AwesomePlayer::setDataSource_l():: This is not a DRM content
V/MediaPlayerService(  245): prepare
V/AwesomePlayer(  245): prepareAsync
V/MediaPlayerService(  245): wait for prepare
V/AwesomePlayer(  245): onPrepareAsyncEvent
I/SecMediaClock(  245): SecMediaClock constructor
I/SecMediaClock(  245): reset
V/AwesomePlayer(  245): initAudioDecoder
V/AwesomePlayer(  245): checkOffloadExceptions is true
I/OMXCodec(  245): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
I/OMX     (  245): mDispatchers.add
I/OMXCodec(  245): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec(  245): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec(  245): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec(  245): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/OMXCodec(  245): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer(  245): finishAsyncPrepare_l
V/AwesomePlayer(  245): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache(  245): notify(0xb8992858, 200, 973, 0)
V/AudioCache(  245): ignored
V/AwesomePlayer(  245): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  245): notify(0xb8992858, 5, 0, 0)
V/AudioCache(  245): ignored
V/AwesomePlayer(  245): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  245): notify(0xb8992858, 1, 0, 0)
V/AudioCache(  245): prepared
V/AudioCache(  245): wait - success
V/MediaPlayerService(  245): start
V/StagefrightPlayer(  245): start
V/AwesomePlayer(  245): play
V/AwesomePlayer(  245): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer(  245): startAudioPlayer_l, sendErrorNotification (0)
I/OMXCodec(  245): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec(  245): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec(  245): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/AudioPlayer(  245):  Audioplayer kKeyAudioPCMFormat:1, 2, 0
I/AudioPlayer(  245):  Audioplayer kKeyAudioPCMFormat read fail(2, 1)
V/AudioCache(  245): open(44100, 2, 0x0, 1, 4)
V/AwesomePlayer(  245): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache(  245): notify(0xb8992858, 6, 0, 0)
V/AudioCache(  245): ignored
V/AwesomePlayer(  245): addBatteryData
V/MediaPlayerService(  245): wait for playback complete
I/AudioPlayer(  245): First fillBuffer call!!
I/OMXCodec(  245): [OMX.google.vorbis.decoder] End Of Stream
V/AwesomePlayer(  245): postAudioEOS delayUs (0)
V/AwesomePlayer(  245): onCheckAudioStatus
V/AwesomePlayer(  245): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  245): onStreamDone
V/AwesomePlayer(  245): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  245): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  245): notify(0xb8992858, 2, 0, 0)
V/AudioCache(  245): playback complete - thread will wake up later
V/AwesomePlayer(  245): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  245): notify(0xb8992858, 7, 0, 0)
V/AudioCache(  245): ignored
V/AwesomePlayer(  245): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer(  245): addBatteryData
V/AudioCache(  245): wait - success
V/StagefrightPlayer(  245): reset
V/AwesomePlayer(  245): reset_l()
V/AwesomePlayer(  245): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  245): notify(0xb8992858, 8, 0, 0)
V/AudioCache(  245): ignored
V/AwesomePlayer(  245): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  245): mAudioTrackVector clear
I/OMXCodec(  245): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec(  245): [OMX.google.vorbis.decoder] stop() sendCommand(0x3b, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec(  245): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
I/OMXCodec(  245): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/OMX     (  245): instance freeNode
I/AudioPlayer(  245): reset out
V/AwesomePlayer(  245): reset_l() mAudioPlayer successfully deleted
I/SecMediaClock(  245): SecMediaClock destructor
V/AwesomePlayer(  245): mSecMediaClock clear
V/StagefrightPlayer(  245): ~StagefrightPlayer
V/StagefrightPlayer(  245): reset
V/AwesomePlayer(  245): reset_l()
V/AwesomePlayer(  245): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  245): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  245): mAudioTrackVector clear
V/AwesomePlayer(  245): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  245): mSecMediaClock clear
V/AwesomePlayer(  245): destructor
V/AwesomePlayer(  245): reset_l()
V/AwesomePlayer(  245): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  245): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  245): mAudioTrackVector clear
V/AwesomePlayer(  245): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  245): mSecMediaClock clear
V/MediaPlayer( 4609): decode(67, 30367732, 5085)
V/MediaPlayerService(  245): decode(35, 30367732, 5085)
V/MediaPlayerService(  245): player type = 3
V/AwesomePlayer(  245): setDefault
V/AwesomePlayer(  245): constructor
V/AwesomePlayer(  245): setDefault
V/AwesomePlayer(  245): reset_l()
V/AwesomePlayer(  245): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  245): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  245): mAudioTrackVector clear
V/AwesomePlayer(  245): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  245): mSecMediaClock clear
V/StagefrightPlayer(  245): StagefrightPlayer
V/AwesomePlayer(  245): setListener
V/StagefrightPlayer(  245): initCheck
V/AwesomePlayer(  245): setAudioSink
V/StagefrightPlayer(  245): setDataSource(35, 30367732, 5085)
V/AwesomePlayer(  245): reset_l()
V/AwesomePlayer(  245): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  245): notify(0xb8987928, 8, 0, 0)
V/AudioCache(  245): ignored
V/AwesomePlayer(  245): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  245): mAudioTrackVector clear
V/AwesomePlayer(  245): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  245): mSecMediaClock clear
V/AwesomePlayer(  245): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer(  245): mBitrate = -1 bits/sec
V/AwesomePlayer(  245): current audio track index (0) is added to vector
V/AwesomePlayer(  245): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer(  245): AwesomePlayer::setDataSource_l():: This is not a DRM content
V/MediaPlayerService(  245): prepare
V/AwesomePlayer(  245): prepareAsync
V/MediaPlayerService(  245): wait for prepare
V/AwesomePlayer(  245): onPrepareAsyncEvent
I/SecMediaClock(  245): SecMediaClock constructor
I/SecMediaClock(  245): reset
V/AwesomePlayer(  245): initAudioDecoder
V/AwesomePlayer(  245): checkOffloadExceptions is true
I/OMXCodec(  245): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
I/OMX     (  245): mDispatchers.add
I/OMXCodec(  245): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec(  245): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec(  245): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec(  245): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/OMXCodec(  245): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer(  245): finishAsyncPrepare_l
V/AwesomePlayer(  245): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache(  245): notify(0xb8987928, 200, 973, 0)
V/AudioCache(  245): ignored
V/AwesomePlayer(  245): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  245): notify(0xb8987928, 5, 0, 0)
V/AudioCache(  245): ignored
V/AwesomePlayer(  245): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  245): notify(0xb8987928, 1, 0, 0)
V/AudioCache(  245): prepared
V/AudioCache(  245): wait - success
V/MediaPlayerService(  245): start
V/StagefrightPlayer(  245): start
V/AwesomePlayer(  245): play
V/AwesomePlayer(  245): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer(  245): startAudioPlayer_l, sendErrorNotification (0)
I/OMXCodec(  245): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec(  245): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec(  245): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/AudioPlayer(  245):  Audioplayer kKeyAudioPCMFormat:1, 2, 0
I/AudioPlayer(  245):  Audioplayer kKeyAudioPCMFormat read fail(2, 1)
V/AudioCache(  245): open(44100, 2, 0x0, 1, 4)
V/AwesomePlayer(  245): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache(  245): notify(0xb8987928, 6, 0, 0)
V/AudioCache(  245): ignored
V/AwesomePlayer(  245): addBatteryData
V/MediaPlayerService(  245): wait for playback complete
I/AudioPlayer(  245): First fillBuffer call!!
I/OMXCodec(  245): [OMX.google.vorbis.decoder] End Of Stream
D/AmoledAdjustTimer(  775): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
V/AwesomePlayer(  245): postAudioEOS delayUs (0)
V/AwesomePlayer(  245): onCheckAudioStatus
V/AwesomePlayer(  245): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  245): onStreamDone
V/AwesomePlayer(  245): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  245): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  245): notify(0xb8987928, 2, 0, 0)
V/AudioCache(  245): playback complete - thread will wake up later
V/AwesomePlayer(  245): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  245): notify(0xb8987928, 7, 0, 0)
V/AudioCache(  245): ignored
V/AwesomePlayer(  245): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer(  245): addBatteryData
V/AudioCache(  245): wait - success
V/StagefrightPlayer(  245): reset
V/AwesomePlayer(  245): reset_l()
V/AwesomePlayer(  245): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  245): notify(0xb8987928, 8, 0, 0)
V/AudioCache(  245): ignored
V/AwesomePlayer(  245): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  245): mAudioTrackVector clear
I/OMXCodec(  245): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec(  245): [OMX.google.vorbis.decoder] stop() sendCommand(0x3c, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec(  245): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
I/OMXCodec(  245): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/OMX     (  245): instance freeNode
I/AudioPlayer(  245): reset out
V/AwesomePlayer(  245): reset_l() mAudioPlayer successfully deleted
I/SecMediaClock(  245): SecMediaClock destructor
V/AwesomePlayer(  245): mSecMediaClock clear
V/StagefrightPlayer(  245): ~StagefrightPlayer
V/StagefrightPlayer(  245): reset
V/AwesomePlayer(  245): reset_l()
V/AwesomePlayer(  245): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  245): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  245): mAudioTrackVector clear
V/AwesomePlayer(  245): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  245): mSecMediaClock clear
V/AwesomePlayer(  245): destructor
V/AwesomePlayer(  245): reset_l()
V/AwesomePlayer(  245): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  245): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  245): mAudioTrackVector clear
V/AwesomePlayer(  245): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  245): mSecMediaClock clear
V/MediaPlayer( 4609): decode(68, 30372876, 21552)
V/MediaPlayerService(  245): decode(35, 30372876, 21552)
V/MediaPlayerService(  245): player type = 3
V/AwesomePlayer(  245): setDefault
V/AwesomePlayer(  245): constructor
V/AwesomePlayer(  245): setDefault
V/AwesomePlayer(  245): reset_l()
V/AwesomePlayer(  245): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  245): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  245): mAudioTrackVector clear
V/AwesomePlayer(  245): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  245): mSecMediaClock clear
V/StagefrightPlayer(  245): StagefrightPlayer
V/AwesomePlayer(  245): setListener
V/StagefrightPlayer(  245): initCheck
V/AwesomePlayer(  245): setAudioSink
V/StagefrightPlayer(  245): setDataSource(35, 30372876, 21552)
V/AwesomePlayer(  245): reset_l()
V/AwesomePlayer(  245): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  245): notify(0xb8983598, 8, 0, 0)
V/AudioCache(  245): ignored
V/AwesomePlayer(  245): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  245): mAudioTrackVector clear
V/AwesomePlayer(  245): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  245): mSecMediaClock clear
V/AwesomePlayer(  245): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer(  245): mBitrate = -1 bits/sec
V/AwesomePlayer(  245): current audio track index (0) is added to vector
V/AwesomePlayer(  245): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer(  245): AwesomePlayer::setDataSource_l():: This is not a DRM content
V/MediaPlayerService(  245): prepare
V/AwesomePlayer(  245): prepareAsync
V/MediaPlayerService(  245): wait for prepare
V/AwesomePlayer(  245): onPrepareAsyncEvent
I/SecMediaClock(  245): SecMediaClock constructor
I/SecMediaClock(  245): reset
V/AwesomePlayer(  245): initAudioDecoder
V/AwesomePlayer(  245): checkOffloadExceptions is true
I/OMXCodec(  245): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
I/OMX     (  245): mDispatchers.add
I/OMXCodec(  245): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec(  245): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec(  245): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec(  245): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/OMXCodec(  245): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer(  245): finishAsyncPrepare_l
V/AwesomePlayer(  245): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache(  245): notify(0xb8983598, 200, 973, 0)
V/AudioCache(  245): ignored
V/AwesomePlayer(  245): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  245): notify(0xb8983598, 5, 0, 0)
V/AudioCache(  245): ignored
V/AwesomePlayer(  245): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  245): notify(0xb8983598, 1, 0, 0)
V/AudioCache(  245): prepared
V/AudioCache(  245): wait - success
V/MediaPlayerService(  245): start
V/StagefrightPlayer(  245): start
V/AwesomePlayer(  245): play
V/AwesomePlayer(  245): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer(  245): startAudioPlayer_l, sendErrorNotification (0)
I/OMXCodec(  245): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec(  245): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec(  245): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/AudioPlayer(  245):  Audioplayer kKeyAudioPCMFormat:1, 2, 0
I/AudioPlayer(  245):  Audioplayer kKeyAudioPCMFormat read fail(2, 1)
V/AudioCache(  245): open(44100, 2, 0x0, 1, 4)
V/AwesomePlayer(  245): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache(  245): notify(0xb8983598, 6, 0, 0)
V/AudioCache(  245): ignored
V/AwesomePlayer(  245): addBatteryData
V/MediaPlayerService(  245): wait for playback complete
I/OMXCodec(  245): [OMX.google.vorbis.decoder] End Of Stream
V/AwesomePlayer(  245): postAudioEOS delayUs (0)
V/AwesomePlayer(  245): onCheckAudioStatus
V/AwesomePlayer(  245): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  245): onStreamDone
V/AwesomePlayer(  245): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  245): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  245): notify(0xb8983598, 2, 0, 0)
V/AudioCache(  245): playback complete - thread will wake up later
V/AwesomePlayer(  245): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  245): notify(0xb8983598, 7, 0, 0)
V/AudioCache(  245): ignored
V/AwesomePlayer(  245): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer(  245): addBatteryData
V/AudioCache(  245): wait - success
V/StagefrightPlayer(  245): reset
V/AwesomePlayer(  245): reset_l()
V/AwesomePlayer(  245): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  245): notify(0xb8983598, 8, 0, 0)
V/AudioCache(  245): ignored
V/AwesomePlayer(  245): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  245): mAudioTrackVector clear
I/OMXCodec(  245): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec(  245): [OMX.google.vorbis.decoder] stop() sendCommand(0x3d, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec(  245): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
I/OMXCodec(  245): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/OMX     (  245): instance freeNode
I/AudioPlayer(  245): reset out
V/AwesomePlayer(  245): reset_l() mAudioPlayer successfully deleted
I/SecMediaClock(  245): SecMediaClock destructor
V/AwesomePlayer(  245): mSecMediaClock clear
V/StagefrightPlayer(  245): ~StagefrightPlayer
V/StagefrightPlayer(  245): reset
V/AwesomePlayer(  245): reset_l()
V/AwesomePlayer(  245): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  245): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  245): mAudioTrackVector clear
V/AwesomePlayer(  245): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  245): mSecMediaClock clear
V/AwesomePlayer(  245): destructor
V/AwesomePlayer(  245): reset_l()
V/AwesomePlayer(  245): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  245): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  245): mAudioTrackVector clear
V/AwesomePlayer(  245): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  245): mSecMediaClock clear
V/MediaPlayer( 4609): decode(69, 37543652, 4230)
V/MediaPlayerService(  245): decode(35, 37543652, 4230)
V/MediaPlayerService(  245): player type = 3
V/AwesomePlayer(  245): setDefault
V/AwesomePlayer(  245): constructor
V/AwesomePlayer(  245): setDefault
V/AwesomePlayer(  245): reset_l()
V/AwesomePlayer(  245): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  245): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  245): mAudioTrackVector clear
V/AwesomePlayer(  245): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  245): mSecMediaClock clear
V/StagefrightPlayer(  245): StagefrightPlayer
V/AwesomePlayer(  245): setListener
V/StagefrightPlayer(  245): initCheck
V/AwesomePlayer(  245): setAudioSink
V/StagefrightPlayer(  245): setDataSource(35, 37543652, 4230)
V/AwesomePlayer(  245): reset_l()
V/AwesomePlayer(  245): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  245): notify(0xb8987928, 8, 0, 0)
V/AudioCache(  245): ignored
V/AwesomePlayer(  245): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  245): mAudioTrackVector clear
V/AwesomePlayer(  245): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  245): mSecMediaClock clear
V/AwesomePlayer(  245): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer(  245): mBitrate = -1 bits/sec
V/AwesomePlayer(  245): current audio track index (0) is added to vector
V/AwesomePlayer(  245): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer(  245): AwesomePlayer::setDataSource_l():: This is not a DRM content
V/MediaPlayerService(  245): prepare
V/AwesomePlayer(  245): prepareAsync
V/MediaPlayerService(  245): wait for prepare
V/AwesomePlayer(  245): onPrepareAsyncEvent
I/SecMediaClock(  245): SecMediaClock constructor
I/SecMediaClock(  245): reset
V/AwesomePlayer(  245): initAudioDecoder
V/AwesomePlayer(  245): checkOffloadExceptions is true
I/OMXCodec(  245): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
I/OMX     (  245): mDispatchers.add
I/OMXCodec(  245): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec(  245): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec(  245): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec(  245): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/OMXCodec(  245): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer(  245): finishAsyncPrepare_l
V/AwesomePlayer(  245): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache(  245): notify(0xb8987928, 200, 973, 0)
V/AudioCache(  245): ignored
V/AwesomePlayer(  245): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  245): notify(0xb8987928, 5, 0, 0)
V/AudioCache(  245): ignored
V/AwesomePlayer(  245): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  245): notify(0xb8987928, 1, 0, 0)
V/AudioCache(  245): prepared
V/AudioCache(  245): wait - success
V/MediaPlayerService(  245): start
V/StagefrightPlayer(  245): start
V/AwesomePlayer(  245): play
V/AwesomePlayer(  245): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer(  245): startAudioPlayer_l, sendErrorNotification (0)
I/OMXCodec(  245): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec(  245): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec(  245): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/OMXCodec(  245): [OMX.google.vorbis.decoder] End Of Stream
I/AudioPlayer(  245):  Audioplayer kKeyAudioPCMFormat:1, 1, 0
I/AudioPlayer(  245):  Audioplayer kKeyAudioPCMFormat read fail(1, 1)
V/AudioCache(  245): open(44100, 1, 0x0, 1, 4)
V/AwesomePlayer(  245): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache(  245): notify(0xb8987928, 6, 0, 0)
V/AudioCache(  245): ignored
V/AwesomePlayer(  245): addBatteryData
V/MediaPlayerService(  245): wait for playback complete
V/AwesomePlayer(  245): postAudioEOS delayUs (0)
V/AwesomePlayer(  245): onCheckAudioStatus
V/AwesomePlayer(  245): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  245): onStreamDone
V/AwesomePlayer(  245): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  245): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  245): notify(0xb8987928, 2, 0, 0)
V/AudioCache(  245): playback complete - thread will wake up later
V/AwesomePlayer(  245): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  245): notify(0xb8987928, 7, 0, 0)
V/AudioCache(  245): ignored
V/AwesomePlayer(  245): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer(  245): addBatteryData
V/AudioCache(  245): wait - success
V/StagefrightPlayer(  245): reset
V/AwesomePlayer(  245): reset_l()
V/AwesomePlayer(  245): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  245): notify(0xb8987928, 8, 0, 0)
V/AudioCache(  245): ignored
V/AwesomePlayer(  245): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  245): mAudioTrackVector clear
I/OMXCodec(  245): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec(  245): [OMX.google.vorbis.decoder] stop() sendCommand(0x3e, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec(  245): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
I/OMXCodec(  245): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/OMX     (  245): instance freeNode
I/AudioPlayer(  245): reset out
V/AwesomePlayer(  245): reset_l() mAudioPlayer successfully deleted
I/SecMediaClock(  245): SecMediaClock destructor
V/AwesomePlayer(  245): mSecMediaClock clear
V/StagefrightPlayer(  245): ~StagefrightPlayer
V/StagefrightPlayer(  245): reset
V/AwesomePlayer(  245): reset_l()
V/AwesomePlayer(  245): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  245): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  245): mAudioTrackVector clear
V/AwesomePlayer(  245): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  245): mSecMediaClock clear
V/AwesomePlayer(  245): destructor
V/AwesomePlayer(  245): reset_l()
V/AwesomePlayer(  245): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  245): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  245): mAudioTrackVector clear
V/AwesomePlayer(  245): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  245): mSecMediaClock clear
V/MediaPlayer( 4609): decode(70, 30337076, 9400)
V/MediaPlayerService(  245): decode(35, 30337076, 9400)
V/MediaPlayerService(  245): player type = 3
V/AwesomePlayer(  245): setDefault
V/AwesomePlayer(  245): constructor
V/AwesomePlayer(  245): setDefault
V/AwesomePlayer(  245): reset_l()
V/AwesomePlayer(  245): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  245): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  245): mAudioTrackVector clear
V/AwesomePlayer(  245): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  245): mSecMediaClock clear
V/StagefrightPlayer(  245): StagefrightPlayer
V/AwesomePlayer(  245): setListener
V/StagefrightPlayer(  245): initCheck
V/AwesomePlayer(  245): setAudioSink
V/StagefrightPlayer(  245): setDataSource(35, 30337076, 9400)
V/AwesomePlayer(  245): reset_l()
V/AwesomePlayer(  245): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  245): notify(0xb89832f0, 8, 0, 0)
V/AudioCache(  245): ignored
V/AwesomePlayer(  245): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  245): mAudioTrackVector clear
V/AwesomePlayer(  245): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  245): mSecMediaClock clear
V/AwesomePlayer(  245): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer(  245): mBitrate = -1 bits/sec
V/AwesomePlayer(  245): current audio track index (0) is added to vector
V/AwesomePlayer(  245): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer(  245): AwesomePlayer::setDataSource_l():: This is not a DRM content
V/MediaPlayerService(  245): prepare
V/AwesomePlayer(  245): prepareAsync
V/MediaPlayerService(  245): wait for prepare
V/AwesomePlayer(  245): onPrepareAsyncEvent
I/SecMediaClock(  245): SecMediaClock constructor
I/SecMediaClock(  245): reset
V/AwesomePlayer(  245): initAudioDecoder
V/AwesomePlayer(  245): checkOffloadExceptions is true
I/OMXCodec(  245): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
I/OMX     (  245): mDispatchers.add
I/OMXCodec(  245): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec(  245): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec(  245): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec(  245): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/OMXCodec(  245): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer(  245): finishAsyncPrepare_l
V/AwesomePlayer(  245): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache(  245): notify(0xb89832f0, 200, 973, 0)
V/AudioCache(  245): ignored
V/AwesomePlayer(  245): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  245): notify(0xb89832f0, 5, 0, 0)
V/AudioCache(  245): ignored
V/AwesomePlayer(  245): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  245): notify(0xb89832f0, 1, 0, 0)
V/AudioCache(  245): prepared
V/AudioCache(  245): wait - success
V/MediaPlayerService(  245): start
V/StagefrightPlayer(  245): start
V/AwesomePlayer(  245): play
V/AwesomePlayer(  245): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer(  245): startAudioPlayer_l, sendErrorNotification (0)
I/SELinux ( 4698): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 4698):  
I/OMXCodec(  245): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec(  245): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec(  245): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/AudioPlayer(  245):  Audioplayer kKeyAudioPCMFormat:1, 1, 0
I/AudioPlayer(  245):  Audioplayer kKeyAudioPCMFormat read fail(1, 1)
V/AudioCache(  245): open(44100, 1, 0x0, 1, 4)
V/AwesomePlayer(  245): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache(  245): notify(0xb89832f0, 6, 0, 0)
V/AudioCache(  245): ignored
V/AwesomePlayer(  245): addBatteryData
V/MediaPlayerService(  245): wait for playback complete
I/AudioPlayer(  245): First fillBuffer call!!
I/OMXCodec(  245): [OMX.google.vorbis.decoder] End Of Stream
V/AwesomePlayer(  245): postAudioEOS delayUs (0)
V/AwesomePlayer(  245): onCheckAudioStatus
V/AwesomePlayer(  245): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  245): onStreamDone
V/AwesomePlayer(  245): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  245): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  245): notify(0xb89832f0, 2, 0, 0)
V/AudioCache(  245): playback complete - thread will wake up later
V/AwesomePlayer(  245): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  245): notify(0xb89832f0, 7, 0, 0)
V/AudioCache(  245): ignored
V/AwesomePlayer(  245): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer(  245): addBatteryData
V/AudioCache(  245): wait - success
V/StagefrightPlayer(  245): reset
V/AwesomePlayer(  245): reset_l()
V/AwesomePlayer(  245): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  245): notify(0xb89832f0, 8, 0, 0)
V/AudioCache(  245): ignored
V/AwesomePlayer(  245): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  245): mAudioTrackVector clear
I/OMXCodec(  245): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec(  245): [OMX.google.vorbis.decoder] stop() sendCommand(0x3f, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec(  245): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
I/OMXCodec(  245): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/OMX     (  245): instance freeNode
I/ActivityManager(  775): Killing 3346:com.android.email/u0a155 (adj 15): empty #43
I/AudioPlayer(  245): reset out
V/AwesomePlayer(  245): reset_l() mAudioPlayer successfully deleted
I/SecMediaClock(  245): SecMediaClock destructor
V/AwesomePlayer(  245): mSecMediaClock clear
V/StagefrightPlayer(  245): ~StagefrightPlayer
V/StagefrightPlayer(  245): reset
V/AwesomePlayer(  245): reset_l()
V/AwesomePlayer(  245): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  245): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  245): mAudioTrackVector clear
V/AwesomePlayer(  245): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  245): mSecMediaClock clear
V/AwesomePlayer(  245): destructor
V/AwesomePlayer(  245): reset_l()
V/AwesomePlayer(  245): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  245): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  245): mAudioTrackVector clear
V/AwesomePlayer(  245): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  245): mSecMediaClock clear
V/MediaPlayer( 4609): decode(71, 33925464, 44276)
V/MediaPlayerService(  245): decode(35, 33925464, 44276)
V/MediaPlayerService(  245): player type = 3
V/AwesomePlayer(  245): setDefault
V/AwesomePlayer(  245): constructor
V/AwesomePlayer(  245): setDefault
V/AwesomePlayer(  245): reset_l()
V/AwesomePlayer(  245): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  245): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  245): mAudioTrackVector clear
V/AwesomePlayer(  245): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  245): mSecMediaClock clear
V/StagefrightPlayer(  245): StagefrightPlayer
V/AwesomePlayer(  245): setListener
V/StagefrightPlayer(  245): initCheck
V/AwesomePlayer(  245): setAudioSink
V/StagefrightPlayer(  245): setDataSource(35, 33925464, 44276)
V/AwesomePlayer(  245): reset_l()
V/AwesomePlayer(  245): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  245): notify(0xb89876b8, 8, 0, 0)
V/AudioCache(  245): ignored
V/AwesomePlayer(  245): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  245): mAudioTrackVector clear
V/AwesomePlayer(  245): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  245): mSecMediaClock clear
I/SELinux ( 4698): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 4698):  
I/SELinux ( 4698):  
I/SELinux ( 4698): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 4698): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 4698): >>>>> Normal User
E/dalvikvm( 4698): >>>>> com.policydm [ userId:0 | appId:1000 ]
E/SELinux ( 4698): [DEBUG] seapp_context_lookup: seinfoCategory = platform
V/AwesomePlayer(  245): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer(  245): mBitrate = -1 bits/sec
V/AwesomePlayer(  245): current audio track index (0) is added to vector
V/AwesomePlayer(  245): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer(  245): AwesomePlayer::setDataSource_l():: This is not a DRM content
V/MediaPlayerService(  245): prepare
V/AwesomePlayer(  245): prepareAsync
V/MediaPlayerService(  245): wait for prepare
V/AwesomePlayer(  245): onPrepareAsyncEvent
I/SecMediaClock(  245): SecMediaClock constructor
I/SecMediaClock(  245): reset
V/AwesomePlayer(  245): initAudioDecoder
V/AwesomePlayer(  245): checkOffloadExceptions is true
I/OMXCodec(  245): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
I/OMX     (  245): mDispatchers.add
I/OMXCodec(  245): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec(  245): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec(  245): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec(  245): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on outp,ut port
I/OMXCodec(  245): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer(  245): finishAsyncPrepare_l
V/AwesomePlayer(  245): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache(  245): notify(0xb89876b8, 200, 973, 0)
V/AudioCache(  245): ignored
V/AwesomePlayer(  245): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  245): notify(0xb89876b8, 5, 0, 0)
V/AudioCache(  245): ignored
V/AwesomePlayer(  245): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  245): notify(0xb89876b8, 1, 0, 0)
V/AudioCache(  245): prepared
V/AudioCache(  245): wait - success
V/MediaPlayerService(  245): start
V/StagefrightPlayer(  245): start
V/AwesomePlayer(  245): play
V/AwesomePlayer(  245): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer(  245): startAudioPlayer_l, sendErrorNotification (0)
I/OMXCodec(  245): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec(  245): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec(  245): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/AudioPlayer(  245):  Audioplayer kKeyAudioPCMFormat:1, 2, 0
I/AudioPlayer(  245):  Audioplayer kKeyAudioPCMFormat read fail(2, 1)
V/AudioCache(  245): open(44100, 2, 0x0, 1, 4)
V/AwesomePlayer(  245): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache(  245): notify(0xb89876b8, 6, 0, 0)
V/AudioCache(  245): ignored
V/AwesomePlayer(  245): addBatteryData
V/MediaPlayerService(  245): wait for playback complete
D/AndroidRuntime( 4664): 
D/AndroidRuntime( 4664): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 4664): CheckJNI is OFF
D/AndroidRuntime( 4664): setted country_code = Poland
D/AndroidRuntime( 4664): setted countryiso_code = PL
D/AndroidRuntime( 4664): setted sales_code = XEO
D/AndroidRuntime( 4664): readGMSProperty: start
D/AndroidRuntime( 4664): readGMSProperty: already setted!!
D/AndroidRuntime( 4664): readGMSProperty: end
D/AndroidRuntime( 4664): addProductProperty: start
D/TimaKeyStoreProvider( 4698): in addTimaSignatureService
D/TimaKeyStoreProvider( 4698): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 4698): Added TimaKesytore provider
D/dalvikvm( 4664): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 4664): Added shared lib libjavacore.so 0x0
D/dalvikvm( 4664): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 4664): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 4664): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
I/OMXCodec(  245): [OMX.google.vorbis.decoder] End Of Stream
V/AwesomePlayer(  245): postAudioEOS delayUs (0)
V/AwesomePlayer(  245): onCheckAudioStatus
V/AwesomePlayer(  245): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  245): onStreamDone
V/AwesomePlayer(  245): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  245): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  245): notify(0xb89876b8, 2, 0, 0)
V/AudioCache(  245): playback complete - thread will wake up later
V/AwesomePlayer(  245): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  245): notify(0xb89876b8, 7, 0, 0)
V/AudioCache(  245): ignored
V/AwesomePlayer(  245): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer(  245): addBatteryData
V/AudioCache(  245): wait - success
V/StagefrightPlayer(  245): reset
V/AwesomePlayer(  245): reset_l()
V/AwesomePlayer(  245): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  245): notify(0xb89876b8, 8, 0, 0)
V/AudioCache(  245): ignored
V/AwesomePlayer(  245): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  245): mAudioTrackVector clear
I/OMXCodec(  245): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec(  245): [OMX.google.vorbis.decoder] stop() sendCommand(0x40, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec(  245): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
I/OMXCodec(  245): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/OMX     (  245): instance freeNode
I/AudioPlayer(  245): reset out
V/AwesomePlayer(  245): reset_l() mAudioPlayer successfully deleted
I/SecMediaClock(  245): SecMediaClock destructor
V/AwesomePlayer(  245): mSecMediaClock clear
V/StagefrightPlayer(  245): ~StagefrightPlayer
V/StagefrightPlayer(  245): reset
V/AwesomePlayer(  245): reset_l()
V/AwesomePlayer(  245): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  245): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  245): mAudioTrackVector clear
V/AwesomePlayer(  245): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  245): mSecMediaClock clear
V/AwesomePlayer(  245): destructor
V/AwesomePlayer(  245): reset_l()
V/AwesomePlayer(  245): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  245): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  245): mAudioTrackVector clear
V/AwesomePlayer(  245): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  245): mSecMediaClock clear
V/MediaPlayer( 4609): decode(72, 33885672, 29256)
V/MediaPlayerService(  245): decode(35, 33885672, 29256)
V/MediaPlayerService(  245): player type = 3
V/AwesomePlayer(  245): setDefault
V/AwesomePlayer(  245): constructor
V/AwesomePlayer(  245): setDefault
V/AwesomePlayer(  245): reset_l()
V/AwesomePlayer(  245): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  245): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  245): mAudioTrackVector clear
V/AwesomePlayer(  245): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  245): mSecMediaClock clear
V/StagefrightPlayer(  245): StagefrightPlayer
V/AwesomePlayer(  245): setListener
V/StagefrightPlayer(  245): initCheck
V/AwesomePlayer(  245): setAudioSink
V/StagefrightPlayer(  245): setDataSource(35, 33885672, 29256)
V/AwesomePlayer(  245): reset_l()
V/AwesomePlayer(  245): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  245): notify(0xb89876b8, 8, 0, 0)
V/AudioCache(  245): ignored
V/AwesomePlayer(  245): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  245): mAudioTrackVector clear
V/AwesomePlayer(  245): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  245): mSecMediaClock clear
V/AwesomePlayer(  245): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer(  245): mBitrate = -1 bits/sec
V/AwesomePlayer(  245): current audio track index (0) is added to vector
V/AwesomePlayer(  245): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer(  245): AwesomePlayer::setDataSource_l():: This is not a DRM content
V/MediaPlayerService(  245): prepare
V/AwesomePlayer(  245): prepareAsync
V/MediaPlayerService(  245): wait for prepare
V/AwesomePlayer(  245): onPrepareAsyncEvent
I/SecMediaClock(  245): SecMediaClock constructor
I/SecMediaClock(  245): reset
V/AwesomePlayer(  245): initAudioDecoder
V/AwesomePlayer(  245): checkOffloadExceptions is true
I/OMXCodec(  245): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
I/OMX     (  245): mDispatchers.add
I/OMXCodec(  245): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec(  245): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec(  245): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec(  245): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/OMXCodec(  245): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer(  245): finishAsyncPrepare_l
V/AwesomePlayer(  245): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache(  245): notify(0xb89876b8, 200, 973, 0)
V/AudioCache(  245): ignored
V/AwesomePlayer(  245): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  245): notify(0xb89876b8, 5, 0, 0)
V/AudioCache(  245): ignored
V/AwesomePlayer(  245): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  245): notify(0xb89876b8, 1, 0, 0)
V/AudioCache(  245): prepared
V/AudioCache(  245): wait - success
V/MediaPlayerService(  245): start
V/StagefrightPlayer(  245): start
V/AwesomePlayer(  245): play
V/AwesomePlayer(  245): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer(  245): startAudioPlayer_l, sendErrorNotification (0)
I/OMXCodec(  245): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec(  245): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec(  245): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/AudioPlayer(  245):  Audioplayer kKeyAudioPCMFormat:1, 2, 0
I/AudioPlayer(  245):  Audioplayer kKeyAudioPCMFormat read fail(2, 1)
V/AudioCache(  245): open(44100, 2, 0x0, 1, 4)
V/AwesomePlayer(  245): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache(  245): notify(0xb89876b8, 6, 0, 0)
V/AudioCache(  245): ignored
V/AwesomePlayer(  245): addBatteryData
V/MediaPlayerService(  245): wait for playback complete
I/OMXCodec(  245): [OMX.google.vorbis.decoder] End Of Stream
V/AwesomePlayer(  245): postAudioEOS delayUs (0)
V/AwesomePlayer(  245): onCheckAudioStatus
V/AwesomePlayer(  245): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  245): onStreamDone
V/AwesomePlayer(  245): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  245): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  245): notify(0xb89876b8, 2, 0, 0)
V/AudioCache(  245): playback complete - thread will wake up later
V/AwesomePlayer(  245): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  245): notify(0xb89876b8, 7, 0, 0)
V/AudioCache(  245): ignored
V/AwesomePlayer(  245): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer(  245): addBatteryData
V/AudioCache(  245): wait - success
V/StagefrightPlayer(  245): reset
V/AwesomePlayer(  245): reset_l()
V/AwesomePlayer(  245): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  245): notify(0xb89876b8, 8, 0, 0)
V/AudioCache(  245): ignored
V/AwesomePlayer(  245): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  245): mAudioTrackVector clear
I/OMXCodec(  245): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec(  245): [OMX.google.vorbis.decoder] stop() sendCommand(0x41, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec(  245): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
I/OMXCodec(  245): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/OMX     (  245): instance freeNode
I/AudioPlayer(  245): reset out
V/AwesomePlayer(  245): reset_l() mAudioPlayer successfully deleted
I/SecMediaClock(  245): SecMediaClock destructor
V/AwesomePlayer(  245): mSecMediaClock clear
V/StagefrightPlayer(  245): ~StagefrightPlayer
V/StagefrightPlayer(  245): reset
V/AwesomePlayer(  245): reset_l()
V/AwesomePlayer(  245): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  245): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  245): mAudioTrackVector clear
V/AwesomePlayer(  245): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  245): mSecMediaClock clear
V/AwesomePlayer(  245): destructor
V/AwesomePlayer(  245): reset_l()
V/AwesomePlayer(  245): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  245): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  245): mAudioTrackVector clear
V/AwesomePlayer(  245): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  245): mSecMediaClock clear
V/MediaPlayer( 4609): decode(73, 37491572, 52024)
V/MediaPlayerService(  245): decode(35, 37491572, 52024)
V/MediaPlayerService(  245): player type = 3
V/AwesomePlayer(  245): setDefault
V/AwesomePlayer(  245): constructor
V/AwesomePlayer(  245): setDefault
V/AwesomePlayer(  245): reset_l()
V/AwesomePlayer(  245): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  245): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  245): mAudioTrackVector clear
V/AwesomePlayer(  245): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  245): mSecMediaClock clear
V/StagefrightPlayer(  245): StagefrightPlayer
V/AwesomePlayer(  245): setListener
V/StagefrightPlayer(  245): initCheck
V/AwesomePlayer(  245): setAudioSink
V/StagefrightPlayer(  245): setDataSource(35, 37491572, 52024)
V/AwesomePlayer(  245): reset_l()
V/AwesomePlayer(  245): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  245): notify(0xb8978f10, 8, 0, 0)
V/AudioCache(  245): ignored
V/AwesomePlayer(  245): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  245): mAudioTrackVector clear
V/AwesomePlayer(  245): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  245): mSecMediaClock clear
V/AwesomePlayer(  245): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer(  245): mBitrate = -1 bits/sec
V/AwesomePlayer(  245): current audio track index (0) is added to vector
V/AwesomePlayer(  245): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer(  245): AwesomePlayer::setDataSource_l():: This is not a DRM content
V/MediaPlayerService(  245): prepare
V/AwesomePlayer(  245): prepareAsync
V/MediaPlayerService(  245): wait for prepare
V/AwesomePlayer(  245): onPrepareAsyncEvent
I/SecMediaClock(  245): SecMediaClock constructor
I/SecMediaClock(  245): reset
V/AwesomePlayer(  245): initAudioDecoder
V/AwesomePlayer(  245): checkOffloadExceptions is true
I/OMXCodec(  245): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
I/OMX     (  245): mDispatchers.add
I/OMXCodec(  245): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec(  245): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec(  245): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec(  245): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/OMXCodec(  245): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer(  245): finishAsyncPrepare_l
V/AwesomePlayer(  245): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache(  245): notify(0xb8978f10, 200, 973, 0)
V/AudioCache(  245): ignored
V/AwesomePlayer(  245): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  245): notify(0xb8978f10, 5, 0, 0)
V/AudioCache(  245): ignored
V/AwesomePlayer(  245): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  245): notify(0xb8978f10, 1, 0, 0)
V/AudioCache(  245): prepared
V/AudioCache(  245): wait - success
V/MediaPlayerService(  245): start
V/StagefrightPlayer(  245): start
V/AwesomePlayer(  245): play
V/AwesomePlayer(  245): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer(  245): startAudioPlayer_l, sendErrorNotification (0)
I/OMXCodec(  245): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec(  245): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec(  245): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/AudioPlayer(  245):  Audioplayer kKeyAudioPCMFormat:1, 2, 0
I/AudioPlayer(  245):  Audioplayer kKeyAudioPCMFormat read fail(2, 1)
V/AudioCache(  245): open(48000, 2, 0x0, 1, 4)
V/AwesomePlayer(  245): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache(  245): notify(0xb8978f10, 6, 0, 0)
V/AudioCache(  245): ignored
V/AwesomePlayer(  245): addBatteryData
V/MediaPlayerService(  245): wait for playback complete
E/SMD     (  235): DCD ON
E/memtrack( 4664): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 4664): failed to load memtrack module: -2
I/OMXCodec(  245): [OMX.google.vorbis.decoder] End Of Stream
V/AwesomePlayer(  245): postAudioEOS delayUs (0)
D/dalvikvm( 4664): Note: class Landroid/app/ActivityManagerNative; has 192 unimplemented (abstract) methods
V/AwesomePlayer(  245): onCheckAudioStatus
V/AwesomePlayer(  245): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  245): onStreamDone
V/AwesomePlayer(  245): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  245): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  245): notify(0xb8978f10, 2, 0, 0)
V/AudioCache(  245): playback complete - thread will wake up later
V/AwesomePlayer(  245): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  245): notify(0xb8978f10, 7, 0, 0)
V/AudioCache(  245): ignored
V/AwesomePlayer(  245): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer(  245): addBatteryData
V/AudioCache(  245): wait - success
V/StagefrightPlayer(  245): reset
V/AwesomePlayer(  245): reset_l()
V/AwesomePlayer(  245): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  245): notify(0xb8978f10, 8, 0, 0)
V/AudioCache(  245): ignored
V/AwesomePlayer(  245): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  245): mAudioTrackVector clear
I/OMXCodec(  245): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec(  245): [OMX.google.vorbis.decoder] stop() sendCommand(0x42, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec(  245): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
I/OMXCodec(  245): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/OMX     (  245): instance freeNode
I/AudioPlayer(  245): reset out
V/AwesomePlayer(  245): reset_l() mAudioPlayer successfully deleted
I/SecMediaClock(  245): SecMediaClock destructor
V/AwesomePlayer(  245): mSecMediaClock clear
V/StagefrightPlayer(  245): ~StagefrightPlayer
V/StagefrightPlayer(  245): reset
V/AwesomePlayer(  245): reset_l()
V/AwesomePlayer(  245): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  245): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  245): mAudioTrackVector clear
V/AwesomePlayer(  245): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  245): mSecMediaClock clear
V/AwesomePlayer(  245): destructor
V/AwesomePlayer(  245): reset_l()
V/AwesomePlayer(  245): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  245): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  245): mAudioTrackVector clear
V/AwesomePlayer(  245): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  245): mSecMediaClock clear
V/MediaPlayer( 4609): decode(74, 33969800, 9226)
V/MediaPlayerService(  245): decode(35, 33969800, 9226)
V/MediaPlayerService(  245): player type = 3
V/AwesomePlayer(  245): setDefault
V/AwesomePlayer(  245): constructor
V/AwesomePlayer(  245): setDefault
V/AwesomePlayer(  245): reset_l()
V/AwesomePlayer(  245): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  245): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  245): mAudioTrackVector clear
V/AwesomePlayer(  245): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  245): mSecMediaClock clear
V/StagefrightPlayer(  245): StagefrightPlayer
V/AwesomePlayer(  245): setListener
V/StagefrightPlayer(  245): initCheck
V/AwesomePlayer(  245): setAudioSink
V/StagefrightPlayer(  245): setDataSource(35, 33969800, 9226)
V/AwesomePlayer(  245): reset_l()
V/AwesomePlayer(  245): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  245): notify(0xb8975cc0, 8, 0, 0)
V/AudioCache(  245): ignored
V/AwesomePlayer(  245): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  245): mAudioTrackVector clear
V/AwesomePlayer(  245): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  245): mSecMediaClock clear
V/AwesomePlayer(  245): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer(  245): mBitrate = -1 bits/sec
V/AwesomePlayer(  245): current audio track index (0) is added to vector
V/AwesomePlayer(  245): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer(  245): AwesomePlayer::setDataSource_l():: This is not a DRM content
V/MediaPlayerService(  245): prepare
V/AwesomePlayer(  245): prepareAsync
V/MediaPlayerService(  245): wait for prepare
V/AwesomePlayer(  245): onPrepareAsyncEvent
I/SecMediaClock(  245): SecMediaClock constructor
I/SecMediaClock(  245): reset
V/AwesomePlayer(  245): initAudioDecoder
V/AwesomePlayer(  245): checkOffloadExceptions is true
I/OMXCodec(  245): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
I/OMX     (  245): mDispatchers.add
I/OMXCodec(  245): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec(  245): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec(  245): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec(  245): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/OMXCodec(  245): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer(  245): finishAsyncPrepare_l
V/AwesomePlayer(  245): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache(  245): notify(0xb8975cc0, 200, 973, 0)
V/AudioCache(  245): ignored
V/AwesomePlayer(  245): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  245): notify(0xb8975cc0, 5, 0, 0)
V/AudioCache(  245): ignored
V/AwesomePlayer(  245): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  245): notify(0xb8975cc0, 1, 0, 0)
V/AudioCache(  245): prepared
V/AudioCache(  245): wait - success
V/MediaPlayerService(  245): start
V/StagefrightPlayer(  245): start
V/AwesomePlayer(  245): play
V/AwesomePlayer(  245): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer(  245): startAudioPlayer_l, sendErrorNotification (0)
I/OMXCodec(  245): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec(  245): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec(  245): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/AudioPlayer(  245):  Audioplayer kKeyAudioPCMFormat:1, 2, 0
I/AudioPlayer(  245):  Audioplayer kKeyAudioPCMFormat read fail(2, 1)
V/AudioCache(  245): open(44100, 2, 0x0, 1, 4)
V/AwesomePlayer(  245): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache(  245): notify(0xb8975cc0, 6, 0, 0)
V/AudioCache(  245): ignored
V/AwesomePlayer(  245): addBatteryData
V/MediaPlayerService(  245): wait for playback complete
I/OMXCodec(  245): [OMX.google.vorbis.decoder] End Of Stream
V/AwesomePlayer(  245): postAudioEOS delayUs (0)
V/AwesomePlayer(  245): onCheckAudioStatus
V/AwesomePlayer(  245): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  245): onStreamDone
V/AwesomePlayer(  245): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  245): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  245): notify(0xb8975cc0, 2, 0, 0)
V/AudioCache(  245): playback complete - thread will wake up later
V/AwesomePlayer(  245): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  245): notify(0xb8975cc0, 7, 0, 0)
V/AudioCache(  245): ignored
V/AwesomePlayer(  245): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer(  245): addBatteryData
V/AudioCache(  245): wait - success
V/StagefrightPlayer(  245): reset
V/AwesomePlayer(  245): reset_l()
V/AwesomePlayer(  245): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  245): notify(0xb8975cc0, 8, 0, 0)
V/AudioCache(  245): ignored
V/AwesomePlayer(  245): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  245): mAudioTrackVector clear
I/OMXCodec(  245): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec(  245): [OMX.google.vorbis.decoder] stop() sendCommand(0x43, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec(  245): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
I/OMXCodec(  245): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/OMX     (  245): instance freeNode
I/AudioPlayer(  245): reset out
V/AwesomePlayer(  245): reset_l() mAudioPlayer successfully deleted
I/SecMediaClock(  245): SecMediaClock destructor
V/AwesomePlayer(  245): mSecMediaClock clear
V/StagefrightPlayer(  245): ~StagefrightPlayer
V/StagefrightPlayer(  245): reset
V/AwesomePlayer(  245): reset_l()
V/AwesomePlayer(  245): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  245): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  245): mAudioTrackVector clear
V/AwesomePlayer(  245): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  245): mSecMediaClock clear
V/AwesomePlayer(  245): destructor
V/AwesomePlayer(  245): reset_l()
V/AwesomePlayer(  245): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  245): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  245): mAudioTrackVector clear
V/AwesomePlayer(  245): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  245): mSecMediaClock clear
V/MediaPlayer( 4609): decode(68, 30402580, 4509)
V/MediaPlayerService(  245): decode(35, 30402580, 4509)
V/MediaPlayerService(  245): player type = 3
V/AwesomePlayer(  245): setDefault
V/AwesomePlayer(  245): constructor
V/AwesomePlayer(  245): setDefault
V/AwesomePlayer(  245): reset_l()
V/AwesomePlayer(  245): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  245): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  245): mAudioTrackVector clear
V/AwesomePlayer(  245): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  245): mSecMediaClock clear
V/StagefrightPlayer(  245): StagefrightPlayer
V/AwesomePlayer(  245): setListener
V/StagefrightPlayer(  245): initCheck
V/AwesomePlayer(  245): setAudioSink
V/StagefrightPlayer(  245): setDataSource(35, 30402580, 4509)
V/AwesomePlayer(  245): reset_l()
V/AwesomePlayer(  245): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  245): notify(0xb89816e8, 8, 0, 0)
V/AudioCache(  245): ignored
V/AwesomePlayer(  245): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  245): mAudioTrackVector clear
V/AwesomePlayer(  245): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  245): mSecMediaClock clear
V/AwesomePlayer(  245): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer(  245): mBitrate = -1 bits/sec
V/AwesomePlayer(  245): current audio track index (0) is added to vector
V/AwesomePlayer(  245): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer(  245): AwesomePlayer::setDataSource_l():: This is not a DRM content
V/MediaPlayerService(  245): prepare
V/AwesomePlayer(  245): prepareAsync
V/MediaPlayerService(  245): wait for prepare
V/AwesomePlayer(  245): onPrepareAsyncEvent
I/SecMediaClock(  245): SecMediaClock constructor
I/SecMediaClock(  245): reset
V/AwesomePlayer(  245): initAudioDecoder
V/AwesomePlayer(  245): checkOffloadExceptions is true
I/OMXCodec(  245): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
I/OMX     (  245): mDispatchers.add
I/OMXCodec(  245): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec(  245): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec(  245): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec(  245): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/OMXCodec(  245): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer(  245): finishAsyncPrepare_l
V/AwesomePlayer(  245): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache(  245): notify(0xb89816e8, 200, 973, 0)
V/AudioCache(  245): ignored
V/AwesomePlayer(  245): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  245): notify(0xb89816e8, 5, 0, 0)
V/AudioCache(  245): ignored
V/AwesomePlayer(  245): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  245): notify(0xb89816e8, 1, 0, 0)
V/AudioCache(  245): prepared
V/AudioCache(  245): wait - success
V/MediaPlayerService(  245): start
V/StagefrightPlayer(  245): start
V/AwesomePlayer(  245): play
V/AwesomePlayer(  245): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer(  245): startAudioPlayer_l, sendErrorNotification (0)
I/OMXCodec(  245): [OMX.google.vorbis.decoder] End Of Stream
I/OMXCodec(  245): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec(  245): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
D/AndroidRuntime( 4664): Calling main entry com.android.commands.am.Am
I/OMXCodec(  245): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/AudioPlayer(  245):  Audioplayer kKeyAudioPCMFormat:1, 2, 0
I/AudioPlayer(  245):  Audioplayer kKeyAudioPCMFormat read fail(2, 1)
V/AudioCache(  245): open(44100, 2, 0x0, 1, 4)
V/AwesomePlayer(  245): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache(  245): notify(0xb89816e8, 6, 0, 0)
V/AudioCache(  245): ignored
V/AwesomePlayer(  245): addBatteryData
V/MediaPlayerService(  245): wait for playback complete
I/AudioPlayer(  245): First fillBuffer call!!
V/AwesomePlayer(  245): postAudioEOS delayUs (0)
V/AwesomePlayer(  245): onCheckAudioStatus
V/AwesomePlayer(  245): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  245): onStreamDone
V/AwesomePlayer(  245): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  245): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  245): notify(0xb89816e8, 2, 0, 0)
V/AudioCache(  245): playback complete - thread will wake up later
V/AwesomePlayer(  245): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  245): notify(0xb89816e8, 7, 0, 0)
V/AudioCache(  245): ignored
V/AwesomePlayer(  245): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer(  245): addBatteryData
V/AudioCache(  245): wait - success
V/StagefrightPlayer(  245): reset
V/AwesomePlayer(  245): reset_l()
V/AwesomePlayer(  245): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  245): notify(0xb89816e8, 8, 0, 0)
V/AudioCache(  245): ignored
V/AwesomePlayer(  245): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  245): mAudioTrackVector clear
I/OMXCodec(  245): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec(  245): [OMX.google.vorbis.decoder] stop() sendCommand(0x44, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec(  245): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
I/OMXCodec(  245): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/OMX     (  245): instance freeNode
I/AudioPlayer(  245): reset out
V/AwesomePlayer(  245): reset_l() mAudioPlayer successfully deleted
I/SecMediaClock(  245): SecMediaClock destructor
V/AwesomePlayer(  245): mSecMediaClock clear
V/StagefrightPlayer(  245): ~StagefrightPlayer
V/StagefrightPlayer(  245): reset
V/AwesomePlayer(  245): reset_l()
V/AwesomePlayer(  245): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  245): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  245): mAudioTrackVector clear
V/AwesomePlayer(  245): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  245): mSecMediaClock clear
V/AwesomePlayer(  245): destructor
V/AwesomePlayer(  245): reset_l()
V/AwesomePlayer(  245): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  245): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  245): mAudioTrackVector clear
V/AwesomePlayer(  245): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  245): mSecMediaClock clear
V/ApplicationPolicy(  775): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
D/CustomFrequencyManagerService(  775): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 775  pkgName : ACTIVITY_RESUME_BOOSTER@5
W/ActivityManager(  775): mDVFSHelper.acquire()
I/SELinux ( 4745): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 4745):  
D/LockPatternUtils( 1068): isPcwEnable = null
D/AndroidRuntime( 4664): Shutting down VM
D/dalvikvm( 4664): GC_CONCURRENT freed 97K, 13% free 717K/816K, paused 0ms+0ms, total 2ms
I/SELinux ( 4745): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 4745):  
I/SELinux ( 4745):  
I/SELinux ( 4745): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 4745): [DEBUG] seapp_context_lookup: seinfoCategory = default
E/dalvikvm( 4745): >>>>> Normal User
E/dalvikvm( 4745): >>>>> com.test.thalitest [ userId:0 | appId:10179 ]
E/SELinux ( 4745): [DEBUG] seapp_context_lookup: seinfoCategory = default
I/SA      ( 4157): [PMR] Received action : android.intent.action.PACKAGE_ADDED
I/SA      ( 4157): [DM] init START
I/SA      ( 4157): [DM] This device is not a Vodafone
I/SA      ( 4157): [DM] getCountryCodeFromCSC : PL
I/SA      ( 4157): support phone number id : false
I/SA      ( 4157): [DM] init END
I/SA      ( 4157): [SUR] onReceive log=[SA = 2.0.0117 V = 19 HWD = 1280X720 2.0 dpi = 320  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = kmini3g P = kmini3gxx I = KOT49H M = SM-G800H OKLEFT false DIS KOT49H.G800HXXU1ANK2 PSS = 4.497045606779314  ]
D/TimaKeyStoreProvider( 4745): in addTimaSignatureService
I/SA      ( 4157): [SUR] onReceive Intent=[ action.PACKAGE_ADDED. package ]
D/TimaKeyStoreProvider( 4745): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 4745): Added TimaKesytore provider
I/ActivityManager(  775): Killing 3342:com.samsung.android.provider.shootingmodeprovider/u0a162 (adj 15): empty #43
D/LockPatternUtils( 1068): isPcwEnable = null
I/SQLiteSecureOpenHelper( 2050): getWritableDatabase(pwd)
I/SQLiteSecureOpenHelper( 2050): getDatabaseLocked(b,b,pwd)...
D/SurfaceWidgetView( 1251): destroyHardwareResources():1128485640
D/Mms/PackageInstallReceiver( 3861): loadAuthorityPref(): sEnableAuthority = true
I/SurfaceFlinger(  241): id=14 Removed CatteryCove (8/13)
I/SurfaceFlinger(  241): id=14 Removed CatteryCove (-2/13)
D/KeyguardUpdateMonitor( 1068): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1068): handleKeyguardVisibilityChanged(1)
W/ContextImpl( 2905): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1857 android.content.ContextWrapper.startService:506 android.content.ContextWrapper.startService:506 com.samsung.android.app.assistantmenu.AssistantMenuReceiver.onReceive:153 android.app.ActivityThread.handleReceiver:2698 
W/ActivityManager(  775): Permission Denial: getCurrentUser() from pid=4745, uid=10179 requires android.permission.INTERACT_ACROSS_USERS
I/SELinux ( 4761): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 4761):  
W/ActivityManager(  775): Permission Denial: getCurrentUser() from pid=4745, uid=10179 requires android.permission.INTERACT_ACROSS_USERS
V/WebViewChromium( 4745): Binding Chromium to the background looper Looper (main, tid 1) {425055e8}
I/chromium( 4745): [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserProcessMain( 4745): Initializing chromium process, renderers=0
I/SELinux ( 4761): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 4761):  
I/SELinux ( 4761):  
I/SELinux ( 4761): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 4761): [DEBUG] seapp_context_lookup: seinfoCategory = samsung
E/dalvikvm( 4761): >>>>> Normal User
E/dalvikvm( 4761): >>>>> com.sec.android.service.cm [ userId:0 | appId:10078 ]
E/SELinux ( 4761): [DEBUG] seapp_context_lookup: seinfoCategory = samsung
W/chromium( 4745): [WARNING:proxy_service.cc(888)] PAC support disabled because there is no system implementation
D/TimaKeyStoreProvider( 4761): in addTimaSignatureService
D/TimaKeyStoreProvider( 4761): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 4761): Added TimaKesytore provider
I/IcingCorporaProvider( 2145): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
D/CapabilityManagerService New( 4761): Receiver Broadcast:android.intent.action.PACKAGE_ADDED
W/ActivityManager(  775): Permission Denial: getCurrentUser() from pid=4761, uid=10078 requires android.permission.INTERACT_ACROSS_USERS
I/SELinux ( 4784): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 4784):  
I/ActivityManager(  775): Killing 3368:com.sec.modem.settings/1000 (adj 15): empty #43
I/SELinux ( 4784): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 4784):  
I/SELinux ( 4784):  
I/SELinux ( 4784): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 4784): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 4784): >>>>> Normal User
E/dalvikvm( 4784): >>>>> com.google.android.apps.docs [ userId:0 | appId:10090 ]
E/SELinux ( 4784): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
D/TimaKeyStoreProvider( 4784): in addTimaSignatureService
D/TimaKeyStoreProvider( 4784): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 4784): Added TimaKesytore provider
I/IcingCorporaProvider( 2145): UpdateCorporaTask done [took 180 ms] updated apps [took 180 ms] 
W/ActivityManager(  775): Permission Denial: getCurrentUser() from pid=4784, uid=10090 requires android.permission.INTERACT_ACROSS_USERS
I/Adreno-EGL( 4745): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 4745): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 4745): Build Date: 03/21/14 Fri
I/Adreno-EGL( 4745): Local Branch: AU200+patches_03212014
I/Adreno-EGL( 4745): Remote Branch: 
I/Adreno-EGL( 4745): Local Patches: 
I/Adreno-EGL( 4745): Reconstruct Branch: 
I/SurfaceFlinger(  241): id=17 Removed TettingsRec (8/12)
I/SurfaceFlinger(  241): id=17 Removed TettingsRec (-2/12)
D/KeyguardUpdateMonitor( 1068): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1068): handleKeyguardVisibilityChanged(1)
I/SecureStorage(  294): [INFO]: SPID(0x00000003)Secure Storage Daemon finished processing with result: 0
I/SecureStorage(  294): [INFO]: SPID(0x00000003)PID: 4632, TID: 4632
I/SurfaceFlinger(  241): id=10 Removed Mauncher (7/11)
I/SurfaceFlinger(  241): id=10 Removed Mauncher (-2/11)
D/KeyguardUpdateMonitor( 1068): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1068): handleKeyguardVisibilityChanged(1)
D/SurfaceWidgetClient$ISurfaceWidgetStub( 1454): [237392/5] Surface widget visibility changed visibility = false on instance = 1
D/Launcher( 1251): onTrimMemory. Level: 20
I/SecureStorage( 4632): [INFO]: SPID(0x00000000)Processing data has been completed
I/SecureStorage( 4632): [INFO]: SPID(0x00000000)WARNING! Failed to find SecureStorageExceptionJNI!..
I/SQLiteSecureOpenHelper( 4632): getWritableDatabase(pwd)
I/SQLiteSecureOpenHelper( 4632): getDatabaseLocked(b,b,pwd)...
I/SQLiteSecureOpenHelper( 4632): Open platform.db in secure mode
I/dalvikvm( 4745): Could not find method android.webkit.CookieManager.setAcceptThirdPartyCookies, referenced from method org.apache.cordova.engine.SystemCookieManager.<init>
D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
D/BatteryService(  775): level:100, scale:100, status:5, health:2, present:true, voltage: 4366, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:40, charge type:1, power sharing:false
D/BatteryService(  775): Sending ACTION_BATTERY_CHANGED.
D/BatteryService(  775): stay LED for fully charged
D/UiModeManager(  775): mCoverManager.getCoverState() : true
W/dalvikvm( 4745): VFY: unable to resolve virtual method 218: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
D/dalvikvm( 4745): VFY: replacing opcode 0x6e at 0x0016
I/dalvikvm( 4745): Could not find method android.webkit.CookieManager.flush, referenced from method org.apache.cordova.engine.SystemCookieManager.flush
W/dalvikvm( 4745): VFY: unable to resolve virtual method 213: Landroid/webkit/CookieManager;.flush ()V
D/dalvikvm( 4745): VFY: replacing opcode 0x6e at 0x0008
W/dalvikvm( 4745): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 4745): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
I/dalvikvm( 4745): Could not find method android.webkit.WebViewClient.onReceivedClientCertRequest, referenced from method org.apache.cordova.engine.SystemWebViewClient.onReceivedClientCertRequest
W/dalvikvm( 4745): VFY: unable to resolve virtual method 271: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
D/dalvikvm( 4745): VFY: replacing opcode 0x6f at 0x001a
W/dalvikvm( 4745): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
I/dalvikvm( 4745): Could not find method android.webkit.PermissionRequest.getResources, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onPermissionRequest
W/dalvikvm( 4745): VFY: unable to resolve virtual method 229: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
D/dalvikvm( 4745): VFY: replacing opcode 0x6e at 0x000d
I/dalvikvm( 4745): Could not find method android.webkit.WebChromeClient$FileChooserParams.createIntent, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onShowFileChooser
W/dalvikvm( 4745): VFY: unable to resolve virtual method 234: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
D/dalvikvm( 4745): VFY: replacing opcode 0x6e at 0x0000
D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SystemWebViewEngine( 4745): CordovaWebView is running on device made by: samsung
I/SELinux ( 4804): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 4804):  
I/ActivityManager(  775): Killing 1342:com.sec.android.provider.badge/u0a72 (adj 15): empty #43
D/STATUSBAR-IconMerger( 1068): checkOverflow(384), More:false, Req:false Child:2
W/GAV2    ( 4784): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
I/SELinux ( 4804): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 4804):  
I/SELinux ( 4804):  
I/SELinux ( 4804): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 4804): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 4804): >>>>> Normal User
E/dalvikvm( 4804): >>>>> com.samsung.android.app.watchmanagerstub [ userId:0 | appId:10100 ]
E/SELinux ( 4804): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 4804): in addTimaSignatureService
,D/TimaKeyStoreProvider( 4804): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 4804): Added TimaKesytore provider
,I/SurfaceFlinger(  241): id=18 createSurf (1x1),1 flag=404, NainActivit
,D/KeyguardUpdateMonitor( 1068): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1068): handleKeyguardVisibilityChanged(1)
,D/KeyguardUpdateMonitor( 1068): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1068): handleKeyguardVisibilityChanged(1)
,I/HWUI    ( 4745): EGLImpl-HWUI Protected EGL context created
,D/PackageIntentReceiver( 4804): ACTION_PACKAGE_ADDED
,D/PackageIntentReceiver( 4804): Not GearManger package! 
,D/OpenGLRenderer( 4745): Enabling debug mode 0
,I/SELinux ( 4831): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 4831):  
D/OpenGLRenderer( 4745): GL error from OpenGLRenderer: 0x502
,E/OpenGLRenderer( 4745):   GL_INVALID_OPERATION
,D/KeyguardUpdateMonitor( 1068): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1068): handleKeyguardVisibilityChanged(1)
,D/CustomFrequencyManagerService(  775): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 775  tag : ACTIVITY_RESUME_BOOSTER@5
,W/ActivityManager(  775): mDVFSHelper.release()
,D/KeyguardUpdateMonitor( 1068): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1068): handleKeyguardVisibilityChanged(1)
D/CustomFrequencyManagerService(  775): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 775  pkgName : ACTIVITY_RESUME_BOOSTER@9
,I/SELinux ( 4831): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 4831):  
I/SELinux ( 4831):  
,I/SELinux ( 4831): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 4831): [DEBUG] seapp_context_lookup: seinfoCategory = release
E/dalvikvm( 4831): >>>>> Normal User
,E/dalvikvm( 4831): >>>>> com.samsung.android.magazine.service [ userId:0 | appId:10106 ]
,E/SELinux ( 4831): [DEBUG] seapp_context_lookup: seinfoCategory = release
,D/TimaKeyStoreProvider( 4831): in addTimaSignatureService
,D/TimaKeyStoreProvider( 4831): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 4831): Added TimaKesytore provider
I/SQLiteSecureOpenHelper( 4632): ...getDatabaseLocked(b,b,pwd)
D/SQLiteSecureOpenHelper( 4632): ...getDatabaseLocked(b,b,pwd)
,I/ActivityManager(  775): Killing 3386:tv.peel.smartremote/u0a163 (adj 15): empty #43
,D/MagazineService Version( 4831): Magazine-Channel: 13
,D/MagazineService Version( 4831): Magazine-Provider: 13
,D/MagazineService Version( 4831): Magazine-Administrator: 11
,W/ActivityManager(  775): Permission Denial: getCurrentUser() from pid=4831, uid=10106 requires android.permission.INTERACT_ACROSS_USERS
D/HeadlinesChannelApplication( 4831): [onCreate]
D/MagazineService::MagazineBroadcastReceiver( 4831): [onReceive] android.intent.action.PACKAGE_ADDED com.test.thalitest
,I/MagazineService::MagazineService( 4831): [onHandleIntent] ACTION_PACKAGE_INSTALLED
D/SSRMv2:SIOP(  775): SIOP:: AP = 310, Delta = 10
,I/SELinux ( 4846): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 4846):  
,D/MagazineService::MagazineService( 4831): [onHandleIntent] Send broadcast to (com.test.thalitest).
,W/GAV2    ( 4784): Thread[main,5,main]: dispatch call queued.  Need to call GAServiceManager.getInstance().initialize().
I/ActivityManager(  775): Killing 3413:org.simalliance.openmobileapi.service/1101 (adj 15): empty #43
I/ActivityManager(  775): Killing 3468:com.sec.android.app.taskmanager/u0a166 (adj 15): empty #43
,I/SELinux ( 4846): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 4846):  
I/SELinux ( 4846):  
,I/SELinux ( 4846): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 4846): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 4846): >>>>> Normal User
,E/dalvikvm( 4846): >>>>> com.samsung.helphub [ userId:0 | appId:1000 ]
,E/SELinux ( 4846): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 4846): in addTimaSignatureService
,D/TimaKeyStoreProvider( 4846): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 4846): Added TimaKesytore provider
,D/JsMessageQueue( 4745): Set native->JS mode to OnlineEventsBridgeMode
,I/Icing   ( 1804): Indexing 04B0A0E440E57B3CEEF518675F9B8A06EBE0353B from com.google.android.googlequicksearchbox
,I/SELinux ( 4863): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 4863):  
I/ActivityManager(  775): Killing 3484:com.samsung.android.service.travel/u0a169 (adj 15): empty #43
,I/SELinux ( 4863): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 4863):  
I/SELinux ( 4863):  
,I/SELinux ( 4863): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 4863): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 4863): >>>>> Normal User
,E/dalvikvm( 4863): >>>>> com.sec.kidsplat.installer [ userId:0 | appId:10158 ]
,E/SELinux ( 4863): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/dalvikvm( 4745): Trying to load lib /data/app-lib/com.test.thalitest-36/libjxcore.so 0x4282c310
,I/Icing   ( 1804): Indexing done 04B0A0E440E57B3CEEF518675F9B8A06EBE0353B
,D/dalvikvm( 4745): Added shared lib /data/app-lib/com.test.thalitest-36/libjxcore.so 0x4282c310
,D/jxcore_app_log( 4745): JniHelper::setJavaVM(0x41a624f8), pthread_self() = 1941854112
,D/JX-Cordova( 4745): jxcore cordova android initializing
,D/TimaKeyStoreProvider( 4863): in addTimaSignatureService
I/dalvikvm( 4745): Could not find method android.bluetooth.BluetoothAdapter.isMultipleAdvertisementSupported, referenced from method io.jxcore.node.ConnectionHelper.isBleAdvertisingSupported
W/dalvikvm( 4745): VFY: unable to resolve virtual method 52: Landroid/bluetooth/BluetoothAdapter;.isMultipleAdvertisementSupported ()Z
,D/dalvikvm( 4745): VFY: replacing opcode 0x6e at 0x0045
D/TimaKeyStoreProvider( 4863): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 4863): Added TimaKesytore provider
,W/ActivityManager(  775): Permission Denial: getCurrentUser() from pid=4863, uid=10158 requires android.permission.INTERACT_ACROSS_USERS
,D/KidsPlatformStub( 4863): Package not found : com.sec.android.app.kidshome
,I/SELinux ( 4875): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 4875):  
I/ActivityManager(  775): Killing 3497:com.google.android.youtube/u0a175 (adj 15): empty #43
,I/SELinux ( 4875): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 4875):  
I/SELinux ( 4875):  
,I/SELinux ( 4875): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 4875): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 4875): >>>>> Normal User
,E/dalvikvm( 4875): >>>>> com.samsung.android.provider.shootingmodeprovider [ userId:0 | appId:10162 ]
,E/SELinux ( 4875): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 4875): in addTimaSignatureService
,D/TimaKeyStoreProvider( 4875): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 4875): Added TimaKesytore provider
,I/SELinux ( 4887): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 4887):  
I/ActivityManager(  775): Killing 3181:com.sec.android.app.mt/1000 (adj 15): empty #43
,I/SELinux ( 4887): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 4887):  
I/SELinux ( 4887):  
,I/SELinux ( 4887): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 4887): [DEBUG] seapp_context_lookup: seinfoCategory = samsung
E/dalvikvm( 4887): >>>>> Normal User
,E/dalvikvm( 4887): >>>>> com.sec.android.app.samsungapps [ userId:0 | appId:10040 ]
,E/SELinux ( 4887): [DEBUG] seapp_context_lookup: seinfoCategory = samsung
,D/TimaKeyStoreProvider( 4887): in addTimaSignatureService
,D/TimaKeyStoreProvider( 4887): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 4887): Added TimaKesytore provider
,D/dalvikvm( 4745): GC_CONCURRENT freed 4924K, 33% free 12763K/19008K, paused 1ms+2ms, total 32ms
D/dalvikvm( 4745): WAIT_FOR_CONCURRENT_GC blocked 22ms
,D/dalvikvm( 4745): WAIT_FOR_CONCURRENT_GC blocked 16ms
,I/ActivityManager(  775): Killing 3698:com.sec.android.widgetapp.activeapplicationwidget/u0a152 (adj 15): empty #43
,D/ChimeraCfgMgr( 1804): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 1804): Loading module APK com.google.android.play.games
,D/PackageBroadcastService( 1804): Received broadcast action=android.intent.action.PACKAGE_ADDED and uri=com.test.thalitest
I/dalvikvm( 1804): Could not find method android.app.admin.DevicePolicyManager.getProfileOwner, referenced from method com.google.android.gms.auth.WorkAccountAuthenticatorInitializer.a
W/dalvikvm( 1804): VFY: unable to resolve virtual method 174: Landroid/app/admin/DevicePolicyManager;.getProfileOwner ()Landroid/content/ComponentName;
,D/dalvikvm( 1804): VFY: replacing opcode 0x6e at 0x0053
,D/Finsky  ( 3577): [1] ExternalReferrer.access$200: Package state data is missing for com.test.thalitest
,I/dalvikvm( 1804): Failed resolving Lcom/google/android/gms/common/permission/PermissionUtils$1; interface 96 'Landroid/content/pm/PackageManager$OnPermissionsChangedListener;'
,W/dalvikvm( 1804): Link of class 'Lcom/google/android/gms/common/permission/PermissionUtils$1;' failed
E/dalvikvm( 1804): Could not find class 'com.google.android.gms.common.permission.PermissionUtils$1', referenced from method com.google.android.gms.chimera.GmsModuleInitializer.initializeModuleV0
W/dalvikvm( 1804): VFY: unable to resolve new-instance 2374 (Lcom/google/android/gms/common/permission/PermissionUtils$1;) in Lcom/google/android/gms/chimera/GmsModuleInitializer;
,D/dalvikvm( 1804): VFY: replacing opcode 0x22 at 0x001a
I/dalvikvm( 1804): Failed resolving Lcom/google/android/gms/common/permission/PermissionUtils$1; interface 96 'Landroid/content/pm/PackageManager$OnPermissionsChangedListener;'
,W/dalvikvm( 1804): Link of class 'Lcom/google/android/gms/common/permission/PermissionUtils$1;' failed
,D/dalvikvm( 1804): DexOpt: unable to opt direct call 0x338d at 0x1c in Lcom/google/android/gms/chimera/GmsModuleInitializer;.initializeModuleV0
,D/CustomFrequencyManagerService(  775): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 775  tag : ACTIVITY_RESUME_BOOSTER@9
,D/ChimeraCfgMgr( 1804): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 1804): Module APK com.google.android.play.games already loaded
,D/ChimeraCfgMgr( 1804): Loading module com.google.android.gms.gass from APK com.google.android.gms
,D/AsyncTaskServiceImpl( 1804): Submit a task: k
,D/ChimeraCfgMgr( 1804): Loading module com.google.android.gms.gass from APK com.google.android.gms
,D/ChimeraCfgMgr( 1804): Loading module com.google.android.gms.vision from APK com.google.android.gms
,W/BaseAppContext( 1804): Using Auth Proxy for data requests.
,D/k       ( 1804): Processing package: com.test.thalitest
,W/BaseAppContext( 1804): Using Auth Proxy for data requests.
,D/GassUtils( 1804): Found app info for package com.test.thalitest:18. Hash: 4eebbbb84f07ed56a3e96e5e8f9d6abddaaf154fffa2a65432a1006e0fa38f32
,D/k       ( 1804): Found info for package com.test.thalitest in db.
,W/BaseAppContext( 1804): Using Auth Proxy for data requests.
,D/dalvikvm( 1323): GC_EXPLICIT freed 1034K, 44% free 10795K/19008K, paused 2ms+5ms, total 41ms
,W/BaseAppContext( 1804): Using Auth Proxy for data requests.
,W/BaseAppContext( 1804): Using Auth Proxy for data requests.
,W/BaseAppContext( 1804): Using Auth Proxy for data requests.
,W/BaseAppContext( 1804): Using Auth Proxy for data requests.
,W/dalvikvm( 1804): VFY: unable to find class referenced in signature (Landroid/app/SharedElementCallback;)
,I/dalvikvm( 1804): Could not find method android.app.Activity.setEnterSharedElementCallback, referenced from method android.support.v4.app.w.setEnterSharedElementCallback
W/dalvikvm( 1804): VFY: unable to resolve virtual method 53: Landroid/app/Activity;.setEnterSharedElementCallback (Landroid/app/SharedElementCallback;)V
D/dalvikvm( 1804): VFY: replacing opcode 0x6e at 0x000e
,W/dalvikvm( 1804): VFY: unable to find class referenced in signature (Landroid/app/SharedElementCallback;)
I/dalvikvm( 1804): Could not find method android.app.Activity.setExitSharedElementCallback, referenced from method android.support.v4.app.w.setExitSharedElementCallback
W/dalvikvm( 1804): VFY: unable to resolve virtual method 54: Landroid/app/Activity;.setExitSharedElementCallback (Landroid/app/SharedElementCallback;)V
D/dalvikvm( 1804): VFY: replacing opcode 0x6e at 0x000e
,I/dalvikvm( 1804): Could not find method android.app.Activity.finishAfterTransition, referenced from method android.support.v4.app.w.supportFinishAfterTransition
W/dalvikvm( 1804): VFY: unable to resolve virtual method 31: Landroid/app/Activity;.finishAfterTransition ()V
D/dalvikvm( 1804): VFY: replacing opcode 0x6e at 0x0006
I/dalvikvm( 1804): Could not find method android.app.Activity.postponeEnterTransition, referenced from method android.support.v4.app.w.supportPostponeEnterTransition
W/dalvikvm( 1804): VFY: unable to resolve virtual method 49: Landroid/app/Activity;.postponeEnterTransition ()V
D/dalvikvm( 1804): VFY: replacing opcode 0x6e at 0x0006
I/dalvikvm( 1804): Could not find method android.app.Activity.startPostponedEnterTransition, referenced from method android.support.v4.app.w.supportStartPostponedEnterTransition
W/dalvikvm( 1804): VFY: unable to resolve virtual method 61: Landroid/app/Activity;.startPostponedEnterTransition ()V
,D/dalvikvm( 1804): VFY: replacing opcode 0x6e at 0x0006
,I/PeopleDatabaseHelper( 1804): cleanUpNonGplusAccounts done.
,D/dalvikvm( 4745): GC_FOR_ALLOC freed 4723K, 28% free 15769K/21832K, paused 33ms, total 36ms
,E/SMD     (  235): DCD ON
,D/dalvikvm(  775): GC_EXPLICIT freed 1956K, 58% free 23281K/55124K, paused 16ms+16ms, total 192ms
,D/dalvikvm( 1804): GC_CONCURRENT freed 1714K, 38% free 11785K/19008K, paused 6ms+5ms, total 43ms
,W/dalvikvm( 1804): VFY: unable to find class referenced in signature (Landroid/util/Size;)
,D/ChimeraCfgMgr( 1804): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 1804): Module APK com.google.android.play.games already loaded
,D/dalvikvm( 4745): GC_FOR_ALLOC freed 5082K, 32% free 16781K/24520K, paused 36ms, total 36ms
,I/dalvikvm-heap( 4745): Grow heap (frag case) to 22.038MB for 2475476-byte allocation
,I/Icing   ( 1804): Indexing 49CA7E3A917E607C6D98AA15891295369CED2106 from com.google.android.gms
,I/Icing   ( 1804): Indexing done 49CA7E3A917E607C6D98AA15891295369CED2106
,D/dalvikvm( 4745): GC_FOR_ALLOC freed 3778K, 36% free 17468K/26940K, paused 33ms, total 36ms
,D/dalvikvm( 4745): GC_FOR_ALLOC freed 1246K, 36% free 17372K/26940K, paused 30ms, total 32ms
,W/jxcore-log( 4745): Initializing JXcore engine
,W/jxcore-log( 4745): JXcore engine is ready
,W/jxcore-log( 4745): Starting JXcore engine
,W/jxcore-log( 4745): Platform android
W/jxcore-log( 4745): 
,W/jxcore-log( 4745): Process ARCH arm
W/jxcore-log( 4745): 
,I/jxcore-log( 4745): JXcore Cordova bridge is ready!
I/jxcore-log( 4745): 
,W/jxcore-log( 4745): JXcore engine is started
,I/chromium( 4745): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot call method 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,E/SMD     (  235): DCD ON
,I/GAV2    ( 4784): Thread[GAThread,5,main]: No campaign data found.
,I/jxcore-log( 4745): Toggling radios to true
I/jxcore-log( 4745): 
,W/ActivityManager(  775): Permission Denial: getCurrentUser() from pid=4745, uid=10179 requires android.permission.INTERACT_ACROSS_USERS
,W/BluetoothManagerService(  775): Failed getting userId using ActivityManagerNative
W/BluetoothManagerService(  775): java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=4745, uid=10179 requires android.permission.INTERACT_ACROSS_USERS
W/BluetoothManagerService(  775): 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:20710)
W/BluetoothManagerService(  775): 	at com.android.server.BluetoothManagerService.enable(BluetoothManagerService.java:620)
W/BluetoothManagerService(  775): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:98)
W/BluetoothManagerService(  775): 	at android.os.Binder.execTransact(Binder.java:404)
W/BluetoothManagerService(  775): 	at dalvik.system.NativeStart.run(Native Method)
E/DevicePolicyManagerService(  775): getAllowBluetoothMode - value retunrs : 2
,D/BluetoothManagerService(  775): foregroundUser: 0
,E/BluetoothManagerService(  775): Package is exist.
,D/BluetoothAdapterState( 3229): CURRENT_STATE=OFF, MSG = USER_TURN_ON
I/BluetoothAdapterState( 3229): Bluetooth adapter state changed: 10-> 11
D/BluetoothAdapterService( 3229): Bluetooth PBAP supproted is true
D/BluetoothAdapterService( 3229): updateAdapterState state is 11
D/BluetoothAdapterService( 3229): Broadcasting updateAdapterState() to 1 receivers.
D/BluetoothAdapterService( 3229): Autoconnection is available 
,D/BluetoothAdapterService( 3229): updateAdapterState prevState = 10newState = 11
D/BtConfig.SecureMode( 3229): isSecureModeOn:false
,D/BtSettings.ProfileConfig( 3229): getProfileSaveSetting: com.android.bluetooth.gatt.GattService
,W/BluetoothAdapterService( 3229): isProfileEnabled(): profile com.android.bluetooth.gatt.GattService, state= 12
,D/BtSettings.ProfileConfig( 3229): getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
,W/BluetoothAdapterService( 3229): isProfileEnabled(): profile not found com.android.bluetooth.hfp.HeadsetService
,D/BtSettings.ProfileConfig( 3229): getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
,W/BluetoothAdapterService( 3229): isProfileEnabled(): profile not found com.android.bluetooth.a2dp.A2dpService
,D/BtSettings.ProfileConfig( 3229): getProfileSaveSetting: com.android.bluetooth.hid.HidService
,W/BluetoothAdapterService( 3229): isProfileEnabled(): profile not found com.android.bluetooth.hid.HidService
,D/BtSettings.ProfileConfig( 3229): getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
W/BluetoothAdapterService( 3229): isProfileEnabled(): profile not found com.android.bluetooth.hdp.HealthService
D/BtSettings.ProfileConfig( 3229): getProfileSaveSetting: com.android.bluetooth.pan.PanService
,W/BluetoothAdapterService( 3229): isProfileEnabled(): profile not found com.android.bluetooth.pan.PanService
,D/BtSettings.ProfileConfig( 3229): getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
W/BluetoothAdapterService( 3229): isProfileEnabled(): profile not found com.android.bluetooth.map.BluetoothMapService
,W/BluetoothAdapterService( 3229): Unable to stop service com.android.bluetooth.gatt.GattService. Invalid state: 12
W/BluetoothAdapterService( 3229): check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.hfp.HeadsetService
D/BtSettings.ProfileConfig( 3229): getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
,W/BluetoothAdapterService( 3229): Not skipping com.android.bluetooth.hfp.HeadsetService
W/InputMethodManagerService(  775): InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
,I/InputMethodManagerService(  775): [BT Setting State] State =11
D/PhoneApp( 1240): mReceiver: BluetoothAdapter.ACTION_STATE_CHANGED: 11
,I/QuickConnect[1.1][2] ( 3199): BluetoothHelper.ACTION_STATE_CHANGED - STATE_TURNING_ON
,W/BluetoothAdapterService( 3229): check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.a2dp.A2dpService
,D/BtSettings.ProfileConfig( 3229): getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
,W/BluetoothAdapterService( 3229): Not skipping com.android.bluetooth.a2dp.A2dpService
,W/BluetoothAdapterService( 3229): check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.hid.HidService
D/BtSettings.ProfileConfig( 3229): getProfileSaveSetting: com.android.bluetooth.hid.HidService
,W/BluetoothAdapterService( 3229): Not skipping com.android.bluetooth.hid.HidService
,W/BluetoothAdapterService( 3229): check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.hdp.HealthService
D/BtSettings.ProfileConfig( 3229): getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
,W/BluetoothAdapterService( 3229): Not skipping com.android.bluetooth.hdp.HealthService
,W/BluetoothAdapterService( 3229): check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.pan.PanService
,D/BtSettings.ProfileConfig( 3229): getProfileSaveSetting: com.android.bluetooth.pan.PanService
,W/BluetoothAdapterService( 3229): Not skipping com.android.bluetooth.pan.PanService
,W/BluetoothAdapterService( 3229): check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.map.BluetoothMapService
D/BtSettings.ProfileConfig( 3229): getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
,W/BluetoothAdapterService( 3229): Not skipping com.android.bluetooth.map.BluetoothMapService
,I/BluetoothAdapterState( 3229): Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
,D/HeadsetService( 3229): Received start request. Starting profile...
,I/BluetoothHeadsetServiceJni( 3229): classInitNative: succeeds
D/HeadsetStateMachine( 3229): Version 1.6
,D/HeadsetStateMachine( 3229): make
,D/QuickConnect[1.1][2] ( 3199): HeadsetProfile.onServiceConnected - Bluetooth service connected
,E/HeadsetStateMachine( 3229): # of Max HF connection is 2
,I/WifiManager( 4745): packageName : com.test.thalitest
I/WifiManager( 4745): setWifiEnabled : true
,I/WifiService(  775): setWifiEnabled: true pid=4745, uid=10179
,W/ActivityManager(  775): Permission Denial: getCurrentUser() from pid=4745, uid=10179 requires android.permission.INTERACT_ACROSS_USERS
W/WifiService(  775): Failed getting userId using ActivityManagerNative
W/WifiService(  775): java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=4745, uid=10179 requires android.permission.INTERACT_ACROSS_USERS
W/WifiService(  775): 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:20710)
W/WifiService(  775): 	at com.android.server.wifi.WifiService.setWifiEnabled(WifiService.java:2348)
W/WifiService(  775): 	at com.android.server.wifi.WifiService.setWifiEnabled(WifiService.java:2336)
W/WifiService(  775): 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:178)
W/WifiService(  775): 	at android.os.Binder.execTransact(Binder.java:404)
W/WifiService(  775): 	at dalvik.system.NativeStart.run(Native Method)
,I/bluedroid( 3229): get_profile_interface handsfree
,D/BluetoothNotiBroadcastReceiver( 1307): onReceive
,D/BluetoothAtMessage( 3229): createCMTIContentObservers
,E/WifiHW  (  775): ##################### set firmware type 0 #####################
D/HeadsetStateMachine( 3229): Enter Disconnected: -2
I/WifiService(  775): disconnect: pid=4745, uid=10179
,E/HeadsetStateMachine( 3229): set to mRemoteBrsf = 0
,I/jxcore-log( 4745): Radios toggled
I/jxcore-log( 4745): 
,D/HeadsetStateMachine( 3229): map size, before remove : 0
,D/HeadsetStateMachine( 3229): map size, after remove: 0
,D/HeadsetStateMachine( 3229): mNextConnectingDevice : null
D/BluetoothA2dp(  775): Proxy object connected
,D/BluetoothA2dp( 3199): Proxy object connected
,D/QuickConnect[1.1][2] ( 3199): A2dpProfile.onServiceConnected - Bluetooth service connected
,D/A2dpService( 3229): Received start request. Starting profile...
I/BluetoothA2dpServiceJni( 3229): classInitNative: succeeds
D/A2dpStateMachine( 3229): make
,D/BluetoothA2dp( 2050): Proxy object connected
,I/jxcore-log( 4745): Got Device Bluetooth address: 38:94:96:B5:06:DC
I/jxcore-log( 4745): 
,I/jxcore-log( 4745): Perf Test app loaded loaded
I/jxcore-log( 4745): 
,I/bluedroid( 3229): get_profile_interface a2dp
,I/GKI_LINUX( 3229): gki_task_entry: gki_task_entry task_id=2 [A2DP-MEDIA] starting
,I/BluetoothAvrcpServiceJni( 3229): classInitNative: succeeds
I/jxcore-log( 4745): check test folder
I/jxcore-log( 4745): 
D/A2dpStateMachine( 3229): Enter Disconnected: -2
,I/bluedroid( 3229): get_profile_interface avrcp
,I/jxcore-log( 4745): found test : ./testFindPeers.js
I/jxcore-log( 4745): 
,D/MediaFocusControl(  775): >>> registerRemoteControlDisplay
,E/MediaFocusControl(  775): Error updating focussed RCC to RCD 
E/MediaFocusControl(  775): java.util.EmptyStackException
E/MediaFocusControl(  775): 	at java.util.Stack.peek(Stack.java:57)
E/MediaFocusControl(  775): 	at android.media.MediaFocusControl.registerRemoteControlDisplay_int(MediaFocusControl.java:2308)
E/MediaFocusControl(  775): 	at android.media.MediaFocusControl.registerRemoteControlDisplay(MediaFocusControl.java:250)
E/MediaFocusControl(  775): 	at android.media.AudioService.registerRemoteControlDisplay(AudioService.java:6425)
E/MediaFocusControl(  775): 	at android.media.IAudioService$Stub.onTransact(IAudioService.java:593)
E/MediaFocusControl(  775): 	at android.os.Binder.execTransact(Binder.java:404)
E/MediaFocusControl(  775): 	at dalvik.system.NativeStart.run(Native Method)
,I/BluetoothHidServiceJni( 3229): classInitNative: succeeds
,D/BluetoothInputDevice( 3199): Proxy object connected
,D/QuickConnect[1.1][2] ( 3199): HidProfile.onServiceConnected - Bluetooth service connected
D/HidService( 3229): Received start request. Starting profile...
I/bluedroid( 3229): get_profile_interface hidhost
D/HidService( 3229): setHidService(): set to: null
,I/BluetoothHealthServiceJni( 3229): classInitNative: succeeds
,D/HealthService( 3229): Received start request. Starting profile...
,I/bluedroid( 3229): get_profile_interface health
,I/BluetoothPanServiceJni( 3229): classInitNative(L105): succeeds
,D/BluetoothPan(  775): BluetoothPAN Proxy object connected
D/PanService( 3229): Received start request. Starting profile...
D/BluetoothPanServiceJni( 3229): initializeNative(L110): pan
,I/bluedroid( 3229): get_profile_interface pan
,D/BluetoothTethering(  775): got CMD_CHANNEL_HALF_CONNECTED
,D/BluetoothMapService( 3229): Received start request. Starting profile...
,W/BluetoothMapMasInstance( 3229): mAccount : null
,D/HeadsetStateMachine( 3229): Try to query the phonestate on bind
D/BluetoothPhoneService( 1240): handleMessage: 4
,V/BluetoothPhoneService( 1240): Call state Converted2: IDLE/IDLE -> 6
,W/BluetoothHeadset( 1240): Proxy not attached to service
,D/HeadsetStateMachine( 3229): Proxy object connected
,D/HeadsetPhoneState( 3229): sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=0
,D/HeadsetPhoneState( 3229): sendDeviceDataStateChanged
,D/HeadsetPhoneState( 3229): Signal level : previous=0 curr=0
D/BluetoothAdapterService( 3229): Profile still not running:com.android.bluetooth.hdp.HealthService
,V/HeadsetService( 3229): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 3229): Disconnected process message: 11
D/HeadsetStateMachine( 3229): Disconnected process message: 20
,D/HeadsetStateMachine( 3229): Disconnected process message: 10
I/jxcore-log( 4745): found test : ./testSendData.js
I/jxcore-log( 4745): 
D/HeadsetPhoneState( 3229): sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
,D/HeadsetStateMachine( 3229): Disconnected process message: 11
D/BluetoothAdapterService( 3229): Profile still not running:com.android.bluetooth.hdp.HealthService
D/BluetoothAdapterService( 3229): Profile still not running:com.android.bluetooth.hdp.HealthService
D/BluetoothAdapterService( 3229): Profile still not running:com.android.bluetooth.map.BluetoothMapService
,D/BluetoothAdapterService( 3229): Profile still not running:com.android.bluetooth.map.BluetoothMapService
,D/AuthorizationBluetoothService( 1323): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,D/BluetoothAdapterState( 3229): CURRENT_STATE=PENDING, MSG = STARTED, isTurningOn=true, isTurningOff=false
,I/bluedroid( 3229): enable
,D/GKI_LINUX( 3229): acquire_my_wake_lock(), g_wake_lock_fd:-1, g_wake_unlock_fd:-1, wake_lock_acquired:0
,E/bt-btif ( 3229): Calling BTA_HhEnable
,E/bt-btif ( 3229): btif_storage_get_adapter_property service_mask:0x140040
E/BluetoothServiceJni( 3229): populateRssiValuesNative
I/bluedroid( 3229): getModelRssiValues
,E/BluetoothServiceJni( 3229): model_rssi_values_callback: low = -70, mid = -60, high = 127
,E/BluetoothRemoteDevices( 3229): devicePropertyChangedCallback: bdDevice: 08:EC:A9:50:75:41, value is empty for type: 10
,D/BtConfig.SecureMode( 3229): isSecureModeOn:false
,E/BluetoothRemoteDevices( 3229): devicePropertyChangedCallback: bdDevice: 08:EC:A9:50:75:41, value is empty for type: 241
,E/BluetoothRemoteDevices( 3229): devicePropertyChangedCallback: bdDevice: 80:01:84:8A:B3:68, value is empty for type: 10
,D/BtConfig.SecureMode( 3229): isSecureModeOn:false
,E/BluetoothRemoteDevices( 3229): devicePropertyChangedCallback: bdDevice: 80:01:84:8A:B3:68, value is empty for type: 241
,E/BluetoothRemoteDevices( 3229): devicePropertyChangedCallback: bdDevice: B0:C5:59:3F:75:69, value is empty for type: 10
,D/BtConfig.SecureMode( 3229): isSecureModeOn:false
,E/BluetoothRemoteDevices( 3229): devicePropertyChangedCallback: bdDevice: B0:C5:59:3F:75:69, value is empty for type: 241
,E/BluetoothRemoteDevices( 3229): devicePropertyChangedCallback: bdDevice: 00:F4:6F:30:E0:6C, value is empty for type: 10
,D/BtConfig.SecureMode( 3229): isSecureModeOn:false
,E/BluetoothRemoteDevices( 3229): devicePropertyChangedCallback: bdDevice: 00:F4:6F:30:E0:6C, value is empty for type: 241
,E/BluetoothRemoteDevices( 3229): devicePropertyChangedCallback: bdDevice: 34:FC:EF:9D:93:0B, value is empty for type: 10
,D/BtConfig.SecureMode( 3229): isSecureModeOn:false
,E/BluetoothRemoteDevices( 3229): devicePropertyChangedCallback: bdDevice: 34:FC:EF:9D:93:0B, value is empty for type: 241
,E/BluetoothRemoteDevices( 3229): devicePropertyChangedCallback: bdDevice: 7C:F9:0E:51:18:22, value is empty for type: 10
,D/BtConfig.SecureMode( 3229): isSecureModeOn:false
,E/BluetoothRemoteDevices( 3229): devicePropertyChangedCallback: bdDevice: 7C:F9:0E:51:18:22, value is empty for type: 241
,E/BluetoothRemoteDevices( 3229): devicePropertyChangedCallback: bdDevice: B4:CE:F6:AB:A4:6A, value is empty for type: 10
,D/BtConfig.SecureMode( 3229): isSecureModeOn:false
,E/BluetoothRemoteDevices( 3229): devicePropertyChangedCallback: bdDevice: B4:CE:F6:AB:A4:6A, value is empty for type: 241
,E/BluetoothRemoteDevices( 3229): devicePropertyChangedCallback: bdDevice: 34:FC:EF:11:AE:67, value is empty for type: 10
,D/BtConfig.SecureMode( 3229): isSecureModeOn:false
,E/BluetoothRemoteDevices( 3229): devicePropertyChangedCallback: bdDevice: 34:FC:EF:11:AE:67, value is empty for type: 241
,E/BluetoothRemoteDevices( 3229): devicePropertyChangedCallback: bdDevice: 34:FC:EF:11:B1:66, value is empty for type: 10
,D/BtConfig.SecureMode( 3229): isSecureModeOn:false
,E/BluetoothRemoteDevices( 3229): devicePropertyChangedCallback: bdDevice: 34:FC:EF:11:B1:66, value is empty for type: 241
,E/BluetoothRemoteDevices( 3229): devicePropertyChangedCallback: bdDevice: 90:E7:C4:F6:69:77, value is empty for type: 10
,D/BtConfig.SecureMode( 3229): isSecureModeOn:false
,E/BluetoothRemoteDevices( 3229): devicePropertyChangedCallback: bdDevice: 90:E7:C4:F6:69:77, value is empty for type: 241
,E/bt-btif ( 3229): btif_handle_bluetooth_enable_evt: btif_core_radio_ref_count:2
,E/bt-btif ( 3229): btif_sock_init, radio_req:0, rfc_init:0, vhci_init:1
E/bt-btif ( 3229): btif_sock_init: !radio_req && !rfc_init
,D/IOP_DB_BT( 3229): db_open: file /etc/bluetooth/iop_bt.db
,D/IOP_DB_BT( 3229): db_open: db_open : handle 2012287768l, read 9734 bytes onto local cache
D/IOP_DB_BT( 3229): db_query: id __IOPFLAGS :: key __KEY_ENABLE_VERBOSE, value 1
D/IOP_DB_BT( 3229): db_query: result 1
I/        ( 3229): iop_db_open: iop_db_open status 0
,I/bte_conf( 3229): Attempt to load did conf from /etc/bluetooth/bt_did.conf
,I/bte_conf( 3229): [1] primary_record=1 vendor_id=0x0075 vendor_id_source=0x0001 product_id=0x0100 version=0x0200
,I/bte_conf( 3229): Attempt to load did conf from /etc/bluetooth/bt_did.conf
,I/bte_conf( 3229): Attempt to load did conf from /etc/bluetooth/bt_did.conf
D/BluetoothAdapterState( 3229): CURRENT_STATE=PENDING, MSG = ENABLE_READY, isTurningOn=true, isTurningOff=false
,D/BluetoothAdapterProperties( 3229): ScanMode =  20
,D/BluetoothAdapterProperties( 3229): State =  11
,D/BtConfig.SecureMode( 3229): isSecureModeOn:false
D/BtConfig.SecureMode( 3229): isSecureModeOn:false
D/BtConfig.SecureMode( 3229): isSecureModeOn:false
,D/BtConfig.SecureMode( 3229): isSecureModeOn:false
D/BtConfig.SecureMode( 3229): isSecureModeOn:false
,D/BtConfig.SecureMode( 3229): isSecureModeOn:false
D/BtConfig.SecureMode( 3229): isSecureModeOn:false
,D/BtConfig.SecureMode( 3229): isSecureModeOn:false
D/BtConfig.SecureMode( 3229): isSecureModeOn:false
,D/BtConfig.SecureMode( 3229): isSecureModeOn:false
,I/BluetoothAdapterState( 3229): Bluetooth adapter state changed: 11-> 12
,D/BluetoothAdapterService( 3229): Bluetooth PBAP supproted is true
,D/BluetoothAdapterService( 3229): updateAdapterState state is 12
,D/BluetoothAdapterService( 3229): Broadcasting updateAdapterState() to 1 receivers.
,D/BluetoothA2dp(  775): onBluetoothStateChange: up=true
D/BluetoothAdapterService(1115950328)( 3229): Register RemoteMessageListener
,D/BluetoothInputDevice( 3199): onBluetoothStateChange: up=true
,D/HeadsetService( 3229): registerMessageListener
,D/BluetoothAdapterService( 3229): Autoconnection is available 
D/HeadsetStateMachine( 3229): Disconnected process message: 70
,D/HeadsetStateMachine( 3229): processRegisterMessageListener : 2, com.android.bluetooth.btservice.RemoteDevices$1@42882ff8
D/BluetoothAdapterService( 3229): updateAdapterState prevState = 11newState = 12
D/BluetoothA2dp( 3199): onBluetoothStateChange: up=true
,D/BluetoothA2dp( 2050): onBluetoothStateChange: up=true
I/BluetoothPbapService( 3229): action: android.bluetooth.adapter.action.STATE_CHANGED, state: 12
,I/BluetoothPbapService( 3229): Handler(): got msg=1
,D/BluetoothAdapterService( 3229): starting service from this receiver
,W/ContextImpl( 3229): Implicit intents with startService are not safe: Intent { act=com.samsung.ble.ACTION_SERVICE_BLE_AUTO_CONNECT } android.content.ContextWrapper.startService:506 com.android.bluetooth.btservice.AdapterService.updateAdapterState:653 com.android.bluetooth.btservice.AdapterState.notifyAdapterStateChange:586 
D/BluetoothAdapterService( 3229): initWakeLock, pfd lock: {ParcelFileDescriptor: FileDescriptor[91]}, pfd unlock: {ParcelFileDescriptor: FileDescriptor[92]}
,D/bluedroid( 3229): init_wake_lock lock_fd:91, unlock_fd:92
,W/InputMethodManagerService(  775): InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
,I/InputMethodManagerService(  775): [BT Setting State] State =12
I/BluetoothAdapterState( 3229): Entering On State from state = 11
,I/WifiTrafficPoller(  775): mBoosterFLAG : 2
,I/WifiTrafficPoller(  775): current booster mode : BTCoexMode
,I/InputMethodManagerService(  775): [BT Setting off -> on] mBTKeyboardCount =0, KEYBOARD_BT(0)
D/BluetoothAdapterService(1115950328)( 3229): Get Bonded Devices being called
D/PhoneApp( 1240): mReceiver: BluetoothAdapter.ACTION_STATE_CHANGED: 12
D/BluetoothHeadset( 1240): registerListener : 11, listenercom.android.phone.PhoneGlobals$MessageListener@42a4a748, true
D/BluetoothHeadset( 1240): registerMessageListener
I/QuickConnect[1.1][2] ( 3199): BluetoothHelper.ACTION_STATE_CHANGED - STATE_ON
,V/BluetoothPbapService( 3229): PBAP Service initSocket try: 0
,D/HeadsetService( 3229): registerMessageListener
,D/HeadsetService( 3229): registerMessageListener
D/PhoneApp( 1240): registerMessageListener
,D/HeadsetStateMachine( 3229): Disconnected process message: 70
,D/HeadsetStateMachine( 3229): processRegisterMessageListener : 11, com.samsung.bt.hfp.IMessageListener$Stub$Proxy@4290cdb8
,D/BluetoothPanServiceJni( 3229): control_state_callback(L61): state:0, local_role:0, ifname:bt-pan
,W/BluetoothAdapter( 3229): getBluetoothService() called with no BluetoothManagerCallback
,E/BluetoothServiceJni( 3229): SOCK FLAG = 1 ***********************
,D/BluetoothPbapService( 3229): PBAP Socket is BluetoothServerSocket
D/STATUSBAR-IconMerger( 1068): checkOverflow(336), More:false, Req:false Child:2
,D/BluetoothMapMasInstance( 3229): set MAP SDP message type : 1
,W/BluetoothAdapter( 3229): getBluetoothService() called with no BluetoothManagerCallback
,E/BluetoothServiceJni( 3229): SOCK FLAG = 3 ***********************
,W/ContextImpl( 1307): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1857 android.content.ContextWrapper.startService:506 android.content.ContextWrapper.startService:506 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,I/chromium( 4745): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,D/LocalBluetoothProfileManager( 1307): Adding local A2DP profile
,D/LocalBluetoothProfileManager( 1307): Adding local HEADSET profile
W/ContextImpl( 1307): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1930 android.content.ContextWrapper.bindService:529 android.bluetooth.BluetoothA2dp.doBind:221 android.bluetooth.BluetoothA2dp.<init>:214 android.bluetooth.BluetoothAdapter.getProfileProxy:1412 
,E/BluetoothHeadset( 1307): BTStateChangeCB is registed
,E/BluetoothHeadset( 1307): BluetoothHeadset service is binded
W/ContextImpl( 1307): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1930 android.content.ContextWrapper.bindService:529 android.bluetooth.BluetoothHeadset.doBind:304 android.bluetooth.BluetoothHeadset.<init>:297 android.bluetooth.BluetoothAdapter.getProfileProxy:1409 
,W/ContextImpl( 1307): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1930 android.content.ContextWrapper.bindService:529 com.broadcom.bt.service.sap.BluetoothSap.doBind:186 com.broadcom.bt.service.sap.BluetoothSap.<init>:179 com.android.settings.bluetooth.SapProfile.<init>:129 
D/Bluetoothsap( 1307): bindService called to Bluetooth SAP Service
,W/ContextImpl( 1307): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1930 android.content.ContextWrapper.bindService:529 android.bluetooth.BluetoothInputDevice.doBind:245 android.bluetooth.BluetoothInputDevice.<init>:238 android.bluetooth.BluetoothAdapter.getProfileProxy:1415 
,D/LocalBluetoothProfileManager( 1307): PANU : true
,D/LocalBluetoothProfileManager( 1307): Adding local MAP profile
,D/BluetoothMap( 1307): Create BluetoothMap proxy object
W/ContextImpl( 1307): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1930 android.content.ContextWrapper.bindService:529 android.bluetooth.BluetoothPan.doBind:173 android.bluetooth.BluetoothPan.<init>:162 android.bluetooth.BluetoothAdapter.getProfileProxy:1418 
W/ContextImpl( 1307): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1930 android.content.ContextWrapper.bindService:529 android.bluetooth.BluetoothMap.doBind:109 android.bluetooth.BluetoothMap.<init>:102 android.bluetooth.BluetoothAdapter.getProfileProxy:1424 
,W/ContextImpl( 1307): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1930 android.content.ContextWrapper.bindService:529 android.bluetooth.BluetoothPbap.doBind:164 android.bluetooth.BluetoothPbap.<init>:157 com.android.settings.bluetooth.PbapServerProfile.<init>:68 
,D/GKI_LINUX( 3229): release_my_wake_lock(), g_wake_lock_fd:91, g_wake_unlock_fd:92, wake_lock_acquired:0
D/Bluetoothsap( 1307): bindService called to Bluetooth SAP Service
,D/LocalBluetoothProfileManager( 1307): LocalBluetoothProfileManager construction complete
,D/DockEventReceiver( 1307): finishStartingService: stopping service
,W/ContextImpl( 1307): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1930 android.content.ContextWrapper.bindService:529 com.broadcom.bt.service.sap.BluetoothSap.doBind:186 com.broadcom.bt.service.sap.BluetoothSap.<init>:179 com.android.settings.bluetooth.SapProfile.<init>:129 
D/BluetoothNotiBroadcastReceiver( 1307): onReceive
D/BluetoothA2dp( 1307): Proxy object connected
D/BtConfig.SecureMode( 3229): isSecureModeOn:false
D/A2dpProfile( 1307): Bluetooth service connected
,D/AuthorizationBluetoothService( 1323): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,E/AuthorizationBluetoothService( 1323): Proximity feature is not enabled.
,D/HeadsetProfile( 1307): Bluetooth service connected
,D/BluetoothInputDevice( 1307): Proxy object connected
,W/BluetoothAdapter( 3229): getBluetoothService() called with no BluetoothManagerCallback
,E/BluetoothServiceJni( 3229): SOCK FLAG = 0 ***********************
D/GKI_LINUX( 3229): acquire_my_wake_lock(), g_wake_lock_fd:91, g_wake_unlock_fd:92, wake_lock_acquired:0
,I/BtOppRfcommListener( 3229): Accept thread started.
,D/HidProfile( 1307): Bluetooth service connected
,D/BluetoothPan( 1307): BluetoothPAN Proxy object connected
,D/PanProfile( 1307): Bluetooth service connected
,D/BluetoothMap( 1307): Proxy object connected
,D/MapProfile( 1307): Bluetooth service connected
,D/BluetoothPbap( 1307): Proxy object connected
,D/PbapServerProfile( 1307): Bluetooth service connected
,D/GKI_LINUX( 3229): release_my_wake_lock(), g_wake_lock_fd:91, g_wake_unlock_fd:92, wake_lock_acquired:1
,D/Tethering(  775): interfaceAdded wlan0
,E/Tethering(  775): No numeric data
,D/Tethering(  775): sendTetherStateChangedBroadcast 1, 0, 0
,D/NtpTrustedTime(  775): forceRefresh() from cache miss
D/Tethering(  775): interfaceLinkStateChanged wlan0, false
,D/Tethering(  775): interfaceStatusChanged wlan0, false
,I/ConnectivityService(  775): defaultVal : 1, tetherEnabledInSettings : true
D/Tethering(  775): InitialState.processMessage what=4
,E/Tethering(  775): No numeric data
,D/Tethering(  775): sendTetherStateChangedBroadcast 0, 0, 0
,D/NtpTrustedTime(  775): forceRefresh Fail.
,D/Tethering(  775): interfaceAdded p2p0
,D/Tethering(  775): p2p0 is not a tetherable iface, ignoring
D/Tethering(  775): interfaceLinkStateChanged p2p0, false
,D/Tethering(  775): interfaceStatusChanged p2p0, false
I/ConnectivityService(  775): defaultVal : 1, tetherEnabledInSettings : true
V/NetworkStats(  775): performPollLocked(flags=0x1)
,I/WifiHW  (  232): wifi_change_fw_path(): fwpath = sta
,D/SoftapController(  232): Softap fwReload - Ok
,D/NtpTrustedTime(  775): forceRefresh() from cache miss
D/NtpTrustedTime(  775): forceRefresh() from cache miss
D/NtpTrustedTime(  775): forceRefresh Fail.
,D/NtpTrustedTime(  775): forceRefresh Fail.
V/NetworkStats(  775): performPollLocked() took 18ms
V/NetworkStats(  775): performPollLocked(flags=0x1)
,V/NetworkStats(  775): performPollLocked() took 14ms
D/NtpTrustedTime(  775): forceRefresh() from cache miss
D/NtpTrustedTime(  775): forceRefresh Fail.
D/CommandListener(  232): Setting iface cfg
D/CommandListener(  232): Trying to bring down wlan0
,D/WifiHW  (  775): Skip the update_ctrl_interface
,D/WifiHW  (  775): Skip the update_ctrl_interface
,E/WifiHW  (  775): supplicant_name : p2p_supplicant
,D/WifiMonitor(  775): startMonitoring(wlan0) with mConnected = false
D/STATUSBAR-NetworkController_dual( 1068): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
D/StatusBar.NetworkController_dual( 1068): mMobileLabelViews start
D/StatusBar.NetworkController_dual( 1068): mMobileLabelViews set mobileLabel[SIM_0] =No service.
D/StatusBar.NetworkController_dual( 1068): mMobileLabelViews GONE
D/StatusBar.NetworkController_dual( 1068): mMobileLabelViews2 set mobileLabel[SIM_1] =No service.
D/StatusBar.NetworkController_dual( 1068): mMobileLabelViews2 GONE
D/StatusBar.NetworkController_dual( 1068): mSingleMobileLabelViews set : simMode = 0
D/StatusBar.NetworkController_dual( 1068): mSingleMobileLabelViews set as slot1`s
,I/knox    ( 3131): MainReceiver.onReceive() : Intent { act=android.net.wifi.WIFI_STATE_CHANGED flg=0x4000010 cmp=com.sec.knox.seandroid/.receiver.MainReceiver (has extras) }
W/ContextImpl( 3131): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1857 android.content.ContextWrapper.startService:506 android.content.ContextWrapper.startService:506 com.sec.knox.seandroid.receiver.MainReceiver.onReceive:142 android.app.ActivityThread.handleReceiver:2698 
,I/knox    ( 3131): MainReceiver.onReceive() END - - - - - : Intent { act=android.net.wifi.WIFI_STATE_CHANGED flg=0x4000010 cmp=com.sec.knox.seandroid/.receiver.MainReceiver (has extras) }
D/knox    ( 3131): KNOXAgentService : onCreate()
,D/knox    ( 3131): KNOXAgentService : set alarms for deniallog and usage data upload
D/knox    ( 3131): KNOXAgentService. startJobThread() start
D/knox    ( 3131): KNOXAgentService. JobThread()
D/knox    ( 3131): KNOXAgentService. JobThread. notifyAll().
,D/knox    ( 3131): KNOXAgentService. startJobThread() wait
,D/dalvikvm(  242): WAIT_FOR_CONCURRENT_GC blocked 1ms
,I/wpa_supplicant( 4982): wpa_supplicant v2.1-devel-4.4.22014-11-04/18:06:52
D/knox    ( 3131): KNOXAgentService : onDestroy().
,D/knox    ( 3131): ModuleBase.cancelAllAlarmManageModule()
I/SELinux ( 4985): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 4985):  
I/wpa_supplicant( 4982): [wpa_supplicant_init]: use SECRIL
I/wpa_supplicant( 4982): Successfully initialized wpa_supplicant
I/wpa_supplicant( 4982): >>>>> Not GET KEY, IV <<<<<
E/wpa_supplicant( 4982): getIMSI cannot open file
,E/wpa_supplicant( 4982): Interworking config: - SIM READ ERROR
,D/dalvikvm(  242): GC_EXPLICIT freed 43K, 50% free 9506K/19008K, paused 3ms+5ms, total 36ms
,I/SELinux ( 4985): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 4985):  
I/SELinux ( 4985):  
,I/SELinux ( 4985): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 4985): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 4985): >>>>> Normal User
,E/dalvikvm( 4985): >>>>> tv.peel.smartremote [ userId:0 | appId:10163 ]
,E/SELinux ( 4985): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
,D/dalvikvm(  242): GC_EXPLICIT freed <1K, 50% free 9506K/19008K, paused 4ms+3ms, total 38ms
,D/TimaKeyStoreProvider( 4985): in addTimaSignatureService
,D/dalvikvm(  242): GC_EXPLICIT freed <1K, 50% free 9506K/19008K, paused 1ms+3ms, total 19ms
,D/TimaKeyStoreProvider( 4985): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 4985): Added TimaKesytore provider
,I/wpa_supplicant( 4982): >>>>> Not GET KEY, IV <<<<<
E/wpa_supplicant( 4982): getIMSI cannot open file
,E/wpa_supplicant( 4982): Interworking config: - SIM READ ERROR
,I/wpa_supplicant( 4982): >>>>> Not GET KEY, IV <<<<<
,I/wpa_supplicant( 4982): rfkill: Cannot open RFKILL control device
D/Tethering(  775): interfaceLinkStateChanged wlan0, false
,D/Tethering(  775): interfaceStatusChanged wlan0, false
,W/ActivityManager(  775): Permission Denial: getCurrentUser() from pid=4985, uid=10163 requires android.permission.INTERACT_ACROSS_USERS
,I/wpa_supplicant( 4982): wlan0: Setting scan request: 0 sec 100000 usec
,I/wpa_supplicant( 4982): >>>>> Not GET KEY, IV <<<<<
,I/wpa_supplicant( 4982): >>>>> Not GET KEY, IV <<<<<
,I/wpa_supplicant( 4982): rfkill: Cannot open RFKILL control device
D/Tethering(  775): interfaceLinkStateChanged p2p0, false
,D/Tethering(  775): interfaceStatusChanged p2p0, false
D/Tethering(  775): interfaceLinkStateChanged p2p0, false
,D/Tethering(  775): interfaceStatusChanged p2p0, false
,I/ActivityManager(  775): Killing 3746:com.sec.android.app.sns3/u0a36 (adj 15): empty #43
,I/wpa_supplicant( 4982): CTRL-EVENT-STATE-CHANGE id=-1 state=2 BSSID=00.00.00 SSID=
,I/wpa_supplicant( 4982): P2P: initialized channels: 81:1,2,3,4,5,6,7,8,9,10,11,12,13 115:36,40,44,48 116:36,44 117:40,48
I/wpa_supplicant( 4982): CTRL-EVENT-STATE-CHANGE id=-1 state=0 BSSID=00.00.00 SSID=
,I/wpa_supplicant( 4982): Skip scan - bUseNetwork false
,D/WifiStateMachine(  775): skipWifiStateBroadcast:false, LastBroadcastedWifiState:2
,D/WifiNative(  775): callSECApiString - ID [21]
I/wpa_supplicant( 4982): HOTSPOT20_ENABLE called
,I/wpa_supplicant( 4982): wlan0: HS20_DISABLED_COMPLETE normal
D/STATUSBAR-NetworkController_dual( 1068): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
D/SignalClusterView_dual( 1068): wifi: GONE sig=0 act=0
D/SignalClusterView_dual( 1068): mMobileDataState=0 mMobileDataState2=0
D/SignalClusterView_dual( 1068): apply() mSeparateMobileGroup=8
D/STATUSBAR-NetworkController_dual( 1068): refreshSignalCluster - setNWBoosterIndicators(false)
D/SignalClusterView_dual( 1068): wifi: GONE sig=2130837981 act=0
D/SignalClusterView_dual( 1068): mMobileDataState=0 mMobileDataState2=0
D/SignalClusterView_dual( 1068): apply() mSeparateMobileGroup=8
D/SignalClusterView_dual( 1068): wifi: GONE sig=2130837981 act=0
D/SignalClusterView_dual( 1068): mMobileDataState=0 mMobileDataState2=0
D/SignalClusterView_dual( 1068): apply() mSeparateMobileGroup=8
D/SignalClusterView_dual( 1068): wifi: GONE sig=2130837981 act=0
D/SignalClusterView_dual( 1068): mMobileDataState=0 mMobileDataState2=0
D/SignalClusterView_dual( 1068): apply() mSeparateMobileGroup=8
D/SignalClusterView_dual( 1068): wifi: GONE sig=2130837981 act=0
D/SignalClusterView_dual( 1068): mMobileDataState=0 mMobileDataState2=0
D/SignalClusterView_dual( 1068): apply() mSeparateMobileGroup=8
D/StatusBar.NetworkController_dual( 1068): mMobileLabelViews start
D/StatusBar.NetworkController_dual( 1068): mMobileLabelViews set mobileLabel[SIM_0] =No service.
D/StatusBar.NetworkController_dual( 1068): mMobileLabelViews GONE
D/StatusBar.NetworkController_dual( 1068): mMobileLabelViews2 set mobileLabel[SIM_1] =No service.
D/StatusBar.NetworkController_dual( 1068): mMobileLabelViews2 GONE
D/StatusBar.NetworkController_dual( 1068): mSingleMobileLabelViews set : simMode = 0
D/StatusBar.NetworkController_dual( 1068): mSingleMobileLabelViews set as slot1`s
,I/knox    ( 3131): MainReceiver.onReceive() : Intent { act=android.net.wifi.WIFI_STATE_CHANGED flg=0x4000010 cmp=com.sec.knox.seandroid/.receiver.MainReceiver (has extras) }
,D/WifiNative(  775): callSECApiInt - ID [65]
,W/ContextImpl( 3131): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1857 android.content.ContextWrapper.startService:506 android.content.ContextWrapper.startService:506 com.sec.knox.seandroid.receiver.MainReceiver.onReceive:142 android.app.ActivityThread.handleReceiver:2698 
I/knox    ( 3131): MainReceiver.onReceive() END - - - - - : Intent { act=android.net.wifi.WIFI_STATE_CHANGED flg=0x4000010 cmp=com.sec.knox.seandroid/.receiver.MainReceiver (has extras) }
D/knox    ( 3131): GSLBThreadManager.NetworkStateChanged : NETWORK_STATE_CHAGED. Upload Call Log Data
D/knox    ( 3131): KNOXAgentService : onCreate()
D/knox    ( 3131): KNOXAgentService : set alarms for deniallog and usage data upload
E/WifiConfigStore(  775): Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
D/knox    ( 3131): KNOXAgentService. startJobThread() start
D/knox    ( 3131): KNOXAgentService. JobThread()
D/knox    ( 3131): KNOXAgentService. JobThread. notifyAll().
D/knox    ( 3131): KNOXAgentService. startJobThread() wait
D/knox    ( 3131): KNOXAgentService : onDestroy().
D/knox    ( 3131): ModuleBase.cancelAllAlarmManageModule()
D/WifiNative(  775): callSECApiBoolean - ID [13]
I/wpa_supplicant( 4982): USE_NETWORK : USE_NETWORK ON
I/wpa_supplicant( 4982): reset timer : RESET_TIMER 0
I/wpa_supplicant( 4982): wlan0: Setting scan request: 0 sec 0 usec
I/wpa_supplicant( 4982): CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00.00.00 SSID=
I/wpa_supplicant( 4982): First Scan Start
I/wpa_supplicant( 4982): Scan requested (ret=0) - scan timeout 30 seconds
E/WifiStateMachine(  775): Set the Nv default ccode
W/Settings( 3076): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiP2pService(  775): P2pDisabledState{ what=131203 }
D/WifiStateMachine(  775): skipWifiStateBroadcast:false, LastBroadcastedWifiState:3
E/WifiStateMachine(  775): HS20_DISABLED_COMPLETEnormal
,W/ContextImpl(  775): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.android.server.enterprise.wifi.WifiPolicy.asyncEnableNetwork:3065 com.android.server.enterprise.wifi.WifiPolicy.edmUpdateConfiguredNetworks:2530 com.android.server.enterprise.wifi.WifiPolicy$2$2.run:3022 java.lang.Thread.run:841 
,I/wpa_supplicant( 4982): P2P: updated channels: 81:1,2,3,4,5,6,7,8,9,10,11,12,13 115:36,40,44,48 116:36,44 117:40,48
,D/CommandListener(  232): Setting iface cfg
,D/CommandListener(  232): Trying to bring up p2p0
,D/WifiMonitor(  775): startMonitoring(p2p0) with mConnected = true
D/WifiP2pService(  775): P2pEnablingState
,D/QuickConnect[1.1][2] ( 3199): SconnectManager.INetworkStateListener, onEnabled - mNetworkState : 4
,D/QuickConnect[1.1][2] ( 3199): P2pHelper.onReceive - ACTION_WIFI_DISPLAY_STATUS_CHANGED :0
D/WifiP2pService(  775): P2pEnablingState{ what=147457 }
D/WifiP2pService(  775): P2p socket connection successful
D/WifiP2pService(  775): P2pEnabledState
D/WifiP2pService(  775): sending p2p connection changed broadcast: IDLE
D/WifiDisplayController(  775): Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=true
D/WifiDisplayController(  775): updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
D/WifiDisplayController(  775): disconnect
D/WifiDisplayController(  775): updateConnection
D/WifiDisplayController(  775): updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
D/WifiDisplayAdapter(  775): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
D/WifiDisplayAdapter(  775): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,D/QuickConnect[1.1][2] ( 3199): P2pHelper.onReceive - P2P_CONNECTION_CHANGED : 
,D/NearbySettings( 1307): MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
D/WifiDisplayController(  775): Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=NetworkInfo: type: WIFI_P2P[], state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,V/NearbySettings( 1307): DMSUtil.isNetworkConnected - flag-null, state-null
,D/QuickConnect[1.1][2] ( 3199): SconnectManager.INetworkStateListener, onDisconnected - networkType : 4
,I/NearbySettings( 1307): DMSUtil.isNetworkConnected - WIFI: IDLE
I/NearbySettings( 1307): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1307): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
,I/NearbySettings( 1307): MountReceiver.onReceive - Set preference state off
,V/NearbySettings( 1307): MountReceiver.mPrefHandler - 7002
D/WifiP2pService(  775): DeviceAddress: 3a:06:dd
,D/FileShare-Server( 4253): ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,E/WifiStateMachine(  775): BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
D/WifiDisplayController(  775): Received WIFI_P2P_THIS_DEVICE_CHANGED_ACTION: mThisDevice= Device: Galaxy S5-2
D/WifiDisplayController(  775):  deviceAddress: 3a:94:96:b5:06:dd
D/WifiDisplayController(  775):  primary type: 10-0050F204-5
D/WifiDisplayController(  775):  secondary type: null
D/WifiDisplayController(  775):  wps: 0
D/WifiDisplayController(  775):  grpcapab: 0
D/WifiDisplayController(  775):  devcapab: 0
D/WifiDisplayController(  775):  status: 3
D/WifiDisplayController(  775):  wfdInfo: null
D/WifiDisplayController(  775):  groupownerAddress: null
D/WifiDisplayController(  775):  GOdeviceName: null
D/WifiDisplayController(  775):  interfaceAddress: 
D/WifiDisplayController(  775):  SConnectInfo : null
W/WifiP2pStateTracker(  775): WifiP2pStateReceiver : android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,D/FileShare-Server( 4253): ServerBroadcastReceiver.onReceive - netInfo.getDetailedState() IDLE
,D/QuickConnect[1.1][2] ( 3199): P2pHelper.requestGroupInfo  - onGroupInfoAvailable- null
D/WifiP2pService(  775): sending p2p persistent groups changed broadcast
D/WifiP2pService(  775): InactiveState
D/WifiP2pService(  775): InactiveState{ what=139287 }
D/WifiP2pService(  775): P2pEnabledState{ what=139287 }
D/WifiP2pService(  775): DefaultState{ what=139287 }
,E/SMD     (  235): DCD ON
,D/Tethering(  775): interfaceLinkStateChanged p2p0, false
,D/Tethering(  775): interfaceStatusChanged p2p0, false
,I/wpa_supplicant( 4982): P2P: updated channels: 81:1,2,3,4,5,6,7,8,9,10,11,12,13 115:36,40,44,48 116:36,44 117:40,48
,I/wpa_supplicant( 4982): P2P: updated channels: 81:1,2,3,4,5,6,7,8,9,10,11,12,13 115:36,40,44,48 116:36,44 117:40,48
,D/AmoledAdjustTimer(  775): prevTemp = 285, currTemp = 286, prevStep = 4, currStep = 4
,I/wpa_supplicant( 4982): nl80211: Received scan results (11 BSSes)
,I/wpa_supplicant( 4982): wlan0: Setting scan request: 8 sec 0 usec
I/wpa_supplicant( 4982): Trying to associate with SSID '4E47373030'
I/wpa_supplicant( 4982): Trying to associate with  'G700'
,I/wpa_supplicant( 4982): CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00.00.00 SSID=
,E/wpa_supplicant( 4982): Cmd 35609 not handled
,D/Tethering(  775): interfaceLinkStateChanged wlan0, false
,D/Tethering(  775): interfaceStatusChanged wlan0, false
,E/WifiStateMachine(  775): Error! unhandled message{ when=-2ms what=135188 target=com.android.internal.util.StateMachine$SmHandler }
,E/wpa_supplicant( 4982): Cmd 35605 not handled
I/wpa_supplicant( 4982): CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00.00.00 SSID=4E47373030
,I/wpa_supplicant( 4982): Associated with C0.AA.48
,I/wpa_supplicant( 4982): CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=C0.AA.48 SSID=4E47373030
E/wpa_supplicant( 4982): Cmd 35847 not handled
E/wpa_supplicant( 4982): Cmd 35848 not handled
,E/wpa_supplicant( 4982): Cmd 35605 not handled
,D/Tethering(  775): interfaceLinkStateChanged wlan0, false
,D/Tethering(  775): interfaceStatusChanged wlan0, false
D/Tethering(  775): interfaceLinkStateChanged wlan0, false
,D/Tethering(  775): interfaceStatusChanged wlan0, false
D/Tethering(  775): interfaceLinkStateChanged wlan0, false
,D/Tethering(  775): interfaceStatusChanged wlan0, false
,I/wpa_supplicant( 4982): CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=C0.AA.48 SSID=4E47373030
I/wpa_supplicant( 4982): WPA: Key negotiation completed with C0.AA.48 [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 4982): CTRL-EVENT-CONNECTED - Connection to C0.AA.48 completed (auth) [id=0 id_str=]
,I/wpa_supplicant( 4982): CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=C0.AA.48 SSID=4E47373030
,D/WifiNative(  775): callSECApiVoid - ID [50]
,D/Tethering(  775): interfaceLinkStateChanged wlan0, true
,D/Tethering(  775): interfaceStatusChanged wlan0, true
,E/Tethering(  775): No numeric data
,D/Tethering(  775): sendTetherStateChangedBroadcast 1, 0, 0
,I/ConnectivityService(  775): defaultVal : 1, tetherEnabledInSettings : true
D/NtpTrustedTime(  775): forceRefresh() from cache miss
,D/NtpTrustedTime(  775): forceRefresh Fail.
V/NetworkStats(  775): performPollLocked(flags=0x1)
,D/Tethering(  775): interfaceLinkStateChanged wlan0, true
,D/Tethering(  775): interfaceStatusChanged wlan0, true
D/STATUSBAR-NetworkController_dual( 1068): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
D/StatusBar.NetworkController_dual( 1068): mMobileLabelViews start
D/StatusBar.NetworkController_dual( 1068): mMobileLabelViews set mobileLabel[SIM_0] =No service.
D/StatusBar.NetworkController_dual( 1068): mMobileLabelViews GONE
D/StatusBar.NetworkController_dual( 1068): mMobileLabelViews2 set mobileLabel[SIM_1] =No service.
D/StatusBar.NetworkController_dual( 1068): mMobileLabelViews2 GONE
D/StatusBar.NetworkController_dual( 1068): mSingleMobileLabelViews set : simMode = 0
D/StatusBar.NetworkController_dual( 1068): mSingleMobileLabelViews set as slot1`s
,D/Tethering(  775): interfaceLinkStateChanged wlan0, true
D/Tethering(  775): interfaceStatusChanged wlan0, true
D/Tethering(  775): interfaceLinkStateChanged wlan0, true
D/Tethering(  775): interfaceStatusChanged wlan0, true
D/Tethering(  775): interfaceLinkStateChanged wlan0, true
,D/Tethering(  775): interfaceStatusChanged wlan0, true
V/NetworkStats(  775): performPollLocked() took 48ms
,D/NtpTrustedTime(  775): forceRefresh() from cache miss
,D/NtpTrustedTime(  775): forceRefresh Fail.
,I/SELinux ( 5019): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5019):  
,D/STATUSBAR-NetworkController_dual( 1068): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
,D/StatusBar.NetworkController_dual( 1068): mMobileLabelViews start
D/StatusBar.NetworkController_dual( 1068): mMobileLabelViews set mobileLabel[SIM_0] =No service.
D/StatusBar.NetworkController_dual( 1068): mMobileLabelViews GONE
D/StatusBar.NetworkController_dual( 1068): mMobileLabelViews2 set mobileLabel[SIM_1] =No service.
,D/StatusBar.NetworkController_dual( 1068): mMobileLabelViews2 GONE
D/StatusBar.NetworkController_dual( 1068): mSingleMobileLabelViews set : simMode = 0
,D/StatusBar.NetworkController_dual( 1068): mSingleMobileLabelViews set as slot1`s
,D/STATUSBAR-NetworkController_dual( 1068): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
,D/StatusBar.NetworkController_dual( 1068): mMobileLabelViews start
D/StatusBar.NetworkController_dual( 1068): mMobileLabelViews set mobileLabel[SIM_0] =No service.
D/StatusBar.NetworkController_dual( 1068): mMobileLabelViews GONE
D/StatusBar.NetworkController_dual( 1068): mMobileLabelViews2 set mobileLabel[SIM_1] =No service.
D/StatusBar.NetworkController_dual( 1068): mMobileLabelViews2 GONE
D/StatusBar.NetworkController_dual( 1068): mSingleMobileLabelViews set : simMode = 0
,D/StatusBar.NetworkController_dual( 1068): mSingleMobileLabelViews set as slot1`s
,D/WifiP2pService(  775): InactiveState{ what=143375 }
,D/WifiP2pService(  775): P2pEnabledState{ what=143375 }
,I/SELinux ( 5019): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5019):  
I/SELinux ( 5019):  
,I/SELinux ( 5019): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5019): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 5019): >>>>> Normal User
,E/dalvikvm( 5019): >>>>> com.vlingo.midas [ userId:0 | appId:10033 ]
,E/SELinux ( 5019): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
,D/TimaKeyStoreProvider( 5019): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5019): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5019): Added TimaKesytore provider
,I/System.out( 5019): Inside WakeupProvider
,I/System.out( 5019): Inside onCreate() of WakeupTriggerProvide
,I/VlingoApplication( 5019): VlingoApplication appVersion ='11.4.0.3.34005', ro.csc.sales_code=XEO
,D/VlingoApplication( 5019): Couldn't create com.nuance.nuancedebugutilpackage context for host settings utility
,D/VlingoApplication( 5019): Couldn't create com.vlingo.midas.lmttutilitypackage context for host settings utility
,I/dhcpcd  ( 5040): if(wlan0) info get Success. (MAC : C0.AA.48)
,I/dhcpcd  ( 5040): bssid match
,D/NearbySettings( 1307): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 1307): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 1307): DMSUtil.isNetworkConnected - WIFI: OBTAINING_IPADDR
I/NearbySettings( 1307): DMSUtil.isNetworkConnected - P2P: IDLE
,I/NearbySettings( 1307): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
,I/NearbySettings( 1307): MountReceiver.onReceive - Set preference state off
,V/NearbySettings( 1307): MountReceiver.mPrefHandler - 7002
,D/DialogFlow( 5019): initQueue()
I/ActivityManager(  775): Killing 3819:com.sec.spp.push:RemoteNotiProcess/u0a38 (adj 15): empty #43
,D/WifiP2pService(  775): InactiveState{ what=143375 }
,D/WifiP2pService(  775): P2pEnabledState{ what=143375 }
,D/WifiStateMachine(  775): VerifyingLinkState enter
D/STATUSBAR-NetworkController_dual( 1068): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
D/StatusBar.NetworkController_dual( 1068): mMobileLabelViews start
D/StatusBar.NetworkController_dual( 1068): mMobileLabelViews set mobileLabel[SIM_0] =No service.
D/StatusBar.NetworkController_dual( 1068): mMobileLabelViews GONE
D/StatusBar.NetworkController_dual( 1068): mMobileLabelViews2 set mobileLabel[SIM_1] =No service.
D/StatusBar.NetworkController_dual( 1068): mMobileLabelViews2 GONE
D/StatusBar.NetworkController_dual( 1068): mSingleMobileLabelViews set : simMode = 0
D/StatusBar.NetworkController_dual( 1068): mSingleMobileLabelViews set as slot1`s
D/STATUSBAR-NetworkController_dual( 1068): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
,D/StatusBar.NetworkController_dual( 1068): mMobileLabelViews start
,D/StatusBar.NetworkController_dual( 1068): mMobileLabelViews set mobileLabel[SIM_0] =No service.
D/StatusBar.NetworkController_dual( 1068): mMobileLabelViews GONE
D/StatusBar.NetworkController_dual( 1068): mMobileLabelViews2 set mobileLabel[SIM_1] =No service.
,D/StatusBar.NetworkController_dual( 1068): mMobileLabelViews2 GONE
,D/StatusBar.NetworkController_dual( 1068): mSingleMobileLabelViews set : simMode = 0
,D/WifiStateMachine(  775): VerifyingLinkState GOOD_LINK_DETECTED: transition to captive portal check
,D/WifiStateMachine(  775): CaptivePortalCheckState enter
,I/WifiTrafficPoller(  775): evaluateTrafficStatsPolling
D/StatusBar.NetworkController_dual( 1068): mSingleMobileLabelViews set as slot1`s
,D/WifiStateMachine(  775): CaptivePortalCheckState CMD_CAPTIVE_CHECK_COMPLETE
D/ConnectivityService(  775): Captive portal check NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService(  775): handleCaptivePortalTrackerCheck: call captivePortalCheckComplete ni=NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/STATUSBAR-NetworkController_dual( 1068): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
D/StatusBar.NetworkController_dual( 1068): mMobileLabelViews start
D/StatusBar.NetworkController_dual( 1068): mMobileLabelViews set mobileLabel[SIM_0] =No service.
D/StatusBar.NetworkController_dual( 1068): mMobileLabelViews GONE
D/StatusBar.NetworkController_dual( 1068): mMobileLabelViews2 set mobileLabel[SIM_1] =No service.
D/StatusBar.NetworkController_dual( 1068): mMobileLabelViews2 GONE
D/StatusBar.NetworkController_dual( 1068): mSingleMobileLabelViews set : simMode = 0
D/StatusBar.NetworkController_dual( 1068): mSingleMobileLabelViews set as slot1`s
,I/WifiTrafficPoller(  775): evaluateTrafficStatsPolling
I/WifiTrafficPoller(  775): mBoosterFLAG : 2
,I/WifiTrafficPoller(  775): current booster mode : BTCoexMode
D/ConnectivityService(  775): ConnectivityChange for WIFI: CONNECTED/CONNECTED
E/ConnectivityService(  775): net.tcp.usercfg.wifi not found in system properties. Using defaults
E/ConnectivityService(  775): net.tcp.delack.wifi not found in system properties. Using defaults
D/STATUSBAR-NetworkController_dual( 1068): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
D/SignalClusterView_dual( 1068): wifi: GONE sig=2130837981 act=0
D/SignalClusterView_dual( 1068): mMobileDataState=0 mMobileDataState2=0
D/SignalClusterView_dual( 1068): apply() mSeparateMobileGroup=8
D/STATUSBAR-NetworkController_dual( 1068): refreshSignalCluster - setNWBoosterIndicators(false)
D/SignalClusterView_dual( 1068): wifi: VISIBLE sig=2130837979 act=2130837939
D/SignalClusterView_dual( 1068): mMobileDataState=0 mMobileDataState2=0
D/SignalClusterView_dual( 1068): apply() mSeparateMobileGroup=8
D/SignalClusterView_dual( 1068): wifi: VISIBLE sig=2130837979 act=2130837939
D/SignalClusterView_dual( 1068): mMobileDataState=0 mMobileDataState2=0
D/SignalClusterView_dual( 1068): apply() mSeparateMobileGroup=8
D/SignalClusterView_dual( 1068): wifi: VISIBLE sig=2130837979 act=2130837939
D/SignalClusterView_dual( 1068): mMobileDataState=0 mMobileDataState2=0
D/SignalClusterView_dual( 1068): apply() mSeparateMobileGroup=8
D/SignalClusterView_dual( 1068): wifi: VISIBLE sig=2130837979 act=2130837939
D/SignalClusterView_dual( 1068): mMobileDataState=0 mMobileDataState2=0
D/SignalClusterView_dual( 1068): apply() mSeparateMobileGroup=8
D/StatusBar.NetworkController_dual( 1068): mMobileLabelViews start
D/StatusBar.NetworkController_dual( 1068): mMobileLabelViews set mobileLabel[SIM_0] =
D/StatusBar.NetworkController_dual( 1068): mMobileLabelViews GONE
D/StatusBar.NetworkController_dual( 1068): mMobileLabelViews2 set mobileLabel[SIM_1] =
D/StatusBar.NetworkController_dual( 1068): mMobileLabelViews2 GONE
D/StatusBar.NetworkController_dual( 1068): mSingleMobileLabelViews set : simMode = 0
D/StatusBar.NetworkController_dual( 1068): mSingleMobileLabelViews set as slot1`s
,D/NearbySettings( 1307): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,I/NearbySettings( 1307): MountReceiver.onReceive - Keep current state
D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,D/ConnectivityService(  775): handleConnectivityChange: setting default proxy info 
,V/RouteController(  232): /system/bin/ip -4 route replace default via 192.168.1.1 dev wlan0 scope global table 2 2>&1
,V/RouteController(  232): /system/bin/ip -4 rule del table 2 2>&1
,D/NearbySettings( 1307): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 1307): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 1307): DMSUtil.isNetworkConnected - WIFI: CONNECTED
I/NearbySettings( 1307): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1307): DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
,I/NearbySettings( 1307): MountReceiver.onReceive - Keep current state
,V/RouteController(  232): RTNETLINK answers: No such file or directory
,V/RouteController(  232): /system/bin/ip -4 rule add from 192.168.1.143 lookup 2 prio 150 2>&1
,V/RouteController(  232): /system/bin/ip route flush cached 2>&1
,D/Toast   ( 1307):  checkMirrorLinkEnabled returns : false
,D/Toast   ( 1307): showing allowed
,V/RouteController(  232): /system/bin/ip route del 192.168.1.0/24 table 2 2>&1
,D/NearbySettings( 1307): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,I/NearbySettings( 1307): MountReceiver.onReceive - Keep current state
,V/RouteController(  232): RTNETLINK answers: No such process
,V/RouteController(  232): /system/bin/ip route add 192.168.1.0/24 dev wlan0 table 2 metric 0 2>&1
,I/SurfaceFlinger(  241): id=19 createSurf (1x1),1 flag=4, Uoast
,D/KeyguardUpdateMonitor( 1068): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1068): handleKeyguardVisibilityChanged(1)
,V/RouteController(  232): /system/bin/ip route flush cached 2>&1
,D/KeyguardUpdateMonitor( 1068): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1068): handleKeyguardVisibilityChanged(1)
,D/PowerManagerService(  775): [api] acquire WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=775
,D/NtpTrustedTime(  775): forceRefresh() from cache miss
V/NetworkStats(  775): updateIfacesLocked()
V/NetworkStats(  775): performPollLocked(flags=0x1)
,V/NetworkStats(  775): performPollLocked() took 23ms
,D/KeyguardUpdateMonitor( 1068): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1068): handleKeyguardVisibilityChanged(1)
,D/KeyguardUpdateMonitor( 1068): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1068): handleKeyguardVisibilityChanged(1)
,D/NtpTrustedTime(  775): requestTime Success from server:2.android.pool.ntp.org mCachedNtpTime : 1450100367325 mCachedNtpElapsedRealtime : 133164 mCachedNtpCertainty : 8
,D/NtpTrustedTime(  775): currentTimeMillis() cache hit
,D/NtpTrustedTime(  775): currentTimeMillis() cache hit
D/NtpTrustedTime(  775): currentTimeMillis() cache hit
,D/NtpTrustedTime(  775): currentTimeMillis() cache hit
D/NtpTrustedTime(  775): currentTimeMillis() cache hit
,D/NtpTrustedTime(  775): currentTimeMillis() cache hit
V/NetworkStats(  775): advisePersistThreshold() given 9223372036854775, clamped to 2097152
,D/Tethering(  775): Tethering got CONNECTIVITY_ACTION
,D/Tethering(  775): MasterInitialState.processMessage what=3
,D/SSRMv2:SIOP(  775): SIOP:: AP = 320, Delta = 10
D/CaptivePortalTracker(  775): NoActiveNetworkState{ when=0 what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
D/NtpTrustedTime(  775): currentTimeMillis() cache hit
D/        (  775): Setting time of day to sec=1450100367
D/        (  775): Trying to open a file
D/        (  775): File Open Success
D/        (  775): File Close Success
,I/        (  775): DRM_TIME_PATH CHMOD 660 for resetState done 
D/STATUSBAR-NetworkController_dual( 1068): onReceive() - CONNECTIVITY_ACTION, INET_CONDITION_ACTION
D/StatusBar.NetworkController_dual( 1068): mMobileLabelViews start
D/StatusBar.NetworkController_dual( 1068): mMobileLabelViews set mobileLabel[SIM_0] =
D/StatusBar.NetworkController_dual( 1068): mMobileLabelViews GONE
D/StatusBar.NetworkController_dual( 1068): mMobileLabelViews2 set mobileLabel[SIM_1] =
D/StatusBar.NetworkController_dual( 1068): mMobileLabelViews2 GONE
D/StatusBar.NetworkController_dual( 1068): mSingleMobileLabelViews set : simMode = 0
D/StatusBar.NetworkController_dual( 1068): mSingleMobileLabelViews set as slot1`s
,W/        (  775): Unable to set rtc to 1450100367: Invalid argument
,V/AlarmManager(  775): waitForAlarm result :65536
D/LocSvc_java(  775): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/LocSvc_java(  775): getAGpsConnectionInfo connType - 4
D/LocSvc_java(  775): ignore wifi update if we are not in OPENING or CLOSING
,D/accuweather( 1454): [KK AccuPhone]>>> SWW:64 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.TIME_SET
,D/KeyguardUpdateMonitor( 1068): handleTimeUpdate
D/StatusBar-DoNotDistrub( 1068): Received intent with android.intent.action.TIME_SET action
D/StatusBar-DoNotDistrub( 1068): Not data shared android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
,W/Settings(  775): Setting auto_time has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/SEC_DRM_PLUGIN_Playready(  243): PlayreadyPlugIn::onAcquireDrmInfo : case TYPE_UPDATE_SECURE_CLOCK after: 1450100367 after conversion: 1450100367
,W/SEC_DRM_PLUGIN_Playready(  243): PlayreadyPlugIn::onAcquireDrmInfo : case TYPE_UPDATE_SECURE_CLOCK before: 1450100367 after conversion: 1450100367
,I/AudioService(  775): getStreamVolume 5 index 110
D/StatusBar-DoNotDistrub( 1068): sendBroadcast android.intent.action.DORMANT_MODE_OFF
D/StatusBar-DoNotDistrub( 1068): The STREAM NOTIFICATION volume is 0
D/STATUSBAR-StatusBarManagerService(  775): manageDisableList what=0x0 pkg=com.android.systemui
,D/STATUSBAR-NotificationService(  775): received android.intent.action.DORMANT_MODE_OFF
,D/LightsService(  775): [api] [SvcLED] turnOff:: id = 4 (uid: 1000 pid: 775) 
,I/SensorManagerA(  775): getReportingMode :: sensor.mType = 5
,D/Sensors (  775): LightSensor setDelay = 200000000
D/Sensors (  775): LightSensor setSensorDelay = 200000000
D/Sensors (  775): Light sensor flush: not enabled 0
,D/Sensors (  775): LightSensor enable = 1
,D/Sensors (  775): LightSensor enableSensor = 1
,D/SensorManager(  775): registerListener :: 16, CM36686 Light Sensor, 200000, 0,  
D/LightsService(  775): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x40 -> 0x40 | SvcLED(id=4) set Off
V/AlarmManager(  775): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
V/AlarmManager(  775): waitForAlarm result :4
I/PCWCLIENTTRACE_PushUtil( 4577): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 4577): sales region : global
I/PCWCLIENTTRACE_PushUtil( 4577): getPushTypeList : [SPP, GCM]
,I/PCWCLIENTTRACE_SYSTEMReceiver( 4577): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,I/NetworkMonitor( 3836): type=WIFI subType= reason=null isConnected=true
,D/accuweather( 1454): [KK AccuPhone]>>> SWW:64 [0:0] action : androidintentactionTIME_SET
,D/accuweather( 1454): [KK AccuPhone]>>> SWW:452 [0:0] doChangeDayOrNight : 1
,D/accuweather( 1454): [KK AccuPhone]>>> SWW:338 [0:0] getWeatherRenderer : 1
D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,I/SELinux ( 5116): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5116):  
,D/BatteryService(  775): level:100, scale:100, status:5, health:2, present:true, voltage: 4366, temperature: 289, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:38, charge type:1, power sharing:false
D/BatteryService(  775): stay LED for fully charged
,D/BatteryService(  775): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
D/UiModeManager(  775): mCoverManager.getCoverState() : true
,V/HeadsetService( 3229): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3229): Disconnected process message: 10
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
I/SELinux ( 5116): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5116):  
I/SELinux ( 5116):  
I/SELinux ( 5116): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 5116): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 5116): >>>>> Normal User
E/dalvikvm( 5116): >>>>> com.sec.android.cloudagent [ userId:0 | appId:10002 ]
E/SELinux ( 5116): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
D/TimaKeyStoreProvider( 5116): in addTimaSignatureService
D/TimaKeyStoreProvider( 5116): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 5116): Added TimaKesytore provider
,D/Sensors (  775): LightSensor enable = 0
,D/Sensors (  775): LightSensor enableSensor = 0
,D/SensorManager(  775): unregisterListener ::   
D/LightsService(  775): [SvcLED]  onSensorChanged::light value = 16
,D/LightsService(  775): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
I/SELinux ( 5136): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5136):  
,I/SELinux ( 5136): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5136):  
I/SELinux ( 5136):  
,I/SELinux ( 5136): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 5136): [DEBUG] seapp_context_lookup: seinfoCategory = chrome
E/dalvikvm( 5136): >>>>> Normal User
,E/dalvikvm( 5136): >>>>> com.android.chrome [ userId:0 | appId:10081 ]
,E/SELinux ( 5136): [DEBUG] seapp_context_lookup: seinfoCategory = chrome
,W/dalvikvm( 1219): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 1219): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,D/TimaKeyStoreProvider( 5136): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5136): Cannot add TimaSignature Service, License check Failed
,W/dalvikvm( 1219): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,D/ActivityThread( 5136): Added TimaKesytore provider
,I/dalvikvm( 1219): Could not find method android.net.Network.openConnection, referenced from method com.google.android.gms.http.g.a
W/dalvikvm( 1219): VFY: unable to resolve virtual method 1007: Landroid/net/Network;.openConnection (Ljava/net/URL;)Ljava/net/URLConnection;
D/dalvikvm( 1219): VFY: replacing opcode 0x6e at 0x00bb
I/dalvikvm( 1804): Could not find method android.os.PowerManager.isInteractive, referenced from method com.google.android.gms.common.util.y.a
W/dalvikvm( 1804): VFY: unable to resolve virtual method 1378: Landroid/os/PowerManager;.isInteractive ()Z
,D/dalvikvm( 1804): VFY: replacing opcode 0x6e at 0x003d
,I/GoogleURLConnFactory( 1219): Using platform SSLCertificateSocketFactory
,E/SMD     (  235): DCD ON
W/ActivityManager(  775): Permission Denial: getCurrentUser() from pid=5116, uid=10002 requires android.permission.INTERACT_ACROSS_USERS
,D/dalvikvm(  775): GC_EXPLICIT freed 2520K, 58% free 23499K/55124K, paused 7ms+14ms, total 145ms
E/ActivityThread( 1804): Failed to find provider info for com.android.contacts.metadata
,W/ActivityManager(  775): Permission Denial: getCurrentUser() from pid=5136, uid=10081 requires android.permission.INTERACT_ACROSS_USERS
,D/SyncManager(  775): failed sync operation 
,D/SyncManager(  775): not retrying sync operation because the error is a hard error: 
,I/PhenotypeConfigurator( 1219): Scheduling Phenotype every 14400 seconds, with flex of 1800 seconds
,W/InstanceID/Rpc( 1219): Found 10011
,D/DelayedSyncController( 5136): Delaying sync.
,I/SELinux ( 5163): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5163):  
,I/jxcore-log( 4745): BLE advertisement not supported: Build version is 19
I/jxcore-log( 4745): 
,I/SELinux ( 5163): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5163):  
I/SELinux ( 5163):  
I/SELinux ( 5163): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5163): [DEBUG] seapp_context_lookup: seinfoCategory = release
E/dalvikvm( 5163): >>>>> Normal User
,E/dalvikvm( 5163): >>>>> com.sec.android.fotaclient [ userId:0 | appId:10010 ]
,E/SELinux ( 5163): [DEBUG] seapp_context_lookup: seinfoCategory = release
,D/PicasaService( 3923): start picasa sync
,D/PicasaService( 3923): end picasa sync
,D/TimaKeyStoreProvider( 5163): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5163): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5163): Added TimaKesytore provider
,I/HarmonyEASService(  775): Updating for all 1
,D/DelayedSyncController( 5136): Delaying sync.
,W/ActivityManager(  775): Permission Denial: getCurrentUser() from pid=5163, uid=10010 requires android.permission.INTERACT_ACROSS_USERS
,I/dalvikvm( 1219): Could not find method android.os.PowerManager.isInteractive, referenced from method com.google.android.gms.common.util.y.a
W/dalvikvm( 1219): VFY: unable to resolve virtual method 1378: Landroid/os/PowerManager;.isInteractive ()Z
,D/dalvikvm( 1219): VFY: replacing opcode 0x6e at 0x003d
,I/ActivityManager(  775): Killing 3799:com.sec.spp.push:RemoteDlcProcess/u0a38 (adj 15): empty #43
,I/PhenotypeConfigurator( 1219): Scheduling Phenotype for one-off execution 4266 seconds from now (1450100368735)
,I/System.out( 1219): Thread-107(HTTPLog):isShipBuild true
,I/System.out( 1219): Thread-107(HTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,D/GetConfigurationSnapshotOperation( 1219): no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,I/ActivityManager(  775): Killing 4039:com.sec.android.app.videoplayer/u0a52 (adj 15): empty #43
,I/SELinux ( 5187): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5187):  
,I/PhenotypeFlagCommitter( 1219): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,I/GoogleURLConnFactory( 1219): Using platform SSLCertificateSocketFactory
,I/SELinux ( 5187): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5187):  
I/SELinux ( 5187):  
,I/SELinux ( 5187): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5187): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 5187): >>>>> Normal User
,E/dalvikvm( 5187): >>>>> com.samsung.klmsagent [ userId:0 | appId:10018 ]
,E/SELinux ( 5187): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,I/Scheduler( 1219): Use legacy PeriodicScheduler
,D/TimaKeyStoreProvider( 5187): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5187): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5187): Added TimaKesytore provider
,W/ContextImpl(  775): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,W/ActivityManager(  775): Permission Denial: getCurrentUser() from pid=5187, uid=10018 requires android.permission.INTERACT_ACROSS_USERS
,D/KLMS-2.3.201 : ( 5187): KLMSValidator() : checkQATesting()
,D/LocationManagerService(  775): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,W/DriveInitializer( 1804): Awaiting to be initialized
,W/DriveInitializer( 1804): Background init thread started
,I/KLMS-2.3.201 : ( 5187): MainReciver() : EventNotificationReciver- method called: AppActivityListner onReceive for Intent Action : android.net.conn.CONNECTIVITY_CHANGE , timestamp: 1450100368987
,I/KLMS-2.3.201 : ( 5187): KLMSUtility() : isNetworkAvailable() - WIFI : true| MOBILE : false
,E/cutils  (  222): Failed to mkdirat(/storage/extSdCard/Android): Read-only file system
,W/ContextImpl( 1804): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.gms/files
W/Vold    (  222): Returning OperationFailed - no handler for errno 30
,I/ActivityManager(  775): Killing 4058:com.sec.android.app.voicenote/1000 (adj 15): empty #43
,D/dalvikvm( 1323): GC_EXPLICIT freed 518K, 44% free 10757K/19008K, paused 4ms+5ms, total 43ms
,I/SELinux ( 5201): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5201):  
,I/LocationTagReadyService( 2402): onStartCommand : Action = com.samsung.android.app.galaxyfinder.tag.start_location_convert
D/GalaxyFinderApplication( 2402): [Slink platform] The state of Slink geocode service is true
D/GalaxyFinderApplication( 2402): [Slink platform] The state of Slink geocode service is true
,D/GalaxyFinderApplication( 2402): [Slink platform] The state of Slink geocode service is true
,I/SELinux ( 5208): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5208):  
I/SELinux ( 5201): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5201):  
I/SELinux ( 5201):  
,I/SELinux ( 5201): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5201): [DEBUG] seapp_context_lookup: seinfoCategory = release
E/dalvikvm( 5201): >>>>> Normal User
,E/dalvikvm( 5201): >>>>> com.sec.android.soagent [ userId:0 | appId:10037 ]
,E/SELinux ( 5201): [DEBUG] seapp_context_lookup: seinfoCategory = release
,I/GallerySearchProvider( 3923): query content://com.sec.android.gallery3d.provider.GallerySearchProvider/search_suggest_tag_query
,D/TimaKeyStoreProvider( 5201): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5201): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5201): Added TimaKesytore provider
,I/SELinux ( 5208): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5208):  
I/SELinux ( 5208):  
,I/SELinux ( 5208): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5208): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 5208): >>>>> Normal User
,E/dalvikvm( 5208): >>>>> com.sec.android.app.videoplayer [ userId:0 | appId:10052 ]
,E/SELinux ( 5208): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 5208): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5208): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5208): Added TimaKesytore provider
,I/SELinux ( 5234): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5234):  
,D/STATUSBAR-NetworkController_dual( 1068): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
,D/StatusBar.NetworkController_dual( 1068): mMobileLabelViews start
D/StatusBar.NetworkController_dual( 1068): mMobileLabelViews set mobileLabel[SIM_0] =
D/StatusBar.NetworkController_dual( 1068): mMobileLabelViews GONE
D/StatusBar.NetworkController_dual( 1068): mMobileLabelViews2 set mobileLabel[SIM_1] =
D/StatusBar.NetworkController_dual( 1068): mMobileLabelViews2 GONE
,D/StatusBar.NetworkController_dual( 1068): mSingleMobileLabelViews set : simMode = 0
,D/StatusBar.NetworkController_dual( 1068): mSingleMobileLabelViews set as slot1`s
,I/SELinux ( 5234): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5234):  
I/SELinux ( 5234):  
I/SELinux ( 5234): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 5234): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 5234): >>>>> Normal User
,E/dalvikvm( 5234): >>>>> com.sec.android.app.voicenote [ userId:0 | appId:1000 ]
,W/ActivityManager(  775): Permission Denial: getCurrentUser() from pid=5201, uid=10037 requires android.permission.INTERACT_ACROSS_USERS
E/SELinux ( 5234): [DEBUG] seapp_context_lookup: seinfoCategory = platform
D/SO_AGENT( 5201): [AccRegisterReceiver.java(Line:56/Method:onReceive)] Receive broadcast meassage:android.net.conn.CONNECTIVITY_CHANGE
D/dalvikvm( 1804): GC_CONCURRENT freed 1663K, 36% free 12194K/19008K, paused 8ms+4ms, total 126ms
I/SO_AGENT( 5201): [AccRegisterReceiver.java(Line:87/Method:onReceive)] Need to accessory setup...
D/TimaKeyStoreProvider( 5234): in addTimaSignatureService
W/DriveInitializer( 1804): Background init thread ended
D/TimaKeyStoreProvider( 5234): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 5234): Added TimaKesytore provider
,D/dalvikvm( 1205): GC_EXPLICIT freed 444K, 48% free 10036K/19008K, paused 8ms+6ms, total 47ms
,V/KVNProvider( 5234): query uri : content://com.sec.android.app.voicenote.common.util.VNProvider/search_suggest_tag_query
,V/KVNProvider( 5234): getFindoCursor query string : 
,I/ActivityManager(  775): Killing 4089:com.android.providers.calendar/u0a44 (adj 15): empty #43
,V/KVNProvider( 5234): getTagSearchCursor() tagSearchCursor count : 0
,I/SA      ( 4157): [OR] onReceive log=[SA = 2.0.0117 V = 19 HWD = 1280X720 2.0 dpi = 320  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = kmini3g P = kmini3gxx I = KOT49H M = SM-G800H OKLEFT false DIS KOT49H.G800HXXU1ANK2 PSS = 4.497045606779314  ]
,I/SA      ( 4157): [BDLM] already registered in spp
I/ActivityManager(  775): Killing 4043:com.android.calendar/u0a142 (adj 15): empty #43
,I/SA      ( 4157): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. ]
,I/SA      ( 4157): [OR] == ACTION_CONNECTIVITY_CHANGE ==
,I/SA      ( 4157): [SLFUCHKMGR] constructor called
,D/dalvikvm( 1219): GC_CONCURRENT freed 1477K, 38% free 11926K/19008K, paused 14ms+7ms, total 164ms
,I/SA      ( 4157): [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
,I/SA      ( 4157): [OR] == isSIMCardReady false ==
,I/SA      ( 4157): [SCU] == networkStateCheck == true
I/SA      ( 4157): [DM] getCountryCodeFromCSC : PL
I/SA      ( 4157): isChinaCountryCode : false
,I/SA      ( 4157): [OR] == networkStateCheck true ==
,I/dalvikvm( 4698): Total arena pages for JIT: 11
,I/dalvikvm( 4698): Total arena pages for JIT: 12
I/dalvikvm( 4698): Total arena pages for JIT: 13
,I/dalvikvm( 4698): Total arena pages for JIT: 14
,I/SA      ( 4157): [OR] GetMyCountryZoneTask
,I/SA      ( 4157): [OR] onReceive END
,I/SA      ( 4157): [SRS] prepareGetMyCountryZone
,I/SA      ( 4157): [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
,I/SA      ( 4157): [SSP] query invoked
I/ActivityManager(  775): Killing 4093:com.sec.android.widgetapp.SPlannerAppWidget/u0a143 (adj 15): empty #43
,I/SA      ( 4157): [TPMU] GetMccFromDB : null
I/SA      ( 4157): [SCU] getMccFromPreferece mcc = 260
,I/SA      ( 4157): [TPM] isNoProxy(default) : true
D/PhoneNumberLocatorBootCompletedReceiver( 1240): onReceive
,D/PhoneNumberLocatorBootCompletedReceiver( 1240): Phone number locator feature is dsiabled
,I/SA      ( 4157): [RC New] Execute method=[GET] start
,I/SELinux ( 5260): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5260):  
,I/SELinux ( 5260): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5260):  
I/SELinux ( 5260):  
,I/SELinux ( 5260): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5260): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 5260): >>>>> Normal User
,E/dalvikvm( 5260): >>>>> com.samsung.android.scloud.backup [ userId:0 | appId:10060 ]
,E/SELinux ( 5260): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 5260): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5260): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5260): Added TimaKesytore provider
,I/System.out( 4157): Thread-401(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
I/sCloudBackupApp( 5260): sCloudBackupApp Version Info : 3.7.3.KK_APP
,I/SCloudBackupReceiver( 5260): Other Intent
,I/ActivityManager(  775): Killing 4026:com.sec.phone/1001 (adj 15): empty #43
D/com.samsung.app( 1454): [KK_EASY_Accu]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
D/com.samsung.app( 1454): [KK_EASY_Accu]>>> WC:37 [0:0] oR : create UI manager : start
D/com.samsung.app( 1454): [KK_EASY_Accu]>>> UIMEM:89 [0:0] getInstance
D/com.samsung.app( 1454): [KK_EASY_Accu]>>> UIMEM:77 [0:0] UIManager : create ui manager
D/accuweather( 1454): [KK AccuPhone]>>> RM:73 [0:0] RefreshManager : create
I/System.out( 4157): Thread-401(ApacheHTTPLog):isShipBuild true
I/System.out( 4157): Thread-401(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
D/accuweather( 1454): [KK AccuPhone]>>> RM:136 [0:0]  V init 
D/daemonapp( 1511): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/accuweather( 1454): [KK AccuPhone]>>> RM:128 [0:0] updateCityList
,D/daemonapp( 1511): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,D/accuweather( 1454): [KK AccuPhone]>>> DBH:3047 [0:0] gADWI : count = 0
,D/daemonapp( 1511): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/com.samsung.app( 1454): [KK_EASY_Accu]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
,D/com.samsung.app( 1454): [KK_EASY_Accu]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
,I/SELinux ( 5274): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5274):  
,D/LocationManagerService(  775): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,I/SELinux ( 5274): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5274):  
I/SELinux ( 5274):  
,I/SELinux ( 5274): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5274): [DEBUG] seapp_context_lookup: seinfoCategory = release
E/dalvikvm( 5274): >>>>> Normal User
,E/dalvikvm( 5274): >>>>> com.samsung.android.internal.headlines [ userId:0 | appId:10106 ]
,E/SELinux ( 5274): [DEBUG] seapp_context_lookup: seinfoCategory = release
,D/TimaKeyStoreProvider( 5274): in addTimaSignatureService
,D/btif_config_util( 3229): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,D/TimaKeyStoreProvider( 5274): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5274): Added TimaKesytore provider
,D/HeadlinesChannelApplication( 5274): [onCreate]
,D/Headlines( 5274): HeadlinesSystemBroadcastReceiver onReceive android.net.conn.CONNECTIVITY_CHANGE
W/ActivityManager(  775): Permission Denial: getCurrentUser() from pid=5274, uid=10106 requires android.permission.INTERACT_ACROSS_USERS
,D/HeadlinesChannelUtil( 5274): getCountryCode(): countryCode = PL
,D/Headlines( 5274): Breath.onCreate
,D/HeadlinesCardManager( 5274): HeadlinesCardManager : constructor
E/HeadlinesCardManager( 5274): HeadlinesCardManager : ctor = image_cache size is 42MB
,D/SA Version( 5274): CardProvider Library : 13
,I/SELinux ( 5286): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5286):  
,D/MagazineService::CardProviderContentProvider( 4831): insertProvider: provider already exists.: com.samsung.android.app.headlines
,W/PhenotypeConfigurator( 1219): Server returned 404
,D/MagazineService::CardProviderContentProvider( 4831): insertProvider: provider is updated.: com.samsung.android.app.headlines
,D/dalvikvm(  242): GC_EXPLICIT freed 43K, 50% free 9506K/19008K, paused 2ms+3ms, total 27ms
,D/com.samsung.android.magazine.cardprovider.ConfigurationManager( 5274): registerCardProvider: provider already exists.
,I/Headlines( 5274): HeadlinesDataCenter ctor
I/Headlines( 5274): HeadlinesDataCenter. mLocale = en_US
,D/HeadlinesChannelUtil( 5274): getCountryCode(): countryCode = PL
,D/HeadlinesCardManager( 5274): HeadlinesCardManager : constructor welcome :YES
,D/dalvikvm(  242): GC_EXPLICIT freed <1K, 50% free 9506K/19008K, paused 2ms+3ms, total 20ms
,I/SELinux ( 5286): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5286):  
I/SELinux ( 5286):  
,I/SELinux ( 5286): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5286): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 5286): >>>>> Normal User
,E/dalvikvm( 5286): >>>>> com.google.android.apps.magazines [ userId:0 | appId:10112 ]
,E/SELinux ( 5286): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
,D/dalvikvm(  242): GC_EXPLICIT freed <1K, 50% free 9506K/19008K, paused 1ms+3ms, total 19ms
,D/LocationManagerService(  775): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/Headlines( 5274): Breath timer started. interval : 30000
,D/TimaKeyStoreProvider( 5286): in addTimaSignatureService
D/Headlines( 5274): Breath.onStartCommand : com.samsung.android.internal.headlines.UPDATE_WELCOME_CARD flag : 0
D/HeadlinesCardManager( 5274): updateCategory : HeadlinesCardManager:updateCategory() category size == 0
,D/HeadlinesCardManager( 5274): updateCategory : HeadlinesCardManager:updateCategory() try to query category list
D/Headlines( 5274): queryCategory.  mRequest is not initialized.
D/HeadlinesCardManager( 5274): updateCategory : HeadlinesCardManager:updateCategory() reponse : false
D/HeadlinesCardManager( 5274): requestUpdateNewsWelcomeCard : request update welcome card to content card.
,D/HeadlinesDataCenter( 5274): requestUpdateNewsWelcomeCard !!! no welcome card
,D/TimaKeyStoreProvider( 5286): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5286): Added TimaKesytore provider
,D/ChimeraCfgMgr( 1804): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 1804): Module APK com.google.android.play.games already loaded
,I/GamesSyncServiceMain( 1804): Found unexpected GCM tag when scheduling; aborting
,W/GamesSyncServiceMain( 1804): Failed to execute periodic sync, missing client context - aborting
V/AlarmManager(  775): waitForAlarm result :8
,V/AlarmManager(  775): waitForAlarm result :8
,V/AlarmManager(  775): waitForAlarm result :8
,V/AlarmManager(  775): waitForAlarm result :8
,V/AlarmManager(  775): waitForAlarm result :8
,E/cutils  (  222): Failed to mkdirat(/storage/extSdCard/Android): Read-only file system
,W/ContextImpl( 5286): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,E/cutils  (  222): Failed to mkdirat(/storage/extSdCard/Android): Read-only file system
W/Vold    (  222): Returning OperationFailed - no handler for errno 30
V/AlarmManager(  775): waitForAlarm result :8
,W/Vold    (  222): Returning OperationFailed - no handler for errno 30
W/ContextImpl( 5286): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,W/GAV2    ( 5286): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,E/cutils  (  222): Failed to mkdirat(/storage/extSdCard/Android): Read-only file system
,W/ContextImpl( 5286): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
W/Vold    (  222): Returning OperationFailed - no handler for errno 30
,E/cutils  (  222): Failed to mkdirat(/storage/extSdCard/Android): Read-only file system
,W/Vold    (  222): Returning OperationFailed - no handler for errno 30
W/ContextImpl( 5286): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,V/WebViewChromium( 5286): Binding Chromium to the main looper Looper (main, tid 1) {4250e000}
,I/chromium( 5286): [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserProcessMain( 5286): Initializing chromium process, renderers=0
,D/dalvikvm(  775): GC_EXPLICIT freed 2031K, 58% free 23371K/55124K, paused 6ms+12ms, total 134ms
I/SA      ( 4157): [RC New] [v2liruge] api execute + 875
,I/SA      ( 4157): [RC New] executeRequest [v2liruge] httpResponse : HTTP/1.1 200 OK
,W/chromium( 5286): [WARNING:proxy_service.cc(888)] PAC support disabled because there is no system implementation
V/AlarmManager(  775): waitForAlarm result :8
,I/System.out( 4157): AsyncTask #1 calls detatch()
,I/Adreno-EGL( 5286): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 5286): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 5286): Build Date: 03/21/14 Fri
I/Adreno-EGL( 5286): Local Branch: AU200+patches_03212014
I/Adreno-EGL( 5286): Remote Branch: 
I/Adreno-EGL( 5286): Local Patches: 
I/Adreno-EGL( 5286): Reconstruct Branch: 
,I/SA      ( 4157): [TPMU] getNetworkMcc : 
,I/SA      ( 4157): [SCU] saveMccToPreferece Start
,I/SA      ( 4157): [SCU] RegionMCC : 260
,I/SA      ( 4157): [SSP] query invoked
,V/GLSActivity( 1323): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1323): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/SA      ( 4157): [TPMU] GetMccFromDB : null
I/SA      ( 4157): [SCU] getMccFromPreferece mcc = 260
,I/SA      ( 4157): [SCU] saveMccToPreferece End
,I/SA      ( 4157): [RC New] executeRequest [v2liruge] end. 912
,I/SA      ( 4157): [RC New] Execute end
,I/SA      ( 4157): [OR] GetMyCountryZoneTask mcc = 260
,I/SA      ( 4157): [OR] GetMyCountryZoneTask Success
,E/WifiStateMachine(  775): CAPTIVE_PORTAL_EVENT_AUTHENTICATED
,I/NSApplication( 5286): Starting up...
,W/ActivityManager(  775): Permission Denial: getCurrentUser() from pid=5286, uid=10112 requires android.permission.INTERACT_ACROSS_USERS
,D/QuickConnect[1.1][2] ( 3199): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
I/QuickConnect[1.1][2] ( 3199): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
,V/QuickConnect[1.1][2] ( 3199): SconnectManager.getInstance - () return existing instance com.samsung.android.sconnect.SconnectManager@42841d98
I/ActivityManager(  775): Killing 3969:com.sec.android.app.music:service/u0a150 (adj 15): empty #43
,D/dalvikvm( 4279): GC_FOR_ALLOC freed 4028K, 38% free 11946K/19008K, paused 29ms, total 29ms
,I/dalvikvm-heap( 4279): Grow heap (frag case) to 16.986MB for 2129936-byte allocation
,I/SELinux ( 5330): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5330):  
,D/dalvikvm( 4279): GC_CONCURRENT freed 35K, 27% free 14010K/19008K, paused 3ms+1ms, total 24ms
,I/SELinux ( 5330): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5330):  
I/SELinux ( 5330):  
,I/SELinux ( 5330): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5330): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 5330): >>>>> Normal User
,E/dalvikvm( 5330): >>>>> com.android.email [ userId:0 | appId:10155 ]
,E/SELinux ( 5330): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 5330): in addTimaSignatureService
D/TimaKeyStoreProvider( 5330): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5330): Added TimaKesytore provider
,D/RCPManagerService(  775): exchangeData() failure , invalid userId
,D/RCPManagerService(  775): exchangeData() failure , invalid userId
,D/RCPManagerService(  775): exchangeData() failure , invalid userId
,I/SurfaceFlinger(  241): id=19 Removed Uoast (11/12)
,I/SurfaceFlinger(  241): id=19 Removed Uoast (-2/12)
,I/ActivityManager(  775): Killing 3076:com.google.android.talk/u0a105 (adj 15): empty #43
D/KeyguardUpdateMonitor( 1068): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1068): handleKeyguardVisibilityChanged(1)
D/PowerManagerService(  775): [api] release WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=775 (0x0)
D/PowerManagerService(  775): [api] applyWakeLockFlagsOnReleaseLocked : userActivityNoUpdateLocked is called : SCREEN_BRIGHT_WAKE_LOCK        'WindowManager' ON_AFTER_RELEASE (uid=1000, pid=775, ws=WorkSource{1000}) (elapsedTime=3460)
,I/SELinux ( 5348): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5348):  
,D/RCPManagerService(  775): exchangeData() failure , invalid userId
W/ActivityManager(  775): Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
,D/RCPManagerService(  775): exchangeData() failure , invalid userId
,D/RCPManagerService(  775): exchangeData() failure , invalid userId
,I/SELinux ( 5348): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5348):  
I/SELinux ( 5348):  
,I/SELinux ( 5348): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5348): [DEBUG] seapp_context_lookup: seinfoCategory = release
E/dalvikvm( 5348): >>>>> Normal User
,E/dalvikvm( 5348): >>>>> com.sec.android.provider.badge [ userId:0 | appId:10072 ]
,E/SELinux ( 5348): [DEBUG] seapp_context_lookup: seinfoCategory = release
,I/SELinux ( 5354): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5354):  
I/ActivityManager(  775): Killing 4117:com.sec.providers.settingsearch/u0a160 (adj 15): empty #43
,D/TimaKeyStoreProvider( 5348): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5348): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5348): Added TimaKesytore provider
,I/ActivityManager(  775): Killing 4267:com.sec.knox.bridge/1000 (adj 15): empty #43
,I/SELinux ( 5354): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5354):  
I/SELinux ( 5354):  
,I/SELinux ( 5354): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5354): [DEBUG] seapp_context_lookup: seinfoCategory = shared
E/dalvikvm( 5354): >>>>> Normal User
,E/dalvikvm( 5354): >>>>> com.samsung.android.service.travel [ userId:0 | appId:10169 ]
,E/SELinux ( 5354): [DEBUG] seapp_context_lookup: seinfoCategory = shared
,D/BadgeProvider( 5348): onCreate
,D/BadgeProvider( 5348): DatabaseHelper
,D/TimaKeyStoreProvider( 5354): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5354): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5354): Added TimaKesytore provider
W/ActivityManager(  775): Permission Denial: getCurrentUser() from pid=5348, uid=10072 requires android.permission.INTERACT_ACROSS_USERS
,D/BadgeProvider( 5348): query, [selection] : package='com.android.email' AND class='com.android.email.activity.Welcome' AND extraData='base_extra_badge'
,D/Launcher.Model( 1251): reloadBadges entered.
D/BadgeProvider( 5348): sendNotify entered. [uri] : content://com.sec.badge/apps/1
D/BadgeProvider( 5348): sendNotify, [notify] : null
D/BadgeProvider( 5348): update, [uri] : content://com.sec.badge/apps/1
D/BadgeProvider( 5348): update, [BadgeCount] : badgecount=0
,D/BadgeProvider( 5348): update, [UpdateCount] : 1
,I/dalvikvm( 1804): Could not find method android.security.NetworkSecurityPolicy.getInstance, referenced from method com.google.android.gms.ads.internal.t.e.a
,W/dalvikvm( 1804): VFY: unable to resolve static method 1032: Landroid/security/NetworkSecurityPolicy;.getInstance ()Landroid/security/NetworkSecurityPolicy;
,D/dalvikvm( 1804): VFY: replacing opcode 0x71 at 0x004e
W/ActivityManager(  775): Permission Denial: getCurrentUser() from pid=5354, uid=10169 requires android.permission.INTERACT_ACROSS_USERS
,D/dalvikvm( 1804): DexOpt: --- BEGIN 'ads1114403566.jar' (bootstrap=0) ---
,D/WaitQueueForNetworkActivate( 4887): notifyNetworkActivated
,W/ContextImpl( 4887): Implicit intents with startService are not safe: Intent { act=com.sec.knox.containeragent.service.containermanager.ContainerManagerService } android.content.ContextWrapper.bindService:529 com.sec.knox.containeragent.ContainerManager.<init>:49 com.sec.android.app.samsungapps.vlibrary2.knoxmode.KNOXAPI.<init>:20 
W/ActivityManager(  775): Unable to start service Intent { act=com.sec.knox.containeragent.service.containermanager.ContainerManagerService } U=0: not found
,D/dalvikvm( 5378): DexOpt: load 5ms, verify+opt 11ms, 197964 bytes
,D/dalvikvm( 1804): DexOpt: --- END 'ads1114403566.jar' (success) ---
,D/dalvikvm( 1804): DEX prep '/data/data/com.google.android.gms/cache/ads1114403566.jar': unzip in 0ms, rewrite 149ms
,E/SMD     (  235): DCD ON
,D/hcjo    ( 4887): AutoUpdateManager:IDLE:execute
,I/dalvikvm( 4887): Could not find method android.view.Window.setStatusBarColor, referenced from method com.sec.android.app.samsungapps.CommonActivity.onCreate
W/dalvikvm( 4887): VFY: unable to resolve virtual method 14867: Landroid/view/Window;.setStatusBarColor (I)V
,D/dalvikvm( 4887): VFY: replacing opcode 0x6e at 0x0024
D/InitializeManagerStateMachine( 4887): execute::IDLE:EXECUTE
,D/InitializeManagerStateMachine( 4887): exit::IDLE
,D/InitializeManagerStateMachine( 4887): entry::NETWORK_CHECK
D/InitializeManagerStateMachine( 4887): execute::NETWORK_CHECK:NETWORK_STATE_OK
D/InitializeManagerStateMachine( 4887): exit::NETWORK_CHECK
D/InitializeManagerStateMachine( 4887): entry::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 4887): execute::CHECK_COUNTRY_INFO:COUNTRY_INFO_OK
,D/InitializeManagerStateMachine( 4887): exit::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 4887): entry::SUCCESS
,D/hcjo    ( 4887): AutoUpdateManager:INITCHECK:onInitializeSuccess
,D/hcjo    ( 4887): AutoUpdateTriggerManager:IDLE:setInterval:345600000
,D/hcjo    ( 4887): AutoUpdateTriggerManager:IDLE:notifyNextTime
,D/hcjo    ( 4887): AutoUpdateManager:UPD_CHECK_TIMING:onNoUpdateTime
,D/InitializeManagerStateMachine( 4887): exit::SUCCESS
,D/InitializeManagerStateMachine( 4887): entry::IDLE
I/ActivityManager(  775): Killing 4322:com.wssyncmldm/1000 (adj 15): empty #43
,I/iu.SyncManager( 1804): SYNC; picasa accounts
,D/NetworkLogImpl( 1804): Loaded NetworkSpeedPredictor
,I/iu.Environment( 1804): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,I/iu.UploadsManager( 1804): num queued entries: 0
,I/iu.UploadsManager( 1804): num updated entries: 0
,I/iu.SyncManager( 1804): NEXT; no task
,I/SELinux ( 5391): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5391):  
,I/SELinux ( 5391): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5391):  
I/SELinux ( 5391):  
,I/SELinux ( 5391): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5391): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 5391): >>>>> Normal User
,E/dalvikvm( 5391): >>>>> com.android.calendar [ userId:0 | appId:10142 ]
,E/SELinux ( 5391): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 5391): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5391): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5391): Added TimaKesytore provider
,I/ActivityManager(  775): Killing 4484:com.android.defcontainer/u0a6 (adj 15): empty #43
D/BootCompletedReceiver(  775): onReceive
,I/KLMS-2.3.201 : ( 5187): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,I/GCM     ( 1323): GCM config loaded
,I/KLMS-2.3.201 : ( 5187): MainReciver() : EventNotificationReciver- method called: AppActivityListner onReceive for Intent Action : android.intent.action.TIME_SET , timestamp: 1450100371528
,I/KLMS-2.3.201 : ( 5187): StateImplV2() : dateTimeChanged() : Mon Dec 14 14:39:31 CET 2015
,D/SO_AGENT( 5201): [ServerTimeReceiver.java(Line:44/Method:onReceive)] Receive broadcast meassage:android.intent.action.TIME_SET
,I/SO_AGENT( 5201): [ServerTimeReceiver.java(Line:47/Method:onReceive)] No action is available before server time settings
,I/SA      ( 4157): [SBR] StdBroadcastReceiver received Intent of  action.TIME_SET.
,D/Mms/MessagingNotification( 3861): [start]    nonBlockingUpdateMessageIndicator()
,D/Mms/MessagingNotification( 3861): sDisableVibrateForCamera = false
D/Mms/MessagingNotification( 3861): isBlockingModeEnable() = false
,D/Mms/TelephonyPermission( 3861): isDefault true
,D/TP/MmsSmsProvider( 1240): match 8:Elapsed time : 3.481 ms
,I/SELinux ( 5420): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5420):  
,D/TP/MmsSmsProvider( 1240): match 200:Elapsed time : 2.004 ms
,D/BadgeProvider( 5348): query, [selection] : package='com.android.mms' AND class='com.android.mms.ui.ConversationComposer' AND extraData='base_extra_badge'
,I/SELinux ( 5420): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5420):  
I/SELinux ( 5420):  
D/BadgeProvider( 5348): sendNotify entered. [uri] : content://com.sec.badge/apps/2
D/BadgeProvider( 5348): sendNotify, [notify] : null
D/BadgeProvider( 5348): update, [uri] : content://com.sec.badge/apps/2
D/BadgeProvider( 5348): update, [BadgeCount] : badgecount=0
,D/BadgeProvider( 5348): update, [UpdateCount] : 1
D/Launcher.Model( 1251): reloadBadges entered.
I/SELinux ( 5420): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,D/Mms/MessagingNotification( 3861): setBadgeCount(), count=0
,E/SELinux ( 5420): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 5420): >>>>> Normal User
E/dalvikvm( 5420): >>>>> com.samsung.android.scloud.sync [ userId:0 | appId:10062 ]
,D/MessagingNotification( 3861): remove alarm
,E/SELinux ( 5420): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/Mms/MessagingNotification( 3861): [end]    nonBlockingUpdateMessageIndicator()
D/TimaKeyStoreProvider( 5420): in addTimaSignatureService
,D/Mms/MessagingNotification( 3861): updateAllHistoryAsRead()
,D/TimaKeyStoreProvider( 5420): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5420): Added TimaKesytore provider
,V/AlarmManager(  775): waitForAlarm result :8
,W/ActivityManager(  775): Permission Denial: getCurrentUser() from pid=5420, uid=10062 requires android.permission.INTERACT_ACROSS_USERS
,I/ActivityManager(  775): Killing 3264:com.sec.android.inputmethod/1000 (adj 15): empty #43
D/com.samsung.app( 1454): [KK_EASY_Accu]>>> WC:30 [0:0] action : androidintentactionTIME_SET
D/com.samsung.app( 1454): [KK_EASY_Accu]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
,I/SELinux ( 5436): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5436):  
,I/ Time Manager ( 5420): Time Difference not stored. TIME_DIFFERENCE
,I/SELinux ( 5436): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5436):  
I/SELinux ( 5436):  
,I/SELinux ( 5436): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5436): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 5436): >>>>> Normal User
,E/dalvikvm( 5436): >>>>> com.sec.android.app.clockpackage [ userId:0 | appId:10084 ]
,E/SELinux ( 5436): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 5436): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5436): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5436): Added TimaKesytore provider
,I/PowerManagerService(  775): [PWL] Off : 75s ago
I/PowerManagerService(  775): [PWL]   PowerManagerService.WakeLocks: ref count=1
,I/PowerManagerService(  775): [PWL]     mWakeLockSummary : 0x1
I/PowerManagerService(  775): [PWL]       PARTIAL_WAKE_LOCK              'AlarmManager' (uid=1000, pid=775, ws=WorkSource{10011 com.google.android.gms}) (elapsedTime=4043)
,I/PowerManagerService(  775): [PWL]       PARTIAL_WAKE_LOCK              '*net_scheduler*' (uid=10011, pid=1323, ws=WorkSource{10011 com.google.android.gms}) (elapsedTime=1666)
,D/ConnectivityService(  775): handleInetConditionHoldEnd: net=1, condition=100, published condition=0
,D/STATUSBAR-NetworkController_dual( 1068): onReceive() - CONNECTIVITY_ACTION, INET_CONDITION_ACTION
D/StatusBar.NetworkController_dual( 1068): mMobileLabelViews start
D/StatusBar.NetworkController_dual( 1068): mMobileLabelViews set mobileLabel[SIM_0] =
D/StatusBar.NetworkController_dual( 1068): mMobileLabelViews GONE
D/StatusBar.NetworkController_dual( 1068): mMobileLabelViews2 set mobileLabel[SIM_1] =
D/StatusBar.NetworkController_dual( 1068): mMobileLabelViews2 GONE
,D/StatusBar.NetworkController_dual( 1068): mSingleMobileLabelViews set : simMode = 0
,D/StatusBar.NetworkController_dual( 1068): mSingleMobileLabelViews set as slot1`s
,I/SELinux ( 5448): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5448):  
I/ActivityManager(  775): Killing 4534:com.google.android.partnersetup/u0a14 (adj 15): empty #43
,D/STATUSBAR-NetworkController_dual( 1068): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
D/StatusBar.NetworkController_dual( 1068): mMobileLabelViews start
D/StatusBar.NetworkController_dual( 1068): mMobileLabelViews set mobileLabel[SIM_0] =
D/StatusBar.NetworkController_dual( 1068): mMobileLabelViews GONE
D/StatusBar.NetworkController_dual( 1068): mMobileLabelViews2 set mobileLabel[SIM_1] =
D/StatusBar.NetworkController_dual( 1068): mMobileLabelViews2 GONE
,D/StatusBar.NetworkController_dual( 1068): mSingleMobileLabelViews set : simMode = 0
,D/StatusBar.NetworkController_dual( 1068): mSingleMobileLabelViews set as slot1`s
,I/SELinux ( 5448): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5448):  
I/SELinux ( 5448):  
,I/SELinux ( 5448): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5448): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 5448): >>>>> Normal User
,E/dalvikvm( 5448): >>>>> com.sec.esdk.elm [ userId:0 | appId:10094 ]
,E/SELinux ( 5448): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 5448): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5448): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5448): Added TimaKesytore provider
,W/ActivityManager(  775): Permission Denial: getCurrentUser() from pid=5448, uid=10094 requires android.permission.INTERACT_ACROSS_USERS
,D/elm:14132( 5448): ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver }
,D/elm:14132( 5448): ELMEngine.ELMEngine( context ).
,D/elm:14132( 5448): MDMBridge.setEnterpriseBridge()
,D/elm:14132( 5448): ELMAbstractReceiver : Receive Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.sec.esdk.elm/.service.ElmAgentService } END.
,D/elm:14132( 5448): ElmAgentService : onCreate()
,D/elm:14132( 5448): ElmAgentService : onHandleIntent() Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.sec.esdk.elm/.service.ElmAgentService }
,I/knox    ( 3131): MainReceiver.onReceive() : Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.sec.knox.seandroid/.receiver.MainReceiver }
,D/knox    ( 3131): MainReceiver.listeningToTimeDateChanges( context, intent ).
,I/knox    ( 3131): MainReceiver.onReceive() END - - - - - : Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.sec.knox.seandroid/.receiver.MainReceiver }
,W/ContextImpl( 3131): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1857 android.content.ContextWrapper.startService:506 android.content.ContextWrapper.startService:506 com.sec.knox.seandroid.receiver.MainReceiver.onReceive:142 android.app.ActivityThread.handleReceiver:2698 
D/elm:14132( 5448): ELMAgentService.listeningToTimeDateChanges( context, intent ).
D/elm:14132( 5448): ELMEngine.ServiceHandler.handleMessage( ALARM_MODIFY ). 
D/elm:14132( 5448): ModuleBase.resetCalllogAPIAlarm()
D/knox    ( 3131): KNOXAgentService : onCreate()
D/knox    ( 3131): KNOXAgentService : set alarms for deniallog and usage data upload
D/knox    ( 3131): KNOXAgentService. startJobThread() start
D/knox    ( 3131): KNOXAgentService. JobThread()
D/knox    ( 3131): KNOXAgentService. JobThread. notifyAll().
D/knox    ( 3131): KNOXAgentService. startJobThread() wait
,I/SELinux ( 5463): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5463):  
,D/elm:14132( 5448): ModuleBase.ModifySetAlarm()
D/elm:14132( 5448): MDMBridge.getInstance()
,D/elm:14132( 5448): MDMBridge.getAllLicenseInfoFromSDK()
D/knox    ( 3131): KNOXAgentService : onDestroy().
,D/knox    ( 3131): ModuleBase.cancelAllAlarmManageModule()
,D/elm:14132( 5448): ElmAgentService : onDestroy().
V/AlarmManager(  775): waitForAlarm result :8
I/ActivityManager(  775): Killing 4548:com.samsung.groupcast/u0a15 (adj 15): empty #43
,I/SELinux ( 5463): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5463):  
I/SELinux ( 5463):  
,I/SELinux ( 5463): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5463): [DEBUG] seapp_context_lookup: seinfoCategory = shared
E/dalvikvm( 5463): >>>>> Normal User
,E/dalvikvm( 5463): >>>>> com.sec.android.widgetapp.SPlannerAppWidget [ userId:0 | appId:10143 ]
,E/SELinux ( 5463): [DEBUG] seapp_context_lookup: seinfoCategory = shared
,D/TimaKeyStoreProvider( 5463): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5463): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5463): Added TimaKesytore provider
,W/ActivityManager(  775): Permission Denial: getCurrentUser() from pid=5463, uid=10143 requires android.permission.INTERACT_ACROSS_USERS
,I/SELinux ( 5475): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5475):  
I/ActivityManager(  775): Killing 4563:com.android.musicfx/u0a24 (adj 15): empty #43
,I/SELinux ( 5475): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5475):  
I/SELinux ( 5475):  
,I/SELinux ( 5475): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5475): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 5475): >>>>> Normal User
,E/dalvikvm( 5475): >>>>> com.sec.android.app.taskmanager [ userId:0 | appId:10166 ]
,E/SELinux ( 5475): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,I/System.out( 1804): Thread-222(HTTPLog):isShipBuild true
,I/System.out( 1804): Thread-222(HTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,D/TimaKeyStoreProvider( 5475): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5475): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5475): Added TimaKesytore provider
,W/ActivityManager(  775): Permission Denial: getCurrentUser() from pid=5475, uid=10166 requires android.permission.INTERACT_ACROSS_USERS
,I/SELinux ( 5490): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5490):  
I/ActivityManager(  775): Killing 4591:com.samsung.android.app.galaxyfinder/u0a34 (adj 15): empty #43
,I/SELinux ( 5490): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5490):  
I/SELinux ( 5490):  
I/SELinux ( 5490): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 5490): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 5490): >>>>> Normal User
E/dalvikvm( 5490): >>>>> com.qualcomm.timeservice [ userId:0 | appId:10168 ]
E/SELinux ( 5490): [DEBUG] seapp_context_lookup: seinfoCategory = platform
D/TimaKeyStoreProvider( 5490): in addTimaSignatureService
D/TimaKeyStoreProvider( 5490): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 5490): Added TimaKesytore provider
W/ActivityManager(  775): Permission Denial: getCurrentUser() from pid=5490, uid=10168 requires android.permission.INTERACT_ACROSS_USERS
D/dalvikvm( 5490): No JNI_OnLoad found in /vendor/lib/libTimeService.so 0x428338e0, skipping init
D/TimeService( 5490): Receivedandroid.intent.action.TIME_SET intent. Current Time is 1450100372700
D/        ( 5490): TimeServiceNative: User Time to be set is 1450100372700
D/QC-time-services( 5490): Lib:time_genoff_operation: pargs->base = 2
D/QC-time-services( 5490): Lib:time_genoff_operation: pargs->operation = 0
D/QC-time-services( 5490): Lib:time_genoff_operation: pargs->ts_val = 1450100372700
D/QC-time-services(  287): Daemon: Connection accepted:time_genoff
D/QC-time-services( 5490): Lib:time_genoff_operation: Send to server  passed!!
D/QC-time-services(  287): Daemon: genoff_handler: Process name is omm.timeservice
D/QC-time-services(  287): Daemon:Received base = 2, unit = 1, operation = 0,value = 1450100372700
D/QC-time-services(  287): Daemon:genoff_opr: Base = 2, val = 1450100372700, operation = 0
D/QC-time-services(  287): Daemon:rtc_get: Time read from RTC -- MM/DD/YY HH:MM:SS0/18/70 5:36:38
D/QC-time-services(  287): Daemon:Value read from RTC seconds = 1488998000
D/QC-time-services(  287): Daemon:new time 1450100372700 
D/QC-time-services(  287): Daemon: delta 1448611374700 genoff 1448611374700 
D/QC-time-services(  287): Daemon:genoff_persistent_update: Writing genoff = 1448611374700 to memory
D/QC-time-services(  287): Daemon:Opening File: /data/time/ats_2
D/QC-time-services(  287): Daemon:time_persistent_memory_opr:Genoff write operation 
D/QC-time-services(  287): Updating the TOD offset
D/QC-time-services(  287): Daemon:genoff_persistent_update: Writing genoff = 1448611374700 to memory
D/QC-time-services(  287): Daemon:Opening File: /data/time/ats_1
D/QC-time-services(  287): Daemon:time_persistent_memory_opr:Genoff write operation 
E/QC-time-services(  287): Daemon:Update to modem bit set
D/QC-time-services(  287): Daemon:genoff_send_modem: Sending data to MODEM !
D/QC-time-services(  287): Daemon: Base = 2, Value being sent to MODEM = 1134135572700
E/QC-time-services( 5490): Receive Passed == base = 2, unit = 1, operation = 0, result = 0
E/QC-time-services(  287): Daemon: Time-services: Waiting to acceptconnection
E/QC-time-services(  287): Daemon:tod_update_ind_cb: Got Update from modem msg_id 40
V/AlarmManager(  775): waitForAlarm result :4
V/AlarmManager(  775): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
I/ActivityManager(  775): Killing 4632:com.sec.android.service.health/u0a16 (adj 15): empty #43
D/daemonapp( 1511): [MSC_Daemon]>>> WU:236 [0:0] regintype : EUR
D/daemonapp( 1511): [MSC_Daemon]>>> WU:292 [0:0] cp type is : cp_eng
D/daemonapp( 1511): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/settings
D/daemonapp( 1511): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
D/daemonapp( 1511): [MSC_Daemon]>>> WDSM:44 [0:0] Act : androidintentactionTIME_SET, run:true
D/comsamsunglog( 1511): [MSC_Daemon]>>> ====================================================================================================================
D/comsamsunglog( 1511): [MSC_Daemon]>>> daemonapp [Version : 14052601 ] [ 1 ] 
D/comsamsunglog( 1511): [MSC_Daemon]>>> Header set to : ===> "daemonapp" <===
D/comsamsunglog( 1511): [MSC_Daemon]>>> ====================================================================================================================
D/daemonapp( 1511): [MSC_Daemon]>>> WDSM:85 [0:0] c:null, r:3
D/daemonapp( 1511): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/packagename
D/daemonapp( 1511): [MSC_Daemon]>>> WU:1485 [0:0] PakNme size = 2
D/daemonapp( 1511): [MSC_Daemon]>>> WU:236 [0:0] regintype : EUR
D/daemonapp( 1511): [MSC_Daemon]>>> WU:292 [0:0] cp type is : cp_eng
D/daemonapp( 1511): [MSC_Daemon]>>> WU:1488 [0:0] CP Name cp_eng
D/dalvikvm( 1511): GC_CONCURRENT freed 7548K, 47% free 10138K/19008K, paused 7ms+4ms, total 73ms
D/dalvikvm( 1511): WAIT_FOR_CONCURRENT_GC blocked 45ms
D/daemonapp( 1511): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/packagename
D/comdaemonstockapp( 1511): [Daemon_Stock]>>> StockclockDaemonService.java:60 [0:0] onReceive: androidintentactionTIME_SET
D/comdaemonstockapp( 1511): [Daemon_Stock]>>> StockclockDaemonService.java:61 [0:0] appServiceStatus: 0
I/PCWCLIENTTRACE_SYSTEMReceiver( 4577): mConnectivityHandler : connected
I/CheckinService( 1804): Checkin interval check for package: unspecified last checkin: 1449576543959 min interval config: 0 actual interval: 523828919
W/PCWCLIENTTRACE_AccountUtil( 4577): [hasSamungAccount] - No Samsung Account
V/AlarmManager(  775): waitForAlarm result :4
V/AlarmManager(  775): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
W/linker  ( 4577): libterrier.so has text relocations. This is wasting memory and is a security risk. Please fix.
I/CSTORAGE( 4577): ================================================
I/CSTORAGE( 4577):  CSTORAGE_SKM_LIB v1.0.14
I/CSTORAGE( 4577): ================================================
D/dalvikvm( 4577): No JNI_OnLoad found in /system/lib/libterrier.so 0x42834320, skipping init
I/PCWCLIENTTRACE_SecurePreferencesJNI( 4577): [GetString-S]
I/terrier ( 4577): v1.1.3q com.sec.pcw.device: getString function called
D/QSEECOMAPI: ( 4577): QSEECom_get_handle sb_length = 0x2040
D/QSEECOMAPI: ( 4577): App is not loaded in QSEE
W/WifiP2pStateTracker(  775): WifiP2pStateReceiver : android.net.wifi.LINK_CONFIGURATION_CHANGED
D/ConnectivityService(  775): handleConnectivityChange: addresses changed linkProperty[1]: resetMask=0
D/ConnectivityService(  775):    car=removed=[] added=[fe80::3a94:96ff:feb5:6dd/64,]
D/ConnectivityService(  775): handleConnectivityChange: setting default proxy info 
D/QSEECOMAPI: ( 4577): Loaded image: APP id = 3
D/ConnectivityService(  775): updateSourceRoutes : no source routing conditions
D/QSEECOMAPI: ( 4577): QSEECom_dealloc_memory 
D/QSEECOMAPI: ( 4577): QSEECom_shutdown_app, app_id = 3
E/terrier ( 4577): com.sec.pcw.device: getString: failed to get string(-1)
I/PCWCLIENTTRACE_SecurePreferencesJNI( 4577): [GetString-E]
I/PCWCLIENTTRACE_PushUtil( 4577): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 4577): sales region : global
I/PCWCLIENTTRACE_PushUtil( 4577): getPushTypeList : [SPP, GCM]
E/PCWCLIENTTRACE_PCWHandler( 4577): [ensureRegistration] - No Samsung account
D/dalvikvm(  775): GC_EXPLICIT freed 1334K, 58% free 23402K/55124K, paused 6ms+13ms, total 162ms
D/dalvikvm( 1323): GC_CONCURRENT freed 1848K, 43% free 10852K/19008K, paused 2ms+3ms, total 25ms
D/Finsky  ( 3577): [349] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
D/Finsky  ( 3577): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,D/Mms/MessagesLockscreen( 3861): onReceive() action = com.android.mms.ui.MessagesLockscreenmSimSlot : [0] Mms = false count = 0
,D/ContextualEventManager( 1068): removeContextualEvent(): requestClass=com.android.mms
D/ContextualEventManager( 1068): removeMissedEventView rq=com.android.mms[cFlag, mFlag]=[false, false]
D/ContextualEventManager( 1068): updateContainer()
D/ContextualEventContainer( 1068): update()
D/ContextualEventContainer( 1068): handleUpdate()
D/ContextualEventManager( 1068): getTopEventView()
,D/ContextualEventManager( 1068): getTopContextualEvent()
,D/Headlines( 5274): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE
,D/Headlines( 5274): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0
,D/Headlines( 5274): Breath 3255 latestRequest time : 1450100369984 current time : 1450100373239
,I/SELinux ( 5507): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5507):  
,D/ContextualEventManager( 1068): top view = flightmode
I/KeyguardEffectViewMain( 1068): *** KeyguardEffectView getInstance ***
D/ContextualEventManager( 1068): getTopEventClass()
,D/ContextualEventManager( 1068): getTopContextualEvent()
,D/ContextualEventManager( 1068): !isClockTop
D/ContextualEventManager( 1068): getTopEventClass()
,D/ContextualEventManager( 1068): getTopContextualEvent()
D/ContextualEventManager( 1068): !isClockTop
D/ContextualEventManager( 1068): getTopEventClass()
,D/ContextualEventManager( 1068): getTopContextualEvent()
D/UsbManager( 1068):  :::: isUsb30Available :: return = false from pid = 1068
,D/dalvikvm(  242): GC_EXPLICIT freed 42K, 50% free 9506K/19008K, paused 2ms+3ms, total 28ms
,D/SecContextualClockFlightMode( 1068): handleUpdateClock()
,D/KeyguardProperties( 1068): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/dalvikvm(  242): GC_EXPLICIT freed <1K, 50% free 9506K/19008K, paused 2ms+3ms, total 19ms
,I/SELinux ( 5507): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5507):  
I/SELinux ( 5507):  
,I/SELinux ( 5507): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 5507): [DEBUG] seapp_context_lookup: seinfoCategory = release
E/dalvikvm( 5507): >>>>> Normal User
,E/dalvikvm( 5507): >>>>> com.android.providers.calendar [ userId:0 | appId:10044 ]
,E/SELinux ( 5507): [DEBUG] seapp_context_lookup: seinfoCategory = release
,D/dalvikvm(  242): GC_EXPLICIT freed <1K, 50% free 9506K/19008K, paused 2ms+2ms, total 20ms
,D/TimaKeyStoreProvider( 5507): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5507): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5507): Added TimaKesytore provider
,W/ActivityManager(  775): Permission Denial: getCurrentUser() from pid=5507, uid=10044 requires android.permission.INTERACT_ACROSS_USERS
,E/Watchdog(  775): !@Sync 4
,E/SMD     (  235): DCD ON
,I/ActivityManager(  775): Killing 3936:com.samsung.android.sdk.samsunglink/u0a42 (adj 15): empty #43
,D/STATUSBAR-NetworkController_dual( 1068): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
,D/StatusBar.NetworkController_dual( 1068): mMobileLabelViews start
D/StatusBar.NetworkController_dual( 1068): mMobileLabelViews set mobileLabel[SIM_0] =
,D/StatusBar.NetworkController_dual( 1068): mMobileLabelViews GONE
D/StatusBar.NetworkController_dual( 1068): mMobileLabelViews2 set mobileLabel[SIM_1] =
,D/StatusBar.NetworkController_dual( 1068): mMobileLabelViews2 GONE
,D/StatusBar.NetworkController_dual( 1068): mSingleMobileLabelViews set : simMode = 0
,D/StatusBar.NetworkController_dual( 1068): mSingleMobileLabelViews set as slot1`s
,I/GAV2    ( 5286): Thread[GAThread,5,main]: No campaign data found.
,D/AmoledAdjustTimer(  775): prevTemp = 286, currTemp = 289, prevStep = 4, currStep = 4
,E/SMD     (  235): DCD ON
,D/CaptivePortalTracker(  775): DelayedCaptiveCheckState{ when=-5ms what=2 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  775): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,D/CaptivePortalTracker(  775): Checking http://216.58.209.46/generate_204
,W/ActivityThread(  775): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,D/SSRMv2:SIOP(  775): SIOP:: AP = 310, Delta = -10
,D/BatteryService(  775): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 292, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:33, charge type:1, power sharing:false
,D/BatteryService(  775): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  775): mCoverManager.getCoverState() : true
,D/BatteryService(  775): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3229): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3229): Disconnected process message: 10
,I/System.out(  775): Thread-163(HTTPLog):isShipBuild true
,I/System.out(  775): Thread-163(HTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,D/CaptivePortalTracker(  775): Don't send network conditions - lacking user consent.
,D/CaptivePortalTracker(  775): isCaptivePortal: ret=false rspCode=204
,D/CaptivePortalTracker(  775): Not captive network NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/CaptivePortalTracker(  775): notifyPortalCheckCompleted: captive=false ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/ConnectivityService(  775): captivePortalCheckCompleted: ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false captive=false
,W/ProcessCpuTracker(  775): Skipping unknown process pid 5563
,W/ProcessCpuTracker(  775): Skipping unknown process pid 5564
,W/ProcessCpuTracker(  775): Skipping unknown process pid 5566
,E/SMD     (  235): DCD ON
,D/PreloadUpdateManagerStateMachine( 4887): execute::IDLE:EXECUTE
,D/PreloadUpdateManagerStateMachine( 4887): exit::IDLE
,D/PreloadUpdateManagerStateMachine( 4887): entry::CHECK_TIMEOUT_FOR_UPDATE
,D/hcjo    ( 4887): AutoUpdateTriggerManager:REQUEST2:requestInterval
,I/Volley  ( 4887): RestApi Request Add : 2307
,E/File    ( 4887): fail readDirectory() errno=2
,D/dalvikvm( 4887): GC_CONCURRENT freed 7582K, 47% free 10107K/19008K, paused 3ms+4ms, total 48ms
,D/dalvikvm( 4887): GC_CONCURRENT freed 1953K, 47% free 10159K/19008K, paused 4ms+3ms, total 37ms
,E/SMD     (  235): DCD ON
,I/System.out( 4887): Thread-475(HTTPLog):isShipBuild true
,I/System.out( 4887): Thread-475(HTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,D/hcjo    ( 4887): AutoUpdateTriggerManager:REQUEST2:setInterval:86400000
,D/hcjo    ( 4887): AutoUpdateTriggerManager:REQUEST2:notifyTimedOutAndWriteUpdateCheckedTime
,D/PreloadUpdateManagerStateMachine( 4887): execute::CHECK_TIMEOUT_FOR_UPDATE:TIMED_OUT
D/PreloadUpdateManagerStateMachine( 4887): exit::CHECK_TIMEOUT_FOR_UPDATE
,D/PreloadUpdateManagerStateMachine( 4887): entry::REQ_UPDATE_CHECK
,I/Volley  ( 4887): RestApi Request Add : 2315
,I/qtaguid ( 4887): Failed write_ctrl(u -1) res=-1 errno=9
,I/qtaguid ( 4887): Untagging socket -1 failed errno=-9
,W/NetworkManagementSocketTagger( 4887): untagSocket(-1) failed with errno -9
,D/PreloadUpdateManagerStateMachine( 4887): execute::REQ_UPDATE_CHECK:REQUEST_SUCCESS
,D/PreloadUpdateManagerStateMachine( 4887): exit::REQ_UPDATE_CHECK
D/PreloadUpdateManagerStateMachine( 4887): entry::NOTIFY_NOTIFICATION
D/PreloadUpdateManagerStateMachine( 4887): exit::NOTIFY_NOTIFICATION
,D/PreloadUpdateManagerStateMachine( 4887): entry::FINISH
,D/PreloadUpdateManagerStateMachine( 4887): exit::FINISH
,D/PreloadUpdateManagerStateMachine( 4887): entry::IDLE
,I/ActivityManager(  775): Waited long enough for: ServiceRecord{4338f598 u0 com.samsung.android.app.headlines/com.samsung.android.internal.headlines.HeadlinesService}
,D/AmoledAdjustTimer(  775): prevTemp = 289, currTemp = 292, prevStep = 4, currStep = 4
,E/SMD     (  235): DCD ON
,D/BatteryService(  775): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 290, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:40, charge type:1, power sharing:false
,D/SSRMv2:SIOP(  775): SIOP:: AP = 300, Delta = -10
,D/BatteryService(  775): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  775): mCoverManager.getCoverState() : true
,D/BatteryService(  775): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,V/HeadsetService( 3229): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3229): Disconnected process message: 10
,W/ContextImpl(  775): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  235): DCD ON
,E/SMD     (  235): DCD ON
,E/SMD     (  235): DCD ON
,D/AmoledAdjustTimer(  775): prevTemp = 292, currTemp = 290, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP(  775): SIOP:: AP = 300, Delta = 0
,E/SMD     (  235): DCD ON
,V/AlarmManager(  775): waitForAlarm result :4
,V/AlarmManager(  775): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,D/BatteryService(  775): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 289, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:33, charge type:1, power sharing:false
,D/BatteryService(  775): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  775): stay LED for fully charged
,D/UiModeManager(  775): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3229): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3229): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/AlarmManager(  775): waitForAlarm result :8
,V/AlarmManager(  775): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1068): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,E/ActivityThread( 1804): Failed to find provider info for com.android.contacts.metadata
,D/SyncManager(  775): failed sync operation 
,D/SyncManager(  775): not retrying sync operation because the error is a hard error: 
,E/SMD     (  235): DCD ON
,I/PowerManagerService(  775): [PWL] Off : 105s ago
,E/Watchdog(  775): !@Sync 5
,E/SMD     (  235): DCD ON
,D/AmoledAdjustTimer(  775): prevTemp = 290, currTemp = 289, prevStep = 4, currStep = 4
,E/SMD     (  235): DCD ON
,D/SSRMv2:SIOP(  775): SIOP:: AP = 300, Delta = 0
,W/ContextImpl(  775): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  235): DCD ON
,V/AlarmManager(  775): waitForAlarm result :4
,V/AlarmManager(  775): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,D/Headlines( 5274): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE
,D/Headlines( 5274): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0
,D/Headlines( 5274): Breath 41805 latestRequest time : 1450100369984 current time : 1450100411789
,D/BatteryService(  775): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:36, charge type:1, power sharing:false
,D/BatteryService(  775): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  775): stay LED for fully charged
,D/UiModeManager(  775): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3229): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3229): Disconnected process message: 10
,I/VacuumService( 1219): Vacuum at: now=1450100412556 tag=VacuumService
,E/SMD     (  235): DCD ON
,D/AmoledAdjustTimer(  775): prevTemp = 289, currTemp = 287, prevStep = 4, currStep = 4
,E/SMD     (  235): DCD ON
,D/SSRMv2:SIOP(  775): SIOP:: AP = 300, Delta = 0
,E/SMD     (  235): DCD ON
,E/SMD     (  235): DCD ON
,E/SMD     (  235): DCD ON
,D/AmoledAdjustTimer(  775): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,E/SMD     (  235): DCD ON
,D/SSRMv2:SIOP(  775): SIOP:: AP = 300, Delta = 0
,V/AlarmManager(  775): waitForAlarm result :4
,V/AlarmManager(  775): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,W/ContextImpl(  775): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/BatteryService(  775): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:34, charge type:1, power sharing:false
,D/BatteryService(  775): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  775): mCoverManager.getCoverState() : true
,D/BatteryService(  775): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3229): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3229): Disconnected process message: 10
D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,V/AlarmManager(  775): waitForAlarm result :8
,D/Headlines( 5274): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE
,D/Headlines( 5274): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0
,D/Headlines( 5274): Breath 60014 latestRequest time : 1450100369984 current time : 1450100429998
,E/SMD     (  235): DCD ON
,E/Watchdog(  775): !@Sync 6
,E/SMD     (  235): DCD ON
,D/AmoledAdjustTimer(  775): prevTemp = 287, currTemp = 285, prevStep = 4, currStep = 4
,I/PowerManagerService(  775): [PWL] Off : 140s ago
,E/SMD     (  235): DCD ON
,D/SSRMv2:SIOP(  775): SIOP:: AP = 300, Delta = 0
,D/BatteryService(  775): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:33, charge type:1, power sharing:false
,D/BatteryService(  775): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  775): mCoverManager.getCoverState() : true
,D/BatteryService(  775): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3229): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3229): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  235): DCD ON
,E/SMD     (  235): DCD ON
,D/AmoledAdjustTimer(  775): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,E/SMD     (  235): DCD ON
,D/SSRMv2:SIOP(  775): SIOP:: AP = 300, Delta = 0
,W/ContextImpl(  775): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/BatteryService(  775): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 284, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:33, charge type:1, power sharing:false
,D/BatteryService(  775): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  775): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
D/UiModeManager(  775): mCoverManager.getCoverState() : true
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,V/HeadsetService( 3229): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3229): Disconnected process message: 10
,E/SMD     (  235): DCD ON
,E/SMD     (  235): DCD ON
,E/SMD     (  235): DCD ON
,D/AmoledAdjustTimer(  775): prevTemp = 285, currTemp = 284, prevStep = 4, currStep = 4
,E/SMD     (  235): DCD ON
,D/SSRMv2:SIOP(  775): SIOP:: AP = 300, Delta = 0
,V/AlarmManager(  775): waitForAlarm result :8
,V/AlarmManager(  775): waitForAlarm result :8
,V/AlarmManager(  775): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1068): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,D/Headlines( 5274): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE
D/BatteryService(  775): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 283, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:33, charge type:1, power sharing:false
D/BatteryService(  775): Sending ACTION_BATTERY_CHANGED.
D/BatteryService(  775): stay LED for fully charged
,D/UiModeManager(  775): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3229): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3229): Disconnected process message: 10
D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,D/Headlines( 5274): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0
,D/Headlines( 5274): Breath 90329 latestRequest time : 1450100369984 current time : 1450100460313
,E/SMD     (  235): DCD ON
,E/Watchdog(  775): !@Sync 7
,E/SMD     (  235): DCD ON
,D/AmoledAdjustTimer(  775): prevTemp = 284, currTemp = 283, prevStep = 4, currStep = 4
,E/SMD     (  235): DCD ON
,D/SSRMv2:SIOP(  775): SIOP:: AP = 300, Delta = 0
,W/ContextImpl(  775): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/BatteryService(  775): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 283, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:31, charge type:1, power sharing:false
,D/BatteryService(  775): Sending ACTION_BATTERY_CHANGED.
E/SMD     (  235): DCD ON
,D/UiModeManager(  775): mCoverManager.getCoverState() : true
,D/BatteryService(  775): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,V/HeadsetService( 3229): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3229): Disconnected process message: 10
,E/SMD     (  235): DCD ON
,D/AmoledAdjustTimer(  775): prevTemp = 283, currTemp = 283, prevStep = 4, currStep = 4
,E/SMD     (  235): DCD ON
,I/PowerManagerService(  775): [PWL] Off : 180s ago
,D/SSRMv2:SIOP(  775): SIOP:: AP = 300, Delta = 0
,E/SMD     (  235): DCD ON
,D/BatteryService(  775): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:29, charge type:1, power sharing:false
,D/BatteryService(  775): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  775): stay LED for fully charged
,D/UiModeManager(  775): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3229): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3229): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  235): DCD ON
,E/SMD     (  235): DCD ON
,D/AmoledAdjustTimer(  775): prevTemp = 283, currTemp = 282, prevStep = 4, currStep = 4
,E/SMD     (  235): DCD ON
,W/ContextImpl(  775): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/SSRMv2:SIOP(  775): SIOP:: AP = 300, Delta = 0
,V/AlarmManager(  775): waitForAlarm result :8
,D/Headlines( 5274): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE
,D/Headlines( 5274): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0
,D/Headlines( 5274): Breath 120042 latestRequest time : 1450100369984 current time : 1450100490026
,D/Headlines( 5274): stop 
,D/Headlines( 5274): Breath.onDestroy : 
,I/ActivityManager(  775): Killing 2905:com.samsung.android.app.assistantmenu/1000 (adj 15): empty #43
,D/BatteryService(  775): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:32, charge type:1, power sharing:false
,D/BatteryService(  775): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  775): stay LED for fully charged
,D/UiModeManager(  775): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
V/HeadsetService( 3229): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 3229): Disconnected process message: 10
,E/SMD     (  235): DCD ON
,E/Watchdog(  775): !@Sync 8
,E/SMD     (  235): DCD ON
,D/AmoledAdjustTimer(  775): prevTemp = 282, currTemp = 282, prevStep = 4, currStep = 4
,E/SMD     (  235): DCD ON
,D/SSRMv2:SIOP(  775): SIOP:: AP = 300, Delta = 0
,E/SMD     (  235): DCD ON
,D/BatteryService(  775): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:32, charge type:1, power sharing:false
,D/BatteryService(  775): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  775): stay LED for fully charged
,D/UiModeManager(  775): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3229): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/HeadsetStateMachine( 3229): Disconnected process message: 10
,E/SMD     (  235): DCD ON
,D/AmoledAdjustTimer(  775): prevTemp = 282, currTemp = 281, prevStep = 4, currStep = 4
,E/SMD     (  235): DCD ON
,W/ContextImpl(  775): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/SSRMv2:SIOP(  775): SIOP:: AP = 300, Delta = 0
,E/SMD     (  235): DCD ON
,D/BatteryService(  775): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:32, charge type:1, power sharing:false
,D/BatteryService(  775): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  775): mCoverManager.getCoverState() : true
,D/BatteryService(  775): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,V/HeadsetService( 3229): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3229): Disconnected process message: 10
,E/SMD     (  235): DCD ON
,E/SMD     (  235): DCD ON
,D/AmoledAdjustTimer(  775): prevTemp = 281, currTemp = 281, prevStep = 4, currStep = 4
,E/SMD     (  235): DCD ON
,D/SSRMv2:SIOP(  775): SIOP:: AP = 300, Delta = 0
,V/AlarmManager(  775): waitForAlarm result :8
,V/AlarmManager(  775): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1068): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,D/BatteryService(  775): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:33, charge type:1, power sharing:false
,D/BatteryService(  775): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  775): stay LED for fully charged
,D/UiModeManager(  775): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3229): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3229): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  235): DCD ON
,I/PowerManagerService(  775): [PWL] Off : 225s ago
,E/Watchdog(  775): !@Sync 9
,E/SMD     (  235): DCD ON
,D/AmoledAdjustTimer(  775): prevTemp = 281, currTemp = 281, prevStep = 4, currStep = 4
,E/SMD     (  235): DCD ON
,W/ContextImpl(  775): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/SSRMv2:SIOP(  775): SIOP:: AP = 300, Delta = 0
,E/SMD     (  235): DCD ON
,D/BatteryService(  775): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 280, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:32, charge type:1, power sharing:false
,D/BatteryService(  775): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  775): mCoverManager.getCoverState() : true
,D/BatteryService(  775): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3229): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3229): Disconnected process message: 10
,E/SMD     (  235): DCD ON
,D/AmoledAdjustTimer(  775): prevTemp = 281, currTemp = 280, prevStep = 4, currStep = 4
,E/SMD     (  235): DCD ON
,E/SMD     (  235): DCD ON
,D/SSRMv2:SIOP(  775): SIOP:: AP = 300, Delta = 0
,D/BatteryService(  775): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 280, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:28, charge type:1, power sharing:false
,D/BatteryService(  775): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  775): stay LED for fully charged
,D/UiModeManager(  775): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3229): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/HeadsetStateMachine( 3229): Disconnected process message: 10
,E/SMD     (  235): DCD ON
,E/SMD     (  235): DCD ON
,D/AmoledAdjustTimer(  775): prevTemp = 280, currTemp = 280, prevStep = 4, currStep = 4
,D/TimaService(  775): TIMA: TimaService scheduler is intialized. 
,D/TimaService(  775): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService(  775): TimaServiceHandler.handleMessage what =1
,I/TLC_TIMA_PKM_initialize(  775): initializing...
,I/TLC_TIMA_PKM_initialize(  775): root = /firmware/image, root_strlen = 15
,I/TLC_TIMA_PKM_initialize(  775): process = tima_pkm, process_strlen = 8
,I/TZ: qc_tlc_communication(  775): root = /firmware/image, root_len = 15
,I/TZ: qc_tlc_communication(  775): process = tima_pkm, process_strlen = 8
,I/TZ: qc_tlc_communication(  775): aligned max_sendmsg_size = 262208 = 0x40040
,I/TZ: qc_tlc_communication(  775): aligned max_recvmsg_size = 262208 = 0x40040
,I/TZ: qc_tlc_communication(  775): max_message_size = 524416 = 0x80080
,D/QSEECOMAPI: (  775): QSEECom_get_handle sb_length = 0x80080
,D/QSEECOMAPI: (  775): App is not loaded in QSEE
,D/QSEECOMAPI: (  775): Loaded image: APP id = 3
,I/TZ: qc_tlc_communication(  775): TIMA: path = /firmware/image, fname = tima_pkm, tzapp is loaded
,I/TLC_TIMA_PKM_initialize(  775): Trustlet response is completed
,E/SMD     (  235): DCD ON
,W/ContextImpl(  775): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/SSRMv2:SIOP(  775): SIOP:: AP = 300, Delta = 0
,E/SMD     (  235): DCD ON
,I/TLC_TIMA_PKM_measure_kernel(  775): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel(  775): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService(  775): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService(  775): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/Watchdog(  775): !@Sync 10
,E/SMD     (  235): DCD ON
,D/AmoledAdjustTimer(  775): prevTemp = 280, currTemp = 280, prevStep = 4, currStep = 4
,E/SMD     (  235): DCD ON
,D/SSRMv2:SIOP(  775): SIOP:: AP = 300, Delta = 0
,E/SMD     (  235): DCD ON
,D/BatteryService(  775): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 280, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:27, charge type:1, power sharing:false
,D/BatteryService(  775): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  775): mCoverManager.getCoverState() : true
,D/BatteryService(  775): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,V/HeadsetService( 3229): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3229): Disconnected process message: 10
,E/SMD     (  235): DCD ON
,D/AmoledAdjustTimer(  775): prevTemp = 280, currTemp = 280, prevStep = 4, currStep = 4
,E/SMD     (  235): DCD ON
,W/ContextImpl(  775): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  235): DCD ON
,D/SSRMv2:SIOP(  775): SIOP:: AP = 300, Delta = 0
,I/PowerManagerService(  775): [PWL] Off : 275s ago
,E/SMD     (  235): DCD ON
,V/AlarmManager(  775): waitForAlarm result :4
,V/AlarmManager(  775): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,I/SELinux ( 5652): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5652):  
,D/BatteryService(  775): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:26, charge type:1, power sharing:false
,D/BatteryService(  775): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  775): stay LED for fully charged
,D/UiModeManager(  775): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,E/SMD     (  235): DCD ON
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3229): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3229): Disconnected process message: 10
,I/SELinux ( 5652): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5652):  
I/SELinux ( 5652):  
,I/SELinux ( 5652): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5652): [DEBUG] seapp_context_lookup: seinfoCategory = default
,E/dalvikvm( 5652): >>>>> Normal User
,E/dalvikvm( 5652): >>>>> com.blurb.checkout [ userId:0 | appId:10075 ]
,E/SELinux ( 5652): [DEBUG] seapp_context_lookup: seinfoCategory = default
,D/TimaKeyStoreProvider( 5652): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5652): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5652): Added TimaKesytore provider
,W/ActivityManager(  775): Permission Denial: getCurrentUser() from pid=5652, uid=10075 requires android.permission.INTERACT_ACROSS_USERS
,I/ActivityManager(  775): Killing 4761:com.sec.android.service.cm/u0a78 (adj 15): empty #43
,D/AmoledAdjustTimer(  775): prevTemp = 280, currTemp = 279, prevStep = 4, currStep = 4
,E/SMD     (  235): DCD ON
,D/SSRMv2:SIOP(  775): SIOP:: AP = 300, Delta = 0
,V/AlarmManager(  775): waitForAlarm result :8
,V/AlarmManager(  775): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1068): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  235): DCD ON
,V/GLSActivity( 1323): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1323): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/Watchdog(  775): !@Sync 11
,D/dalvikvm( 3577): GC_CONCURRENT freed 2753K, 46% free 10438K/19008K, paused 15ms+24ms, total 219ms
,E/SMD     (  235): DCD ON
,D/BatteryService(  775): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:31, charge type:1, power sharing:false
,D/BatteryService(  775): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  775): stay LED for fully charged
,D/UiModeManager(  775): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,V/HeadsetService( 3229): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3229): Disconnected process message: 10
,D/AmoledAdjustTimer(  775): prevTemp = 279, currTemp = 279, prevStep = 4, currStep = 4
,E/SMD     (  235): DCD ON
,W/ContextImpl(  775): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/SSRMv2:SIOP(  775): SIOP:: AP = 300, Delta = 0
,E/SMD     (  235): DCD ON
,E/SMD     (  235): DCD ON
,D/BatteryService(  775): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:28, charge type:1, power sharing:false
,D/BatteryService(  775): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  775): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/BatteryService(  775): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3229): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3229): Disconnected process message: 10
,D/AmoledAdjustTimer(  775): prevTemp = 279, currTemp = 279, prevStep = 4, currStep = 4
,E/SMD     (  235): DCD ON
,E/SMD     (  235): DCD ON
,D/SSRMv2:SIOP(  775): SIOP:: AP = 300, Delta = 0
,E/SMD     (  235): DCD ON
,E/SMD     (  235): DCD ON
,D/BatteryService(  775): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:26, charge type:1, power sharing:false
,D/BatteryService(  775): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  775): stay LED for fully charged
,D/UiModeManager(  775): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3229): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3229): Disconnected process message: 10
D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,D/AmoledAdjustTimer(  775): prevTemp = 279, currTemp = 279, prevStep = 4, currStep = 4
,D/dalvikvm(  775): GC_CONCURRENT freed 3177K, 58% free 23600K/55124K, paused 31ms+86ms, total 686ms
,E/SMD     (  235): DCD ON
,W/ContextImpl(  775): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/SSRMv2:SIOP(  775): SIOP:: AP = 300, Delta = 0
,E/SMD     (  235): DCD ON
,E/Watchdog(  775): !@Sync 12
,E/SMD     (  235): DCD ON
,D/BatteryService(  775): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:24, charge type:1, power sharing:false
,D/BatteryService(  775): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  775): stay LED for fully charged
,D/UiModeManager(  775): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3229): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3229): Disconnected process message: 10
D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,D/AmoledAdjustTimer(  775): prevTemp = 279, currTemp = 279, prevStep = 4, currStep = 4
,E/SMD     (  235): DCD ON
,D/SSRMv2:SIOP(  775): SIOP:: AP = 300, Delta = 0
,E/SMD     (  235): DCD ON
,E/SMD     (  235): DCD ON
,D/BatteryService(  775): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:25, charge type:1, power sharing:false
,D/BatteryService(  775): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  775): stay LED for fully charged
,D/UiModeManager(  775): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3229): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3229): Disconnected process message: 10
D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,D/AmoledAdjustTimer(  775): prevTemp = 279, currTemp = 279, prevStep = 4, currStep = 4
,E/SMD     (  235): DCD ON
,I/PowerManagerService(  775): [PWL] Off : 330s ago
,W/ContextImpl(  775): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  235): DCD ON
,D/SSRMv2:SIOP(  775): SIOP:: AP = 300, Delta = 0
,E/SMD     (  235): DCD ON
,E/SMD     (  235): DCD ON
,D/BatteryService(  775): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:27, charge type:1, power sharing:false
,D/BatteryService(  775): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  775): mCoverManager.getCoverState() : true
,D/BatteryService(  775): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 3229): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 3229): Disconnected process message: 10
,D/AmoledAdjustTimer(  775): prevTemp = 279, currTemp = 278, prevStep = 4, currStep = 4
,I/jxcore-log( 4745): Connected to the server!
I/jxcore-log( 4745): 
,I/chromium( 4745): [INFO:CONSOLE(63)] "logCallback Connected to the server", source: file:///android_asset/www/js/thali_main.js (63)
,E/SMD     (  235): DCD ON
,V/AlarmManager(  775): waitForAlarm result :8
,V/AlarmManager(  775): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1068): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  775): SIOP:: AP = 300, Delta = 0
,E/SMD     (  235): DCD ON
,E/Watchdog(  775): !@Sync 13
,E/SMD     (  235): DCD ON
,D/AmoledAdjustTimer(  775): prevTemp = 278, currTemp = 278, prevStep = 4, currStep = 4
,E/SMD     (  235): DCD ON
,W/ContextImpl(  775): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  235): DCD ON
,D/SSRMv2:SIOP(  775): SIOP:: AP = 300, Delta = 0
,E/SMD     (  235): DCD ON
,D/AmoledAdjustTimer(  775): prevTemp = 278, currTemp = 278, prevStep = 4, currStep = 4
,E/SMD     (  235): DCD ON
,E/SMD     (  235): DCD ON
,D/SSRMv2:SIOP(  775): SIOP:: AP = 300, Delta = 0
,E/SMD     (  235): DCD ON
,E/SMD     (  235): DCD ON
,D/BatteryService(  775): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:25, charge type:1, power sharing:false
,D/BatteryService(  775): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  775): mCoverManager.getCoverState() : true
,D/BatteryService(  775): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3229): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3229): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,D/AmoledAdjustTimer(  775): prevTemp = 278, currTemp = 277, prevStep = 4, currStep = 4
,E/SMD     (  235): DCD ON
,W/ContextImpl(  775): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/SSRMv2:SIOP(  775): SIOP:: AP = 300, Delta = 0
,E/SMD     (  235): DCD ON
,E/Watchdog(  775): !@Sync 14
,E/SMD     (  235): DCD ON
,D/BatteryService(  775): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:28, charge type:1, power sharing:false
,D/BatteryService(  775): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  775): mCoverManager.getCoverState() : true
,D/BatteryService(  775): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3229): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
D/HeadsetStateMachine( 3229): Disconnected process message: 10
,D/AmoledAdjustTimer(  775): prevTemp = 277, currTemp = 277, prevStep = 4, currStep = 4
,E/SMD     (  235): DCD ON
,E/SMD     (  235): DCD ON
,D/SSRMv2:SIOP(  775): SIOP:: AP = 300, Delta = 0
,E/SMD     (  235): DCD ON
,D/BatteryService(  775): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:25, charge type:1, power sharing:false
,D/BatteryService(  775): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  775): stay LED for fully charged
,D/UiModeManager(  775): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3229): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
D/HeadsetStateMachine( 3229): Disconnected process message: 10
,D/AmoledAdjustTimer(  775): prevTemp = 277, currTemp = 277, prevStep = 4, currStep = 4
,E/SMD     (  235): DCD ON
,I/PowerManagerService(  775): [PWL] Off : 390s ago
,W/ContextImpl(  775): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  235): DCD ON
,D/SSRMv2:SIOP(  775): SIOP:: AP = 300, Delta = 0
,E/SMD     (  235): DCD ON
,E/SMD     (  235): DCD ON
,D/AmoledAdjustTimer(  775): prevTemp = 277, currTemp = 277, prevStep = 4, currStep = 4
,E/SMD     (  235): DCD ON
,V/AlarmManager(  775): waitForAlarm result :8
,V/AlarmManager(  775): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1068): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  775): SIOP:: AP = 300, Delta = 0
,E/SMD     (  235): DCD ON
,E/Watchdog(  775): !@Sync 15
,E/SMD     (  235): DCD ON
,D/BatteryService(  775): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:22, charge type:1, power sharing:false
,D/BatteryService(  775): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  775): mCoverManager.getCoverState() : true
,D/BatteryService(  775): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3229): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3229): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,D/AmoledAdjustTimer(  775): prevTemp = 277, currTemp = 276, prevStep = 4, currStep = 4
,E/SMD     (  235): DCD ON
,W/ContextImpl(  775): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  235): DCD ON
,D/SSRMv2:SIOP(  775): SIOP:: AP = 300, Delta = 0
,E/SMD     (  235): DCD ON
,D/BatteryService(  775): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:24, charge type:1, power sharing:false
,D/BatteryService(  775): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  775): mCoverManager.getCoverState() : true
,D/BatteryService(  775): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3229): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3229): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,D/AmoledAdjustTimer(  775): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,E/SMD     (  235): DCD ON
,E/SMD     (  235): DCD ON
,D/SSRMv2:SIOP(  775): SIOP:: AP = 300, Delta = 0
,E/SMD     (  235): DCD ON
,E/SMD     (  235): DCD ON
,D/BatteryService(  775): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:23, charge type:1, power sharing:false
,D/BatteryService(  775): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  775): stay LED for fully charged
,D/UiModeManager(  775): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3229): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3229): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,D/AmoledAdjustTimer(  775): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,E/SMD     (  235): DCD ON
,W/ContextImpl(  775): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  235): DCD ON
,D/SSRMv2:SIOP(  775): SIOP:: AP = 300, Delta = 0
,E/Watchdog(  775): !@Sync 16
,E/SMD     (  235): DCD ON
,D/AmoledAdjustTimer(  775): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,E/SMD     (  235): DCD ON
,E/SMD     (  235): DCD ON
,D/SSRMv2:SIOP(  775): SIOP:: AP = 300, Delta = 0
,E/SMD     (  235): DCD ON
,D/BatteryService(  775): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:24, charge type:1, power sharing:false
,D/BatteryService(  775): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  775): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
D/UiModeManager(  775): mCoverManager.getCoverState() : true
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer(  775): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,V/HeadsetService( 3229): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3229): Disconnected process message: 10
,E/SMD     (  235): DCD ON
,W/ContextImpl(  775): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  235): DCD ON
,D/SSRMv2:SIOP(  775): SIOP:: AP = 300, Delta = 0
,I/PowerManagerService(  775): [PWL] Off : 455s ago
,E/SMD     (  235): DCD ON
,E/SMD     (  235): DCD ON
,D/BatteryService(  775): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:22, charge type:1, power sharing:false
,D/BatteryService(  775): Sending ACTION_BATTERY_CHANGED.
,D/AmoledAdjustTimer(  775): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,D/UiModeManager(  775): mCoverManager.getCoverState() : true
,D/BatteryService(  775): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
V/HeadsetService( 3229): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 3229): Disconnected process message: 10
,E/SMD     (  235): DCD ON
,V/AlarmManager(  775): waitForAlarm result :8
,V/AlarmManager(  775): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1068): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  235): DCD ON
,D/SSRMv2:SIOP(  775): SIOP:: AP = 300, Delta = 0
,E/Watchdog(  775): !@Sync 17
,E/SMD     (  235): DCD ON
,D/AmoledAdjustTimer(  775): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,D/BatteryService(  775): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:24, charge type:1, power sharing:false
,D/BatteryService(  775): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  775): mCoverManager.getCoverState() : true
,D/BatteryService(  775): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3229): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3229): Disconnected process message: 10
,E/SMD     (  235): DCD ON
,W/ContextImpl(  775): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  235): DCD ON
,D/SSRMv2:SIOP(  775): SIOP:: AP = 300, Delta = 0
,E/SMD     (  235): DCD ON
,D/AmoledAdjustTimer(  775): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,E/SMD     (  235): DCD ON
,D/BatteryService(  775): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:21, charge type:1, power sharing:false
,D/BatteryService(  775): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  775): stay LED for fully charged
,D/UiModeManager(  775): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3229): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3229): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  235): DCD ON
,D/SSRMv2:SIOP(  775): SIOP:: AP = 300, Delta = 0
,E/SMD     (  235): DCD ON
,E/SMD     (  235): DCD ON
,D/AmoledAdjustTimer(  775): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,D/BatteryService(  775): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:23, charge type:1, power sharing:false
,D/BatteryService(  775): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  775): stay LED for fully charged
,D/UiModeManager(  775): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3229): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3229): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  235): DCD ON
,W/ContextImpl(  775): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  235): DCD ON
,D/SSRMv2:SIOP(  775): SIOP:: AP = 300, Delta = 0
,E/Watchdog(  775): !@Sync 18
,E/SMD     (  235): DCD ON
,D/AmoledAdjustTimer(  775): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,D/BatteryService(  775): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:20, charge type:1, power sharing:false
,D/BatteryService(  775): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  775): mCoverManager.getCoverState() : true
,D/BatteryService(  775): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3229): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3229): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  235): DCD ON
,E/SMD     (  235): DCD ON
,D/SSRMv2:SIOP(  775): SIOP:: AP = 300, Delta = 0
,E/SMD     (  235): DCD ON
,E/SMD     (  235): DCD ON
D/AmoledAdjustTimer(  775): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,D/BatteryService(  775): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:24, charge type:1, power sharing:false
,D/BatteryService(  775): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  775): stay LED for fully charged
,D/UiModeManager(  775): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3229): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3229): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,W/ContextImpl(  775): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  235): DCD ON
,D/SSRMv2:SIOP(  775): SIOP:: AP = 300, Delta = 0
,E/SMD     (  235): DCD ON
,E/SMD     (  235): DCD ON
,D/AmoledAdjustTimer(  775): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,D/BatteryService(  775): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:18, charge type:1, power sharing:false
,D/BatteryService(  775): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  775): stay LED for fully charged
,D/UiModeManager(  775): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,V/HeadsetService( 3229): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3229): Disconnected process message: 10
,E/SMD     (  235): DCD ON
,V/AlarmManager(  775): waitForAlarm result :8
,V/AlarmManager(  775): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1068): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  235): DCD ON
,I/PowerManagerService(  775): [PWL] Off : 525s ago
,D/SSRMv2:SIOP(  775): SIOP:: AP = 300, Delta = 0
,E/Watchdog(  775): !@Sync 19
,E/SMD     (  235): DCD ON
,D/AmoledAdjustTimer(  775): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,D/BatteryService(  775): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:21, charge type:1, power sharing:false
,D/BatteryService(  775): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  775): stay LED for fully charged
,D/UiModeManager(  775): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
V/HeadsetService( 3229): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 3229): Disconnected process message: 10
,E/SMD     (  235): DCD ON
,W/ContextImpl(  775): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  235): DCD ON
,D/SSRMv2:SIOP(  775): SIOP:: AP = 300, Delta = 0
,E/SMD     (  235): DCD ON
,E/SMD     (  235): DCD ON
,D/AmoledAdjustTimer(  775): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,D/BatteryService(  775): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:24, charge type:1, power sharing:false
,D/BatteryService(  775): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  775): stay LED for fully charged
,D/UiModeManager(  775): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3229): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3229): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  235): DCD ON
,E/SMD     (  235): DCD ON
,D/SSRMv2:SIOP(  775): SIOP:: AP = 300, Delta = 0
,E/SMD     (  235): DCD ON
,D/AmoledAdjustTimer(  775): prevTemp = 276, currTemp = 275, prevStep = 4, currStep = 4
,D/BatteryService(  775): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:22, charge type:1, power sharing:false
,D/BatteryService(  775): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  775): stay LED for fully charged
,D/UiModeManager(  775): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3229): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3229): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,D/TimaService(  775): TIMA: TimaService scheduler is intialized. 
,D/TimaService(  775): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService(  775): TimaServiceHandler.handleMessage what =1
,E/SMD     (  235): DCD ON
,W/ContextImpl(  775): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  235): DCD ON
,I/TLC_TIMA_PKM_measure_kernel(  775): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel(  775): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService(  775): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService(  775): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/SSRMv2:SIOP(  775): SIOP:: AP = 300, Delta = 0
,E/Watchdog(  775): !@Sync 20
,E/SMD     (  235): DCD ON
,D/AmoledAdjustTimer(  775): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,D/BatteryService(  775): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:21, charge type:1, power sharing:false
,D/BatteryService(  775): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  775): stay LED for fully charged
,D/UiModeManager(  775): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3229): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3229): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  235): DCD ON
,E/SMD     (  235): DCD ON
,D/SSRMv2:SIOP(  775): SIOP:: AP = 300, Delta = 0
,E/SMD     (  235): DCD ON
,E/SMD     (  235): DCD ON
,D/AmoledAdjustTimer(  775): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,D/BatteryService(  775): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:23, charge type:1, power sharing:false
,D/BatteryService(  775): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  775): stay LED for fully charged
,D/UiModeManager(  775): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3229): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3229): Disconnected process message: 10
D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,W/ContextImpl(  775): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  235): DCD ON
,E/SMD     (  235): DCD ON
,D/SSRMv2:SIOP(  775): SIOP:: AP = 300, Delta = 0
,E/SMD     (  235): DCD ON
,D/AmoledAdjustTimer(  775): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,D/BatteryService(  775): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:19, charge type:1, power sharing:false
,D/BatteryService(  775): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  775): mCoverManager.getCoverState() : true
,D/BatteryService(  775): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3229): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3229): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  235): DCD ON
,V/AlarmManager(  775): waitForAlarm result :8
,V/AlarmManager(  775): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1068): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  235): DCD ON
,D/SSRMv2:SIOP(  775): SIOP:: AP = 300, Delta = 0
,E/Watchdog(  775): !@Sync 21
,E/SMD     (  235): DCD ON
,D/AmoledAdjustTimer(  775): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,D/BatteryService(  775): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:20, charge type:1, power sharing:false
,D/BatteryService(  775): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  775): mCoverManager.getCoverState() : true
,D/BatteryService(  775): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3229): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3229): Disconnected process message: 10
D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  235): DCD ON
,E/SMD     (  235): DCD ON
,D/SSRMv2:SIOP(  775): SIOP:: AP = 300, Delta = 0
,E/SMD     (  235): DCD ON
,E/SMD     (  235): DCD ON
,D/AmoledAdjustTimer(  775): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,I/PowerManagerService(  775): [PWL] Off : 600s ago
,D/BatteryService(  775): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:19, charge type:1, power sharing:false
,D/BatteryService(  775): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  775): stay LED for fully charged
,D/UiModeManager(  775): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3229): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3229): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  235): DCD ON
,E/SMD     (  235): DCD ON
,D/SSRMv2:SIOP(  775): SIOP:: AP = 300, Delta = 0
,E/SMD     (  235): DCD ON
,D/AmoledAdjustTimer(  775): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,D/BatteryService(  775): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:22, charge type:1, power sharing:false
,D/BatteryService(  775): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  775): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
D/UiModeManager(  775): mCoverManager.getCoverState() : true
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3229): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3229): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  235): DCD ON
,E/SMD     (  235): DCD ON
,D/SSRMv2:SIOP(  775): SIOP:: AP = 300, Delta = 0
,E/Watchdog(  775): !@Sync 22
,E/SMD     (  235): DCD ON
,D/AmoledAdjustTimer(  775): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,D/BatteryService(  775): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:24, charge type:1, power sharing:false
,D/BatteryService(  775): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  775): stay LED for fully charged
,D/UiModeManager(  775): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,E/SMD     (  235): DCD ON
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3229): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3229): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  235): DCD ON
,D/SSRMv2:SIOP(  775): SIOP:: AP = 300, Delta = 0
,E/SMD     (  235): DCD ON
,E/SMD     (  235): DCD ON
,D/AmoledAdjustTimer(  775): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,D/BatteryService(  775): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:19, charge type:1, power sharing:false
,D/BatteryService(  775): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  775): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
D/UiModeManager(  775): mCoverManager.getCoverState() : true
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3229): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3229): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  235): DCD ON
,E/SMD     (  235): DCD ON
,D/SSRMv2:SIOP(  775): SIOP:: AP = 300, Delta = 0
,E/SMD     (  235): DCD ON
,D/AmoledAdjustTimer(  775): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,D/BatteryService(  775): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:22, charge type:1, power sharing:false
,D/BatteryService(  775): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  775): stay LED for fully charged
,D/UiModeManager(  775): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3229): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3229): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  235): DCD ON
,V/AlarmManager(  775): waitForAlarm result :8
,V/AlarmManager(  775): ClockReceiver onReceive() ACTION_TIME_TICK
,V/AlarmManager(  775): ___SyncScheduler (v3) ACTIVATED___
,V/AlarmManager(  775): <AppSync3 Whitelist>
,V/AlarmManager(  775): (AppSync) ### 0 added ###
D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.TIME_TICK
D/KeyguardUpdateMonitor( 1068): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  235): DCD ON
,E/Watchdog(  775): !@Sync 23
,D/SSRMv2:SIOP(  775): SIOP:: AP = 300, Delta = 0
,E/SMD     (  235): DCD ON
,D/AmoledAdjustTimer(  775): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,E/SMD     (  235): DCD ON
,D/BatteryService(  775): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:17, charge type:1, power sharing:false
,D/BatteryService(  775): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  775): stay LED for fully charged
,D/UiModeManager(  775): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3229): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3229): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  235): DCD ON
,E/SMD     (  235): DCD ON
,D/SSRMv2:SIOP(  775): SIOP:: AP = 300, Delta = 0
,E/SMD     (  235): DCD ON
,D/AmoledAdjustTimer(  775): prevTemp = 275, currTemp = 274, prevStep = 4, currStep = 4
,D/BatteryService(  775): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:19, charge type:1, power sharing:false
,D/BatteryService(  775): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  775): mCoverManager.getCoverState() : true
,D/BatteryService(  775): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3229): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3229): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  235): DCD ON
,E/SMD     (  235): DCD ON
,D/SSRMv2:SIOP(  775): SIOP:: AP = 300, Delta = 0
,E/SMD     (  235): DCD ON
,D/AmoledAdjustTimer(  775): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,D/BatteryService(  775): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:20, charge type:1, power sharing:false
,D/BatteryService(  775): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  775): stay LED for fully charged
,D/UiModeManager(  775): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3229): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3229): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  235): DCD ON
,E/SMD     (  235): DCD ON
,E/Watchdog(  775): !@Sync 24
,D/SSRMv2:SIOP(  775): SIOP:: AP = 300, Delta = 0
,E/SMD     (  235): DCD ON
,D/AmoledAdjustTimer(  775): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,I/PowerManagerService(  775): [PWL] Off : 680s ago
,E/SMD     (  235): DCD ON
,D/BatteryService(  775): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:18, charge type:1, power sharing:false
,D/BatteryService(  775): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  775): mCoverManager.getCoverState() : true
,D/BatteryService(  775): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3229): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3229): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  235): DCD ON
,E/SMD     (  235): DCD ON
,D/SSRMv2:SIOP(  775): SIOP:: AP = 300, Delta = 0
,E/SMD     (  235): DCD ON
,D/AmoledAdjustTimer(  775): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,D/BatteryService(  775): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:19, charge type:1, power sharing:false
,D/BatteryService(  775): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  775): stay LED for fully charged
,D/UiModeManager(  775): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3229): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3229): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  235): DCD ON
,E/SMD     (  235): DCD ON
,D/SSRMv2:SIOP(  775): SIOP:: AP = 300, Delta = 0
,E/SMD     (  235): DCD ON
,D/AmoledAdjustTimer(  775): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,D/BatteryService(  775): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:17, charge type:1, power sharing:false
,D/BatteryService(  775): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  775): stay LED for fully charged
,D/UiModeManager(  775): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3229): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3229): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  235): DCD ON
,V/AlarmManager(  775): waitForAlarm result :8
,V/AlarmManager(  775): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1068): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  235): DCD ON
,E/Watchdog(  775): !@Sync 25
,D/SSRMv2:SIOP(  775): SIOP:: AP = 300, Delta = 0
,E/SMD     (  235): DCD ON
,D/AmoledAdjustTimer(  775): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,E/SMD     (  235): DCD ON
,E/SMD     (  235): DCD ON
,E/SMD     (  235): DCD ON
,D/SSRMv2:SIOP(  775): SIOP:: AP = 300, Delta = 0
,D/dalvikvm(  775): GC_CONCURRENT freed 3486K, 57% free 23543K/54572K, paused 29ms+51ms, total 657ms
,E/SMD     (  235): DCD ON
,D/AmoledAdjustTimer(  775): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,E/SMD     (  235): DCD ON
,E/SMD     (  235): DCD ON
,D/SSRMv2:SIOP(  775): SIOP:: AP = 300, Delta = 0
,E/SMD     (  235): DCD ON
,D/AmoledAdjustTimer(  775): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,D/BatteryService(  775): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:13, charge type:1, power sharing:false
,D/BatteryService(  775): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  775): stay LED for fully charged
,D/UiModeManager(  775): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3229): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3229): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  235): DCD ON
,E/SMD     (  235): DCD ON
,E/Watchdog(  775): !@Sync 26
,E/SMD     (  235): DCD ON
,D/SSRMv2:SIOP(  775): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  775): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,E/SMD     (  235): DCD ON
,D/BatteryService(  775): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:16, charge type:1, power sharing:false
,D/BatteryService(  775): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  775): stay LED for fully charged
,D/UiModeManager(  775): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3229): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3229): Disconnected process message: 10
D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  235): DCD ON
,E/SMD     (  235): DCD ON
,D/SSRMv2:SIOP(  775): SIOP:: AP = 300, Delta = 0
,E/SMD     (  235): DCD ON
,D/AmoledAdjustTimer(  775): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,D/BatteryService(  775): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:21, charge type:1, power sharing:false
,D/BatteryService(  775): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  775): mCoverManager.getCoverState() : true
,D/BatteryService(  775): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3229): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3229): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  235): DCD ON
,E/SMD     (  235): DCD ON
,D/SSRMv2:SIOP(  775): SIOP:: AP = 300, Delta = 0
,E/SMD     (  235): DCD ON
,D/AmoledAdjustTimer(  775): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,D/BatteryService(  775): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:15, charge type:1, power sharing:false
,D/BatteryService(  775): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  775): stay LED for fully charged
,D/UiModeManager(  775): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3229): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3229): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  235): DCD ON
,V/AlarmManager(  775): waitForAlarm result :8
,V/AlarmManager(  775): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1068): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  235): DCD ON
,I/PowerManagerService(  775): [PWL] Off : 765s ago
,E/Watchdog(  775): !@Sync 27
,E/SMD     (  235): DCD ON
,D/SSRMv2:SIOP(  775): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  775): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,E/SMD     (  235): DCD ON
,D/BatteryService(  775): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:16, charge type:1, power sharing:false
,D/BatteryService(  775): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  775): mCoverManager.getCoverState() : true
,D/BatteryService(  775): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3229): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3229): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  235): DCD ON
,E/SMD     (  235): DCD ON
,D/SSRMv2:SIOP(  775): SIOP:: AP = 300, Delta = 0
,E/SMD     (  235): DCD ON
,D/AmoledAdjustTimer(  775): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,D/BatteryService(  775): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:14, charge type:1, power sharing:false
,D/BatteryService(  775): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  775): stay LED for fully charged
,D/UiModeManager(  775): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3229): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3229): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  235): DCD ON
,E/SMD     (  235): DCD ON
,D/SSRMv2:SIOP(  775): SIOP:: AP = 300, Delta = 0
,E/SMD     (  235): DCD ON
,D/AmoledAdjustTimer(  775): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,D/BatteryService(  775): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:19, charge type:1, power sharing:false
,D/BatteryService(  775): Sending ACTION_BATTERY_CHANGED.
E/SMD     (  235): DCD ON
,D/UiModeManager(  775): mCoverManager.getCoverState() : true
,D/BatteryService(  775): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3229): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3229): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  235): DCD ON
,E/Watchdog(  775): !@Sync 28
,E/SMD     (  235): DCD ON
,D/SSRMv2:SIOP(  775): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  775): prevTemp = 274, currTemp = 273, prevStep = 4, currStep = 4
,E/SMD     (  235): DCD ON
,D/BatteryService(  775): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:16, charge type:1, power sharing:false
,D/BatteryService(  775): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  775): stay LED for fully charged
,D/UiModeManager(  775): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3229): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3229): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  235): DCD ON
,E/SMD     (  235): DCD ON
,D/SSRMv2:SIOP(  775): SIOP:: AP = 300, Delta = 0
,E/SMD     (  235): DCD ON
,D/AmoledAdjustTimer(  775): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,D/BatteryService(  775): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:15, charge type:1, power sharing:false
,D/BatteryService(  775): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  775): stay LED for fully charged
,D/UiModeManager(  775): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3229): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3229): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  235): DCD ON
,E/SMD     (  235): DCD ON
,E/SMD     (  235): DCD ON
,D/SSRMv2:SIOP(  775): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  775): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,E/SMD     (  235): DCD ON
,V/AlarmManager(  775): waitForAlarm result :8
,V/AlarmManager(  775): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1068): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,D/BatteryService(  775): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:19, charge type:1, power sharing:false
,D/BatteryService(  775): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  775): stay LED for fully charged
,D/UiModeManager(  775): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3229): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3229): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  235): DCD ON
,E/Watchdog(  775): !@Sync 29
,E/SMD     (  235): DCD ON
,D/SSRMv2:SIOP(  775): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  775): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,E/SMD     (  235): DCD ON
,D/BatteryService(  775): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:13, charge type:1, power sharing:false
,D/BatteryService(  775): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  775): stay LED for fully charged
,D/UiModeManager(  775): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3229): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3229): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  235): DCD ON
,E/SMD     (  235): DCD ON
,D/SSRMv2:SIOP(  775): SIOP:: AP = 300, Delta = 0
,E/SMD     (  235): DCD ON
,D/AmoledAdjustTimer(  775): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,E/SMD     (  235): DCD ON
,D/BatteryService(  775): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:14, charge type:1, power sharing:false
,D/BatteryService(  775): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  775): stay LED for fully charged
,D/UiModeManager(  775): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3229): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3229): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  235): DCD ON
,E/SMD     (  235): DCD ON
,D/SSRMv2:SIOP(  775): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  775): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,D/TimaService(  775): TIMA: TimaService scheduler is intialized. 
,D/TimaService(  775): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService(  775): TimaServiceHandler.handleMessage what =1
,E/SMD     (  235): DCD ON
,D/BatteryService(  775): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:17, charge type:1, power sharing:false
,D/BatteryService(  775): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  775): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/BatteryService(  775): stay LED for fully charged
D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3229): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 3229): Disconnected process message: 10
,E/SMD     (  235): DCD ON
,I/PowerManagerService(  775): [PWL] Off : 855s ago
,I/PowerManagerService(  775): [PWL]   PowerManagerService.WakeLocks: ref count=1
,I/PowerManagerService(  775): [PWL]     mWakeLockSummary : 0x1
,I/PowerManagerService(  775): [PWL]       PARTIAL_WAKE_LOCK              'TimaService' (uid=1000, pid=775, ws=null) (elapsedTime=4013)
,I/TLC_TIMA_PKM_measure_kernel(  775): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel(  775): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService(  775): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService(  775): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/Watchdog(  775): !@Sync 30
,E/SMD     (  235): DCD ON
,D/SSRMv2:SIOP(  775): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  775): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,E/SMD     (  235): DCD ON
,D/BatteryService(  775): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:18, charge type:1, power sharing:false
,D/BatteryService(  775): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  775): stay LED for fully charged
,D/UiModeManager(  775): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3229): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3229): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  235): DCD ON
,E/SMD     (  235): DCD ON
,D/SSRMv2:SIOP(  775): SIOP:: AP = 300, Delta = 0
,E/SMD     (  235): DCD ON
,D/AmoledAdjustTimer(  775): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,E/SMD     (  235): DCD ON
,D/BatteryService(  775): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:16, charge type:1, power sharing:false
,D/BatteryService(  775): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  775): stay LED for fully charged
,D/UiModeManager(  775): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3229): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3229): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  235): DCD ON
,E/SMD     (  235): DCD ON
,D/SSRMv2:SIOP(  775): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  775): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,E/SMD     (  235): DCD ON
,V/AlarmManager(  775): waitForAlarm result :8
,V/AlarmManager(  775): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1068): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,D/BatteryService(  775): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:13, charge type:1, power sharing:false
,D/BatteryService(  775): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  775): mCoverManager.getCoverState() : true
,D/BatteryService(  775): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3229): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3229): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  235): DCD ON
,E/Watchdog(  775): !@Sync 31
,E/SMD     (  235): DCD ON
,D/SSRMv2:SIOP(  775): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  775): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,E/SMD     (  235): DCD ON
,E/SMD     (  235): DCD ON
,E/SMD     (  235): DCD ON
,D/SSRMv2:SIOP(  775): SIOP:: AP = 300, Delta = 0
,E/SMD     (  235): DCD ON
,D/AmoledAdjustTimer(  775): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,E/SMD     (  235): DCD ON
,D/BatteryService(  775): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:12, charge type:1, power sharing:false
,D/BatteryService(  775): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  775): stay LED for fully charged
,D/UiModeManager(  775): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3229): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3229): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  235): DCD ON
,E/SMD     (  235): DCD ON
,D/SSRMv2:SIOP(  775): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  775): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,E/SMD     (  235): DCD ON
,D/BatteryService(  775): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:18, charge type:1, power sharing:false
,D/BatteryService(  775): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  775): stay LED for fully charged
,D/UiModeManager(  775): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3229): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3229): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  235): DCD ON
,E/Watchdog(  775): !@Sync 32
,E/SMD     (  235): DCD ON
,D/SSRMv2:SIOP(  775): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  775): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,E/SMD     (  235): DCD ON
,E/SMD     (  235): DCD ON
,D/BatteryService(  775): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:12, charge type:1, power sharing:false
,D/BatteryService(  775): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  775): stay LED for fully charged
,D/UiModeManager(  775): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3229): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3229): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  235): DCD ON
,E/SMD     (  235): DCD ON
,D/SSRMv2:SIOP(  775): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  775): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,E/SMD     (  235): DCD ON
,D/BatteryService(  775): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:15, charge type:1, power sharing:false
,D/BatteryService(  775): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  775): stay LED for fully charged
,D/UiModeManager(  775): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3229): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3229): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  235): DCD ON
,E/SMD     (  235): DCD ON
,D/SSRMv2:SIOP(  775): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  775): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,E/SMD     (  235): DCD ON
,V/AlarmManager(  775): waitForAlarm result :8
,V/AlarmManager(  775): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1068): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  235): DCD ON
,E/Watchdog(  775): !@Sync 33
,E/SMD     (  235): DCD ON
,I/PowerManagerService(  775): [PWL] Off : 950s ago
,D/SSRMv2:SIOP(  775): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  775): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,E/SMD     (  235): DCD ON
,E/SMD     (  235): DCD ON
,D/BatteryService(  775): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:15, charge type:1, power sharing:false
,D/BatteryService(  775): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  775): stay LED for fully charged
,D/UiModeManager(  775): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3229): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3229): Disconnected process message: 10
,E/SMD     (  235): DCD ON
,E/SMD     (  235): DCD ON
,D/SSRMv2:SIOP(  775): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  775): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,E/SMD     (  235): DCD ON
,D/BatteryService(  775): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:13, charge type:1, power sharing:false
,D/BatteryService(  775): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  775): mCoverManager.getCoverState() : true
,D/BatteryService(  775): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3229): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3229): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  235): DCD ON
,E/SMD     (  235): DCD ON
,D/SSRMv2:SIOP(  775): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  775): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,E/SMD     (  235): DCD ON
,V/AlarmManager(  775): waitForAlarm result :4
,I/SensorManagerA(  775): getReportingMode :: sensor.mType = 5
,D/Sensors (  775): LightSensor setDelay = 200000000
,D/Sensors (  775): LightSensor setSensorDelay = 200000000
,D/LightsService(  775): [api] onReceive : SvcLEDReceiver re-enables LightSenor and sends MSG_FORCEDSVCLEDTASK
D/Sensors (  775): Light sensor flush: not enabled 0
D/Sensors (  775): LightSensor enable = 1
D/Sensors (  775): LightSensor enableSensor = 1
,D/SensorManager(  775): registerListener :: 16, CM36686 Light Sensor, 200000, 0,  
,E/SMD     (  235): DCD ON
,V/AlarmManager(  775): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,V/AlarmManager(  775): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,D/BatteryService(  775): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:15, charge type:1, power sharing:false
,D/BatteryService(  775): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  775): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3229): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3229): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,D/LightsService(  775): [SvcLED]  onSensorChanged::light value = 10
,D/BatteryService(  775): stay LED for fully charged
,D/Sensors (  775): LightSensor enable = 0
,D/Sensors (  775): LightSensor enableSensor = 0
,D/SensorManager(  775): unregisterListener ::   
D/LightsService(  775): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,D/dalvikvm( 1804): GC_CONCURRENT freed 1747K, 35% free 12397K/19008K, paused 34ms+15ms, total 677ms
,I/EventLogService( 1804): Aggregate from 1450098989960 (log), 1450098989960 (data)
D/ConnectivityService(  775): handleInetConditionHoldEnd: net=1, condition=100, published condition=100
D/STATUSBAR-NetworkController_dual( 1068): onReceive() - CONNECTIVITY_ACTION, INET_CONDITION_ACTION
D/StatusBar.NetworkController_dual( 1068): mMobileLabelViews start
D/StatusBar.NetworkController_dual( 1068): mMobileLabelViews set mobileLabel[SIM_0] =
D/StatusBar.NetworkController_dual( 1068): mMobileLabelViews GONE
D/StatusBar.NetworkController_dual( 1068): mMobileLabelViews2 set mobileLabel[SIM_1] =
D/StatusBar.NetworkController_dual( 1068): mMobileLabelViews2 GONE
D/StatusBar.NetworkController_dual( 1068): mSingleMobileLabelViews set : simMode = 0
D/StatusBar.NetworkController_dual( 1068): mSingleMobileLabelViews set as slot1`s
,D/GetConfigurationSnapshotOperation( 1219): no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,I/PhenotypeFlagCommitter( 1219): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,I/GoogleURLConnFactory( 1219): Using platform SSLCertificateSocketFactory
,D/LocationManagerService(  775): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/dalvikvm( 1219): GC_CONCURRENT freed 1953K, 38% free 11939K/19008K, paused 6ms+8ms, total 55ms
,E/Watchdog(  775): !@Sync 34
,E/SMD     (  235): DCD ON
,D/SSRMv2:SIOP(  775): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  775): prevTemp = 273, currTemp = 272, prevStep = 4, currStep = 4
,E/SMD     (  235): DCD ON
,E/SMD     (  235): DCD ON
,D/BatteryService(  775): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:17, charge type:1, power sharing:false
,D/BatteryService(  775): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  775): stay LED for fully charged
,D/UiModeManager(  775): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3229): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3229): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  235): DCD ON
,E/SMD     (  235): DCD ON
,D/SSRMv2:SIOP(  775): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  775): prevTemp = 272, currTemp = 273, prevStep = 4, currStep = 4
,E/SMD     (  235): DCD ON
,D/BatteryService(  775): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:14, charge type:1, power sharing:false
,D/BatteryService(  775): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  775): stay LED for fully charged
,D/UiModeManager(  775): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3229): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3229): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  235): DCD ON
,E/SMD     (  235): DCD ON
,D/SSRMv2:SIOP(  775): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  775): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,E/SMD     (  235): DCD ON
,V/AlarmManager(  775): waitForAlarm result :8
,V/AlarmManager(  775): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1068): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  235): DCD ON
,D/BatteryService(  775): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:16, charge type:1, power sharing:false
,D/BatteryService(  775): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  775): stay LED for fully charged
,D/UiModeManager(  775): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3229): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3229): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,E/Watchdog(  775): !@Sync 35
,E/SMD     (  235): DCD ON
,D/SSRMv2:SIOP(  775): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  775): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
E/SMD     (  235): DCD ON
,E/SMD     (  235): DCD ON
,D/BatteryService(  775): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:17, charge type:1, power sharing:false
,D/BatteryService(  775): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  775): stay LED for fully charged
,D/UiModeManager(  775): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3229): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3229): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  235): DCD ON
,E/SMD     (  235): DCD ON
,D/SSRMv2:SIOP(  775): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  775): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,E/SMD     (  235): DCD ON
,D/BatteryService(  775): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:12, charge type:1, power sharing:false
,D/BatteryService(  775): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  775): stay LED for fully charged
,D/UiModeManager(  775): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3229): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3229): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  235): DCD ON
,E/SMD     (  235): DCD ON
,D/SSRMv2:SIOP(  775): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  775): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,E/SMD     (  235): DCD ON
,E/SMD     (  235): DCD ON
,D/BatteryService(  775): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:11, charge type:1, power sharing:false
,D/BatteryService(  775): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  775): mCoverManager.getCoverState() : true
,D/BatteryService(  775): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3229): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3229): Disconnected process message: 10
D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,E/Watchdog(  775): !@Sync 36
,E/SMD     (  235): DCD ON
,E/SMD     (  235): DCD ON
,D/SSRMv2:SIOP(  775): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  775): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,E/SMD     (  235): DCD ON
,D/BatteryService(  775): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:12, charge type:1, power sharing:false
,D/BatteryService(  775): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  775): mCoverManager.getCoverState() : true
,D/BatteryService(  775): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3229): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3229): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  235): DCD ON
,E/SMD     (  235): DCD ON
,I/PowerManagerService(  775): [PWL] Off : 1050s ago
,D/SSRMv2:SIOP(  775): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  775): prevTemp = 273, currTemp = 272, prevStep = 4, currStep = 4
,E/SMD     (  235): DCD ON
,D/BatteryService(  775): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:13, charge type:1, power sharing:false
,D/BatteryService(  775): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  775): stay LED for fully charged
,D/UiModeManager(  775): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
V/HeadsetService( 3229): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 3229): Disconnected process message: 10
,E/SMD     (  235): DCD ON
,E/SMD     (  235): DCD ON
,D/SSRMv2:SIOP(  775): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  775): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,E/SMD     (  235): DCD ON
,V/AlarmManager(  775): waitForAlarm result :8
,V/AlarmManager(  775): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1068): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  235): DCD ON
,D/BatteryService(  775): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:12, charge type:1, power sharing:false
,D/BatteryService(  775): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  775): mCoverManager.getCoverState() : true
,D/BatteryService(  775): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3229): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3229): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,E/Watchdog(  775): !@Sync 37
,E/SMD     (  235): DCD ON
,E/SMD     (  235): DCD ON
,D/SSRMv2:SIOP(  775): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  775): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,E/SMD     (  235): DCD ON
,D/BatteryService(  775): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:15, charge type:1, power sharing:false
,D/BatteryService(  775): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  775): stay LED for fully charged
,D/UiModeManager(  775): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3229): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3229): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  235): DCD ON
,E/SMD     (  235): DCD ON
,D/SSRMv2:SIOP(  775): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  775): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,E/SMD     (  235): DCD ON
,E/SMD     (  235): DCD ON
,E/SMD     (  235): DCD ON
,D/SSRMv2:SIOP(  775): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  775): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,E/SMD     (  235): DCD ON
,D/dalvikvm(  775): GC_CONCURRENT freed 3382K, 57% free 23574K/54572K, paused 48ms+38ms, total 637ms
,E/SMD     (  235): DCD ON
,D/BatteryService(  775): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:14, charge type:1, power sharing:false
,D/BatteryService(  775): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  775): mCoverManager.getCoverState() : true
,D/BatteryService(  775): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3229): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3229): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,E/Watchdog(  775): !@Sync 38
,E/SMD     (  235): DCD ON
,E/SMD     (  235): DCD ON
,D/SSRMv2:SIOP(  775): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  775): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,E/SMD     (  235): DCD ON
,E/SMD     (  235): DCD ON
,E/SMD     (  235): DCD ON
,D/SSRMv2:SIOP(  775): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  775): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,E/SMD     (  235): DCD ON
,D/BatteryService(  775): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:10, charge type:1, power sharing:false
,D/BatteryService(  775): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  775): stay LED for fully charged
,E/SMD     (  235): DCD ON
D/UiModeManager(  775): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3229): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3229): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  235): DCD ON
,E/SMD     (  235): DCD ON
,D/SSRMv2:SIOP(  775): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  775): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,V/AlarmManager(  775): waitForAlarm result :8
,V/AlarmManager(  775): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1068): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  235): DCD ON
,D/BatteryService(  775): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:11, charge type:1, power sharing:false
,D/BatteryService(  775): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  775): stay LED for fully charged
,D/UiModeManager(  775): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3229): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3229): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,E/Watchdog(  775): !@Sync 39
,E/SMD     (  235): DCD ON
,E/SMD     (  235): DCD ON
,D/SSRMv2:SIOP(  775): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  775): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,E/SMD     (  235): DCD ON
,D/BatteryService(  775): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:16, charge type:1, power sharing:false
,D/BatteryService(  775): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  775): stay LED for fully charged
,D/UiModeManager(  775): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3229): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3229): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  235): DCD ON
,E/SMD     (  235): DCD ON
,D/SSRMv2:SIOP(  775): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  775): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,E/SMD     (  235): DCD ON
,E/SMD     (  235): DCD ON
,D/BatteryService(  775): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:12, charge type:1, power sharing:false
,D/BatteryService(  775): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  775): stay LED for fully charged
,D/UiModeManager(  775): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3229): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3229): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  235): DCD ON
,D/TimaService(  775): TIMA: TimaService scheduler is intialized. 
,D/TimaService(  775): TimaServiceHandler.handleMessage what =1
,D/TimaService(  775): TIMA: checkEvent, operation: 50000 subject: 10000
,E/SMD     (  235): DCD ON
,D/SSRMv2:SIOP(  775): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  775): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,I/PowerManagerService(  775): [PWL] Off : 1155s ago
,I/PowerManagerService(  775): [PWL]   PowerManagerService.WakeLocks: ref count=1
,I/PowerManagerService(  775): [PWL]     mWakeLockSummary : 0x1
,I/PowerManagerService(  775): [PWL]       PARTIAL_WAKE_LOCK              'TimaService' (uid=1000, pid=775, ws=null) (elapsedTime=4026)
,E/SMD     (  235): DCD ON
,I/TLC_TIMA_PKM_measure_kernel(  775): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel(  775): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService(  775): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService(  775): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/BatteryService(  775): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:11, charge type:1, power sharing:false
,D/BatteryService(  775): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  775): stay LED for fully charged
,D/UiModeManager(  775): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3229): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3229): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,E/Watchdog(  775): !@Sync 40
,E/SMD     (  235): DCD ON
,E/SMD     (  235): DCD ON
,D/SSRMv2:SIOP(  775): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  775): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,E/SMD     (  235): DCD ON
,D/BatteryService(  775): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:13, charge type:1, power sharing:false
,D/BatteryService(  775): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  775): stay LED for fully charged
,D/UiModeManager(  775): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3229): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3229): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  235): DCD ON
,E/SMD     (  235): DCD ON
,D/SSRMv2:SIOP(  775): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  775): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,E/SMD     (  235): DCD ON
,E/SMD     (  235): DCD ON
,D/BatteryService(  775): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:12, charge type:1, power sharing:false
,D/BatteryService(  775): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  775): stay LED for fully charged
,D/UiModeManager(  775): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3229): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3229): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  235): DCD ON
,E/SMD     (  235): DCD ON
,D/SSRMv2:SIOP(  775): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  775): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,V/AlarmManager(  775): waitForAlarm result :8
,V/AlarmManager(  775): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1068): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  235): DCD ON
,D/BatteryService(  775): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:8, charge type:1, power sharing:false
,D/BatteryService(  775): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  775): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
D/BatteryService(  775): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3229): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3229): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,E/Watchdog(  775): !@Sync 41
,E/SMD     (  235): DCD ON
,E/SMD     (  235): DCD ON
,D/SSRMv2:SIOP(  775): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  775): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,E/SMD     (  235): DCD ON
,D/BatteryService(  775): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:14, charge type:1, power sharing:false
,D/BatteryService(  775): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  775): mCoverManager.getCoverState() : true
,D/BatteryService(  775): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3229): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3229): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  235): DCD ON
,E/SMD     (  235): DCD ON
,D/SSRMv2:SIOP(  775): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  775): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,E/SMD     (  235): DCD ON
,E/SMD     (  235): DCD ON
,D/BatteryService(  775): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:10, charge type:1, power sharing:false
,D/BatteryService(  775): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  775): mCoverManager.getCoverState() : true
,D/BatteryService(  775): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3229): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3229): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  235): DCD ON
,E/SMD     (  235): DCD ON
,D/SSRMv2:SIOP(  775): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  775): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,E/SMD     (  235): DCD ON
,D/BatteryService(  775): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:12, charge type:1, power sharing:false
,D/BatteryService(  775): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  775): stay LED for fully charged
,D/UiModeManager(  775): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,E/Watchdog(  775): !@Sync 42
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3229): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3229): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  235): DCD ON
,E/SMD     (  235): DCD ON
,D/SSRMv2:SIOP(  775): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  775): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,E/SMD     (  235): DCD ON
,D/BatteryService(  775): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:10, charge type:1, power sharing:false
,D/BatteryService(  775): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  775): mCoverManager.getCoverState() : true
,D/BatteryService(  775): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3229): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3229): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  235): DCD ON
,E/SMD     (  235): DCD ON
,E/SMD     (  235): DCD ON
,D/SSRMv2:SIOP(  775): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  775): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,E/SMD     (  235): DCD ON
,D/BatteryService(  775): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:14, charge type:1, power sharing:false
,D/BatteryService(  775): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  775): stay LED for fully charged
,D/UiModeManager(  775): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,V/HeadsetService( 3229): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3229): Disconnected process message: 10
,E/SMD     (  235): DCD ON
,E/SMD     (  235): DCD ON
,V/AlarmManager(  775): waitForAlarm result :8
,V/AlarmManager(  775): ClockReceiver onReceive() ACTION_TIME_TICK
,V/AlarmManager(  775): ___SyncScheduler (v3) ACTIVATED___
,V/AlarmManager(  775): <AppSync3 Whitelist>
,V/AlarmManager(  775): (AppSync) ### 0 added ###
D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.TIME_TICK
D/KeyguardUpdateMonitor( 1068): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  775): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  775): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,E/SMD     (  235): DCD ON
,E/Watchdog(  775): !@Sync 43
,D/BatteryService(  775): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:11, charge type:1, power sharing:false
,D/BatteryService(  775): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  775): stay LED for fully charged
,D/UiModeManager(  775): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3229): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
D/HeadsetStateMachine( 3229): Disconnected process message: 10
,E/SMD     (  235): DCD ON
,E/SMD     (  235): DCD ON
,D/SSRMv2:SIOP(  775): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  775): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,E/SMD     (  235): DCD ON
,D/BatteryService(  775): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:10, charge type:1, power sharing:false
,D/BatteryService(  775): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  775): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,E/SMD     (  235): DCD ON
D/UiModeManager(  775): mCoverManager.getCoverState() : true
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3229): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3229): Disconnected process message: 10
D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  235): DCD ON
,E/SMD     (  235): DCD ON
,D/SSRMv2:SIOP(  775): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  775): prevTemp = 272, currTemp = 271, prevStep = 4, currStep = 4
,I/PowerManagerService(  775): [PWL] Off : 1265s ago
,E/SMD     (  235): DCD ON
,D/BatteryService(  775): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:8, charge type:1, power sharing:false
,D/BatteryService(  775): stay LED for fully charged
,D/BatteryService(  775): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/UiModeManager(  775): mCoverManager.getCoverState() : true
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3229): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,D/HeadsetStateMachine( 3229): Disconnected process message: 10
D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  235): DCD ON
,E/SMD     (  235): DCD ON
,D/SSRMv2:SIOP(  775): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  775): prevTemp = 271, currTemp = 272, prevStep = 4, currStep = 4
,E/SMD     (  235): DCD ON
,E/Watchdog(  775): !@Sync 44
,D/BatteryService(  775): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:11, charge type:1, power sharing:false
,D/BatteryService(  775): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  775): stay LED for fully charged
,D/UiModeManager(  775): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3229): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3229): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  235): DCD ON
,E/SMD     (  235): DCD ON
,D/SSRMv2:SIOP(  775): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  775): prevTemp = 272, currTemp = 271, prevStep = 4, currStep = 4
,E/SMD     (  235): DCD ON
,E/SMD     (  235): DCD ON
,D/BatteryService(  775): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:13, charge type:1, power sharing:false
,D/BatteryService(  775): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  775): mCoverManager.getCoverState() : true
,D/BatteryService(  775): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3229): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3229): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  235): DCD ON
,E/SMD     (  235): DCD ON
,D/SSRMv2:SIOP(  775): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  775): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,E/SMD     (  235): DCD ON
,D/BatteryService(  775): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:9, charge type:1, power sharing:false
,D/BatteryService(  775): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  775): stay LED for fully charged
,D/UiModeManager(  775): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3229): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3229): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  235): DCD ON
,E/SMD     (  235): DCD ON
,V/AlarmManager(  775): waitForAlarm result :8
,V/AlarmManager(  775): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1068): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  775): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  775): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,E/SMD     (  235): DCD ON
,E/Watchdog(  775): !@Sync 45
,D/BatteryService(  775): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:10, charge type:1, power sharing:false
,D/BatteryService(  775): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  775): stay LED for fully charged
,D/UiModeManager(  775): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3229): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3229): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  235): DCD ON
,E/SMD     (  235): DCD ON
,E/SMD     (  235): DCD ON
,D/SSRMv2:SIOP(  775): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  775): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,E/SMD     (  235): DCD ON
,D/BatteryService(  775): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:11, charge type:1, power sharing:false
,D/BatteryService(  775): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  775): mCoverManager.getCoverState() : true
,D/BatteryService(  775): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3229): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3229): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  235): DCD ON
,E/SMD     (  235): DCD ON
,D/SSRMv2:SIOP(  775): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  775): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,E/SMD     (  235): DCD ON
,D/BatteryService(  775): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:9, charge type:1, power sharing:false
,D/BatteryService(  775): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  775): stay LED for fully charged
,D/UiModeManager(  775): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3229): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3229): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  235): DCD ON
,E/SMD     (  235): DCD ON
,D/SSRMv2:SIOP(  775): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  775): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,E/SMD     (  235): DCD ON
,E/Watchdog(  775): !@Sync 46
,D/BatteryService(  775): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:11, charge type:1, power sharing:false
,D/BatteryService(  775): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  775): mCoverManager.getCoverState() : true
,D/BatteryService(  775): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3229): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3229): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  235): DCD ON
,E/SMD     (  235): DCD ON
,E/SMD     (  235): DCD ON
,D/SSRMv2:SIOP(  775): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  775): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,E/SMD     (  235): DCD ON
,D/BatteryService(  775): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:6, charge type:1, power sharing:false
,D/BatteryService(  775): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  775): mCoverManager.getCoverState() : true
,D/BatteryService(  775): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3229): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3229): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  235): DCD ON
,E/SMD     (  235): DCD ON
,D/SSRMv2:SIOP(  775): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  775): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,E/SMD     (  235): DCD ON
,D/BatteryService(  775): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:5, charge type:1, power sharing:false
,D/BatteryService(  775): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  775): stay LED for fully charged
,D/UiModeManager(  775): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3229): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3229): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  235): DCD ON
,E/SMD     (  235): DCD ON
,V/AlarmManager(  775): waitForAlarm result :8
,V/AlarmManager(  775): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1068): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  775): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  775): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,E/SMD     (  235): DCD ON
,E/Watchdog(  775): !@Sync 47
,D/BatteryService(  775): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:10, charge type:1, power sharing:false
,D/BatteryService(  775): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  775): stay LED for fully charged
,D/UiModeManager(  775): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3229): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3229): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  235): DCD ON
,E/SMD     (  235): DCD ON
,E/SMD     (  235): DCD ON
,D/SSRMv2:SIOP(  775): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  775): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,E/SMD     (  235): DCD ON
,D/BatteryService(  775): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:11, charge type:1, power sharing:false
,D/BatteryService(  775): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  775): stay LED for fully charged
,D/UiModeManager(  775): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3229): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3229): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,I/PowerManagerService(  775): [PWL] Off : 1380s ago
,E/SMD     (  235): DCD ON
,E/SMD     (  235): DCD ON
,D/SSRMv2:SIOP(  775): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  775): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,E/SMD     (  235): DCD ON
,E/SMD     (  235): DCD ON
,E/SMD     (  235): DCD ON
,D/SSRMv2:SIOP(  775): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  775): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,E/SMD     (  235): DCD ON
,E/Watchdog(  775): !@Sync 48
,D/BatteryService(  775): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:12, charge type:1, power sharing:false
,D/BatteryService(  775): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  775): stay LED for fully charged
,D/UiModeManager(  775): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3229): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3229): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  235): DCD ON
,E/SMD     (  235): DCD ON
,E/SMD     (  235): DCD ON
,D/SSRMv2:SIOP(  775): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  775): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,E/SMD     (  235): DCD ON
,D/BatteryService(  775): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:10, charge type:1, power sharing:false
,D/BatteryService(  775): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  775): stay LED for fully charged
,D/UiModeManager(  775): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3229): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3229): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  235): DCD ON
,E/SMD     (  235): DCD ON
,D/SSRMv2:SIOP(  775): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  775): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,E/SMD     (  235): DCD ON
,D/BatteryService(  775): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:10, charge type:1, power sharing:false
,D/BatteryService(  775): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  775): mCoverManager.getCoverState() : true
,D/BatteryService(  775): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3229): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3229): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  235): DCD ON
,E/SMD     (  235): DCD ON
,V/AlarmManager(  775): waitForAlarm result :8
,V/AlarmManager(  775): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1068): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  235): DCD ON
,D/SSRMv2:SIOP(  775): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  775): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,E/Watchdog(  775): !@Sync 49
,E/SMD     (  235): DCD ON
,D/BatteryService(  775): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:9, charge type:1, power sharing:false
,D/BatteryService(  775): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  775): stay LED for fully charged
,D/UiModeManager(  775): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3229): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3229): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  235): DCD ON
,E/SMD     (  235): DCD ON
,D/SSRMv2:SIOP(  775): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  775): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,E/SMD     (  235): DCD ON
,D/BatteryService(  775): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:11, charge type:1, power sharing:false
,D/BatteryService(  775): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  775): mCoverManager.getCoverState() : true
,D/BatteryService(  775): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3229): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3229): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  235): DCD ON
,E/SMD     (  235): DCD ON
,D/SSRMv2:SIOP(  775): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  775): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,E/SMD     (  235): DCD ON
,D/BatteryService(  775): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:9, charge type:1, power sharing:false
,D/BatteryService(  775): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  775): stay LED for fully charged
,D/UiModeManager(  775): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3229): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3229): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  235): DCD ON
,D/TimaService(  775): TIMA: TimaService scheduler is intialized. 
,D/TimaService(  775): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService(  775): TimaServiceHandler.handleMessage what =1
,E/SMD     (  235): DCD ON
,E/SMD     (  235): DCD ON
,I/TLC_TIMA_PKM_measure_kernel(  775): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel(  775): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService(  775): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService(  775): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/SSRMv2:SIOP(  775): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  775): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,E/Watchdog(  775): !@Sync 50
,E/SMD     (  235): DCD ON
,D/BatteryService(  775): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:11, charge type:1, power sharing:false
,D/BatteryService(  775): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  775): stay LED for fully charged
,D/UiModeManager(  775): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3229): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3229): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  235): DCD ON
,E/SMD     (  235): DCD ON
,D/SSRMv2:SIOP(  775): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  775): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,E/SMD     (  235): DCD ON
,D/BatteryService(  775): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:9, charge type:1, power sharing:false
,D/BatteryService(  775): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  775): stay LED for fully charged
,D/UiModeManager(  775): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3229): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3229): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  235): DCD ON
,E/SMD     (  235): DCD ON
,D/SSRMv2:SIOP(  775): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  775): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,E/SMD     (  235): DCD ON
,D/BatteryService(  775): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:10, charge type:1, power sharing:false
,D/BatteryService(  775): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  775): stay LED for fully charged
,D/UiModeManager(  775): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3229): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3229): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  235): DCD ON
,E/SMD     (  235): DCD ON
,V/AlarmManager(  775): waitForAlarm result :8
,V/AlarmManager(  775): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1068): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  235): DCD ON
,D/SSRMv2:SIOP(  775): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  775): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,E/Watchdog(  775): !@Sync 51
,E/SMD     (  235): DCD ON
,E/SMD     (  235): DCD ON
,E/SMD     (  235): DCD ON
,D/SSRMv2:SIOP(  775): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  775): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,E/SMD     (  235): DCD ON
,I/PowerManagerService(  775): [PWL] Off : 1500s ago
,E/SMD     (  235): DCD ON
,E/SMD     (  235): DCD ON
,E/SMD     (  235): DCD ON
,D/SSRMv2:SIOP(  775): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  775): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,D/BatteryService(  775): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:9, charge type:1, power sharing:false
,D/BatteryService(  775): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  775): mCoverManager.getCoverState() : true
,D/BatteryService(  775): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3229): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3229): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  235): DCD ON
,D/dalvikvm(  775): GC_CONCURRENT freed 3440K, 57% free 23549K/54572K, paused 30ms+57ms, total 625ms
,E/SMD     (  235): DCD ON
,E/SMD     (  235): DCD ON
,D/SSRMv2:SIOP(  775): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  775): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,E/Watchdog(  775): !@Sync 52
,E/SMD     (  235): DCD ON
,D/BatteryService(  775): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:11, charge type:1, power sharing:false
,D/BatteryService(  775): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  775): stay LED for fully charged
,D/UiModeManager(  775): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3229): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3229): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  235): DCD ON
,E/SMD     (  235): DCD ON
,D/SSRMv2:SIOP(  775): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  775): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,E/SMD     (  235): DCD ON
,E/SMD     (  235): DCD ON
,E/SMD     (  235): DCD ON
,E/SMD     (  235): DCD ON
,D/SSRMv2:SIOP(  775): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  775): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,D/BatteryService(  775): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:10, charge type:1, power sharing:false
,D/BatteryService(  775): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  775): stay LED for fully charged
,D/UiModeManager(  775): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3229): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3229): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  235): DCD ON
,E/SMD     (  235): DCD ON
,V/AlarmManager(  775): waitForAlarm result :8
,V/AlarmManager(  775): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1068): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  235): DCD ON
,D/SSRMv2:SIOP(  775): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  775): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,E/Watchdog(  775): !@Sync 53
,E/SMD     (  235): DCD ON
,D/BatteryService(  775): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:7, charge type:1, power sharing:false
,D/BatteryService(  775): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  775): stay LED for fully charged
,D/UiModeManager(  775): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3229): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
D/HeadsetStateMachine( 3229): Disconnected process message: 10
,E/SMD     (  235): DCD ON
,E/SMD     (  235): DCD ON
,D/SSRMv2:SIOP(  775): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  775): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,E/SMD     (  235): DCD ON
,D/BatteryService(  775): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:12, charge type:1, power sharing:false
,D/BatteryService(  775): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  775): mCoverManager.getCoverState() : true
,D/BatteryService(  775): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,V/HeadsetService( 3229): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3229): Disconnected process message: 10
D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  235): DCD ON
,E/SMD     (  235): DCD ON
,E/SMD     (  235): DCD ON
,D/SSRMv2:SIOP(  775): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  775): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,D/BatteryService(  775): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:15, charge type:1, power sharing:false
,D/BatteryService(  775): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  775): stay LED for fully charged
,D/UiModeManager(  775): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,E/SMD     (  235): DCD ON
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3229): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3229): Disconnected process message: 10
D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  235): DCD ON
,E/SMD     (  235): DCD ON
,E/Watchdog(  775): !@Sync 54
,D/SSRMv2:SIOP(  775): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  775): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,E/SMD     (  235): DCD ON
,D/BatteryService(  775): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:9, charge type:1, power sharing:false
,D/BatteryService(  775): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  775): mCoverManager.getCoverState() : true
,D/BatteryService(  775): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3229): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3229): Disconnected process message: 10
D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  235): DCD ON
,E/SMD     (  235): DCD ON
,D/SSRMv2:SIOP(  775): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  775): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,E/SMD     (  235): DCD ON
,D/BatteryService(  775): level:100, scale:100, status:5, health:2, present:true, voltage: 4371, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:11, charge type:1, power sharing:false
,D/BatteryService(  775): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  775): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/UiModeManager(  775): mCoverManager.getCoverState() : true
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3229): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3229): Disconnected process message: 10
D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  235): DCD ON
,E/SMD     (  235): DCD ON
,E/SMD     (  235): DCD ON
,D/SSRMv2:SIOP(  775): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  775): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,E/SMD     (  235): DCD ON
,D/BatteryService(  775): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:5, charge type:1, power sharing:false
,D/BatteryService(  775): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  775): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/UiModeManager(  775): mCoverManager.getCoverState() : true
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3229): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3229): Disconnected process message: 10
D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  235): DCD ON
,V/AlarmManager(  775): waitForAlarm result :8
,V/AlarmManager(  775): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1068): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  235): DCD ON
,E/Watchdog(  775): !@Sync 55
,D/SSRMv2:SIOP(  775): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  775): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,E/SMD     (  235): DCD ON
,D/BatteryService(  775): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:11, charge type:1, power sharing:false
,D/BatteryService(  775): Sending ACTION_BATTERY_CHANGED.
D/BatteryService(  775): stay LED for fully charged
D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
D/UiModeManager(  775): mCoverManager.getCoverState() : true
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3229): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3229): Disconnected process message: 10
D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  235): DCD ON
,E/SMD     (  235): DCD ON
,E/SMD     (  235): DCD ON
,D/SSRMv2:SIOP(  775): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  775): prevTemp = 271, currTemp = 270, prevStep = 4, currStep = 4
,D/BatteryService(  775): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:12, charge type:1, power sharing:false
,D/BatteryService(  775): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  775): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/UiModeManager(  775): mCoverManager.getCoverState() : true
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3229): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3229): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  235): DCD ON
,E/SMD     (  235): DCD ON
,I/PowerManagerService(  775): [PWL] Off : 1625s ago
,E/SMD     (  235): DCD ON
,D/SSRMv2:SIOP(  775): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  775): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  235): DCD ON
,D/BatteryService(  775): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:13, charge type:1, power sharing:false
,D/BatteryService(  775): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  775): mCoverManager.getCoverState() : true
,D/BatteryService(  775): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3229): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3229): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  235): DCD ON
,E/SMD     (  235): DCD ON
,E/Watchdog(  775): !@Sync 56
,D/SSRMv2:SIOP(  775): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  775): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  235): DCD ON
,D/BatteryService(  775): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:8, charge type:1, power sharing:false
,D/BatteryService(  775): stay LED for fully charged
,D/BatteryService(  775): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/UiModeManager(  775): mCoverManager.getCoverState() : true
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,V/HeadsetService( 3229): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3229): Disconnected process message: 10
D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  235): DCD ON
,E/SMD     (  235): DCD ON
,E/SMD     (  235): DCD ON
,D/SSRMv2:SIOP(  775): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  775): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,D/BatteryService(  775): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:10, charge type:1, power sharing:false
,D/BatteryService(  775): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  775): stay LED for fully charged
,D/UiModeManager(  775): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3229): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3229): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  235): DCD ON
,E/SMD     (  235): DCD ON
,E/SMD     (  235): DCD ON
,D/SSRMv2:SIOP(  775): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  775): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  235): DCD ON
,D/BatteryService(  775): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:11, charge type:1, power sharing:false
,D/BatteryService(  775): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  775): mCoverManager.getCoverState() : true
,D/BatteryService(  775): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3229): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3229): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  235): DCD ON
,V/AlarmManager(  775): waitForAlarm result :8
,V/AlarmManager(  775): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1068): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  235): DCD ON
,E/Watchdog(  775): !@Sync 57
,D/SSRMv2:SIOP(  775): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  775): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  235): DCD ON
,D/BatteryService(  775): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:6, charge type:1, power sharing:false
,D/BatteryService(  775): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  775): stay LED for fully charged
,D/UiModeManager(  775): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3229): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3229): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  235): DCD ON
,E/SMD     (  235): DCD ON
,E/SMD     (  235): DCD ON
,D/SSRMv2:SIOP(  775): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  775): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,D/BatteryService(  775): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:7, charge type:1, power sharing:false
,D/BatteryService(  775): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  775): stay LED for fully charged
,D/UiModeManager(  775): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3229): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3229): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  235): DCD ON
,E/SMD     (  235): DCD ON
,E/SMD     (  235): DCD ON
,D/SSRMv2:SIOP(  775): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  775): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  235): DCD ON
,D/BatteryService(  775): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:8, charge type:1, power sharing:false
,D/BatteryService(  775): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  775): mCoverManager.getCoverState() : true
,D/BatteryService(  775): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3229): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3229): Disconnected process message: 10
,E/SMD     (  235): DCD ON
,E/SMD     (  235): DCD ON
,E/Watchdog(  775): !@Sync 58
,D/SSRMv2:SIOP(  775): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  775): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  235): DCD ON
,D/BatteryService(  775): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:11, charge type:1, power sharing:false
,D/BatteryService(  775): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  775): stay LED for fully charged
,D/UiModeManager(  775): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3229): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3229): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  235): DCD ON
,E/SMD     (  235): DCD ON
,E/SMD     (  235): DCD ON
,D/SSRMv2:SIOP(  775): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  775): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,D/BatteryService(  775): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:9, charge type:1, power sharing:false
,D/BatteryService(  775): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  775): stay LED for fully charged
,D/UiModeManager(  775): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3229): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3229): Disconnected process message: 10
,E/SMD     (  235): DCD ON
,E/SMD     (  235): DCD ON
,E/SMD     (  235): DCD ON
,D/SSRMv2:SIOP(  775): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  775): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  235): DCD ON
,D/BatteryService(  775): level:100, scale:100, status:5, health:2, present:true, voltage: 4371, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:10, charge type:1, power sharing:false
,D/BatteryService(  775): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  775): stay LED for fully charged
,D/UiModeManager(  775): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3229): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3229): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  235): DCD ON
,V/AlarmManager(  775): waitForAlarm result :8
,V/AlarmManager(  775): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1068): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  235): DCD ON
,E/Watchdog(  775): !@Sync 59
,E/SMD     (  235): DCD ON
,D/SSRMv2:SIOP(  775): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  775): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,D/BatteryService(  775): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:10, charge type:1, power sharing:false
,D/BatteryService(  775): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  775): stay LED for fully charged
,D/UiModeManager(  775): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3229): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3229): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  235): DCD ON
,E/SMD     (  235): DCD ON
,E/SMD     (  235): DCD ON
,D/SSRMv2:SIOP(  775): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  775): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,D/BatteryService(  775): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:8, charge type:1, power sharing:false
,D/BatteryService(  775): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  775): stay LED for fully charged
,E/SMD     (  235): DCD ON
,D/UiModeManager(  775): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3229): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3229): Disconnected process message: 10
D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  235): DCD ON
,E/SMD     (  235): DCD ON
,D/SSRMv2:SIOP(  775): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  775): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  235): DCD ON
,D/BatteryService(  775): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:6, charge type:1, power sharing:false
,D/BatteryService(  775): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  775): stay LED for fully charged
,D/UiModeManager(  775): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3229): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
D/HeadsetStateMachine( 3229): Disconnected process message: 10
,D/TimaService(  775): TIMA: TimaService scheduler is intialized. 
,D/TimaService(  775): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService(  775): TimaServiceHandler.handleMessage what =1
,E/SMD     (  235): DCD ON
,I/PowerManagerService(  775): [PWL] Off : 1755s ago
,I/PowerManagerService(  775): [PWL]   PowerManagerService.WakeLocks: ref count=1
I/PowerManagerService(  775): [PWL]     mWakeLockSummary : 0x1
,I/PowerManagerService(  775): [PWL]       PARTIAL_WAKE_LOCK              'TimaService' (uid=1000, pid=775, ws=null) (elapsedTime=4061)
,I/TLC_TIMA_PKM_measure_kernel(  775): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel(  775): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService(  775): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService(  775): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/SMD     (  235): DCD ON
,E/Watchdog(  775): !@Sync 60
,E/SMD     (  235): DCD ON
,D/SSRMv2:SIOP(  775): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  775): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,D/BatteryService(  775): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:12, charge type:1, power sharing:false
,D/BatteryService(  775): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  775): mCoverManager.getCoverState() : true
,D/BatteryService(  775): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3229): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3229): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  235): DCD ON
,E/SMD     (  235): DCD ON
,E/SMD     (  235): DCD ON
,D/SSRMv2:SIOP(  775): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  775): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  235): DCD ON
,D/BatteryService(  775): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:10, charge type:1, power sharing:false
,D/BatteryService(  775): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  775): mCoverManager.getCoverState() : true
,D/BatteryService(  775): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3229): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3229): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  235): DCD ON
,E/SMD     (  235): DCD ON
,D/SSRMv2:SIOP(  775): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  775): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  235): DCD ON
,D/BatteryService(  775): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:9, charge type:1, power sharing:false
,D/BatteryService(  775): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  775): mCoverManager.getCoverState() : true
,D/BatteryService(  775): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3229): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3229): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  235): DCD ON
,V/AlarmManager(  775): waitForAlarm result :8
,V/AlarmManager(  775): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1068): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,I/ProcessStatsService(  775): Prepared write state in 165ms
,I/ProcessStatsService(  775): Prepared write state in 155ms
,I/ProcessStatsService(  775): Prepared write state in 64ms
,I/ProcessStatsService(  775): Prepared write state in 52ms
,I/ProcessStatsService(  775): Pruning old procstats: /data/system/procstats/state-2015-12-13-11-36-47.bin
,E/SMD     (  235): DCD ON
,E/Watchdog(  775): !@Sync 61
,E/SMD     (  235): DCD ON
,D/SSRMv2:SIOP(  775): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  775): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,D/BatteryService(  775): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:13, charge type:1, power sharing:false
,D/BatteryService(  775): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  775): stay LED for fully charged
,D/UiModeManager(  775): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3229): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3229): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  235): DCD ON
,E/SMD     (  235): DCD ON
,E/SMD     (  235): DCD ON
,D/SSRMv2:SIOP(  775): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  775): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  235): DCD ON
,D/BatteryService(  775): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:5, charge type:1, power sharing:false
,D/BatteryService(  775): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  775): stay LED for fully charged
,D/UiModeManager(  775): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3229): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3229): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  235): DCD ON
,E/SMD     (  235): DCD ON
,E/SMD     (  235): DCD ON
,D/SSRMv2:SIOP(  775): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  775): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  235): DCD ON
,E/SMD     (  235): DCD ON
,E/Watchdog(  775): !@Sync 62
,E/SMD     (  235): DCD ON
,D/SSRMv2:SIOP(  775): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  775): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,D/BatteryService(  775): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:6, charge type:1, power sharing:false
,D/BatteryService(  775): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  775): stay LED for fully charged
,D/UiModeManager(  775): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3229): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3229): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  235): DCD ON
,E/SMD     (  235): DCD ON
,E/SMD     (  235): DCD ON
,D/SSRMv2:SIOP(  775): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  775): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  235): DCD ON
,D/BatteryService(  775): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:10, charge type:1, power sharing:false
,D/BatteryService(  775): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  775): stay LED for fully charged
,D/UiModeManager(  775): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3229): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3229): Disconnected process message: 10
D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  235): DCD ON
,E/SMD     (  235): DCD ON
,E/SMD     (  235): DCD ON
,D/SSRMv2:SIOP(  775): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  775): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,D/BatteryService(  775): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:9, charge type:1, power sharing:false
,D/BatteryService(  775): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  775): stay LED for fully charged
,D/UiModeManager(  775): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3229): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3229): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  235): DCD ON
,V/AlarmManager(  775): waitForAlarm result :8
,V/AlarmManager(  775): ClockReceiver onReceive() ACTION_TIME_TICK
,V/AlarmManager(  775): ___SyncScheduler (v3) ACTIVATED___
,V/AlarmManager(  775): <AppSync3 Whitelist>
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1068): handleTimeUpdate
V/AlarmManager(  775): (AppSync) ### 0 added ###
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  235): DCD ON
,E/Watchdog(  775): !@Sync 63
,E/SMD     (  235): DCD ON
,D/SSRMv2:SIOP(  775): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  775): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,D/BatteryService(  775): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:5, charge type:1, power sharing:false
,D/BatteryService(  775): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  775): mCoverManager.getCoverState() : true
,D/BatteryService(  775): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3229): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
D/HeadsetStateMachine( 3229): Disconnected process message: 10
,E/SMD     (  235): DCD ON
,E/SMD     (  235): DCD ON
,E/SMD     (  235): DCD ON
,D/SSRMv2:SIOP(  775): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  775): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  235): DCD ON
,D/BatteryService(  775): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:12, charge type:1, power sharing:false
,D/BatteryService(  775): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  775): mCoverManager.getCoverState() : true
,D/BatteryService(  775): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3229): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3229): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  235): DCD ON
,E/SMD     (  235): DCD ON
,E/SMD     (  235): DCD ON
,D/SSRMv2:SIOP(  775): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  775): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  235): DCD ON
,V/AlarmManager(  775): waitForAlarm result :4
,I/SensorManagerA(  775): getReportingMode :: sensor.mType = 5
,D/LightsService(  775): [api] onReceive : SvcLEDReceiver re-enables LightSenor and sends MSG_FORCEDSVCLEDTASK
D/Sensors (  775): LightSensor setDelay = 200000000
D/Sensors (  775): LightSensor setSensorDelay = 200000000
D/Sensors (  775): Light sensor flush: not enabled 0
D/Sensors (  775): LightSensor enable = 1
D/Sensors (  775): LightSensor enableSensor = 1
D/SensorManager(  775): registerListener :: 16, CM36686 Light Sensor, 200000, 0,  
,I/ActivityManager(  775): Killing 4609:com.sec.android.app.shealth/u0a35 (adj 15): empty for 1800s
,I/ActivityManager(  775): Killing 5187:com.samsung.klmsagent/u0a18 (adj 15): empty for 1800s
,I/ActivityManager(  775): Killing 5163:com.sec.android.fotaclient/u0a10 (adj 15): empty for 1800s
,I/ActivityManager(  775): Killing 5354:com.samsung.android.service.travel/u0a169 (adj 15): empty for 1801s
,I/ActivityManager(  775): Killing 5348:com.sec.android.provider.badge/u0a72 (adj 15): empty for 1801s
,I/ActivityManager(  775): Killing 4985:tv.peel.smartremote/u0a163 (adj 15): empty for 1801s
,I/ActivityManager(  775): Killing 5330:com.android.email/u0a155 (adj 15): empty for 1801s
,I/ActivityManager(  775): Killing 4279:com.google.android.apps.plus/u0a130 (adj 15): empty for 1801s
,I/ActivityManager(  775): Killing 5286:com.google.android.apps.magazines/u0a112 (adj 15): empty for 1802s
,I/ActivityManager(  775): Killing 4831:com.samsung.android.magazine.service/u0a106 (adj 15): empty for 1802s
,I/ActivityManager(  775): Killing 5136:com.android.chrome/u0a81 (adj 15): empty for 1802s
,I/ActivityManager(  775): Killing 5260:com.samsung.android.scloud.backup/u0a60 (adj 15): empty for 1802s
,I/ActivityManager(  775): Killing 3777:com.sec.spp.push/u0a38 (adj 15): empty for 1802s
,I/ActivityManager(  775): Killing 5234:com.sec.android.app.voicenote/1000 (adj 15): empty for 1803s
,I/ActivityManager(  775): Killing 4698:com.policydm/1000 (adj 15): empty for 1803s
,I/ActivityManager(  775): Killing 5208:com.sec.android.app.videoplayer/u0a52 (adj 15): empty for 1803s
,I/ActivityManager(  775): Killing 5019:com.vlingo.midas/u0a33 (adj 15): empty for 1803s
,I/ActivityManager(  775): Killing 4310:com.sec.android.diagmonagent/1000 (adj 15): empty for 1803s
,I/ActivityManager(  775): Killing 5116:com.sec.android.cloudagent/u0a2 (adj 15): empty for 1804s
,I/ActivityManager(  775): Killing 3836:com.google.android.music:main/u0a122 (adj 15): empty for 1804s
,I/ActivityManager(  775): Killing 4577:com.sec.pcw.device/1000 (adj 15): empty for 1804s
,I/ActivityManager(  775): Killing 4253:com.sec.android.app.FileShareServer/u0a69 (adj 15): empty for 1807s
,I/ActivityManager(  775): Killing 4875:com.samsung.android.provider.shootingmodeprovider/u0a162 (adj 15): empty for 1814s
,I/ActivityManager(  775): Killing 4863:com.sec.kidsplat.installer/u0a158 (adj 15): empty for 1814s
,D/BatteryService(  775): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:4, charge type:1, power sharing:false
,D/BatteryService(  775): stay LED for fully charged
,I/ActivityManager(  775): Killing 4846:com.samsung.helphub/1000 (adj 15): empty for 1814s
,I/ActivityManager(  775): Killing 4804:com.samsung.android.app.watchmanagerstub/u0a100 (adj 15): empty for 1814s
,I/ActivityManager(  775): Killing 4784:com.google.android.apps.docs/u0a90 (adj 15): empty for 1814s
,D/NtpTrustedTime(  775): currentTimeMillis() cache hit
V/NetworkStats(  775): performPollLocked(flags=0x3)
,D/Sensors (  775): LightSensor enable = 0
,D/Sensors (  775): LightSensor enableSensor = 0
D/LightsService(  775): [SvcLED]  onSensorChanged::light value = 4
,D/SensorManager(  775): unregisterListener ::   
D/LightsService(  775): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,E/SMD     (  235): DCD ON
,V/AlarmManager(  775): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,D/BatteryService(  775): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  775): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3229): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3229): Disconnected process message: 10
,D/NtpTrustedTime(  775): currentTimeMillis() cache hit
V/NetworkStats(  775): performPollLocked() took 340ms
,D/NtpTrustedTime(  775): currentTimeMillis() cache hit
,D/NtpTrustedTime(  775): currentTimeMillis() cache hit
,D/dalvikvm(  775): GC_CONCURRENT freed 3417K, 57% free 23651K/54572K, paused 82ms+19ms, total 416ms
,V/GLSActivity( 1323): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1323): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ConnectivityService(  775): handleInetConditionHoldEnd: net=1, condition=100, published condition=100
,D/STATUSBAR-NetworkController_dual( 1068): onReceive() - CONNECTIVITY_ACTION, INET_CONDITION_ACTION
,D/StatusBar.NetworkController_dual( 1068): mMobileLabelViews start
D/StatusBar.NetworkController_dual( 1068): mMobileLabelViews set mobileLabel[SIM_0] =
D/StatusBar.NetworkController_dual( 1068): mMobileLabelViews GONE
D/StatusBar.NetworkController_dual( 1068): mMobileLabelViews2 set mobileLabel[SIM_1] =
,D/StatusBar.NetworkController_dual( 1068): mMobileLabelViews2 GONE
,D/StatusBar.NetworkController_dual( 1068): mSingleMobileLabelViews set : simMode = 0
,D/StatusBar.NetworkController_dual( 1068): mSingleMobileLabelViews set as slot1`s
,E/Watchdog(  775): !@Sync 64
,E/SMD     (  235): DCD ON
,D/SSRMv2:SIOP(  775): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer(  775): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  235): DCD ON
,E/SMD     (  235): DCD ON
,D/BatteryService(  775): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:4, charge type:1, power sharing:false
,D/BatteryService(  775): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  775): stay LED for fully charged
,D/UiModeManager(  775): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1068): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1068): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1068):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1068): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3229): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/STATUSBAR-IconMerger( 1068): checkOverflow(288), More:false, Req:false Child:2
D/HeadsetStateMachine( 3229): Disconnected process message: 10
,TIME-OUT KILL (timeout was 1800000ms),E/SMD     (  235): DCD ON
I/PowerManagerService(  775): [PWL] Off : 1890s ago
D/SSRMv2:SIOP(  775): SIOP:: AP = 300, Delta = 0
D/AmoledAdjustTimer(  775): prevTemp = 270, currTemp = 271, prevStep = 4, currStep = 4
E/SMD     (  235): DCD ON
D/AndroidRuntime( 6086): 
D/AndroidRuntime( 6086): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 6086): CheckJNI is OFF
D/AndroidRuntime( 6086): setted country_code = Poland
D/AndroidRuntime( 6086): setted countryiso_code = PL
D/AndroidRuntime( 6086): setted sales_code = XEO
D/AndroidRuntime( 6086): readGMSProperty: start
D/AndroidRuntime( 6086): readGMSProperty: already setted!!
D/AndroidRuntime( 6086): readGMSProperty: end
D/AndroidRuntime( 6086): addProductProperty: start
D/dalvikvm( 6086): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 6086): Added shared lib libjavacore.so 0x0
D/dalvikvm( 6086): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 6086): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 6086): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
E/memtrack( 6086): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 6086): failed to load memtrack module: -2
D/dalvikvm( 6086): Note: class Landroid/app/ActivityManagerNative; has 192 unimplemented (abstract) methods
E/SMD     (  235): DCD ON
D/AndroidRuntime( 6086): Calling main entry com.android.commands.pm.Pm
D/PackageManagerService(  775): deletePackageAsUser- pkg:com.test.thalitest, userId:0
D/PackageManager(  775): START PACKAGE DELETE: observer{1124149176}
D/PackageManager(  775): pkg{<packageName>}
D/PackageManager(  775): user{0}
D/PersonaManagerService(  775): isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
D/PersonaManagerService(  775): isFromApprovedUnInstaller: isApproved : true
D/PersonaManagerService(  775): isFromApprovedUnInstaller: isApproved before exit: true
D/PackageManager(  775): deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag3
D/PackageManager(  775): deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag3
D/PackageManagerService(  775): deletePackage- pkg:com.test.thalitest, edmuserId:0
D/PackageManagerService(  775): deletePackage- pkg:com.test.thalitest, edmuserId:-1
D/ApplicationPolicy(  775): getApplicationUninstallationEnabled
D/ApplicationPolicy(  775): getApplicationUninstallationEnabled :  enabled true
D/PackageManagerService(  775): deletePackageX- pkg:com.test.thalitest, userId:0
D/PackageManager(  775): deletePackageAsUser : uid = 2000 userId = 0
D/PackageManager(  775): [MSG] DELETE_PACKAGE_AS_USER
D/PackageManager(  775): !@killApplicatoin: 10179, uninstall pkg
I/ActivityManager(  775): Killing 4745:com.test.thalitest/u0a179 (adj 0): stop com.test.thalitest
D/CustomFrequencyManagerService(  775): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 775  pkgName : ACTIVITY_RESUME_BOOSTER@5
W/ActivityManager(  775): mDVFSHelper.acquire()
D/KeyguardUpdateMonitor( 1068): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1068): handleKeyguardVisibilityChanged(1)
D/KeyguardUpdateMonitor( 1068): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1068): handleKeyguardVisibilityChanged(1)
D/KeyguardUpdateMonitor( 1068): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1068): handleKeyguardVisibilityChanged(1)
I/SurfaceFlinger(  241): id=18 Removed NainActivit (7/11)
I/SurfaceFlinger(  241): id=18 Removed NainActivit (-2/11)
I/SurfaceFlinger(  241): id=18 Removed NainActivit (-2/11)
D/KeyguardUpdateMonitor( 1068): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1068): handleKeyguardVisibilityChanged(1)
I/WindowState(  775): WIN DEATH: Window{447b9350 u0 com.test.thalitest/com.test.thalitest.MainActivity}
D/SurfaceWidgetView( 1251): destroyHardwareResources():1128485640
W/PackageSettings(  775): Skipping PackageSetting{42edf0f8 com.example.hello/10180} due to missing metadata
D/PackageManager(  775): queryIntentReceivers - Execution time: 124 ms
D/LockPatternUtils( 1068): isPcwEnable = null
D/PackageManager(  775): Sending to user 0: act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000000 Bundle[{android.intent.extra.REMOVED_FOR_ALL_USERS=true, android.intent.extra.UID=10179, android.intent.extra.DATA_REMOVED=true, android.intent.extra.user_handle=0}]
D/KeyguardUpdateMonitor( 1068): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1068): handleKeyguardVisibilityChanged(1)
D/Launcher( 1251): onRestart, Launcher: 1116551112
D/Launcher( 1251): onStart, Launcher: 1116551112
D/Launcher.HomeView( 1251): onStart
D/KeyguardUpdateMonitor( 1068): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1068): handleKeyguardVisibilityChanged(1)
I/SurfaceFlinger(  241): id=20 createSurf (1x1),2 flag=404, CatteryCove
D/SurfaceWidgetClient$ISurfaceWidgetStub( 1454): [237392/5] Surface widget visibility changed visibility = true on instance = 1
D/SurfaceWidget.Renderer( 1454): [237392/5] SurfaceWidget drawing first frame
D/KeyguardUpdateMonitor( 1068): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1068): handleKeyguardVisibilityChanged(1)
D/dalvikvm( 1804): GC_EXPLICIT freed 455K, 35% free 12455K/19008K, paused 4ms+8ms, total 52ms
W/SQLiteConnectionPool( 1804): A SQLiteConnection object for database '+data+data+com_google_android_gms+databases+networkstatistics_sqlite' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
D/KeyguardUpdateMonitor( 1068): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1068): handleKeyguardVisibilityChanged(1)
D/AdaptiveEventManager( 1068): action=android.intent.action.PACKAGE_REMOVED
I/PackageManager(  775):   Action: "android.intent.action.SENDTO"
I/PackageManager(  775):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  775):   Scheme: "sms"
I/PackageManager(  775): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
D/QuickConnect[1.1][2] ( 3199): SconnectManager.onReceiver - action : android.intent.action.PACKAGE_REMOVED, package : com.test.thalitest
I/FPMS_FingerprintManagerService( 1087): onReceive: android.intent.action.PACKAGE_REMOVED
I/SurfaceFlinger(  241): id=21 createSurf (720x1280),1 flag=4, Mauncher
D/elm:14132( 5448): ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
I/PackageManager(  775):   Action: "android.intent.action.SENDTO"
I/PackageManager(  775):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  775):   Scheme: "smsto"
D/dalvikvm( 1409): GC_EXPLICIT freed 4293K, 48% free 10017K/19008K, paused 7ms+5ms, total 84ms
I/PackageManager(  775): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
D/KeyguardUpdateMonitor( 1068): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1068): handleKeyguardVisibilityChanged(1)
I/InputReader(  775): Reconfiguring input devices.  changes=0x00000010
D/PackageManager(  775): Sending to user 0: act=android.intent.action.PACKAGE_FULLY_REMOVED dat=package:com.test.thalitest flg=0x4000000 Bundle[{android.intent.extra.REMOVED_FOR_ALL_USERS=true, android.intent.extra.UID=10179, android.intent.extra.DATA_REMOVED=true, android.intent.extra.user_handle=0}]
I/PackageManager(  775):   Action: "android.intent.action.SENDTO"
I/PackageManager(  775):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  775):   Scheme: "mms"
I/PackageManager(  775): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
W/GeofencerStateMachine( 1219): Ignoring removeGeofence because network location is disabled.
I/PackageManager(  775):   Action: "android.intent.action.SENDTO"
I/PackageManager(  775):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  775):   Scheme: "mmsto"
I/PackageManager(  775): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
I/SurfaceFlinger(  241): id=22 createSurf (707x984),1 flag=4, TettingsRec
D/KeyguardUpdateMonitor( 1068): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1068): handleKeyguardVisibilityChanged(1)
D/elm:14132( 5448): ELMAbstractReceiver : Receive Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
D/CustomFrequencyManagerService(  775): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 775  tag : ACTIVITY_RESUME_BOOSTER@5
W/ActivityManager(  775): mDVFSHelper.release()
D/elm:14132( 5448): ElmAgentService : onCreate()
D/elm:14132( 5448): ElmAgentService : onHandleIntent() Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
D/elm:14132( 5448): MainReceiver.listeningToPackageRemoved()
D/elm:14132( 5448): MDMBridge.getInstance()
D/elm:14132( 5448): MDMBridge.getAllLicenseInfoFromSDK()
D/elm:14132( 5448): MDMBridge.getAllLicenseInfoFromSDK()
D/CustomFrequencyManagerService(  775): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 775  pkgName : ACTIVITY_RESUME_BOOSTER@9
D/dalvikvm(  775): GC_EXPLICIT freed 1665K, 57% free 23674K/54572K, paused 7ms+15ms, total 177ms
I/PackageManager(  775):   Action: "android.intent.action.SENDTO"
I/PackageManager(  775):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  775):   Scheme: "sms"
D/dalvikvm( 2145): GC_EXPLICIT freed 1201K, 41% free 11278K/19008K, paused 33ms+6ms, total 192ms
I/PackageManager(  775): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
D/dalvikvm(  775): WAIT_FOR_CONCURRENT_GC blocked 63ms
I/SELinux ( 6117): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 6117):  
I/PackageManager(  775): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
I/PackageManager(  775):   Action: "android.intent.action.SENDTO"
I/PackageManager(  775):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  775):   Scheme: "smsto"
D/KeyguardUpdateMonitor( 1068): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1068): handleKeyguardVisibilityChanged(1)
I/PackageManager(  775):   Action: "android.intent.action.SENDTO"
I/PackageManager(  775):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  775):   Scheme: "mms"
D/KeyguardUpdateMonitor( 1068): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1068): handleKeyguardVisibilityChanged(1)
I/PackageManager(  775): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
D/elm:14132( 5448): MainReceiver.listeningToPackageRemoved(). SEND to KLMS. Remove All KNOX/ONS License
D/RCPManagerService(  775): PackageReceiver onReceive()
D/elm:14132( 5448): ElmAgentService : onDestroy().
D/KeyguardUpdateMonitor( 1068): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1068): handleKeyguardVisibilityChanged(1)
I/SELinux ( 6117): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 6117):  
I/SELinux ( 6117):  
I/SELinux ( 6117): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 6117): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 6117): >>>>> Normal User
E/dalvikvm( 6117): >>>>> com.sec.android.service.health [ userId:0 | appId:10016 ]
E/SELinux ( 6117): [DEBUG] seapp_context_lookup: seinfoCategory = platform
I/PackageManager(  775):   Action: "android.intent.action.SENDTO"
I/PackageManager(  775):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  775):   Scheme: "mmsto"
I/PackageManager(  775): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
I/HarmonyEASService(  775): onReceive : android.intent.action.PACKAGE_REMOVED for 0
D/KeyguardUpdateMonitor( 1068): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1068): handleKeyguardVisibilityChanged(1)
D/TimaKeyStoreProvider( 6117): in addTimaSignatureService
D/TimaKeyStoreProvider( 6117): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 6117): Added TimaKesytore provider
D/EnterpriseDeviceManagerService(  775): Package has changed for user 0
D/EnterpriseDeviceManagerService(  775): Admin package name: com.google.android.gms
W/Resources(  775): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/ActivityManager(  775): Permission Denial: getCurrentUser() from pid=6117, uid=10016 requires android.permission.INTERACT_ACROSS_USERS
W/Resources(  775): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/dalvikvm(  775): GC_EXPLICIT freed 780K, 57% free 23625K/54572K, paused 6ms+21ms, total 218ms
D/PackageManager(  775): delete sourFile : 
D/dalvikvm( 6117): No JNI_OnLoad found in /system/lib/libsecure_storage_jni.so 0x4282cca8, skipping init
I/SecureStorage( 6117): [INFO]: SPID(0x00000000)Checking if this device supports Secure Storage
I/SecureStorage( 6117): [INFO]: SPID(0x00000000)This device supports Secure Storage
I/SecureStorage(  294): [INFO]: SPID(0x00000004)Credentials: uid 10016, gid 10016, pid 6117
I/SecureStorage(  294): [INFO]: SPID(0x00000004)Received function mask & code: 0000010C
I/SecureStorage( 6117): [INFO]: SPID(0x00000000)SS Daemon is running
D/PackageManager(  775): delete native library directory: 
I/SecureStorage( 6117): [INFO]: SPID(0x00000000)Processing data
I/SecureStorage(  294): [INFO]: SPID(0x00000004)Credentials: uid 10016, gid 10016, pid 6117
I/SecureStorage(  294): [INFO]: SPID(0x00000004)Received function mask & code: 00000106
D/PackageManager(  775): return delete result to caller: 1124149176
D/PackageManager(  775): returnCode: 1
D/AndroidRuntime( 6086): Shutting down VM
D/dalvikvm( 6086): GC_CONCURRENT freed 96K, 14% free 670K/772K, paused 1ms+1ms, total 3ms
I/PackageManager(  775):   Action: "android.intent.action.SENDTO"
I/PackageManager(  775):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  775):   Scheme: "sms"
I/PackageManager(  775): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
D/BackupManagerService(  775): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
V/BackupManagerService(  775): removePackageParticipantsLocked: uid=10179 #1
I/PackageManager(  775):   Action: "android.intent.action.SENDTO"
I/PackageManager(  775):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  775):   Scheme: "smsto"
I/PackageManager(  775): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
I/PackageManager(  775):   Action: "android.intent.action.SENDTO"
I/PackageManager(  775): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
I/PackageManager(  775):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  775):   Scheme: "mms"
W/Resources(  775): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
I/PackageManager(  775):   Action: "android.intent.action.SENDTO"
I/PackageManager(  775):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  775):   Scheme: "mmsto"
I/PackageManager(  775): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
W/Resources(  775): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  775): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  775): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  775): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/Launcher.HomeView( 1251): onStop
W/Resources(  775): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  775): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  775): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  775): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
W/Resources(  775): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  775): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  775): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
W/Resources(  775): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  775): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  775): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
I/CrashAnrDetector(  775): onPackageRemoved : com.test.thalitest
D/UsbSettingsManager(  775): clearDefaults: com.test.thalitest
D/InputReader(  775): Processing first event
W/ApplicationsProvider( 1409): Could not fetch usage stats
W/ApplicationsProvider( 1409): java.lang.SecurityException: Neither user 10020 nor current process has android.permission.PACKAGE_USAGE_STATS.
W/ApplicationsProvider( 1409): 	at android.os.Parcel.readException(Parcel.java:1465)
W/ApplicationsProvider( 1409): 	at android.os.Parcel.readException(Parcel.java:1419)
W/ApplicationsProvider( 1409): 	at com.android.internal.app.IUsageStats$Stub$Proxy.getAllPkgUsageStats(IUsageStats.java:317)
W/ApplicationsProvider( 1409): 	at android.app.ActivityManager.getAllPackageUsageStats(ActivityManager.java:2543)
W/ApplicationsProvider( 1409): 	at com.android.providers.applications.ApplicationsProvider.fetchUsageStats(ApplicationsProvider.java:681)
W/ApplicationsProvider( 1409): 	at com.android.providers.applications.ApplicationsProvider.updateApplicationsList(ApplicationsProvider.java:519)
W/ApplicationsProvider( 1409): 	at com.android.providers.applications.ApplicationsProvider.access$300(ApplicationsProvider.java:70)
W/ApplicationsProvider( 1409): 	at com.android.providers.applications.ApplicationsProvider$UpdateHandler.handleMessage(ApplicationsProvider.java:209)
W/ApplicationsProvider( 1409): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/ApplicationsProvider( 1409): 	at android.os.Looper.loop(Looper.java:146)
W/ApplicationsProvider( 1409): 	at android.os.HandlerThread.run(HandlerThread.java:61)

```
