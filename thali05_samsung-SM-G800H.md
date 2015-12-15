#### Test 5038801913f4183_thali05_samsung-SM-G800H Logs


```
--------- beginning of /dev/log/main
I/OMXCodec(  253): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec(  253): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec(  253): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/OMXCodec(  253): [OMX.google.vorbis.decoder] End Of Stream
I/AudioPlayer(  253):  Audioplayer kKeyAudioPCMFormat:1, 1, 0
I/AudioPlayer(  253):  Audioplayer kKeyAudioPCMFormat read fail(1, 1)
V/AudioCache(  253): open(44100, 1, 0x0, 1, 4)
V/AwesomePlayer(  253): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache(  253): notify(0xb8aacc40, 6, 0, 0)
V/AudioCache(  253): ignored
V/AwesomePlayer(  253): addBatteryData
V/MediaPlayerService(  253): wait for playback complete
V/AwesomePlayer(  253): postAudioEOS delayUs (0)
V/AwesomePlayer(  253): onCheckAudioStatus
V/AwesomePlayer(  253): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  253): onStreamDone
V/AwesomePlayer(  253): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  253): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  253): notify(0xb8aacc40, 2, 0, 0)
V/AudioCache(  253): playback complete - thread will wake up later
V/AwesomePlayer(  253): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  253): notify(0xb8aacc40, 7, 0, 0)
V/AudioCache(  253): ignored
V/AwesomePlayer(  253): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer(  253): addBatteryData
V/AudioCache(  253): wait - success
V/StagefrightPlayer(  253): reset
V/AwesomePlayer(  253): reset_l()
V/AwesomePlayer(  253): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  253): notify(0xb8aacc40, 8, 0, 0)
V/AudioCache(  253): ignored
V/AwesomePlayer(  253): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  253): mAudioTrackVector clear
I/OMXCodec(  253): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec(  253): [OMX.google.vorbis.decoder] stop() sendCommand(0x30, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec(  253): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
I/OMXCodec(  253): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/OMX     (  253): instance freeNode
I/AudioPlayer(  253): reset out
V/AwesomePlayer(  253): reset_l() mAudioPlayer successfully deleted
I/SecMediaClock(  253): SecMediaClock destructor
V/AwesomePlayer(  253): mSecMediaClock clear
V/StagefrightPlayer(  253): ~StagefrightPlayer
V/StagefrightPlayer(  253): reset
V/AwesomePlayer(  253): reset_l()
V/AwesomePlayer(  253): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  253): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  253): mAudioTrackVector clear
V/AwesomePlayer(  253): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  253): mSecMediaClock clear
V/AwesomePlayer(  253): destructor
V/AwesomePlayer(  253): reset_l()
V/AwesomePlayer(  253): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  253): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  253): mAudioTrackVector clear
V/AwesomePlayer(  253): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  253): mSecMediaClock clear
V/MediaPlayer( 2673): decode(70, 30337076, 9400)
V/MediaPlayerService(  253): decode(35, 30337076, 9400)
V/MediaPlayerService(  253): player type = 3
V/AwesomePlayer(  253): setDefault
V/AwesomePlayer(  253): constructor
V/AwesomePlayer(  253): setDefault
V/AwesomePlayer(  253): reset_l()
V/AwesomePlayer(  253): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  253): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  253): mAudioTrackVector clear
V/AwesomePlayer(  253): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  253): mSecMediaClock clear
V/StagefrightPlayer(  253): StagefrightPlayer
V/AwesomePlayer(  253): setListener
V/StagefrightPlayer(  253): initCheck
V/AwesomePlayer(  253): setAudioSink
V/StagefrightPlayer(  253): setDataSource(35, 30337076, 9400)
V/AwesomePlayer(  253): reset_l()
V/AwesomePlayer(  253): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  253): notify(0xb8ab5eb0, 8, 0, 0)
V/AudioCache(  253): ignored
V/AwesomePlayer(  253): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  253): mAudioTrackVector clear
V/AwesomePlayer(  253): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  253): mSecMediaClock clear
V/AwesomePlayer(  253): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer(  253): mBitrate = -1 bits/sec
V/AwesomePlayer(  253): current audio track index (0) is added to vector
V/AwesomePlayer(  253): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer(  253): AwesomePlayer::setDataSource_l():: This is not a DRM content
V/MediaPlayerService(  253): prepare
V/AwesomePlayer(  253): prepareAsync
V/MediaPlayerService(  253): wait for prepare
I/SELinux ( 2734): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 2734):  
V/AwesomePlayer(  253): onPrepareAsyncEvent
I/SecMediaClock(  253): SecMediaClock constructor
I/SecMediaClock(  253): reset
V/AwesomePlayer(  253): initAudioDecoder
V/AwesomePlayer(  253): checkOffloadExceptions is true
I/OMXCodec(  253): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
I/OMX     (  253): mDispatchers.add
I/OMXCodec(  253): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec(  253): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec(  253): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec(  253): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/OMXCodec(  253): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer(  253): finishAsyncPrepare_l
V/AwesomePlayer(  253): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache(  253): notify(0xb8ab5eb0, 200, 973, 0)
V/AudioCache(  253): ignored
V/AwesomePlayer(  253): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  253): notify(0xb8ab5eb0, 5, 0, 0)
V/AudioCache(  253): ignored
V/AwesomePlayer(  253): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  253): notify(0xb8ab5eb0, 1, 0, 0)
V/AudioCache(  253): prepared
V/AudioCache(  253): wait - success
V/MediaPlayerService(  253): start
V/StagefrightPlayer(  253): start
V/AwesomePlayer(  253): play
V/AwesomePlayer(  253): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer(  253): startAudioPlayer_l, sendErrorNotification (0)
I/OMXCodec(  253): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec(  253): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec(  253): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/AudioPlayer(  253):  Audioplayer kKeyAudioPCMFormat:1, 1, 0
I/AudioPlayer(  253):  Audioplayer kKeyAudioPCMFormat read fail(1, 1)
V/AudioCache(  253): open(44100, 1, 0x0, 1, 4)
V/AwesomePlayer(  253): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache(  253): notify(0xb8ab5eb0, 6, 0, 0)
V/AudioCache(  253): ignored
V/AwesomePlayer(  253): addBatteryData
I/AudioPlayer(  253): First fillBuffer call!!
I/ServiceManager(  291): Waiting for service AtCmdFwd...
V/MediaPlayerService(  253): wait for playback complete
I/OMXCodec(  253): [OMX.google.vorbis.decoder] End Of Stream
V/AwesomePlayer(  253): postAudioEOS delayUs (0)
V/AwesomePlayer(  253): onCheckAudioStatus
V/AwesomePlayer(  253): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  253): onStreamDone
V/AwesomePlayer(  253): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  253): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  253): notify(0xb8ab5eb0, 2, 0, 0)
V/AudioCache(  253): playback complete - thread will wake up later
V/AwesomePlayer(  253): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  253): notify(0xb8ab5eb0, 7, 0, 0)
V/AudioCache(  253): ignored
V/AwesomePlayer(  253): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer(  253): addBatteryData
V/AudioCache(  253): wait - success
V/StagefrightPlayer(  253): reset
V/AwesomePlayer(  253): reset_l()
V/AwesomePlayer(  253): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  253): notify(0xb8ab5eb0, 8, 0, 0)
V/AudioCache(  253): ignored
V/AwesomePlayer(  253): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  253): mAudioTrackVector clear
I/OMXCodec(  253): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec(  253): [OMX.google.vorbis.decoder] stop() sendCommand(0x31, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec(  253): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
I/OMXCodec(  253): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/OMX     (  253): instance freeNode
I/AudioPlayer(  253): reset out
V/AwesomePlayer(  253): reset_l() mAudioPlayer successfully deleted
I/SecMediaClock(  253): SecMediaClock destructor
V/AwesomePlayer(  253): mSecMediaClock clear
V/StagefrightPlayer(  253): ~StagefrightPlayer
V/StagefrightPlayer(  253): reset
V/AwesomePlayer(  253): reset_l()
V/AwesomePlayer(  253): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  253): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  253): mAudioTrackVector clear
V/AwesomePlayer(  253): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  253): mSecMediaClock clear
V/AwesomePlayer(  253): destructor
V/AwesomePlayer(  253): reset_l()
V/AwesomePlayer(  253): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  253): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  253): mAudioTrackVector clear
V/AwesomePlayer(  253): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  253): mSecMediaClock clear
V/MediaPlayer( 2673): decode(71, 33925464, 44276)
V/MediaPlayerService(  253): decode(35, 33925464, 44276)
V/MediaPlayerService(  253): player type = 3
V/AwesomePlayer(  253): setDefault
V/AwesomePlayer(  253): constructor
V/AwesomePlayer(  253): setDefault
V/AwesomePlayer(  253): reset_l()
V/AwesomePlayer(  253): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  253): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  253): mAudioTrackVector clear
V/AwesomePlayer(  253): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  253): mSecMediaClock clear
V/StagefrightPlayer(  253): StagefrightPlayer
V/AwesomePlayer(  253): setListener
V/StagefrightPlayer(  253): initCheck
V/AwesomePlayer(  253): setAudioSink
V/StagefrightPlayer(  253): setDataSource(35, 33925464, 44276)
V/AwesomePlayer(  253): reset_l()
V/AwesomePlayer(  253): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  253): notify(0xb8ab5f38, 8, 0, 0)
V/AudioCache(  253): ignored
V/AwesomePlayer(  253): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  253): mAudioTrackVector clear
V/AwesomePlayer(  253): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  253): mSecMediaClock clear
V/AwesomePlayer(  253): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer(  253): mBitrate = -1 bits/sec
V/AwesomePlayer(  253): current audio track index (0) is added to vector
V/AwesomePlayer(  253): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer(  253): AwesomePlayer::setDataSource_l():: This is not a DRM content
V/MediaPlayerService(  253): prepare
V/AwesomePlayer(  253): prepareAsync
V/MediaPlayerService(  253): wait for prepare
V/AwesomePlayer(  253): onPrepareAsyncEvent
I/SecMediaClock(  253): SecMediaClock constructor
I/SecMediaClock(  253): reset
V/AwesomePlayer(  253): initAudioDecoder
V/AwesomePlayer(  253): checkOffloadExceptions is true
I/OMXCodec(  253): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
I/OMX     (  253): mDispatchers.add
I/OMXCodec(  253): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec(  253): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec(  253): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec(  253): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/OMXCodec(  253): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer(  253): finishAsyncPrepare_l
V/AwesomePlayer(  253): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache(  253): notify(0xb8ab5f38, 200, 973, 0)
V/AudioCache(  253): ignored
V/AwesomePlayer(  253): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  253): notify(0xb8ab5f38, 5, 0, 0)
V/AudioCache(  253): ignored
V/AwesomePlayer(  253): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  253): notify(0xb8ab5f38, 1, 0, 0)
V/AudioCache(  253): prepared
V/AudioCache(  253): wait - success
V/MediaPlayerService(  253): start
V/StagefrightPlayer(  253): start
V/AwesomePlayer(  253): play
V/AwesomePlayer(  253): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer(  253): startAudioPlayer_l, sendErrorNotification (0)
I/SELinux ( 2734): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 2734):  
I/SELinux ( 2734):  
I/SELinux ( 2734): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 2734): [DEBUG] seapp_context_lookup: seinfoCategory = samsung
E/dalvikvm( 2734): >>>>> Normal User
E/dalvikvm( 2734): >>>>> com.sec.android.app.sns3 [ userId:0 | appId:10036 ]
I/OMXCodec(  253): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec(  253): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec(  253): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
E/SELinux ( 2734): [DEBUG] seapp_context_lookup: seinfoCategory = samsung
I/AudioPlayer(  253):  Audioplayer kKeyAudioPCMFormat:1, 2, 0
I/AudioPlayer(  253):  Audioplayer kKeyAudioPCMFormat read fail(2, 1)
V/AudioCache(  253): open(44100, 2, 0x0, 1, 4)
V/AwesomePlayer(  253): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache(  253): notify(0xb8ab5f38, 6, 0, 0)
V/AudioCache(  253): ignored
V/AwesomePlayer(  253): addBatteryData
I/AudioPlayer(  253): First fillBuffer call!!
V/MediaPlayerService(  253): wait for playback complete
D/btif_config_util( 1948): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
I/OMXCodec(  253): [OMX.google.vorbis.decoder] End Of Stream
D/TimaKeyStoreProvider( 2734): in addTimaSignatureService
V/AwesomePlayer(  253): postAudioEOS delayUs (0)
V/AwesomePlayer(  253): onCheckAudioStatus
V/AwesomePlayer(  253): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  253): onStreamDone
V/AwesomePlayer(  253): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  253): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  253): notify(0xb8ab5f38, 2, 0, 0)
V/AudioCache(  253): playback complete - thread will wake up later
V/AwesomePlayer(  253): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  253): notify(0xb8ab5f38, 7, 0, 0)
V/AudioCache(  253): ignored
V/AwesomePlayer(  253): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer(  253): addBatteryData
V/AudioCache(  253): wait - success
V/StagefrightPlayer(  253): reset
V/AwesomePlayer(  253): reset_l()
V/AwesomePlayer(  253): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  253): notify(0xb8ab5f38, 8, 0, 0)
D/TimaKeyStoreProvider( 2734): Cannot add TimaSignature Service, License check Failed
V/AudioCache(  253): ignored
V/AwesomePlayer(  253): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  253): mAudioTrackVector clear
I/OMXCodec(  253): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec(  253): [OMX.google.vorbis.decoder] stop() sendCommand(0x32, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec(  253): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
I/OMXCodec(  253): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/OMX     (  253): instance freeNode
I/AudioPlayer(  253): reset out
V/AwesomePlayer(  253): reset_l() mAudioPlayer successfully deleted
I/SecMediaClock(  253): SecMediaClock destructor
V/AwesomePlayer(  253): mSecMediaClock clear
V/StagefrightPlayer(  253): ~StagefrightPlayer
V/StagefrightPlayer(  253): reset
V/AwesomePlayer(  253): reset_l()
V/AwesomePlayer(  253): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  253): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  253): mAudioTrackVector clear
V/AwesomePlayer(  253): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  253): mSecMediaClock clear
V/AwesomePlayer(  253): destructor
V/AwesomePlayer(  253): reset_l()
V/AwesomePlayer(  253): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  253): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  253): mAudioTrackVector clear
V/AwesomePlayer(  253): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  253): mSecMediaClock clear
D/ActivityThread( 2734): Added TimaKesytore provider
V/MediaPlayer( 2673): decode(72, 33885672, 29256)
V/MediaPlayerService(  253): decode(35, 33885672, 29256)
V/MediaPlayerService(  253): player type = 3
V/AwesomePlayer(  253): setDefault
V/AwesomePlayer(  253): constructor
V/AwesomePlayer(  253): setDefault
V/AwesomePlayer(  253): reset_l()
V/AwesomePlayer(  253): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  253): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  253): mAudioTrackVector clear
V/AwesomePlayer(  253): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  253): mSecMediaClock clear
V/StagefrightPlayer(  253): StagefrightPlayer
V/AwesomePlayer(  253): setListener
V/StagefrightPlayer(  253): initCheck
V/AwesomePlayer(  253): setAudioSink
V/StagefrightPlayer(  253): setDataSource(35, 33885672, 29256)
V/AwesomePlayer(  253): reset_l()
V/AwesomePlayer(  253): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  253): notify(0xb8abd878, 8, 0, 0)
V/AudioCache(  253): ignored
V/AwesomePlayer(  253): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  253): mAudioTrackVector clear
V/AwesomePlayer(  253): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  253): mSecMediaClock clear
V/AwesomePlayer(  253): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer(  253): mBitrate = -1 bits/sec
V/AwesomePlayer(  253): current audio track index (0) is added to vector
V/AwesomePlayer(  253): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer(  253): AwesomePlayer::setDataSource_l():: This is not a DRM content
V/MediaPlayerService(  253): prepare
V/AwesomePlayer(  253): prepareAsync
V/MediaPlayerService(  253): wait for prepare
V/AwesomePlayer(  253): onPrepareAsyncEvent
I/SecMediaClock(  253): SecMediaClock constructor
I/SecMediaClock(  253): reset
V/AwesomePlayer(  253): initAudioDecoder
V/AwesomePlayer(  253): checkOffloadExceptions is true
I/OMXCodec(  253): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
I/OMX     (  253): mDispatchers.add
I/OMXCodec(  253): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec(  253): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec(  253): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec(  253): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/OMXCodec(  253): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer(  253): finishAsyncPrepare_l
V/AwesomePlayer(  253): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache(  253): notify(0xb8abd878, 200, 973, 0)
V/AudioCache(  253): ignored
V/AwesomePlayer(  253): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  253): notify(0xb8abd878, 5, 0, 0)
V/AudioCache(  253): ignored
V/AwesomePlayer(  253): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  253): notify(0xb8abd878, 1, 0, 0)
V/AudioCache(  253): prepared
V/AudioCache(  253): wait - success
V/MediaPlayerService(  253): start
V/StagefrightPlayer(  253): start
V/AwesomePlayer(  253): play
V/AwesomePlayer(  253): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer(  253): startAudioPlayer_l, sendErrorNotification (0)
I/OMXCodec(  253): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec(  253): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec(  253): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/AudioPlayer(  253):  Audioplayer kKeyAudioPCMFormat:1, 2, 0
I/AudioPlayer(  253):  Audioplayer kKeyAudioPCMFormat read fail(2, 1)
V/AudioCache(  253): open(44100, 2, 0x0, 1, 4)
V/AwesomePlayer(  253): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache(  253): notify(0xb8abd878, 6, 0, 0)
V/AudioCache(  253): ignored
V/AwesomePlayer(  253): addBatteryData
V/MediaPlayerService(  253): wait for playback complete
I/AudioPlayer(  253): First fillBuffer call!!
I/OMXCodec(  253): [OMX.google.vorbis.decoder] End Of Stream
V/AwesomePlayer(  253): postAudioEOS delayUs (0)
V/AwesomePlayer(  253): onCheckAudioStatus
V/AwesomePlayer(  253): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  253): onStreamDone
V/AwesomePlayer(  253): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  253): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  253): notify(0xb8abd878, 2, 0, 0)
V/AudioCache(  253): playback complete - thread will wake up later
V/AwesomePlayer(  253): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  253): notify(0xb8abd878, 7, 0, 0)
V/AudioCache(  253): ignored
V/AwesomePlayer(  253): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer(  253): addBatteryData
V/AudioCache(  253): wait - success
V/StagefrightPlayer(  253): reset
V/AwesomePlayer(  253): reset_l()
V/AwesomePlayer(  253): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  253): notify(0xb8abd878, 8, 0, 0)
V/AudioCache(  253): ignored
V/AwesomePlayer(  253): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  253): mAudioTrackVector clear
I/OMXCodec(  253): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec(  253): [OMX.google.vorbis.decoder] stop() sendCommand(0x33, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec(  253): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
I/OMXCodec(  253): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/OMX     (  253): instance freeNode
I/AudioPlayer(  253): reset out
V/AwesomePlayer(  253): reset_l() mAudioPlayer successfully deleted
I/SecMediaClock(  253): SecMediaClock destructor
V/AwesomePlayer(  253): mSecMediaClock clear
V/StagefrightPlayer(  253): ~StagefrightPlayer
V/StagefrightPlayer(  253): reset
V/AwesomePlayer(  253): reset_l()
V/AwesomePlayer(  253): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  253): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  253): mAudioTrackVector clear
V/AwesomePlayer(  253): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  253): mSecMediaClock clear
V/AwesomePlayer(  253): destructor
V/AwesomePlayer(  253): reset_l()
V/AwesomePlayer(  253): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  253): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  253): mAudioTrackVector clear
V/AwesomePlayer(  253): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  253): mSecMediaClock clear
V/MediaPlayer( 2673): decode(73, 37491572, 52024)
V/MediaPlayerService(  253): decode(35, 37491572, 52024)
V/MediaPlayerService(  253): player type = 3
V/AwesomePlayer(  253): setDefault
V/AwesomePlayer(  253): constructor
V/AwesomePlayer(  253): setDefault
V/AwesomePlayer(  253): reset_l()
V/AwesomePlayer(  253): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  253): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  253): mAudioTrackVector clear
V/AwesomePlayer(  253): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  253): mSecMediaClock clear
V/StagefrightPlayer(  253): StagefrightPlayer
V/AwesomePlayer(  253): setListener
V/StagefrightPlayer(  253): initCheck
V/AwesomePlayer(  253): setAudioSink
V/StagefrightPlayer(  253): setDataSource(35, 37491572, 52024)
V/AwesomePlayer(  253): reset_l()
V/AwesomePlayer(  253): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  253): notify(0xb8aaf708, 8, 0, 0)
V/AudioCache(  253): ignored
V/AwesomePlayer(  253): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  253): mAudioTrackVector clear
V/AwesomePlayer(  253): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  253): mSecMediaClock clear
V/AwesomePlayer(  253): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer(  253): mBitrate = -1 bits/sec
V/AwesomePlayer(  253): current audio track index (0) is added to vector
V/AwesomePlayer(  253): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer(  253): AwesomePlayer::setDataSource_l():: This is not a DRM content
V/MediaPlayerService(  253): prepare
V/AwesomePlayer(  253): prepareAsync
V/MediaPlayerService(  253): wait for prepare
V/AwesomePlayer(  253): onPrepareAsyncEvent
I/SecMediaClock(  253): SecMediaClock constructor
I/SecMediaClock(  253): reset
V/AwesomePlayer(  253): initAudioDecoder
V/AwesomePlayer(  253): checkOffloadExceptions is true
I/OMXCodec(  253): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
I/OMX     (  253): mDispatchers.add
I/OMXCodec(  253): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec(  253): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec(  253): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec(  253): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/OMXCodec(  253): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer(  253): finishAsyncPrepare_l
V/AwesomePlayer(  253): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache(  253): notify(0xb8aaf708, 200, 973, 0)
V/AudioCache(  253): ignored
V/AwesomePlayer(  253): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  253): notify(0xb8aaf708, 5, 0, 0)
V/AudioCache(  253): ignored
V/AwesomePlayer(  253): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  253): notify(0xb8aaf708, 1, 0, 0)
V/AudioCache(  253): prepared
V/AudioCache(  253): wait - success
V/MediaPlayerService(  253): start
V/StagefrightPlayer(  253): start
V/AwesomePlayer(  253): play
V/AwesomePlayer(  253): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer(  253): startAudioPlayer_l, sendErrorNotification (0)
I/OMXCodec(  253): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec(  253): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec(  253): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/AudioPlayer(  253):  Audioplayer kKeyAudioPCMFormat:1, 2, 0
I/AudioPlayer(  253):  Audioplayer kKeyAudioPCMFormat read fail(2, 1)
V/AudioCache(  253): open(48000, 2, 0x0, 1, 4)
V/AwesomePlayer(  253): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache(  253): notify(0xb8aaf708, 6, 0, 0)
V/AudioCache(  253): ignored
V/AwesomePlayer(  253): addBatteryData
V/MediaPlayerService(  253): wait for playback complete
--------- beginning of /dev/log/system
D/SignalClusterView_dual( 1066): wifi: VISIBLE sig=2130837979 act=2130837936
D/SignalClusterView_dual( 1066): mMobileDataState=0 mMobileDataState2=0
D/SignalClusterView_dual( 1066): apply() mSeparateMobileGroup=8
D/STATUSBAR-NetworkController_dual( 1066): refreshSignalCluster - setNWBoosterIndicators(false)
D/SignalClusterView_dual( 1066): wifi: VISIBLE sig=2130837979 act=2130837946
D/SignalClusterView_dual( 1066): mMobileDataState=0 mMobileDataState2=0
D/SignalClusterView_dual( 1066): apply() mSeparateMobileGroup=8
D/SignalClusterView_dual( 1066): wifi: VISIBLE sig=2130837979 act=2130837946
D/SignalClusterView_dual( 1066): mMobileDataState=0 mMobileDataState2=0
D/SignalClusterView_dual( 1066): apply() mSeparateMobileGroup=8
D/SignalClusterView_dual( 1066): wifi: VISIBLE sig=2130837979 act=2130837946
D/SignalClusterView_dual( 1066): mMobileDataState=0 mMobileDataState2=0
D/SignalClusterView_dual( 1066): apply() mSeparateMobileGroup=8
D/SignalClusterView_dual( 1066): wifi: VISIBLE sig=2130837979 act=2130837946
D/SignalClusterView_dual( 1066): mMobileDataState=0 mMobileDataState2=0
D/SignalClusterView_dual( 1066): apply() mSeparateMobileGroup=8
D/StatusBar.NetworkController_dual( 1066): mMobileLabelViews start
D/StatusBar.NetworkController_dual( 1066): mMobileLabelViews set mobileLabel[SIM_0] =
D/StatusBar.NetworkController_dual( 1066): mMobileLabelViews GONE
D/StatusBar.NetworkController_dual( 1066): mMobileLabelViews2 set mobileLabel[SIM_1] =
D/StatusBar.NetworkController_dual( 1066): mMobileLabelViews2 GONE
D/StatusBar.NetworkController_dual( 1066): mSingleMobileLabelViews set : simMode = 0
D/StatusBar.NetworkController_dual( 1066): mSingleMobileLabelViews set as slot1`s
D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:1
I/OMXCodec(  253): [OMX.google.vorbis.decoder] End Of Stream
V/AwesomePlayer(  253): postAudioEOS delayUs (0)
V/AwesomePlayer(  253): onCheckAudioStatus
V/AwesomePlayer(  253): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  253): onStreamDone
V/AwesomePlayer(  253): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  253): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  253): notify(0xb8aaf708, 2, 0, 0)
V/AudioCache(  253): playback complete - thread will wake up later
V/AwesomePlayer(  253): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  253): notify(0xb8aaf708, 7, 0, 0)
V/AudioCache(  253): ignored
V/AwesomePlayer(  253): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer(  253): addBatteryData
V/AudioCache(  253): wait - success
V/StagefrightPlayer(  253): reset
V/AwesomePlayer(  253): reset_l()
V/AwesomePlayer(  253): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  253): notify(0xb8aaf708, 8, 0, 0)
V/AudioCache(  253): ignored
V/AwesomePlayer(  253): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  253): mAudioTrackVector clear
I/OMXCodec(  253): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec(  253): [OMX.google.vorbis.decoder] stop() sendCommand(0x34, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec(  253): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
I/OMXCodec(  253): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/OMX     (  253): instance freeNode
I/AudioPlayer(  253): reset out
V/AwesomePlayer(  253): reset_l() mAudioPlayer successfully deleted
I/SecMediaClock(  253): SecMediaClock destructor
V/AwesomePlayer(  253): mSecMediaClock clear
V/StagefrightPlayer(  253): ~StagefrightPlayer
V/StagefrightPlayer(  253): reset
V/AwesomePlayer(  253): reset_l()
V/AwesomePlayer(  253): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  253): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  253): mAudioTrackVector clear
V/AwesomePlayer(  253): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  253): mSecMediaClock clear
V/AwesomePlayer(  253): destructor
V/AwesomePlayer(  253): reset_l()
V/AwesomePlayer(  253): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  253): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  253): mAudioTrackVector clear
V/AwesomePlayer(  253): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  253): mSecMediaClock clear
V/MediaPlayer( 2673): decode(74, 33969800, 9226)
V/MediaPlayerService(  253): decode(35, 33969800, 9226)
V/MediaPlayerService(  253): player type = 3
V/AwesomePlayer(  253): setDefault
V/AwesomePlayer(  253): constructor
V/AwesomePlayer(  253): setDefault
V/AwesomePlayer(  253): reset_l()
V/AwesomePlayer(  253): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  253): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  253): mAudioTrackVector clear
V/AwesomePlayer(  253): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  253): mSecMediaClock clear
V/StagefrightPlayer(  253): StagefrightPlayer
V/AwesomePlayer(  253): setListener
V/StagefrightPlayer(  253): initCheck
V/AwesomePlayer(  253): setAudioSink
V/StagefrightPlayer(  253): setDataSource(35, 33969800, 9226)
V/AwesomePlayer(  253): reset_l()
V/AwesomePlayer(  253): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  253): notify(0xb8abbb08, 8, 0, 0)
V/AudioCache(  253): ignored
V/AwesomePlayer(  253): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  253): mAudioTrackVector clear
V/AwesomePlayer(  253): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  253): mSecMediaClock clear
V/AwesomePlayer(  253): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer(  253): mBitrate = -1 bits/sec
V/AwesomePlayer(  253): current audio track index (0) is added to vector
V/AwesomePlayer(  253): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer(  253): AwesomePlayer::setDataSource_l():: This is not a DRM content
V/MediaPlayerService(  253): prepare
V/AwesomePlayer(  253): prepareAsync
V/MediaPlayerService(  253): wait for prepare
V/AwesomePlayer(  253): onPrepareAsyncEvent
I/SecMediaClock(  253): SecMediaClock constructor
I/SecMediaClock(  253): reset
V/AwesomePlayer(  253): initAudioDecoder
V/AwesomePlayer(  253): checkOffloadExceptions is true
I/OMXCodec(  253): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
I/OMX     (  253): mDispatchers.add
I/OMXCodec(  253): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec(  253): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec(  253): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec(  253): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/OMXCodec(  253): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer(  253): finishAsyncPrepare_l
V/AwesomePlayer(  253): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache(  253): notify(0xb8abbb08, 200, 973, 0)
V/AudioCache(  253): ignored
V/AwesomePlayer(  253): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  253): notify(0xb8abbb08, 5, 0, 0)
V/AudioCache(  253): ignored
V/AwesomePlayer(  253): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  253): notify(0xb8abbb08, 1, 0, 0)
V/AudioCache(  253): prepared
V/AudioCache(  253): wait - success
V/MediaPlayerService(  253): start
V/StagefrightPlayer(  253): start
V/AwesomePlayer(  253): play
V/AwesomePlayer(  253): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer(  253): startAudioPlayer_l, sendErrorNotification (0)
I/OMXCodec(  253): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec(  253): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec(  253): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/AudioPlayer(  253):  Audioplayer kKeyAudioPCMFormat:1, 2, 0
I/AudioPlayer(  253):  Audioplayer kKeyAudioPCMFormat read fail(2, 1)
V/AudioCache(  253): open(44100, 2, 0x0, 1, 4)
V/AwesomePlayer(  253): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache(  253): notify(0xb8abbb08, 6, 0, 0)
V/AudioCache(  253): ignored
V/AwesomePlayer(  253): addBatteryData
V/MediaPlayerService(  253): wait for playback complete
I/OMXCodec(  253): [OMX.google.vorbis.decoder] End Of Stream
V/AwesomePlayer(  253): postAudioEOS delayUs (0)
V/AwesomePlayer(  253): onCheckAudioStatus
V/AwesomePlayer(  253): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  253): onStreamDone
V/AwesomePlayer(  253): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  253): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  253): notify(0xb8abbb08, 2, 0, 0)
V/AudioCache(  253): playback complete - thread will wake up later
V/AwesomePlayer(  253): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  253): notify(0xb8abbb08, 7, 0, 0)
V/AudioCache(  253): ignored
V/AwesomePlayer(  253): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer(  253): addBatteryData
V/AudioCache(  253): wait - success
V/StagefrightPlayer(  253): reset
V/AwesomePlayer(  253): reset_l()
V/AwesomePlayer(  253): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  253): notify(0xb8abbb08, 8, 0, 0)
V/AudioCache(  253): ignored
V/AwesomePlayer(  253): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  253): mAudioTrackVector clear
I/OMXCodec(  253): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec(  253): [OMX.google.vorbis.decoder] stop() sendCommand(0x35, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec(  253): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
I/OMXCodec(  253): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/OMX     (  253): instance freeNode
I/AudioPlayer(  253): reset out
V/AwesomePlayer(  253): reset_l() mAudioPlayer successfully deleted
I/SecMediaClock(  253): SecMediaClock destructor
V/AwesomePlayer(  253): mSecMediaClock clear
V/StagefrightPlayer(  253): ~StagefrightPlayer
V/StagefrightPlayer(  253): reset
V/AwesomePlayer(  253): reset_l()
V/AwesomePlayer(  253): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  253): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  253): mAudioTrackVector clear
V/AwesomePlayer(  253): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  253): mSecMediaClock clear
V/AwesomePlayer(  253): destructor
V/AwesomePlayer(  253): reset_l()
V/AwesomePlayer(  253): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  253): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  253): mAudioTrackVector clear
V/AwesomePlayer(  253): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  253): mSecMediaClock clear
V/MediaPlayer( 2673): decode(75, 30402580, 4509)
V/MediaPlayerService(  253): decode(35, 30402580, 4509)
V/MediaPlayerService(  253): player type = 3
V/AwesomePlayer(  253): setDefault
V/AwesomePlayer(  253): constructor
V/AwesomePlayer(  253): setDefault
V/AwesomePlayer(  253): reset_l()
V/AwesomePlayer(  253): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  253): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  253): mAudioTrackVector clear
V/AwesomePlayer(  253): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  253): mSecMediaClock clear
V/StagefrightPlayer(  253): StagefrightPlayer
V/AwesomePlayer(  253): setListener
V/StagefrightPlayer(  253): initCheck
V/AwesomePlayer(  253): setAudioSink
V/StagefrightPlayer(  253): setDataSource(35, 30402580, 4509)
V/AwesomePlayer(  253): reset_l()
V/AwesomePlayer(  253): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  253): notify(0xb8ab4308, 8, 0, 0)
V/AudioCache(  253): ignored
V/AwesomePlayer(  253): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  253): mAudioTrackVector clear
V/AwesomePlayer(  253): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  253): mSecMediaClock clear
V/AwesomePlayer(  253): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer(  253): mBitrate = -1 bits/sec
V/AwesomePlayer(  253): current audio track index (0) is added to vector
V/AwesomePlayer(  253): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer(  253): AwesomePlayer::setDataSource_l():: This is not a DRM content
V/MediaPlayerService(  253): prepare
V/AwesomePlayer(  253): prepareAsync
V/MediaPlayerService(  253): wait for prepare
V/AwesomePlayer(  253): onPrepareAsyncEvent
I/SecMediaClock(  253): SecMediaClock constructor
I/SecMediaClock(  253): reset
V/AwesomePlayer(  253): initAudioDecoder
V/AwesomePlayer(  253): checkOffloadExceptions is true
I/OMXCodec(  253): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
I/OMX     (  253): mDispatchers.add
I/OMXCodec(  253): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec(  253): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec(  253): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec(  253): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/OMXCodec(  253): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer(  253): finishAsyncPrepare_l
V/AwesomePlayer(  253): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache(  253): notify(0xb8ab4308, 200, 973, 0)
V/AudioCache(  253): ignored
V/AwesomePlayer(  253): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  253): notify(0xb8ab4308, 5, 0, 0)
V/AudioCache(  253): ignored
V/AwesomePlayer(  253): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  253): notify(0xb8ab4308, 1, 0, 0)
V/AudioCache(  253): prepared
V/AudioCache(  253): wait - success
V/MediaPlayerService(  253): start
V/StagefrightPlayer(  253): start
V/AwesomePlayer(  253): play
V/AwesomePlayer(  253): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer(  253): startAudioPlayer_l, sendErrorNotification (0)
I/OMXCodec(  253): [OMX.google.vorbis.decoder] End Of Stream
I/OMXCodec(  253): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec(  253): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec(  253): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/AudioPlayer(  253):  Audioplayer kKeyAudioPCMFormat:1, 2, 0
I/AudioPlayer(  253):  Audioplayer kKeyAudioPCMFormat read fail(2, 1)
V/AudioCache(  253): open(44100, 2, 0x0, 1, 4)
V/AwesomePlayer(  253): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache(  253): notify(0xb8ab4308, 6, 0, 0)
I/AudioPlayer(  253): First fillBuffer call!!
V/AudioCache(  253): ignored
V/AwesomePlayer(  253): addBatteryData
V/MediaPlayerService(  253): wait for playback complete
V/AwesomePlayer(  253): postAudioEOS delayUs (0)
V/AwesomePlayer(  253): onCheckAudioStatus
V/AwesomePlayer(  253): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  253): onStreamDone
V/AwesomePlayer(  253): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  253): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  253): notify(0xb8ab4308, 2, 0, 0)
V/AudioCache(  253): playback complete - thread will wake up later
V/AwesomePlayer(  253): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  253): notify(0xb8ab4308, 7, 0, 0)
V/AudioCache(  253): ignored
V/AwesomePlayer(  253): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer(  253): addBatteryData
V/AudioCache(  253): wait - success
V/StagefrightPlayer(  253): reset
V/AwesomePlayer(  253): reset_l()
V/AwesomePlayer(  253): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  253): notify(0xb8ab4308, 8, 0, 0)
V/AudioCache(  253): ignored
V/AwesomePlayer(  253): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  253): mAudioTrackVector clear
I/OMXCodec(  253): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec(  253): [OMX.google.vorbis.decoder] stop() sendCommand(0x36, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec(  253): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
I/OMXCodec(  253): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/OMX     (  253): instance freeNode
I/AudioPlayer(  253): reset out
V/AwesomePlayer(  253): reset_l() mAudioPlayer successfully deleted
I/SecMediaClock(  253): SecMediaClock destructor
V/AwesomePlayer(  253): mSecMediaClock clear
V/StagefrightPlayer(  253): ~StagefrightPlayer
V/StagefrightPlayer(  253): reset
V/AwesomePlayer(  253): reset_l()
V/AwesomePlayer(  253): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  253): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  253): mAudioTrackVector clear
V/AwesomePlayer(  253): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  253): mSecMediaClock clear
V/AwesomePlayer(  253): destructor
V/AwesomePlayer(  253): reset_l()
V/AwesomePlayer(  253): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  253): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  253): mAudioTrackVector clear
V/AwesomePlayer(  253): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  253): mSecMediaClock clear
W/ActivityManager(  742): Permission Denial: getCurrentUser() from pid=2734, uid=10036 requires android.permission.INTERACT_ACROSS_USERS
I/Process ( 2734): Sending signal. PID: 2734 SIG: 9
I/ActivityManager(  742): Process com.sec.android.app.sns3 (pid 2734) (adj 0) has died.
I/SELinux ( 2787): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 2787):  
I/SELinux ( 2787): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 2787):  
I/SELinux ( 2787):  
I/SELinux ( 2787): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 2787): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 2787): >>>>> Normal User
E/dalvikvm( 2787): >>>>> com.policydm [ userId:0 | appId:1000 ]
E/SELinux ( 2787): [DEBUG] seapp_context_lookup: seinfoCategory = platform
D/TimaKeyStoreProvider( 2787): in addTimaSignatureService
D/TimaKeyStoreProvider( 2787): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 2787): Added TimaKesytore provider
I/SELinux ( 2807): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 2807):  
I/SELinux ( 2807): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 2807):  
I/SELinux ( 2807):  
I/SELinux ( 2807): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 2807): [DEBUG] seapp_context_lookup: seinfoCategory = samsung
E/dalvikvm( 2807): >>>>> Normal User
E/dalvikvm( 2807): >>>>> com.sec.spp.push [ userId:0 | appId:10038 ]
E/SELinux ( 2807): [DEBUG] seapp_context_lookup: seinfoCategory = samsung
D/TimaKeyStoreProvider( 2807): in addTimaSignatureService
D/TimaKeyStoreProvider( 2807): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 2807): Added TimaKesytore provider
E/SPPClientService( 2807): ============PushLog. commonIsShipBuild. stop!
E/SPPClientService( 2807): [PushClientApplication] Push log off : This is Ship build version
D/SPPClientService( 2807): PushLog.txt file is not deleted.
D/SPPClientService( 2807): PushLog.txt file is not deleted.
D/SPPClientService( 2807): ============PushLog. stop!
E/SPPClientService( 2807): [SystemStateMoniter] ACTION_BOOT_COMPLETED
I/SELinux ( 2821): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 2821):  
I/SELinux ( 2821): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 2821):  
I/SELinux ( 2821):  
I/SELinux ( 2821): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 2821): [DEBUG] seapp_context_lookup: seinfoCategory = default
E/dalvikvm( 2821): >>>>> Normal User
E/dalvikvm( 2821): >>>>> com.osp.app.signin [ userId:0 | appId:10043 ]
E/SELinux ( 2821): [DEBUG] seapp_context_lookup: seinfoCategory = default
D/TimaKeyStoreProvider( 2821): in addTimaSignatureService
D/TimaKeyStoreProvider( 2821): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 2821): Added TimaKesytore provider
I/SA      ( 2821): [SSP] onCreated
I/SA      ( 2821): [TPM] There is no property file
I/SA      ( 2821): [SCU] isHaveSA() - false
I/SA      ( 2821): [TPM] getModelProperty : null
I/SA      ( 2821): [TPM] getCSCProperty : null
I/SA      ( 2821): [SBR] StdBroadcastReceiver received Intent of  action_BOOT_COMPLETED
I/SA      ( 2821): [DM] init START
I/SA      ( 2821): [DM] This device is not a Vodafone
I/SA      ( 2821): [DM] getCountryCodeFromCSC : PL
I/SA      ( 2821): support phone number id : false
I/SA      ( 2821): [DM] init END
I/SA      ( 2821): [OR] onReceive log=[SA = 2.0.0117 V = 19 HWD = 1280X720 2.0 dpi = 320  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = kmini3g P = kmini3gxx I = KOT49H M = SM-G800H OKLEFT false DIS KOT49H.G800HXXU1ANK2 PSS = 4.497045606779314  ]
I/SA      ( 2821): [BDLM] already registered in spp
I/SA      ( 2821): [OR] onReceive Intent=[ action_BOOT_COMPLETED ]
I/SA      ( 2821): [OR] onReceive END
I/SA      ( 2821): [BDC] create
W/Atfwd_Sendcmd(  291): AtCmdFwd service not published, waiting... retryCnt : 3
I/SA      ( 2821): [DBMV2] getEmailID
I/SA      ( 2821): [DBMV2] getDataV02ForItems
I/SA      ( 2821): [SSP] query invoked
I/SA      ( 2821): [SCU] get signed id from samsung account2.0 DB.
I/SELinux ( 2837): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 2837):  
I/SA      ( 2821): [SCU] get signed id from samsung account1.0 DB.
I/SA      ( 2821): [BDC] destroy
I/SELinux ( 2837): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 2837):  
I/SELinux ( 2837):  
I/SELinux ( 2837): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 2837): [DEBUG] seapp_context_lookup: seinfoCategory = release
E/dalvikvm( 2837): >>>>> Normal User
E/dalvikvm( 2837): >>>>> com.android.providers.calendar [ userId:0 | appId:10044 ]
E/SELinux ( 2837): [DEBUG] seapp_context_lookup: seinfoCategory = release
D/TimaKeyStoreProvider( 2837): in addTimaSignatureService
D/TimaKeyStoreProvider( 2837): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 2837): Added TimaKesytore provider
D/SignalClusterView_dual( 1066): wifi: VISIBLE sig=2130837979 act=2130837946
D/SignalClusterView_dual( 1066): mMobileDataState=0 mMobileDataState2=0
D/SignalClusterView_dual( 1066): apply() mSeparateMobileGroup=8
D/STATUSBAR-NetworkController_dual( 1066): refreshSignalCluster - setNWBoosterIndicators(false)
D/SignalClusterView_dual( 1066): wifi: VISIBLE sig=2130837979 act=2130837936
D/SignalClusterView_dual( 1066): mMobileDataState=0 mMobileDataState2=0
D/SignalClusterView_dual( 1066): apply() mSeparateMobileGroup=8
D/SignalClusterView_dual( 1066): wifi: VISIBLE sig=2130837979 act=2130837936
D/SignalClusterView_dual( 1066): mMobileDataState=0 mMobileDataState2=0
D/SignalClusterView_dual( 1066): apply() mSeparateMobileGroup=8
D/SignalClusterView_dual( 1066): wifi: VISIBLE sig=2130837979 act=2130837936
D/SignalClusterView_dual( 1066): mMobileDataState=0 mMobileDataState2=0
D/SignalClusterView_dual( 1066): apply() mSeparateMobileGroup=8
D/SignalClusterView_dual( 1066): wifi: VISIBLE sig=2130837979 act=2130837936
D/SignalClusterView_dual( 1066): mMobileDataState=0 mMobileDataState2=0
D/SignalClusterView_dual( 1066): apply() mSeparateMobileGroup=8
D/StatusBar.NetworkController_dual( 1066): mMobileLabelViews start
D/StatusBar.NetworkController_dual( 1066): mMobileLabelViews set mobileLabel[SIM_0] =
D/StatusBar.NetworkController_dual( 1066): mMobileLabelViews GONE
D/StatusBar.NetworkController_dual( 1066): mMobileLabelViews2 set mobileLabel[SIM_1] =
D/StatusBar.NetworkController_dual( 1066): mMobileLabelViews2 GONE
D/StatusBar.NetworkController_dual( 1066): mSingleMobileLabelViews set : simMode = 0
D/StatusBar.NetworkController_dual( 1066): mSingleMobileLabelViews set as slot1`s
D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:1
,W/ActivityManager(  742): Permission Denial: getCurrentUser() from pid=2837, uid=10044 requires android.permission.INTERACT_ACROSS_USERS
D/MediaScannerReceiver( 1204): action: android.intent.action.BOOT_COMPLETED
W/ContextImpl(  742): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
W/ContextImpl(  742): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.android.server.ssrm.u.i:-1 com.android.server.ssrm.ai.run:-1 android.os.Handler.handleCallback:733 android.os.Handler.dispatchMessage:95 
D/PowerManagerService(  742): [s] UserActivityState : 1 -> 0
I/PowerManagerService(  742): Nap time...
D/PowerManagerService(  742): [s] WAKEFULNESS_NAPPING
I/PowerManagerService(  742): !@[ps] Screen__Off(2) :  dream finished from Napping
I/PowerManagerService(  742): Going to sleep due to screen timeout...
D/PowerManagerService(  742): [s] WAKEFULNESS_ASLEEP
D/DisplayPowerController(  742): [DAB] setLightSensorEnabled : Send Update unregisterListener mLightSensor
I/DisplayPowerController(  742): [DAB] fileWriteInt : /sys/class/backlight/panel/auto_brightness  value : 0
D/Sensors (  742): LightSensor enable = 0
D/Sensors (  742): LightSensor enableSensor = 0
D/SensorManager(  742): unregisterListener ::   
I/Sensors (  742): HAL:resetDataRates mEnabled=4
D/DisplayPowerController(  742): [DAB] setLightSensorEnabled : unregisterListener mLightSensor
D/SensorManager(  742): unregisterListener ::   
D/MediaScannerService( 1204): !@start scanning volume internal: [/system/media]
D/TP/MmsProvider( 1239): Update uri=content://mms, match=0
D/TP/MmsProvider( 1239): update , handleReadChangedBroadcast
D/TP/MmsSmsProvider( 1239): need read changed broadcast:false
I/Mms:transaction( 1669): [MmsSystemEventReceiver] restorePduNotificationStatus count=0
D/Mms/MessagingNotification( 1669): [start]    nonBlockingUpdateMessageIndicator()
I/Mms/ReservationManager( 1669): resetAfterConnected()
D/Mms/MessagingNotification( 1669): sDisableVibrateForCamera = false
D/TP/MmsSmsProvider( 1239): match 7:Elapsed time : 2.274 ms
D/Mms/MessagingNotification( 1669): isBlockingModeEnable() = false
D/Mms/TelephonyPermission( 1669): isDefault true
I/Mms/ReservationManager( 1669): getReservedSendMessageCount(): retMessageCount=0
D/TP/MmsSmsProvider( 1239): match 200:Elapsed time : 1.360 ms
I/SELinux ( 2864): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 2864):  
I/SurfaceFlinger(  248): id=14 createSurf (720x1280),-1 flag=20004, FlectronBea
D/dalvikvm(  249): GC_EXPLICIT freed 43K, 50% free 9509K/18976K, paused 2ms+3ms, total 25ms
D/DisplayPowerController(  742): !@ElectronBeam entry
D/dalvikvm(  249): GC_EXPLICIT freed <1K, 50% free 9509K/18976K, paused 1ms+3ms, total 19ms
I/SELinux ( 2864): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 2864):  
I/SELinux ( 2864):  
I/SELinux ( 2864): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 2864): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 2864): >>>>> Normal User
E/dalvikvm( 2864): >>>>> com.sec.android.app.safetyassurance [ userId:0 | appId:10050 ]
E/SELinux ( 2864): [DEBUG] seapp_context_lookup: seinfoCategory = platform
D/dalvikvm(  249): GC_EXPLICIT freed <1K, 50% free 9509K/18976K, paused 1ms+4ms, total 21ms
D/TimaKeyStoreProvider( 2864): in addTimaSignatureService
D/TimaKeyStoreProvider( 2864): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 2864): Added TimaKesytore provider
D/SSRMv2:SIOP(  742): SIOP:: AP = 330, Delta = 20
D/Mms/TelephonyPermission( 1669): isDefault true
D/Mms/SmsReceiverService( 1669): [SMS]Receiver handleMessage : Action =android.intent.action.BOOT_COMPLETED
D/Mms/SmsReceiverService( 1669): [start]    handleBootCompleted()
D/AndroidRuntime( 2850): 
D/AndroidRuntime( 2850): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/TP/MmsSmsProvider( 1239): deleteConversation threadId: 9223372036854775806
D/AndroidRuntime( 2850): CheckJNI is OFF
D/AndroidRuntime( 2850): setted country_code = Poland
D/AndroidRuntime( 2850): setted countryiso_code = PL
D/AndroidRuntime( 2850): setted sales_code = XEO
D/AndroidRuntime( 2850): readGMSProperty: start
D/AndroidRuntime( 2850): readGMSProperty: already setted!!
D/AndroidRuntime( 2850): readGMSProperty: end
D/AndroidRuntime( 2850): addProductProperty: start
D/BadgeProvider( 1340): query, [selection] : package='com.android.mms' AND class='com.android.mms.ui.ConversationComposer' AND extraData='base_extra_badge'
D/SensorService(  742):   -0.1 -0.1 9.6
D/TP/MmsSmsProvider( 1239): delete URI_CONVERSATIONS_MESSAGES affectedRows=0
D/dalvikvm( 2850): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 2850): Added shared lib libjavacore.so 0x0
D/Launcher.Model( 1259): reloadBadges entered.
D/dalvikvm( 2850): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 2850): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 2850): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
D/BadgeProvider( 1340): sendNotify entered. [uri] : content://com.sec.badge/apps/2
D/BadgeProvider( 1340): sendNotify, [notify] : null
D/BadgeProvider( 1340): update, [uri] : content://com.sec.badge/apps/2
D/BadgeProvider( 1340): update, [BadgeCount] : badgecount=0
D/BadgeProvider( 1340): update, [UpdateCount] : 1
D/Mms/MessagingNotification( 1669): setBadgeCount(), count=0
D/MessagingNotification( 1669): remove alarm
W/dalvikvm( 2864): Refusing to reopen boot DEX '/system/framework/seccamera.jar'
D/Mms/MessagingNotification( 1669): updateAllHistoryAsRead()
D/TP/MmsSmsProvider( 1239): delete threadId: 9223372036854775806
D/TP/MmsSmsProvider( 1239): need read changed broadcast:false
D/Mms/MessagingNotification( 1669): [end]    nonBlockingUpdateMessageIndicator()
D/SafetyAssuranceAppFeatures( 2864): init start
I/SafetyAssuranceAppFeatures( 2864): mLoadBaiduMap:false
I/SafetyAssuranceAppFeatures( 2864): mFeatureEnableMultiSim true
D/SafetyAssuranceAppFeatures( 2864): init end
D/Mms/Conversation( 1669): deleteTempConversation(),deleted=0
D/SafetyAssuranceReceiver( 2864): onReceive
I/SafetyAssuranceApp( 2864): Acquire WL
D/SmsProvider( 1239): Update uri=content://sms/outbox, match=8
D/TP/MmsSmsProvider( 1239): need read changed broadcast:false
D/SafetyAssuranceConfig( 2864): getAppState : 1
D/SafetyAssuranceReceiver( 2864): onReceive - action:android.intent.action.BOOT_COMPLETED, currentAppState:1
D/SafetyAssuranceReceiver( 2864): Init App state
D/Mms/SmsReceiverService( 1669): sendFirstQueuedMessage()
D/Mms/SmsReceiverService( 1669): [SIM-1]sendFirstQueuedMessage()
W/BackupManagerService(  742): dataChanged but no participant pkg='com.android.providers.settings' uid=10050
D/SafetyAssuranceConfig( 2864): setAppState : 1
D/SafetyAssuranceApp( 2864): topActivity's name is=.BatteryCover
I/SafetyAssuranceApp( 2864): Release WL
D/KeyguardViewMediator( 1066): handleKeyguardDoneDrawing
D/lights  (  742): lcd : 0 +
D/Mms/MessagingNotification( 1669): sDisableVibrateForCamera = false
D/Mms/MessagingNotification( 1669): isBlockingModeEnable() = false
D/Mms/TelephonyPermission( 1669): isDefault true
D/MediaScanner( 1204): Prescan. DB items number : 156 DB_FILES_NUMBER_CACHING_LIMITATION : 7000  Caching mode : true
I/NetworkStatusReceiver( 1239): action: android.intent.action.BOOT_COMPLETED
D/lights  (  742): lcd : 0 -
D/MISC PowerHAL(  742): miscpower_set_interactive: /sys/class/input/input1/enabled
D/MISC PowerHAL(  742): sysfs_write +: /sys/class/input/input1/enabled: 0
D/MISC PowerHAL(  742): sysfs_write -: /sys/class/input/input1/enabled: 0
D/MISC PowerHAL(  742): miscpower_set_interactive: /sys/class/input/input6/enabled
D/MISC PowerHAL(  742): sysfs_write +: /sys/class/input/input6/enabled: 0
D/MISC PowerHAL(  742): sysfs_write -: /sys/class/input/input6/enabled: 0
D/MISC PowerHAL(  742): sysfs_write +: /sys/class/power_supply/battery/lcd: 0
V/WindowOrientationListener(  742): WindowOrientationListener disabled
D/SensorService(  742): AutoRotationSensor::activate (ident=0x72a49700, enabled=0)
I/Sensors (  742): HAL: batch Dry Run is complete
D/KeyguardViewMediator( 1066): onScreenTurnedOff(3)
D/PowerManagerService(  742): blankAllDisplays() is called.
D/PowerManagerService(  742): [s] mDisplayPowerControllerCallbacks : onStateChanged()
D/PowerManagerService(  742): [PWL] sb acquire: PowerManagerService.Broadcasts
D/PowerManagerService(  742): [PWL] sb release: PowerManagerService.Display
D/MISC PowerHAL(  742): sysfs_write -: /sys/class/power_supply/battery/lcd: 0
I/QCOM PowerHAL(  742): Got set_interactive hint
D/KeyguardViewMediator( 1066): notifyScreenOffLocked
I/Sensors (  742): HAL:resetDataRates mEnabled=4
D/SurfaceFlinger(  248): Screen released, type=0 flinger=0xb7ab5980
D/qdhwcomposer(  248): hwc_blank: Blanking display: 0
E/KeyguardViewMediator( 1066): resetStateLocked
D/KeyguardViewMediator( 1066): handleNotifyScreenOff
D/KeyguardViewManager( 1066): onScreenTurnedOff()
D/KeyguardHostView( 1066): screen off, instance 4259e9f8 at 39835
D/LockPatternUtils( 1066): isPcwEnable = null
V/KeyguardHostView( 1066): showPrimarySecurityScreen(turningOff=true)
D/PowerManagerService(  742): !@[s] blankAllDisplays() : blankAllDisplaysFromPowerManage
I/MDPP    ( 1066): Property: Empty
D/KeyguardHostView( 1066): showSecurityScreen(None)
D/SecCameraShortcut( 1066): onScreenTurnedOff
D/SensorManager(  742): unregisterListener ::   
D/InputDispatcher(  742): setInputDispatchMode: enabled=0, frozen=0
D/SensorManager( 1066): unregisterListener ::   
I/KeyguardEffectViewMain( 1066): *** KeyguardEffectView getInstance ***
D/VisualEffectParticleEffect( 1066): KeyguardEffectViewParticleSpace : screenTurnedOff
D/VisualEffectParticleEffect( 1066): clearEffect
D/PersonaManager( 1066): isKioskContainerExistOnDevice
D/KeyguardViewMediator( 1066): Kiosk container not exists on device or sim lock exists.
D/KeyguardViewMediator( 1066): handleReset
D/KeyguardViewManager( 1066): reset()
D/KeyguardHostView( 1066): onSaveInstanceState, tstate=1
D/KeyguardGuestSelectorView( 1066): onDetachedFromWindow()
V/KeyguardUpdateMonitor( 1066): *** unregister callback for com.android.keyguard.CarrierText$1@42877428
V/KeyguardUpdateMonitor( 1066): *** unregister callback for com.android.keyguard.MSimCarrierText$1@42877800
V/KeyguardUpdateMonitor( 1066): *** unregister callback for com.android.keyguard.CarrierText$1@42864088
V/KeyguardUpdateMonitor( 1066): *** unregister callback for com.android.keyguard.EmergencyButton$1@42874230
E/memtrack( 2850): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 2850): failed to load memtrack module: -2
V/MediaScanner( 1204): processDirectory :  /system/media
D/dalvikvm( 2850): Note: class Landroid/app/ActivityManagerNative; has 192 unimplemented (abstract) methods
V/MediaScanner( 1204):  prescan time: 352ms (DB items: 156)
V/MediaScanner( 1204):     scan time: 58ms (Caching mode: true), (makeEntry time: 27ms ~46%),  (parsing time: 0ms ~0%),  (bitmapDecoding time: 0ms ~0%), (exifExtracting time : 0ms ~0%), (sefExtracting time : 0ms ~0%), (bulkInserter time : 0ms ~0%)
V/MediaScanner( 1204): postscan time: 1ms (bulkDeleter : 0), (delete DeadThumbnail time : 0ms)
V/MediaScanner( 1204):    total time: 411ms
V/MediaScanner( 1204): checked files: 149  directories : 5  (I: 0, U: 0)
D/MediaScanner( 1204): checkDefaultSounds
D/MediaScanner( 1204): system alarm_alert  : Vwiurug_etwofi5wgg
D/AndroidRuntime( 2850): Calling main entry com.android.commands.am.Am
D/qdhwcomposer(  248): hwc_blank: Done blanking display: 0
D/SurfaceControl(  742): Excessive delay in blankDisplay() while turning screen off: 249ms
I/libsuspend(  742): !@[s] autosuspend_autosleep_enable
I/libsuspend(  742): !@[s] autosuspend_autosleep_enable done
D/KeyguardUpdateMonitor( 1066): sendKeyguardVisibilityChanged(true)
D/PowerManagerService(  742): Excessive delay in mDisplayManagerService.blankAllDisplaysFromPowerManager(): 250ms
D/PowerManagerService(  742): SecHardwareInterface.setBatteryADC : false
I/PowerManagerService(  742): [PWL] Off : 0s ago
I/PowerManagerService(  742): [PWL]   PowerManagerService.WakeLocks: ref count=1
I/PowerManagerService(  742): [PWL]     mWakeLockSummary : 0x1
I/PowerManagerService(  742): [PWL]       PARTIAL_WAKE_LOCK              'MediaScannerService' (uid=10045, pid=1204, ws=null) (elapsedTime=573)
I/PowerManagerService(  742): [PWL]       PARTIAL_WAKE_LOCK              'StartingAlertService' (uid=10048, pid=1669, ws=null) (elapsedTime=548)
I/PowerManagerService(  742): [PWL]       PARTIAL_WAKE_LOCK              'ActivityManager-Sleep' (uid=1000, pid=742, ws=null) (elapsedTime=242)
I/PowerManagerService(  742): [PWL]   PowerManagerService.Broadcasts: ref count=1
I/WindowManager(  742): Screenshot max retries 4 of Token{42f6fe58 ActivityRecord{42f6fcd8 u0 com.sec.android.app.popupuireceiver/.BatteryCover t2}} appWin=Window{43053ac0 u0 com.sec.android.app.popupuireceiver/com.sec.android.app.popupuireceiver.BatteryCover} drawState=4
V/KeyguardUpdateMonitor( 1066): *** unregister callback for com.android.keyguard.sec.KeyguardSecurityViewOverlay$1@42649da8
W/WindowManager(  742): Screenshot failure taking screenshot for (720x1280) to layer 21005
V/ApplicationPolicy(  742): isApplicationStateBlocked userId 0 pkgname com.example.hello
D/CustomFrequencyManagerService(  742): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 742  pkgName : ACTIVITY_RESUME_BOOSTER@5
W/ActivityManager(  742): mDVFSHelper.acquire()
D/MediaScanner( 1204): OK. alarm_alert is already exist in setting DB.
D/LockPatternUtils( 1066): isPcwEnable = null
D/AndroidRuntime( 2850): Shutting down VM
D/MediaScanner( 1204): system notification_sound  : K_Oprkltf5wgg
D/MediaScanner( 1204): OK. notification_sound is already exist in setting DB.
D/MediaScanner( 1204): system ringtone  : Wmfi_lpf_pwirywu5wgg
D/MediaScanner( 1204): OK. ringtone is already exist in setting DB.
D/dalvikvm( 2850): GC_CONCURRENT freed 97K, 13% free 717K/816K, paused 1ms+1ms, total 3ms
D/NearbySettings( 1307): MountReceiver.onReceive - Create HandlerThread
D/NearbySettings( 1307): MountReceiver.onReceive - Start HandlerThread
D/NearbySettings( 1307): MountReceiver.onReceive - Create mPrefHandler
D/NearbySettings( 1307): MountReceiver.onReceive - ACTION: android.intent.action.BOOT_COMPLETED
V/NearbySettings( 1307): MountReceiver.mPrefHandler - 7002
I/SensorManagerA(  742): getReportingMode :: sensor.mType = 5
D/Sensors (  742): LightSensor setDelay = 200000000
D/Sensors (  742): LightSensor setSensorDelay = 200000000
D/Sensors (  742): Light sensor flush: not enabled 0
D/Sensors (  742): LightSensor enable = 1
D/Sensors (  742): LightSensor enableSensor = 1
I/NearbySettings( 1307): MountReceiver.onReceive - Path: (systemPath)/storage/emulated/0/Download, (internalPath)/storage/emulated/0/Download, (externalPath)/storage/extSdCard/Download
I/NearbySettings( 1307): MountReceiver.onReceive - Internal Path
D/LightsService(  742): [api] [SvcLED] setFlashing :: id = 3, color = 0, mode = 10, onMS = 0, offMS = 0,  (uid: 1000 pid: 742) 
D/LightsService(  742): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x0 -> 0x10 | SvcLED(id=3) set On
D/SensorManager(  742): registerListener :: 16, CM36686 Light Sensor, 200000, 0,  
D/MediaScanner( 1204): system ringtone_2  : Wmfi_lpf_pwirywu5wgg
D/MediaScanner( 1204): OK. ringtone_2 is already exist in setting DB.
D/MediaScanner( 1204): system notification_sound_2  : K_Oprkltf5wgg
D/MediaScanner( 1204): OK. notification_sound_2 is already exist in setting DB.
D/BatteryService(  742): turn on LED for charging
D/VibratorService(  742): JNI vibratorOff()
I/SELinux ( 2894): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 2894):  
V/KeyguardUpdateMonitor( 1066): *** unregister callback for com.android.keyguard.KeyguardHostView$2@4259fe48
E/KeyguardHostView( 1066): KeyguardHostView()
D/Launcher.HomeView( 1259): onStop
D/SurfaceWidgetClient$ISurfaceWidgetStub( 1443): [237392/5] Surface widget pause on instance = 1
D/accuweather( 1443): [KK AccuPhone]>>> SWW:224 [0:0] [SWW] onPause : instance = 1
D/SurfaceWidgetClient$ISurfaceWidgetStub( 1443): [237392/5] Surface widget visibility changed visibility = false on instance = 1
D/ContextualEventManager( 1066): setOnClickHandler()
D/accuweather( 1443): [KK AccuPhone]>>> SWW:239 [0:0] onPause : size = 0
D/accuweather( 1443): [KK AccuPhone]>>> SWW:517 [0:0]  unRegisterTTReceiver !! 
V/KeyguardHostView( 1066): mIsMultipleLockOn is false
D/KeyguardHostView( 1066): mIsVoiceUnlockOn=false
V/KeyguardHostView( 1066): Initial transport state: 1, pbstate=0
I/KeyguardEffectViewMain( 1066): *** KeyguardEffectView getInstance ***
D/LockPatternUtils( 1066): isPcwEnable = null
D/MediaScannerService( 1204): !@done scanning volume internal
D/accuweather( 1443): [KK AccuPhone]>>> WR:149 [0:0] onPause
D/accuweather( 1443): [KK AccuPhone]>>> SM:526 [0:0] onPause
W/InputMethodManagerService(  742): Ignoring setImeWindowStatus of uid 1000 token: null
D/ContextualEventContainer( 1066): ContextualEventContainer()
V/KeyguardUpdateMonitor( 1066): *** register callback for com.android.keyguard.KeyguardMessageArea$2@42507810
V/KeyguardUpdateMonitor( 1066): *** unregister callback for null
D/MediaScannerService( 1204): !@start scanning volume external: [/storage/emulated/0, /storage/extSdCard, /storage/Private, /storage/UsbDriveA, /storage/UsbDriveB, /storage/UsbDriveC, /storage/UsbDriveD, /storage/UsbDriveE, /storage/UsbDriveF]
D/ContextualEventContainer( 1066): onFinishInflate()
D/ContextualEventContainer( 1066): update()
I/SELinux ( 2894): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 2894):  
I/SELinux ( 2894):  
I/SELinux ( 2894): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 2894): [DEBUG] seapp_context_lookup: seinfoCategory = default
E/dalvikvm( 2894): >>>>> Normal User
E/dalvikvm( 2894): >>>>> com.example.hello [ userId:0 | appId:10181 ]
D/LockPatternUtils( 1066): isPcwEnable = null
E/SELinux ( 2894): [DEBUG] seapp_context_lookup: seinfoCategory = default
D/SurfaceWidgetView( 1259): destroyHardwareResources():1126188616
D/LockPatternUtils( 1066): isPcwEnable = null
D/LockPatternUtils( 1066): isPcwEnable = null
D/KeyguardHostView( 1066): mIsFMMEnabled = false, mIsCarrierLockEnabled = false, mIsCarrierLockPlusEnabled = false
D/LockPatternUtils( 1066): isPcwEnable = null
D/STATUSBAR-NotificationService(  742): ACTION_SCREEN_OFF
D/LightsService(  742): [api] [SvcLED] turnOff:: id = 4 (uid: 1000 pid: 742) 
D/LightsService(  742): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x10 -> 0x10 | SvcLED(id=4) set Off
I/SurfaceFlinger(  248): id=13 Removed CatteryCove (8/12)
D/audio_hw_primary(  253): adev_set_parameters: enter: screen_state=off
V/voice   (  253): voice_set_parameters: enter: screen_state=off
V/voice   (  253): voice_set_parameters: exit with code(-2)
V/msm8974_platform(  253): platform_set_parameters: enter: screen_state=off
V/msm8974_platform(  253): platform_set_parameters: exit with code(-2)
V/audio_hw_primary(  253): adev_set_parameters: exit
I/SurfaceFlinger(  248): id=13 Removed CatteryCove (-2/12)
I/SecExternalDisplayIntents_Java(  742): Intent Recieved ..  -android.intent.action.SCREEN_OFFBroadCast Map value - 18
V/KeyguardHostView( 1066): showPrimarySecurityScreen(turningOff=false)
I/MDPP    ( 1066): Property: Empty
D/KeyguardHostView( 1066): showSecurityScreen(None)
V/KeyguardHostView( 1066): inflating id = 2130903095
D/IpRemoteDisplayController(  742): intent received android.intent.action.SCREEN_OFF
D/IpRemoteDisplayController(  742): Bridge Server is not available
D/KeyguardUpdateMonitor( 1066): sendKeyguardVisibilityChanged(true)
D/SecuritySelectorView( 1066): explore by touch mode off
D/MediaProvider( 1204): savePlaylistTableInBulkDeleter started
D/PersonaManagerService(  742): ACTION_SCREEN_OFF onReceive
D/TimaKeyStoreProvider( 2894): in addTimaSignatureService
D/PersonaManagerServiceHandler(  742): MSG_ACTION_SCREEN_OFF called
D/TimaKeyStoreProvider( 2894): Cannot add TimaSignature Service, License check Failed
I/KeyguardEffectViewMain( 1066): *** KeyguardEffectView getInstance ***
I/AccessibilityManagerService(  742): setmDNIeNegative (false)
D/ActivityThread( 2894): Added TimaKesytore provider
I/KeyguardEffectViewMain( 1066): *** KeyguardEffectView getInstance ***
D/SecCameraShortcut( 1066): shortcutSetting:1
D/SecCameraShortcut( 1066): isKidsMode:false
D/SecCameraShortcut( 1066): isEmergencyMode:false
I/SurfaceFlinger(  248): id=7 Removed Mauncher (7/11)
I/SurfaceFlinger(  248): id=7 Removed Mauncher (-2/11)
D/KeyguardUpdateMonitor( 1066): sendKeyguardVisibilityChanged(true)
D/MediaProvider( 1204): savePlaylistTableInBulkDeleter started - audio_playlists_map_cache existed
D/TP/MmsSmsProvider( 1239): match 200:Elapsed time : 15.764 ms
D/LockPatternUtils( 1066): isPcwEnable = null
D/Launcher( 1259): onTrimMemory. Level: 20
D/MediaProvider( 1204): savePlaylistTableInBulkDeleter started - audio_playlists_map_cache is empty
I/SQLiteSecureOpenHelper( 2111): getWritableDatabase(pwd)
I/SQLiteSecureOpenHelper( 2111): getDatabaseLocked(b,b,pwd)...
D/LockPatternUtils( 1066): isPcwEnable = null
D/EmergencyButton( 1066): enabled = false, :0
W/Settings( 1307): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/LockPatternUtils( 1066): isPcwEnable = null
I/KeyguardEffectViewMain( 1066): *** KeyguardEffectView getInstance ***
D/MediaProvider( 1204): savePlaylistTableInBulkDeleter finished
D/MediaProvider( 1204): savePlaylistTableInBulkDeleter started
D/SecCameraShortcut( 1066): setCallback(): null
D/MediaProvider( 1204): savePlaylistTableInBulkDeleter started - audio_playlists_map_personal_cache existed
D/MediaProvider( 1204): savePlaylistTableInBulkDeleter started - audio_playlists_map_personal_cache is empty
D/KeyguardVoiceEngineThread( 1066): condition = 0
D/SecuritySelectorView( 1066): mIsAirViewEnabled =false
D/SecCameraShortcut( 1066): setCallback(): not null
D/SecuritySelectorView( 1066): hideBouncer mBouncerHelpText != null
D/SecCameraShortcut( 1066): setCallback(): not null
D/SecCameraShortcut( 1066): setCallback(): not null
D/SecuritySelectorView( 1066): hideBouncer mBouncerHelpText != null
D/KeyguardHostView( 1066): mKeyguardHelpOverlay : null
D/KeyguardHostView( 1066): AUTO_WIPE = false , IT Policy = false
D/ContextualEventManager( 1066): setOnClickHandler()
E/LSO     ( 1066): LSO Service is not yet ready!!!
V/KeyguardUpdateMonitor( 1066): *** register callback for com.android.keyguard.KeyguardHostView$2@42a339a0
V/KeyguardUpdateMonitor( 1066): *** unregister callback for null
V/KeyguardHostView( 1066): music state changed: 0
D/KeyguardProperties( 1066): isIgnoreNationalRoaming() = false
D/VisualEffectCircleUnlockEffect( 1066): KeyguardEffectViewNone : Constructor
D/VisualEffectCircleUnlockEffect( 1066): screenWidth : 720
D/VisualEffectCircleUnlockEffect( 1066): screenHeight : 1280
D/VisualEffectCircleUnlockEffect( 1066): ratio : 0.6666667
D/VisualEffectCircleUnlockEffect( 1066): Constructor
D/VisualEffectCircleUnlockEffect( 1066): arrowImageId = 2130837796
D/VisualEffectCircleUnlockEffect( 1066): circleUnlockMaxWidth = 576
D/VisualEffectCircleUnlockEffect( 1066): circleUnlockMinWidth = 172
D/VisualEffectCircleUnlockEffect( 1066): outerStrokeWidth = 2
D/VisualEffectCircleUnlockEffect( 1066): innerStrokeWidth = 4
D/VisualEffectCircleUnlockEffect( 1066): lockSequenceTotal = 30
D/Sensors (  742): LightSensor enable = 0
D/Sensors (  742): LightSensor enableSensor = 0
D/LightsService(  742): [SvcLED]  onSensorChanged::light value = 0
D/SensorManager(  742): unregisterListener ::   
D/lights  (  742): led_pattern : 1 +
D/MediaProvider( 1204): savePlaylistTableInBulkDeleter finished
,D/lights  (  742): led_pattern : 1 -
,V/KeyguardUpdateMonitor( 1066): *** register callback for com.android.keyguard.sec.KeyguardSecurityViewOverlay$1@425f75b0
,V/KeyguardUpdateMonitor( 1066): *** unregister callback for null
,V/KeyguardUpdateMonitor( 1066): *** register callback for com.android.keyguard.MSimCarrierText$1@42578db0
V/KeyguardUpdateMonitor( 1066): *** unregister callback for null
D/MSimCarrierText( 1066):  onRefreshCarrierInfo:: PLMN : nullSPN:null SUB: 0
,D/CarrierText( 1066): getCarrierTextForSimState: status = Normal
D/CarrierText( 1066): getCarrierTextForSimState: status = Normal
D/MSimCarrierText( 1066): updateCarrierText: text = 
,D/CarrierText( 1066): getCarrierTextForSimState: status = SimNotReady
D/CarrierText( 1066): getCarrierTextForSimState: status = Normal
,D/MSimCarrierText( 1066): updateCarrierText: text = 
,D/LightsService(  742): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
D/MSimCarrierText( 1066):  onRefreshCarrierInfo:: PLMN : nullSPN:null SUB: 1
D/CarrierText( 1066): getCarrierTextForSimState: status = SimNotReady
D/CarrierText( 1066): getCarrierTextForSimState: status = Normal
D/MSimCarrierText( 1066): updateCarrierText: text = 
D/CarrierText( 1066): getCarrierTextForSimState: status = SimNotReady
D/CarrierText( 1066): getCarrierTextForSimState: status = SimNotReady
D/MSimCarrierText( 1066): updateCarrierText: text = null
V/KeyguardUpdateMonitor( 1066): *** register callback for com.android.keyguard.EmergencyButton$1@425149d0
V/KeyguardUpdateMonitor( 1066): *** unregister callback for null
D/MediaScanner( 1204): Prescan. DB items number : 20 DB_FILES_NUMBER_CACHING_LIMITATION : 7000  Caching mode : true
D/LockPatternUtils( 1066): isPcwEnable = null
D/EmergencyButton( 1066): enabled = false, :0
D/SecCameraShortcut( 1066): setCallback(): not null
D/SecuritySelectorView( 1066): hideBouncer mBouncerHelpText != null
D/KeyguardViewManager( 1066): mWindowLayoutParams not null
D/KeyguardHostView( 1066): onRestoreInstanceState, transport=1
I/KeyguardEffectViewMain( 1066): *** KeyguardEffectView getInstance ***
D/VisualEffectParticleEffect( 1066): KeyguardEffectViewParticleSpace : reset
I/Choreographer( 1066): Skipped 33 frames!  The application may be doing too much work on its main thread.
,I/iu.UploadsManager( 1758): #reloadSettings(); account: -1; IU: disabled; IS: disabled; IS account: -1; photoWiFi: true; videoWiFi: true; roam: false; battery: true; size: STANDARD; maxMobile: 157286400
,D/BadgeProvider( 1340): query, [selection] : package='com.android.mms' AND class='com.android.mms.ui.ConversationComposer' AND extraData='base_extra_badge'
,I/SettingSearch/SearchIntentReceiver( 1307): action : android.intent.action.BOOT_COMPLETED
,I/SettingSearch/SearchIntentReceiver( 1307): search setting db init!!
,D/dalvikvm(  742): GC_EXPLICIT freed 1937K, 17% free 23014K/27684K, paused 6ms+13ms, total 168ms
,W/ContextImpl( 1307): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendOrderedBroadcast:1544 android.content.ContextWrapper.sendOrderedBroadcast:394 android.content.ContextWrapper.sendOrderedBroadcast:394 com.android.settings.settingssearch.SettingsSearchIntentReceiver.restoredb:40 com.android.settings.settingssearch.SettingsSearchIntentReceiver.onReceive:60 
D/KeyguardUpdateMonitor( 1066): sendKeyguardVisibilityChanged(true)
I/SettingSearch/SearchIntentReceiver( 1307): BOOT_COMPLETED call InitSerachDBThread thread start!
,D/KeyguardUpdateMonitor( 1066): handleKeyguardVisibilityChanged(1)
D/SignalClusterView_dual( 1066): wifi: VISIBLE sig=2130837979 act=2130837936
D/SignalClusterView_dual( 1066): mMobileDataState=0 mMobileDataState2=0
D/SignalClusterView_dual( 1066): apply() mSeparateMobileGroup=8
D/STATUSBAR-NetworkController_dual( 1066): refreshSignalCluster - setNWBoosterIndicators(false)
D/SignalClusterView_dual( 1066): wifi: VISIBLE sig=2130837979 act=2130837946
D/SignalClusterView_dual( 1066): mMobileDataState=0 mMobileDataState2=0
D/SignalClusterView_dual( 1066): apply() mSeparateMobileGroup=8
D/SignalClusterView_dual( 1066): wifi: VISIBLE sig=2130837979 act=2130837946
D/SignalClusterView_dual( 1066): mMobileDataState=0 mMobileDataState2=0
D/SignalClusterView_dual( 1066): apply() mSeparateMobileGroup=8
D/SignalClusterView_dual( 1066): wifi: VISIBLE sig=2130837979 act=2130837946
D/SignalClusterView_dual( 1066): mMobileDataState=0 mMobileDataState2=0
D/SignalClusterView_dual( 1066): apply() mSeparateMobileGroup=8
D/SignalClusterView_dual( 1066): wifi: VISIBLE sig=2130837979 act=2130837946
D/SignalClusterView_dual( 1066): mMobileDataState=0 mMobileDataState2=0
D/SignalClusterView_dual( 1066): apply() mSeparateMobileGroup=8
D/StatusBar.NetworkController_dual( 1066): mMobileLabelViews start
D/StatusBar.NetworkController_dual( 1066): mMobileLabelViews set mobileLabel[SIM_0] =
D/StatusBar.NetworkController_dual( 1066): mMobileLabelViews GONE
D/StatusBar.NetworkController_dual( 1066): mMobileLabelViews2 set mobileLabel[SIM_1] =
D/StatusBar.NetworkController_dual( 1066): mMobileLabelViews2 GONE
D/StatusBar.NetworkController_dual( 1066): mSingleMobileLabelViews set : simMode = 0
D/ContextualEventContainer( 1066): handleUpdate()
D/ContextualEventManager( 1066): getTopEventView()
,D/ContextualEventManager( 1066): getTopContextualEvent()
D/ContextualEventManager( 1066): top view = flightmode
I/KeyguardEffectViewMain( 1066): *** KeyguardEffectView getInstance ***
D/ContextualEventManager( 1066): getTopEventClass()
,D/ContextualEventManager( 1066): getTopContextualEvent()
D/ContextualEventManager( 1066): !isClockTop
D/ContextualEventManager( 1066): getTopEventClass()
,D/ContextualEventManager( 1066): getTopContextualEvent()
,D/ContextualEventManager( 1066): !isClockTop
D/ContextualEventManager( 1066): getTopEventClass()
,D/ContextualEventManager( 1066): getTopContextualEvent()
D/StatusBar.NetworkController_dual( 1066): mSingleMobileLabelViews set as slot1`s
D/STATUSBAR-NetworkController_dual( 1066): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
D/StatusBar.NetworkController_dual( 1066): mMobileLabelViews start
D/StatusBar.NetworkController_dual( 1066): mMobileLabelViews set mobileLabel[SIM_0] =
D/StatusBar.NetworkController_dual( 1066): mMobileLabelViews GONE
D/StatusBar.NetworkController_dual( 1066): mMobileLabelViews2 set mobileLabel[SIM_1] =
D/StatusBar.NetworkController_dual( 1066): mMobileLabelViews2 GONE
D/StatusBar.NetworkController_dual( 1066): mSingleMobileLabelViews set : simMode = 0
D/StatusBar.NetworkController_dual( 1066): mSingleMobileLabelViews set as slot1`s
D/UsbManager( 1066):  :::: isUsb30Available :: return = false from pid = 1066
,W/ActivityManager(  742): Permission Denial: getCurrentUser() from pid=2894, uid=10181 requires android.permission.INTERACT_ACROSS_USERS
,I/HarmonyEASService(  742): Updating for all 1
,D/Launcher.Model( 1259): reloadBadges entered.
D/BadgeProvider( 1340): sendNotify entered. [uri] : content://com.sec.badge/apps/2
D/BadgeProvider( 1340): sendNotify, [notify] : null
,D/BadgeProvider( 1340): update, [uri] : content://com.sec.badge/apps/2
D/BadgeProvider( 1340): update, [BadgeCount] : badgecount=0
,D/BadgeProvider( 1340): update, [UpdateCount] : 1
,V/MediaScanner( 1204): processDirectory :  /storage/emulated/0
D/MediaScanner( 1204): Skipping:
,D/MediaScanner( 1204): 7klwibgf7fvntblfd7(75ebcf7
,I/SELinux ( 2916): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 2916):  
,D/PhoneNumberLocatorBootCompletedReceiver( 1239): onReceive
,D/PhoneNumberLocatorBootCompletedReceiver( 1239): Phone number locator feature is dsiabled
,D/Mms/MessagingNotification( 1669): setBadgeCount(), count=0
,D/MessagingNotification( 1669): remove alarm
W/ActivityManager(  742): Permission Denial: getCurrentUser() from pid=2894, uid=10181 requires android.permission.INTERACT_ACROSS_USERS
,D/dalvikvm( 1066): GC_EXPLICIT freed 13480K, 33% free 31336K/46172K, paused 3ms+7ms, total 50ms
,D/KeyguardUpdateMonitor( 1066): handleKeyguardVisibilityChanged(1)
D/KeyguardUpdateMonitor( 1066): handleKeyguardVisibilityChanged(1)
D/MediaScanner( 1204): Skipping:
D/MediaScanner( 1204): 7klwibgf7fvntblfd7(7Budiwrd7dblb7
D/KeyguardUpdateMonitor( 1066): handleKeyguardVisibilityChanged(1)
D/KeyguardViewMediator( 1066): handleKeyguardDoneDrawing
V/MediaScanner( 1204): processDirectory :  /storage/extSdCard
W/MediaScanner( 1204): Error opening directory, reason : Permission denied.
W/MediaScanner( 1204): 7klwibgf7fxlKdCbid7
W/BackupManagerService(  742): dataChanged but no participant pkg='com.android.providers.settings' uid=1001
D/STATUSBAR-PhoneStatusBar( 1066): makeExpandedInvisible
D/PhoneStatusBarView( 1066): marqueeStatusBar:121, mClearCover:0
D/STATUSBAR-IconMerger( 1066): checkOverflow(288), More:false, Req:false Child:1
V/WebViewChromium( 2894): Binding Chromium to the background looper Looper (main, tid 1) {422d3330}
D/SecContextualClockFlightMode( 1066): handleUpdateClock()
E/File    ( 1204): fail readDirectory() errno=2
D/KeyguardProperties( 1066): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
I/chromium( 2894): [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
V/MediaScanner( 1204): pruneDeadThumbnailFiles... android.database.sqlite.SQLiteCursor@426de878
I/BrowserProcessMain( 2894): Initializing chromium process, renderers=0
V/MediaScanner( 1204): /pruneDeadThumbnailFiles... android.database.sqlite.SQLiteCursor@426de878
I/BootupListener( 1239): mPendingNetworkManualSelection : false
I/SELinux ( 2916): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 2916):  
I/SELinux ( 2916):  
I/SELinux ( 2916): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 2916): [DEBUG] seapp_context_lookup: seinfoCategory = release
E/dalvikvm( 2916): >>>>> Normal User
E/dalvikvm( 2916): >>>>> com.sec.providers.settingsearch [ userId:0 | appId:10160 ]
D/Mms/MessagingNotification( 1669): updateAllHistoryAsRead()
,E/SELinux ( 2916): [DEBUG] seapp_context_lookup: seinfoCategory = release
V/MediaScanner( 1204):  prescan time: 161ms (DB items: 20)
V/MediaScanner( 1204):     scan time: 47ms (Caching mode: true), (makeEntry time: 35ms ~74%),  (parsing time: 0ms ~0%),  (bitmapDecoding time: 0ms ~0%), (exifExtracting time : 0ms ~0%), (sefExtracting time : 0ms ~0%), (bulkInserter time : 0ms ~0%)
V/MediaScanner( 1204): postscan time: 11ms (bulkDeleter : 0), (delete DeadThumbnail time : 8ms)
V/MediaScanner( 1204):    total time: 219ms
,V/MediaScanner( 1204): checked files: 3  directories : 17  (I: 0, U: 0)
,I/ManualSelectionReceiver( 1239): onReceive : Intent = Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.android.phone/.ManualSelectionReceiver (has extras) }
D/MediaScannerService( 1204): !@done scanning volume external
,D/TimaKeyStoreProvider( 2916): in addTimaSignatureService
,D/TimaKeyStoreProvider( 2916): Cannot add TimaSignature Service, License check Failed
,W/chromium( 2894): [WARNING:proxy_service.cc(888)] PAC support disabled because there is no system implementation
,D/ActivityThread( 2916): Added TimaKesytore provider
,I/SELinux ( 2939): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 2939):  
,I/Adreno-EGL( 2894): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 2894): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 2894): Build Date: 03/21/14 Fri
I/Adreno-EGL( 2894): Local Branch: AU200+patches_03212014
I/Adreno-EGL( 2894): Remote Branch: 
I/Adreno-EGL( 2894): Local Patches: 
I/Adreno-EGL( 2894): Reconstruct Branch: 
D/MediaScannerService( 1204): send command to ssrm : REQ_DROP_CACHE
,D/SecKeyguardFlightModeView( 1066): received broadcast android.intent.action.SCREEN_OFF
,D/accuweather( 1443): [KK AccuPhone]>>> SWW:64 [0:0] action : androidintentactionSCREEN_OFF
D/accuweather( 1443): [KK AccuPhone]>>> SWW:440 [0:0] stopRefreshIcon : 1
,D/accuweather( 1443): [KK AccuPhone]>>> SWW:338 [0:0] getWeatherRenderer : 1
,I/SELinux ( 2939): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 2939):  
I/SELinux ( 2939):  
,I/SELinux ( 2939): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 2939): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 2939): >>>>> Normal User
E/dalvikvm( 2939): >>>>> com.wssyncmldm [ userId:0 | appId:1000 ]
D/LockPatternUtils( 1066): isPcwEnable = null
,E/SELinux ( 2939): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/PowerManagerService(  742): [PWL] sb release: PowerManagerService.Broadcasts
,D/Mms/SmsReceiverService( 1669): [end]    handleBootCompleted()
,D/TimaKeyStoreProvider( 2939): in addTimaSignatureService
,D/TimaKeyStoreProvider( 2939): Cannot add TimaSignature Service, License check Failed
,I/iu.UploadsManager( 1758): End new media; added: 0, uploading: 0, time: 298 ms
,D/ActivityThread( 2939): Added TimaKesytore provider
,E/SMD     (  242): DCD ON
,I/dalvikvm( 2894): Could not find method android.webkit.CookieManager.setAcceptThirdPartyCookies, referenced from method org.apache.cordova.engine.SystemCookieManager.<init>
,W/dalvikvm( 2894): VFY: unable to resolve virtual method 168: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
D/dalvikvm( 2894): VFY: replacing opcode 0x6e at 0x0016
I/dalvikvm( 2894): Could not find method android.webkit.CookieManager.flush, referenced from method org.apache.cordova.engine.SystemCookieManager.flush
W/dalvikvm( 2894): VFY: unable to resolve virtual method 163: Landroid/webkit/CookieManager;.flush ()V
,D/dalvikvm( 2894): VFY: replacing opcode 0x6e at 0x0008
,W/dalvikvm( 2894): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
,W/dalvikvm( 2894): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
I/dalvikvm( 2894): Could not find method android.webkit.WebViewClient.onReceivedClientCertRequest, referenced from method org.apache.cordova.engine.SystemWebViewClient.onReceivedClientCertRequest
W/dalvikvm( 2894): VFY: unable to resolve virtual method 221: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
,D/dalvikvm( 2894): VFY: replacing opcode 0x6f at 0x001a
,W/dalvikvm( 2894): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
I/dalvikvm( 2894): Could not find method android.webkit.PermissionRequest.getResources, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onPermissionRequest
W/dalvikvm( 2894): VFY: unable to resolve virtual method 179: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
,D/dalvikvm( 2894): VFY: replacing opcode 0x6e at 0x000d
I/dalvikvm( 2894): Could not find method android.webkit.WebChromeClient$FileChooserParams.createIntent, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onShowFileChooser
W/dalvikvm( 2894): VFY: unable to resolve virtual method 184: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
,D/dalvikvm( 2894): VFY: replacing opcode 0x6e at 0x0000
,D/SystemWebViewEngine( 2894): CordovaWebView is running on device made by: samsung
,W/ActivityManager(  742): Permission Denial: getCurrentUser() from pid=2916, uid=10160 requires android.permission.INTERACT_ACROSS_USERS
,I/DBG_DM  ( 2939): [][Line:95][onCreate] 
,E/DBG_DM  ( 2939): BootingfileStream is null
,E/DBG_DM  ( 2939): xdmCreateBootingFilestream
,D/SSRMv2:SIOP(  742): SIOP:: AP = 330, Delta = 0
,I/DBG_DM  ( 2939): [3.19.140541][Line:718][xdmGetCheckWifiOnlyModel] isWifiOnly : false
,I/DBG_DM  ( 2939): [3.19.140541][Line:744][xdmGetCheckDataOnly] Voice : true
,I/DBG_DM  ( 2939): [3.19.140541][Line:745][xdmGetCheckDataOnly] SMS : true
,I/DBG_DM  ( 2939): [3.19.140541][Line:746][xdmGetCheckDataOnly] isDataOnly : false
,I/SurfaceFlinger(  248): id=15 createSurf (1x1),1 flag=404, NainActivit
,D/AmoledAdjustTimer(  742): prevTemp = 283, currTemp = 287, prevStep = 4, currStep = 4
D/KeyguardUpdateMonitor( 1066): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1066): handleKeyguardVisibilityChanged(1)
,D/KeyguardUpdateMonitor( 1066): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1066): handleKeyguardVisibilityChanged(1)
,I/DBG_DM  ( 2939): [3.19.140541][Line:139][xdmCheckFeatureRoamingWifiOnly] get SecProductFeature
,I/HWUI    ( 2894): EGLImpl-HWUI Protected EGL context created
,I/DBG_DM  ( 2939): [3.19.140541][Line:154][xdmCheckFeatureRoamingUnableNetworkMsg] get SecProductFeature
,I/DBG_DM  ( 2939): [3.19.140541][Line:36][onCreate] myUserId : 0
,D/OpenGLRenderer( 2894): Enabling debug mode 0
,D/OpenGLRenderer( 2894): GL error from OpenGLRenderer: 0x502
,E/OpenGLRenderer( 2894):   GL_INVALID_OPERATION
,I/DBG_DM  ( 2939): [3.19.140541][Line:2663][xdmDbsqlGetFUMOStatus] xdbsqlGetFUMOStatus : 0
,D/KeyguardUpdateMonitor( 1066): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1066): handleKeyguardVisibilityChanged(1)
,D/CustomFrequencyManagerService(  742): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 742  pkgName : ACTIVITY_RESUME_BOOSTER@9
,D/CustomFrequencyManagerService(  742): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 742  tag : ACTIVITY_RESUME_BOOSTER@5
,D/CustomFrequencyManagerService(  742): FrequencyrequestList.getNextMaxCPUCoreRequest, index: 0
,I/DBG_DM  ( 2939): [3.19.140541][Line:2702][xdmdbsqlGetDownloadPostponeStatus] xdbsqlGetDownloadPostponeStatus : 0
,W/ActivityManager(  742): mDVFSHelper.release()
D/KeyguardUpdateMonitor( 1066): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1066): handleKeyguardVisibilityChanged(1)
,I/DBG_DM  ( 2939): [3.19.140541][Line:2586][xdmGetUpdateReport] wssGetUpdateReport : 0
,I/DBG_DM  ( 2939): [3.19.140541][Line:99][onCreate] DMApplication NOT Start !
,I/DBG_DM  ( 2939): [3.19.140541][Line:139][onReceive] android.intent.action.BOOT_COMPLETED
,D/OverheatReceiver( 1066): onReceive() getAction : android.intent.action.BOOT_COMPLETED
D/OverheatReceiver( 1066): into the SAFE_MODE_ACTION
,D/OverheatReceiver( 1066): VZW on -> change to Global UX [safe mode]
,D/OverheatReceiver( 1066): isSafeMode = false
,D/LocationManagerService(  742): getProviders()=[passive]
,I/ContactAccountLoggerTas( 2181): canRun() : Opted Out
,E/Tethering(  742): No numeric data
,E/Tethering(  742): No numeric data
,E/Tethering(  742): No numeric data
,E/Tethering(  742): No numeric data
I/ConnectivityService(  742): defaultVal : 1, tetherEnabledInSettings : true
I/ConnectivityService(  742): defaultVal : 1, tetherEnabledInSettings : true
I/ConnectivityService(  742): defaultVal : 1, tetherEnabledInSettings : true
I/ConnectivityService(  742): defaultVal : 1, tetherEnabledInSettings : true
,I/ConnectivityService(  742): defaultVal : 1, tetherEnabledInSettings : true
E/Tethering(  742): No numeric data
,E/Tethering(  742): No numeric data
I/ConnectivityService(  742): defaultVal : 1, tetherEnabledInSettings : true
,W/GAV2    ( 2181): Thread[Background Non-Blocking-0,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,W/GAV2    ( 2181): Thread[Background Non-Blocking-0,5,main]: dispatch call queued.  Need to call GAServiceManager.getInstance().initialize().
I/dalvikvm( 1311): Could not find method android.accounts.AccountManager.removeAccount, referenced from method com.google.android.gms.auth.o.a
W/dalvikvm( 1311): VFY: unable to resolve virtual method 15: Landroid/accounts/AccountManager;.removeAccount (Landroid/accounts/Account;Landroid/app/Activity;Landroid/accounts/AccountManagerCallback;Landroid/os/Handler;)Landroid/accounts/AccountManagerFuture;
,D/dalvikvm( 1311): VFY: replacing opcode 0x6e at 0x001c
,I/ContactAccountLoggerTas( 2181): canRun() : Opted Out
,W/dalvikvm( 2181): method Lcom/google/android/search/core/state/QueryState;.a incorrectly overrides package-private method with same name in Lcfl;
,V/GLSActivity( 1311): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1311): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/chromium( 2894): [INFO:CONSOLE(10)] "Viewport target-densitydpi is not supported.", source: file:///android_asset/www/index.html (10)
,E/Tethering(  742): No numeric data
,E/Tethering(  742): No numeric data
,E/Tethering(  742): No numeric data
,E/Tethering(  742): No numeric data
,V/NFC     ( 1307): this device does not have NFC support
V/NFC     ( 1307): this device does not have NFC support
V/NFC     ( 1307): this device does not have NFC support
,V/NFC     ( 1307): this device does not have NFC support
I/ConnectivityService(  742): defaultVal : 1, tetherEnabledInSettings : true
I/ConnectivityService(  742): defaultVal : 1, tetherEnabledInSettings : true
I/ConnectivityService(  742): defaultVal : 1, tetherEnabledInSettings : true
I/ConnectivityService(  742): defaultVal : 1, tetherEnabledInSettings : true
,E/AndroidProtocolHandler( 2894): Unable to open asset URL: file:///android_asset/www/jxcore.js
,V/VibratorService(  742): hasVibrator - useVibetonz: false
,D/WifiDisplayAdapter(  742): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,D/WifiDisplayAdapter(  742): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,I/AudioService(  742): getStreamVolume 3 index 0
,I/MediaRouter( 2181): Found default route: MediaRouter.RouteInfo{ uniqueId=android/kb:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=0, volumeMax=15, presentationDisplayId=-1, extras=null, providerPackageName=android }
,D/JsMessageQueue( 2894): Set native->JS mode to OnlineEventsBridgeMode
,D/WifiDisplayAdapter(  742): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,I/SELinux ( 3009): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 3009):  
,I/SELinux ( 3009): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 3009):  
I/SELinux ( 3009):  
,I/SELinux ( 3009): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 3009): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 3009): >>>>> Normal User
,E/dalvikvm( 3009): >>>>> com.samsung.android.intelligenceservice [ userId:0 | appId:10005 ]
,E/SELinux ( 3009): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/dalvikvm( 2894): Trying to load lib /data/app-lib/com.example.hello-3/libjxcore.so 0x425fa000
,D/TimaKeyStoreProvider( 3009): in addTimaSignatureService
,D/TimaKeyStoreProvider( 3009): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 3009): Added TimaKesytore provider
,I/dalvikvm( 1311): Could not find method android.accounts.AccountManager.removeAccountExplicitly, referenced from method com.google.android.gms.auth.be.p.a
W/dalvikvm( 1311): VFY: unable to resolve virtual method 16: Landroid/accounts/AccountManager;.removeAccountExplicitly (Landroid/accounts/Account;)Z
,D/dalvikvm( 1311): VFY: replacing opcode 0x6e at 0x001f
,D/dalvikvm( 2894): Added shared lib /data/app-lib/com.example.hello-3/libjxcore.so 0x425fa000
D/jxcore_app_log( 2894): JniHelper::setJavaVM(0x418194f8), pthread_self() = 1920922504
,D/JX-Cordova( 2894): jxcore cordova android initializing
,V/GLSActivity( 1311): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/dalvikvm( 1311): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 1311): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 1311): VFY: unable to find class referenced in signature (Landroid/net/Network;)
I/dalvikvm( 1311): Could not find method android.net.Network.openConnection, referenced from method com.google.android.gms.http.g.a
W/dalvikvm( 1311): VFY: unable to resolve virtual method 1007: Landroid/net/Network;.openConnection (Ljava/net/URL;)Ljava/net/URLConnection;
,D/dalvikvm( 1311): VFY: replacing opcode 0x6e at 0x00bb
,I/dalvikvm( 1311): Could not find method android.accounts.AccountManager.notifyAccountAuthenticated, referenced from method com.google.android.gms.auth.be.s.a
W/dalvikvm( 1311): VFY: unable to resolve virtual method 13: Landroid/accounts/AccountManager;.notifyAccountAuthenticated (Landroid/accounts/Account;)Z
,D/dalvikvm( 1311): VFY: replacing opcode 0x6e at 0x0041
,I/dalvikvm( 1311): Could not find method android.accounts.AccountManager.renameAccount, referenced from method com.google.android.gms.auth.be.account.a.b
W/dalvikvm( 1311): VFY: unable to resolve virtual method 17: Landroid/accounts/AccountManager;.renameAccount (Landroid/accounts/Account;Ljava/lang/String;Landroid/accounts/AccountManagerCallback;Landroid/os/Handler;)Landroid/accounts/AccountManagerFuture;
,D/dalvikvm( 1311): VFY: replacing opcode 0x6e at 0x0046
,I/LockPatternUtils( 1307): isSmartCardAuthenticationAvailable: false
,D/UserAnalysis.PlaceProvider( 3009): Create SecureDbHelper
,W/ActivityManager(  742): Permission Denial: getCurrentUser() from pid=3009, uid=10005 requires android.permission.INTERACT_ACROSS_USERS
D/UserAnalysis.UserAnalysisBroadcastReceiver( 3009): Create SecureDbHelper
,V/GLSActivity( 1311): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1311): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/SQLiteSecureOpenHelper( 3009): getReadableDatabase(pwd)
I/SQLiteSecureOpenHelper( 3009): getDatabaseLocked(b,b,pwd)...
,I/SQLiteSecureOpenHelper( 3009): Open Place.db in secure mode
W/jxcore-log( 2894): Initializing JXcore engine
,W/jxcore-log( 2894): JXcore engine is ready
,W/dalvikvm( 1311): VFY: unable to find class referenced in signature (Landroid/net/Network;)
E/dalvikvm( 1311): Could not find class 'android.net.Network', referenced from method com.google.android.gms.http.l.a
W/dalvikvm( 1311): VFY: unable to resolve check-cast 229 (Landroid/net/Network;) in Lcom/google/android/gms/http/l;
,D/dalvikvm( 1311): VFY: replacing opcode 0x1f at 0x0011
I/dalvikvm( 1311): Could not find method android.os.PowerManager.isInteractive, referenced from method com.google.android.gms.common.util.y.a
W/dalvikvm( 1311): VFY: unable to resolve virtual method 1378: Landroid/os/PowerManager;.isInteractive ()Z
,D/dalvikvm( 1311): VFY: replacing opcode 0x6e at 0x003d
,W/jxcore-log( 2894): Starting JXcore engine
,I/System.out( 1311): Thread-53(HTTPLog):isShipBuild true
,I/System.out( 1311): Thread-53(HTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,V/VibratorService(  742): hasVibrator - useVibetonz: false
,I/SQLiteSecureOpenHelper( 3009): ...getDatabaseLocked(b,b,pwd)
,D/SQLiteSecureOpenHelper( 3009): ...getDatabaseLocked(b,b,pwd)
,I/SQLiteSecureOpenHelper( 3009): getWritableDatabase(pwd)
,I/SQLiteSecureOpenHelper( 3009): getDatabaseLocked(b,b,pwd)...
,D/UserAnalysis.CarAnalyzer( 3009): Create SecureDbHelper
,I/SQLiteSecureOpenHelper( 3009): getWritableDatabase(pwd)
,I/SQLiteSecureOpenHelper( 3009): getDatabaseLocked(b,b,pwd)...
,I/SQLiteSecureOpenHelper( 3009): Open Place.db in secure mode
,D/CustomFrequencyManagerService(  742): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 742  tag : ACTIVITY_RESUME_BOOSTER@9
,I/SQLiteSecureOpenHelper( 3009): ...getDatabaseLocked(b,b,pwd)
,D/SQLiteSecureOpenHelper( 3009): ...getDatabaseLocked(b,b,pwd)
,I/LockPatternUtils( 1307): isSmartCardAuthenticationAvailable: false
,I/SELinux ( 3025): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 3025):  
,W/jxcore-log( 2894): Platform android
W/jxcore-log( 2894): 
,W/jxcore-log( 2894): Process ARCH arm
W/jxcore-log( 2894): 
,I/SELinux ( 3025): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 3025):  
I/SELinux ( 3025):  
,I/SELinux ( 3025): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 3025): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 3025): >>>>> Normal User
,E/dalvikvm( 3025): >>>>> com.samsung.android.scloud.backup [ userId:0 | appId:10060 ]
,E/SELinux ( 3025): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 3025): in addTimaSignatureService
,D/TimaKeyStoreProvider( 3025): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 3025): Added TimaKesytore provider
,I/jxcore-log( 2894): JXcore Cordova bridge is ready!
I/jxcore-log( 2894): 
,W/jxcore-log( 2894): JXcore engine is started
,I/dalvikvm( 1311): Could not find method android.os.PowerManager.isDeviceIdleMode, referenced from method com.google.android.gms.gcm.nts.a.c.b
,W/dalvikvm( 1311): VFY: unable to resolve virtual method 1473: Landroid/os/PowerManager;.isDeviceIdleMode ()Z
,D/dalvikvm( 1311): VFY: replacing opcode 0x6e at 0x000f
,D/GCM     ( 1311): COMPAT: Multi user not supported
,E/jxcore-log( 2894): >> samsung-SM-G800H
E/jxcore-log( 2894): 
,I/jxcore-log( 2894): Total memory 1454641152
I/jxcore-log( 2894): 
I/jxcore-log( 2894): Free memory 366694400
I/jxcore-log( 2894): 
I/jxcore-log( 2894): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 2894): 
,I/jxcore-log( 2894): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 2894): 
,I/jxcore-log( 2894): userPath [ 'rList-com.example.hello.MainActivity', 'www' ]
I/jxcore-log( 2894): 
,I/jxcore-log( 2894): Size 720 1280
I/jxcore-log( 2894): 
,I/jxcore-log( 2894): Screen Brightness 134
I/jxcore-log( 2894): 
,E/jxcore-log( 2894): Dummy Error Log.
E/jxcore-log( 2894): 
,D/PackageManager(  742): [MSG] MCS_UNBIND
I/PackageManager(  742): calling disconnectService()
,D/PackageManager(  742): Trying to unbind to DefaultContainerService
,I/ContactAccountLoggerTas( 2181): canRun() : Opted Out
,I/sCloudBackupApp( 3025): sCloudBackupApp Version Info : 3.7.3.KK_APP
,I/SELinux ( 3040): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 3040):  
,I/SELinux ( 3040): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 3040):  
I/SELinux ( 3040):  
,I/SELinux ( 3040): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 3040): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 3040): >>>>> Normal User
,E/dalvikvm( 3040): >>>>> com.samsung.android.scloud.sync [ userId:0 | appId:10062 ]
,E/SELinux ( 3040): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 3040): in addTimaSignatureService
,D/TimaKeyStoreProvider( 3040): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 3040): Added TimaKesytore provider
,I/SettingSearch/SearchIntentReceiver( 1307): InitSerachDBThread thread end!
W/ContextImpl( 1307): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendOrderedBroadcast:1544 android.content.ContextWrapper.sendOrderedBroadcast:394 android.content.ContextWrapper.sendOrderedBroadcast:394 com.android.settings.settingssearch.SettingsSearchIntentReceiver$InitSerachDBThread.run:129 <bottom of call stack> 
,W/ActivityManager(  742): Permission Denial: getCurrentUser() from pid=3040, uid=10062 requires android.permission.INTERACT_ACROSS_USERS
,I/SELinux ( 3054): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 3054):  
,I/ActivityManager(  742): Killing 1288:com.sec.android.provider.emergencymode/u0a96 (adj 15): empty #43
,W/BackupManagerService(  742): dataChanged but no participant pkg='com.android.providers.settings' uid=10062
,W/BackupManagerService(  742): dataChanged but no participant pkg='com.android.providers.settings' uid=10062
,I/SELinux ( 3054): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 3054):  
I/SELinux ( 3054):  
,I/SELinux ( 3054): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 3054): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 3054): >>>>> Normal User
,E/dalvikvm( 3054): >>>>> com.wssnps [ userId:0 | appId:1000 ]
,E/SELinux ( 3054): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 3054): in addTimaSignatureService
,D/TimaKeyStoreProvider( 3054): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 3054): Added TimaKesytore provider
,D/NPS_WSSNPS( 3054): [] android.intent.action.BOOT_COMPLETED
W/ContextImpl( 3054): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1857 android.content.ContextWrapper.startService:506 android.content.ContextWrapper.startService:506 com.wssnps.smlNpsReceiver.onReceive:380 android.app.ActivityThread.handleReceiver:2698 
,D/NPS_WSSNPS( 3054): [] Service onCreate!!
,I/SELinux ( 3069): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 3069):  
,D/NPS_WSSNPS( 3054): [] NpsServiceTask Start
,I/NPS_WSSNPS( 3054): [44.140541] loadCryptionkeyLibrary
,I/NPS_WSSNPS( 3054): [44.140541] FirstLoad Or Not Exist
,D/dalvikvm( 3054): Trying to load lib /data/data/com.wssnps/files/libCryptionkey.so 0x42601710
,D/dalvikvm( 3054): Added shared lib /data/data/com.wssnps/files/libCryptionkey.so 0x42601710
,D/NPS_WSSNPS( 3054): [44.140541] smlDBHelper
,I/NPS_WSSNPS( 3054): [44.140541] AsyncBulkFlagCheck
,I/NPS_WSSNPS( 3054): [44.140541] IsRemain_AsyncBulkCheck
,I/NPS_WSSNPS( 3054): [44.140541] IsRemain_Asyncing nothing
,D/NPS_WSSNPS( 3054): [44.140541] Service onDestroy
,I/NPS_WSSNPS( 3054): [44.140541] smlBRConfigurationDelete
,W/ContextImpl( 3054): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:1863 android.content.ContextWrapper.stopService:511 com.wssnps.smlNpsService$1.run:108 java.util.Timer$TimerImpl.run:284 <bottom of call stack> 
I/NPS_WSSNPS( 3054): [44.140541] smlBRMessageDelete
I/NPS_WSSNPS( 3054): [44.140541] smlBREmailDelete
I/NPS_WSSNPS( 3054): [44.140541] smlBRNetworkDelete
I/NPS_WSSNPS( 3054): [44.140541] smlBRCallLogDelete
I/NPS_WSSNPS( 3054): [44.140541] smlBRMiniDiaryDelete
I/NPS_WSSNPS( 3054): [44.140541] smlBRPenMemoMDelete
I/NPS_WSSNPS( 3054): [44.140541] smlBRSMemoDelete
I/NPS_WSSNPS( 3054): [44.140541] cpuBooster release : false
D/NPS_WSSNPS( 3054): [44.140541] dsServerSocket close
I/SELinux ( 3069): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 3069):  
I/SELinux ( 3069):  
I/SELinux ( 3069): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 3069): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 3069): >>>>> Normal User
,E/dalvikvm( 3069): >>>>> com.samsung.android.app.accesscontrol [ userId:0 | appId:10064 ]
,E/SELinux ( 3069): [DEBUG] seapp_context_lookup: seinfoCategory = platform
I/ActivityManager(  742): Killing 1275:com.android.printspooler/u0a144 (adj 15): empty #43
,D/TimaKeyStoreProvider( 3069): in addTimaSignatureService
,D/TimaKeyStoreProvider( 3069): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 3069): Added TimaKesytore provider
,I/SELinux ( 3085): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 3085):  
I/ActivityManager(  742): Killing 1717:com.sec.android.app.SecSetupWizard/1000 (adj 15): empty #43
,I/jxcore-log( 2894): getBuffer is called!!!!
I/jxcore-log( 2894): 
,I/SELinux ( 3085): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 3085):  
I/SELinux ( 3085):  
,I/SELinux ( 3085): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 3085): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 3085): >>>>> Normal User
,E/dalvikvm( 3085): >>>>> com.sec.android.app.FileShareServer [ userId:0 | appId:10069 ]
,E/SELinux ( 3085): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 3085): in addTimaSignatureService
,D/TimaKeyStoreProvider( 3085): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 3085): Added TimaKesytore provider
,D/FileShare-Server( 3085): ServerBroadcastReceiver.onReceive - action android.intent.action.BOOT_COMPLETED // null
,I/SELinux ( 3099): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 3099):  
,I/ActivityManager(  742): Killing 1732:com.sec.modem.settings/1000 (adj 15): empty #43
,I/SELinux ( 3099): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 3099):  
I/SELinux ( 3099):  
,I/SELinux ( 3099): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 3099): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 3099): >>>>> Normal User
,E/dalvikvm( 3099): >>>>> com.sec.android.nearby.mediaserver [ userId:0 | appId:10070 ]
,E/SELinux ( 3099): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 3099): in addTimaSignatureService
,D/TimaKeyStoreProvider( 3099): Cannot add TimaSignature Service, License check Failed
,I/ActivityManager(  742): Waited long enough for: ServiceRecord{43159088 u0 com.sec.android.daemonapp/.ap.accuweather.WeatherClockService}
D/ActivityThread( 3099): Added TimaKesytore provider
,I/AllShare(ASF-DMSLIB)( 3099): DMSReceiver.onReceive - android.intent.action.BOOT_COMPLETED
,W/BackupManagerService(  742): dataChanged but no participant pkg='com.android.providers.settings' uid=10070
,I/SELinux ( 3111): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 3111):  
,I/ActivityManager(  742): Killing 1744:com.sec.tcpdumpservice/1000 (adj 15): empty #43
,D/dalvikvm(  249): GC_EXPLICIT freed 45K, 50% free 9509K/18976K, paused 2ms+2ms, total 24ms
,D/dalvikvm(  249): GC_EXPLICIT freed <1K, 50% free 9509K/18976K, paused 1ms+2ms, total 18ms
,I/SELinux ( 3111): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 3111):  
I/SELinux ( 3111):  
,I/SELinux ( 3111): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 3111): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 3111): >>>>> Normal User
,E/dalvikvm( 3111): >>>>> com.samsung.android.app.assistantmenu [ userId:0 | appId:1000 ]
,E/SELinux ( 3111): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/dalvikvm(  249): GC_EXPLICIT freed <1K, 50% free 9509K/18976K, paused 2ms+3ms, total 18ms
,D/TimaKeyStoreProvider( 3111): in addTimaSignatureService
,D/TimaKeyStoreProvider( 3111): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 3111): Added TimaKesytore provider
,W/ContextImpl( 3111): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1857 android.content.ContextWrapper.startService:506 android.content.ContextWrapper.startService:506 com.samsung.android.app.assistantmenu.AssistantMenuReceiver.onReceive:61 android.app.ActivityThread.handleReceiver:2698 
,I/SELinux ( 3124): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 3124):  
,I/SELinux ( 3124): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 3124):  
I/SELinux ( 3124):  
,I/SELinux ( 3124): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 3124): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 3124): >>>>> Normal User
,E/dalvikvm( 3124): >>>>> com.sec.android.app.bluetoothtest [ userId:0 | appId:1000 ]
,E/SELinux ( 3124): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 3124): in addTimaSignatureService
D/TimaKeyStoreProvider( 3124): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 3124): Added TimaKesytore provider
,D/BluetoothBDAdrressReceiver( 3124): onReceive(), action: android.intent.action.BOOT_COMPLETED
,W/ContextImpl( 3124): Implicit intents with startService are not safe: Intent { act=com.bluetoothtestapp.BtBDstartservice.BootComplete } android.content.ContextWrapper.startService:506 android.content.ContextWrapper.startService:506 com.sec.android.app.bluetoothtest.BluetoothBDAdrressReceiver.onReceive:19 
W/ContextImpl( 3124): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1857 android.content.ContextWrapper.startService:506 android.content.ContextWrapper.startService:506 com.sec.android.app.bluetoothtest.BluetoothBDAdrressReceiver.onReceive:19 android.app.ActivityThread.handleReceiver:2698 
,I/SELinux ( 3136): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 3136):  
,I/ActivityManager(  742): Killing 1845:com.sec.android.widgetapp.activeapplicationwidget/u0a152 (adj 15): empty #43
D/BluetoothBDTestService( 1239): onCreate()
E/BluetoothBDTestService( 1239): onStart(), action: com.bluetoothtestapp.BtBDstartservice.BootComplete
E/BluetoothBDTestService( 1239): bd_address_path: /efs/bluetooth/bt_addr
E/BluetoothBDTestService( 1239): already exist!( /efs/bluetooth/bt_addr ), file length: 17
,I/SELinux ( 3136): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 3136):  
I/SELinux ( 3136):  
,I/SELinux ( 3136): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 3136): [DEBUG] seapp_context_lookup: seinfoCategory = default
E/dalvikvm( 3136): >>>>> Normal User
,E/dalvikvm( 3136): >>>>> com.blurb.checkout [ userId:0 | appId:10075 ]
,E/SELinux ( 3136): [DEBUG] seapp_context_lookup: seinfoCategory = default
,D/TimaKeyStoreProvider( 3136): in addTimaSignatureService
,D/TimaKeyStoreProvider( 3136): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 3136): Added TimaKesytore provider
,W/ActivityManager(  742): Permission Denial: getCurrentUser() from pid=3136, uid=10075 requires android.permission.INTERACT_ACROSS_USERS
,D/CaptivePortalTracker(  742): DelayedCaptiveCheckState{ when=-10ms what=2 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  742): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,I/SELinux ( 3149): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 3149):  
I/ActivityManager(  742): Killing 1690:com.sec.android.app.mt/1000 (adj 15): empty #43
,E/SMD     (  242): DCD ON
,D/CaptivePortalTracker(  742): Checking http://216.58.209.46/generate_204
W/ActivityThread(  742): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,I/SELinux ( 3149): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 3149):  
I/SELinux ( 3149):  
,I/SELinux ( 3149): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 3149): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 3149): >>>>> Normal User
,E/dalvikvm( 3149): >>>>> com.sec.knox.bridge [ userId:0 | appId:1000 ]
,E/SELinux ( 3149): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 3149): in addTimaSignatureService
,D/TimaKeyStoreProvider( 3149): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 3149): Added TimaKesytore provider
,I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.sec.android.gallery3d.app.GalleryActivity
,I/AMMetaDataParserService( 3111): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3111): getResourcePackageName:android.app.searchable
,I/AMMetaDataParserService( 3111): Resource data:2131165197
I/System.out(  742): Thread-164(HTTPLog):isShipBuild true
,I/System.out(  742): Thread-164(HTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,I/AMMetaDataParserService( 3111): getResourceName:com.sec.android.gallery3d:xml/gallery_searchable
,I/AMMetaDataParserService( 3111): getResourceTypeNamexml
,I/AMMetaDataParserService( 3111): getResourcePackageName:assistant
,I/AMMetaDataParserService( 3111): Resource data:2131165194
I/AMMetaDataParserService( 3111): getResourceName:com.sec.android.gallery3d:xml/assistant
,I/AMMetaDataParserService( 3111): getResourceTypeNamexml
,E/PersonaManagerService(  742): returning null in  getPersonasForUser
,D/CaptivePortalTracker(  742): Don't send network conditions - lacking user consent.
,D/CaptivePortalTracker(  742): isCaptivePortal: ret=false rspCode=204
D/CaptivePortalTracker(  742): Not captive network NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/CaptivePortalTracker(  742): notifyPortalCheckCompleted: captive=false ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService(  742): captivePortalCheckCompleted: ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false captive=false
,I/AMMetaDataParserService( 3111): Icon data: ResourceDrawer2131624995android.intent.action.drawer2130837586
,I/SELinux ( 3166): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 3166):  
I/ActivityManager(  742): Killing 1920:com.sec.phone/1001 (adj 15): empty #43
,I/AMMetaDataParserService( 3111): Icon data: ResourceSlideshow2131624009android.intent.action.slideshow2130837584
,I/SELinux ( 3166): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 3166):  
I/SELinux ( 3166):  
,I/SELinux ( 3166): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 3166): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 3166): >>>>> Normal User
,E/dalvikvm( 3166): >>>>> com.sec.android.app.clockpackage [ userId:0 | appId:10084 ]
,E/SELinux ( 3166): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 3166): in addTimaSignatureService
,D/TimaKeyStoreProvider( 3166): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 3166): Added TimaKesytore provider
,I/AMMetaDataParserService( 3111): Icon data: ResourceCamera2131624012android.intent.action.camera2130837583
,I/AMMetaDataParserService( 3111): Icon data: ResourceDelete2131624000android.intent.action.delete2130837585
,I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.cooliris.media.Gallery
,I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.sec.android.gallery3d.app.Gallery
I/AMMetaDataParserService( 3111): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3111): getResourcePackageName:assistant
,I/AMMetaDataParserService( 3111): Resource data:2131165194
I/AMMetaDataParserService( 3111): getResourceName:com.sec.android.gallery3d:xml/assistant
,I/AMMetaDataParserService( 3111): getResourceTypeNamexml
,I/AMMetaDataParserService( 3111): Icon data: ResourceDrawer2131624995android.intent.action.drawer2130837586
,I/AMMetaDataParserService( 3111): Icon data: ResourceSlideshow2131624009android.intent.action.slideshow2130837584
,I/AMMetaDataParserService( 3111): Icon data: ResourceCamera2131624012android.intent.action.camera2130837583
,I/AMMetaDataParserService( 3111): Icon data: ResourceDelete2131624000android.intent.action.delete2130837585
,I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.sec.android.gallery3d.app.UsbDeviceActivity
,I/AMMetaDataParserService( 3111): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3111): getResourcePackageName:android.hardware.usb.action.USB_DEVICE_ATTACHED
,I/AMMetaDataParserService( 3111): Resource data:2131165195
,I/AMMetaDataParserService( 3111): getResourceName:com.sec.android.gallery3d:xml/device_filter
I/AMMetaDataParserService( 3111): getResourceTypeNamexml
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.sec.android.gallery3d.app.Wallpaper
,I/AMMetaDataParserService( 3111): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3111): getResourcePackageName:android.wallpaper.preview
,I/AMMetaDataParserService( 3111): Resource data:2131165204
I/AMMetaDataParserService( 3111): getResourceName:com.sec.android.gallery3d:xml/wallpaper_picker_preview
,I/AMMetaDataParserService( 3111): getResourceTypeNamexml
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.sec.android.gallery3d.app.LockScreen
I/AMMetaDataParserService( 3111): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3111): getResourcePackageName:android.wallpaper.preview
,I/AMMetaDataParserService( 3111): Resource data:2131165204
,I/AMMetaDataParserService( 3111): getResourceName:com.sec.android.gallery3d:xml/wallpaper_picker_preview
I/AMMetaDataParserService( 3111): getResourceTypeNamexml
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.sec.android.gallery3d.app.BothScreen
,I/AMMetaDataParserService( 3111): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3111): getResourcePackageName:android.wallpaper.preview
,I/AMMetaDataParserService( 3111): Resource data:2131165204
I/AMMetaDataParserService( 3111): getResourceName:com.sec.android.gallery3d:xml/wallpaper_picker_preview
,I/AMMetaDataParserService( 3111): getResourceTypeNamexml
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.sec.android.gallery3d.app.TrimVideo
,I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.sec.android.gallery3d.app.CropImage
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.sec.android.gallery3d.app.ContextualTagSetting
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.sec.android.gallery3d.app.ContextualTagWeatherSetting
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.sec.samsung.gallery.view.gallerysearch.DeleteHistoryForGallerySearchActivity
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.sec.samsung.gallery.view.usertag.AddUserTagListActivity
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.sec.samsung.gallery.view.detailview.moreinfo.MoreInfoLocationEditActivity
,I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.sec.android.gallery3d.settings.GallerySettings
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.sec.android.gallery3d.gadget.WidgetTypeChooser
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.sec.android.gallery3d.gadget.WidgetClickHandler
,I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.sec.android.gallery3d.gadget.WidgetConfigure
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.sec.android.gallery3d.gadget.MagazineWidgetConfigure
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.sec.android.gallery3d.gadget.EasyWidgetConfigure
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.sec.android.gallery3d.gadget.WidgetPreferenceActivity
,I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.sec.android.gallery3d.gadget.MagazineWidgetPreferenceActivity
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.sec.android.gallery3d.settings.AccountSettingActivity
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.sec.android.gallery3d.settings.FilterbySettingActivity
,I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.sec.gallery2d.viewstate.MapView2dPage
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.sec.samsung.gallery.app.imagenote.ImageNote
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.sec.samsung.gallery.app.photonote.PhotoNote
,I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.sec.samsung.gallery.controller.StartMmsSaveCmd$CallMmsSave
,I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.mms.ui.RoamingGuardPopupActivity
,I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.mms.ui.AutoRetrievePreferenceActivity
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.mms.ui.AutoRetrieveTabActivity
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.mms.ui.ConversationComposer
I/AMMetaDataParserService( 3111): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3111): getResourcePackageName:android.app.spellscroll
,I/AMMetaDataParserService( 3111): Resource data:2131099676
,I/AMMetaDataParserService( 3111): getResourceName:com.android.mms:xml/spellscroll
,I/AMMetaDataParserService( 3111): getResourceTypeNamexml
,D/dalvikvm(  742): GC_EXPLICIT freed 1843K, 17% free 23230K/27684K, paused 4ms+9ms, total 119ms
,I/AMMetaDataParserService( 3111): getResourcePackageName:android.app.default_searchable
I/AMMetaDataParserService( 3111): getResourcePackageName:assistant
,I/AMMetaDataParserService( 3111): Resource data:2131099648
,I/AMMetaDataParserService( 3111): getResourceName:com.android.mms:xml/assistant_messaging
,I/AMMetaDataParserService( 3111): getResourceTypeNamexml
,I/AMMetaDataParserService( 3111): Icon data: ResourceSearch2131493233com.android.mms.ui.conversationlistfragment.searchmessages2130837516
W/BackupManagerService(  742): dataChanged but no participant pkg='com.android.providers.settings' uid=10084
,I/AMMetaDataParserService( 3111): Icon data: ResourceCompose2131492866com.android.mms.ui.conversationlistfragment.composemessage2130837515
V/AlarmManager(  742): waitForAlarm result :4
V/AlarmManager(  742): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,I/AMMetaDataParserService( 3111): Icon data: ResourceAdd from contacts2131493281com.android.mms.ui.composemessagefragment.attachcontacts2130837512
,I/AMMetaDataParserService( 3111): Icon data: ResourceCall2131493971com.android.mms.ui.composemessagefragment.calltocontact2130837513
,I/SELinux ( 3184): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 3184):  
I/ActivityManager(  742): Killing 2035:com.google.android.configupdater/u0a3 (adj 15): empty #43
,I/AMMetaDataParserService( 3111): Icon data: ResourceDelete2131492988com.android.mms.ui.composemessagefragment.delete2130837514
,I/AMMetaDataParserService( 3111): Icon data: ResourceSend2131492905com.android.mms.ui.composemessagefragment.send2130837517
W/ContextImpl(  742): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,I/SELinux ( 3184): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 3184):  
I/SELinux ( 3184):  
,I/SELinux ( 3184): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 3184): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 3184): >>>>> Normal User
,E/dalvikvm( 3184): >>>>> com.samsung.android.app.colorblind [ userId:0 | appId:1000 ]
,I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.mms.ui.ComposeMessageActivityNoLockScreen
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.mms.ui.ComposeMessageMms
E/SELinux ( 3184): [DEBUG] seapp_context_lookup: seinfoCategory = platform
I/AMMetaDataParserService( 3111): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3111): getResourcePackageName:assistant
,I/AMMetaDataParserService( 3111): Resource data:2131099648
I/AMMetaDataParserService( 3111): getResourceName:com.android.mms:xml/assistant_messaging
,I/AMMetaDataParserService( 3111): getResourceTypeNamexml
,I/AMMetaDataParserService( 3111): Icon data: ResourceSearch2131493233com.android.mms.ui.conversationlistfragment.searchmessages2130837516
,D/TimaKeyStoreProvider( 3184): in addTimaSignatureService
,D/TimaKeyStoreProvider( 3184): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 3184): Added TimaKesytore provider
,I/AMMetaDataParserService( 3111): Icon data: ResourceCompose2131492866com.android.mms.ui.conversationlistfragment.composemessage2130837515
,I/AMMetaDataParserService( 3111): Icon data: ResourceAdd from contacts2131493281com.android.mms.ui.composemessagefragment.attachcontacts2130837512
,I/AMMetaDataParserService( 3111): Icon data: ResourceCall2131493971com.android.mms.ui.composemessagefragment.calltocontact2130837513
,I/SELinux ( 3196): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 3196):  
I/ActivityManager(  742): Killing 2154:com.sec.dsm.system/1000 (adj 15): empty #43
,I/AMMetaDataParserService( 3111): Icon data: ResourceDelete2131492988com.android.mms.ui.composemessagefragment.delete2130837514
,I/SELinux ( 3196): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 3196):  
I/SELinux ( 3196):  
,I/SELinux ( 3196): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 3196): [DEBUG] seapp_context_lookup: seinfoCategory = default
E/dalvikvm( 3196): >>>>> Normal User
,E/dalvikvm( 3196): >>>>> com.dropbox.android [ userId:0 | appId:10091 ]
E/SELinux ( 3196): [DEBUG] seapp_context_lookup: seinfoCategory = default
,I/AMMetaDataParserService( 3111): Icon data: ResourceSend2131492905com.android.mms.ui.composemessagefragment.send2130837517
,I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.mms.ui.CbConfigPreferenceActivity
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.mms.ui.CbSettingTabActivity
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.mms.ui.ComposeMessage
I/AMMetaDataParserService( 3111): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3111): getResourcePackageName:assistant
,I/AMMetaDataParserService( 3111): Resource data:2131099648
I/AMMetaDataParserService( 3111): getResourceName:com.android.mms:xml/assistant_messaging
,I/AMMetaDataParserService( 3111): getResourceTypeNamexml
D/TimaKeyStoreProvider( 3196): in addTimaSignatureService
D/TimaKeyStoreProvider( 3196): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 3196): Added TimaKesytore provider
,I/AMMetaDataParserService( 3111): Icon data: ResourceSearch2131493233com.android.mms.ui.conversationlistfragment.searchmessages2130837516
,I/AMMetaDataParserService( 3111): Icon data: ResourceCompose2131492866com.android.mms.ui.conversationlistfragment.composemessage2130837515
,I/AMMetaDataParserService( 3111): Icon data: ResourceAdd from contacts2131493281com.android.mms.ui.composemessagefragment.attachcontacts2130837512
,I/AMMetaDataParserService( 3111): Icon data: ResourceCall2131493971com.android.mms.ui.composemessagefragment.calltocontact2130837513
,I/AMMetaDataParserService( 3111): Icon data: ResourceDelete2131492988com.android.mms.ui.composemessagefragment.delete2130837514
,I/AMMetaDataParserService( 3111): Icon data: ResourceSend2131492905com.android.mms.ui.composemessagefragment.send2130837517
,I/com.dropbox.android.service.DropboxNetworkReceiver( 3196): Setting receiver enabled: false
,I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.mms.ui.ForwardMessageActivity
,I/AMMetaDataParserService( 3111): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3111): getResourcePackageName:assistant
,I/AMMetaDataParserService( 3111): Resource data:2131099648
I/AMMetaDataParserService( 3111): getResourceName:com.android.mms:xml/assistant_messaging
,I/AMMetaDataParserService( 3111): getResourceTypeNamexml
,I/AMMetaDataParserService( 3111): Icon data: ResourceSearch2131493233com.android.mms.ui.conversationlistfragment.searchmessages2130837516
,I/com.dropbox.sync.android.a( 3196): Prepared cache dir '/data/data/com.dropbox.android/app_DropboxSyncCache/hizqkiq3952astb'.
,I/AMMetaDataParserService( 3111): Icon data: ResourceCompose2131492866com.android.mms.ui.conversationlistfragment.composemessage2130837515
,I/com.dropbox.sync.android.aa( 3196): Dropbox initialized for application: hizqkiq3952astb (com.dropbox.android/231222 DropboxSync/2.0.2 (Android; 4.4.2; samsung SM-G800H armeabi-v7a; en_US))
,I/AMMetaDataParserService( 3111): Icon data: ResourceAdd from contacts2131493281com.android.mms.ui.composemessagefragment.attachcontacts2130837512
W/ActivityManager(  742): Permission Denial: getCurrentUser() from pid=3196, uid=10091 requires android.permission.INTERACT_ACROSS_USERS
,I/AMMetaDataParserService( 3111): Icon data: ResourceCall2131493971com.android.mms.ui.composemessagefragment.calltocontact2130837513
,I/SELinux ( 3217): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 3217):  
I/ActivityManager(  742): Killing 2214:com.sec.android.app.factorykeystring/1000 (adj 15): empty #43
,I/AMMetaDataParserService( 3111): Icon data: ResourceDelete2131492988com.android.mms.ui.composemessagefragment.delete2130837514
,I/SELinux ( 3217): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 3217):  
I/SELinux ( 3217):  
,I/SELinux ( 3217): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 3217): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 3217): >>>>> Normal User
,E/dalvikvm( 3217): >>>>> com.sec.esdk.elm [ userId:0 | appId:10094 ]
,E/SELinux ( 3217): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,I/AMMetaDataParserService( 3111): Icon data: ResourceSend2131492905com.android.mms.ui.composemessagefragment.send2130837517
,D/TimaKeyStoreProvider( 3217): in addTimaSignatureService
,D/TimaKeyStoreProvider( 3217): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 3217): Added TimaKesytore provider
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.mms.ui.ReplyMessageActivity
I/AMMetaDataParserService( 3111): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3111): getResourcePackageName:assistant
,I/AMMetaDataParserService( 3111): Resource data:2131099648
I/AMMetaDataParserService( 3111): getResourceName:com.android.mms:xml/assistant_messaging
,I/AMMetaDataParserService( 3111): getResourceTypeNamexml
,I/AMMetaDataParserService( 3111): Icon data: ResourceSearch2131493233com.android.mms.ui.conversationlistfragment.searchmessages2130837516
,I/AMMetaDataParserService( 3111): Icon data: ResourceCompose2131492866com.android.mms.ui.conversationlistfragment.composemessage2130837515
W/ActivityManager(  742): Permission Denial: getCurrentUser() from pid=3217, uid=10094 requires android.permission.INTERACT_ACROSS_USERS
,D/elm:14132( 3217): ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
,D/elm:14132( 3217): ELMEngine.ELMEngine( context ).
,D/elm:14132( 3217): MDMBridge.setEnterpriseBridge()
D/elm:14132( 3217): ELMAbstractReceiver : Receive Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
D/elm:14132( 3217): ElmAgentService : onCreate()
D/elm:14132( 3217): ElmAgentService : onHandleIntent() Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
D/elm:14132( 3217): ELMEngine.ServiceHandler.handleMessage( BOOT_COMPLETED ). 
D/elm:14132( 3217): BootCompletedState : startBootCompleted() call
,D/elm:14132( 3217): ModuleBase.resetCalllogAPIAlarm()
,I/SELinux ( 3232): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 3232):  
,D/elm:14132( 3217): MDMBridge.getAllLicenseInfoFromSDK()
,I/elm:14132( 3217): Get License : 0
,D/elm:14132( 3217): ElmAgentService : onDestroy().
,I/ActivityManager(  742): Killing 2218:com.sec.kidsplat.installer/u0a158 (adj 15): empty #43
I/AMMetaDataParserService( 3111): Icon data: ResourceAdd from contacts2131493281com.android.mms.ui.composemessagefragment.attachcontacts2130837512
,I/PowerManagerService(  742): [PWL] Off : 5s ago
,I/PowerManagerService(  742): [PWL]   PowerManagerService.WakeLocks: ref count=1
I/PowerManagerService(  742): [PWL]     mWakeLockSummary : 0x1
,I/PowerManagerService(  742): [PWL]       PARTIAL_WAKE_LOCK              'AlarmReceiver' (uid=10084, pid=3166, ws=null) (elapsedTime=788)
,I/PowerManagerService(  742): [PWL]       PARTIAL_WAKE_LOCK              'AlarmManager' (uid=1000, pid=742, ws=WorkSource{10044}) (elapsedTime=730)
I/AMMetaDataParserService( 3111): Icon data: ResourceCall2131493971com.android.mms.ui.composemessagefragment.calltocontact2130837513
,I/SELinux ( 3232): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 3232):  
I/SELinux ( 3232):  
,I/SELinux ( 3232): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 3232): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 3232): >>>>> Normal User
,E/dalvikvm( 3232): >>>>> com.sec.android.fwupgrade [ userId:0 | appId:1000 ]
,E/SELinux ( 3232): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 3232): in addTimaSignatureService
,I/AMMetaDataParserService( 3111): Icon data: ResourceDelete2131492988com.android.mms.ui.composemessagefragment.delete2130837514
,D/TimaKeyStoreProvider( 3232): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 3232): Added TimaKesytore provider
,I/AMMetaDataParserService( 3111): Icon data: ResourceSend2131492905com.android.mms.ui.composemessagefragment.send2130837517
,I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.mms.ui.ConversationList
,I/AMMetaDataParserService( 3111): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3111): getResourcePackageName:assistant
,I/AMMetaDataParserService( 3111): Resource data:2131099648
,I/AMMetaDataParserService( 3111): getResourceName:com.android.mms:xml/assistant_messaging
,I/AMMetaDataParserService( 3111): getResourceTypeNamexml
,I/System.out( 3196): Thread-269(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
I/System.out( 3196): Thread-269(ApacheHTTPLog):isShipBuild true
I/System.out( 3196): Thread-269(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,I/AMMetaDataParserService( 3111): Icon data: ResourceSearch2131493233com.android.mms.ui.conversationlistfragment.searchmessages2130837516
,I/SELinux ( 3246): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 3246):  
I/ActivityManager(  742): Killing 2253:com.sec.factory/1000 (adj 15): empty #43
,I/AMMetaDataParserService( 3111): Icon data: ResourceCompose2131492866com.android.mms.ui.conversationlistfragment.composemessage2130837515
,I/AMMetaDataParserService( 3111): Icon data: ResourceAdd from contacts2131493281com.android.mms.ui.composemessagefragment.attachcontacts2130837512
I/SELinux ( 3246): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 3246):  
I/SELinux ( 3246):  
,I/SELinux ( 3246): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 3246): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 3246): >>>>> Normal User
,E/dalvikvm( 3246): >>>>> com.sec.factory.camera [ userId:0 | appId:1000 ]
,E/SELinux ( 3246): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,I/AMMetaDataParserService( 3111): Icon data: ResourceCall2131493971com.android.mms.ui.composemessagefragment.calltocontact2130837513
,D/TimaKeyStoreProvider( 3246): in addTimaSignatureService
,D/TimaKeyStoreProvider( 3246): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 3246): Added TimaKesytore provider
,I/AMMetaDataParserService( 3111): Icon data: ResourceDelete2131492988com.android.mms.ui.composemessagefragment.delete2130837514
,I/AMMetaDataParserService( 3111): Icon data: ResourceSend2131492905com.android.mms.ui.composemessagefragment.send2130837517
,I/CameraApp( 3246): CameraApp.onCreate()... mFeature : null
,I/testFeature( 3246): Feature.Feature(context)
I/testFeature( 3246): Feature.readInternalDefaultXml()
,I/testFeature( 3246): ResetFeatureValue
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.mms.ui.DeliveryReportActivity
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.mms.ui.WarnOfStorageLimitsActivity
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.mms.ui.SlideshowActivity
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.mms.ui.MmsSinglePageActivity
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.mms.ui.ClassZeroActivity
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.mms.ui.RetryActivity
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.mms.ui.MessagingPreferenceActivity
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.mms.settings.EntrancePrefActivity
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.mms.settings.DisplaySettings
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.mms.settings.CMASSettings
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.mms.settings.TextMessagesSettings
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.mms.settings.MultimediamessagesSettings
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.mms.settings.DeleteoldMessagesSettings
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.mms.settings.PushMessagesSettings
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.mms.settings.NotificationSettings
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.mms.settings.NotificationSettingsDS
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.mms.settings.SignatureSettings
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.mms.settings.SpamSettings
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.mms.settings.SafemodeSettings
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.mms.settings.DelaySendingSettings
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.mms.settings.MessageSmscActivityDS
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.mms.settings.SignatureEditActivity
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.mms.settings.PreviewsMessagesSettings
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.mms.settings.QuickReplySettings
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.mms.settings.CallbackNumberSettings
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.mms.settings.CallbackNumberEditActivity
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.mms.settings.BackgroundStyle
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.mms.settings.BubbleStyle
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.mms.ui.PushMessageDialog
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.samsung.mms.ui.SaveThreadActivity
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.samsung.mms.ui.SavedMsgsList
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.samsung.mms.ui.RestorePreviewActivity
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.samsung.mms.ui.ConversationListRestore
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.mms.ui.ManageSimMessages
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom,.android.mms.ui.MmsRetryActivity
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.mms.ui.ConfirmRateLimitActivity
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.mms.ui.SearchActivity
I/AMMetaDataParserService( 3111): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3111): getResourcePackageName:android.app.searchable
,I/AMMetaDataParserService( 3111): Resource data:2131099671
,I/AMMetaDataParserService( 3111): getResourceName:com.android.mms:xml/searchable
I/AMMetaDataParserService( 3111): getResourceTypeNamexml
,I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.mms.ui.SmsViewerActivity
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.mms.ui.MmsNotificationViewerActivity
,I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.mms.ui.DrmContentsActivity
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.mms.ui.CMASPreferenceActivity
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.mms.ui.CMASDialog
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.mms.ui.CMASDialog_single_top
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.mms.ui.PDPResetDialog
,I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.mms.ui.CMASUserPromptDialog
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.mms.ui.LockedMessageManager
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.mms.ui.SpamMessageManager
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.mms.ui.ReservationMessageManager
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.mms.ui.DraftMessageManager
I/CameraFirmware_broadcast( 3246): CameraFirmwareBroadCastReceiver...
,I/CameraApp( 3246): CameraApp.getAppFeature()...
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.mms.ui.RecipientListActivity
,I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.mms.ui.GroupMessagingRecipientListActivity
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.mms.ui.SelectMapActivity
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.mms.ui.BoxListViewActivity
I/AMMetaDataParserService( 3111): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3111): getResourcePackageName:android.app.default_searchable
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.mms.provisioning.MmsProvisionActivity
,I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.mms.ui.ManageSDMessages
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.mms.ui.VMessageViewerActivity
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.mms.spam.HelpActivity
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.mms.spam.SetupSpamNumberList
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.mms.spam.SetupSpamKeywordList
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.mms.spam.SetupSpamNumberWriteForm
,I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.mms.spam.SetupSpamKeywordWriteForm
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.mms.ui.SettingsReservationActivity
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.mms.ui.SettingsTransmitMessageActivity
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.mms.ui.MessageDatabaseBackupActivity
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.samsung.mms.content.MmsPartExportDialogActivity
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.samsung.mms.content.MmsPartExportDialogActivityAlien
,I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.mms.ui.MmsPartExportActivity
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.mms.template.TextTemplateListActivity
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.mms.template.TextTemplateEditActivity
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.mms.help.AirViewMainActivity
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.mms.help.AirButtonMainActivity
,I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.mms.widget.WidgetPreferenceActivity
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.mms.cover.MissedMsgActivity
I/AMMetaDataParserService( 3111): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 3111): getResourcePackageName:com.sec.android.multiwindow.activity.STYLE
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.samsung.mms.ui.AutoSendingTestActivity
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.mms.prioritysender.AddGlanceListActivity
,I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.mms.prioritysender.AddThreadListActivity
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.mms.smishing.PackageAuthorityActivity
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.mms.smishing.PackageAuthorityDialog
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.mms.settings.CheckDefaultSmsAppsActivity
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.mms.help.PrioritySenderHelpActivity
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.mms.help.AddGlanceListHelpActivity
,I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.mms.accessory.ReadReportActivity
,I/SELinux ( 3258): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 3258):  
,I/ActivityManager(  742): Killing 2322:com.sec.android.diagmonagent/1000 (adj 15): empty #43
,I/ActivityManager(  742): Waited long enough for: ServiceRecord{43257a90 u0 com.samsung.android.providers.context/.ContextService}
,I/SELinux ( 3258): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 3258):  
I/SELinux ( 3258):  
,I/SELinux ( 3258): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 3258): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 3258): >>>>> Normal User
,E/dalvikvm( 3258): >>>>> com.samsung.android.app.watchmanagerstub [ userId:0 | appId:10100 ]
,E/SELinux ( 3258): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 3258): in addTimaSignatureService
,D/TimaKeyStoreProvider( 3258): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 3258): Added TimaKesytore provider
,D/dalvikvm( 3111): GC_CONCURRENT freed 5000K, 34% free 12689K/18976K, paused 2ms+3ms, total 37ms
,D/dalvikvm( 3111): WAIT_FOR_CONCURRENT_GC blocked 23ms
,I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.settings.GridSettings
I/AMMetaDataParserService( 3111): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3111): getResourcePackageName:assistant
,I/AMMetaDataParserService( 3111): Resource data:2131165216
,I/AMMetaDataParserService( 3111): getResourceName:com.android.settings:xml/assistant
,I/AMMetaDataParserService( 3111): getResourceTypeNamexml
,I/AMMetaDataParserService( 3111): Icon data: ResourceSearch2131297802com.android.settings.Search2130837582
,D/PackageIntentReceiver( 3258): ACTION_BOOT_COMPLETED
,D/PackageIntentReceiver( 3258): jangil::ACTION_BOOT_COMPLETED::do not need pkg remove..
I/ActivityManager(  742): Killing 1643:com.fmm.dm/1000 (adj 15): empty #43
,I/AMMetaDataParserService( 3111): Icon data: ResourceEdit quick settings2131296308com.android.settings.Favorite2130837581
,I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.settings.SubSettings
,I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.settings.TimDataConnectionDialog
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.settings.LabelName
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.settings.Password
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.settings.TetherHelp
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.settings.Settings$EthernetSettingsActivity
I/AMMetaDataParserService( 3111): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3111): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3111): Resource data:2131429159
I/SELinux ( 3273): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 3273):  
I/AMMetaDataParserService( 3111): getResourceName:com.android.settings:id/wireless_settings
,I/AMMetaDataParserService( 3111): getResourceTypeNameid
,I/AMMetaDataParserService( 3111): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,D/dalvikvm(  249): GC_EXPLICIT freed 46K, 50% free 9509K/18976K, paused 2ms+2ms, total 28ms
,I/AMMetaDataParserService( 3111): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3111): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3111): Resource data:2131296695
I/AMMetaDataParserService( 3111): getResourceName:com.android.settings:string/wireless_networks_settings_title
I/AMMetaDataParserService( 3111): getResourceTypeNamestring
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.settings.ethernet.EthernetEnabler
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.settings.ethernet.EthernetConfigure
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.settings.Settings$WirelessSettingsActivity
I/AMMetaDataParserService( 3111): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3111): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3111): Resource data:2131429159
I/AMMetaDataParserService( 3111): getResourceName:com.android.settings:id/wireless_settings
I/AMMetaDataParserService( 3111): getResourceTypeNameid
I/AMMetaDataParserService( 3111): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.settings.Settings$WifiSettingsActivity
I/AMMetaDataParserService( 3111): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3111): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3111): Resource data:2131429144
I/AMMetaDataParserService( 3111): getResourceName:com.android.settings:id/wifi_settings
I/AMMetaDataParserService( 3111): getResourceTypeNameid
I/AMMetaDataParserService( 3111): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.settings.wifi.WifiSettings
I/AMMetaDataParserService( 3111): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3111): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3111): Resource data:2131429144
I/AMMetaDataParserService( 3111): getResourceName:com.android.settings:id/wifi_settings
I/AMMetaDataParserService( 3111): getResourceTypeNameid
I/AMMetaDataParserService( 3111): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.settings.wifi.WifiPickerActivity
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.settings.wifi.WifiSecPickerActivity
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.settings.wifi.WifiDummyPickerActivity
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.settings.wifi.WifiCaptiveActivity
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.settings.wifi.WifiPickerDialog
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.settings.wifi.hs20.Hs20PickerDialog
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.settings.wifi.WifiWarningDialog
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.settings.wifi.WifiOffloadDialog
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.settings.wifi.SetupWizardWifiScreen
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.settings.wifi.CaptivePortalWebViewActivity
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.settings.wifi.WifiAdvancedVzwSetupActivity
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.settings.wifi.WifiAdvancedSecSetupActivity
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.settings.wifi.WifiSecSetupActivity
I/AMMetaDataParserService( 3111): Resource data:Loo,p for running activitycom.android.settings.wifi.WifiSetupActivity
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.settings.wifi.WifiSettingsForSetupWizardXL
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.settings.wifi.WifiManageNetworks
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.settings.Settings$AdvancedWifiSettingsActivity
,I/AMMetaDataParserService( 3111): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 3111): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 3111): Resource data:2131429144
,D/dalvikvm(  249): GC_EXPLICIT freed <1K, 50% free 9509K/18976K, paused 2ms+3ms, total 19ms
,I/AMMetaDataParserService( 3111): getResourceName:com.android.settings:id/wifi_settings
I/AMMetaDataParserService( 3111): getResourceTypeNameid
I/AMMetaDataParserService( 3111): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,I/AMMetaDataParserService( 3111): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3111): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
,I/AMMetaDataParserService( 3111): Resource data:2131297114
,I/AMMetaDataParserService( 3111): getResourceName:com.android.settings:string/wifi_settings
I/AMMetaDataParserService( 3111): getResourceTypeNamestring
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.settings.wifi.WifiInfo
,I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.settings.wifi.WifiConfigInfo
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.settings.wifi.WifiAPITest
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.settings.wifi.WifiStatusTest
,I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.settings.wifi.mobileap.WifiApSettings
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.settings.wifi.mobileap.WifiApWarning
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.settings.wifi.WifiPoorConnection
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.settings.wifi.WifiHiddenApListActivity
,I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.settings.wifi.WifiHiddenApDeleteActivity
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.settings.wifi.WifiConnectionSettings
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.settings.ApnSettings
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.settings.ApnSettingsTabActivity
,I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.settings.Settings$BluetoothSettingsActivity
I/AMMetaDataParserService( 3111): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3111): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 3111): Resource data:2131429146
,I/AMMetaDataParserService( 3111): getResourceName:com.android.settings:id/bluetooth_settings
I/AMMetaDataParserService( 3111): getResourceTypeNameid
I/AMMetaDataParserService( 3111): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.settings.bluetooth.BluetoothSettings
I/AMMetaDataParserService( 3111): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 3111): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 3111): Resource data:2131429146
I/SELinux ( 3273): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 3273):  
I/SELinux ( 3273):  
,I/SELinux ( 3273): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
I/AMMetaDataParserService( 3111): getResourceName:com.android.settings:id/bluetooth_settings
,E/SELinux ( 3273): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
I/AMMetaDataParserService( 3111): getResourceTypeNameid
E/dalvikvm( 3273): >>>>> Normal User
E/dalvikvm( 3273): >>>>> com.google.android.talk [ userId:0 | appId:10105 ]
,I/AMMetaDataParserService( 3111): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.settings.bluetooth.BluetoothScanDialog
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.settings.bluetooth.BluetoothErrorActivity
,I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.settings.bluetooth.CheckBluetoothStateActivity
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.settings.bluetooth.DevicePickerActivity
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.settings.Settings$MirrorLinkActivity
,I/AMMetaDataParserService( 3111): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3111): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3111): Resource data:2131429168
,E/SELinux ( 3273): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
,I/AMMetaDataParserService( 3111): getResourceName:com.android.settings:id/mirror_link_settings
I/AMMetaDataParserService( 3111): getResourceTypeNameid
I/AMMetaDataParserService( 3111): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.settings.Settings$TetherSettingsActivity
I/AMMetaDataParserService( 3111): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 3111): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 3111): Resource data:2131429159
,I/AMMetaDataParserService( 3111): getResourceName:com.android.settings:id/wireless_settings
I/AMMetaDataParserService( 3111): getResourceTypeNameid
I/AMMetaDataParserService( 3111): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,I/AMMetaDataParserService( 3111): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3111): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
,I/AMMetaDataParserService( 3111): Resource data:2131296695
,D/dalvikvm(  249): GC_EXPLICIT freed <1K, 50% free 9509K/18976K, paused 2ms+3ms, total 21ms
I/AMMetaDataParserService( 3111): getResourceName:com.android.settings:string/wireless_networks_settings_title
,I/AMMetaDataParserService( 3111): getResourceTypeNamestring
I/AMMetaDataParserService( 3111): getResourcePackageName:com.samsung.android.multiuser.install_only_owner
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.settings.TetherSettings
,I/AMMetaDataParserService( 3111): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3111): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3111): Resource data:2131429159
I/AMMetaDataParserService( 3111): getResourceName:com.android.settings:id/wireless_settings
I/AMMetaDataParserService( 3111): getResourceTypeNameid
I/AMMetaDataParserService( 3111): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3111): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3111): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3111): Resource data:2131296695
I/AMMetaDataParserService( 3111): getResourceName:com.android.settings:string/wireless_networks_settings_title
I/AMMetaDataParserService( 3111): getResourceTypeNamestring
I/AMMetaDataParserService( 3111): getResourcePackageName:com.samsung.android.multiuser.install_only_owner
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.settings.Settings$WifiP2pSettingsActivity
I/AMMetaDataParserService( 3111): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3111): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 3111): Resource data:2131429144
I/AMMetaDataParserService( 3111): getResourceName:com.android.settings:id/wifi_settings
I/AMMetaDataParserService( 3111): getResourceTypeNameid
I/AMMetaDataParserService( 3111): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3111): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
,I/AMMetaDataParserService( 3111): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
,I/AMMetaDataParserService( 3111): Resource data:2131297114
I/AMMetaDataParserService( 3111): getResourceName:com.android.settings:string/wifi_settings
I/AMMetaDataParserService( 3111): getResourceTypeNamestring
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.settings.wifi.p2p.WifiP2pSettings
,I/AMMetaDataParserService( 3111): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3111): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 3111): Resource data:2131429159
,I/AMMetaDataParserService( 3111): getResourceName:com.android.settings:id/wireless_settings
I/AMMetaDataParserService( 3111): getResourceTypeNameid
I/AMMetaDataParserService( 3111): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,I/AMMetaDataParserService( 3111): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3111): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
,I/AMMetaDataParserService( 3111): Resource data:2131296695
I/AMMetaDataParserService( 3111): getResourceName:com.android.settings:string/wireless_networks_settings_title
I/AMMetaDataParserService( 3111): getResourceTypeNamestring
,I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.settings.Settings$WifiP2pHelpActivity
I/AMMetaDataParserService( 3111): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3111): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 3111): Resource data:2131429159
I/AMMetaDataParserService( 3111): getResourceName:com.android.settings:id/wireless_settings
,I/AMMetaDataParserService( 3111): getResourceTypeNameid
I/AMMetaDataParserService( 3111): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3111): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
,I/AMMetaDataParserService( 3111): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
,I/AMMetaDataParserService( 3111): Resource data:2131296695
I/AMMetaDataParserService( 3111): getResourceName:com.android.settings:string/wireless_networks_settings_title
I/AMMetaDataParserService( 3111): getResourceTypeNamestring
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.settings.wifi.p2p.WifiP2pDummyPickerActivity
,I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.settings.Settings$NearbySettingsActivity
I/AMMetaDataParserService( 3111): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3111): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
D/TimaKeyStoreProvider( 3273): in addTimaSignatureService
,I/AMMetaDataParserService( 3111): Resource data:2131429159
,I/AMMetaDataParserService( 3111): getResourceName:com.android.settings:id/wireless_settings
I/AMMetaDataParserService( 3111): getResourceTypeNameid
I/AMMetaDataParserService( 3111): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3111): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3111): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
,I/AMMetaDataParserService( 3111): Resource data:2131296695
,I/AMMetaDataParserService( 3111): getResourceName:com.android.settings:string/wireless_networks_settings_title
I/AMMetaDataParserService( 3111): getResourceTypeNamestring
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.settings.nearby.NearbySettings
I/AMMetaDataParserService( 3111): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 3111): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 3111): Resource data:2131429159
D/TimaKeyStoreProvider( 3273): Cannot add TimaSignature Service, License check Failed
I/AMMetaDataParserService( 3111): getResourceName:com.android.settings:id/wireless_settings
I/AMMetaDataParserService( 3111): getResourceTypeNameid
I/AMMetaDataParserService( 3111): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,I/AMMetaDataParserService( 3111): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3111): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
,I/AMMetaDataParserService( 3111): Resource data:2131296695
D/ActivityThread( 3273): Added TimaKesytore provider
I/AMMetaDataParserService( 3111): getResourceName:com.android.settings:string/wireless_networks_settings_title
,I/AMMetaDataParserService( 3111): getResourceTypeNamestring
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.settings.wfd.WfdHelpActivity
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.settings.wfd.WfdPickerDialog
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.settings.Settings$VpnSettingsActivity
,I/AMMetaDataParserService( 3111): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3111): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 3111): Resource data:2131429159
I/AMMetaDataParserService( 3111): getResourceName:com.android.settings:id/wireless_settings
I/AMMetaDataParserService( 3111): getResourceTypeNameid
,I/AMMetaDataParserService( 3111): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3111): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3111): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
,I/AMMetaDataParserService( 3111): Resource data:2131296695
,I/AMMetaDataParserService( 3111): getResourceName:com.android.settings:string/wireless_networks_settings_title
I/AMMetaDataParserService( 3111): getResourceTypeNamestring
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.settings.Settings$DateTimeSettingsActivity
I/AMMetaDataParserService( 3111): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3111): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 3111): Resource data:2131429219
I/AMMetaDataParserService( 3111): getResourceName:com.android.settings:id/date_time_settings
I/AMMetaDataParserService( 3111): getResourceTypeNameid
I/AMMetaDataParserService( 3111): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.settings.DateTimeSettingsSetupWizard
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.settings.FeatureSettingsSetupWizard
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.settings.Settings$LocalePickerActivity
I/AMMetaDataParserService( 3111): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3111): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 3111): Resource data:2131429191
I/AMMetaDataParserService( 3111): getResourceName:com.android.settings:id/language_settings
I/AMMetaDataParserService( 3111): getResourceTypeNameid
I/AMMetaDataParserService( 3111): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.settings.Settings$InputMethodAndLanguageSettingsActivity
I/AMMetaDataParserService( 3111): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3111): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 3111): Resource data:2131429191
I/AMMetaDataParserService( 3111): getResourceName:com.android.settings:id/language_settings
I/AMMetaDataParserService( 3111): getResourceTypeNameid
I/AMMetaDataParserService( 3111): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.settings.Settings$HandwritingLanguageActivity
I/AMMetaDataParserService( 3111): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3111): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 3111): Resource data:2131429191
I/AMMetaDataParserService( 3111): getResourceName:com.android.settings:id/language_settings
I/AMMetaDataParserService( 3111): getResourceTypeNameid
I/AMMetaDataParserService( 3111): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.settings.handwritingsearch.HandwritingLanguageTablet
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.settings.Settings$KeyboardLayoutPickerActivity
I/AMMetaDataParserService( 3111): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3111): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 3111): Resource data:2131429191
I/AMMetaDataParserService( 3111): getResourceName:com.android.settings:id/language_settings
I/AMMetaDataParserService( 3111): getResourceTypeNameid
I/AMMetaDataParserService( 3111): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.settings.LanguageSettings
I/AMMetaDataParserService( 3111): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3111): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 3111): Resource data:2131429191
I/AMMetaDataParserService( 3111): getResourceName:com.android.settings:id/language_settings
I/AMMetaDataParserService( 3111): getResourceTypeNameid
I/AMMetaDataParserService( 3111): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.settings.Settings$SpellCheckersSettingsActivity
I/AMMetaDataParserService( 3111): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3111): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 3111): Resource data:2131429191
I/AMMetaDataParserService( 3111): getResourceName:com.android.settings:id/language_settings
I/AMMetaDataParserService( 3111): getResourceTypeNameid
I/AMMetaDataParserService( 3111): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3111): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3111): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
,I/AMMetaDataParserService( 3111): Resource data:2131298419
I/AMMetaDataParserService( 3111): getResourceName:com.android.settings:string/language_keyboard_settings_title
I/AMMetaDataParserService( 3111): getResourceTypeNamestring
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.settings.inputmethod.InputMethodAndSubtypeEnablerActivity
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.settings.Settings$UserDictionarySettingsActivity
I/AMMetaDataParserService( 3111): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3111): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 3111): Resource data:2131429191
I/AMMetaDataParserService( 3111): getResourceName:com.android.settings:id/language_settings
I/AMMetaDataParserService( 3111): getResourceTypeNameid
I/AMMetaDataParserService( 3111): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3111): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3111): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
,I/AMMetaDataParserService( 3111): Resource data:2131298419
I/AMMetaDataParserService( 3111): getResourceName:com.android.settings:string/language_keyboard_settings_title
I/AMMetaDataParserService( 3111): getResourceTypeNamestring
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.settings.inputmethod.UserDictionaryAddWordActivity
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.settings.UserDictionarySettings
I/AMMetaDataParserService( 3111): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3111): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 3111): Resource data:2131429191
I/AMMetaDataParserService( 3111): getResourceName:com.android.settings:id/language_settings
I/AMMetaDataParserService( 3111): getResourceTypeNameid
I/AMMetaDataParserService( 3111): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3111): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3111): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
,I/AMMetaDataParserService( 3111): Resource data:2131298419
I/AMMetaDataParserService( 3111): getResourceName:com.android.settings:string/language_keyboard_settings_title
I/AMMetaDataParserService( 3111): getResourceTypeNamestring
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.settings.Settings$SoundSettingsActivity
I/AMMetaDataParserService( 3111): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3111): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 3111): Resource data:2131429176
I/AMMetaDataParserService( 3111): getResourceName:com.android.settings:id/sound_settings
,I/AMMetaDataParserService( 3111): getResourceTypeNameid
I/AMMetaDataParserService( 3111): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.settings.SoundSettings
I/AMMetaDataParserService( 3111): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3111): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 3111): Resource data:2131429176
,I/AMMetaDataParserService( 3111): getResourceName:com.android.settings:id/sound_settings
I/AMMetaDataParserService( 3111): getResourceTypeNameid
I/AMMetaDataParserService( 3111): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.settings.Settings$LockScreenSettingsActivity
,I/AMMetaDataParserService( 3111): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3111): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.settings.Settings$DisplaySettingsActivity
I/AMMetaDataParserService( 3111): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3111): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 3111): Resource data:2131429173
,I/AMMetaDataParserService( 3111): getResourceName:com.android.settings:id/display_settings
I/AMMetaDataParserService( 3111): getResourceTypeNameid
I/AMMetaDataParserService( 3111): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.settings.DisplaySettings
I/AMMetaDataParserService( 3111): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 3111): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 3111): Resource data:2131429173
I/AMMetaDataParserService( 3111): getResourceName:com.android.settings:id/display_settings
,I/AMMetaDataParserService( 3111): getResourceTypeNameid
I/AMMetaDataParserService( 3111): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.settings.Settings$LockscreenMenuActivity
I/AMMetaDataParserService( 3111): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 3111): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 3111): Resource data:2131429172
I/AMMetaDataParserService( 3111): getResourceName:com.android.settings:id/lock_screen_menu_settings
I/AMMetaDataParserService( 3111): getResourceTypeNameid
I/AMMetaDataParserService( 3111): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.settings.LockscreenMenuSettings
,I/AMMetaDataParserService( 3111): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3111): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 3111): Resource data:2131429172
,I/AMMetaDataParserService( 3111): getResourceName:com.android.settings:id/lock_screen_menu_settings
I/AMMetaDataParserService( 3111): getResourceTypeNameid
I/AMMetaDataParserService( 3111): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.settings.Settings$BlockSettingsActivity
,I/AMMetaDataParserService( 3111): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3111): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 3111): Resource data:2131429182
,I/AMMetaDataParserService( 3111): getResourceName:com.android.settings:id/block_settings
I/AMMetaDataParserService( 3111): getResourceTypeNameid
I/AMMetaDataParserService( 3111): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.settings.Settings$LedIndicatorSettingsActivity
I/AMMetaDataParserService( 3111): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3111): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 3111): Resource data:2131429173
,I/AMMetaDataParserService( 3111): getResourceName:com.android.settings:id/display_settings
I/AMMetaDataParserService( 3111): getResourceTypeNameid
I/AMMetaDataParserService( 3111): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.settings.Settings$DockSettingsActivity
,I/AMMetaDataParserService( 3111): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3111): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 3111): Resource data:2131429186
,I/AMMetaDataParserService( 3111): getResourceName:com.android.settings:id/dock_settings
I/AMMetaDataParserService( 3111): getResourceTypeNameid
I/AMMetaDataParserService( 3111): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.settings.DockSettings
,I/AMMetaDataParserService( 3111): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3111): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 3111): Resource data:2131429186
I/AMMetaDataParserService( 3111): getResourceName:com.android.settings:id/dock_settings
I/AMMetaDataParserService( 3111): getResourceTypeNameid
I/AMMetaDataParserService( 3111): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.settings.ContextualPageSettings
I/AMMetaDataParserService( 3111): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3111): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 3111): Resource data:2131429173
I/AMMetaDataParserService( 3111): getResourceName:com.android.settings:id/display_settings
I/AMMetaDataParserService( 3111): getResourceTypeNameid
I/AMMetaDataParserService( 3111): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3111): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3111): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
,I/AMMetaDataParserService( 3111): Resource data:2131297804
I/AMMetaDataParserService( 3111): getResourceName:com.android.settings:string/display_settings
I/AMMetaDataParserService( 3111): getResourceTypeNamestring
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.settings.Settings$ContextualPageHelpActivity
I/AMMetaDataParserService( 3111): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3111): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 3111): Resource data:2131429173
I/AMMetaDataParserService( 3111): getResourceName:com.android.settings:id/display_settings
I/AMMetaDataParserService( 3111): getResourceTypeNameid
I/AMMetaDataParserService( 3111): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.settings.Settings$DeviceInfoSettingsActivity
I/AMMetaDataParserService( 3111): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3111): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 3111): Resource data:2131429228
I/AMMetaDataParserService( 3111): getResourceName:com.android.settings:id/about_settings
I/AMMetaDataParserService( 3111): getResourceTypeNameid
I/AMMetaDataParserService( 3111): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.settings.SettingsLicenseActivity
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.settings.TermsAndConditionActivity
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.settings.PrivacyAlertDialogActivity
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.settings.PrivacyAlertProceedDialogActivity
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.settings.SettingsSafetyLegalActivity
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.settings.users.UserOptions
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.settings.Settings$ManageApplicationsActivity
I/AMMetaDataParserService( 3111): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3111): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 3111): Resource data:2131429128
I/AMMetaDataParserService( 3111): getResourceName:com.android.settings:id/application_settings
I/AMMetaDataParserService( 3111): getResourceTypeNameid
I/AMMetaDataParserService( 3111): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.settings.applications.ManageApplications
I/AMMetaDataParserService( 3111): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3111): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 3111): Resource data:2131429128
,I/AMMetaDataParserService( 3111): getResourceName:com.android.settings:id/application_settings
I/AMMetaDataParserService( 3111): getResourceTypeNameid
I/AMMetaDataParserService( 3111): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.settings.ManageApplications
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.settings.RunningServices
I/AMMetaDataParserService( 3111): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3111): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 3111): Resource data:2131429128
I/AMMetaDataParserService( 3111): getResourceName:com.android.settings:id/application_settings
I/AMMetaDataParserService( 3111): getResourceTypeNameid
I/AMMetaDataParserService( 3111): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.settings.LaunchApplication
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.settings.Settings$HomeSettingsActivity
I/AMMetaDataParserService( 3111): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3111): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 3111): Resource data:2131429127
I/AMMetaDataParserService( 3111): getResourceName:com.android.settings:id/home_settings
I/AMMetaDataParserService( 3111): getResourceTypeNameid
I/AMMetaDataParserService( 3111): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.settings.HomeSettings
I/AMMetaDataParserService( 3111): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3111): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 3111): Resource data:2131429127
I/AMMetaDataParserService( 3111): getResourceName:com.android.settings:id/home_settings
I/AMMetaDataParserService( 3111): getResourceTypeNameid
I/AMMetaDataParserService( 3111): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.settings.applications.StorageUse
I/AMMetaDataParserService( 3111): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3111): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 3111): Resource data:2131429128
I/AMMetaDataParserService( 3111): getResourceName:com.android.settings:id/application_settings
I/AMMetaDataParserService( 3111): getResourceTypeNameid
I/AMMetaDataParserService( 3111): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.settings.applications.InstalledAppDetailsTop
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.settings.applications.InstalledAppDetails
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.settings.applications.UninstallMultipleScreen
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.settings.users.AppRestrictionsFragment$Activity
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.settings.Settings$RunningServicesActivity
I/AMMetaDataParserService( 3111): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3111): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 3111): Resource data:2131429128
I/AMMetaDataParserService( 3111): getResourceName:com.android.settings:id/application_settings
I/AMMetaDataParserService( 3111): getResourceTypeNameid
I/AMMetaDataParserService( 3111): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.settings.LaunchApplication
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.settings.Settings$HomeSettingsActivity
I/AMMetaDataParserService( 3111): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3111): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 3111): Resource data:2131429127
I/AMMetaDataParserService( 3111): getResourceName:com.android.settings:id/home_settings
I/AMMetaDataParserService( 3111): getResourceTypeNameid
I/AMMetaDataParserService( 3111): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.settings.HomeSettings
I/AMMetaDataParserService( 3111): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3111): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 3111): Resource data:2131429127
I/AMMetaDataParserService( 3111): getResourceName:com.android.settings:id/home_settings
I/AMMetaDataParserService( 3111): getResourceTypeNameid
I/AMMetaDataParserService( 3111): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.settings.Settings$StorageUseActivity
I/AMMetaDataParserService( 3111): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3111): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 3111): Resource data:2131429128
I/AMMetaDataParserService( 3111): getResourceName:com.android.settings:id/application_settings
I/AMMetaDataParserService( 3111): getResourceTypeNameid
I/AMMetaDataParserService( 3111): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.settings.Settings$NotificationStationActivity
I/AMMetaDataParserService( 3111): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3111): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.settings.Settings$LocationSettingsActivity
I/AMMetaDataParserService( 3111): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3111): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 3111): Resource data:2131429153
I/AMMetaDataParserService( 3111): getResourceName:com.android.settings:id/location_settings
I/AMMetaDataParserService( 3111): getResourceTypeNameid
I/AMMetaDataParserService( 3111): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.settings.Settings$SecuritySettingsActivity
I/AMMetaDataParserService( 3111): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3111): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 3111): Resource data:2131429224
I/AMMetaDataParserService( 3111): getResourceName:com.android.settings:id/security_settings
I/AMMetaDataParserService( 3111): getResourceTypeNameid
I/AMMetaDataParserService( 3111): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.settings.CarrierMatchSetting
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.settings.MonitoringCertInfoActivity
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.settings.Settings$TrustedCredentialsSettingsActivity
I/AMMetaDataParserService( 3111): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3111): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 3111): Resource data:2131429224
I/AMMetaDataParserService( 3111): getResourceName:com.android.settings:id/security_settings
I/AMMetaDataParserService( 3111): getResourceTypeNameid
,I/AMMetaDataParserService( 3111): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3111): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3111): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
,I/AMMetaDataParserService( 3111): Resource data:2131296750
I/AMMetaDataParserService( 3111): getResourceName:com.android.settings:string/security_settings_title
,I/AMMetaDataParserService( 3111): getResourceTypeNamestring
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.settings.SecuritySettings
I/AMMetaDataParserService( 3111): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3111): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3111): Resource data:2131429224
I/AMMetaDataParserService( 3111): getResourceName:com.android.settings:id/security_settings
I/AMMetaDataParserService( 3111): getResourceTypeNameid
,I/AMMetaDataParserService( 3111): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.settings.Settings$PrivacySettingsActivity
I/AMMetaDataParserService( 3111): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3111): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 3111): Resource data:2131429123
I/AMMetaDataParserService( 3111): getResourceName:com.android.settings:id/privacy_settings
,I/AMMetaDataParserService( 3111): getResourceTypeNameid
I/AMMetaDataParserService( 3111): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.settings.SetFullBackupPassword
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.settings.CredentialStorage
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.settings.Settings$DeviceAdminSettingsActivity
,I/AMMetaDataParserService( 3111): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3111): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 3111): Resource data:2131429224
I/AMMetaDataParserService( 3111): getResourceName:com.android.settings:id/security_settings
I/AMMetaDataParserService( 3111): getResourceTypeNameid
I/AMMetaDataParserService( 3111): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3111): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
,I/AMMetaDataParserService( 3111): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3111): Resource data:2131296750
I/AMMetaDataParserService( 3111): getResourceName:com.android.settings:string/security_settings_title
I/AMMetaDataParserService( 3111): getResourceTypeNamestring
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.settings.DeviceAdminSettings
,I/AMMetaDataParserService( 3111): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3111): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 3111): Resource data:2131429224
I/AMMetaDataParserService( 3111): getResourceName:com.android.settings:id/security_settings
I/AMMetaDataParserService( 3111): getResourceTypeNameid
I/AMMetaDataParserService( 3111): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,I/AMMetaDataParserService( 3111): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3111): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
,I/AMMetaDataParserService( 3111): Resource data:2131296750
I/AMMetaDataParserService( 3111): getResourceName:com.android.settings:string/security_settings_title
I/AMMetaDataParserService( 3111): getResourceTypeNamestring
,I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.settings.DeviceAdminAdd
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.settings.IccLockSettings
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.settings.SimPinLockSettings
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.settings.SimPersoLockSettings
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.settings.Settings$AccessibilitySettingsActivity
I/AMMetaDataParserService( 3111): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3111): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 3111): Resource data:2131429187
,I/AMMetaDataParserService( 3111): getResourceName:com.android.settings:id/accessibility_settings
I/AMMetaDataParserService( 3111): getResourceTypeNameid
I/AMMetaDataParserService( 3111): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.settings.Settings$CaptioningSettingsActivity
I/AMMetaDataParserService( 3111): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 3111): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3111): Resource data:2131429187
,I/AMMetaDataParserService( 3111): getResourceName:com.android.settings:id/accessibility_settings
I/AMMetaDataParserService( 3111): getResourceTypeNameid
I/AMMetaDataParserService( 3111): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3111): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3111): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
,I/AMMetaDataParserService( 3111): Resource data:2131298587
,I/AMMetaDataParserService( 3111): getResourceName:com.android.settings:string/accessibility_settings
I/AMMetaDataParserService( 3111): getResourceTypeNamestring
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.settings.Settings$AssistantMenuPreferenceFragmentActivity
I/AMMetaDataParserService( 3111): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 3111): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3111): Resource data:2131429187
,I/AMMetaDataParserService( 3111): getResourceName:com.android.settings:id/accessibility_settings
I/AMMetaDataParserService( 3111): getResourceTypeNameid
I/AMMetaDataParserService( 3111): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3111): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3111): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
,I/AMMetaDataParserService( 3111): Resource data:2131298587
,I/AMMetaDataParserService( 3111): getResourceName:com.android.settings:string/accessibility_settings
I/AMMetaDataParserService( 3111): getResourceTypeNamestring
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.settings.AccessibilitySettingsSetupWizard
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.settings.Settings$TextToSpeechSettingsActivity
I/AMMetaDataParserService( 3111): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 3111): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3111): Resource data:2131429191
I/AMMetaDataParserService( 3111): getResourceName:com.android.settings:id/language_settings
,I/AMMetaDataParserService( 3111): getResourceTypeNameid
I/AMMetaDataParserService( 3111): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.settings.Settings$DrivingModeSettingsActivity
I/AMMetaDataParserService( 3111): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3111): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 3111): Resource data:2131429180
I/AMMetaDataParserService( 3111): getResourceName:com.android.settings:id/driving_mode
,I/AMMetaDataParserService( 3111): getResourceTypeNameid
I/AMMetaDataParserService( 3111): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.settings.Settings$AssistiveHepticSettingsActivity
I/AMMetaDataParserService( 3111): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3111): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.settings.ConfirmLockPattern
,I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.settings.ConfirmLockPassword
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.settings.BluetoothPairingWithCac
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.settings.ChooseLockGeneric
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.settings.ChooseLockGeneric$InternalActivity
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.settings.ChooseLockPattern
,I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.settings.ChooseLockBLock
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.settings.ChooseLockPassword
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.settings.ChooseLockMotion
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.settings.ChooseLockAdditionalPin
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.settings.ChooseLockSignature
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.settings.deviceinfo.Status
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.settings.Settings$StorageSettingsActivity
I/AMMetaDataParserService( 3111): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 3111): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 3111): Resource data:2131429223
I/AMMetaDataParserService( 3111): getResourceName:com.android.settings:id/storage_settings
I/AMMetaDataParserService( 3111): getResourceTypeNameid
,I/AMMetaDataParserService( 3111): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.settings.deviceinfo.MiscFilesHandler
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.settings.deviceinfo.DeviceInfoTabActivity
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.settings.ApnEditor
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.settings.MediaFormat
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.settings.MediaFormatSd
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.settings.quicklaunch.QuickLaunchSettings
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.settings.quicklaunch.BookmarkPicker
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.settings.Settings$DevelopmentSettingsActivity
I/AMMetaDataParserService( 3111): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 3111): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3111): Resource data:2131429225
,I/AMMetaDataParserService( 3111): getResourceName:com.android.settings:id/development_settings
I/AMMetaDataParserService( 3111): getResourceTypeNameid
I/AMMetaDataParserService( 3111): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.settings.Settings$PrintSettingsActivity
I/AMMetaDataParserService( 3111): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 3111): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 3111): Resource data:2131429159
I/AMMetaDataParserService( 3111): getResourceName:com.android.settings:id/wireless_settings
I/AMMetaDataParserService( 3111): getResourceTypeNameid
I/AMMetaDataParserService( 3111): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3111): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
,I/AMMetaDataParserService( 3111): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
,I/AMMetaDataParserService( 3111): Resource data:2131296695
I/AMMetaDataParserService( 3111): getResourceName:com.android.settings:string/wireless_networks_settings_title
I/AMMetaDataParserService( 3111): getResourceTypeNamestring
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.settings.Settings$PrintJobSettingsActivity
,I/AMMetaDataParserService( 3111): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3111): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 3111): Resource data:2131429165
I/AMMetaDataParserService( 3111): getResourceName:com.android.settings:id/print_settings
I/AMMetaDataParserService( 3111): getResourceTypeNameid
I/AMMetaDataParserService( 3111): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.settings.DevelopmentSettings
,I/AMMetaDataParserService( 3111): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3111): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 3111): Resource data:2131429225
I/AMMetaDataParserService( 3111): getResourceName:com.android.settings:id/development_settings
I/AMMetaDataParserService( 3111): getResourceTypeNameid
,I/AMMetaDataParserService( 3111): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.settings.AppPicker
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.settings.Settings$UsbSettingsActivity
I/AMMetaDataParserService( 3111): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3111): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 3111): Resource data:2131429223
I/AMMetaDataParserService( 3111): getResourceName:com.android.settings:id/storage_settings
I/AMMetaDataParserService( 3111): getResourceTypeNameid
,I/AMMetaDataParserService( 3111): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3111): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3111): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
,I/AMMetaDataParserService( 3111): Resource data:2131297938
I/AMMetaDataParserService( 3111): getResourceName:com.android.settings:string/storage_settings_title
I/AMMetaDataParserService( 3111): getResourceTypeNamestring
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.settings.UsbSettings
I/AMMetaDataParserService( 3111): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 3111): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 3111): Resource data:2131429223
I/AMMetaDataParserService( 3111): getResourceName:com.android.settings:id/storage_settings
I/AMMetaDataParserService( 3111): getResourceTypeNameid
I/AMMetaDataParserService( 3111): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3111): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
,I/AMMetaDataParserService( 3111): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
,I/AMMetaDataParserService( 3111): Resource data:2131297938
I/AMMetaDataParserService( 3111): getResourceName:com.android.settings:string/storage_settings_title
I/AMMetaDataParserService( 3111): getResourceTypeNamestring
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.settings.bluetooth.BluetoothPairingDialog
,I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.settings.bluetooth.RequestPermissionActivity
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.settings.wifi.WifiScanModeActivity
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.settings.bluetooth.RequestPermissionHelperActivity
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.settings.bluetooth.BluetoothPermissionActivity
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.settings.ActivityPicker
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.settings.bluetooth.BluetoothEnableActivity
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.settings.bluetooth.BluetoothEnablingActivity
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.settings.Settings$NfcSettingsActivity
I/AMMetaDataParserService( 3111): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3111): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 3111): Resource data:2131429161
,I/AMMetaDataParserService( 3111): getResourceName:com.android.settings:id/nfc_setting
I/AMMetaDataParserService( 3111): getResourceTypeNameid
I/AMMetaDataParserService( 3111): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.settings.nfc.NfcAdvancedRoutingSetting
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.settings.Settings$AndroidBeamSettingsActivity
,I/AMMetaDataParserService( 3111): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3111): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.settings.Settings$SBeamSettingsActivity
I/AMMetaDataParserService( 3111): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3111): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 3111): Resource data:2131429163
,I/AMMetaDataParserService( 3111): getResourceName:com.android.settings:id/sbeam_setting
I/AMMetaDataParserService( 3111): getResourceTypeNameid
I/AMMetaDataParserService( 3111): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.settings.Settings$WifiDisplaySettingsActivity
I/AMMetaDataParserService( 3111): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 3111): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3111): Resource data:2131429167
I/AMMetaDataParserService( 3111): getResourceName:com.android.settings:id/screen_mirroring_settings
I/AMMetaDataParserService( 3111): getResourceTypeNameid
,I/AMMetaDataParserService( 3111): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3111): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3111): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3111): Resource data:2131296695
,I/AMMetaDataParserService( 3111): getResourceName:com.android.settings:string/wireless_networks_settings_title
I/AMMetaDataParserService( 3111): getResourceTypeNamestring
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.settings.BatteryInfo
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.settings.Display
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.settings.RadioInfo
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.settings.ProxySelector
,I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.settings.BandMode
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.settings.TestingSettings
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.settings.fulllocalepickertest.FullLocalePickerTest
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.settings.AppWidgetPickActivity
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.settings.AllowBindAppWidgetActivity
,I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.settings.KeyguardAppWidgetPickActivity
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.settings.UsageStats
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.settings.Settings$PowerUsageSummaryActivity
I/AMMetaDataParserService( 3111): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3111): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 3111): Resource data:2131429221
,I/AMMetaDataParserService( 3111): getResourceName:com.android.settings:id/battery_settings
I/AMMetaDataParserService( 3111): getResourceTypeNameid
I/AMMetaDataParserService( 3111): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.settings.fuelgauge.PowerUsageSummary
,I/AMMetaDataParserService( 3111): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3111): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 3111): Resource data:2131429221
I/AMMetaDataParserService( 3111): getResourceName:com.android.settings:id/battery_settings
I/AMMetaDataParserService( 3111): getResourceTypeNameid
I/AMMetaDataParserService( 3111): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.settings.Settings$AccountSyncSettingsActivity
I/AMMetaDataParserService( 3111): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3111): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 3111): Resource data:2131429119
I/AMMetaDataParserService( 3111): getResourceName:com.android.settings:id/account_settings
,I/AMMetaDataParserService( 3111): getResourceTypeNameid
I/AMMetaDataParserService( 3111): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.settings.accounts.SyncSettingsActivity
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.settings.AccountMenu
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.settings.Settings$AccountMenuActivity
,I/AMMetaDataParserService( 3111): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3111): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 3111): Resource data:2131429217
I/AMMetaDataParserService( 3111): getResourceName:com.android.settings:id/header_general_account_and_backup
I/AMMetaDataParserService( 3111): getResourceTypeNameid
I/AMMetaDataParserService( 3111): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.settings.accounts.AddAccountSettings
,I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.settings.accounts.ChooseAccountActivity
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.settings.CryptKeeper
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.settings.CryptKeeper$FadeToBlack
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.settings.CryptKeeperConfirm$Blank
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.settings.CryptDecryptConfirm$Blank
,I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.settings.Settings$CryptKeeperSettingsActivity
I/AMMetaDataParserService( 3111): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3111): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 3111): Resource data:2131429224
I/AMMetaDataParserService( 3111): getResourceName:com.android.settings:id/security_settings
,I/AMMetaDataParserService( 3111): getResourceTypeNameid
I/AMMetaDataParserService( 3111): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.settings.Settings$CryptSDCardSettingsActivity
I/AMMetaDataParserService( 3111): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3111): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 3111): Resource data:2131429224
I/AMMetaDataParserService( 3111): getResourceName:com.android.settings:id/security_settings
,I/AMMetaDataParserService( 3111): getResourceTypeNameid
I/AMMetaDataParserService( 3111): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.settings.Settings$DataUsageSummaryActivity
I/AMMetaDataParserService( 3111): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3111): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 3111): Resource data:2131429159
,I/AMMetaDataParserService( 3111): getResourceName:com.android.settings:id/wireless_settings
I/AMMetaDataParserService( 3111): getResourceTypeNameid
I/AMMetaDataParserService( 3111): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.settings.AppEncryption
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.settings.Settings$DreamSettingsActivity
,I/AMMetaDataParserService( 3111): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3111): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 3111): Resource data:2131429173
,I/AMMetaDataParserService( 3111): getResourceName:com.android.settings:id/display_settings
I/AMMetaDataParserService( 3111): getResourceTypeNameid
I/AMMetaDataParserService( 3111): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.settings.Settings$UserSettingsActivity
I/AMMetaDataParserService( 3111): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 3111): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 3111): Resource data:2131429208
I/AMMetaDataParserService( 3111): getResourceName:com.android.settings:id/user_settings
I/AMMetaDataParserService( 3111): getResourceTypeNameid
I/AMMetaDataParserService( 3111): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.settings.Settings$PaymentSettingsActivity
I/AMMetaDataParserService( 3111): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3111): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 3111): Resource data:2131429286
,I/AMMetaDataParserService( 3111): getResourceName:com.android.settings:id/nfc_payment_settings
I/AMMetaDataParserService( 3111): getResourceTypeNameid
I/AMMetaDataParserService( 3111): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.settings.nfc.PaymentDefaultDialog
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.settings.SmsDefaultDialog
,I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.settings.Settings$NotificationAccessSettingsActivity
I/AMMetaDataParserService( 3111): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3111): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 3111): Resource data:2131429224
I/AMMetaDataParserService( 3111): getResourceName:com.android.settings:id/security_settings
,I/AMMetaDataParserService( 3111): getResourceTypeNameid
I/AMMetaDataParserService( 3111): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.settings.RegulatoryInfoDisplayActivity
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.settings.FactoryResetDialog
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.settings.LockScreenWallpaper
,I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.settings.Settings$WallpaperSettingsActivity
I/AMMetaDataParserService( 3111): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3111): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 3111): Resource data:2131429201
,I/AMMetaDataParserService( 3111): getResourceName:com.android.settings:id/header_display_wallpaper
I/AMMetaDataParserService( 3111): getResourceTypeNameid
I/AMMetaDataParserService( 3111): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.settings.InformationTicker
I/AMMetaDataParserService( 3111): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 3111): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.settings.GSensorSettings
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.settings.ASensorSettings
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.settings.Settings$PowerSavingModeSettingsActivity
I/AMMetaDataParserService( 3111): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 3111): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3111): Resource data:2131429185
I/AMMetaDataParserService( 3111): getResourceName:com.android.settings:id/power_saving_mode
I/AMMetaDataParserService( 3111): getResourceTypeNameid
I/AMMetaDataParserService( 3111): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.settings.Settings$PowerSavingMode2014Activity
,I/AMMetaDataParserService( 3111): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3111): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 3111): Resource data:2131429185
I/AMMetaDataParserService( 3111): getResourceName:com.android.settings:id/power_saving_mode
I/AMMetaDataParserService( 3111): getResourceTypeNameid
,I/AMMetaDataParserService( 3111): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3111): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3111): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
,I/AMMetaDataParserService( 3111): Resource data:2131299843
,I/AMMetaDataParserService( 3111): getResourceName:com.android.settings:string/power_saving_mode_title
,I/AMMetaDataParserService( 3111): getResourceTypeNamestring
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.settings.Settings$PowerSavingModeSettings2014Activity
I/AMMetaDataParserService( 3111): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3111): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 3111): Resource data:2131429185
,I/AMMetaDataParserService( 3111): getResourceName:com.android.settings:id/power_saving_mode
I/AMMetaDataParserService( 3111): getResourceTypeNameid
I/AMMetaDataParserService( 3111): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.settings.Settings$UltraPowerSavingModeActivity
,I/AMMetaDataParserService( 3111): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3111): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 3111): Resource data:2131429185
,I/AMMetaDataParserService( 3111): getResourceName:com.android.settings:id/power_saving_mode
I/AMMetaDataParserService( 3111): getResourceTypeNameid
I/AMMetaDataParserService( 3111): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.settings.ModePreviewTablet
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.settings.ModePreviewDialog
,I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.settings.InkeffectPreview
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.settings.InkeffectPreviewTablet
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.settings.ModePreview
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.settings.NewModePreview
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.settings.SViewColor
,I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.settings.ChooseLockFaceWarning
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.settings.AskUSBMode
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.settings.Settings$PowerSettingsActivity
I/AMMetaDataParserService( 3111): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3111): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 3111): Resource data:2131429222
I/AMMetaDataParserService( 3111): getResourceName:com.android.settings:id/power_settings
,I/AMMetaDataParserService( 3111): getResourceTypeNameid
I/AMMetaDataParserService( 3111): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.settings.RecommendRingtoneDialog
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.settings.Settings$SelectInfoCoverSettingsActivity
I/AMMetaDataParserService( 3111): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 3111): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 3111): Resource data:2131429186
I/AMMetaDataParserService( 3111): getResourceName:com.android.settings:id/dock_settings
I/AMMetaDataParserService( 3111): getResourceTypeNameid
I/AMMetaDataParserService( 3111): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.settings.SelectItemDisplay
,W/ActivityManager(  742): Permission Denial: getCurrentUser() from pid=3273, uid=10105 requires android.permission.INTERACT_ACROSS_USERS
I/AMMetaDataParserService( 3111): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3111): getResourcePackageName:com.sec.android.sdk.cover.MODE
I/AMMetaDataParserService( 3111): Resource data:1
W/ResourceType( 3111): No package identifier when getting name for resource number 0x00000001
W/System.err( 3111): android.content.res.Resources$NotFoundException: Unable to find resource ID #0x1
W/System.err( 3111): 	at android.content.res.Resources.getResourceName(Resources.java:3017)
W/System.err( 3111): 	at com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.constructDBdata(AMMetaDataParserService.java:159)
W/System.err( 3111): 	at com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent(AMMetaDataParserService.java:86)
W/System.err( 3111): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
W/System.err( 3111): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3111): 	at android.os.Looper.loop(Looper.java:146)
W/System.err( 3111): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.settings.WarrantyLegal
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.settings.PenDetachmentOption
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.settings.Settings$PenDetachmentOptionActivity
I/AMMetaDataParserService( 3111): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3111): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3111): Resource data:2131429199
I/AMMetaDataParserService( 3111): getResourceName:com.android.settings:id/pen_settings_menu
I/AMMetaDataParserService( 3111): getResourceTypeNameid
I/AMMetaDataParserService( 3111): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3111): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3111): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3111): Resource data:2131301070
I/AMMetaDataParserService( 3111): getResourceName:com.android.settings:string/pen_settings
I/AMMetaDataParserService( 3111): getResourceTypeNamestring
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.settings.NotificationPanelMenu
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.settings.Settings$NotificationPanelMenuActivity
I/AMMetaDataParserService( 3111): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3111): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3111): Resource data:2131429173
I/AMMetaDataParserService( 3111): getResourceName:com.android.settings:id/display_settings
I/AMMetaDataParserService( 3111): getResourceTypeNameid
I/AMMetaDataParserService( 3111): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3111): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3111): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3111): Resource data:2131297804
I/AMMetaDataParserService( 3111): getResourceName:com.android.settings:string/display_settings
I/AMMetaDataParserService( 3111): getResourceTypeNamestring
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.settings.NotificationPanelSettings
I/AMMetaDataParserService( 3111): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3111): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3111): Resource data:2131429203
I/AMMetaDataParserService( 3111): getResourceName:com.android.settings:id/header_displ,ay_notification_panel
I/AMMetaDataParserService( 3111): getResourceTypeNameid
I/AMMetaDataParserService( 3111): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.settings.Settings$MotionSettingsActivity
I/AMMetaDataParserService( 3111): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3111): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3111): Resource data:2131429193
I/AMMetaDataParserService( 3111): getResourceName:com.android.settings:id/motion_settings
I/AMMetaDataParserService( 3111): getResourceTypeNameid
I/AMMetaDataParserService( 3111): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.settings.motion.ShakeTutorial
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.settings.Settings$AirMotionSettingActivity
I/AMMetaDataParserService( 3111): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3111): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3111): Resource data:2131429194
I/AMMetaDataParserService( 3111): getResourceName:com.android.settings:id/s_motion_settings
I/AMMetaDataParserService( 3111): getResourceTypeNameid
I/AMMetaDataParserService( 3111): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.settings.Settings$SMotionGuideHub2014Activity
I/AMMetaDataParserService( 3111): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3111): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3111): Resource data:2131429206
I/AMMetaDataParserService( 3111): getResourceName:com.android.settings:id/header_input_motion_and_gesture_2014
I/AMMetaDataParserService( 3111): getResourceTypeNameid
I/AMMetaDataParserService( 3111): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3111): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3111): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3111): Resource data:2131300118
I/AMMetaDataParserService( 3111): getResourceName:com.android.settings:string/motions_title
I/AMMetaDataParserService( 3111): getResourceTypeNamestring
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.settings.Settings$FingerAirViewSettingActivity
I/AMMetaDataParserService( 3111): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3111): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3111): Resource data:2131429196
I/AMMetaDataParserService( 3111): getResourceName:com.android.settings:id/finger_air_view_settings
I/AMMetaDataParserService( 3111): getResourceTypeNameid
I/AMMetaDataParserService( 3111): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.settings.Settings$FingerAirViewHelpSettingActivity
I/AMMetaDataParserService( 3111): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3111): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3111): Resource data:2131429260
I/AMMetaDataParserService( 3111): getResourceName:com.android.settings:id/finger_air_view_settings_k
I/AMMetaDataParserService( 3111): getResourceTypeNameid
I/AMMetaDataParserService( 3111): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.settings.Settings$AirViewSettingActivity
I/AMMetaDataParserService( 3111): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3111): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3111): Reso,urce data:2131429197
I/AMMetaDataParserService( 3111): getResourceName:com.android.settings:id/air_view_settings
I/AMMetaDataParserService( 3111): getResourceTypeNameid
I/AMMetaDataParserService( 3111): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.settings.Settings$MouseHoveringSettingsActivity
I/AMMetaDataParserService( 3111): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3111): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3111): Resource data:2131429291
I/AMMetaDataParserService( 3111): getResourceName:com.android.settings:id/mouse_hovering_settings
I/AMMetaDataParserService( 3111): getResourceTypeNameid
I/AMMetaDataParserService( 3111): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.settings.Settings$SoftwareUpdateSettingActivity
I/AMMetaDataParserService( 3111): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3111): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3111): Resource data:2131429228
I/AMMetaDataParserService( 3111): getResourceName:com.android.settings:id/about_settings
I/AMMetaDataParserService( 3111): getResourceTypeNameid
I/AMMetaDataParserService( 3111): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.settings.PenHovering
I/AMMetaDataParserService( 3111): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3111): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.settings.PenHelpActivity
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.settings.Settings$PenHelpFragmentActivity
I/AMMetaDataParserService( 3111): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3111): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3111): Resource data:2131429199
I/AMMetaDataParserService( 3111): getResourceName:com.android.settings:id/pen_settings_menu
I/AMMetaDataParserService( 3111): getResourceTypeNameid
I/AMMetaDataParserService( 3111): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.settings.Settings$DirectPenInputSettingsActivity
I/AMMetaDataParserService( 3111): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3111): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3111): Resource data:2131429199
I/AMMetaDataParserService( 3111): getResourceName:com.android.settings:id/pen_settings_menu
I/AMMetaDataParserService( 3111): getResourceTypeNameid
I/AMMetaDataParserService( 3111): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.settings.Settings$PenAirViewSettingsMenuActivity
I/AMMetaDataParserService( 3111): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3111): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3111): Resource data:2131429199
I/AMMetaDataParserService( 3111): getResourceName:com.android.settings:id/pen_settings_menu
I/AMMetaDataParserService( 3111): getResourceTypeNameid
I/AMMetaDataParserService( 3111): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.settings.Settings$PenSettingsMenuActivity
I/AMMetaDataParserService( 3111): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3111): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3111): Resource data:2131429199
I/AMMetaDataParserService( 3111): getResourceName:com.android.settings:id/pen_settings_menu
I/AMMetaDataParserService( 3111): getResourceTypeNameid
I/AMMetaDataParserService( 3111): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.settings.PenHelpPopup
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.settings.PhoneVibration
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.settings.OneHandHelp
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.settings.EnableScreenHelp
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.settings.OneHandAdaptiveHelp
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.settings.InputControlHelp
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.settings.personalvibration.PersonalVibration
I/AMMetaDataParserService( 3111): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3111): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.settings.NetworkManagement
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.settings.MultiSimCardManagerPreference
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.settings.NetworkManagementSetting
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.settings.DualHelpActivity
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.settings.DualSoundRingtoneSettings
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.settings.RingtoneSettingTabActivity
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.settings.IccLockTabSettings
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.settings.personalvibration.SelectPatternDialog
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.settings.lockscreenshortcut.LockScreenShortcutSettings
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.settings.lockscreenshortcut.AppList
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.settings.lockscreenshortcut.ExpandAppList
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.settings.Settings$ReadingModeSettingsActivity
I/AMMetaDataParserService( 3111): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3111): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3111): Resource data:2131429173
I/AMMetaDataParserService( 3111): getResourceName:com.android.settings:id/display_settings
I/AMMetaDataParserService( 3111): getResourceTypeNameid
I/AMMetaDataParserService( 3111): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.settings.ReadingModeSettings
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.settings.customizablekey.CustomizableKeySettings
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.settings.Settings$CustomizableKeySettingsActivity
I/AMMetaDataParserService( 3111): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3111): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3111): Resource data:2131429285
I/AMMetaDataParserService( 3111): getResourceName:com.android.settings:id/customizable_key
I/AMMetaDataParserService( 3111): getResourceTypeNameid
I/AMMetaDataParserService( 3111): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.settings.customizablekey.AppList
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.settings.Settings$DualClockSettingActivity
I/AMMetaDataParserService( 3111): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3111): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3111): Resource data:2131429172
I/AMMetaDataParserService( 3111): getResourceName:com.android.settings:id/lock_screen_menu_settings
I/AMMetaDataParserService( 3111): getResourceTypeNameid
I/AMMetaDataParserService( 3111): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3111): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3111): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3111): Resource data:2131301505
I/AMMetaDataParserService( 3111): getResourceName:com.android.settings:string/lock_screen_options
I/AMMetaDataParserService( 3111): getResourceTypeNamestring
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.settings.Settings$RecommendedAppsMenuActivity
I/AMMetaDataParserService( 3111): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3111): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3111): Resource data:2131429203
I/AMMetaDataParserService( 3111): getResourceName:com.android.settings:id/header_display_notification_panel
I/AMMetaDataParserService( 3111): getResourceTypeNameid
I/AMMetaDataParserService( 3111): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.settings.Settings$RecommendedAppsListActivity
I/AMMetaDataParserService( 3111): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3111): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3111): Resource data:2131429203
I/AMMetaDataParserService( 3111): getResourceName:com.android.settings:id/header_display_notification_panel
I/AMMetaDataParserService( 3111): getResourceTypeNameid
I/AMMetaDataParserService( 3111): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3111): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3111): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3111): Resource data:2131302910
I/AMMetaDataParserService( 3111): getResourceName:com.android.settings:string/recommended_apps
I/AMMetaDataParserService( 3111): getResourceTypeNamestring
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.settings.SettingsReceiverActivity
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.settings.SelectPenDetachNotiDialog
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.bst.airmessage.setting.AirMsgSetting
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.settings.SecurityWarningDialog
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.settings.Settings$DormantmodeSettingsActivity
I/AMMetaDataParserService( 3111): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3111): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3111): Resource data:2131429179
I/AMMetaDataParserService( 3111): getResourceName:com.android.settings:id/dormant_mode
I/AMMetaDataParserService( 3111): getResourceTypeNameid
I/AMMetaDataParserService( 3111): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.settings.dormantmode.DormantmodeSettings
I/AMMetaDataParserService( 3111): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3111): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3111): Resource data:2130838248
I/AMMetaDataParserService( 3111): getResourceName:com.android.settings:drawable/ic_settings_dormant_mode
I/AMMetaDataParserService( 3111): getResourceTypeNamedrawable
I/AMMetaDataParserService( 3111): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.settings.dormantmode.DormantModeCustomList
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.settings.dormantmode.DormantModeCustomListDel
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.settings.Settings$GlanceSettingsActivity
I/AMMetaDataParserService( 3111): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3111): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3111): Resource data:2131429216
I/AMMetaDataParserService( 3111): getResourceName:com.android.settings:id/glance_settings
I/AMMetaDataParserService( 3111): getResourceTypeNameid
I/AMMetaDataParserService( 3111): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.settings.Settings$PersonalPageSettingsActivity
I/AMMetaDataParserService( 3111): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3111): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3111): Resource data:2131429209
I/AMMetaDataParserService( 3111): getResourceName:com.android.settings:id/header_personal_page
I/AMMetaDataParserService( 3111): getResourceTypeNameid
I/AMMetaDataParserService( 3111): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageSettings
I/AMMetaDataParserService( 3111): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3111): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3111): Resource data:2131429209
I/AMMetaDataParserService( 3111): getResourceName:com.android.settings:id/header_personal_page
I/AMMetaDataParserService( 3111): getResourceTypeNameid
I/AMMetaDataParserService( 3111): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.settings.PersonalPageDisclaimer
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageTutorial
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageTutorialAppActivity
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageTutorialAddActivity
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageChooseLockPattern
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageChooseLockPassword
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageChooseLockAdditionalPin
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageConfirmLockPattern
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageConfirmLockPassword
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageAlertDialogActivity
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.settings.Settings$EasyModeSettingsActivity
I/AMMetaDataParserService( 3111): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3111): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3111): Resource data:2131429177
I/AMMetaDataParserService( 3111): getResourceName:com.android.settings:id/home_screen_mode_settings
I/AMMetaDataParserService( 3111): getResourceTypeNameid
I/AMMetaDataParserService( 3111): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.settings.Settings$EasyModeActivity
I/AMMetaDataParserService( 3111): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3111): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3111): Resource data:2131429212
I/AMMetaDataParserService( 3111): getResourceName:com.android.settings:id/easy_mode_settings
I/AMMetaDataParserService( 3111): getResourceTypeNameid
I/AMMetaDataParserService( 3111): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.settings.Settings$EasyModeAppActivity
I/AMMetaDataParserService( 3111): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3111): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3111): Resource data:2131429213
I/AMMetaDataParserService( 3111): getResourceName:com.android.settings:id/easy_mode_app_settings
I/AMMetaDataParserService( 3111): getResourceTypeNameid
I/AMMetaDataParserService( 3111): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.settings.LocationAlert
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.settings.Settings$MyPlaceSettingsActivity
I/AMMetaDataParserService( 3111): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3111): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3111): Resource data:2131429153
I/AMMetaDataParserService( 3111): getResourceName:com.android.settings:id/location_settings
I/AMMetaDataParserService( 3111): getResourceTypeNameid
I/AMMetaDataParserService( 3111): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3111): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3111): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3111): Resource data:2131302078
I/AMMetaDataParserService( 3111): getResourceName:com.android.settings:string/myplace_title
I/AMMetaDataParserService( 3111): getResourceTypeNamestring
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.settings.Settings$MyPlaceProfileSettingsActivity
I/AMMetaDataParserService( 3111): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3111): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3111): Resource data:2131429153
I/AMMetaDataParserService( 3111): getResourceName:com.android.settings:id/location_settings
I/AMMetaDataParserService( 3111): getResourceTypeNameid
I/AMMetaDataParserService( 3111): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3111): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3111): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3111): Resource data:2131302078
I/AMMetaDataParserService( 3111): getResourceName:com.android.settings:string/myplace_title
I/AMMetaDataParserService( 3111): getResourceTypeNamestring
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.settings.Settings$PlaceSettingsActivity
I/AMMetaDataParserService( 3111): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3111): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3111): Resource data:2131429153
I/AMMetaDataParserService( 3111): getResourceName:com.android.settings:id/location_settings
I/AMMetaDataParserService( 3111): getResourceTypeNameid
I/AMMetaDataParserService( 3111): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3111): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3111): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3111): Resource data:2131302107
I/AMMetaDataParserService( 3111): getResourceName:com.android.settings:string/place_settings_title
I/AMMetaDataParserService( 3111): getResourceTypeNamestring
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.settings.myplace.SelectMapActivity
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.settings.Settings$GlobalRoamingSettingsActivity
I/AMMetaDataParserService( 3111): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3111): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3111): Resource data:2131429159
I/AMMetaDataParserService( 3111): getResourceName:com.android.settings:id/wireless_settings
I/AMMetaDataParserService( 3111): getResourceTypeNameid
I/AMMetaDataParserService( 3111): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.settings.Settings$TRoamingSettingsActivity
I/AMMetaDataParserService( 3111): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3111): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3111): Resource data:2131429159
I/AMMetaDataParserService( 3111): getResourceName:com.android.settings:id/wireless_settings
I/AMMetaDataParserService( 3111): getResourceTypeNameid
I/AMMetaDataParserService( 3111): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.settings.flipfont.FontListActivity
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.settings.flipfont.FontListProgressActivity
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.settings.Settings$BackupAssistantPlusSettingsActivity
I/AMMetaDataParserService( 3111): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3111): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3111): Resource data:2131429117
I/AMMetaDataParserService( 3111): getResourceName:com.android.settings:id/bua_plus
I/AMMetaDataParserService( 3111): getResourceTypeNameid
I/AMMetaDataParserService( 3111): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.settings.myprofile.MyProfileActivity
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.settings.MagazineCard
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.settings.Settings$ClockWidgetActivity
I/AMMetaDataParserService( 3111): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3111): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.settings.myprofile.PersonalMessage
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.settings.Settings$CloudPictureSyncSettingActivity
I/AMMetaDataParserService( 3111): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3111): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.settings.Settings$CloudVideoSyncSettingActivity
I/AMMetaDataParserService( 3111): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3111): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.settings.Settings$CloudSettingActivity
I/AMMetaDataParserService( 3111): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3111): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3111): Resource data:2131429122
I/AMMetaDataParserService( 3111): getResourceName:com.android.settings:id/scloud_settings
I/AMMetaDataParserService( 3111): getResourceTypeNameid
I/AMMetaDataParserService( 3111): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.settings.ShortCameraMenu
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.settings.ClockMyprofileMenu
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.settings.ClockMyprofileMenuTablet
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.settings.Settings$LaunchCameraSettingsActivity
I/AMMetaDataParserService( 3111): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3111): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.settings.Settings$SmartScreenSettingsActivity
I/AMMetaDataParserService( 3111): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3111): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3111): Resource data:2131429195
I/AMMetaDataParserService( 3111): getResourceName:com.android.settings:id/smart_screen
I/AMMetaDataParserService( 3111): getResourceTypeNameid
I/AMMetaDataParserService( 3111): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3111): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3111): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3111): Resource data:2131297804
I/AMMetaDataParserService( 3111): getResourceName:com.android.settings:string/display_settings
I/AMMetaDataParserService( 3111): getResourceTypeNamestring
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.settings.Settings$SmartBondingSettingsActivity
I/AMMetaDataParserService( 3111): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3111): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3111): Resource data:2131429151
I/AMMetaDataParserService( 3111): getResourceName:com.android.settings:id/smart_bonding_settings
I/AMMetaDataParserService( 3111): getResourceTypeNameid
I/AMMetaDataParserService( 3111): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.settings.Settings$ToolboxMenuActivity
I/AMMetaDataParserService( 3111): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3111): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3111): Resource data:2131429204
I/AMMetaDataParserService( 3111): getResourceName:com.android.settings:id/header_toolbox
I/AMMetaDataParserService( 3111): getResourceTypeNameid
I/AMMetaDataParserService( 3111): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.settings.Settings$ToolboxListActivity
I/AMMetaDataParserService( 3111): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3111): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3111): Resource data:2131429204
I/AMMetaDataParserService( 3111): getResourceName:com.android.settings:id/header_toolbox
I/AMMetaDataParserService( 3111): getResourceTypeNameid
I/AMMetaDataParserService( 3111): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.settings.Settings$SmartScrollAdvancedSettingsActivity
I/AMMetaDataParserService( 3111): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3111): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3111): Resource data:2131429195
I/AMMetaDataParserService( 3111): getResourceName:com.android.settings:id/smart_screen
I/AMMetaDataParserService( 3111): getResourceTypeNameid
I/AMMetaDataParserService( 3111): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.settings.Settings$TorchlightSettingsActivity
I/AMMetaDataParserService( 3111): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3111): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3111): Resource data:2130838300
I/AMMetaDataParserService( 3111): getResourceName:com.android.settings:drawable/ic_settings_torchlight
I/AMMetaDataParserService( 3111): getResourceTypeNamedrawable
I/AMMetaDataParserService( 3111): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.settings.torchlight.TorchlightSettings
I/AMMetaDataParserService( 3111): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3111): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3111): Resource data:2130838300
I/AMMetaDataParserService( 3111): getResourceName:com.android.settings:drawable/ic_settings_torchlight
I/AMMetaDataParserService( 3111): getResourceTypeNamedrawable
I/AMMetaDataParserService( 3111): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.settings.Settings$MultiWindowSettingsActivity
I/AMMetaDataParserService( 3111): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3111): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3111): Resource data:2131429202
I/AMMetaDataParserService( 3111): getResourceName:com.android.settings:id/header_display_multi_window
I/AMMetaDataParserService( 3111): getResourceTypeNameid
I/AMMetaDataParserService( 3111): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.settings.MultiWindowSettings
I/AMMetaDataParserService( 3111): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3111): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3111): Resource data:2131429202
I/AMMetaDataParserService( 3111): getResourceName:com.android.settings:id/header_display_multi_window
I/AMMetaDataParserService( 3111): getResourceTypeNameid
I/AMMetaDataParserService( 3111): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.settings.settingssearch.SettingsSearchActivity
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.settings.search.SearchMain
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.settings.SearchActivity
I/AMMetaDataParserService( 3111): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3111): getResourcePackageName:android.app.searchable
I/AMMetaDataParserService( 3111): Resource data:2131165381
I/AMMetaDataParserService( 3111): getResourceName:com.android.settings:xml/searchable
I/AMMetaDataParserService( 3111): getResourceTypeNamexml
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.settings.settingssearch.SettingsSearchActivity
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.settings.Settings$HomeSyncBackupAndRestoreActivity
I/AMMetaDataParserService( 3111): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3111): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3111): Resource data:2131429124
I/AMMetaDataParserService( 3111): getResourceName:com.android.settings:id/homesync_backup_and_restore_settings
I/AMMetaDataParserService( 3111): getResourceTypeNameid
I/AMMetaDataParserService( 3111): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.settings.Settings$ColorChipReportActivity
I/AMMetaDataParserService( 3111): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3111): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3111): Resource data:2131429187
I/AMMetaDataParserService( 3111): getResourceName:com.android.settings:id/accessibility_settings
I/AMMetaDataParserService( 3111): getResourceTypeNameid
I/AMMetaDataParserService( 3111): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3111): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3111): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3111): Resource data:2131298587
I/AMMetaDataParserService( 3111): getResourceName:com.android.settings:string/accessibility_settings
I/AMMetaDataParserService( 3111): getResourceTypeNamestring
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.settings.Settings$DirectAccessActivity
I/AMMetaDataParserService( 3111): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3111): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.settings.Settings$NotificationReminderActivity
I/AMMetaDataParserService( 3111): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3111): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.settings.Settings$VoiceInputControlSettingsActivity
I/AMMetaDataParserService( 3111): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3111): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3111): Resource data:2131429198
I/Babel   ( 3273): MmsConfig: mnc/mcc: 0/0
I/Babel   ( 3273): MmsConfig.loadMmsSettings
I/AMMetaDataParserService( 3111): getResourceName:com.android.settings:id/voice_input_control_settings
I/AMMetaDataParserService( 3111): getResourceTypeNameid
I/Babel   ( 3273): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=SAMSUNG-ANDROID-MMS/SM-G800H, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-G800H.xml
I/AMMetaDataParserService( 3111): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/Babel   ( 3273): MmsConfig.loadFromDatabase
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.settings.PreloadAppUpdate
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.settings.PreloadAppUpdateList
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.settings.activekey.ActiveKeySettings
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.settings.Settings$ActiveKeySettingsActivity
I/AMMetaDataParserService( 3111): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3111): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3111): Resource data:2131429258
I/AMMetaDataParserService( 3111): getResourceName:com.android.settings:id/active_key_settings
I/AMMetaDataParserService( 3111): getResourceTypeNameid
I/AMMetaDataParserService( 3111): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.settings.activekey.AppList
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.settings.Settings$DisplaySettingsTab
I/AMMetaDataParserService( 3111): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3111): getResourcePackageName:com.android.settings.SETTING_HEADER_ID
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.settings.Settings$InputAndControlSettingsTab
I/AMMetaDataParserService( 3111): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3111): getResourcePackageName:com.android.settings.SETTING_HEADER_ID
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.settings.Settings$GeneralSettingsTab
I/AMMetaDataParserService( 3111): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3111): getResourcePackageName:com.android.settings.SETTING_HEADER_ID
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.settings.DeviceHealthActivity
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.settings.Settings$SettingsEmergencyActivity
I/AMMetaDataParserService( 3111): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3111): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3111): Resource data:2131429220
I/AMMetaDataParserService( 3111): getResourceName:com.android.settings:id/safetycare_settings
I/AMMetaDataParserService( 3111): getResourceTypeNameid
I/AMMetaDataParserService( 3111): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.settings.Settings$SafetyCareSettingsActivity
I/AMMetaDataParserService( 3111): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3111): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3111): Resource data:2131429220
I/AMMetaDataParserService( 3111): getResourceName:com.android.settings:id/safetycare_settings
I/AMMetaDataParserService( 3111): getResourceTypeNameid
I/AMMetaDataParserService( 3111): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.settings.Settings$SafetyCareEmergencyModeActivity
I/AMMetaDataParserService( 3111): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3111): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3111): Resource data:2131429276
I/AMMetaDataParserService( 3111): getResourceName:com.android.settings:id/safetycare_help
I/AMMetaDataParserService( 3111): getResourceTypeNameid
I/AMMetaDataParserService( 3111): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.settings.Settings$SafetyCareDisasterActivity
I/AMMetaDataParserService( 3111): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3111): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3111): Resource data:2131429276
I/AMMetaDataParserService( 3111): getResourceName:com.android.settings:id/safetycare_help
I/AMMetaDataParserService( 3111): getResourceTypeNameid
I/AMMetaDataParserService( 3111): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.settings.safetycare.SafetyCareDisclaimerActivity
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.settings.safetycare.SafetyCareDisasterDisclaimerActivity
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.settings.safetycare.SafetyCareCoverageDialog
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.settings.Settings$AirplaneModeSettingsActivity
I/AMMetaDataParserService( 3111): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3111): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3111): Resource data:2131429148
I/AMMetaDataParserService( 3111): getResourceName:com.android.settings:id/airplane_mode
I/AMMetaDataParserService( 3111): getResourceTypeNameid
I/AMMetaDataParserService( 3111): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.settings.Settings$ToddlerModeSettingsActivity
I/AMMetaDataParserService( 3111): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3111): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3111): Resource data:2131429242
I/AMMetaDataParserService( 3111): getResourceName:com.android.settings:id/toddler_mode
I/AMMetaDataParserService( 3111): getResourceTypeNameid
I/AMMetaDataParserService( 3111): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.settings.KnoxSettings
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.settings.favorite.FavoriteMenuList
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.settings.favorite.MySettnigsRemoveActivity
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.settings.Settings$FestivalEffectSettingsActivity
I/AMMetaDataParserService( 3111): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3111): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3111): Resource data:2131429211
I/AMMetaDataParserService( 3111): getResourceName:com.android.settings:id/festival_effect_settings
I/AMMetaDataParserService( 3111): getResourceTypeNameid
I/AMMetaDataParserService( 3111): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.settings.wifi.WifiConnectDialogActivity
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.settings.powersavingmode.PowerNotiDialog
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.settings.powersavingmode.PowerNotiDataDialog
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.settings.Settings$FingerprintSettingsActivity
I/AMMetaDataParserService( 3111): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3111): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3111): Resource data:2130838248
I/AMMetaDataParserService( 3111): getResourceName:com.android.settings:drawable/ic_settings_dormant_mode
,I/AMMetaDataParserService( 3111): getResourceTypeNamedrawable
I/AMMetaDataParserService( 3111): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.settings.fingerprint.FingerprintDisclaimer
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.settings.Settings$FingerPrintManagerUIActivity
I/AMMetaDataParserService( 3111): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3111): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3111): Resource data:2131429192
I/AMMetaDataParserService( 3111): getResourceName:com.android.settings:id/fingerprint_settings
I/AMMetaDataParserService( 3111): getResourceTypeNameid
I/AMMetaDataParserService( 3111): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.settings.fingerprint.FingerprintOnehandGrip
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.settings.fingerprint.RegisterFingerprint
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.settings.fingerprint.FingerprintPassword
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.settings.fingerprint.FingerprintConfirmPassword
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.settings.fingerprint.FingerprintConfirm
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.settings.fingerprint.FingerprintSupportingFeatures
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.settings.fingerprint.FingerprintWebsignin
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.settings.fingerprint.FingerPrintSettingsSetupWizard
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.settings.fingerprint.FingerPrintSettingsUseFingerprint
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.settings.fingerprint.PaypalPayment
E/Babel   ( 3273): canonicalizeMccMnc: invalid mccmnc 
I/Babel   ( 3273): MmsConfig.loadFromResources
D/dalvikvm( 3273): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 3273): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
D/dalvikvm( 3273): VFY: replacing opcode 0x62 at 0x000a
D/dalvikvm( 3273): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
W/dalvikvm( 3273): VFY: unable to resolve instance field 36
D/dalvikvm( 3273): VFY: replacing opcode 0x54 at 0x005f
D/dalvikvm( 3273): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 3273): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
D/dalvikvm( 3273): VFY: replacing opcode 0x62 at 0x0047
D/dalvikvm( 3273): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
I/dalvikvm( 3273): DexOpt: unable to optimize instance field ref 0x0024 at 0x63 in Lcom/google/android/gms/common/util/ay;.b
E/Babel   ( 3273): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel   ( 3273): MmsConfig.loadMmsSettings: mUserAgent=SAMSUNG-ANDROID-MMS/SM-G800H, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-G800H.xml
D/dalvikvm( 3273): Trying to load lib /data/app-lib/com.google.android.gms-2/libgmscore.so 0x42706aa8
D/dalvikvm( 3273): Added shared lib /data/app-lib/com.google.android.gms-2/libgmscore.so 0x42706aa8
D/dalvikvm( 3273): No JNI_OnLoad found in /data/app-lib/com.google.android.gms-2/libgmscore.so 0x42706aa8, skipping init
D/dalvikvm( 3273): Trying to load lib /data/app-lib/com.google.android.gms-2/libconscrypt_gmscore_jni.so 0x42706aa8
D/dalvikvm( 3273): Added shared lib /data/app-lib/com.google.android.gms-2/libconscrypt_gmscore_jni.so 0x42706aa8
V/JNIHelp ( 3273): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.contacts.activities.PeopleActivity
I/AMMetaDataParserService( 3111): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3111): getResourcePackageName:android.app.searchable
I/AMMetaDataParserService( 3111): Resource data:2131034120
W/Settings( 3273): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/AMMetaDataParserService( 3111): getResourceName:com.android.contacts:xml/searchable
I/AMMetaDataParserService( 3111): getResourceTypeNamexml
I/AMMetaDataParserService( 3111): getResourcePackageName:assistant
I/AMMetaDataParserService( 3111): Resource data:2131034113
I/AMMetaDataParserService( 3111): getResourceName:com.android.contacts:xml/assistant_main
I/AMMetaDataParserService( 3111): getResourceTypeNamexml
I/AMMetaDataParserService( 3111): Icon data: ResourceLogs2131624573android.intent.assistant.main.log2130837531
V/Babel   ( 3273): babel boot account: thalitester@gmail.com
V/Babel   ( 3273): babel boot account: SMS
I/AMMetaDataParserService( 3111): Icon data: ResourceContacts2131623966android.intent.assistant.main.contact2130837529
D/dalvikvm( 3273): Trying to load lib /data/app-lib/com.google.android.gms-2/libgmscore.so 0x42706aa8
D/dalvikvm( 3273): Shared lib '/data/app-lib/com.google.android.gms-2/libgmscore.so' already loaded in same CL 0x42706aa8
D/dalvikvm( 3273): Trying to load lib /data/app-lib/com.google.android.gms-2/libconscrypt_gmscore_jni.so 0x42706aa8
,D/dalvikvm( 3273): Shared lib '/data/app-lib/com.google.android.gms-2/libconscrypt_gmscore_jni.so' already loaded in same CL 0x42706aa8
,I/SELinux ( 3304): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 3304):  
I/ActivityManager(  742): Killing 2357:com.sec.android.fotaclient/u0a10 (adj 15): empty #43
,I/AMMetaDataParserService( 3111): Icon data: ResourceFavourites2131624366android.intent.assistant.main.favorite2130837528
,I/AMMetaDataParserService( 3111): Icon data: ResourceKeypad2131624567android.intent.assistant.main.keypad2130837530
I/SELinux ( 3304): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 3304):  
I/SELinux ( 3304):  
,I/SELinux ( 3304): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 3304): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 3304): >>>>> Normal User
,E/dalvikvm( 3304): >>>>> com.samsung.helphub [ userId:0 | appId:1000 ]
,E/SELinux ( 3304): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.dialer.DialtactsActivity
I/AMMetaDataParserService( 3111): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3111): getResourcePackageName:assistant
,I/AMMetaDataParserService( 3111): Resource data:2131034113
I/AMMetaDataParserService( 3111): getResourceName:com.android.contacts:xml/assistant_main
,I/AMMetaDataParserService( 3111): getResourceTypeNamexml
,D/TimaKeyStoreProvider( 3304): in addTimaSignatureService
,D/TimaKeyStoreProvider( 3304): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 3304): Added TimaKesytore provider
,I/AMMetaDataParserService( 3111): Icon data: ResourceLogs2131624573android.intent.assistant.main.log2130837531
,I/ProviderInstaller( 3273): Installed default security provider GmsCore_OpenSSL
,V/AlarmManager(  742): waitForAlarm result :4
,V/AlarmManager(  742): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,V/AlarmManager(  742): waitForAlarm result :4
,V/AlarmManager(  742): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,I/AMMetaDataParserService( 3111): Icon data: ResourceContacts2131623966android.intent.assistant.main.contact2130837529
,I/AMMetaDataParserService( 3111): Icon data: ResourceFavourites2131624366android.intent.assistant.main.favorite2130837528
,I/AMMetaDataParserService( 3111): Icon data: ResourceKeypad2131624567android.intent.assistant.main.keypad2130837530
,I/AMMetaDataParserService( 3111): getResourcePackageName:com.samsung.android.multiuser.install_only_owner
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.contacts.activities.ContactSelectionActivity
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.samsung.contacts.interactions.InteractionTabActivity
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.samsung.contacts.interactions.InteractionGroupSelectionActivity
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.contacts.DialtactsActivity
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.contacts.RecentCallsListActivity
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.contacts.activities.CallLogActivity
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.contacts.ContactsListActivity
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.contacts.activities.ContactsFrontDoor
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.contacts.DialtactsContactsEntryActivity
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.contacts.activities.JoinContactActivity
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.samsung.dialer.dialpad.VVM
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.contacts.preference.ContactsPreferenceActivity
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.contacts.common.list.AccountFilterActivity
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.contacts.common.list.CustomContactListFilterActivity
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.contacts.activities.ShowOrCreateActivity
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.contacts.activities.GroupDetailActivity
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.contacts.activities.GroupEditorActivity
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.contacts.quickcontact.QuickContactActivity
I/AMMetaDataParserService( 3111): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3111): getResourcePackageName:com.sec.android.multiwindow.activity.STYLE
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.contacts.ContactShortcut
I/AMMetaDataParserService( 3111): Resource data:Loop for running activityalias.DialShortcut
I/AMMetaDataParserService( 3111): Resource data:Loop for running activityalias.MessageShortcut
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.dialer.CallDetailActivity
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.samsung.dialer.calllog.CallDetailAllCallsActivity
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.samsung.dialer.calllog.CallDetailDeleteActivity
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.contacts.activities.ContactDetailActivity
I/AMMetaDataParserService( 3111): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3111): getResourcePackageName:assistant
,I/AMMetaDataParserService( 3111): Resource data:2131034112
I/AMMetaDataParserService( 3111): getResourceName:com.android.contacts:xml/assistant_detail
,I/AMMetaDataParserService( 3111): getResourceTypeNamexml
,I/SELinux ( 3320): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 3320):  
,I/AMMetaDataParserService( 3111): Icon data: ResourceAdd to favourites2131623990android.intent.assistant.detail.favorite2130837528
I/ActivityManager(  742): Killing 2369:com.google.android.onetimeinitializer/u0a13 (adj 15): empty #43
,I/AMMetaDataParserService( 3111): Icon data: ResourceRemove from favourites2131623991android.intent.assistant.detail.favorite2130837528
,I/SELinux ( 3320): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 3320):  
I/SELinux ( 3320):  
,I/SELinux ( 3320): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 3320): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 3320): >>>>> Normal User
,E/dalvikvm( 3320): >>>>> com.sec.knox.seandroid [ userId:0 | appId:1000 ]
,E/SELinux ( 3320): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,I/AMMetaDataParserService( 3111): Icon data: ResourceEdit2131623992android.intent.assistant.detail.edit2130837527
,D/TimaKeyStoreProvider( 3320): in addTimaSignatureService
,D/TimaKeyStoreProvider( 3320): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 3320): Added TimaKesytore provider
,I/AMMetaDataParserService( 3111): Icon data: ResourceDelete2131623993android.intent.assistant.detail.delete2130837526
,I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.samsung.contacts.detail.SelectContactInfoActivity
,I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.contacts.activities.ConfirmAddDetailActivity
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.contacts.activities.ContactEditorAccountsChangedActivity
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.contacts.activities.ContactEditorActivity
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.samsung.contacts.activities.RingtoneRecommendationHelperActivity
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.samsung.contacts.editor.AddAnotherFieldDialogActivity
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.contacts.common.test.FragmentTestActivity
,I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.contacts.activities.AttachPhotoActivity
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.contacts.activities.PhotoSelectionActivity
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.contacts.common.vcard.ImportVCardActivity
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.samsung.contacts.vcard.ImportVCardPreviewActivity
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.contacts.common.vcard.NfcImportVCardActivity
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.contacts.common.vcard.CancelActivity
,I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.contacts.common.vcard.SelectAccountActivity
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.contacts.common.vcard.ExportVCardActivity
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.samsung.contacts.vcard.ImportFinishActivity
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.samsung.contacts.activities.SIMContactSelectionActivity
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.samsung.contacts.activities.ServiceNumbers
,I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.samsung.contacts.activities.ServiceNumbersTabActivity
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.contacts.widget.PinnedHeaderListDemoActivity
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.contacts.NonPhoneActivity
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.samsung.contacts.favorite.FavoriteSelectionActivity
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.samsung.contacts.detail.SetDefaultActivity
,I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.samsung.contacts.group.GroupChangeOrderActivity
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.samsung.contacts.editor.EditGroupSelectionActivity
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.samsung.contacts.group.GroupMultiSelectionActivity
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.samsung.contacts.emergency.InteractionEmergencyMessageActivity
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.samsung.contacts.emergency.EmergencyMessageContactCreateActivity
,I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.samsung.contacts.emergency.EmergencyContactListDialogActivity
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.samsung.contacts.group.SubGroupDetailActivity
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.samsung.contacts.activities.GroupListActivity
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.samsung.aab.activity.SubscriberInfoCheckerActivity
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.samsung.aab.activity.ATTAB
,I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.samsung.aab.activity.AABReadyToUseActivity
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.samsung.aab.activity.SimCopy
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.samsung.aab.activity.AccessingSimCardInfo
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.samsung.aab.activity.WelcomeDecline
,I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.samsung.aab.activity.ContactsReadyToUseActivity
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.samsung.aab.activity.PhoneUpdateLater
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.samsung.aab.activity.PhoneUpdatePrompt
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.samsung.aab.activity.ActivationStatusActivity
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.samsung.aab.activity.StartSyncInitialActivity
,I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.samsung.aab.activity.FeaturesActivity
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.samsung.aab.activity.RegistrationFailure
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.samsung.aab.activity.SyncResponseActivity
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.samsung.aab.activity.ActivateLater
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.samsung.aab.activity.ZeroSimCardInfo
,I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.samsung.aab.activity.NewURLActivity
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.samsung.dialer.calllog.CallDurationActivity
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.samsung.dialer.calllog.CallDurationTabActivity
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.samsung.contacts.detail.LinkedContactActivity
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.samsung.dialer.impl.DialerTutorialActivity
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.samsung.contacts.impl.HelpPeopleActivity
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.samsung.contacts.impl.HelpEasyPeopleActivity
,I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.samsung.contacts.impl.HelpInteractionTabActivity
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.samsung.contacts.impl.HelpEasyInteractionTabActivity
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.samsung.contacts.impl.HelpSpeedDialActivity
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.samsung.contacts.impl.HelpContactEditorActivity
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.samsung.contacts.impl.HelpContactSelectionActivity
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.samsung.contacts.activities.EasyPeopleActivity
I/AMMetaDataParserService( 3111): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3111): getResourcePackageName:assistant
,I/AMMetaDataParserService( 3111): Resource data:2131034113
,I/AMMetaDataParserService( 3111): getResourceName:com.android.contacts:xml/assistant_main
,I/AMMetaDataParserService( 3111): getResourceTypeNamexml
,I/AMMetaDataParserService( 3111): Icon data: ResourceLogs2131624573android.intent.assistant.main.log2130837531
,W/ContextImpl( 3320): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1857 android.content.ContextWrapper.startService:506 android.content.ContextWrapper.startService:506 com.sec.knox.seandroid.service.MainReceiver.onReceive:47 android.app.ActivityThread.handleReceiver:2698 
,D/dalvikvm( 3111): GC_CONCURRENT freed 2257K, 35% free 12366K/18976K, paused 1ms+3ms, total 26ms
I/AMMetaDataParserService( 3111): Icon data: ResourceContacts2131623966android.intent.assistant.main.contact2130837529
,I/knox    ( 3320): MainReceiver.onReceive() : Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.sec.knox.seandroid/.receiver.MainReceiver (has extras) }
W/ContextImpl( 3320): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1857 android.content.ContextWrapper.startService:506 android.content.ContextWrapper.startService:506 com.sec.knox.seandroid.receiver.CommomReceiver.listeningToBootCompleted:59 com.sec.knox.seandroid.receiver.MainReceiver.onReceive:162 
,I/knox    ( 3320): MainReceiver.onReceive() END - - - - - : Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.sec.knox.seandroid/.receiver.MainReceiver (has extras) }
,D/knox    ( 3320): KNOXAgentService : onCreate()
,D/knox    ( 3320): KNOXAgentService : set alarms for deniallog and usage data upload
,I/System.out( 3196): pool-4-thread-1 calls detatch()
,D/knox    ( 3320): KNOXAgentService. startJobThread() start
D/knox    ( 3320): KNOXAgentService. JobThread()
,D/knox    ( 3320): KNOXAgentService. JobThread. notifyAll().
,D/knox    ( 3320): KNOXAgentService. startJobThread() wait
,I/SELinux ( 3334): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 3334):  
,D/knox    ( 3320): mKnoxAgentEngine.ELMEngine( context , reStart:true).
D/knox    ( 3320): KNOXAgentService : onDestroy().
,D/knox    ( 3320): ModuleBase.cancelAllAlarmManageModule()
,I/AMMetaDataParserService( 3111): Icon data: ResourceFavourites2131624366android.intent.assistant.main.favorite2130837528
,I/AMMetaDataParserService( 3111): Icon data: ResourceKeypad2131624567android.intent.assistant.main.keypad2130837530
,I/SELinux ( 3334): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 3334):  
I/SELinux ( 3334):  
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.samsung.contacts.interactions.EasyInteractionTabActivity
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.samsung.dialer.calllog.LogsFindoSearchResultsActivity
I/AMMetaDataParserService( 3111): Resource data:Inside bundle  check
I/SELinux ( 3334): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
I/AMMetaDataParserService( 3111): getResourcePackageName:android.app.searchable
,I/AMMetaDataParserService( 3111): Resource data:2131034116
,E/SELinux ( 3334): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 3334): >>>>> Normal User
E/dalvikvm( 3334): >>>>> com.sec.knox.knoxsetupwizardclient [ userId:0 | appId:1000 ]
I/AMMetaDataParserService( 3111): getResourceName:com.android.contacts:xml/findo_searchable
,I/AMMetaDataParserService( 3111): getResourceTypeNamexml
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.samsung.dialer.dialpad.RegularSearchActivity
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.samsung.dialer.interaction.InteractionRecentActivity
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.samsung.contacts.editor.SamsungAccountValidationCheckActivity
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.samsung.contacts.autolink.AutoLinkActivity
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.samsung.contacts.activities.EmergencyPeopleActivity
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.samsung.contacts.speeddial.SpeedDialActivity
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.samsung.contacts.businesscard.BusinesscardListActivity
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.samsung.contacts.businesscard.BusinesscardViewer
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.samsung.dialer.callmessage.CallMessageActivity
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.samsung.dialer.callmessage.RecentCallMessageActivity
,I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.samsung.dialer.callmessage.PhrasesEditActivity
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.samsung.dialer.callmessage.PhrasesDeleteActivity
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.samsung.dialer.callmessage.CallMessageEditActivity
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.samsung.contacts.activities.ContactResolverActivity
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.samsung.contacts.emergency.MyEmergencyInfoDetailActivity
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.samsung.contacts.emergency.MyEmergencyInfoEditorActivity
,E/SELinux ( 3334): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.sec.android.app.sbrowser.SBrowserMainActivity
I/AMMetaDataParserService( 3111): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 3111): getResourcePackageName:android.app.searchable
,I/AMMetaDataParserService( 3111): Resource data:2131099668
,I/AMMetaDataParserService( 3111): getResourceName:com.sec.android.app.sbrowser:xml/searchable
,I/AMMetaDataParserService( 3111): getResourceTypeNamexml
,D/TimaKeyStoreProvider( 3334): in addTimaSignatureService
I/AMMetaDataParserService( 3111): getResourcePackageName:assistantlist
,I/AMMetaDataParserService( 3111): Resource data:2131099650
I/AMMetaDataParserService( 3111): getResourceName:com.sec.android.app.sbrowser:xml/assistantlist
,I/AMMetaDataParserService( 3111): getResourceTypeNamexml
,D/TimaKeyStoreProvider( 3334): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 3334): Added TimaKesytore provider
,I/AMMetaDataParserService( 3111): Icon data: ResourceEnter URL2131558515android.intent.action.doInputURL2130837507
,I/AMMetaDataParserService( 3111): Icon data: ResourceWindow manager2131558482android.intent.action.doWindowManager2130837509
,E/KnoxSetupWizardClient( 3334): isShipMode : 1
,I/KnoxSetupWizardClient( 3334): onReceive : android.intent.action.BOOT_COMPLETED
,W/System.err( 3334): java.lang.IllegalArgumentException: Unknown package: com.sec.knox.setupwizardstub
I/AMMetaDataParserService( 3111): Icon data: ResourceNew window2131558765android.intent.action.doNewWindow2130837508
W/System.err( 3334): 	at android.os.Parcel.readException(Parcel.java:1469)
W/System.err( 3334): 	at android.os.Parcel.readException(Parcel.java:1419)
W/System.err( 3334): 	at android.content.pm.IPackageManager$Stub$Proxy.setApplicationEnabledSetting(IPackageManager.java:3458)
,W/System.err( 3334): 	at android.app.ApplicationPackageManager.setApplicationEnabledSetting(ApplicationPackageManager.java:1519)
W/System.err( 3334): 	at com.sec.knox.knoxsetupwizardclient.detector.StubPackageThread.processInternal(StubPackageThread.java:83)
,W/System.err( 3334): 	at com.sec.knox.knoxsetupwizardclient.detector.StubPackageThread.run(StubPackageThread.java:49)
,W/System.err( 3334): java.lang.IllegalArgumentException: Unknown package: com.sec.knox.containeragent
W/System.err( 3334): 	at android.os.Parcel.readException(Parcel.java:1469)
W/System.err( 3334): 	at android.os.Parcel.readException(Parcel.java:1419)
,W/System.err( 3334): 	at android.content.pm.IPackageManager$Stub$Proxy.setApplicationEnabledSetting(IPackageManager.java:3458)
W/System.err( 3334): 	at android.app.ApplicationPackageManager.setApplicationEnabledSetting(ApplicationPackageManager.java:1519)
W/System.err( 3334): 	at com.sec.knox.knoxsetupwizardclient.detector.StubPackageThread.disablePackage(StubPackageThread.java:132)
W/System.err( 3334): 	at com.sec.knox.knoxsetupwizardclient.detector.StubPackageThread.processInternal(StubPackageThread.java:103)
,W/System.err( 3334): 	at com.sec.knox.knoxsetupwizardclient.detector.StubPackageThread.run(StubPackageThread.java:49)
,I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.sec.android.app.sbrowser.mainactivity.controller.SecPowerControl
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.sec.android.app.sbrowser.bookmarksDb.ui.ShowBookmarksActivity
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.sec.android.app.sbrowser.quickaccess.ui.AddQuickAccessActivity
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.sec.android.app.sbrowser.bookmarksDb.ui.SelectBookmarkFolderActivity
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.sec.android.app.sbrowser.bookmarksDb.ui.CreateBookmarkFolderActivity
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.sec.android.app.sbrowser.history.ui.HistoryActivity
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.sec.android.app.sbrowser.multiwindow.MultiTabActivity
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.sec.android.app.sbrowser.preferences.Settings
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.sec.android.app.sbrowser.reader.ui.ReaderActivity
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.sec.android.app.sbrowser.extractmode.ExtracterActivity
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.sec.android.app.sbrowser.readinglist.activity.ReadingListActivity
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.sec.android.app.sbrowser.bookmarksDb.ui.DeleteBookmarksActivity
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.sec.android.app.sbrowser.bookmarksDb.ui.MoveToFolderActivity
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.sec.android.app.sbrowser.synctab.ui.SynctabActivity
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.sec.android.app.sbrowser.preferences.AutofillFormDelete
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.sec.android.app.sbrowser.bookmarksDb.ui.EditBookmarkFolderActivity
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.sec.android.app.sbrowser.bookmarksDb.ui.ReOrderBookmarksActivity
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.sec.android.app.sbrowser.common.DataChargingDialog
I/AMMetaDataParserService( 3111): Resource data:Loop for running activityorg.samsung.content.sbrowser.pipette.SbrPipetteAnimationGLActivity
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.sec.android.app.sbrowser.widget.BookmarkWidgetConfigure
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.sec.android.app.sbrowser.preferences.SBrowserProfileEditorContainerActivity
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.sec.android.app.sbrowser.bookmarksDb.ui.AddBookmarkActivity
,I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.sec.android.app.sbrowser.synctab.ui.DeleteSyncTabActivity
,D/ShortcutReceiver( 3334):  ShortcutReceiver onReceive() intent: android.intent.action.BOOT_COMPLETED
,I/yash    ( 3334): setDisableWidget>size:0
,I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.email.activity.setup.SSLCertValidationActivity
,I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.email.activity.Welcome
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.email.activity.UpgradeAccounts
,I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.email.activity.setup.snc.AccountSetupWizard
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.email.activity.setup.snc.VZWSetupWizard
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.email.activity.setup.snc.AccountSetupSncRestoreAccounts
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.email.activity.setup.snc.SncRestoreAccounts
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.email.activity.setup.snc.AccountSetupSncRestoreOptions
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.email.activity.setup.snc.AccountSetupSncNames
,I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.email.activity.setup.snc.AccountSetupSncExchangeAccounts
,I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.email.activity.setup.snc.AccountSetupSncAccountsLogin
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.email.activity.setup.LDAPClientSettings
,I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.email.activity.LDAPAccountsList
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupBasics
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.email.DataConnection
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupAccountType
,I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupIncoming
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupOutgoing
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.email.activity.cba.ImportCertificate
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.email.activity.cba.InstalledCertificatesList
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupExchange
,I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupAutoDiscover
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupOptions
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupNames
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupDisclaimerWeb
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSettingsXL
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSettingsAddRulesforFiltering
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.email.activity.setup.AddPrioritySenderActivity
,I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSecurity
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.email.activity.setup.AccountPreSetup
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.email.activity.SaveasActivity
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.email.activity.Debug
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.email.activity.setup.TestHarnessMainActivity
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.email.activity.setup.TestHarnessManualSettingsScreen
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.email.activity.MessageListXL
,I/AMMetaDataParserService( 3111): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3111): getResourcePackageName:assistant
,I/AMMetaDataParserService( 3111): Resource data:2131099667
,I/SELinux ( 3347): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 3347):  
I/AMMetaDataParserService( 3111): getResourceName:com.android.email:xml/email_assistant_menu
,I/AMMetaDataParserService( 3111): getResourceTypeNamexml
I/ActivityManager(  742): Killing 2396:com.samsung.klmsagent/u0a18 (adj 15): empty #43
,I/AMMetaDataParserService( 3111): Icon data: ResourceDrawer menu2131297956com.android.email.intent.messagelistfragment.drawer2130837559
,I/AMMetaDataParserService( 3111): Icon data: ResourceMessage marked as complete2131296812com.android.email.intent.messageviewfragment.favorite2130837558
I/SELinux ( 3347): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 3347):  
I/SELinux ( 3347):  
,I/SELinux ( 3347): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 3347): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 3347): >>>>> Normal User
,E/dalvikvm( 3347): >>>>> com.LocalFota [ userId:0 | appId:10110 ]
,E/SELinux ( 3347): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 3347): in addTimaSignatureService
,D/TimaKeyStoreProvider( 3347): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 3347): Added TimaKesytore provider
,I/GAV2    ( 2181): Thread[GAThread,5,main]: No campaign data found.
,I/AMMetaDataParserService( 3111): Icon data: ResourceFlagged message2131296810com.android.email.intent.messageviewfragment.favorite2130837558
,I/GAv4-SVC( 1758): Google Analytics 8.4.89 is starting up.
,I/AMMetaDataParserService( 3111): Icon data: ResourceUnflagged message2131296811com.android.email.intent.messageviewfragment.favorite2130837558
,I/DBG_WSS_LF( 3347): [Not Defined][Line:75][onCreate] LocalFOTA Application Start !
,W/ActivityManager(  742): Permission Denial: getCurrentUser() from pid=3347, uid=10110 requires android.permission.INTERACT_ACROSS_USERS
I/DBG_WSS_LF( 3347): [20.0040.140326][Line:27][<init>] First call
,I/AMMetaDataParserService( 3111): Icon data: ResourceStarred message2131296815com.android.email.intent.messageviewfragment.favorite2130837560
,I/AMMetaDataParserService( 3111): Icon data: ResourceUnstarred message2131296816com.android.email.intent.messageviewfragment.favorite2130837560
,I/DBG_WSS_LF( 3347): [20.0040.140326][Line:27][onReceive] android.intent.action.BOOT_COMPLETED
,I/DBG_WSS_LF( 3347): [20.0040.140326][Line:31][onReceive] *** boot complete ***
,I/DBG_WSS_LF( 3347): [20.0040.140326][Line:441][xLFGetLFStatus] !!! Status -1 !!!
,I/DBG_WSS_LF( 3347): [20.0040.140326][Line:41][onReceive] nStatus : -1
,I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.email.activity.setup.MailboxSettings
,I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.email.activity.UNCSearchResultsList
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.email.activity.EmailDocSearchQuery
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.email.activity.MessageViewDisplayModePopup
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.email.activity.SelectGroup
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.email.activity.SavedEmail
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.email.activity.MessageFileView
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.pgp.CreateKeySettingsActivity
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSettingsHtmlSignature
,I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.email.activity.MessageCompose
I/AMMetaDataParserService( 3111): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3111): getResourcePackageName:android.app.spellscroll
,I/AMMetaDataParserService( 3111): Resource data:2131099689
I/AMMetaDataParserService( 3111): getResourceName:com.android.email:xml/spellscroll
I/AMMetaDataParserService( 3111): getResourceTypeNamexml
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.email.activity.SelectMapActivity
,I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.email.activity.setup.OoOSetMessage
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.email.activity.CustomizeDate
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.email.activity.QuickReplyActivity
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.email.activity.SettingsReservationActivity
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.email.activity.DebugActivity
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupBasicsChoiceProviderForKOR
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSoundNotiSetup
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSoundNotiGeneralPreference
,I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.email.activity.SearchActivity
I/AMMetaDataParserService( 3111): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3111): getResourcePackageName:android.app.searchable
I/AMMetaDataParserService( 3111): Resource data:2131099685
,I/AMMetaDataParserService( 3111): getResourceName:com.android.email:xml/searchable
I/AMMetaDataParserService( 3111): getResourceTypeNamexml
I/AMMetaDataParserService( 3111): getResourcePackageName:android.app.default_searchable
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.email.activity.MessageComposeDrawingModePopup
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.email.activity.utils.airjump.EmailAirScrollTryActivity
,I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.android.email.activity.SmartStayActivity
,I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.sec.android.app.camera.Camera
I/AMMetaDataParserService( 3111): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3111): getResourcePackageName:com.android.keyguard.layout
,I/AMMetaDataParserService( 3111): Resource data:2130903052
,I/SELinux ( 3367): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 3367):  
,I/AMMetaDataParserService( 3111): getResourceName:com.sec.android.app.camera:layout/keyguard_widget
I/AMMetaDataParserService( 3111): getResourceTypeNamelayout
I/AMMetaDataParserService( 3111): getResourcePackageName:assistant
,I/AMMetaDataParserService( 3111): Resource data:2131034112
I/AMMetaDataParserService( 3111): getResourceName:com.sec.android.app.camera:xml/assistant
,I/AMMetaDataParserService( 3111): getResourceTypeNamexml
I/ActivityManager(  742): Killing 2431:com.sec.android.app.mss/u0a21 (adj 15): empty #43
,I/AMMetaDataParserService( 3111): Icon data: ResourceSwitch camera2131428066android.intent.action.switchcamera2130837508
,I/AMMetaDataParserService( 3111): Icon data: ResourceGallery2131427734android.intent.action.switchgallery2130837507
I/SELinux ( 3367): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 3367):  
I/SELinux ( 3367):  
,I/SELinux ( 3367): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 3367): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 3367): >>>>> Normal User
,E/dalvikvm( 3367): >>>>> com.sec.android.app.mt [ userId:0 | appId:1000 ]
,E/SELinux ( 3367): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.sec.android.app.camera.Camcorder
,I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.sec.android.app.camera.QuickShot
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.sec.android.app.camera.DummyActivity
I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.sec.android.app.camera.CropImage
,I/AMMetaDataParserService( 3111): Resource data:Loop for running activitycom.sec.android.app.shootingmodemanager.ManageShootingModeActivity
,D/TimaKeyStoreProvider( 3367): in addTimaSignatureService
,D/TimaKeyStoreProvider( 3367): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 3367): Added TimaKesytore provider
I/ActivityManager(  742): Killing 2435:com.android.chrome/u0a81 (adj 15): empty #43
,D/StatusChecker( 3367): onReceive : android.intent.action.BOOT_COMPLETED
,I/SELinux ( 3381): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 3381):  
I/ActivityManager(  742): Killing 2460:com.sec.android.app.msa/u0a23 (adj 15): empty #43
,I/SELinux ( 3381): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 3381):  
I/SELinux ( 3381):  
,I/SELinux ( 3381): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 3381): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 3381): >>>>> Normal User
,E/dalvikvm( 3381): >>>>> com.samsung.android.sconnect [ userId:0 | appId:10133 ]
,E/SELinux ( 3381): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 3381): in addTimaSignatureService
,D/TimaKeyStoreProvider( 3381): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 3381): Added TimaKesytore provider
,E/SMD     (  242): DCD ON
,D/QuickConnect( 3381): PeriphStartReceiver.onReceive - android.intent.action.BOOT_COMPLETED
,D/QuickConnect( 3381): Utils.setQCRunningSetting - set : 0
,W/BackupManagerService(  742): dataChanged but no participant pkg='com.android.providers.settings' uid=10133
I/QuickConnect( 3381): PeriphStartReceiver.onReceive - USER_OWNER care ACTION_BOOT_COMPLETED. run P service
V/QuickConnect( 3381): SconnectManager.getInstance - () return existing instance null
W/ContextImpl( 3381): Implicit intents with startService are not safe: Intent { act=com.samsung.android.sconnect.periph.START_SERVICE } android.content.ContextWrapper.startServiceAsUser:517 android.content.ContextWrapper.startServiceAsUser:517 com.samsung.android.sconnect.periph.PeriphStartReceiver.onReceive:30 
I/QuickConnect( 3381): PeriphService.onCreate - [START]
,I/SELinux ( 3396): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 3396):  
,I/QuickConnect( 3381): PeriphService.onCreate - [START] USER_OWNER
,D/QuickConnect( 3381): PeriphService.setProcessForeground - Build.VERSION.SDK_INT = 19
,I/QuickConnect( 3381): PeriphService.setProcessForeground - true of JB_MR2 complete 
I/QuickConnect( 3381): PeriphService.setState - 0 >> 1
,V/QuickConnect( 3381): PeriphService.runService - 
,I/QuickConnect[1.1][2] ( 3381): SconnectManager.SconnectManager - initiate from com.samsung.android.sconnect.periph.PeriphService@42609b90
I/QuickConnect[1.1][2] ( 3381): SconnectManager.SconnectManager - set getApplicationContext android.app.Application@42601c18
,D/QuickConnect[1.1][2] ( 3381): SconnectManager.registerBroadcast - --
,D/QuickConnect[1.1][2] ( 3381): SconnectManager.SconnectManager - REQUEST_ID :  1
,D/QuickConnect[1.1][2] ( 3381): ScanThread.ScanThread - created!
,V/QuickConnect[1.1][2] ( 3381): BluetoothHelper.BluetoothHelper - 
,D/QuickConnect[1.1][2] ( 3381): BluetoothHelper.registerBluetoothAdapterReceiver - mIsBluetoothAdapterReceiver = false
,V/QuickConnect[1.1][2] ( 3381): BleHelper.BleHelper - Constructor
I/SELinux ( 3396): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 3396):  
I/SELinux ( 3396):  
,I/SELinux ( 3396): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 3396): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 3396): >>>>> Normal User
,E/dalvikvm( 3396): >>>>> com.sec.android.service.bezel [ userId:0 | appId:1000 ]
,E/SELinux ( 3396): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 3396): in addTimaSignatureService
,D/TimaKeyStoreProvider( 3396): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 3396): Added TimaKesytore provider
,E/QuickConnect[1.1][2] ( 3381): BleHelper.startScan - not isGattServiceReady. Try to BLE On calling addLeRadioReference()
,D/BluetoothRadioManager( 3381): addLeRadioReference: Add CB  com.samsung.android.sconnect.common.net.BleHelper$GattServiceStateChangeCallback@4261d0b0
D/BluetoothRadioManager( 3381):  addRadioReference enabled = false
,D/BluetoothRadioManager( 3381):  BLE Radio count is : 1
,D/BluetoothRadioManager( 3381): addRadioReference()  registerRadioClient mUUID = daa00bb4-2e1e-4a61-8bcc-9411d5a762eb
,D/BluetoothManagerService(  742): foregroundUser: 0
,E/BluetoothManagerService(  742): Package is exist.
,D/BluetoothRadioManager( 3381): addLeRadioReference: isRadioEnabled() =  false
,I/bluedroid( 1948): update_radio_count
D/BluetoothAdapterState( 1948): CURRENT_STATE=ON, MSG = USER_TURN_ON_RADIO
V/QuickConnect[1.1][2] ( 3381): BleHelper.mSearchWearable - true
I/BluetoothAdapterState( 1948): Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=false
D/BluetoothAdapterState( 1948): CURRENT_STATE=PENDING, MSG = BEGIN_ENABLE_RADIO, isTurningOnRadio=true, isTurningOffRadio=false
,I/bluedroid( 1948): enable
,E/bt-btif ( 1948): btif_handle_bluetooth_enable_evt: btif_core_radio_ref_count:2
E/bt-btif ( 1948): btif_sock_init, radio_req:1, rfc_init:1, vhci_init:1
D/BluetoothAdapterState( 1948): CURRENT_STATE=PENDING, MSG = ENABLED_RADIO, isTurningOnRadio=true, isTurningOffRadio=false
I/BluetoothAdapterState( 1948): Bluetooth adapter radio state changed: 14
,D/BluetoothAdapterService( 1948): Bluetooth PBAP supproted is true
D/BluetoothAdapterService( 1948): updateAdapterState state is 14
D/BluetoothAdapterService( 1948): Broadcasting updateAdapterState() to 1 receivers.
D/BluetoothAdapterService( 1948): Autoconnection is available 
,D/BluetoothAdapterService( 1948): updateAdapterState prevState = 12newState = 14
I/BluetoothAdapterState( 1948): Entering On State from state = 12
,D/BluetoothManagerService(  742): Broadcasting Radio() to 1 Radio Mgr receivers.
,D/BluetoothRadioManager( 3381): onBTRadioStateChange:  up = true
,E/QuickConnect[1.1][2] ( 3381): BleHelper.onGattServiceStateChange - up = true, BluetoothGatt is android.bluetooth.IBluetoothGatt$Stub$Proxy@4264b9b0
,E/QuickConnect[1.1][2] ( 3381): BleHelper.onGattServiceStateChange - Radio turned on
,V/QuickConnect[1.1][2] ( 3381): UpnpHelper.UpnpHelper - 
,V/QuickConnect[1.1][2] ( 3381): JmdnsHelper.JmdnsHelper - Constructor
,V/QuickConnect[1.1][2] ( 3381): P2pHelper.P2pHelper - EXEC
,D/QuickConnect[1.1][2] ( 3381): p2pHelperWorkThread.p2pHelperWorkThread - created!
,D/QuickConnect[1.1][2] ( 3381): WifiHelper.WifiHelper -  -- 
,D/WifiDisplayAdapter(  742): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
I/QuickConnect[1.1][2] ( 3381): CentralActionManager.CentralActionManager - EXEC
V/QuickConnect[1.1][2] ( 3381): BluetoothOppActionHelper.BluetoothOppActionHelper - 
V/QuickConnect[1.1][2] ( 3381): GroupVoiceTalkActionHelper.GroupVoiceTalkActionHelper -  --
V/QuickConnect[1.1][2] ( 3381): SmartHomeActionHelper.SmartHomeActionHelper - --
V/QuickConnect[1.1][2] ( 3381): ScreenMirrorActionHelper.ScreenMirrorActionHelper - 
V/QuickConnect[1.1][2] ( 3381): BluetoothActionHelper.BluetoothActionHelper - 
D/BezelQuickConnect( 3396): BezelBroadcastReceiver - onReceive : android.intent.action.BOOT_COMPLETED
D/BezelQuickConnect( 3396): BezelBroadcastReceiver - StartBezelInteractionService
D/BezelQuickConnect( 3396): BezelManagerService - setProcessForeground, Build.VERSION.SDK_INT = 19
I/BezelQuickConnect( 3396): BezelManagerService - setProcessForeground, true of JB_MR2 complete 
,D/BezelQuickConnect( 3396): BezelBroadcastReceiver - onReceive : Send to quickpanel - service.ENABLED
,V/PhoneStatusBar( 1066): onReceive: Intent { act=com.sec.android.sconnect.service.ENABLED flg=0x10 }mQconnectEnable = true
W/ContextImpl( 3396): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 android.content.ContextWrapper.sendBroadcast:377 android.content.ContextWrapper.sendBroadcast:377 com.sec.android.service.bezel.BezelBroadcastReceiver.onReceive:40 android.app.ActivityThread.handleReceiver:2698 
,E/NetworkSettingsReceiver( 1704): onReceive: android.intent.action.BOOT_COMPLETED
D/STATUSBAR-PhoneStatusBar( 1066): showHideQConnectLayout userID : 0 emMode:false mQconnectEnable:true QconnectService:true
,E/BluetoothHeadset( 3381): BTStateChangeCB is registed
,E/BluetoothHeadset( 3381): BluetoothHeadset service is binded
,I/QuickConnect[1.1][2] ( 3381): SconnectManager.getInstance - make new instance com.samsung.android.sconnect.SconnectManager@4260b888
,V/QuickConnect[1.1][2] ( 3381): SconnectManager.getInstance - return existing instance com.samsung.android.sconnect.SconnectManager@4260b888
,V/QuickConnect[1.1][2] ( 3381): PreDiscoveryHelper.PreDiscoveryHelper -  -- 
,D/QuickConnect[1.1][2] ( 3381): PreDiscoveryHelper.setVisibilityFromSystemDb - --
,D/QuickConnect[1.1][2] ( 3381): Utils.getFromDb -  Key[quick_connect_allow_connect], isEnabled [0] /   <0 : Disable, 1 : Enable>
,D/QuickConnect[1.1][2] ( 3381): Utils.getFromDb -  Key[quick_connect_contact_only], isEnabled [1] /   <0 : Disable, 1 : Enable>
D/QuickConnect[1.1][2] ( 3381): PreDiscoveryHelper.setVisibilityFromSystemDb - isAllowToConnect : false, isContactOnly : true, visibilitySetting : 2
D/QuickConnect[1.1][2] ( 3381): PreDiscoveryHelper.changeResponseSetting - changed: 2
V/QuickConnect[1.1][2] ( 3381): PreDiscoveryHelper.updateAdvData - 
,V/QuickConnect[1.1][2] ( 3381): SconnectManager.getInstance - () return existing instance com.samsung.android.sconnect.SconnectManager@4260b888
,W/BroadcastQueue(  742): Permission Denial: receiving Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 (has extras) } to com.android.calendar/.magazine.CalendarUpdateRelatedDataReceiver requires android.permission.RECEIVE_BOOT_COMPLETED due to sender null (uid 1000)
D/QuickConnect[1.1][2] ( 3381): WifiHelper.isEnableMobileAP - HOTSPOT Disabled
,I/SELinux ( 3413): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 3413):  
,V/QuickConnect[1.1][2] ( 3381): PreDiscoveryHelper.updateRespTarget - 
,D/QuickConnect[1.1][2] ( 3381): PreDiscoveryHelper.initializeAdvData - 
V/QuickConnect[1.1][2] ( 3381): PreDiscoveryHelper.initializeAdvData - name: Galaxy S5-2(11)
D/QuickConnect[1.1][2] ( 3381): PreDiscoveryHelper.initializeAdvData - name selected: Galaxy S5-2(11)
,V/QuickConnect[1.1][2] ( 3381): CONTACT_Info.getMyMobileNumber - 
,D/QuickConnect[1.1][2] ( 3381): CONTACT_Info.getAccountNumber - ($)
,I/QuickConnect[1.1][2] ( 3381): CONTACT_Info.getMyMobileNumber - null 
,D/QuickConnect[1.1][2] ( 3381): NetUtil.getP2pMacFromWifiMac - ($)
,V/QuickConnect[1.1][2] ( 3381): SconnectManager.getInstance - () return existing instance com.samsung.android.sconnect.SconnectManager@4260b888
,W/QuickConnect[1.1][2] ( 3381): AppPackageUtil.isAppInstalled - Not installed - com.sec.android.emeeting.b2c.hancom
,D/QuickConnect[1.1][2] ( 3381): SconnectManager.setServiceCapability - [Downloaded App] Not installed!! - com.sec.android.emeeting
,D/QuickConnect[1.1][2] ( 3381): AppPackageUtil.isStubApk - but Stub version[2.7.025] of com.samsung.groupcast
W/QuickConnect[1.1][2] ( 3381): AppPackageUtil.isAppInstalled - this is Stub - com.samsung.groupcast
D/QuickConnect[1.1][2] ( 3381): SconnectManager.setServiceCapability - [Downloaded App] Not installed!! - com.samsung.groupcast
,W/QuickConnect[1.1][2] ( 3381): AppPackageUtil.isAppInstalled - Not installed - com.sec.android.sidesync30
,D/QuickConnect[1.1][2] ( 3381): SconnectManager.setServiceCapability - [Downloaded App] Not installed!! - com.sec.android.sidesync30
,D/QuickConnect[1.1][2] ( 3381): PeriphService.registerUserReceiver - mIsUserReceiver == false
,I/QuickConnect[1.1][2] ( 3381): PeriphService.onStartCommand - USER_OWNER
I/QuickConnect[1.1][2] ( 3381): PeriphService.onStartCommand - Intent { act=com.samsung.android.sconnect.periph.START_SERVICE } flags[0] startId[1]
,I/QuickConnect[1.1][2] ( 3381): PeriphService.onStartCommand - Action: com.samsung.android.sconnect.periph.START_SERVICE
,D/QuickConnect[1.1][2] ( 3381): SconnectManager.INetworkStateListener, onEnabled - mNetworkState : 4
,D/QuickConnect[1.1][2] ( 3381): P2pHelper.onReceive - P2P_CONNECTION_CHANGED : 
,D/QuickConnect[1.1][2] ( 3381): SconnectManager.INetworkStateListener, onDisconnected - networkType : 4
,D/BluetoothA2dp( 3381): Proxy object connected
D/WifiP2pService(  742): InactiveState{ what=139287 }
D/WifiP2pService(  742): P2pEnabledState{ what=139287 }
,D/WifiP2pService(  742): DefaultState{ what=139287 }
D/QuickConnect[1.1][2] ( 3381): A2dpProfile.onServiceConnected - Bluetooth service connected
,D/QuickConnect[1.1][2] ( 3381): HeadsetProfile.onServiceConnected - Bluetooth service connected
,D/BluetoothInputDevice( 3381): Proxy object connected
,D/QuickConnect[1.1][2] ( 3381): HidProfile.onServiceConnected - Bluetooth service connected
I/SELinux ( 3413): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 3413):  
I/SELinux ( 3413):  
,I/SELinux ( 3413): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
D/QuickConnect[1.1][2] ( 3381): P2pHelper.requestGroupInfo  - onGroupInfoAvailable- null
,E/SELinux ( 3413): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 3413): >>>>> Normal User
,E/dalvikvm( 3413): >>>>> com.sec.android.app.camera [ userId:0 | appId:10147 ]
,E/SELinux ( 3413): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 3413): in addTimaSignatureService
,D/TimaKeyStoreProvider( 3413): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 3413): Added TimaKesytore provider
,W/dalvikvm( 3413): Refusing to reopen boot DEX '/system/framework/seccamera.jar'
,I/SELinux ( 3427): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 3427):  
I/ActivityManager(  742): Killing 1184:com.samsung.android.MtpApplication/1000 (adj 15): empty #43
,I/QuickConnect[1.1][2] ( 3381): BleAdvertiser.BleAdvertiser - Constructor
,D/BluetoothGattServer( 3381): registerCallback()
,D/BluetoothGattServer( 3381): registerCallback() - UUID=01f24cdf-d65b-4fd7-b0ab-3eb79276a447
,D/BtGatt.GattService( 1948): registerServer() - UUID=01f24cdf-d65b-4fd7-b0ab-3eb79276a447
D/BtGatt.btif( 1948): btif_gatts_register_app
D/BtGatt.btif( 1948): btgatts_handle_event: Event 2000
E/bt-btif ( 1948): register application first_unuse rcb_idx = 0
,D/BtGatt.btif( 1948): btapp_gatts_handle_cback: Event 0
,D/BtGatt.GattService( 1948): onServerRegistered() - UUID=01f24cdf-d65b-4fd7-b0ab-3eb79276a447, serverIf=5
,D/BluetoothGattServer( 3381): onServerRegistered() - status=0 serverIf=5
,I/SELinux ( 3427): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 3427):  
I/SELinux ( 3427):  
,I/SELinux ( 3427): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 3427): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 3427): >>>>> Normal User
,E/dalvikvm( 3427): >>>>> com.sec.android.inputmethod [ userId:0 | appId:1000 ]
,E/SELinux ( 3427): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 3427): in addTimaSignatureService
,D/TimaKeyStoreProvider( 3427): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 3427): Added TimaKesytore provider
,I/SELinux ( 3439): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 3439):  
I/ActivityManager(  742): Killing 2480:com.sec.pcw.device/1000 (adj 15): empty #43
,D/BluetoothAdapterService(1113652040)( 1948): unRegister RemoteMessageListener
,D/HeadsetService( 1948): registerMessageListener
D/HeadsetStateMachine( 1948): Disconnected process message: 80
D/BluetoothAdapterState( 1948): CURRENT_STATE=ON, MSG = USER_TURN_OFF
D/HeadsetStateMachine( 1948): processUnRegisterMessageListener : 2
I/BluetoothAdapterState( 1948): Bluetooth adapter state changed: 12-> 13
D/BluetoothAdapterService( 1948): Bluetooth PBAP supproted is true
,D/BluetoothAdapterService( 1948): updateAdapterState state is 13
,I/BluetoothPbapService( 1948): action: android.bluetooth.adapter.action.STATE_CHANGED, state: 13
,E/bt-btif ( 1948): bta_jv_rfcomm_stop_server
,D/BluetoothAdapterService( 1948): Broadcasting updateAdapterState() to 1 receivers.
,D/BluetoothAdapterService( 1948): Autoconnection is available 
,D/BluetoothAdapterService( 1948): updateAdapterState prevState = 12newState = 13
,D/BluetoothAdapterService( 1948): terminating service from this receiver
,W/ContextImpl( 1948): Implicit intents with startService are not safe: Intent { act=com.samsung.ble.ACTION_SERVICE_BLE_AUTO_CONNECT } android.content.ContextWrapper.stopService:511 com.android.bluetooth.btservice.AdapterService.updateAdapterState:657 com.android.bluetooth.btservice.AdapterState.notifyAdapterStateChange:586 
D/GKI_LINUX( 1948): acquire_my_wake_lock(), g_wake_lock_fd:91, g_wake_unlock_fd:92, wake_lock_acquired:0
,I/BluetoothAdapterState( 1948): Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
W/InputMethodManagerService(  742): InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
I/InputMethodManagerService(  742): [BT Setting State] State =13
,D/PhoneApp( 1239): mReceiver: BluetoothAdapter.ACTION_STATE_CHANGED: 13
,I/QuickConnect[1.1][2] ( 3381): BluetoothHelper.ACTION_STATE_CHANGED - STATE_TURNING_OFF
D/BluetoothAdapterState( 1948): CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
,E/bt-btif ( 1948): btif_sock_cleanup, sock_thread_handle:6, rfc_init:1, vhci_init:1
E/bt-btif ( 1948): bta_jv_rfcomm_stop_server
,E/bt-btif ( 1948): bta_jv_rfcomm_stop_server
,D/btif_config_util( 1948): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,D/STATUSBAR-IconMerger( 1066): checkOverflow(336), More:false, Req:false Child:1
I/WifiManager( 2894): packageName : com.example.hello
I/WifiManager( 2894): setWifiEnabled : false
I/WifiService(  742): setWifiEnabled: false pid=2894, uid=10181
D/IOP_DB_BT( 1948): db_close: nbr users 0
D/IOP_DB_BT( 1948): db_close: free database
,I/jxcore-log( 2894): ****TEST TOOK:  5154  ms ****
I/jxcore-log( 2894): 
,I/jxcore-log( 2894): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 2894): 
I/wpa_supplicant( 1959): reset timer : RESET_TIMER 0
,I/wpa_supplicant( 1959): wlan0: Setting scan request: 0 sec 0 usec
I/wpa_supplicant( 1959): Scan requested (ret=0) - scan timeout 30 seconds
W/Settings(  742): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/WifiStateMachine(  742): ignore requestNetworkTransitionWakelock airplane:true
I/SELinux ( 3439): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 3439):  
I/SELinux ( 3439):  
I/SELinux ( 3439): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 3439): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 3439): >>>>> Normal User
,E/dalvikvm( 3439): >>>>> com.android.email [ userId:0 | appId:10155 ]
D/CommandListener(  239): Clearing all IP addresses on wlan0
,E/SELinux ( 3439): [DEBUG] seapp_context_lookup: seinfoCategory = platform
D/WifiP2pService(  742): InactiveState{ what=143375 }
D/WifiP2pService(  742): P2pEnabledState{ what=143375 }
D/STATUSBAR-NetworkController_dual( 1066): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
D/StatusBar.NetworkController_dual( 1066): mMobileLabelViews start
D/StatusBar.NetworkController_dual( 1066): mMobileLabelViews set mobileLabel[SIM_0] =
D/StatusBar.NetworkController_dual( 1066): mMobileLabelViews GONE
D/StatusBar.NetworkController_dual( 1066): mMobileLabelViews2 set mobileLabel[SIM_1] =
D/StatusBar.NetworkController_dual( 1066): mMobileLabelViews2 GONE
D/StatusBar.NetworkController_dual( 1066): mSingleMobileLabelViews set : simMode = 0
D/StatusBar.NetworkController_dual( 1066): mSingleMobileLabelViews set as slot1`s
V/AlarmManager(  742): waitForAlarm result :4
,I/WifiTrafficPoller(  742): evaluateTrafficStatsPolling
D/ConnectivityService(  742): ConnectivityChange for WIFI: DISCONNECTED/DISCONNECTED
D/ConnectivityService(  742): tryFailover: set mActiveDefaultNetwork=-1, prevNetType=1
E/ConnectivityService(  742): net.tcp.usercfg.default not found in system default properties
E/ConnectivityService(  742): Can't set delayed ACK size:java.io.FileNotFoundException: /sys/kernel/ipv4/tcp_use_userconfig: open failed: ENOENT (No such file or directory)
E/ConnectivityService(  742): net.tcp.delack.default not found in system default properties
E/ConnectivityService(  742): Can't set delayed ACK size:java.io.FileNotFoundException: /sys/kernel/ipv4/tcp_delack_seg: open failed: ENOENT (No such file or directory)
D/STATUSBAR-NetworkController_dual( 1066): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
D/SignalClusterView_dual( 1066): wifi: VISIBLE sig=2130837979 act=2130837946
D/SignalClusterView_dual( 1066): mMobileDataState=0 mMobileDataState2=0
D/SignalClusterView_dual( 1066): apply() mSeparateMobileGroup=8
D/STATUSBAR-NetworkController_dual( 1066): refreshSignalCluster - setNWBoosterIndicators(false)
D/ConnectivityService(  742): Attempting to switch to mobile
D/SignalClusterView_dual( 1066): wifi: GONE sig=2130837981 act=2130837946
D/ConnectivityService(  742): Attempting to switch to BLUETOOTH_TETHER
D/SignalClusterView_dual( 1066): mMobileDataState=0 mMobileDataState2=0
D/SignalClusterView_dual( 1066): apply() mSeparateMobileGroup=8
D/SignalClusterView_dual( 1066): wifi: GONE sig=2130837981 act=2130837946
D/SignalClusterView_dual( 1066): mMobileDataState=0 mMobileDataState2=0
D/SignalClusterView_dual( 1066): apply() mSeparateMobileGroup=8
D/SignalClusterView_dual( 1066): wifi: GONE sig=2130837981 act=2130837946
D/SignalClusterView_dual( 1066): mMobileDataState=0 mMobileDataState2=0
D/SignalClusterView_dual( 1066): apply() mSeparateMobileGroup=8
D/SignalClusterView_dual( 1066): wifi: GONE sig=2130837981 act=2130837946
D/SignalClusterView_dual( 1066): mMobileDataState=0 mMobileDataState2=0
D/SignalClusterView_dual( 1066): apply() mSeparateMobileGroup=8
D/StatusBar.NetworkController_dual( 1066): mMobileLabelViews start
D/StatusBar.NetworkController_dual( 1066): mMobileLabelViews set mobileLabel[SIM_0] =No service.
D/StatusBar.NetworkController_dual( 1066): mMobileLabelViews GONE
D/StatusBar.NetworkController_dual( 1066): mMobileLabelViews2 set mobileLabel[SIM_1] =No service.
D/StatusBar.NetworkController_dual( 1066): mMobileLabelViews2 GONE
D/StatusBar.NetworkController_dual( 1066): mSingleMobileLabelViews set : simMode = 0
,D/StatusBar.NetworkController_dual( 1066): mSingleMobileLabelViews set as slot1`s
E/WifiStateMachine(  742): Error! unhandled message{ when=-1ms what=135188 target=com.android.internal.util.StateMachine$SmHandler }
,V/RouteController(  239): /system/bin/ip -6 route del default table 2 2>&1
,E/WifiStateMachine(  742): Error! unhandled message{ when=-4ms what=135188 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  742): InactiveState{ what=131204 }
D/WifiP2pService(  742): P2pEnabledState{ what=131204 }
,D/STATUSBAR-IconMerger( 1066): checkOverflow(384), More:false, Req:false Child:1
,D/WifiP2pService(  742): sending p2p connection changed broadcast: FAILED
,W/WifiP2pStateTracker(  742): WifiP2pStateReceiver : android.net.wifi.p2p.CONNECTION_STATE_CHANGE
D/WifiDisplayController(  742): Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=NetworkInfo: type: WIFI_P2P[], state: DISCONNECTED/FAILED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/WifiDisplayAdapter(  742): onP2pDisconnected
D/IpRemoteDisplayController(  742): disconnectWfdBridgeServer
,I/dalvikvm(  742): Jit: resizing JitTable from 8192 to 16384
,D/TimaKeyStoreProvider( 3439): in addTimaSignatureService
,D/QuickConnect[1.1][2] ( 3381): P2pHelper.onReceive - P2P_CONNECTION_CHANGED : 
,D/QuickConnect[1.1][2] ( 3381): SconnectManager.INetworkStateListener, onDisconnected - networkType : 4
D/IpRemoteDisplayController(  742): WfdBridgeServer is already null
,D/WifiP2pService(  742): sending p2p connection changed broadcast: DISCONNECTED
V/RouteController(  239): RTNETLINK answers: No such process
,E/WifiStateMachine(  742): BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
,V/RouteController(  239): /system/bin/ip -6 rule del table 2 2>&1
,D/QuickConnect[1.1][2] ( 3381): SconnectManager.INetworkStateListener, onDisabled - mNetworkState : 0
,D/QuickConnect[1.1][2] ( 3381): P2pHelper.cancelConnectPeer -  mTargetList clear all 
,D/TimaKeyStoreProvider( 3439): Cannot add TimaSignature Service, License check Failed
,D/QuickConnect[1.1][2] ( 3381): P2pHelper.removeP2pConfirm - skip: false
,D/QuickConnect[1.1][2] ( 3381): CentralActionManager.removeHoldingIntentAll - all request done.
D/WifiDisplayController(  742): Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=false
D/WifiDisplayController(  742): updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
D/WifiDisplayController(  742): disconnect
D/WifiDisplayController(  742): updateConnection
D/WifiDisplayController(  742): updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
,D/WifiDisplayAdapter(  742): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,D/ActivityThread( 3439): Added TimaKesytore provider
,D/QuickConnect[1.1][2] ( 3381): P2pHelper.onReceive - P2P_CONNECTION_CHANGED : 
,D/QuickConnect[1.1][2] ( 3381): SconnectManager.INetworkStateListener, onDisconnected - networkType : 4
D/WifiP2pService(  742): P2pDisablingState
D/WifiP2pService(  742): P2pDisablingState{ what=147458 }
W/WifiP2pStateTracker(  742): WifiP2pStateReceiver : android.net.wifi.p2p.CONNECTION_STATE_CHANGE
D/WifiP2pService(  742): p2p socket connection lost
D/WifiDisplayController(  742): Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=NetworkInfo: type: WIFI_P2P[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false
D/WifiDisplayAdapter(  742): onP2pDisconnected
D/IpRemoteDisplayController(  742): disconnectWfdBridgeServer
D/IpRemoteDisplayController(  742): WfdBridgeServer is already null
D/WifiDisplayAdapter(  742): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,D/QuickConnect[1.1][2] ( 3381): P2pHelper.onReceive - ACTION_WIFI_DISPLAY_STATUS_CHANGED :0
,V/RouteController(  239): RTNETLINK answers: No such file or directory
,D/CommandListener(  239): Clearing all IP addresses on wlan0
,D/QuickConnect[1.1][2] ( 3381): P2pHelper.requestGroupInfo  - onGroupInfoAvailable- null
D/BatteryService(  742): level:100, scale:100, status:2, health:2, present:true, voltage: 4365, temperature: 290, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:8, charge type:1, power sharing:false
D/BatteryService(  742): stay LED for charging
D/BatteryService(  742): Sending ACTION_BATTERY_CHANGED.
D/UiModeManager(  742): mCoverManager.getCoverState() : true
D/WifiP2pService(  742): P2pDisabledState
D/WifiP2pService(  742): P2pDisabledState{ what=139287 }
,D/WifiP2pService(  742): DefaultState{ what=139287 }
D/KeyguardUpdateMonitor( 1066): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1066): handleBatteryUpdate
,D/QuickConnect[1.1][2] ( 3381): P2pHelper.requestGroupInfo  - onGroupInfoAvailable- null
,W/NetworkManagementService(  742): route cmd failed: 
W/NetworkManagementService(  742): com.android.server.NativeDaemonConnector$NativeDaemonFailureException: command '34 route del src v6 2' failed with '400 34 -6 rule del table 2: RTNETLINK answers: No such file or directory
W/NetworkManagementService(  742): '
W/NetworkManagementService(  742): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:406)
W/NetworkManagementService(  742): 	at com.android.server.NativeDaemonConnector.executeForList(NativeDaemonConnector.java:338)
W/NetworkManagementService(  742): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:303)
W/NetworkManagementService(  742): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:288)
W/NetworkManagementService(  742): 	at com.android.server.NetworkManagementService.delSrcRoute(NetworkManagementService.java:2502)
W/NetworkManagementService(  742): 	at com.android.server.ConnectivityService.updateSourceRoutes(ConnectivityService.java:4156)
W/NetworkManagementService(  742): 	at com.android.server.ConnectivityService.handleConnectivityChange(ConnectivityService.java:3938)
W/NetworkManagementService(  742): 	at com.android.server.ConnectivityService.handleDisconnect(ConnectivityService.java:3088)
W/NetworkManagementService(  742): 	at com.android.server.ConnectivityService.access$1800(ConnectivityService.java:258)
W/NetworkManagementService(  742): 	at com.android.server.ConnectivityService$NetworkStateTrackerHandler.handleMessage(ConnectivityService.java:4781)
W/NetworkManagementService(  742): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/NetworkManagementService(  742): 	at android.os.Looper.loop(Looper.java:146)
W/NetworkManagementService(  742): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,V/HeadsetService( 1948): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/WifiP2pService(  742): P2pDisabledState{ what=139376 }
D/WifiP2pService(  742): DefaultState{ what=139376 }
E/WifiP2pService(  742): Unhandled message { what=139376 }
D/WifiP2pService(  742): P2pDisabledState{ what=139287 }
,D/WifiP2pService(  742): DefaultState{ what=139287 }
D/HeadsetStateMachine( 1948): Disconnected process message: 10
V/RouteController(  239): /system/bin/ip -4 route del default table 2 2>&1
D/WifiNative(  742): callSECApiBoolean - ID [13]
,I/wpa_supplicant( 1959): USE_NETWORK : USE_NETWORK OFF
D/STATUSBAR-PhoneStatusBar( 1066):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
D/BatteryMeterView( 1066): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,I/WifiTrafficPoller(  742): evaluateTrafficStatsPolling
,V/RouteController(  239): RTNETLINK answers: No such process
,V/RouteController(  239): /system/bin/ip -4 rule del table 2 2>&1
,D/STATUSBAR-IconMerger( 1066): checkOverflow(384), More:false, Req:false Child:1
,D/STATUSBAR-NetworkController_dual( 1066): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
D/StatusBar.NetworkController_dual( 1066): mMobileLabelViews start
D/StatusBar.NetworkController_dual( 1066): mMobileLabelViews set mobileLabel[SIM_0] =No service.
D/StatusBar.NetworkController_dual( 1066): mMobileLabelViews GONE
D/StatusBar.NetworkController_dual( 1066): mMobileLabelViews2 set mobileLabel[SIM_1] =No service.
D/StatusBar.NetworkController_dual( 1066): mMobileLabelViews2 GONE
,D/StatusBar.NetworkController_dual( 1066): mSingleMobileLabelViews set : simMode = 0
,D/StatusBar.NetworkController_dual( 1066): mSingleMobileLabelViews set as slot1`s
D/STATUSBAR-NetworkController_dual( 1066): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
D/SignalClusterView_dual( 1066): wifi: GONE sig=2130837981 act=2130837946
D/SignalClusterView_dual( 1066): mMobileDataState=0 mMobileDataState2=0
D/SignalClusterView_dual( 1066): apply() mSeparateMobileGroup=8
D/STATUSBAR-NetworkController_dual( 1066): refreshSignalCluster - setNWBoosterIndicators(false)
D/SignalClusterView_dual( 1066): wifi: GONE sig=0 act=2130837946
D/SignalClusterView_dual( 1066): mMobileDataState=0 mMobileDataState2=0
,D/SignalClusterView_dual( 1066): apply() mSeparateMobileGroup=8
D/SignalClusterView_dual( 1066): wifi: GONE sig=0 act=2130837946
D/SignalClusterView_dual( 1066): mMobileDataState=0 mMobileDataState2=0
D/SignalClusterView_dual( 1066): apply() mSeparateMobileGroup=8
D/SignalClusterView_dual( 1066): wifi: GONE sig=0 act=2130837946
D/SignalClusterView_dual( 1066): mMobileDataState=0 mMobileDataState2=0
D/SignalClusterView_dual( 1066): apply() mSeparateMobileGroup=8
D/SignalClusterView_dual( 1066): wifi: GONE sig=0 act=2130837946
D/SignalClusterView_dual( 1066): mMobileDataState=0 mMobileDataState2=0
D/SignalClusterView_dual( 1066): apply() mSeparateMobileGroup=8
D/StatusBar.NetworkController_dual( 1066): mMobileLabelViews start
D/StatusBar.NetworkController_dual( 1066): mMobileLabelViews set mobileLabel[SIM_0] =No service.
D/StatusBar.NetworkController_dual( 1066): mMobileLabelViews GONE
D/StatusBar.NetworkController_dual( 1066): mMobileLabelViews2 set mobileLabel[SIM_1] =No service.
,V/RouteController(  239): /system/bin/ip route flush cached 2>&1
D/StatusBar.NetworkController_dual( 1066): mMobileLabelViews2 GONE
D/StatusBar.NetworkController_dual( 1066): mSingleMobileLabelViews set : simMode = 0
D/StatusBar.NetworkController_dual( 1066): mSingleMobileLabelViews set as slot1`s
,D/BluetoothAdapterState( 1948): CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
D/BtConfig.SecureMode( 1948): isSecureModeOn:false
W/BluetoothAdapterService( 1948): check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.gatt.GattService
W/BluetoothAdapterService( 1948): Skipping to stop Quiet mode profile com.android.bluetooth.gatt.GattService
W/BluetoothAdapterService( 1948): check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.hfp.HeadsetService
,D/BtSettings.ProfileConfig( 1948): getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
,W/BluetoothAdapterService( 1948): Not skipping com.android.bluetooth.hfp.HeadsetService
,D/NetUtils(  742): android_net_utils_resetConnections in env=0x77f43500 clazz=0x51000001 iface=wlan0 mask=0x3
,E/WifiStateMachine(  742): Error! unhandled message{ when=-40ms what=135188 target=com.android.internal.util.StateMachine$SmHandler }
,E/WifiStateMachine(  742): Error! unhandled message{ when=-40ms what=135191 target=com.android.internal.util.StateMachine$SmHandler }
,D/ConnectivityService(  742): resetConnections(wlan0, 3)
E/WifiStateMachine(  742): Error! unhandled message{ when=-18ms what=135188 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiStateMachine(  742): Error! unhandled message{ when=-18ms what=135191 target=com.android.internal.util.StateMachine$SmHandler }
W/BluetoothAdapterService( 1948): check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.a2dp.A2dpService
D/BtSettings.ProfileConfig( 1948): getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
W/BluetoothAdapterService( 1948): Not skipping com.android.bluetooth.a2dp.A2dpService
D/HeadsetService( 1948): Received stop request...Stopping profile...
W/BluetoothAdapterService( 1948): check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.hid.HidService
D/BtSettings.ProfileConfig( 1948): getProfileSaveSetting: com.android.bluetooth.hid.HidService
W/BluetoothAdapterService( 1948): Not skipping com.android.bluetooth.hid.HidService
D/QuickConnect[1.1][2] ( 3381): HeadsetProfile.onServiceDisconnected - Bluetooth service disconnected
D/A2dpService( 1948): Received stop request...Stopping profile...
W/BluetoothAdapterService( 1948): check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.hdp.HealthService
D/BtSettings.ProfileConfig( 1948): getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
D/Avrcp   ( 1948): Unregistering previous receiver
D/MediaFocusControl(  742): <<< unregisterRemoteControlDisplay
W/BluetoothAdapterService( 1948): Not skipping com.android.bluetooth.hdp.HealthService
D/A2dpStateMachine( 1948): Exit Disconnected: -1
W/BluetoothAdapterService( 1948): check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.pan.PanService
D/BtSettings.ProfileConfig( 1948): getProfileSaveSetting: com.android.bluetooth.pan.PanService
D/BluetoothA2dp(  742): Proxy object disconnected
D/BluetoothA2dp( 3381): Proxy object disconnected
D/QuickConnect[1.1][2] ( 3381): A2dpProfile.onServiceConnected - Bluetooth service disconnected
W/BluetoothAdapterService( 1948): Not skipping com.android.bluetooth.pan.PanService
D/BluetoothA2dp( 2111): Proxy object disconnected
W/BluetoothAdapterService( 1948): check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.map.BluetoothMapService
D/BtSettings.ProfileConfig( 1948): getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
W/BluetoothAdapterService( 1948): Not skipping com.android.bluetooth.map.BluetoothMapService
D/BluetoothAdapterState( 1948): Stopping profile services that were post enabled
D/BtSettings.ProfileConfig( 1948): getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
D/BluetoothAdapterService( 1948): Profile still running: com.android.bluetooth.hdp.HealthService
W/BluetoothHeadsetServiceJni( 1948): Cleaning up Bluetooth Handsfree Interface...
W/BluetoothHeadsetServiceJni( 1948): Cleaning up Bluetooth Handsfree callback object
D/HidService( 1948): Received stop request...Stopping profile...
D/HidService( 1948): Stopping Bluetooth HidService
D/BluetoothInputDevice( 3381): Proxy object disconnected
D/QuickConnect[1.1][2] ( 3381): HidProfile.onServiceDisconnected - Bluetooth service disconnected
D/BtSettings.ProfileConfig( 1948): getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
D/BluetoothAdapterService( 1948): Profile still running: com.android.bluetooth.hdp.HealthService
D/HealthService( 1948): Received stop request...Stopping profile...
I/GKI_LINUX( 1948): gki_task_entry: gki_task task_id=2 [A2DP-MEDIA] terminating
I/GKI_LINUX( 1948): GKI_exit_task: GKI_exit_task 2 done
I/GKI_LINUX( 1948): GKI_destroy_task: GKI_shutdown(): task [A2DP-MEDIA] terminated
D/PanService( 1948): Received stop request...Stopping profile...
D/BluetoothPan(  742): BluetoothPAN Proxy object disconnected
D/BluetoothMapService( 1948): Received stop request...Stopping profile...
D/BtSettings.ProfileConfig( 1948): getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
D/BluetoothAdapt,erService( 1948): Profile still running: com.android.bluetooth.hdp.HealthService
W/BluetoothHidServiceJni( 1948): Cleaning up Bluetooth HID Interface...
W/BluetoothHidServiceJni( 1948): Cleaning up Bluetooth GID callback object
D/BtSettings.ProfileConfig( 1948): getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
D/BluetoothAdapterService( 1948): Profile still running: com.android.bluetooth.map.BluetoothMapService
W/BluetoothHealthServiceJni( 1948): Cleaning up Bluetooth Health Interface...
W/BluetoothHealthServiceJni( 1948): Cleaning up Bluetooth Health object
D/BtSettings.ProfileConfig( 1948): getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
D/BluetoothAdapterService( 1948): Profile still running: com.android.bluetooth.map.BluetoothMapService
W/BluetoothPanServiceJni( 1948): Cleaning up Bluetooth PAN Interface...
W/BluetoothPanServiceJni( 1948): Cleaning up Bluetooth PAN callback object
D/BluetoothAdapterService( 1948): Quiet mode profile com.android.bluetooth.gatt.GattService running since Radio Cnt > 0. 
D/BluetoothAdapterState( 1948): CURRENT_STATE=PENDING,MSG = STOPPED, isTurningOn=false, isTurningOff=true
I/BluetoothAdapterState( 1948): Bluetooth adapter state changed: 13-> 10
D/BluetoothAdapterService( 1948): Bluetooth PBAP supproted is true
D/BluetoothAdapterService( 1948): updateAdapterState state is 10
D/BluetoothAdapterService( 1948): Broadcasting updateAdapterState() to 1 receivers.
D/BluetoothAdapterService( 1948): Autoconnection is available 
D/BluetoothAdapterService( 1948): updateAdapterState prevState = 13newState = 10
I/BluetoothAdapterState( 1948): Entering OffState
D/BluetoothA2dp( 2111): onBluetoothStateChange: up=false
D/BluetoothInputDevice( 3381): onBluetoothStateChange: up=false
D/BluetoothA2dp( 3381): onBluetoothStateChange: up=false
D/BluetoothA2dp(  742): onBluetoothStateChange: up=false
W/InputMethodManagerService(  742): InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
I/WifiTrafficPoller(  742): mBoosterFLAG : 0
,I/WifiTrafficPoller(  742): current booster mode : FullMode
I/InputMethodManagerService(  742): [BT Setting State] State =10
I/InputMethodManagerService(  742): [BT Setting on -> off] mBTKeyboardCount =0, KEYBOARD_BT(0)
,D/PhoneApp( 1239): mReceiver: BluetoothAdapter.ACTION_STATE_CHANGED: 10
,I/QuickConnect[1.1][2] ( 3381): BluetoothHelper.ACTION_STATE_CHANGED - STATE_OFF
,D/Tethering(  742): interfaceLinkStateChanged p2p0, false
,D/Tethering(  742): interfaceStatusChanged p2p0, false
,I/wpa_supplicant( 1959): p2p0: CTRL-EVENT-TERMINATING 
D/Tethering(  742): interfaceLinkStateChanged wlan0, true
,D/Tethering(  742): interfaceStatusChanged wlan0, true
,D/GKI_LINUX( 1948): release_my_wake_lock(), g_wake_lock_fd:91, g_wake_unlock_fd:92, wake_lock_acquired:1
,I/wpa_supplicant( 1959): CTRL-EVENT-DISCONNECTED bssid=C0.AA.48 reason=3 locally_generated=1
,D/Tethering(  742): interfaceLinkStateChanged wlan0, false
,D/Tethering(  742): interfaceStatusChanged wlan0, false
,D/Tethering(  742): InitialState.processMessage what=4
,E/Tethering(  742): No numeric data
I/wpa_supplicant( 1959): Prev BSS - hexdump(len=6): c0 ff d4 d3 aa 48
,I/wpa_supplicant( 1959): CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=C0.AA.48 SSID=4E47373030
D/Tethering(  742): interfaceLinkStateChanged wlan0, false
,D/Tethering(  742): interfaceStatusChanged wlan0, false
I/ConnectivityService(  742): defaultVal : 1, tetherEnabledInSettings : true
,D/NtpTrustedTime(  742): currentTimeMillis() cache hit
,D/Tethering(  742): sendTetherStateChangedBroadcast 0, 0, 0
D/Tethering(  742): interfaceLinkStateChanged wlan0, false
,D/Tethering(  742): interfaceStatusChanged wlan0, false
V/NetworkStats(  742): performPollLocked(flags=0x1)
,D/NtpTrustedTime(  742): currentTimeMillis() cache hit
D/BluetoothTethering(  742): got CMD_CHANNEL_DISCONNECTED
,E/BluetoothTethering(  742): attempted to stop reverse tether with nothing tethered
,D/NtpTrustedTime(  742): currentTimeMillis() cache hit
,D/NtpTrustedTime(  742): currentTimeMillis() cache hit
,D/NtpTrustedTime(  742): currentTimeMillis() cache hit
,D/NtpTrustedTime(  742): currentTimeMillis() cache hit
,D/NtpTrustedTime(  742): currentTimeMillis() cache hit
V/NetworkStats(  742): advisePersistThreshold() given 9223372036854775, clamped to 2097152
V/NetworkStats(  742): performPollLocked() took 33ms
V/NetworkStats(  742): updateIfacesLocked()
V/NetworkStats(  742): performPollLocked(flags=0x1)
,D/NtpTrustedTime(  742): currentTimeMillis() cache hit
V/NetworkStats(  742): performPollLocked() took 24ms
,D/NtpTrustedTime(  742): currentTimeMillis() cache hit
,D/NtpTrustedTime(  742): currentTimeMillis() cache hit
D/NtpTrustedTime(  742): currentTimeMillis() cache hit
,D/NtpTrustedTime(  742): currentTimeMillis() cache hit
,D/RCPManagerService(  742): exchangeData() failure , invalid userId
,D/RCPManagerService(  742): exchangeData() failure , invalid userId
,D/RCPManagerService(  742): exchangeData() failure , invalid userId
,D/Tethering(  742): interfaceLinkStateChanged wlan0, false
D/Tethering(  742): interfaceStatusChanged wlan0, false
,I/wpa_supplicant( 1959): wlan0: CTRL-EVENT-TERMINATING 
,D/RCPManagerService(  742): exchangeData() failure , invalid userId
,D/WifiStateMachine(  742): skipWifiStateBroadcast:false, LastBroadcastedWifiState:0
,W/Settings( 3273): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings( 1218): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/STATUSBAR-NetworkController_dual( 1066): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
D/StatusBar.NetworkController_dual( 1066): mMobileLabelViews start
D/StatusBar.NetworkController_dual( 1066): mMobileLabelViews set mobileLabel[SIM_0] =No service.
D/StatusBar.NetworkController_dual( 1066): mMobileLabelViews GONE
D/StatusBar.NetworkController_dual( 1066): mMobileLabelViews2 set mobileLabel[SIM_1] =No service.
D/StatusBar.NetworkController_dual( 1066): mMobileLabelViews2 GONE
D/StatusBar.NetworkController_dual( 1066): mSingleMobileLabelViews set : simMode = 0
D/StatusBar.NetworkController_dual( 1066): mSingleMobileLabelViews set as slot1`s
,D/AndroidRuntime( 3462): 
D/AndroidRuntime( 3462): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/AndroidRuntime( 3462): CheckJNI is OFF
,D/AndroidRuntime( 3462): setted country_code = Poland
,D/AndroidRuntime( 3462): setted countryiso_code = PL
D/AndroidRuntime( 3462): setted sales_code = XEO
D/AndroidRuntime( 3462): readGMSProperty: start
,D/AndroidRuntime( 3462): readGMSProperty: already setted!!
D/AndroidRuntime( 3462): readGMSProperty: end
,D/AndroidRuntime( 3462): addProductProperty: start
,D/dalvikvm( 3462): Trying to load lib libjavacore.so 0x0
,D/dalvikvm(  742): GC_EXPLICIT freed 1806K, 16% free 23354K/27684K, paused 5ms+11ms, total 131ms
,D/dalvikvm( 3462): Added shared lib libjavacore.so 0x0
,D/BadgeProvider( 1340): query, [selection] : package='com.android.email' AND class='com.android.email.activity.Welcome' AND extraData='base_extra_badge'
D/dalvikvm( 3462): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 3462): Added shared lib libnativehelper.so 0x0
,D/dalvikvm( 3462): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
W/ActivityManager(  742): Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
,D/BadgeProvider( 1340): sendNotify entered. [uri] : content://com.sec.badge/apps/1
D/BadgeProvider( 1340): sendNotify, [notify] : null
D/BadgeProvider( 1340): update, [uri] : content://com.sec.badge/apps/1
,D/BadgeProvider( 1340): update, [BadgeCount] : badgecount=0
,D/BadgeProvider( 1340): update, [UpdateCount] : 1
,D/Launcher.Model( 1259): reloadBadges entered.
,I/SELinux ( 3499): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 3499):  
I/ActivityManager(  742): Killing 2493:com.samsung.android.sdk.samsunglink/u0a42 (adj 15): empty #43
W/ActivityManager(  742): Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
,D/dalvikvm(  249): GC_EXPLICIT freed 48K, 50% free 9509K/18976K, paused 2ms+3ms, total 26ms
,D/dalvikvm(  249): GC_EXPLICIT freed <1K, 50% free 9509K/18976K, paused 2ms+2ms, total 19ms
I/SELinux ( 3499): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 3499):  
I/SELinux ( 3499):  
,I/SELinux ( 3499): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 3499): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 3499): >>>>> Normal User
,E/dalvikvm( 3499): >>>>> com.android.exchange [ userId:0 | appId:10156 ]
,E/SELinux ( 3499): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/dalvikvm(  249): GC_EXPLICIT freed <1K, 50% free 9509K/18976K, paused 2ms+2ms, total 20ms
,D/TimaKeyStoreProvider( 3499): in addTimaSignatureService
,D/TimaKeyStoreProvider( 3499): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 3499): Added TimaKesytore provider
,I/Process ( 3439): Sending signal. PID: 3439 SIG: 9
,E/memtrack( 3462): Couldn't load memtrack module (No such file or directory)
,E/android.os.Debug( 3462): failed to load memtrack module: -2
I/ActivityManager(  742): Process com.android.email (pid 3439) (adj 9) has died.
,D/dalvikvm( 3462): Note: class Landroid/app/ActivityManagerNative; has 192 unimplemented (abstract) methods
D/Tethering(  742): Tethering got CONNECTIVITY_ACTION
I/ApplicationPolicy(  742): updateDataUsageMap
D/Tethering(  742): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker(  742): Disconnected from active network NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService(  742): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
D/STATUSBAR-NetworkController_dual( 1066): onReceive() - CONNECTIVITY_ACTION, INET_CONDITION_ACTION
,D/accuweather( 1443): [KK AccuPhone]>>> SWW:64 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/LocSvc_java(  742): updateNetworkState unavailable info: NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false
D/LocSvc_java(  742): getAGpsConnectionInfo connType - 4
,D/LocSvc_java(  742): ignore wifi update if we are not in OPENING or CLOSING
D/StatusBar.NetworkController_dual( 1066): mMobileLabelViews start
D/StatusBar.NetworkController_dual( 1066): mMobileLabelViews set mobileLabel[SIM_0] =No service.
D/StatusBar.NetworkController_dual( 1066): mMobileLabelViews GONE
D/StatusBar.NetworkController_dual( 1066): mMobileLabelViews2 set mobileLabel[SIM_1] =No service.
D/StatusBar.NetworkController_dual( 1066): mMobileLabelViews2 GONE
D/StatusBar.NetworkController_dual( 1066): mSingleMobileLabelViews set : simMode = 0
D/StatusBar.NetworkController_dual( 1066): mSingleMobileLabelViews set as slot1`s
,I/SELinux ( 3513): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 3513):  
,I/SELinux ( 3517): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 3517):  
,D/AndroidRuntime( 3462): Calling main entry com.android.commands.pm.Pm
,I/SELinux ( 3513): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 3513):  
I/SELinux ( 3513):  
,I/SELinux ( 3513): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 3513): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 3513): >>>>> Normal User
,E/dalvikvm( 3513): >>>>> com.android.email [ userId:0 | appId:10155 ]
D/PackageManagerService(  742): deletePackageAsUser- pkg:com.example.hello, userId:0
D/PersonaManagerService(  742): isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
E/SELinux ( 3513): [DEBUG] seapp_context_lookup: seinfoCategory = platform
D/PersonaManagerService(  742): isFromApprovedUnInstaller: isApproved : true
D/PersonaManagerService(  742): isFromApprovedUnInstaller: isApproved before exit: true
D/PackageManager(  742): deletePackageAsUser- pkg:com.example.hello, userId:0, flag3
,D/PackageManager(  742): deletePackageAsUser- pkg:com.example.hello, userId:0, flag3
,D/PackageManagerService(  742): deletePackage- pkg:com.example.hello, edmuserId:0
D/PackageManagerService(  742): deletePackage- pkg:com.example.hello, edmuserId:-1
,D/ApplicationPolicy(  742): getApplicationUninstallationEnabled
D/ApplicationPolicy(  742): getApplicationUninstallationEnabled :  enabled true
,D/PackageManagerService(  742): deletePackageX- pkg:com.example.hello, userId:0
D/PackageManager(  742): START PACKAGE DELETE: observer{1121680816}
D/PackageManager(  742): pkg{<packageName>}
D/PackageManager(  742): user{0}
D/PackageManager(  742): deletePackageAsUser : uid = 2000 userId = 0
D/PackageManager(  742): [MSG] DELETE_PACKAGE_AS_USER
,I/SELinux ( 3517): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 3517):  
I/SELinux ( 3517):  
,I/SELinux ( 3517): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,D/TimaKeyStoreProvider( 3513): in addTimaSignatureService
,E/SELinux ( 3517): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 3517): >>>>> Normal User
,E/dalvikvm( 3517): >>>>> com.samsung.android.provider.shootingmodeprovider [ userId:0 | appId:10162 ]
,W/Netd    (  239): No subsystem found in netlink event
,E/SELinux ( 3517): [DEBUG] seapp_context_lookup: seinfoCategory = platform
D/NetlinkEvent(  239): Unexpected netlink message. type=0x11
,D/Vpn     (  742): Interface removed : wlan0
D/Tethering(  742): interfaceRemoved wlan0
,E/Tethering(  742): attempting to remove unknown iface (wlan0), ignoring
,D/TimaKeyStoreProvider( 3513): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 3513): Added TimaKesytore provider
,D/TimaKeyStoreProvider( 3517): in addTimaSignatureService
,D/TimaKeyStoreProvider( 3517): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 3517): Added TimaKesytore provider
I/ActivityManager(  742): Killing 2541:com.vlingo.midas/u0a33 (adj 15): empty #43
D/PackageManager(  742): !@killApplicatoin: 10181, uninstall pkg
,W/Netd    (  239): No subsystem found in netlink event
,D/Vpn     (  742): Interface removed : p2p0
D/Tethering(  742): interfaceRemoved p2p0
,E/Tethering(  742): attempting to remove unknown iface (p2p0), ignoring
D/NetlinkEvent(  239): Unexpected netlink message. type=0x11
,W/PackageSettings(  742): Skipping PackageSetting{42cb30b0 com.test.thalitest/10179} due to missing metadata
,D/PackageManager(  742): Sending to user 0: act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000000 Bundle[{android.intent.extra.REMOVED_FOR_ALL_USERS=true, android.intent.extra.UID=10181, android.intent.extra.DATA_REMOVED=true, android.intent.extra.user_handle=0}]
,I/ActivityManager(  742): Killing 2894:com.example.hello/u0a181 (adj 0): stop com.example.hello
,D/CustomFrequencyManagerService(  742): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 742  pkgName : ACTIVITY_RESUME_BOOSTER@5
,W/ActivityManager(  742): mDVFSHelper.acquire()
,D/KeyguardUpdateMonitor( 1066): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1066): handleKeyguardVisibilityChanged(1)
,D/KeyguardUpdateMonitor( 1066): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1066): handleKeyguardVisibilityChanged(1)
,D/LockPatternUtils( 1066): isPcwEnable = null
,D/SurfaceWidgetView( 1259): destroyHardwareResources():1126188616
,D/KeyguardUpdateMonitor( 1066): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1066): handleKeyguardVisibilityChanged(1)
,W/InputDispatcher(  742): channel ~ Consumer closed input channel or an error occurred.  events=0x9
,E/InputDispatcher(  742): channel ~ Channel is unrecoverably broken and will be disposed!
,D/KeyguardUpdateMonitor( 1066): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1066): handleKeyguardVisibilityChanged(1)
,W/InputDispatcher(  742): Attempted to unregister already unregistered input channel
D/Launcher( 1259): onRestart, Launcher: 1114253552
D/Launcher( 1259): onStart, Launcher: 1114253552
D/Launcher.HomeView( 1259): onStart
I/SurfaceFlinger(  248): id=15 Removed NainActivit (7/11)
,I/SurfaceFlinger(  248): id=15 Removed NainActivit (-2/11)
,I/WindowState(  742): WIN DEATH: Window{42645c90 u0 com.example.hello/com.example.hello.MainActivity}
D/SurfaceWidgetClient$ISurfaceWidgetStub( 1443): [237392/5] Surface widget visibility changed visibility = true on instance = 1
D/SurfaceWidget.Renderer( 1443): [237392/5] SurfaceWidget drawing first frame
D/KeyguardUpdateMonitor( 1066): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1066): handleKeyguardVisibilityChanged(1)
I/SurfaceFlinger(  248): id=15 Removed NainActivit (-2/11)
,D/PackageManager(  742): Sending to user 0: act=android.intent.action.PACKAGE_FULLY_REMOVED dat=package:com.example.hello flg=0x4000000 Bundle[{android.intent.extra.REMOVED_FOR_ALL_USERS=true, android.intent.extra.UID=10181, android.intent.extra.DATA_REMOVED=true, android.intent.extra.user_handle=0}]
,I/FPMS_FingerprintManagerService( 1086): onReceive: android.intent.action.PACKAGE_REMOVED
,D/AdaptiveEventManager( 1066): action=android.intent.action.PACKAGE_REMOVED
,W/GeofencerStateMachine( 1218): Ignoring removeGeofence because network location is disabled.
,I/InputReader(  742): Reconfiguring input devices.  changes=0x00000010
,D/QuickConnect[1.1][2] ( 3381): SconnectManager.onReceiver - action : android.intent.action.PACKAGE_REMOVED, package : com.example.hello
,I/SurfaceFlinger(  248): id=16 createSurf (720x1280),1 flag=4, Mauncher
,D/dalvikvm( 1396): GC_EXPLICIT freed 4168K, 48% free 10001K/18976K, paused 3ms+3ms, total 47ms
,I/PackageManager(  742):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  742):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  742):   Scheme: "sms"
,D/KeyguardUpdateMonitor( 1066): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1066): handleKeyguardVisibilityChanged(1)
I/PackageManager(  742): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,I/SurfaceFlinger(  248): id=17 createSurf (1x1),2 flag=404, CatteryCove
,I/PackageManager(  742):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  742):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  742):   Scheme: "smsto"
D/KeyguardUpdateMonitor( 1066): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1066): handleKeyguardVisibilityChanged(1)
,D/RCPManagerService(  742): exchangeData() failure , invalid userId
I/PackageManager(  742): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,I/PackageManager(  742):   Action: "android.intent.action.SENDTO"
I/PackageManager(  742):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  742):   Scheme: "mms"
I/PackageManager(  742): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,D/RCPManagerService(  742): exchangeData() failure , invalid userId
,D/RCPManagerService(  742): PackageReceiver onReceive()
,I/PackageManager(  742):   Action: "android.intent.action.SENDTO"
I/PackageManager(  742):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  742):   Scheme: "mmsto"
,I/HarmonyEASService(  742): onReceive : android.intent.action.PACKAGE_REMOVED for 0
I/PackageManager(  742): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,D/KeyguardUpdateMonitor( 1066): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1066): handleKeyguardVisibilityChanged(1)
,D/KeyguardUpdateMonitor( 1066): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1066): handleKeyguardVisibilityChanged(1)
,I/SELinux ( 3546): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 3546):  
,I/ActivityManager(  742): Killing 2673:com.sec.android.app.shealth/u0a35 (adj 15): empty #43
D/KeyguardUpdateMonitor( 1066): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1066): handleKeyguardVisibilityChanged(1)
,D/RCPManagerService(  742): exchangeData() failure , invalid userId
I/PackageManager(  742):   Action: "android.intent.action.SENDTO"
I/PackageManager(  742):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  742):   Scheme: "sms"
I/PackageManager(  742): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,D/CustomFrequencyManagerService(  742): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 742  pkgName : ACTIVITY_RESUME_BOOSTER@9
,D/CustomFrequencyManagerService(  742): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 742  tag : ACTIVITY_RESUME_BOOSTER@5
,D/CustomFrequencyManagerService(  742): FrequencyrequestList.getNextMaxCPUCoreRequest, index: 0
,W/ActivityManager(  742): mDVFSHelper.release()
,D/KeyguardUpdateMonitor( 1066): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1066): handleKeyguardVisibilityChanged(1)
,I/PackageManager(  742):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  742):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  742):   Scheme: "smsto"
,I/PackageManager(  742): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
I/SELinux ( 3546): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 3546):  
I/SELinux ( 3546):  
I/SELinux ( 3546): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 3546): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 3546): >>>>> Normal User
E/dalvikvm( 3546): >>>>> com.sec.modem.settings [ userId:0 | appId:1000 ]
E/SELinux ( 3546): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,I/PackageManager(  742):   Action: "android.intent.action.SENDTO"
I/PackageManager(  742):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  742):   Scheme: "mms"
I/PackageManager(  742): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,D/TimaKeyStoreProvider( 3546): in addTimaSignatureService
,D/TimaKeyStoreProvider( 3546): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 3546): Added TimaKesytore provider
,I/PackageManager(  742):   Action: "android.intent.action.SENDTO"
I/PackageManager(  742):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  742):   Scheme: "mmsto"
E/Watchdog(  742): !@Sync 1
I/PackageManager(  742): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,D/EnterpriseDeviceManagerService(  742): Package has changed for user 0
,D/EnterpriseDeviceManagerService(  742): Admin package name: com.google.android.gms
,I/SELinux ( 3563): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 3563):  
I/ActivityManager(  742): Killing 2066:com.sec.android.service.health/u0a16 (adj 15): empty #43
,D/BadgeProvider( 1340): query, [selection] : package='com.android.email' AND class='com.android.email.activity.Welcome' AND extraData='base_extra_badge'
,D/BadgeProvider( 1340): sendNotify entered. [uri] : content://com.sec.badge/apps/1
D/BadgeProvider( 1340): sendNotify, [notify] : null
D/BadgeProvider( 1340): update, [uri] : content://com.sec.badge/apps/1
D/BadgeProvider( 1340): update, [BadgeCount] : badgecount=0
,D/BadgeProvider( 1340): update, [UpdateCount] : 1
,I/SELinux ( 3563): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 3563):  
I/SELinux ( 3563):  
,I/SELinux ( 3563): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 3563): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 3563): >>>>> Normal User
,E/dalvikvm( 3563): >>>>> tv.peel.smartremote [ userId:0 | appId:10163 ]
,E/SELinux ( 3563): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
,W/Resources(  742): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/TimaKeyStoreProvider( 3563): in addTimaSignatureService
,D/RCPManagerService(  742): exchangeData() failure , invalid userId
,D/TimaKeyStoreProvider( 3563): Cannot add TimaSignature Service, License check Failed
,I/Process ( 3499): Sending signal. PID: 3499 SIG: 9
,D/ActivityThread( 3563): Added TimaKesytore provider
,W/Resources(  742): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/WifiStateMachine(  742): skipWifiStateBroadcast:false, LastBroadcastedWifiState:1
D/BackupManagerService(  742): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 (has extras) }
V/BackupManagerService(  742): removePackageParticipantsLocked: uid=10181 #1
W/ActivityManager(  742): Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
,I/ActivityManager(  742): Process com.android.exchange (pid 3499) (adj 9) has died.
,D/dalvikvm(  742): GC_EXPLICIT freed 2332K, 15% free 23711K/27684K, paused 6ms+17ms, total 407ms
D/PackageManager(  742): delete sourFile : 
,D/PackageManager(  742): delete native library directory: 
D/PackageManager(  742): return delete result to caller: 1121680816
,D/PackageManager(  742): returnCode: 1
D/AndroidRuntime( 3462): Shutting down VM
D/dalvikvm( 3462): GC_CONCURRENT freed 96K, 14% free 670K/772K, paused 0ms+0ms, total 2ms
,I/PackageManager(  742):   Action: "android.intent.action.SENDTO"
I/PackageManager(  742):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  742):   Scheme: "sms"
I/PackageManager(  742): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,I/PackageManager(  742):   Action: "android.intent.action.SENDTO"
I/PackageManager(  742):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  742):   Scheme: "smsto"
I/PackageManager(  742): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,W/ActivityManager(  742): Permission Denial: getCurrentUser() from pid=3563, uid=10163 requires android.permission.INTERACT_ACROSS_USERS
,I/PackageManager(  742):   Action: "android.intent.action.SENDTO"
I/PackageManager(  742):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  742):   Scheme: "mms"
I/PackageManager(  742): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,I/PackageManager(  742):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  742):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  742):   Scheme: "mmsto"
I/PackageManager(  742): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,W/Resources(  742): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  742): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/Launcher.HomeView( 1259): onStop
,D/Launcher.Model( 1259): reloadBadges entered.
,W/Resources(  742): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  742): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  742): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/ContextImpl(  742): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,W/Resources(  742): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  742): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  742): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  742): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,W/Resources(  742): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,E/SQLiteDatabase( 3563): Failed to open database '/data/data/tv.peel.smartremote/databases/peel'.
E/SQLiteDatabase( 3563): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 3563): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 3563): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteDatabase( 3563): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteDatabase( 3563): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 3563): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 3563): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 3563): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteDatabase( 3563): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteDatabase( 3563): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteDatabase( 3563): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteDatabase( 3563): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 3563): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 3563): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 3563): 	at com.peel.c.s.a(Unknown Source)
E/SQLiteDatabase( 3563): 	at com.peel.data.v.a(Unknown Source)
E/SQLiteDatabase( 3563): 	at com.peel.control.ba.run(Unknown Source)
E/SQLiteDatabase( 3563): 	at com.peel.util.l.run(Unknown Source)
E/SQLiteDatabase( 3563): 	at android.os.Handler.handleCallback(Handler.java:733)
E/SQLiteDatabase( 3563): 	at android.os.Handler.dispatchMessage(Handler.java:95)
E/SQLiteDatabase( 3563): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteDatabase( 3563): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,W/Resources(  742): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  742): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
D/NotiRemoteService( 3563): action com.peel.widget.notification.SETUP_SERVICE_CONNECTION
,D/NotiRemoteService( 3563): connectToPeelService 0
,W/ContextImpl( 3563): Implicit intents with startService are not safe: Intent { act=tv.peel.samsung.widget.service.IPeelService } android.content.ContextWrapper.bindService:529 tv.peel.samsung.widget.a.c.<init>:-1 tv.peel.samsung.widget.NotiRemoteService.a:-1 
,W/Resources(  742): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  742): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  742): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,I/SELinux ( 3586): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 3586):  
I/CrashAnrDetector(  742): onPackageRemoved : com.example.hello
D/NotiRemoteService( 3563): onServiceOn() mServiceState = 1
D/NotiRemoteService( 3563): Send action to self com.peel.widget.notification.SERVICE_BINDED
D/NotiRemoteService( 3563): action com.peel.widget.notification.SERVICE_BINDED
D/NotiRemoteService( 3563): feature is Off. Stop service
,D/NotiRemoteService( 3563): Send action to self com.peel.widget.notification.STOP_PROCESS
,D/UsbSettingsManager(  742): clearDefaults: com.example.hello
D/NotiRemoteService( 3563): action com.peel.widget.notification.STOP_PROCESS
D/NotiRemoteService( 3563): onDestroy()
D/NotiRemoteService( 3563): mOrientationChangeReceier was not registered
,W/AtomicFile(  742): Couldn't rename file /data/system/users/0/appwidgets.xml to backup file /data/system/users/0/appwidgets.xml.bak
W/AppWidgetServiceImpl(  742): Failed open state file for write: java.io.IOException: Couldn't create directory /data/system/users/0/appwidgets.xml
,I/SELinux ( 3586): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 3586):  
I/SELinux ( 3586):  
,I/SELinux ( 3586): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 3586): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 3586): >>>>> Normal User
,E/dalvikvm( 3586): >>>>> org.simalliance.openmobileapi.service [ userId:0 | appId:1101 ]
,E/SELinux ( 3586): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/InputReader(  742): Processing first event
,D/TimaKeyStoreProvider( 3586): in addTimaSignatureService
,D/TimaKeyStoreProvider( 3586): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 3586): Added TimaKesytore provider
,I/EventHub(  742): Removing device sec_touchscreen due to epoll hang-up event.
,I/EventHub(  742): Removed device: path=/dev/input/event1 name=sec_touchscreen id=6 fd=216 classes=0x94
,I/InputReader(  742): Device removed: id=6, name='sec_touchscreen', sources=0x80001002
,D/InputReader(  742): Could not retrieve current multitouch slot index.  status=-1
,D/InputReader(  742): MultiTouchMotionAccumulator: initial slot number is -1
,I/EventHub(  742): Removing device '/dev/input/event1' due to inotify event
I/ActivityManager(  742): Config changes=8 {0 1.0 ?mcc?mnc en_US ldltr sw360dp w360dp h615dp 320dpi nrml long port -touch -keyb/v/h -nav/h s.5}
,D/InputDispatcher(  742): setInputDispatchMode: enabled=0, frozen=1
,I/SurfaceFlinger(  248): id=18 createSurf (720x1280),2 flag=404, TcreenshotS
,D/PermissionCache(  248): checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (198 us)
,D/Mms/MmsApp( 1669): [start]    onConfigurationChanged(),newConfig={0 1.0 ?mcc?mnc en_US ldltr sw360dp w360dp h615dp 320dpi nrml long port -touch -keyb/v/h -nav/h s.5}
,D/Mms/MmsApp( 1669): [end]    onConfigurationChanged(),newConfig={0 1.0 ?mcc?mnc en_US ldltr sw360dp w360dp h615dp 320dpi nrml long port -touch -keyb/v/h -nav/h s.5}
D/MenuAppsGridFragment( 1259): onDestroyView
,W/Launcher.MenuAppsGrid( 1259): Trying to exit a state that hasn't been entered
,D/PhoneStatusBar( 1066): mSettingsPanelGravity = 55
,D/KeyguardUpdateMonitor( 1066): sendKeyguardVisibilityChanged(true)
,I/SurfaceFlinger(  248): id=17 Removed CatteryCove (8/13)
,I/SurfaceFlinger(  248): id=17 Removed CatteryCove (-2/13)
,E/Tethering(  742): No numeric data
D/PhoneStatusBarView( 1066): marqueeStatusBar:122, mClearCover:0
E/SmartFaceService(  742): onReceive: android.intent.action.CONFIGURATION_CHANGED
E/SmartFaceService(  742): mFolderCoverOpened: (true, true) -> true
,D/KeyguardUpdateMonitor( 1066): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1066): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1066): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1066): handleKeyguardVisibilityChanged(1)
,D/KeyguardHostView( 1066): onSaveInstanceState, tstate=1
,D/KeyguardUpdateMonitor( 1066): sendKeyguardVisibilityChanged(true)
,D/KeyguardGuestSelectorView( 1066): onDetachedFromWindow()
V/KeyguardUpdateMonitor( 1066): *** unregister callback for com.android.keyguard.CarrierText$1@42578d48
V/KeyguardUpdateMonitor( 1066): *** unregister callback for com.android.keyguard.MSimCarrierText$1@42578db0
V/KeyguardUpdateMonitor( 1066): *** unregister callback for com.android.keyguard.CarrierText$1@42315158
,V/KeyguardUpdateMonitor( 1066): *** unregister callback for com.android.keyguard.EmergencyButton$1@425149d0
,V/KeyguardUpdateMonitor( 1066): *** unregister callback for com.android.keyguard.sec.KeyguardSecurityViewOverlay$1@425f75b0
,D/STATUSBAR-IconMerger( 1066): checkOverflow(384), More:false, Req:false Child:1
V/KeyguardUpdateMonitor( 1066): *** unregister callback for com.android.keyguard.KeyguardHostView$2@42a339a0
,W/ApplicationsProvider( 1396): Could not fetch usage stats
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

```
