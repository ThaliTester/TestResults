#### Test 5065027857de7f1_thali05_samsung-SM-G800H Logs


```
--------- beginning of /dev/log/system
W/ActivityManager(  740): Permission Denial: getCurrentUser() from pid=4526, uid=10035 requires android.permission.INTERACT_ACROSS_USERS
--------- beginning of /dev/log/main
W/ContextImpl( 4526): Implicit intents with startService are not safe: Intent { act=com.sec.android.service.health.cp.accesscontrol } android.content.ContextWrapper.bindService:529 com.samsung.android.sdk.health.content.ShealthAccessControl.startService:274 com.samsung.android.sdk.health.content.ShealthAccessControl.requestPermission:212 
I/SELinux ( 4546): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 4546):  
E/Device Type Shared Preferences( 4526): Device Type Shared Preferences - getDeviceTypeChecked -true
E/Device Type Shared Preferences( 4526): Device Type Shared Preferences - not connecting to service
E/com.sec.android.app.shealth.SHealthApplication( 4526): ContentProvider is not null
I/SELinux ( 4546): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 4546):  
I/SELinux ( 4546):  
I/SELinux ( 4546): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 4546): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 4546): >>>>> Normal User
E/dalvikvm( 4546): >>>>> com.sec.android.service.health [ userId:0 | appId:10016 ]
,E/SELinux ( 4546): [DEBUG] seapp_context_lookup: seinfoCategory = platform
D/TimaKeyStoreProvider( 4546): in addTimaSignatureService
D/TimaKeyStoreProvider( 4546): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 4546): Added TimaKesytore provider
V/MediaPlayer( 4526): decode(61, 33979084, 48105)
V/MediaPlayerService(  248): decode(35, 33979084, 48105)
V/MediaPlayerService(  248): player type = 3
V/AwesomePlayer(  248): setDefault
V/AwesomePlayer(  248): constructor
V/AwesomePlayer(  248): setDefault
V/AwesomePlayer(  248): reset_l()
V/AwesomePlayer(  248): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  248): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  248): mAudioTrackVector clear
V/AwesomePlayer(  248): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  248): mSecMediaClock clear
V/StagefrightPlayer(  248): StagefrightPlayer
V/AwesomePlayer(  248): setListener
V/StagefrightPlayer(  248): initCheck
V/AwesomePlayer(  248): setAudioSink
V/StagefrightPlayer(  248): setDataSource(35, 33979084, 48105)
V/AwesomePlayer(  248): reset_l()
V/AwesomePlayer(  248): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  248): notify(0xb7d906c8, 8, 0, 0)
V/AudioCache(  248): ignored
V/AwesomePlayer(  248): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  248): mAudioTrackVector clear
V/AwesomePlayer(  248): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  248): mSecMediaClock clear
I/FileSource(  248): [Read time] time (14490) us > 10000 us, request_size (27), read_size (27)
V/AwesomePlayer(  248): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer(  248): mBitrate = -1 bits/sec
V/AwesomePlayer(  248): current audio track index (0) is added to vector
V/AwesomePlayer(  248): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer(  248): AwesomePlayer::setDataSource_l():: This is not a DRM content
V/MediaPlayerService(  248): prepare
V/AwesomePlayer(  248): prepareAsync
V/MediaPlayerService(  248): wait for prepare
V/AwesomePlayer(  248): onPrepareAsyncEvent
I/SecMediaClock(  248): SecMediaClock constructor
I/SecMediaClock(  248): reset
V/AwesomePlayer(  248): initAudioDecoder
V/AwesomePlayer(  248): checkOffloadExceptions is true
I/OMXCodec(  248): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
I/OMX     (  248): mDispatchers.add
I/OMXCodec(  248): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec(  248): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec(  248): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec(  248): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/OMXCodec(  248): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer(  248): finishAsyncPrepare_l
V/AwesomePlayer(  248): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache(  248): notify(0xb7d906c8, 200, 973, 0)
V/AudioCache(  248): ignored
V/AwesomePlayer(  248): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  248): notify(0xb7d906c8, 5, 0, 0)
V/AudioCache(  248): ignored
V/AwesomePlayer(  248): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  248): notify(0xb7d906c8, 1, 0, 0)
V/AudioCache(  248): prepared
V/AudioCache(  248): wait - success
V/MediaPlayerService(  248): start
V/StagefrightPlayer(  248): start
V/AwesomePlayer(  248): play
V/AwesomePlayer(  248): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer(  248): startAudioPlayer_l, sendErrorNotification (0)
I/OMXCodec(  248): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec(  248): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec(  248): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/AudioPlayer(  248):  Audioplayer kKeyAudioPCMFormat:1, 2, 0
I/AudioPlayer(  248):  Audioplayer kKeyAudioPCMFormat read fail(2, 1)
V/AudioCache(  248): open(44100, 2, 0x0, 1, 4)
V/AwesomePlayer(  248): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache(  248): notify(0xb7d906c8, 6, 0, 0)
V/AudioCache(  248): ignored
V/AwesomePlayer(  248): addBatteryData
V/MediaPlayerService(  248): wait for playback complete
I/AudioPlayer(  248): First fillBuffer call!!
I/OMXCodec(  248): [OMX.google.vorbis.decoder] End Of Stream
V/AwesomePlayer(  248): postAudioEOS delayUs (0)
V/AwesomePlayer(  248): onCheckAudioStatus
V/AwesomePlayer(  248): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  248): onStreamDone
V/AwesomePlayer(  248): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  248): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  248): notify(0xb7d906c8, 2, 0, 0)
V/AudioCache(  248): playback complete - thread will wake up later
V/AwesomePlayer(  248): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  248): notify(0xb7d906c8, 7, 0, 0)
V/AudioCache(  248): ignored
V/AwesomePlayer(  248): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer(  248): addBatteryData
V/AudioCache(  248): wait - success
V/StagefrightPlayer(  248): reset
V/AwesomePlayer(  248): reset_l()
V/AwesomePlayer(  248): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  248): notify(0xb7d906c8, 8, 0, 0)
V/AudioCache(  248): ignored
V/AwesomePlayer(  248): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  248): mAudioTrackVector clear
I/OMXCodec(  248): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec(  248): [OMX.google.vorbis.decoder] stop() sendCommand(0x37, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec(  248): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
I/OMXCodec(  248): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/OMX     (  248): instance freeNode
I/AudioPlayer(  248): reset out
V/AwesomePlayer(  248): reset_l() mAudioPlayer successfully deleted
I/SecMediaClock(  248): SecMediaClock destructor
V/AwesomePlayer(  248): mSecMediaClock clear
V/StagefrightPlayer(  248): ~StagefrightPlayer
V/StagefrightPlayer(  248): reset
V/AwesomePlayer(  248): reset_l()
V/AwesomePlayer(  248): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  248): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  248): mAudioTrackVector clear
V/AwesomePlayer(  248): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  248): mSecMediaClock clear
V/AwesomePlayer(  248): destructor
V/AwesomePlayer(  248): reset_l()
V/AwesomePlayer(  248): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  248): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  248): mAudioTrackVector clear
V/AwesomePlayer(  248): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  248): mSecMediaClock clear
V/MediaPlayer( 4526): decode(63, 33914984, 10421)
V/MediaPlayerService(  248): decode(35, 33914984, 10421)
V/MediaPlayerService(  248): player type = 3
V/AwesomePlayer(  248): setDefault
V/AwesomePlayer(  248): constructor
V/AwesomePlayer(  248): setDefault
V/AwesomePlayer(  248): reset_l()
V/AwesomePlayer(  248): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  248): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  248): mAudioTrackVector clear
V/AwesomePlayer(  248): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  248): mSecMediaClock clear
V/StagefrightPlayer(  248): StagefrightPlayer
V/AwesomePlayer(  248): setListener
V/StagefrightPlayer(  248): initCheck
V/AwesomePlayer(  248): setAudioSink
V/StagefrightPlayer(  248): setDataSource(35, 33914984, 10421)
V/AwesomePlayer(  248): reset_l()
V/AwesomePlayer(  248): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  248): notify(0xb7d91b70, 8, 0, 0)
V/AudioCache(  248): ignored
V/AwesomePlayer(  248): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  248): mAudioTrackVector clear
V/AwesomePlayer(  248): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  248): mSecMediaClock clear
V/AwesomePlayer(  248): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer(  248): mBitrate = -1 bits/sec
V/AwesomePlayer(  248): current audio track index (0) is added to vector
V/AwesomePlayer(  248): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer(  248): AwesomePlayer::setDataSource_l():: This is not a DRM content
V/MediaPlayerService(  248): prepare
V/AwesomePlayer(  248): prepareAsync
V/MediaPlayerService(  248): wait for prepare
V/AwesomePlayer(  248): onPrepareAsyncEvent
I/SecMediaClock(  248): SecMediaClock constructor
I/SecMediaClock(  248): reset
V/AwesomePlayer(  248): initAudioDecoder
V/AwesomePlayer(  248): checkOffloadExceptions is true
I/OMXCodec(  248): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
I/OMX     (  248): mDispatchers.add
I/OMXCodec(  248): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec(  248): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec(  248): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec(  248): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/OMXCodec(  248): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer(  248): finishAsyncPrepare_l
V/AwesomePlayer(  248): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache(  248): notify(0xb7d91b70, 200, 973, 0)
V/AudioCache(  248): ignored
V/AwesomePlayer(  248): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  248): notify(0xb7d91b70, 5, 0, 0)
V/AudioCache(  248): ignored
V/AwesomePlayer(  248): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  248): notify(0xb7d91b70, 1, 0, 0)
V/AudioCache(  248): prepared
V/AudioCache(  248): wait - success
V/MediaPlayerService(  248): start
V/StagefrightPlayer(  248): start
V/AwesomePlayer(  248): play
V/AwesomePlayer(  248): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer(  248): startAudioPlayer_l, sendErrorNotification (0)
I/OMXCodec(  248): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec(  248): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec(  248): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/AudioPlayer(  248):  Audioplayer kKeyAudioPCMFormat:1, 2, 0
I/AudioPlayer(  248):  Audioplayer kKeyAudioPCMFormat read fail(2, 1)
V/AudioCache(  248): open(44100, 2, 0x0, 1, 4)
V/AwesomePlayer(  248): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache(  248): notify(0xb7d91b70, 6, 0, 0)
V/AudioCache(  248): ignored
V/AwesomePlayer(  248): addBatteryData
V/MediaPlayerService(  248): wait for playback complete
I/OMXCodec(  248): [OMX.google.vorbis.decoder] End Of Stream
V/AwesomePlayer(  248): postAudioEOS delayUs (0)
V/AwesomePlayer(  248): onCheckAudioStatus
V/AwesomePlayer(  248): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  248): onStreamDone
V/AwesomePlayer(  248): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  248): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  248): notify(0xb7d91b70, 2, 0, 0)
V/AudioCache(  248): playback complete - thread will wake up later
V/AwesomePlayer(  248): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  248): notify(0xb7d91b70, 7, 0, 0)
V/AudioCache(  248): ignored
V/AwesomePlayer(  248): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer(  248): addBatteryData
V/AudioCache(  248): wait - success
V/StagefrightPlayer(  248): reset
V/AwesomePlayer(  248): reset_l()
V/AwesomePlayer(  248): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  248): notify(0xb7d91b70, 8, 0, 0)
V/AudioCache(  248): ignored
V/AwesomePlayer(  248): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  248): mAudioTrackVector clear
I/OMXCodec(  248): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec(  248): [OMX.google.vorbis.decoder] stop() sendCommand(0x38, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec(  248): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
I/OMXCodec(  248): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/OMX     (  248): instance freeNode
I/AudioPlayer(  248): reset out
V/AwesomePlayer(  248): reset_l() mAudioPlayer successfully deleted
I/SecMediaClock(  248): SecMediaClock destructor
V/AwesomePlayer(  248): mSecMediaClock clear
V/StagefrightPlayer(  248): ~StagefrightPlayer
V/StagefrightPlayer(  248): reset
V/AwesomePlayer(  248): reset_l()
V/AwesomePlayer(  248): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  248): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  248): mAudioTrackVector clear
V/AwesomePlayer(  248): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  248): mSecMediaClock clear
V/AwesomePlayer(  248): destructor
V/AwesomePlayer(  248): reset_l()
V/AwesomePlayer(  248): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  248): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  248): mAudioTrackVector clear
V/AwesomePlayer(  248): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  248): mSecMediaClock clear
V/MediaPlayer( 4526): decode(64, 37457308, 34198)
V/MediaPlayerService(  248): decode(35, 37457308, 34198)
V/MediaPlayerService(  248): player type = 3
V/AwesomePlayer(  248): setDefault
V/AwesomePlayer(  248): constructor
V/AwesomePlayer(  248): setDefault
V/AwesomePlayer(  248): reset_l()
V/AwesomePlayer(  248): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  248): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  248): mAudioTrackVector clear
V/AwesomePlayer(  248): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  248): mSecMediaClock clear
V/StagefrightPlayer(  248): StagefrightPlayer
V/AwesomePlayer(  248): setListener
V/StagefrightPlayer(  248): initCheck
V/AwesomePlayer(  248): setAudioSink
V/StagefrightPlayer(  248): setDataSource(35, 37457308, 34198)
V/AwesomePlayer(  248): reset_l()
V/AwesomePlayer(  248): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  248): notify(0xb7da22f0, 8, 0, 0)
V/AudioCache(  248): ignored
V/AwesomePlayer(  248): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  248): mAudioTrackVector clear
V/AwesomePlayer(  248): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  248): mSecMediaClock clear
V/AwesomePlayer(  248): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer(  248): mBitrate = -1 bits/sec
V/AwesomePlayer(  248): current audio track index (0) is added to vector
V/AwesomePlayer(  248): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer(  248): AwesomePlayer::setDataSource_l():: This is not a DRM content
V/MediaPlayerService(  248): prepare
V/AwesomePlayer(  248): prepareAsync
V/MediaPlayerService(  248): wait for prepare
V/AwesomePlayer(  248): onPrepareAsyncEvent
I/SecMediaClock(  248): SecMediaClock constructor
I/SecMediaClock(  248): reset
V/AwesomePlayer(  248): initAudioDecoder
V/AwesomePlayer(  248): checkOffloadExceptions is true
I/OMXCodec(  248): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
I/OMX     (  248): mDispatchers.add
I/OMXCodec(  248): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec(  248): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec(  248): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec(  248): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/OMXCodec(  248): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer(  248): finishAsyncPrepare_l
V/AwesomePlayer(  248): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache(  248): notify(0xb7da22f0, 200, 973, 0)
V/AudioCache(  248): ignored
V/AwesomePlayer(  248): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  248): notify(0xb7da22f0, 5, 0, 0)
V/AudioCache(  248): ignored
V/AwesomePlayer(  248): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  248): notify(0xb7da22f0, 1, 0, 0)
V/AudioCache(  248): prepared
V/AudioCache(  248): wait - success
V/MediaPlayerService(  248): start
V/StagefrightPlayer(  248): start
V/AwesomePlayer(  248): play
W/ActivityManager(  740): Permission Denial: getCurrentUser() from pid=4546, uid=10016 requires android.permission.INTERACT_ACROSS_USERS
V/AwesomePlayer(  248): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer(  248): startAudioPlayer_l, sendErrorNotification (0)
I/OMXCodec(  248): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec(  248): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec(  248): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/AudioPlayer(  248):  Audioplayer kKeyAudioPCMFormat:1, 2, 0
I/AudioPlayer(  248):  Audioplayer kKeyAudioPCMFormat read fail(2, 1)
V/AudioCache(  248): open(44100, 2, 0x0, 1, 4)
V/AwesomePlayer(  248): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache(  248): notify(0xb7da22f0, 6, 0, 0)
V/AudioCache(  248): ignored
V/AwesomePlayer(  248): addBatteryData
V/MediaPlayerService(  248): wait for playback complete
I/OMXCodec(  248): [OMX.google.vorbis.decoder] End Of Stream
V/AwesomePlayer(  248): postAudioEOS delayUs (0)
V/AwesomePlayer(  248): onCheckAudioStatus
V/AwesomePlayer(  248): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  248): onStreamDone
V/AwesomePlayer(  248): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  248): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  248): notify(0xb7da22f0, 2, 0, 0)
V/AudioCache(  248): playback complete - thread will wake up later
V/AwesomePlayer(  248): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  248): notify(0xb7da22f0, 7, 0, 0)
V/AudioCache(  248): ignored
V/AwesomePlayer(  248): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer(  248): addBatteryData
V/AudioCache(  248): wait - success
V/StagefrightPlayer(  248): reset
V/AwesomePlayer(  248): reset_l()
V/AwesomePlayer(  248): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  248): notify(0xb7da22f0, 8, 0, 0)
V/AudioCache(  248): ignored
V/AwesomePlayer(  248): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  248): mAudioTrackVector clear
I/OMXCodec(  248): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec(  248): [OMX.google.vorbis.decoder] stop() sendCommand(0x39, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec(  248): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
I/OMXCodec(  248): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/OMX     (  248): instance freeNode
I/AudioPlayer(  248): reset out
V/AwesomePlayer(  248): reset_l() mAudioPlayer successfully deleted
I/SecMediaClock(  248): SecMediaClock destructor
V/AwesomePlayer(  248): mSecMediaClock clear
V/StagefrightPlayer(  248): ~StagefrightPlayer
V/StagefrightPlayer(  248): reset
V/AwesomePlayer(  248): reset_l()
V/AwesomePlayer(  248): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  248): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  248): mAudioTrackVector clear
V/AwesomePlayer(  248): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  248): mSecMediaClock clear
V/AwesomePlayer(  248): destructor
V/AwesomePlayer(  248): reset_l()
V/AwesomePlayer(  248): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  248): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  248): mAudioTrackVector clear
V/AwesomePlayer(  248): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  248): mSecMediaClock clear
V/MediaPlayer( 4526): decode(65, 33862452, 7405)
V/MediaPlayerService(  248): decode(35, 33862452, 7405)
D/dalvikvm( 4546): No JNI_OnLoad found in /system/lib/libsecure_storage_jni.so 0x425d6c98, skipping init
I/SecureStorage( 4546): [INFO]: SPID(0x00000000)Checking if this device supports Secure Storage
I/SecureStorage( 4546): [INFO]: SPID(0x00000000)This device supports Secure Storage
V/MediaPlayerService(  248): player type = 3
V/AwesomePlayer(  248): setDefault
V/AwesomePlayer(  248): constructor
V/AwesomePlayer(  248): setDefault
V/AwesomePlayer(  248): reset_l()
V/AwesomePlayer(  248): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  248): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  248): mAudioTrackVector clear
V/AwesomePlayer(  248): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  248): mSecMediaClock clear
V/StagefrightPlayer(  248): StagefrightPlayer
V/AwesomePlayer(  248): setListener
V/StagefrightPlayer(  248): initCheck
V/AwesomePlayer(  248): setAudioSink
V/StagefrightPlayer(  248): setDataSource(35, 33862452, 7405)
V/AwesomePlayer(  248): reset_l()
V/AwesomePlayer(  248): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
I/SecureStorage(  297): [INFO]: SPID(0x00000003)Credentials: uid 10016, gid 10016, pid 4546
I/SecureStorage(  297): [INFO]: SPID(0x00000003)Received function mask & code: 0000010C
I/SecureStorage( 4546): [INFO]: SPID(0x00000000)SS Daemon is running
V/AudioCache(  248): notify(0xb7da79a8, 8, 0, 0)
V/AudioCache(  248): ignored
V/AwesomePlayer(  248): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  248): mAudioTrackVector clear
V/AwesomePlayer(  248): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  248): mSecMediaClock clear
V/AwesomePlayer(  248): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer(  248): mBitrate = -1 bits/sec
V/AwesomePlayer(  248): current audio track index (0) is added to vector
V/AwesomePlayer(  248): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer(  248): AwesomePlayer::setDataSource_l():: This is not a DRM content
V/MediaPlayerService(  248): prepare
V/AwesomePlayer(  248): prepareAsync
V/MediaPlayerService(  248): wait for prepare
V/AwesomePlayer(  248): onPrepareAsyncEvent
I/SecMediaClock(  248): SecMediaClock constructor
I/SecMediaClock(  248): reset
V/AwesomePlayer(  248): initAudioDecoder
V/AwesomePlayer(  248): checkOffloadExceptions is true
I/OMXCodec(  248): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
I/OMX     (  248): mDispatchers.add
I/OMXCodec(  248): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec(  248): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec(  248): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec(  248): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/OMXCodec(  248): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer(  248): finishAsyncPrepare_l
V/AwesomePlayer(  248): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache(  248): notify(0xb7da79a8, 200, 973, 0)
V/AudioCache(  248): ignored
V/AwesomePlayer(  248): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  248): notify(0xb7da79a8, 5, 0, 0)
V/AudioCache(  248): ignored
V/AwesomePlayer(  248): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  248): notify(0xb7da79a8, 1, 0, 0)
V/AudioCache(  248): prepared
V/AudioCache(  248): wait - success
V/MediaPlayerService(  248): start
V/StagefrightPlayer(  248): start
V/AwesomePlayer(  248): play
V/AwesomePlayer(  248): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer(  248): startAudioPlayer_l, sendErrorNotification (0)
I/SecureStorage( 4546): [INFO]: SPID(0x00000000)Processing data
I/SecureStorage(  297): [INFO]: SPID(0x00000003)Credentials: uid 10016, gid 10016, pid 4546
I/SecureStorage(  297): [INFO]: SPID(0x00000003)Received function mask & code: 00000106
I/OMXCodec(  248): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec(  248): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec(  248): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/AudioPlayer(  248):  Audioplayer kKeyAudioPCMFormat:1, 2, 0
I/AudioPlayer(  248):  Audioplayer kKeyAudioPCMFormat read fail(2, 1)
V/AudioCache(  248): open(44100, 2, 0x0, 1, 4)
V/AwesomePlayer(  248): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache(  248): notify(0xb7da79a8, 6, 0, 0)
V/AudioCache(  248): ignored
V/AwesomePlayer(  248): addBatteryData
V/MediaPlayerService(  248): wait for playback complete
I/OMXCodec(  248): [OMX.google.vorbis.decoder] End Of Stream
V/AwesomePlayer(  248): postAudioEOS delayUs (0)
V/AwesomePlayer(  248): onCheckAudioStatus
V/AwesomePlayer(  248): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  248): onStreamDone
V/AwesomePlayer(  248): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  248): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  248): notify(0xb7da79a8, 2, 0, 0)
V/AudioCache(  248): playback complete - thread will wake up later
V/AwesomePlayer(  248): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  248): notify(0xb7da79a8, 7, 0, 0)
V/AudioCache(  248): ignored
V/AwesomePlayer(  248): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer(  248): addBatteryData
V/AudioCache(  248): wait - success
V/StagefrightPlayer(  248): reset
V/AwesomePlayer(  248): reset_l()
V/AwesomePlayer(  248): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  248): notify(0xb7da79a8, 8, 0, 0)
V/AudioCache(  248): ignored
V/AwesomePlayer(  248): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  248): mAudioTrackVector clear
I/OMXCodec(  248): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec(  248): [OMX.google.vorbis.decoder] stop() sendCommand(0x3a, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec(  248): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
I/OMXCodec(  248): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/OMX     (  248): instance freeNode
I/AudioPlayer(  248): reset out
V/AwesomePlayer(  248): reset_l() mAudioPlayer successfully deleted
I/SecMediaClock(  248): SecMediaClock destructor
V/AwesomePlayer(  248): mSecMediaClock clear
V/StagefrightPlayer(  248): ~StagefrightPlayer
V/StagefrightPlayer(  248): reset
V/AwesomePlayer(  248): reset_l()
V/AwesomePlayer(  248): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  248): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  248): mAudioTrackVector clear
V/AwesomePlayer(  248): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  248): mSecMediaClock clear
V/AwesomePlayer(  248): destructor
V/AwesomePlayer(  248): reset_l()
V/AwesomePlayer(  248): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  248): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  248): mAudioTrackVector clear
V/AwesomePlayer(  248): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  248): mSecMediaClock clear
V/MediaPlayer( 4526): decode(66, 37547940, 5555)
V/MediaPlayerService(  248): decode(35, 37547940, 5555)
V/MediaPlayerService(  248): player type = 3
V/AwesomePlayer(  248): setDefault
V/AwesomePlayer(  248): constructor
V/AwesomePlayer(  248): setDefault
V/AwesomePlayer(  248): reset_l()
V/AwesomePlayer(  248): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  248): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  248): mAudioTrackVector clear
V/AwesomePlayer(  248): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  248): mSecMediaClock clear
V/StagefrightPlayer(  248): StagefrightPlayer
V/AwesomePlayer(  248): setListener
V/StagefrightPlayer(  248): initCheck
V/AwesomePlayer(  248): setAudioSink
V/StagefrightPlayer(  248): setDataSource(35, 37547940, 5555)
V/AwesomePlayer(  248): reset_l()
V/AwesomePlayer(  248): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  248): notify(0xb7d9ab60, 8, 0, 0)
V/AudioCache(  248): ignored
V/AwesomePlayer(  248): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  248): mAudioTrackVector clear
V/AwesomePlayer(  248): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  248): mSecMediaClock clear
V/AwesomePlayer(  248): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer(  248): mBitrate = -1 bits/sec
V/AwesomePlayer(  248): current audio track index (0) is added to vector
V/AwesomePlayer(  248): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer(  248): AwesomePlayer::setDataSource_l():: This is not a DRM content
V/MediaPlayerService(  248): prepare
V/AwesomePlayer(  248): prepareAsync
V/MediaPlayerService(  248): wait for prepare
V/AwesomePlayer(  248): onPrepareAsyncEvent
I/SecMediaClock(  248): SecMediaClock constructor
I/SecMediaClock(  248): reset
V/AwesomePlayer(  248): initAudioDecoder
V/AwesomePlayer(  248): checkOffloadExceptions is true
I/OMXCodec(  248): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
I/OMX     (  248): mDispatchers.add
I/OMXCodec(  248): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec(  248): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec(  248): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec(  248): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/OMXCodec(  248): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer(  248): finishAsyncPrepare_l
V/AwesomePlayer(  248): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache(  248): notify(0xb7d9ab60, 200, 973, 0)
V/AudioCache(  248): ignored
V/AwesomePlayer(  248): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  248): notify(0xb7d9ab60, 5, 0, 0)
V/AudioCache(  248): ignored
V/AwesomePlayer(  248): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  248): notify(0xb7d9ab60, 1, 0, 0)
V/AudioCache(  248): prepared
V/AudioCache(  248): wait - success
V/MediaPlayerService(  248): start
V/StagefrightPlayer(  248): start
V/AwesomePlayer(  248): play
V/AwesomePlayer(  248): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer(  248): startAudioPlayer_l, sendErrorNotification (0)
I/OMXCodec(  248): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec(  248): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec(  248): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/AudioPlayer(  248):  Audioplayer kKeyAudioPCMFormat:1, 2, 0
I/AudioPlayer(  248):  Audioplayer kKeyAudioPCMFormat read fail(2, 1)
V/AudioCache(  248): open(44100, 2, 0x0, 1, 4)
V/AwesomePlayer(  248): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache(  248): notify(0xb7d9ab60, 6, 0, 0)
V/AudioCache(  248): ignored
V/AwesomePlayer(  248): addBatteryData
V/MediaPlayerService(  248): wait for playback complete
I/OMXCodec(  248): [OMX.google.vorbis.decoder] End Of Stream
V/AwesomePlayer(  248): postAudioEOS delayUs (0)
V/AwesomePlayer(  248): onCheckAudioStatus
V/AwesomePlayer(  248): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  248): onStreamDone
V/AwesomePlayer(  248): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  248): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  248): notify(0xb7d9ab60, 2, 0, 0)
V/AudioCache(  248): playback complete - thread will wake up later
V/AwesomePlayer(  248): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  248): notify(0xb7d9ab60, 7, 0, 0)
V/AudioCache(  248): ignored
V/AwesomePlayer(  248): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer(  248): addBatteryData
V/AudioCache(  248): wait - success
V/StagefrightPlayer(  248): reset
V/AwesomePlayer(  248): reset_l()
V/AwesomePlayer(  248): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  248): notify(0xb7d9ab60, 8, 0, 0)
V/AudioCache(  248): ignored
V/AwesomePlayer(  248): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  248): mAudioTrackVector clear
I/OMXCodec(  248): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec(  248): [OMX.google.vorbis.decoder] stop() sendCommand(0x3b, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec(  248): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
I/OMXCodec(  248): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/OMX     (  248): instance freeNode
I/AudioPlayer(  248): reset out
V/AwesomePlayer(  248): reset_l() mAudioPlayer successfully deleted
I/SecMediaClock(  248): SecMediaClock destructor
V/AwesomePlayer(  248): mSecMediaClock clear
V/StagefrightPlayer(  248): ~StagefrightPlayer
V/StagefrightPlayer(  248): reset
V/AwesomePlayer(  248): reset_l()
V/AwesomePlayer(  248): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  248): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  248): mAudioTrackVector clear
V/AwesomePlayer(  248): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  248): mSecMediaClock clear
V/AwesomePlayer(  248): destructor
V/AwesomePlayer(  248): reset_l()
V/AwesomePlayer(  248): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  248): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  248): mAudioTrackVector clear
V/AwesomePlayer(  248): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  248): mSecMediaClock clear
V/MediaPlayer( 4526): decode(67, 30367732, 5085)
V/MediaPlayerService(  248): decode(35, 30367732, 5085)
V/MediaPlayerService(  248): player type = 3
V/AwesomePlayer(  248): setDefault
V/AwesomePlayer(  248): constructor
V/AwesomePlayer(  248): setDefault
V/AwesomePlayer(  248): reset_l()
V/AwesomePlayer(  248): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  248): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  248): mAudioTrackVector clear
V/AwesomePlayer(  248): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  248): mSecMediaClock clear
V/StagefrightPlayer(  248): StagefrightPlayer
V/AwesomePlayer(  248): setListener
V/StagefrightPlayer(  248): initCheck
V/AwesomePlayer(  248): setAudioSink
V/StagefrightPlayer(  248): setDataSource(35, 30367732, 5085)
V/AwesomePlayer(  248): reset_l()
V/AwesomePlayer(  248): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  248): notify(0xb7da6538, 8, 0, 0)
V/AudioCache(  248): ignored
V/AwesomePlayer(  248): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  248): mAudioTrackVector clear
V/AwesomePlayer(  248): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  248): mSecMediaClock clear
V/AwesomePlayer(  248): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer(  248): mBitrate = -1 bits/sec
V/AwesomePlayer(  248): current audio track index (0) is added to vector
V/AwesomePlayer(  248): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer(  248): AwesomePlayer::setDataSource_l():: This is not a DRM content
V/MediaPlayerService(  248): prepare
V/AwesomePlayer(  248): prepareAsync
V/MediaPlayerService(  248): wait for prepare
V/AwesomePlayer(  248): onPrepareAsyncEvent
I/SecMediaClock(  248): SecMediaClock constructor
I/SecMediaClock(  248): reset
V/AwesomePlayer(  248): initAudioDecoder
V/AwesomePlayer(  248): checkOffloadExceptions is true
I/OMXCodec(  248): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
I/OMX     (  248): mDispatchers.add
I/OMXCodec(  248): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec(  248): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec(  248): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec(  248): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/OMXCodec(  248): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer(  248): finishAsyncPrepare_l
V/AwesomePlayer(  248): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache(  248): notify(0xb7da6538, 200, 973, 0)
V/AudioCache(  248): ignored
V/AwesomePlayer(  248): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  248): notify(0xb7da6538, 5, 0, 0)
V/AudioCache(  248): ignored
V/AwesomePlayer(  248): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  248): notify(0xb7da6538, 1, 0, 0)
V/AudioCache(  248): prepared
V/AudioCache(  248): wait - success
V/MediaPlayerService(  248): start
V/StagefrightPlayer(  248): start
V/AwesomePlayer(  248): play
V/AwesomePlayer(  248): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer(  248): startAudioPlayer_l, sendErrorNotification (0)
I/OMXCodec(  248): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec(  248): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec(  248): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/AudioPlayer(  248):  Audioplayer kKeyAudioPCMFormat:1, 2, 0
I/AudioPlayer(  248):  Audioplayer kKeyAudioPCMFormat read fail(2, 1)
V/AudioCache(  248): open(44100, 2, 0x0, 1, 4)
V/AwesomePlayer(  248): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache(  248): notify(0xb7da6538, 6, 0, 0)
V/AudioCache(  248): ignored
V/AwesomePlayer(  248): addBatteryData
V/MediaPlayerService(  248): wait for playback complete
I/AudioPlayer(  248): First fillBuffer call!!
I/OMXCodec(  248): [OMX.google.vorbis.decoder] End Of Stream
V/AwesomePlayer(  248): postAudioEOS delayUs (0)
V/AwesomePlayer(  248): onCheckAudioStatus
V/AwesomePlayer(  248): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  248): onStreamDone
V/AwesomePlayer(  248): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  248): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  248): notify(0xb7da6538, 2, 0, 0)
V/AudioCache(  248): playback complete - thread will wake up later
V/AwesomePlayer(  248): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  248): notify(0xb7da6538, 7, 0, 0)
V/AudioCache(  248): ignored
V/AwesomePlayer(  248): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer(  248): addBatteryData
V/AudioCache(  248): wait - success
V/StagefrightPlayer(  248): reset
V/AwesomePlayer(  248): reset_l()
V/AwesomePlayer(  248): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  248): notify(0xb7da6538, 8, 0, 0)
V/AudioCache(  248): ignored
V/AwesomePlayer(  248): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  248): mAudioTrackVector clear
I/OMXCodec(  248): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec(  248): [OMX.google.vorbis.decoder] stop() sendCommand(0x3c, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec(  248): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
I/OMXCodec(  248): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/OMX     (  248): instance freeNode
I/AudioPlayer(  248): reset out
V/AwesomePlayer(  248): reset_l() mAudioPlayer successfully deleted
I/SecMediaClock(  248): SecMediaClock destructor
V/AwesomePlayer(  248): mSecMediaClock clear
V/StagefrightPlayer(  248): ~StagefrightPlayer
V/StagefrightPlayer(  248): reset
V/AwesomePlayer(  248): reset_l()
V/AwesomePlayer(  248): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  248): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  248): mAudioTrackVector clear
V/AwesomePlayer(  248): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  248): mSecMediaClock clear
V/AwesomePlayer(  248): destructor
V/AwesomePlayer(  248): reset_l()
V/AwesomePlayer(  248): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  248): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  248): mAudioTrackVector clear
V/AwesomePlayer(  248): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  248): mSecMediaClock clear
V/MediaPlayer( 4526): decode(68, 30372876, 21552)
V/MediaPlayerService(  248): decode(35, 30372876, 21552)
V/MediaPlayerService(  248): player type = 3
V/AwesomePlayer(  248): setDefault
V/AwesomePlayer(  248): constructor
V/AwesomePlayer(  248): setDefault
V/AwesomePlayer(  248): reset_l()
V/AwesomePlayer(  248): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  248): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  248): mAudioTrackVector clear
V/AwesomePlayer(  248): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  248): mSecMediaClock clear
V/StagefrightPlayer(  248): StagefrightPlayer
V/AwesomePlayer(  248): setListener
V/StagefrightPlayer(  248): initCheck
V/AwesomePlayer(  248): setAudioSink
V/StagefrightPlayer(  248): setDataSource(35, 30372876, 21552)
V/AwesomePlayer(  248): reset_l()
V/AwesomePlayer(  248): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  248): notify(0xb7d9ab60, 8, 0, 0)
V/AudioCache(  248): ignored
V/AwesomePlayer(  248): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  248): mAudioTrackVector clear
V/AwesomePlayer(  248): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  248): mSecMediaClock clear
V/AwesomePlayer(  248): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer(  248): mBitrate = -1 bits/sec
V/AwesomePlayer(  248): current audio track index (0) is added to vector
V/AwesomePlayer(  248): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer(  248): AwesomePlayer::setDataSource_l():: This is not a DRM content
V/MediaPlayerService(  248): prepare
V/AwesomePlayer(  248): prepareAsync
V/MediaPlayerService(  248): wait for prepare
V/AwesomePlayer(  248): onPrepareAsyncEvent
I/SecMediaClock(  248): SecMediaClock constructor
I/SecMediaClock(  248): reset
V/AwesomePlayer(  248): initAudioDecoder
V/AwesomePlayer(  248): checkOffloadExceptions is true
I/OMXCodec(  248): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
I/OMX     (  248): mDispatchers.add
I/OMXCodec(  248): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec(  248): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec(  248): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec(  248): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/OMXCodec(  248): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer(  248): finishAsyncPrepare_l
V/AwesomePlayer(  248): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache(  248): notify(0xb7d9ab60, 200, 973, 0)
V/AudioCache(  248): ignored
V/AwesomePlayer(  248): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  248): notify(0xb7d9ab60, 5, 0, 0)
V/AudioCache(  248): ignored
V/AwesomePlayer(  248): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  248): notify(0xb7d9ab60, 1, 0, 0)
V/AudioCache(  248): prepared
V/AudioCache(  248): wait - success
V/MediaPlayerService(  248): start
V/StagefrightPlayer(  248): start
V/AwesomePlayer(  248): play
V/AwesomePlayer(  248): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer(  248): startAudioPlayer_l, sendErrorNotification (0)
I/OMXCodec(  248): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec(  248): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec(  248): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/AudioPlayer(  248):  Audioplayer kKeyAudioPCMFormat:1, 2, 0
I/AudioPlayer(  248):  Audioplayer kKeyAudioPCMFormat read fail(2, 1)
V/AudioCache(  248): open(44100, 2, 0x0, 1, 4)
V/AwesomePlayer(  248): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache(  248): notify(0xb7d9ab60, 6, 0, 0)
V/AudioCache(  248): ignored
V/AwesomePlayer(  248): addBatteryData
V/MediaPlayerService(  248): wait for playback complete
D/AndroidRuntime( 4570): 
D/AndroidRuntime( 4570): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 4570): CheckJNI is OFF
D/AndroidRuntime( 4570): setted country_code = Poland
D/AndroidRuntime( 4570): setted countryiso_code = PL
D/AndroidRuntime( 4570): setted sales_code = XEO
D/AndroidRuntime( 4570): readGMSProperty: start
D/AndroidRuntime( 4570): readGMSProperty: already setted!!
D/AndroidRuntime( 4570): readGMSProperty: end
D/AndroidRuntime( 4570): addProductProperty: start
I/OMXCodec(  248): [OMX.google.vorbis.decoder] End Of Stream
V/AwesomePlayer(  248): postAudioEOS delayUs (0)
V/AwesomePlayer(  248): onCheckAudioStatus
V/AwesomePlayer(  248): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  248): onStreamDone
V/AwesomePlayer(  248): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  248): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  248): notify(0xb7d9ab60, 2, 0, 0)
V/AudioCache(  248): playback complete - thread will wake up later
V/AwesomePlayer(  248): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  248): notify(0xb7d9ab60, 7, 0, 0)
V/AudioCache(  248): ignored
V/AwesomePlayer(  248): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer(  248): addBatteryData
V/AudioCache(  248): wait - success
V/StagefrightPlayer(  248): reset
V/AwesomePlayer(  248): reset_l()
V/AwesomePlayer(  248): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  248): notify(0xb7d9ab60, 8, 0, 0)
V/AudioCache(  248): ignored
V/AwesomePlayer(  248): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  248): mAudioTrackVector clear
I/OMXCodec(  248): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec(  248): [OMX.google.vorbis.decoder] stop() sendCommand(0x3d, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec(  248): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
D/dalvikvm( 4570): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 4570): Added shared lib libjavacore.so 0x0
D/dalvikvm( 4570): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 4570): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 4570): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
I/OMXCodec(  248): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/OMX     (  248): instance freeNode
I/AudioPlayer(  248): reset out
V/AwesomePlayer(  248): reset_l() mAudioPlayer successfully deleted
I/SecMediaClock(  248): SecMediaClock destructor
V/AwesomePlayer(  248): mSecMediaClock clear
V/StagefrightPlayer(  248): ~StagefrightPlayer
V/StagefrightPlayer(  248): reset
V/AwesomePlayer(  248): reset_l()
V/AwesomePlayer(  248): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  248): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  248): mAudioTrackVector clear
V/AwesomePlayer(  248): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  248): mSecMediaClock clear
V/AwesomePlayer(  248): destructor
V/AwesomePlayer(  248): reset_l()
V/AwesomePlayer(  248): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  248): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  248): mAudioTrackVector clear
V/AwesomePlayer(  248): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  248): mSecMediaClock clear
V/MediaPlayer( 4526): decode(69, 37543652, 4230)
V/MediaPlayerService(  248): decode(35, 37543652, 4230)
V/MediaPlayerService(  248): player type = 3
V/AwesomePlayer(  248): setDefault
V/AwesomePlayer(  248): constructor
V/AwesomePlayer(  248): setDefault
V/AwesomePlayer(  248): reset_l()
V/AwesomePlayer(  248): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  248): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  248): mAudioTrackVector clear
V/AwesomePlayer(  248): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  248): mSecMediaClock clear
V/StagefrightPlayer(  248): StagefrightPlayer
V/AwesomePlayer(  248): setListener
V/StagefrightPlayer(  248): initCheck
V/AwesomePlayer(  248): setAudioSink
V/StagefrightPlayer(  248): setDataSource(35, 37543652, 4230)
V/AwesomePlayer(  248): reset_l()
V/AwesomePlayer(  248): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  248): notify(0xb7da6438, 8, 0, 0)
V/AudioCache(  248): ignored
V/AwesomePlayer(  248): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  248): mAudioTrackVector clear
V/AwesomePlayer(  248): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  248): mSecMediaClock clear
V/AwesomePlayer(  248): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer(  248): mBitrate = -1 bits/sec
V/AwesomePlayer(  248): current audio track index (0) is added to vector
V/AwesomePlayer(  248): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer(  248): AwesomePlayer::setDataSource_l():: This is not a DRM content
V/MediaPlayerService(  248): prepare
V/AwesomePlayer(  248): prepareAsync
V/MediaPlayerService(  248): wait for prepare
V/AwesomePlayer(  248): onPrepareAsyncEvent
I/SecMediaClock(  248): SecMediaClock constructor
I/SecMediaClock(  248): reset
V/AwesomePlayer(  248): initAudioDecoder
V/AwesomePlayer(  248): checkOffloadExceptions is true
I/OMXCodec(  248): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
I/OMX     (  248): mDispatchers.add
I/OMXCodec(  248): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec(  248): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec(  248): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec(  248): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/OMXCodec(  248): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer(  248): finishAsyncPrepare_l
V/AwesomePlayer(  248): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache(  248): notify(0xb7da6438, 200, 973, 0)
V/AudioCache(  248): ignored
V/AwesomePlayer(  248): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  248): notify(0xb7da6438, 5, 0, 0)
V/AudioCache(  248): ignored
V/AwesomePlayer(  248): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  248): notify(0xb7da6438, 1, 0, 0)
V/AudioCache(  248): prepared
V/AudioCache(  248): wait - success
V/MediaPlayerService(  248): start
V/StagefrightPlayer(  248): start
V/AwesomePlayer(  248): play
V/AwesomePlayer(  248): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer(  248): startAudioPlayer_l, sendErrorNotification (0)
I/OMXCodec(  248): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec(  248): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec(  248): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/OMXCodec(  248): [OMX.google.vorbis.decoder] End Of Stream
I/AudioPlayer(  248):  Audioplayer kKeyAudioPCMFormat:1, 1, 0
I/AudioPlayer(  248):  Audioplayer kKeyAudioPCMFormat read fail(1, 1)
V/AudioCache(  248): open(44100, 1, 0x0, 1, 4)
V/AwesomePlayer(  248): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache(  248): notify(0xb7da6438, 6, 0, 0)
V/AudioCache(  248): ignored
V/AwesomePlayer(  248): addBatteryData
V/MediaPlayerService(  248): wait for playback complete
V/AwesomePlayer(  248): postAudioEOS delayUs (0)
V/AwesomePlayer(  248): onCheckAudioStatus
V/AwesomePlayer(  248): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  248): onStreamDone
V/AwesomePlayer(  248): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  248): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  248): notify(0xb7da6438, 2, 0, 0)
V/AudioCache(  248): playback complete - thread will wake up later
V/AwesomePlayer(  248): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  248): notify(0xb7da6438, 7, 0, 0)
V/AudioCache(  248): ignored
V/AwesomePlayer(  248): cancelPlayerEvents (keepNotifications=1)
V/AudioCache(  248): wait - success
V/StagefrightPlayer(  248): reset
V/AwesomePlayer(  248): addBatteryData
V/AwesomePlayer(  248): reset_l()
V/AwesomePlayer(  248): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  248): notify(0xb7da6438, 8, 0, 0)
V/AudioCache(  248): ignored
V/AwesomePlayer(  248): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  248): mAudioTrackVector clear
I/OMXCodec(  248): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec(  248): [OMX.google.vorbis.decoder] stop() sendCommand(0x3e, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec(  248): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
I/OMXCodec(  248): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/OMX     (  248): instance freeNode
I/AudioPlayer(  248): reset out
V/AwesomePlayer(  248): reset_l() mAudioPlayer successfully deleted
I/SecMediaClock(  248): SecMediaClock destructor
V/AwesomePlayer(  248): mSecMediaClock clear
V/StagefrightPlayer(  248): ~StagefrightPlayer
V/StagefrightPlayer(  248): reset
V/AwesomePlayer(  248): reset_l()
V/AwesomePlayer(  248): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  248): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  248): mAudioTrackVector clear
V/AwesomePlayer(  248): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  248): mSecMediaClock clear
V/AwesomePlayer(  248): destructor
V/AwesomePlayer(  248): reset_l()
V/AwesomePlayer(  248): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  248): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  248): mAudioTrackVector clear
V/AwesomePlayer(  248): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  248): mSecMediaClock clear
V/MediaPlayer( 4526): decode(70, 30337076, 9400)
V/MediaPlayerService(  248): decode(36, 30337076, 9400)
V/MediaPlayerService(  248): player type = 3
V/AwesomePlayer(  248): setDefault
V/AwesomePlayer(  248): constructor
V/AwesomePlayer(  248): setDefault
V/AwesomePlayer(  248): reset_l()
V/AwesomePlayer(  248): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  248): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  248): mAudioTrackVector clear
V/AwesomePlayer(  248): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  248): mSecMediaClock clear
V/StagefrightPlayer(  248): StagefrightPlayer
V/AwesomePlayer(  248): setListener
V/StagefrightPlayer(  248): initCheck
V/AwesomePlayer(  248): setAudioSink
V/StagefrightPlayer(  248): setDataSource(36, 30337076, 9400)
V/AwesomePlayer(  248): reset_l()
V/AwesomePlayer(  248): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  248): notify(0xb7dab6f8, 8, 0, 0)
V/AudioCache(  248): ignored
V/AwesomePlayer(  248): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  248): mAudioTrackVector clear
V/AwesomePlayer(  248): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  248): mSecMediaClock clear
V/AwesomePlayer(  248): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer(  248): mBitrate = -1 bits/sec
V/AwesomePlayer(  248): current audio track index (0) is added to vector
V/AwesomePlayer(  248): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer(  248): AwesomePlayer::setDataSource_l():: This is not a DRM content
V/MediaPlayerService(  248): prepare
V/AwesomePlayer(  248): prepareAsync
V/MediaPlayerService(  248): wait for prepare
V/AwesomePlayer(  248): onPrepareAsyncEvent
I/SecMediaClock(  248): SecMediaClock constructor
I/SecMediaClock(  248): reset
V/AwesomePlayer(  248): initAudioDecoder
V/AwesomePlayer(  248): checkOffloadExceptions is true
I/OMXCodec(  248): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
I/OMX     (  248): mDispatchers.add
I/OMXCodec(  248): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec(  248): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec(  248): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec(  248): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/OMXCodec(  248): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer(  248): finishAsyncPrepare_l
V/AwesomePlayer(  248): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache(  248): notify(0xb7dab6f8, 200, 973, 0)
V/AudioCache(  248): ignored
V/AwesomePlayer(  248): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  248): notify(0xb7dab6f8, 5, 0, 0)
V/AudioCache(  248): ignored
V/AwesomePlayer(  248): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  248): notify(0xb7dab6f8, 1, 0, 0)
V/AudioCache(  248): prepared
V/AudioCache(  248): wait - success
V/MediaPlayerService(  248): start
V/StagefrightPlayer(  248): start
V/AwesomePlayer(  248): play
V/AwesomePlayer(  248): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer(  248): startAudioPlayer_l, sendErrorNotification (0)
I/OMXCodec(  248): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec(  248): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec(  248): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/AudioPlayer(  248):  Audioplayer kKeyAudioPCMFormat:1, 1, 0
I/AudioPlayer(  248):  Audioplayer kKeyAudioPCMFormat read fail(1, 1)
V/AudioCache(  248): open(44100, 1, 0x0, 1, 4)
V/AwesomePlayer(  248): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache(  248): notify(0xb7dab6f8, 6, 0, 0)
V/AudioCache(  248): ignored
V/AwesomePlayer(  248): addBatteryData
V/MediaPlayerService(  248): wait for playback complete
I/SELinux ( 4621): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 4621):  
I/ActivityManager(  740): Killing 3123:com.sec.android.app.mt/1000 (adj 15): empty #43
I/OMXCodec(  248): [OMX.google.vorbis.decoder] End Of Stream
V/AwesomePlayer(  248): postAudioEOS delayUs (0)
V/AwesomePlayer(  248): onCheckAudioStatus
V/AwesomePlayer(  248): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  248): onStreamDone
V/AwesomePlayer(  248): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  248): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  248): notify(0xb7dab6f8, 2, 0, 0)
V/AudioCache(  248): playback complete - thread will wake up later
V/AwesomePlayer(  248): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  248): notify(0xb7dab6f8, 7, 0, 0)
V/AudioCache(  248): ignored
V/AwesomePlayer(  248): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer(  248): addBatteryData
V/AudioCache(  248): wait - success
V/StagefrightPlayer(  248): reset
V/AwesomePlayer(  248): reset_l()
V/AwesomePlayer(  248): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  248): notify(0xb7dab6f8, 8, 0, 0)
V/AudioCache(  248): ignored
V/AwesomePlayer(  248): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  248): mAudioTrackVector clear
I/OMXCodec(  248): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec(  248): [OMX.google.vorbis.decoder] stop() sendCommand(0x3f, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec(  248): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
I/OMXCodec(  248): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/OMX     (  248): instance freeNode
I/AudioPlayer(  248): reset out
V/AwesomePlayer(  248): reset_l() mAudioPlayer successfully deleted
I/SecMediaClock(  248): SecMediaClock destructor
V/AwesomePlayer(  248): mSecMediaClock clear
V/StagefrightPlayer(  248): ~StagefrightPlayer
V/StagefrightPlayer(  248): reset
V/AwesomePlayer(  248): reset_l()
V/AwesomePlayer(  248): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  248): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  248): mAudioTrackVector clear
V/AwesomePlayer(  248): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  248): mSecMediaClock clear
V/AwesomePlayer(  248): destructor
V/AwesomePlayer(  248): reset_l()
V/AwesomePlayer(  248): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  248): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  248): mAudioTrackVector clear
V/AwesomePlayer(  248): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  248): mSecMediaClock clear
V/MediaPlayer( 4526): decode(71, 33925464, 44276)
V/MediaPlayerService(  248): decode(35, 33925464, 44276)
V/MediaPlayerService(  248): player type = 3
V/AwesomePlayer(  248): setDefault
V/AwesomePlayer(  248): constructor
V/AwesomePlayer(  248): setDefault
V/AwesomePlayer(  248): reset_l()
V/AwesomePlayer(  248): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  248): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  248): mAudioTrackVector clear
V/AwesomePlayer(  248): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  248): mSecMediaClock clear
V/StagefrightPlayer(  248): StagefrightPlayer
V/AwesomePlayer(  248): setListener
V/StagefrightPlayer(  248): initCheck
V/AwesomePlayer(  248): setAudioSink
V/StagefrightPlayer(  248): setDataSource(35, 33925464, 44276)
V/AwesomePlayer(  248): reset_l()
V/AwesomePlayer(  248): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  248): notify(0xb7d95968, 8, 0, 0)
V/AudioCache(  248): ignored
V/AwesomePlayer(  248): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  248): mAudioTrackVector clear
V/AwesomePlayer(  248): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  248): mSecMediaClock clear
V/AwesomePlayer(  248): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer(  248): mBitrate = -1 bits/sec
V/AwesomePlayer(  248): current audio track index (0) is added to vector
V/AwesomePlayer(  248): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer(  248): AwesomePlayer::setDataSource_l():: This is not a DRM content
V/MediaPlayerService(  248): prepare
V/AwesomePlayer(  248): prepareAsync
V/MediaPlayerService(  248): wait for prepare
V/AwesomePlayer(  248): onPrepareAsyncEvent
I/SecMediaClock(  248): SecMediaClock constructor
I/SecMediaClock(  248): reset
V/AwesomePlayer(  248): initAudioDecoder
V/AwesomePlayer(  248): checkOffloadExceptions is true
I/OMXCodec(  248): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
I/OMX     (  248): mDispatchers.add
I/OMXCodec(  248): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec(  248): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec(  248): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec(  248): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/OMXCodec(  248): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer(  248): finishAsyncPrepare_l
V/AwesomePlayer(  248): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache(  248): notify(0xb7d95968, 200, 973, 0)
V/AudioCache(  248): ignored
V/AwesomePlayer(  248): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  248): notify(0xb7d95968, 5, 0, 0)
V/AudioCache(  248): ignored
V/AwesomePlayer(  248): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  248): notify(0xb7d95968, 1, 0, 0)
V/AudioCache(  248): prepared
V/AudioCache(  248): wait - success
V/MediaPlayerService(  248): start
V/StagefrightPlayer(  248): start
V/AwesomePlayer(  248): play
V/AwesomePlayer(  248): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer(  248): startAudioPlayer_l, sendErrorNotification (0)
I/OMXCodec(  248): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec(  248): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCod,ec(  248): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/AudioPlayer(  248):  Audioplayer kKeyAudioPCMFormat:1, 2, 0
I/AudioPlayer(  248):  Audioplayer kKeyAudioPCMFormat read fail(2, 1)
V/AudioCache(  248): open(44100, 2, 0x0, 1, 4)
V/AwesomePlayer(  248): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache(  248): notify(0xb7d95968, 6, 0, 0)
V/AudioCache(  248): ignored
V/AwesomePlayer(  248): addBatteryData
V/MediaPlayerService(  248): wait for playback complete
I/SELinux ( 4621): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 4621):  
I/SELinux ( 4621):  
I/SELinux ( 4621): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 4621): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 4621): >>>>> Normal User
E/dalvikvm( 4621): >>>>> com.policydm [ userId:0 | appId:1000 ]
E/SELinux ( 4621): [DEBUG] seapp_context_lookup: seinfoCategory = platform
D/TimaKeyStoreProvider( 4621): in addTimaSignatureService
I/OMXCodec(  248): [OMX.google.vorbis.decoder] End Of Stream
D/TimaKeyStoreProvider( 4621): Cannot add TimaSignature Service, License check Failed
V/AwesomePlayer(  248): postAudioEOS delayUs (0)
D/ActivityThread( 4621): Added TimaKesytore provider
V/AwesomePlayer(  248): onCheckAudioStatus
V/AwesomePlayer(  248): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  248): onStreamDone
V/AwesomePlayer(  248): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  248): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  248): notify(0xb7d95968, 2, 0, 0)
V/AudioCache(  248): playback complete - thread will wake up later
V/AwesomePlayer(  248): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  248): notify(0xb7d95968, 7, 0, 0)
V/AudioCache(  248): ignored
V/AwesomePlayer(  248): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer(  248): addBatteryData
V/AudioCache(  248): wait - success
V/StagefrightPlayer(  248): reset
V/AwesomePlayer(  248): reset_l()
V/AwesomePlayer(  248): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  248): notify(0xb7d95968, 8, 0, 0)
V/AudioCache(  248): ignored
V/AwesomePlayer(  248): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  248): mAudioTrackVector clear
I/OMXCodec(  248): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec(  248): [OMX.google.vorbis.decoder] stop() sendCommand(0x40, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec(  248): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
I/OMXCodec(  248): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/OMX     (  248): instance freeNode
I/AudioPlayer(  248): reset out
V/AwesomePlayer(  248): reset_l() mAudioPlayer successfully deleted
I/SecMediaClock(  248): SecMediaClock destructor
V/AwesomePlayer(  248): mSecMediaClock clear
V/StagefrightPlayer(  248): ~StagefrightPlayer
V/StagefrightPlayer(  248): reset
V/AwesomePlayer(  248): reset_l()
V/AwesomePlayer(  248): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  248): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  248): mAudioTrackVector clear
V/AwesomePlayer(  248): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  248): mSecMediaClock clear
V/AwesomePlayer(  248): destructor
V/AwesomePlayer(  248): reset_l()
V/AwesomePlayer(  248): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  248): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  248): mAudioTrackVector clear
V/AwesomePlayer(  248): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  248): mSecMediaClock clear
V/MediaPlayer( 4526): decode(72, 33885672, 29256)
V/MediaPlayerService(  248): decode(35, 33885672, 29256)
V/MediaPlayerService(  248): player type = 3
V/AwesomePlayer(  248): setDefault
V/AwesomePlayer(  248): constructor
V/AwesomePlayer(  248): setDefault
V/AwesomePlayer(  248): reset_l()
V/AwesomePlayer(  248): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  248): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  248): mAudioTrackVector clear
V/AwesomePlayer(  248): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  248): mSecMediaClock clear
V/StagefrightPlayer(  248): StagefrightPlayer
V/AwesomePlayer(  248): setListener
V/StagefrightPlayer(  248): initCheck
V/AwesomePlayer(  248): setAudioSink
V/StagefrightPlayer(  248): setDataSource(35, 33885672, 29256)
V/AwesomePlayer(  248): reset_l()
V/AwesomePlayer(  248): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
E/memtrack( 4570): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 4570): failed to load memtrack module: -2
V/AudioCache(  248): notify(0xb7d9c208, 8, 0, 0)
V/AudioCache(  248): ignored
V/AwesomePlayer(  248): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  248): mAudioTrackVector clear
V/AwesomePlayer(  248): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  248): mSecMediaClock clear
V/AwesomePlayer(  248): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer(  248): mBitrate = -1 bits/sec
V/AwesomePlayer(  248): current audio track index (0) is added to vector
V/AwesomePlayer(  248): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer(  248): AwesomePlayer::setDataSource_l():: This is not a DRM content
V/MediaPlayerService(  248): prepare
V/AwesomePlayer(  248): prepareAsync
V/MediaPlayerService(  248): wait for prepare
V/AwesomePlayer(  248): onPrepareAsyncEvent
I/SecMediaClock(  248): SecMediaClock constructor
I/SecMediaClock(  248): reset
V/AwesomePlayer(  248): initAudioDecoder
V/AwesomePlayer(  248): checkOffloadExceptions is true
I/OMXCodec(  248): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
I/OMX     (  248): mDispatchers.add
I/OMXCodec(  248): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec(  248): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec(  248): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec(  248): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/OMXCodec(  248): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer(  248): finishAsyncPrepare_l
V/AwesomePlayer(  248): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache(  248): notify(0xb7d9c208, 200, 973, 0)
V/AudioCache(  248): ignored
V/AwesomePlayer(  248): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  248): notify(0xb7d9c208, 5, 0, 0)
V/AudioCache(  248): ignored
V/AwesomePlayer(  248): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  248): notify(0xb7d9c208, 1, 0, 0)
V/AudioCache(  248): prepared
V/AudioCache(  248): wait - success
V/MediaPlayerService(  248): start
V/StagefrightPlayer(  248): start
V/AwesomePlayer(  248): play
V/AwesomePlayer(  248): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer(  248): startAudioPlayer_l, sendErrorNotification (0)
I/OMXCodec(  248): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec(  248): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec(  248): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/AudioPlayer(  248):  Audioplayer kKeyAudioPCMFormat:1, 2, 0
I/AudioPlayer(  248):  Audioplayer kKeyAudioPCMFormat read fail(2, 1)
V/AudioCache(  248): open(44100, 2, 0x0, 1, 4)
V/AwesomePlayer(  248): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache(  248): notify(0xb7d9c208, 6, 0, 0)
V/AudioCache(  248): ignored
V/AwesomePlayer(  248): addBatteryData
V/MediaPlayerService(  248): wait for playback complete
D/dalvikvm( 4570): Note: class Landroid/app/ActivityManagerNative; has 192 unimplemented (abstract) methods
I/OMXCodec(  248): [OMX.google.vorbis.decoder] End Of Stream
V/AwesomePlayer(  248): postAudioEOS delayUs (0)
V/AwesomePlayer(  248): onCheckAudioStatus
V/AwesomePlayer(  248): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  248): onStreamDone
V/AwesomePlayer(  248): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  248): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  248): notify(0xb7d9c208, 2, 0, 0)
V/AudioCache(  248): playback complete - thread will wake up later
V/AwesomePlayer(  248): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  248): notify(0xb7d9c208, 7, 0, 0)
V/AudioCache(  248): ignored
V/AwesomePlayer(  248): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer(  248): addBatteryData
V/AudioCache(  248): wait - success
V/StagefrightPlayer(  248): reset
V/AwesomePlayer(  248): reset_l()
V/AwesomePlayer(  248): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  248): notify(0xb7d9c208, 8, 0, 0)
V/AudioCache(  248): ignored
V/AwesomePlayer(  248): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  248): mAudioTrackVector clear
I/OMXCodec(  248): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec(  248): [OMX.google.vorbis.decoder] stop() sendCommand(0x41, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec(  248): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
I/OMXCodec(  248): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/OMX     (  248): instance freeNode
I/AudioPlayer(  248): reset out
V/AwesomePlayer(  248): reset_l() mAudioPlayer successfully deleted
I/SecMediaClock(  248): SecMediaClock destructor
V/AwesomePlayer(  248): mSecMediaClock clear
V/StagefrightPlayer(  248): ~StagefrightPlayer
V/StagefrightPlayer(  248): reset
V/AwesomePlayer(  248): reset_l()
V/AwesomePlayer(  248): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  248): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  248): mAudioTrackVector clear
V/AwesomePlayer(  248): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  248): mSecMediaClock clear
V/AwesomePlayer(  248): destructor
V/AwesomePlayer(  248): reset_l()
V/AwesomePlayer(  248): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  248): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  248): mAudioTrackVector clear
V/AwesomePlayer(  248): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  248): mSecMediaClock clear
V/MediaPlayer( 4526): decode(73, 37491572, 52024)
V/MediaPlayerService(  248): decode(35, 37491572, 52024)
V/MediaPlayerService(  248): player type = 3
V/AwesomePlayer(  248): setDefault
V/AwesomePlayer(  248): constructor
V/AwesomePlayer(  248): setDefault
V/AwesomePlayer(  248): reset_l()
V/AwesomePlayer(  248): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  248): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  248): mAudioTrackVector clear
V/AwesomePlayer(  248): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  248): mSecMediaClock clear
V/StagefrightPlayer(  248): StagefrightPlayer
V/AwesomePlayer(  248): setListener
V/StagefrightPlayer(  248): initCheck
V/AwesomePlayer(  248): setAudioSink
V/StagefrightPlayer(  248): setDataSource(35, 37491572, 52024)
V/AwesomePlayer(  248): reset_l()
V/AwesomePlayer(  248): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  248): notify(0xb7da2e38, 8, 0, 0)
V/AudioCache(  248): ignored
V/AwesomePlayer(  248): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  248): mAudioTrackVector clear
V/AwesomePlayer(  248): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  248): mSecMediaClock clear
V/AwesomePlayer(  248): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer(  248): mBitrate = -1 bits/sec
V/AwesomePlayer(  248): current audio track index (0) is added to vector
V/AwesomePlayer(  248): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer(  248): AwesomePlayer::setDataSource_l():: This is not a DRM content
V/MediaPlayerService(  248): prepare
V/AwesomePlayer(  248): prepareAsync
V/MediaPlayerService(  248): wait for prepare
V/AwesomePlayer(  248): onPrepareAsyncEvent
I/SecMediaClock(  248): SecMediaClock constructor
I/SecMediaClock(  248): reset
V/AwesomePlayer(  248): initAudioDecoder
V/AwesomePlayer(  248): checkOffloadExceptions is true
I/OMXCodec(  248): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
I/OMX     (  248): mDispatchers.add
I/OMXCodec(  248): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec(  248): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec(  248): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec(  248): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/OMXCodec(  248): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer(  248): finishAsyncPrepare_l
V/AwesomePlayer(  248): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache(  248): notify(0xb7da2e38, 200, 973, 0)
V/AudioCache(  248): ignored
V/AwesomePlayer(  248): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  248): notify(0xb7da2e38, 5, 0, 0)
V/AudioCache(  248): ignored
V/AwesomePlayer(  248): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  248): notify(0xb7da2e38, 1, 0, 0)
V/AudioCache(  248): prepared
V/AudioCache(  248): wait - success
V/MediaPlayerService(  248): start
V/StagefrightPlayer(  248): start
V/AwesomePlayer(  248): play
V/AwesomePlayer(  248): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer(  248): startAudioPlayer_l, sendErrorNotification (0)
I/OMXCodec(  248): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec(  248): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec(  248): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/AudioPlayer(  248):  Audioplayer kKeyAudioPCMFormat:1, 2, 0
I/AudioPlayer(  248):  Audioplayer kKeyAudioPCMFormat read fail(2, 1)
V/AudioCache(  248): open(48000, 2, 0x0, 1, 4)
V/AwesomePlayer(  248): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache(  248): notify(0xb7da2e38, 6, 0, 0)
V/AudioCache(  248): ignored
V/AwesomePlayer(  248): addBatteryData
V/MediaPlayerService(  248): wait for playback complete
I/AudioPlayer(  248): First fillBuffer call!!
D/AndroidRuntime( 4570): Calling main entry com.android.commands.am.Am
E/SMD     (  239): DCD ON
I/OMXCodec(  248): [OMX.google.vorbis.decoder] End Of Stream
V/ApplicationPolicy(  740): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
V/AwesomePlayer(  248): postAudioEOS delayUs (0)
V/AwesomePlayer(  248): onCheckAudioStatus
V/AwesomePlayer(  248): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  248): onStreamDone
V/AwesomePlayer(  248): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  248): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  248): notify(0xb7da2e38, 2, 0, 0)
V/AudioCache(  248): playback complete - thread will wake up later
V/AwesomePlayer(  248): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  248): notify(0xb7da2e38, 7, 0, 0)
V/AudioCache(  248): ignored
V/AwesomePlayer(  248): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer(  248): addBatteryData
V/AudioCache(  248): wait - success
V/StagefrightPlayer(  248): reset
V/AwesomePlayer(  248): reset_l()
V/AwesomePlayer(  248): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  248): notify(0xb7da2e38, 8, 0, 0)
V/AudioCache(  248): ignored
V/AwesomePlayer(  248): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  248): mAudioTrackVector clear
I/OMXCodec(  248): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec(  248): [OMX.google.vorbis.decoder] stop() sendCommand(0x42, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec(  248): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
I/OMXCodec(  248): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/OMX     (  248): instance freeNode
I/AudioPlayer(  248): reset out
V/AwesomePlayer(  248): reset_l() mAudioPlayer successfully deleted
I/SecMediaClock(  248): SecMediaClock destructor
V/AwesomePlayer(  248): mSecMediaClock clear
V/StagefrightPlayer(  248): ~StagefrightPlayer
V/StagefrightPlayer(  248): reset
V/AwesomePlayer(  248): reset_l()
V/AwesomePlayer(  248): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  248): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  248): mAudioTrackVector clear
V/AwesomePlayer(  248): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  248): mSecMediaClock clear
V/AwesomePlayer(  248): destructor
V/AwesomePlayer(  248): reset_l()
V/AwesomePlayer(  248): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  248): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  248): mAudioTrackVector clear
V/AwesomePlayer(  248): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  248): mSecMediaClock clear
V/MediaPlayer( 4526): decode(74, 33969800, 9226)
V/MediaPlayerService(  248): decode(35, 33969800, 9226)
V/MediaPlayerService(  248): player type = 3
V/AwesomePlayer(  248): setDefault
V/AwesomePlayer(  248): constructor
V/AwesomePlayer(  248): setDefault
V/AwesomePlayer(  248): reset_l()
V/AwesomePlayer(  248): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  248): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  248): mAudioTrackVector clear
V/AwesomePlayer(  248): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  248): mSecMediaClock clear
V/StagefrightPlayer(  248): StagefrightPlayer
V/AwesomePlayer(  248): setListener
V/StagefrightPlayer(  248): initCheck
V/AwesomePlayer(  248): setAudioSink
V/StagefrightPlayer(  248): setDataSource(35, 33969800, 9226)
V/AwesomePlayer(  248): reset_l()
V/AwesomePlayer(  248): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  248): notify(0xb7dabd80, 8, 0, 0)
V/AudioCache(  248): ignored
V/AwesomePlayer(  248): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  248): mAudioTrackVector clear
V/AwesomePlayer(  248): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  248): mSecMediaClock clear
V/AwesomePlayer(  248): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer(  248): mBitrate = -1 bits/sec
V/AwesomePlayer(  248): current audio track index (0) is added to vector
V/AwesomePlayer(  248): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer(  248): AwesomePlayer::setDataSource_l():: This is not a DRM content
V/MediaPlayerService(  248): prepare
V/AwesomePlayer(  248): prepareAsync
V/MediaPlayerService(  248): wait for prepare
D/CustomFrequencyManagerService(  740): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 740  pkgName : ACTIVITY_RESUME_BOOSTER@5
V/AwesomePlayer(  248): onPrepareAsyncEvent
I/SecMediaClock(  248): SecMediaClock constructor
I/SecMediaClock(  248): reset
V/AwesomePlayer(  248): initAudioDecoder
V/AwesomePlayer(  248): checkOffloadExceptions is true
I/OMXCodec(  248): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
W/ActivityManager(  740): mDVFSHelper.acquire()
I/OMX     (  248): mDispatchers.add
I/OMXCodec(  248): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec(  248): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec(  248): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec(  248): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/OMXCodec(  248): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer(  248): finishAsyncPrepare_l
V/AwesomePlayer(  248): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache(  248): notify(0xb7dabd80, 200, 973, 0)
V/AudioCache(  248): ignored
V/AwesomePlayer(  248): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  248): notify(0xb7dabd80, 5, 0, 0)
V/AudioCache(  248): ignored
V/AwesomePlayer(  248): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  248): notify(0xb7dabd80, 1, 0, 0)
V/AudioCache(  248): prepared
V/AudioCache(  248): wait - success
V/MediaPlayerService(  248): start
V/StagefrightPlayer(  248): start
V/AwesomePlayer(  248): play
V/AwesomePlayer(  248): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer(  248): startAudioPlayer_l, sendErrorNotification (0)
I/OMXCodec(  248): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec(  248): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec(  248): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/AudioPlayer(  248):  Audioplayer kKeyAudioPCMFormat:1, 2, 0
I/AudioPlayer(  248):  Audioplayer kKeyAudioPCMFormat read fail(2, 1)
V/AudioCache(  248): open(44100, 2, 0x0, 1, 4)
V/AwesomePlayer(  248): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache(  248): notify(0xb7dabd80, 6, 0, 0)
V/AudioCache(  248): ignored
V/AwesomePlayer(  248): addBatteryData
V/MediaPlayerService(  248): wait for playback complete
I/OMXCodec(  248): [OMX.google.vorbis.decoder] End Of Stream
V/AwesomePlayer(  248): postAudioEOS delayUs (0)
V/AwesomePlayer(  248): onCheckAudioStatus
V/AwesomePlayer(  248): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  248): onStreamDone
V/AwesomePlayer(  248): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  248): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  248): notify(0xb7dabd80, 2, 0, 0)
V/AudioCache(  248): playback complete - thread will wake up later
V/AwesomePlayer(  248): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  248): notify(0xb7dabd80, 7, 0, 0)
V/AudioCache(  248): ignored
V/AwesomePlayer(  248): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer(  248): addBatteryData
V/AudioCache(  248): wait - success
V/StagefrightPlayer(  248): reset
V/AwesomePlayer(  248): reset_l()
V/AwesomePlayer(  248): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  248): notify(0xb7dabd80, 8, 0, 0)
V/AudioCache(  248): ignored
V/AwesomePlayer(  248): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  248): mAudioTrackVector clear
I/OMXCodec(  248): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec(  248): [OMX.google.vorbis.decoder] stop() sendCommand(0x43, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec(  248): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
I/OMXCodec(  248): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/OMX     (  248): instance freeNode
I/AudioPlayer(  248): reset out
V/AwesomePlayer(  248): reset_l() mAudioPlayer successfully deleted
I/SecMediaClock(  248): SecMediaClock destructor
V/AwesomePlayer(  248): mSecMediaClock clear
V/StagefrightPlayer(  248): ~StagefrightPlayer
V/StagefrightPlayer(  248): reset
V/AwesomePlayer(  248): reset_l()
V/AwesomePlayer(  248): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  248): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  248): mAudioTrackVector clear
V/AwesomePlayer(  248): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  248): mSecMediaClock clear
V/AwesomePlayer(  248): destructor
V/AwesomePlayer(  248): reset_l()
V/AwesomePlayer(  248): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  248): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  248): mAudioTrackVector clear
V/AwesomePlayer(  248): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  248): mSecMediaClock clear
V/MediaPlayer( 4526): decode(75, 30402580, 4509)
V/MediaPlayerService(  248): decode(35, 30402580, 4509)
V/MediaPlayerService(  248): player type = 3
V/AwesomePlayer(  248): setDefault
V/AwesomePlayer(  248): constructor
V/AwesomePlayer(  248): setDefault
V/AwesomePlayer(  248): reset_l()
V/AwesomePlayer(  248): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  248): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  248): mAudioTrackVector clear
V/AwesomePlayer(  248): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  248): mSecMediaClock clear
V/StagefrightPlayer(  248): StagefrightPlayer
V/AwesomePlayer(  248): setListener
V/StagefrightPlayer(  248): initCheck
V/AwesomePlayer(  248): setAudioSink
V/StagefrightPlayer(  248): setDataSource(35, 30402580, 4509)
V/AwesomePlayer(  248): reset_l()
V/AwesomePlayer(  248): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  248): notify(0xb7d942b0, 8, 0, 0)
V/AudioCache(  248): ignored
V/AwesomePlayer(  248): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  248): mAudioTrackVector clear
V/AwesomePlayer(  248): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  248): mSecMediaClock clear
V/AwesomePlayer(  248): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer(  248): mBitrate = -1 bits/sec
V/AwesomePlayer(  248): current audio track index (0) is added to vector
V/AwesomePlayer(  248): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer(  248): AwesomePlayer::setDataSource_l():: This is not a DRM content
V/MediaPlayerService(  248): prepare
V/AwesomePlayer(  248): prepareAsync
V/MediaPlayerService(  248): wait for prepare
V/AwesomePlayer(  248): onPrepareAsyncEvent
I/SecMediaClock(  248): SecMediaClock constructor
I/SecMediaClock(  248): reset
V/AwesomePlayer(  248): initAudioDecoder
V/AwesomePlayer(  248): checkOffloadExceptions is true
I/OMXCodec(  248): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
I/OMX     (  248): mDispatchers.add
I/OMXCodec(  248): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/SELinux ( 4656): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 4656):  
I/OMXCodec(  248): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec(  248): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec(  248): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/OMXCodec(  248): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer(  248): finishAsyncPrepare_l
V/AwesomePlayer(  248): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache(  248): notify(0xb7d942b0, 200, 973, 0)
V/AudioCache(  248): ignored
V/AwesomePlayer(  248): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  248): notify(0xb7d942b0, 5, 0, 0)
V/AudioCache(  248): ignored
V/AwesomePlayer(  248): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  248): notify(0xb7d942b0, 1, 0, 0)
V/AudioCache(  248): prepared
V/AudioCache(  248): wait - success
V/MediaPlayerService(  248): start
V/StagefrightPlayer(  248): start
V/AwesomePlayer(  248): play
V/AwesomePlayer(  248): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer(  248): startAudioPlayer_l, sendErrorNotification (0)
I/OMXCodec(  248): [OMX.google.vorbis.decoder] End Of Stream
I/OMXCodec(  248): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec(  248): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec(  248): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
D/dalvikvm(  246): GC_EXPLICIT freed 45K, 50% free 9512K/18944K, paused 2ms+3ms, total 29ms
I/AudioPlayer(  248):  Audioplayer kKeyAudioPCMFormat:1, 2, 0
I/AudioPlayer(  248):  Audioplayer kKeyAudioPCMFormat read fail(2, 1)
V/AudioCache(  248): open(44100, 2, 0x0, 1, 4)
D/dalvikvm(  246): GC_EXPLICIT freed <1K, 50% free 9512K/18944K, paused 2ms+2ms, total 18ms
I/SELinux ( 4656): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 4656):  
I/SELinux ( 4656):  
I/SELinux ( 4656): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 4656): [DEBUG] seapp_context_lookup: seinfoCategory = default
E/dalvikvm( 4656): >>>>> Normal User
E/dalvikvm( 4656): >>>>> com.test.thalitest [ userId:0 | appId:10179 ]
E/SELinux ( 4656): [DEBUG] seapp_context_lookup: seinfoCategory = default
V/AwesomePlayer(  248): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache(  248): notify(0xb7d942b0, 6, 0, 0)
V/AudioCache(  248): ignored
V/AwesomePlayer(  248): addBatteryData
V/MediaPlayerService(  248): wait for playback complete
D/dalvikvm(  246): GC_EXPLICIT freed <1K, 50% free 9512K/18944K, paused 2ms+2ms, total 19ms
D/LockPatternUtils( 1064): isPcwEnable = null
D/AndroidRuntime( 4570): Shutting down VM
V/AwesomePlayer(  248): postAudioEOS delayUs (0)
V/AwesomePlayer(  248): onCheckAudioStatus
V/AwesomePlayer(  248): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  248): onStreamDone
V/AwesomePlayer(  248): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  248): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  248): notify(0xb7d942b0, 2, 0, 0)
V/AudioCache(  248): playback complete - thread will wake up later
V/AwesomePlayer(  248): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  248): notify(0xb7d942b0, 7, 0, 0)
V/AudioCache(  248): ignored
V/AwesomePlayer(  248): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer(  248): addBatteryData
V/AudioCache(  248): wait - success
V/StagefrightPlayer(  248): reset
V/AwesomePlayer(  248): reset_l()
V/AwesomePlayer(  248): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  248): notify(0xb7d942b0, 8, 0, 0)
V/AudioCache(  248): ignored
V/AwesomePlayer(  248): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  248): mAudioTrackVector clear
I/OMXCodec(  248): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec(  248): [OMX.google.vorbis.decoder] stop() sendCommand(0x44, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec(  248): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
I/OMXCodec(  248): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/OMX     (  248): instance freeNode
I/AudioPlayer(  248): reset out
V/AwesomePlayer(  248): reset_l() mAudioPlayer successfully deleted
I/SecMediaClock(  248): SecMediaClock destructor
V/AwesomePlayer(  248): mSecMediaClock clear
V/StagefrightPlayer(  248): ~StagefrightPlayer
V/StagefrightPlayer(  248): reset
V/AwesomePlayer(  248): reset_l()
V/AwesomePlayer(  248): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  248): cancelPlayerEvents (keepNotifications=0)
D/TimaKeyStoreProvider( 4656): in addTimaSignatureService
V/AwesomePlayer(  248): mAudioTrackVector clear
V/AwesomePlayer(  248): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  248): mSecMediaClock clear
V/AwesomePlayer(  248): destructor
V/AwesomePlayer(  248): reset_l()
V/AwesomePlayer(  248): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  248): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  248): mAudioTrackVector clear
V/AwesomePlayer(  248): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  248): mSecMediaClock clear
D/dalvikvm( 4570): GC_CONCURRENT freed 97K, 13% free 717K/816K, paused 0ms+0ms, total 2ms
D/TimaKeyStoreProvider( 4656): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 4656): Added TimaKesytore provider
D/SurfaceWidgetClient$ISurfaceWidgetStub( 1441): [237392/5] Surface widget visibility changed visibility = false on instance = 1
D/LockPatternUtils( 1064): isPcwEnable = null
I/SQLiteSecureOpenHelper( 2024): getWritableDatabase(pwd)
I/SQLiteSecureOpenHelper( 2024): getDatabaseLocked(b,b,pwd)...
D/SurfaceWidgetView( 1256): destroyHardwareResources():1126006440
I/SurfaceFlinger(  245): id=13 Removed CatteryCove (8/13)
I/SurfaceFlinger(  245): id=13 Removed CatteryCove (-2/13)
D/KeyguardUpdateMonitor( 1064): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1064): handleKeyguardVisibilityChanged(1)
W/ActivityManager(  740): Permission Denial: getCurrentUser() from pid=4656, uid=10179 requires android.permission.INTERACT_ACROSS_USERS
I/SELinux ( 4672): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 4672):  
I/ActivityManager(  740): Killing 3178:com.sec.android.app.camera/u0a147 (adj 15): empty #43
W/ActivityManager(  740): Permission Denial: getCurrentUser() from pid=4656, uid=10179 requires android.permission.INTERACT_ACROSS_USERS
V/WebViewChromium( 4656): Binding Chromium to the background looper Looper (main, tid 1) {422b1890}
I/chromium( 4656): [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserProcessMain( 4656): Initializing chromium process, renderers=0
I/SELinux ( 4672): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 4672):  
I/SELinux ( 4672):  
I/SELinux ( 4672): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 4672): [DEBUG] seapp_context_lookup: seinfoCategory = default
E/dalvikvm( 4672): >>>>> Normal User
E/dalvikvm( 4672): >>>>> com.osp.app.signin [ userId:0 | appId:10043 ]
E/SELinux ( 4672): [DEBUG] seapp_context_lookup: seinfoCategory = default
W/chromium( 4656): [WARNING:proxy_service.cc(888)] PAC support disabled because there is no system implementation
D/TimaKeyStoreProvider( 4672): in addTimaSignatureService
D/TimaKeyStoreProvider( 4672): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 4672): Added TimaKesytore provider
D/CustomFrequencyManagerService(  740): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 740  tag : ACTIVITY_RESUME_BOOSTER@5
,W/ActivityManager(  740): mDVFSHelper.release()
D/CustomFrequencyManagerService(  740): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 740  pkgName : ACTIVITY_RESUME_BOOSTER@9
I/SA      ( 4672): [SSP] onCreated
I/SA      ( 4672): [TPM] There is no property file
I/SA      ( 4672): [SCU] isHaveSA() - false
I/SA      ( 4672): [TPM] getModelProperty : null
I/SA      ( 4672): [TPM] getCSCProperty : null
I/SA      ( 4672): [PMR] Received action : android.intent.action.PACKAGE_ADDED
I/SA      ( 4672): [DM] init START
I/SA      ( 4672): [DM] This device is not a Vodafone
I/SA      ( 4672): [DM] getCountryCodeFromCSC : PL
I/SA      ( 4672): support phone number id : false
I/SA      ( 4672): [DM] init END
I/SA      ( 4672): [SUR] onReceive log=[SA = 2.0.0117 V = 19 HWD = 1280X720 2.0 dpi = 320  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = kmini3g P = kmini3gxx I = KOT49H M = SM-G800H OKLEFT false DIS KOT49H.G800HXXU1ANK2 PSS = 4.497045606779314  ]
I/SA      ( 4672): [SUR] onReceive Intent=[ action.PACKAGE_ADDED. package ]
I/ActivityManager(  740): Killing 3283:com.android.email/u0a155 (adj 15): empty #43
D/Mms/PackageInstallReceiver( 3779): loadAuthorityPref(): sEnableAuthority = true
I/IcingCorporaProvider( 2120): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
W/ContextImpl( 2837): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1857 android.content.ContextWrapper.startService:506 android.content.ContextWrapper.startService:506 com.samsung.android.app.assistantmenu.AssistantMenuReceiver.onReceive:153 android.app.ActivityThread.handleReceiver:2698 
I/SELinux ( 4701): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 4701):  
I/SELinux ( 4701): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 4701):  
I/SELinux ( 4701):  
I/SELinux ( 4701): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 4701): [DEBUG] seapp_context_lookup: seinfoCategory = samsung
E/dalvikvm( 4701): >>>>> Normal User
E/dalvikvm( 4701): >>>>> com.sec.android.service.cm [ userId:0 | appId:10078 ]
E/SELinux ( 4701): [DEBUG] seapp_context_lookup: seinfoCategory = samsung
I/IcingCorporaProvider( 2120): UpdateCorporaTask done [took 97 ms] updated apps [took 97 ms] 
D/TimaKeyStoreProvider( 4701): in addTimaSignatureService
D/TimaKeyStoreProvider( 4701): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 4701): Added TimaKesytore provider
D/CapabilityManagerService New( 4701): Receiver Broadcast:android.intent.action.PACKAGE_ADDED
W/ActivityManager(  740): Permission Denial: getCurrentUser() from pid=4701, uid=10078 requires android.permission.INTERACT_ACROSS_USERS
I/SELinux ( 4713): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 4713):  
I/ActivityManager(  740): Killing 3278:com.samsung.android.provider.shootingmodeprovider/u0a162 (adj 15): empty #43
I/SELinux ( 4713): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 4713):  
I/SELinux ( 4713):  
I/SELinux ( 4713): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 4713): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 4713): >>>>> Normal User
E/dalvikvm( 4713): >>>>> com.google.android.apps.docs [ userId:0 | appId:10090 ]
E/SELinux ( 4713): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
D/TimaKeyStoreProvider( 4713): in addTimaSignatureService
D/TimaKeyStoreProvider( 4713): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 4713): Added TimaKesytore provider
W/ActivityManager(  740): Permission Denial: getCurrentUser() from pid=4713, uid=10090 requires android.permission.INTERACT_ACROSS_USERS
I/Adreno-EGL( 4656): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 4656): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 4656): Build Date: 03/21/14 Fri
I/Adreno-EGL( 4656): Local Branch: AU200+patches_03212014
I/Adreno-EGL( 4656): Remote Branch: 
I/Adreno-EGL( 4656): Local Patches: 
I/Adreno-EGL( 4656): Reconstruct Branch: 
I/SurfaceFlinger(  245): id=16 Removed TettingsRec (8/12)
D/KeyguardUpdateMonitor( 1064): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1064): handleKeyguardVisibilityChanged(1)
I/SecureStorage(  297): [INFO]: SPID(0x00000003)Secure Storage Daemon finished processing with result: 0
I/SecureStorage(  297): [INFO]: SPID(0x00000003)PID: 4546, TID: 4546
I/SurfaceFlinger(  245): id=8 Removed Mauncher (7/11)
I/SurfaceFlinger(  245): id=8 Removed Mauncher (-2/11)
D/KeyguardUpdateMonitor( 1064): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1064): handleKeyguardVisibilityChanged(1)
D/Launcher( 1256): onTrimMemory. Level: 20
I/dalvikvm( 4656): Could not find method android.webkit.CookieManager.setAcceptThirdPartyCookies, referenced from method org.apache.cordova.engine.SystemCookieManager.<init>
W/dalvikvm( 4656): VFY: unable to resolve virtual method 218: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
D/dalvikvm( 4656): VFY: replacing opcode 0x6e at 0x0016
I/dalvikvm( 4656): Could not find method android.webkit.CookieManager.flush, referenced from method org.apache.cordova.engine.SystemCookieManager.flush
W/dalvikvm( 4656): VFY: unable to resolve virtual method 213: Landroid/webkit/CookieManager;.flush ()V
D/dalvikvm( 4656): VFY: replacing opcode 0x6e at 0x0008
W/dalvikvm( 4656): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 4656): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
I/dalvikvm( 4656): Could not find method android.webkit.WebViewClient.onReceivedClientCertRequest, referenced from method org.apache.cordova.engine.SystemWebViewClient.onReceivedClientCertRequest
W/dalvikvm( 4656): VFY: unable to resolve virtual method 271: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
D/dalvikvm( 4656): VFY: replacing opcode 0x6f at 0x001a
W/dalvikvm( 4656): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
I/dalvikvm( 4656): Could not find method android.webkit.PermissionRequest.getResources, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onPermissionRequest
W/dalvikvm( 4656): VFY: unable to resolve virtual method 229: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
D/dalvikvm( 4656): VFY: replacing opcode 0x6e at 0x000d
I/dalvikvm( 4656): Could not find method android.webkit.WebChromeClient$FileChooserParams.createIntent, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onShowFileChooser
W/dalvikvm( 4656): VFY: unable to resolve virtual method 234: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
D/dalvikvm( 4656): VFY: replacing opcode 0x6e at 0x0000
D/SystemWebViewEngine( 4656): CordovaWebView is running on device made by: samsung
I/SecureStorage( 4546): [INFO]: SPID(0x00000000)Processing data has been completed
I/SecureStorage( 4546): [INFO]: SPID(0x00000000)WARNING! Failed to find SecureStorageExceptionJNI!..
I/SQLiteSecureOpenHelper( 4546): getWritableDatabase(pwd)
I/SQLiteSecureOpenHelper( 4546): getDatabaseLocked(b,b,pwd)...
I/SQLiteSecureOpenHelper( 4546): Open platform.db in secure mode
I/SurfaceFlinger(  245): id=17 createSurf (1x1),1 flag=404, NainActivit
D/KeyguardUpdateMonitor( 1064): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1064): handleKeyguardVisibilityChanged(1)
D/KeyguardUpdateMonitor( 1064): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1064): handleKeyguardVisibilityChanged(1)
I/HWUI    ( 4656): EGLImpl-HWUI Protected EGL context created
D/OpenGLRenderer( 4656): Enabling debug mode 0
D/OpenGLRenderer( 4656): GL error from OpenGLRenderer: 0x502
E/OpenGLRenderer( 4656):   GL_INVALID_OPERATION
D/KeyguardUpdateMonitor( 1064): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1064): handleKeyguardVisibilityChanged(1)
D/KeyguardUpdateMonitor( 1064): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1064): handleKeyguardVisibilityChanged(1)
I/SQLiteSecureOpenHelper( 4546): ...getDatabaseLocked(b,b,pwd)
D/SQLiteSecureOpenHelper( 4546): ...getDatabaseLocked(b,b,pwd)
W/GAV2    ( 4713): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
I/SELinux ( 4747): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 4747):  
I/ActivityManager(  740): Killing 3310:com.sec.modem.settings/1000 (adj 15): empty #43
D/CustomFrequencyManagerService(  740): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 740  tag : ACTIVITY_RESUME_BOOSTER@9
I/SELinux ( 4747): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 4747):  
I/SELinux ( 4747):  
I/SELinux ( 4747): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 4747): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 4747): >>>>> Normal User
E/dalvikvm( 4747): >>>>> com.samsung.android.app.watchmanagerstub [ userId:0 | appId:10100 ]
E/SELinux ( 4747): [DEBUG] seapp_context_lookup: seinfoCategory = platform
D/TimaKeyStoreProvider( 4747): in addTimaSignatureService
D/TimaKeyStoreProvider( 4747): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 4747): Added TimaKesytore provider
D/PackageIntentReceiver( 4747): ACTION_PACKAGE_ADDED
D/PackageIntentReceiver( 4747): Not GearManger package! 
I/SELinux ( 4763): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 4763):  
I/ActivityManager(  740): Killing 1332:com.sec.android.provider.badge/u0a72 (adj 15): empty #43
D/JsMessageQueue( 4656): Set native->JS mode to OnlineEventsBridgeMode
I/SELinux ( 4763): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 4763):  
I/SELinux ( 4763):  
I/SELinux ( 4763): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 4763): [DEBUG] seapp_context_lookup: seinfoCategory = release
E/dalvikvm( 4763): >>>>> Normal User
E/dalvikvm( 4763): >>>>> com.samsung.android.magazine.service [ userId:0 | appId:10106 ]
E/SELinux ( 4763): [DEBUG] seapp_context_lookup: seinfoCategory = release
D/TimaKeyStoreProvider( 4763): in addTimaSignatureService
D/TimaKeyStoreProvider( 4763): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 4763): Added TimaKesytore provider
D/MagazineService Version( 4763): Magazine-Channel: 13
D/dalvikvm( 4656): Trying to load lib /data/app-lib/com.test.thalitest-33/libjxcore.so 0x425d86b8
D/MagazineService Version( 4763): Magazine-Provider: 13
D/MagazineService Version( 4763): Magazine-Administrator: 11
D/HeadlinesChannelApplication( 4763): [onCreate]
D/MagazineService::MagazineBroadcastReceiver( 4763): [onReceive] android.intent.action.PACKAGE_ADDED com.test.thalitest
D/dalvikvm( 4656): Added shared lib /data/app-lib/com.test.thalitest-33/libjxcore.so 0x425d86b8
W/ActivityManager(  740): Permission Denial: getCurrentUser() from pid=4763, uid=10106 requires android.permission.INTERACT_ACROSS_USERS
D/jxcore_app_log( 4656): JniHelper::setJavaVM(0x418154f8), pthread_self() = 1943129168
D/JX-Cordova( 4656): jxcore cordova android initializing
I/dalvikvm( 4656): Could not find method android.bluetooth.BluetoothAdapter.isMultipleAdvertisementSupported, referenced from method io.jxcore.node.ConnectionHelper.isBleAdvertisingSupported
W/dalvikvm( 4656): VFY: unable to resolve virtual method 52: Landroid/bluetooth/BluetoothAdapter;.isMultipleAdvertisementSupported ()Z
D/dalvikvm( 4656): VFY: replacing opcode 0x6e at 0x0045
I/SELinux ( 4776): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 4776):  
I/MagazineService::MagazineService( 4763): [onHandleIntent] ACTION_PACKAGE_INSTALLED
D/MagazineService::MagazineService( 4763): [onHandleIntent] Send broadcast to (com.test.thalitest).
I/ActivityManager(  740): Killing 3336:tv.peel.smartremote/u0a163 (adj 15): empty #43
W/GAV2    ( 4713): Thread[main,5,main]: dispatch call queued.  Need to call GAServiceManager.getInstance().initialize().
I/ActivityManager(  740): Killing 3360:org.simalliance.openmobileapi.service/1101 (adj 15): empty #43
I/SELinux ( 4776): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 4776):  
I/SELinux ( 4776):  
I/SELinux ( 4776): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 4776): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 4776): >>>>> Normal User
E/dalvikvm( 4776): >>>>> com.samsung.helphub [ userId:0 | appId:1000 ]
E/SELinux ( 4776): [DEBUG] seapp_context_lookup: seinfoCategory = platform
D/TimaKeyStoreProvider( 4776): in addTimaSignatureService
D/TimaKeyStoreProvider( 4776): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 4776): Added TimaKesytore provider
,I/SELinux ( 4790): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 4790):  
I/ActivityManager(  740): Killing 3418:com.sec.android.app.taskmanager/u0a166 (adj 15): empty #43
,I/SELinux ( 4790): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 4790):  
I/SELinux ( 4790):  
,I/SELinux ( 4790): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 4790): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 4790): >>>>> Normal User
,E/dalvikvm( 4790): >>>>> com.sec.kidsplat.installer [ userId:0 | appId:10158 ]
,E/SELinux ( 4790): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 4790): in addTimaSignatureService
,D/TimaKeyStoreProvider( 4790): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 4790): Added TimaKesytore provider
,D/dalvikvm( 4656): GC_CONCURRENT freed 4947K, 33% free 12746K/18944K, paused 3ms+2ms, total 34ms
,D/dalvikvm( 4656): WAIT_FOR_CONCURRENT_GC blocked 19ms
,D/dalvikvm( 4656): WAIT_FOR_CONCURRENT_GC blocked 25ms
,W/ActivityManager(  740): Permission Denial: getCurrentUser() from pid=4790, uid=10158 requires android.permission.INTERACT_ACROSS_USERS
,D/KidsPlatformStub( 4790): Package not found : com.sec.android.app.kidshome
,I/SELinux ( 4802): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 4802):  
I/ActivityManager(  740): Killing 3430:com.samsung.android.service.travel/u0a169 (adj 15): empty #43
,I/SELinux ( 4802): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 4802):  
I/SELinux ( 4802):  
,I/SELinux ( 4802): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 4802): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 4802): >>>>> Normal User
,E/dalvikvm( 4802): >>>>> com.samsung.android.provider.shootingmodeprovider [ userId:0 | appId:10162 ]
,E/SELinux ( 4802): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 4802): in addTimaSignatureService
D/TimaKeyStoreProvider( 4802): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 4802): Added TimaKesytore provider
,D/AmoledAdjustTimer(  740): prevTemp = 284, currTemp = 285, prevStep = 4, currStep = 4
,I/SELinux ( 4814): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 4814):  
I/ActivityManager(  740): Killing 3445:com.google.android.youtube/u0a175 (adj 15): empty #43
,I/SELinux ( 4814): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 4814):  
I/SELinux ( 4814):  
,I/SELinux ( 4814): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 4814): [DEBUG] seapp_context_lookup: seinfoCategory = samsung
E/dalvikvm( 4814): >>>>> Normal User
,E/dalvikvm( 4814): >>>>> com.sec.android.app.samsungapps [ userId:0 | appId:10040 ]
,E/SELinux ( 4814): [DEBUG] seapp_context_lookup: seinfoCategory = samsung
,D/TimaKeyStoreProvider( 4814): in addTimaSignatureService
,D/TimaKeyStoreProvider( 4814): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 4814): Added TimaKesytore provider
,I/ActivityManager(  740): Killing 3627:com.sec.android.widgetapp.activeapplicationwidget/u0a152 (adj 15): empty #43
,D/Finsky  ( 3515): [1] ExternalReferrer.access$200: Package state data is missing for com.test.thalitest
,D/ChimeraCfgMgr( 1795): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 1795): Loading module APK com.google.android.play.games
,D/PackageBroadcastService( 1795): Received broadcast action=android.intent.action.PACKAGE_ADDED and uri=com.test.thalitest
,I/dalvikvm( 1795): Could not find method android.app.admin.DevicePolicyManager.getProfileOwner, referenced from method com.google.android.gms.auth.WorkAccountAuthenticatorInitializer.a
W/dalvikvm( 1795): VFY: unable to resolve virtual method 174: Landroid/app/admin/DevicePolicyManager;.getProfileOwner ()Landroid/content/ComponentName;
,D/dalvikvm( 1795): VFY: replacing opcode 0x6e at 0x0053
,I/dalvikvm( 1795): Failed resolving Lcom/google/android/gms/common/permission/PermissionUtils$1; interface 96 'Landroid/content/pm/PackageManager$OnPermissionsChangedListener;'
,W/dalvikvm( 1795): Link of class 'Lcom/google/android/gms/common/permission/PermissionUtils$1;' failed
E/dalvikvm( 1795): Could not find class 'com.google.android.gms.common.permission.PermissionUtils$1', referenced from method com.google.android.gms.chimera.GmsModuleInitializer.initializeModuleV0
W/dalvikvm( 1795): VFY: unable to resolve new-instance 2374 (Lcom/google/android/gms/common/permission/PermissionUtils$1;) in Lcom/google/android/gms/chimera/GmsModuleInitializer;
,D/dalvikvm( 1795): VFY: replacing opcode 0x22 at 0x001a
I/dalvikvm( 1795): Failed resolving Lcom/google/android/gms/common/permission/PermissionUtils$1; interface 96 'Landroid/content/pm/PackageManager$OnPermissionsChangedListener;'
,W/dalvikvm( 1795): Link of class 'Lcom/google/android/gms/common/permission/PermissionUtils$1;' failed
,D/dalvikvm( 1795): DexOpt: unable to opt direct call 0x338d at 0x1c in Lcom/google/android/gms/chimera/GmsModuleInitializer;.initializeModuleV0
,D/dalvikvm( 4656): GC_FOR_ALLOC freed 4730K, 28% free 15775K/21776K, paused 34ms, total 36ms
,D/ChimeraCfgMgr( 1795): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 1795): Module APK com.google.android.play.games already loaded
,D/ChimeraCfgMgr( 1795): Loading module com.google.android.gms.gass from APK com.google.android.gms
,D/AsyncTaskServiceImpl( 1795): Submit a task: k
,D/ChimeraCfgMgr( 1795): Loading module com.google.android.gms.gass from APK com.google.android.gms
,D/ChimeraCfgMgr( 1795): Loading module com.google.android.gms.vision from APK com.google.android.gms
,D/k       ( 1795): Processing package: com.test.thalitest
,D/dalvikvm( 1313): GC_EXPLICIT freed 990K, 43% free 10803K/18944K, paused 3ms+4ms, total 64ms
,W/BaseAppContext( 1795): Using Auth Proxy for data requests.
,W/BaseAppContext( 1795): Using Auth Proxy for data requests.
,W/BaseAppContext( 1795): Using Auth Proxy for data requests.
,W/BaseAppContext( 1795): Using Auth Proxy for data requests.
,W/BaseAppContext( 1795): Using Auth Proxy for data requests.
,W/BaseAppContext( 1795): Using Auth Proxy for data requests.
,D/GassUtils( 1795): Found app info for package com.test.thalitest:18. Hash: 4eebbbb84f07ed56a3e96e5e8f9d6abddaaf154fffa2a65432a1006e0fa38f32
,D/k       ( 1795): Found info for package com.test.thalitest in db.
,W/BaseAppContext( 1795): Using Auth Proxy for data requests.
,E/SMD     (  239): DCD ON
,D/dalvikvm( 4656): GC_FOR_ALLOC freed 5085K, 32% free 16788K/24464K, paused 38ms, total 40ms
,I/dalvikvm-heap( 4656): Grow heap (frag case) to 21.975MB for 2475476-byte allocation
,D/dalvikvm( 1795): GC_CONCURRENT freed 1628K, 38% free 11810K/18944K, paused 4ms+18ms, total 103ms
,W/dalvikvm( 1795): VFY: unable to find class referenced in signature (Landroid/util/Size;)
,D/ChimeraCfgMgr( 1795): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 1795): Module APK com.google.android.play.games already loaded
,D/BatteryService(  740): level:100, scale:100, status:5, health:2, present:true, voltage: 4367, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:9, charge type:1, power sharing:false
D/BatteryService(  740): stay LED for fully charged
,D/BatteryService(  740): Sending ACTION_BATTERY_CHANGED.
D/KeyguardUpdateMonitor( 1064): received broadcast android.intent.action.BATTERY_CHANGED
,D/UiModeManager(  740): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 1064): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1064):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1064): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP(  740): SIOP:: AP = 310, Delta = 10
,D/STATUSBAR-IconMerger( 1064): checkOverflow(384), More:false, Req:false Child:2
,D/dalvikvm( 4656): GC_FOR_ALLOC freed 3779K, 36% free 17474K/26884K, paused 35ms, total 36ms
,D/dalvikvm( 4656): GC_FOR_ALLOC freed 1243K, 36% free 17378K/26884K, paused 28ms, total 30ms
,W/jxcore-log( 4656): Initializing JXcore engine
,W/jxcore-log( 4656): JXcore engine is ready
,W/jxcore-log( 4656): Starting JXcore engine
,I/Icing   ( 1795): Indexing 49CA7E3A917E607C6D98AA15891295369CED2106 from com.google.android.gms
,I/Icing   ( 1795): Indexing done 49CA7E3A917E607C6D98AA15891295369CED2106
,W/jxcore-log( 4656): Platform android
W/jxcore-log( 4656): 
,W/jxcore-log( 4656): Process ARCH arm
W/jxcore-log( 4656): 
,I/jxcore-log( 4656): JXcore Cordova bridge is ready!
I/jxcore-log( 4656): 
,W/jxcore-log( 4656): JXcore engine is started
,I/chromium( 4656): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot call method 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,E/SMD     (  239): DCD ON
,I/GAV2    ( 4713): Thread[GAThread,5,main]: No campaign data found.
,I/jxcore-log( 4656): Toggling radios to true
I/jxcore-log( 4656): 
,D/dalvikvm(  740): GC_EXPLICIT freed 2042K, 58% free 23380K/54724K, paused 7ms+13ms, total 127ms
,W/ActivityManager(  740): Permission Denial: getCurrentUser() from pid=4656, uid=10179 requires android.permission.INTERACT_ACROSS_USERS
,W/BluetoothManagerService(  740): Failed getting userId using ActivityManagerNative
W/BluetoothManagerService(  740): java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=4656, uid=10179 requires android.permission.INTERACT_ACROSS_USERS
W/BluetoothManagerService(  740): 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:20710)
W/BluetoothManagerService(  740): 	at com.android.server.BluetoothManagerService.enable(BluetoothManagerService.java:620)
W/BluetoothManagerService(  740): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:98)
W/BluetoothManagerService(  740): 	at android.os.Binder.execTransact(Binder.java:404)
W/BluetoothManagerService(  740): 	at dalvik.system.NativeStart.run(Native Method)
E/DevicePolicyManagerService(  740): getAllowBluetoothMode - value retunrs : 2
,D/BluetoothManagerService(  740): foregroundUser: 0
,E/BluetoothManagerService(  740): Package is exist.
,D/BluetoothAdapterState( 3163): CURRENT_STATE=OFF, MSG = USER_TURN_ON
I/BluetoothAdapterState( 3163): Bluetooth adapter state changed: 10-> 11
I/WifiManager( 4656): packageName : com.test.thalitest
D/BluetoothAdapterService( 3163): Bluetooth PBAP supproted is true
,D/BluetoothAdapterService( 3163): updateAdapterState state is 11
D/BluetoothAdapterService( 3163): Broadcasting updateAdapterState() to 1 receivers.
D/BluetoothAdapterService( 3163): Autoconnection is available 
,I/WifiManager( 4656): setWifiEnabled : true
D/BluetoothAdapterService( 3163): updateAdapterState prevState = 10newState = 11
,I/WifiService(  740): setWifiEnabled: true pid=4656, uid=10179
D/BtConfig.SecureMode( 3163): isSecureModeOn:false
,D/BtSettings.ProfileConfig( 3163): getProfileSaveSetting: com.android.bluetooth.gatt.GattService
,W/BluetoothAdapterService( 3163): isProfileEnabled(): profile com.android.bluetooth.gatt.GattService, state= 12
,D/BtSettings.ProfileConfig( 3163): getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
W/ActivityManager(  740): Permission Denial: getCurrentUser() from pid=4656, uid=10179 requires android.permission.INTERACT_ACROSS_USERS
W/InputMethodManagerService(  740): InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
,I/InputMethodManagerService(  740): [BT Setting State] State =11
W/WifiService(  740): Failed getting userId using ActivityManagerNative
W/WifiService(  740): java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=4656, uid=10179 requires android.permission.INTERACT_ACROSS_USERS
W/WifiService(  740): 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:20710)
W/WifiService(  740): 	at com.android.server.wifi.WifiService.setWifiEnabled(WifiService.java:2348)
W/WifiService(  740): 	at com.android.server.wifi.WifiService.setWifiEnabled(WifiService.java:2336)
W/WifiService(  740): 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:178)
W/WifiService(  740): 	at android.os.Binder.execTransact(Binder.java:404)
W/WifiService(  740): 	at dalvik.system.NativeStart.run(Native Method)
,E/WifiHW  (  740): ##################### set firmware type 0 #####################
,I/WifiService(  740): disconnect: pid=4656, uid=10179
,D/PhoneApp( 1234): mReceiver: BluetoothAdapter.ACTION_STATE_CHANGED: 11
,I/QuickConnect[1.1][2] ( 3137): BluetoothHelper.ACTION_STATE_CHANGED - STATE_TURNING_ON
W/BluetoothAdapterService( 3163): isProfileEnabled(): profile not found com.android.bluetooth.hfp.HeadsetService
,D/BtSettings.ProfileConfig( 3163): getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
,I/jxcore-log( 4656): Radios toggled
I/jxcore-log( 4656): 
W/BluetoothAdapterService( 3163): isProfileEnabled(): profile not found com.android.bluetooth.a2dp.A2dpService
,D/BtSettings.ProfileConfig( 3163): getProfileSaveSetting: com.android.bluetooth.hid.HidService
,I/jxcore-log( 4656): Got Device Bluetooth address: 38:94:96:B5:06:DC
I/jxcore-log( 4656): 
W/BluetoothAdapterService( 3163): isProfileEnabled(): profile not found com.android.bluetooth.hid.HidService
,D/BtSettings.ProfileConfig( 3163): getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
,W/BluetoothAdapterService( 3163): isProfileEnabled(): profile not found com.android.bluetooth.hdp.HealthService
,D/BtSettings.ProfileConfig( 3163): getProfileSaveSetting: com.android.bluetooth.pan.PanService
,W/BluetoothAdapterService( 3163): isProfileEnabled(): profile not found com.android.bluetooth.pan.PanService
,D/BtSettings.ProfileConfig( 3163): getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
,W/BluetoothAdapterService( 3163): isProfileEnabled(): profile not found com.android.bluetooth.map.BluetoothMapService
W/BluetoothAdapterService( 3163): Unable to stop service com.android.bluetooth.gatt.GattService. Invalid state: 12
W/BluetoothAdapterService( 3163): check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.hfp.HeadsetService
D/BtSettings.ProfileConfig( 3163): getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
,W/BluetoothAdapterService( 3163): Not skipping com.android.bluetooth.hfp.HeadsetService
W/BluetoothAdapterService( 3163): check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.a2dp.A2dpService
D/BtSettings.ProfileConfig( 3163): getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
,W/BluetoothAdapterService( 3163): Not skipping com.android.bluetooth.a2dp.A2dpService
W/BluetoothAdapterService( 3163): check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.hid.HidService
D/BtSettings.ProfileConfig( 3163): getProfileSaveSetting: com.android.bluetooth.hid.HidService
,W/BluetoothAdapterService( 3163): Not skipping com.android.bluetooth.hid.HidService
,D/QuickConnect[1.1][2] ( 3137): HeadsetProfile.onServiceConnected - Bluetooth service connected
W/BluetoothAdapterService( 3163): check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.hdp.HealthService
D/BtSettings.ProfileConfig( 3163): getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
,W/BluetoothAdapterService( 3163): Not skipping com.android.bluetooth.hdp.HealthService
,W/BluetoothAdapterService( 3163): check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.pan.PanService
,D/HeadsetService( 3163): Received start request. Starting profile...
,I/BluetoothHeadsetServiceJni( 3163): classInitNative: succeeds
D/BtSettings.ProfileConfig( 3163): getProfileSaveSetting: com.android.bluetooth.pan.PanService
W/BluetoothAdapterService( 3163): Not skipping com.android.bluetooth.pan.PanService
D/HeadsetStateMachine( 3163): Version 1.6
,D/HeadsetStateMachine( 3163): make
,W/BluetoothAdapterService( 3163): check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.map.BluetoothMapService
,I/jxcore-log( 4656): Perf Test app loaded loaded
I/jxcore-log( 4656): 
,D/BtSettings.ProfileConfig( 3163): getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
W/BluetoothAdapterService( 3163): Not skipping com.android.bluetooth.map.BluetoothMapService
,E/HeadsetStateMachine( 3163): # of Max HF connection is 2
,I/BluetoothAdapterState( 3163): Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
,I/jxcore-log( 4656): check test folder
I/jxcore-log( 4656): 
,I/jxcore-log( 4656): found test : ./testFindPeers.js
I/jxcore-log( 4656): 
,I/bluedroid( 3163): get_profile_interface handsfree
,D/BluetoothAtMessage( 3163): createCMTIContentObservers
,D/HeadsetStateMachine( 3163): Enter Disconnected: -2
,E/HeadsetStateMachine( 3163): set to mRemoteBrsf = 0
,D/BluetoothNotiBroadcastReceiver( 1300): onReceive
D/HeadsetStateMachine( 3163): map size, before remove : 0
D/HeadsetStateMachine( 3163): map size, after remove: 0
,D/HeadsetStateMachine( 3163): mNextConnectingDevice : null
,D/BluetoothA2dp( 2024): Proxy object connected
,D/BluetoothA2dp( 3137): Proxy object connected
,D/BluetoothA2dp(  740): Proxy object connected
,D/QuickConnect[1.1][2] ( 3137): A2dpProfile.onServiceConnected - Bluetooth service connected
,D/A2dpService( 3163): Received start request. Starting profile...
I/BluetoothA2dpServiceJni( 3163): classInitNative: succeeds
,D/A2dpStateMachine( 3163): make
,I/bluedroid( 3163): get_profile_interface a2dp
,I/GKI_LINUX( 3163): gki_task_entry: gki_task_entry task_id=2 [A2DP-MEDIA] starting
,D/A2dpStateMachine( 3163): Enter Disconnected: -2
I/BluetoothAvrcpServiceJni( 3163): classInitNative: succeeds
,I/bluedroid( 3163): get_profile_interface avrcp
,D/MediaFocusControl(  740): >>> registerRemoteControlDisplay
,E/MediaFocusControl(  740): Error updating focussed RCC to RCD 
E/MediaFocusControl(  740): java.util.EmptyStackException
E/MediaFocusControl(  740): 	at java.util.Stack.peek(Stack.java:57)
E/MediaFocusControl(  740): 	at android.media.MediaFocusControl.registerRemoteControlDisplay_int(MediaFocusControl.java:2308)
E/MediaFocusControl(  740): 	at android.media.MediaFocusControl.registerRemoteControlDisplay(MediaFocusControl.java:250)
E/MediaFocusControl(  740): 	at android.media.AudioService.registerRemoteControlDisplay(AudioService.java:6425)
E/MediaFocusControl(  740): 	at android.media.IAudioService$Stub.onTransact(IAudioService.java:593)
E/MediaFocusControl(  740): 	at android.os.Binder.execTransact(Binder.java:404)
E/MediaFocusControl(  740): 	at dalvik.system.NativeStart.run(Native Method)
,I/BluetoothHidServiceJni( 3163): classInitNative: succeeds
,D/BluetoothInputDevice( 3137): Proxy object connected
,D/QuickConnect[1.1][2] ( 3137): HidProfile.onServiceConnected - Bluetooth service connected
,D/HidService( 3163): Received start request. Starting profile...
I/bluedroid( 3163): get_profile_interface hidhost
,D/HidService( 3163): setHidService(): set to: null
I/BluetoothHealthServiceJni( 3163): classInitNative: succeeds
,I/jxcore-log( 4656): found test : ./testSendData.js
I/jxcore-log( 4656): 
,D/HealthService( 3163): Received start request. Starting profile...
,I/bluedroid( 3163): get_profile_interface health
,I/BluetoothPanServiceJni( 3163): classInitNative(L105): succeeds
,D/BluetoothPan(  740): BluetoothPAN Proxy object connected
D/PanService( 3163): Received start request. Starting profile...
D/BluetoothPanServiceJni( 3163): initializeNative(L110): pan
I/bluedroid( 3163): get_profile_interface pan
,D/BluetoothTethering(  740): got CMD_CHANNEL_HALF_CONNECTED
,D/BluetoothMapService( 3163): Received start request. Starting profile...
,W/BluetoothMapMasInstance( 3163): mAccount : null
,D/HeadsetStateMachine( 3163): Try to query the phonestate on bind
D/BluetoothPhoneService( 1234): handleMessage: 4
,D/HeadsetPhoneState( 3163): sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=0
,D/HeadsetStateMachine( 3163): Proxy object connected
,V/BluetoothPhoneService( 1234): Call state Converted2: IDLE/IDLE -> 6
,D/HeadsetStateMachine( 3163): Disconnected process message: 11
,W/BluetoothHeadset( 1234): Proxy not attached to service
,D/HeadsetPhoneState( 3163): sendDeviceDataStateChanged
D/HeadsetStateMachine( 3163): Disconnected process message: 20
,D/HeadsetPhoneState( 3163): Signal level : previous=0 curr=0
D/BluetoothAdapterService( 3163): Profile still not running:com.android.bluetooth.hdp.HealthService
V/HeadsetService( 3163): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3163): Disconnected process message: 10
D/HeadsetPhoneState( 3163): sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
,D/HeadsetStateMachine( 3163): Disconnected process message: 11
,D/BluetoothAdapterService( 3163): Profile still not running:com.android.bluetooth.hdp.HealthService
D/BluetoothAdapterService( 3163): Profile still not running:com.android.bluetooth.hdp.HealthService
,D/BluetoothAdapterService( 3163): Profile still not running:com.android.bluetooth.map.BluetoothMapService
,D/BluetoothAdapterService( 3163): Profile still not running:com.android.bluetooth.map.BluetoothMapService
D/BluetoothAdapterState( 3163): CURRENT_STATE=PENDING, MSG = STARTED, isTurningOn=true, isTurningOff=false
,I/bluedroid( 3163): enable
,D/GKI_LINUX( 3163): acquire_my_wake_lock(), g_wake_lock_fd:-1, g_wake_unlock_fd:-1, wake_lock_acquired:0
,E/bt-btif ( 3163): Calling BTA_HhEnable
,E/bt-btif ( 3163): btif_storage_get_adapter_property service_mask:0x140040
,E/BluetoothServiceJni( 3163): populateRssiValuesNative
I/bluedroid( 3163): getModelRssiValues
,E/BluetoothServiceJni( 3163): model_rssi_values_callback: low = -70, mid = -60, high = 127
,D/AuthorizationBluetoothService( 1313): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,E/BluetoothRemoteDevices( 3163): devicePropertyChangedCallback: bdDevice: 08:EC:A9:50:75:41, value is empty for type: 10
,D/BtConfig.SecureMode( 3163): isSecureModeOn:false
,E/BluetoothRemoteDevices( 3163): devicePropertyChangedCallback: bdDevice: 08:EC:A9:50:75:41, value is empty for type: 241
,E/BluetoothRemoteDevices( 3163): devicePropertyChangedCallback: bdDevice: 80:01:84:8A:B3:68, value is empty for type: 10
,D/BtConfig.SecureMode( 3163): isSecureModeOn:false
,E/BluetoothRemoteDevices( 3163): devicePropertyChangedCallback: bdDevice: 80:01:84:8A:B3:68, value is empty for type: 241
,E/BluetoothRemoteDevices( 3163): devicePropertyChangedCallback: bdDevice: B0:C5:59:3F:75:69, value is empty for type: 10
,D/BtConfig.SecureMode( 3163): isSecureModeOn:false
,E/BluetoothRemoteDevices( 3163): devicePropertyChangedCallback: bdDevice: B0:C5:59:3F:75:69, value is empty for type: 241
,E/BluetoothRemoteDevices( 3163): devicePropertyChangedCallback: bdDevice: 00:F4:6F:30:E0:6C, value is empty for type: 10
,D/BtConfig.SecureMode( 3163): isSecureModeOn:false
,E/BluetoothRemoteDevices( 3163): devicePropertyChangedCallback: bdDevice: 00:F4:6F:30:E0:6C, value is empty for type: 241
,E/BluetoothRemoteDevices( 3163): devicePropertyChangedCallback: bdDevice: 34:FC:EF:9D:93:0B, value is empty for type: 10
,D/BtConfig.SecureMode( 3163): isSecureModeOn:false
,E/BluetoothRemoteDevices( 3163): devicePropertyChangedCallback: bdDevice: 34:FC:EF:9D:93:0B, value is empty for type: 241
,E/BluetoothRemoteDevices( 3163): devicePropertyChangedCallback: bdDevice: 7C:F9:0E:51:18:22, value is empty for type: 10
,D/BtConfig.SecureMode( 3163): isSecureModeOn:false
,E/BluetoothRemoteDevices( 3163): devicePropertyChangedCallback: bdDevice: 7C:F9:0E:51:18:22, value is empty for type: 241
,E/BluetoothRemoteDevices( 3163): devicePropertyChangedCallback: bdDevice: B4:CE:F6:AB:A4:6A, value is empty for type: 10
,D/BtConfig.SecureMode( 3163): isSecureModeOn:false
,E/BluetoothRemoteDevices( 3163): devicePropertyChangedCallback: bdDevice: B4:CE:F6:AB:A4:6A, value is empty for type: 241
,E/BluetoothRemoteDevices( 3163): devicePropertyChangedCallback: bdDevice: 34:FC:EF:11:AE:67, value is empty for type: 10
,D/BtConfig.SecureMode( 3163): isSecureModeOn:false
,E/BluetoothRemoteDevices( 3163): devicePropertyChangedCallback: bdDevice: 34:FC:EF:11:AE:67, value is empty for type: 241
,E/BluetoothRemoteDevices( 3163): devicePropertyChangedCallback: bdDevice: 34:FC:EF:11:B1:66, value is empty for type: 10
,D/BtConfig.SecureMode( 3163): isSecureModeOn:false
,E/BluetoothRemoteDevices( 3163): devicePropertyChangedCallback: bdDevice: 34:FC:EF:11:B1:66, value is empty for type: 241
,E/BluetoothRemoteDevices( 3163): devicePropertyChangedCallback: bdDevice: 90:E7:C4:F6:69:77, value is empty for type: 10
,D/BtConfig.SecureMode( 3163): isSecureModeOn:false
,E/BluetoothRemoteDevices( 3163): devicePropertyChangedCallback: bdDevice: 90:E7:C4:F6:69:77, value is empty for type: 241
E/bt-btif ( 3163): btif_handle_bluetooth_enable_evt: btif_core_radio_ref_count:2
E/bt-btif ( 3163): btif_sock_init, radio_req:0, rfc_init:0, vhci_init:1
E/bt-btif ( 3163): btif_sock_init: !radio_req && !rfc_init
,D/IOP_DB_BT( 3163): db_open: file /etc/bluetooth/iop_bt.db
,D/IOP_DB_BT( 3163): db_open: db_open : handle 2012521240l, read 9734 bytes onto local cache
D/IOP_DB_BT( 3163): db_query: id __IOPFLAGS :: key __KEY_ENABLE_VERBOSE, value 1
,D/IOP_DB_BT( 3163): db_query: result 1
I/        ( 3163): iop_db_open: iop_db_open status 0
,I/bte_conf( 3163): Attempt to load did conf from /etc/bluetooth/bt_did.conf
,I/bte_conf( 3163): [1] primary_record=1 vendor_id=0x0075 vendor_id_source=0x0001 product_id=0x0100 version=0x0200
I/bte_conf( 3163): Attempt to load did conf from /etc/bluetooth/bt_did.conf
,I/bte_conf( 3163): Attempt to load did conf from /etc/bluetooth/bt_did.conf
D/BluetoothAdapterState( 3163): CURRENT_STATE=PENDING, MSG = ENABLE_READY, isTurningOn=true, isTurningOff=false
D/BluetoothAdapterProperties( 3163): ScanMode =  20
,D/BluetoothAdapterProperties( 3163): State =  11
,D/BtConfig.SecureMode( 3163): isSecureModeOn:false
D/BtConfig.SecureMode( 3163): isSecureModeOn:false
,D/BtConfig.SecureMode( 3163): isSecureModeOn:false
D/BtConfig.SecureMode( 3163): isSecureModeOn:false
D/BtConfig.SecureMode( 3163): isSecureModeOn:false
,D/BtConfig.SecureMode( 3163): isSecureModeOn:false
D/BtConfig.SecureMode( 3163): isSecureModeOn:false
D/BtConfig.SecureMode( 3163): isSecureModeOn:false
,D/BtConfig.SecureMode( 3163): isSecureModeOn:false
,D/BtConfig.SecureMode( 3163): isSecureModeOn:false
,I/BluetoothAdapterState( 3163): Bluetooth adapter state changed: 11-> 12
,D/BluetoothAdapterService( 3163): Bluetooth PBAP supproted is true
,D/BluetoothAdapterService( 3163): updateAdapterState state is 12
,D/BluetoothAdapterService( 3163): Broadcasting updateAdapterState() to 1 receivers.
D/BluetoothAdapterService(1113472432)( 3163): Register RemoteMessageListener
,D/BluetoothA2dp(  740): onBluetoothStateChange: up=true
,D/HeadsetService( 3163): registerMessageListener
D/BluetoothAdapterService( 3163): Autoconnection is available 
D/HeadsetStateMachine( 3163): Disconnected process message: 70
,D/HeadsetStateMachine( 3163): processRegisterMessageListener : 2, com.android.bluetooth.btservice.RemoteDevices$1@42626910
D/BluetoothAdapterService( 3163): updateAdapterState prevState = 11newState = 12
,D/BluetoothAdapterService( 3163): starting service from this receiver
,D/BluetoothInputDevice( 3137): onBluetoothStateChange: up=true
,D/BluetoothA2dp( 3137): onBluetoothStateChange: up=true
,D/BluetoothA2dp( 2024): onBluetoothStateChange: up=true
,D/BluetoothAdapterService( 3163): initWakeLock, pfd lock: {ParcelFileDescriptor: FileDescriptor[91]}, pfd unlock: {ParcelFileDescriptor: FileDescriptor[92]}
D/bluedroid( 3163): init_wake_lock lock_fd:91, unlock_fd:92
,W/ContextImpl( 3163): Implicit intents with startService are not safe: Intent { act=com.samsung.ble.ACTION_SERVICE_BLE_AUTO_CONNECT } android.content.ContextWrapper.startService:506 com.android.bluetooth.btservice.AdapterService.updateAdapterState:653 com.android.bluetooth.btservice.AdapterState.notifyAdapterStateChange:586 
I/WifiTrafficPoller(  740): mBoosterFLAG : 2
,I/WifiTrafficPoller(  740): current booster mode : BTCoexMode
,D/BluetoothAdapterService(1113472432)( 3163): Get Bonded Devices being called
W/InputMethodManagerService(  740): InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
I/InputMethodManagerService(  740): [BT Setting State] State =12
I/InputMethodManagerService(  740): [BT Setting off -> on] mBTKeyboardCount =0, KEYBOARD_BT(0)
,D/PhoneApp( 1234): mReceiver: BluetoothAdapter.ACTION_STATE_CHANGED: 12
,I/QuickConnect[1.1][2] ( 3137): BluetoothHelper.ACTION_STATE_CHANGED - STATE_ON
,D/BluetoothHeadset( 1234): registerListener : 11, listenercom.android.phone.PhoneGlobals$MessageListener@42796768, true
,D/BluetoothHeadset( 1234): registerMessageListener
,D/HeadsetService( 3163): registerMessageListener
,I/BluetoothAdapterState( 3163): Entering On State from state = 11
D/HeadsetService( 3163): registerMessageListener
D/HeadsetStateMachine( 3163): Disconnected process message: 70
D/HeadsetStateMachine( 3163): processRegisterMessageListener : 11, com.samsung.bt.hfp.IMessageListener$Stub$Proxy@426acfe0
,D/PhoneApp( 1234): registerMessageListener
,I/BluetoothPbapService( 3163): action: android.bluetooth.adapter.action.STATE_CHANGED, state: 12
,I/chromium( 4656): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,D/STATUSBAR-IconMerger( 1064): checkOverflow(336), More:false, Req:false Child:2
D/BluetoothPanServiceJni( 3163): control_state_callback(L61): state:0, local_role:0, ifname:bt-pan
,I/BluetoothPbapService( 3163): Handler(): got msg=1
,W/ContextImpl( 1300): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1857 android.content.ContextWrapper.startService:506 android.content.ContextWrapper.startService:506 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
V/BluetoothPbapService( 3163): PBAP Service initSocket try: 0
,W/BluetoothAdapter( 3163): getBluetoothService() called with no BluetoothManagerCallback
,E/BluetoothServiceJni( 3163): SOCK FLAG = 1 ***********************
,D/BluetoothPbapService( 3163): PBAP Socket is BluetoothServerSocket
,D/BluetoothMapMasInstance( 3163): set MAP SDP message type : 1
,W/BluetoothAdapter( 3163): getBluetoothService() called with no BluetoothManagerCallback
,E/BluetoothServiceJni( 3163): SOCK FLAG = 3 ***********************
,D/LocalBluetoothProfileManager( 1300): Adding local A2DP profile
,W/ContextImpl( 1300): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1930 android.content.ContextWrapper.bindService:529 android.bluetooth.BluetoothA2dp.doBind:221 android.bluetooth.BluetoothA2dp.<init>:214 android.bluetooth.BluetoothAdapter.getProfileProxy:1412 
D/LocalBluetoothProfileManager( 1300): Adding local HEADSET profile
,E/BluetoothHeadset( 1300): BTStateChangeCB is registed
,E/BluetoothHeadset( 1300): BluetoothHeadset service is binded
W/ContextImpl( 1300): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1930 android.content.ContextWrapper.bindService:529 android.bluetooth.BluetoothHeadset.doBind:304 android.bluetooth.BluetoothHeadset.<init>:297 android.bluetooth.BluetoothAdapter.getProfileProxy:1409 
,D/Bluetoothsap( 1300): bindService called to Bluetooth SAP Service
W/ContextImpl( 1300): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1930 android.content.ContextWrapper.bindService:529 com.broadcom.bt.service.sap.BluetoothSap.doBind:186 com.broadcom.bt.service.sap.BluetoothSap.<init>:179 com.android.settings.bluetooth.SapProfile.<init>:129 
W/ContextImpl( 1300): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1930 android.content.ContextWrapper.bindService:529 android.bluetooth.BluetoothInputDevice.doBind:245 android.bluetooth.BluetoothInputDevice.<init>:238 android.bluetooth.BluetoothAdapter.getProfileProxy:1415 
,D/LocalBluetoothProfileManager( 1300): PANU : true
,D/LocalBluetoothProfileManager( 1300): Adding local MAP profile
,W/ContextImpl( 1300): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1930 android.content.ContextWrapper.bindService:529 android.bluetooth.BluetoothPan.doBind:173 android.bluetooth.BluetoothPan.<init>:162 android.bluetooth.BluetoothAdapter.getProfileProxy:1418 
,D/BluetoothMap( 1300): Create BluetoothMap proxy object
W/ContextImpl( 1300): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1930 android.content.ContextWrapper.bindService:529 android.bluetooth.BluetoothMap.doBind:109 android.bluetooth.BluetoothMap.<init>:102 android.bluetooth.BluetoothAdapter.getProfileProxy:1424 
W/ContextImpl( 1300): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1930 android.content.ContextWrapper.bindService:529 android.bluetooth.BluetoothPbap.doBind:164 android.bluetooth.BluetoothPbap.<init>:157 com.android.settings.bluetooth.PbapServerProfile.<init>:68 
,D/Bluetoothsap( 1300): bindService called to Bluetooth SAP Service
,D/LocalBluetoothProfileManager( 1300): LocalBluetoothProfileManager construction complete
,D/DockEventReceiver( 1300): finishStartingService: stopping service
,D/BluetoothNotiBroadcastReceiver( 1300): onReceive
,D/BluetoothA2dp( 1300): Proxy object connected
,D/BtConfig.SecureMode( 3163): isSecureModeOn:false
,W/ContextImpl( 1300): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1930 android.content.ContextWrapper.bindService:529 com.broadcom.bt.service.sap.BluetoothSap.doBind:186 com.broadcom.bt.service.sap.BluetoothSap.<init>:179 com.android.settings.bluetooth.SapProfile.<init>:129 
D/A2dpProfile( 1300): Bluetooth service connected
D/GKI_LINUX( 3163): release_my_wake_lock(), g_wake_lock_fd:91, g_wake_unlock_fd:92, wake_lock_acquired:0
D/AuthorizationBluetoothService( 1313): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
E/AuthorizationBluetoothService( 1313): Proximity feature is not enabled.
D/HeadsetProfile( 1300): Bluetooth service connected
D/BluetoothInputDevice( 1300): Proxy object connected
,D/HidProfile( 1300): Bluetooth service connected
,D/BluetoothPan( 1300): BluetoothPAN Proxy object connected
,D/PanProfile( 1300): Bluetooth service connected
,D/BluetoothMap( 1300): Proxy object connected
,D/MapProfile( 1300): Bluetooth service connected
,D/BluetoothPbap( 1300): Proxy object connected
,D/PbapServerProfile( 1300): Bluetooth service connected
,W/BluetoothAdapter( 3163): getBluetoothService() called with no BluetoothManagerCallback
,E/BluetoothServiceJni( 3163): SOCK FLAG = 0 ***********************
D/GKI_LINUX( 3163): acquire_my_wake_lock(), g_wake_lock_fd:91, g_wake_unlock_fd:92, wake_lock_acquired:0
,I/BtOppRfcommListener( 3163): Accept thread started.
,D/Tethering(  740): interfaceAdded wlan0
,E/Tethering(  740): No numeric data
,D/Tethering(  740): sendTetherStateChangedBroadcast 1, 0, 0
,D/NtpTrustedTime(  740): forceRefresh() from cache miss
D/Tethering(  740): interfaceLinkStateChanged wlan0, false
,D/Tethering(  740): interfaceStatusChanged wlan0, false
,D/Tethering(  740): InitialState.processMessage what=4
I/ConnectivityService(  740): defaultVal : 1, tetherEnabledInSettings : true
,E/Tethering(  740): No numeric data
,D/Tethering(  740): sendTetherStateChangedBroadcast 0, 0, 0
,D/Tethering(  740): interfaceAdded p2p0
,D/Tethering(  740): p2p0 is not a tetherable iface, ignoring
,D/NtpTrustedTime(  740): forceRefresh Fail.
D/Tethering(  740): interfaceLinkStateChanged p2p0, false
,D/Tethering(  740): interfaceStatusChanged p2p0, false
I/ConnectivityService(  740): defaultVal : 1, tetherEnabledInSettings : true
V/NetworkStats(  740): performPollLocked(flags=0x1)
,I/WifiHW  (  236): wifi_change_fw_path(): fwpath = sta
,D/SoftapController(  236): Softap fwReload - Ok
,D/NtpTrustedTime(  740): forceRefresh() from cache miss
,D/NtpTrustedTime(  740): forceRefresh Fail.
D/NtpTrustedTime(  740): forceRefresh() from cache miss
,D/NtpTrustedTime(  740): forceRefresh Fail.
D/CommandListener(  236): Setting iface cfg
,D/CommandListener(  236): Trying to bring down wlan0
V/NetworkStats(  740): performPollLocked() took 15ms
V/NetworkStats(  740): performPollLocked(flags=0x1)
,D/NtpTrustedTime(  740): forceRefresh() from cache miss
,D/NtpTrustedTime(  740): forceRefresh Fail.
,D/WifiHW  (  740): Skip the update_ctrl_interface
,D/WifiHW  (  740): Skip the update_ctrl_interface
,E/WifiHW  (  740): supplicant_name : p2p_supplicant
V/NetworkStats(  740): performPollLocked() took 14ms
,D/GKI_LINUX( 3163): release_my_wake_lock(), g_wake_lock_fd:91, g_wake_unlock_fd:92, wake_lock_acquired:1
,I/wpa_supplicant( 4905): wpa_supplicant v2.1-devel-4.4.22014-11-04/18:06:52
,I/wpa_supplicant( 4905): [wpa_supplicant_init]: use SECRIL
I/wpa_supplicant( 4905): Successfully initialized wpa_supplicant
,I/wpa_supplicant( 4905): >>>>> Not GET KEY, IV <<<<<
,E/wpa_supplicant( 4905): getIMSI cannot open file
,E/wpa_supplicant( 4905): Interworking config: - SIM READ ERROR
,D/WifiMonitor(  740): startMonitoring(wlan0) with mConnected = false
D/STATUSBAR-NetworkController_dual( 1064): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
D/StatusBar.NetworkController_dual( 1064): mMobileLabelViews start
D/StatusBar.NetworkController_dual( 1064): mMobileLabelViews set mobileLabel[SIM_0] =No service.
D/StatusBar.NetworkController_dual( 1064): mMobileLabelViews GONE
D/StatusBar.NetworkController_dual( 1064): mMobileLabelViews2 set mobileLabel[SIM_1] =No service.
D/StatusBar.NetworkController_dual( 1064): mMobileLabelViews2 GONE
D/StatusBar.NetworkController_dual( 1064): mSingleMobileLabelViews set : simMode = 0
D/StatusBar.NetworkController_dual( 1064): mSingleMobileLabelViews set as slot1`s
,I/knox    ( 3076): MainReceiver.onReceive() : Intent { act=android.net.wifi.WIFI_STATE_CHANGED flg=0x4000010 cmp=com.sec.knox.seandroid/.receiver.MainReceiver (has extras) }
W/ContextImpl( 3076): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1857 android.content.ContextWrapper.startService:506 android.content.ContextWrapper.startService:506 com.sec.knox.seandroid.receiver.MainReceiver.onReceive:142 android.app.ActivityThread.handleReceiver:2698 
,I/knox    ( 3076): MainReceiver.onReceive() END - - - - - : Intent { act=android.net.wifi.WIFI_STATE_CHANGED flg=0x4000010 cmp=com.sec.knox.seandroid/.receiver.MainReceiver (has extras) }
,D/knox    ( 3076): KNOXAgentService : onCreate()
D/knox    ( 3076): KNOXAgentService : set alarms for deniallog and usage data upload
D/knox    ( 3076): KNOXAgentService. startJobThread() start
D/knox    ( 3076): KNOXAgentService. JobThread()
D/knox    ( 3076): KNOXAgentService. JobThread. notifyAll().
,D/knox    ( 3076): KNOXAgentService. startJobThread() wait
,I/SELinux ( 4907): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 4907):  
,I/wpa_supplicant( 4905): >>>>> Not GET KEY, IV <<<<<
E/wpa_supplicant( 4905): getIMSI cannot open file
,E/wpa_supplicant( 4905): Interworking config: - SIM READ ERROR
,I/wpa_supplicant( 4905): >>>>> Not GET KEY, IV <<<<<
,I/wpa_supplicant( 4905): rfkill: Cannot open RFKILL control device
,D/knox    ( 3076): KNOXAgentService : onDestroy().
,D/knox    ( 3076): ModuleBase.cancelAllAlarmManageModule()
,D/Tethering(  740): interfaceLinkStateChanged wlan0, false
,D/Tethering(  740): interfaceStatusChanged wlan0, false
,I/SELinux ( 4907): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 4907):  
I/SELinux ( 4907):  
,I/SELinux ( 4907): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
I/wpa_supplicant( 4905): wlan0: Setting scan request: 0 sec 100000 usec
,E/SELinux ( 4907): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 4907): >>>>> Normal User
,E/dalvikvm( 4907): >>>>> tv.peel.smartremote [ userId:0 | appId:10163 ]
,E/SELinux ( 4907): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
,D/TimaKeyStoreProvider( 4907): in addTimaSignatureService
,D/TimaKeyStoreProvider( 4907): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 4907): Added TimaKesytore provider
,W/ActivityManager(  740): Permission Denial: getCurrentUser() from pid=4907, uid=10163 requires android.permission.INTERACT_ACROSS_USERS
,I/wpa_supplicant( 4905): >>>>> Not GET KEY, IV <<<<<
,I/wpa_supplicant( 4905): >>>>> Not GET KEY, IV <<<<<
,I/wpa_supplicant( 4905): rfkill: Cannot open RFKILL control device
D/Tethering(  740): interfaceLinkStateChanged p2p0, false
,D/Tethering(  740): interfaceStatusChanged p2p0, false
D/Tethering(  740): interfaceLinkStateChanged p2p0, false
,D/Tethering(  740): interfaceStatusChanged p2p0, false
,I/wpa_supplicant( 4905): CTRL-EVENT-STATE-CHANGE id=-1 state=2 BSSID=00.00.00 SSID=
,I/wpa_supplicant( 4905): P2P: initialized channels: 81:1,2,3,4,5,6,7,8,9,10,11,12,13 115:36,40,44,48 116:36,44 117:40,48
I/wpa_supplicant( 4905): CTRL-EVENT-STATE-CHANGE id=-1 state=0 BSSID=00.00.00 SSID=
,I/wpa_supplicant( 4905): Skip scan - bUseNetwork false
,D/WifiStateMachine(  740): skipWifiStateBroadcast:false, LastBroadcastedWifiState:2
,D/WifiNative(  740): callSECApiString - ID [21]
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
,I/wpa_supplicant( 4905): HOTSPOT20_ENABLE called
,I/wpa_supplicant( 4905): wlan0: HS20_DISABLED_COMPLETE normal
,I/ActivityManager(  740): Killing 3678:com.sec.android.app.sns3/u0a36 (adj 15): empty #43
,I/knox    ( 3076): MainReceiver.onReceive() : Intent { act=android.net.wifi.WIFI_STATE_CHANGED flg=0x4000010 cmp=com.sec.knox.seandroid/.receiver.MainReceiver (has extras) }
,D/WifiNative(  740): callSECApiInt - ID [65]
,I/knox    ( 3076): MainReceiver.onReceive() END - - - - - : Intent { act=android.net.wifi.WIFI_STATE_CHANGED flg=0x4000010 cmp=com.sec.knox.seandroid/.receiver.MainReceiver (has extras) }
,W/ContextImpl( 3076): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1857 android.content.ContextWrapper.startService:506 android.content.ContextWrapper.startService:506 com.sec.knox.seandroid.receiver.MainReceiver.onReceive:142 android.app.ActivityThread.handleReceiver:2698 
D/knox    ( 3076): KNOXAgentService : onCreate()
D/knox    ( 3076): KNOXAgentService : set alarms for deniallog and usage data upload
D/knox    ( 3076): GSLBThreadManager.NetworkStateChanged : NETWORK_STATE_CHAGED. Upload Call Log Data
,E/WifiConfigStore(  740): Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
,D/knox    ( 3076): KNOXAgentService. startJobThread() start
D/knox    ( 3076): KNOXAgentService. JobThread()
,D/knox    ( 3076): KNOXAgentService. JobThread. notifyAll().
,D/knox    ( 3076): KNOXAgentService. startJobThread() wait
,D/WifiNative(  740): callSECApiBoolean - ID [13]
,I/wpa_supplicant( 4905): USE_NETWORK : USE_NETWORK ON
I/wpa_supplicant( 4905): reset timer : RESET_TIMER 0
,I/wpa_supplicant( 4905): wlan0: Setting scan request: 0 sec 0 usec
I/wpa_supplicant( 4905): CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00.00.00 SSID=
I/wpa_supplicant( 4905): First Scan Start
,I/wpa_supplicant( 4905): Scan requested (ret=0) - scan timeout 30 seconds
,E/WifiStateMachine(  740): Set the Nv default ccode
,W/Settings( 3033): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiStateMachine(  740): skipWifiStateBroadcast:false, LastBroadcastedWifiState:3
D/CommandListener(  236): Setting iface cfg
D/CommandListener(  236): Trying to bring up p2p0
D/knox    ( 3076): KNOXAgentService : onDestroy().
,D/knox    ( 3076): ModuleBase.cancelAllAlarmManageModule()
,E/WifiStateMachine(  740): HS20_DISABLED_COMPLETEnormal
,D/WifiP2pService(  740): P2pDisabledState{ what=131203 }
,D/WifiMonitor(  740): startMonitoring(p2p0) with mConnected = true
,E/WifiStateMachine(  740): BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
,D/QuickConnect[1.1][2] ( 3137): SconnectManager.INetworkStateListener, onEnabled - mNetworkState : 4
,I/wpa_supplicant( 4905): P2P: updated channels: 81:1,2,3,4,5,6,7,8,9,10,11,12,13 115:36,40,44,48 116:36,44 117:40,48
D/WifiP2pService(  740): P2pEnablingState
D/WifiP2pService(  740): P2pEnablingState{ what=147457 }
D/WifiP2pService(  740): P2p socket connection successful
D/WifiP2pService(  740): P2pEnabledState
W/ContextImpl(  740): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.android.server.enterprise.wifi.WifiPolicy.asyncEnableNetwork:3065 com.android.server.enterprise.wifi.WifiPolicy.edmUpdateConfiguredNetworks:2530 com.android.server.enterprise.wifi.WifiPolicy$2$2.run:3022 java.lang.Thread.run:841 
D/WifiP2pService(  740): sending p2p connection changed broadcast: IDLE
D/WifiDisplayController(  740): Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=true
D/WifiDisplayController(  740): updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
D/WifiDisplayController(  740): disconnect
D/WifiDisplayController(  740): updateConnection
D/WifiDisplayController(  740): updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
D/WifiDisplayAdapter(  740): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,D/QuickConnect[1.1][2] ( 3137): P2pHelper.onReceive - ACTION_WIFI_DISPLAY_STATUS_CHANGED :0
,D/QuickConnect[1.1][2] ( 3137): P2pHelper.onReceive - P2P_CONNECTION_CHANGED : 
D/WifiDisplayAdapter(  740): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
D/WifiDisplayController(  740): Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=NetworkInfo: type: WIFI_P2P[], state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/QuickConnect[1.1][2] ( 3137): SconnectManager.INetworkStateListener, onDisconnected - networkType : 4
,D/NearbySettings( 1300): MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
D/WifiP2pService(  740): DeviceAddress: 3a:06:dd
D/WifiDisplayController(  740): Received WIFI_P2P_THIS_DEVICE_CHANGED_ACTION: mThisDevice= Device: Galaxy S5-2
D/WifiDisplayController(  740):  deviceAddress: 3a:94:96:b5:06:dd
D/WifiDisplayController(  740):  primary type: 10-0050F204-5
D/WifiDisplayController(  740):  secondary type: null
D/WifiDisplayController(  740):  wps: 0
D/WifiDisplayController(  740):  grpcapab: 0
D/WifiDisplayController(  740):  devcapab: 0
D/WifiDisplayController(  740):  status: 3
D/WifiDisplayController(  740):  wfdInfo: null
D/WifiDisplayController(  740):  groupownerAddress: null
D/WifiDisplayController(  740):  GOdeviceName: null
D/WifiDisplayController(  740):  interfaceAddress: 
D/WifiDisplayController(  740):  SConnectInfo : null
,V/NearbySettings( 1300): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 1300): DMSUtil.isNetworkConnected - WIFI: IDLE
I/NearbySettings( 1300): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1300): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
,I/NearbySettings( 1300): MountReceiver.onReceive - Set preference state off
,V/NearbySettings( 1300): MountReceiver.mPrefHandler - 7002
W/WifiP2pStateTracker(  740): WifiP2pStateReceiver : android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,D/FileShare-Server( 4172): ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,D/QuickConnect[1.1][2] ( 3137): P2pHelper.requestGroupInfo  - onGroupInfoAvailable- null
,D/FileShare-Server( 4172): ServerBroadcastReceiver.onReceive - netInfo.getDetailedState() IDLE
D/WifiP2pService(  740): sending p2p persistent groups changed broadcast
D/WifiP2pService(  740): InactiveState
D/WifiP2pService(  740): InactiveState{ what=139287 }
D/WifiP2pService(  740): P2pEnabledState{ what=139287 }
D/WifiP2pService(  740): DefaultState{ what=139287 }
,D/Tethering(  740): interfaceLinkStateChanged p2p0, false
,D/Tethering(  740): interfaceStatusChanged p2p0, false
,I/wpa_supplicant( 4905): P2P: updated channels: 81:1,2,3,4,5,6,7,8,9,10,11,12,13 115:36,40,44,48 116:36,44 117:40,48
,I/wpa_supplicant( 4905): P2P: updated channels: 81:1,2,3,4,5,6,7,8,9,10,11,12,13 115:36,40,44,48 116:36,44 117:40,48
,E/SMD     (  239): DCD ON
,I/wpa_supplicant( 4905): nl80211: Received scan results (8 BSSes)
,I/wpa_supplicant( 4905): wlan0: Setting scan request: 8 sec 0 usec
I/wpa_supplicant( 4905): Trying to associate with SSID '4E47373030'
I/wpa_supplicant( 4905): Trying to associate with  'G700'
,I/wpa_supplicant( 4905): CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00.00.00 SSID=
,E/wpa_supplicant( 4905): Cmd 35609 not handled
,D/Tethering(  740): interfaceLinkStateChanged wlan0, false
,D/Tethering(  740): interfaceStatusChanged wlan0, false
,E/WifiStateMachine(  740): Error! unhandled message{ when=-6ms what=135188 target=com.android.internal.util.StateMachine$SmHandler }
,E/wpa_supplicant( 4905): Cmd 35605 not handled
E/wpa_supplicant( 4905): Cmd 35847 not handled
E/wpa_supplicant( 4905): Cmd 35848 not handled
,E/wpa_supplicant( 4905): Cmd 35605 not handled
I/wpa_supplicant( 4905): CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00.00.00 SSID=4E47373030
I/wpa_supplicant( 4905): Associated with C0.AA.48
,I/wpa_supplicant( 4905): CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=C0.AA.48 SSID=4E47373030
,D/Tethering(  740): interfaceLinkStateChanged wlan0, false
,D/Tethering(  740): interfaceStatusChanged wlan0, false
D/Tethering(  740): interfaceLinkStateChanged wlan0, false
,D/Tethering(  740): interfaceStatusChanged wlan0, false
D/Tethering(  740): interfaceLinkStateChanged wlan0, false
D/Tethering(  740): interfaceStatusChanged wlan0, false
D/Tethering(  740): interfaceLinkStateChanged wlan0, true
,D/Tethering(  740): interfaceStatusChanged wlan0, true
E/Tethering(  740): No numeric data
D/Tethering(  740): interfaceLinkStateChanged wlan0, true
,D/Tethering(  740): interfaceStatusChanged wlan0, true
,D/Tethering(  740): sendTetherStateChangedBroadcast 1, 0, 0
,D/NtpTrustedTime(  740): forceRefresh() from cache miss
,D/NtpTrustedTime(  740): forceRefresh Fail.
I/ConnectivityService(  740): defaultVal : 1, tetherEnabledInSettings : true
I/wpa_supplicant( 4905): CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=C0.AA.48 SSID=4E47373030
I/wpa_supplicant( 4905): WPA: Key negotiation completed with C0.AA.48 [PTK=CCMP GTK=CCMP]
,I/wpa_supplicant( 4905): CTRL-EVENT-CONNECTED - Connection to C0.AA.48 completed (auth) [id=0 id_str=]
D/Tethering(  740): interfaceLinkStateChanged wlan0, true
I/wpa_supplicant( 4905): CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=C0.AA.48 SSID=4E47373030
,D/Tethering(  740): interfaceStatusChanged wlan0, true
,D/Tethering(  740): interfaceLinkStateChanged wlan0, true
,D/Tethering(  740): interfaceStatusChanged wlan0, true
,D/WifiNative(  740): callSECApiVoid - ID [50]
V/NetworkStats(  740): performPollLocked(flags=0x1)
,D/Tethering(  740): interfaceLinkStateChanged wlan0, true
,D/Tethering(  740): interfaceStatusChanged wlan0, true
D/STATUSBAR-NetworkController_dual( 1064): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
D/StatusBar.NetworkController_dual( 1064): mMobileLabelViews start
D/StatusBar.NetworkController_dual( 1064): mMobileLabelViews set mobileLabel[SIM_0] =No service.
D/StatusBar.NetworkController_dual( 1064): mMobileLabelViews GONE
D/StatusBar.NetworkController_dual( 1064): mMobileLabelViews2 set mobileLabel[SIM_1] =No service.
D/StatusBar.NetworkController_dual( 1064): mMobileLabelViews2 GONE
D/StatusBar.NetworkController_dual( 1064): mSingleMobileLabelViews set : simMode = 0
D/StatusBar.NetworkController_dual( 1064): mSingleMobileLabelViews set as slot1`s
,V/NetworkStats(  740): performPollLocked() took 44ms
,I/SELinux ( 4947): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 4947):  
,D/NtpTrustedTime(  740): forceRefresh() from cache miss
,D/NtpTrustedTime(  740): forceRefresh Fail.
D/STATUSBAR-NetworkController_dual( 1064): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
D/StatusBar.NetworkController_dual( 1064): mMobileLabelViews start
D/StatusBar.NetworkController_dual( 1064): mMobileLabelViews set mobileLabel[SIM_0] =No service.
D/StatusBar.NetworkController_dual( 1064): mMobileLabelViews GONE
D/StatusBar.NetworkController_dual( 1064): mMobileLabelViews2 set mobileLabel[SIM_1] =No service.
D/StatusBar.NetworkController_dual( 1064): mMobileLabelViews2 GONE
D/StatusBar.NetworkController_dual( 1064): mSingleMobileLabelViews set : simMode = 0
D/StatusBar.NetworkController_dual( 1064): mSingleMobileLabelViews set as slot1`s
D/STATUSBAR-NetworkController_dual( 1064): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
D/StatusBar.NetworkController_dual( 1064): mMobileLabelViews start
D/StatusBar.NetworkController_dual( 1064): mMobileLabelViews set mobileLabel[SIM_0] =No service.
D/StatusBar.NetworkController_dual( 1064): mMobileLabelViews GONE
D/StatusBar.NetworkController_dual( 1064): mMobileLabelViews2 set mobileLabel[SIM_1] =No service.
D/StatusBar.NetworkController_dual( 1064): mMobileLabelViews2 GONE
D/StatusBar.NetworkController_dual( 1064): mSingleMobileLabelViews set : simMode = 0
D/StatusBar.NetworkController_dual( 1064): mSingleMobileLabelViews set as slot1`s
,D/dalvikvm(  246): GC_EXPLICIT freed 43K, 50% free 9512K/18944K, paused 3ms+2ms, total 29ms
,D/WifiP2pService(  740): InactiveState{ what=143375 }
,I/SELinux ( 4947): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 4947):  
I/SELinux ( 4947):  
,I/SELinux ( 4947): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 4947): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
D/dalvikvm(  246): GC_EXPLICIT freed <1K, 50% free 9512K/18944K, paused 2ms+4ms, total 19ms
E/dalvikvm( 4947): >>>>> Normal User
,E/dalvikvm( 4947): >>>>> com.vlingo.midas [ userId:0 | appId:10033 ]
,E/SELinux ( 4947): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
D/WifiP2pService(  740): P2pEnabledState{ what=143375 }
,D/TimaKeyStoreProvider( 4947): in addTimaSignatureService
,D/dalvikvm(  246): GC_EXPLICIT freed <1K, 50% free 9512K/18944K, paused 1ms+2ms, total 18ms
,D/TimaKeyStoreProvider( 4947): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 4947): Added TimaKesytore provider
,I/System.out( 4947): Inside WakeupProvider
,I/System.out( 4947): Inside onCreate() of WakeupTriggerProvide
,I/VlingoApplication( 4947): VlingoApplication appVersion ='11.4.0.3.34005', ro.csc.sales_code=XEO
,D/VlingoApplication( 4947): Couldn't create com.nuance.nuancedebugutilpackage context for host settings utility
,D/VlingoApplication( 4947): Couldn't create com.vlingo.midas.lmttutilitypackage context for host settings utility
,I/dhcpcd  ( 4962): if(wlan0) info get Success. (MAC : C0.AA.48)
,I/dhcpcd  ( 4962): bssid match
,D/NearbySettings( 1300): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 1300): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 1300): DMSUtil.isNetworkConnected - WIFI: OBTAINING_IPADDR
I/NearbySettings( 1300): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1300): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
,I/NearbySettings( 1300): MountReceiver.onReceive - Set preference state off
,V/NearbySettings( 1300): MountReceiver.mPrefHandler - 7002
,D/DialogFlow( 4947): initQueue()
I/ActivityManager(  740): Killing 3714:com.sec.spp.push:RemoteDlcProcess/u0a38 (adj 15): empty #43
,D/WifiP2pService(  740): InactiveState{ what=143375 }
,D/WifiP2pService(  740): P2pEnabledState{ what=143375 }
,D/WifiStateMachine(  740): VerifyingLinkState enter
D/STATUSBAR-NetworkController_dual( 1064): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
D/StatusBar.NetworkController_dual( 1064): mMobileLabelViews start
D/StatusBar.NetworkController_dual( 1064): mMobileLabelViews set mobileLabel[SIM_0] =No service.
D/StatusBar.NetworkController_dual( 1064): mMobileLabelViews GONE
D/StatusBar.NetworkController_dual( 1064): mMobileLabelViews2 set mobileLabel[SIM_1] =No service.
D/StatusBar.NetworkController_dual( 1064): mMobileLabelViews2 GONE
D/StatusBar.NetworkController_dual( 1064): mSingleMobileLabelViews set : simMode = 0
D/StatusBar.NetworkController_dual( 1064): mSingleMobileLabelViews set as slot1`s
D/STATUSBAR-NetworkController_dual( 1064): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
,D/StatusBar.NetworkController_dual( 1064): mMobileLabelViews start
,D/StatusBar.NetworkController_dual( 1064): mMobileLabelViews set mobileLabel[SIM_0] =No service.
D/StatusBar.NetworkController_dual( 1064): mMobileLabelViews GONE
D/StatusBar.NetworkController_dual( 1064): mMobileLabelViews2 set mobileLabel[SIM_1] =No service.
,D/StatusBar.NetworkController_dual( 1064): mMobileLabelViews2 GONE
,D/StatusBar.NetworkController_dual( 1064): mSingleMobileLabelViews set : simMode = 0
,D/StatusBar.NetworkController_dual( 1064): mSingleMobileLabelViews set as slot1`s
,D/WifiStateMachine(  740): VerifyingLinkState GOOD_LINK_DETECTED: transition to captive portal check
,D/WifiStateMachine(  740): CaptivePortalCheckState enter
,I/WifiTrafficPoller(  740): evaluateTrafficStatsPolling
,D/WifiStateMachine(  740): CaptivePortalCheckState CMD_CAPTIVE_CHECK_COMPLETE
D/ConnectivityService(  740): Captive portal check NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService(  740): handleCaptivePortalTrackerCheck: call captivePortalCheckComplete ni=NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/STATUSBAR-NetworkController_dual( 1064): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
D/StatusBar.NetworkController_dual( 1064): mMobileLabelViews start
D/StatusBar.NetworkController_dual( 1064): mMobileLabelViews set mobileLabel[SIM_0] =No service.
D/StatusBar.NetworkController_dual( 1064): mMobileLabelViews GONE
D/StatusBar.NetworkController_dual( 1064): mMobileLabelViews2 set mobileLabel[SIM_1] =No service.
D/StatusBar.NetworkController_dual( 1064): mMobileLabelViews2 GONE
D/StatusBar.NetworkController_dual( 1064): mSingleMobileLabelViews set : simMode = 0
D/StatusBar.NetworkController_dual( 1064): mSingleMobileLabelViews set as slot1`s
,D/NearbySettings( 1300): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,I/NearbySettings( 1300): MountReceiver.onReceive - Keep current state
,D/STATUSBAR-NetworkController_dual( 1064): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
,D/SignalClusterView_dual( 1064): wifi: GONE sig=2130837981 act=0
D/SignalClusterView_dual( 1064): mMobileDataState=0 mMobileDataState2=0
D/SignalClusterView_dual( 1064): apply() mSeparateMobileGroup=8
,D/STATUSBAR-NetworkController_dual( 1064): refreshSignalCluster - setNWBoosterIndicators(false)
,D/SignalClusterView_dual( 1064): wifi: VISIBLE sig=2130837979 act=2130837939
D/SignalClusterView_dual( 1064): mMobileDataState=0 mMobileDataState2=0
D/SignalClusterView_dual( 1064): apply() mSeparateMobileGroup=8
,D/SignalClusterView_dual( 1064): wifi: VISIBLE sig=2130837979 act=2130837939
D/SignalClusterView_dual( 1064): mMobileDataState=0 mMobileDataState2=0
D/SignalClusterView_dual( 1064): apply() mSeparateMobileGroup=8
D/SignalClusterView_dual( 1064): wifi: VISIBLE sig=2130837979 act=2130837939
,D/SignalClusterView_dual( 1064): mMobileDataState=0 mMobileDataState2=0
D/SignalClusterView_dual( 1064): apply() mSeparateMobileGroup=8
D/SignalClusterView_dual( 1064): wifi: VISIBLE sig=2130837979 act=2130837939
D/SignalClusterView_dual( 1064): mMobileDataState=0 mMobileDataState2=0
,D/SignalClusterView_dual( 1064): apply() mSeparateMobileGroup=8
D/StatusBar.NetworkController_dual( 1064): mMobileLabelViews start
D/StatusBar.NetworkController_dual( 1064): mMobileLabelViews set mobileLabel[SIM_0] =
D/StatusBar.NetworkController_dual( 1064): mMobileLabelViews GONE
D/StatusBar.NetworkController_dual( 1064): mMobileLabelViews2 set mobileLabel[SIM_1] =
,D/StatusBar.NetworkController_dual( 1064): mMobileLabelViews2 GONE
D/StatusBar.NetworkController_dual( 1064): mSingleMobileLabelViews set : simMode = 0
,I/WifiTrafficPoller(  740): evaluateTrafficStatsPolling
,I/WifiTrafficPoller(  740): mBoosterFLAG : 2
,I/WifiTrafficPoller(  740): current booster mode : BTCoexMode
D/StatusBar.NetworkController_dual( 1064): mSingleMobileLabelViews set as slot1`s
,D/NearbySettings( 1300): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
D/ConnectivityService(  740): ConnectivityChange for WIFI: CONNECTED/CONNECTED
E/ConnectivityService(  740): net.tcp.usercfg.wifi not found in system properties. Using defaults
E/ConnectivityService(  740): net.tcp.delack.wifi not found in system properties. Using defaults
,D/STATUSBAR-IconMerger( 1064): checkOverflow(288), More:false, Req:false Child:2
V/NearbySettings( 1300): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 1300): DMSUtil.isNetworkConnected - WIFI: CONNECTED
,I/NearbySettings( 1300): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1300): DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
,I/NearbySettings( 1300): MountReceiver.onReceive - Keep current state
,D/ConnectivityService(  740): handleConnectivityChange: setting default proxy info 
,V/RouteController(  236): /system/bin/ip -4 route replace default via 192.168.1.1 dev wlan0 scope global table 2 2>&1
,V/RouteController(  236): /system/bin/ip -4 rule del table 2 2>&1
,V/RouteController(  236): RTNETLINK answers: No such file or directory
,V/RouteController(  236): /system/bin/ip -4 rule add from 192.168.1.143 lookup 2 prio 150 2>&1
,D/Toast   ( 1300):  checkMirrorLinkEnabled returns : false
,D/Toast   ( 1300): showing allowed
,V/RouteController(  236): /system/bin/ip route flush cached 2>&1
,D/NearbySettings( 1300): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,I/NearbySettings( 1300): MountReceiver.onReceive - Keep current state
,V/RouteController(  236): /system/bin/ip route del 192.168.1.0/24 table 2 2>&1
,I/SurfaceFlinger(  245): id=18 createSurf (1x1),1 flag=4, Uoast
,D/KeyguardUpdateMonitor( 1064): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1064): handleKeyguardVisibilityChanged(1)
,V/RouteController(  236): RTNETLINK answers: No such process
,V/RouteController(  236): /system/bin/ip route add 192.168.1.0/24 dev wlan0 table 2 metric 0 2>&1
,D/PowerManagerService(  740): [api] acquire WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=740
V/RouteController(  236): /system/bin/ip route flush cached 2>&1
D/KeyguardUpdateMonitor( 1064): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1064): handleKeyguardVisibilityChanged(1)
D/KeyguardUpdateMonitor( 1064): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1064): handleKeyguardVisibilityChanged(1)
,D/NtpTrustedTime(  740): forceRefresh() from cache miss
V/NetworkStats(  740): updateIfacesLocked()
V/NetworkStats(  740): performPollLocked(flags=0x1)
,V/NetworkStats(  740): performPollLocked() took 17ms
,D/KeyguardUpdateMonitor( 1064): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1064): handleKeyguardVisibilityChanged(1)
,D/KeyguardUpdateMonitor( 1064): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1064): handleKeyguardVisibilityChanged(1)
,D/NtpTrustedTime(  740): requestTime Success from server:2.android.pool.ntp.org mCachedNtpTime : 1449832369683 mCachedNtpElapsedRealtime : 130066 mCachedNtpCertainty : 12
,D/NtpTrustedTime(  740): currentTimeMillis() cache hit
,D/NtpTrustedTime(  740): currentTimeMillis() cache hit
D/NtpTrustedTime(  740): currentTimeMillis() cache hit
,D/NtpTrustedTime(  740): currentTimeMillis() cache hit
D/NtpTrustedTime(  740): currentTimeMillis() cache hit
,D/NtpTrustedTime(  740): currentTimeMillis() cache hit
V/NetworkStats(  740): advisePersistThreshold() given 9223372036854775, clamped to 2097152
,D/Tethering(  740): Tethering got CONNECTIVITY_ACTION
,D/Tethering(  740): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker(  740): NoActiveNetworkState{ when=-1ms what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
,D/NtpTrustedTime(  740): currentTimeMillis() cache hit
D/        (  740): Setting time of day to sec=1449832370
,D/        (  740): Trying to open a file
D/        (  740): File Open Success
,D/        (  740): File Close Success
,I/        (  740): DRM_TIME_PATH CHMOD 660 for resetState done 
D/STATUSBAR-NetworkController_dual( 1064): onReceive() - CONNECTIVITY_ACTION, INET_CONDITION_ACTION
D/StatusBar.NetworkController_dual( 1064): mMobileLabelViews start
D/StatusBar.NetworkController_dual( 1064): mMobileLabelViews set mobileLabel[SIM_0] =
D/StatusBar.NetworkController_dual( 1064): mMobileLabelViews GONE
D/StatusBar.NetworkController_dual( 1064): mMobileLabelViews2 set mobileLabel[SIM_1] =
D/StatusBar.NetworkController_dual( 1064): mMobileLabelViews2 GONE
D/StatusBar.NetworkController_dual( 1064): mSingleMobileLabelViews set : simMode = 0
,D/StatusBar.NetworkController_dual( 1064): mSingleMobileLabelViews set as slot1`s
,W/        (  740): Unable to set rtc to 1449832370: Invalid argument
V/AlarmManager(  740): waitForAlarm result :65536
,D/KeyguardUpdateMonitor( 1064): received broadcast android.intent.action.TIME_SET
,D/KeyguardUpdateMonitor( 1064): handleTimeUpdate
D/StatusBar-DoNotDistrub( 1064): Received intent with android.intent.action.TIME_SET action
D/StatusBar-DoNotDistrub( 1064): Not data shared android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
,D/StatusBar-DoNotDistrub( 1064): sendBroadcast android.intent.action.DORMANT_MODE_OFF
,I/AudioService(  740): getStreamVolume 5 index 110
D/StatusBar-DoNotDistrub( 1064): The STREAM NOTIFICATION volume is 0
D/STATUSBAR-StatusBarManagerService(  740): manageDisableList what=0x0 pkg=com.android.systemui
,W/Settings(  740): Setting auto_time has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
V/AlarmManager(  740): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
V/AlarmManager(  740): waitForAlarm result :4
,W/SEC_DRM_PLUGIN_Playready(  247): PlayreadyPlugIn::onAcquireDrmInfo : case TYPE_UPDATE_SECURE_CLOCK after: 1449832368 after conversion: 1449832368
,W/SEC_DRM_PLUGIN_Playready(  247): PlayreadyPlugIn::onAcquireDrmInfo : case TYPE_UPDATE_SECURE_CLOCK before: 1449832370 after conversion: 1449832370
,I/SensorManagerA(  740): getReportingMode :: sensor.mType = 5
,D/Sensors (  740): LightSensor setDelay = 200000000
,D/Sensors (  740): LightSensor setSensorDelay = 200000000
D/Sensors (  740): Light sensor flush: not enabled 0
D/Sensors (  740): LightSensor enable = 1
,D/Sensors (  740): LightSensor enableSensor = 1
D/SensorManager(  740): registerListener :: 16, CM36686 Light Sensor, 200000, 0,  
,D/LocSvc_java(  740): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/LocSvc_java(  740): getAGpsConnectionInfo connType - 4
,D/LocSvc_java(  740): ignore wifi update if we are not in OPENING or CLOSING
D/STATUSBAR-IconMerger( 1064): checkOverflow(288), More:false, Req:false Child:2
D/STATUSBAR-NotificationService(  740): received android.intent.action.DORMANT_MODE_OFF
D/LightsService(  740): [api] [SvcLED] turnOff:: id = 4 (uid: 1000 pid: 740) 
D/LightsService(  740): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x40 -> 0x40 | SvcLED(id=4) set Off
,D/accuweather( 1441): [KK AccuPhone]>>> SWW:64 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,I/NetworkMonitor( 3749): type=WIFI subType= reason=null isConnected=true
I/PCWCLIENTTRACE_PushUtil( 4493): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 4493): sales region : global
I/PCWCLIENTTRACE_PushUtil( 4493): getPushTypeList : [SPP, GCM]
,I/PCWCLIENTTRACE_SYSTEMReceiver( 4493): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
D/accuweather( 1441): [KK AccuPhone]>>> SWW:64 [0:0] action : androidintentactionTIME_SET
,D/accuweather( 1441): [KK AccuPhone]>>> SWW:452 [0:0] doChangeDayOrNight : 1
,D/accuweather( 1441): [KK AccuPhone]>>> SWW:338 [0:0] getWeatherRenderer : 1
,I/SELinux ( 5045): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5045):  
,I/SELinux ( 5045): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5045):  
I/SELinux ( 5045):  
,I/SELinux ( 5045): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5045): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 5045): >>>>> Normal User
,E/dalvikvm( 5045): >>>>> com.sec.android.cloudagent [ userId:0 | appId:10002 ]
,E/SELinux ( 5045): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 5045): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5045): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5045): Added TimaKesytore provider
,D/ChimeraCfgMgr( 1795): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 1795): Module APK com.google.android.play.games already loaded
,I/GamesSyncServiceMain( 1795): Found unexpected GCM tag when scheduling; aborting
,W/GamesSyncServiceMain( 1795): Failed to execute periodic sync, missing client context - aborting
,I/SELinux ( 5065): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5065):  
D/Sensors (  740): LightSensor enable = 0
D/Sensors (  740): LightSensor enableSensor = 0
D/SensorManager(  740): unregisterListener ::   
D/LightsService(  740): [SvcLED]  onSensorChanged::light value = 49
D/LightsService(  740): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,W/dalvikvm( 1213): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 1213): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 1213): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,I/dalvikvm( 1213): Could not find method android.net.Network.openConnection, referenced from method com.google.android.gms.http.g.a
W/dalvikvm( 1213): VFY: unable to resolve virtual method 1007: Landroid/net/Network;.openConnection (Ljava/net/URL;)Ljava/net/URLConnection;
,D/dalvikvm( 1213): VFY: replacing opcode 0x6e at 0x00bb
,I/GoogleURLConnFactory( 1213): Using platform SSLCertificateSocketFactory
I/SELinux ( 5065): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5065):  
I/SELinux ( 5065):  
,I/SELinux ( 5065): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5065): [DEBUG] seapp_context_lookup: seinfoCategory = chrome
E/dalvikvm( 5065): >>>>> Normal User
,E/dalvikvm( 5065): >>>>> com.android.chrome [ userId:0 | appId:10081 ]
,E/SELinux ( 5065): [DEBUG] seapp_context_lookup: seinfoCategory = chrome
,D/TimaKeyStoreProvider( 5065): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5065): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5065): Added TimaKesytore provider
,I/dalvikvm( 1795): Could not find method android.os.PowerManager.isInteractive, referenced from method com.google.android.gms.common.util.y.a
,W/dalvikvm( 1795): VFY: unable to resolve virtual method 1378: Landroid/os/PowerManager;.isInteractive ()Z
,D/dalvikvm( 1795): VFY: replacing opcode 0x6e at 0x003d
,W/ActivityManager(  740): Permission Denial: getCurrentUser() from pid=5045, uid=10002 requires android.permission.INTERACT_ACROSS_USERS
,E/ActivityThread( 1795): Failed to find provider info for com.android.contacts.metadata
,I/PhenotypeConfigurator( 1213): Scheduling Phenotype every 14400 seconds, with flex of 1800 seconds
,D/SyncManager(  740): failed sync operation 
,D/SyncManager(  740): not retrying sync operation because the error is a hard error: 
,E/SMD     (  239): DCD ON
,I/HarmonyEASService(  740): Updating for all 1
,D/dalvikvm(  740): GC_EXPLICIT freed 2616K, 58% free 23496K/54724K, paused 9ms+12ms, total 165ms
,W/ActivityManager(  740): Permission Denial: getCurrentUser() from pid=5065, uid=10081 requires android.permission.INTERACT_ACROSS_USERS
,I/SELinux ( 5093): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5093):  
,I/jxcore-log( 4656): BLE advertisement not supported: Build version is 19
I/jxcore-log( 4656): 
,D/DelayedSyncController( 5065): Delaying sync.
,I/SELinux ( 5093): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5093):  
I/SELinux ( 5093):  
,I/SELinux ( 5093): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5093): [DEBUG] seapp_context_lookup: seinfoCategory = release
E/dalvikvm( 5093): >>>>> Normal User
,E/dalvikvm( 5093): >>>>> com.sec.android.fotaclient [ userId:0 | appId:10010 ]
,E/SELinux ( 5093): [DEBUG] seapp_context_lookup: seinfoCategory = release
,D/TimaKeyStoreProvider( 5093): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5093): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5093): Added TimaKesytore provider
,D/PicasaService( 3847): start picasa sync
,D/PicasaService( 3847): end picasa sync
,I/dalvikvm( 1213): Could not find method android.os.PowerManager.isInteractive, referenced from method com.google.android.gms.common.util.y.a
W/dalvikvm( 1213): VFY: unable to resolve virtual method 1378: Landroid/os/PowerManager;.isInteractive ()Z
,D/dalvikvm( 1213): VFY: replacing opcode 0x6e at 0x003d
D/AmoledAdjustTimer(  740): prevTemp = 285, currTemp = 286, prevStep = 4, currStep = 4
,W/ActivityManager(  740): Permission Denial: getCurrentUser() from pid=5093, uid=10010 requires android.permission.INTERACT_ACROSS_USERS
,D/DelayedSyncController( 5065): Delaying sync.
,I/System.out( 1213): Thread-107(HTTPLog):isShipBuild true
,I/System.out( 1213): Thread-107(HTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,I/ActivityManager(  740): Killing 3732:com.sec.spp.push:RemoteNotiProcess/u0a38 (adj 15): empty #43
,I/ActivityManager(  740): Killing 3971:com.sec.android.app.videoplayer/u0a52 (adj 15): empty #43
,I/SELinux ( 5114): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5114):  
,D/STATUSBAR-NetworkController_dual( 1064): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
D/StatusBar.NetworkController_dual( 1064): mMobileLabelViews start
D/StatusBar.NetworkController_dual( 1064): mMobileLabelViews set mobileLabel[SIM_0] =
D/StatusBar.NetworkController_dual( 1064): mMobileLabelViews GONE
D/StatusBar.NetworkController_dual( 1064): mMobileLabelViews2 set mobileLabel[SIM_1] =
D/StatusBar.NetworkController_dual( 1064): mMobileLabelViews2 GONE
,D/StatusBar.NetworkController_dual( 1064): mSingleMobileLabelViews set : simMode = 0
,D/StatusBar.NetworkController_dual( 1064): mSingleMobileLabelViews set as slot1`s
,W/WifiP2pStateTracker(  740): WifiP2pStateReceiver : android.net.wifi.LINK_CONFIGURATION_CHANGED
,D/ConnectivityService(  740): handleConnectivityChange: addresses changed linkProperty[1]: resetMask=0
D/ConnectivityService(  740):    car=removed=[] added=[fe80::3a94:96ff:feb5:6dd/64,]
,D/ConnectivityService(  740): handleConnectivityChange: setting default proxy info 
,I/SELinux ( 5114): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5114):  
I/SELinux ( 5114):  
,I/SELinux ( 5114): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5114): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 5114): >>>>> Normal User
,E/dalvikvm( 5114): >>>>> com.samsung.klmsagent [ userId:0 | appId:10018 ]
,E/SELinux ( 5114): [DEBUG] seapp_context_lookup: seinfoCategory = platform
D/ConnectivityService(  740): updateSourceRoutes : no source routing conditions
,D/TimaKeyStoreProvider( 5114): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5114): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5114): Added TimaKesytore provider
,W/ActivityManager(  740): Permission Denial: getCurrentUser() from pid=5114, uid=10018 requires android.permission.INTERACT_ACROSS_USERS
,D/KLMS-2.3.201 : ( 5114): KLMSValidator() : checkQATesting()
,D/dalvikvm( 1795): GC_CONCURRENT freed 1662K, 37% free 12097K/18944K, paused 3ms+11ms, total 45ms
,I/KLMS-2.3.201 : ( 5114): MainReciver() : EventNotificationReciver- method called: AppActivityListner onReceive for Intent Action : android.net.conn.CONNECTIVITY_CHANGE , timestamp: 1449832371210
,I/KLMS-2.3.201 : ( 5114): KLMSUtility() : isNetworkAvailable() - WIFI : true| MOBILE : false
,W/DriveInitializer( 1795): Awaiting to be initialized
,W/DriveInitializer( 1795): Background init thread started
,I/ActivityManager(  740): Killing 3985:com.sec.android.app.voicenote/1000 (adj 15): empty #43
,E/cutils  (  226): Failed to mkdirat(/storage/extSdCard/Android): Read-only file system
,W/ContextImpl( 1795): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.gms/files
W/Vold    (  226): Returning OperationFailed - no handler for errno 30
,I/SELinux ( 5128): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5128):  
,I/LocationTagReadyService( 2357): onStartCommand : Action = com.samsung.android.app.galaxyfinder.tag.start_location_convert
D/GalaxyFinderApplication( 2357): [Slink platform] The state of Slink geocode service is true
,D/GalaxyFinderApplication( 2357): [Slink platform] The state of Slink geocode service is true
,D/GalaxyFinderApplication( 2357): [Slink platform] The state of Slink geocode service is true
,I/GallerySearchProvider( 3847): query content://com.sec.android.gallery3d.provider.GallerySearchProvider/search_suggest_tag_query
,I/SELinux ( 5134): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5134):  
,I/SELinux ( 5128): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5128):  
I/SELinux ( 5128):  
,I/SELinux ( 5128): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5128): [DEBUG] seapp_context_lookup: seinfoCategory = release
E/dalvikvm( 5128): >>>>> Normal User
,E/dalvikvm( 5128): >>>>> com.sec.android.soagent [ userId:0 | appId:10037 ]
,E/SELinux ( 5128): [DEBUG] seapp_context_lookup: seinfoCategory = release
,I/SELinux ( 5134): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5134):  
I/SELinux ( 5134):  
,I/SELinux ( 5134): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 5134): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 5134): >>>>> Normal User
E/dalvikvm( 5134): >>>>> com.sec.android.app.videoplayer [ userId:0 | appId:10052 ]
,I/SELinux ( 5151): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5151):  
,E/SELinux ( 5134): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 5128): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5128): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5128): Added TimaKesytore provider
,D/TimaKeyStoreProvider( 5134): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5134): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5134): Added TimaKesytore provider
,W/DriveInitializer( 1795): Background init thread ended
,I/SELinux ( 5151): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5151):  
I/SELinux ( 5151):  
,I/SELinux ( 5151): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5151): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 5151): >>>>> Normal User
,E/dalvikvm( 5151): >>>>> com.sec.android.app.voicenote [ userId:0 | appId:1000 ]
,E/SELinux ( 5151): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 5151): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5151): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5151): Added TimaKesytore provider
,W/ActivityManager(  740): Permission Denial: getCurrentUser() from pid=5128, uid=10037 requires android.permission.INTERACT_ACROSS_USERS
,D/SO_AGENT( 5128): [AccRegisterReceiver.java(Line:56/Method:onReceive)] Receive broadcast meassage:android.net.conn.CONNECTIVITY_CHANGE
,I/SO_AGENT( 5128): [AccRegisterReceiver.java(Line:87/Method:onReceive)] Need to accessory setup...
,V/KVNProvider( 5151): query uri : content://com.sec.android.app.voicenote.common.util.VNProvider/search_suggest_tag_query
,V/KVNProvider( 5151): getFindoCursor query string : 
,V/KVNProvider( 5151): getTagSearchCursor() tagSearchCursor count : 0
,D/dalvikvm( 1199): GC_EXPLICIT freed 443K, 47% free 10047K/18944K, paused 7ms+8ms, total 58ms
,I/ActivityManager(  740): Killing 3947:com.sec.phone/1001 (adj 15): empty #43
,I/SA      ( 4672): [OR] onReceive log=[SA = 2.0.0117 V = 19 HWD = 1280X720 2.0 dpi = 320  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = kmini3g P = kmini3gxx I = KOT49H M = SM-G800H OKLEFT false DIS KOT49H.G800HXXU1ANK2 PSS = 4.497045606779314  ]
I/ActivityManager(  740): Killing 3891:com.sec.android.app.music:service/u0a150 (adj 15): empty #43
,I/SA      ( 4672): [BDLM] already registered in spp
I/SA      ( 4672): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. ]
,I/SA      ( 4672): [OR] == ACTION_CONNECTIVITY_CHANGE ==
,I/SA      ( 4672): [SLFUCHKMGR] constructor called
,I/SA      ( 4672): [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
,I/SA      ( 4672): [OR] == isSIMCardReady false ==
,I/SA      ( 4672): [SCU] == networkStateCheck == true
I/SA      ( 4672): [DM] getCountryCodeFromCSC : PL
I/SA      ( 4672): isChinaCountryCode : false
,I/SA      ( 4672): [OR] == networkStateCheck true ==
,I/SA      ( 4672): [OR] GetMyCountryZoneTask
,I/SA      ( 4672): [OR] onReceive END
I/dalvikvm( 4621): Total arena pages for JIT: 11
,I/dalvikvm( 4621): Total arena pages for JIT: 12
I/dalvikvm( 4621): Total arena pages for JIT: 13
,I/dalvikvm( 4621): Total arena pages for JIT: 14
,I/ActivityManager(  740): Killing 3964:com.android.calendar/u0a142 (adj 15): empty #43
I/SA      ( 4672): [SRS] prepareGetMyCountryZone
,I/SA      ( 4672): [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
,I/SA      ( 4672): [SSP] query invoked
,D/PhoneNumberLocatorBootCompletedReceiver( 1234): onReceive
,D/PhoneNumberLocatorBootCompletedReceiver( 1234): Phone number locator feature is dsiabled
,I/SELinux ( 5187): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5187):  
,I/SA      ( 4672): [TPMU] GetMccFromDB : null
I/SA      ( 4672): [SCU] getMccFromPreferece mcc = 260
,I/SA      ( 4672): [TPM] isNoProxy(default) : true
,I/SA      ( 4672): [RC New] Execute method=[GET] start
,I/SELinux ( 5187): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5187):  
I/SELinux ( 5187):  
,I/SELinux ( 5187): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5187): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 5187): >>>>> Normal User
,E/dalvikvm( 5187): >>>>> com.samsung.android.scloud.backup [ userId:0 | appId:10060 ]
,E/SELinux ( 5187): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 5187): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5187): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5187): Added TimaKesytore provider
,I/sCloudBackupApp( 5187): sCloudBackupApp Version Info : 3.7.3.KK_APP
,I/SCloudBackupReceiver( 5187): Other Intent
,I/System.out( 4672): Thread-449(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
,D/com.samsung.app( 1441): [KK_EASY_Accu]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/com.samsung.app( 1441): [KK_EASY_Accu]>>> WC:37 [0:0] oR : create UI manager : start
,I/ActivityManager(  740): Killing 4016:com.android.providers.calendar/u0a44 (adj 15): empty #43
D/com.samsung.app( 1441): [KK_EASY_Accu]>>> UIMEM:89 [0:0] getInstance
D/com.samsung.app( 1441): [KK_EASY_Accu]>>> UIMEM:77 [0:0] UIManager : create ui manager
I/System.out( 4672): Thread-449(ApacheHTTPLog):isShipBuild true
I/System.out( 4672): Thread-449(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
D/accuweather( 1441): [KK AccuPhone]>>> RM:73 [0:0] RefreshManager : create
D/accuweather( 1441): [KK AccuPhone]>>> RM:136 [0:0]  V init 
D/daemonapp( 1458): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/accuweather( 1441): [KK AccuPhone]>>> RM:128 [0:0] updateCityList
,D/daemonapp( 1458): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,D/accuweather( 1441): [KK AccuPhone]>>> DBH:3047 [0:0] gADWI : count = 0
,D/daemonapp( 1458): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/com.samsung.app( 1441): [KK_EASY_Accu]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
,D/com.samsung.app( 1441): [KK_EASY_Accu]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
,D/dalvikvm( 1213): GC_CONCURRENT freed 1639K, 38% free 11791K/18944K, paused 3ms+4ms, total 46ms
,D/dalvikvm( 1213): WAIT_FOR_CONCURRENT_GC blocked 12ms
,I/SELinux ( 5202): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5202):  
,I/SELinux ( 5202): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5202):  
I/SELinux ( 5202):  
,I/SELinux ( 5202): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5202): [DEBUG] seapp_context_lookup: seinfoCategory = release
E/dalvikvm( 5202): >>>>> Normal User
,E/dalvikvm( 5202): >>>>> com.samsung.android.internal.headlines [ userId:0 | appId:10106 ]
,E/SELinux ( 5202): [DEBUG] seapp_context_lookup: seinfoCategory = release
,D/TimaKeyStoreProvider( 5202): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5202): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5202): Added TimaKesytore provider
,D/HeadlinesChannelApplication( 5202): [onCreate]
,D/Headlines( 5202): HeadlinesSystemBroadcastReceiver onReceive android.net.conn.CONNECTIVITY_CHANGE
W/ActivityManager(  740): Permission Denial: getCurrentUser() from pid=5202, uid=10106 requires android.permission.INTERACT_ACROSS_USERS
,D/HeadlinesChannelUtil( 5202): getCountryCode(): countryCode = PL
,W/PhenotypeConfigurator( 1213): Server returned 404
,D/Headlines( 5202): Breath.onCreate
D/HeadlinesCardManager( 5202): HeadlinesCardManager : constructor
,E/HeadlinesCardManager( 5202): HeadlinesCardManager : ctor = image_cache size is 42MB
,D/SA Version( 5202): CardProvider Library : 13
,I/SELinux ( 5214): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5214):  
,D/MagazineService::CardProviderContentProvider( 4763): insertProvider: provider already exists.: com.samsung.android.app.headlines
,D/MagazineService::CardProviderContentProvider( 4763): insertProvider: provider is updated.: com.samsung.android.app.headlines
,D/com.samsung.android.magazine.cardprovider.ConfigurationManager( 5202): registerCardProvider: provider already exists.
I/Headlines( 5202): HeadlinesDataCenter ctor
I/Headlines( 5202): HeadlinesDataCenter. mLocale = en_US
,D/HeadlinesChannelUtil( 5202): getCountryCode(): countryCode = PL
,D/HeadlinesCardManager( 5202): HeadlinesCardManager : constructor welcome :YES
,D/dalvikvm( 1313): GC_EXPLICIT freed 733K, 44% free 10774K/18944K, paused 3ms+6ms, total 37ms
,I/SELinux ( 5214): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5214):  
I/SELinux ( 5214):  
,I/SELinux ( 5214): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5214): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 5214): >>>>> Normal User
,E/dalvikvm( 5214): >>>>> com.google.android.apps.magazines [ userId:0 | appId:10112 ]
,E/SELinux ( 5214): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
,D/Headlines( 5202): Breath timer started. interval : 30000
,D/Headlines( 5202): Breath.onStartCommand : com.samsung.android.internal.headlines.UPDATE_WELCOME_CARD flag : 0
D/HeadlinesCardManager( 5202): updateCategory : HeadlinesCardManager:updateCategory() category size == 0
D/HeadlinesCardManager( 5202): updateCategory : HeadlinesCardManager:updateCategory() try to query category list
,D/Headlines( 5202): queryCategory.  mRequest is not initialized.
D/HeadlinesCardManager( 5202): updateCategory : HeadlinesCardManager:updateCategory() reponse : false
D/HeadlinesCardManager( 5202): requestUpdateNewsWelcomeCard : request update welcome card to content card.
,D/HeadlinesDataCenter( 5202): requestUpdateNewsWelcomeCard !!! no welcome card
,D/TimaKeyStoreProvider( 5214): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5214): Cannot add TimaSignature Service, License check Failed
V/AlarmManager(  740): waitForAlarm result :8
,D/ActivityThread( 5214): Added TimaKesytore provider
V/AlarmManager(  740): waitForAlarm result :8
,D/btif_config_util( 3163): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,E/cutils  (  226): Failed to mkdirat(/storage/extSdCard/Android): Read-only file system
,W/ContextImpl( 5214): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
W/Vold    (  226): Returning OperationFailed - no handler for errno 30
,E/cutils  (  226): Failed to mkdirat(/storage/extSdCard/Android): Read-only file system
,W/ContextImpl( 5214): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
W/Vold    (  226): Returning OperationFailed - no handler for errno 30
,W/GAV2    ( 5214): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,E/cutils  (  226): Failed to mkdirat(/storage/extSdCard/Android): Read-only file system
,W/ContextImpl( 5214): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,E/cutils  (  226): Failed to mkdirat(/storage/extSdCard/Android): Read-only file system
,W/ContextImpl( 5214): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
W/Vold    (  226): Returning OperationFailed - no handler for errno 30
W/Vold    (  226): Returning OperationFailed - no handler for errno 30
,D/SSRMv2:SIOP(  740): SIOP:: AP = 320, Delta = 10
,V/WebViewChromium( 5214): Binding Chromium to the main looper Looper (main, tid 1) {422b0050}
,I/chromium( 5214): [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserProcessMain( 5214): Initializing chromium process, renderers=0
,W/chromium( 5214): [WARNING:proxy_service.cc(888)] PAC support disabled because there is no system implementation
,I/Adreno-EGL( 5214): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 5214): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 5214): Build Date: 03/21/14 Fri
I/Adreno-EGL( 5214): Local Branch: AU200+patches_03212014
I/Adreno-EGL( 5214): Remote Branch: 
I/Adreno-EGL( 5214): Local Patches: 
I/Adreno-EGL( 5214): Reconstruct Branch: 
,I/NSApplication( 5214): Starting up...
,W/ActivityManager(  740): Permission Denial: getCurrentUser() from pid=5214, uid=10112 requires android.permission.INTERACT_ACROSS_USERS
,D/QuickConnect[1.1][2] ( 3137): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
I/QuickConnect[1.1][2] ( 3137): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
,V/QuickConnect[1.1][2] ( 3137): SconnectManager.getInstance - () return existing instance com.samsung.android.sconnect.SconnectManager@425e4c98
I/ActivityManager(  740): Killing 4020:com.sec.android.widgetapp.SPlannerAppWidget/u0a143 (adj 15): empty #43
,I/SELinux ( 5252): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5252):  
,I/SA      ( 4672): [RC New] [v2liruge] api execute + 842
,I/SA      ( 4672): [RC New] executeRequest [v2liruge] httpResponse : HTTP/1.1 200 OK
,I/System.out( 4672): AsyncTask #1 calls detatch()
,I/SA      ( 4672): [TPMU] getNetworkMcc : 
,I/SA      ( 4672): [SCU] saveMccToPreferece Start
,I/SA      ( 4672): [SCU] RegionMCC : 260
,I/SA      ( 4672): [SSP] query invoked
I/SA      ( 4672): [TPMU] GetMccFromDB : null
,I/SA      ( 4672): [SCU] getMccFromPreferece mcc = 260
,I/SA      ( 4672): [SCU] saveMccToPreferece End
I/SA      ( 4672): [RC New] executeRequest [v2liruge] end. 859
,I/SA      ( 4672): [RC New] Execute end
,I/SA      ( 4672): [OR] GetMyCountryZoneTask mcc = 260
,I/SA      ( 4672): [OR] GetMyCountryZoneTask Success
,D/dalvikvm(  246): GC_EXPLICIT freed 43K, 50% free 9512K/18944K, paused 2ms+2ms, total 28ms
,D/dalvikvm(  246): GC_EXPLICIT freed <1K, 50% free 9512K/18944K, paused 2ms+2ms, total 18ms
I/SELinux ( 5252): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5252):  
I/SELinux ( 5252):  
,I/SELinux ( 5252): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5252): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 5252): >>>>> Normal User
,E/dalvikvm( 5252): >>>>> com.android.email [ userId:0 | appId:10155 ]
,E/SELinux ( 5252): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/dalvikvm(  246): GC_EXPLICIT freed <1K, 50% free 9512K/18944K, paused 2ms+3ms, total 18ms
,D/TimaKeyStoreProvider( 5252): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5252): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5252): Added TimaKesytore provider
,D/RCPManagerService(  740): exchangeData() failure , invalid userId
,D/RCPManagerService(  740): exchangeData() failure , invalid userId
,D/RCPManagerService(  740): exchangeData() failure , invalid userId
,D/RCPManagerService(  740): exchangeData() failure , invalid userId
,D/RCPManagerService(  740): exchangeData() failure , invalid userId
,D/RCPManagerService(  740): exchangeData() failure , invalid userId
,I/SELinux ( 5271): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5271):  
,E/WifiStateMachine(  740): CAPTIVE_PORTAL_EVENT_AUTHENTICATED
,I/SELinux ( 5278): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5278):  
I/ActivityManager(  740): Killing 3033:com.google.android.talk/u0a105 (adj 15): empty #43
W/ActivityManager(  740): Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
,I/SELinux ( 5271): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5271):  
I/SELinux ( 5271):  
,I/SELinux ( 5271): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5271): [DEBUG] seapp_context_lookup: seinfoCategory = release
E/dalvikvm( 5271): >>>>> Normal User
,E/dalvikvm( 5271): >>>>> com.sec.android.provider.badge [ userId:0 | appId:10072 ]
,E/SELinux ( 5271): [DEBUG] seapp_context_lookup: seinfoCategory = release
,D/TimaKeyStoreProvider( 5271): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5271): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5271): Added TimaKesytore provider
,I/SELinux ( 5278): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5278):  
I/SELinux ( 5278):  
,I/SELinux ( 5278): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 5278): [DEBUG] seapp_context_lookup: seinfoCategory = shared
,E/dalvikvm( 5278): >>>>> Normal User
,E/dalvikvm( 5278): >>>>> com.samsung.android.service.travel [ userId:0 | appId:10169 ]
,E/SELinux ( 5278): [DEBUG] seapp_context_lookup: seinfoCategory = shared
,D/TimaKeyStoreProvider( 5278): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5278): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5278): Added TimaKesytore provider
,D/dalvikvm(  740): GC_EXPLICIT freed 1619K, 58% free 23445K/54724K, paused 7ms+14ms, total 149ms
I/ActivityManager(  740): Killing 4043:com.sec.providers.settingsearch/u0a160 (adj 15): empty #43
,W/ActivityManager(  740): Permission Denial: getCurrentUser() from pid=5278, uid=10169 requires android.permission.INTERACT_ACROSS_USERS
,D/BadgeProvider( 5271): onCreate
,D/BadgeProvider( 5271): DatabaseHelper
,I/SurfaceFlinger(  245): id=18 Removed Uoast (11/12)
,I/SurfaceFlinger(  245): id=18 Removed Uoast (-2/12)
,D/KeyguardUpdateMonitor( 1064): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1064): handleKeyguardVisibilityChanged(1)
I/ActivityManager(  740): Killing 4238:com.wssyncmldm/1000 (adj 15): empty #43
W/ActivityManager(  740): Permission Denial: getCurrentUser() from pid=5271, uid=10072 requires android.permission.INTERACT_ACROSS_USERS
D/PowerManagerService(  740): [api] release WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=740 (0x0)
D/PowerManagerService(  740): [api] applyWakeLockFlagsOnReleaseLocked : userActivityNoUpdateLocked is called : SCREEN_BRIGHT_WAKE_LOCK        'WindowManager' ON_AFTER_RELEASE (uid=1000, pid=740, ws=WorkSource{1000}) (elapsedTime=3465)
,D/BadgeProvider( 5271): query, [selection] : package='com.android.email' AND class='com.android.email.activity.Welcome' AND extraData='base_extra_badge'
,D/WaitQueueForNetworkActivate( 4814): notifyNetworkActivated
,D/BadgeProvider( 5271): sendNotify entered. [uri] : content://com.sec.badge/apps/1
,D/BadgeProvider( 5271): sendNotify, [notify] : null
D/BadgeProvider( 5271): update, [uri] : content://com.sec.badge/apps/1
D/Launcher.Model( 1256): reloadBadges entered.
D/BadgeProvider( 5271): update, [BadgeCount] : badgecount=0
,D/BadgeProvider( 5271): update, [UpdateCount] : 1
,W/ContextImpl( 4814): Implicit intents with startService are not safe: Intent { act=com.sec.knox.containeragent.service.containermanager.ContainerManagerService } android.content.ContextWrapper.bindService:529 com.sec.knox.containeragent.ContainerManager.<init>:49 com.sec.android.app.samsungapps.vlibrary2.knoxmode.KNOXAPI.<init>:20 
W/ActivityManager(  740): Unable to start service Intent { act=com.sec.knox.containeragent.service.containermanager.ContainerManagerService } U=0: not found
,D/hcjo    ( 4814): AutoUpdateManager:IDLE:execute
,I/dalvikvm( 4814): Could not find method android.view.Window.setStatusBarColor, referenced from method com.sec.android.app.samsungapps.CommonActivity.onCreate
W/dalvikvm( 4814): VFY: unable to resolve virtual method 14867: Landroid/view/Window;.setStatusBarColor (I)V
,D/dalvikvm( 4814): VFY: replacing opcode 0x6e at 0x0024
,D/InitializeManagerStateMachine( 4814): execute::IDLE:EXECUTE
D/InitializeManagerStateMachine( 4814): exit::IDLE
,D/InitializeManagerStateMachine( 4814): entry::NETWORK_CHECK
D/InitializeManagerStateMachine( 4814): execute::NETWORK_CHECK:NETWORK_STATE_OK
D/InitializeManagerStateMachine( 4814): exit::NETWORK_CHECK
D/InitializeManagerStateMachine( 4814): entry::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 4814): execute::CHECK_COUNTRY_INFO:COUNTRY_INFO_OK
D/InitializeManagerStateMachine( 4814): exit::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 4814): entry::SUCCESS
,D/hcjo    ( 4814): AutoUpdateManager:INITCHECK:onInitializeSuccess
,D/hcjo    ( 4814): AutoUpdateTriggerManager:REQUEST2:requestInterval
,I/Volley  ( 4814): RestApi Request Add : 2307
,E/File    ( 4814): fail readDirectory() errno=2
,D/dalvikvm( 1313): null clazz in OP_INSTANCE_OF, single-stepping
,I/iu.SyncManager( 1795): SYNC; picasa accounts
,D/NetworkLogImpl( 1795): Loaded NetworkSpeedPredictor
,I/iu.Environment( 1795): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,I/iu.UploadsManager( 1795): num queued entries: 0
,I/iu.UploadsManager( 1795): num updated entries: 0
,I/iu.SyncManager( 1795): NEXT; no task
,I/SELinux ( 5306): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5306):  
,I/SELinux ( 5306): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5306):  
I/SELinux ( 5306):  
,I/SELinux ( 5306): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5306): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 5306): >>>>> Normal User
,E/dalvikvm( 5306): >>>>> com.android.calendar [ userId:0 | appId:10142 ]
,E/SELinux ( 5306): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 5306): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5306): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5306): Added TimaKesytore provider
,D/BootCompletedReceiver(  740): onReceive
I/ActivityManager(  740): Killing 2896:com.sec.knox.bridge/1000 (adj 15): empty #43
,I/KLMS-2.3.201 : ( 5114): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,I/KLMS-2.3.201 : ( 5114): MainReciver() : EventNotificationReciver- method called: AppActivityListner onReceive for Intent Action : android.intent.action.TIME_SET , timestamp: 1449832373594
,I/KLMS-2.3.201 : ( 5114): StateImplV2() : dateTimeChanged() : Fri Dec 11 12:12:53 CET 2015
,I/GCM     ( 1313): GCM config loaded
,D/SO_AGENT( 5128): [ServerTimeReceiver.java(Line:44/Method:onReceive)] Receive broadcast meassage:android.intent.action.TIME_SET
,I/SO_AGENT( 5128): [ServerTimeReceiver.java(Line:47/Method:onReceive)] No action is available before server time settings
,I/SA      ( 4672): [SBR] StdBroadcastReceiver received Intent of  action.TIME_SET.
,V/AlarmManager(  740): waitForAlarm result :8
,D/Mms/MessagingNotification( 3779): [start]    nonBlockingUpdateMessageIndicator()
,D/Mms/MessagingNotification( 3779): sDisableVibrateForCamera = false
D/Mms/MessagingNotification( 3779): isBlockingModeEnable() = false
,D/Mms/TelephonyPermission( 3779): isDefault true
,D/TP/MmsSmsProvider( 1234): match 8:Elapsed time : 3.437 ms
,E/SMD     (  239): DCD ON
,I/SELinux ( 5330): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5330):  
,I/VacuumService( 1213): Vacuum at: now=1449832373742 tag=VacuumService
,D/TP/MmsSmsProvider( 1234): match 200:Elapsed time : 1.236 ms
I/SELinux ( 5330): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5330):  
I/SELinux ( 5330):  
,I/SELinux ( 5330): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 5330): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 5330): >>>>> Normal User
,E/dalvikvm( 5330): >>>>> com.samsung.android.scloud.sync [ userId:0 | appId:10062 ]
,E/SELinux ( 5330): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 5330): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5330): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5330): Added TimaKesytore provider
,D/BadgeProvider( 5271): query, [selection] : package='com.android.mms' AND class='com.android.mms.ui.ConversationComposer' AND extraData='base_extra_badge'
,D/Launcher.Model( 1256): reloadBadges entered.
D/BadgeProvider( 5271): sendNotify entered. [uri] : content://com.sec.badge/apps/2
D/BadgeProvider( 5271): sendNotify, [notify] : null
D/BadgeProvider( 5271): update, [uri] : content://com.sec.badge/apps/2
D/BadgeProvider( 5271): update, [BadgeCount] : badgecount=0
,D/BadgeProvider( 5271): update, [UpdateCount] : 1
,D/Mms/MessagingNotification( 3779): setBadgeCount(), count=0
,D/MessagingNotification( 3779): remove alarm
,D/Mms/MessagingNotification( 3779): [end]    nonBlockingUpdateMessageIndicator()
,D/Mms/MessagingNotification( 3779): updateAllHistoryAsRead()
,W/ActivityManager(  740): Permission Denial: getCurrentUser() from pid=5330, uid=10062 requires android.permission.INTERACT_ACROSS_USERS
,I/ActivityManager(  740): Killing 4413:com.android.defcontainer/u0a6 (adj 15): empty #43
D/com.samsung.app( 1441): [KK_EASY_Accu]>>> WC:30 [0:0] action : androidintentactionTIME_SET
D/com.samsung.app( 1441): [KK_EASY_Accu]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
I/ Time Manager ( 5330): Time Difference not stored. TIME_DIFFERENCE
,I/SELinux ( 5352): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5352):  
,I/SELinux ( 5352): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5352):  
I/SELinux ( 5352):  
,I/SELinux ( 5352): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5352): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 5352): >>>>> Normal User
,E/dalvikvm( 5352): >>>>> com.sec.android.app.clockpackage [ userId:0 | appId:10084 ]
,E/SELinux ( 5352): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 5352): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5352): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5352): Added TimaKesytore provider
,W/ContextImpl(  740): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/STATUSBAR-NetworkController_dual( 1064): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
,D/StatusBar.NetworkController_dual( 1064): mMobileLabelViews start
D/StatusBar.NetworkController_dual( 1064): mMobileLabelViews set mobileLabel[SIM_0] =
D/StatusBar.NetworkController_dual( 1064): mMobileLabelViews GONE
D/StatusBar.NetworkController_dual( 1064): mMobileLabelViews2 set mobileLabel[SIM_1] =
D/StatusBar.NetworkController_dual( 1064): mMobileLabelViews2 GONE
,D/StatusBar.NetworkController_dual( 1064): mSingleMobileLabelViews set : simMode = 0
,D/StatusBar.NetworkController_dual( 1064): mSingleMobileLabelViews set as slot1`s
,D/dalvikvm( 4814): GC_CONCURRENT freed 7609K, 47% free 10082K/18944K, paused 2ms+5ms, total 43ms
,D/ConnectivityService(  740): handleInetConditionHoldEnd: net=1, condition=100, published condition=0
,D/STATUSBAR-NetworkController_dual( 1064): onReceive() - CONNECTIVITY_ACTION, INET_CONDITION_ACTION
D/StatusBar.NetworkController_dual( 1064): mMobileLabelViews start
D/StatusBar.NetworkController_dual( 1064): mMobileLabelViews set mobileLabel[SIM_0] =
,D/StatusBar.NetworkController_dual( 1064): mMobileLabelViews GONE
D/StatusBar.NetworkController_dual( 1064): mMobileLabelViews2 set mobileLabel[SIM_1] =
D/StatusBar.NetworkController_dual( 1064): mMobileLabelViews2 GONE
,D/StatusBar.NetworkController_dual( 1064): mSingleMobileLabelViews set : simMode = 0
,D/StatusBar.NetworkController_dual( 1064): mSingleMobileLabelViews set as slot1`s
,I/SELinux ( 5372): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5372):  
I/ActivityManager(  740): Killing 3193:com.sec.android.inputmethod/1000 (adj 15): empty #43
,I/SELinux ( 5372): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5372):  
I/SELinux ( 5372):  
,I/SELinux ( 5372): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5372): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 5372): >>>>> Normal User
,E/dalvikvm( 5372): >>>>> com.sec.esdk.elm [ userId:0 | appId:10094 ]
,E/SELinux ( 5372): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 5372): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5372): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5372): Added TimaKesytore provider
,W/ActivityManager(  740): Permission Denial: getCurrentUser() from pid=5372, uid=10094 requires android.permission.INTERACT_ACROSS_USERS
,D/elm:14132( 5372): ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver }
,D/elm:14132( 5372): ELMEngine.ELMEngine( context ).
,D/elm:14132( 5372): MDMBridge.setEnterpriseBridge()
,D/elm:14132( 5372): ELMAbstractReceiver : Receive Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.sec.esdk.elm/.service.ElmAgentService } END.
,D/elm:14132( 5372): ElmAgentService : onCreate()
,D/elm:14132( 5372): ElmAgentService : onHandleIntent() Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.sec.esdk.elm/.service.ElmAgentService }
,I/knox    ( 3076): MainReceiver.onReceive() : Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.sec.knox.seandroid/.receiver.MainReceiver }
,D/elm:14132( 5372): ELMAgentService.listeningToTimeDateChanges( context, intent ).
D/elm:14132( 5372): ELMEngine.ServiceHandler.handleMessage( ALARM_MODIFY ). 
,D/elm:14132( 5372): ModuleBase.resetCalllogAPIAlarm()
,D/knox    ( 3076): MainReceiver.listeningToTimeDateChanges( context, intent ).
,I/knox    ( 3076): MainReceiver.onReceive() END - - - - - : Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.sec.knox.seandroid/.receiver.MainReceiver }
W/ContextImpl( 3076): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1857 android.content.ContextWrapper.startService:506 android.content.ContextWrapper.startService:506 com.sec.knox.seandroid.receiver.MainReceiver.onReceive:142 android.app.ActivityThread.handleReceiver:2698 
,D/knox    ( 3076): KNOXAgentService : onCreate()
D/knox    ( 3076): KNOXAgentService : set alarms for deniallog and usage data upload
D/elm:14132( 5372): ModuleBase.ModifySetAlarm()
D/elm:14132( 5372): MDMBridge.getInstance()
,D/elm:14132( 5372): MDMBridge.getAllLicenseInfoFromSDK()
D/knox    ( 3076): KNOXAgentService. startJobThread() start
,D/knox    ( 3076): KNOXAgentService. JobThread()
D/knox    ( 3076): KNOXAgentService. JobThread. notifyAll().
,D/knox    ( 3076): KNOXAgentService. startJobThread() wait
,D/elm:14132( 5372): ElmAgentService : onDestroy().
,I/SELinux ( 5388): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5388):  
,D/knox    ( 3076): KNOXAgentService : onDestroy().
,D/knox    ( 3076): ModuleBase.cancelAllAlarmManageModule()
I/ActivityManager(  740): Killing 4450:com.google.android.partnersetup/u0a14 (adj 15): empty #43
,I/SELinux ( 5388): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5388):  
I/SELinux ( 5388):  
,I/SELinux ( 5388): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5388): [DEBUG] seapp_context_lookup: seinfoCategory = shared
E/dalvikvm( 5388): >>>>> Normal User
,E/dalvikvm( 5388): >>>>> com.sec.android.widgetapp.SPlannerAppWidget [ userId:0 | appId:10143 ]
,E/SELinux ( 5388): [DEBUG] seapp_context_lookup: seinfoCategory = shared
,D/TimaKeyStoreProvider( 5388): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5388): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5388): Added TimaKesytore provider
,D/dalvikvm( 4814): GC_CONCURRENT freed 1969K, 47% free 10160K/18944K, paused 1ms+3ms, total 25ms
W/ActivityManager(  740): Permission Denial: getCurrentUser() from pid=5388, uid=10143 requires android.permission.INTERACT_ACROSS_USERS
,I/SELinux ( 5400): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5400):  
I/ActivityManager(  740): Killing 4467:com.samsung.groupcast/u0a15 (adj 15): empty #43
,I/SELinux ( 5400): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5400):  
I/SELinux ( 5400):  
,I/SELinux ( 5400): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5400): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 5400): >>>>> Normal User
,E/dalvikvm( 5400): >>>>> com.sec.android.app.taskmanager [ userId:0 | appId:10166 ]
,E/SELinux ( 5400): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 5400): in addTimaSignatureService
D/InitializeManagerStateMachine( 4814): exit::SUCCESS
D/InitializeManagerStateMachine( 4814): entry::IDLE
,D/TimaKeyStoreProvider( 5400): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5400): Added TimaKesytore provider
,I/System.out( 4814): Thread-475(HTTPLog):isShipBuild true
,I/System.out( 4814): Thread-475(HTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,W/ActivityManager(  740): Permission Denial: getCurrentUser() from pid=5400, uid=10166 requires android.permission.INTERACT_ACROSS_USERS
,I/SELinux ( 5419): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5419):  
I/ActivityManager(  740): Killing 4479:com.android.musicfx/u0a24 (adj 15): empty #43
,I/SELinux ( 5419): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5419):  
I/SELinux ( 5419):  
,I/SELinux ( 5419): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5419): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 5419): >>>>> Normal User
,E/dalvikvm( 5419): >>>>> com.qualcomm.timeservice [ userId:0 | appId:10168 ]
,E/SELinux ( 5419): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 5419): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5419): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5419): Added TimaKesytore provider
,W/ActivityManager(  740): Permission Denial: getCurrentUser() from pid=5419, uid=10168 requires android.permission.INTERACT_ACROSS_USERS
D/dalvikvm( 5419): No JNI_OnLoad found in /vendor/lib/libTimeService.so 0x425d58e0, skipping init
D/TimeService( 5419): Receivedandroid.intent.action.TIME_SET intent. Current Time is 1449832374758
D/        ( 5419): TimeServiceNative: User Time to be set is 1449832374759
D/QC-time-services( 5419): Lib:time_genoff_operation: pargs->base = 2
D/QC-time-services( 5419): Lib:time_genoff_operation: pargs->operation = 0
D/QC-time-services( 5419): Lib:time_genoff_operation: pargs->ts_val = 1449832374759
D/QC-time-services( 5419): Lib:time_genoff_operation: Send to server  passed!!
D/QC-time-services(  289): Daemon: Connection accepted:time_genoff
D/QC-time-services(  289): Daemon: genoff_handler: Process name is omm.timeservice
D/QC-time-services(  289): Daemon:Received base = 2, unit = 1, operation = 0,value = 1449832374759
D/QC-time-services(  289): Daemon:genoff_opr: Base = 2, val = 1449832374759, operation = 0
D/QC-time-services(  289): Daemon:rtc_get: Time read from RTC -- MM/DD/YY HH:MM:SS0/15/70 3:10:1
D/QC-time-services(  289): Daemon:Value read from RTC seconds = 1221001000
D/QC-time-services(  289): Daemon:new time 1449832374759 
D/QC-time-services(  289): Daemon: delta 1448611373759 genoff 1448611373759 
D/QC-time-services(  289): Daemon:genoff_persistent_update: Writing genoff = 1448611373759 to memory
D/QC-time-services(  289): Daemon:Opening File: /data/time/ats_2
D/QC-time-services(  289): Daemon:time_persistent_memory_opr:Genoff write operation 
D/QC-time-services(  289): Updating the TOD offset
D/QC-time-services(  289): Daemon:genoff_persistent_update: Writing genoff = 1448611373759 to memory
D/QC-time-services(  289): Daemon:Opening File: /data/time/ats_1
D/QC-time-services(  289): Daemon:time_persistent_memory_opr:Genoff write operation 
E/QC-time-services(  289): Daemon:Update to modem bit set
D/QC-time-services(  289): Daemon:genoff_send_modem: Sending data to MODEM !
D/QC-time-services(  289): Daemon: Base = 2, Value being sent to MODEM = 1133867574759
E/QC-time-services( 5419): Receive Passed == base = 2, unit = 1, operation = 0, result = 0
,E/QC-time-services(  289): Daemon: Time-services: Waiting to acceptconnection
,E/QC-time-services(  289): Daemon:tod_update_ind_cb: Got Update from modem msg_id 40
I/ActivityManager(  740): Killing 4508:com.samsung.android.app.galaxyfinder/u0a34 (adj 15): empty #43
,D/daemonapp( 1458): [MSC_Daemon]>>> WU:236 [0:0] regintype : EUR
,D/daemonapp( 1458): [MSC_Daemon]>>> WU:292 [0:0] cp type is : cp_eng
,D/daemonapp( 1458): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/daemonapp( 1458): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,D/daemonapp( 1458): [MSC_Daemon]>>> WDSM:44 [0:0] Act : androidintentactionTIME_SET, run:true
D/comsamsunglog( 1458): [MSC_Daemon]>>> ====================================================================================================================
,D/comsamsunglog( 1458): [MSC_Daemon]>>> daemonapp [Version : 14052601 ] [ 1 ] 
D/comsamsunglog( 1458): [MSC_Daemon]>>> Header set to : ===> "daemonapp" <===
D/comsamsunglog( 1458): [MSC_Daemon]>>> ====================================================================================================================
,D/daemonapp( 1458): [MSC_Daemon]>>> WDSM:85 [0:0] c:null, r:3
,D/daemonapp( 1458): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/packagename
,D/daemonapp( 1458): [MSC_Daemon]>>> WU:1485 [0:0] PakNme size = 2
,D/daemonapp( 1458): [MSC_Daemon]>>> WU:236 [0:0] regintype : EUR
,D/daemonapp( 1458): [MSC_Daemon]>>> WU:292 [0:0] cp type is : cp_eng
,D/daemonapp( 1458): [MSC_Daemon]>>> WU:1488 [0:0] CP Name cp_eng
,D/daemonapp( 1458): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/packagename
,D/comdaemonstockapp( 1458): [Daemon_Stock]>>> StockclockDaemonService.java:60 [0:0] onReceive: androidintentactionTIME_SET
,D/comdaemonstockapp( 1458): [Daemon_Stock]>>> StockclockDaemonService.java:61 [0:0] appServiceStatus: 0
,I/CheckinService( 1795): Checkin interval check for package: unspecified last checkin: 1449576543959 min interval config: 0 actual interval: 255830890
,I/rmt_storage(  296): rmt_storage_connect_cb: clnt_h=0x5 conn_h=0xb87a2178
I/rmt_storage(  296): rmt_storage_rw_iovec_cb: /boot/modem_fs2: clnt_h=0x2: req_h=0xa msg_id=3: R/W request received
I/rmt_storage(  296): wakelock acquired: 1, error no: 42
,I/rmt_storage(  296): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 Unblock worker thread (th_id: -1199955400)
,D/hcjo    ( 4814): AutoUpdateTriggerManager:REQUEST2:setInterval:345600000
D/hcjo    ( 4814): AutoUpdateTriggerManager:REQUEST2:notifyTimedOutAndWriteUpdateCheckedTime
D/hcjo    ( 4814): AutoUpdateManager:UPD_CHECK_TIMING:onUpdateTime
,D/hcjo    ( 4814): SelfUpdateManager:IDLE:execute
,D/hcjo    ( 4814): SelfUpdateManager:CONDITION_CHECK:onUpdateCondition
,I/Volley  ( 4814): RestApi Request Add : 2346
,I/rmt_storage(  296): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0xa msg_id=3: Bytes written = 1572864
,I/rmt_storage(  296): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0xa msg_id=3: Send response: res=0 err=0
,I/rmt_storage(  296): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 About to block rmt_storage client thread (th_id: -1199955400) wakelock released: 1, error no: 0
I/rmt_storage(  296): 
,I/rmt_storage(  296): rmt_storage_disconnect_cb: clnt_h=0x0x5 conn_h=0x0xb87a2178
V/AlarmManager(  740): waitForAlarm result :4
V/AlarmManager(  740): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,D/BatteryService(  740): level:100, scale:100, status:5, health:2, present:true, voltage: 4366, temperature: 291, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:9, charge type:1, power sharing:false
D/BatteryService(  740): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  740): stay LED for fully charged
,D/UiModeManager(  740): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 1064): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1064): handleBatteryUpdate
V/HeadsetService( 3163): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3163): Disconnected process message: 10
,D/STATUSBAR-PhoneStatusBar( 1064):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1064): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/SELinux ( 5436): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5436):  
D/STATUSBAR-IconMerger( 1064): checkOverflow(288), More:false, Req:false Child:2
,I/SELinux ( 5436): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5436):  
I/SELinux ( 5436):  
,I/SELinux ( 5436): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5436): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 5436): >>>>> Normal User
,E/dalvikvm( 5436): >>>>> com.google.android.talk [ userId:0 | appId:10105 ]
,E/SELinux ( 5436): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
,D/TimaKeyStoreProvider( 5436): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5436): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5436): Added TimaKesytore provider
,V/AlarmManager(  740): waitForAlarm result :4
,V/AlarmManager(  740): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,W/ActivityManager(  740): Permission Denial: getCurrentUser() from pid=5436, uid=10105 requires android.permission.INTERACT_ACROSS_USERS
,I/PCWCLIENTTRACE_SYSTEMReceiver( 4493): mConnectivityHandler : connected
,W/PCWCLIENTTRACE_AccountUtil( 4493): [hasSamungAccount] - No Samsung Account
,I/qtaguid ( 4814): Failed write_ctrl(u -1) res=-1 errno=9
,I/qtaguid ( 4814): Untagging socket -1 failed errno=-9
,W/NetworkManagementSocketTagger( 4814): untagSocket(-1) failed with errno -9
,D/hcjo    ( 4814): SelfUpdateManager:REQUEST_UPD_CHECK:onUpdateCheckSuccessAndNoNeedUpdate
,D/hcjo    ( 4814): AutoUpdateManager:CHECK_SELF_UPD:onSelfUpdateResult:T
,D/hcjo    ( 4814): SellerAppAutoUpdate:clearFlag
,D/SellerAppAutoUpdateManagerStateMachine( 4814): execute::IDLE:EXECUTE
D/SellerAppAutoUpdateManagerStateMachine( 4814): exit::IDLE
,D/SellerAppAutoUpdateManagerStateMachine( 4814): entry::TOKENCHECK
D/SellerAppAutoUpdateManagerStateMachine( 4814): execute::TOKENCHECK:TOKEN_RECEIVED
D/SellerAppAutoUpdateManagerStateMachine( 4814): exit::TOKENCHECK
D/SellerAppAutoUpdateManagerStateMachine( 4814): entry::FAILED
D/hcjo    ( 4814): AutoUpdateManager:SELLER_UPD:onSellerAutoUpdateFailed
D/SellerAppAutoUpdateManagerStateMachine( 4814): exit::FAILED
,D/SellerAppAutoUpdateManagerStateMachine( 4814): entry::IDLE
I/ActivityManager(  740): Killing 4546:com.sec.android.service.health/u0a16 (adj 15): empty #43
,I/Babel   ( 5436): MmsConfig: mnc/mcc: 0/0
,I/Babel   ( 5436): MmsConfig.loadMmsSettings
I/Babel   ( 5436): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=SAMSUNG-ANDROID-MMS/SM-G800H, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-G800H.xml
,I/Babel   ( 5436): MmsConfig.loadFromDatabase
,W/linker  ( 4493): libterrier.so has text relocations. This is wasting memory and is a security risk. Please fix.
I/CSTORAGE( 4493): ================================================
I/CSTORAGE( 4493):  CSTORAGE_SKM_LIB v1.0.14
I/CSTORAGE( 4493): ================================================
D/dalvikvm( 4493): No JNI_OnLoad found in /system/lib/libterrier.so 0x425d5180, skipping init
I/PCWCLIENTTRACE_SecurePreferencesJNI( 4493): [GetString-S]
,I/terrier ( 4493): v1.1.3q com.sec.pcw.device: getString function called
,D/QSEECOMAPI: ( 4493): QSEECom_get_handle sb_length = 0x2040
,D/QSEECOMAPI: ( 4493): App is not loaded in QSEE
,E/Babel   ( 5436): canonicalizeMccMnc: invalid mccmnc 
,I/Babel   ( 5436): MmsConfig.loadFromResources
,E/Babel   ( 5436): canonicalizeMccMnc: invalid mccmnc nullnull
,D/Finsky  ( 3515): [349] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,I/Babel   ( 5436): MmsConfig.loadMmsSettings: mUserAgent=SAMSUNG-ANDROID-MMS/SM-G800H, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-G800H.xml
,D/Finsky  ( 3515): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,D/QSEECOMAPI: ( 4493): Loaded image: APP id = 3
,W/Settings( 5436): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/QSEECOMAPI: ( 4493): QSEECom_dealloc_memory 
,D/QSEECOMAPI: ( 4493): QSEECom_shutdown_app, app_id = 3
E/terrier ( 4493): com.sec.pcw.device: getString: failed to get string(-1)
,I/PCWCLIENTTRACE_SecurePreferencesJNI( 4493): [GetString-E]
I/PCWCLIENTTRACE_PushUtil( 4493): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 4493): sales region : global
I/PCWCLIENTTRACE_PushUtil( 4493): getPushTypeList : [SPP, GCM]
,E/PCWCLIENTTRACE_PCWHandler( 4493): [ensureRegistration] - No Samsung account
D/dalvikvm( 5436): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 5436): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 5436): VFY: replacing opcode 0x62 at 0x000a
D/dalvikvm( 5436): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
W/dalvikvm( 5436): VFY: unable to resolve instance field 36
,D/dalvikvm( 5436): VFY: replacing opcode 0x54 at 0x005f
D/dalvikvm( 5436): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 5436): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 5436): VFY: replacing opcode 0x62 at 0x0047
D/dalvikvm( 5436): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
,I/dalvikvm( 5436): DexOpt: unable to optimize instance field ref 0x0024 at 0x63 in Lcom/google/android/gms/common/util/ay;.b
,D/dalvikvm( 5436): Trying to load lib /data/app-lib/com.google.android.gms-2/libgmscore.so 0x42707af0
,D/dalvikvm( 5436): Added shared lib /data/app-lib/com.google.android.gms-2/libgmscore.so 0x42707af0
,D/dalvikvm( 5436): No JNI_OnLoad found in /data/app-lib/com.google.android.gms-2/libgmscore.so 0x42707af0, skipping init
,D/dalvikvm( 5436): Trying to load lib /data/app-lib/com.google.android.gms-2/libconscrypt_gmscore_jni.so 0x42707af0
,D/dalvikvm( 5436): Added shared lib /data/app-lib/com.google.android.gms-2/libconscrypt_gmscore_jni.so 0x42707af0
,V/JNIHelp ( 5436): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,D/Mms/MessagesLockscreen( 3779): onReceive() action = com.android.mms.ui.MessagesLockscreenmSimSlot : [0] Mms = false count = 0
,D/ContextualEventManager( 1064): removeContextualEvent(): requestClass=com.android.mms
D/ContextualEventManager( 1064): removeMissedEventView rq=com.android.mms[cFlag, mFlag]=[false, false]
D/ContextualEventManager( 1064): updateContainer()
D/ContextualEventContainer( 1064): update()
D/ContextualEventContainer( 1064): handleUpdate()
D/ContextualEventManager( 1064): getTopEventView()
,D/ContextualEventManager( 1064): getTopContextualEvent()
,D/Headlines( 5202): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE
,D/Headlines( 5202): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0
,D/Headlines( 5202): Breath 3345 latestRequest time : 1449832372100 current time : 1449832375445
,I/SELinux ( 5468): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5468):  
D/ContextualEventManager( 1064): top view = flightmode
I/KeyguardEffectViewMain( 1064): *** KeyguardEffectView getInstance ***
D/ContextualEventManager( 1064): getTopEventClass()
,D/ContextualEventManager( 1064): getTopContextualEvent()
D/ContextualEventManager( 1064): !isClockTop
D/ContextualEventManager( 1064): getTopEventClass()
,D/ContextualEventManager( 1064): getTopContextualEvent()
D/ContextualEventManager( 1064): !isClockTop
D/ContextualEventManager( 1064): getTopEventClass()
,D/ContextualEventManager( 1064): getTopContextualEvent()
D/UsbManager( 1064):  :::: isUsb30Available :: return = false from pid = 1064
,D/dalvikvm( 5436): Trying to load lib /data/app-lib/com.google.android.gms-2/libgmscore.so 0x42707af0
,D/dalvikvm( 5436): Shared lib '/data/app-lib/com.google.android.gms-2/libgmscore.so' already loaded in same CL 0x42707af0
D/dalvikvm( 5436): Trying to load lib /data/app-lib/com.google.android.gms-2/libconscrypt_gmscore_jni.so 0x42707af0
,D/dalvikvm( 5436): Shared lib '/data/app-lib/com.google.android.gms-2/libconscrypt_gmscore_jni.so' already loaded in same CL 0x42707af0
,D/SecContextualClockFlightMode( 1064): handleUpdateClock()
,D/KeyguardProperties( 1064): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/dalvikvm(  246): GC_EXPLICIT freed 41K, 50% free 9512K/18944K, paused 3ms+3ms, total 26ms
,D/dalvikvm(  246): GC_EXPLICIT freed <1K, 50% free 9512K/18944K, paused 2ms+3ms, total 19ms
I/SELinux ( 5468): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5468):  
I/SELinux ( 5468):  
,I/SELinux ( 5468): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5468): [DEBUG] seapp_context_lookup: seinfoCategory = release
E/dalvikvm( 5468): >>>>> Normal User
,E/dalvikvm( 5468): >>>>> com.android.providers.calendar [ userId:0 | appId:10044 ]
,E/SELinux ( 5468): [DEBUG] seapp_context_lookup: seinfoCategory = release
,D/dalvikvm(  246): GC_EXPLICIT freed <1K, 50% free 9512K/18944K, paused 1ms+3ms, total 18ms
,D/TimaKeyStoreProvider( 5468): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5468): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5468): Added TimaKesytore provider
,I/ProviderInstaller( 5436): Installed default security provider GmsCore_OpenSSL
,D/dalvikvm(  740): GC_EXPLICIT freed 1427K, 58% free 23441K/54724K, paused 4ms+10ms, total 120ms
,V/GLSActivity( 1313): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1313): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager(  740): Permission Denial: getCurrentUser() from pid=5468, uid=10044 requires android.permission.INTERACT_ACROSS_USERS
,D/dalvikvm( 1313): GC_CONCURRENT freed 1862K, 43% free 10930K/18944K, paused 2ms+3ms, total 35ms
,I/System.out( 5436): Thread-551(HTTPLog):isShipBuild true
,I/System.out( 5436): Thread-551(HTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,I/PhenotypeConfigurator( 1213): Scheduling Phenotype for one-off execution 12099 seconds from now (1449832376428)
,D/GetConfigurationSnapshotOperation( 1213): no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,I/PhenotypeFlagCommitter( 1213): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,I/GoogleURLConnFactory( 1213): Using platform SSLCertificateSocketFactory
,D/LocationManagerService(  740): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,E/SMD     (  239): DCD ON
,D/LocationManagerService(  740): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/LocationManagerService(  740): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,I/PowerManagerService(  740): [PWL] Off : 75s ago
,I/PowerManagerService(  740): [PWL]   PowerManagerService.WakeLocks: ref count=1
I/PowerManagerService(  740): [PWL]     mWakeLockSummary : 0x1
I/PowerManagerService(  740): [PWL]       PARTIAL_WAKE_LOCK              'AlarmReceiver' (uid=10084, pid=5352, ws=null) (elapsedTime=2768)
,I/PowerManagerService(  740): [PWL]       PARTIAL_WAKE_LOCK              '*net_scheduler*' (uid=10011, pid=1313, ws=WorkSource{10011 com.google.android.gms}) (elapsedTime=593)
,D/LocationManagerService(  740): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/LocationManagerService(  740): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,I/ActivityManager(  740): Killing 3860:com.samsung.android.sdk.samsunglink/u0a42 (adj 15): empty #43
,D/STATUSBAR-NetworkController_dual( 1064): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
,D/StatusBar.NetworkController_dual( 1064): mMobileLabelViews start
D/StatusBar.NetworkController_dual( 1064): mMobileLabelViews set mobileLabel[SIM_0] =
,D/StatusBar.NetworkController_dual( 1064): mMobileLabelViews GONE
D/StatusBar.NetworkController_dual( 1064): mMobileLabelViews2 set mobileLabel[SIM_1] =
D/StatusBar.NetworkController_dual( 1064): mMobileLabelViews2 GONE
,D/StatusBar.NetworkController_dual( 1064): mSingleMobileLabelViews set : simMode = 0
,D/StatusBar.NetworkController_dual( 1064): mSingleMobileLabelViews set as slot1`s
,D/dalvikvm( 1213): GC_CONCURRENT freed 1805K, 38% free 11922K/18944K, paused 9ms+13ms, total 83ms
,I/GAV2    ( 5214): Thread[GAThread,5,main]: No campaign data found.
,I/Babel   ( 5436): Account registration complete:Redacted-21
,E/Watchdog(  740): !@Sync 4
,E/SMD     (  239): DCD ON
,V/AlarmManager(  740): waitForAlarm result :8
,V/AlarmManager(  740): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1064): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1064): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1064): checkOverflow(288), More:false, Req:false Child:2
,D/CaptivePortalTracker(  740): DelayedCaptiveCheckState{ when=-9ms what=2 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
,D/ConnectivityService(  740): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,D/CaptivePortalTracker(  740): Checking http://216.58.209.78/generate_204
,W/ActivityThread(  740): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,I/System.out(  740): Thread-162(HTTPLog):isShipBuild true
,I/System.out(  740): Thread-162(HTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,D/CaptivePortalTracker(  740): Don't send network conditions - lacking user consent.
,D/CaptivePortalTracker(  740): isCaptivePortal: ret=false rspCode=204
,D/CaptivePortalTracker(  740): Not captive network NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/CaptivePortalTracker(  740): notifyPortalCheckCompleted: captive=false ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService(  740): captivePortalCheckCompleted: ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false captive=false
,D/AmoledAdjustTimer(  740): prevTemp = 286, currTemp = 291, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP(  740): SIOP:: AP = 310, Delta = -10
,D/EnterpriseDeviceManagerService(  740): Creating context as user 0
,I/ActivityManager(  740): Killing 2837:com.samsung.android.app.assistantmenu/1000 (adj 15): empty #43
,I/GAV4    ( 5436): Thread[GAThread,5,main]: No campaign data found.
,E/SMD     (  239): DCD ON
,D/PreloadUpdateManagerStateMachine( 4814): execute::IDLE:EXECUTE
,D/PreloadUpdateManagerStateMachine( 4814): exit::IDLE
,D/PreloadUpdateManagerStateMachine( 4814): entry::CHECK_TIMEOUT_FOR_UPDATE
,D/hcjo    ( 4814): AutoUpdateTriggerManager:IDLE:setInterval:86400000
,D/hcjo    ( 4814): AutoUpdateTriggerManager:IDLE:notifyNextTime
,D/PreloadUpdateManagerStateMachine( 4814): execute::CHECK_TIMEOUT_FOR_UPDATE:NO_TIMED_OUT
,D/PreloadUpdateManagerStateMachine( 4814): exit::CHECK_TIMEOUT_FOR_UPDATE
,D/PreloadUpdateManagerStateMachine( 4814): entry::IDLE
,D/BatteryService(  740): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 291, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:11, charge type:1, power sharing:false
,D/BatteryService(  740): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  740): mCoverManager.getCoverState() : true
,D/BatteryService(  740): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1064): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1064): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1064):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1064): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3163): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3163): Disconnected process message: 10
D/STATUSBAR-IconMerger( 1064): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  239): DCD ON
,I/ActivityManager(  740): Waited long enough for: ServiceRecord{430353f8 u0 com.samsung.android.app.headlines/com.samsung.android.internal.headlines.HeadlinesService}
,E/SMD     (  239): DCD ON
,D/AmoledAdjustTimer(  740): prevTemp = 291, currTemp = 291, prevStep = 4, currStep = 4
,E/SMD     (  239): DCD ON
,D/SSRMv2:SIOP(  740): SIOP:: AP = 300, Delta = -10
,D/PackageManager(  740): [MSG] SEND_PENDING_BROADCAST
,D/PackageManager(  740): Sending to user 0: act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.talk flg=0x4000000 Bundle[{android.intent.extra.changed_component_name=com.google.android.apps.babel.realtimechat.RequestWriter$NetworkStateReceiver, android.intent.extra.DONT_KILL_APP=true, android.intent.extra.UID=10105, android.intent.extra.changed_component_name_list=[Ljava.lang.String;@4440cc50, com.samsung.android.intent.extra.SECRET_APP=false, android.intent.extra.user_handle=0}]
,I/InputReader(  740): Reconfiguring input devices.  changes=0x00000010
,I/PackageManager(  740):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  740):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  740):   Scheme: "sms"
I/PackageManager(  740): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,I/PackageManager(  740):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  740):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  740):   Scheme: "smsto"
I/PackageManager(  740): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,V/ApplicationPolicy(  740): isApplicationStateBlocked userId 0 pkgname com.google.android.talk
,I/PackageManager(  740):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  740):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  740):   Scheme: "mms"
I/PackageManager(  740): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,I/PackageManager(  740):   Action: "android.intent.action.SENDTO"
I/PackageManager(  740):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  740):   Scheme: "mmsto"
I/PackageManager(  740): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,I/PackageManager(  740):   Action: "android.intent.action.SENDTO"
I/PackageManager(  740):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  740):   Scheme: "sms"
I/PackageManager(  740): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,I/IcingCorporaProvider( 2120): Updating corpora: APPS=com.google.android.talk, CONTACTS=MAYBE
,I/Launcher.Workspace( 1256): isBadgeUpdate : false
,D/FileShare-Server( 4172): ServerBroadcastReceiver.onReceive - action android.intent.action.PACKAGE_CHANGED // package:com.google.android.talk
,I/PackageManager(  740):   Action: "android.intent.action.SENDTO"
I/PackageManager(  740):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  740):   Scheme: "smsto"
I/PackageManager(  740): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,I/PackageManager(  740):   Action: "android.intent.action.SENDTO"
I/PackageManager(  740):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  740):   Scheme: "mms"
I/PackageManager(  740): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,I/SELinux ( 5571): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5571):  
,W/Resources(  740): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
I/PackageManager(  740):   Action: "android.intent.action.SENDTO"
I/PackageManager(  740):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  740):   Scheme: "mmsto"
I/PackageManager(  740): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,W/Resources(  740): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  740): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  740): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  740): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  740): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  740): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,I/SELinux ( 5571): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5571):  
I/SELinux ( 5571):  
,I/SELinux ( 5571): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5571): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 5571): >>>>> Normal User
,E/dalvikvm( 5571): >>>>> com.sec.knox.bridge [ userId:0 | appId:1000 ]
,E/SELinux ( 5571): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,W/Resources(  740): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  740): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  740): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  740): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,D/TimaKeyStoreProvider( 5571): in addTimaSignatureService
,W/Resources(  740): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/dalvikvm( 2120): GC_CONCURRENT freed 1693K, 39% free 11618K/18944K, paused 13ms+6ms, total 116ms
,D/dalvikvm( 2120): WAIT_FOR_CONCURRENT_GC blocked 72ms
,D/TimaKeyStoreProvider( 5571): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5571): Added TimaKesytore provider
,W/Resources(  740): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  740): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,W/Resources(  740): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  740): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  740): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,I/IcingCorporaProvider( 2120): UpdateCorporaTask done [took 231 ms] updated apps [took 230 ms] 
,D/BezelQuickConnect( 3149): BezelBroadcastReceiver - onReceive : android.intent.action.PACKAGE_CHANGED
,D/BezelQuickConnect( 3149): BezelBroadcastReceiver - packageName : com.google.android.talk
,D/PackageBroadcastService( 1795): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.talk
,D/dalvikvm( 4190): GC_FOR_ALLOC freed 4093K, 37% free 11970K/18944K, paused 38ms, total 40ms
,I/dalvikvm-heap( 4190): Grow heap (frag case) to 16.941MB for 2129936-byte allocation
,I/ActivityManager(  740): Killing 4701:com.sec.android.service.cm/u0a78 (adj 15): empty #43
,D/dalvikvm( 4190): GC_CONCURRENT freed 37K, 27% free 14014K/18944K, paused 11ms+3ms, total 33ms
,D/dalvikvm( 4190): WAIT_FOR_CONCURRENT_GC blocked 18ms
,I/dalvikvm-heap( 4190): Grow heap (frag case) to 18.937MB for 2129936-byte allocation
,D/dalvikvm( 4190): GC_CONCURRENT freed 2K, 24% free 16092K/21028K, paused 5ms+2ms, total 23ms
,W/ApplicationsProvider( 1396): Could not fetch usage stats
W/ApplicationsProvider( 1396): java.lang.SecurityException: Neither user 10020 nor current process has android.permission.PACKAGE_USAGE_STATS.
W/ApplicationsProvider( 1396): 	at android.os.Parcel.readException(Parcel.java:1465)
W/ApplicationsProvider( 1396): 	at android.os.Parcel.readException(Parcel.java:1419)
W/ApplicationsProvider( 1396): 	at com.android.internal.app.IUsageStats$Stub$Proxy.getAllPkgUsageStats(IUsageStats.java:317)
W/ApplicationsProvider( 1396): 	at android.app.ActivityManager.getAllPackageUsageStats(ActivityManager.java:2543)
W/ApplicationsProvider( 1396): 	at com.android.providers.applications.ApplicationsProvider.fetchUsageStats(ApplicationsProvider.java:681)
W/ApplicationsProvider( 1396): 	at com.android.providers.applications.ApplicationsProvider.updateApplicationsList(ApplicationsProvider.java:519)
W/ApplicationsProvider( 1396): 	at com.android.providers.applications.ApplicationsProvider.access$300(ApplicationsProvider.java:70)
W/ApplicationsProvider( 1396): 	at com.android.providers.applications.ApplicationsProvider$UpdateHandler.handleMessage(ApplicationsProvider.java:212)
W/ApplicationsProvider( 1396): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/ApplicationsProvider( 1396): 	at android.os.Looper.loop(Looper.java:146)
W/ApplicationsProvider( 1396): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,W/ContextImpl(  740): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  239): DCD ON
,I/Icing   ( 1795): Indexing 49CA7E3A917E607C6D98AA15891295369CED2106 from com.google.android.gms
,I/Icing   ( 1795): Indexing done 49CA7E3A917E607C6D98AA15891295369CED2106
,E/SMD     (  239): DCD ON
,E/SMD     (  239): DCD ON
,D/AmoledAdjustTimer(  740): prevTemp = 291, currTemp = 291, prevStep = 4, currStep = 4
,V/AlarmManager(  740): waitForAlarm result :4
,V/AlarmManager(  740): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,D/BatteryService(  740): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 288, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:8, charge type:1, power sharing:false
,V/AlarmManager(  740): waitForAlarm result :8
,D/BatteryService(  740): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  740): stay LED for fully charged
,D/UiModeManager(  740): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1064): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1064): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1064):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1064): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3163): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3163): Disconnected process message: 10
D/STATUSBAR-IconMerger( 1064): checkOverflow(288), More:false, Req:false Child:2
,D/Headlines( 5202): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE
,D/Headlines( 5202): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0
,D/Headlines( 5202): Breath 30130 latestRequest time : 1449832372100 current time : 1449832402230
,D/SSRMv2:SIOP(  740): SIOP:: AP = 300, Delta = 0
,E/ActivityThread( 1795): Failed to find provider info for com.android.contacts.metadata
,D/SyncManager(  740): failed sync operation 
,D/SyncManager(  740): not retrying sync operation because the error is a hard error: 
,E/SMD     (  239): DCD ON
,E/SMD     (  239): DCD ON
,I/PowerManagerService(  740): [PWL] Off : 105s ago
,E/Watchdog(  740): !@Sync 5
,E/SMD     (  239): DCD ON
,D/AmoledAdjustTimer(  740): prevTemp = 291, currTemp = 288, prevStep = 4, currStep = 4
,D/BatteryService(  740): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:13, charge type:1, power sharing:false
,D/BatteryService(  740): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  740): mCoverManager.getCoverState() : true
,D/BatteryService(  740): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1064): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1064): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1064):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1064): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3163): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3163): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1064): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  740): SIOP:: AP = 300, Delta = 0
,E/SMD     (  239): DCD ON
,W/ContextImpl(  740): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  239): DCD ON
,E/SMD     (  239): DCD ON
,D/AmoledAdjustTimer(  740): prevTemp = 288, currTemp = 287, prevStep = 4, currStep = 4
,E/SMD     (  239): DCD ON
,D/BatteryService(  740): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:10, charge type:1, power sharing:false
,D/BatteryService(  740): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  740): stay LED for fully charged
,D/UiModeManager(  740): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1064): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1064): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1064):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1064): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3163): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3163): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1064): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  740): SIOP:: AP = 300, Delta = 0
,E/SMD     (  239): DCD ON
,E/SMD     (  239): DCD ON
,E/SMD     (  239): DCD ON
,D/AmoledAdjustTimer(  740): prevTemp = 287, currTemp = 286, prevStep = 4, currStep = 4
,D/dalvikvm(  740): GC_CONCURRENT freed 2946K, 57% free 23889K/54724K, paused 25ms+59ms, total 570ms
,V/AlarmManager(  740): waitForAlarm result :8
,V/AlarmManager(  740): waitForAlarm result :4
,V/AlarmManager(  740): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,D/Headlines( 5202): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE
,D/BatteryService(  740): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:10, charge type:1, power sharing:false
,D/BatteryService(  740): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  740): stay LED for fully charged
,D/UiModeManager(  740): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1064): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1064): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1064):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1064): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 3163): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 3163): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1064): checkOverflow(288), More:false, Req:false Child:2
,D/Headlines( 5202): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0
,D/Headlines( 5202): Breath 60359 latestRequest time : 1449832372100 current time : 1449832432459
,D/SSRMv2:SIOP(  740): SIOP:: AP = 300, Delta = 0
,E/SMD     (  239): DCD ON
,W/ContextImpl(  740): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  239): DCD ON
,E/Watchdog(  740): !@Sync 6
,E/SMD     (  239): DCD ON
,V/AlarmManager(  740): waitForAlarm result :8
,V/AlarmManager(  740): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1064): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1064): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1064): checkOverflow(288), More:false, Req:false Child:2
,D/AmoledAdjustTimer(  740): prevTemp = 286, currTemp = 285, prevStep = 4, currStep = 4
,I/PowerManagerService(  740): [PWL] Off : 140s ago
,D/BatteryService(  740): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 284, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:8, charge type:1, power sharing:false
,D/BatteryService(  740): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  740): mCoverManager.getCoverState() : true
,D/BatteryService(  740): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1064): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1064): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1064):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1064): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3163): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3163): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1064): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  740): SIOP:: AP = 300, Delta = 0
,E/SMD     (  239): DCD ON
,E/SMD     (  239): DCD ON
,E/SMD     (  239): DCD ON
,D/AmoledAdjustTimer(  740): prevTemp = 285, currTemp = 284, prevStep = 4, currStep = 4
,E/SMD     (  239): DCD ON
,D/BatteryService(  740): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 284, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:4, charge type:1, power sharing:false
,D/BatteryService(  740): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  740): stay LED for fully charged
,D/UiModeManager(  740): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1064): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1064): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1064):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1064): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3163): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3163): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1064): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  740): SIOP:: AP = 300, Delta = 0
,W/ContextImpl(  740): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  239): DCD ON
,E/SMD     (  239): DCD ON
,E/SMD     (  239): DCD ON
,D/AmoledAdjustTimer(  740): prevTemp = 284, currTemp = 284, prevStep = 4, currStep = 4
,V/AlarmManager(  740): waitForAlarm result :8
,D/Headlines( 5202): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE
,D/Headlines( 5202): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0
,D/Headlines( 5202): Breath 90037 latestRequest time : 1449832372100 current time : 1449832462138
,D/BatteryService(  740): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 283, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:5, charge type:1, power sharing:false
,D/BatteryService(  740): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  740): mCoverManager.getCoverState() : true
,D/BatteryService(  740): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1064): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1064): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1064):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1064): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3163): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3163): Disconnected process message: 10
D/STATUSBAR-IconMerger( 1064): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  740): SIOP:: AP = 300, Delta = 0
,E/SMD     (  239): DCD ON
,E/SMD     (  239): DCD ON
,E/Watchdog(  740): !@Sync 7
,E/SMD     (  239): DCD ON
,D/AmoledAdjustTimer(  740): prevTemp = 284, currTemp = 283, prevStep = 4, currStep = 4
,D/BatteryService(  740): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 283, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:5, charge type:1, power sharing:false
,D/BatteryService(  740): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  740): mCoverManager.getCoverState() : true
,D/BatteryService(  740): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1064): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1064): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1064):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1064): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3163): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3163): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1064): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  740): SIOP:: AP = 300, Delta = 0
,E/SMD     (  239): DCD ON
,W/ContextImpl(  740): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  239): DCD ON
,E/SMD     (  239): DCD ON
,D/AmoledAdjustTimer(  740): prevTemp = 283, currTemp = 283, prevStep = 4, currStep = 4
,E/SMD     (  239): DCD ON
,I/PowerManagerService(  740): [PWL] Off : 180s ago
,D/BatteryService(  740): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:2, charge type:1, power sharing:false
,D/BatteryService(  740): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  740): stay LED for fully charged
,D/UiModeManager(  740): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1064): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1064): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1064):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1064): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3163): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3163): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1064): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  740): SIOP:: AP = 300, Delta = 0
,E/SMD     (  239): DCD ON
,E/SMD     (  239): DCD ON
,E/SMD     (  239): DCD ON
,D/AmoledAdjustTimer(  740): prevTemp = 283, currTemp = 282, prevStep = 4, currStep = 4
,V/AlarmManager(  740): waitForAlarm result :8
,D/Headlines( 5202): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE
,D/Headlines( 5202): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0
,D/Headlines( 5202): Breath 120037 latestRequest time : 1449832372100 current time : 1449832492141
,D/Headlines( 5202): stop 
,D/Headlines( 5202): Breath.onDestroy : 
,I/ActivityManager(  740): Killing 4713:com.google.android.apps.docs/u0a90 (adj 15): empty #43
,D/SSRMv2:SIOP(  740): SIOP:: AP = 300, Delta = 0
,E/SMD     (  239): DCD ON
,W/ContextImpl(  740): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  239): DCD ON
,E/Watchdog(  740): !@Sync 8
,E/SMD     (  239): DCD ON
,V/AlarmManager(  740): waitForAlarm result :8
,V/AlarmManager(  740): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1064): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1064): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1064): checkOverflow(288), More:false, Req:false Child:2
,D/AmoledAdjustTimer(  740): prevTemp = 282, currTemp = 282, prevStep = 4, currStep = 4
,D/BatteryService(  740): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:2, charge type:1, power sharing:false
,D/BatteryService(  740): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  740): mCoverManager.getCoverState() : true
,D/BatteryService(  740): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1064): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1064): handleBatteryUpdate
,E/SMD     (  239): DCD ON
,D/STATUSBAR-PhoneStatusBar( 1064):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1064): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3163): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3163): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1064): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  740): SIOP:: AP = 300, Delta = 0
,E/SMD     (  239): DCD ON
,E/SMD     (  239): DCD ON
,D/AmoledAdjustTimer(  740): prevTemp = 282, currTemp = 281, prevStep = 4, currStep = 4
,E/SMD     (  239): DCD ON
,D/SSRMv2:SIOP(  740): SIOP:: AP = 300, Delta = 0
,W/ContextImpl(  740): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  239): DCD ON
,E/SMD     (  239): DCD ON
,E/SMD     (  239): DCD ON
,D/AmoledAdjustTimer(  740): prevTemp = 281, currTemp = 281, prevStep = 4, currStep = 4
,D/BatteryService(  740): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService(  740): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  740): mCoverManager.getCoverState() : true
,D/BatteryService(  740): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1064): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1064): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1064):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1064): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3163): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3163): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1064): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  740): SIOP:: AP = 300, Delta = 0
,E/SMD     (  239): DCD ON
,I/jxcore-log( 4656): Connected to the server!
I/jxcore-log( 4656): 
,I/chromium( 4656): [INFO:CONSOLE(63)] "logCallback Connected to the server", source: file:///android_asset/www/js/thali_main.js (63)
,E/SMD     (  239): DCD ON
,I/PowerManagerService(  740): [PWL] Off : 225s ago
,E/Watchdog(  740): !@Sync 9
,E/SMD     (  239): DCD ON
,D/AmoledAdjustTimer(  740): prevTemp = 281, currTemp = 281, prevStep = 4, currStep = 4
,E/SMD     (  239): DCD ON
,D/BatteryService(  740): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 280, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:2, charge type:1, power sharing:false
,D/BatteryService(  740): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  740): stay LED for fully charged
,D/UiModeManager(  740): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1064): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1064): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1064):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3163): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3163): Disconnected process message: 10
D/STATUSBAR-IconMerger( 1064): checkOverflow(288), More:false, Req:false Child:2
D/BatteryMeterView( 1064): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP(  740): SIOP:: AP = 300, Delta = 0
,W/ContextImpl(  740): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  239): DCD ON
,E/SMD     (  239): DCD ON
,D/AmoledAdjustTimer(  740): prevTemp = 281, currTemp = 280, prevStep = 4, currStep = 4
,E/SMD     (  239): DCD ON
,D/BatteryService(  740): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 280, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:8, charge type:1, power sharing:false
,D/BatteryService(  740): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  740): stay LED for fully charged
,D/UiModeManager(  740): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1064): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1064): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1064):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1064): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3163): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3163): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1064): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  740): SIOP:: AP = 300, Delta = 0
,E/SMD     (  239): DCD ON
,E/SMD     (  239): DCD ON
,E/SMD     (  239): DCD ON
,D/AmoledAdjustTimer(  740): prevTemp = 280, currTemp = 280, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP(  740): SIOP:: AP = 300, Delta = 0
,D/TimaService(  740): TIMA: TimaService scheduler is intialized. 
,D/TimaService(  740): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService(  740): TimaServiceHandler.handleMessage what =1
,I/TLC_TIMA_PKM_initialize(  740): initializing...
,I/TLC_TIMA_PKM_initialize(  740): root = /firmware/image, root_strlen = 15
,I/TLC_TIMA_PKM_initialize(  740): process = tima_pkm, process_strlen = 8
,I/TZ: qc_tlc_communication(  740): root = /firmware/image, root_len = 15
,I/TZ: qc_tlc_communication(  740): process = tima_pkm, process_strlen = 8
,I/TZ: qc_tlc_communication(  740): aligned max_sendmsg_size = 262208 = 0x40040
,I/TZ: qc_tlc_communication(  740): aligned max_recvmsg_size = 262208 = 0x40040
,I/TZ: qc_tlc_communication(  740): max_message_size = 524416 = 0x80080
,D/QSEECOMAPI: (  740): QSEECom_get_handle sb_length = 0x80080
,D/QSEECOMAPI: (  740): App is not loaded in QSEE
,D/QSEECOMAPI: (  740): Loaded image: APP id = 3
,I/TZ: qc_tlc_communication(  740): TIMA: path = /firmware/image, fname = tima_pkm, tzapp is loaded
,I/TLC_TIMA_PKM_initialize(  740): Trustlet response is completed
,E/SMD     (  239): DCD ON
,W/ContextImpl(  740): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  239): DCD ON
,I/TLC_TIMA_PKM_measure_kernel(  740): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel(  740): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService(  740): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService(  740): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/Watchdog(  740): !@Sync 10
,E/SMD     (  239): DCD ON
,V/AlarmManager(  740): waitForAlarm result :8
,V/AlarmManager(  740): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1064): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1064): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1064): checkOverflow(288), More:false, Req:false Child:2
,D/AmoledAdjustTimer(  740): prevTemp = 280, currTemp = 280, prevStep = 4, currStep = 4
,E/SMD     (  239): DCD ON
,D/SSRMv2:SIOP(  740): SIOP:: AP = 300, Delta = 0
,E/SMD     (  239): DCD ON
,E/SMD     (  239): DCD ON
,D/AmoledAdjustTimer(  740): prevTemp = 280, currTemp = 280, prevStep = 4, currStep = 4
,E/SMD     (  239): DCD ON
,D/SSRMv2:SIOP(  740): SIOP:: AP = 300, Delta = 0
,W/ContextImpl(  740): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  239): DCD ON
,I/PowerManagerService(  740): [PWL] Off : 275s ago
,E/SMD     (  239): DCD ON
,V/AlarmManager(  740): waitForAlarm result :4
,V/AlarmManager(  740): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,I/SELinux ( 5649): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5649):  
D/BatteryService(  740): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
D/BatteryService(  740): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  740): stay LED for fully charged
,D/UiModeManager(  740): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1064): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1064): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1064):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 1064): checkOverflow(288), More:false, Req:false Child:2
,D/BatteryMeterView( 1064): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3163): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3163): Disconnected process message: 10
,I/SELinux ( 5649): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 5649):  
I/SELinux ( 5649):  
,I/SELinux ( 5649): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5649): [DEBUG] seapp_context_lookup: seinfoCategory = default
,E/dalvikvm( 5649): >>>>> Normal User
,E/dalvikvm( 5649): >>>>> com.blurb.checkout [ userId:0 | appId:10075 ]
,E/SELinux ( 5649): [DEBUG] seapp_context_lookup: seinfoCategory = default
,D/TimaKeyStoreProvider( 5649): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5649): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5649): Added TimaKesytore provider
,W/ActivityManager(  740): Permission Denial: getCurrentUser() from pid=5649, uid=10075 requires android.permission.INTERACT_ACROSS_USERS
,I/ActivityManager(  740): Killing 4747:com.samsung.android.app.watchmanagerstub/u0a100 (adj 15): empty #43
,E/SMD     (  239): DCD ON
,D/AmoledAdjustTimer(  740): prevTemp = 280, currTemp = 279, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP(  740): SIOP:: AP = 300, Delta = 0
,E/SMD     (  239): DCD ON
,E/SMD     (  239): DCD ON
,V/GLSActivity( 1313): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1313): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/dalvikvm( 3515): GC_CONCURRENT freed 2761K, 45% free 10426K/18944K, paused 13ms+15ms, total 190ms
,E/Watchdog(  740): !@Sync 11
,E/SMD     (  239): DCD ON
,D/AmoledAdjustTimer(  740): prevTemp = 279, currTemp = 279, prevStep = 4, currStep = 4
,E/SMD     (  239): DCD ON
,D/SSRMv2:SIOP(  740): SIOP:: AP = 300, Delta = 0
,W/ContextImpl(  740): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  239): DCD ON
,E/SMD     (  239): DCD ON
,D/BatteryService(  740): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:3, charge type:1, power sharing:false
,D/BatteryService(  740): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  740): mCoverManager.getCoverState() : true
,D/BatteryService(  740): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1064): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1064): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1064):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1064): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3163): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3163): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1064): checkOverflow(288), More:false, Req:false Child:2
,D/AmoledAdjustTimer(  740): prevTemp = 279, currTemp = 279, prevStep = 4, currStep = 4
,E/SMD     (  239): DCD ON
,D/SSRMv2:SIOP(  740): SIOP:: AP = 300, Delta = 0
,E/SMD     (  239): DCD ON
,E/SMD     (  239): DCD ON
,D/BatteryService(  740): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  740): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  740): stay LED for fully charged
,D/UiModeManager(  740): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1064): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1064): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1064):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1064): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3163): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3163): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1064): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  239): DCD ON
,D/AmoledAdjustTimer(  740): prevTemp = 279, currTemp = 279, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP(  740): SIOP:: AP = 300, Delta = 0
,E/SMD     (  239): DCD ON
,W/ContextImpl(  740): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  239): DCD ON
,E/Watchdog(  740): !@Sync 12
,E/SMD     (  239): DCD ON
,V/AlarmManager(  740): waitForAlarm result :8
,V/AlarmManager(  740): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1064): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1064): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1064): checkOverflow(288), More:false, Req:false Child:2
,D/BatteryService(  740): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:6, charge type:1, power sharing:false
,D/BatteryService(  740): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  740): mCoverManager.getCoverState() : true
,D/BatteryService(  740): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1064): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1064): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1064):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3163): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3163): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1064): checkOverflow(288), More:false, Req:false Child:2
,D/BatteryMeterView( 1064): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer(  740): prevTemp = 279, currTemp = 279, prevStep = 4, currStep = 4
,E/SMD     (  239): DCD ON
,D/SSRMv2:SIOP(  740): SIOP:: AP = 300, Delta = 0
,E/SMD     (  239): DCD ON
,E/SMD     (  239): DCD ON
,D/BatteryService(  740): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:4, charge type:1, power sharing:false
,D/BatteryService(  740): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  740): stay LED for fully charged
,D/UiModeManager(  740): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1064): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1064): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1064):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1064): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3163): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3163): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1064): checkOverflow(288), More:false, Req:false Child:2
,D/AmoledAdjustTimer(  740): prevTemp = 279, currTemp = 279, prevStep = 4, currStep = 4
,E/SMD     (  239): DCD ON
,I/PowerManagerService(  740): [PWL] Off : 330s ago
,D/SSRMv2:SIOP(  740): SIOP:: AP = 300, Delta = 0
,W/ContextImpl(  740): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  239): DCD ON
,E/SMD     (  239): DCD ON
,D/BatteryService(  740): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:3, charge type:1, power sharing:false
,D/BatteryService(  740): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  740): mCoverManager.getCoverState() : true
,D/BatteryService(  740): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1064): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1064): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1064):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1064): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3163): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3163): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1064): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  239): DCD ON
,D/AmoledAdjustTimer(  740): prevTemp = 279, currTemp = 278, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP(  740): SIOP:: AP = 300, Delta = 0
,E/SMD     (  239): DCD ON
,E/SMD     (  239): DCD ON
,E/Watchdog(  740): !@Sync 13
,E/SMD     (  239): DCD ON
,D/AmoledAdjustTimer(  740): prevTemp = 278, currTemp = 278, prevStep = 4, currStep = 4
,E/SMD     (  239): DCD ON
,D/SSRMv2:SIOP(  740): SIOP:: AP = 300, Delta = 0
,W/ContextImpl(  740): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  239): DCD ON
,E/SMD     (  239): DCD ON
,D/BatteryService(  740): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:9, charge type:1, power sharing:false
,D/BatteryService(  740): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  740): mCoverManager.getCoverState() : true
,D/BatteryService(  740): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1064): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1064): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1064):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3163): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3163): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1064): checkOverflow(288), More:false, Req:false Child:2
,D/BatteryMeterView( 1064): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer(  740): prevTemp = 278, currTemp = 278, prevStep = 4, currStep = 4
,E/SMD     (  239): DCD ON
,D/SSRMv2:SIOP(  740): SIOP:: AP = 300, Delta = 0
,E/SMD     (  239): DCD ON
,E/SMD     (  239): DCD ON
,D/BatteryService(  740): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:8, charge type:1, power sharing:false
,D/BatteryService(  740): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  740): mCoverManager.getCoverState() : true
,D/BatteryService(  740): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1064): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1064): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1064):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1064): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3163): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3163): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1064): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  239): DCD ON
,D/AmoledAdjustTimer(  740): prevTemp = 278, currTemp = 277, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP(  740): SIOP:: AP = 300, Delta = 0
,E/SMD     (  239): DCD ON
,W/ContextImpl(  740): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  239): DCD ON
,E/Watchdog(  740): !@Sync 14
,E/SMD     (  239): DCD ON
,V/AlarmManager(  740): waitForAlarm result :8
,V/AlarmManager(  740): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1064): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1064): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1064): checkOverflow(288), More:false, Req:false Child:2
,D/BatteryService(  740): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:6, charge type:1, power sharing:false
,D/BatteryService(  740): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  740): mCoverManager.getCoverState() : true
,D/BatteryService(  740): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1064): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1064): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1064):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1064): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3163): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3163): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1064): checkOverflow(288), More:false, Req:false Child:2
,D/AmoledAdjustTimer(  740): prevTemp = 277, currTemp = 277, prevStep = 4, currStep = 4
,E/SMD     (  239): DCD ON
,D/SSRMv2:SIOP(  740): SIOP:: AP = 300, Delta = 0
,E/SMD     (  239): DCD ON
,E/SMD     (  239): DCD ON
,D/BatteryService(  740): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:2, charge type:1, power sharing:false
,D/BatteryService(  740): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  740): stay LED for fully charged
,D/UiModeManager(  740): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1064): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1064): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1064):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1064): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3163): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3163): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1064): checkOverflow(288), More:false, Req:false Child:2
,D/AmoledAdjustTimer(  740): prevTemp = 277, currTemp = 277, prevStep = 4, currStep = 4
,I/PowerManagerService(  740): [PWL] Off : 390s ago
,E/SMD     (  239): DCD ON
,D/SSRMv2:SIOP(  740): SIOP:: AP = 300, Delta = 0
,W/ContextImpl(  740): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  239): DCD ON
,E/SMD     (  239): DCD ON
,D/BatteryService(  740): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:3, charge type:1, power sharing:false
,D/BatteryService(  740): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  740): stay LED for fully charged
,D/UiModeManager(  740): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1064): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1064): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1064):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1064): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3163): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3163): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1064): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  239): DCD ON
,D/AmoledAdjustTimer(  740): prevTemp = 277, currTemp = 277, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP(  740): SIOP:: AP = 300, Delta = 0
,E/SMD     (  239): DCD ON
,E/SMD     (  239): DCD ON
,E/Watchdog(  740): !@Sync 15
,E/SMD     (  239): DCD ON
,D/AmoledAdjustTimer(  740): prevTemp = 277, currTemp = 277, prevStep = 4, currStep = 4
,E/SMD     (  239): DCD ON
,D/SSRMv2:SIOP(  740): SIOP:: AP = 300, Delta = 0
,W/ContextImpl(  740): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  239): DCD ON
,E/SMD     (  239): DCD ON
,D/BatteryService(  740): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService(  740): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  740): mCoverManager.getCoverState() : true
,D/BatteryService(  740): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1064): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1064): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1064):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1064): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3163): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3163): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1064): checkOverflow(288), More:false, Req:false Child:2
,D/AmoledAdjustTimer(  740): prevTemp = 277, currTemp = 277, prevStep = 4, currStep = 4
,E/SMD     (  239): DCD ON
,D/SSRMv2:SIOP(  740): SIOP:: AP = 300, Delta = 0
,E/SMD     (  239): DCD ON
,E/SMD     (  239): DCD ON
,D/BatteryService(  740): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  740): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  740): stay LED for fully charged
,D/UiModeManager(  740): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1064): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1064): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1064):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1064): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3163): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3163): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1064): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  239): DCD ON
,D/AmoledAdjustTimer(  740): prevTemp = 277, currTemp = 277, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP(  740): SIOP:: AP = 300, Delta = 0
,E/SMD     (  239): DCD ON
,W/ContextImpl(  740): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  239): DCD ON
,E/Watchdog(  740): !@Sync 16
,E/SMD     (  239): DCD ON
,V/AlarmManager(  740): waitForAlarm result :8
,V/AlarmManager(  740): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1064): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1064): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1064): checkOverflow(288), More:false, Req:false Child:2
,D/BatteryService(  740): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService(  740): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  740): mCoverManager.getCoverState() : true
,D/BatteryService(  740): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1064): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1064): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1064):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1064): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3163): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3163): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1064): checkOverflow(288), More:false, Req:false Child:2
,D/AmoledAdjustTimer(  740): prevTemp = 277, currTemp = 276, prevStep = 4, currStep = 4
,E/SMD     (  239): DCD ON
,D/SSRMv2:SIOP(  740): SIOP:: AP = 300, Delta = 0
,E/SMD     (  239): DCD ON
,E/SMD     (  239): DCD ON
,D/BatteryService(  740): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:5, charge type:1, power sharing:false
,D/BatteryService(  740): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  740): mCoverManager.getCoverState() : true
,D/BatteryService(  740): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1064): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1064): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1064):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1064): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3163): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3163): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1064): checkOverflow(288), More:false, Req:false Child:2
,D/AmoledAdjustTimer(  740): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,E/SMD     (  239): DCD ON
,D/SSRMv2:SIOP(  740): SIOP:: AP = 300, Delta = 0
,W/ContextImpl(  740): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  239): DCD ON
,I/PowerManagerService(  740): [PWL] Off : 455s ago
,E/SMD     (  239): DCD ON
,E/SMD     (  239): DCD ON
,D/BatteryService(  740): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:6, charge type:1, power sharing:false
,D/BatteryService(  740): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  740): mCoverManager.getCoverState() : true
,D/BatteryService(  740): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1064): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1064): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1064):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1064): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3163): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3163): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1064): checkOverflow(288), More:false, Req:false Child:2
,D/AmoledAdjustTimer(  740): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP(  740): SIOP:: AP = 300, Delta = 0
,E/SMD     (  239): DCD ON
,E/SMD     (  239): DCD ON
,E/Watchdog(  740): !@Sync 17
,E/SMD     (  239): DCD ON
,D/AmoledAdjustTimer(  740): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,E/SMD     (  239): DCD ON
,D/SSRMv2:SIOP(  740): SIOP:: AP = 300, Delta = 0
,W/ContextImpl(  740): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  239): DCD ON
,E/SMD     (  239): DCD ON
,D/BatteryService(  740): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:4, charge type:1, power sharing:false
,D/BatteryService(  740): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  740): stay LED for fully charged
,D/UiModeManager(  740): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1064): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1064): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1064):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/AmoledAdjustTimer(  740): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,D/BatteryMeterView( 1064): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3163): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3163): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1064): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  239): DCD ON
,D/SSRMv2:SIOP(  740): SIOP:: AP = 300, Delta = 0
,E/SMD     (  239): DCD ON
,E/SMD     (  239): DCD ON
,E/SMD     (  239): DCD ON
,D/BatteryService(  740): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:5, charge type:1, power sharing:false
,D/BatteryService(  740): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  740): mCoverManager.getCoverState() : true
,D/BatteryService(  740): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1064): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1064): handleBatteryUpdate
,D/AmoledAdjustTimer(  740): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,D/STATUSBAR-PhoneStatusBar( 1064):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1064): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3163): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3163): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1064): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  740): SIOP:: AP = 300, Delta = 0
,E/SMD     (  239): DCD ON
,W/ContextImpl(  740): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  239): DCD ON
,E/Watchdog(  740): !@Sync 18
,V/AlarmManager(  740): waitForAlarm result :8
,V/AlarmManager(  740): ClockReceiver onReceive() ACTION_TIME_TICK
E/SMD     (  239): DCD ON
,D/KeyguardUpdateMonitor( 1064): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1064): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1064): checkOverflow(288), More:false, Req:false Child:2
,D/AmoledAdjustTimer(  740): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,E/SMD     (  239): DCD ON
,D/SSRMv2:SIOP(  740): SIOP:: AP = 300, Delta = 0
,E/SMD     (  239): DCD ON
,E/SMD     (  239): DCD ON
,D/AmoledAdjustTimer(  740): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,D/BatteryService(  740): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-1, charge type:1, power sharing:false
,D/BatteryService(  740): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  740): stay LED for fully charged
,D/UiModeManager(  740): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1064): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1064): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1064):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3163): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3163): Disconnected process message: 10
D/BatteryMeterView( 1064): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1064): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  239): DCD ON
,D/SSRMv2:SIOP(  740): SIOP:: AP = 300, Delta = 0
,W/ContextImpl(  740): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  239): DCD ON
,E/SMD     (  239): DCD ON
,E/SMD     (  239): DCD ON
,D/AmoledAdjustTimer(  740): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,D/BatteryService(  740): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  740): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  740): stay LED for fully charged
,D/UiModeManager(  740): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1064): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1064): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1064):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1064): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3163): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3163): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1064): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  239): DCD ON
,D/SSRMv2:SIOP(  740): SIOP:: AP = 300, Delta = 0
,I/PowerManagerService(  740): [PWL] Off : 525s ago
,E/SMD     (  239): DCD ON
,E/Watchdog(  740): !@Sync 19
,E/SMD     (  239): DCD ON
,D/AmoledAdjustTimer(  740): prevTemp = 276, currTemp = 275, prevStep = 4, currStep = 4
,D/BatteryService(  740): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  740): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  740): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1064): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1064): handleBatteryUpdate
D/BatteryService(  740): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1064):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3163): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3163): Disconnected process message: 10
D/STATUSBAR-IconMerger( 1064): checkOverflow(288), More:false, Req:false Child:2
D/BatteryMeterView( 1064): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/dalvikvm(  740): GC_CONCURRENT freed 3792K, 57% free 23609K/54688K, paused 24ms+50ms, total 638ms
,E/SMD     (  239): DCD ON
,W/ContextImpl(  740): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/SSRMv2:SIOP(  740): SIOP:: AP = 300, Delta = 0
,E/SMD     (  239): DCD ON
,E/SMD     (  239): DCD ON
,D/AmoledAdjustTimer(  740): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,D/BatteryService(  740): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:5, charge type:1, power sharing:false
,D/BatteryService(  740): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  740): mCoverManager.getCoverState() : true
,D/BatteryService(  740): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1064): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1064): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1064):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1064): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3163): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3163): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1064): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  239): DCD ON
,D/SSRMv2:SIOP(  740): SIOP:: AP = 300, Delta = 0
,E/SMD     (  239): DCD ON
,E/SMD     (  239): DCD ON
,E/SMD     (  239): DCD ON
,D/AmoledAdjustTimer(  740): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,D/BatteryService(  740): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  740): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  740): mCoverManager.getCoverState() : true
,D/BatteryService(  740): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1064): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1064): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1064):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1064): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3163): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3163): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1064): checkOverflow(288), More:false, Req:false Child:2
,D/TimaService(  740): TIMA: TimaService scheduler is intialized. 
,D/TimaService(  740): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService(  740): TimaServiceHandler.handleMessage what =1
,E/SMD     (  239): DCD ON
,W/ContextImpl(  740): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/SSRMv2:SIOP(  740): SIOP:: AP = 300, Delta = 0
,E/SMD     (  239): DCD ON
,I/TLC_TIMA_PKM_measure_kernel(  740): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel(  740): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService(  740): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService(  740): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/Watchdog(  740): !@Sync 20
,V/AlarmManager(  740): waitForAlarm result :8
,V/AlarmManager(  740): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1064): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1064): handleTimeUpdate
,E/SMD     (  239): DCD ON
D/STATUSBAR-IconMerger( 1064): checkOverflow(288), More:false, Req:false Child:2
,D/AmoledAdjustTimer(  740): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,D/BatteryService(  740): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  740): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  740): stay LED for fully charged
,D/UiModeManager(  740): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1064): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1064): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1064):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1064): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3163): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3163): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1064): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  239): DCD ON
,D/SSRMv2:SIOP(  740): SIOP:: AP = 300, Delta = 0
,E/SMD     (  239): DCD ON
,E/SMD     (  239): DCD ON
,D/AmoledAdjustTimer(  740): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,D/BatteryService(  740): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  740): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  740): stay LED for fully charged
,D/UiModeManager(  740): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1064): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1064): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1064):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1064): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3163): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3163): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1064): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  239): DCD ON
,W/ContextImpl(  740): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/SSRMv2:SIOP(  740): SIOP:: AP = 300, Delta = 0
,E/SMD     (  239): DCD ON
,E/SMD     (  239): DCD ON
,E/SMD     (  239): DCD ON
,D/AmoledAdjustTimer(  740): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,E/SMD     (  239): DCD ON
,D/SSRMv2:SIOP(  740): SIOP:: AP = 300, Delta = 0
,E/SMD     (  239): DCD ON
,E/Watchdog(  740): !@Sync 21
,E/SMD     (  239): DCD ON
,D/AmoledAdjustTimer(  740): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,E/SMD     (  239): DCD ON
,D/SSRMv2:SIOP(  740): SIOP:: AP = 300, Delta = 0
,E/SMD     (  239): DCD ON
,E/SMD     (  239): DCD ON
,D/AmoledAdjustTimer(  740): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,D/BatteryService(  740): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:5, charge type:1, power sharing:false
,D/BatteryService(  740): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  740): stay LED for fully charged
,D/UiModeManager(  740): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1064): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1064): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1064):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,I/PowerManagerService(  740): [PWL] Off : 600s ago
,D/STATUSBAR-IconMerger( 1064): checkOverflow(288), More:false, Req:false Child:2
,D/BatteryMeterView( 1064): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3163): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3163): Disconnected process message: 10
,E/SMD     (  239): DCD ON
,D/SSRMv2:SIOP(  740): SIOP:: AP = 300, Delta = 0
,E/SMD     (  239): DCD ON
,E/SMD     (  239): DCD ON
,E/SMD     (  239): DCD ON
,D/AmoledAdjustTimer(  740): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,D/BatteryService(  740): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:4, charge type:1, power sharing:false
,D/BatteryService(  740): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  740): stay LED for fully charged
,D/UiModeManager(  740): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1064): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1064): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1064):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1064): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3163): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3163): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1064): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  239): DCD ON
,D/SSRMv2:SIOP(  740): SIOP:: AP = 300, Delta = 0
,E/SMD     (  239): DCD ON
,E/Watchdog(  740): !@Sync 22
,V/AlarmManager(  740): waitForAlarm result :8
,V/AlarmManager(  740): ClockReceiver onReceive() ACTION_TIME_TICK
,V/AlarmManager(  740): ___SyncScheduler (v3) ACTIVATED___
,V/AlarmManager(  740): <AppSync3 Whitelist>
,D/KeyguardUpdateMonitor( 1064): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1064): handleTimeUpdate
V/AlarmManager(  740): (AppSync) ### 0 added ###
,D/STATUSBAR-IconMerger( 1064): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  239): DCD ON
,D/AmoledAdjustTimer(  740): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,D/BatteryService(  740): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:8, charge type:1, power sharing:false
,D/BatteryService(  740): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  740): stay LED for fully charged
,D/UiModeManager(  740): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1064): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1064): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1064):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1064): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3163): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3163): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1064): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  239): DCD ON
,D/SSRMv2:SIOP(  740): SIOP:: AP = 300, Delta = 0
,E/SMD     (  239): DCD ON
,E/SMD     (  239): DCD ON
,D/AmoledAdjustTimer(  740): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,D/BatteryService(  740): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  740): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  740): mCoverManager.getCoverState() : true
,D/BatteryService(  740): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1064): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1064): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1064):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3163): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3163): Disconnected process message: 10
D/BatteryMeterView( 1064): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1064): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  239): DCD ON
,D/SSRMv2:SIOP(  740): SIOP:: AP = 300, Delta = 0
,E/SMD     (  239): DCD ON
,E/SMD     (  239): DCD ON
,E/SMD     (  239): DCD ON
,D/AmoledAdjustTimer(  740): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,D/BatteryService(  740): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  740): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  740): mCoverManager.getCoverState() : true
,D/BatteryService(  740): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1064): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1064): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1064):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1064): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3163): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3163): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1064): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  239): DCD ON
,D/SSRMv2:SIOP(  740): SIOP:: AP = 300, Delta = 0
,E/SMD     (  239): DCD ON
,E/Watchdog(  740): !@Sync 23
,E/SMD     (  239): DCD ON
,D/AmoledAdjustTimer(  740): prevTemp = 275, currTemp = 274, prevStep = 4, currStep = 4
,D/BatteryService(  740): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:4, charge type:1, power sharing:false
,D/BatteryService(  740): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  740): mCoverManager.getCoverState() : true
,D/BatteryService(  740): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1064): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1064): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1064):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1064): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3163): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3163): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1064): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  239): DCD ON
,D/SSRMv2:SIOP(  740): SIOP:: AP = 300, Delta = 0
,E/SMD     (  239): DCD ON
,E/SMD     (  239): DCD ON
,D/AmoledAdjustTimer(  740): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,E/SMD     (  239): DCD ON
,D/BatteryService(  740): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:3, charge type:1, power sharing:false
,D/BatteryService(  740): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  740): mCoverManager.getCoverState() : true
,D/BatteryService(  740): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1064): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1064): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1064):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1064): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3163): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3163): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1064): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  740): SIOP:: AP = 300, Delta = 0
,E/SMD     (  239): DCD ON
,E/SMD     (  239): DCD ON
,E/SMD     (  239): DCD ON
,D/AmoledAdjustTimer(  740): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,D/BatteryService(  740): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:4, charge type:1, power sharing:false
,D/BatteryService(  740): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  740): mCoverManager.getCoverState() : true
,D/BatteryService(  740): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1064): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1064): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1064):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1064): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3163): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3163): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1064): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  239): DCD ON
,D/SSRMv2:SIOP(  740): SIOP:: AP = 300, Delta = 0
,E/SMD     (  239): DCD ON
,E/Watchdog(  740): !@Sync 24
,V/AlarmManager(  740): waitForAlarm result :8
,V/AlarmManager(  740): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1064): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1064): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1064): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  239): DCD ON
,D/AmoledAdjustTimer(  740): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,I/PowerManagerService(  740): [PWL] Off : 680s ago
,D/BatteryService(  740): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:3, charge type:1, power sharing:false
,D/BatteryService(  740): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  740): stay LED for fully charged
,D/UiModeManager(  740): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1064): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1064): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1064):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1064): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3163): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3163): Disconnected process message: 10
D/STATUSBAR-IconMerger( 1064): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  239): DCD ON
,D/SSRMv2:SIOP(  740): SIOP:: AP = 300, Delta = 0
,E/SMD     (  239): DCD ON
,E/SMD     (  239): DCD ON
,D/AmoledAdjustTimer(  740): prevTemp = 274, currTemp = 275, prevStep = 4, currStep = 4
,E/SMD     (  239): DCD ON
,D/BatteryService(  740): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  740): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  740): stay LED for fully charged
,D/UiModeManager(  740): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1064): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1064): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1064):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1064): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3163): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3163): Disconnected process message: 10
D/STATUSBAR-IconMerger( 1064): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  740): SIOP:: AP = 300, Delta = 0
,E/SMD     (  239): DCD ON
,E/SMD     (  239): DCD ON
,E/SMD     (  239): DCD ON
,D/AmoledAdjustTimer(  740): prevTemp = 275, currTemp = 274, prevStep = 4, currStep = 4
,D/BatteryService(  740): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-4, charge type:1, power sharing:false
,D/BatteryService(  740): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  740): mCoverManager.getCoverState() : true
,D/BatteryService(  740): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1064): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1064): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1064):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1064): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3163): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3163): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1064): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  239): DCD ON
,D/SSRMv2:SIOP(  740): SIOP:: AP = 300, Delta = 0
,E/SMD     (  239): DCD ON
,E/Watchdog(  740): !@Sync 25
,E/SMD     (  239): DCD ON
,D/AmoledAdjustTimer(  740): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,D/BatteryService(  740): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  740): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  740): mCoverManager.getCoverState() : true
,D/BatteryService(  740): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1064): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1064): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1064):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1064): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3163): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3163): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1064): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  239): DCD ON
,D/SSRMv2:SIOP(  740): SIOP:: AP = 300, Delta = 0
,E/SMD     (  239): DCD ON
,E/SMD     (  239): DCD ON
,D/AmoledAdjustTimer(  740): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,E/SMD     (  239): DCD ON
,D/BatteryService(  740): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:2, charge type:1, power sharing:false
,D/BatteryService(  740): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  740): mCoverManager.getCoverState() : true
,D/BatteryService(  740): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1064): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1064): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1064):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1064): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3163): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3163): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1064): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  740): SIOP:: AP = 300, Delta = 0
,E/SMD     (  239): DCD ON
,E/SMD     (  239): DCD ON
,E/SMD     (  239): DCD ON
,D/AmoledAdjustTimer(  740): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,D/BatteryService(  740): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:4, charge type:1, power sharing:false
,D/BatteryService(  740): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  740): mCoverManager.getCoverState() : true
,D/BatteryService(  740): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1064): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1064): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1064):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1064): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3163): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3163): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1064): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  239): DCD ON
,D/SSRMv2:SIOP(  740): SIOP:: AP = 300, Delta = 0
,E/SMD     (  239): DCD ON
,E/Watchdog(  740): !@Sync 26
,V/AlarmManager(  740): waitForAlarm result :8
,V/AlarmManager(  740): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1064): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1064): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1064): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  239): DCD ON
,D/AmoledAdjustTimer(  740): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,D/BatteryService(  740): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:2, charge type:1, power sharing:false
,D/BatteryService(  740): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  740): stay LED for fully charged
,D/UiModeManager(  740): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1064): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1064): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1064):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1064): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3163): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3163): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1064): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  239): DCD ON
,D/SSRMv2:SIOP(  740): SIOP:: AP = 300, Delta = 0
,E/SMD     (  239): DCD ON
,E/SMD     (  239): DCD ON
,D/AmoledAdjustTimer(  740): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,E/SMD     (  239): DCD ON
,D/BatteryService(  740): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:4, charge type:1, power sharing:false
,D/BatteryService(  740): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  740): mCoverManager.getCoverState() : true
,D/BatteryService(  740): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1064): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1064): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1064):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1064): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3163): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3163): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1064): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  740): SIOP:: AP = 300, Delta = 0
,E/SMD     (  239): DCD ON
,E/SMD     (  239): DCD ON
,E/SMD     (  239): DCD ON
,D/AmoledAdjustTimer(  740): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,D/BatteryService(  740): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:3, charge type:1, power sharing:false
,D/BatteryService(  740): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  740): mCoverManager.getCoverState() : true
,D/BatteryService(  740): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1064): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1064): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1064):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1064): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3163): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3163): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1064): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  239): DCD ON
,D/SSRMv2:SIOP(  740): SIOP:: AP = 300, Delta = 0
,I/PowerManagerService(  740): [PWL] Off : 765s ago
,E/SMD     (  239): DCD ON
,E/Watchdog(  740): !@Sync 27
,E/SMD     (  239): DCD ON
,D/AmoledAdjustTimer(  740): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,D/BatteryService(  740): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:4, charge type:1, power sharing:false
,D/BatteryService(  740): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  740): stay LED for fully charged
,D/UiModeManager(  740): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1064): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1064): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1064):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1064): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3163): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3163): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1064): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  239): DCD ON
,D/SSRMv2:SIOP(  740): SIOP:: AP = 300, Delta = 0
,E/SMD     (  239): DCD ON
,E/SMD     (  239): DCD ON
,D/AmoledAdjustTimer(  740): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,E/SMD     (  239): DCD ON
,D/BatteryService(  740): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-2, charge type:1, power sharing:false
,D/BatteryService(  740): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  740): mCoverManager.getCoverState() : true
,D/BatteryService(  740): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1064): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1064): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1064):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1064): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3163): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3163): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1064): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  740): SIOP:: AP = 300, Delta = 0
,E/SMD     (  239): DCD ON
,E/SMD     (  239): DCD ON
,E/SMD     (  239): DCD ON
,D/AmoledAdjustTimer(  740): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,D/BatteryService(  740): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-3, charge type:1, power sharing:false
,D/BatteryService(  740): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  740): stay LED for fully charged
,D/UiModeManager(  740): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1064): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1064): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1064):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1064): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3163): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3163): Disconnected process message: 10
D/STATUSBAR-IconMerger( 1064): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  239): DCD ON
,D/SSRMv2:SIOP(  740): SIOP:: AP = 300, Delta = 0
,E/SMD     (  239): DCD ON
,E/Watchdog(  740): !@Sync 28
,V/AlarmManager(  740): waitForAlarm result :8
,V/AlarmManager(  740): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1064): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1064): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1064): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  239): DCD ON
,D/AmoledAdjustTimer(  740): prevTemp = 274, currTemp = 273, prevStep = 4, currStep = 4
,D/BatteryService(  740): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  740): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  740): stay LED for fully charged
,D/UiModeManager(  740): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1064): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1064): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1064):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1064): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3163): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3163): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1064): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  239): DCD ON
,D/SSRMv2:SIOP(  740): SIOP:: AP = 300, Delta = 0
,E/SMD     (  239): DCD ON
,E/SMD     (  239): DCD ON
,D/AmoledAdjustTimer(  740): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,E/SMD     (  239): DCD ON
,D/BatteryService(  740): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-2, charge type:1, power sharing:false
,D/BatteryService(  740): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  740): mCoverManager.getCoverState() : true
,D/BatteryService(  740): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1064): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1064): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1064):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1064): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3163): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3163): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1064): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  740): SIOP:: AP = 300, Delta = 0
,E/SMD     (  239): DCD ON
,E/SMD     (  239): DCD ON
,E/SMD     (  239): DCD ON
,D/AmoledAdjustTimer(  740): prevTemp = 273, currTemp = 274, prevStep = 4, currStep = 4
,D/BatteryService(  740): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  740): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  740): mCoverManager.getCoverState() : true
,D/BatteryService(  740): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1064): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1064): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1064):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1064): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3163): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3163): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1064): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  239): DCD ON
,D/SSRMv2:SIOP(  740): SIOP:: AP = 300, Delta = 0
,E/SMD     (  239): DCD ON
,E/Watchdog(  740): !@Sync 29
,E/SMD     (  239): DCD ON
,D/AmoledAdjustTimer(  740): prevTemp = 274, currTemp = 273, prevStep = 4, currStep = 4
,D/BatteryService(  740): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-2, charge type:1, power sharing:false
,D/BatteryService(  740): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  740): mCoverManager.getCoverState() : true
,D/BatteryService(  740): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1064): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1064): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1064):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1064): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3163): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3163): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1064): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  239): DCD ON
,D/SSRMv2:SIOP(  740): SIOP:: AP = 300, Delta = 0
,E/SMD     (  239): DCD ON
,E/SMD     (  239): DCD ON
,D/AmoledAdjustTimer(  740): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,E/SMD     (  239): DCD ON
,D/BatteryService(  740): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  740): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  740): stay LED for fully charged
,D/UiModeManager(  740): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1064): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1064): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1064):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1064): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3163): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3163): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1064): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  239): DCD ON
,D/SSRMv2:SIOP(  740): SIOP:: AP = 300, Delta = 0
,E/SMD     (  239): DCD ON
,E/SMD     (  239): DCD ON
,D/AmoledAdjustTimer(  740): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,D/TimaService(  740): TIMA: TimaService scheduler is intialized. 
,D/TimaService(  740): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService(  740): TimaServiceHandler.handleMessage what =1
,E/SMD     (  239): DCD ON
,D/SSRMv2:SIOP(  740): SIOP:: AP = 300, Delta = 0
,I/PowerManagerService(  740): [PWL] Off : 855s ago
,I/PowerManagerService(  740): [PWL]   PowerManagerService.WakeLocks: ref count=1
,I/PowerManagerService(  740): [PWL]     mWakeLockSummary : 0x1
,I/PowerManagerService(  740): [PWL]       PARTIAL_WAKE_LOCK              'TimaService' (uid=1000, pid=740, ws=null) (elapsedTime=3733)
,I/TLC_TIMA_PKM_measure_kernel(  740): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel(  740): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,E/SMD     (  239): DCD ON
D/TimaService(  740): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService(  740): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/Watchdog(  740): !@Sync 30
,V/AlarmManager(  740): waitForAlarm result :8
,V/AlarmManager(  740): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1064): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1064): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1064): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  239): DCD ON
,D/AmoledAdjustTimer(  740): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,E/SMD     (  239): DCD ON
,D/BatteryService(  740): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-3, charge type:1, power sharing:false
,D/BatteryService(  740): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  740): stay LED for fully charged
,D/UiModeManager(  740): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1064): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1064): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1064):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1064): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3163): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3163): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1064): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  740): SIOP:: AP = 300, Delta = 0
,E/SMD     (  239): DCD ON
,E/SMD     (  239): DCD ON
,D/AmoledAdjustTimer(  740): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,E/SMD     (  239): DCD ON
,D/BatteryService(  740): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  740): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  740): mCoverManager.getCoverState() : true
,D/BatteryService(  740): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1064): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1064): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1064):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1064): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3163): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3163): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1064): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  239): DCD ON
,D/SSRMv2:SIOP(  740): SIOP:: AP = 300, Delta = 0
,E/SMD     (  239): DCD ON
,E/SMD     (  239): DCD ON
,D/AmoledAdjustTimer(  740): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,D/BatteryService(  740): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService(  740): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  740): mCoverManager.getCoverState() : true
,D/BatteryService(  740): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1064): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1064): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1064):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1064): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3163): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3163): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1064): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  239): DCD ON
,D/SSRMv2:SIOP(  740): SIOP:: AP = 300, Delta = 0
,E/SMD     (  239): DCD ON
,E/Watchdog(  740): !@Sync 31
,E/SMD     (  239): DCD ON
,D/AmoledAdjustTimer(  740): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,E/SMD     (  239): DCD ON
,D/SSRMv2:SIOP(  740): SIOP:: AP = 300, Delta = 0
,E/SMD     (  239): DCD ON
,E/SMD     (  239): DCD ON
,D/AmoledAdjustTimer(  740): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,E/SMD     (  239): DCD ON
,D/BatteryService(  740): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-2, charge type:1, power sharing:false
,D/BatteryService(  740): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  740): mCoverManager.getCoverState() : true
,D/BatteryService(  740): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1064): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1064): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1064):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1064): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3163): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3163): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1064): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  239): DCD ON
,D/SSRMv2:SIOP(  740): SIOP:: AP = 300, Delta = 0
,E/SMD     (  239): DCD ON
,E/SMD     (  239): DCD ON
,D/AmoledAdjustTimer(  740): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,D/BatteryService(  740): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-1, charge type:1, power sharing:false
,D/BatteryService(  740): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  740): mCoverManager.getCoverState() : true
,D/BatteryService(  740): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1064): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1064): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1064):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1064): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3163): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3163): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1064): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  239): DCD ON
,D/SSRMv2:SIOP(  740): SIOP:: AP = 300, Delta = 0
,E/SMD     (  239): DCD ON
,E/Watchdog(  740): !@Sync 32
,V/AlarmManager(  740): waitForAlarm result :8
,V/AlarmManager(  740): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1064): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1064): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1064): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  239): DCD ON
,D/AmoledAdjustTimer(  740): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,E/SMD     (  239): DCD ON
,D/BatteryService(  740): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-2, charge type:1, power sharing:false
,D/BatteryService(  740): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  740): stay LED for fully charged
,D/UiModeManager(  740): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1064): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1064): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1064):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1064): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3163): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3163): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1064): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  740): SIOP:: AP = 300, Delta = 0
,E/SMD     (  239): DCD ON
,E/SMD     (  239): DCD ON
,D/AmoledAdjustTimer(  740): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,E/SMD     (  239): DCD ON
,D/BatteryService(  740): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService(  740): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  740): mCoverManager.getCoverState() : true
,D/BatteryService(  740): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1064): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1064): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1064):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1064): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3163): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3163): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1064): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  239): DCD ON
,D/SSRMv2:SIOP(  740): SIOP:: AP = 300, Delta = 0
,E/SMD     (  239): DCD ON
,E/SMD     (  239): DCD ON
,D/AmoledAdjustTimer(  740): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,D/dalvikvm(  740): GC_CONCURRENT freed 3458K, 57% free 23573K/54688K, paused 24ms+32ms, total 497ms
,D/BatteryService(  740): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  740): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  740): mCoverManager.getCoverState() : true
,D/BatteryService(  740): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1064): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1064): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1064):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1064): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3163): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3163): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1064): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  239): DCD ON
,D/SSRMv2:SIOP(  740): SIOP:: AP = 300, Delta = 0
,E/SMD     (  239): DCD ON
,E/Watchdog(  740): !@Sync 33
,E/SMD     (  239): DCD ON
,D/AmoledAdjustTimer(  740): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,I/PowerManagerService(  740): [PWL] Off : 950s ago
,E/SMD     (  239): DCD ON
,D/BatteryService(  740): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService(  740): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  740): stay LED for fully charged
,D/UiModeManager(  740): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1064): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1064): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1064):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1064): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3163): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3163): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1064): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  740): SIOP:: AP = 300, Delta = 0
,E/SMD     (  239): DCD ON
,E/SMD     (  239): DCD ON
,D/AmoledAdjustTimer(  740): prevTemp = 273, currTemp = 272, prevStep = 4, currStep = 4
,E/SMD     (  239): DCD ON
,E/SMD     (  239): DCD ON
,D/SSRMv2:SIOP(  740): SIOP:: AP = 300, Delta = 0
,E/SMD     (  239): DCD ON
,E/SMD     (  239): DCD ON
,D/AmoledAdjustTimer(  740): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,V/AlarmManager(  740): waitForAlarm result :4
,D/LightsService(  740): [api] onReceive : SvcLEDReceiver re-enables LightSenor and sends MSG_FORCEDSVCLEDTASK
I/SensorManagerA(  740): getReportingMode :: sensor.mType = 5
D/Sensors (  740): LightSensor setDelay = 200000000
,D/Sensors (  740): LightSensor setSensorDelay = 200000000
,D/Sensors (  740): Light sensor flush: not enabled 0
,D/Sensors (  740): LightSensor enable = 1
,D/Sensors (  740): LightSensor enableSensor = 1
,D/SensorManager(  740): registerListener :: 16, CM36686 Light Sensor, 200000, 0,  
,V/AlarmManager(  740): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,V/AlarmManager(  740): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,D/BatteryService(  740): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:2, charge type:1, power sharing:false
,D/BatteryService(  740): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  740): stay LED for fully charged
,D/UiModeManager(  740): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1064): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1064): handleBatteryUpdate
,V/HeadsetService( 3163): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/STATUSBAR-PhoneStatusBar( 1064):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/HeadsetStateMachine( 3163): Disconnected process message: 10
D/BatteryMeterView( 1064): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1064): checkOverflow(288), More:false, Req:false Child:2
,D/Sensors (  740): LightSensor enable = 0
,D/Sensors (  740): LightSensor enableSensor = 0
,D/SensorManager(  740): unregisterListener ::   
D/LightsService(  740): [SvcLED]  onSensorChanged::light value = 54
D/LightsService(  740): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,I/EventLogService( 1795): Aggregate from 1449830854462 (log), 1449830854462 (data)
,E/SMD     (  239): DCD ON
,D/ConnectivityService(  740): handleInetConditionHoldEnd: net=1, condition=100, published condition=100
,D/STATUSBAR-NetworkController_dual( 1064): onReceive() - CONNECTIVITY_ACTION, INET_CONDITION_ACTION
,D/StatusBar.NetworkController_dual( 1064): mMobileLabelViews start
,D/StatusBar.NetworkController_dual( 1064): mMobileLabelViews set mobileLabel[SIM_0] =
D/StatusBar.NetworkController_dual( 1064): mMobileLabelViews GONE
,D/StatusBar.NetworkController_dual( 1064): mMobileLabelViews2 set mobileLabel[SIM_1] =
,D/StatusBar.NetworkController_dual( 1064): mMobileLabelViews2 GONE
,D/StatusBar.NetworkController_dual( 1064): mSingleMobileLabelViews set : simMode = 0
,D/StatusBar.NetworkController_dual( 1064): mSingleMobileLabelViews set as slot1`s
,D/dalvikvm( 1795): GC_CONCURRENT freed 1548K, 35% free 12488K/18944K, paused 9ms+10ms, total 82ms
,D/SSRMv2:SIOP(  740): SIOP:: AP = 300, Delta = 0
,E/SMD     (  239): DCD ON
,E/Watchdog(  740): !@Sync 34
,V/AlarmManager(  740): waitForAlarm result :8
,V/AlarmManager(  740): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1064): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1064): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1064): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  239): DCD ON
,D/AmoledAdjustTimer(  740): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,E/SMD     (  239): DCD ON
,D/BatteryService(  740): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  740): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  740): mCoverManager.getCoverState() : true
,D/BatteryService(  740): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1064): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1064): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1064):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1064): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3163): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3163): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1064): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  740): SIOP:: AP = 300, Delta = 0
,E/SMD     (  239): DCD ON
,E/SMD     (  239): DCD ON
,D/AmoledAdjustTimer(  740): prevTemp = 272, currTemp = 273, prevStep = 4, currStep = 4
,E/SMD     (  239): DCD ON
,D/BatteryService(  740): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-2, charge type:1, power sharing:false
,D/BatteryService(  740): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  740): mCoverManager.getCoverState() : true
,D/BatteryService(  740): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1064): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1064): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1064):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1064): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3163): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3163): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1064): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  239): DCD ON
,D/SSRMv2:SIOP(  740): SIOP:: AP = 300, Delta = 0
,E/SMD     (  239): DCD ON
,E/SMD     (  239): DCD ON
,D/AmoledAdjustTimer(  740): prevTemp = 273, currTemp = 272, prevStep = 4, currStep = 4
,D/BatteryService(  740): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  740): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  740): stay LED for fully charged
,D/UiModeManager(  740): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1064): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1064): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1064):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1064): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3163): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3163): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1064): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  239): DCD ON
,D/SSRMv2:SIOP(  740): SIOP:: AP = 300, Delta = 0
,E/SMD     (  239): DCD ON
,E/Watchdog(  740): !@Sync 35
,E/SMD     (  239): DCD ON
,D/AmoledAdjustTimer(  740): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,E/SMD     (  239): DCD ON
,D/BatteryService(  740): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-1, charge type:1, power sharing:false
,D/BatteryService(  740): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  740): mCoverManager.getCoverState() : true
,D/BatteryService(  740): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1064): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1064): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1064):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1064): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3163): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3163): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1064): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  740): SIOP:: AP = 300, Delta = 0
,E/SMD     (  239): DCD ON
,E/SMD     (  239): DCD ON
,D/AmoledAdjustTimer(  740): prevTemp = 272, currTemp = 273, prevStep = 4, currStep = 4
,E/SMD     (  239): DCD ON
,D/BatteryService(  740): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  740): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  740): mCoverManager.getCoverState() : true
,D/BatteryService(  740): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1064): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1064): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1064):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1064): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3163): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3163): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1064): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  239): DCD ON
,D/SSRMv2:SIOP(  740): SIOP:: AP = 300, Delta = 0
,E/SMD     (  239): DCD ON
,E/SMD     (  239): DCD ON
,D/AmoledAdjustTimer(  740): prevTemp = 273, currTemp = 272, prevStep = 4, currStep = 4
,D/BatteryService(  740): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-1, charge type:1, power sharing:false
,D/BatteryService(  740): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  740): mCoverManager.getCoverState() : true
,D/BatteryService(  740): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1064): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1064): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1064):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1064): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3163): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3163): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1064): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  239): DCD ON
,D/SSRMv2:SIOP(  740): SIOP:: AP = 300, Delta = 0
,E/SMD     (  239): DCD ON
,E/Watchdog(  740): !@Sync 36
,V/AlarmManager(  740): waitForAlarm result :8
,V/AlarmManager(  740): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1064): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1064): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1064): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  239): DCD ON
,D/AmoledAdjustTimer(  740): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,E/SMD     (  239): DCD ON
,D/BatteryService(  740): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  740): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  740): mCoverManager.getCoverState() : true
,D/BatteryService(  740): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1064): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1064): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1064):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1064): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3163): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3163): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1064): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  740): SIOP:: AP = 300, Delta = 0
,E/SMD     (  239): DCD ON
,E/SMD     (  239): DCD ON
,I/PowerManagerService(  740): [PWL] Off : 1050s ago
,D/AmoledAdjustTimer(  740): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,E/SMD     (  239): DCD ON
,D/BatteryService(  740): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-1, charge type:1, power sharing:false
,D/BatteryService(  740): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  740): mCoverManager.getCoverState() : true
,D/BatteryService(  740): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1064): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1064): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1064):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1064): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3163): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3163): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1064): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  239): DCD ON
,D/SSRMv2:SIOP(  740): SIOP:: AP = 300, Delta = 0
,E/SMD     (  239): DCD ON
,E/SMD     (  239): DCD ON
,D/AmoledAdjustTimer(  740): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,D/BatteryService(  740): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  740): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  740): stay LED for fully charged
,D/UiModeManager(  740): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1064): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1064): handleBatteryUpdate
,E/SMD     (  239): DCD ON
D/STATUSBAR-PhoneStatusBar( 1064):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
D/BatteryMeterView( 1064): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3163): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3163): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1064): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  740): SIOP:: AP = 300, Delta = 0
,E/SMD     (  239): DCD ON
,E/Watchdog(  740): !@Sync 37
,E/SMD     (  239): DCD ON
,D/AmoledAdjustTimer(  740): prevTemp = 272, currTemp = 273, prevStep = 4, currStep = 4
,E/SMD     (  239): DCD ON
,D/BatteryService(  740): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  740): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  740): stay LED for fully charged
,D/UiModeManager(  740): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1064): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1064): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1064):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1064): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 3163): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 3163): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1064): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  740): SIOP:: AP = 300, Delta = 0
,E/SMD     (  239): DCD ON
,E/SMD     (  239): DCD ON
,D/AmoledAdjustTimer(  740): prevTemp = 273, currTemp = 272, prevStep = 4, currStep = 4
,E/SMD     (  239): DCD ON
,E/SMD     (  239): DCD ON
,D/SSRMv2:SIOP(  740): SIOP:: AP = 300, Delta = 0
,E/SMD     (  239): DCD ON
,E/SMD     (  239): DCD ON
,D/AmoledAdjustTimer(  740): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,E/SMD     (  239): DCD ON
,D/SSRMv2:SIOP(  740): SIOP:: AP = 300, Delta = 0
,E/SMD     (  239): DCD ON
,E/Watchdog(  740): !@Sync 38
,V/AlarmManager(  740): waitForAlarm result :8
,V/AlarmManager(  740): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1064): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1064): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1064): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  239): DCD ON
,D/AmoledAdjustTimer(  740): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,E/SMD     (  239): DCD ON
,D/SSRMv2:SIOP(  740): SIOP:: AP = 300, Delta = 0
,E/SMD     (  239): DCD ON
,E/SMD     (  239): DCD ON
,D/AmoledAdjustTimer(  740): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,E/SMD     (  239): DCD ON
,D/BatteryService(  740): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:2, charge type:1, power sharing:false
,D/BatteryService(  740): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  740): stay LED for fully charged
,D/UiModeManager(  740): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1064): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1064): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1064):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1064): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3163): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3163): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1064): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  239): DCD ON
,D/SSRMv2:SIOP(  740): SIOP:: AP = 300, Delta = 0
,E/SMD     (  239): DCD ON
,E/SMD     (  239): DCD ON
,D/AmoledAdjustTimer(  740): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,E/SMD     (  239): DCD ON
,D/BatteryService(  740): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService(  740): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  740): mCoverManager.getCoverState() : true
,D/BatteryService(  740): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1064): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1064): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1064):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1064): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3163): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3163): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1064): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  740): SIOP:: AP = 300, Delta = 0
,E/SMD     (  239): DCD ON
,E/Watchdog(  740): !@Sync 39
,E/SMD     (  239): DCD ON
,D/AmoledAdjustTimer(  740): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,E/SMD     (  239): DCD ON
,D/BatteryService(  740): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  740): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  740): stay LED for fully charged
,D/UiModeManager(  740): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1064): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1064): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1064):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1064): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3163): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3163): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1064): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  740): SIOP:: AP = 300, Delta = 0
,E/SMD     (  239): DCD ON
,E/SMD     (  239): DCD ON
,D/AmoledAdjustTimer(  740): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,E/SMD     (  239): DCD ON
,D/BatteryService(  740): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-2, charge type:1, power sharing:false
,D/BatteryService(  740): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  740): mCoverManager.getCoverState() : true
,D/BatteryService(  740): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1064): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1064): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1064):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1064): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3163): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3163): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1064): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  239): DCD ON
,D/SSRMv2:SIOP(  740): SIOP:: AP = 300, Delta = 0
,E/SMD     (  239): DCD ON
,E/SMD     (  239): DCD ON
,D/AmoledAdjustTimer(  740): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,D/TimaService(  740): TIMA: TimaService scheduler is intialized. 
,D/TimaService(  740): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService(  740): TimaServiceHandler.handleMessage what =1
,E/SMD     (  239): DCD ON
,D/SSRMv2:SIOP(  740): SIOP:: AP = 300, Delta = 0
,I/PowerManagerService(  740): [PWL] Off : 1155s ago
,I/PowerManagerService(  740): [PWL]   PowerManagerService.WakeLocks: ref count=1
,I/PowerManagerService(  740): [PWL]     mWakeLockSummary : 0x1
,I/PowerManagerService(  740): [PWL]       PARTIAL_WAKE_LOCK              'TimaService' (uid=1000, pid=740, ws=null) (elapsedTime=3744)
,I/TLC_TIMA_PKM_measure_kernel(  740): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel(  740): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService(  740): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService(  740): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/SMD     (  239): DCD ON
,E/Watchdog(  740): !@Sync 40
,V/AlarmManager(  740): waitForAlarm result :8
,V/AlarmManager(  740): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1064): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1064): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1064): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  239): DCD ON
,D/AmoledAdjustTimer(  740): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,E/SMD     (  239): DCD ON
,D/BatteryService(  740): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  740): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  740): stay LED for fully charged
,D/UiModeManager(  740): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1064): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1064): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1064):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1064): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3163): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3163): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1064): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  740): SIOP:: AP = 300, Delta = 0
,E/SMD     (  239): DCD ON
,E/SMD     (  239): DCD ON
,D/AmoledAdjustTimer(  740): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,E/SMD     (  239): DCD ON
,E/SMD     (  239): DCD ON
,D/SSRMv2:SIOP(  740): SIOP:: AP = 300, Delta = 0
,E/SMD     (  239): DCD ON
,E/SMD     (  239): DCD ON
,D/AmoledAdjustTimer(  740): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,E/SMD     (  239): DCD ON
,D/BatteryService(  740): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-5, charge type:1, power sharing:false
,D/BatteryService(  740): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  740): mCoverManager.getCoverState() : true
,D/BatteryService(  740): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1064): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1064): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1064):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3163): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3163): Disconnected process message: 10
D/BatteryMeterView( 1064): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1064): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  740): SIOP:: AP = 300, Delta = 0
,E/SMD     (  239): DCD ON
,E/Watchdog(  740): !@Sync 41
,E/SMD     (  239): DCD ON
,D/AmoledAdjustTimer(  740): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,E/SMD     (  239): DCD ON
,D/BatteryService(  740): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService(  740): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  740): mCoverManager.getCoverState() : true
,D/BatteryService(  740): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1064): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1064): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1064):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1064): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3163): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3163): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1064): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  239): DCD ON
,D/SSRMv2:SIOP(  740): SIOP:: AP = 300, Delta = 0
,E/SMD     (  239): DCD ON
,D/AmoledAdjustTimer(  740): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,E/SMD     (  239): DCD ON
,E/SMD     (  239): DCD ON
,D/SSRMv2:SIOP(  740): SIOP:: AP = 300, Delta = 0
,E/SMD     (  239): DCD ON
,E/SMD     (  239): DCD ON
,D/AmoledAdjustTimer(  740): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,E/SMD     (  239): DCD ON
,D/BatteryService(  740): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:2, charge type:1, power sharing:false
,D/BatteryService(  740): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  740): mCoverManager.getCoverState() : true
,D/BatteryService(  740): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1064): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1064): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1064):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1064): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3163): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3163): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1064): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  740): SIOP:: AP = 300, Delta = 0
,E/SMD     (  239): DCD ON
,E/Watchdog(  740): !@Sync 42
,V/AlarmManager(  740): waitForAlarm result :8
,V/AlarmManager(  740): ClockReceiver onReceive() ACTION_TIME_TICK
,V/AlarmManager(  740): ___SyncScheduler (v3) ACTIVATED___
,V/AlarmManager(  740): <AppSync3 Whitelist>
,D/KeyguardUpdateMonitor( 1064): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1064): handleTimeUpdate
V/AlarmManager(  740): (AppSync) ### 0 added ###
,D/STATUSBAR-IconMerger( 1064): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  239): DCD ON
,D/AmoledAdjustTimer(  740): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,E/SMD     (  239): DCD ON
,D/BatteryService(  740): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-1, charge type:1, power sharing:false
,D/BatteryService(  740): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  740): stay LED for fully charged
,D/UiModeManager(  740): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1064): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1064): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1064):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1064): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 3163): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 3163): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1064): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  239): DCD ON
,D/SSRMv2:SIOP(  740): SIOP:: AP = 300, Delta = 0
,E/SMD     (  239): DCD ON
,D/AmoledAdjustTimer(  740): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,E/SMD     (  239): DCD ON
,D/BatteryService(  740): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-2, charge type:1, power sharing:false
,D/BatteryService(  740): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  740): mCoverManager.getCoverState() : true
,D/BatteryService(  740): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1064): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1064): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1064):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1064): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3163): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3163): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1064): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  239): DCD ON
,D/SSRMv2:SIOP(  740): SIOP:: AP = 300, Delta = 0
,E/SMD     (  239): DCD ON
,E/SMD     (  239): DCD ON
,D/AmoledAdjustTimer(  740): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,E/SMD     (  239): DCD ON
,D/BatteryService(  740): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-4, charge type:1, power sharing:false
,D/BatteryService(  740): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  740): stay LED for fully charged
,D/UiModeManager(  740): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1064): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1064): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1064):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1064): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3163): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3163): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1064): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  740): SIOP:: AP = 300, Delta = 0
,E/SMD     (  239): DCD ON
,E/Watchdog(  740): !@Sync 43
,E/SMD     (  239): DCD ON
,D/AmoledAdjustTimer(  740): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,E/SMD     (  239): DCD ON
,D/BatteryService(  740): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  740): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  740): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1064): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1064): handleBatteryUpdate
,D/UiModeManager(  740): mCoverManager.getCoverState() : true
,D/STATUSBAR-PhoneStatusBar( 1064):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1064): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3163): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3163): Disconnected process message: 10
D/STATUSBAR-IconMerger( 1064): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  239): DCD ON
,D/SSRMv2:SIOP(  740): SIOP:: AP = 300, Delta = 0
,E/SMD     (  239): DCD ON
,D/AmoledAdjustTimer(  740): prevTemp = 272, currTemp = 271, prevStep = 4, currStep = 4
,E/SMD     (  239): DCD ON
,D/BatteryService(  740): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  740): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  740): stay LED for fully charged
,D/UiModeManager(  740): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1064): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1064): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1064):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1064): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  239): DCD ON
,V/HeadsetService( 3163): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3163): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1064): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  740): SIOP:: AP = 300, Delta = 0
,I/PowerManagerService(  740): [PWL] Off : 1265s ago
,E/SMD     (  239): DCD ON
,E/SMD     (  239): DCD ON
,D/AmoledAdjustTimer(  740): prevTemp = 271, currTemp = 272, prevStep = 4, currStep = 4
,E/SMD     (  239): DCD ON
,D/BatteryService(  740): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  740): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  740): mCoverManager.getCoverState() : true
,D/BatteryService(  740): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1064): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1064): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1064):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1064): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3163): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3163): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1064): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  740): SIOP:: AP = 300, Delta = 0
,E/SMD     (  239): DCD ON
,E/Watchdog(  740): !@Sync 44
,V/AlarmManager(  740): waitForAlarm result :8
,V/AlarmManager(  740): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1064): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1064): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1064): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  239): DCD ON
,D/AmoledAdjustTimer(  740): prevTemp = 272, currTemp = 271, prevStep = 4, currStep = 4
,E/SMD     (  239): DCD ON
,E/SMD     (  239): DCD ON
,D/SSRMv2:SIOP(  740): SIOP:: AP = 300, Delta = 0
,E/SMD     (  239): DCD ON
,D/AmoledAdjustTimer(  740): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,E/SMD     (  239): DCD ON
,E/SMD     (  239): DCD ON
,D/SSRMv2:SIOP(  740): SIOP:: AP = 300, Delta = 0
,E/SMD     (  239): DCD ON
,E/SMD     (  239): DCD ON
,D/AmoledAdjustTimer(  740): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,E/SMD     (  239): DCD ON
,D/BatteryService(  740): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-2, charge type:1, power sharing:false
,D/BatteryService(  740): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  740): stay LED for fully charged
,D/UiModeManager(  740): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1064): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1064): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1064):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1064): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3163): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3163): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1064): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  740): SIOP:: AP = 300, Delta = 0
,E/SMD     (  239): DCD ON
,E/Watchdog(  740): !@Sync 45
,E/SMD     (  239): DCD ON
,D/AmoledAdjustTimer(  740): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,E/SMD     (  239): DCD ON
,D/BatteryService(  740): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  740): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  740): mCoverManager.getCoverState() : true
,D/BatteryService(  740): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1064): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1064): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1064):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1064): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3163): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3163): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1064): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  239): DCD ON
,D/SSRMv2:SIOP(  740): SIOP:: AP = 300, Delta = 0
,E/SMD     (  239): DCD ON
,D/AmoledAdjustTimer(  740): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,E/SMD     (  239): DCD ON
,E/SMD     (  239): DCD ON
,D/SSRMv2:SIOP(  740): SIOP:: AP = 300, Delta = 0
,E/SMD     (  239): DCD ON
,E/SMD     (  239): DCD ON
,D/AmoledAdjustTimer(  740): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,E/SMD     (  239): DCD ON
,D/SSRMv2:SIOP(  740): SIOP:: AP = 300, Delta = 0
,E/SMD     (  239): DCD ON
,E/Watchdog(  740): !@Sync 46
,V/AlarmManager(  740): waitForAlarm result :8
,V/AlarmManager(  740): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1064): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1064): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1064): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  239): DCD ON
,D/AmoledAdjustTimer(  740): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,E/SMD     (  239): DCD ON
,E/SMD     (  239): DCD ON
,D/SSRMv2:SIOP(  740): SIOP:: AP = 300, Delta = 0
,E/SMD     (  239): DCD ON
,D/AmoledAdjustTimer(  740): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,E/SMD     (  239): DCD ON
,E/SMD     (  239): DCD ON
,D/SSRMv2:SIOP(  740): SIOP:: AP = 300, Delta = 0
,D/dalvikvm(  740): GC_CONCURRENT freed 3370K, 57% free 23630K/54688K, paused 24ms+49ms, total 557ms
,E/SMD     (  239): DCD ON
,E/SMD     (  239): DCD ON
,D/AmoledAdjustTimer(  740): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,E/SMD     (  239): DCD ON
,D/BatteryService(  740): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-3, charge type:1, power sharing:false
,D/BatteryService(  740): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  740): mCoverManager.getCoverState() : true
,D/BatteryService(  740): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1064): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1064): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1064):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1064): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3163): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3163): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1064): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  740): SIOP:: AP = 300, Delta = 0
,E/SMD     (  239): DCD ON
,E/Watchdog(  740): !@Sync 47
,E/SMD     (  239): DCD ON
,D/AmoledAdjustTimer(  740): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,E/SMD     (  239): DCD ON
,D/BatteryService(  740): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:3, charge type:1, power sharing:false
,D/BatteryService(  740): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  740): mCoverManager.getCoverState() : true
,D/BatteryService(  740): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1064): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1064): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1064):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1064): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3163): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3163): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1064): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  239): DCD ON
,D/SSRMv2:SIOP(  740): SIOP:: AP = 300, Delta = 0
,E/SMD     (  239): DCD ON
,I/PowerManagerService(  740): [PWL] Off : 1380s ago
,D/AmoledAdjustTimer(  740): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,E/SMD     (  239): DCD ON
,E/SMD     (  239): DCD ON
,D/BatteryService(  740): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:4, charge type:1, power sharing:false
,D/BatteryService(  740): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  740): stay LED for fully charged
,D/UiModeManager(  740): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1064): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1064): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1064):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1064): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3163): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3163): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1064): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  740): SIOP:: AP = 300, Delta = 0
,E/SMD     (  239): DCD ON
,E/SMD     (  239): DCD ON
,D/AmoledAdjustTimer(  740): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,E/SMD     (  239): DCD ON
,D/BatteryService(  740): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:4, charge type:1, power sharing:false
,D/BatteryService(  740): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  740): mCoverManager.getCoverState() : true
,D/BatteryService(  740): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1064): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1064): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1064):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1064): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3163): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3163): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1064): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  740): SIOP:: AP = 300, Delta = 0
,E/SMD     (  239): DCD ON
,E/Watchdog(  740): !@Sync 48
,V/AlarmManager(  740): waitForAlarm result :8
,V/AlarmManager(  740): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1064): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1064): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1064): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  239): DCD ON
,D/AmoledAdjustTimer(  740): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,E/SMD     (  239): DCD ON
,D/BatteryService(  740): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService(  740): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  740): mCoverManager.getCoverState() : true
,D/BatteryService(  740): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1064): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1064): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1064):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1064): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3163): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3163): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1064): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  239): DCD ON
,D/SSRMv2:SIOP(  740): SIOP:: AP = 300, Delta = 0
,E/SMD     (  239): DCD ON
,D/AmoledAdjustTimer(  740): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,E/SMD     (  239): DCD ON
,E/SMD     (  239): DCD ON
,D/BatteryService(  740): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:9, charge type:1, power sharing:false
,D/BatteryService(  740): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  740): mCoverManager.getCoverState() : true
,D/BatteryService(  740): stay LED for fully charged
D/KeyguardUpdateMonitor( 1064): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1064): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1064):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1064): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3163): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3163): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1064): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  740): SIOP:: AP = 300, Delta = 0
,E/SMD     (  239): DCD ON
,E/SMD     (  239): DCD ON
,D/AmoledAdjustTimer(  740): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,E/SMD     (  239): DCD ON
,D/BatteryService(  740): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:3, charge type:1, power sharing:false
,D/BatteryService(  740): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  740): mCoverManager.getCoverState() : true
,D/BatteryService(  740): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1064): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1064): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1064):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1064): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3163): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3163): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1064): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  740): SIOP:: AP = 300, Delta = 0
,E/SMD     (  239): DCD ON
,E/Watchdog(  740): !@Sync 49
,E/SMD     (  239): DCD ON
,D/AmoledAdjustTimer(  740): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,E/SMD     (  239): DCD ON
,D/BatteryService(  740): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-3, charge type:1, power sharing:false
,D/BatteryService(  740): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  740): mCoverManager.getCoverState() : true
,D/BatteryService(  740): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1064): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1064): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1064):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1064): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3163): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3163): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1064): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  239): DCD ON
,D/SSRMv2:SIOP(  740): SIOP:: AP = 300, Delta = 0
,E/SMD     (  239): DCD ON
,D/AmoledAdjustTimer(  740): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,E/SMD     (  239): DCD ON
,E/SMD     (  239): DCD ON
,D/BatteryService(  740): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-3, charge type:1, power sharing:false
,D/BatteryService(  740): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  740): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1064): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1064): handleBatteryUpdate
D/BatteryService(  740): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1064):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1064): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3163): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3163): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1064): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  740): SIOP:: AP = 300, Delta = 0
,E/SMD     (  239): DCD ON
,E/SMD     (  239): DCD ON
,D/AmoledAdjustTimer(  740): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,D/TimaService(  740): TIMA: TimaService scheduler is intialized. 
,D/TimaService(  740): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService(  740): TimaServiceHandler.handleMessage what =1
,E/SMD     (  239): DCD ON
,D/BatteryService(  740): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-1, charge type:1, power sharing:false
,D/BatteryService(  740): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  740): stay LED for fully charged
,D/UiModeManager(  740): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1064): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1064): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1064):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1064): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1064): checkOverflow(288), More:false, Req:false Child:2
V/HeadsetService( 3163): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 3163): Disconnected process message: 10
,I/TLC_TIMA_PKM_measure_kernel(  740): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel(  740): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService(  740): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService(  740): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/SSRMv2:SIOP(  740): SIOP:: AP = 300, Delta = 0
,E/SMD     (  239): DCD ON
,E/Watchdog(  740): !@Sync 50
,V/AlarmManager(  740): waitForAlarm result :8
,V/AlarmManager(  740): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1064): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1064): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1064): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  239): DCD ON
,D/AmoledAdjustTimer(  740): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,E/SMD     (  239): DCD ON
,D/BatteryService(  740): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:3, charge type:1, power sharing:false
,D/BatteryService(  740): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  740): stay LED for fully charged
,D/UiModeManager(  740): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1064): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1064): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1064):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1064): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3163): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3163): Disconnected process message: 10
,E/SMD     (  239): DCD ON
D/STATUSBAR-IconMerger( 1064): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  740): SIOP:: AP = 300, Delta = 0
,E/SMD     (  239): DCD ON
,D/AmoledAdjustTimer(  740): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,E/SMD     (  239): DCD ON
,E/SMD     (  239): DCD ON
,D/BatteryService(  740): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  740): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  740): stay LED for fully charged
,D/UiModeManager(  740): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1064): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1064): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1064):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1064): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3163): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3163): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1064): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  740): SIOP:: AP = 300, Delta = 0
,E/SMD     (  239): DCD ON
,E/SMD     (  239): DCD ON
,D/AmoledAdjustTimer(  740): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,E/SMD     (  239): DCD ON
,D/SSRMv2:SIOP(  740): SIOP:: AP = 300, Delta = 0
,E/SMD     (  239): DCD ON
,E/Watchdog(  740): !@Sync 51
,E/SMD     (  239): DCD ON
,D/AmoledAdjustTimer(  740): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,E/SMD     (  239): DCD ON
,E/SMD     (  239): DCD ON
,D/BatteryService(  740): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-2, charge type:1, power sharing:false
,D/BatteryService(  740): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  740): mCoverManager.getCoverState() : true
,D/BatteryService(  740): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1064): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1064): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1064):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1064): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3163): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3163): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1064): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  740): SIOP:: AP = 300, Delta = 0
,E/SMD     (  239): DCD ON
,I/PowerManagerService(  740): [PWL] Off : 1500s ago
,D/AmoledAdjustTimer(  740): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,E/SMD     (  239): DCD ON
,E/SMD     (  239): DCD ON
,D/BatteryService(  740): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-4, charge type:1, power sharing:false
,D/BatteryService(  740): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  740): stay LED for fully charged
,D/UiModeManager(  740): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1064): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1064): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1064):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1064): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3163): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3163): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1064): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  740): SIOP:: AP = 300, Delta = 0
,E/SMD     (  239): DCD ON
,E/SMD     (  239): DCD ON
,D/AmoledAdjustTimer(  740): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,E/SMD     (  239): DCD ON
,D/SSRMv2:SIOP(  740): SIOP:: AP = 300, Delta = 0
,E/SMD     (  239): DCD ON
,E/Watchdog(  740): !@Sync 52
,V/AlarmManager(  740): waitForAlarm result :8
,V/AlarmManager(  740): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1064): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1064): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1064): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  239): DCD ON
,D/AmoledAdjustTimer(  740): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,E/SMD     (  239): DCD ON
,E/SMD     (  239): DCD ON
,D/BatteryService(  740): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:2, charge type:1, power sharing:false
,D/BatteryService(  740): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  740): stay LED for fully charged
,D/UiModeManager(  740): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1064): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1064): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1064):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1064): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3163): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3163): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1064): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  740): SIOP:: AP = 300, Delta = 0
,E/SMD     (  239): DCD ON
,D/AmoledAdjustTimer(  740): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,E/SMD     (  239): DCD ON
,E/SMD     (  239): DCD ON
,D/BatteryService(  740): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService(  740): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  740): stay LED for fully charged
,D/UiModeManager(  740): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1064): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1064): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1064):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1064): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3163): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3163): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1064): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  740): SIOP:: AP = 300, Delta = 0
,E/SMD     (  239): DCD ON
,E/SMD     (  239): DCD ON
,D/AmoledAdjustTimer(  740): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,E/SMD     (  239): DCD ON
,D/BatteryService(  740): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:4, charge type:1, power sharing:false
,D/BatteryService(  740): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  740): stay LED for fully charged
,D/UiModeManager(  740): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1064): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1064): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1064):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1064): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3163): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3163): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1064): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  239): DCD ON
,D/SSRMv2:SIOP(  740): SIOP:: AP = 300, Delta = 0
,E/Watchdog(  740): !@Sync 53
,E/SMD     (  239): DCD ON
,D/AmoledAdjustTimer(  740): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,E/SMD     (  239): DCD ON
,E/SMD     (  239): DCD ON
,D/BatteryService(  740): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-2, charge type:1, power sharing:false
,D/BatteryService(  740): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  740): mCoverManager.getCoverState() : true
,D/BatteryService(  740): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1064): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1064): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1064):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1064): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3163): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3163): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1064): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  740): SIOP:: AP = 300, Delta = 0
,E/SMD     (  239): DCD ON
,D/AmoledAdjustTimer(  740): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,E/SMD     (  239): DCD ON
,E/SMD     (  239): DCD ON
,D/BatteryService(  740): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-1, charge type:1, power sharing:false
,D/BatteryService(  740): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  740): stay LED for fully charged
,D/UiModeManager(  740): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1064): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1064): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1064):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1064): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3163): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3163): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1064): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  740): SIOP:: AP = 300, Delta = 0
,E/SMD     (  239): DCD ON
,E/SMD     (  239): DCD ON
,D/AmoledAdjustTimer(  740): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,E/SMD     (  239): DCD ON
,D/BatteryService(  740): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-5, charge type:1, power sharing:false
,D/BatteryService(  740): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  740): mCoverManager.getCoverState() : true
,D/BatteryService(  740): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1064): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1064): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1064):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1064): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3163): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3163): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1064): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  239): DCD ON
,D/SSRMv2:SIOP(  740): SIOP:: AP = 300, Delta = 0
,E/Watchdog(  740): !@Sync 54
,V/AlarmManager(  740): waitForAlarm result :8
,V/AlarmManager(  740): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1064): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1064): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1064): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  239): DCD ON
,D/AmoledAdjustTimer(  740): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,E/SMD     (  239): DCD ON
,E/SMD     (  239): DCD ON
,D/BatteryService(  740): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService(  740): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  740): mCoverManager.getCoverState() : true
,D/BatteryService(  740): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1064): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1064): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1064):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1064): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3163): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3163): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1064): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  740): SIOP:: AP = 300, Delta = 0
,E/SMD     (  239): DCD ON
,D/AmoledAdjustTimer(  740): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,E/SMD     (  239): DCD ON
,E/SMD     (  239): DCD ON
,D/BatteryService(  740): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:3, charge type:1, power sharing:false
,D/BatteryService(  740): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  740): mCoverManager.getCoverState() : true
,D/BatteryService(  740): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1064): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1064): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1064):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1064): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3163): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3163): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1064): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  740): SIOP:: AP = 300, Delta = 0
,E/SMD     (  239): DCD ON
,E/SMD     (  239): DCD ON
,D/AmoledAdjustTimer(  740): prevTemp = 271, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  239): DCD ON
,D/BatteryService(  740): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:2, charge type:1, power sharing:false
,D/BatteryService(  740): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  740): mCoverManager.getCoverState() : true
,D/BatteryService(  740): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1064): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1064): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1064):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1064): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3163): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3163): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1064): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  239): DCD ON
,D/SSRMv2:SIOP(  740): SIOP:: AP = 300, Delta = 0
,E/Watchdog(  740): !@Sync 55
,E/SMD     (  239): DCD ON
,D/AmoledAdjustTimer(  740): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  239): DCD ON
,E/SMD     (  239): DCD ON
,D/BatteryService(  740): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-3, charge type:1, power sharing:false
,D/BatteryService(  740): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  740): stay LED for fully charged
,D/UiModeManager(  740): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1064): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1064): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1064):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1064): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3163): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3163): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1064): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  740): SIOP:: AP = 300, Delta = 0
,E/SMD     (  239): DCD ON
,E/SMD     (  239): DCD ON
D/AmoledAdjustTimer(  740): prevTemp = 270, currTemp = 271, prevStep = 4, currStep = 4
,E/SMD     (  239): DCD ON
,I/PowerManagerService(  740): [PWL] Off : 1625s ago
,D/BatteryService(  740): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-4, charge type:1, power sharing:false
,D/BatteryService(  740): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  740): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1064): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1064): handleBatteryUpdate
D/BatteryService(  740): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1064):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1064): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3163): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3163): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1064): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  740): SIOP:: AP = 300, Delta = 0
,E/SMD     (  239): DCD ON
,E/SMD     (  239): DCD ON
,D/AmoledAdjustTimer(  740): prevTemp = 271, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  239): DCD ON
,D/BatteryService(  740): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-7, charge type:1, power sharing:false
,D/BatteryService(  740): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  740): mCoverManager.getCoverState() : true
,D/BatteryService(  740): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1064): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1064): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1064):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3163): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/BatteryMeterView( 1064): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/HeadsetStateMachine( 3163): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1064): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  239): DCD ON
,D/SSRMv2:SIOP(  740): SIOP:: AP = 300, Delta = 0
,E/Watchdog(  740): !@Sync 56
,V/AlarmManager(  740): waitForAlarm result :8
,V/AlarmManager(  740): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1064): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1064): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1064): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  239): DCD ON
,D/AmoledAdjustTimer(  740): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  239): DCD ON
,E/SMD     (  239): DCD ON
,D/BatteryService(  740): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-3, charge type:1, power sharing:false
,D/BatteryService(  740): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  740): mCoverManager.getCoverState() : true
,D/BatteryService(  740): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1064): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1064): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1064):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1064): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3163): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3163): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1064): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  740): SIOP:: AP = 300, Delta = 0
,E/SMD     (  239): DCD ON
,E/SMD     (  239): DCD ON
,D/AmoledAdjustTimer(  740): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  239): DCD ON
,D/BatteryService(  740): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-1, charge type:1, power sharing:false
,D/BatteryService(  740): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  740): mCoverManager.getCoverState() : true
,D/BatteryService(  740): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1064): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1064): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1064):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1064): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3163): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3163): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1064): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  740): SIOP:: AP = 300, Delta = 0
,E/SMD     (  239): DCD ON
,E/SMD     (  239): DCD ON
,D/AmoledAdjustTimer(  740): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  239): DCD ON
,E/SMD     (  239): DCD ON
,D/SSRMv2:SIOP(  740): SIOP:: AP = 300, Delta = 0
,E/Watchdog(  740): !@Sync 57
,E/SMD     (  239): DCD ON
,D/AmoledAdjustTimer(  740): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  239): DCD ON
,E/SMD     (  239): DCD ON
,D/BatteryService(  740): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-2, charge type:1, power sharing:false
,D/BatteryService(  740): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  740): stay LED for fully charged
,D/UiModeManager(  740): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1064): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1064): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1064):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1064): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3163): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3163): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1064): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  740): SIOP:: AP = 300, Delta = 0
,E/SMD     (  239): DCD ON
,E/SMD     (  239): DCD ON
,D/AmoledAdjustTimer(  740): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  239): DCD ON
,D/BatteryService(  740): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-4, charge type:1, power sharing:false
,D/BatteryService(  740): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  740): stay LED for fully charged
D/KeyguardUpdateMonitor( 1064): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1064): handleBatteryUpdate
,D/UiModeManager(  740): mCoverManager.getCoverState() : true
,D/STATUSBAR-PhoneStatusBar( 1064):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3163): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/STATUSBAR-IconMerger( 1064): checkOverflow(288), More:false, Req:false Child:2
,D/HeadsetStateMachine( 3163): Disconnected process message: 10
D/BatteryMeterView( 1064): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP(  740): SIOP:: AP = 300, Delta = 0
,E/SMD     (  239): DCD ON
,E/SMD     (  239): DCD ON
,D/AmoledAdjustTimer(  740): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  239): DCD ON
,E/SMD     (  239): DCD ON
,D/BatteryService(  740): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-2, charge type:1, power sharing:false
,D/BatteryService(  740): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  740): stay LED for fully charged
,D/UiModeManager(  740): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1064): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1064): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1064):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1064): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3163): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3163): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1064): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  740): SIOP:: AP = 300, Delta = 0
,E/Watchdog(  740): !@Sync 58
,V/AlarmManager(  740): waitForAlarm result :8
,V/AlarmManager(  740): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1064): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1064): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1064): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  239): DCD ON
,D/AmoledAdjustTimer(  740): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  239): DCD ON
,E/SMD     (  239): DCD ON
,D/BatteryService(  740): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-4, charge type:1, power sharing:false
,D/BatteryService(  740): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  740): stay LED for fully charged
,D/UiModeManager(  740): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1064): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1064): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1064):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1064): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3163): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3163): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1064): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  740): SIOP:: AP = 300, Delta = 0
,E/SMD     (  239): DCD ON
,E/SMD     (  239): DCD ON
,D/AmoledAdjustTimer(  740): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  239): DCD ON
,D/BatteryService(  740): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-2, charge type:1, power sharing:false
,D/BatteryService(  740): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  740): mCoverManager.getCoverState() : true
,D/BatteryService(  740): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1064): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1064): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1064):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1064): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3163): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3163): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1064): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  740): SIOP:: AP = 300, Delta = 0
,E/SMD     (  239): DCD ON
,E/SMD     (  239): DCD ON
,D/AmoledAdjustTimer(  740): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  239): DCD ON
,E/SMD     (  239): DCD ON
,D/BatteryService(  740): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-7, charge type:1, power sharing:false
,D/BatteryService(  740): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  740): stay LED for fully charged
,D/UiModeManager(  740): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1064): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1064): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1064):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1064): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3163): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3163): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1064): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  740): SIOP:: AP = 300, Delta = 0
,E/Watchdog(  740): !@Sync 59
,E/SMD     (  239): DCD ON
,D/AmoledAdjustTimer(  740): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  239): DCD ON
,E/SMD     (  239): DCD ON
,D/BatteryService(  740): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  740): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  740): stay LED for fully charged
,D/UiModeManager(  740): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1064): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1064): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1064):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1064): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3163): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3163): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1064): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  740): SIOP:: AP = 300, Delta = 0
,E/SMD     (  239): DCD ON
,E/SMD     (  239): DCD ON
,D/AmoledAdjustTimer(  740): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  239): DCD ON
,D/BatteryService(  740): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-4, charge type:1, power sharing:false
,D/BatteryService(  740): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  740): stay LED for fully charged
,D/UiModeManager(  740): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1064): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1064): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1064):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1064): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3163): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3163): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1064): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  740): SIOP:: AP = 300, Delta = 0
,E/SMD     (  239): DCD ON
,E/SMD     (  239): DCD ON
,D/AmoledAdjustTimer(  740): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,D/TimaService(  740): TIMA: TimaService scheduler is intialized. 
,D/TimaService(  740): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService(  740): TimaServiceHandler.handleMessage what =1
,E/SMD     (  239): DCD ON
,I/PowerManagerService(  740): [PWL] Off : 1755s ago
,I/PowerManagerService(  740): [PWL]   PowerManagerService.WakeLocks: ref count=1
,I/PowerManagerService(  740): [PWL]     mWakeLockSummary : 0x1
,I/PowerManagerService(  740): [PWL]       PARTIAL_WAKE_LOCK              'TimaService' (uid=1000, pid=740, ws=null) (elapsedTime=3756)
,I/TLC_TIMA_PKM_measure_kernel(  740): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel(  740): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService(  740): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService(  740): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/dalvikvm(  740): GC_CONCURRENT freed 3494K, 57% free 23613K/54688K, paused 46ms+17ms, total 811ms
,E/SMD     (  239): DCD ON
,D/BatteryService(  740): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
,D/BatteryService(  740): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  740): stay LED for fully charged
,D/UiModeManager(  740): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1064): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1064): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1064):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1064): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3163): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3163): Disconnected process message: 10
D/STATUSBAR-IconMerger( 1064): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  740): SIOP:: AP = 300, Delta = 0
,E/Watchdog(  740): !@Sync 60
,V/AlarmManager(  740): waitForAlarm result :8
,V/AlarmManager(  740): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 1064): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1064): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1064): checkOverflow(288), More:false, Req:false Child:2
,I/ProcessStatsService(  740): Prepared write state in 142ms
,I/ProcessStatsService(  740): Prepared write state in 141ms
,I/ProcessStatsService(  740): Pruning old procstats: /data/system/procstats/state-2015-12-10-15-10-09.bin
,E/SMD     (  239): DCD ON
,D/AmoledAdjustTimer(  740): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  239): DCD ON
,E/SMD     (  239): DCD ON
,D/BatteryService(  740): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-5, charge type:1, power sharing:false
,D/BatteryService(  740): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  740): mCoverManager.getCoverState() : true
,D/BatteryService(  740): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1064): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1064): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1064):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1064): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 1064): checkOverflow(288), More:false, Req:false Child:2
,V/HeadsetService( 3163): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3163): Disconnected process message: 10
,D/SSRMv2:SIOP(  740): SIOP:: AP = 300, Delta = 0,
,E/SMD     (  239): DCD ON
,E/SMD     (  239): DCD ON
,D/AmoledAdjustTimer(  740): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  239): DCD ON
,D/SSRMv2:SIOP(  740): SIOP:: AP = 300, Delta = 0
,E/SMD     (  239): DCD ON
,E/SMD     (  239): DCD ON
,D/AmoledAdjustTimer(  740): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  239): DCD ON
,E/SMD     (  239): DCD ON
,D/BatteryService(  740): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-2, charge type:1, power sharing:false
,D/BatteryService(  740): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  740): mCoverManager.getCoverState() : true
,D/BatteryService(  740): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1064): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1064): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1064):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1064): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3163): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3163): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1064): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  740): SIOP:: AP = 300, Delta = 0
,E/Watchdog(  740): !@Sync 61
,E/SMD     (  239): DCD ON
,D/AmoledAdjustTimer(  740): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  239): DCD ON
,E/SMD     (  239): DCD ON
,D/BatteryService(  740): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-1, charge type:1, power sharing:false
,D/BatteryService(  740): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  740): mCoverManager.getCoverState() : true
,D/BatteryService(  740): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1064): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1064): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1064):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1064): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3163): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3163): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1064): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  740): SIOP:: AP = 300, Delta = 0
,E/SMD     (  239): DCD ON
,E/SMD     (  239): DCD ON
,D/AmoledAdjustTimer(  740): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  239): DCD ON
,D/BatteryService(  740): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-6, charge type:1, power sharing:false
,D/BatteryService(  740): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  740): mCoverManager.getCoverState() : true
,D/BatteryService(  740): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1064): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1064): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1064):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1064): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3163): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3163): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1064): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  740): SIOP:: AP = 300, Delta = 0
,E/SMD     (  239): DCD ON
,E/SMD     (  239): DCD ON
,D/AmoledAdjustTimer(  740): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  239): DCD ON
,E/SMD     (  239): DCD ON
,D/SSRMv2:SIOP(  740): SIOP:: AP = 300, Delta = 0
,E/Watchdog(  740): !@Sync 62
,V/AlarmManager(  740): waitForAlarm result :8
,V/AlarmManager(  740): ClockReceiver onReceive() ACTION_TIME_TICK
,V/AlarmManager(  740): ___SyncScheduler (v3) ACTIVATED___
,V/AlarmManager(  740): <AppSync3 Whitelist>
,V/AlarmManager(  740): (AppSync) ### 0 added ###
D/KeyguardUpdateMonitor( 1064): received broadcast android.intent.action.TIME_TICK
D/KeyguardUpdateMonitor( 1064): handleTimeUpdate
,D/STATUSBAR-IconMerger( 1064): checkOverflow(288), More:false, Req:false Child:2
,E/SMD     (  239): DCD ON
,D/AmoledAdjustTimer(  740): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  239): DCD ON
,E/SMD     (  239): DCD ON
,D/BatteryService(  740): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:3, charge type:1, power sharing:false
,D/BatteryService(  740): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  740): mCoverManager.getCoverState() : true
,D/BatteryService(  740): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1064): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1064): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1064):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1064): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3163): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3163): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1064): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  740): SIOP:: AP = 300, Delta = 0
,E/SMD     (  239): DCD ON
,E/SMD     (  239): DCD ON
,D/AmoledAdjustTimer(  740): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  239): DCD ON
,D/BatteryService(  740): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:2, charge type:1, power sharing:false
,D/BatteryService(  740): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager(  740): mCoverManager.getCoverState() : true
,D/BatteryService(  740): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1064): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1064): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1064):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1064): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3163): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3163): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1064): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  740): SIOP:: AP = 300, Delta = 0
,E/SMD     (  239): DCD ON
,E/SMD     (  239): DCD ON
,D/AmoledAdjustTimer(  740): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  239): DCD ON
,E/SMD     (  239): DCD ON
,D/BatteryService(  740): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-4, charge type:1, power sharing:false
,D/BatteryService(  740): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  740): stay LED for fully charged
,D/UiModeManager(  740): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1064): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1064): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1064):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1064): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3163): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3163): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1064): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  740): SIOP:: AP = 300, Delta = 0
,E/Watchdog(  740): !@Sync 63
,E/SMD     (  239): DCD ON
,D/AmoledAdjustTimer(  740): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  239): DCD ON
,E/SMD     (  239): DCD ON
,D/BatteryService(  740): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:-5, charge type:1, power sharing:false
,D/BatteryService(  740): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  740): stay LED for fully charged
,D/UiModeManager(  740): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 1064): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1064): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1064):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1064): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3163): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3163): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 1064): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP(  740): SIOP:: AP = 300, Delta = 0
,E/SMD     (  239): DCD ON
,E/SMD     (  239): DCD ON
,D/AmoledAdjustTimer(  740): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,E/SMD     (  239): DCD ON
,E/SMD     (  239): DCD ON
,D/SSRMv2:SIOP(  740): SIOP:: AP = 300, Delta = 0
,TIME-OUT KILL (timeout was 1800000ms),E/SMD     (  239): DCD ON
D/AmoledAdjustTimer(  740): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
V/AlarmManager(  740): waitForAlarm result :4
I/SensorManagerA(  740): getReportingMode :: sensor.mType = 5
D/Sensors (  740): LightSensor setDelay = 200000000
D/Sensors (  740): LightSensor setSensorDelay = 200000000
D/LightsService(  740): [api] onReceive : SvcLEDReceiver re-enables LightSenor and sends MSG_FORCEDSVCLEDTASK
D/Sensors (  740): Light sensor flush: not enabled 0
D/Sensors (  740): LightSensor enable = 1
D/Sensors (  740): LightSensor enableSensor = 1
D/SensorManager(  740): registerListener :: 16, CM36686 Light Sensor, 200000, 0,  
I/ActivityManager(  740): Killing 5352:com.sec.android.app.clockpackage/u0a84 (adj 15): empty for 1800s
I/ActivityManager(  740): Killing 5330:com.samsung.android.scloud.sync/u0a62 (adj 15): empty for 1800s
I/ActivityManager(  740): Killing 4672:com.osp.app.signin/u0a43 (adj 15): empty for 1800s
I/ActivityManager(  740): Killing 5128:com.sec.android.soagent/u0a37 (adj 15): empty for 1800s
I/ActivityManager(  740): Killing 4526:com.sec.android.app.shealth/u0a35 (adj 15): empty for 1800s
I/ActivityManager(  740): Killing 5114:com.samsung.klmsagent/u0a18 (adj 15): empty for 1800s
I/ActivityManager(  740): Killing 5093:com.sec.android.fotaclient/u0a10 (adj 15): empty for 1800s
I/ActivityManager(  740): Killing 5278:com.samsung.android.service.travel/u0a169 (adj 15): empty for 1801s
I/ActivityManager(  740): Killing 5271:com.sec.android.provider.badge/u0a72 (adj 15): empty for 1801s
I/ActivityManager(  740): Killing 4907:tv.peel.smartremote/u0a163 (adj 15): empty for 1801s
I/ActivityManager(  740): Killing 5252:com.android.email/u0a155 (adj 15): empty for 1801s
D/BatteryService(  740): level:100, scale:100, status:5, health:2, present:true, voltage: 4369, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:0, charge type:1, power sharing:false
D/BatteryService(  740): stay LED for fully charged
I/ActivityManager(  740): Killing 5214:com.google.android.apps.magazines/u0a112 (adj 15): empty for 1801s
I/ActivityManager(  740): Killing 4763:com.samsung.android.magazine.service/u0a106 (adj 15): empty for 1802s
I/ActivityManager(  740): Killing 5065:com.android.chrome/u0a81 (adj 15): empty for 1802s
I/ActivityManager(  740): Killing 5187:com.samsung.android.scloud.backup/u0a60 (adj 15): empty for 1802s
I/ActivityManager(  740): Killing 3700:com.sec.spp.push/u0a38 (adj 15): empty for 1802s
I/ActivityManager(  740): Killing 4621:com.policydm/1000 (adj 15): empty for 1802s
I/ActivityManager(  740): Killing 5151:com.sec.android.app.voicenote/1000 (adj 15): empty for 1802s
I/ActivityManager(  740): Killing 5134:com.sec.android.app.videoplayer/u0a52 (adj 15): empty for 1802s
I/ActivityManager(  740): Killing 4947:com.vlingo.midas/u0a33 (adj 15): empty for 1802s
I/ActivityManager(  740): Killing 4225:com.sec.android.diagmonagent/1000 (adj 15): empty for 1803s
I/ActivityManager(  740): Killing 5045:com.sec.android.cloudagent/u0a2 (adj 15): empty for 1803s
I/ActivityManager(  740): Killing 3749:com.google.android.music:main/u0a122 (adj 15): empty for 1803s
I/ActivityManager(  740): Killing 4493:com.sec.pcw.device/1000 (adj 15): empty for 1803s
I/ActivityManager(  740): Killing 4802:com.samsung.android.provider.shootingmodeprovider/u0a162 (adj 15): empty for 1813s
I/ActivityManager(  740): Killing 4790:com.sec.kidsplat.installer/u0a158 (adj 15): empty for 1813s
I/ActivityManager(  740): Killing 4776:com.samsung.helphub/1000 (adj 15): empty for 1813s
V/NetworkStats(  740): performPollLocked(flags=0x3)
D/NtpTrustedTime(  740): currentTimeMillis() cache hit
V/AlarmManager(  740): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
D/BatteryService(  740): Sending ACTION_BATTERY_CHANGED.
D/Sensors (  740): LightSensor enable = 0
D/LightsService(  740): [SvcLED]  onSensorChanged::light value = 39
D/Sensors (  740): LightSensor enableSensor = 0
D/UiModeManager(  740): mCoverManager.getCoverState() : true
D/SensorManager(  740): unregisterListener ::   
D/LightsService(  740): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
D/KeyguardUpdateMonitor( 1064): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1064): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 1064):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
D/BatteryMeterView( 1064): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/STATUSBAR-IconMerger( 1064): checkOverflow(288), More:false, Req:false Child:2
V/HeadsetService( 3163): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 3163): Disconnected process message: 10
V/NetworkStats(  740): performPollLocked() took 247ms
D/NtpTrustedTime(  740): currentTimeMillis() cache hit
D/NtpTrustedTime(  740): currentTimeMillis() cache hit
D/NtpTrustedTime(  740): currentTimeMillis() cache hit
V/GLSActivity( 1313): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/GLSActivity( 1313): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
E/SMD     (  239): DCD ON
D/ConnectivityService(  740): handleInetConditionHoldEnd: net=1, condition=100, published condition=100
D/STATUSBAR-NetworkController_dual( 1064): onReceive() - CONNECTIVITY_ACTION, INET_CONDITION_ACTION
D/StatusBar.NetworkController_dual( 1064): mMobileLabelViews start
D/StatusBar.NetworkController_dual( 1064): mMobileLabelViews set mobileLabel[SIM_0] =
D/StatusBar.NetworkController_dual( 1064): mMobileLabelViews GONE
D/StatusBar.NetworkController_dual( 1064): mMobileLabelViews2 set mobileLabel[SIM_1] =
D/StatusBar.NetworkController_dual( 1064): mMobileLabelViews2 GONE
D/StatusBar.NetworkController_dual( 1064): mSingleMobileLabelViews set : simMode = 0
D/StatusBar.NetworkController_dual( 1064): mSingleMobileLabelViews set as slot1`s
E/SMD     (  239): DCD ON
E/Watchdog(  740): !@Sync 64
D/SSRMv2:SIOP(  740): SIOP:: AP = 300, Delta = 0
D/AndroidRuntime( 6048): 
D/AndroidRuntime( 6048): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 6048): CheckJNI is OFF
D/AndroidRuntime( 6048): setted country_code = Poland
D/AndroidRuntime( 6048): setted countryiso_code = PL
D/AndroidRuntime( 6048): setted sales_code = XEO
D/AndroidRuntime( 6048): readGMSProperty: start
D/AndroidRuntime( 6048): readGMSProperty: already setted!!
D/AndroidRuntime( 6048): readGMSProperty: end
D/AndroidRuntime( 6048): addProductProperty: start
D/dalvikvm( 6048): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 6048): Added shared lib libjavacore.so 0x0
D/dalvikvm( 6048): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 6048): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 6048): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
E/memtrack( 6048): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 6048): failed to load memtrack module: -2
D/dalvikvm( 6048): Note: class Landroid/app/ActivityManagerNative; has 192 unimplemented (abstract) methods
D/AndroidRuntime( 6048): Calling main entry com.android.commands.pm.Pm
D/PackageManagerService(  740): deletePackageAsUser- pkg:com.test.thalitest, userId:0
D/PersonaManagerService(  740): isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
D/PersonaManagerService(  740): isFromApprovedUnInstaller: isApproved : true
D/PersonaManagerService(  740): isFromApprovedUnInstaller: isApproved before exit: true
D/PackageManager(  740): deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag3
D/PackageManager(  740): deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag3
D/PackageManager(  740): START PACKAGE DELETE: observer{1124329160}
D/PackageManager(  740): pkg{<packageName>}
D/PackageManager(  740): user{0}
D/PackageManager(  740): deletePackageAsUser : uid = 2000 userId = 0
D/PackageManagerService(  740): deletePackage- pkg:com.test.thalitest, edmuserId:0
D/PackageManagerService(  740): deletePackage- pkg:com.test.thalitest, edmuserId:-1
D/ApplicationPolicy(  740): getApplicationUninstallationEnabled
D/ApplicationPolicy(  740): getApplicationUninstallationEnabled :  enabled true
D/PackageManagerService(  740): deletePackageX- pkg:com.test.thalitest, userId:0
D/PackageManager(  740): [MSG] DELETE_PACKAGE_AS_USER
D/PackageManager(  740): !@killApplicatoin: 10179, uninstall pkg
I/ActivityManager(  740): Killing 4656:com.test.thalitest/u0a179 (adj 0): stop com.test.thalitest
D/CustomFrequencyManagerService(  740): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 740  pkgName : ACTIVITY_RESUME_BOOSTER@5
W/ActivityManager(  740): mDVFSHelper.acquire()
D/KeyguardUpdateMonitor( 1064): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1064): handleKeyguardVisibilityChanged(1)
D/KeyguardUpdateMonitor( 1064): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1064): handleKeyguardVisibilityChanged(1)
D/KeyguardUpdateMonitor( 1064): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1064): handleKeyguardVisibilityChanged(1)
D/Launcher( 1256): onRestart, Launcher: 1114072968
D/Launcher( 1256): onStart, Launcher: 1114072968
D/Launcher.HomeView( 1256): onStart
D/SurfaceWidgetClient$ISurfaceWidgetStub( 1441): [237392/5] Surface widget visibility changed visibility = true on instance = 1
D/SurfaceWidget.Renderer( 1441): [237392/5] SurfaceWidget drawing first frame
I/SurfaceFlinger(  245): id=17 Removed NainActivit (7/11)
I/SurfaceFlinger(  245): id=17 Removed NainActivit (-2/11)
I/SurfaceFlinger(  245): id=17 Removed NainActivit (-2/11)
D/KeyguardUpdateMonitor( 1064): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1064): handleKeyguardVisibilityChanged(1)
I/WindowState(  740): WIN DEATH: Window{431a24a8 u0 com.test.thalitest/com.test.thalitest.MainActivity}
W/PackageSettings(  740): Skipping PackageSetting{427b94f0 com.example.hello/10180} due to missing metadata
D/PackageManager(  740): queryIntentReceivers - Execution time: 154 ms
D/PackageManager(  740): checkUidPermission - Execution time: 138 ms
D/LockPatternUtils( 1064): isPcwEnable = null
D/PackageManager(  740): Sending to user 0: act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000000 Bundle[{android.intent.extra.REMOVED_FOR_ALL_USERS=true, android.intent.extra.UID=10179, android.intent.extra.DATA_REMOVED=true, android.intent.extra.user_handle=0}]
D/KeyguardUpdateMonitor( 1064): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1064): handleKeyguardVisibilityChanged(1)
I/SurfaceFlinger(  245): id=19 createSurf (1x1),2 flag=404, CatteryCove
D/KeyguardUpdateMonitor( 1064): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1064): handleKeyguardVisibilityChanged(1)
I/SurfaceFlinger(  245): id=20 createSurf (720x1280),1 flag=4, Mauncher
D/KeyguardUpdateMonitor( 1064): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1064): handleKeyguardVisibilityChanged(1)
V/AlarmManager(  740): waitForAlarm result :8
D/dalvikvm( 2120): GC_EXPLICIT freed 544K, 41% free 11228K/18944K, paused 4ms+3ms, total 39ms
D/PackageManager(  740): Sending to user 0: act=android.intent.action.PACKAGE_FULLY_REMOVED dat=package:com.test.thalitest flg=0x4000000 Bundle[{android.intent.extra.REMOVED_FOR_ALL_USERS=true, android.intent.extra.UID=10179, android.intent.extra.DATA_REMOVED=true, android.intent.extra.user_handle=0}]
D/AdaptiveEventManager( 1064): action=android.intent.action.PACKAGE_REMOVED
D/QuickConnect[1.1][2] ( 3137): SconnectManager.onReceiver - action : android.intent.action.PACKAGE_REMOVED, package : com.test.thalitest
D/elm:14132( 5372): ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
I/FPMS_FingerprintManagerService( 1083): onReceive: android.intent.action.PACKAGE_REMOVED
D/dalvikvm( 1396): GC_EXPLICIT freed 4378K, 48% free 10026K/18944K, paused 4ms+4ms, total 76ms
W/GeofencerStateMachine( 1213): Ignoring removeGeofence because network location is disabled.
D/elm:14132( 5372): ELMAbstractReceiver : Receive Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
I/InputReader(  740): Reconfiguring input devices.  changes=0x00000010
D/elm:14132( 5372): ElmAgentService : onCreate()
I/PackageManager(  740):   Action: "android.intent.action.SENDTO"
I/PackageManager(  740):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  740):   Scheme: "sms"
D/elm:14132( 5372): ElmAgentService : onHandleIntent() Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
D/elm:14132( 5372): MainReceiver.listeningToPackageRemoved()
D/elm:14132( 5372): MDMBridge.getInstance()
D/elm:14132( 5372): MDMBridge.getAllLicenseInfoFromSDK()
I/PackageManager(  740): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
D/dalvikvm( 1795): GC_EXPLICIT freed 498K, 36% free 12249K/18944K, paused 5ms+22ms, total 113ms
W/SQLiteConnectionPool( 1795): A SQLiteConnection object for database '+data+data+com_google_android_gms+databases+networkstatistics_sqlite' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
D/KeyguardUpdateMonitor( 1064): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1064): handleKeyguardVisibilityChanged(1)
D/KeyguardUpdateMonitor( 1064): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1064): handleKeyguardVisibilityChanged(1)
I/SELinux ( 6076): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 6076):  
I/PackageManager(  740):   Action: "android.intent.action.SENDTO"
I/PackageManager(  740):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  740):   Scheme: "smsto"
D/dalvikvm(  740): GC_EXPLICIT freed 2628K, 57% free 23638K/54688K, paused 7ms+16ms, total 176ms
D/dalvikvm(  740): WAIT_FOR_CONCURRENT_GC blocked 103ms
D/elm:14132( 5372): MDMBridge.getAllLicenseInfoFromSDK()
I/PackageManager(  740): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
D/CustomFrequencyManagerService(  740): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 740  tag : ACTIVITY_RESUME_BOOSTER@5
W/ActivityManager(  740): mDVFSHelper.release()
D/KeyguardUpdateMonitor( 1064): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1064): handleKeyguardVisibilityChanged(1)
I/SurfaceFlinger(  245): id=21 createSurf (707x984),1 flag=4, TettingsRec
D/CustomFrequencyManagerService(  740): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 740  pkgName : ACTIVITY_RESUME_BOOSTER@9
D/KeyguardUpdateMonitor( 1064): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1064): handleKeyguardVisibilityChanged(1)
I/SELinux ( 6076): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 6076):  
I/SELinux ( 6076):  
I/SELinux ( 6076): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 6076): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 6076): >>>>> Normal User
E/dalvikvm( 6076): >>>>> com.sec.android.service.health [ userId:0 | appId:10016 ]
E/SELinux ( 6076): [DEBUG] seapp_context_lookup: seinfoCategory = platform
I/PackageManager(  740):   Action: "android.intent.action.SENDTO"
I/PackageManager(  740):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  740):   Scheme: "mms"
I/PackageManager(  740): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
D/elm:14132( 5372): MainReceiver.listeningToPackageRemoved(). SEND to KLMS. Remove All KNOX/ONS License
D/KeyguardUpdateMonitor( 1064): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1064): handleKeyguardVisibilityChanged(1)
D/elm:14132( 5372): ElmAgentService : onDestroy().
I/PackageManager(  740):   Action: "android.intent.action.SENDTO"
I/PackageManager(  740):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  740):   Scheme: "mmsto"
I/PackageManager(  740): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
D/TimaKeyStoreProvider( 6076): in addTimaSignatureService
D/TimaKeyStoreProvider( 6076): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 6076): Added TimaKesytore provider
D/KeyguardUpdateMonitor( 1064): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1064): handleKeyguardVisibilityChanged(1)
D/RCPManagerService(  740): PackageReceiver onReceive()
I/HarmonyEASService(  740): onReceive : android.intent.action.PACKAGE_REMOVED for 0
I/PackageManager(  740):   Action: "android.intent.action.SENDTO"
I/PackageManager(  740):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  740):   Scheme: "sms"
I/PackageManager(  740): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
I/PackageManager(  740):   Action: "android.intent.action.SENDTO"
I/PackageManager(  740):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  740):   Scheme: "smsto"
I/PackageManager(  740): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
I/PackageManager(  740):   Action: "android.intent.action.SENDTO"
I/PackageManager(  740):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  740):   Scheme: "mms"
I/PackageManager(  740): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
I/PackageManager(  740):   Action: "android.intent.action.SENDTO"
I/PackageManager(  740):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  740):   Scheme: "mmsto"
I/PackageManager(  740): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
W/ActivityManager(  740): Permission Denial: getCurrentUser() from pid=6076, uid=10016 requires android.permission.INTERACT_ACROSS_USERS
D/BackupManagerService(  740): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
D/dalvikvm(  740): GC_EXPLICIT freed 830K, 57% free 23599K/54688K, paused 8ms+20ms, total 240ms
D/KeyguardUpdateMonitor( 1064): received broadcast android.intent.action.TIME_TICK
D/KeyguardUpdateMonitor( 1064): handleTimeUpdate
D/dalvikvm( 6076): No JNI_OnLoad found in /system/lib/libsecure_storage_jni.so 0x425d0e68, skipping init
I/SecureStorage( 6076): [INFO]: SPID(0x00000000)Checking if this device supports Secure Storage
I/SecureStorage( 6076): [INFO]: SPID(0x00000000)This device supports Secure Storage
I/SecureStorage(  297): [INFO]: SPID(0x00000004)Credentials: uid 10016, gid 10016, pid 6076
I/SecureStorage(  297): [INFO]: SPID(0x00000004)Received function mask & code: 0000010C
V/BackupManagerService(  740): removePackageParticipantsLocked: uid=10179 #1
V/AlarmManager(  740): ClockReceiver onReceive() ACTION_TIME_TICK
D/PackageManager(  740): delete sourFile : 
I/SecureStorage( 6076): [INFO]: SPID(0x00000000)SS Daemon is running
D/PackageManager(  740): delete native library directory: 
D/STATUSBAR-IconMerger( 1064): checkOverflow(288), More:false, Req:false Child:2
I/SecureStorage( 6076): [INFO]: SPID(0x00000000)Processing data
I/SecureStorage(  297): [INFO]: SPID(0x00000004)Credentials: uid 10016, gid 10016, pid 6076
I/SecureStorage(  297): [INFO]: SPID(0x00000004)Received function mask & code: 00000106
D/EnterpriseDeviceManagerService(  740): Package has changed for user 0
D/EnterpriseDeviceManagerService(  740): Admin package name: com.google.android.gms
D/AndroidRuntime( 6048): Shutting down VM
D/PackageManager(  740): return delete result to caller: 1124329160
D/PackageManager(  740): returnCode: 1
D/dalvikvm( 6048): GC_CONCURRENT freed 96K, 14% free 670K/772K, paused 1ms+0ms, total 3ms
W/Resources(  740): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  740): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
I/PackageManager(  740):   Action: "android.intent.action.SENDTO"
I/PackageManager(  740):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  740):   Scheme: "sms"
I/PackageManager(  740): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
I/PackageManager(  740):   Action: "android.intent.action.SENDTO"
I/PackageManager(  740):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  740):   Scheme: "smsto"
I/PackageManager(  740): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
I/PackageManager(  740):   Action: "android.intent.action.SENDTO"
I/PackageManager(  740):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  740):   Scheme: "mms"
I/PackageManager(  740): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
I/PackageManager(  740):   Action: "android.intent.action.SENDTO"
I/PackageManager(  740):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  740): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
I/PackageManager(  740):   Scheme: "mmsto"
W/Resources(  740): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  740): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  740): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  740): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/Launcher.HomeView( 1256): onStop
W/Resources(  740): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  740): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  740): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  740): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  740): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
W/Resources(  740): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  740): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  740): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
W/Resources(  740): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  740): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  740): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
I/CrashAnrDetector(  740): onPackageRemoved : com.test.thalitest
D/UsbSettingsManager(  740): clearDefaults: com.test.thalitest
D/InputReader(  740): Processing first event
I/EventHub(  740): Removing device sec_touchscreen due to epoll hang-up event.
I/EventHub(  740): Removed device: path=/dev/input/event1 name=sec_touchscreen id=6 fd=217 classes=0x94
I/EventHub(  740): Removing device '/dev/input/event1' due to inotify event
I/InputReader(  740): Device removed: id=6, name='sec_touchscreen', sources=0x80001002
D/InputReader(  740): Could not retrieve current multitouch slot index.  status=-1
D/InputReader(  740): MultiTouchMotionAccumulator: initial slot number is -1
I/ActivityManager(  740): Config changes=8 {0 1.0 ?mcc?mnc en_US ldltr sw360dp w360dp h615dp 320dpi nrml long port -touch -keyb/v/h -nav/h s.5}
D/InputDispatcher(  740): setInputDispatchMode: enabled=0, frozen=1
I/SurfaceFlinger(  245): id=22 createSurf (720x1280),2 flag=404, TcreenshotS
E/SMD     (  239): DCD ON
D/PermissionCache(  245): checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (190 us)
D/Mms/MmsApp( 3779): [start]    onConfigurationChanged(),newConfig={0 1.0 ?mcc?mnc en_US ldltr sw360dp w360dp h615dp 320dpi nrml long port -touch -keyb/v/h -nav/h s.5}
D/Mms/MmsApp( 3779): [end]    onConfigurationChanged(),newConfig={0 1.0 ?mcc?mnc en_US ldltr sw360dp w360dp h615dp 320dpi nrml long port -touch -keyb/v/h -nav/h s.5}
D/dalvikvm( 4190): GC_FOR_ALLOC freed 3K, 22% free 18171K/23112K, paused 11ms, total 11ms
I/dalvikvm-heap( 4190): Grow heap (frag case) to 22.997MB for 2129936-byte allocation
W/ApplicationsProvider( 1396): Could not fetch usage stats
W/ApplicationsProvider( 1396): java.lang.SecurityException: Neither user 10020 nor current process has android.permission.PACKAGE_USAGE_STATS.
W/ApplicationsProvider( 1396): 	at android.os.Parcel.readException(Parcel.java:1465)
W/ApplicationsProvider( 1396): 	at android.os.Parcel.readException(Parcel.java:1419)
W/ApplicationsProvider( 1396): 	at com.android.internal.app.IUsageStats$Stub$Proxy.getAllPkgUsageStats(IUsageStats.java:317)
W/ApplicationsProvider( 1396): 	at android.app.ActivityManager.getAllPackageUsageStats(ActivityManager.java:2543)
W/ApplicationsProvider( 1396): 	at com.android.providers.applications.ApplicationsProvider.fetchUsageStats(ApplicationsProvider.java:681)
W/ApplicationsProvider( 1396): 	at com.android.providers.applications.ApplicationsProvider.updateApplicationsList(ApplicationsProvider.java:519)
W/ApplicationsProvider( 1396): 	at com.android.providers.applications.ApplicationsProvider.access$300(ApplicationsProvider.java:70)
W/ApplicationsProvider( 1396): 	at com.android.providers.applications.ApplicationsProvider$UpdateHandler.handleMessage(ApplicationsProvider.java:209)
W/ApplicationsProvider( 1396): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/ApplicationsProvider( 1396): 	at android.os.Looper.loop(Looper.java:146)
W/ApplicationsProvider( 1396): 	at android.os.HandlerThread.run(HandlerThread.java:61)
D/CustomFrequencyManagerService(  740): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 740  tag : ACTIVITY_RESUME_BOOSTER@9

```
