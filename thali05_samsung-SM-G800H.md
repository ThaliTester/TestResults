#### Test 50388019385b4d9_thali05_samsung-SM-G800H Logs


```
--------- beginning of /dev/log/main
I/SELinux ( 2390): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 2390):  
D/dalvikvm(  250): GC_EXPLICIT freed 43K, 50% free 9508K/18756K, paused 2ms+3ms, total 23ms
D/dalvikvm(  250): GC_EXPLICIT freed <1K, 50% free 9508K/18756K, paused 1ms+2ms, total 18ms
I/SELinux ( 2390): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 2390):  
I/SELinux ( 2390):  
I/SELinux ( 2390): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 2390): [DEBUG] seapp_context_lookup: seinfoCategory = release
E/dalvikvm( 2390): >>>>> Normal User
E/dalvikvm( 2390): >>>>> com.sec.android.app.shealth [ userId:0 | appId:10035 ]
E/SELinux ( 2390): [DEBUG] seapp_context_lookup: seinfoCategory = release
D/dalvikvm(  250): GC_EXPLICIT freed <1K, 50% free 9508K/18756K, paused 2ms+3ms, total 19ms
D/TimaKeyStoreProvider( 2390): in addTimaSignatureService
D/TimaKeyStoreProvider( 2390): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 2390): Added TimaKesytore provider
I/TagReady( 2373): registerContentObserver() Support usertag? true
--------- beginning of /dev/log/system
W/ActivityManager(  745): Permission Denial: getCurrentUser() from pid=2390, uid=10035 requires android.permission.INTERACT_ACROSS_USERS
W/ContextImpl( 2390): Implicit intents with startService are not safe: Intent { act=com.sec.android.service.health.cp.accesscontrol } android.content.ContextWrapper.bindService:529 com.samsung.android.sdk.health.content.ShealthAccessControl.startService:274 com.samsung.android.sdk.health.content.ShealthAccessControl.requestPermission:212 
E/Device Type Shared Preferences( 2390): Device Type Shared Preferences - getDeviceTypeChecked -true
E/Device Type Shared Preferences( 2390): Device Type Shared Preferences - not connecting to service
E/com.sec.android.app.shealth.SHealthApplication( 2390): ContentProvider is not null
V/MediaPlayer( 2390): decode(61, 33979084, 48105)
V/MediaPlayerService(  252): decode(33, 33979084, 48105)
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
V/StagefrightPlayer(  252): setDataSource(33, 33979084, 48105)
V/AwesomePlayer(  252): reset_l()
V/AwesomePlayer(  252): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  252): notify(0xb779b6e0, 8, 0, 0)
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
V/AudioCache(  252): notify(0xb779b6e0, 200, 973, 0)
V/AudioCache(  252): ignored
V/AwesomePlayer(  252): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  252): notify(0xb779b6e0, 5, 0, 0)
V/AudioCache(  252): ignored
V/AwesomePlayer(  252): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  252): notify(0xb779b6e0, 1, 0, 0)
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
V/AudioCache(  252): notify(0xb779b6e0, 6, 0, 0)
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
V/AudioCache(  252): notify(0xb779b6e0, 2, 0, 0)
V/AudioCache(  252): playback complete - thread will wake up later
V/AwesomePlayer(  252): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  252): notify(0xb779b6e0, 7, 0, 0)
V/AudioCache(  252): ignored
V/AwesomePlayer(  252): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer(  252): addBatteryData
V/AudioCache(  252): wait - success
V/StagefrightPlayer(  252): reset
V/AwesomePlayer(  252): reset_l()
V/AwesomePlayer(  252): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  252): notify(0xb779b6e0, 8, 0, 0)
V/AudioCache(  252): ignored
V/AwesomePlayer(  252): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  252): mAudioTrackVector clear
I/OMXCodec(  252): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec(  252): [OMX.google.vorbis.decoder] stop() sendCommand(0x20, OMX_CommandStateSet, OMX_StateIdle)
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
V/MediaPlayer( 2390): decode(63, 33914984, 10421)
V/MediaPlayerService(  252): decode(33, 33914984, 10421)
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
V/StagefrightPlayer(  252): setDataSource(33, 33914984, 10421)
V/AwesomePlayer(  252): reset_l()
V/AwesomePlayer(  252): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  252): notify(0xb77a2028, 8, 0, 0)
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
V/AudioCache(  252): notify(0xb77a2028, 200, 973, 0)
V/AudioCache(  252): ignored
V/AwesomePlayer(  252): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  252): notify(0xb77a2028, 5, 0, 0)
V/AudioCache(  252): ignored
V/AwesomePlayer(  252): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  252): notify(0xb77a2028, 1, 0, 0)
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
V/AudioCache(  252): notify(0xb77a2028, 6, 0, 0)
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
V/AudioCache(  252): notify(0xb77a2028, 2, 0, 0)
V/AudioCache(  252): playback complete - thread will wake up later
V/AwesomePlayer(  252): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  252): notify(0xb77a2028, 7, 0, 0)
V/AudioCache(  252): ignored
V/AwesomePlayer(  252): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer(  252): addBatteryData
V/AudioCache(  252): wait - success
V/StagefrightPlayer(  252): reset
V/AwesomePlayer(  252): reset_l()
V/AwesomePlayer(  252): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  252): notify(0xb77a2028, 8, 0, 0)
V/AudioCache(  252): ignored
V/AwesomePlayer(  252): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  252): mAudioTrackVector clear
I/OMXCodec(  252): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec(  252): [OMX.google.vorbis.decoder] stop() sendCommand(0x21, OMX_CommandStateSet, OMX_StateIdle)
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
V/MediaPlayer( 2390): decode(64, 37457308, 34198)
V/MediaPlayerService(  252): decode(34, 37457308, 34198)
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
V/StagefrightPlayer(  252): setDataSource(34, 37457308, 34198)
V/AwesomePlayer(  252): reset_l()
V/AwesomePlayer(  252): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  252): notify(0xb77ad360, 8, 0, 0)
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
V/AudioCache(  252): notify(0xb77ad360, 200, 973, 0)
V/AudioCache(  252): ignored
V/AwesomePlayer(  252): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  252): notify(0xb77ad360, 5, 0, 0)
V/AudioCache(  252): ignored
V/AwesomePlayer(  252): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  252): notify(0xb77ad360, 1, 0, 0)
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
V/AudioCache(  252): notify(0xb77ad360, 6, 0, 0)
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
V/AudioCache(  252): notify(0xb77ad360, 2, 0, 0)
V/AudioCache(  252): playback complete - thread will wake up later
V/AwesomePlayer(  252): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  252): notify(0xb77ad360, 7, 0, 0)
V/AudioCache(  252): ignored
V/AwesomePlayer(  252): cancelPlayerEvents (keepNotifications=1)
V/AudioCache(  252): wait - success
V/StagefrightPlayer(  252): reset
V/AwesomePlayer(  252): addBatteryData
V/AwesomePlayer(  252): reset_l()
V/AwesomePlayer(  252): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  252): notify(0xb77ad360, 8, 0, 0)
V/AudioCache(  252): ignored
V/AwesomePlayer(  252): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  252): mAudioTrackVector clear
I/OMXCodec(  252): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec(  252): [OMX.google.vorbis.decoder] stop() sendCommand(0x22, OMX_CommandStateSet, OMX_StateIdle)
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
V/MediaPlayer( 2390): decode(65, 33862452, 7405)
V/MediaPlayerService(  252): decode(33, 33862452, 7405)
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
V/StagefrightPlayer(  252): setDataSource(33, 33862452, 7405)
V/AwesomePlayer(  252): reset_l()
V/AwesomePlayer(  252): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  252): notify(0xb77a4b80, 8, 0, 0)
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
V/AudioCache(  252): notify(0xb77a4b80, 200, 973, 0)
V/AudioCache(  252): ignored
V/AwesomePlayer(  252): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  252): notify(0xb77a4b80, 5, 0, 0)
V/AudioCache(  252): ignored
V/AwesomePlayer(  252): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  252): notify(0xb77a4b80, 1, 0, 0)
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
V/AudioCache(  252): notify(0xb77a4b80, 6, 0, 0)
V/AudioCache(  252): ignored
V/AwesomePlayer(  252): addBatteryData
V/MediaPlayerService(  252): wait for playback complete
I/ServiceManager(  287): Waiting for service AtCmdFwd...
I/OMXCodec(  252): [OMX.google.vorbis.decoder] End Of Stream
V/AwesomePlayer(  252): postAudioEOS delayUs (0)
V/AwesomePlayer(  252): onCheckAudioStatus
V/AwesomePlayer(  252): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  252): onStreamDone
V/AwesomePlayer(  252): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  252): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  252): notify(0xb77a4b80, 2, 0, 0)
V/AudioCache(  252): playback complete - thread will wake up later
V/AwesomePlayer(  252): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  252): notify(0xb77a4b80, 7, 0, 0)
V/AudioCache(  252): ignored
V/AwesomePlayer(  252): cancelPlayerEvents (keepNotifications=1)
V/AudioCache(  252): wait - success
V/StagefrightPlayer(  252): reset
V/AwesomePlayer(  252): addBatteryData
V/AwesomePlayer(  252): reset_l()
V/AwesomePlayer(  252): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  252): notify(0xb77a4b80, 8, 0, 0)
V/AudioCache(  252): ignored
V/AwesomePlayer(  252): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  252): mAudioTrackVector clear
I/OMXCodec(  252): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec(  252): [OMX.google.vorbis.decoder] stop() sendCommand(0x23, OMX_CommandStateSet, OMX_StateIdle)
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
V/MediaPlayer( 2390): decode(66, 37547940, 5555)
V/MediaPlayerService(  252): decode(33, 37547940, 5555)
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
V/StagefrightPlayer(  252): setDataSource(33, 37547940, 5555)
V/AwesomePlayer(  252): reset_l()
V/AwesomePlayer(  252): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  252): notify(0xb7798c70, 8, 0, 0)
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
V/AudioCache(  252): notify(0xb7798c70, 200, 973, 0)
V/AudioCache(  252): ignored
V/AwesomePlayer(  252): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  252): notify(0xb7798c70, 5, 0, 0)
V/AudioCache(  252): ignored
V/AwesomePlayer(  252): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  252): notify(0xb7798c70, 1, 0, 0)
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
V/AudioCache(  252): notify(0xb7798c70, 6, 0, 0)
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
V/AudioCache(  252): notify(0xb7798c70, 2, 0, 0)
V/AudioCache(  252): playback complete - thread will wake up later
V/AwesomePlayer(  252): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  252): notify(0xb7798c70, 7, 0, 0)
V/AudioCache(  252): ignored
V/AwesomePlayer(  252): cancelPlayerEvents (keepNotifications=1)
V/AudioCache(  252): wait - success
V/StagefrightPlayer(  252): reset
V/AwesomePlayer(  252): addBatteryData
V/AwesomePlayer(  252): reset_l()
V/AwesomePlayer(  252): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  252): notify(0xb7798c70, 8, 0, 0)
V/AudioCache(  252): ignored
V/AwesomePlayer(  252): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  252): mAudioTrackVector clear
I/OMXCodec(  252): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec(  252): [OMX.google.vorbis.decoder] stop() sendCommand(0x24, OMX_CommandStateSet, OMX_StateIdle)
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
V/MediaPlayer( 2390): decode(67, 30367732, 5085)
V/MediaPlayerService(  252): decode(33, 30367732, 5085)
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
V/StagefrightPlayer(  252): setDataSource(33, 30367732, 5085)
V/AwesomePlayer(  252): reset_l()
V/AwesomePlayer(  252): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  252): notify(0xb7797160, 8, 0, 0)
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
V/AudioCache(  252): notify(0xb7797160, 200, 973, 0)
V/AudioCache(  252): ignored
V/AwesomePlayer(  252): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  252): notify(0xb7797160, 5, 0, 0)
V/AudioCache(  252): ignored
V/AwesomePlayer(  252): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  252): notify(0xb7797160, 1, 0, 0)
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
V/AudioCache(  252): notify(0xb7797160, 6, 0, 0)
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
V/AudioCache(  252): notify(0xb7797160, 2, 0, 0)
V/AudioCache(  252): playback complete - thread will wake up later
V/AwesomePlayer(  252): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  252): notify(0xb7797160, 7, 0, 0)
V/AudioCache(  252): ignored
V/AwesomePlayer(  252): cancelPlayerEvents (keepNotifications=1)
V/AudioCache(  252): wait - success
V/StagefrightPlayer(  252): reset
V/AwesomePlayer(  252): addBatteryData
V/AwesomePlayer(  252): reset_l()
V/AwesomePlayer(  252): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  252): notify(0xb7797160, 8, 0, 0)
V/AudioCache(  252): ignored
V/AwesomePlayer(  252): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  252): mAudioTrackVector clear
I/OMXCodec(  252): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec(  252): [OMX.google.vorbis.decoder] stop() sendCommand(0x25, OMX_CommandStateSet, OMX_StateIdle)
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
V/MediaPlayer( 2390): decode(68, 30372876, 21552)
V/MediaPlayerService(  252): decode(33, 30372876, 21552)
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
V/StagefrightPlayer(  252): setDataSource(33, 30372876, 21552)
V/AwesomePlayer(  252): reset_l()
V/AwesomePlayer(  252): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  252): notify(0xb779e4a0, 8, 0, 0)
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
V/AudioCache(  252): notify(0xb779e4a0, 200, 973, 0)
V/AudioCache(  252): ignored
V/AwesomePlayer(  252): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  252): notify(0xb779e4a0, 5, 0, 0)
V/AudioCache(  252): ignored
V/AwesomePlayer(  252): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  252): notify(0xb779e4a0, 1, 0, 0)
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
V/AudioCache(  252): notify(0xb779e4a0, 6, 0, 0)
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
V/AudioCache(  252): notify(0xb779e4a0, 2, 0, 0)
V/AudioCache(  252): playback complete - thread will wake up later
V/AwesomePlayer(  252): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  252): notify(0xb779e4a0, 7, 0, 0)
V/AudioCache(  252): ignored
V/AwesomePlayer(  252): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer(  252): addBatteryData
V/AudioCache(  252): wait - success
V/StagefrightPlayer(  252): reset
V/AwesomePlayer(  252): reset_l()
V/AwesomePlayer(  252): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  252): notify(0xb779e4a0, 8, 0, 0)
V/AudioCache(  252): ignored
V/AwesomePlayer(  252): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  252): mAudioTrackVector clear
I/OMXCodec(  252): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec(  252): [OMX.google.vorbis.decoder] stop() sendCommand(0x26, OMX_CommandStateSet, OMX_StateIdle)
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
V/MediaPlayer( 2390): decode(69, 37543652, 4230)
V/MediaPlayerService(  252): decode(33, 37543652, 4230)
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
V/StagefrightPlayer(  252): setDataSource(33, 37543652, 4230)
V/AwesomePlayer(  252): reset_l()
V/AwesomePlayer(  252): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  252): notify(0xb77ad098, 8, 0, 0)
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
V/AudioCache(  252): notify(0xb77ad098, 200, 973, 0)
V/AudioCache(  252): ignored
V/AwesomePlayer(  252): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  252): notify(0xb77ad098, 5, 0, 0)
V/AudioCache(  252): ignored
V/AwesomePlayer(  252): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  252): notify(0xb77ad098, 1, 0, 0)
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
V/AudioCache(  252): notify(0xb77ad098, 6, 0, 0)
V/AudioCache(  252): ignored
V/AwesomePlayer(  252): addBatteryData
V/MediaPlayerService(  252): wait for playback complete
V/AwesomePlayer(  252): postAudioEOS delayUs (0)
V/AwesomePlayer(  252): onCheckAudioStatus
V/AwesomePlayer(  252): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  252): onStreamDone
V/AwesomePlayer(  252): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  252): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  252): notify(0xb77ad098, 2, 0, 0)
V/AudioCache(  252): playback complete - thread will wake up later
V/AwesomePlayer(  252): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  252): notify(0xb77ad098, 7, 0, 0)
V/AudioCache(  252): ignored
V/AwesomePlayer(  252): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer(  252): addBatteryData
V/AudioCache(  252): wait - success
V/StagefrightPlayer(  252): reset
V/AwesomePlayer(  252): reset_l()
V/AwesomePlayer(  252): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  252): notify(0xb77ad098, 8, 0, 0)
V/AudioCache(  252): ignored
V/AwesomePlayer(  252): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  252): mAudioTrackVector clear
I/OMXCodec(  252): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec(  252): [OMX.google.vorbis.decoder] stop() sendCommand(0x27, OMX_CommandStateSet, OMX_StateIdle)
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
V/MediaPlayer( 2390): decode(70, 30337076, 9400)
V/MediaPlayerService(  252): decode(30, 30337076, 9400)
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
V/StagefrightPlayer(  252): setDataSource(30, 30337076, 9400)
V/AwesomePlayer(  252): reset_l()
V/AwesomePlayer(  252): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  252): notify(0xb77a1e18, 8, 0, 0)
V/AudioCache(  252): ignored
V/AwesomePlayer(  252): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  252): mAudioTrackVector clear
V/AwesomePlayer(  252): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  252): mSecMediaClock clear
I/Process ( 2390): Sending signal. PID: 2390 SIG: 9
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
V/AudioCache(  252): notify(0xb77a1e18, 200, 973, 0)
V/AudioCache(  252): ignored
V/AwesomePlayer(  252): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  252): notify(0xb77a1e18, 5, 0, 0)
V/AudioCache(  252): ignored
V/AwesomePlayer(  252): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  252): notify(0xb77a1e18, 1, 0, 0)
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
E/IMemory (  252): binder=0xb77667e8 transaction failed fd=-2147483647, size=0, err=-32 (Broken pipe)
E/IMemory (  252): cannot dup fd=-2147483647, size=0, err=-32 (Bad file number)
E/IMemory (  252): cannot map BpMemoryHeap (binder=0xb77667e8), size=0, fd=-1 (Bad file number)
V/StagefrightPlayer(  252): reset
V/AwesomePlayer(  252): reset_l()
V/AwesomePlayer(  252): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  252): notify(0xb77a1e18, 8, 0, 0)
V/AudioCache(  252): ignored
V/AwesomePlayer(  252): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  252): mAudioTrackVector clear
V/AwesomePlayer(  252): reset_l() stop AudioSource since AudioPlayer not exist
I/OMXCodec(  252): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec(  252): [OMX.google.vorbis.decoder] stop() sendCommand(0x28, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec(  252): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
I/OMXCodec(  252): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/OMX     (  252): instance freeNode
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
I/ActivityManager(  745): Process com.sec.android.app.shealth (pid 2390) (adj 0) has died.
I/SELinux ( 2462): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 2462):  
I/SELinux ( 2462): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 2462):  
I/SELinux ( 2462):  
I/SELinux ( 2462): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 2462): [DEBUG] seapp_context_lookup: seinfoCategory = release
E/dalvikvm( 2462): >>>>> Normal User
E/dalvikvm( 2462): >>>>> com.sec.android.app.shealth [ userId:0 | appId:10035 ]
,E/SELinux ( 2462): [DEBUG] seapp_context_lookup: seinfoCategory = release
D/TimaKeyStoreProvider( 2462): in addTimaSignatureService
D/TimaKeyStoreProvider( 2462): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 2462): Added TimaKesytore provider
W/ActivityManager(  745): Permission Denial: getCurrentUser() from pid=2462, uid=10035 requires android.permission.INTERACT_ACROSS_USERS
W/ContextImpl( 2462): Implicit intents with startService are not safe: Intent { act=com.sec.android.service.health.cp.accesscontrol } android.content.ContextWrapper.bindService:529 com.samsung.android.sdk.health.content.ShealthAccessControl.startService:274 com.samsung.android.sdk.health.content.ShealthAccessControl.requestPermission:212 
E/Device Type Shared Preferences( 2462): Device Type Shared Preferences - getDeviceTypeChecked -true
E/Device Type Shared Preferences( 2462): Device Type Shared Preferences - not connecting to service
E/com.sec.android.app.shealth.SHealthApplication( 2462): ContentProvider is not null
V/MediaPlayer( 2462): decode(61, 33979084, 48105)
V/MediaPlayerService(  252): decode(33, 33979084, 48105)
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
V/StagefrightPlayer(  252): setDataSource(33, 33979084, 48105)
V/AwesomePlayer(  252): reset_l()
V/AwesomePlayer(  252): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  252): notify(0xb77a4b80, 8, 0, 0)
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
V/AudioCache(  252): notify(0xb77a4b80, 200, 973, 0)
V/AudioCache(  252): ignored
V/AwesomePlayer(  252): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  252): notify(0xb77a4b80, 5, 0, 0)
V/AudioCache(  252): ignored
V/AwesomePlayer(  252): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  252): notify(0xb77a4b80, 1, 0, 0)
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
V/AudioCache(  252): notify(0xb77a4b80, 6, 0, 0)
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
V/AudioCache(  252): notify(0xb77a4b80, 2, 0, 0)
V/AudioCache(  252): playback complete - thread will wake up later
V/AwesomePlayer(  252): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  252): notify(0xb77a4b80, 7, 0, 0)
V/AudioCache(  252): ignored
V/AwesomePlayer(  252): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer(  252): addBatteryData
V/AudioCache(  252): wait - success
V/StagefrightPlayer(  252): reset
V/AwesomePlayer(  252): reset_l()
V/AwesomePlayer(  252): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  252): notify(0xb77a4b80, 8, 0, 0)
V/AudioCache(  252): ignored
V/AwesomePlayer(  252): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  252): mAudioTrackVector clear
I/OMXCodec(  252): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec(  252): [OMX.google.vorbis.decoder] stop() sendCommand(0x29, OMX_CommandStateSet, OMX_StateIdle)
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
V/MediaPlayer( 2462): decode(63, 33914984, 10421)
V/MediaPlayerService(  252): decode(33, 33914984, 10421)
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
V/StagefrightPlayer(  252): setDataSource(33, 33914984, 10421)
V/AwesomePlayer(  252): reset_l()
V/AwesomePlayer(  252): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  252): notify(0xb77a7868, 8, 0, 0)
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
V/AudioCache(  252): notify(0xb77a7868, 200, 973, 0)
V/AudioCache(  252): ignored
V/AwesomePlayer(  252): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  252): notify(0xb77a7868, 5, 0, 0)
V/AudioCache(  252): ignored
V/AwesomePlayer(  252): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  252): notify(0xb77a7868, 1, 0, 0)
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
V/AudioCache(  252): notify(0xb77a7868, 6, 0, 0)
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
V/AudioCache(  252): notify(0xb77a7868, 2, 0, 0)
V/AudioCache(  252): playback complete - thread will wake up later
V/AwesomePlayer(  252): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  252): notify(0xb77a7868, 7, 0, 0)
V/AudioCache(  252): ignored
V/AwesomePlayer(  252): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer(  252): addBatteryData
V/AudioCache(  252): wait - success
V/StagefrightPlayer(  252): reset
V/AwesomePlayer(  252): reset_l()
V/AwesomePlayer(  252): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  252): notify(0xb77a7868, 8, 0, 0)
V/AudioCache(  252): ignored
V/AwesomePlayer(  252): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  252): mAudioTrackVector clear
I/OMXCodec(  252): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec(  252): [OMX.google.vorbis.decoder] stop() sendCommand(0x2a, OMX_CommandStateSet, OMX_StateIdle)
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
V/MediaPlayer( 2462): decode(64, 37457308, 34198)
V/MediaPlayerService(  252): decode(33, 37457308, 34198)
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
V/StagefrightPlayer(  252): setDataSource(33, 37457308, 34198)
V/AwesomePlayer(  252): reset_l()
V/AwesomePlayer(  252): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  252): notify(0xb77a9300, 8, 0, 0)
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
V/AudioCache(  252): notify(0xb77a9300, 200, 973, 0)
V/AudioCache(  252): ignored
V/AwesomePlayer(  252): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  252): notify(0xb77a9300, 5, 0, 0)
V/AudioCache(  252): ignored
V/AwesomePlayer(  252): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  252): notify(0xb77a9300, 1, 0, 0)
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
V/AudioCache(  252): notify(0xb77a9300, 6, 0, 0)
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
V/AudioCache(  252): notify(0xb77a9300, 2, 0, 0)
V/AudioCache(  252): playback complete - thread will wake up later
V/AwesomePlayer(  252): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  252): notify(0xb77a9300, 7, 0, 0)
V/AudioCache(  252): ignored
V/AwesomePlayer(  252): cancelPlayerEvents (keepNotifications=1)
V/AudioCache(  252): wait - success
V/StagefrightPlayer(  252): reset
V/AwesomePlayer(  252): addBatteryData
V/AwesomePlayer(  252): reset_l()
V/AwesomePlayer(  252): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  252): notify(0xb77a9300, 8, 0, 0)
V/AudioCache(  252): ignored
V/AwesomePlayer(  252): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  252): mAudioTrackVector clear
I/OMXCodec(  252): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec(  252): [OMX.google.vorbis.decoder] stop() sendCommand(0x2b, OMX_CommandStateSet, OMX_StateIdle)
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
V/MediaPlayer( 2462): decode(65, 33862452, 7405)
V/MediaPlayerService(  252): decode(33, 33862452, 7405)
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
V/StagefrightPlayer(  252): setDataSource(33, 33862452, 7405)
V/AwesomePlayer(  252): reset_l()
V/AwesomePlayer(  252): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  252): notify(0xb77add38, 8, 0, 0)
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
V/AudioCache(  252): notify(0xb77add38, 200, 973, 0)
V/AudioCache(  252): ignored
V/AwesomePlayer(  252): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  252): notify(0xb77add38, 5, 0, 0)
V/AudioCache(  252): ignored
V/AwesomePlayer(  252): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  252): notify(0xb77add38, 1, 0, 0)
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
V/AudioCache(  252): notify(0xb77add38, 6, 0, 0)
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
V/AudioCache(  252): notify(0xb77add38, 2, 0, 0)
V/AudioCache(  252): playback complete - thread will wake up later
V/AwesomePlayer(  252): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  252): notify(0xb77add38, 7, 0, 0)
V/AudioCache(  252): ignored
V/AwesomePlayer(  252): cancelPlayerEvents (keepNotifications=1)
V/AudioCache(  252): wait - success
V/StagefrightPlayer(  252): reset
V/AwesomePlayer(  252): addBatteryData
V/AwesomePlayer(  252): reset_l()
V/AwesomePlayer(  252): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  252): notify(0xb77add38, 8, 0, 0)
V/AudioCache(  252): ignored
V/AwesomePlayer(  252): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  252): mAudioTrackVector clear
I/OMXCodec(  252): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec(  252): [OMX.google.vorbis.decoder] stop() sendCommand(0x2c, OMX_CommandStateSet, OMX_StateIdle)
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
V/MediaPlayer( 2462): decode(66, 37547940, 5555)
V/MediaPlayerService(  252): decode(33, 37547940, 5555)
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
V/StagefrightPlayer(  252): setDataSource(33, 37547940, 5555)
V/AwesomePlayer(  252): reset_l()
V/AwesomePlayer(  252): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  252): notify(0xb77a4428, 8, 0, 0)
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
V/AudioCache(  252): notify(0xb77a4428, 200, 973, 0)
V/AudioCache(  252): ignored
V/AwesomePlayer(  252): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  252): notify(0xb77a4428, 5, 0, 0)
V/AudioCache(  252): ignored
V/AwesomePlayer(  252): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  252): notify(0xb77a4428, 1, 0, 0)
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
V/AudioCache(  252): notify(0xb77a4428, 6, 0, 0)
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
V/AudioCache(  252): notify(0xb77a4428, 2, 0, 0)
V/AudioCache(  252): playback complete - thread will wake up later
V/AwesomePlayer(  252): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  252): notify(0xb77a4428, 7, 0, 0)
V/AudioCache(  252): ignored
V/AwesomePlayer(  252): cancelPlayerEvents (keepNotifications=1)
V/AudioCache(  252): wait - success
V/StagefrightPlayer(  252): reset
V/AwesomePlayer(  252): addBatteryData
V/AwesomePlayer(  252): reset_l()
V/AwesomePlayer(  252): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  252): notify(0xb77a4428, 8, 0, 0)
V/AudioCache(  252): ignored
V/AwesomePlayer(  252): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  252): mAudioTrackVector clear
I/OMXCodec(  252): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec(  252): [OMX.google.vorbis.decoder] stop() sendCommand(0x2d, OMX_CommandStateSet, OMX_StateIdle)
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
V/MediaPlayer( 2462): decode(67, 30367732, 5085)
V/MediaPlayerService(  252): decode(33, 30367732, 5085)
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
V/StagefrightPlayer(  252): setDataSource(33, 30367732, 5085)
V/AwesomePlayer(  252): reset_l()
V/AwesomePlayer(  252): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  252): notify(0xb77a0cf8, 8, 0, 0)
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
V/AudioCache(  252): notify(0xb77a0cf8, 200, 973, 0)
V/AudioCache(  252): ignored
V/AwesomePlayer(  252): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  252): notify(0xb77a0cf8, 5, 0, 0)
V/AudioCache(  252): ignored
V/AwesomePlayer(  252): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  252): notify(0xb77a0cf8, 1, 0, 0)
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
V/AudioCache(  252): notify(0xb77a0cf8, 6, 0, 0)
V/AudioCache(  252): ignored
V/AwesomePlayer(  252): addBatteryData
V/MediaPlayerService(  252): wait for playback complete
D/AndroidRuntime( 2474): 
D/AndroidRuntime( 2474): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/SensorService(  745):   -0.0 -0.1 9.5
I/OMXCodec(  252): [OMX.google.vorbis.decoder] End Of Stream
V/AwesomePlayer(  252): postAudioEOS delayUs (0)
D/AndroidRuntime( 2474): CheckJNI is OFF
V/AwesomePlayer(  252): onCheckAudioStatus
V/AwesomePlayer(  252): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  252): onStreamDone
V/AwesomePlayer(  252): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  252): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  252): notify(0xb77a0cf8, 2, 0, 0)
V/AudioCache(  252): playback complete - thread will wake up later
V/AwesomePlayer(  252): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  252): notify(0xb77a0cf8, 7, 0, 0)
V/AudioCache(  252): ignored
V/AwesomePlayer(  252): cancelPlayerEvents (keepNotifications=1)
V/AudioCache(  252): wait - success
V/StagefrightPlayer(  252): reset
D/AndroidRuntime( 2474): setted country_code = Poland
V/AwesomePlayer(  252): addBatteryData
D/AndroidRuntime( 2474): setted countryiso_code = PL
V/AwesomePlayer(  252): reset_l()
V/AwesomePlayer(  252): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  252): notify(0xb77a0cf8, 8, 0, 0)
V/AudioCache(  252): ignored
V/AwesomePlayer(  252): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  252): mAudioTrackVector clear
D/AndroidRuntime( 2474): setted sales_code = XEO
D/AndroidRuntime( 2474): readGMSProperty: start
D/AndroidRuntime( 2474): readGMSProperty: already setted!!
I/OMXCodec(  252): [OMX.google.vorbis.decoder] stop mState=4
D/AndroidRuntime( 2474): readGMSProperty: end
D/AndroidRuntime( 2474): addProductProperty: start
I/OMXCodec(  252): [OMX.google.vorbis.decoder] stop() sendCommand(0x2e, OMX_CommandStateSet, OMX_StateIdle)
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
V/MediaPlayer( 2462): decode(68, 30372876, 21552)
V/MediaPlayerService(  252): decode(34, 30372876, 21552)
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
V/StagefrightPlayer(  252): setDataSource(34, 30372876, 21552)
V/AwesomePlayer(  252): reset_l()
V/AwesomePlayer(  252): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  252): notify(0xb779bb68, 8, 0, 0)
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
D/dalvikvm( 2474): Trying to load lib libjavacore.so 0x0
V/MediaPlayerService(  252): wait for prepare
V/AwesomePlayer(  252): onPrepareAsyncEvent
I/SecMediaClock(  252): SecMediaClock constructor
I/SecMediaClock(  252): reset
V/AwesomePlayer(  252): initAudioDecoder
V/AwesomePlayer(  252): checkOffloadExceptions is true
I/OMXCodec(  252): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
D/dalvikvm( 2474): Added shared lib libjavacore.so 0x0
I/OMX     (  252): mDispatchers.add
I/OMXCodec(  252): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec(  252): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec(  252): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec(  252): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/OMXCodec(  252): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer(  252): finishAsyncPrepare_l
V/AwesomePlayer(  252): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache(  252): notify(0xb779bb68, 200, 973, 0)
V/AudioCache(  252): ignored
V/AwesomePlayer(  252): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  252): notify(0xb779bb68, 5, 0, 0)
V/AudioCache(  252): ignored
V/AwesomePlayer(  252): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  252): notify(0xb779bb68, 1, 0, 0)
V/AudioCache(  252): prepared
D/dalvikvm( 2474): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 2474): Added shared lib libnativehelper.so 0x0
V/AudioCache(  252): wait - success
D/dalvikvm( 2474): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
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
V/AudioCache(  252): notify(0xb779bb68, 6, 0, 0)
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
V/AudioCache(  252): notify(0xb779bb68, 2, 0, 0)
V/AudioCache(  252): playback complete - thread will wake up later
V/AwesomePlayer(  252): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  252): notify(0xb779bb68, 7, 0, 0)
V/AudioCache(  252): ignored
V/AwesomePlayer(  252): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer(  252): addBatteryData
V/AudioCache(  252): wait - success
V/StagefrightPlayer(  252): reset
V/AwesomePlayer(  252): reset_l()
V/AwesomePlayer(  252): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  252): notify(0xb779bb68, 8, 0, 0)
V/AudioCache(  252): ignored
V/AwesomePlayer(  252): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  252): mAudioTrackVector clear
I/OMXCodec(  252): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec(  252): [OMX.google.vorbis.decoder] stop() sendCommand(0x2f, OMX_CommandStateSet, OMX_StateIdle)
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
V/MediaPlayer( 2462): decode(69, 37543652, 4230)
V/MediaPlayerService(  252): decode(33, 37543652, 4230)
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
V/StagefrightPlayer(  252): setDataSource(33, 37543652, 4230)
V/AwesomePlayer(  252): reset_l()
V/AwesomePlayer(  252): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  252): notify(0xb779d078, 8, 0, 0)
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
V/AudioCache(  252): notify(0xb779d078, 200, 973, 0)
V/AudioCache(  252): ignored
V/AwesomePlayer(  252): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  252): notify(0xb779d078, 5, 0, 0)
V/AudioCache(  252): ignored
V/AwesomePlayer(  252): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  252): notify(0xb779d078, 1, 0, 0)
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
V/AudioCache(  252): notify(0xb779d078, 6, 0, 0)
V/AudioCache(  252): ignored
I/AudioPlayer(  252): First fillBuffer call!!
V/AwesomePlayer(  252): addBatteryData
V/MediaPlayerService(  252): wait for playback complete
V/AwesomePlayer(  252): postAudioEOS delayUs (0)
V/AwesomePlayer(  252): onCheckAudioStatus
V/AwesomePlayer(  252): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  252): onStreamDone
V/AwesomePlayer(  252): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  252): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  252): notify(0xb779d078, 2, 0, 0)
V/AudioCache(  252): playback complete - thread will wake up later
V/AwesomePlayer(  252): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  252): notify(0xb779d078, 7, 0, 0)
V/AudioCache(  252): ignored
V/AwesomePlayer(  252): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer(  252): addBatteryData
V/AudioCache(  252): wait - success
V/StagefrightPlayer(  252): reset
V/AwesomePlayer(  252): reset_l()
V/AwesomePlayer(  252): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  252): notify(0xb779d078, 8, 0, 0)
V/AudioCache(  252): ignored
V/AwesomePlayer(  252): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  252): mAudioTrackVector clear
I/OMXCodec(  252): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec(  252): [OMX.google.vorbis.decoder] stop() sendCommand(0x30, OMX_CommandStateSet, OMX_StateIdle)
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
V/MediaPlayer( 2462): decode(70, 30337076, 9400)
V/MediaPlayerService(  252): decode(33, 30337076, 9400)
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
V/StagefrightPlayer(  252): setDataSource(33, 30337076, 9400)
V/AwesomePlayer(  252): reset_l()
V/AwesomePlayer(  252): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  252): notify(0xb779a070, 8, 0, 0)
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
V/AudioCache(  252): notify(0xb779a070, 200, 973, 0)
V/AudioCache(  252): ignored
V/AwesomePlayer(  252): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  252): notify(0xb779a070, 5, 0, 0)
V/AudioCache(  252): ignored
V/AwesomePlayer(  252): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  252): notify(0xb779a070, 1, 0, 0)
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
V/AudioCache(  252): notify(0xb779a070, 6, 0, 0)
V/AudioCache(  252): ignored
V/AwesomePlayer(  252): addBatteryData
V/MediaPlayerService(  252): wait for playback complete
I/SELinux ( 2531): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 2531):  
I/OMXCodec(  252): [OMX.google.vorbis.decoder] End Of Stream
V/AwesomePlayer(  252): postAudioEOS delayUs (0)
V/AwesomePlayer(  252): onCheckAudioStatus
V/AwesomePlayer(  252): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  252): onStreamDone
V/AwesomePlayer(  252): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  252): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  252): notify(0xb779a070, 2, 0, 0)
V/AudioCache(  252): playback complete - thread will wake up later
V/AwesomePlayer(  252): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  252): notify(0xb779a070, 7, 0, 0)
V/AudioCache(  252): ignored
V/AwesomePlayer(  252): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer(  252): addBatteryData
V/AudioCache(  252): wait - success
V/StagefrightPlayer(  252): reset
V/AwesomePlayer(  252): reset_l()
V/AwesomePlayer(  252): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  252): notify(0xb779a070, 8, 0, 0)
V/AudioCache(  252): ignored
V/AwesomePlayer(  252): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  252): mAudioTrackVector clear
I/OMXCodec(  252): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec(  252): [OMX.google.vorbis.decoder] stop() sendCommand(0x31, OMX_CommandStateSet, OMX_StateIdle)
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
V/MediaPlayer( 2462): decode(71, 33925464, 44276)
V/MediaPlayerService(  252): decode(33, 33925464, 44276)
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
V/StagefrightPlayer(  252): setDataSource(33, 33925464, 44276)
V/AwesomePlayer(  252): reset_l()
V/AwesomePlayer(  252): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  252): notify(0xb77ae2d8, 8, 0, 0)
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
V/AudioCache(  252): notify(0xb77ae2d8, 200, 973, 0)
V/AudioCache(  252): ignored
V/AwesomePlayer(  252): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  252): notify(0xb77ae2d8, 5, 0, 0)
V/AudioCache(  252): ignored
V/AwesomePlayer(  252): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  252): notify(0xb77ae2d8, 1, 0, 0)
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
I/AudioPlayer(  252):  Audioplayer kKeyAudioPCMFormat, read fail(2, 1)
V/AudioCache(  252): open(44100, 2, 0x0, 1, 4)
V/AwesomePlayer(  252): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache(  252): notify(0xb77ae2d8, 6, 0, 0)
V/AudioCache(  252): ignored
V/AwesomePlayer(  252): addBatteryData
V/MediaPlayerService(  252): wait for playback complete
I/AudioPlayer(  252): First fillBuffer call!!
E/memtrack( 2474): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 2474): failed to load memtrack module: -2
I/SELinux ( 2531): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 2531):  
I/SELinux ( 2531):  
I/SELinux ( 2531): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 2531): [DEBUG] seapp_context_lookup: seinfoCategory = samsung
E/dalvikvm( 2531): >>>>> Normal User
E/dalvikvm( 2531): >>>>> com.sec.android.app.sns3 [ userId:0 | appId:10036 ]
E/SELinux ( 2531): [DEBUG] seapp_context_lookup: seinfoCategory = samsung
D/TimaKeyStoreProvider( 2531): in addTimaSignatureService
D/TimaKeyStoreProvider( 2531): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 2531): Added TimaKesytore provider
D/dalvikvm( 2474): Note: class Landroid/app/ActivityManagerNative; has 192 unimplemented (abstract) methods
I/OMXCodec(  252): [OMX.google.vorbis.decoder] End Of Stream
V/AwesomePlayer(  252): postAudioEOS delayUs (0)
V/AwesomePlayer(  252): onCheckAudioStatus
V/AwesomePlayer(  252): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  252): onStreamDone
V/AwesomePlayer(  252): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  252): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  252): notify(0xb77ae2d8, 2, 0, 0)
V/AudioCache(  252): playback complete - thread will wake up later
V/AwesomePlayer(  252): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  252): notify(0xb77ae2d8, 7, 0, 0)
V/AudioCache(  252): ignored
V/AwesomePlayer(  252): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer(  252): addBatteryData
V/AudioCache(  252): wait - success
V/StagefrightPlayer(  252): reset
V/AwesomePlayer(  252): reset_l()
V/AwesomePlayer(  252): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  252): notify(0xb77ae2d8, 8, 0, 0)
V/AudioCache(  252): ignored
V/AwesomePlayer(  252): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  252): mAudioTrackVector clear
I/OMXCodec(  252): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec(  252): [OMX.google.vorbis.decoder] stop() sendCommand(0x32, OMX_CommandStateSet, OMX_StateIdle)
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
V/MediaPlayer( 2462): decode(72, 33885672, 29256)
V/MediaPlayerService(  252): decode(33, 33885672, 29256)
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
V/StagefrightPlayer(  252): setDataSource(33, 33885672, 29256)
V/AwesomePlayer(  252): reset_l()
V/AwesomePlayer(  252): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  252): notify(0xb77a4b80, 8, 0, 0)
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
V/AudioCache(  252): notify(0xb77a4b80, 200, 973, 0)
V/AudioCache(  252): ignored
V/AwesomePlayer(  252): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  252): notify(0xb77a4b80, 5, 0, 0)
V/AudioCache(  252): ignored
V/AwesomePlayer(  252): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  252): notify(0xb77a4b80, 1, 0, 0)
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
V/AudioCache(  252): notify(0xb77a4b80, 6, 0, 0)
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
V/AudioCache(  252): notify(0xb77a4b80, 2, 0, 0)
V/AudioCache(  252): playback complete - thread will wake up later
V/AwesomePlayer(  252): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  252): notify(0xb77a4b80, 7, 0, 0)
V/AudioCache(  252): ignored
V/AwesomePlayer(  252): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer(  252): addBatteryData
V/AudioCache(  252): wait - success
V/StagefrightPlayer(  252): reset
V/AwesomePlayer(  252): reset_l()
V/AwesomePlayer(  252): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  252): notify(0xb77a4b80, 8, 0, 0)
V/AudioCache(  252): ignored
V/AwesomePlayer(  252): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  252): mAudioTrackVector clear
I/OMXCodec(  252): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec(  252): [OMX.google.vorbis.decoder] stop() sendCommand(0x33, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec(  252): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
I/OMXCodec(  252): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/OMX     (  252): instance freeNode
I/AudioPlayer(  252): reset out
D/AndroidRuntime( 2474): Calling main entry com.android.commands.am.Am
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
V/MediaPlayer( 2462): decode(73, 37491572, 52024)
V/MediaPlayerService(  252): decode(34, 37491572, 52024)
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
V/StagefrightPlayer(  252): setDataSource(34, 37491572, 52024)
V/AwesomePlayer(  252): reset_l()
V/AwesomePlayer(  252): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  252): notify(0xb779bd28, 8, 0, 0)
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
V/AudioCache(  252): notify(0xb779bd28, 200, 973, 0)
V/AudioCache(  252): ignored
V/AwesomePlayer(  252): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  252): notify(0xb779bd28, 5, 0, 0)
V/AudioCache(  252): ignored
V/AwesomePlayer(  252): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  252): notify(0xb779bd28, 1, 0, 0)
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
V/AudioCache(  252): notify(0xb779bd28, 6, 0, 0)
V/AudioCache(  252): ignored
V/AwesomePlayer(  252): addBatteryData
V/MediaPlayerService(  252): wait for playback complete
V/ApplicationPolicy(  745): isApplicationStateBlocked userId 0 pkgname com.example.hello
D/CustomFrequencyManagerService(  745): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 745  pkgName : ACTIVITY_RESUME_BOOSTER@5
W/ActivityManager(  745): mDVFSHelper.acquire()
I/ServiceManager(  287): Waiting for service AtCmdFwd...
I/SurfaceFlinger(  249): id=15 createSurf (1x1),1 flag=404, iello
D/KeyguardUpdateMonitor( 1069): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1069): handleKeyguardVisibilityChanged(1)
I/OMXCodec(  252): [OMX.google.vorbis.decoder] End Of Stream
V/AwesomePlayer(  252): postAudioEOS delayUs (0)
V/AwesomePlayer(  252): onCheckAudioStatus
V/AwesomePlayer(  252): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  252): onStreamDone
V/AwesomePlayer(  252): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  252): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  252): notify(0xb779bd28, 2, 0, 0)
V/AudioCache(  252): playback complete - thread will wake up later
V/AwesomePlayer(  252): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  252): notify(0xb779bd28, 7, 0, 0)
V/AudioCache(  252): ignored
V/AwesomePlayer(  252): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer(  252): addBatteryData
V/AudioCache(  252): wait - success
V/StagefrightPlayer(  252): reset
V/AwesomePlayer(  252): reset_l()
V/AwesomePlayer(  252): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  252): notify(0xb779bd28, 8, 0, 0)
V/AudioCache(  252): ignored
V/AwesomePlayer(  252): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  252): mAudioTrackVector clear
I/OMXCodec(  252): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec(  252): [OMX.google.vorbis.decoder] stop() sendCommand(0x34, OMX_CommandStateSet, OMX_StateIdle)
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
V/MediaPlayer( 2462): decode(74, 33969800, 9226)
V/MediaPlayerService(  252): decode(33, 33969800, 9226)
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
V/StagefrightPlayer(  252): setDataSource(33, 33969800, 9226)
V/AwesomePlayer(  252): reset_l()
V/AwesomePlayer(  252): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  252): notify(0xb779bb68, 8, 0, 0)
V/AudioCache(  252): ignored
V/AwesomePlayer(  252): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  252): mAudioTrackVector clear
V/AwesomePlayer(  252): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  252): mSecMediaClock clear
D/KeyguardUpdateMonitor( 1069): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1069): handleKeyguardVisibilityChanged(1)
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
V/AudioCache(  252): notify(0xb779bb68, 200, 973, 0)
V/AudioCache(  252): ignored
V/AwesomePlayer(  252): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  252): notify(0xb779bb68, 5, 0, 0)
V/AudioCache(  252): ignored
V/AwesomePlayer(  252): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  252): notify(0xb779bb68, 1, 0, 0)
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
V/AudioCache(  252): notify(0xb779bb68, 6, 0, 0)
V/AudioCache(  252): ignored
V/AwesomePlayer(  252): addBatteryData
V/MediaPlayerService(  252): wait for playback complete
I/AudioPlayer(  252): First fillBuffer call!!
D/KeyguardUpdateMonitor( 1069): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1069): handleKeyguardVisibilityChanged(1)
I/OMXCodec(  252): [OMX.google.vorbis.decoder] End Of Stream
V/AwesomePlayer(  252): postAudioEOS delayUs (0)
V/AwesomePlayer(  252): onCheckAudioStatus
V/AwesomePlayer(  252): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  252): onStreamDone
V/AwesomePlayer(  252): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  252): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  252): notify(0xb779bb68, 2, 0, 0)
V/AudioCache(  252): playback complete - thread will wake up later
V/AwesomePlayer(  252): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  252): notify(0xb779bb68, 7, 0, 0)
V/AudioCache(  252): ignored
V/AwesomePlayer(  252): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer(  252): addBatteryData
V/AudioCache(  252): wait - success
V/StagefrightPlayer(  252): reset
V/AwesomePlayer(  252): reset_l()
V/AwesomePlayer(  252): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  252): notify(0xb779bb68, 8, 0, 0)
V/AudioCache(  252): ignored
V/AwesomePlayer(  252): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  252): mAudioTrackVector clear
I/OMXCodec(  252): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec(  252): [OMX.google.vorbis.decoder] stop() sendCommand(0x35, OMX_CommandStateSet, OMX_StateIdle)
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
V/MediaPlayer( 2462): decode(75, 30402580, 4509)
V/MediaPlayerService(  252): decode(33, 30402580, 4509)
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
V/StagefrightPlayer(  252): setDataSource(33, 30402580, 4509)
V/AwesomePlayer(  252): reset_l()
V/AwesomePlayer(  252): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  252): notify(0xb77a1160, 8, 0, 0)
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
V/AudioCache(  252): notify(0xb77a1160, 200, 973, 0)
V/AudioCache(  252): ignored
V/AwesomePlayer(  252): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  252): notify(0xb77a1160, 5, 0, 0)
V/AudioCache(  252): ignored
V/AwesomePlayer(  252): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  252): notify(0xb77a1160, 1, 0, 0)
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
I/AudioPlayer(  252):  Audioplayer kKeyAudioPCMFormat:1, 2, 0
I/AudioPlayer(  252):  Audioplayer kKeyAudioPCMFormat read fail(2, 1)
V/AudioCache(  252): open(44100, 2, 0x0, 1, 4)
V/AwesomePlayer(  252): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache(  252): notify(0xb77a1160, 6, 0, 0)
V/AudioCache(  252): ignored
V/AwesomePlayer(  252): addBatteryData
V/MediaPlayerService(  252): wait for playback complete
V/AwesomePlayer(  252): postAudioEOS delayUs (0)
V/AwesomePlayer(  252): onCheckAudioStatus
V/AwesomePlayer(  252): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  252): onStreamDone
V/AwesomePlayer(  252): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  252): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  252): notify(0xb77a1160, 2, 0, 0)
V/AudioCache(  252): playback complete - thread will wake up later
V/AwesomePlayer(  252): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  252): notify(0xb77a1160, 7, 0, 0)
V/AudioCache(  252): ignored
V/AwesomePlayer(  252): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer(  252): addBatteryData
V/AudioCache(  252): wait - success
V/StagefrightPlayer(  252): reset
V/AwesomePlayer(  252): reset_l()
V/AwesomePlayer(  252): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  252): notify(0xb77a1160, 8, 0, 0)
V/AudioCache(  252): ignored
V/AwesomePlayer(  252): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  252): mAudioTrackVector clear
I/OMXCodec(  252): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec(  252): [OMX.google.vorbis.decoder] stop() sendCommand(0x36, OMX_CommandStateSet, OMX_StateIdle)
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
I/WindowManager(  745): Screenshot max retries 4 of Token{4263ea20 ActivityRecord{42e61860 u0 com.sec.android.app.popupuireceiver/.BatteryCover t2}} appWin=Window{42e89ef0 u0 com.sec.android.app.popupuireceiver/com.sec.android.app.popupuireceiver.BatteryCover} drawState=4
W/WindowManager(  745): Screenshot failure taking screenshot for (720x1280) to layer 21005
D/LockPatternUtils( 1069): isPcwEnable = null
D/AndroidRuntime( 2474): Shutting down VM
D/dalvikvm( 2474): GC_CONCURRENT freed 97K, 13% free 717K/816K, paused 0ms+0ms, total 3ms
W/ActivityManager(  745): Permission Denial: getCurrentUser() from pid=2531, uid=10036 requires android.permission.INTERACT_ACROSS_USERS
I/SELinux ( 2575): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 2575):  
I/Process ( 2531): Sending signal. PID: 2531 SIG: 9
I/ActivityManager(  745): Process com.sec.android.app.sns3 (pid 2531) (adj 0) has died.
I/SELinux ( 2575): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 2575):  
I/SELinux ( 2575):  
I/SELinux ( 2575): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 2575): [DEBUG] seapp_context_lookup: seinfoCategory = default
E/dalvikvm( 2575): >>>>> Normal User
E/dalvikvm( 2575): >>>>> com.example.hello [ userId:0 | appId:10181 ]
E/SELinux ( 2575): [DEBUG] seapp_context_lookup: seinfoCategory = default
I/SELinux ( 2589): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 2589):  
D/TimaKeyStoreProvider( 2575): in addTimaSignatureService
D/TimaKeyStoreProvider( 2575): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 2575): Added TimaKesytore provider
D/Launcher.HomeView( 1252): onStop
D/SurfaceWidgetClient$ISurfaceWidgetStub( 1449): [237392/5] Surface widget pause on instance = 1
D/SurfaceWidgetClient$ISurfaceWidgetStub( 1449): [237392/5] Surface widget visibility changed visibility = false on instance = 1
D/accuweather( 1449): [KK AccuPhone]>>> SWW:224 [0:0] [SWW] onPause : instance = 1
D/accuweather( 1449): [KK AccuPhone]>>> SWW:239 [0:0] onPause : size = 0
D/accuweather( 1449): [KK AccuPhone]>>> SWW:517 [0:0]  unRegisterTTReceiver !! 
D/KeyguardUpdateMonitor( 1069): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1069): handleKeyguardVisibilityChanged(1)
D/LockPatternUtils( 1069): isPcwEnable = null
D/accuweather( 1449): [KK AccuPhone]>>> WR:149 [0:0] onPause
D/accuweather( 1449): [KK AccuPhone]>>> SM:526 [0:0] onPause
D/SurfaceWidgetView( 1252): destroyHardwareResources():1126822200
I/SELinux ( 2589): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 2589):  
I/SELinux ( 2589):  
I/SELinux ( 2589): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 2589): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 2589): >>>>> Normal User
E/dalvikvm( 2589): >>>>> com.policydm [ userId:0 | appId:1000 ]
E/SELinux ( 2589): [DEBUG] seapp_context_lookup: seinfoCategory = platform
D/KeyguardUpdateMonitor( 1069): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1069): handleKeyguardVisibilityChanged(1)
D/Launcher( 1252): onTrimMemory. Level: 20
D/TimaKeyStoreProvider( 2589): in addTimaSignatureService
D/TimaKeyStoreProvider( 2589): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 2589): Added TimaKesytore provider
W/ActivityManager(  745): Permission Denial: getCurrentUser() from pid=2575, uid=10181 requires android.permission.INTERACT_ACROSS_USERS
W/ActivityManager(  745): Permission Denial: getCurrentUser() from pid=2575, uid=10181 requires android.permission.INTERACT_ACROSS_USERS
V/WebViewChromium( 2575): Binding Chromium to the background looper Looper (main, tid 1) {423701f8}
I/chromium( 2575): [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserProcessMain( 2575): Initializing chromium process, renderers=0
D/BatteryService(  745): level:100, scale:100, status:5, health:2, present:true, voltage: 4362, temperature: 283, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:18, charge type:1, power sharing:false
D/BatteryService(  745): Sending ACTION_BATTERY_CHANGED.
D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1069): handleBatteryUpdate
D/UiModeManager(  745): mCoverManager.getCoverState() : true
D/PowerManagerService(  745): [api] acquire WakeLock flags=0x10000006 tag=PowerUI uid=10019 pid=1069
W/ContextImpl(  745): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1515 com.android.server.StatusBarManagerService.sendNotification:987 com.android.server.StatusBarManagerService.addNotification:676 com.android.server.NotificationManagerService$7.run:2157 android.os.Handler.handleCallback:733 
D/NotificationService(  745): Sending broadcast with sbn as extra = StatusBarNotification(pkg=com.android.systemui user=UserHandle{-1} id=5 tag=null score=0: Notification(pri=0 icon=7f0200dd contentView=com.android.systemui/0x1090080 vibrate=null sound=null defaults=0x0 flags=0x2 when=0 ledARGB=0x0 contentIntent=Y deleteIntent=N contentTitle=4 contentText=38 originalPackageName=N tickerText=38 kind=[null]))
D/STATUSBAR-StatusBarManagerService(  745): sendNotification(1) - 5
D/RCPManagerService(  745): NotificationReceiver onReceive()
D/RCPManagerService(  745):  NotificationReceiver sbn.getPackageName() com.android.systemui sbn.getUser().getIdentifier() -1
D/RCPManagerService(  745): getPolicy: Policy checking block entered for Notifications; for user/persona = -1 ; Policy = knox-sanitize-data ; token = 4294967296745
D/RCPManagerService(  745): getPolicy: policy value returned = false
D/RCPManagerService(  745): going to get the app label for pkg == com.android.systemui
D/RCPManagerService(  745): app label == com.android.systemui
D/RCPManagerService(  745): getPolicy: Policy checking block entered for Notifications; for user/persona = -1 ; Policy = knox-export-data ; token = 4294967296745
D/RCPManagerService(  745): getPolicy: policy value returned = true
D/RCPManagerService(  745): Calling User is -1
D/RCPManagerService(  745): userid of SBN ==-1
W/chromium( 2575): [WARNING:proxy_service.cc(888)] PAC support disabled because there is no system implementation
W/ContextImpl(  745): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1515 com.android.server.NotificationManagerService$7.run:2187 android.os.Handler.handleCallback:733 android.os.Handler.dispatchMessage:95 android.os.Looper.loop:146 
D/UserManagerService(  745): User -1does not exists!!
E/PersonaManagerService(  745): returning null in  getPersonasForUser
I/Adreno-EGL( 2575): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 2575): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 2575): Build Date: 03/21/14 Fri
I/Adreno-EGL( 2575): Local Branch: AU200+patches_03212014
I/Adreno-EGL( 2575): Remote Branch: 
I/Adreno-EGL( 2575): Local Patches: 
I/Adreno-EGL( 2575): Reconstruct Branch: 
D/STATUSBAR-PhoneStatusBar( 1069):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
D/BatteryMeterView( 1069): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/ProgressBar( 1069): setProgressDrawable drawableHeight = 12
D/PhoneStatusBar( 1069): tick(): knoxCustomManager = android.app.enterprise.knoxcustom.KnoxCustomManager@42398978
D/KeyguardViewMediator( 1069): handleKeyguardDoneDrawing
D/BatteryMeterView( 1069): onDraw batteryColor : -1
I/dalvikvm( 2575): Could not find method android.webkit.CookieManager.setAcceptThirdPartyCookies, referenced from method org.apache.cordova.engine.SystemCookieManager.<init>
W/dalvikvm( 2575): VFY: unable to resolve virtual method 168: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
D/dalvikvm( 2575): VFY: replacing opcode 0x6e at 0x0016
I/dalvikvm( 2575): Could not find method android.webkit.CookieManager.flush, referenced from method org.apache.cordova.engine.SystemCookieManager.flush
W/dalvikvm( 2575): VFY: unable to resolve virtual method 163: Landroid/webkit/CookieManager;.flush ()V
D/dalvikvm( 2575): VFY: replacing opcode 0x6e at 0x0008
W/dalvikvm( 2575): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 2575): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
I/dalvikvm( 2575): Could not find method android.webkit.WebViewClient.onReceivedClientCertRequest, referenced from method org.apache.cordova.engine.SystemWebViewClient.onReceivedClientCertRequest
W/dalvikvm( 2575): VFY: unable to resolve virtual method 221: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
D/dalvikvm( 2575): VFY: replacing opcode 0x6f at 0x001a
W/dalvikvm( 2575): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
I/dalvikvm( 2575): Could not find method android.webkit.PermissionRequest.getResources, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onPermissionRequest
W/dalvikvm( 2575): VFY: unable to resolve virtual method 179: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
D/dalvikvm( 2575): VFY: replacing opcode 0x6e at 0x000d
I/dalvikvm( 2575): Could not find method android.webkit.WebChromeClient$FileChooserParams.createIntent, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onShowFileChooser
W/dalvikvm( 2575): VFY: unable to resolve virtual method 184: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
D/dalvikvm( 2575): VFY: replacing opcode 0x6e at 0x0000
I/SELinux ( 2622): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 2622):  
D/SystemWebViewEngine( 2575): CordovaWebView is running on device made by: samsung
I/SELinux ( 2622): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 2622):  
I/SELinux ( 2622):  
I/SELinux ( 2622): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 2622): [DEBUG] seapp_context_lookup: seinfoCategory = samsung
E/dalvikvm( 2622): >>>>> Normal User
E/dalvikvm( 2622): >>>>> com.sec.spp.push [ userId:0 | appId:10038 ]
E/SELinux ( 2622): [DEBUG] seapp_context_lookup: seinfoCategory = samsung
D/TimaKeyStoreProvider( 2622): in addTimaSignatureService
D/TimaKeyStoreProvider( 2622): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 2622): Added TimaKesytore provider
D/KeyguardUpdateMonitor( 1069): sendKeyguardVisibilityChanged(true)
I/SurfaceFlinger(  249): id=16 createSurf (720x1280),1 flag=404, NainActivit
D/KeyguardUpdateMonitor( 1069): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1069): handleKeyguardVisibilityChanged(1)
D/KeyguardUpdateMonitor( 1069): handleKeyguardVisibilityChanged(1)
I/HWUI    ( 2575): EGLImpl-HWUI Protected EGL context created
D/OpenGLRenderer( 2575): Enabling debug mode 0
W/AwContents( 2575): nativeOnDraw failed; clearing to background color.
E/SPPClientService( 2622): ============PushLog. commonIsShipBuild. stop!
E/SPPClientService( 2622): [PushClientApplication] Push log off : This is Ship build version
D/SPPClientService( 2622): PushLog.txt file is not deleted.
D/KeyguardUpdateMonitor( 1069): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1069): handleKeyguardVisibilityChanged(1)
D/SPPClientService( 2622): PushLog.txt file is not deleted.
D/SPPClientService( 2622): ============PushLog. stop!
D/KeyguardUpdateMonitor( 1069): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1069): sendKeyguardVisibilityChanged(true)
I/SurfaceFlinger(  249): id=7 Removed Mauncher (8/13)
I/SurfaceFlinger(  249): id=7 Removed Mauncher (-2/13)
D/CustomFrequencyManagerService(  745): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 745  tag : ACTIVITY_RESUME_BOOSTER@5
W/ActivityManager(  745): mDVFSHelper.release()
D/CustomFrequencyManagerService(  745): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 745  pkgName : ACTIVITY_RESUME_BOOSTER@9
D/KeyguardUpdateMonitor( 1069): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1069): handleKeyguardVisibilityChanged(1)
D/KeyguardUpdateMonitor( 1069): handleKeyguardVisibilityChanged(1)
I/SurfaceFlinger(  249): id=15 Removed iello (9/12)
I/SurfaceFlinger(  249): id=15 Removed iello (-2/12)
D/SurfaceWidgetView( 1252): destroyHardwareResources():1126822200
D/KeyguardUpdateMonitor( 1069): sendKeyguardVisibilityChanged(true)
E/SPPClientService( 2622): [SystemStateMoniter] ACTION_BOOT_COMPLETED
D/KeyguardUpdateMonitor( 1069): handleKeyguardVisibilityChanged(1)
D/KeyguardUpdateMonitor( 1069): handleKeyguardVisibilityChanged(1)
I/SurfaceFlinger(  249): id=14 Removed CatteryCove (7/11)
I/SurfaceFlinger(  249): id=14 Removed CatteryCove (-2/11)
D/KeyguardUpdateMonitor( 1069): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1069): handleKeyguardVisibilityChanged(1)
D/KeyguardUpdateMonitor( 1069): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1069): handleKeyguardVisibilityChanged(1)
I/SELinux ( 2646): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 2646):  
I/SELinux ( 2646): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 2646):  
I/SELinux ( 2646):  
I/SELinux ( 2646): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 2646): [DEBUG] seapp_context_lookup: seinfoCategory = default
E/dalvikvm( 2646): >>>>> Normal User
E/dalvikvm( 2646): >>>>> com.osp.app.signin [ userId:0 | appId:10043 ]
I/ServiceManager(  287): Waiting for service AtCmdFwd...
E/SELinux ( 2646): [DEBUG] seapp_context_lookup: seinfoCategory = default
D/TimaKeyStoreProvider( 2646): in addTimaSignatureService
D/TimaKeyStoreProvider( 2646): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 2646): Added TimaKesytore provider
I/chromium( 2575): [INFO:CONSOLE(10)] "Viewport target-densitydpi is not supported.", source: file:///android_asset/www/index.html (10)
E/SMD     (  243): DCD ON
I/SA      ( 2646): [SSP] onCreated
E/AndroidProtocolHandler( 2575): Unable to open asset URL: file:///android_asset/www/jxcore.js
I/SA      ( 2646): [TPM] There is no property file
I/SA      ( 2646): [SCU] isHaveSA() - false
I/SA      ( 2646): [TPM] getModelProperty : null
I/SA      ( 2646): [TPM] getCSCProperty : null
I/SA      ( 2646): [SBR] StdBroadcastReceiver received Intent of  action_BOOT_COMPLETED
I/SA      ( 2646): [DM] init START
I/SA      ( 2646): [DM] This device is not a Vodafone
I/SA      ( 2646): [DM] getCountryCodeFromCSC : PL
I/SA      ( 2646): support phone number id : false
I/SA      ( 2646): [DM] init END
I/SA      ( 2646): [OR] onReceive log=[SA = 2.0.0117 V = 19 HWD = 1280X720 2.0 dpi = 320  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = kmini3g P = kmini3gxx I = KOT49H M = SM-G800H OKLEFT false DIS KOT49H.G800HXXU1ANK2 PSS = 4.497045606779314  ]
I/SA      ( 2646): [BDLM] already registered in spp
I/SA      ( 2646): [OR] onReceive Intent=[ action_BOOT_COMPLETED ]
I/SA      ( 2646): [OR] onReceive END
I/SA      ( 2646): [BDC] create
D/JsMessageQueue( 2575): Set native->JS mode to OnlineEventsBridgeMode
I/SA      ( 2646): [DBMV2] getEmailID
I/SA      ( 2646): [DBMV2] getDataV02ForItems
I/SA      ( 2646): [SSP] query invoked
I/SA      ( 2646): [SCU] get signed id from samsung account2.0 DB.
I/SA      ( 2646): [SCU] get signed id from samsung account1.0 DB.
I/SELinux ( 2667): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 2667):  
I/SA      ( 2646): [BDC] destroy
I/HarmonyEASService(  745): Updating for all 1
I/SELinux ( 2667): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 2667):  
I/SELinux ( 2667):  
I/SELinux ( 2667): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 2667): [DEBUG] seapp_context_lookup: seinfoCategory = release
E/dalvikvm( 2667): >>>>> Normal User
E/dalvikvm( 2667): >>>>> com.android.providers.calendar [ userId:0 | appId:10044 ]
E/SELinux ( 2667): [DEBUG] seapp_context_lookup: seinfoCategory = release
D/TimaKeyStoreProvider( 2667): in addTimaSignatureService
D/TimaKeyStoreProvider( 2667): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 2667): Added TimaKesytore provider
I/chromium( 2575): [INFO:async_pixel_transfer_manager_android.cc(56)] Async pixel transfers not supported
D/dalvikvm( 2575): Trying to load lib /data/app-lib/com.example.hello-2/libjxcore.so 0x42696ed0
D/dalvikvm( 2575): Added shared lib /data/app-lib/com.example.hello-2/libjxcore.so 0x42696ed0
D/jxcore_app_log( 2575): JniHelper::setJavaVM(0x4190b4f8), pthread_self() = 2028807776
D/JX-Cordova( 2575): jxcore cordova android initializing
I/chromium( 2575): [INFO:async_pixel_transfer_manager_android.cc(56)] Async pixel transfers not supported
,E/libGLESv2( 2575): HWUI Protection: wrong calling from app context F:ES3-glDeleteShader current id:202
,E/libGLESv2( 2575): HWUI Protection: wrong calling from app context F:ES3-glDeleteShader current id:202
,E/libGLESv2( 2575): HWUI Protection: wrong calling from app context F:ES3-glDeleteShader current id:202
,E/libGLESv2( 2575): HWUI Protection: wrong calling from app context F:ES3-glDeleteShader current id:202
,W/jxcore-log( 2575): Initializing JXcore engine
,W/jxcore-log( 2575): JXcore engine is ready
W/jxcore-log( 2575): Starting JXcore engine
,W/ActivityManager(  745): Permission Denial: getCurrentUser() from pid=2667, uid=10044 requires android.permission.INTERACT_ACROSS_USERS
,D/dalvikvm(  745): GC_EXPLICIT freed 2545K, 19% free 22769K/27832K, paused 4ms+11ms, total 125ms
,W/jxcore-log( 2575): Platform android
W/jxcore-log( 2575): 
,W/jxcore-log( 2575): Process ARCH arm
W/jxcore-log( 2575): 
,D/MediaScannerReceiver( 1207): action: android.intent.action.BOOT_COMPLETED
,I/jxcore-log( 2575): JXcore Cordova bridge is ready!
I/jxcore-log( 2575): 
,W/jxcore-log( 2575): JXcore engine is started
D/CustomFrequencyManagerService(  745): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 745  tag : ACTIVITY_RESUME_BOOSTER@9
,E/jxcore-log( 2575): >> samsung-SM-G800H
E/jxcore-log( 2575): 
,I/jxcore-log( 2575): Total memory 1454641152
I/jxcore-log( 2575): 
I/jxcore-log( 2575): Free memory 126906368
I/jxcore-log( 2575): 
I/jxcore-log( 2575): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 2575): 
,I/jxcore-log( 2575): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 2575): 
,I/jxcore-log( 2575): userPath [ 'rList-com.example.hello.MainActivity', 'www' ]
I/jxcore-log( 2575): 
,I/jxcore-log( 2575): Size 720 1280
I/jxcore-log( 2575): 
,I/jxcore-log( 2575): Screen Brightness 134
I/jxcore-log( 2575): 
,E/jxcore-log( 2575): Dummy Error Log.
E/jxcore-log( 2575): 
,D/MediaScannerService( 1207): !@start scanning volume internal: [/system/media]
,D/TP/MmsProvider( 1242): Update uri=content://mms, match=0
D/TP/MmsProvider( 1242): update , handleReadChangedBroadcast
,D/TP/MmsSmsProvider( 1242): need read changed broadcast:false
I/Mms:transaction( 1674): [MmsSystemEventReceiver] restorePduNotificationStatus count=0
,D/Mms/MessagingNotification( 1674): [start]    nonBlockingUpdateMessageIndicator()
,I/Mms/ReservationManager( 1674): resetAfterConnected()
,D/Mms/MessagingNotification( 1674): sDisableVibrateForCamera = false
,D/Mms/MessagingNotification( 1674): isBlockingModeEnable() = false
,D/Mms/TelephonyPermission( 1674): isDefault true
,D/TP/MmsSmsProvider( 1242): match 7:Elapsed time : 2.440 ms
,I/Mms/ReservationManager( 1674): getReservedSendMessageCount(): retMessageCount=0
,D/TP/MmsSmsProvider( 1242): match 200:Elapsed time : 4.286 ms
,I/SELinux ( 2690): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 2690):  
,D/Mms/TelephonyPermission( 1674): isDefault true
D/Mms/SmsReceiverService( 1674): [SMS]Receiver handleMessage : Action =android.intent.action.BOOT_COMPLETED
,D/Mms/SmsReceiverService( 1674): [start]    handleBootCompleted()
,D/TP/MmsSmsProvider( 1242): deleteConversation threadId: 9223372036854775806
,D/TP/MmsSmsProvider( 1242): delete URI_CONVERSATIONS_MESSAGES affectedRows=0
,W/Atfwd_Sendcmd(  287): AtCmdFwd service not published, waiting... retryCnt : 3
,D/TP/MmsSmsProvider( 1242): delete threadId: 9223372036854775806
I/SELinux ( 2690): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 2690):  
I/SELinux ( 2690):  
D/TP/MmsSmsProvider( 1242): need read changed broadcast:false
,I/SELinux ( 2690): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 2690): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 2690): >>>>> Normal User
,E/dalvikvm( 2690): >>>>> com.sec.android.app.safetyassurance [ userId:0 | appId:10050 ]
E/SELinux ( 2690): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/Mms/Conversation( 1674): deleteTempConversation(),deleted=0
,D/MediaScanner( 1207): Prescan. DB items number : 156 DB_FILES_NUMBER_CACHING_LIMITATION : 7000  Caching mode : true
D/BadgeProvider( 1338): query, [selection] : package='com.android.mms' AND class='com.android.mms.ui.ConversationComposer' AND extraData='base_extra_badge'
,D/SmsProvider( 1242): Update uri=content://sms/outbox, match=8
,D/TP/MmsSmsProvider( 1242): need read changed broadcast:false
D/Mms/SmsReceiverService( 1674): sendFirstQueuedMessage()
,D/Mms/SmsReceiverService( 1674): [SIM-1]sendFirstQueuedMessage()
,D/TimaKeyStoreProvider( 2690): in addTimaSignatureService
D/BadgeProvider( 1338): sendNotify entered. [uri] : content://com.sec.badge/apps/2
D/BadgeProvider( 1338): sendNotify, [notify] : null
D/BadgeProvider( 1338): update, [uri] : content://com.sec.badge/apps/2
D/BadgeProvider( 1338): update, [BadgeCount] : badgecount=0
,D/BadgeProvider( 1338): update, [UpdateCount] : 1
,D/Launcher.Model( 1252): reloadBadges entered.
D/Mms/MessagingNotification( 1674): setBadgeCount(), count=0
,D/MessagingNotification( 1674): remove alarm
,D/TimaKeyStoreProvider( 2690): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 2690): Added TimaKesytore provider
,D/Mms/MessagingNotification( 1674): updateAllHistoryAsRead()
,D/Mms/MessagingNotification( 1674): [end]    nonBlockingUpdateMessageIndicator()
,D/Mms/MessagingNotification( 1674): sDisableVibrateForCamera = false
,D/Mms/MessagingNotification( 1674): isBlockingModeEnable() = false
,D/Mms/TelephonyPermission( 1674): isDefault true
,D/TP/MmsSmsProvider( 1242): match 200:Elapsed time : 2.875 ms
,W/dalvikvm( 2690): Refusing to reopen boot DEX '/system/framework/seccamera.jar'
,D/SafetyAssuranceAppFeatures( 2690): init start
,I/SafetyAssuranceAppFeatures( 2690): mLoadBaiduMap:false
I/SafetyAssuranceAppFeatures( 2690): mFeatureEnableMultiSim true
,D/SafetyAssuranceAppFeatures( 2690): init end
,D/SafetyAssuranceReceiver( 2690): onReceive
,I/SafetyAssuranceApp( 2690): Acquire WL
,D/SafetyAssuranceConfig( 2690): getAppState : 1
D/SafetyAssuranceReceiver( 2690): onReceive - action:android.intent.action.BOOT_COMPLETED, currentAppState:1
,D/SafetyAssuranceReceiver( 2690): Init App state
,V/MediaScanner( 1207): processDirectory :  /system/media
,D/BadgeProvider( 1338): query, [selection] : package='com.android.mms' AND class='com.android.mms.ui.ConversationComposer' AND extraData='base_extra_badge'
,W/BackupManagerService(  745): dataChanged but no participant pkg='com.android.providers.settings' uid=10050
D/SafetyAssuranceConfig( 2690): setAppState : 1
D/SafetyAssuranceApp( 2690): topActivity's name is=.MainActivity
I/SafetyAssuranceApp( 2690): Release WL
,D/KeyguardViewMediator( 1069): handleKeyguardDoneDrawing
,D/Launcher.Model( 1252): reloadBadges entered.
D/BadgeProvider( 1338): sendNotify entered. [uri] : content://com.sec.badge/apps/2
D/BadgeProvider( 1338): sendNotify, [notify] : null
D/BadgeProvider( 1338): update, [uri] : content://com.sec.badge/apps/2
D/BadgeProvider( 1338): update, [BadgeCount] : badgecount=0
,D/BadgeProvider( 1338): update, [UpdateCount] : 1
,D/Mms/MessagingNotification( 1674): setBadgeCount(), count=0
,I/NetworkStatusReceiver( 1242): action: android.intent.action.BOOT_COMPLETED
,D/MessagingNotification( 1674): remove alarm
,D/Mms/MessagingNotification( 1674): updateAllHistoryAsRead()
,D/Mms/SmsReceiverService( 1674): [end]    handleBootCompleted()
D/NearbySettings( 1313): MountReceiver.onReceive - Create HandlerThread
,D/NearbySettings( 1313): MountReceiver.onReceive - Start HandlerThread
,D/NearbySettings( 1313): MountReceiver.onReceive - Create mPrefHandler
D/NearbySettings( 1313): MountReceiver.onReceive - ACTION: android.intent.action.BOOT_COMPLETED
V/NearbySettings( 1313): MountReceiver.mPrefHandler - 7002
I/NearbySettings( 1313): MountReceiver.onReceive - Path: (systemPath)/storage/emulated/0/Download, (internalPath)/storage/emulated/0/Download, (externalPath)/storage/extSdCard/Download
I/NearbySettings( 1313): MountReceiver.onReceive - Internal Path
,I/AccessibilityManagerService(  745): setmDNIeNegative (false)
,V/MediaScanner( 1207):  prescan time: 242ms (DB items: 156)
V/MediaScanner( 1207):     scan time: 120ms (Caching mode: true), (makeEntry time: 48ms ~40%),  (parsing time: 0ms ~0%),  (bitmapDecoding time: 0ms ~0%), (exifExtracting time : 0ms ~0%), (sefExtracting time : 0ms ~0%), (bulkInserter time : 0ms ~0%)
V/MediaScanner( 1207): postscan time: 0ms (bulkDeleter : 0), (delete DeadThumbnail time : 0ms)
V/MediaScanner( 1207):    total time: 362ms
,V/MediaScanner( 1207): checked files: 149  directories : 5  (I: 0, U: 0)
,D/MediaScanner( 1207): checkDefaultSounds
,D/MediaScanner( 1207): system alarm_alert  : Vwiurug_etwofi5wgg
,D/MediaScanner( 1207): OK. alarm_alert is already exist in setting DB.
,D/MediaScanner( 1207): system notification_sound  : K_Oprkltf5wgg
,D/MediaScanner( 1207): OK. notification_sound is already exist in setting DB.
,D/MediaScanner( 1207): system ringtone  : Wmfi_lpf_pwirywu5wgg
,D/MediaScanner( 1207): OK. ringtone is already exist in setting DB.
,D/MediaScanner( 1207): system ringtone_2  : Wmfi_lpf_pwirywu5wgg
,D/MediaScanner( 1207): OK. ringtone_2 is already exist in setting DB.
,D/MediaScanner( 1207): system notification_sound_2  : K_Oprkltf5wgg
,D/MediaScanner( 1207): OK. notification_sound_2 is already exist in setting DB.
,D/MediaScannerService( 1207): !@done scanning volume internal
,D/MediaScannerService( 1207): !@start scanning volume external: [/storage/emulated/0, /storage/extSdCard, /storage/Private, /storage/UsbDriveA, /storage/UsbDriveB, /storage/UsbDriveC, /storage/UsbDriveD, /storage/UsbDriveE, /storage/UsbDriveF]
,D/MediaProvider( 1207): savePlaylistTableInBulkDeleter started
,D/MediaProvider( 1207): savePlaylistTableInBulkDeleter started - audio_playlists_map_cache existed
,D/MediaProvider( 1207): savePlaylistTableInBulkDeleter started - audio_playlists_map_cache is empty
,D/MediaProvider( 1207): savePlaylistTableInBulkDeleter finished
,D/MediaProvider( 1207): savePlaylistTableInBulkDeleter started
,D/MediaProvider( 1207): savePlaylistTableInBulkDeleter started - audio_playlists_map_personal_cache existed
,D/MediaProvider( 1207): savePlaylistTableInBulkDeleter started - audio_playlists_map_personal_cache is empty
,D/MediaProvider( 1207): savePlaylistTableInBulkDeleter finished
,D/MediaScanner( 1207): Prescan. DB items number : 20 DB_FILES_NUMBER_CACHING_LIMITATION : 7000  Caching mode : true
,V/MediaScanner( 1207): processDirectory :  /storage/emulated/0
D/MediaScanner( 1207): Skipping:
,D/MediaScanner( 1207): 7klwibgf7fvntblfd7(75ebcf7
,D/MediaScanner( 1207): Skipping:
,D/MediaScanner( 1207): 7klwibgf7fvntblfd7(7Budiwrd7dblb7
,I/iu.UploadsManager( 1800): #reloadSettings(); account: -1; IU: disabled; IS: disabled; IS account: -1; photoWiFi: true; videoWiFi: true; roam: false; battery: true; size: STANDARD; maxMobile: 157286400
V/MediaScanner( 1207): processDirectory :  /storage/extSdCard
,W/MediaScanner( 1207): Error opening directory, reason : Permission denied.
,W/MediaScanner( 1207): 7klwibgf7fxlKdCbid7
,E/File    ( 1207): fail readDirectory() errno=2
,V/MediaScanner( 1207): pruneDeadThumbnailFiles... android.database.sqlite.SQLiteCursor@42771e70
,V/MediaScanner( 1207): /pruneDeadThumbnailFiles... android.database.sqlite.SQLiteCursor@42771e70
V/MediaScanner( 1207):  prescan time: 23ms (DB items: 20)
V/MediaScanner( 1207):     scan time: 44ms (Caching mode: true), (makeEntry time: 36ms ~81%),  (parsing time: 0ms ~0%),  (bitmapDecoding time: 0ms ~0%), (exifExtracting time : 0ms ~0%), (sefExtracting time : 0ms ~0%), (bulkInserter time : 0ms ~0%)
V/MediaScanner( 1207): postscan time: 10ms (bulkDeleter : 0), (delete DeadThumbnail time : 6ms)
V/MediaScanner( 1207):    total time: 77ms
V/MediaScanner( 1207): checked files: 3  directories : 17  (I: 0, U: 0)
,D/MediaScannerService( 1207): !@done scanning volume external
,D/MediaScannerService( 1207): send command to ssrm : REQ_DROP_CACHE
,I/jxcore-log( 2575): getBuffer is called!!!!
I/jxcore-log( 2575): 
,I/iu.UploadsManager( 1800): End new media; added: 0, uploading: 0, time: 61 ms
,W/Settings( 1313): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/SettingSearch/SearchIntentReceiver( 1313): action : android.intent.action.BOOT_COMPLETED
,I/SettingSearch/SearchIntentReceiver( 1313): search setting db init!!
,I/SettingSearch/SearchIntentReceiver( 1313): BOOT_COMPLETED call InitSerachDBThread thread start!
W/ContextImpl( 1313): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendOrderedBroadcast:1544 android.content.ContextWrapper.sendOrderedBroadcast:394 android.content.ContextWrapper.sendOrderedBroadcast:394 com.android.settings.settingssearch.SettingsSearchIntentReceiver.restoredb:40 com.android.settings.settingssearch.SettingsSearchIntentReceiver.onReceive:60 
,I/SELinux ( 2718): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 2718):  
,D/PhoneNumberLocatorBootCompletedReceiver( 1242): onReceive
,D/PhoneNumberLocatorBootCompletedReceiver( 1242): Phone number locator feature is dsiabled
,W/BackupManagerService(  745): dataChanged but no participant pkg='com.android.providers.settings' uid=1001
,I/BootupListener( 1242): mPendingNetworkManualSelection : false
,I/ManualSelectionReceiver( 1242): onReceive : Intent = Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.android.phone/.ManualSelectionReceiver (has extras) }
,D/KeyguardViewMediator( 1069): handleKeyguardDoneDrawing
,I/SELinux ( 2718): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 2718):  
I/SELinux ( 2718):  
,I/SELinux ( 2718): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 2718): [DEBUG] seapp_context_lookup: seinfoCategory = release
E/dalvikvm( 2718): >>>>> Normal User
,E/dalvikvm( 2718): >>>>> com.sec.providers.settingsearch [ userId:0 | appId:10160 ]
,I/SELinux ( 2722): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 2722):  
,E/SELinux ( 2718): [DEBUG] seapp_context_lookup: seinfoCategory = release
,D/TimaKeyStoreProvider( 2718): in addTimaSignatureService
,D/TimaKeyStoreProvider( 2718): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 2718): Added TimaKesytore provider
,I/SELinux ( 2722): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 2722):  
I/SELinux ( 2722):  
,I/SELinux ( 2722): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 2722): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 2722): >>>>> Normal User
,E/dalvikvm( 2722): >>>>> com.wssyncmldm [ userId:0 | appId:1000 ]
,E/SELinux ( 2722): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 2722): in addTimaSignatureService
,D/TimaKeyStoreProvider( 2722): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 2722): Added TimaKesytore provider
,W/ActivityManager(  745): Permission Denial: getCurrentUser() from pid=2718, uid=10160 requires android.permission.INTERACT_ACROSS_USERS
,W/ContextImpl(  745): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.android.server.ssrm.u.i:-1 com.android.server.ssrm.ai.run:-1 android.os.Handler.handleCallback:733 android.os.Handler.dispatchMessage:95 
,W/ContextImpl(  745): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/PowerManagerService(  745): [s] UserActivityState : 1 -> 0
I/PowerManagerService(  745): [PWL] On : 0 (39908 ms ago)
,I/PowerManagerService(  745): [PWL]  mStayOn: false  mWakeLockSummary & WAKE_LOCK_STAY_AWAKE: 20  mUserActivitySummary: 0x0
I/PowerManagerService(  745): [PWL]  SCREEN_DIM_WAKE_LOCK           'PowerUI' ACQUIRE_CAUSES_WAKEUP (uid=10019, pid=1069, ws=null) (elapsedTime=2323)
,D/DisplayPowerController(  745): animation target = 2 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,I/DBG_DM  ( 2722): [][Line:95][onCreate] 
,E/DBG_DM  ( 2722): BootingfileStream is null
,E/DBG_DM  ( 2722): xdmCreateBootingFilestream
D/PowerManagerService(  745): [s] mDisplayPowerControllerCallbacks : onStateChanged()
,D/lights  (  745): lcd : 2 +
D/RampAnimator(  745): Light Animator Finished currentValue=2
,I/DBG_DM  ( 2722): [3.19.140541][Line:718][xdmGetCheckWifiOnlyModel] isWifiOnly : false
,D/lights  (  745): lcd : 2 -
,I/DBG_DM  ( 2722): [3.19.140541][Line:744][xdmGetCheckDataOnly] Voice : true
,I/DBG_DM  ( 2722): [3.19.140541][Line:745][xdmGetCheckDataOnly] SMS : true
,I/DBG_DM  ( 2722): [3.19.140541][Line:746][xdmGetCheckDataOnly] isDataOnly : false
,D/SSRMv2:SIOP(  745): SIOP:: AP = 330, Delta = 20
,I/DBG_DM  ( 2722): [3.19.140541][Line:139][xdmCheckFeatureRoamingWifiOnly] get SecProductFeature
,I/DBG_DM  ( 2722): [3.19.140541][Line:154][xdmCheckFeatureRoamingUnableNetworkMsg] get SecProductFeature
,D/SensorService(  745):   -0.0 -0.1 9.6
,I/DBG_DM  ( 2722): [3.19.140541][Line:36][onCreate] myUserId : 0
,I/DBG_DM  ( 2722): [3.19.140541][Line:2663][xdmDbsqlGetFUMOStatus] xdbsqlGetFUMOStatus : 0
,I/DBG_DM  ( 2722): [3.19.140541][Line:2702][xdmdbsqlGetDownloadPostponeStatus] xdbsqlGetDownloadPostponeStatus : 0
,I/DBG_DM  ( 2722): [3.19.140541][Line:2586][xdmGetUpdateReport] wssGetUpdateReport : 0
,I/DBG_DM  ( 2722): [3.19.140541][Line:99][onCreate] DMApplication NOT Start !
,I/DBG_DM  ( 2722): [3.19.140541][Line:139][onReceive] android.intent.action.BOOT_COMPLETED
,D/OverheatReceiver( 1069): onReceive() getAction : android.intent.action.BOOT_COMPLETED
D/OverheatReceiver( 1069): into the SAFE_MODE_ACTION
,D/OverheatReceiver( 1069): VZW on -> change to Global UX [safe mode]
,D/OverheatReceiver( 1069): isSafeMode = false
,E/Tethering(  745): No numeric data
,E/Tethering(  745): No numeric data
,E/Tethering(  745): No numeric data
,E/Tethering(  745): No numeric data
,E/Tethering(  745): No numeric data
,E/Tethering(  745): No numeric data
I/ConnectivityService(  745): defaultVal : 1, tetherEnabledInSettings : true
I/ConnectivityService(  745): defaultVal : 1, tetherEnabledInSettings : true
I/ConnectivityService(  745): defaultVal : 1, tetherEnabledInSettings : true
I/ConnectivityService(  745): defaultVal : 1, tetherEnabledInSettings : true
I/ConnectivityService(  745): defaultVal : 1, tetherEnabledInSettings : true
I/ConnectivityService(  745): defaultVal : 1, tetherEnabledInSettings : true
,D/LocationManagerService(  745): getProviders()=[passive]
,E/Tethering(  745): No numeric data
,E/Tethering(  745): No numeric data
,E/Tethering(  745): No numeric data
I/ConnectivityService(  745): defaultVal : 1, tetherEnabledInSettings : true
I/ConnectivityService(  745): defaultVal : 1, tetherEnabledInSettings : true
I/ConnectivityService(  745): defaultVal : 1, tetherEnabledInSettings : true
,E/Tethering(  745): No numeric data
,V/NFC     ( 1313): this device does not have NFC support
,V/NFC     ( 1313): this device does not have NFC support
V/NFC     ( 1313): this device does not have NFC support
,V/NFC     ( 1313): this device does not have NFC support
I/ConnectivityService(  745): defaultVal : 1, tetherEnabledInSettings : true
,I/ContactAccountLoggerTas( 2149): canRun() : Opted Out
,V/VibratorService(  745): hasVibrator - useVibetonz: false
,I/Velvet.VelvetFactory( 2149): checking for language pack updates
,W/dalvikvm( 2149): method Lcom/google/android/search/core/state/QueryState;.a incorrectly overrides package-private method with same name in Lcfl;
,D/WifiDisplayAdapter(  745): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,D/WifiDisplayAdapter(  745): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
I/AudioService(  745): getStreamVolume 3 index 0
I/MediaRouter( 2149): Found default route: MediaRouter.RouteInfo{ uniqueId=android/kb:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=0, volumeMax=15, presentationDisplayId=-1, extras=null, providerPackageName=android }
,D/LockPatternUtils( 1069): isPcwEnable = null
,I/Velvet.VelvetFactory( 2149): refreshing search history.
D/WifiDisplayAdapter(  745): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,D/LockPatternUtils( 1069): isPcwEnable = null
,I/SELinux ( 2762): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 2762):  
,D/dalvikvm(  250): GC_EXPLICIT freed 44K, 50% free 9508K/18756K, paused 2ms+3ms, total 28ms
,D/dalvikvm(  250): GC_EXPLICIT freed <1K, 50% free 9508K/18756K, paused 2ms+2ms, total 21ms
,I/SELinux ( 2762): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 2762):  
I/SELinux ( 2762):  
,I/SELinux ( 2762): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 2762): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 2762): >>>>> Normal User
,E/dalvikvm( 2762): >>>>> com.samsung.android.intelligenceservice [ userId:0 | appId:10005 ]
,E/SELinux ( 2762): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,V/WebViewChromium( 2149): Binding Chromium to the main looper Looper (main, tid 1) {42376990}
,D/dalvikvm(  250): GC_EXPLICIT freed <1K, 50% free 9508K/18756K, paused 2ms+3ms, total 22ms
,I/chromium( 2149): [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
,I/ContactAccountLoggerTas( 2149): canRun() : Opted Out
,I/BrowserProcessMain( 2149): Initializing chromium process, renderers=0
,I/LockPatternUtils( 1313): isSmartCardAuthenticationAvailable: false
,D/TimaKeyStoreProvider( 2762): in addTimaSignatureService
,D/TimaKeyStoreProvider( 2762): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 2762): Added TimaKesytore provider
,I/ContactAccountLoggerTas( 2149): canRun() : Opted Out
,W/GAV2    ( 2149): Thread[Background Non-Blocking-1,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,W/chromium( 2149): [WARNING:proxy_service.cc(888)] PAC support disabled because there is no system implementation
,W/GAV2    ( 2149): Thread[Background Non-Blocking-1,5,main]: dispatch call queued.  Need to call GAServiceManager.getInstance().initialize().
,I/ContactAccountLoggerTas( 2149): canRun() : Opted Out
,I/ContactAccountLoggerTas( 2149): canRun() : Opted Out
,I/Adreno-EGL( 2149): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 2149): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 2149): Build Date: 03/21/14 Fri
I/Adreno-EGL( 2149): Local Branch: AU200+patches_03212014
I/Adreno-EGL( 2149): Remote Branch: 
I/Adreno-EGL( 2149): Local Patches: 
I/Adreno-EGL( 2149): Reconstruct Branch: 
,D/dalvikvm(  745): GC_EXPLICIT freed 1059K, 19% free 22718K/27832K, paused 10ms+12ms, total 156ms
,D/PackageManager(  745): [MSG] MCS_UNBIND
I/PackageManager(  745): calling disconnectService()
,D/PackageManager(  745): Trying to unbind to DefaultContainerService
,D/UserAnalysis.PlaceProvider( 2762): Create SecureDbHelper
,D/UserAnalysis.UserAnalysisBroadcastReceiver( 2762): Create SecureDbHelper
W/ActivityManager(  745): Permission Denial: getCurrentUser() from pid=2762, uid=10005 requires android.permission.INTERACT_ACROSS_USERS
,I/SQLiteSecureOpenHelper( 2762): getReadableDatabase(pwd)
,I/SQLiteSecureOpenHelper( 2762): getDatabaseLocked(b,b,pwd)...
,I/SQLiteSecureOpenHelper( 2762): Open Place.db in secure mode
V/VibratorService(  745): hasVibrator - useVibetonz: false
,D/dalvikvm( 2149): GC_CONCURRENT freed 6350K, 41% free 11246K/18756K, paused 3ms+5ms, total 40ms
,W/NetworkUtils( 2149): OkHttp exception
,I/ContactAccountLoggerTas( 2149): canRun() : Opted Out
,I/LockPatternUtils( 1313): isSmartCardAuthenticationAvailable: false
,I/SQLiteSecureOpenHelper( 2762): ...getDatabaseLocked(b,b,pwd)
D/SQLiteSecureOpenHelper( 2762): ...getDatabaseLocked(b,b,pwd)
I/SQLiteSecureOpenHelper( 2762): getWritableDatabase(pwd)
,I/SQLiteSecureOpenHelper( 2762): getDatabaseLocked(b,b,pwd)...
,D/UserAnalysis.CarAnalyzer( 2762): Create SecureDbHelper
,I/SQLiteSecureOpenHelper( 2762): getWritableDatabase(pwd)
I/SQLiteSecureOpenHelper( 2762): getDatabaseLocked(b,b,pwd)...
,I/SQLiteSecureOpenHelper( 2762): Open Place.db in secure mode
,I/SQLiteSecureOpenHelper( 2762): ...getDatabaseLocked(b,b,pwd)
,D/SQLiteSecureOpenHelper( 2762): ...getDatabaseLocked(b,b,pwd)
,I/SELinux ( 2794): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 2794):  
,I/SELinux ( 2794): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 2794):  
I/SELinux ( 2794):  
,I/SELinux ( 2794): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 2794): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 2794): >>>>> Normal User
,E/dalvikvm( 2794): >>>>> com.samsung.android.scloud.backup [ userId:0 | appId:10060 ]
,E/SELinux ( 2794): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 2794): in addTimaSignatureService
,D/TimaKeyStoreProvider( 2794): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 2794): Added TimaKesytore provider
,E/SMD     (  243): DCD ON
,W/ContextImpl( 1313): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendOrderedBroadcast:1544 android.content.ContextWrapper.sendOrderedBroadcast:394 android.content.ContextWrapper.sendOrderedBroadcast:394 com.android.settings.settingssearch.SettingsSearchIntentReceiver$InitSerachDBThread.run:129 <bottom of call stack> 
I/SettingSearch/SearchIntentReceiver( 1313): InitSerachDBThread thread end!
,I/sCloudBackupApp( 2794): sCloudBackupApp Version Info : 3.7.3.KK_APP
,I/SELinux ( 2810): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 2810):  
,I/SELinux ( 2810): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 2810):  
I/SELinux ( 2810):  
,I/SELinux ( 2810): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 2810): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 2810): >>>>> Normal User
,E/dalvikvm( 2810): >>>>> com.samsung.android.scloud.sync [ userId:0 | appId:10062 ]
,E/SELinux ( 2810): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 2810): in addTimaSignatureService
,D/TimaKeyStoreProvider( 2810): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 2810): Added TimaKesytore provider
,W/ActivityManager(  745): Permission Denial: getCurrentUser() from pid=2810, uid=10062 requires android.permission.INTERACT_ACROSS_USERS
,I/SELinux ( 2826): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 2826):  
,W/BackupManagerService(  745): dataChanged but no participant pkg='com.android.providers.settings' uid=10062
,W/BackupManagerService(  745): dataChanged but no participant pkg='com.android.providers.settings' uid=10062
,D/KeyguardViewMediator( 1069): handleKeyguardDoneDrawing
,D/KeyguardViewMediator( 1069): handleKeyguardDoneDrawing
,I/SELinux ( 2826): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 2826):  
I/SELinux ( 2826):  
,I/SELinux ( 2826): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 2826): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 2826): >>>>> Normal User
,E/dalvikvm( 2826): >>>>> com.wssnps [ userId:0 | appId:1000 ]
,E/SELinux ( 2826): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 2826): in addTimaSignatureService
,D/TimaKeyStoreProvider( 2826): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 2826): Added TimaKesytore provider
,D/NPS_WSSNPS( 2826): [] android.intent.action.BOOT_COMPLETED
W/ContextImpl( 2826): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1857 android.content.ContextWrapper.startService:506 android.content.ContextWrapper.startService:506 com.wssnps.smlNpsReceiver.onReceive:380 android.app.ActivityThread.handleReceiver:2698 
,D/NPS_WSSNPS( 2826): [] Service onCreate!!
,I/SELinux ( 2838): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 2838):  
,D/NPS_WSSNPS( 2826): [] NpsServiceTask Start
,I/NPS_WSSNPS( 2826): [44.140541] loadCryptionkeyLibrary
,I/NPS_WSSNPS( 2826): [44.140541] FirstLoad Or Not Exist
,D/dalvikvm( 2826): Trying to load lib /data/data/com.wssnps/files/libCryptionkey.so 0x42698690
,D/dalvikvm( 2826): Added shared lib /data/data/com.wssnps/files/libCryptionkey.so 0x42698690
,D/NPS_WSSNPS( 2826): [44.140541] smlDBHelper
,I/NPS_WSSNPS( 2826): [44.140541] AsyncBulkFlagCheck
,I/NPS_WSSNPS( 2826): [44.140541] IsRemain_AsyncBulkCheck
,I/NPS_WSSNPS( 2826): [44.140541] IsRemain_Asyncing nothing
,D/NPS_WSSNPS( 2826): [44.140541] Service onDestroy
,I/NPS_WSSNPS( 2826): [44.140541] smlBRConfigurationDelete
,I/NPS_WSSNPS( 2826): [44.140541] smlBRMessageDelete
,I/NPS_WSSNPS( 2826): [44.140541] smlBREmailDelete
,I/NPS_WSSNPS( 2826): [44.140541] smlBRNetworkDelete
,W/ContextImpl( 2826): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:1863 android.content.ContextWrapper.stopService:511 com.wssnps.smlNpsService$1.run:108 java.util.Timer$TimerImpl.run:284 <bottom of call stack> 
I/NPS_WSSNPS( 2826): [44.140541] smlBRCallLogDelete
I/NPS_WSSNPS( 2826): [44.140541] smlBRMiniDiaryDelete
I/NPS_WSSNPS( 2826): [44.140541] smlBRPenMemoMDelete
I/NPS_WSSNPS( 2826): [44.140541] smlBRSMemoDelete
I/NPS_WSSNPS( 2826): [44.140541] cpuBooster release : false
D/NPS_WSSNPS( 2826): [44.140541] dsServerSocket close
I/SELinux ( 2838): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 2838):  
I/SELinux ( 2838):  
I/SELinux ( 2838): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 2838): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 2838): >>>>> Normal User
E/dalvikvm( 2838): >>>>> com.samsung.android.app.accesscontrol [ userId:0 | appId:10064 ]
E/SELinux ( 2838): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 2838): in addTimaSignatureService
,D/TimaKeyStoreProvider( 2838): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 2838): Added TimaKesytore provider
,D/AmoledAdjustTimer(  745): prevTemp = 281, currTemp = 283, prevStep = 4, currStep = 4
,I/SELinux ( 2854): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 2854):  
I/ActivityManager(  745): Killing 1290:com.sec.android.provider.emergencymode/u0a96 (adj 15): empty #43
,I/SELinux ( 2854): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 2854):  
I/SELinux ( 2854):  
,I/SELinux ( 2854): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 2854): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 2854): >>>>> Normal User
,E/dalvikvm( 2854): >>>>> com.sec.android.app.FileShareServer [ userId:0 | appId:10069 ]
,E/SELinux ( 2854): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 2854): in addTimaSignatureService
,D/TimaKeyStoreProvider( 2854): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 2854): Added TimaKesytore provider
,D/FileShare-Server( 2854): ServerBroadcastReceiver.onReceive - action android.intent.action.BOOT_COMPLETED // null
,I/SELinux ( 2868): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 2868):  
I/ActivityManager(  745): Killing 1277:com.android.printspooler/u0a144 (adj 15): empty #43
,I/SELinux ( 2868): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 2868):  
I/SELinux ( 2868):  
,I/SELinux ( 2868): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 2868): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 2868): >>>>> Normal User
,E/dalvikvm( 2868): >>>>> com.sec.android.nearby.mediaserver [ userId:0 | appId:10070 ]
,E/SELinux ( 2868): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 2868): in addTimaSignatureService
,D/TimaKeyStoreProvider( 2868): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 2868): Added TimaKesytore provider
,I/AllShare(ASF-DMSLIB)( 2868): DMSReceiver.onReceive - android.intent.action.BOOT_COMPLETED
,W/BackupManagerService(  745): dataChanged but no participant pkg='com.android.providers.settings' uid=10070
,D/KeyguardViewMediator( 1069): handleKeyguardDoneDrawing
I/SELinux ( 2881): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 2881):  
I/ActivityManager(  745): Killing 1722:com.sec.android.app.SecSetupWizard/1000 (adj 15): empty #43
,I/SELinux ( 2881): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 2881):  
I/SELinux ( 2881):  
,I/SELinux ( 2881): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 2881): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 2881): >>>>> Normal User
,E/dalvikvm( 2881): >>>>> com.samsung.android.app.assistantmenu [ userId:0 | appId:1000 ]
,E/SELinux ( 2881): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 2881): in addTimaSignatureService
,D/TimaKeyStoreProvider( 2881): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 2881): Added TimaKesytore provider
,W/ContextImpl( 2881): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1857 android.content.ContextWrapper.startService:506 android.content.ContextWrapper.startService:506 com.samsung.android.app.assistantmenu.AssistantMenuReceiver.onReceive:61 android.app.ActivityThread.handleReceiver:2698 
,I/SELinux ( 2894): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 2894):  
,I/SELinux ( 2894): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 2894):  
I/SELinux ( 2894):  
,I/SELinux ( 2894): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 2894): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 2894): >>>>> Normal User
E/dalvikvm( 2894): >>>>> com.sec.android.app.bluetoothtest [ userId:0 | appId:1000 ]
E/SELinux ( 2894): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 2894): in addTimaSignatureService
,D/TimaKeyStoreProvider( 2894): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 2894): Added TimaKesytore provider
,D/BluetoothBDAdrressReceiver( 2894): onReceive(), action: android.intent.action.BOOT_COMPLETED
,W/ContextImpl( 2894): Implicit intents with startService are not safe: Intent { act=com.bluetoothtestapp.BtBDstartservice.BootComplete } android.content.ContextWrapper.startService:506 android.content.ContextWrapper.startService:506 com.sec.android.app.bluetoothtest.BluetoothBDAdrressReceiver.onReceive:19 
W/ContextImpl( 2894): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1857 android.content.ContextWrapper.startService:506 android.content.ContextWrapper.startService:506 com.sec.android.app.bluetoothtest.BluetoothBDAdrressReceiver.onReceive:19 android.app.ActivityThread.handleReceiver:2698 
,D/BluetoothBDTestService( 1242): onCreate()
,E/BluetoothBDTestService( 1242): onStart(), action: com.bluetoothtestapp.BtBDstartservice.BootComplete
,E/BluetoothBDTestService( 1242): bd_address_path: /efs/bluetooth/bt_addr
,E/BluetoothBDTestService( 1242): already exist!( /efs/bluetooth/bt_addr ), file length: 17
,I/SELinux ( 2906): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 2906):  
,I/ActivityManager(  745): Killing 1735:com.sec.modem.settings/1000 (adj 15): empty #43
,I/SELinux ( 2906): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 2906):  
I/SELinux ( 2906):  
,I/SELinux ( 2906): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 2906): [DEBUG] seapp_context_lookup: seinfoCategory = default
E/dalvikvm( 2906): >>>>> Normal User
,E/dalvikvm( 2906): >>>>> com.blurb.checkout [ userId:0 | appId:10075 ]
,E/SELinux ( 2906): [DEBUG] seapp_context_lookup: seinfoCategory = default
,D/TimaKeyStoreProvider( 2906): in addTimaSignatureService
,D/TimaKeyStoreProvider( 2906): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 2906): Added TimaKesytore provider
,W/ActivityManager(  745): Permission Denial: getCurrentUser() from pid=2906, uid=10075 requires android.permission.INTERACT_ACROSS_USERS
,I/SELinux ( 2922): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 2922):  
I/ActivityManager(  745): Killing 1747:com.sec.tcpdumpservice/1000 (adj 15): empty #43
,I/SELinux ( 2922): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 2922):  
I/SELinux ( 2922):  
,I/SELinux ( 2922): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 2922): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 2922): >>>>> Normal User
,E/dalvikvm( 2922): >>>>> com.sec.knox.bridge [ userId:0 | appId:1000 ]
,E/SELinux ( 2922): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 2922): in addTimaSignatureService
I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.sec.android.gallery3d.app.GalleryActivity
,I/AMMetaDataParserService( 2881): Resource data:Inside bundle  check
,D/TimaKeyStoreProvider( 2922): Cannot add TimaSignature Service, License check Failed
I/AMMetaDataParserService( 2881): getResourcePackageName:android.app.searchable
,I/AMMetaDataParserService( 2881): Resource data:2131165197
,D/ActivityThread( 2922): Added TimaKesytore provider
,I/AMMetaDataParserService( 2881): getResourceName:com.sec.android.gallery3d:xml/gallery_searchable
,I/AMMetaDataParserService( 2881): getResourceTypeNamexml
,I/AMMetaDataParserService( 2881): getResourcePackageName:assistant
,I/AMMetaDataParserService( 2881): Resource data:2131165194
,I/AMMetaDataParserService( 2881): getResourceName:com.sec.android.gallery3d:xml/assistant
,I/AMMetaDataParserService( 2881): getResourceTypeNamexml
,I/AMMetaDataParserService( 2881): Icon data: ResourceDrawer2131624995android.intent.action.drawer2130837586
,E/PersonaManagerService(  745): returning null in  getPersonasForUser
,I/AMMetaDataParserService( 2881): Icon data: ResourceSlideshow2131624009android.intent.action.slideshow2130837584
,I/SELinux ( 2934): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 2934):  
I/ActivityManager(  745): Killing 1774:com.sec.android.widgetapp.activeapplicationwidget/u0a152 (adj 15): empty #43
,D/dalvikvm(  250): GC_EXPLICIT freed 45K, 50% free 9508K/18756K, paused 2ms+2ms, total 29ms
,D/dalvikvm(  250): GC_EXPLICIT freed <1K, 50% free 9508K/18756K, paused 1ms+3ms, total 18ms
I/SELinux ( 2934): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 2934):  
I/SELinux ( 2934):  
,I/SELinux ( 2934): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 2934): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 2934): >>>>> Normal User
,E/dalvikvm( 2934): >>>>> com.sec.android.app.clockpackage [ userId:0 | appId:10084 ]
,E/SELinux ( 2934): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,I/AMMetaDataParserService( 2881): Icon data: ResourceCamera2131624012android.intent.action.camera2130837583
D/TimaKeyStoreProvider( 2934): in addTimaSignatureService
,D/dalvikvm(  250): GC_EXPLICIT freed <1K, 50% free 9508K/18756K, paused 2ms+2ms, total 20ms
,D/TimaKeyStoreProvider( 2934): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 2934): Added TimaKesytore provider
,I/AMMetaDataParserService( 2881): Icon data: ResourceDelete2131624000android.intent.action.delete2130837585
,I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.cooliris.media.Gallery
I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.sec.android.gallery3d.app.Gallery
I/AMMetaDataParserService( 2881): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2881): getResourcePackageName:assistant
,I/AMMetaDataParserService( 2881): Resource data:2131165194
I/AMMetaDataParserService( 2881): getResourceName:com.sec.android.gallery3d:xml/assistant
,I/AMMetaDataParserService( 2881): getResourceTypeNamexml
,I/AMMetaDataParserService( 2881): Icon data: ResourceDrawer2131624995android.intent.action.drawer2130837586
,I/AMMetaDataParserService( 2881): Icon data: ResourceSlideshow2131624009android.intent.action.slideshow2130837584
,I/AMMetaDataParserService( 2881): Icon data: ResourceCamera2131624012android.intent.action.camera2130837583
,W/BackupManagerService(  745): dataChanged but no participant pkg='com.android.providers.settings' uid=10084
,I/AMMetaDataParserService( 2881): Icon data: ResourceDelete2131624000android.intent.action.delete2130837585
,D/KeyguardViewMediator( 1069): handleKeyguardDoneDrawing
,I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.sec.android.gallery3d.app.UsbDeviceActivity
I/AMMetaDataParserService( 2881): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2881): getResourcePackageName:android.hardware.usb.action.USB_DEVICE_ATTACHED
,I/AMMetaDataParserService( 2881): Resource data:2131165195
I/AMMetaDataParserService( 2881): getResourceName:com.sec.android.gallery3d:xml/device_filter
,I/AMMetaDataParserService( 2881): getResourceTypeNamexml
I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.sec.android.gallery3d.app.Wallpaper
I/AMMetaDataParserService( 2881): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2881): getResourcePackageName:android.wallpaper.preview
,I/AMMetaDataParserService( 2881): Resource data:2131165204
I/AMMetaDataParserService( 2881): getResourceName:com.sec.android.gallery3d:xml/wallpaper_picker_preview
,I/AMMetaDataParserService( 2881): getResourceTypeNamexml
I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.sec.android.gallery3d.app.LockScreen
I/AMMetaDataParserService( 2881): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2881): getResourcePackageName:android.wallpaper.preview
,I/AMMetaDataParserService( 2881): Resource data:2131165204
I/AMMetaDataParserService( 2881): getResourceName:com.sec.android.gallery3d:xml/wallpaper_picker_preview
,I/AMMetaDataParserService( 2881): getResourceTypeNamexml
I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.sec.android.gallery3d.app.BothScreen
,I/AMMetaDataParserService( 2881): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2881): getResourcePackageName:android.wallpaper.preview
,I/AMMetaDataParserService( 2881): Resource data:2131165204
I/AMMetaDataParserService( 2881): getResourceName:com.sec.android.gallery3d:xml/wallpaper_picker_preview
,I/AMMetaDataParserService( 2881): getResourceTypeNamexml
I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.sec.android.gallery3d.app.TrimVideo
I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.sec.android.gallery3d.app.CropImage
I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.sec.android.gallery3d.app.ContextualTagSetting
I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.sec.android.gallery3d.app.ContextualTagWeatherSetting
I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.sec.samsung.gallery.view.gallerysearch.DeleteHistoryForGallerySearchActivity
I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.sec.samsung.gallery.view.usertag.AddUserTagListActivity
I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.sec.samsung.gallery.view.detailview.moreinfo.MoreInfoLocationEditActivity
I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.sec.android.gallery3d.settings.GallerySettings
I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.sec.android.gallery3d.gadget.WidgetTypeChooser
I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.sec.android.gallery3d.gadget.WidgetClickHandler
I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.sec.android.gallery3d.gadget.WidgetConfigure
I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.sec.android.gallery3d.gadget.MagazineWidgetConfigure
I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.sec.android.gallery3d.gadget.EasyWidgetConfigure
I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.sec.android.gallery3d.gadget.WidgetPreferenceActivity
I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.sec.android.gallery3d.gadget.MagazineWidgetPreferenceActivity
I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.sec.android.gallery3d.settings.AccountSettingActivity
I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.sec.android.gallery3d.settings.FilterbySettingActivity
I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.android.sec.gallery2d.viewstate.MapView2dPage
I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.sec.samsung.gallery.app.imagenote.ImageNote
I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.sec.samsung.gallery.app.photonote.PhotoNote
,I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.sec.samsung.gallery.controller.StartMmsSaveCmd$CallMmsSave
,I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.android.mms.ui.RoamingGuardPopupActivity
I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.android.mms.ui.AutoRetrievePreferenceActivity
I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.android.mms.ui.AutoRetrieveTabActivity
I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.android.mms.ui.ConversationComposer
I/AMMetaDataParserService( 2881): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2881): getResourcePackageName:android.app.spellscroll
,I/AMMetaDataParserService( 2881): Resource data:2131099676
,I/AMMetaDataParserService( 2881): getResourceName:com.android.mms:xml/spellscroll
,I/AMMetaDataParserService( 2881): getResourceTypeNamexml
I/AMMetaDataParserService( 2881): getResourcePackageName:android.app.default_searchable
I/AMMetaDataParserService( 2881): getResourcePackageName:assistant
,I/AMMetaDataParserService( 2881): Resource data:2131099648
I/AMMetaDataParserService( 2881): getResourceName:com.android.mms:xml/assistant_messaging
,I/AMMetaDataParserService( 2881): getResourceTypeNamexml
,I/AMMetaDataParserService( 2881): Icon data: ResourceSearch2131493233com.android.mms.ui.conversationlistfragment.searchmessages2130837516
,I/SELinux ( 2948): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 2948):  
,I/AMMetaDataParserService( 2881): Icon data: ResourceCompose2131492866com.android.mms.ui.conversationlistfragment.composemessage2130837515
I/ActivityManager(  745): Killing 1338:com.sec.android.provider.badge/u0a72 (adj 15): empty #43
,I/AMMetaDataParserService( 2881): Icon data: ResourceAdd from contacts2131493281com.android.mms.ui.composemessagefragment.attachcontacts2130837512
,I/SELinux ( 2948): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 2948):  
I/SELinux ( 2948):  
,I/SELinux ( 2948): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 2948): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 2948): >>>>> Normal User
,E/dalvikvm( 2948): >>>>> com.samsung.android.app.colorblind [ userId:0 | appId:1000 ]
,E/SELinux ( 2948): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,I/AMMetaDataParserService( 2881): Icon data: ResourceCall2131493971com.android.mms.ui.composemessagefragment.calltocontact2130837513
,D/TimaKeyStoreProvider( 2948): in addTimaSignatureService
,D/TimaKeyStoreProvider( 2948): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 2948): Added TimaKesytore provider
,I/AMMetaDataParserService( 2881): Icon data: ResourceDelete2131492988com.android.mms.ui.composemessagefragment.delete2130837514
,I/AMMetaDataParserService( 2881): Icon data: ResourceSend2131492905com.android.mms.ui.composemessagefragment.send2130837517
,I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.android.mms.ui.ComposeMessageActivityNoLockScreen
,I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.android.mms.ui.ComposeMessageMms
I/AMMetaDataParserService( 2881): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2881): getResourcePackageName:assistant
,I/AMMetaDataParserService( 2881): Resource data:2131099648
,I/AMMetaDataParserService( 2881): getResourceName:com.android.mms:xml/assistant_messaging
,I/AMMetaDataParserService( 2881): getResourceTypeNamexml
,I/SELinux ( 2961): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 2961):  
,I/AMMetaDataParserService( 2881): Icon data: ResourceSearch2131493233com.android.mms.ui.conversationlistfragment.searchmessages2130837516
I/ActivityManager(  745): Killing 1695:com.sec.android.app.mt/1000 (adj 15): empty #43
,D/SensorService(  745):   -0.1 -0.1 9.5
,I/AMMetaDataParserService( 2881): Icon data: ResourceCompose2131492866com.android.mms.ui.conversationlistfragment.composemessage2130837515
,I/SELinux ( 2961): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 2961):  
I/SELinux ( 2961):  
,I/SELinux ( 2961): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 2961): [DEBUG] seapp_context_lookup: seinfoCategory = default
E/dalvikvm( 2961): >>>>> Normal User
,E/dalvikvm( 2961): >>>>> com.dropbox.android [ userId:0 | appId:10091 ]
,E/SELinux ( 2961): [DEBUG] seapp_context_lookup: seinfoCategory = default
,I/AMMetaDataParserService( 2881): Icon data: ResourceAdd from contacts2131493281com.android.mms.ui.composemessagefragment.attachcontacts2130837512
,D/TimaKeyStoreProvider( 2961): in addTimaSignatureService
,D/TimaKeyStoreProvider( 2961): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 2961): Added TimaKesytore provider
,I/AMMetaDataParserService( 2881): Icon data: ResourceCall2131493971com.android.mms.ui.composemessagefragment.calltocontact2130837513
,I/AMMetaDataParserService( 2881): Icon data: ResourceDelete2131492988com.android.mms.ui.composemessagefragment.delete2130837514
,I/AMMetaDataParserService( 2881): Icon data: ResourceSend2131492905com.android.mms.ui.composemessagefragment.send2130837517
,I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.android.mms.ui.CbConfigPreferenceActivity
I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.android.mms.ui.CbSettingTabActivity
I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.android.mms.ui.ComposeMessage
I/AMMetaDataParserService( 2881): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2881): getResourcePackageName:assistant
,I/AMMetaDataParserService( 2881): Resource data:2131099648
I/AMMetaDataParserService( 2881): getResourceName:com.android.mms:xml/assistant_messaging
,I/AMMetaDataParserService( 2881): getResourceTypeNamexml
,I/AMMetaDataParserService( 2881): Icon data: ResourceSearch2131493233com.android.mms.ui.conversationlistfragment.searchmessages2130837516
,I/AMMetaDataParserService( 2881): Icon data: ResourceCompose2131492866com.android.mms.ui.conversationlistfragment.composemessage2130837515
,I/com.dropbox.android.service.DropboxNetworkReceiver( 2961): Setting receiver enabled: false
,I/AMMetaDataParserService( 2881): Icon data: ResourceAdd from contacts2131493281com.android.mms.ui.composemessagefragment.attachcontacts2130837512
,I/com.dropbox.sync.android.a( 2961): Prepared cache dir '/data/data/com.dropbox.android/app_DropboxSyncCache/hizqkiq3952astb'.
,I/AMMetaDataParserService( 2881): Icon data: ResourceCall2131493971com.android.mms.ui.composemessagefragment.calltocontact2130837513
,I/com.dropbox.sync.android.aa( 2961): Dropbox initialized for application: hizqkiq3952astb (com.dropbox.android/231222 DropboxSync/2.0.2 (Android; 4.4.2; samsung SM-G800H armeabi-v7a; en_US))
,I/AMMetaDataParserService( 2881): Icon data: ResourceDelete2131492988com.android.mms.ui.composemessagefragment.delete2130837514
,I/AMMetaDataParserService( 2881): Icon data: ResourceSend2131492905com.android.mms.ui.composemessagefragment.send2130837517
,W/ActivityManager(  745): Permission Denial: getCurrentUser() from pid=2961, uid=10091 requires android.permission.INTERACT_ACROSS_USERS
,I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.android.mms.ui.ForwardMessageActivity
,I/AMMetaDataParserService( 2881): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2881): getResourcePackageName:assistant
,I/AMMetaDataParserService( 2881): Resource data:2131099648
,I/AMMetaDataParserService( 2881): getResourceName:com.android.mms:xml/assistant_messaging
,I/AMMetaDataParserService( 2881): getResourceTypeNamexml
,I/AMMetaDataParserService( 2881): Icon data: ResourceSearch2131493233com.android.mms.ui.conversationlistfragment.searchmessages2130837516
,I/SELinux ( 2983): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 2983):  
I/ActivityManager(  745): Killing 1927:com.sec.phone/1001 (adj 15): empty #43
,D/STATUSBAR-IconMerger( 1069): checkOverflow(384), More:false, Req:false Child:2
,I/AMMetaDataParserService( 2881): Icon data: ResourceCompose2131492866com.android.mms.ui.conversationlistfragment.composemessage2130837515
,I/SELinux ( 2983): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 2983):  
I/SELinux ( 2983):  
,I/SELinux ( 2983): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 2983): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 2983): >>>>> Normal User
,E/dalvikvm( 2983): >>>>> com.sec.esdk.elm [ userId:0 | appId:10094 ]
,E/SELinux ( 2983): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 2983): in addTimaSignatureService
,D/TimaKeyStoreProvider( 2983): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 2983): Added TimaKesytore provider
V/AlarmManager(  745): waitForAlarm result :4
V/AlarmManager(  745): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,I/AMMetaDataParserService( 2881): Icon data: ResourceAdd from contacts2131493281com.android.mms.ui.composemessagefragment.attachcontacts2130837512
,I/AMMetaDataParserService( 2881): Icon data: ResourceCall2131493971com.android.mms.ui.composemessagefragment.calltocontact2130837513
,W/ActivityManager(  745): Permission Denial: getCurrentUser() from pid=2983, uid=10094 requires android.permission.INTERACT_ACROSS_USERS
,D/elm:14132( 2983): ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
,D/elm:14132( 2983): ELMEngine.ELMEngine( context ).
,D/elm:14132( 2983): MDMBridge.setEnterpriseBridge()
,D/elm:14132( 2983): ELMAbstractReceiver : Receive Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
,I/AMMetaDataParserService( 2881): Icon data: ResourceDelete2131492988com.android.mms.ui.composemessagefragment.delete2130837514
,D/elm:14132( 2983): ElmAgentService : onCreate()
,D/elm:14132( 2983): ElmAgentService : onHandleIntent() Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
D/elm:14132( 2983): ELMEngine.ServiceHandler.handleMessage( BOOT_COMPLETED ). 
,D/elm:14132( 2983): BootCompletedState : startBootCompleted() call
,D/elm:14132( 2983): ModuleBase.resetCalllogAPIAlarm()
,I/SELinux ( 3002): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 3002):  
,I/ActivityManager(  745): Waited long enough for: ServiceRecord{4306fdc0 u0 com.sec.android.daemonapp/.ap.accuweather.WeatherClockService}
D/elm:14132( 2983): MDMBridge.getAllLicenseInfoFromSDK()
I/elm:14132( 2983): Get License : 0
,D/elm:14132( 2983): ElmAgentService : onDestroy().
I/ActivityManager(  745): Killing 2014:com.google.android.configupdater/u0a3 (adj 15): empty #43
,I/AMMetaDataParserService( 2881): Icon data: ResourceSend2131492905com.android.mms.ui.composemessagefragment.send2130837517
,I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.android.mms.ui.ReplyMessageActivity
I/AMMetaDataParserService( 2881): Resource data:Inside bundle  check
I/SELinux ( 3002): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 3002):  
I/SELinux ( 3002):  
,I/SELinux ( 3002): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 3002): [DEBUG] seapp_context_lookup: seinfoCategory = platform
I/AMMetaDataParserService( 2881): getResourcePackageName:assistant
I/AMMetaDataParserService( 2881): Resource data:2131099648
E/dalvikvm( 3002): >>>>> Normal User
,E/dalvikvm( 3002): >>>>> com.sec.android.fwupgrade [ userId:0 | appId:1000 ]
,E/SELinux ( 3002): [DEBUG] seapp_context_lookup: seinfoCategory = platform
I/AMMetaDataParserService( 2881): getResourceName:com.android.mms:xml/assistant_messaging
,I/AMMetaDataParserService( 2881): getResourceTypeNamexml
,D/TimaKeyStoreProvider( 3002): in addTimaSignatureService
,I/AMMetaDataParserService( 2881): Icon data: ResourceSearch2131493233com.android.mms.ui.conversationlistfragment.searchmessages2130837516
,D/TimaKeyStoreProvider( 3002): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 3002): Added TimaKesytore provider
,I/AMMetaDataParserService( 2881): Icon data: ResourceCompose2131492866com.android.mms.ui.conversationlistfragment.composemessage2130837515
,I/System.out( 2961): Thread-258(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
,I/AMMetaDataParserService( 2881): Icon data: ResourceAdd from contacts2131493281com.android.mms.ui.composemessagefragment.attachcontacts2130837512
,I/System.out( 2961): Thread-258(ApacheHTTPLog):isShipBuild true
,I/System.out( 2961): Thread-258(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,I/SELinux ( 3015): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 3015):  
I/ActivityManager(  745): Killing 2081:com.sec.dsm.system/1000 (adj 15): empty #43
,I/System.out( 2961): pool-4-thread-1 calls detatch()
,I/AMMetaDataParserService( 2881): Icon data: ResourceCall2131493971com.android.mms.ui.composemessagefragment.calltocontact2130837513
,E/BluetoothManagerService(  745): Bluetooth is already disabled. DO NOT disable again.
,I/WifiManager( 2575): packageName : com.example.hello
,I/WifiManager( 2575): setWifiEnabled : false
I/WifiService(  745): setWifiEnabled: false pid=2575, uid=10181
I/SELinux ( 3015): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 3015):  
I/SELinux ( 3015):  
,I/SELinux ( 3015): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 3015): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 3015): >>>>> Normal User
,E/dalvikvm( 3015): >>>>> com.sec.factory.camera [ userId:0 | appId:1000 ]
,I/jxcore-log( 2575): ****TEST TOOK:  5060  ms ****
I/jxcore-log( 2575): 
I/jxcore-log( 2575): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 2575): 
,E/SELinux ( 3015): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 3015): in addTimaSignatureService
,I/AMMetaDataParserService( 2881): Icon data: ResourceDelete2131492988com.android.mms.ui.composemessagefragment.delete2130837514
,D/TimaKeyStoreProvider( 3015): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 3015): Added TimaKesytore provider
,I/AMMetaDataParserService( 2881): Icon data: ResourceSend2131492905com.android.mms.ui.composemessagefragment.send2130837517
,I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.android.mms.ui.ConversationList
I/AMMetaDataParserService( 2881): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2881): getResourcePackageName:assistant
,I/AMMetaDataParserService( 2881): Resource data:2131099648
I/AMMetaDataParserService( 2881): getResourceName:com.android.mms:xml/assistant_messaging
,I/AMMetaDataParserService( 2881): getResourceTypeNamexml
,I/CameraApp( 3015): CameraApp.onCreate()... mFeature : null
,I/testFeature( 3015): Feature.Feature(context)
I/testFeature( 3015): Feature.readInternalDefaultXml()
,I/testFeature( 3015): ResetFeatureValue
,I/AMMetaDataParserService( 2881): Icon data: ResourceSearch2131493233com.android.mms.ui.conversationlistfragment.searchmessages2130837516
,I/CameraFirmware_broadcast( 3015): CameraFirmwareBroadCastReceiver...
,I/CameraApp( 3015): CameraApp.getAppFeature()...
,I/ActivityManager(  745): Killing 2117:com.sec.android.app.factorykeystring/1000 (adj 15): empty #43
I/SELinux ( 3033): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 3033):  
,I/AMMetaDataParserService( 2881): Icon data: ResourceCompose2131492866com.android.mms.ui.conversationlistfragment.composemessage2130837515
,E/SMD     (  243): DCD ON
,I/SELinux ( 3033): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 3033):  
I/SELinux ( 3033):  
,I/SELinux ( 3033): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 3033): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 3033): >>>>> Normal User
,E/dalvikvm( 3033): >>>>> com.samsung.android.app.watchmanagerstub [ userId:0 | appId:10100 ]
,E/SELinux ( 3033): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,I/AMMetaDataParserService( 2881): Icon data: ResourceAdd from contacts2131493281com.android.mms.ui.composemessagefragment.attachcontacts2130837512
,D/TimaKeyStoreProvider( 3033): in addTimaSignatureService
,D/TimaKeyStoreProvider( 3033): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 3033): Added TimaKesytore provider
,I/AMMetaDataParserService( 2881): Icon data: ResourceCall2131493971com.android.mms.ui.composemessagefragment.calltocontact2130837513
,I/AMMetaDataParserService( 2881): Icon data: ResourceDelete2131492988com.android.mms.ui.composemessagefragment.delete2130837514
,D/PackageIntentReceiver( 3033): ACTION_BOOT_COMPLETED
,D/PackageIntentReceiver( 3033): jangil::ACTION_BOOT_COMPLETED::do not need pkg remove..
I/ActivityManager(  745): Killing 2174:com.sec.factory/1000 (adj 15): empty #43
,I/AMMetaDataParserService( 2881): Icon data: ResourceSend2131492905com.android.mms.ui.composemessagefragment.send2130837517
,I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.android.mms.ui.DeliveryReportActivity
,I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.android.mms.ui.WarnOfStorageLimitsActivity
I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.android.mms.ui.SlideshowActivity
I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.android.mms.ui.MmsSinglePageActivity
I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.android.mms.ui.ClassZeroActivity
I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.android.mms.ui.RetryActivity
,I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.android.mms.ui.MessagingPreferenceActivity
I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.android.mms.settings.EntrancePrefActivity
I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.android.mms.settings.DisplaySettings
I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.android.mms.settings.CMASSettings
,I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.android.mms.settings.TextMessagesSettings
I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.android.mms.settings.MultimediamessagesSettings
I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.android.mms.settings.DeleteoldMessagesSettings
I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.android.mms.settings.PushMessagesSettings
I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.android.mms.settings.NotificationSettings
,I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.android.mms.settings.NotificationSettingsDS
I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.android.mms.settings.SignatureSettings
I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.android.mms.settings.SpamSettings
I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.android.mms.settings.SafemodeSettings
,I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.android.mms.settings.DelaySendingSettings
I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.android.mms.settings.MessageSmscActivityDS
,I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.android.mms.settings.SignatureEditActivity
I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.android.mms.settings.PreviewsMessagesSettings
,I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.android.mms.settings.QuickReplySettings
I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.android.mms.settings.CallbackNumberSettings
I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.android.mms.settings.CallbackNumberEditActivity
I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.android.mms.settings.BackgroundStyle
I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.android.mms.settings.BubbleStyle
,I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.android.mms.ui.PushMessageDialog
I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.samsung.mms.ui.SaveThreadActivity
I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.samsung.mms.ui.SavedMsgsList
I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.samsung.mms.ui.RestorePreviewActivity
I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.samsung.mms.ui.ConversationListRestore
,I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.android.mms.ui.ManageSimMessages
I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.android.mms.ui.MmsRetryActivity
I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.android.mms.ui.ConfirmRateLimitActivity
I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.android.mms.ui.SearchActivity
I/AMMetaDataParserService( 2881): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 2881): getResourcePackageName:android.app.searchable
,I/AMMetaDataParserService( 2881): Resource data:2131099671
,I/AMMetaDataParserService( 2881): getResourceName:com.android.mms:xml/searchable
I/AMMetaDataParserService( 2881): getResourceTypeNamexml
I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.android.mms.ui.SmsViewerActivity
I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.android.mms.ui.MmsNotificationViewerActivity
I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.android.mms.ui.DrmContentsActivity
I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.android.mms.ui.CMASPreferenceActivity
,I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.android.mms.ui.CMASDialog
,I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.android.mms.ui.CMASDialog_single_top
I/SELinux ( 3048): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 3048):  
,I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.android.mms.ui.PDPResetDialog
I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.android.mms.ui.CMASUserPromptDialog
I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.android.mms.ui.LockedMessageManager
I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.android.mms.ui.SpamMessageManager
I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.android.mms.ui.ReservationMessageManager
I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.android.mms.ui.DraftMessageManager
I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.android.mms.ui.RecipientListActivity
I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.android.mms.ui.GroupMessagingRecipientListActivity
I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.android.mms.ui.SelectMapActivity
I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.android.mms.ui.BoxListViewActivity
I/AMMetaDataParserService( 2881): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2881): getResourcePackageName:android.app.default_searchable
I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.android.mms.provisioning.MmsProvisionActivity
I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.android.mms.ui.ManageSDMessages
I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.android.mms.ui.VMessageViewerActivity
I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.android.mms.spam.HelpActivity
I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.android.mms.spam.SetupSpamNumberList
I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.android.mms.spam.SetupSpamKeywordList
I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.android.mms.spam.SetupSpamNumberWriteForm
,I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.android.mms.spam.SetupSpamKeywordWriteForm
I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.android.mms.ui.SettingsReservationActivity
I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.android.mms.ui.SettingsTransmitMessageActivity
I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.android.mms.ui.MessageDatabaseBackupActivity
,I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.samsung.mms.content.MmsPartExportDialogActivity
I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.samsung.mms.content.MmsPartExportDialogActivityAlien
I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.android.mms.ui.MmsPartExportActivity
I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.android.mms.template.TextTemplateListActivity
,I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.android.mms.template.TextTemplateEditActivity
I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.android.mms.help.AirViewMainActivity
,I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.android.mms.help.AirButtonMainActivity
I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.android.mms.widget.WidgetPreferenceActivity
,I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.android.mms.cover.MissedMsgActivity
I/AMMetaDataParserService( 2881): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 2881): getResourcePackageName:com.sec.android.multiwindow.activity.STYLE
,I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.samsung.mms.ui.AutoSendingTestActivity
,I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.android.mms.prioritysender.AddGlanceListActivity
I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.android.mms.prioritysender.AddThreadListActivity
I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.android.mms.smishing.PackageAuthorityActivity
,I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.android.mms.smishing.PackageAuthorityDialog
I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.android.mms.settings.CheckDefaultSmsAppsActivity
I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.android.mms.help.PrioritySenderHelpActivity
I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.android.mms.help.AddGlanceListHelpActivity
,I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.android.mms.accessory.ReadReportActivity
,I/SELinux ( 3048): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 3048):  
I/SELinux ( 3048):  
,I/SELinux ( 3048): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 3048): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 3048): >>>>> Normal User
,E/dalvikvm( 3048): >>>>> com.google.android.talk [ userId:0 | appId:10105 ]
,E/SELinux ( 3048): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
,D/TimaKeyStoreProvider( 3048): in addTimaSignatureService
,D/TimaKeyStoreProvider( 3048): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 3048): Added TimaKesytore provider
,D/dalvikvm( 2881): GC_CONCURRENT freed 4984K, 33% free 12704K/18756K, paused 2ms+3ms, total 34ms
,D/dalvikvm( 2881): WAIT_FOR_CONCURRENT_GC blocked 23ms
,I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.android.settings.GridSettings
I/AMMetaDataParserService( 2881): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2881): getResourcePackageName:assistant
,I/AMMetaDataParserService( 2881): Resource data:2131165216
,I/AMMetaDataParserService( 2881): getResourceName:com.android.settings:xml/assistant
,I/AMMetaDataParserService( 2881): getResourceTypeNamexml
,I/AMMetaDataParserService( 2881): Icon data: ResourceSearch2131297802com.android.settings.Search2130837582
,D/AndroidRuntime( 3031): 
D/AndroidRuntime( 3031): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,I/AMMetaDataParserService( 2881): Icon data: ResourceEdit quick settings2131296308com.android.settings.Favorite2130837581
,D/AndroidRuntime( 3031): CheckJNI is OFF
,D/AndroidRuntime( 3031): setted country_code = Poland
,D/AndroidRuntime( 3031): setted countryiso_code = PL
,D/AndroidRuntime( 3031): setted sales_code = XEO
D/AndroidRuntime( 3031): readGMSProperty: start
D/AndroidRuntime( 3031): readGMSProperty: already setted!!
D/AndroidRuntime( 3031): readGMSProperty: end
D/AndroidRuntime( 3031): addProductProperty: start
I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.android.settings.SubSettings
I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.android.settings.TimDataConnectionDialog
I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.android.settings.LabelName
I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.android.settings.Password
I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.android.settings.TetherHelp
I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.android.settings.Settings$EthernetSettingsActivity
I/AMMetaDataParserService( 2881): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2881): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 2881): Resource data:2131429159
I/AMMetaDataParserService( 2881): getResourceName:com.android.settings:id/wireless_settings
I/AMMetaDataParserService( 2881): getResourceTypeNameid
,I/AMMetaDataParserService( 2881): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2881): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 2881): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
,I/AMMetaDataParserService( 2881): Resource data:2131296695
I/AMMetaDataParserService( 2881): getResourceName:com.android.settings:string/wireless_networks_settings_title
,I/AMMetaDataParserService( 2881): getResourceTypeNamestring
I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.android.settings.ethernet.EthernetEnabler
I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.android.settings.ethernet.EthernetConfigure
I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.android.settings.Settings$WirelessSettingsActivity
I/AMMetaDataParserService( 2881): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2881): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 2881): Resource data:2131429159
,I/AMMetaDataParserService( 2881): getResourceName:com.android.settings:id/wireless_settings
I/AMMetaDataParserService( 2881): getResourceTypeNameid
I/AMMetaDataParserService( 2881): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.android.settings.Settings$WifiSettingsActivity
,I/AMMetaDataParserService( 2881): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2881): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 2881): Resource data:2131429144
I/AMMetaDataParserService( 2881): getResourceName:com.android.settings:id/wifi_settings
I/AMMetaDataParserService( 2881): getResourceTypeNameid
I/AMMetaDataParserService( 2881): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.android.settings.wifi.WifiSettings
,I/AMMetaDataParserService( 2881): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2881): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2881): Resource data:2131429144
,I/AMMetaDataParserService( 2881): getResourceName:com.android.settings:id/wifi_settings
I/AMMetaDataParserService( 2881): getResourceTypeNameid
I/AMMetaDataParserService( 2881): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.android.settings.wifi.WifiPickerActivity
,I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.android.settings.wifi.WifiSecPickerActivity
I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.android.settings.wifi.WifiDummyPickerActivity
I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.android.settings.wifi.WifiCaptiveActivity
I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.android.settings.wifi.WifiPickerDialog
,I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.android.settings.wifi.hs20.Hs20PickerDialog
I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.android.settings.wifi.WifiWarningDialog
I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.android.settings.wifi.WifiOffloadDialog
I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.android.settings.wifi.SetupWizardWifiScreen
I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.android.settings.wifi.CaptivePortalWebViewActivity
I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.android.settings.wifi.WifiAdvancedVzwSetupActivity
,I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.android.settings.wifi.WifiAdvancedSecSetupActivity
I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.android.settings.wifi.WifiSecSetupActivity
I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.android.settings.wifi.WifiSetupActivity
I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.android.settings.wifi.WifiSettingsForSetupWizardXL
I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.android.settings.wifi.WifiManageNetworks
I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.android.settings.Settings$AdvancedWifiSettingsActivity
I/AMMetaDataParserService( 2881): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2881): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 2881): Resource data:2131429144
,I/AMMetaDataParserService( 2881): getResourceName:com.android.settings:id/wifi_settings
I/AMMetaDataParserService( 2881): getResourceTypeNameid
,I/AMMetaDataParserService( 2881): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2881): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 2881): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
,I/AMMetaDataParserService( 2881): Resource data:2131297114
I/AMMetaDataParserService( 2881): getResourceName:com.android.settings:string/wifi_settings
,I/AMMetaDataParserService( 2881): getResourceTypeNamestring
I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.android.settings.wifi.WifiInfo
I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.android.settings.wifi.WifiConfigInfo
,I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.android.settings.wifi.WifiAPITest
I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.android.settings.wifi.WifiStatusTest
I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.android.settings.wifi.mobileap.WifiApSettings
I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.android.settings.wifi.mobileap.WifiApWarning
I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.android.settings.wifi.WifiPoorConnection
I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.android.settings.wifi.WifiHiddenApListActivity
,I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.android.settings.wifi.WifiHiddenApDeleteActivity
,I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.android.settings.wifi.WifiConnectionSettings
I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.android.settings.ApnSettings
,I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.android.settings.ApnSettingsTabActivity
I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.android.settings.Settings$BluetoothSettingsActivity
I/AMMetaDataParserService( 2881): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 2881): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 2881): Resource data:2131429146
I/AMMetaDataParserService( 2881): getResourceName:com.android.settings:id/bluetooth_settings
I/AMMetaDataParserService( 2881): getResourceTypeNameid
I/AMMetaDataParserService( 2881): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.android.settings.bluetooth.BluetoothSettings
,I/AMMetaDataParserService( 2881): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2881): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 2881): Resource data:2131429146
I/AMMetaDataParserService( 2881): getResourceName:com.android.settings:id/bluetooth_settings
I/AMMetaDataParserService( 2881): getResourceTypeNameid
I/AMMetaDataParserService( 2881): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.android.settings.bluetooth.BluetoothScanDialog
I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.android.settings.bluetooth.BluetoothErrorActivity
,I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.android.settings.bluetooth.CheckBluetoothStateActivity
I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.android.settings.bluetooth.DevicePickerActivity
I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.android.settings.Settings$MirrorLinkActivity
I/AMMetaDataParserService( 2881): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2881): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 2881): Resource data:2131429168
,I/AMMetaDataParserService( 2881): getResourceName:com.android.settings:id/mirror_link_settings
I/AMMetaDataParserService( 2881): getResourceTypeNameid
I/AMMetaDataParserService( 2881): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
D/dalvikvm( 3031): Trying to load lib libjavacore.so 0x0
I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.android.settings.Settings$TetherSettingsActivity
I/AMMetaDataParserService( 2881): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 2881): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 2881): Resource data:2131429159
I/AMMetaDataParserService( 2881): getResourceName:com.android.settings:id/wireless_settings
I/AMMetaDataParserService( 2881): getResourceTypeNameid
I/AMMetaDataParserService( 2881): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,I/AMMetaDataParserService( 2881): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 2881): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
,I/AMMetaDataParserService( 2881): Resource data:2131296695
I/AMMetaDataParserService( 2881): getResourceName:com.android.settings:string/wireless_networks_settings_title
I/AMMetaDataParserService( 2881): getResourceTypeNamestring
,I/AMMetaDataParserService( 2881): getResourcePackageName:com.samsung.android.multiuser.install_only_owner
I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.android.settings.TetherSettings
I/AMMetaDataParserService( 2881): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2881): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2881): Resource data:2131429159
,D/dalvikvm( 3031): Added shared lib libjavacore.so 0x0
I/AMMetaDataParserService( 2881): getResourceName:com.android.settings:id/wireless_settings
,I/AMMetaDataParserService( 2881): getResourceTypeNameid
I/AMMetaDataParserService( 2881): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2881): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 2881): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
,I/AMMetaDataParserService( 2881): Resource data:2131296695
I/AMMetaDataParserService( 2881): getResourceName:com.android.settings:string/wireless_networks_settings_title
,I/AMMetaDataParserService( 2881): getResourceTypeNamestring
I/AMMetaDataParserService( 2881): getResourcePackageName:com.samsung.android.multiuser.install_only_owner
I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.android.settings.Settings$WifiP2pSettingsActivity
I/AMMetaDataParserService( 2881): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2881): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2881): Resource data:2131429144
D/dalvikvm( 3031): Trying to load lib libnativehelper.so 0x0
I/AMMetaDataParserService( 2881): getResourceName:com.android.settings:id/wifi_settings
D/dalvikvm( 3031): Added shared lib libnativehelper.so 0x0
,D/dalvikvm( 3031): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
I/AMMetaDataParserService( 2881): getResourceTypeNameid
I/AMMetaDataParserService( 2881): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2881): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 2881): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
,I/AMMetaDataParserService( 2881): Resource data:2131297114
I/AMMetaDataParserService( 2881): getResourceName:com.android.settings:string/wifi_settings
I/AMMetaDataParserService( 2881): getResourceTypeNamestring
I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.android.settings.wifi.p2p.WifiP2pSettings
I/AMMetaDataParserService( 2881): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2881): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2881): Resource data:2131429159
,W/ActivityManager(  745): Permission Denial: getCurrentUser() from pid=3048, uid=10105 requires android.permission.INTERACT_ACROSS_USERS
I/AMMetaDataParserService( 2881): getResourceName:com.android.settings:id/wireless_settings
I/AMMetaDataParserService( 2881): getResourceTypeNameid
I/AMMetaDataParserService( 2881): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2881): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 2881): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 2881): Resource data:2131296695
I/AMMetaDataParserService( 2881): getResourceName:com.android.settings:string/wireless_networks_settings_title
I/AMMetaDataParserService( 2881): getResourceTypeNamestring
I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.android.settings.Settings$WifiP2pHelpActivity
I/AMMetaDataParserService( 2881): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2881): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2881): Resource data:2131429159
I/AMMetaDataParserService( 2881): getResourceName:com.android.settings:id/wireless_settings
I/AMMetaDataParserService( 2881): getResourceTypeNameid
I/AMMetaDataParserService( 2881): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2881): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 2881): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 2881): Resource data:2131296695
I/AMMetaDataParserService( 2881): getResourceName:com.android.settings:string/wireless_networks_settings_title
I/AMMetaDataParserService( 2881): getResourceTypeNamestring
I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.android.settings.wifi.p2p.WifiP2pDummyPickerActivity
I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.android.settings.Settings$NearbySettingsActivity
I/AMMetaDataParserService( 2881): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2881): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2881): Resource data:2131429159
I/AMMetaDataParserService( 2881): getResourceName:com.android.settings:id/wireless_settings
I/AMMetaDataParserService( 2881): getResourceTypeNameid
I/AMMetaDataParserService( 2881): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2881): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 2881): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 2881): Resource data:2131296695
I/AMMetaDataParserService( 2881): getResourceName:com.android.settings:string/wireless_networks_settings_title
I/AMMetaDataParserService( 2881): getResourceTypeNamestring
I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.android.settings.nearby.NearbySettings
I/AMMetaDataParserService( 2881): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2881): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2881): Resource data:2131429159
I/AMMetaDataParserService( 2881): getResourceName:com.android.settings:id/wireless_settings
I/AMMetaDataParserService( 2881): getResourceTypeNameid
I/AMMetaDataParserService( 2881): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2881): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 2881): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 2881): Resource data:2131296695
I/AMMetaDataParserService( 2881): getResourceName:com.android.settings:string/wireless_networks_settings_title
I/AMMetaDataParserService( 2881): getResourceTypeNamestring
I/AMMetaDataParserService( 2881): Resource data:Loop for, running activitycom.android.settings.wfd.WfdHelpActivity
I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.android.settings.wfd.WfdPickerDialog
I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.android.settings.Settings$VpnSettingsActivity
I/AMMetaDataParserService( 2881): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2881): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2881): Resource data:2131429159
I/AMMetaDataParserService( 2881): getResourceName:com.android.settings:id/wireless_settings
I/AMMetaDataParserService( 2881): getResourceTypeNameid
I/AMMetaDataParserService( 2881): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2881): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 2881): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 2881): Resource data:2131296695
I/AMMetaDataParserService( 2881): getResourceName:com.android.settings:string/wireless_networks_settings_title
I/AMMetaDataParserService( 2881): getResourceTypeNamestring
I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.android.settings.Settings$DateTimeSettingsActivity
I/AMMetaDataParserService( 2881): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2881): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2881): Resource data:2131429219
I/AMMetaDataParserService( 2881): getResourceName:com.android.settings:id/date_time_settings
I/AMMetaDataParserService( 2881): getResourceTypeNameid
I/AMMetaDataParserService( 2881): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.android.settings.DateTimeSettingsSetupWizard
I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.android.settings.FeatureSettingsSetupWizard
I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.android.settings.Settings$LocalePickerActivity
I/AMMetaDataParserService( 2881): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2881): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2881): Resource data:2131429191
I/AMMetaDataParserService( 2881): getResourceName:com.android.settings:id/language_settings
I/AMMetaDataParserService( 2881): getResourceTypeNameid
I/AMMetaDataParserService( 2881): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.android.settings.Settings$InputMethodAndLanguageSettingsActivity
I/AMMetaDataParserService( 2881): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2881): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2881): Resource data:2131429191
I/AMMetaDataParserService( 2881): getResourceName:com.android.settings:id/language_settings
I/AMMetaDataParserService( 2881): getResourceTypeNameid
I/AMMetaDataParserService( 2881): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.android.settings.Settings$HandwritingLanguageActivity
I/AMMetaDataParserService( 2881): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2881): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2881): Resource data:2131429191
I/AMMetaDataParserService( 2881): getResourceName:com.android.settings:id/language_settings
I/AMMetaDataParserService( 2881): getResourceTypeNameid
I/AMMetaDataParserService( 2881): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.android.settings.handwritingsearch.HandwritingLanguageTablet
I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.android,.settings.Settings$KeyboardLayoutPickerActivity
I/AMMetaDataParserService( 2881): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2881): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2881): Resource data:2131429191
I/AMMetaDataParserService( 2881): getResourceName:com.android.settings:id/language_settings
I/AMMetaDataParserService( 2881): getResourceTypeNameid
I/AMMetaDataParserService( 2881): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.android.settings.LanguageSettings
I/AMMetaDataParserService( 2881): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 2881): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2881): Resource data:2131429191
I/AMMetaDataParserService( 2881): getResourceName:com.android.settings:id/language_settings
I/AMMetaDataParserService( 2881): getResourceTypeNameid
I/AMMetaDataParserService( 2881): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.android.settings.Settings$SpellCheckersSettingsActivity
I/AMMetaDataParserService( 2881): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2881): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2881): Resource data:2131429191
I/AMMetaDataParserService( 2881): getResourceName:com.android.settings:id/language_settings
I/AMMetaDataParserService( 2881): getResourceTypeNameid
,I/AMMetaDataParserService( 2881): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2881): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 2881): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 2881): Resource data:2131298419,
I/AMMetaDataParserService( 2881): getResourceName:com.android.settings:string/language_keyboard_settings_title
I/AMMetaDataParserService( 2881): getResourceTypeNamestring
I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.android.settings.inputmethod.InputMethodAndSubtypeEnablerActivity
I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.android.settings.Settings$UserDictionarySettingsActivity
I/AMMetaDataParserService( 2881): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2881): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2881): Resource data:2131429191
I/AMMetaDataParserService( 2881): getResourceName:com.android.settings:id/language_settings
I/AMMetaDataParserService( 2881): getResourceTypeNameid
,I/AMMetaDataParserService( 2881): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2881): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 2881): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 2881): Resource data:2131298419
I/AMMetaDataParserService( 2881): getResourceName:com.android.settings:string/language_keyboard_settings_title
I/AMMetaDataParserService( 2881): getResourceTypeNamestring
I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.android.settings.inputmethod.UserDictionaryAddWordActivity
I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.android.settings.UserDictionarySettings
I/AMMetaDataParserService( 2881): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2881): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2881): Resource data:2131429191
I/AMMetaDataParserService( 2881): getResourceName:com.android.settings:id/language_settings
I/AMMetaDataParserService( 2881): getResourceTypeNameid
I/AMMetaDataParserService( 2881): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2881): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 2881): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 2881): Resource data:2131298419
I/AMMetaDataParserService( 2881): getResourceName:com.android.settings:string/language_keyboard_settings_title
I/AMMetaDataParserService( 2881): getResourceTypeNamestring
I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.android.settings.Settings$SoundSettingsActivity
I/AMMetaDataParserService( 2881): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2881): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2881): Resource data:2131429176
I/AMMetaDataParserService( 2881): getResourceName:com.android.settings:id/sound_settings
I/AMMetaDataParserService( 2881): getResourceTypeNameid
I/AMMetaDataParserService( 2881): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.android.settings.SoundSettings
I/AMMetaDataParserService( 2881): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2881): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2881): Resource data:2131429176
I/AMMetaDataParserService( 2881): getResourceName:com.android.settings:id/sound_settings
I/AMMetaDataParserService( 2881): getResourceTypeNameid
I/AMMetaDataParserService( 2881): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.android.settings.Settings$LockScreenSettingsActivity
I/AMMetaDataParserService( 2881): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2881): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.android.settings.Settings$DisplaySettingsActivity
I/AMMetaDataParserService( 2881): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2881): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2881): Resource data:2131429173
I/AMMetaDataParserService( 2881): getResourceName:com.android.settings:id/display_settings
I/AMMetaDataParserService( 2881): getResourceTypeNameid
I/AMMetaDataParserService( 2881): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.android.settings.DisplaySettings
I/AMMetaDataParserService( 2881): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2881): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2881): Resource data:213142,9173
I/AMMetaDataParserService( 2881): getResourceName:com.android.settings:id/display_settings
I/AMMetaDataParserService( 2881): getResourceTypeNameid
I/AMMetaDataParserService( 2881): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.android.settings.Settings$LockscreenMenuActivity
I/AMMetaDataParserService( 2881): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2881): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2881): Resource data:2131429172
I/AMMetaDataParserService( 2881): getResourceName:com.android.settings:id/lock_screen_menu_settings
I/AMMetaDataParserService( 2881): getResourceTypeNameid
I/AMMetaDataParserService( 2881): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.android.settings.LockscreenMenuSettings
I/AMMetaDataParserService( 2881): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2881): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2881): Resource data:2131429172
I/AMMetaDataParserService( 2881): getResourceName:com.android.settings:id/lock_screen_menu_settings
I/AMMetaDataParserService( 2881): getResourceTypeNameid
I/AMMetaDataParserService( 2881): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.android.settings.Settings$BlockSettingsActivity
I/AMMetaDataParserService( 2881): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2881): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2881): Resource data:2131429182
I/AMMetaDataParserService( 2881): getResourceName:com.android.settings:id/block_settings
I/AMMetaDataParserService( 2881): getResourceTypeNameid
I/AMMetaDataParserService( 2881): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.android.settings.Settings$LedIndicatorSettingsActivity
I/AMMetaDataParserService( 2881): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2881): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2881): Resource data:2131429173
I/AMMetaDataParserService( 2881): getResourceName:com.android.settings:id/display_settings
I/AMMetaDataParserService( 2881): getResourceTypeNameid
I/AMMetaDataParserService( 2881): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.android.settings.Settings$DockSettingsActivity
I/AMMetaDataParserService( 2881): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2881): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2881): Resource data:2131429186
I/AMMetaDataParserService( 2881): getResourceName:com.android.settings:id/dock_settings
I/AMMetaDataParserService( 2881): getResourceTypeNameid
I/AMMetaDataParserService( 2881): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.android.settings.DockSettings
I/AMMetaDataParserService( 2881): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2881): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2881): Resource data:2131429186
I/AMMetaDataParserService( 2881): getResourceName:com.android.settings:id/dock_settings
I/AMMetaDataParserService( 2881): getResourceTypeNameid
I/AMMetaDataParserService( 2881): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.android.settings.ContextualPageSettings
I/AMMetaDataParserService( 2881): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2881): getResourcePackageName:com.android.settings.TO,P_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2881): Resource data:2131429173
I/AMMetaDataParserService( 2881): getResourceName:com.android.settings:id/display_settings
I/AMMetaDataParserService( 2881): getResourceTypeNameid
I/AMMetaDataParserService( 2881): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2881): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 2881): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 2881): Resource data:2131297804
I/AMMetaDataParserService( 2881): getResourceName:com.android.settings:string/display_settings
I/AMMetaDataParserService( 2881): getResourceTypeNamestring
I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.android.settings.Settings$ContextualPageHelpActivity
I/AMMetaDataParserService( 2881): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2881): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2881): Resource data:2131429173
I/AMMetaDataParserService( 2881): getResourceName:com.android.settings:id/display_settings
I/AMMetaDataParserService( 2881): getResourceTypeNameid
I/AMMetaDataParserService( 2881): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.android.settings.Settings$DeviceInfoSettingsActivity
I/AMMetaDataParserService( 2881): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2881): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2881): Resource data:2131429228
I/AMMetaDataParserService( 2881): getResourceName:com.android.settings:id/about_settings
I/AMMetaDataParserService( 2881): getResourceTypeNameid
I/AMMetaDataParserService( 2881): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.android.settings.SettingsLicenseActivity
I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.android.settings.TermsAndConditionActivity
I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.android.settings.PrivacyAlertDialogActivity
I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.android.settings.PrivacyAlertProceedDialogActivity
I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.android.settings.SettingsSafetyLegalActivity
I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.android.settings.users.UserOptions
I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.android.settings.Settings$ManageApplicationsActivity
I/AMMetaDataParserService( 2881): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2881): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2881): Resource data:2131429128
I/AMMetaDataParserService( 2881): getResourceName:com.android.settings:id/application_settings
I/AMMetaDataParserService( 2881): getResourceTypeNameid
I/AMMetaDataParserService( 2881): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.android.settings.applications.ManageApplications
I/AMMetaDataParserService( 2881): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2881): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2881): Resource data:2131429128
I/AMMetaDataParserService( 2881): getResourceName:com.android.settings:id/application_settings
I/AMMetaDataParserService( 2881): getResourceTypeNameid
I/AMMetaDataParserService( 2881): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.android.settings.ManageApplications
I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.android.settings.Runnin,gServices
I/AMMetaDataParserService( 2881): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2881): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2881): Resource data:2131429128
I/AMMetaDataParserService( 2881): getResourceName:com.android.settings:id/application_settings
I/AMMetaDataParserService( 2881): getResourceTypeNameid
I/AMMetaDataParserService( 2881): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.android.settings.LaunchApplication
I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.android.settings.Settings$HomeSettingsActivity
I/AMMetaDataParserService( 2881): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2881): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2881): Resource data:2131429127
I/AMMetaDataParserService( 2881): getResourceName:com.android.settings:id/home_settings
I/AMMetaDataParserService( 2881): getResourceTypeNameid
I/AMMetaDataParserService( 2881): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.android.settings.HomeSettings
I/AMMetaDataParserService( 2881): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2881): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2881): Resource data:2131429127
I/AMMetaDataParserService( 2881): getResourceName:com.android.settings:id/home_settings
I/AMMetaDataParserService( 2881): getResourceTypeNameid
I/AMMetaDataParserService( 2881): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.android.settings.applications.StorageUse
I/AMMetaDataParserService( 2881): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2881): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2881): Resource data:2131429128
I/AMMetaDataParserService( 2881): getResourceName:com.android.settings:id/application_settings
I/AMMetaDataParserService( 2881): getResourceTypeNameid
I/AMMetaDataParserService( 2881): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.android.settings.applications.InstalledAppDetailsTop
I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.android.settings.applications.InstalledAppDetails
I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.android.settings.applications.UninstallMultipleScreen
I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.android.settings.users.AppRestrictionsFragment$Activity
I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.android.settings.Settings$RunningServicesActivity
I/AMMetaDataParserService( 2881): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2881): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/Babel   ( 3048): MmsConfig: mnc/mcc: 0/0
I/AMMetaDataParserService( 2881): Resource data:2131429128
I/AMMetaDataParserService( 2881): getResourceName:com.android.settings:id/application_settings
I/AMMetaDataParserService( 2881): getResourceTypeNameid
I/AMMetaDataParserService( 2881): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.android.settings.LaunchApplication
I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.android.settings.Settings$HomeSettingsActivity
I/AMMetaDataParserService( 2881): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2881): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2881): Resource data:2131429127
I/AMMetaDataParserService( 2881): getResourceName:com.android.settings:id/home_settings
I,/AMMetaDataParserService( 2881): getResourceTypeNameid
I/AMMetaDataParserService( 2881): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/Babel   ( 3048): MmsConfig.loadMmsSettings
I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.android.settings.HomeSettings
I/AMMetaDataParserService( 2881): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2881): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2881): Resource data:2131429127
I/AMMetaDataParserService( 2881): getResourceName:com.android.settings:id/home_settings
I/AMMetaDataParserService( 2881): getResourceTypeNameid
I/AMMetaDataParserService( 2881): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.android.settings.Settings$StorageUseActivity
I/AMMetaDataParserService( 2881): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2881): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2881): Resource data:2131429128
I/AMMetaDataParserService( 2881): getResourceName:com.android.settings:id/application_settings
I/AMMetaDataParserService( 2881): getResourceTypeNameid
I/AMMetaDataParserService( 2881): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.android.settings.Settings$NotificationStationActivity
I/AMMetaDataParserService( 2881): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2881): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.android.settings.Settings$LocationSettingsActivity
I/AMMetaDataParserService( 2881): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2881): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2881): Resource data:2131429153
I/AMMetaDataParserService( 2881): getResourceName:com.android.settings:id/location_settings
I/AMMetaDataParserService( 2881): getResourceTypeNameid
I/AMMetaDataParserService( 2881): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.android.settings.Settings$SecuritySettingsActivity
I/AMMetaDataParserService( 2881): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2881): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2881): Resource data:2131429224
I/AMMetaDataParserService( 2881): getResourceName:com.android.settings:id/security_settings
I/AMMetaDataParserService( 2881): getResourceTypeNameid
I/AMMetaDataParserService( 2881): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.android.settings.CarrierMatchSetting
,I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.android.settings.MonitoringCertInfoActivity
I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.android.settings.Settings$TrustedCredentialsSettingsActivity
I/AMMetaDataParserService( 2881): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2881): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2881): Resource data:2131429224
I/AMMetaDataParserService( 2881): getResourceName:com.android.settings:id/security_settings
I/AMMetaDataParserService( 2881): getResourceTypeNameid
I/AMMetaDataParserService( 2881): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2881): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 2881): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 2881): Resource data:2131296750
I/Babel   ( 3048): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=SAMSUNG-ANDROID-MMS/SM-G800H, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-G800H.xml
I/Babel   ( 3048): MmsConfig.loadFromDatabase
I/AMMetaDataParserService( 2881): getResourceName:com.android.settings:string/security_settings_title
,I/AMMetaDataParserService( 2881): getResourceTypeNamestring
I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.android.settings.SecuritySettings
I/AMMetaDataParserService( 2881): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2881): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2881): Resource data:2131429224
I/AMMetaDataParserService( 2881): getResourceName:com.android.settings:id/security_settings
I/AMMetaDataParserService( 2881): getResourceTypeNameid
I/AMMetaDataParserService( 2881): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.android.settings.Settings$PrivacySettingsActivity
I/AMMetaDataParserService( 2881): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2881): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2881): Resource data:2131429123
,I/AMMetaDataParserService( 2881): getResourceName:com.android.settings:id/privacy_settings
I/AMMetaDataParserService( 2881): getResourceTypeNameid
I/AMMetaDataParserService( 2881): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.android.settings.SetFullBackupPassword
I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.android.settings.CredentialStorage
I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.android.settings.Settings$DeviceAdminSettingsActivity
I/AMMetaDataParserService( 2881): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2881): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2881): Resource data:2131429224
I/AMMetaDataParserService( 2881): getResourceName:com.android.settings:id/security_settings
I/AMMetaDataParserService( 2881): getResourceTypeNameid
I/AMMetaDataParserService( 2881): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,I/AMMetaDataParserService( 2881): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 2881): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 2881): Resource data:2131296750
I/AMMetaDataParserService( 2881): getResourceName:com.android.settings:string/security_settings_title
I/AMMetaDataParserService( 2881): getResourceTypeNamestring
I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.android.settings.DeviceAdminSettings
I/AMMetaDataParserService( 2881): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2881): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2881): Resource data:2131429224
I/AMMetaDataParserService( 2881): getResourceName:com.android.settings:id/security_settings
I/AMMetaDataParserService( 2881): getResourceTypeNameid
I/AMMetaDataParserService( 2881): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2881): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
,I/AMMetaDataParserService( 2881): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 2881): Resource data:2131296750
I/AMMetaDataParserService( 2881): getResourceName:com.android.settings:string/security_settings_title
I/AMMetaDataParserService( 2881): getResourceTypeNamestring
I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.android.settings.DeviceAdminAdd
I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.android.settings.IccLockSettings
I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.android.settings.SimPinLockSettings
I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.android.settings.SimPersoLockSettings
I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.android.settings.Settings$AccessibilitySettingsActivity
I/AMMetaDataParserService( 2881): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 2881): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2881): Resource data:2131429187
I/AMMetaDataParserService( 2881): getResourceName:com.android.settings:id/accessibility_settings
I/AMMetaDataParserService( 2881): getResourceTypeNameid
I/AMMetaDataParserService( 2881): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.android.settings.Settings$CaptioningSettingsActivity
I/AMMetaDataParserService( 2881): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2881): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2881): Resource data:2131429187
I/AMMetaDataParserService( 2881): getResourceName:com.android.settings:id/accessibility_settings
I/AMMetaDataParserService( 2881): getResourceTypeNameid
,I/AMMetaDataParserService( 2881): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2881): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 2881): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 2881): Resource data:2131298587
I/AMMetaDataParserService( 2881): getResourceName:com.android.settings:string/accessibility_settings
I/AMMetaDataParserService( 2881): getResourceTypeNamestring
I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.android.settings.Settings$AssistantMenuPreferenceFragmentActivity
I/AMMetaDataParserService( 2881): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2881): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2881): Resource data:2131429187
I/AMMetaDataParserService( 2881): getResourceName:com.android.settings:id/accessibility_settings
,I/AMMetaDataParserService( 2881): getResourceTypeNameid
I/AMMetaDataParserService( 2881): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2881): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 2881): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 2881): Resource data:2131298587
W/Settings( 3048): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/AMMetaDataParserService( 2881): getResourceName:com.android.settings:string/accessibility_settings
I/AMMetaDataParserService( 2881): getResourceTypeNamestring
I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.android.settings.AccessibilitySettingsSetupWizard
I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.android.settings.Settings$TextToSpeechSettingsActivity
I/AMMetaDataParserService( 2881): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 2881): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2881): Resource data:2131429191
E/Babel   ( 3048): canonicalizeMccMnc: invalid mccmnc 
I/Babel   ( 3048): MmsConfig.loadFromResources
I/AMMetaDataParserService( 2881): getResourceName:com.android.settings:id/language_settings
I/AMMetaDataParserService( 2881): getResourceTypeNameid
I/AMMetaDataParserService( 2881): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.android.settings.Settings$DrivingModeSettingsActivity
I/AMMetaDataParserService( 2881): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2881): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2881): Resource data:2131429180
,I/AMMetaDataParserService( 2881): getResourceName:com.android.settings:id/driving_mode
I/AMMetaDataParserService( 2881): getResourceTypeNameid
I/AMMetaDataParserService( 2881): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.android.settings.Settings$AssistiveHepticSettingsActivity
I/AMMetaDataParserService( 2881): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2881): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.android.settings.ConfirmLockPattern
I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.android.settings.ConfirmLockPassword
I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.android.settings.BluetoothPairingWithCac
I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.android.settings.ChooseLockGeneric
I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.android.settings.ChooseLockGeneric$InternalActivity
,I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.android.settings.ChooseLockPattern
I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.android.settings.ChooseLockBLock
I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.android.settings.ChooseLockPassword
I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.android.settings.ChooseLockMotion
I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.android.settings.ChooseLockAdditionalPin
I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.android.settings.ChooseLockSignature
I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.android.settings.deviceinfo.Status
I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.android.settings.Settings$StorageSettingsActivity,
I/AMMetaDataParserService( 2881): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2881): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2881): Resource data:2131429223
E/Babel   ( 3048): canonicalizeMccMnc: invalid mccmnc nullnull
,I/AMMetaDataParserService( 2881): getResourceName:com.android.settings:id/storage_settings
I/AMMetaDataParserService( 2881): getResourceTypeNameid
I/AMMetaDataParserService( 2881): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.android.settings.deviceinfo.MiscFilesHandler
I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.android.settings.deviceinfo.DeviceInfoTabActivity
I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.android.settings.ApnEditor
I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.android.settings.MediaFormat
I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.android.settings.MediaFormatSd
I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.android.settings.quicklaunch.QuickLaunchSettings
I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.android.settings.quicklaunch.BookmarkPicker
I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.android.settings.Settings$DevelopmentSettingsActivity
,I/AMMetaDataParserService( 2881): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2881): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2881): Resource data:2131429225
I/AMMetaDataParserService( 2881): getResourceName:com.android.settings:id/development_settings
I/AMMetaDataParserService( 2881): getResourceTypeNameid
I/AMMetaDataParserService( 2881): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.android.settings.Settings$PrintSettingsActivity
I/AMMetaDataParserService( 2881): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2881): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 2881): Resource data:2131429159
I/Babel   ( 3048): MmsConfig.loadMmsSettings: mUserAgent=SAMSUNG-ANDROID-MMS/SM-G800H, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-G800H.xml
I/AMMetaDataParserService( 2881): getResourceName:com.android.settings:id/wireless_settings
I/AMMetaDataParserService( 2881): getResourceTypeNameid
I/AMMetaDataParserService( 2881): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2881): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 2881): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
,I/AMMetaDataParserService( 2881): Resource data:2131296695
I/AMMetaDataParserService( 2881): getResourceName:com.android.settings:string/wireless_networks_settings_title
I/AMMetaDataParserService( 2881): getResourceTypeNamestring
I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.android.settings.Settings$PrintJobSettingsActivity
I/AMMetaDataParserService( 2881): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 2881): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2881): Resource data:2131429165
I/AMMetaDataParserService( 2881): getResourceName:com.android.settings:id/print_settings
I/AMMetaDataParserService( 2881): getResourceTypeNameid
,I/AMMetaDataParserService( 2881): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.android.settings.DevelopmentSettings
I/AMMetaDataParserService( 2881): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2881): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2881): Resource data:2131429225
I/AMMetaDataParserService( 2881): getResourceName:com.android.settings:id/development_settings
I/AMMetaDataParserService( 2881): getResourceTypeNameid
I/AMMetaDataParserService( 2881): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.android.settings.AppPicker
I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.android.settings.Settings$UsbSettingsActivity
I/AMMetaDataParserService( 2881): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2881): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2881): Resource data:2131429223
,I/AMMetaDataParserService( 2881): getResourceName:com.android.settings:id/storage_settings
,I/AMMetaDataParserService( 2881): getResourceTypeNameid
I/AMMetaDataParserService( 2881): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2881): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 2881): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 2881): Resource data:2131297938
I/AMMetaDataParserService( 2881): getResourceName:com.android.settings:string/storage_settings_title
I/AMMetaDataParserService( 2881): getResourceTypeNamestring
I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.android.settings.UsbSettings
I/AMMetaDataParserService( 2881): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 2881): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2881): Resource data:2131429223
I/AMMetaDataParserService( 2881): getResourceName:com.android.settings:id/storage_settings
I/AMMetaDataParserService( 2881): getResourceTypeNameid
I/AMMetaDataParserService( 2881): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2881): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 2881): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 2881): Resource data:2131297938
I/AMMetaDataParserService( 2881): getResourceName:com.android.settings:string/storage_settings_title
,I/AMMetaDataParserService( 2881): getResourceTypeNamestring
I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.android.settings.bluetooth.BluetoothPairingDialog
I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.android.settings.bluetooth.RequestPermissionActivity
I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.android.settings.wifi.WifiScanModeActivity
I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.android.settings.bluetooth.RequestPermissionHelperActivity
I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.android.settings.bluetooth.BluetoothPermissionActivity
I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.android.settings.ActivityPicker
I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.android.settings.bluetooth.BluetoothEnableActivity
,I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.android.settings.bluetooth.BluetoothEnablingActivity
I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.android.settings.Settings$NfcSettingsActivity
I/AMMetaDataParserService( 2881): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2881): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2881): Resource data:2131429161
I/AMMetaDataParserService( 2881): getResourceName:com.android.settings:id/nfc_setting
I/AMMetaDataParserService( 2881): getResourceTypeNameid
I/AMMetaDataParserService( 2881): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.android.settings.nfc.NfcAdvancedRoutingSetting
,I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.android.settings.Settings$AndroidBeamSettingsActivity
I/AMMetaDataParserService( 2881): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2881): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.android.settings.Settings$SBeamSettingsActivity
I/AMMetaDataParserService( 2881): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2881): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2881): Resource data:2131429163
I/AMMetaDataParserService( 2881): getResourceName:com.android.settings:id/sbeam_setting
I/AMMetaDataParserService( 2881): getResourceTypeNameid
,I/AMMetaDataParserService( 2881): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.android.settings.Settings$WifiDisplaySettingsActivity
I/AMMetaDataParserService( 2881): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2881): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2881): Resource data:2131429167
I/AMMetaDataParserService( 2881): getResourceName:com.android.settings:id/screen_mirroring_settings
I/AMMetaDataParserService( 2881): getResourceTypeNameid
I/AMMetaDataParserService( 2881): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2881): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
,I/AMMetaDataParserService( 2881): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 2881): Resource data:2131296695
I/AMMetaDataParserService( 2881): getResourceName:com.android.settings:string/wireless_networks_settings_title
I/AMMetaDataParserService( 2881): getResourceTypeNamestring
I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.android.settings.BatteryInfo
I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.android.settings.Display
I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.android.settings.RadioInfo
I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.android.settings.ProxySelector
I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.android.settings.BandMode
I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.android.settings.TestingSettings
I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.android.settings.fulllocalepickertest.FullLocalePickerTest
,I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.android.settings.AppWidgetPickActivity
I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.android.settings.AllowBindAppWidgetActivity
I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.android.settings.KeyguardAppWidgetPickActivity
I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.android.settings.UsageStats
I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.android.settings.Settings$PowerUsageSummaryActivity
I/AMMetaDataParserService( 2881): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2881): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2881): Resource data:2131429221
I/AMMetaDataParserService( 2881): getResourceName:com.android.settings:id/battery_settings
I/AMMetaDataParserService( 2881): getResourceTypeNameid
,I/AMMetaDataParserService( 2881): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.android.settings.fuelgauge.PowerUsageSummary
I/AMMetaDataParserService( 2881): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2881): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2881): Resource data:2131429221
I/AMMetaDataParserService( 2881): getResourceName:com.android.settings:id/battery_settings
I/AMMetaDataParserService( 2881): getResourceTypeNameid
I/AMMetaDataParserService( 2881): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.android.settings.Settings$AccountSyncSettingsActivity
I/AMMetaDataParserService( 2881): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2881): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 2881): Resource data:2131429119
I/AMMetaDataParserService( 2881): getResourceName:com.android.settings:id/account_settings
I/AMMetaDataParserService( 2881): getResourceTypeNameid
I/AMMetaDataParserService( 2881): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.android.settings.accounts.SyncSettingsActivity
I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.android.settings.AccountMenu
I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.android.settings.Settings$AccountMenuActivity
I/AMMetaDataParserService( 2881): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2881): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 2881): Resource data:2131429217
I/AMMetaDataParserService( 2881): getResourceName:com.android.settings:id/header_general_account_and_backup
I/AMMetaDataParserService( 2881): getResourceTypeNameid
I/AMMetaDataParserService( 2881): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.android.settings.accounts.AddAccountSettings
I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.android.settings.accounts.ChooseAccountActivity
I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.android.settings.CryptKeeper
I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.android.settings.CryptKeeper$FadeToBlack
I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.android.settings.CryptKeeperConfirm$Blank
I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.android.settings.CryptDecryptConfirm$Blank
I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.android.settings.Settings$CryptKeeperSettingsActivity
I/AMMetaDataParserService( 2881): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2881): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 2881): Resource data:2131429224
I/AMMetaDataParserService( 2881): getResourceName:com.android.settings:id/security_settings
I/AMMetaDataParserService( 2881): getResourceTypeNameid
I/AMMetaDataParserService( 2881): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.android.settings.Settings$CryptSDCardSettingsActivity
I/AMMetaDataParserService( 2881): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2881): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2881): Resource data:2131429224
I/AMMetaDataParserService( 2881): getResourceName:com.android.settings:id/security_settings
,I/AMMetaDataParserService( 2881): getResourceTypeNameid
I/AMMetaDataParserService( 2881): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.android.settings.Settings$DataUsageSummaryActivity
I/AMMetaDataParserService( 2881): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2881): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2881): Resource data:2131429159
E/memtrack( 3031): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 3031): failed to load memtrack module: -2
I/AMMetaDataParserService( 2881): getResourceName:com.android.settings:id/wireless_settings
,I/AMMetaDataParserService( 2881): getResourceTypeNameid
I/AMMetaDataParserService( 2881): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.android.settings.AppEncryption
I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.android.settings.Settings$DreamSettingsActivity
I/AMMetaDataParserService( 2881): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2881): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2881): Resource data:2131429173
I/AMMetaDataParserService( 2881): getResourceName:com.android.settings:id/display_settings
I/AMMetaDataParserService( 2881): getResourceTypeNameid
,I/AMMetaDataParserService( 2881): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.android.settings.Settings$UserSettingsActivity
I/AMMetaDataParserService( 2881): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2881): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2881): Resource data:2131429208
,I/AMMetaDataParserService( 2881): getResourceName:com.android.settings:id/user_settings
I/AMMetaDataParserService( 2881): getResourceTypeNameid
I/AMMetaDataParserService( 2881): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.android.settings.Settings$PaymentSettingsActivity
I/AMMetaDataParserService( 2881): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2881): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 2881): Resource data:2131429286
I/AMMetaDataParserService( 2881): getResourceName:com.android.settings:id/nfc_payment_settings
,I/AMMetaDataParserService( 2881): getResourceTypeNameid
I/AMMetaDataParserService( 2881): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.android.settings.nfc.PaymentDefaultDialog
I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.android.settings.SmsDefaultDialog
I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.android.settings.Settings$NotificationAccessSettingsActivity
I/AMMetaDataParserService( 2881): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2881): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 2881): Resource data:2131429224
,I/AMMetaDataParserService( 2881): getResourceName:com.android.settings:id/security_settings
I/AMMetaDataParserService( 2881): getResourceTypeNameid
I/AMMetaDataParserService( 2881): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.android.settings.RegulatoryInfoDisplayActivity
I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.android.settings.FactoryResetDialog
I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.android.settings.LockScreenWallpaper
,I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.android.settings.Settings$WallpaperSettingsActivity
I/AMMetaDataParserService( 2881): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 2881): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 2881): Resource data:2131429201
D/dalvikvm( 3048): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
I/AMMetaDataParserService( 2881): getResourceName:com.android.settings:id/header_display_wallpaper
,I/AMMetaDataParserService( 2881): getResourceTypeNameid
I/AMMetaDataParserService( 2881): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.android.settings.InformationTicker
I/AMMetaDataParserService( 2881): Resource data:Inside bundle  check
W/dalvikvm( 3048): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
D/dalvikvm( 3048): VFY: replacing opcode 0x62 at 0x000a
I/AMMetaDataParserService( 2881): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.android.settings.GSensorSettings
I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.android.settings.ASensorSettings
I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.android.settings.Settings$PowerSavingModeSettingsActivity
I/AMMetaDataParserService( 2881): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2881): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
D/dalvikvm( 3048): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
,I/AMMetaDataParserService( 2881): Resource data:2131429185
W/dalvikvm( 3048): VFY: unable to resolve instance field 36
,D/dalvikvm( 3048): VFY: replacing opcode 0x54 at 0x005f
I/AMMetaDataParserService( 2881): getResourceName:com.android.settings:id/power_saving_mode
I/AMMetaDataParserService( 2881): getResourceTypeNameid
I/AMMetaDataParserService( 2881): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.android.settings.Settings$PowerSavingMode2014Activity
I/AMMetaDataParserService( 2881): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2881): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 2881): Resource data:2131429185
V/Babel   ( 3048): babel boot account: thalitester@gmail.com
I/AMMetaDataParserService( 2881): getResourceName:com.android.settings:id/power_saving_mode
I/AMMetaDataParserService( 2881): getResourceTypeNameid
I/AMMetaDataParserService( 2881): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2881): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 2881): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
,I/AMMetaDataParserService( 2881): Resource data:2131299843
V/Babel   ( 3048): babel boot account: SMS
I/AMMetaDataParserService( 2881): getResourceName:com.android.settings:string/power_saving_mode_title
I/AMMetaDataParserService( 2881): getResourceTypeNamestring
I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.android.settings.Settings$PowerSavingModeSettings2014Activity
I/AMMetaDataParserService( 2881): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 2881): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2881): Resource data:2131429185
,I/AMMetaDataParserService( 2881): getResourceName:com.android.settings:id/power_saving_mode
I/AMMetaDataParserService( 2881): getResourceTypeNameid
I/AMMetaDataParserService( 2881): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.android.settings.Settings$UltraPowerSavingModeActivity
I/AMMetaDataParserService( 2881): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 2881): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 2881): Resource data:2131429185
,I/AMMetaDataParserService( 2881): getResourceName:com.android.settings:id/power_saving_mode
I/AMMetaDataParserService( 2881): getResourceTypeNameid
I/AMMetaDataParserService( 2881): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.android.settings.ModePreviewTablet
I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.android.settings.ModePreviewDialog
,I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.android.settings.InkeffectPreview
I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.android.settings.InkeffectPreviewTablet
I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.android.settings.ModePreview
I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.android.settings.NewModePreview
I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.android.settings.SViewColor
,I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.android.settings.ChooseLockFaceWarning
I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.android.settings.AskUSBMode
I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.android.settings.Settings$PowerSettingsActivity
I/AMMetaDataParserService( 2881): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2881): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 2881): Resource data:2131429222
,I/AMMetaDataParserService( 2881): getResourceName:com.android.settings:id/power_settings
I/AMMetaDataParserService( 2881): getResourceTypeNameid
I/AMMetaDataParserService( 2881): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.android.settings.RecommendRingtoneDialog
I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.android.settings.Settings$SelectInfoCoverSettingsActivity
,I/AMMetaDataParserService( 2881): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2881): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 2881): Resource data:2131429186
I/AMMetaDataParserService( 2881): getResourceName:com.android.settings:id/dock_settings
I/AMMetaDataParserService( 2881): getResourceTypeNameid
,I/AMMetaDataParserService( 2881): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.android.settings.SelectItemDisplay
I/AMMetaDataParserService( 2881): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2881): getResourcePackageName:com.sec.android.sdk.cover.MODE
,I/AMMetaDataParserService( 2881): Resource data:1
,W/ResourceType( 2881): No package identifier when getting name for resource number 0x00000001
,W/System.err( 2881): android.content.res.Resources$NotFoundException: Unable to find resource ID #0x1
W/System.err( 2881): 	at android.content.res.Resources.getResourceName(Resources.java:3017)
W/System.err( 2881): 	at com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.constructDBdata(AMMetaDataParserService.java:159)
W/System.err( 2881): 	at com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent(AMMetaDataParserService.java:86)
,W/System.err( 2881): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
W/System.err( 2881): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 2881): 	at android.os.Looper.loop(Looper.java:146)
W/System.err( 2881): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.android.settings.WarrantyLegal
,I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.android.settings.PenDetachmentOption
I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.android.settings.Settings$PenDetachmentOptionActivity
I/AMMetaDataParserService( 2881): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2881): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 2881): Resource data:2131429199
D/dalvikvm( 3048): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 3048): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 3048): VFY: replacing opcode 0x62 at 0x0047
I/AMMetaDataParserService( 2881): getResourceName:com.android.settings:id/pen_settings_menu
I/AMMetaDataParserService( 2881): getResourceTypeNameid
,I/AMMetaDataParserService( 2881): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2881): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 2881): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
,I/AMMetaDataParserService( 2881): Resource data:2131301070
I/AMMetaDataParserService( 2881): getResourceName:com.android.settings:string/pen_settings
I/AMMetaDataParserService( 2881): getResourceTypeNamestring
I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.android.settings.NotificationPanelMenu
I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.android.settings.Settings$NotificationPanelMenuActivity
,I/AMMetaDataParserService( 2881): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2881): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 2881): Resource data:2131429173
,I/AMMetaDataParserService( 2881): getResourceName:com.android.settings:id/display_settings
I/AMMetaDataParserService( 2881): getResourceTypeNameid
I/AMMetaDataParserService( 2881): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2881): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 2881): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
,I/AMMetaDataParserService( 2881): Resource data:2131297804
I/AMMetaDataParserService( 2881): getResourceName:com.android.settings:string/display_settings
I/AMMetaDataParserService( 2881): getResourceTypeNamestring
I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.android.settings.NotificationPanelSettings
I/AMMetaDataParserService( 2881): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2881): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2881): Resource data:2131429203
D/dalvikvm( 3048): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
I/dalvikvm( 3048): DexOpt: unable to optimize instance field ref 0x0024 at 0x63 in Lcom/google/android/gms/common/util/ay;.b
D/dalvikvm( 3031): Note: class Landroid/app/ActivityManagerNative; has 192 unimplemented (abstract) methods
I/AMMetaDataParserService( 2881): getResourceName:com.android.settings:id/header_display_notification_panel
I/AMMetaDataParserService( 2881): getResourceTypeNameid
I/AMMetaDataParserService( 2881): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.android.settings.Settings$MotionSettingsActivity
I/AMMetaDataParserService( 2881): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2881): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 2881): Resource data:2131429193
I/SELinux ( 3080): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 3080):  
I/AMMetaDataParserService( 2881): getResourceName:com.android.settings:id/motion_settings
I/AMMetaDataParserService( 2881): getResourceTypeNameid
I/AMMetaDataParserService( 2881): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.android.settings.motion.ShakeTutorial
I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.android.settings.Settings$AirMotionSettingActivity
I/AMMetaDataParserService( 2881): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2881): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 2881): Resource data:2131429194
,I/AMMetaDataParserService( 2881): getResourceName:com.android.settings:id/s_motion_settings
I/AMMetaDataParserService( 2881): getResourceTypeNameid
I/AMMetaDataParserService( 2881): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.android.settings.Settings$SMotionGuideHub2014Activity
I/AMMetaDataParserService( 2881): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 2881): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 2881): Resource data:2131429206
I/AMMetaDataParserService( 2881): getResourceName:com.android.settings:id/header_input_motion_and_gesture_2014
,I/AMMetaDataParserService( 2881): getResourceTypeNameid
,I/AMMetaDataParserService( 2881): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2881): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 2881): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
,I/AMMetaDataParserService( 2881): Resource data:2131300118
I/AMMetaDataParserService( 2881): getResourceName:com.android.settings:string/motions_title
,I/AMMetaDataParserService( 2881): getResourceTypeNamestring
I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.android.settings.Settings$FingerAirViewSettingActivity
I/AMMetaDataParserService( 2881): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2881): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 2881): Resource data:2131429196
I/AMMetaDataParserService( 2881): getResourceName:com.android.settings:id/finger_air_view_settings
I/AMMetaDataParserService( 2881): getResourceTypeNameid
,I/AMMetaDataParserService( 2881): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.android.settings.Settings$FingerAirViewHelpSettingActivity
I/AMMetaDataParserService( 2881): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2881): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 2881): Resource data:2131429260
,I/AMMetaDataParserService( 2881): getResourceName:com.android.settings:id/finger_air_view_settings_k
,I/AMMetaDataParserService( 2881): getResourceTypeNameid
,I/AMMetaDataParserService( 2881): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.android.settings.Settings$AirViewSettingActivity
I/AMMetaDataParserService( 2881): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2881): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 2881): Resource data:2131429197
,I/ActivityManager(  745): Killing 2191:com.sec.kidsplat.installer/u0a158 (adj 15): empty #43
I/AMMetaDataParserService( 2881): getResourceName:com.android.settings:id/air_view_settings
I/AMMetaDataParserService( 2881): getResourceTypeNameid
I/AMMetaDataParserService( 2881): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.android.settings.Settings$MouseHoveringSettingsActivity
I/AMMetaDataParserService( 2881): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2881): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2881): Resource data:2131429291
I/AMMetaDataParserService( 2881): getResourceName:com.android.settings:id/mouse_hovering_settings
I/AMMetaDataParserService( 2881): getResourceTypeNameid
I/AMMetaDataParserService( 2881): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.android.settings.Settings$SoftwareUpdateSettingActivity
I/AMMetaDataParserService( 2881): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2881): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2881): Resource data:2131429228
I/AMMetaDataParserService( 2881): getResourceName:com.android.settings:id/about_settings
I/AMMetaDataParserService( 2881): getResourceTypeNameid
I/AMMetaDataParserService( 2881): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.android.settings.PenHovering
I/AMMetaDataParserService( 2881): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2881): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.android.settings.PenHelpActivity
I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.android.settings.Settings$PenHelpFragmentActivity
I/AMMetaDataParserService( 2881): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2881): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2881): Resource data:2131429199
I/AMMetaDataParserService( 2881): getResourceName:com.android.settings:id/pen_settings_menu
D/dalvikvm( 3048): Trying to load lib /data/app-lib/com.google.android.gms-2/libgmscore.so 0x427c5038
I/AMMetaDataParserService( 2881): getResourceTypeNameid
I/AMMetaDataParserService( 2881): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.android.settings.Settings$DirectPenInputSettingsActivity
I/AMMetaDataParserService( 2881): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2881): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2881): Resource data:2131429199
I/AMMetaDataParserService( 2881): getResourceName:com.android.settings:id/pen_settings_menu
I/AMMetaDataParserService( 2881): getResourceTypeNameid
I/AMMetaDataParserService( 2881): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.android.settings.Settings$PenAirViewSettingsMenuActivity
I/AMMetaDataParserService( 2881): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2881): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2881): Resource data:2131429199
I/AMMetaDataParserService( 2881): getResourceName:com.android.settings:id/pen_settings_menu
I/AMMetaDataParserService( 2881): getResourceTypeNameid
I/AMMetaDataParserService( 2881): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.android.settings.Settings$PenSettingsMenuActivity
I/AMMetaDataParserService( 2881): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2881): getReso,urcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2881): Resource data:2131429199
I/AMMetaDataParserService( 2881): getResourceName:com.android.settings:id/pen_settings_menu
I/AMMetaDataParserService( 2881): getResourceTypeNameid
I/AMMetaDataParserService( 2881): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.android.settings.PenHelpPopup
I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.android.settings.PhoneVibration
I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.android.settings.OneHandHelp
I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.android.settings.EnableScreenHelp
I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.android.settings.OneHandAdaptiveHelp
I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.android.settings.InputControlHelp
I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.android.settings.personalvibration.PersonalVibration
I/AMMetaDataParserService( 2881): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2881): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.android.settings.NetworkManagement
I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.android.settings.MultiSimCardManagerPreference
I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.android.settings.NetworkManagementSetting
I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.android.settings.DualHelpActivity
I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.android.settings.DualSoundRingtoneSettings
I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.android.settings.RingtoneSettingTabActivity
I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.android.settings.IccLockTabSettings
I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.android.settings.personalvibration.SelectPatternDialog
I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.android.settings.lockscreenshortcut.LockScreenShortcutSettings
I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.android.settings.lockscreenshortcut.AppList
I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.android.settings.lockscreenshortcut.ExpandAppList
I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.android.settings.Settings$ReadingModeSettingsActivity
I/AMMetaDataParserService( 2881): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2881): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2881): Resource data:2131429173
I/AMMetaDataParserService( 2881): getResourceName:com.android.settings:id/display_settings
I/AMMetaDataParserService( 2881): getResourceTypeNameid
I/AMMetaDataParserService( 2881): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.android.settings.ReadingModeSettings
I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.android.settings.customizablekey.CustomizableKeySettings
I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.android.settings.Settings$CustomizableKeySettingsActivity
I/AMMetaDataParserService( 2881): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2881): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2881): Resource data:2131429285
I/AMMetaDataParserService( 2881): getResourceName:com.android.settings:id/customizable_key
I/AMMetaDataParserService( 2881): getResourceTypeNameid
I/AMMetaDataParserService( 2881): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.android.settings.customizablekey.AppList
I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.android.settings.Settings$DualClockSettingActivity
I/AMMetaDataParserService( 2881): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2881): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2881): Resource data:2131429172
I/AMMetaDataParserService( 2881): getResourceName:com.android.settings:id/lock_screen_menu_settings
I/AMMetaDataParserService( 2881): getResourceTypeNameid
I/AMMetaDataParserService( 2881): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2881): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 2881): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 2881): Resource data:2131301505
I/AMMetaDataParserService( 2881): getResourceName:com.android.settings:string/lock_screen_options
I/AMMetaDataParserService( 2881): getResourceTypeNamestring
I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.android.settings.Settings$RecommendedAppsMenuActivity
I/AMMetaDataParserService( 2881): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2881): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2881): Resource data:2131429203
I/AMMetaDataParserService( 2881): getResourceName:com.android.settings:id/header_display_notification_panel
I/AMMetaDataParserService( 2881): getResourceTypeNameid
I/AMMetaDataParserService( 2881): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.android.settings.Settings$RecommendedAppsListActivity
I/AMMetaDataParserService( 2881): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2881): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2881): Resource data:2131429203
I/AMMetaDataParserService( 2881): getResourceName:com.android.settings:id/header_display_notification_panel
I/AMMetaDataParserService( 2881): getResourceTypeNameid
I/AMMetaDataParserService( 2881): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2881): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 2881): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 2881): Resource data:2131302910
I/AMMetaDataParserService( 2881): getResourceName:com.android.settings:string/recommended_apps
I/AMMetaDataParserService( 2881): getResourceTypeNamestring
I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.android.settings.SettingsReceiverActivity
I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.android.settings.SelectPenDetachNotiDialog
I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.bst.airmessage.setting.AirMsgSetting
I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.android.settings.SecurityWarningDialog
I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.android.settings.Settings$DormantmodeSettingsActivity
I/AMMetaDataParserService( 2881): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2881): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2881): Resource data:2131429179
I/AMMetaDataParserService( 2881): getResourceName:com.android.settings:id/dormant_mode
I/AMMetaDataParserService( 2881): getResourceTypeNameid
I/AMMetaDataParserService( 2881): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.android.settings.dormantmode.DormantmodeSettings
I/AMMetaDataParserService( 2881): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2881): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2881): Resource data:2130838248
I/AMMetaDataParserService( 2881): getResourceName:com.android.settings:drawable/ic_settings_dormant_mode
I/AMMetaDataParserService( 2881): getResourceTypeNamedrawable
I/AMMetaDataParserService( 2881): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.android.settings.dormantmode.DormantModeCustomList
I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.android.settings.dormantmode.DormantModeCustomListDel
I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.android.settings.Settings$GlanceSettingsActivity
I/AMMetaDataParserService( 2881): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2881): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2881): Resource data:2131429216
I/AMMetaDataParserService( 2881): getResourceName:com.android.settings:id/glance_settings
I/AMMetaDataParserService( 2881): getResourceTypeNameid
I/AMMetaDataParserService( 2881): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.android.settings.Settings$PersonalPageSettingsActivity
I/AMMetaDataParserService( 2881): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2881): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2881): Resource data:2131429209
I/AMMetaDataParserService( 2881): getResourceName:com.android.settings:id/header_personal_page
I/AMMetaDataParserService( 2881): getResourceTypeNameid
I/AMMetaDataParserService( 2881): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageSettings
I/AMMetaDataParserService( 2881): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2881): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2881): Resource data:2131429209
I/AMMetaDataParserService( 2881): getResourceName:com.android.settings:id/header_personal_page
I/AMMetaDataParserService( 2881): getResourceTypeNameid
I/AMMetaDataParserService( 2881): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.android.settings.PersonalPageDisclaimer
I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageTutorial
I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageTutorialAppActivity
I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageTutorialAddActivity
I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageChooseLockPattern
I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageChooseLockPassword
I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageChooseLockAdditionalPin
I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageConfirmLockPattern
I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageConfirmLockPassword
I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageAlertDialogActivity
I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.android.settings.Settings$EasyModeSettingsActivity
I/AMMetaDataParserService( 2881): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2881): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2881): Resource data:2131429177
I/AMMetaDataParserService( 2881): getResourceName:com.android.settings:id/home_screen_mode_settings
I/AMMetaDataParserService( 2881): getResourceTypeNameid
I/AMMetaDataParserService( 2881): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.android.settings.Settings$EasyModeActivity
I/AMMetaDataParserService( 2881): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2881): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2881): Resource data:2131429212
I/AMMetaDataParserService( 2881): getResourceName:com.android.settings:id/easy_mode_settings
I/AMMetaDataParserService( 2881): getResourceTypeNameid
I/AMMetaDataParserService( 2881): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.android.settings.Settings$EasyModeAppActivity
I/AMMetaDataParserService( 2881): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2881): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2881): Resource data:2131429213
I/AMMetaDataParserService( 2881): getResourceName:com.android.settings:id/easy_mode_app_settings
I/AMMetaDataParserService( 2881): getResourceTypeNameid
I/AMMetaDataParserService( 2881): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.android.settings.LocationAlert
I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.android.settings.Settings$MyPlaceSettingsActivity
I/AMMetaDataParserService( 2881): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2881): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2881): Resource data:2131429153
I/AMMetaDataParserService( 2881): getResourceName:com.android.settings:id/location_settings
I/AMMetaDataParserService( 2881): getResourceTypeNameid
I/AMMetaDataParserService( 2881): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2881): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 2881): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 2881): Resource data:2131302078
I/AMMetaDataParserService( 2881): getResourceName:com.android.settings:string/myplace_title
D/dalvikvm( 3048): Added shared lib /data/app-lib/com.google.android.gms-2/libgmscore.so 0x427c5038
D/dalvikvm( 3048): No JNI_OnLoad found in /data/app-lib/com.google.android.gms-2/libgmscore.so 0x427c5038, skipping init
I/SELinux ( 3080): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 3080):  
I/SELinux ( 3080):  
I/SELinux ( 3080): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
I/AMMetaDataParserService( 2881): getResourceTypeNamestring
I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.android.settings.Settings$MyPlaceProfileSettingsActivity
I/AMMetaDataParserService( 2881): Resource data:Inside bundle  check
E/SELinux ( 3080): [DEBUG] seapp_context_lookup: seinfoCategory = platform
I/AMMetaDataParserService( 2881): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2881): Resource data:2131429153
E/dalvikvm( 3080): >>>>> Normal User
E/dalvikvm( 3080): >>>>> com.samsung.helphub [ userId:0 | appId:1000 ]
I/AMMetaDataParserService( 2881): getResourceName:com.android.settings:id/location_settings
D/AndroidRuntime( 3031): Calling main entry com.android.commands.pm.Pm
I/AMMetaDataParserService( 2881): getResourceTypeNameid
I/AMMetaDataParserService( 2881): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2881): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 2881): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
D/dalvikvm( 3048): Trying to load lib /data/app-lib/com.google.android.gms-2/libconscrypt_gmscore_jni.so 0x427c5038
I/AMMetaDataParserService( 2881): Resource data:2131302078
E/SELinux ( 3080): [DEBUG] seapp_context_lookup: seinfoCategory = platform
I/AMMetaDataParserService( 2881): getResourceName:com.android.settings:string/myplace_title
I/AMMetaDataParserService( 2881): getResourceTypeNamestring
I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.android.settings.Settings$PlaceSettingsActivity
I/AMMetaDataParserService( 2881): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2881): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2881): Resource data:2131429153
I/AMMetaDataParserService( 2881): getResourceName:com.android.settings:id/location_settings
D/dalvikvm( 3048): Added shared lib /data/app-lib/com.google.android.gms-2/libconscrypt_gmscore_jni.so 0x427c5038
V/JNIHelp ( 3048): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
I/AMMetaDataParserService( 2881): getResourceTypeNameid
I/AMMetaDataParserService( 2881): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2881): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 2881): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 2881): Resource data:2131302107
I/AMMetaDataParserService( 2881): getResourceName:com.android.settings:string/place_settings_title
I/AMMetaDataParserService( 2881): getResourceTypeNamestring
I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.android.settings.myplace.SelectMapActivity
I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.android.settings.Settings$GlobalRoamingSettingsActivity
I/AMMetaDataParserService( 2881): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2881): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2881): Resource data:2131429159
I/AMMetaDataParserService( 2881): getResourceName:com.android.settings:id/wireless_settings
I/AMMetaDataParserService( 2881): getResourceTypeNameid
I/AMMetaDataParserService( 2881): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.android.settings.Settings$TRoamingSettingsActivity
I/AMMetaDataParserService( 2881): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2881): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2881): Resource data:2131429159
I/AMMetaDataParserService( 2881): getResourceName:com.android.settings:id/wireless_settings
I/AMMetaDataParserService( 2881): getResourceTypeNameid
I/AMMetaDataParserService( 2881): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.android.settings.flipfont.FontListActivity
I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.android.settings.flipfont.FontListProgressActivity
I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.android.settings.Settings$BackupAssistantPlusSettingsActivity
I/AMMetaDataParserService( 2881): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2881): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2881): Resource data:2131429117
I/AMMetaDataParserService( 2881): getResourceName:com.android.settings:id/bua_plus
I/AMMetaDataParserService( 2881): getResourceTypeNameid
I/AMMetaDataParserService( 2881): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.android.settings.myprofile.MyProfileActivity
I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.android.settings.MagazineCard
I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.android.settings.Settings$ClockWidgetActivity
I/AMMetaDataParserService( 2881): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2881): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.android.settings.myprofile.PersonalMessage
I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.android.settings.Settings$CloudPictureSyncSettingActivity
I/AMMetaDataParserService( 2881): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2881): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.android.settings.Settings$CloudVideoSyncSettingActivity
I/AMMetaDataParserService( 2881): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2881): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.android.settings.Settings$CloudSettingActivity
I/AMMetaDataParserService( 2881): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2881): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2881): Resource data:2131429122
I/AMMetaDataParserService( 2881): getResourceName:com.android.settings:id/scloud_settings
I/AMMetaDataParserService( 2881): getResourceTypeNameid
I/AMMetaDataParserService( 2881): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.android.settings.ShortCameraMenu
I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.android.settings.ClockMyprofileMenu
I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.android.settings.ClockMyprofileMenuTablet
I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.android.settings.Settings$LaunchCameraSettingsActivity
I/AMMetaDataParserService( 2881): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2881): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.android.settings.Settings$SmartScreenSettingsActivity
I/AMMetaDataParserService( 2881): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2881): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2881): Resource data:2131429195
I/AMMetaDataParserService( 2881): getResourceName:com.android.settings:id/smart_screen
I/AMMetaDataParserService( 2881): getResourceTypeNameid
I/AMMetaDataParserService( 2881): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2881): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 2881): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 2881): Resource data:2131297804
I/AMMetaDataParserService( 2881): getResourceName:com.android.settings:string/display_settings
I/AMMetaDataParserService( 2881): getResourceTypeNamestring
I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.android.settings.Settings$SmartBondingSettingsActivity
I/AMMetaDataParserService( 2881): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2881): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2881): Resource data:2131429151
D/TimaKeyStoreProvider( 3080): in addTimaSignatureService
D/PackageManagerService(  745): deletePackageAsUser- pkg:com.example.hello, userId:0
D/PersonaManagerService(  745): isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
D/PersonaManagerService(  745): isFromApprovedUnInstaller: isApproved : true
D/PersonaManagerService(  745): isFromApprovedUnInstaller: isApproved before exit: true
D/PackageManager(  745): deletePackageAsUser- pkg:com.example.hello, userId:0, flag3
I/AMMetaDataParserService( 2881): getResourceName:com.android.settings:id/smart_bonding_settings
D/PackageManager(  745): deletePackageAsUser- pkg:com.example.hello, userId:0, flag3
I/AMMetaDataParserService( 2881): getResourceTypeNameid
I/AMMetaDataParserService( 2881): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.android.settings.Settings$ToolboxMenuActivity
I/AMMetaDataParserService( 2881): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2881): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2881): Resource data:2131429204
D/TimaKeyStoreProvider( 3080): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 3080): Added TimaKesytore provider
D/PackageManager(  745): START PACKAGE DELETE: observer{1125426400}
D/PackageManager(  745): pkg{<packageName>}
D/PackageManager(  745): user{0}
D/PackageManager(  745): deletePackageAsUser : uid = 2000 userId = 0
I/AMMetaDataParserService( 2881): getResourceName:com.android.settings:id/header_toolbox
I/AMMetaDataParserService( 2881): getResourceTypeNameid
I/AMMetaDataParserService( 2881): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.android.settings.Settings$ToolboxListActivity
I/AMMetaDataParserService( 2881): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2881): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2881): Resource data:2131429204
D/PackageManagerService(  745): deletePackage- pkg:com.example.hello, edmuserId:0
D/PackageManagerService(  745): deletePackage- pkg:com.example.hello, edmuserId:-1
D/ApplicationPolicy(  745): getApplicationUninstallationEnabled
D/ApplicationPolicy(  745): getApplicationUninstallationEnabled :  enabled true
D/PackageManagerService(  745): deletePackageX- pkg:com.example.hello, userId:0
I/AMMetaDataParserService( 2881): getResourceName:com.android.settings:id/header_toolbox
I/AMMetaDataParserService( 2881): getResourceTypeNameid
I/AMMetaDataParserService( 2881): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.android.settings.Settings$SmartScrollAdvancedSettingsActivity
I/AMMetaDataParserService( 2881): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2881): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2881): Resource data:2131429195
I/AMMetaDataParserService( 2881): getResourceName:com.android.settings:id/smart_screen
I/AMMetaDataParserService( 2881): getResourceTypeNameid
I/AMMetaDataParserService( 2881): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.android.settings.Settings$TorchlightSettingsActivity
I/AMMetaDataParserService( 2881): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2881): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2881): Resource data:2130838300
I/AMMetaDataParserService( 2881): getResourceName:com.android.settings:drawable/ic_settings_torchlight
I/AMMetaDataParserService( 2881): getResourceTypeNamedrawable
I/AMMetaDataParserService( 2881): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.android.settings.torchlight.TorchlightSettings
I/AMMetaDataParserService( 2881): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2881): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2881): Resource data:2130838300
I/AMMetaDataParserService( 2881): getResourceName:com.android.settings:drawable/ic_settings_torchlight
I/AMMetaDataParserService( 2881): getResourceTypeNamedrawable
I/AMMetaDataParserService( 2881): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.android.settings.Settings$MultiWindowSettingsActivity
I/AMMetaDataParserService( 2881): Resource data:Inside bundle  check
,D/PackageManager(  745): [MSG] DELETE_PACKAGE_AS_USER
I/AMMetaDataParserService( 2881): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2881): Resource data:2131429202
I/AMMetaDataParserService( 2881): getResourceName:com.android.settings:id/header_display_multi_window
I/AMMetaDataParserService( 2881): getResourceTypeNameid
I/AMMetaDataParserService( 2881): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.android.settings.MultiWindowSettings
I/AMMetaDataParserService( 2881): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2881): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2881): Resource data:2131429202
I/AMMetaDataParserService( 2881): getResourceName:com.android.settings:id/header_display_multi_window
I/AMMetaDataParserService( 2881): getResourceTypeNameid
I/AMMetaDataParserService( 2881): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.android.settings.settingssearch.SettingsSearchActivity
I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.android.settings.search.SearchMain
I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.android.settings.SearchActivity
I/AMMetaDataParserService( 2881): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2881): getResourcePackageName:android.app.searchable
I/AMMetaDataParserService( 2881): Resource data:2131165381
I/AMMetaDataParserService( 2881): getResourceName:com.android.settings:xml/searchable
I/AMMetaDataParserService( 2881): getResourceTypeNamexml
I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.android.settings.settingssearch.SettingsSearchActivity
I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.android.settings.Settings$HomeSyncBackupAndRestoreActivity
I/AMMetaDataParserService( 2881): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2881): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2881): Resource data:2131429124
I/AMMetaDataParserService( 2881): getResourceName:com.android.settings:id/homesync_backup_and_restore_settings
I/AMMetaDataParserService( 2881): getResourceTypeNameid
I/AMMetaDataParserService( 2881): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.android.settings.Settings$ColorChipReportActivity
W/ContextImpl(  745): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
I/AMMetaDataParserService( 2881): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2881): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2881): Resource data:2131429187
I/AMMetaDataParserService( 2881): getResourceName:com.android.settings:id/accessibility_settings
I/AMMetaDataParserService( 2881): getResourceTypeNameid
I/AMMetaDataParserService( 2881): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2881): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 2881): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 2881): Resource data:2131298587
I/AMMetaDataParserService( 2881): getResourceName:com.android.settings:string/accessibility_settings
I/AMMetaDataParserService( 2881): getResourceTypeNamestring
I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.android.settings.Settings$DirectAccessActivity
I/AMMetaDataParserService( 2881): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2881): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.android.settings.Settings$NotificationReminderActivity
I/AMMetaDataParserService( 2881): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2881): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.android.settings.Settings$VoiceInputControlSettingsActivity
I/AMMetaDataParserService( 2881): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2881): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2881): Resource data:2131429198
I/AMMetaDataParserService( 2881): getResourceName:com.android.settings:id/voice_input_control_settings
I/AMMetaDataParserService( 2881): getResourceTypeNameid
I/AMMetaDataParserService( 2881): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.android.settings.PreloadAppUpdate
I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.android.settings.PreloadAppUpdateList
I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.android.settings.activekey.ActiveKeySettings
I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.android.settings.Settings$ActiveKeySettingsActivity
I/AMMetaDataParserService( 2881): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2881): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2881): Resource data:2131429258
I/AMMetaDataParserService( 2881): getResourceName:com.android.settings:id/active_key_settings
I/AMMetaDataParserService( 2881): getResourceTypeNameid
I/AMMetaDataParserService( 2881): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.android.settings.activekey.AppList
I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.android.settings.Settings$DisplaySettingsTab
I/AMMetaDataParserService( 2881): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2881): getResourcePackageName:com.android.settings.SETTING_HEADER_ID
I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.android.settings.Settings$InputAndControlSettingsTab
I/AMMetaDataParserService( 2881): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2881): getResourcePackageName:com.android.settings.SETTING_HEADER_ID
I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.android.settings.Settings$GeneralSettingsTab
I/AMMetaDataParserService( 2881): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2881): getResourcePackageName:com.android.settings.SETTING_HEADER_ID
I/PowerManagerService(  745): [PWL] On : 0 (44908 ms ago)
I/PowerManagerService(  745): [PWL]  mStayOn: false  mWakeLockSummary & WAKE_LOCK_STAY_AWAKE: 20  mUserActivitySummary: 0x0
I/PowerManagerService(  745): [PWL]  SCREEN_DIM_WAKE_LOCK           'PowerUI' ACQUIRE_CAUSES_WAKEUP (uid=10019, pid=1069, ws=null) (elapsedTime=7323)
I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.android.settings.DeviceHealthActivity
I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.android.settings.Settings$SettingsEmergencyActivity
I/AMMetaDataParserService( 2881): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2881): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2881): Resource data:2131429220
I/AMMetaDataParserService( 2881): getResourceName:com.android.settings:id/safetycare_settings
I/AMMetaDataParserService( 2881): getResourceTypeNameid
I/AMMetaDataParserService( 2881): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.android.settings.Settings$SafetyCareSettingsActivity
I/AMMetaDataParserService( 2881): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2881): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2881): Resource data:2131429220
I/AMMetaDataParserService( 2881): getResourceName:com.android.settings:id/safetycare_settings
I/AMMetaDataParserService( 2881): getResourceTypeNameid
I/AMMetaDataParserService( 2881): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.android.settings.Settings$SafetyCareEmergencyModeActivity
I/AMMetaDataParserService( 2881): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2881): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2881): Resource data:2131429276
I/AMMetaDataParserService( 2881): getResourceName:com.android.settings:id/safetycare_help
I/AMMetaDataParserService( 2881): getResourceTypeNameid
I/AMMetaDataParserService( 2881): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.android.settings.Settings$SafetyCareDisasterActivity
I/AMMetaDataParserService( 2881): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2881): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2881): Resource data:2131429276
D/dalvikvm( 3048): Trying to load lib /data/app-lib/com.google.android.gms-2/libgmscore.so 0x427c5038
D/dalvikvm( 3048): Shared lib '/data/app-lib/com.google.android.gms-2/libgmscore.so' already loaded in same CL 0x427c5038
D/dalvikvm( 3048): Trying to load lib /data/app-lib/com.google.android.gms-2/libconscrypt_gmscore_jni.so 0x427c5038
D/dalvikvm( 3048): Shared lib '/data/app-lib/com.google.android.gms-2/libconscrypt_gmscore_jni.so' already loaded in same CL 0x427c5038
I/AMMetaDataParserService( 2881): getResourceName:com.android.settings:id/safetycare_help
I/AMMetaDataParserService( 2881): getResourceTypeNameid
I/AMMetaDataParserService( 2881): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.android.settings.safetycare.SafetyCareDisclaimerActivity
I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.android.settings.safetycare.SafetyCareDisasterDisclaimerActivity
I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.android.settings.safetycare.SafetyCareCoverageDialog
I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.android.settings.Settings$AirplaneModeSettingsActivity
I/AMMetaDataParserService( 2881): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2881): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2881): Resource data:2131429148
I/AMMetaDataParserService( 2881): getResourceName:com.android.settings:id/airplane_mode
I/AMMetaDataParserService( 2881): getResourceTypeNameid
I/AMMetaDataParserService( 2881): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.android.settings.Settings$ToddlerModeSettingsActivity
I/AMMetaDataParserService( 2881): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2881): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 2881): Resource data:2131429242
D/PackageManager(  745): !@killApplicatoin: 10181, uninstall pkg
I/ActivityManager(  745): Killing 2575:com.example.hello/u0a181 (adj 0): stop com.example.hello
,I/SurfaceFlinger(  249): id=16 Removed NainActivit (7/10)
,I/SurfaceFlinger(  249): id=16 Removed NainActivit (-2/10)
,D/KeyguardUpdateMonitor( 1069): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1069): handleKeyguardVisibilityChanged(1)
I/WindowState(  745): WIN DEATH: Window{433a2f80 u0 com.example.hello/com.example.hello.MainActivity}
,I/ProviderInstaller( 3048): Installed default security provider GmsCore_OpenSSL
W/PackageSettings(  745): Skipping PackageSetting{42bb2620 com.test.thalitest/10179} due to missing metadata
,D/PackageManager(  745): queryIntentReceivers - Execution time: 110 ms
,D/PackageManager(  745): getApplicationInfo - Execution time: 109 ms
I/AMMetaDataParserService( 2881): getResourceName:com.android.settings:id/toddler_mode
I/AMMetaDataParserService( 2881): getResourceTypeNameid
,I/AMMetaDataParserService( 2881): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.android.settings.KnoxSettings
I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.android.settings.favorite.FavoriteMenuList
I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.android.settings.favorite.MySettnigsRemoveActivity
I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.android.settings.Settings$FestivalEffectSettingsActivity
I/AMMetaDataParserService( 2881): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2881): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 2881): Resource data:2131429211
I/AMMetaDataParserService( 2881): getResourceName:com.android.settings:id/festival_effect_settings
I/AMMetaDataParserService( 2881): getResourceTypeNameid
I/AMMetaDataParserService( 2881): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.android.settings.wifi.WifiConnectDialogActivity
I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.android.settings.powersavingmode.PowerNotiDialog
I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.android.settings.powersavingmode.PowerNotiDataDialog
I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.android.settings.Settings$FingerprintSettingsActivity
I/AMMetaDataParserService( 2881): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2881): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 2881): Resource data:2130838248
I/AMMetaDataParserService( 2881): getResourceName:com.android.settings:drawable/ic_settings_dormant_mode
I/AMMetaDataParserService( 2881): getResourceTypeNamedrawable
I/AMMetaDataParserService( 2881): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.android.settings.fingerprint.FingerprintDisclaimer
I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.android.settings.Settings$FingerPrintManagerUIActivity
I/AMMetaDataParserService( 2881): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2881): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 2881): Resource data:2131429192
,D/LockPatternUtils( 1069): isPcwEnable = null
I/AMMetaDataParserService( 2881): getResourceName:com.android.settings:id/fingerprint_settings
I/AMMetaDataParserService( 2881): getResourceTypeNameid
I/AMMetaDataParserService( 2881): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.android.settings.fingerprint.FingerprintOnehandGrip
I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.android.settings.fingerprint.RegisterFingerprint
I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.android.settings.fingerprint.FingerprintPassword
,I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.android.settings.fingerprint.FingerprintConfirmPassword
I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.android.settings.fingerprint.FingerprintConfirm
I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.android.settings.fingerprint.FingerprintSupportingFeatures
I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.android.settings.fingerprint.FingerprintWebsignin
I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.android.settings.fingerprint.FingerPrintSettingsSetupWizard
I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.android.settings.fingerprint.FingerPrintSettingsUseFingerprint
,I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.android.settings.fingerprint.PaypalPayment
W/ActivityManager(  745): Force removing ActivityRecord{4341fe88 u0 com.example.hello/.MainActivity t3}: app died, no saved state
,D/PackageManager(  745): Sending to user 0: act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000000 Bundle[{android.intent.extra.REMOVED_FOR_ALL_USERS=true, android.intent.extra.UID=10181, android.intent.extra.DATA_REMOVED=true, android.intent.extra.user_handle=0}]
I/SQLiteSecureOpenHelper( 2043): getWritableDatabase(pwd)
,I/SQLiteSecureOpenHelper( 2043): getDatabaseLocked(b,b,pwd)...
D/CustomFrequencyManagerService(  745): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 745  pkgName : ACTIVITY_RESUME_BOOSTER@5
W/ActivityManager(  745): mDVFSHelper.acquire()
D/Launcher( 1252): onRestart, Launcher: 1114888352
D/Launcher( 1252): onStart, Launcher: 1114888352
,D/Launcher.HomeView( 1252): onStart
D/SurfaceWidgetClient$ISurfaceWidgetStub( 1449): [237392/5] Surface widget visibility changed visibility = true on instance = 1
,D/SurfaceWidget.Renderer( 1449): [237392/5] SurfaceWidget drawing first frame
,D/LockPatternUtils( 1069): isPcwEnable = null
,D/KeyguardUpdateMonitor( 1069): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1069): handleKeyguardVisibilityChanged(1)
,V/AlarmManager(  745): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1069): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1069): handleKeyguardVisibilityChanged(1)
,I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.android.contacts.activities.PeopleActivity
I/AMMetaDataParserService( 2881): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2881): getResourcePackageName:android.app.searchable
,I/AMMetaDataParserService( 2881): Resource data:2131034120
,I/AMMetaDataParserService( 2881): getResourceName:com.android.contacts:xml/searchable
,I/AMMetaDataParserService( 2881): getResourceTypeNamexml
,I/AMMetaDataParserService( 2881): getResourcePackageName:assistant
,I/AMMetaDataParserService( 2881): Resource data:2131034113
,I/AMMetaDataParserService( 2881): getResourceName:com.android.contacts:xml/assistant_main
,I/AMMetaDataParserService( 2881): getResourceTypeNamexml
,I/SurfaceFlinger(  249): id=17 createSurf (720x1280),1 flag=4, Mauncher
D/KeyguardUpdateMonitor( 1069): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1069): handleKeyguardVisibilityChanged(1)
,I/AMMetaDataParserService( 2881): Icon data: ResourceLogs2131624573android.intent.assistant.main.log2130837531
,D/KeyguardUpdateMonitor( 1069): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1069): handleKeyguardVisibilityChanged(1)
V/AlarmManager(  745): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
V/AlarmManager(  745): waitForAlarm result :4
V/AlarmManager(  745): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
D/PackageManager(  745): Sending to user 0: act=android.intent.action.PACKAGE_FULLY_REMOVED dat=package:com.example.hello flg=0x4000000 Bundle[{android.intent.extra.REMOVED_FOR_ALL_USERS=true, android.intent.extra.UID=10181, android.intent.extra.DATA_REMOVED=true, android.intent.extra.user_handle=0}]
,D/AdaptiveEventManager( 1069): action=android.intent.action.PACKAGE_REMOVED
,I/FPMS_FingerprintManagerService( 1088): onReceive: android.intent.action.PACKAGE_REMOVED
,W/GeofencerStateMachine( 1221): Ignoring removeGeofence because network location is disabled.
,D/dalvikvm( 1413): GC_EXPLICIT freed 4151K, 47% free 9989K/18756K, paused 3ms+14ms, total 62ms
,I/AMMetaDataParserService( 2881): Icon data: ResourceContacts2131623966android.intent.assistant.main.contact2130837529
,I/SurfaceFlinger(  249): id=18 createSurf (1x1),2 flag=404, CatteryCove
I/PackageManager(  745):   Action: "android.intent.action.SENDTO"
I/PackageManager(  745):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  745):   Scheme: "sms"
,I/InputReader(  745): Reconfiguring input devices.  changes=0x00000010
,I/PackageManager(  745): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
D/KeyguardUpdateMonitor( 1069): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1069): handleKeyguardVisibilityChanged(1)
,D/KeyguardUpdateMonitor( 1069): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1069): handleKeyguardVisibilityChanged(1)
,I/PackageManager(  745):   Action: "android.intent.action.SENDTO"
I/PackageManager(  745):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  745):   Scheme: "smsto"
I/PackageManager(  745): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,I/SELinux ( 3101): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 3101):  
D/KeyguardUpdateMonitor( 1069): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1069): handleKeyguardVisibilityChanged(1)
I/ActivityManager(  745): Killing 2208:com.sec.android.diagmonagent/1000 (adj 15): empty #43
,I/AMMetaDataParserService( 2881): Icon data: ResourceFavourites2131624366android.intent.assistant.main.favorite2130837528
,I/PackageManager(  745):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  745):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  745):   Scheme: "mms"
D/KeyguardUpdateMonitor( 1069): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1069): handleKeyguardVisibilityChanged(1)
,D/RCPManagerService(  745): PackageReceiver onReceive()
,I/PackageManager(  745): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
D/KeyguardUpdateMonitor( 1069): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1069): handleKeyguardVisibilityChanged(1)
,D/CustomFrequencyManagerService(  745): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 745  tag : ACTIVITY_RESUME_BOOSTER@5
W/ActivityManager(  745): mDVFSHelper.release()
,D/KeyguardUpdateMonitor( 1069): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1069): handleKeyguardVisibilityChanged(1)
I/SELinux ( 3101): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 3101):  
I/SELinux ( 3101):  
,I/SELinux ( 3101): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 3101): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 3101): >>>>> Normal User
,E/dalvikvm( 3101): >>>>> com.sec.knox.seandroid [ userId:0 | appId:1000 ]
,D/CustomFrequencyManagerService(  745): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 745  pkgName : ACTIVITY_RESUME_BOOSTER@9
E/SELinux ( 3101): [DEBUG] seapp_context_lookup: seinfoCategory = platform
I/HarmonyEASService(  745): onReceive : android.intent.action.PACKAGE_REMOVED for 0
D/KeyguardUpdateMonitor( 1069): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1069): handleKeyguardVisibilityChanged(1)
I/PackageManager(  745):   Action: "android.intent.action.SENDTO"
I/PackageManager(  745):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  745):   Scheme: "mmsto"
I/PackageManager(  745): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,D/TimaKeyStoreProvider( 3101): in addTimaSignatureService
,D/TimaKeyStoreProvider( 3101): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 3101): Added TimaKesytore provider
I/PackageManager(  745):   Action: "android.intent.action.SENDTO"
I/PackageManager(  745):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  745):   Scheme: "sms"
I/PackageManager(  745): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,I/AMMetaDataParserService( 2881): Icon data: ResourceKeypad2131624567android.intent.assistant.main.keypad2130837530
,I/PackageManager(  745):   Action: "android.intent.action.SENDTO"
I/PackageManager(  745):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  745):   Scheme: "smsto"
D/EnterpriseDeviceManagerService(  745): Package has changed for user 0
,D/EnterpriseDeviceManagerService(  745): Admin package name: com.google.android.gms
I/PackageManager(  745): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,I/PackageManager(  745):   Action: "android.intent.action.SENDTO"
I/PackageManager(  745):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  745):   Scheme: "mms"
,I/PackageManager(  745): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.android.dialer.DialtactsActivity
I/AMMetaDataParserService( 2881): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2881): getResourcePackageName:assistant
I/AMMetaDataParserService( 2881): Resource data:2131034113
,I/AMMetaDataParserService( 2881): getResourceName:com.android.contacts:xml/assistant_main
,I/AMMetaDataParserService( 2881): getResourceTypeNamexml
,I/AMMetaDataParserService( 2881): Icon data: ResourceLogs2131624573android.intent.assistant.main.log2130837531
,I/PackageManager(  745):   Action: "android.intent.action.SENDTO"
I/PackageManager(  745):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  745):   Scheme: "mmsto"
I/PackageManager(  745): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,I/AMMetaDataParserService( 2881): Icon data: ResourceContacts2131623966android.intent.assistant.main.contact2130837529
,W/ContextImpl( 3101): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1857 android.content.ContextWrapper.startService:506 android.content.ContextWrapper.startService:506 com.sec.knox.seandroid.service.MainReceiver.onReceive:47 android.app.ActivityThread.handleReceiver:2698 
,I/knox    ( 3101): MainReceiver.onReceive() : Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.sec.knox.seandroid/.receiver.MainReceiver (has extras) }
,I/AMMetaDataParserService( 2881): Icon data: ResourceFavourites2131624366android.intent.assistant.main.favorite2130837528
W/ContextImpl( 3101): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1857 android.content.ContextWrapper.startService:506 android.content.ContextWrapper.startService:506 com.sec.knox.seandroid.receiver.CommomReceiver.listeningToBootCompleted:59 com.sec.knox.seandroid.receiver.MainReceiver.onReceive:162 
,W/Resources(  745): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/dalvikvm(  745): GC_EXPLICIT freed 2898K, 17% free 23133K/27832K, paused 17ms+16ms, total 323ms
,I/knox    ( 3101): MainReceiver.onReceive() END - - - - - : Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.sec.knox.seandroid/.receiver.MainReceiver (has extras) }
,D/knox    ( 3101): KNOXAgentService : onCreate()
,D/knox    ( 3101): KNOXAgentService : set alarms for deniallog and usage data upload
,D/knox    ( 3101): KNOXAgentService. startJobThread() start
,D/knox    ( 3101): KNOXAgentService. JobThread()
,D/knox    ( 3101): KNOXAgentService. JobThread. notifyAll().
,D/knox    ( 3101): KNOXAgentService. startJobThread() wait
D/PackageManager(  745): delete sourFile : 
,I/SELinux ( 3115): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 3115):  
,D/knox    ( 3101): mKnoxAgentEngine.ELMEngine( context , reStart:true).
,D/knox    ( 3101): ELMEngine.ServiceHandler.handleMessage( DEFAULT ).
D/knox    ( 3101): KNOXAgentService : onDestroy().
,D/knox    ( 3101): ModuleBase.cancelAllAlarmManageModule()
,W/Resources(  745): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/PackageManager(  745): delete native library directory: 
,D/AndroidRuntime( 3031): Shutting down VM
,D/dalvikvm( 3031): GC_CONCURRENT freed 96K, 14% free 670K/772K, paused 1ms+1ms, total 3ms
D/PackageManager(  745): return delete result to caller: 1125426400
D/PackageManager(  745): returnCode: 1
,I/AMMetaDataParserService( 2881): Icon data: ResourceKeypad2131624567android.intent.assistant.main.keypad2130837530
,I/PackageManager(  745):   Action: "android.intent.action.SENDTO"
I/PackageManager(  745):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  745):   Scheme: "sms"
I/PackageManager(  745): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,D/BackupManagerService(  745): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 (has extras) }
,V/BackupManagerService(  745): removePackageParticipantsLocked: uid=10181 #1
,I/SELinux ( 3115): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 3115):  
I/SELinux ( 3115):  
,I/SELinux ( 3115): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 3115): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 3115): >>>>> Normal User
,E/dalvikvm( 3115): >>>>> com.sec.knox.knoxsetupwizardclient [ userId:0 | appId:1000 ]
,E/SELinux ( 3115): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,I/PackageManager(  745):   Action: "android.intent.action.SENDTO"
I/PackageManager(  745):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  745):   Scheme: "smsto"
,D/TimaKeyStoreProvider( 3115): in addTimaSignatureService
I/AMMetaDataParserService( 2881): getResourcePackageName:com.samsung.android.multiuser.install_only_owner
I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.android.contacts.activities.ContactSelectionActivity
,I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.samsung.contacts.interactions.InteractionTabActivity
I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.samsung.contacts.interactions.InteractionGroupSelectionActivity
I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.android.contacts.DialtactsActivity
I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.android.contacts.RecentCallsListActivity
,I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.android.contacts.activities.CallLogActivity
I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.android.contacts.ContactsListActivity
I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.android.contacts.activities.ContactsFrontDoor
I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.android.contacts.DialtactsContactsEntryActivity
,D/TimaKeyStoreProvider( 3115): Cannot add TimaSignature Service, License check Failed
I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.android.contacts.activities.JoinContactActivity
I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.samsung.dialer.dialpad.VVM
I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.android.contacts.preference.ContactsPreferenceActivity
,I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.android.contacts.common.list.AccountFilterActivity
I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.android.contacts.common.list.CustomContactListFilterActivity
I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.android.contacts.activities.ShowOrCreateActivity
I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.android.contacts.activities.GroupDetailActivity
D/ActivityThread( 3115): Added TimaKesytore provider
I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.android.contacts.activities.GroupEditorActivity
,I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.android.contacts.quickcontact.QuickContactActivity
I/AMMetaDataParserService( 2881): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2881): getResourcePackageName:com.sec.android.multiwindow.activity.STYLE
I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.android.contacts.ContactShortcut
I/AMMetaDataParserService( 2881): Resource data:Loop for running activityalias.DialShortcut
I/AMMetaDataParserService( 2881): Resource data:Loop for running activityalias.MessageShortcut
I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.android.dialer.CallDetailActivity
I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.samsung.dialer.calllog.CallDetailAllCallsActivity
I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.samsung.dialer.calllog.CallDetailDeleteActivity
I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.android.contacts.activities.ContactDetailActivity
I/AMMetaDataParserService( 2881): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2881): getResourcePackageName:assistant
,I/PackageManager(  745): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
I/AMMetaDataParserService( 2881): Resource data:2131034112
,I/AMMetaDataParserService( 2881): getResourceName:com.android.contacts:xml/assistant_detail
,I/AMMetaDataParserService( 2881): getResourceTypeNamexml
,I/GAV2    ( 2149): Thread[GAThread,5,main]: No campaign data found.
I/PackageManager(  745):   Action: "android.intent.action.SENDTO"
I/PackageManager(  745):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  745):   Scheme: "mms"
,I/AMMetaDataParserService( 2881): Icon data: ResourceAdd to favourites2131623990android.intent.assistant.detail.favorite2130837528
I/PackageManager(  745): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,I/GAv4-SVC( 1800): Google Analytics 8.4.89 is starting up.
,I/PackageManager(  745):   Action: "android.intent.action.SENDTO"
I/PackageManager(  745):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  745):   Scheme: "mmsto"
,I/AMMetaDataParserService( 2881): Icon data: ResourceRemove from favourites2131623991android.intent.assistant.detail.favorite2130837528
I/PackageManager(  745): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,W/Resources(  745): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
V/AlarmManager(  745): waitForAlarm result :8
,V/AlarmManager(  745): ClockReceiver onReceive() ACTION_TIME_TICK
D/KeyguardUpdateMonitor( 1069): received broadcast android.intent.action.TIME_TICK
D/KeyguardUpdateMonitor( 1069): handleTimeUpdate
,E/KnoxSetupWizardClient( 3115): isShipMode : 1
,I/KnoxSetupWizardClient( 3115): onReceive : android.intent.action.BOOT_COMPLETED
D/STATUSBAR-IconMerger( 1069): checkOverflow(384), More:false, Req:false Child:2
,I/AMMetaDataParserService( 2881): Icon data: ResourceEdit2131623992android.intent.assistant.detail.edit2130837527
,W/System.err( 3115): java.lang.IllegalArgumentException: Unknown package: com.sec.knox.setupwizardstub
W/System.err( 3115): 	at android.os.Parcel.readException(Parcel.java:1469)
,W/System.err( 3115): 	at android.os.Parcel.readException(Parcel.java:1419)
W/Resources(  745): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/System.err( 3115): 	at android.content.pm.IPackageManager$Stub$Proxy.setApplicationEnabledSetting(IPackageManager.java:3458)
W/System.err( 3115): 	at android.app.ApplicationPackageManager.setApplicationEnabledSetting(ApplicationPackageManager.java:1519)
W/System.err( 3115): 	at com.sec.knox.knoxsetupwizardclient.detector.StubPackageThread.processInternal(StubPackageThread.java:83)
,W/System.err( 3115): 	at com.sec.knox.knoxsetupwizardclient.detector.StubPackageThread.run(StubPackageThread.java:49)
,W/System.err( 3115): java.lang.IllegalArgumentException: Unknown package: com.sec.knox.containeragent
W/System.err( 3115): 	at android.os.Parcel.readException(Parcel.java:1469)
W/System.err( 3115): 	at android.os.Parcel.readException(Parcel.java:1419)
,W/System.err( 3115): 	at android.content.pm.IPackageManager$Stub$Proxy.setApplicationEnabledSetting(IPackageManager.java:3458)
W/System.err( 3115): 	at android.app.ApplicationPackageManager.setApplicationEnabledSetting(ApplicationPackageManager.java:1519)
,W/System.err( 3115): 	at com.sec.knox.knoxsetupwizardclient.detector.StubPackageThread.disablePackage(StubPackageThread.java:132)
,D/KeyguardViewMediator( 1069): handleKeyguardDoneDrawing
,W/System.err( 3115): 	at com.sec.knox.knoxsetupwizardclient.detector.StubPackageThread.processInternal(StubPackageThread.java:103)
,W/System.err( 3115): 	at com.sec.knox.knoxsetupwizardclient.detector.StubPackageThread.run(StubPackageThread.java:49)
,D/daemonapp( 1467): [MSC_Daemon]>>> WU:1159 [0:0] cDayONight() ::: sunrise is null 
D/daemonapp( 1467): [MSC_Daemon]>>> WU:1175 [0:0] cDayONight() ::: sunset is null 
,D/daemonapp( 1467): [MSC_Daemon]>>> WCS:143 [0:0] action:androidintentactionTIME_TICK
I/ActivityManager(  745): Waited long enough for: ServiceRecord{43256a80 u0 com.samsung.android.providers.context/.ContextService}
,I/AMMetaDataParserService( 2881): Icon data: ResourceDelete2131623993android.intent.assistant.detail.delete2130837526
,D/ShortcutReceiver( 3115):  ShortcutReceiver onReceive() intent: android.intent.action.BOOT_COMPLETED
,I/yash    ( 3115): setDisableWidget>size:0
I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.samsung.contacts.detail.SelectContactInfoActivity
I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.android.contacts.activities.ConfirmAddDetailActivity
I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.android.contacts.activities.ContactEditorAccountsChangedActivity
I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.android.contacts.activities.ContactEditorActivity
I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.samsung.contacts.activities.RingtoneRecommendationHelperActivity
I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.samsung.contacts.editor.AddAnotherFieldDialogActivity
I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.android.contacts.common.test.FragmentTestActivity
I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.android.contacts.activities.AttachPhotoActivity
I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.android.contacts.activities.PhotoSelectionActivity
I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.android.contacts.common.vcard.ImportVCardActivity
I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.samsung.contacts.vcard.ImportVCardPreviewActivity
I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.android.contacts.common.vcard.NfcImportVCardActivity
I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.android.contacts.common.vcard.CancelActivity
I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.android.contacts.common.vcard.SelectAccountActivity
I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.android.contacts.common.vcard.ExportVCardActivity
I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.samsung.contacts.vcard.ImportFinishActivity
I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.samsung.contacts.activities.SIMContactSelectionActivity
I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.samsung.contacts.activities.ServiceNumbers
I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.samsung.contacts.activities.ServiceNumbersTabActivity
I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.android.contacts.widget.PinnedHeaderListDemoActivity
I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.android.contacts.NonPhoneActivity
I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.samsung.contacts.favorite.FavoriteSelectionActivity
I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.samsung.contacts.detail.SetDefaultActivity
I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.samsung.contacts.group.GroupChangeOrderActivity
I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.samsung.contacts.editor.EditGroupSelectionActivity
I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.samsung.contacts.group.GroupMultiSelectionActivity
I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.samsung.contacts.emergency.InteractionEmergencyMessageActivity
I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.samsung.contacts.emergency.EmergencyMessageContactCreateActivity
I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.samsung.contacts.emergency.EmergencyContactListDialogActivity
I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.samsung.contacts.group.SubGroupDetailActivity
I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.samsung.contacts.activities.GroupListActivity
I/AMMetaDataParserService( 2881): Res,ource data:Loop for running activitycom.samsung.aab.activity.SubscriberInfoCheckerActivity
I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.samsung.aab.activity.ATTAB
I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.samsung.aab.activity.AABReadyToUseActivity
I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.samsung.aab.activity.SimCopy
I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.samsung.aab.activity.AccessingSimCardInfo
I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.samsung.aab.activity.WelcomeDecline
I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.samsung.aab.activity.ContactsReadyToUseActivity
I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.samsung.aab.activity.PhoneUpdateLater
I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.samsung.aab.activity.PhoneUpdatePrompt
I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.samsung.aab.activity.ActivationStatusActivity
I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.samsung.aab.activity.StartSyncInitialActivity
I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.samsung.aab.activity.FeaturesActivity
I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.samsung.aab.activity.RegistrationFailure
I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.samsung.aab.activity.SyncResponseActivity
I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.samsung.aab.activity.ActivateLater
I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.samsung.aab.activity.ZeroSimCardInfo
I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.samsung.aab.activity.NewURLActivity
I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.samsung.dialer.calllog.CallDurationActivity
I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.samsung.dialer.calllog.CallDurationTabActivity
I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.samsung.contacts.detail.LinkedContactActivity
I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.samsung.dialer.impl.DialerTutorialActivity
I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.samsung.contacts.impl.HelpPeopleActivity
I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.samsung.contacts.impl.HelpEasyPeopleActivity
I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.samsung.contacts.impl.HelpInteractionTabActivity
I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.samsung.contacts.impl.HelpEasyInteractionTabActivity
I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.samsung.contacts.impl.HelpSpeedDialActivity
I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.samsung.contacts.impl.HelpContactEditorActivity
I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.samsung.contacts.impl.HelpContactSelectionActivity
I/AMMetaDataParserService( 2881): Resource data:Loop for running activitycom.samsung.contacts.activities.EasyPeopleActivity
I/AMMetaDataParserService( 2881): Resource data:Inside bundle  check
I/AMMetaDataParserService( 2881): getResourcePackageName:assistant
,I/AMMetaDataParserService( 2881): Resource data:2131034113
I/AMMetaDataParserService( 2881): getResourceName:com.android.contacts:xml/assistant_main
,I/AMMetaDataParserService( 2881): getResourceTypeNamexml
,W/Resources(  745): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,I/AMMetaDataParserService( 2881): Icon data: ResourceLogs2131624573android.intent.assistant.main.log2130837531
,I/SELinux ( 3133): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 3133):  
I/ActivityManager(  745): Killing 1649:com.fmm.dm/1000 (adj 15): empty #43
,D/dalvikvm(  250): GC_EXPLICIT freed 47K, 50% free 9508K/18756K, paused 2ms+3ms, total 30ms
,W/Resources(  745): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,I/AMMetaDataParserService( 2881): Icon data: ResourceContacts2131623966android.intent.assistant.main.contact2130837529
,I/SELinux ( 3133): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 3133):  
I/SELinux ( 3133):  
,I/SELinux ( 3133): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 3133): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/dalvikvm(  250): GC_EXPLICIT freed <1K, 50% free 9508K/18756K, paused 2ms+3ms, total 21ms
E/dalvikvm( 3133): >>>>> Normal User
,E/dalvikvm( 3133): >>>>> com.LocalFota [ userId:0 | appId:10110 ]
E/SELinux ( 3133): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/SQLiteDatabase( 2881): Failed to open database '/data/data/com.samsung.android.app.assistantmenu/databases/AssistantMenu'.
E/SQLiteDatabase( 2881): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 2881): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 2881): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteDatabase( 2881): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteDatabase( 2881): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 2881): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 2881): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 2881): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteDatabase( 2881): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteDatabase( 2881): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteDatabase( 2881): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteDatabase( 2881): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 2881): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 2881): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 2881): 	at com.samsung.android.app.assistantmenu.serviceframework.DatabaseHandler.addAMData(DatabaseHandler.java:63)
E/SQLiteDatabase( 2881): 	at com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.constructDBdata(AMMetaDataParserService.java:190)
E/SQLiteDatabase( 2881): 	at com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent(AMMetaDataParserService.java:86)
E/SQLiteDatabase( 2881): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 2881): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 2881): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteDatabase( 2881): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,W/System.err( 2881): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
W/System.err( 2881): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
W/System.err( 2881): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
W/System.err( 2881): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
,W/System.err( 2881): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
W/System.err( 2881): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
W/System.err( 2881): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
,W/System.err( 2881): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
W/System.err( 2881): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
,W/System.err( 2881): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
W/System.err( 2881): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
,W/System.err( 2881): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
W/System.err( 2881): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
,W/System.err( 2881): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
W/System.err( 2881): 	at com.samsung.android.app.assistantmenu.serviceframework.DatabaseHandler.addAMData(DatabaseHandler.java:63)
W/System.err( 2881): 	at com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.constructDBdata(AMMetaDataParserService.java:190)
,W/System.err( 2881): 	at com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent(AMMetaDataParserService.java:86)
W/System.err( 2881): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
,W/System.err( 2881): 	at android.os.Handler.dispatchMessage(Handler.java:102)
,W/System.err( 2881): 	at android.os.Looper.loop(Looper.java:146)
,W/System.err( 2881): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ActivityManager(  745): Killing 2225:com.sec.android.fotaclient/u0a10 (adj 15): empty #43
,D/dalvikvm(  250): GC_EXPLICIT freed <1K, 50% free 9508K/18756K, paused 2ms+3ms, total 21ms
,D/TimaKeyStoreProvider( 3133): in addTimaSignatureService
,W/Resources(  745): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/TimaKeyStoreProvider( 3133): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 3133): Added TimaKesytore provider
,D/dalvikvm( 2881): GC_CONCURRENT freed 2361K, 35% free 12321K/18756K, paused 9ms+3ms, total 61ms
,W/Resources(  745): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,I/DBG_WSS_LF( 3133): [Not Defined][Line:75][onCreate] LocalFOTA Application Start !
,W/ActivityManager(  745): Permission Denial: getCurrentUser() from pid=3133, uid=10110 requires android.permission.INTERACT_ACROSS_USERS
W/Resources(  745): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
I/DBG_WSS_LF( 3133): [20.0040.140326][Line:27][<init>] First call
,D/InputReader(  745): Processing first event
,W/ApplicationsProvider( 1413): Could not fetch usage stats
W/ApplicationsProvider( 1413): java.lang.SecurityException: Neither user 10020 nor current process has android.permission.PACKAGE_USAGE_STATS.
W/ApplicationsProvider( 1413): 	at android.os.Parcel.readException(Parcel.java:1465)
W/ApplicationsProvider( 1413): 	at android.os.Parcel.readException(Parcel.java:1419)
W/ApplicationsProvider( 1413): 	at com.android.internal.app.IUsageStats$Stub$Proxy.getAllPkgUsageStats(IUsageStats.java:317)
W/ApplicationsProvider( 1413): 	at android.app.ActivityManager.getAllPackageUsageStats(ActivityManager.java:2543)
W/ApplicationsProvider( 1413): 	at com.android.providers.applications.ApplicationsProvider.fetchUsageStats(ApplicationsProvider.java:681)
W/ApplicationsProvider( 1413): 	at com.android.providers.applications.ApplicationsProvider.updateApplicationsList(ApplicationsProvider.java:519)
W/ApplicationsProvider( 1413): 	at com.android.providers.applications.ApplicationsProvider.access$300(ApplicationsProvider.java:70)
W/ApplicationsProvider( 1413): 	at com.android.providers.applications.ApplicationsProvider$UpdateHandler.handleMessage(ApplicationsProvider.java:209)
W/ApplicationsProvider( 1413): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/ApplicationsProvider( 1413): 	at android.os.Looper.loop(Looper.java:146)
W/ApplicationsProvider( 1413): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,D/CustomFrequencyManagerService(  745): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 745  tag : ACTIVITY_RESUME_BOOSTER@9

```
